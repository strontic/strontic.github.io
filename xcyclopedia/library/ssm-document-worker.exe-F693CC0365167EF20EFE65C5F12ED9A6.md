---
title: ssm-document-worker.exe | 
excerpt: What is ssm-document-worker.exe?
---

# ssm-document-worker.exe 

* File Path: `C:\Program Files\Amazon\SSM\ssm-document-worker.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F693CC0365167EF20EFE65C5F12ED9A6`
SHA1 | `A6D40E0BF4DD6C8B30EA875AEE6434A5EEDC4024`
SHA256 | `8DBB6FA1BEB4F206BD7A888FA684ED658793CE70568879B034F0FD0B24E61C38`
SHA384 | `5372524BB390C861D599D70A78DAD59D025DAEFC64F384AC543CF0DFA589A69DA6149F9A44658D068A2401F3AF822EB8`
SHA512 | `F49A4FB7879D65271E9C35EC599481B3D43AA203C516C4B4971667C4EE2078714C0A300A11F3B913DCF79022480AC5E72FF407225E1DEC6554EE3B2854661645`
SSDEEP | `196608:KMQqcOS+sylVOmRbbH9uaozhvk4aIgBkFFBFAx:vYeHDozhv+IbFm`
IMP | `F0070935B15A909B9DC00BE7997E6112`
PESHA1 | `461B1973E295DADDE21C8221BADD2D8054C12B8B`
PE256 | `8B688AFDF79136CAA3A91CEEDC1FF49B821929399B0D0FF4EC57A79B747BAA4B`

## Runtime Data

### Usage (stdout):
```cmhg
Initializing new seelog logger
New Seelog Logger Creation Complete
2020-10-19 22:59:00 INFO parsing args: [C:\Program Files\Amazon\SSM\ssm-document-worker.exe --help]
2020-10-19 22:59:00 INFO using channelName --help, instanceID: 
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] document: --help worker started
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] channel: --help not found, creating a new file channel...
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:runPowerShellScript
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:updateSsmAgent
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:runDockerAction
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:configurePackage
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:downloadContent
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:runDocument
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:softwareInventory
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:configureDocker
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform independent plugin aws:refreshAssociation
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform dependent plugin aws:psModule
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform dependent plugin aws:applications
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform dependent plugin aws:domainJoin
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] Successfully loaded platform dependent plugin aws:updateAgent
2020-10-19 22:59:00 INFO [ssm-document-worker] [--help] inter process communication started
2020-10-19 22:59:00 WARN [ssm-document-worker] [--help] IPC file not readable: tmp

```

### Usage (stderr):
```cmhg
2020/10/19 22:58:35 Failed to load instance info from vault. RegistrationKey does not exist.

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
C:\Program Files\Amazon\SSM\ssm-document-worker.exe |
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





MIT License. Copyright (c) 2020-2021 Strontic.


