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
MD5 | `DC6C71AB53DA4EBED427DD4F02B16688`
SHA1 | `9F1F5D7A6DCC64EBE76708BDC494123FE0AC8C5D`
SHA256 | `5C0FAEBCEDE7821DFBCE95ABED8B85BC25E19489EA6CF4D404A54E4E366A5E88`
SHA384 | `B0FDFF876706AB6C60A9E8157D5A1EA7BECC8435B8C12385CBB1B8D1BBE1CD399C6287162B95DA9DD41E46B04FAD7FFB`
SHA512 | `2E707F58B7EC98EF763C9ADDD191920F9BCE7138B1564052B5525C1B2BF5BFEE11BE4C399F60FB02FAA83FFB3A18605C6B81CD66B1B9FC194288A837F74F14D2`
SSDEEP | `3072:BwufRJRxMXakk9X/QWV1GIhHSXNBJPgUe19fK:BjJWKkk9v71GQSXNj`
IMP | `9514316F92E1910DDBCE2EA3735D33A5`
PESHA1 | `F6D01A79EAF158F2BF3F058FA49B2236DA80BBFF`
PE256 | `A5DCAD6865E4CF5FD990AAF407788736F341DE11262C7125DB583AA768D5CE98`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/5c0faebcede7821dfbce95abed8b85bc25e19489ea6cf4d404a54e4e366a5e88/detection/


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


