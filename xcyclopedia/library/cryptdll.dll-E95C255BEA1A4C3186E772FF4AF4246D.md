---
title: cryptdll.dll | Cryptography Manager
excerpt: What is cryptdll.dll?
---

# cryptdll.dll 

* File Path: `C:\Windows\system32\cryptdll.dll`
* Description: Cryptography Manager

## Hashes

Type | Hash
-- | --
MD5 | `E95C255BEA1A4C3186E772FF4AF4246D`
SHA1 | `6B701887806F9CB720BB3394CAF24FB0EC093903`
SHA256 | `1B760C40C6D4F81E90978A13321C94C62CE53CC220234D50DFE8EC4638BF4B95`
SHA384 | `B380FDFCEFE1D48B4AEB8F939247E29543B61184036F7ED0F41A348624323A03CE0C35484664B5F38709E8F12F356B39`
SHA512 | `B57898A12536C50B048C38E6CBD4ADB92DB0AA3FCE9017768D2B80DA0BF16F160B224A959D9175C0A5563B43631F997DC9783122E8840ABB9B7F7A0B2E2F61F5`
SSDEEP | `1536:SHPn+CokVTSizVLXopJvgZik250hBzBgFtsVf0DIPK74:AfcvGik250hfgFGtCIZ`
IMP | `DC7032551F2AF422C6637CE127C973E4`
PESHA1 | `28AF71F1D3695E10F3D3C63D212ABB0170567CC9`
PE256 | `85416216A60AAF7891395B0060E8FA50DE58070040150E02CB7FDCE8F839633E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`CDRegisterRng` | 12 | Exported Function
`HMACwithSHA` | 13 | Exported Function
`CDRegisterCSystem` | 10 | Exported Function
`CDLocateRng` | 9 | Exported Function
`CDRegisterCheckSum` | 11 | Exported Function
`MD5Update` | 17 | Exported Function
`PBKDF2` | 18 | Exported Function
`MD5Init` | 16 | Exported Function
`KRBFXCF2` | 14 | Exported Function
`MD5Final` | 15 | Exported Function
`CDBuildVect` | 2 | Exported Function
`CDFindCommonCSystem` | 3 | Exported Function
`CDBuildIntegrityVect` | 1 | Exported Function
`aesCTSDecryptMsg` | 19 | Exported Function
`aesCTSEncryptMsg` | 20 | Exported Function
`CDLocateCheckSum` | 8 | Exported Function
`CDLocateCSystem` | 7 | Exported Function
`CDGetIntegrityVect` | 6 | Exported Function
`CDFindCommonCSystemWithKey` | 4 | Exported Function
`CDGenerateRandomBits` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: cryptdll.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/1b760c40c6d4f81e90978a13321c94c62ce53cc220234d50dfe8ec4638bf4b95/detection/


## Possible Misuse

*The following table contains possible examples of `cryptdll.dll` being misused. While `cryptdll.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'cryptdll.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_skeletonkey.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_skeletonkey.yar) | $dll1 = "cryptdll.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


