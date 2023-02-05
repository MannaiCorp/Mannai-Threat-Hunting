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

|Enterprise|T1105|Ingress Tool Transfer|BackdoorDiplomacy has downloaded additional files and tools onto a compromised host.|

|Enterprise|T1036,.004|Masquerading: Masquerade Task or Service|BackdoorDiplomacy has disguised their backdoor droppers with naming conventions designed to blend into normal operations.|

|Enterprise|T1036,.005|Masquerading: Match Legitimate Name or Location|BackdoorDiplomacy has dropped implants in folders named for legitimate software.|

|Enterprise|T1046|Network Service Discovery|BackdoorDiplomacy has used SMBTouch, a vulnerability scanner, to determine whether a target is vulnerable to EternalBlue malware.|

|Enterprise|T1095|Non-Application Layer Protocol|BackdoorDiplomacy has used EarthWorm for network tunneling with a SOCKS5 server and port transfer functionalities.|

|Enterprise|T1027|Obfuscated Files or Information|BackdoorDiplomacy has obfuscated tools and malware it uses with VMProtect.|

|Enterprise|T1588,.001|Obtain Capabilities: Malware|BackdoorDiplomacy has obtained and used leaked malware, including DoublePulsar, EternalBlue, EternalRocks, and EternalSynergy, in its operations.|

|Enterprise|T1588,.002|Obtain Capabilities: Tool|BackdoorDiplomacy has obtained a variety of open-source reconnaissance and red team tools for discovery and lateral movement.|

|Enterprise|T1120|Peripheral Device Discovery|BackdoorDiplomacy has used an executable to detect removable media, such as USB flash drives.|

|Enterprise|T1055,.001|Process Injection: Dynamic-link Library Injection|BackdoorDiplomacy has dropped legitimate software onto a compromised host and used it to execute malicious DLLs.|

|Enterprise|T1505|.003|Server Software Component: Web Shell|BackdoorDiplomacy has used web shells to establish an initial foothold and for lateral movement within a victim's system.|

|Enterprise|T1049|System Network Connections Discovery|BackdoorDiplomacy has used NetCat and PortQry to enumerate network connections and display the status of related TCP and UDP ports.|
