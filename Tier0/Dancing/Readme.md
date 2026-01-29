This machine explores vulnerabilities of SMB Port 445


<img width="531" height="228" alt="image" src="https://github.com/user-attachments/assets/d9d19dec-1042-43d3-aab9-3f051168a32c" /></br>

Date: January 26,2026 | Difficulty: Very Easy
Platfrom: Hack The Box

<h2>Executive Summary</h2></br>
In this engagement, I performed a security assessment on a Windows-based target. The primary goal was to identify open services and potential misconfigurations. 
I discovered an <b>unathenticated SMB share (Null Session) </b> which allowed me to browse the file system and retrieve senitive information(flag).

<pre>
<h2>Tools Used</h2>
-------------------------------------------------------------------
Tool           |   Purpose 
-------------------------------------------------------------------
Nmap           |   Network scanning and service detection
-------------------------------------------------------------------
smbclient      |   Interacting with SMB(Server Message Block) shares
-------------------------------------------------------------------
Linux Terminal |   Command-line execution and file management
-------------------------------------------------------------------

</pre>

<h2>Phase 1: Enumeration</h2>
Network Scanning
I initated the reconnaisance with an aggresive Nmap scan to map the atteck surface.</br>
<code> Nmap -sV -sC 10.129.</code>
