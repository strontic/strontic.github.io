---
title: amazon-ssm-agent.exe | 
excerpt: What is amazon-ssm-agent.exe?
---

# amazon-ssm-agent.exe 

* File Path: `C:\Program Files\Amazon\SSM\amazon-ssm-agent.exe`

## Hashes

Type | Hash
-- | --
MD5 | `D99D0B786003034B7255BA854D2750DF`
SHA1 | `63B5A7FD10E3F069E55CDE0589B164C4785D8013`
SHA256 | `E59FC75594AA351583476F38E8C008C2AD2119C229D9C4540EFE17AFAEF7ED34`
SHA384 | `A9FC7C39690F653E4E3609412D8343BD566793268AA788B1D45229B23FC7A36646BE4DA178B1414B80B6E2C7C9AE066F`
SHA512 | `6E0782011AC8A1A75578E43BBEE155F247EC3271386721A2102D0D29E012D9D8AE3CADE0D3F07332AD1C109842F1321AD2A4365632A74E9A8B6648A01A5017CE`
SSDEEP | `196608:rmUGT/XfKfdJUxecpCzwznb1oTo75R/+sHzZtaP6F+M0:2ppCc+sHF6`
IMP | `F0070935B15A909B9DC00BE7997E6112`
PESHA1 | `A1441DF045DBA2462AF9911688498B0D2DB3C2FA`
PE256 | `EF5A2FE4DF5B3AAFF14BB73317EFAE2EAB1D0045A4FFB930BC38DA1ED1A26037`

## Runtime Data

### Usage (stdout):
```cmhg
Initializing new seelog logger
New Seelog Logger Creation Complete
2020-10-19 22:56:49 INFO Windows Only: Job object creation on SSM agent successful
2020-10-19 22:56:49 INFO Getting IE proxy configuration for current user: The operation completed successfully.
2020-10-19 22:56:49 INFO Getting WinHTTP proxy default configuration: The operation completed successfully.
2020-10-19 22:56:49 INFO Proxy environment variables:
2020-10-19 22:56:49 INFO http_proxy: 
2020-10-19 22:56:49 INFO https_proxy: 
2020-10-19 22:56:50 INFO Agent is in hibernate mode. Reducing logging. Logging will be reduced to one log per backoff period
2020-10-19 22:56:49 INFO no_proxy: 
2020-10-19 22:56:50 INFO Entering SSM Agent hibernate - EC2RoleRequestError: no EC2 instance role found
caused by: EC2MetadataError: failed to make EC2Metadata request
	status code: 404, request id: 
caused by: <?xml version="1.0" encoding="iso-8859-1"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
	"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="en" lang="en">
 <head>
  <title>404 - Not Found</title>
 </head>
 <body>
  <h1>404 - Not Found</h1>
 </body>
</html>


```

### Usage (stderr):
```cmhg
2020/10/19 22:56:58 Failed to load instance info from vault. RegistrationKey does not exist.
Usage of C:\Program Files\Amazon\SSM\amazon-ssm-agent.exe:
  -clear
    	
  -code string
    	
  -fingerprint
    	
  -i string
    	instance id
  -id string
    	
  -r string
    	instance region
  -region string
    	
  -register
    	
  -similarityThreshold int
    	 (default 40)
  -y	

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\ProgramData\Amazon\SSM\Logs\amazon-ssm-agent.log | File
(RW-)   C:\Users\user | File
(RW-)   C:\Users\user\{{LOCALAPPDATA}}\Amazon\SSM\Logs\hibernate.log | File
(RWD)   C:\Program Files\Amazon\SSM | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\SSM\amazon-ssm-agent.exe |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\SYSTEM32\CRYPTBASE.DLL |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\SYSTEM32\dhcpcsvc.DLL |
C:\Windows\SYSTEM32\dhcpcsvc6.DLL |
C:\Windows\SYSTEM32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\netapi32.dll |
C:\Windows\System32\NSI.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
C:\Windows\SYSTEM32\SAMCLI.DLL |
C:\Windows\SYSTEM32\SAMLIB.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\winmm.dll |
C:\Windows\SYSTEM32\WINMMBASE.dll |
C:\Windows\System32\ws2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/e59fc75594aa351583476f38e8c008c2ad2119c229d9c4540efe17afaef7ed34/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


