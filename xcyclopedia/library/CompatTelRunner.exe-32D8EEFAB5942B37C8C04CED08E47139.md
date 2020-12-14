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
MD5 | `32D8EEFAB5942B37C8C04CED08E47139`
SHA1 | `995FE5540E3CAF8E9EA80951F5B2B1F783190EF1`
SHA256 | `C0A5986A4DD6D7CACF09C5A980DF634C44FF73028206D99CB561E64A74A0958A`
SHA384 | `48ECDA940284522818FCAF7A2638BB1EA9E5FD94618DF3A9E8BB72BAE8B3DE2552671825AF43F60BEA0CEF824FA2226B`
SHA512 | `7FBD60BFA3C54E872083DC7365AB0030E22650D613F2AE6F6A4689A127890942B14B624007DC5D68FC459B9562FB5B59D07A8251052CE85C3E42054944B12F3E`
SSDEEP | `3072:fm18wDYYRZVaVWELsqeW+arDGi9UkIHLLeDDAtwJ2H260L:f88wn3VaVMqeWY1k4WDDA6j`
IMP | `5E4D55883A5FB7A7D7CAB55A34B42708`
PESHA1 | `F45336CFC6E2AFD609643AA2AE285DA231D93870`
PE256 | `F35C42CD3A7F2F5468C8F61857766FF55738A88B03A2F9455A2760F9F012A32E`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\CompatTelRunner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\SYSTEM32\ntmarta.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\WS2_32.dll |


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

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/c0a5986a4dd6d7cacf09c5a980df634c44ff73028206d99cb561e64a74a0958a/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\CompatTelRunner.exe](CompatTelRunner.exe-CB6CA75C8DE515340514D54DD2EB0E64.md) | 93

## Possible Misuse

*The following table contains possible examples of `CompatTelRunner.exe` being misused. While `CompatTelRunner.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\CompatTelRunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\compattelrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


