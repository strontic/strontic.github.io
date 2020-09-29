---
title: cemapi.dll | CEMAPI
excerpt: What is cemapi.dll?
---

# cemapi.dll 

* File Path: `C:\Windows\system32\cemapi.dll`
* Description: CEMAPI

## Hashes

Type | Hash
-- | --
MD5 | `0B701AF9B83BFF148563517A17644FBB`
SHA1 | `0C185DB0C73C6BD8018AF51A11D1F4A14F95A6EF`
SHA256 | `A4F12A2AFBBB76FAE65EDA4CEC6C7ED6FC19442F4DCFCF85C78732F68473B729`
SHA384 | `FFAD394EF386E9ED6082D874467637CBE9BED29357658A751C2FE9715C51E25501B2A60C87B65C74F98EF7B899D0867B`
SHA512 | `AA40DDCAAE0674E134D4F20AA9E44EB06BF20177DF60E2254AE9C200731E983ED923798F0A2B410089F761573A6F15EC03ABED27E58431A780C6FE0D91ACFF0C`
SSDEEP | `3072:kjD1W1ZNsOsRomila/Nw6Yo+Z6WSKxxFuRkeKMIT1u5Qh6xKuB7ncoVnyAcpSi+G:mD1W1ZNoomPyk9i6tUJN3pS`
IMP | `4F5DDEC9A2E951D2941F0FBEBE171033`
PESHA1 | `96C9E52709B1A01F973595152CED7BCA3DB028E4`
PE256 | `DAD6C9A54C064F0A5AFBF0D2990A176AC2A250BB8669CF707D8B8B284AE1DAF9`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateMAPITableWalker` | 63 (0x3f) | Exported Function | 0x0000000180009bc0 | 0x00009bc0
`TranslateSPlusV1MessageClassToV2` | 62 (0x3e) | Exported Function | 0x0000000180006f50 | 0x00006f50
`SetConversationId` | 83 (0x53) | Exported Function | 0x00000001800085a0 | 0x000085a0
`ReadMailVolumeNameEx` | 82 (0x52) | Exported Function | 0x0000000180007890 | 0x00007890
`MAPIUninitialize` | 80 (0x50) | Exported Function | 0x000000018000bfa0 | 0x0000bfa0
`MAPILogonEx` | 79 (0x4f) | Exported Function | 0x000000018000c080 | 0x0000c080
`MAPIInitialize` | 78 (0x4e) | Exported Function | 0x000000018000c040 | 0x0000c040
`MAPIGetContext` | 77 (0x4d) | Exported Function | 0x0000000180007b20 | 0x00007b20
`MAPIFreeBuffer` | 76 (0x4c) | Exported Function | 0x000000018000a2d0 | 0x0000a2d0
`MAPIDupString` | 75 (0x4b) | Exported Function | 0x00000001800094c0 | 0x000094c0
`MAPIDeleteMessageById` | 74 (0x4a) | Exported Function | 0x00000001800088c0 | 0x000088c0
`MAPIAllocateMore_dbg` | 53 (0x35) | Exported Function | 0x000000018000a380 | 0x0000a380
`MAPIAllocateMore` | 73 (0x49) | Exported Function | 0x000000018000a1b0 | 0x0000a1b0
`MAPIAllocateBuffer_dbg` | 52 (0x34) | Exported Function | 0x000000018000a390 | 0x0000a390
`MAPIAllocateBuffer` | 72 (0x48) | Exported Function | 0x000000018000a100 | 0x0000a100
`MAPI_GetStoreByName` | 81 (0x51) | Exported Function | 0x0000000180009060 | 0x00009060
`MAPI_CompareEntryIDs` | 61 (0x3d) | Exported Function | 0x00000001800071a0 | 0x000071a0
`IsMessageClassSPlusV2` | 60 (0x3c) | Exported Function | 0x0000000180006fe0 | 0x00006fe0
`CreateMAPITableWalkerEx` | 64 (0x40) | Exported Function | 0x0000000180009bf0 | 0x00009bf0
`FlushMailStore` | 65 (0x41) | Exported Function | 0x00000001800078e0 | 0x000078e0
`FreeProws` | 66 (0x42) | Exported Function | 0x0000000180009f70 | 0x00009f70
`GetEntryIDType` | 67 (0x43) | Exported Function | 0x00000001800095a0 | 0x000095a0
`GetMAPIStorePropTags` | 54 (0x36) | Exported Function | 0x0000000180006790 | 0x00006790
`GetMsgClassEnum` | 55 (0x37) | Exported Function | 0x0000000180006d20 | 0x00006d20
`USOIDfromCEENTRYID` | 84 (0x54) | Exported Function | 0x0000000180008cb0 | 0x00008cb0
`GetMsgClassEnumFromMsg` | 56 (0x38) | Exported Function | 0x0000000180006da0 | 0x00006da0
`GetNamedPropTag` | 69 (0x45) | Exported Function | 0x00000001800093c0 | 0x000093c0
`HrGetOneProp` | 70 (0x46) | Exported Function | 0x000000018000bc60 | 0x0000bc60
`HrSetOneProp` | 71 (0x47) | Exported Function | 0x000000018000bd60 | 0x0000bd60
`InitializeServiceProps` | 57 (0x39) | Exported Function | 0x0000000180007080 | 0x00007080
`IsMessageClassDeviceGenerated` | 58 (0x3a) | Exported Function | 0x0000000180006ef0 | 0x00006ef0
`IsMessageClassReadRequest` | 59 (0x3b) | Exported Function | 0x0000000180006e20 | 0x00006e20
`GetMsgStoreFromMessage` | 68 (0x44) | Exported Function | 0x00000001800092d0 | 0x000092d0
`USOIDtoCEENTRYID` | 85 (0x55) | Exported Function | 0x0000000180008c20 | 0x00008c20


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CEMAPI.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a4f12a2afbbb76fae65eda4cec6c7ed6fc19442f4dcfcf85c78732f68473b729/detection/





MIT License. Copyright (c) 2020 Strontic.


