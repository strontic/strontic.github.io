---
title: bcrypt.dll | Windows Cryptographic Primitives Library
excerpt: What is bcrypt.dll?
---

# bcrypt.dll 

* File Path: `C:\Windows\system32\bcrypt.dll`
* Description: Windows Cryptographic Primitives Library

## Hashes

Type | Hash
-- | --
MD5 | `001E4599898EF88078E0AA8A5F0EC1A1`
SHA1 | `A55695066DEAF08A087B6934A5D1A5DF96B4C35F`
SHA256 | `0B212C340C47A0F107DFCB87E8CFACA799B08BDAE2B0EE0E07BB535FA3C29FF9`
SHA384 | `44E7B3E9F00DF3640614E229EED1989FB257E9CB762E2632BC4CCCC3121B7B7AD1DC5F2B67AB8C49D495B89C4D21781D`
SHA512 | `959FBE73054585E5320C61273039ACC9996A4DE4B5763BE1DDB0B944C3D579F0152266578AEBA51BFCFC46786BF34A8714CB5603811CD55AF97963472CC96045`
SSDEEP | `3072:rUiHWf4Z3eYJF1UwZKQMkdk6LgJumD3CuOS:rUiHWAZuYJMMK3ATgJTPOS`
IMP | `E5649DCD6FA9472DB9A89CCD123913C0`
PESHA1 | `CC246A51880963E73AD3352A3ED266580049E8D2`
PE256 | `8EA6051C6F068DFA81D364AF61F3B81177A44F3C604997902344524D080AA40C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BCryptAddContextFunction` | 1 (0x1) | Exported Function | 0x00000001800150d0 | 0x000150d0
`BCryptGenRandom` | 30 (0x1e) | Exported Function | 0x0000000180003070 | 0x00003070
`BCryptGetFipsAlgorithmMode` | 33 (0x21) | Exported Function | 0x0000000180006510 | 0x00006510
`BCryptGetProperty` | 34 (0x22) | Exported Function | 0x0000000180003e90 | 0x00003e90
`BCryptHash` | 35 (0x23) | Exported Function | 0x00000001800035e0 | 0x000035e0
`BCryptHashData` | 36 (0x24) | Exported Function | 0x0000000180003810 | 0x00003810
`BCryptImportKey` | 37 (0x25) | Exported Function | 0x0000000180002c10 | 0x00002c10
`BCryptImportKeyPair` | 38 (0x26) | Exported Function | 0x0000000180001010 | 0x00001010
`BCryptKeyDerivation` | 39 (0x27) | Exported Function | 0x00000001800018c0 | 0x000018c0
`BCryptOpenAlgorithmProvider` | 40 (0x28) | Exported Function | 0x00000001800051e0 | 0x000051e0
`BCryptProcessMultiOperations` | 41 (0x29) | Exported Function | 0x000000018000e800 | 0x0000e800
`BCryptQueryContextConfiguration` | 42 (0x2a) | Exported Function | 0x0000000180016a60 | 0x00016a60
`BCryptQueryContextFunctionConfiguration` | 43 (0x2b) | Exported Function | 0x0000000180016df0 | 0x00016df0
`BCryptQueryContextFunctionProperty` | 44 (0x2c) | Exported Function | 0x00000001800171f0 | 0x000171f0
`BCryptQueryProviderRegistration` | 45 (0x2d) | Exported Function | 0x0000000180007750 | 0x00007750
`BCryptRegisterConfigChangeNotify` | 46 (0x2e) | Exported Function | 0x0000000180007f30 | 0x00007f30
`BCryptRegisterProvider` | 47 (0x2f) | Exported Function | 0x0000000180017640 | 0x00017640
`BCryptRemoveContextFunction` | 48 (0x30) | Exported Function | 0x0000000180017a10 | 0x00017a10
`BCryptRemoveContextFunctionProvider` | 49 (0x31) | Exported Function | 0x0000000180017d80 | 0x00017d80
`BCryptResolveProviders` | 50 (0x32) | Exported Function | 0x0000000180004ce0 | 0x00004ce0
`BCryptSecretAgreement` | 51 (0x33) | Exported Function | 0x0000000180002410 | 0x00002410
`BCryptSetAuditingInterface` | 52 (0x34) | Exported Function | 0x0000000180008160 | 0x00008160
`BCryptSetContextFunctionProperty` | 53 (0x35) | Exported Function | 0x0000000180018110 | 0x00018110
`BCryptSetProperty` | 54 (0x36) | Exported Function | 0x0000000180002f20 | 0x00002f20
`BCryptSignHash` | 55 (0x37) | Exported Function | 0x0000000180006d00 | 0x00006d00
`BCryptUnregisterConfigChangeNotify` | 56 (0x38) | Exported Function | 0x00000001800184c0 | 0x000184c0
`BCryptGenerateSymmetricKey` | 32 (0x20) | Exported Function | 0x0000000180003bf0 | 0x00003bf0
`BCryptGenerateKeyPair` | 31 (0x1f) | Exported Function | 0x0000000180002550 | 0x00002550
`BCryptFreeBuffer` | 29 (0x1d) | Exported Function | 0x0000000180003370 | 0x00003370
`BCryptFinishHash` | 28 (0x1c) | Exported Function | 0x0000000180003760 | 0x00003760
`BCryptAddContextFunctionProvider` | 2 (0x2) | Exported Function | 0x0000000180015440 | 0x00015440
`BCryptCloseAlgorithmProvider` | 3 (0x3) | Exported Function | 0x0000000180002da0 | 0x00002da0
`BCryptConfigureContext` | 4 (0x4) | Exported Function | 0x00000001800157e0 | 0x000157e0
`BCryptConfigureContextFunction` | 5 (0x5) | Exported Function | 0x0000000180015b30 | 0x00015b30
`BCryptCreateContext` | 6 (0x6) | Exported Function | 0x0000000180015ea0 | 0x00015ea0
`BCryptCreateHash` | 7 (0x7) | Exported Function | 0x00000001800038b0 | 0x000038b0
`BCryptCreateMultiHash` | 8 (0x8) | Exported Function | 0x000000018000dc00 | 0x0000dc00
`BCryptDecrypt` | 9 (0x9) | Exported Function | 0x00000001800019b0 | 0x000019b0
`BCryptDeleteContext` | 10 (0xa) | Exported Function | 0x00000001800161f0 | 0x000161f0
`BCryptDeriveKey` | 11 (0xb) | Exported Function | 0x0000000180002300 | 0x00002300
`BCryptDeriveKeyCapi` | 12 (0xc) | Exported Function | 0x00000001800033d0 | 0x000033d0
`BCryptDeriveKeyPBKDF2` | 13 (0xd) | Exported Function | 0x0000000180007140 | 0x00007140
`BCryptUnregisterProvider` | 57 (0x39) | Exported Function | 0x0000000180018590 | 0x00018590
`BCryptDestroyHash` | 14 (0xe) | Exported Function | 0x0000000180003680 | 0x00003680
`BCryptDestroySecret` | 16 (0x10) | Exported Function | 0x0000000180002690 | 0x00002690
`BCryptDuplicateHash` | 17 (0x11) | Exported Function | 0x0000000180001760 | 0x00001760
`BCryptDuplicateKey` | 18 (0x12) | Exported Function | 0x000000018000de20 | 0x0000de20
`BCryptEncrypt` | 19 (0x13) | Exported Function | 0x00000001800015b0 | 0x000015b0
`BCryptEnumAlgorithms` | 20 (0x14) | Exported Function | 0x000000018000e060 | 0x0000e060
`BCryptEnumContextFunctionProviders` | 21 (0x15) | Exported Function | 0x0000000180007c30 | 0x00007c30
`BCryptEnumContextFunctions` | 22 (0x16) | Exported Function | 0x0000000180007530 | 0x00007530
`BCryptEnumContexts` | 23 (0x17) | Exported Function | 0x0000000180016530 | 0x00016530
`BCryptEnumProviders` | 24 (0x18) | Exported Function | 0x000000018000e4a0 | 0x0000e4a0
`BCryptEnumRegisteredProviders` | 25 (0x19) | Exported Function | 0x0000000180016810 | 0x00016810
`BCryptExportKey` | 26 (0x1a) | Exported Function | 0x0000000180001220 | 0x00001220
`BCryptFinalizeKeyPair` | 27 (0x1b) | Exported Function | 0x0000000180002760 | 0x00002760
`BCryptDestroyKey` | 15 (0xf) | Exported Function | 0x0000000180006a50 | 0x00006a50
`BCryptVerifySignature` | 58 (0x3a) | Exported Function | 0x00000001800027f0 | 0x000027f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bcrypt.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/0b212c340c47a0f107dfcb87e8cfaca799b08bdae2b0ee0e07bb535fa3c29ff9/detection/





MIT License. Copyright (c) 2020 Strontic.


