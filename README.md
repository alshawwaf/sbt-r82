## Check Point Software Blade Demo

```txt

This Demo Environment is aimed to help demo the Check Point Software Blades. 
While this training was designed on Check POint R82, the Labs and demo should work
with other Check Point versions. 
Included blades include:
```
- Application Control and URL filtering
- HTTPS INspection
- Idenitty Awareness
- Inspection Settings
- IPS
- Anti-Virus
- Anti-Bot & DNS Security
- Threat Emulation
- Threat Extraction (under Development)
- Mail Transfer Agent (Under Development)

> **NOTE**
>
> To request more content, contact your regional architect.

### Lab Environemnt Access


> IMPORTANT
>
>If you are a Check Point Employee, reach out to your Regional or Solution Architects to access the Demo Environment. For Customers, pleasecontract your SE to get access.



### Demo Envieronment

```txt
The virtual environment is hosted on CLoudShare. it consists of the following nodes:
```
```
- Check Point Management Server
 - R82 SMS
 - IP Address: 10.1.1.100
```
```
- Check Point Gateway
 - R82 GW
 - Interfaces:
  - 10.1.1.111 Main IP Address (Management Network)
  - External: 203.0.113.111
  - Server Network: 10.1.2.111
  - Web Network: 10.1.3.111
  - DMZ Network: 10.1.4.111
```
```
- Windows Client
 - Windows 11
 - Client in the Server Network
 - IP Address: 10.1.1.220
 - Default Gateway: 10.1.1.111
```
```
- Windows Server
 - Windows server 2022
 - Domain COntroller, DNS Server, Mail Server and other services.
 - IP Address: 10.1.2.250
 - Default Gateway: 10.1.2.111
```
```
- Kali Linux
 - Kali Linux Oenetration Testing Environemnt
 - Demo Web Server and Vulnerability Testing Server located on the External Network
 - IP Address: 203.0.113.5
 - Default Gateway: 203.0.113.1 (Lab Default Gateway)
```
```
- Ubuntu CLient (For Future Use)
 - Client in the Web Network
 - IP Address: 10.1.3.60
 - Default Gateway: 10.1.3.111
```
```
- T-Pot Honeypot (For Future Use)
 - Honeypot in the DMZ Network
 - IP Address: 10.1.4.70
 - Default Gateway: 10.1.4.111
```
