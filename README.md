# Home-Lab


## Objective


The objective of the Home Lab Project is to establish a controlled environment for simulating and detecting cyber attacks. The primary focus is to set up virtual machines (such as Kali Linux and Ubuntu) to create an isolated environment where I can practice cybersecurity techniques, conduct experiments, and deepen my understanding of network security, attack patterns, and defensive strategies

### Skills Learned


- Network Security: Understanding and securing network architectures.
- Threat Detection: Identifying and analyzing potential cyber threats.
- Incident Response: Developing procedures to respond to security incidents.
- Digital Forensics: Investigating and analyzing digital evidence.
- Log Analysis: Interpreting log data to uncover suspicious activities.
- Vulnerability Assessment: Identifying and mitigating system vulnerabilities.
- Penetration Testing: Simulating cyberattacks to find security weaknesses.
- Using Security Tools: Proficiency with tools like Wireshark, Metasploit, and Splunk.
- SIEM: Implementing and using Security Information and Event Management systems.
- Documentation: Creating detailed reports and documenting incidents effectively.

### Tools Used


- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps

<p align="center">
Creating Windows VM: <br/>
<br />
<img src="1.creating windows WM .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
2.Installing windows: <br/>
<br />
<img src="2.Installing windows.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
3.dowloading kali linux: <br/>
<br />
<img src="3.dowloading kali linux.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
4.downloading 7 zip: <br/>
<br />
<img src="4.downloading 7 zip.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
5.extracting kali VM using 7-zip: <br/>
<br />
<img src="5.extracting kali VM using 7-zip.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
6.starting Kali VM p: <br/>
<br />
<img src="6.starting Kali VM .png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
7.Both VMs setup: <br/>
<br />
<img src="7.Both VMs setup.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
8.congifuring windows VM network: <br/>
<br />
<img src="8.congifuring windows VM network.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
9.configuring kali linux VM network: <br/>
<br />
<img src="9.configuring kali linux VM network.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
10.staticlly assigning IP Address to windows machine: <br/>
<br />
<img src="10.staticlly assigning IP Address to windows machine.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
11.confirming windows machine IP Addressk: <br/>
<br />
<img src="11.confirming windows machine IP Address.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
12.staticlly assigning IP Address to kali linux machine: <br/>
<br />
<img src="12.staticlly assigning IP Address to kali linux machine.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
13.confirming Kali linux machine IP Address: <br/>
<br />
<img src="13.confirming Kali linux machine IP Address.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
14.pinging kali machine on windows machine to ensure connectivity: <br/>
<br />
<img src="14.pinging kali machine on windows machine to ensure connectivity.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
15.downloading splunk on windows machine: <br/>
<br />
<img src="15.downloading splunk on windows machine.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
16.installing splunk: <br/>
<br />
<img src="16.installing splunk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
17.downloading sysmon on windows VM: <br/>
<br />
<img src="17.downloading sysmon on windows VM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
18.Downloading sysmon config: <br/>
<br />
<img src="18.Downloading sysmon config.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
19.extracting sysmon: <br/>
<br />
<img src="19.extracting sysmon.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
20.running powershell in the same directory as the downloaded location of sysmon: <br/>
<br />
<img src="20.running powershell in the same directory as the downloaded location of sysmon.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
21.confirming if the sysmon config exl is there: <br/>
<br />
<img src="21.confirming if the sysmon config exl is there.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
22.executing sysmon64 on powershell: <br/>
<br />
<img src="22.executing sysmon64 on powershell.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
23.checking if sysmon was previously installed: <br/>
<br />
<img src="23.checking if sysmon was previously installed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
24.installing sysmon with the option of using a config xml: <br/>
<br />
<img src="24.installing sysmon with the option of using a config xml.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />

<p align="center">
25.sysmon user agreement: <br/>
<br />
<img src="25.sysmon user agreement.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<p align="center">
26.checking to see if sysmon was successfully installed: <br/>
<br />
<img src="26.checking to see if sysmon was successfully installed.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />






