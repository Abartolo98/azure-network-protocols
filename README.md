<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/sxKiLlg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Back in wireshark, i filtered only DNS traffic Only as shown from the picture above. From my windows 10 virtual machine command line, i typed in Nslookup to see what google.com and Disney.com Ip adresses are and observing the DNS traffic shown in WireShark.
</p>
<br />

<p>
<img src="https://i.imgur.com/ROCTaCt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Observing ICMP traffic, Ive retrieved the private Ip address from Ubuntu Virtual Machine and attempted pinging it from windows Virtual Machine as shown from the image above. 
</p>
<br />

<p>
<img src="https://i.imgur.com/uOML5z8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
SSH traffic Filtered, What i did is SSH into my Ubuntu Virtual Machine via its private ip Address, once i completed my task successfully, i observed the traffic spam in wireshark from my windows 10 Virtual machine, after all of that i logged myself out of ssh.
</p>
<br />
