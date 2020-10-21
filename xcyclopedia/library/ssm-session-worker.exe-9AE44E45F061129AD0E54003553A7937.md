---
title: ssm-session-worker.exe | 
excerpt: What is ssm-session-worker.exe?
---

# ssm-session-worker.exe 

* File Path: `C:\Program Files\Amazon\SSM\ssm-session-worker.exe`

## Hashes

Type | Hash
-- | --
MD5 | `9AE44E45F061129AD0E54003553A7937`
SHA1 | `180EF7BC5032BE080563E46F45A7A5DE15626AAA`
SHA256 | `5C83F6681AEC35D9272DABD62DDA78AC7E8A46B69FDFF432041B6C31081810C4`
SHA384 | `E6FCE37A707E440F5BC7A8AB715C3EC9FB1F8EA881A7CCCB47A847C1E97F6451FA69ABD787BD0CD37C8EC48D8FE8F093`
SHA512 | `D8579819B3A350A059DD57F1A357E9DDF91FFB6A46A640A8E423D8CE4192817CC690D481FFF7430E2D99497F245571BB4753F28BAC2553A39E8E7218BC8D5D01`
SSDEEP | `196608:k3FEErsmQQMhwP1hlDDbtPBdYoPddAsaUfESaSCX9VY:CfhXlPdOfS2y`
IMP | `F0070935B15A909B9DC00BE7997E6112`
PESHA1 | `D09780A13E65669C13F6D8EE97FABBA113AF6932`
PE256 | `DC7E2DF421CA7EB512C6F81B13AC1BE3F12FB21C7BE8951C6FCE742B95FED226`

## Runtime Data

### Usage (stdout):
```cmhg
Initializing new seelog logger
New Seelog Logger Creation Complete
2020-10-19 23:00:06 INFO [ssm-session-worker] [/?] document: /? worker started
2020-10-19 23:00:06 INFO [ssm-session-worker] [/?] channel: /? not found, creating a new file channel...
2020-10-19 23:00:06 ERROR [ssm-session-worker] [/?] failed to create directory: CreateFile C:\ProgramData\Amazon\SSM\InstanceData/i-0cb123bb7dbf3caae/channels/?: The filename, directory name, or volume label syntax is incorrect.
2020-10-19 23:00:06 ERROR [ssm-session-worker] [/?] failed to create channel: CreateFile C:\ProgramData\Amazon\SSM\InstanceData/i-0cb123bb7dbf3caae/channels/?: The filename, directory name, or volume label syntax is incorrect.
2020-10-19 23:00:06 INFO [ssm-session-worker] [/?] Session worker closed

```

### Usage (stderr):
```cmhg
2020/10/19 23:00:06 Failed to load instance info from vault. RegistrationKey does not exist.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\ProgramData\Amazon\SSM\Logs\amazon-ssm-agent.log | File
(RW-)   C:\Users\user | File
(RWD)   C:\ProgramData\Amazon\SSM\InstanceData\i-0cb123bb7dbf3caae\channels\--help | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\Amazon\SSM\ssm-session-worker.exe |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\SYSTEM32\CRYPTBASE.DLL |
C:\Windows\System32\CRYPTSP.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\mswsock.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\rsaenh.dll |
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

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


