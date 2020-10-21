---
title: wab32res.dll | Microsoft (R) Contacts DLL
excerpt: What is wab32res.dll?
---

# wab32res.dll 

* File Path: `C:\Program Files (x86)\Common Files\System\wab32res.dll`
* Description: Microsoft (R) Contacts DLL

## Hashes

Type | Hash
-- | --
MD5 | `2CF78091007752C1AFC635C337265E67`
SHA1 | `9423D09F0EFECD43CB7512B24CB713AB91D3333A`
SHA256 | `4CD7F926E8E4EC1ABD0AD0B5E280B6E5487C922631C44658704E9EA5B9C5C157`
SHA384 | `A0AF6FB0BE603DAC34A325E42DF1988345D376B9DCC800EA6F43D4549B0CA33513F9F5E4943C64F43223762FA0A6B2EE`
SHA512 | `C24069BD520E2EC8EFB6361E44DE2176C770DACB8DFB3E97FDAAA5C29573B255416346EFE9B18749DA9192A5DB321E845C288D6A9EACE36A6939C764CFDA95D2`
SSDEEP | `12288:bTx5KRZ18xtSy2567TW7NG96FEMed/ayvTd2erR2567TWTTx5KRZIEMm:4mxtSyqiW7NGcfpAR2oqiWQSm`
IMP | `n/a`
PESHA1 | `5DF28DF40627CF18D66AE333B791994E231DDCA2`
PE256 | `EC83D8FD99D4F27E7C2F8332B75702F9250EFE164F397DAE216ACAAC04F6E77A`


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WAB32res.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/4cd7f926e8e4ec1abd0ad0b5e280b6e5487c922631c44658704e9ea5b9c5c157/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Mail\wab.exe](wab.exe-58CDC40AE57D2F2C6FC787BF66BAA1A6.md) | 35
[C:\Program Files\Windows Mail\wab.exe](wab.exe-1763CB1756D4DF101F71DBC360C875E1.md) | 35

## Possible Misuse

*The following table contains possible examples of `wab32res.dll` being misused. While `wab32res.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | description = "Detects KeyBoy Loader wab32res.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s3 = "%s\\wab32res.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


