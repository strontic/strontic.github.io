---
title: winipcsecproc.dll | Microsoft Active Directory Rights Management Services Desktop Security Processor
excerpt: What is winipcsecproc.dll?
---

# winipcsecproc.dll 

* File Path: `C:\Windows\system32\winipcsecproc.dll`
* Description: Microsoft Active Directory Rights Management Services Desktop Security Processor

## Hashes

Type | Hash
-- | --
MD5 | `6FEB8889E35BAF2FEECA392C853C5ECC`
SHA1 | `07C10E689F0875961ECE596577CE6C5C51BCE65F`
SHA256 | `C4F2596A460817DB98F1E252FB3D681DC91D55799F2B9813E97CB36E8C5FFF9F`
SHA384 | `40F60FB390578375F673CA868CAEB1836A95E1A92E34297DFA44FE4D550E3CFB74497387B14D8AC2FED3E9C8251D67C6`
SHA512 | `349AF93E6909BC3C42987861D214195FC74B333CC10F33E4BDFF8F49C42678491D95283F7115A8218B3043CADE29C88B7614A94561978BCA2389527182C481C0`
SSDEEP | `24576:PBpZpO8qXiYNm/mRjeq+Mmowo7j6Bfrb:PLZp9oMQJAEj+fr`
IMP | `402CB0DFDAB8F09C9DCD4C31795C259B`
PESHA1 | `9E6BC15E575C60158CB23C995E17E453B5044AF4`
PE256 | `E919B867FF927ED56E2A80FE9665B6BBFD78B242D1A6859D8D212624597B7ADF`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`IpcSPAttest` | 1 (0x1) | Exported Function | 0x0000000180004260 | 0x00004260
`IpcSPIsActivated` | 26 (0x1a) | Exported Function | 0x0000000180006550 | 0x00006550
`IpcSPInitialize` | 25 (0x19) | Exported Function | 0x00000001800041a0 | 0x000041a0
`IpcSPGetProcAddress` | 24 (0x18) | Exported Function | 0x0000000180005c60 | 0x00005c60
`IpcSPGetInfo` | 23 (0x17) | Exported Function | 0x00000001800055c0 | 0x000055c0
`IpcSPGetCurrentTime` | 22 (0x16) | Exported Function | 0x0000000180005450 | 0x00005450
`IpcSPGetBoundRightKey` | 21 (0x15) | Exported Function | 0x0000000180006610 | 0x00006610
`IpcSPEncryptUpdate` | 20 (0x14) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPEncryptFinal` | 19 (0x13) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPEncrypt` | 18 (0x12) | Exported Function | 0x00000001800052c0 | 0x000052c0
`IpcSPEnablePublishingLicense` | 17 (0x11) | Exported Function | 0x0000000180005200 | 0x00005200
`IpcSPEnableAndEncrypt` | 16 (0x10) | Exported Function | 0x0000000180005eb0 | 0x00005eb0
`IpcSPDecryptWithRac` | 15 (0xf) | Exported Function | 0x0000000180005060 | 0x00005060
`IpcSPDecryptUpdate` | 14 (0xe) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPDecryptFinal` | 13 (0xd) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPDecrypt` | 12 (0xc) | Exported Function | 0x0000000180004ed0 | 0x00004ed0
`IpcSPCreateSecurityProcessor` | 11 (0xb) | Exported Function | 0x0000000180004c70 | 0x00004c70
`IpcSPCreatePCE` | 10 (0xa) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPCreateMachineCerts` | 9 (0x9) | Exported Function | 0x00000001800059c0 | 0x000059c0
`IpcSPCreateEncryptor` | 8 (0x8) | Exported Function | 0x0000000180004aa0 | 0x00004aa0
`IpcSPCreateEnablingPrincipal` | 7 (0x7) | Exported Function | 0x0000000180004880 | 0x00004880
`IpcSPCreateDecryptor` | 6 (0x6) | Exported Function | 0x00000001800046b0 | 0x000046b0
`IpcSPCommit` | 5 (0x5) | Exported Function | 0x00000001800046a0 | 0x000046a0
`IpcSPCloseHandle` | 4 (0x4) | Exported Function | 0x0000000180004600 | 0x00004600
`IpcSPCheckEnvironmentSecurity` | 3 (0x3) | Exported Function | 0x0000000180004690 | 0x00004690
`IpcSPBindLicense` | 2 (0x2) | Exported Function | 0x0000000180004420 | 0x00004420
`IpcSPLoadLibrary` | 27 (0x1b) | Exported Function | 0x0000000180005a80 | 0x00005a80
`IpcSPSign` | 28 (0x1c) | Exported Function | 0x0000000180005800 | 0x00005800


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ipcsecproc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/c4f2596a460817db98f1e252fb3d681dc91d55799f2b9813e97cb36e8c5fff9f/detection/





MIT License. Copyright (c) 2020 Strontic.


