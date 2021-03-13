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
MD5 | `58A5ED5D96E2C671CFC69808E1F7B4FA`
SHA1 | `B647E85161505E59B0BE3659A6DA4FED9F7FDED6`
SHA256 | `5E6540869A48565787573F9E6ED168D3074ADA48ED1B732C1615C980AF711F34`
SHA384 | `3E98BB8AFBCA22B9D9FDF63BCA64861DD319DA9C36F72A364DBDFCA55C8A5E047FC3499D06D32A9AAF21CE8C14B7DDEE`
SHA512 | `B470B0F3449BB304BAD04A88C78EB91B5023C246088B5830B013D861C0FF932EDAE57CE1976D61676FE91DD90A058CDB3ED048C6EFFF09964D6ED609F1E057A1`
SSDEEP | `12288:J09H9MkWWUV8mKTPKbO1CR/OzvlPzc2Hywa:J06HPV8musOzvlPzcyha`
IMP | `A8411DCFB6906C782549D77E5571DC7E`
PESHA1 | `DC6D34CBE5268633BDE83150D9FA78308380297F`
PE256 | `9FFD4126868D24A6F4545E71AF84AB38AF392541A3AE8A67F20953F6A598906E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcrypt.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CRYPTSP.dll |
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
* VirusTotal Link: https://www.virustotal.com/gui/file/5e6540869a48565787573f9e6ed168d3074ada48ed1b732c1615c980af711f34/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\WerFault.exe](WerFault.exe-7DEF45F3DC7946073D1128FE2D061511.md) | 90

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- '\System32\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `Image\|endswith: '\werfault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_wmiprvse_spawning_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_wmiprvse_spawning_process.yml) | `- '\WerFault.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


