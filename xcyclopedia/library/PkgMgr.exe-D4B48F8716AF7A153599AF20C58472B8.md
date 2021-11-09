---
title: PkgMgr.exe | Windows Package Manager
excerpt: What is PkgMgr.exe?
---

# PkgMgr.exe 

* File Path: `C:\WINDOWS\system32\PkgMgr.exe`
* Description: Windows Package Manager

## Screenshot

![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-1.png)
![PkgMgr.exe](screenshots/PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `D4B48F8716AF7A153599AF20C58472B8`
SHA1 | `7A0B55D0F1C6E6ACF8F737E92522FC15FF3E5DEC`
SHA256 | `FB865203AC6257ABE20D9BC09321E9106E389742FF9E2CD562A1BAB50D7237BC`
SHA384 | `24CBEB8B0FBA615B086C34C8933464DBC6FB4310824CADDA2DA25D7F56C5B194E1C29D3BAA0C03850C465F06E0296A0C`
SHA512 | `77FC3EA5375CCE031C1B41239AB7CF751D858FB2EEC32C20E97AB6496DCE1DF04A1EC78E64DF7E917D4EB8AE9DE25FA70E69D9A8EA907167105940EC7FD10B76`
SSDEEP | `3072:Ey7p8AAhTpeaJXDmEgpBxNYABoi32QANzIR4eS2ENXK6JTAqs4xjw8m1IMqCg88:ENhTbhmEgpjNvoimbNs7S2GHxM8c7g8`
IMP | `042361D097EA2E8CBEFDFE3B9C8B0FC9`
PESHA1 | `92577B5A4919782ECC153C56B8D2690CE9082E72`
PE256 | `2F14556A880B6873DE9DC01383D4C59EAAEBE59C4E3DF09C3C11B5387279EBD1`

## Runtime Data

### Window Title:
Windows Package Manager

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\KernelBase.dll.mui | File
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\2\Windows\Theme1077709572 | Section
\Windows\Theme3461253685 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\PkgMgr.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PkgMgr.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.120 (WinBuild.160101.0800)
* Product Version: 10.0.22000.120
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/fb865203ac6257abe20d9bc09321e9106e389742ff9e2cd562a1bab50d7237bc/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ocsetapi.dll](ocsetapi.dll-23BC4F98A5F7B0810CA560BF3DF76EF7.md) | 44
[C:\WINDOWS\system32\PkgMgr.exe](PkgMgr.exe-16C0DDFCE82A53516E634F691689EBB6.md) | 44
[C:\windows\system32\PkgMgr.exe](PkgMgr.exe-B212B2FE6910AF8B2068F2FF2242204F.md) | 32
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DC51BE58FEAF1A400DA1BBFC16219C10.md) | 40
[C:\Windows\system32\PkgMgr.exe](PkgMgr.exe-DDE0B63F2E276B969C9C1E6983990CB2.md) | 44
[C:\Windows\system32\wusa.exe](wusa.exe-59701FE9C8BA85BCEB73A9B1B3E8E1C4.md) | 35

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


