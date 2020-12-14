---
title: rasauto.dll | Remote Access AutoDial Manager
excerpt: What is rasauto.dll?
---

# rasauto.dll 

* File Path: `C:\Windows\system32\rasauto.dll`
* Description: Remote Access AutoDial Manager

## Hashes

Type | Hash
-- | --
MD5 | `CDEE1DAD843C354A0515D71C89D2741F`
SHA1 | `8A0CAC419E55AC1FE356F732767F47C9E8B25CC0`
SHA256 | `BF04BD9885CE53355343F7C8CE3092A7AE432BB8CBAC2C3223BA9E2A39BC00FB`
SHA384 | `923F8508CFFBED62C9DDC01FE34E0675DD5C6E49700248CA114D8A85C4FB3A46542EFAE91A5FB050F20E5877E4D09F97`
SHA512 | `CFEF0EFE217605FE473998D3F3519FDA306B12FEF5B56C3FA26AF058305F456521DF7F5083711F7A8C411F40D7EFD93D1C53CC70A2BE8D4AE7DB2F060BAA43E5`
SSDEEP | `1536:cn1GYSvbH0EwJKVZ4q3p2fl2HzvyU+WfZYc6M5Fd648feIT61AacCfVblIs44tQQ:cYYSHp29RUJaEFdI61AwJ44Wm/`
IMP | `088F671DBBEC0BBE76643C55479BD103`
PESHA1 | `B0E328ADDFD3F0D632814FEF321ABF0E5D0B9FAC`
PE256 | `BEF98330BAB325ECE48C7D92A7E86266C3A3E16875B3AE29A2E5047C2256DE99`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SetAddressDisabledEx` | 2 | Exported Function
`ServiceMain` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasauto.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/bf04bd9885ce53355343f7c8ce3092a7ae432bb8cbac2c3223ba9e2a39bc00fb/detection/


## Possible Misuse

*The following table contains possible examples of `rasauto.dll` being misused. While `rasauto.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_glassRAT.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_glassRAT.yar) | $s3 = "SYSTEM\\CurrentControlSet\\Services\\RasAuto\\Parameters" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_glassRAT.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_glassRAT.yar) | $s8 = "SYSTEM\\ControlSet00%d\\Services\\RasAuto" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s4 = "%s\\rasauto.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s1 = "\\RasAuto.dll" fullword ascii /* score: '11.025' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


