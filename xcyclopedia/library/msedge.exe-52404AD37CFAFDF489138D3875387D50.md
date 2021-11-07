---
title: msedge.exe | Microsoft Edge
excerpt: What is msedge.exe?
---

# msedge.exe 

* File Path: `C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe`
* Description: Microsoft Edge

## Screenshot

![msedge.exe](screenshots/msedge.exe-EABEB6BDCE61B1A5670B19E4180BC753-8.png)

## Hashes

Type | Hash
-- | --
MD5 | `52404AD37CFAFDF489138D3875387D50`
SHA1 | `BD5A1F074D973902A42234AEFD92F4E37369FC17`
SHA256 | `71A40DD26769A2AE0256AE54F02F22EC6A60C9AC8AABE5BA3773EEDDDE22B756`
SHA384 | `FD8EA742E8DFF69B02C5B2936AFB489B9680A909E3D06F1691936805A616A7E16E50A12FE27DA607B562465832A14F8F`
SHA512 | `274C6D54A752C1EC5DBB00A09ADF159EF4FAB8C88D6EFD8576B70E4C295300A5ADE41EBC0E37C82BFD0A70171312E586187EE32BD0A3E050DEE91B898FDF16DA`
SSDEEP | `49152:7y5eKqxOIoi2U9AYdDos38TQsgB9uCcIZyUuO3wOTlF2y/BC:INa2U98T44yY`
IMP | `24BFDC0AC9545B2F0A59FE7AC595FB6D`
PESHA1 | `AC9401B97583800D702538E3D00A45DFACB39A16`
PE256 | `15E0C260DDE1EBBD09B1CDE32E680068A859F8F5EC8EB2864AB01BD187A3CFA9`

## Runtime Data

### Usage (stdout):
```cmhg
Opening in existing browser session.

```

### Child Processes:
msedge.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001E2F17D92020E49F87F0000000001E2`
* Thumbprint: `C774204049D25D30AF9AC2F116B3C1FB88EE00A4`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msedge.exe
* Product Name: Microsoft Edge
* Company Name: Microsoft Corporation
* File Version: 95.0.1020.40
* Product Version: 95.0.1020.40
* Language: English (United States)
* Legal Copyright: Copyright Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/71a40dd26769a2ae0256ae54f02f22ec6a60c9ac8aabe5ba3773eeddde22b756/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft\Edge\Application\95.0.1020.40\msedge.exe](msedge.exe-52404AD37CFAFDF489138D3875387D50.md) | 100

## Possible Misuse

*The following table contains possible examples of `msedge.exe` being misused. While `msedge.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [net_susp_ipify.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/net_susp_ipify.yml) | `- \msedge.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_vhd_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_vhd_download.yml) | `- msedge.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_susp_esentutl_params.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_susp_esentutl_params.yml) | `description: Conti recommendation to its affiliates to use esentult to access NTDS dumped file. Trickbot also uses this utilities to get MSEdge info via its module pwgrab.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


