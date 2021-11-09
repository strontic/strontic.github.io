---
title: rasautou.exe | Remote Access Dialer
excerpt: What is rasautou.exe?
---

# rasautou.exe 

* File Path: `C:\WINDOWS\system32\rasautou.exe`
* Description: Remote Access Dialer

## Hashes

Type | Hash
-- | --
MD5 | `5DD32A591FA034555E7BB911C6DCCA25`
SHA1 | `3DBEA5BA8671DB221D6959CB789A8F607DA78E08`
SHA256 | `7DC7A64168F741932A45FAD98009CEA05A4B26D5D2C92165D78A372C7E8713AB`
SHA384 | `C96699C4A7D54C6C38656BF3260CCD39371E321F590C23374BEF590261D89AB82286A52936D9DB6C9FD26BBF0FF88013`
SHA512 | `989D8857AA73A284904E6A8DEEDAE6DDA1C53FE1AC95533659DCDCA672A0281CC13BEE5A347CCED5F239BE3024910A0E94DEAE41399890C94079ED8CB7D67368`
SSDEEP | `384:zoolboKIvu8ZytlbLXLVL47YXLXeWbIzbEWIBW:zoowW8Z0xXLVhPMb2`
IMP | `69DC1709B7740448A0DC0AD149C69D48`
PESHA1 | `68258485666B8C2E647512187FE10F44CD191113`
PE256 | `68EEEE9DF9D9EE0B3A16D5F1955DEBD02E291F39A0B3F727B12A5DB9DD1A0D91`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rasautou [-f phonebook] [-a address] [-e entry] [-s]

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\rasautou.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasdlui.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/7dc7a64168f741932a45fad98009cea05a4b26d5d2c92165d78a372c7e8713ab/detection


## Possible Misuse

*The following table contains possible examples of `rasautou.exe` being misused. While `rasautou.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `title: DLL Execution via Rasautou.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `description: Detects using Rasautou.exe for loading arbitrary .DLL specified in -d option and executes the export specified in -p. `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `- https://lolbas-project.github.io/lolbas/Binaries/Rasautou/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rasautou_dll_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rasautou_dll_execution.yml) | `Image\|endswith: '\rasautou.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `Name: Rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Command: rasautou -d powershell.dll -p powershell -a a -e e`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- Path: C:\Windows\System32\rasautou.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rasautou.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rasautou.yml) | `- IOC: rasautou.exe command line containing -d and -p`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


