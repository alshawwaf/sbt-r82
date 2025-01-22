## Check Point Software Blade Demo Environment


This Demo Environment is aimed to help demo the Check Point Software Blades. 
While this training was designed on Check Point R82, the Labs and demo should work
with other Check Point versions. 
Included blades:

```
- Application Control and URL filtering
- HTTPS Inspection
- Identity Awareness
- Inspection Settings
- IPS
- Anti-Virus
- Anti-Bot & DNS Security
- Threat Emulation
- Threat Extraction
- Mail Transfer Agent
- Zero-Phishing
```

> **NOTE**
>
> To request more content, contact your regional architect.


### Lab Access

If you are a Check Point Employee, please reach out to your Regional Architec or the Solutions Architect to access the Demo Environment. For Customers, please contact your SE to get access.



### Demo Environment


The virtual environment is hosted on CloudShare. it consists of the following nodes:

```
Check Point Management Server
 - R82 SMS
 - IP Address: 10.1.1.100
```
```
Check Point Gateway
 - R82 GW
 - Interfaces:
  - 10.1.1.111 Main IP Address (Management Network)
  - External: 203.0.113.111
  - Server Network: 10.1.2.111
  - Web Network: 10.1.3.111
  - DMZ Network: 10.1.4.111
```
```
 Windows Client
 - Windows 11
 - Client in the Server Network
 - IP Address: 10.1.1.220
 - Default Gateway: 10.1.1.111
```
```
Windows Server
 - Windows server 2022
 - Domain Controller, DNS Server, Mail Server and other services.
 - IP Address: 10.1.2.250
 - Default Gateway: 10.1.2.111
```
```
Kali Linux
 - Kali Linux Penetration Testing Environemnt
 - Demo Web Server and Vulnerability Testing Server located on the External Network
 - IP Address: 203.0.113.5
 - Default Gateway: 203.0.113.1 (Lab Default Gateway)
```
