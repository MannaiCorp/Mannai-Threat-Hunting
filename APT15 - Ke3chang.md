# Associated Group Descriptions
## Techniques Used
| Domain | ID | Name  | Use |
|:------:|:--:|:-----:|:---:|
|Enterprise|T1087,.001|Account Discovery: Local Account|Ke3chang performs account discovery using commands such as net localgroup administrators and net group "REDACTED" /domain on specific permissions groups.|
|Enterprise|T1087,.002|Account Discovery: Domain Account|Ke3chang performs account discovery using commands such as net localgroup administrators and net group "REDACTED" /domain on specific permissions groups.|
Enterprise|T1071,.001|Application Layer Protocol: Web Protocols|Ke3chang malware including RoyalCli and BS2005 have communicated over HTTP with the C2 server through Internet Explorer (IE) by using the COM interface IWebBrowser2.|
Enterprise|T1071,.004|Application Layer Protocol:DNS|Ke3chang malware RoyalDNS has used DNS for C2.|
|Enterprise|T1560|Archive Collected Data|The Ke3chang group has been known to compress data before exfiltration.|
|Enterprise|T1560,.001|Archive via Utility|Ke3chang is known to use 7Zip and RAR with passwords to encrypt data prior to exfiltration.|
|Enterprise|T1119|Automated Collection|Ke3chang has performed frequent and scheduled data collection from victim networks.|
|Enterprise|T1020|Automated Exfiltration|Ke3chang has performed frequent and scheduled data exfiltration from compromised networks.|
|Enterprise|T1547,.001|Boot or Logon Autostart Execution: Registry Run Keys / Startup Folder|Several Ke3chang backdoors achieved persistence by adding a Run key.|
|Enterprise|T1059|Command and Scripting Interpreter|Malware used by Ke3chang can run commands on the command-line interface.|
|Enterprise|T1059,.003|Windows Command Shell|Ke3chang has used batch scripts in its malware to install persistence mechanisms.|
|Enterprise|T1543,.003|Create or Modify System Process: Windows Service|Ke3chang backdoor RoyalDNS established persistence through adding a service called Nwsapagent.|
|Enterprise|T1213,.002|Data from Information Repositories: Sharepoint|Ke3chang used a SharePoint enumeration and data dumping tool known as spwebmember.|
|Enterprise|T1005|Data from Local System|Ke3chang gathered information and files from local directories for exfiltration.|
|Enterprise|T1140|Deobfuscate/Decode Files or Information|Ke3chang has deobfuscated Base64-encoded shellcode strings prior to loading them.|
|Enterprise|T1587,.001|Develop Capabilities: Malware|Ke3chang has developed custom malware that allowed them to maintain persistence on victim networks.|
|Enterprise|T1114,.002|Email Collection: Remote Email Collection|Ke3chang has used compromised credentials and a .NET tool to dump data from Microsoft Exchange mailboxes.|
|Enterprise	|T1041|Exfiltration Over C2 Channel|Ke3chang transferred compressed and encrypted RAR files containing exfiltration through the established backdoor command and control channel during operations.|
|Enterprise	|T1190|Exploit Public-Facing Application|Ke3chang has compromised networks by exploiting Internet-facing applications, including vulnerable Microsoft Exchange and SharePoint servers.|
|Enterprise|T1133|External Remote Services|Ke3chang has gained access through VPNs including with compromised accounts and stolen VPN certificates.|
|Enterprise|T1083|File and Directory Discovery|Ke3chang uses command-line interaction to search files and directories.|
|Enterprise|T1105|Ingress Tool Transfer|Ke3chang has used tools to download files to compromised machines.|
|Enterprise|T1056,.001|Input Capture: Keylogging|Ke3chang has used keyloggers.[2][4]
|Enterprise|T1036,.002|Masquerading: Right-to-Left Override|Ke3chang has used the right-to-left override character in spearphishing attachment names to trick targets into executing .scr and .exe files.|
|Enterprise|T1036,.005|Masquerading: Match Legitimate Name or Location|Ke3chang has dropped their malware into legitimate installed software paths including: C:\ProgramFiles\Realtek\Audio\HDA\AERTSr.exe, C:\Program Files (x86)\Foxit Software\Foxit Reader\FoxitRdr64.exe, C:\Program Files (x86)\Adobe\Flash Player\AddIns\airappinstaller\airappinstall.exe, and C:\Program Files (x86)\Adobe\Acrobat Reader DC\Reader\AcroRd64.exe.|
|Enterprise|T1027|Obfuscated Files or Information|Ke3chang has used Base64-encoded shellcode strings.|
|Enterprise|T1588,.002|Obtain Capabilities: Tool|Ke3chang has obtained and used tools such as Mimikatz.|
|Enterprise|T1003,.001|OS Credential Dumping: LSASS Memory|Ke3chang has dumped credentials, including by using Mimikatz.|
|Enterprise|T1003,.002|OS Credential Dumping: Security Account Manager|Ke3chang has dumped credentials, including by using gsecdump.|
|Enterprise|T1003,.003|OS Credential Dumping: NTDS|Ke3chang has used NTDSDump and other password dumping tools to gather credentials.|
|Enterprise|T1003,.004|OS Credential Dumping: LSA Secrets|Ke3chang has dumped credentials, including by using gsecdump.|
|Enterprise|T1069,.002|Permission Groups Discovery: Domain Groups|Ke3chang performs discovery of permission groups net group /domain.|
|Enterprise|T1057|Process Discovery|Ke3chang performs process discovery using tasklist commands.|
|Enterprise|T1021;.002|Remote Services: SMB/Windows Admin Shares|Ke3chang actors have been known to copy files to the network shares of other computers to move laterally.|
|Enterprise|T1018|Remote System Discovery|Ke3chang has used network scanning and enumeration tools, including Ping.|
|Enterprise|T1558,.001|Steal or Forge Kerberos Tickets: Golden Ticket|Ke3chang has used Mimikatz to generate Kerberos golden tickets.|
|Enterprise|T1082|System Information Discovery|Ke3chang performs operating system information discovery using systeminfo and has used implants to identify the system language and computer name.|
|Enterprise|T1614,.001|System Location Discovery: System Language Discovery|Ke3chang has used implants to collect the system language ID of a compromised machine.|
|Enterprise|T1016|System Network Configuration Discovery|Ke3chang has performed local network configuration discovery using ipconfig.|
|Enterprise|T1049|System Network Connections Discovery|Ke3chang performs local network connection discovery using netstat.|
|Enterprise|T1033|System Owner/User Discovery|Ke3chang has used implants capable of collecting the signed-in username.|
|Enterprise|T1007|System Service Discovery|Ke3chang performs service discovery using net start commands.|
|Enterprise|T1569,.002|System Services: Service Execution|Ke3chang has used a tool known as RemoteExec (similar to PsExec) to remotely execute batch scripts and binaries.|
|Enterprise|T1078|Valid Accounts|Ke3chang has used credential dumpers or stealers to obtain legitimate credentials, which they used to gain access to victim accounts.|
|Enterprise|T1078,.004|Cloud Accounts|Ke3chang has used compromised credentials to sign into victims’ Microsoft 365 accounts.|
