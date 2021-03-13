---
title: dllhost.exe | COM Surrogate
excerpt: What is dllhost.exe?
---

# dllhost.exe 

* File Path: `C:\windows\SysWOW64\dllhost.exe`
* Description: COM Surrogate

## Hashes

Type | Hash
-- | --
MD5 | `CC05C14EEFF5E7813A49718BA88E59B0`
SHA1 | `2BB3A1C63CC3B09AE7C8AD45FF2F437CAD4B7A97`
SHA256 | `771151FDEB8E30545F4BBFE1B73EEE0E1187DB905A535E9CC12D2C57AA0ACC8D`
SHA384 | `8CBE36A582CA1C2E6E04F924EF7906A6A46B6A8C9971AC66991CA019FDD8C1DA43B44600015DB6FE8E8DF671566B3146`
SHA512 | `E48DF4286A9114A47FEBC96480AD748FEE97C0FF50F87B525AA17CFE7DC043BE5F8FE406E6001D5049DA68F742EB06A620D66C7A5F5DD1E89A480B3FF29DFCF4`
SSDEEP | `384:4O1slXwD+Og1GFWe5WoDBRJBLlxXWindGC:4IZg1Gbt1PB7Gin4C`

## Signature

* Status: Signature verified.
* Serial: `330000004EA1D80770A9BBE94400000000004E`
* Thumbprint: `DF3B9B7E5AEA1AA0B82EA25F542A6A00963AB890`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `- 'C:\windows\system32\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `title: Dllhost Internet Connection`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `description: Detects Dllhost that communicates with public IP addresses`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_dllhost_net_connections.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_dllhost_net_connections.yml) | `Image: '*\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_unc2452_cmds.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_unc2452_cmds.yml) | `Image\|endswith: '\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `ParentCommandLine\|contains: '\DllHost.exe '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\dllhost.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `Name: Dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Command: dllhost.exe /Processid:{CLSID}`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `Description: Use dllhost.exe to load a registered or hijacked COM Server payload.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Path: C:\Windows\System32\dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Path: C:\Windows\SysWOW64\dllhost.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dllhost.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dllhost.yml) | `- Link: https://nasbench.medium.com/what-is-the-dllhost-exe-process-actually-running-ef9fe4c19c08`{:.highlight .language-yaml} | 
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nopetya_jun17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nopetya_jun17.yar) | $s7 = "dllhost.dat" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


