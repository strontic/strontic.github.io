---
title: TSpkg.dll | Web Service Security Package
excerpt: What is TSpkg.dll?
---

# TSpkg.dll 

* File Path: `C:\Windows\system32\TSpkg.dll`
* Description: Web Service Security Package

## Hashes

Type | Hash
-- | --
MD5 | `0A5F60015365A3CE5F5983B0BC1A7ABC`
SHA1 | `D33D724E884555CF844033EEED9BCDF2003E5C75`
SHA256 | `CBF62012671FBC723D88E17A4B940A505995A0888D92C8CA97143FF100836D60`
SHA384 | `7444BD01A399AB7B5B01D74A404FF037C465587CC4A127FBF38A7EEEC3311E40F5E3A36DA6EAFAF8F968418E280A271B`
SHA512 | `EF6DDCED0DA0F043A65E118C12D03417B01AE5EF78D7F78C54B02DA19BE4FE40E05740363FA5FA30F00FC584626700FE46BA974ECF09202413D7A9CED0F52D3F`
SSDEEP | `3072:gSHemKoHyO23tF43AE1wdWmGZcolzQxpJlD8y+Q0x8:BHemKoW3tF436dWmGZcDpY40`
IMP | `E54A18644CEF669FF00700F10393B944`
PESHA1 | `03FEFA8815AD486BEA9E22B1888D8C15AD79F95E`
PE256 | `55973E1432376A49CA5CC65C477CD33DA3B50451DE1812DBAD45A53A0ADB6EE1`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`SpUserModeInitialize` | 2 | Exported Function
`SpLsaModeInitialize` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSpkg.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.264 (WinBuild.160101.0800)
* Product Version: 10.0.19041.264
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/cbf62012671fbc723d88e17a4b940a505995a0888d92c8ca97143ff100836d60/detection/


## Possible Misuse

*The following table contains possible examples of `TSpkg.dll` being misused. While `TSpkg.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s6 = "tspkg!TSGlobalCredTable" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mimikatz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mimikatz.yar) | $s5 = "sekurlsa::tspkg" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


