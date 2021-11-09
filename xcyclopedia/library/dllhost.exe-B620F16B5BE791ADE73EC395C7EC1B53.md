---
title: dllhost.exe | COM Surrogate
excerpt: What is dllhost.exe?
---

# dllhost.exe 

* File Path: `C:\WINDOWS\system32\dllhost.exe`
* Description: COM Surrogate

## Hashes

Type | Hash
-- | --
MD5 | `B620F16B5BE791ADE73EC395C7EC1B53`
SHA1 | `B2C58FEF5E6ABFC119336F4A747D2C6113FE70AD`
SHA256 | `7BC7D4062BB3F8271DBC93B5D55011219AD2D8ED0D67ACED925E46E7EDA9B438`
SHA384 | `A3DF87B9D49E907DD57DBA4BDF43EBD26DC6CA4AFB81E035268F1B5071F28499A06E8263E73A45A6F1CAE13DC9BB3ACC`
SHA512 | `2505714D46AC3B81E1CAA307957880276AC58F741FED814F4E9DEFC16EC5EFC2BE7576AB6DB7C379E3451075BB685E916AAC7F9326C6FADB2D97D73F531AB9A5`
SSDEEP | `192:VahsOfijGhcXktyuNfkmh9aRuaEZcRWv5WAqUyfUlHDBQABJ+c/uuOiqnajljO9Y:8hs+hcXktztcRWv5WgDBRJ+NilZz`
IMP | `FBDAC0471446783AD621D3CAB6033559`
PESHA1 | `233FEAAED3F148493329702310A2E24E6E6D39D0`
PE256 | `9386FAE9CF94F4B2BEDFF487FCB1FBE7BB803276E4B993B843F9F55CC6F5DEDC`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\dllhost.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7bc7d4062bb3f8271dbc93b5d55011219ad2d8ed0d67aced925e46e7eda9b438/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\dllhst3g.exe](dllhst3g.exe-B00A34952FB4581B6A4543B3A7E14D38.md) | 47
[C:\Windows\system32\downlevel\api-ms-win-core-threadpool-private-l1-1-0.dll](api-ms-win-core-threadpool-private-l1-1-0.dll-26CEDF47AECFB777EFC169A0740416A2.md) | 32
[C:\Windows\system32\downlevel\api-ms-win-crt-stdio-l1-1-0.dll](api-ms-win-crt-stdio-l1-1-0.dll-429C26ED27A026442F89C95FF16CE8C2.md) | 33
[C:\Windows\SystemApps\MicrosoftWindows.Client.CBS_cw5n1h2txyewy\ScreenClipping\ScreenClippingHost.exe](ScreenClippingHost.exe-3C4E7F1BF05A5088430FB512081061B2.md) | 36
[C:\WINDOWS\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-1A79FA2EC172EC30F985348A51C9105E.md) | 38

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


