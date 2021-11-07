---
title: smss.exe | Windows Session Manager
excerpt: What is smss.exe?
---

# smss.exe 

* File Path: `C:\Windows\system32\smss.exe`
* Description: Windows Session Manager

## Hashes

Type | Hash
-- | --
MD5 | `2C3F91BB4C0994A7B36ED0B6B14EC9C7`
SHA1 | `53311CBDE782DA05C8EF97D7BC40D768E3A3EA64`
SHA256 | `56AFE5133FDC5806EC6B19436F7B55F1499CFC94619740C171424FBCF7808FD3`
SHA384 | `257ADB455DEF1D45E83DFB1A86167F236097B37EBE567B88E11CDB4E2391695CFDD911DEB64AB13EEF27031FFFEA4AC2`
SHA512 | `B602F69F67095EFC15145A0F477F22420A12564D52BDBA34C9A4134BAA96702C3EE2223932B45F13962796957AEDDB0D431C8C78D0396938C6F9758C94F15A3D`
SSDEEP | `1536:aQufZPbiE3y7vxRVXONK5OPviHfeS/DXvBADJkyYUfM8Wl20yBJ9js9VVyJPy8:vANbIk+M8rbXvBAkyYUfW25BJN4VuT`
IMP | `67B500D64F6BDF6FFD6C4F7F4DE9FDA6`
PESHA1 | `B780D2200BDC64B78F5C2EA1BEF8D76CC8E7C7B2`
PE256 | `952BC98F1DC33DD898784C627E7C786EB18C5C00BD748CA23576D857CB3C5C25`

## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smss.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/56afe5133fdc5806ec6b19436f7b55f1499cfc94619740c171424fbcf7808fd3/detection


## Possible Misuse

*The following table contains possible examples of `smss.exe` being misused. While `smss.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_use_of_sqltoolsps_bin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_use_of_sqltoolsps_bin.yml) | `ParentImage\|endswith: '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_use_of_sqltoolsps_bin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_use_of_sqltoolsps_bin.yml) | `- Direct PS command execution through SQLToolsPS.exe is uncommon, childprocess sqltoolsps.exe spawned by smss.exe is a legitimate action.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`smss.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


