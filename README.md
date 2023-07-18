# Using-the-NIST-Cybersecurity-Framework-to-respond-to-a-network-incident
<h1>Project Description</h1>
I'm a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. The organization recently experienced an attack, which compromised the internal network.
<h1>Project Proccess</h1>
I began the incident analysis by capturing the packets and analysing it.<br>
By doing that I noticed a flood of ICMP pings from different IP addresses into the company’s network through an unconfigured firewall which indicates that the network has experienced a DDOS attack.It comprimesed the network for two hours before resolving the issue<br>
me and my security team ran some procedures which allowed us to resolve the problem.<br>
first of all we implemented a new firewall rule to limit the rate of incoming ICMP packets.Then we configured Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
After that we had to implement network monitoring software to detect abnormal traffic patterns.At the end we implemented an IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics.<br>
After the incident me and my team was asked to construct a report about this incident using  the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).<br>


