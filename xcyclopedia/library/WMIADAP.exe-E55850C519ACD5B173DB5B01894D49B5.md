---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\Windows\SysWOW64\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `E55850C519ACD5B173DB5B01894D49B5`
SHA1 | `65AE829618142649C64536FB50B42F68F3490037`
SHA256 | `9119DA0262826F56EEDA0D3C13DC4B5357078AE499B3F224904FF9B8E9E3F99F`
SHA384 | `CC83FF67507FF5EB518E9A34FFD67B85A3B9C00B02AB4896B818F8CFC68B77D5955F0B41D0F867CA14A2634A244215C9`
SHA512 | `0234345AA766BBF2667EA38F68EAD9F5FF54E77E631D3994A24B5CA3BBC2F381E6B46605B00721DC93EF8BDF921ADE37066247D949F6B03913191AF150280151`
SSDEEP | `3072:ri+6S+4VOWQZPOu2qgXRm6kMcmZOmNn26/W:rix4kWQ9x2qotkPmZOmN2sW`
IMP | `8CFB5725B2F97204F3268EDACE605269`
PESHA1 | `8572CBE28E2C756FB8F6AC352788FB75B493A1BC`
PE256 | `B031B877874958546A19E126FC0BC579EEA10324AF3C95FB91387EE72CFF1C0A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wbem\WMIADAP.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/9119da0262826f56eeda0d3c13dc4b5357078ae499b3f224904ff9b8e9e3f99f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wbem\WMIADAP.exe](WMIADAP.exe-83CFA0ACAA299FD5B1B5A255CBD4602B.md) | 82
[C:\Windows\SysWOW64\wbem\WMIADAP.exe](WMIADAP.exe-F9BBB6D53ED2EC2929CB58FD3673C1DE.md) | 85

## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


