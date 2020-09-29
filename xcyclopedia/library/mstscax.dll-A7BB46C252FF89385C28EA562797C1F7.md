---
title: mstscax.dll | Remote Desktop Services ActiveX Client
excerpt: What is mstscax.dll?
---

# mstscax.dll 

* File Path: `C:\Windows\SysWOW64\mstscax.dll`
* Description: Remote Desktop Services ActiveX Client

## Hashes

Type | Hash
-- | --
MD5 | `A7BB46C252FF89385C28EA562797C1F7`
SHA1 | `90E748B5DBC2F94A00289C69F5D3CD61A05DCD76`
SHA256 | `86BF0D1584A21BDFF148376EE90539EECE0768F9E70841F562E42769CFFB9C52`
SHA384 | `16FA91FDE3095456EC1965AE51B19B52E5D03919AA4180C0F04CBAF412ADF53CF5817E0756D373692C8F27A7030055A3`
SHA512 | `C7A482817354A29A3F86728D6B87D1543DE6034AAC8CBFC4BF3E7DB20E8129BFC2B10A2AD8040137F3F0CB537EC3B91CFD4555B7F45F7D43D4D3C5825D74ED26`
SSDEEP | `196608:tM6Po5YHfZ2BY4oMatFROgFMgKWhSoUlAmFPdXu1:e6PoWHfZLHMWFRKde1`
IMP | `33ACF9BF096A6AADD78F504D6019DF5A`
PESHA1 | `E805E1B0FADFF865BD9FCCBBE8DAFA44C04781AA`
PE256 | `4D45D0FF211CB9EE16DF4177B58C022F8C3A00110E1A5600AD57E033C5B8DD71`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCancelAuthentication` | 2 (0x2) | Exported Function | 0x6a7e35c0 | 0x001e35c0
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x6a7e35b0 | 0x001e35b0
`DllDeleteSavedCreds` | 3 (0x3) | Exported Function | 0x6a7e35d0 | 0x001e35d0
`DllGetClaimsToken` | 4 (0x4) | Exported Function | 0x6a7e35f0 | 0x001e35f0
`DllGetClassObject` | 5 (0x5) | Exported Function | 0x6a7e3620 | 0x001e3620
`DllGetTscCtlVer` | 6 (0x6) | Exported Function | 0x6a7e3640 | 0x001e3640
`DllLogoffClaimsToken` | 7 (0x7) | Exported Function | 0x6a7e3650 | 0x001e3650
`DllRegisterServer` | 8 (0x8) | Exported Function | 0x6a7e36a0 | 0x001e36a0
`DllSetAuthProperties` | 9 (0x9) | Exported Function | 0x6a7e36b0 | 0x001e36b0
`DllSetClaimsToken` | 10 (0xa) | Exported Function | 0x6a7e36e0 | 0x001e36e0
`DllUnregisterServer` | 11 (0xb) | Exported Function | 0x6a7e3720 | 0x001e3720


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mstscax.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/86bf0d1584a21bdff148376ee90539eece0768f9e70841f562e42769cffb9c52/detection/


## Possible Misuse

*The following table contains possible examples of `mstscax.dll` being misused. While `mstscax.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | description = "Sample from CN Honker Pentest Toolset - file MSTSCAX.DLL" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


