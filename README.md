<h1>Network Troubleshooting Commands (for Windows)</h1>
Here is a list of some key network troubleshooting commands for Windows. These will allow you to check connectivity, view network details, trace packet paths, analyze network connections, resolve DNS issues, and access MAC addresses depending on the command used.

	<h2>“ping (IP address)”</h2>
 		<p>Operates at Level 3 of the OSI Model, can see if we can reach the Internet</p>
	<h2>“ping google.com”</h2>
 		<p>see if we get a response from one of world’s most commonly accessed websites</p>
	<h2>“ipconfig”</h2>
 		<p>gives us our network settings - IPv4, MAC, subnet mask, default gateway,etc.</p>
	<h2>“ipconfig /all”</h2>
 		<p>gives even more detailed info</p>
	<h2>“ipconfig /release”</h2> 
	<h2>“ipconfig /renew”</h2>
 		<p>need to run this command after running “ipconfig /release”</p>
	<h2>“ipconfig /displaydns”</h2>
 		<p>gives details on our DNS records</p>
	<h2>“ipconfig /flushdns”</h2> 
 		<p>clears out our cache of resolved DNSs</p>
	<h2>“ipconfig /displaydns”</h2> 
 		<p>doesn’t show anything since we just cleared out the cache</p>
	<h2>“ipconfig /registerdns”</h2> 
 		<p>re registers with our DNS servers; must be run after flush</p>
	<h2>“ipconfig - -help”</h2> 
 		<p>shows all the different commands we can run</p>
	<h2>“tracert (IP address)”</h2> 
 		<p>shows all of the hops made to get to destination IP address</p>
	<h2>“netstat”</h2> 
 		<p>shows the hops but also shows if TCP or UDP</p>
	<h2>“arp -a”</h2> 
 		<p>shows us the ARP (Address Resolution Protocol) table on our pc</p>
	<h2>“arp - -help”</h2> 
 		<p>shows different arp commands we can run</p>
	<h2>“arp -d * “</h2> 
 		<p>clears out our ARP table</p>
