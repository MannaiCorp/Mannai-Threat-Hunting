# Associated Group Descriptions
## Techniques Used

| Domain | ID | Name  | Use |
|:------:|:--:|:-----:|:---:|
|Enterprise|T1583,.001|Acquire Infrastructure: Domains|BITTER has registered a variety of domains to host malicious payloads and for C2.|
|Enterprise|T1071,.001|Application Layer Protocol: Web Protocols|BITTER has used HTTP POST requests for C2.|
|Enterprise|T1568|Dynamic Resolution|BITTER has used DDNS for C2 communications.|
|Enterprise|T1573|Encrypted Channel|BITTER has encrypted their C2 communications.|
|Enterprise|T1203|Exploitation for Client Execution|BITTER has exploited Microsoft Office vulnerabilities CVE-2012-0158, CVE-2017-11882, CVE-2018-0798, and CVE-2018-0802.|
|Enterprise|T1068|Exploitation for Privilege Escalation|BITTER has exploited CVE-2021-1732 for privilege escalation.|
|Enterprise|T1105|Ingress Tool Transfer|BITTER has downloaded additional malware and tools onto a compromised host.|
|Enterprise|T1559|.002|Inter-Process Communication: Dynamic Data Exchange|BITTER has executed OLE objects using Microsoft Equation Editor to download and run malicious payloads.|
|Enterprise|T1036,.004|Masquerading: Masquerade Task or Service|BITTER has disguised malware as a Windows Security update service.|
|Enterprise|T1095|Non-Application Layer Protocol|BITTER has used TCP for C2 communications.|
|Enterprise|T1027|Obfuscated Files or Information|BITTER has used a RAR SFX dropper to deliver malware.|
|Enterprise|T1588,.002|Obtain Capabilities: Tool|BITTER has obtained tools such as PuTTY for use in their operations.|
|Enterprise|T1566,.001|Phishing: Spearphishing Attachment|BITTER has sent spearphishing emails with a malicious RTF document or Excel spreadsheet.|
|Enterprise|T1053,.005|Scheduled Task/Job: Scheduled Task|BITTER has used scheduled tasks for persistence and execution.|
|Enterprise|T1608,.001|Stage Capabilities: Upload Malware|BITTER has registered domains to stage payloads.|
|Enterprise|T1204,.002|User Execution: Malicious File|BITTER has attempted to lure victims into opening malicious attachments delivered via spearphishing.|

## Software
| ID | Name | Techniques |
|:------:|:--:|:---:|
|S1013|ZxxZ|Data from Local System, Deobfuscate/Decode Files or Information, Ingress Tool Transfer, Masquerading: Masquerade Task or Service, Native API, Obfuscated Files or Information, Phishing: Spearphishing Attachment, Process Discovery, Query Registry, Scheduled Task/Job: Scheduled Task, Software Discovery: Security Software Discovery, System Information Discovery, System Owner/User Discovery, User Execution: Malicious File|

