---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\system32\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `1BFFABBD200C850E6346820E92B915DC`
SHA1 | `C82C3B5236420FCC0BC54F62322DFA598DC4C404`
SHA256 | `6C51C1968A7AD1B40251AD58F44602114888DB2859B1375E0BFFC7EB8C2C22E4`
SHA384 | `4C854393A09F57F6FFFF29D536B001452E305B160E2D4ED249CBC0C3C5A1377CDEBB23642AE1E49459AECEDDC2DD7610`
SHA512 | `90AF5E628D9DB2FF11DF1D4DC5B1433A3286F042484CEF620639964FC3F49BDA93FFD0A82C82DECDB5318E24409A128DE04D8D40E82C1F6AE6216AC4D8B7F2A5`
SSDEEP | `1536:cZ5H2POb7l/WO7bMv+MinfDTeuzP0DxPfrkiD9r+vCtrStwgVeBL6B1jh1aANQd3:61JbMvefDF8DNHD9r+qC11mwUMVo6Fa`
IMP | `367D299428703C9A9715504BFE071C97`
PESHA1 | `2BED97D556E884ACE8978CF3E0AB49719DF7F35B`
PE256 | `9116000880800F45F9BDDC9CBF37B9B28424479C9694C0403527F4697889D2E4`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\system32\wbem\WMIADAP.exe |
C:\Windows\SYSTEM32\wbemcomn.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1320 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1320
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6c51c1968a7ad1b40251ad58f44602114888db2859b1375e0bffc7eb8c2c22e4/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\WMIADAP.exe](WMIADAP.exe-44FA781649A564AD9DD8453D14758F96.md) | 93

## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


