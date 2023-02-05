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
