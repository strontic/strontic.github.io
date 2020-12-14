---
title: WerFault.exe | Windows Problem Reporting
excerpt: What is WerFault.exe?
---

# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `7DEF45F3DC7946073D1128FE2D061511`
SHA1 | `7C6560566535E966989F80E45FC3FEF426B0B48A`
SHA256 | `F69FF67FD26F7659D6D92C1A6D060D9BC6915E4FE048671C46BB42E57CC64518`
SHA384 | `8FEC5CDBE087C1939F17B5846419AD0EC9BF4DA271C8D38012A1BA59CEA41981FB8183404DF03547AFA1AD0D983E6C53`
SHA512 | `4E6A6F6929F8E4CE868CEA6E1A466053FB3961BE50AC74E9685559F4E3A97E087F1EBEE0D98CAFBB717EB0DBF83B1A504FB7846580FE4D66900130BB71D36678`
SSDEEP | `12288:809l9MkWWUV8mKTPKbO1CRIOzvlPzc2HywP:8K6HPV8muXOzvlPzcyhP`
IMP | `A8411DCFB6906C782549D77E5571DC7E`
PESHA1 | `0C9932141E14AC6821707902ED7404DA6D73C3B9`
PE256 | `0D468C9DD7B8C8F65CCE9177A89FBCD674CE6175A0DE2085B707A21A6D794F56`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CRYPTSP.dll |
C:\Windows\system32\dbgcore.DLL |
C:\Windows\system32\dbghelp.dll |
C:\Windows\system32\faultrep.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\SYSTEM32\powrprof.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wer.dll |
C:\Windows\system32\WerFault.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/f69ff67fd26f7659d6d92c1a6d060d9bc6915e4fe048671c46bb42e57cc64518/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WerFault.exe](WerFault.exe-58A5ED5D96E2C671CFC69808E1F7B4FA.md) | 90

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


