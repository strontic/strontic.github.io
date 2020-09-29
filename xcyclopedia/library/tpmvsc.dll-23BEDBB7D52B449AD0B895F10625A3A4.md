---
title: tpmvsc.dll | Microsoft TPM Virtual Smart Card
excerpt: What is tpmvsc.dll?
---

# tpmvsc.dll 

* File Path: `C:\Windows\system32\tpmvsc.dll`
* Description: Microsoft TPM Virtual Smart Card

## Hashes

Type | Hash
-- | --
MD5 | `23BEDBB7D52B449AD0B895F10625A3A4`
SHA1 | `085F2FB76C251693945297CF391B796872048BE0`
SHA256 | `C23698E9E03506EBD4D51C625B9A306722101D0F60092C67D444695A9D837A31`
SHA384 | `B1F96ED9D80C7E9604D2A06154C3B096108E101141651529EF97E607B480D3760B412930A534A454B5CC917DCB0BB50D`
SHA512 | `C6469E10B6AF3FCE3220EC5B24AFB133CA22ECE1886A00F0A70C49440004A9F3F29085DCF73EDC45F4C34F15CE2E3A8EEEF3D253F7F443CF734FC9C37521D630`
SSDEEP | `6144:mlbB/gVb8y6AEszDCz0qopEE+aCaVlI2pVorGF5RTohYBlZU6PI:iB/eFezropVc2pVfToKZ`
IMP | `4AC8E64055DFB25BA50178336266041B`
PESHA1 | `58F5577A2FA0E7DC8F17B4EADAD3EF8A00ED246E`
PE256 | `63D50656E881FA0A4ADB8F5EB84E65025CF5126E2DD1E3449FC42D6C2867020C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x000000018001b500 | 0x0001b500
`VCardGetAikCertificate` | 21 (0x15) | Exported Function | 0x0000000180031dd0 | 0x00031dd0
`VCardGetAikContainerName` | 22 (0x16) | Exported Function | 0x0000000180031f70 | 0x00031f70
`VCardGetChallenge` | 23 (0x17) | Exported Function | 0x000000018002e3c0 | 0x0002e3c0
`VCardGetKeyType` | 24 (0x18) | Exported Function | 0x0000000180030830 | 0x00030830
`VCardGetPinLength` | 25 (0x19) | Exported Function | 0x000000018002f000 | 0x0002f000
`VCardGetRemainingRetryCount` | 26 (0x1a) | Exported Function | 0x000000018002f190 | 0x0002f190
`VCardGetTransportKeyAlg` | 27 (0x1b) | Exported Function | 0x000000018002fa90 | 0x0002fa90
`VCardImportRsaKey` | 28 (0x1c) | Exported Function | 0x000000018002fb80 | 0x0002fb80
`VCardImportSymKey` | 29 (0x1d) | Exported Function | 0x00000001800301a0 | 0x000301a0
`VCardInitialize` | 30 (0x1e) | Exported Function | 0x000000018002d9b0 | 0x0002d9b0
`VCardInvalidateChallenge` | 31 (0x1f) | Exported Function | 0x000000018002e950 | 0x0002e950
`VCardOpen` | 32 (0x20) | Exported Function | 0x000000018002dce0 | 0x0002dce0
`VCardOpenChannel` | 33 (0x21) | Exported Function | 0x000000018002e080 | 0x0002e080
`VCardResetPin` | 34 (0x22) | Exported Function | 0x000000018002f660 | 0x0002f660
`VCardSetResponse` | 35 (0x23) | Exported Function | 0x000000018002e790 | 0x0002e790
`VCardExportRsaPubKey` | 20 (0x14) | Exported Function | 0x00000001800309b0 | 0x000309b0
`VCardSignHash` | 36 (0x24) | Exported Function | 0x00000001800315c0 | 0x000315c0
`VCardEncrypt` | 19 (0x13) | Exported Function | 0x0000000180030d60 | 0x00030d60
`VCardDeinitialize` | 17 (0x11) | Exported Function | 0x000000018002db20 | 0x0002db20
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x000000018001b620 | 0x0001b620
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x000000018001b770 | 0x0001b770
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x000000018001b8e0 | 0x0001b8e0
`TpmVCardCreate` | 5 (0x5) | Exported Function | 0x00000001800323c0 | 0x000323c0
`TpmVCardCreateInProc` | 6 (0x6) | Exported Function | 0x00000001800328a0 | 0x000328a0
`TpmVCardDestroy` | 7 (0x7) | Exported Function | 0x0000000180032d70 | 0x00032d70
`TpmVCardDestroyInProc` | 8 (0x8) | Exported Function | 0x0000000180032f50 | 0x00032f50
`VCardAuthenticatePin` | 9 (0x9) | Exported Function | 0x000000018002ead0 | 0x0002ead0
`VCardChangePin` | 10 (0xa) | Exported Function | 0x000000018002f330 | 0x0002f330
`VCardClose` | 11 (0xb) | Exported Function | 0x000000018002dec0 | 0x0002dec0
`VCardCloseChannel` | 12 (0xc) | Exported Function | 0x000000018002e260 | 0x0002e260
`VCardCreateClaim` | 13 (0xd) | Exported Function | 0x00000001800319f0 | 0x000319f0
`VCardCreateKey` | 14 (0xe) | Exported Function | 0x000000018002f7f0 | 0x0002f7f0
`VCardDeauthenticate` | 15 (0xf) | Exported Function | 0x000000018002eea0 | 0x0002eea0
`VCardDecrypt` | 16 (0x10) | Exported Function | 0x0000000180031190 | 0x00031190
`VCardDeleteKey` | 18 (0x12) | Exported Function | 0x0000000180030650 | 0x00030650
`VCardUnblockPin` | 37 (0x25) | Exported Function | 0x000000018002f4d0 | 0x0002f4d0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tpmvsc.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/c23698e9e03506ebd4d51c625b9a306722101d0f60092c67d444695a9d837a31/detection/





MIT License. Copyright (c) 2020 Strontic.


