---
title: capisp.dll | Sysprep cleanup dll for CAPI
excerpt: What is capisp.dll?
---

# capisp.dll 

* File Path: `C:\Windows\SysWOW64\capisp.dll`
* Description: Sysprep cleanup dll for CAPI

## Hashes

Type | Hash
-- | --
MD5 | `75A603D846A301BC80DB16DD0B5EF187`
SHA1 | `2CF5C64444D8F21CDB161B79D90C2D3D2FB9BCD1`
SHA256 | `7396E18969490BD0786A48A6F50056C6E0CD42DD7D98D0EEFC8EACA10D21C087`
SHA384 | `1B4D4ABDE200E2E790B02A629A0144AB62F7688116042DA878EAE10EC8922423D3903CCE58B35A0A804AB8F398CDA482`
SHA512 | `0B7E6F4537FE606FCAE3F81B42DFC91A8268FF1F00A3D590675E2A5D6526E00F9000073495E86C33B3D61725A7F995CB8B53007300D65DA69CF7852011775A59`
SSDEEP | `384:NfbjK+tBNmwV8J7e+JDla2axkOS3Ch4AV+ZfKySqfTAR0ZZ0WcWghW2:x7ala2axvONHrSeTHZZcT`
IMP | `5533CB9574CE75D3AC71FA3B540F95C9`
PESHA1 | `D761AC8741392D0F229DCC7124E650A6570C3DDB`
PE256 | `3B771A12B6B8FD4A5496BA0CA0D7BC932D71486065EFFB962C02AD7C5A93313A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CAPISysPrep_Generalize` | 1 (0x1) | Exported Function | 0x10002d80 | 0x00002d80
`CryptoSysPrep_Clean` | 2 (0x2) | Exported Function | 0x100035e0 | 0x000035e0
`CryptoSysPrep_Specialize` | 3 (0x3) | Exported Function | 0x100031d0 | 0x000031d0
`CryptoSysPrep_Specialize_Clone` | 4 (0x4) | Exported Function | 0x100031e0 | 0x000031e0
`CryptoSysPrep_Specialize_Offline` | 5 (0x5) | Exported Function | 0x100031f0 | 0x000031f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: capisp.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/7396e18969490bd0786a48a6f50056c6e0cd42dd7d98d0eefc8eaca10d21c087/detection/


## Possible Misuse

*The following table contains possible examples of `capisp.dll` being misused. While `capisp.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `www.capisp.com` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


