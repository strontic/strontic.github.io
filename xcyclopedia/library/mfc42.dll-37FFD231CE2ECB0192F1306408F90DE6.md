---
title: mfc42.dll | MFCDLL Shared Library - Retail Version
excerpt: What is mfc42.dll?
---

# mfc42.dll 

* File Path: `C:\Windows\SysWOW64\mfc42.dll`
* Description: MFCDLL Shared Library - Retail Version

## Hashes

Type | Hash
-- | --
MD5 | `37FFD231CE2ECB0192F1306408F90DE6`
SHA1 | `16A6D984BD83F1085DC83B9725059403FE8AD7EF`
SHA256 | `FBE6BCA89EBB72C9BE2498C4E84F2767467A4846395A8B6B74BEA3DE669200DF`
SHA384 | `E486D777F2C2E2CD059E66F1A26EBE0D81EF65E7C6B1512E5CF149B272295F1E03360317FB1331319C630E53E1D0C3E6`
SHA512 | `16F15FA76D000BD41C1F9591E38489C37BECF04685251237D9A99847F62582C34353A74A12D355AEBD3ECF9B172A8B71E230FBF0135D536A11DF51E61877F83C`
SSDEEP | `24576:0Dv3nwWAF6i5IpsryyRvac0sRcdoJRoKC2vtWRCKAe:C3nIF6im8vaXs4oJaKkCKZ`
IMP | `7A5A818C87F0262A305407568CE32C7D`
PESHA1 | `51D631E30A5F6480B1DB4D79E1F81079D3D5D773`
PE256 | `4FD07282C6630A9DA3D592FAC0EEC05AF2AC662054523257C22E44A6D1EBD5AC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 7 | Exported Function
`DllGetClassObject` | 8 | Exported Function
`DllRegisterServer` | 9 | Exported Function
`DllUnregisterServer` | 10 | Exported Function
`CCachedDataPathProperty::classCCachedDataPathProperty` | 5 | Exported Function
`CDataPathProperty::classCDataPathProperty` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MFC42.DLL
* Product Name: Microsoft (R) Visual C++
* Company Name: Microsoft Corporation
* File Version: 6.06.8063.0
* Product Version: 6.06.400
* Language: English (United States)
* Legal Copyright: Copyright (C) Microsoft Corp. 1993-2002
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/fbe6bca89ebb72c9be2498c4e84f2767467a4846395a8b6b74bea3de669200df/detection/


## Possible Misuse

*The following table contains possible examples of `mfc42.dll` being misused. While `mfc42.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s11 = "MFC42.DLL" fullword ascii /* score: '-31' */ /* Goodware String - occured 36 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


