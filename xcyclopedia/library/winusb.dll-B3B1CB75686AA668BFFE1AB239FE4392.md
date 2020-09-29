---
title: winusb.dll | Windows USB Driver User Library
excerpt: What is winusb.dll?
---

# winusb.dll 

* File Path: `C:\Windows\SysWOW64\winusb.dll`
* Description: Windows USB Driver User Library

## Hashes

Type | Hash
-- | --
MD5 | `B3B1CB75686AA668BFFE1AB239FE4392`
SHA1 | `5B9C8A3E51D1054AEC90C1CB5DF9467B8DB53E13`
SHA256 | `DDE44C27C640F9C72D316B3E3B3C464B8674332EBF812135A5071F00D6F70FB1`
SHA384 | `B0CFDB26DADD69BE4C65B4B9527A3600709DC833382B248098A6CB301CAB7D41DB103699C8819D932F27115971828385`
SHA512 | `46162AE5F9A757118A9F57146BA475FE0A7AE933C9A22844D9793262A331405961DACDD445548C546EF03F1A8A41315F0A99B8929EB2825A234746ECFE710C56`
SSDEEP | `384:vjaAGWIrQcEbCySM/2WWWHmu6SNMEaRH4xAe6jIy9Ic0cHzWudWZS:vOAGWIrQ9CyfB3dAe6jIMI0HNM`
IMP | `FEB82DB03CBDCB91A517C429439BBCB0`
PESHA1 | `EA9FE3C35C41BA0BFAC62211CA5551338803E968`
PE256 | `6AADDB401C80E170DF29313091A3E807325FC234DECECEDCC00780EFA8B5A3BB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`WinUsb_AbortPipe` | 1 (0x1) | Exported Function | 0x10002ee0 | 0x00002ee0
`WinUsb_QueryPipeEx` | 21 (0x15) | Exported Function | 0x100015d0 | 0x000015d0
`WinUsb_ReadIsochPipe` | 22 (0x16) | Exported Function | 0x10003a80 | 0x00003a80
`WinUsb_ReadIsochPipeAsap` | 23 (0x17) | Exported Function | 0x10003a50 | 0x00003a50
`WinUsb_ReadPipe` | 24 (0x18) | Exported Function | 0x100028f0 | 0x000028f0
`WinUsb_RegisterIsochBuffer` | 25 (0x19) | Exported Function | 0x100032c0 | 0x000032c0
`WinUsb_ResetPipe` | 26 (0x1a) | Exported Function | 0x10002d90 | 0x00002d90
`WinUsb_ResetPipeAsync` | 27 (0x1b) | Exported Function | 0x10002d00 | 0x00002d00
`WinUsb_SetCurrentAlternateSetting` | 28 (0x1c) | Exported Function | 0x10002200 | 0x00002200
`WinUsb_SetCurrentAlternateSettingAsync` | 29 (0x1d) | Exported Function | 0x100020d0 | 0x000020d0
`WinUsb_SetPipePolicy` | 30 (0x1e) | Exported Function | 0x10002450 | 0x00002450
`WinUsb_SetPowerPolicy` | 31 (0x1f) | Exported Function | 0x100026a0 | 0x000026a0
`WinUsb_StartTrackingForTimeSync` | 32 (0x20) | Exported Function | 0x10003ab0 | 0x00003ab0
`WinUsb_StopTrackingForTimeSync` | 33 (0x21) | Exported Function | 0x10003c90 | 0x00003c90
`WinUsb_UnregisterIsochBuffer` | 34 (0x22) | Exported Function | 0x10003420 | 0x00003420
`WinUsb_WriteIsochPipe` | 35 (0x23) | Exported Function | 0x10003770 | 0x00003770
`WinUsb_QueryPipe` | 20 (0x14) | Exported Function | 0x10002390 | 0x00002390
`WinUsb_WriteIsochPipeAsap` | 36 (0x24) | Exported Function | 0x10003740 | 0x00003740
`WinUsb_QueryInterfaceSettings` | 19 (0x13) | Exported Function | 0x10001e80 | 0x00001e80
`WinUsb_ParseDescriptors` | 17 (0x11) | Exported Function | 0x10001440 | 0x00001440
`WinUsb_AbortPipeAsync` | 2 (0x2) | Exported Function | 0x10002e50 | 0x00002e50
`WinUsb_ControlTransfer` | 3 (0x3) | Exported Function | 0x10002b90 | 0x00002b90
`WinUsb_FlushPipe` | 4 (0x4) | Exported Function | 0x10002fa0 | 0x00002fa0
`WinUsb_Free` | 5 (0x5) | Exported Function | 0x10001c50 | 0x00001c50
`WinUsb_GetAdjustedFrameNumber` | 6 (0x6) | Exported Function | 0x10003200 | 0x00003200
`WinUsb_GetAssociatedInterface` | 7 (0x7) | Exported Function | 0x10001cd0 | 0x00001cd0
`WinUsb_GetCurrentAlternateSetting` | 8 (0x8) | Exported Function | 0x100022c0 | 0x000022c0
`WinUsb_GetCurrentFrameNumber` | 9 (0x9) | Exported Function | 0x10003100 | 0x00003100
`WinUsb_GetCurrentFrameNumberAndQpc` | 10 (0xa) | Exported Function | 0x10003ba0 | 0x00003ba0
`WinUsb_GetDescriptor` | 11 (0xb) | Exported Function | 0x10001fd0 | 0x00001fd0
`WinUsb_GetOverlappedResult` | 12 (0xc) | Exported Function | 0x10003080 | 0x00003080
`WinUsb_GetPipePolicy` | 13 (0xd) | Exported Function | 0x100025a0 | 0x000025a0
`WinUsb_GetPowerPolicy` | 14 (0xe) | Exported Function | 0x100027f0 | 0x000027f0
`WinUsb_Initialize` | 15 (0xf) | Exported Function | 0x10001720 | 0x00001720
`WinUsb_ParseConfigurationDescriptor` | 16 (0x10) | Exported Function | 0x100014a0 | 0x000014a0
`WinUsb_QueryDeviceInformation` | 18 (0x12) | Exported Function | 0x10001ef0 | 0x00001ef0
`WinUsb_WritePipe` | 37 (0x25) | Exported Function | 0x10002a40 | 0x00002a40


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/dde44c27c640f9c72d316b3e3b3c464b8674332ebf812135a5071f00d6f70fb1/detection/





MIT License. Copyright (c) 2020 Strontic.


