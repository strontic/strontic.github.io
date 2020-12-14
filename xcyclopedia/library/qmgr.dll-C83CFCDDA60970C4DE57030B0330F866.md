---
title: qmgr.dll | Background Intelligent Transfer Service
excerpt: What is qmgr.dll?
---

# qmgr.dll 

* File Path: `C:\Windows\system32\qmgr.dll`
* Description: Background Intelligent Transfer Service

## Hashes

Type | Hash
-- | --
MD5 | `C83CFCDDA60970C4DE57030B0330F866`
SHA1 | `D492C4E1D705B2EE50DC88E7F83EB0EC6B327288`
SHA256 | `3E91AF855D39D3FBD8DDE9BD39B86C42558F851CA3B0B46A3F05156EF563ED96`
SHA384 | `BE36A816C4FB24D0A32E501E83D25CB2A668FE8CE9A5D498EE15F71A0CED9F86E8BA340B81C8EAE28B38850AB44C675E`
SHA512 | `66725CDA6A211FB8E6FDAB954B01830BAE2D8BFEE8C796BE2D88664D1272D22935CFBC4DDF7592D028CB261C53A3CB4A7AE7D945B7512738F6802D9CA936BDD9`
SSDEEP | `24576:Ug554yqM/xGZRD+88zFj6SOsWaABnKDtAumQPyeFhIMo5x9T8W1uKzz:75aM/xGPD+3zFuSOzgyumnh95xT1uK`
IMP | `48887E9125A2697E695C9A310B62D48D`
PESHA1 | `A6C7D85C352D4AF2E258B4B0958A1DA6257EAFC5`
PE256 | `114D400FF73356645AA6DA98583E533C503A3FF94ACF16F1EAF9121064EC302C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CPerfMon::__INSTANCE_ID` | 4 | Exported Function
`CPerfMon::__OBJECT_ID` | 7 | Exported Function
`CPerfMon::operator` | 1 | Exported Function
`ServiceMain` | 9 | Exported Function
`CPerfMon::__INSTANCE_ID` | 3 | Exported Function
`CPerfMon::__INSTANCE_ID` | 5 | Exported Function
`BITSServiceMain` | 10 | Exported Function
`CPerfMon::__OBJECT_ORD` | 6 | Exported Function
`CPerfMon::__COUNTER_ID` | 2 | Exported Function
`CPerfMon::__OBJECT_ID` | 8 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qmgr.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 7.8.19041.1 (WinBuild.160101.0800)
* Product Version: 7.8.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/3e91af855d39d3fbd8dde9bd39b86c42558f851ca3b0b46a3f05156ef563ed96/detection/


## Possible Misuse

*The following table contains possible examples of `qmgr.dll` being misused. While `qmgr.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $s1 = "%SystemRoot%\\System32\\qmgr.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


