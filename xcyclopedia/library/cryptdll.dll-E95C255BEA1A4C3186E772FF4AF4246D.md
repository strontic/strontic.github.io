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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`aesCTSDecryptMsg` | 19 (0x13) | Exported Function | 0x0000000180002aa0 | 0x00002aa0
`MD5Init` | 16 (0x10) | Exported Function | NTDLL.MD5Init | 0x0000d63a
`MD5Final` | 15 (0xf) | Exported Function | NTDLL.MD5Final | 0x0000d623
`KRBFXCF2` | 14 (0xe) | Exported Function | 0x0000000180001ae0 | 0x00001ae0
`HMACwithSHA` | 13 (0xd) | Exported Function | 0x00000001800018f0 | 0x000018f0
`CDRegisterRng` | 12 (0xc) | Exported Function | 0x0000000180001770 | 0x00001770
`CDRegisterCSystem` | 10 (0xa) | Exported Function | 0x0000000180001220 | 0x00001220
`CDRegisterCheckSum` | 11 (0xb) | Exported Function | 0x0000000180001850 | 0x00001850
`CDLocateRng` | 9 (0x9) | Exported Function | 0x00000001800017c0 | 0x000017c0
`CDLocateCSystem` | 7 (0x7) | Exported Function | 0x00000001800015d0 | 0x000015d0
`CDLocateCheckSum` | 8 (0x8) | Exported Function | 0x00000001800018b0 | 0x000018b0
`CDGetIntegrityVect` | 6 (0x6) | Exported Function | 0x0000000180001350 | 0x00001350
`CDGenerateRandomBits` | 5 (0x5) | Exported Function | 0x0000000180001740 | 0x00001740
`CDFindCommonCSystemWithKey` | 4 (0x4) | Exported Function | 0x0000000180001690 | 0x00001690
`CDFindCommonCSystem` | 3 (0x3) | Exported Function | 0x0000000180001610 | 0x00001610
`CDBuildVect` | 2 (0x2) | Exported Function | 0x00000001800012a0 | 0x000012a0
`CDBuildIntegrityVect` | 1 (0x1) | Exported Function | 0x00000001800012e0 | 0x000012e0
`aesCTSEncryptMsg` | 20 (0x14) | Exported Function | 0x00000001800029a0 | 0x000029a0
`MD5Update` | 17 (0x11) | Exported Function | NTDLL.MD5Update | 0x0000d652
`PBKDF2` | 18 (0x12) | Exported Function | 0x0000000180001a50 | 0x00001a50


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


