---
title: mfc42.dll | MFCDLL Shared Library - Retail Version
excerpt: What is mfc42.dll?
---

# mfc42.dll 

* File Path: `C:\Windows\system32\mfc42.dll`
* Description: MFCDLL Shared Library - Retail Version

## Hashes

Type | Hash
-- | --
MD5 | `1E54CD09F2D1762B3F4369058DA3A217`
SHA1 | `D95BB96D13CEFB93E42C2151D58F5DF68A9E966D`
SHA256 | `5FD08C60FC0E5FBF1B367A4D6E27D5B078A331566BABCFDBF676C917F33A05B2`
SHA384 | `FB0E07BB8C0430068A0281D21861EF2549FA4AAC584E9B0328F9CD2AB0E3D51E6D655FC489AB1C918D1B94D9D6486299`
SHA512 | `C459381262D28267C5DD00E32B5D16006CCC6B35B21D6CA5F25A55125BFF1C1B1EB2B2F1683E7EE4822855954548D3F7BE042854776A01305413F0E675A1CDD3`
SSDEEP | `24576:jdWNOYQm2hiWMky4quvNPDLNhBjazbrXXMaA9lJvI:qOYQituvNPDNuzbrn29LQ`
IMP | `02CA6B246A6507957ED2F445F9DD2A2C`
PESHA1 | `3F237F437B88B6F9125AB4C417F2D8B1970DDDED`
PE256 | `034CFEB0167CA23ED3E27B818BA495301441CEC47D85B57D4F97EE62F85CDE42`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`struct HINSTANCE__ * __ptr64 __cdecl AfxLoadLibrary(char const * __ptr64)` | 1494 | Exported Function
`int __cdecl AfxFreeLibrary(struct HINSTANCE__ * __ptr64)` | 1452 | Exported Function
`void __cdecl AfxUnlockGlobals(int)` | 1587 | Exported Function
`void __cdecl AfxLockGlobals(int)` | 1497 | Exported Function
`DllGetClassObject` | 8 | Exported Function
`DllCanUnloadNow` | 7 | Exported Function
`DllUnregisterServer` | 10 | Exported Function
`DllRegisterServer` | 9 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MFC42.DLL.MUI
* Product Name: Microsoft (R) Visual C++
* Company Name: Microsoft Corporation
* File Version: 6.06.8063.0
* Product Version: 6.06.400
* Language: English (United States)
* Legal Copyright: Copyright (C) Microsoft Corp. 1993-2002
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/5fd08c60fc0e5fbf1b367a4d6e27d5b078a331566babcfdbf676c917f33a05b2/detection/


## Possible Misuse

*The following table contains possible examples of `mfc42.dll` being misused. While `mfc42.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poisonivy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poisonivy.yar) | $s11 = "MFC42.DLL" fullword ascii /* score: '-31' */ /* Goodware String - occured 36 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


