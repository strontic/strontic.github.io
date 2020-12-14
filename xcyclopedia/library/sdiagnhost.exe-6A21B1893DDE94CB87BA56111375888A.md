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
MD5 | `6A21B1893DDE94CB87BA56111375888A`
SHA1 | `540745F1CE67423A156069218680B9DA873B4778`
SHA256 | `761815301A00D0B3A7BB4959A5004B623C55009CE701C6E867C96F468DC1323A`
SHA384 | `4A7C83879CB0A023C98E7908A706B88D4B44C8CA3253884A0A9E030CD5CFEDFA821DF4D2A9A4FB4B79AC2AEFCE08B35C`
SHA512 | `AB4261F78EABC4EFD9ECA0240C147F69A17DBFFAE0486420AA2396A1C1260F82889D060FC4D3D4959AD84C23E65BD1C0AFA8F3328B4497B14391439ECF5CAC08`
SSDEEP | `384:bJwNWEgA6slYA8AGoZesJ1MYEFu8BNtbFTpUHGcMXgvaNS/uoJwJsL4BxKilsWh2:dwNW764o/+b7rHNS/uLs8KiR`
IMP | `88C840A970A1633DCA61E1CD2D926E21`
PESHA1 | `593CC73AEA0ED6AAD288D92C3B6A63BE8A628B19`
PE256 | `842636E8014B8043A4FF5BBACB6EB14E142D491AC7B7599B6B6F961AF3B142CD`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\sdiagnhost.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/761815301a00d0b3a7bb4959a5004b623c55009ce701c6e867c96f468dc1323a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\sdiagnhost.exe](sdiagnhost.exe-4946EEFDBC08E0BAD98033137502FAA6.md) | 22
[C:\WINDOWS\system32\sdiagnhost.exe](sdiagnhost.exe-6458634E67F8AE415A0A871953C04F06.md) | 35
[C:\Windows\system32\sdiagnhost.exe](sdiagnhost.exe-9BB47FC39CB24A16A0AB0302960645BA.md) | 36

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '*\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


