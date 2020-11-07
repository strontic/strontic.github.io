---
title: Windows.Media.dll | Windows Media Runtime DLL
excerpt: What is Windows.Media.dll?
---

# Windows.Media.dll 

* File Path: `C:\Windows\SysWOW64\Windows.Media.dll`
* Description: Windows Media Runtime DLL

## Hashes

Type | Hash
-- | --
MD5 | `0662B423B84DBCE6750FB66255575386`
SHA1 | `F6CD3096095E67F5ABAD689B6F1991AF6A506EDA`
SHA256 | `5A9430211A4A8A15D0C37980B58CB36692EF605DC01188E08146E423052AF997`
SHA384 | `391632930B1B046F9C7EC532C080FE1CA95D52A5F4A0D15FE6C61485ED4508F156B80627BA455A6010ED9C1855BD02BB`
SHA512 | `7A42652CF54CE8CD0F43217F57387E0645D3069E63216F6D3BD160A4F88FB6EC5260E2DD87D2991E763324C1913B9327014740ACEE05ECE5FF9E1B6D765D5E65`
SSDEEP | `49152:wEdL9nZJ/HM1llGMTTN7YmXRoXcfN3UxbpejMHAeOZ0LUyRzdo8KNhU5cwHkSuAy:JSJXmXcJUxbwjMgryRGuAi3ZWI1l6`
IMP | `46C5FD0FCCD3D2CAC61B53126F5A33FB`
PESHA1 | `0E9FED0A740E2DC1BD6560A6F5B77B523ED4BFDD`
PE256 | `53E354ADBDB900C00CEF5F4A17B81C23C1BBA6DC9C52C0857970273BD7B07D23`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 2 | Exported Function
`DllGetActivationFactory` | 1 | Exported Function
`DllGetClassObject` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Windows.Media.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/5a9430211a4a8a15d0c37980b58cb36692ef605dc01188e08146e423052af997/detection/


## Possible Misuse

*The following table contains possible examples of `Windows.Media.dll` being misused. While `Windows.Media.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\Windows Media Player\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_exec_folder.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_exec_folder.yml) | `- C:\Windows\Media\\*` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


