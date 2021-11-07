---
title: dllhost.exe | COM Surrogate
excerpt: What is dllhost.exe?
---

# dllhost.exe 

* File Path: `C:\Windows\system32\dllhost.exe`
* Description: COM Surrogate

## Hashes

Type | Hash
-- | --
MD5 | `08EB78E5BE019DF044C26B14703BD1FA`
SHA1 | `2CE12A317BEBF8293F3544433A55D972A5967996`
SHA256 | `E7FC40B41AA8B83841A0B96D169EAF0800AA784733E636935374D56536253F10`
SHA384 | `FE56817F7F5B8534AA8E57A7FFC546DF18B9B74A0765CA590D3015AAC4B8A4FE79BC1B7DD6B837747F9FB51230C3CDB8`
SHA512 | `A2BC4EB15048C182AF80192C19147D8871396B1463A8CB9257C80B142698B71A8093C65206847D9E07FCC2FBED0829390908597F617E26AC6523577927836562`
SSDEEP | `384:lJRXcksOiPxc+rWw5Ww78hDBRJXP+CcWlGsaX:lJR7cxcEKh1PfwL`
IMP | `CF79FCE90FCED31836373F3E48251A5D`
PESHA1 | `24BBAE507219C32594364D9ED39EA16AFB892032`
PE256 | `07F72EC5C39A54A33C0E9238E42E517168682029210AA9CDAC647116B9D1B954`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\system32\dllhost.exe |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/e7fc40b41aa8b83841a0b96d169eaf0800aa784733e636935374d56536253f10/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\dllhost.exe](dllhost.exe-C6723950D1A8CD49D93C8D082B175D41.md) | 44
[C:\Windows\system32\dllhst3g.exe](dllhst3g.exe-E4208ACA399EC8C0AD48B05960F7FA9D.md) | 41

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


