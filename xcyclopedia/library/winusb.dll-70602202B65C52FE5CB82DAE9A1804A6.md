---
title: winusb.dll | Windows USB Driver User Library
excerpt: What is winusb.dll?
---

# winusb.dll 

* File Path: `C:\Windows\system32\winusb.dll`
* Description: Windows USB Driver User Library

## Hashes

Type | Hash
-- | --
MD5 | `70602202B65C52FE5CB82DAE9A1804A6`
SHA1 | `E5E976C7471CD571EFC52B1EE06F38A97DB9A91C`
SHA256 | `ED473BD48C7704E96CFC258047FCDD3F601B778A22C778C349A1AA936CB0295E`
SHA384 | `B6EBC0EB5A6745A8997386B4DC9AA83AC915C642FBFE470403F1A991ECF2D1070BA27BFF4E81AA74431571918E67E88E`
SHA512 | `F688DE44A2E6B6A941C90DEE9243DA31AC014878F78C4A6CDB60FB671AF628ECC5C344BC72087E18F44E52EA8BF403034ADEF13B83B29612A8C9D8EE9E0B3278`
SSDEEP | `384:dYq3++VpCHsYGIDmSHs0vfQPeYyz4+inwJMdAOCySN3iCfw2As1OhGuqf91elYcb:Gg+Sol4sE525/8Ae6qbeHP9`
IMP | `C5B956863D4784EC1EA3704CEC6BDE37`
PESHA1 | `7DA9B9C4BA5D6ED643CC7D0A7E3613FCF2E960FE`
PE256 | `E5BF8384C82E2ED5ADB97C36662F1D4197C5D7004BE1254753C00DF0D157B3CB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WinUsb_AbortPipe` | 1 (0x1) | Exported Function | 0x00000001800033a0 | 0x000033a0
`WinUsb_QueryPipeEx` | 21 (0x15) | Exported Function | 0x0000000180001210 | 0x00001210
`WinUsb_ReadIsochPipe` | 22 (0x16) | Exported Function | 0x0000000180004180 | 0x00004180
`WinUsb_ReadIsochPipeAsap` | 23 (0x17) | Exported Function | 0x0000000180004130 | 0x00004130
`WinUsb_ReadPipe` | 24 (0x18) | Exported Function | 0x0000000180002c00 | 0x00002c00
`WinUsb_RegisterIsochBuffer` | 25 (0x19) | Exported Function | 0x0000000180003800 | 0x00003800
`WinUsb_ResetPipe` | 26 (0x1a) | Exported Function | 0x0000000180003230 | 0x00003230
`WinUsb_ResetPipeAsync` | 27 (0x1b) | Exported Function | 0x00000001800031b0 | 0x000031b0
`WinUsb_SetCurrentAlternateSetting` | 28 (0x1c) | Exported Function | 0x0000000180002270 | 0x00002270
`WinUsb_SetCurrentAlternateSettingAsync` | 29 (0x1d) | Exported Function | 0x0000000180002130 | 0x00002130
`WinUsb_SetPipePolicy` | 30 (0x1e) | Exported Function | 0x0000000180002580 | 0x00002580
`WinUsb_SetPowerPolicy` | 31 (0x1f) | Exported Function | 0x00000001800028c0 | 0x000028c0
`WinUsb_StartTrackingForTimeSync` | 32 (0x20) | Exported Function | 0x00000001800041d0 | 0x000041d0
`WinUsb_StopTrackingForTimeSync` | 33 (0x21) | Exported Function | 0x0000000180004470 | 0x00004470
`WinUsb_UnregisterIsochBuffer` | 34 (0x22) | Exported Function | 0x00000001800039b0 | 0x000039b0
`WinUsb_WriteIsochPipe` | 35 (0x23) | Exported Function | 0x0000000180003da0 | 0x00003da0
`WinUsb_QueryPipe` | 20 (0x14) | Exported Function | 0x0000000180002480 | 0x00002480
`WinUsb_WriteIsochPipeAsap` | 36 (0x24) | Exported Function | 0x0000000180003d70 | 0x00003d70
`WinUsb_QueryInterfaceSettings` | 19 (0x13) | Exported Function | 0x0000000180001de0 | 0x00001de0
`WinUsb_ParseDescriptors` | 17 (0x11) | Exported Function | 0x0000000180001010 | 0x00001010
`WinUsb_AbortPipeAsync` | 2 (0x2) | Exported Function | 0x0000000180003320 | 0x00003320
`WinUsb_ControlTransfer` | 3 (0x3) | Exported Function | 0x0000000180002fa0 | 0x00002fa0
`WinUsb_FlushPipe` | 4 (0x4) | Exported Function | 0x0000000180003490 | 0x00003490
`WinUsb_Free` | 5 (0x5) | Exported Function | 0x0000000180001b00 | 0x00001b00
`WinUsb_GetAdjustedFrameNumber` | 6 (0x6) | Exported Function | 0x0000000180003760 | 0x00003760
`WinUsb_GetAssociatedInterface` | 7 (0x7) | Exported Function | 0x0000000180001be0 | 0x00001be0
`WinUsb_GetCurrentAlternateSetting` | 8 (0x8) | Exported Function | 0x0000000180002360 | 0x00002360
`WinUsb_GetCurrentFrameNumber` | 9 (0x9) | Exported Function | 0x0000000180003600 | 0x00003600
`WinUsb_GetCurrentFrameNumberAndQpc` | 10 (0xa) | Exported Function | 0x0000000180004320 | 0x00004320
`WinUsb_GetDescriptor` | 11 (0xb) | Exported Function | 0x0000000180001fc0 | 0x00001fc0
`WinUsb_GetOverlappedResult` | 12 (0xc) | Exported Function | 0x00000001800035c0 | 0x000035c0
`WinUsb_GetPipePolicy` | 13 (0xd) | Exported Function | 0x0000000180002750 | 0x00002750
`WinUsb_GetPowerPolicy` | 14 (0xe) | Exported Function | 0x0000000180002aa0 | 0x00002aa0
`WinUsb_Initialize` | 15 (0xf) | Exported Function | 0x00000001800013a0 | 0x000013a0
`WinUsb_ParseConfigurationDescriptor` | 16 (0x10) | Exported Function | 0x0000000180001080 | 0x00001080
`WinUsb_QueryDeviceInformation` | 18 (0x12) | Exported Function | 0x0000000180001e80 | 0x00001e80
`WinUsb_WritePipe` | 37 (0x25) | Exported Function | 0x0000000180002dd0 | 0x00002dd0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winusb.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/ed473bd48c7704e96cfc258047fcdd3f601b778a22c778c349a1aa936cb0295e/detection/





MIT License. Copyright (c) 2020 Strontic.


