---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
excerpt: What is sdiagnhost.exe?
---

# sdiagnhost.exe 

* File Path: `C:\Windows\system32\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host

## Hashes

Type | Hash
-- | --
MD5 | `9BB47FC39CB24A16A0AB0302960645BA`
SHA1 | `8963ED884F78D263A039A9A68719840412ED30AD`
SHA256 | `50A816FE57195376AD30AEEC2EA7968936A706508E26299302F30366CC7FF3A4`
SHA384 | `3D48D1810E0ADF70CE8DEC34A387E63A1F3AB8C83822A989D7A4F94B374A4CCFB67814537087802392B08DA048689FBE`
SHA512 | `BC4EBE417272BFDAAF85D073C7D598C8B7DB74CF26FC220AE1AE247DF08F6D30D804D16BDE4AE12D2CDA1039F3BABF877EEB7469C6DD29CE3CC77B0382BB097B`
SSDEEP | `384:9NaPLsFWEjuhHKkTy8YBFMHgrQMylq1MIHGcMXgva/HRlsvfyxKil8WG7DW:bsL0W7gkzy/Wd/HPsnaKim`
IMP | `88C840A970A1633DCA61E1CD2D926E21`
PESHA1 | `B0492CFE4BFE941D05A26A6C4C09E67102C3CC54`
PE256 | `FED938CCB061C0319F45AB611B8362AD79927BDCDB49E97188754C7FFA1F0E58`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\sdiagnhost.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSECDB4 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\sdiagnhost.exe |
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

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/50a816fe57195376ad30aeec2ea7968936a706508e26299302f30366cc7ff3a4/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\sdiagnhost.exe](sdiagnhost.exe-4946EEFDBC08E0BAD98033137502FAA6.md) | 30
[C:\WINDOWS\system32\sdiagnhost.exe](sdiagnhost.exe-6458634E67F8AE415A0A871953C04F06.md) | 74
[C:\Windows\system32\sdiagnhost.exe](sdiagnhost.exe-6A21B1893DDE94CB87BA56111375888A.md) | 36

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


