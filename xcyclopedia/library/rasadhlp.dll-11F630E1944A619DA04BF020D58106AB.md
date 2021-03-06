﻿---
title: rasadhlp.dll | Remote Access AutoDial Helper
excerpt: What is rasadhlp.dll?
---

# rasadhlp.dll 

* File Path: `C:\Windows\SysWOW64\rasadhlp.dll`
* Description: Remote Access AutoDial Helper

## Hashes

Type | Hash
-- | --
MD5 | `11F630E1944A619DA04BF020D58106AB`
SHA1 | `5207A31A4F4F49A9E74E69A3641F8DB44A6BEEAD`
SHA256 | `4FC12A7A1214A3DA726DD516E713F11D661E595B187CF0977999429674D731A2`
SHA384 | `6BAE9716E374E881BCCAC425C24509D1E79A45FD4423D34EAF332891F493C5A48325DA4A39C0ED410D7564F6A4E52379`
SHA512 | `46B9E31EE5162FE3AC1B92D1091EFF26793A56E3E182DDE0EEA0FF0F17D1D866679A501E59D8B5AE69DE34F5B74844639CBAAC1052FF8E5D48E137E5686FBC2A`
SSDEEP | `192:n2PNP4OBRlgwAyZekQ63W18CJG4myEtq6JaeoWlYWjn63:nkBR+wAueyG18CG4mlqqoWlYW`
IMP | `5976C60A4CD910F4E054E1AD4F691D7D`
PESHA1 | `82D0C8D0B8AC87323D99DC1F58F6AFAE00FEE6B6`
PE256 | `A4D9C512EC899C8167988FA0D5BAD9E4CCF2F18B0446E5365F7628B9DE388C59`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WSAttemptAutodialName` | 3 | Exported Function
`WSNoteSuccessfulHostentLookup` | 4 | Exported Function
`AcsHlpNbConnection` | 1 | Exported Function
`WSAttemptAutodialAddr` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rasadhlp.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/4fc12a7a1214a3da726dd516e713f11d661e595b187cf0977999429674d731a2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\rasadhlp.dll](rasadhlp.dll-F3325EBA04ED472DB07A67E76B01E38C.md) | 35

## Possible Misuse

*The following table contains possible examples of `rasadhlp.dll` being misused. While `rasadhlp.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-crutch-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-crutch-event.json) | `"value": "%PROGRAMFILES%\\(x86)\\Mozilla Firefox\\rasadhlp.dll",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [turla](https://github.com/eset/malware-ioc/blob/master/turla/README.adoc) | `* `++C:\Program Files (x86)\Mozilla Firefox\rasadhlp.dll++`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


