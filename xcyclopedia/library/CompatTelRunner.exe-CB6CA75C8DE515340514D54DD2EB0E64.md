---
title: CompatTelRunner.exe | Microsoft Compatibility Telemetry
excerpt: What is CompatTelRunner.exe?
---

# CompatTelRunner.exe 

* File Path: `C:\Windows\system32\CompatTelRunner.exe`
* Description: Microsoft Compatibility Telemetry

## Hashes

Type | Hash
-- | --
MD5 | `CB6CA75C8DE515340514D54DD2EB0E64`
SHA1 | `D562D36F3F1AB5F1C96D6532DFDBEEDC12491CE1`
SHA256 | `2967699A953D5690222655124FBB79ACCDBBE7714F7698FCADC1815B1684E81B`
SHA384 | `5CBE00C1EE68C812EE1FAE702603AAC932788623D9E3C805D9A2ADB890A7655EF37650A26C2D7F3E8E3FC696A25E8762`
SHA512 | `28470B803778FF7B8D4D8F9CE7BD971352B5881E21E7283EFDA5223A2ECD8F8BBF8DAF45088EA7D825F155ECC95809E246A6099FD073BC0BAF07046E295AC863`
SSDEEP | `3072:qm18wDYYRZVaVWELsqeW+arDGi9UkIHLLeDDAtwJ2H2NXd:q88wn3VaVMqeWY1k4WDDA6N`
IMP | `5E4D55883A5FB7A7D7CAB55A34B42708`
PESHA1 | `F45336CFC6E2AFD609643AA2AE285DA231D93870`
PE256 | `F35C42CD3A7F2F5468C8F61857766FF55738A88B03A2F9455A2760F9F012A32E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\CompatTelRunner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CompatTelRunner.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19645.1016 (WinBuild.160101.0800)
* Product Version: 10.0.19645.1016
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/2967699a953d5690222655124fbb79accdbbe7714f7698fcadc1815b1684e81b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-32D8EEFAB5942B37C8C04CED08E47139.md) | 93

## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\CompatTelRunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\compattelrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


