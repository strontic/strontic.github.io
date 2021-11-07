---
title: PkgMgr.exe | Windows Package Manager
excerpt: What is PkgMgr.exe?
---

# PkgMgr.exe 

* File Path: `C:\Windows\system32\PkgMgr.exe`
* Description: Windows Package Manager

## Screenshot

![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-1.png)
![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `DDE0B63F2E276B969C9C1E6983990CB2`
SHA1 | `6D3027D9187F38F4B10047A6E9194FC2B409B08C`
SHA256 | `5BED2AA29ECB2AEF1A41E8B33A0CEFD32DDEFBFA1F7767430A311C064CF13D67`
SHA384 | `C16C88BE49B555A2FCC4D6AE507D1B1B0E6DD74CD0237EF67725232BD5441D89D185F6CAACBE70BCA3F71AFE5FBC540D`
SHA512 | `33D2B7A8918EF14996CFB21BDFB8C6DA5BDA937FACB9B7911FCA0D40D4D7F2696FDF65C3F30D45E3186C470CF05D92F33E8E3DBA1C0E7579780EB29E479655BF`
SSDEEP | `3072:JdN18XlC0HmKIbTENXK6JRAqs4xjw8m1IsF/Xq:fX89HmtbTMHxM8cT/X`
IMP | `BEE03492F0B5EDD4B94BB7DD6E56B8A1`
PESHA1 | `4BDF4E683B3E2ECCD0B98802CAC9F07148A3B867`
PE256 | `3623BDA85D57AAD0EAF2F4729D0849F7A236D6029C3A72E98C0DA70BBC4DD314`

## Runtime Data

### Window Title:
Windows Package Manager

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme2131664586 | Section
\Windows\Theme966197582 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\PkgMgr.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PkgMgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5bed2aa29ecb2aef1a41e8b33a0cefd32ddefbfa1f7767430a311c064cf13d67/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ocsetapi.dll](ocsetapi.dll-23BC4F98A5F7B0810CA560BF3DF76EF7.md) | 47
[C:\WINDOWS\system32\PkgMgr.exe](PkgMgr.exe-16C0DDFCE82A53516E634F691689EBB6.md) | 50
[C:\windows\system32\PkgMgr.exe](PkgMgr.exe-B212B2FE6910AF8B2068F2FF2242204F.md) | 41
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10.md) | 46
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 43

## Possible Misuse

*The following table contains possible examples of `PkgMgr.exe` being misused. While `PkgMgr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_uac_bypass_msconfig_gui.yml) | `TargetFilename\|endswith: '\AppData\Local\Temp\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_msconfig_gui.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_msconfig_gui.yml) | `ParentImage\|endswith: '\AppData\Local\Temp\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `title: UAC Bypass Using PkgMgr and DISM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `description: Detects the pattern of UAC Bypass using pkgmgr.exe and dism.exe (UACMe 23)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_pkgmgr_dism.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_pkgmgr_dism.yml) | `ParentImage\|endswith: '\pkgmgr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Target:	\system32\pkgmgr.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


