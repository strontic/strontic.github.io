---
title: smss.exe | Windows Session Manager
excerpt: What is smss.exe?
---

# smss.exe 

* File Path: `C:\windows\system32\smss.exe`
* Description: Windows Session Manager

## Hashes

Type | Hash
-- | --
MD5 | `D8564418BAC13776E43DB5F6B4FA775E`
SHA1 | `495461D0DF8F1F89C4BBC03F997E027BEA08DDE2`
SHA256 | `FC8EF5704C871187AE4945000DB3D3758E8B867E90F8E530B0F12C6438D17D35`
SHA384 | `84CAB02AF8CC27A761CBF4E14F1A1912BFFC039FDFDAEB7EF5D23443DA567116B816C65A15E2648C462814C2FCAEC63E`
SHA512 | `418FD106F44455AA5D3449144526B2CDCE14C2B820413A7ADDF5F97E96F98D3DA7FA3A659CC78214826586594BD25F4459C843BFFD9E6AC1EBD52809CED4257F`
SSDEEP | `3072:jRBB9yXQQDEiZyKLwzMdX9Wg6WwjDfuequOyorTe:jRBbV3ionmeq9`

## Signature

* Status: Signature verified.
* Serial: `330000000ECB1DE44CF76049B800000000000E`
* Thumbprint: `1D17F6631C3F4E9C4B563AF01A1E811D83E15B95`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: smss.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `smss.exe` being misused. While `smss.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\smss.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`smss.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects uncommon file size of smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | and filename == "smss.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


