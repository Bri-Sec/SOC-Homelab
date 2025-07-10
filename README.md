# Basic SOC Home Lab

This was the first project I did which wasn't part of my curriculum, in which I set up a basic home lab including a Windows and Kali VM.

## Objective

The Detection Lab project involved building a controlled home lab environment using virtualization to safely test cybersecurity tools, techniques, and malware. The lab setup included installing and configuring virtual machines with Windows 10 and Kali Linux to simulate attacker and defender roles. This approach enabled hands-on learning with real telemetry generation, log ingestion, and attack simulation within a sandboxed virtual environment, facilitating a deeper understanding of network security, malware behavior, and detection methodologies without risking production systems.

### Skills Learned

- Setting up and configuring virtualized sandbox environments using VirtualBox for cybersecurity testing.
- Creating and managing snapshots to preserve and restore system states before and after testing.
- Installing and configuring Windows and Kali Linux virtual machines for attacker and defender roles.
- Generating realistic telemetry with Sysmon and Splunk to analyze network and host behavior.
- Safely executing and monitoring malware and exploits within a controlled environment.
- Understanding the importance of resource allocation and system specifications in virtualization.
- Developing detection engineering skills by analyzing telemetry from simulated attacks.
- Practicing offensive techniques such as running web scanners and Metasploit modules to create attack signatures.

### Tools Used

<img src="https://img.shields.io/badge/-VirtualBox-183A61?&style=for-the-badge&logo=VirtualBox&logoColor=white" />   — for creating and managing virtual machines in a sandboxed environment. <br>
<img src="https://img.shields.io/badge/-Windows_10-0078D6?&style=for-the-badge&logo=Windows&logoColor=white" />   — installed as the primary victim/defender machine. <br>
<img src="https://img.shields.io/badge/-Kali_Linux-557C94?&style=for-the-badge&logo=KaliLinux&logoColor=white" />  — used as the attacker machine with pre-built virtual machine images. <br>
<img src="https://img.shields.io/badge/-Sysmon-000000?&style=for-the-badge&logo=windows&logoColor=white" />  — for generating detailed Windows system telemetry. <br>
<img src="https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white" /> — for ingesting, visualizing, and analyzing security logs. <br>

## Steps

![image](https://github.com/user-attachments/assets/6dea08dc-95b0-4643-971b-f1afce0ce48c) <br>
*Ref 1: Splunk installed on Windows VM*

![image](https://github.com/user-attachments/assets/097fa447-1a22-46c2-a6ed-a9de7b71fa86) <br>
*Ref 2: Create Reverse tcp malware on Kali VM using Msfvenom*

![image](https://github.com/user-attachments/assets/616090ad-586e-4cb6-ab75-c71ab0a6088d) <br>
*Ref 3: Process with the same name as suspicious file is running after opening the file*

![image](https://github.com/user-attachments/assets/5676a4d2-0dae-431f-aeda-f5f31fa45853) <br>
*Ref 4: Connection to the IP-address with same PID is also found using netstat*

![image](https://github.com/user-attachments/assets/66559d57-a78d-4900-aec4-5d8d90eff3bb) <br>
*Ref 5: Access and enumeration on Kali machine*

![image](https://github.com/user-attachments/assets/ab4d9439-255c-4da0-8028-d74d9ee450a0) <br>
*Ref 6: 7 RDP events logged in splunk*

![image](https://github.com/user-attachments/assets/b2afdc92-afcb-4331-b062-d0c81b60913b) <br>
*Ref 7: Investigating Process Guid of one event shows commands executed*






