---
title: ntoskrnl.exe | NT Kernel & System
excerpt: What is ntoskrnl.exe?
---

# ntoskrnl.exe 

* File Path: `C:\Windows\system32\ntoskrnl.exe`
* Description: NT Kernel & System

## Hashes

Type | Hash
-- | --
MD5 | `247F07BED19389B12AA2EC550FB5FF90`
SHA1 | `81CB5B2B8521AE59B3BF932CDDC04100C581F5DA`
SHA256 | `ADBA735E87F72021A87D10E67710F15B44486A0720711A324E03849DA528834B`
SHA384 | `F2C71948C05FA8A0A67DCDAA8AEED3C222FB9B1BB86B87FE1FBA3C8B96D47E5580559F52DC61AD6B4B2A0DA39293ED01`
SHA512 | `18106F48EA8D6A86E1115A871E21108B9EBBB96557EF5A753619408990307BB255B93FD8E382F1816AA81ACBDC4C610EA52D32FD34D93B8D336FBA6CFBABED58`
SSDEEP | `98304:RdfRjVM5rIaScBStSelf4fuX75jbr5uyOLTSfu1jOVu1giesSezNluj:JuRSwUSelf4fuX75jbr5uycDjO8Wi5pC`
IMP | `E0E869BBD92F59B58E146BA81EEE3F6D`
PESHA1 | `23A330A84B293ACA2898B7195D655F4A39289631`
PE256 | `991E62450BA177BA5CD74235BD7EC5780D7EDF31DD2D335BD2EEDE95FA4B2B2A`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ntkrnlmp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.610 (WinBuild.160101.0800)
* Product Version: 10.0.19041.610
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/adba735e87f72021a87d10e67710f15b44486a0720711a324e03849da528834b/detection


## Possible Misuse

*The following table contains possible examples of `ntoskrnl.exe` being misused. While `ntoskrnl.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hackingteam_rules.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hackingteam_rules.yar) | $x4 = "C:\\\\Windows\\\\Sysnative\\\\ntoskrnl.exe" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $s17 = "NTOSKRNL.EXE" fullword wide /* Goodware String - occured 4 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a5 = "ntoskrnl.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a3 = "%SystemRoot%\\System32\\ntoskrnl.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_hdroot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_hdroot.yar) | $s1 = "\\system32\\ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_querty_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_querty_fiveeyes.yar) | $s3 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $s4 = "ntoskrnl.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


