---
title: sdiagnhost.exe | Scripted Diagnostics Native Host
excerpt: What is sdiagnhost.exe?
---

# sdiagnhost.exe 

* File Path: `C:\Windows\SysWOW64\sdiagnhost.exe`
* Description: Scripted Diagnostics Native Host

## Hashes

Type | Hash
-- | --
MD5 | `48582EF64F96E054C0CDCF3055258101`
SHA1 | `F60F1B93B7172336137CE353E0DB018A42996B80`
SHA256 | `B2ADF4CB63C8B1B2FF014BD328DEAC96354C6F834FAF0660EFD8F7E89F1B2399`
SHA384 | `D4EA6A0AE2C8CDD09580F7E40B99213F2C78B28A5ED2468E7C0075CCFD2AF38E98E2B4B14AF9EBE45D2B7AC307772F12`
SHA512 | `E8AF437B086FF1FE00AA3C372EAEEA00CEEF754A5CC713DD150CDB205DC36EE394FD932321128F4489C60947FBDCC9436669AC0AD0F1A2E8D554113B605D0C1E`
SSDEEP | `384:QHm8MXAvaaGVWyxfAzfVRmffQ7MPrOrye7mEZxaLelgWG7DWz:F1VnILVRmg7f7mmaLeC2`
IMP | `1AC4615E680B9BC131EC1F2ADCF60B35`
PESHA1 | `43F4CDC04527CAA55FCC340F95D7BFB9A1269BF0`
PE256 | `8638CC4929363E9FFC12D92BE0FEAD6E9E6C7900D65FDBB5454EE3C1B86FFA86`

## Runtime Data

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\sdiagnhost.exe.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSECB58 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sdiagnhost.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sdiagnhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/b2adf4cb63c8b1b2ff014bd328deac96354c6f834faf0660efd8f7e89f1b2399/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-258F58247AACD6568910D85E33A07886.md) | 50
[C:\Windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-43353191117C9236DDCCE362A8E74BA7.md) | 52
[C:\windows\SysWOW64\sdiagnhost.exe](sdiagnhost.exe-BD954F1A95B1C1B0D68AC4AF5E427807.md) | 35

## Possible Misuse

*The following table contains possible examples of `sdiagnhost.exe` being misused. While `sdiagnhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_in_memory_powershell.yml) | `- '\WINDOWS\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_in_memory_assembly_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_in_memory_assembly_execution.yml) | `- '\Windows\System32\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_csc_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_csc_folder.yml) | `- '\sdiagnhost.exe'  # https://twitter.com/gN3mes1s/status/1206874118282448897`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\sdiagnhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


