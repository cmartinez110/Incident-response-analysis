<h1>Incident Response Analysis</h1>


<h2>Description</h2> The follow is the scenario which I referenced for the drafting of an incident response anlysis report:

"Recently, your organization faced a DDoS attack that disrupted the internal network for two hours.

During the attack, network services halted due to a flood of ICMP packets, affecting internal network traffic. The incident management team responded by blocking ICMP packets, taking non-critical services offline, and restoring critical ones.

Further investigation revealed a malicious actor initiated the attack by flooding ICMP pings through an unconfigured firewall, causing a DDoS attack.

To address the issue, the network security team implemented:

A new firewall rule to limit incoming ICMP packet rates.
Source IP address verification on the firewall to detect spoofed IP addresses.
Network monitoring software to identify unusual traffic patterns.
An IDS/IPS system to filter suspicious ICMP traffic."
<br />


<h2>Languages and Utilities Used</h2>

- <b>Microsoft Word</b> 


<h2>Project walk-through:</h2>

<p align="center">
Using the provided scenario, I was able to document an incident response report, to serve as documentation and serve as a reference for crafting a playbook, to reduce response time to this type of attack: <br/>
<img src="https://i.imgur.com/Z7znsSe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
