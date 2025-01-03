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


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Network Commands</title>
</head>
<body>
    <header>
        <h1>Common Network Commands</h1>
        <p>Below are useful network commands and their descriptions.</p>
    </header>
    <section>
        <h2>Ping Commands</h2>
        <ul>
            <li><b>ping (IP address):</b> Operates at Level 3 of the OSI Model; checks if the Internet is reachable.</li>
            <li><b>ping google.com:</b> Checks connectivity to one of the world's most commonly accessed websites.</li>
        </ul>
    </section>
    <section>
        <h2>IP Configuration Commands</h2>
        <ul>
            <li><b>ipconfig:</b> Displays network settings such as IPv4, MAC address, subnet mask, and default gateway.</li>
            <li><b>ipconfig /all:</b> Provides detailed network configuration information.</li>
            <li><b>ipconfig /release:</b> Releases the current IP configuration.</li>
            <li><b>ipconfig /renew:</b> Renews the IP configuration (used after <code>ipconfig /release</code>).</li>
            <li><b>ipconfig /displaydns:</b> Shows cached DNS records.</li>
            <li><b>ipconfig /flushdns:</b> Clears cached DNS entries.</li>
            <li><b>ipconfig /registerdns:</b> Re-registers the PC with DNS servers (used after flushing DNS).</li>
            <li><b>ipconfig --help:</b> Lists available ipconfig commands.</li>
        </ul>
    </section>
    <section>
        <h2>Other Network Commands</h2>
        <ul>
            <li><b>tracert (IP address):</b> Shows all hops made to reach the destination IP address.</li>
            <li><b>netstat:</b> Displays active connections, including TCP or UDP details.</li>
            <li><b>arp -a:</b> Shows the ARP (Address Resolution Protocol) table.</li>
            <li><b>arp --help:</b> Lists available ARP commands.</li>
            <li><b>arp -d *:</b> Clears the ARP table.</li>
        </ul>
    </section>
</body>
</html>
