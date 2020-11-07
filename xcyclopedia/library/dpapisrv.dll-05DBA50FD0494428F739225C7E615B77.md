---
title: dpapisrv.dll | DPAPI Server
excerpt: What is dpapisrv.dll?
---

# dpapisrv.dll 

* File Path: `C:\Windows\system32\dpapisrv.dll`
* Description: DPAPI Server

## Hashes

Type | Hash
-- | --
MD5 | `05DBA50FD0494428F739225C7E615B77`
SHA1 | `605DDA4C49A9E597AE636559A1BAD9E8D4CC0C02`
SHA256 | `5CCC3E86E91FAA2D6A5F8F2B597F46D526FA5B5F714AB20ECFBEB2271B3C6417`
SHA384 | `94F80143AFD10317616C06DE38E88A075F540488737D3D2D1BA33D34EE65339F5BAE645527B900337478945A18E42A2F`
SHA512 | `BF362EBD4ACE4311B08F4BC22E98C3DF67736220D928797DCE16D00F6CC7037EEE03C94725F0C230767784E10EAEF038017E31F251FDD7B5036FBCD46A934D18`
SSDEEP | `3072:2GiR8mrHEFSKyugB5ny/fzsyjd4TTSWXvce4VJwqCPGDsostTrg5UNgItmi+N/4J:xmrcN2Bly/gOd4TTVXgVfCPdPptmi+`
IMP | `C0025AFD2F803F9E2E39889BF570177A`
PESHA1 | `D946783BC36E84E831742E4A56B969DBD39DFE8C`
PE256 | `D4294B57129A5516C7F953685FA88E9EC104FF85B578DED71B90807E431DBF12`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`InitializeLsaExtension` | 1 | Exported Function
`QueryLsaInterface` | 2 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dpapisrv.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/5ccc3e86e91faa2d6a5f8f2b597f46d526fa5b5f714ab20ecfbeb2271b3c6417/detection/


## Possible Misuse

*The following table contains possible examples of `dpapisrv.dll` being misused. While `dpapisrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s1 = "dpapisrv!g_MasterKeyCacheList" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


