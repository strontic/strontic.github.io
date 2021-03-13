---
title: iexplore.exe | Internet Explorer
excerpt: What is iexplore.exe?
---

# iexplore.exe 

* File Path: `C:\Program Files (x86)\Internet Explorer\iexplore.exe`
* Description: Internet Explorer

## Screenshot

![iexplore.exe](screenshots/iexplore.exe-6BFE7CA23C89FD5809A48355EC5625EE-8.png)

## Hashes

Type | Hash
-- | --
MD5 | `A2CD9CF67DEB267D7A2813F00D47245C`
SHA1 | `BB16D6876EB89343D31BEEA8DCFF56AD9BAD6DD5`
SHA256 | `3BE1ABC6DAF27760A91413B77C4BA0A73EF92115FDA35FF6947B8AD937F54DF9`
SHA384 | `2BC1FA5A0DB664923B6D8C7CF362478809AF169593638835DA6B1BE23C6C76232D53A9D08D2ED0E106E8A17AEBBE12E3`
SHA512 | `FF49954A579274FDA687DFADDCE7A7522B62B30F88A2E0AD6A16AEAC456AD86B30FE69D6F8EA667B08DF237503867645CF3A722EB8BE168BB52F0D8EFDA21AFF`
SSDEEP | `24576:S3fqlGLbMMHMMMvMMZMMMKzb6XmMMMiMMMz8JMMHMMM6MMZMMMeXNMMzMMMUMMVG:S7MMHMMMvMMZMMMlmMMMiMMMYJMMHMMs`
IMP | `2C2E1D73CA9132FDC123B09EF74BD684`
PESHA1 | `B89AA13656E8E297C93A12D13A9FE3D648B23193`
PE256 | `4CD57C1672446F40F9BEBE58293A738EAA5B8434E1381B1AB4744BF5F5C01B66`

## Runtime Data

### Child Processes:
iexplore.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Internet Explorer\iexplore.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IEXPLORE.EXE.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3be1abc6daf27760a91413b77c4ba0a73ef92115fda35ff6947b8ad937f54df9/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Internet Explorer\iexplore.exe](iexplore.exe-2E414291458B49ACDA42C80A4C10DE7E.md) | 94
[C:\Program Files\Internet Explorer\iexplore.exe](iexplore.exe-6BFE7CA23C89FD5809A48355EC5625EE.md) | 93
[C:\Program Files\internet explorer\iexplore.exe](iexplore.exe-F640445694FD65DEC07CA3A84F560534.md) | 93

## Possible Misuse

*The following table contains possible examples of `iexplore.exe` being misused. While `iexplore.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_abusing_azure_browser_sso.yml) | `- iexplore.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1388.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1388.yml) | `Image: '*\iexplore.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\iexplore.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\iexplore.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `IExplore`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `iexplore.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | Upon execution, "Process C:\Program Files\Internet Explorer\iexplore.exe is spawned with pid ####" will be displayed and | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | \| spawnto_process_path \| Path of the process to spawn \| path \| C:&#92;Program Files&#92;Internet Explorer&#92;iexplore.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.004/T1134.004.md) | \| spawnto_process_name \| Name of the process to spawn \| string \| iexplore\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s10 = "iexplore." ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s8 = "iexplore." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt30_backspace.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt30_backspace.yar) | $s1 = "iexplore.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_bronze_butler.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_bronze_butler.yar) | $s4 = "iexplore.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eternalblue_non_wannacry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eternalblue_non_wannacry.yar) | $s1 = "\\Program Files\\Internet Explorer\\iexplore.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | $s1 = "%ProgramFiles%\\Internet Explorer\\iexplore.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_dexter_trojan.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_dexter_trojan.yar) | $s3 = "\\Internet Explorer\\iexplore.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of iexplore.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "iexplore.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_malware_set_qa.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_malware_set_qa.yar) | $s5 = "\\Internet Explorer\\iexplore.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s5 = "!&start iexplore http://www.crsky.com/soft/4818.html)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal iexplore.exe - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $win2003_win7_u1 = "IEXPLORE.EXE" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename == "iexplore.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


