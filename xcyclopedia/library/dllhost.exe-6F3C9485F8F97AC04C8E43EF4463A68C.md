---
title: dllhost.exe | COM Surrogate
excerpt: What is dllhost.exe?
---

# dllhost.exe 

* File Path: `C:\Windows\SysWOW64\dllhost.exe`
* Description: COM Surrogate

## Hashes

Type | Hash
-- | --
MD5 | `6F3C9485F8F97AC04C8E43EF4463A68C`
SHA1 | `497B8CE238DB644B7E1A16B417DBB5BC052A2684`
SHA256 | `3ED69CAAB035258E008EFBCF40DB305891B40BA02CA2737E20DEFA7C2D4AFAF7`
SHA384 | `825CC484BCFF8DA9E29239B5401C828729E1ECB784A1C887FC2A18D7B48B09D9F9F774C397753519396046F4680107CE`
SHA512 | `DBB04F0D2AA4AC2C234B08125564F8F9F790B115E0C5B3F3765ED3C20F3CFD24D6110AF04FEB1837E77DA84524180A85CC9B6802F9ACFBD8809B052221A04EA7`
SSDEEP | `384:bWHTVQyztcEUJnPjz2M2ucqWw5WG+GOxr6wDDBRJcoTCTlJSBA:bqKyxcEUR2rucs5Ar6wD1PFC6G`
IMP | `B6A6C5247EFBD2610E3DEA44649D7041`
PESHA1 | `2B27B79FFA64C9305AD074513EE51AEDA9A9FD23`
PE256 | `7C06EE399035352594D2C16EBEF24098BAB91577A4DE2D38332A49AC52E6AFB5`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\dllhost.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/3ed69caab035258e008efbcf40db305891b40ba02ca2737e20defa7c2d4afaf7/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll](6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll-513E16B14C2E8DE6AEA439153A9733FD.md) | 40
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-ABA7E7513886979AF8A3B68A1F4E591D.md) | 32
[C:\Windows\system32\LocationFrameworkPS.dll](LocationFrameworkPS.dll-FBF3B3CCC037AD1D9FC36C28D0E29A25.md) | 30
[C:\Windows\system32\migwiz\migres.dll](migres.dll-E937B164DC2D2A03490AC3EB9D5875B2.md) | 33
[C:\Windows\system32\oobe\diagER.dll](diagER.dll-971972596DCCC4AFDFAB8CC15DAA2F4B.md) | 32
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-09C06B0224F439DF8666CF7B411B7B1C.md) | 33
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-5D20EF28D0B222CA57F47524F2D3E8C0.md) | 29
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 36
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-C64357854C5214AC178B78EF1A17042F.md) | 32
[C:\Windows\system32\WerEnc.dll](WerEnc.dll-57896D83DAD20250B3878747AB6115F6.md) | 35
[C:\Windows\SystemApps\MicrosoftWindows.UndockedDevKit_cw5n1h2txyewy\UndockedDevKit.exe](UndockedDevKit.exe-C1FD0D396683E3F59646E4CEC2A55A85.md) | 33
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F290D12F0351B56708B3DF1EC26CB45B.md) | 33
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-BE467A8F33CDEB0538E98CF10101E9E0.md) | 63
[C:\Windows\SysWOW64\dllhst3g.exe](dllhst3g.exe-98858F3C8EE47AC663BDF08919F38EFE.md) | 58
[C:\Windows\SysWOW64\WerEnc.dll](WerEnc.dll-F4C2183256B20B62EBD7C9397F0C5D85.md) | 35

## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_uac_bypass_wmp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_uac_bypass_wmp.yml) | `Image: 'C:\Windows\system32\DllHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `- 'C:\windows\system32\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_suspicious_vss_ps_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/win_suspicious_vss_ps_load.yml) | `- '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_mal_darkside_ransomware.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/process_creation_mal_darkside_ransomware.yml) | `- 'DllHost.exe /Processid:{3E5FC7F9-9A51-4367-9063-A120244FBEC7}'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `title: Dllhost Internet Connection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `description: Detects Dllhost that communicates with public IP addresses`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `Image\|endswith: '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_unc2452_cmds.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_unc2452_cmds.yml) | `Image\|endswith: '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `ParentImage\|endswith: '\DllHost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `ParentImage\|endswith: '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_script_event_consumer_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_script_event_consumer_spawn.yml) | `- '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `Name: Dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Command: dllhost.exe /Processid:{CLSID}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `Description: Use dllhost.exe to load a registered or hijacked COM Server payload.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Path: C:\Windows\System32\dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Path: C:\Windows\SysWOW64\dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Link: https://nasbench.medium.com/what-is-the-dllhost-exe-process-actually-running-ef9fe4c19c08`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $s7 = "dllhost.dat" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


