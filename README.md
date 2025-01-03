<h1>Network Troubleshooting Commands (for Windows)</h1>
Here is a list of some key network troubleshooting commands for Windows. These will allow you to check connectivity, view network details, trace packet paths, analyze network connections, resolve DNS issues, and access MAC addresses depending on the command used.


		<p></p>Server - physical, virtual and/or in the Azure cloud)</p>
		<p>Hosts Active Directory database</p>
		<p>Responds to authentication requests</p>
		<p>Processes logins and enforces policies</p>
	<h2>Active Directory Database (NTDS.dit)</H2>
		<p>Stores the data for the directory</p>
		<p>Stores log files</p>
		<p>Structure of the database is called a <b>Schema</b></p>




	<h2>“ping (IP address)”</h2>
 		Operates at Level 3 of the OSI Model, can see if we can reach the Internet
	“ping google.com” - see if we get a response from one of world’s most commonly accessed websites
	“ipconfig” - gives us our network settings - IPv4, MAC, subnet mask, default gateway,etc
	“ipconfig /all” - gives even more detailed info
	“ipconfig /release” - 
	“ipconfig /renew” - need to run this command after running “ipconfig /release”
	“ipconfig /displaydns” - gives details on our DNS records
	“ipconfig /flushdns” - clears out our cache of resolved DNSs
	“ipconfig /displaydns” - doesn’t show anything since we just cleared out the cache
	“ipconfig /registerdns” - re registers with our DNS servers; must be run after flush
	“ipconfig - -help” - shows all the different commands we can run
	“tracert (IP address)” - shows all of the hops made to get to destination IP address
	“netstat” - shows the hops but also shows if TCP or UDP
	“arp -a” - shows us the ARP (Address Resolution Protocol) table on our pc
	“arp - -help” - shows different arp commands we can run
	“arp -d * “ - clears out our ARP table
