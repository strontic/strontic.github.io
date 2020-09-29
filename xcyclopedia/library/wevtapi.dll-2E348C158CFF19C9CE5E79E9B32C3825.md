---
title: wevtapi.dll | Eventing Consumption and Configuration API
excerpt: What is wevtapi.dll?
---

# wevtapi.dll 

* File Path: `C:\Windows\system32\wevtapi.dll`
* Description: Eventing Consumption and Configuration API

## Hashes

Type | Hash
-- | --
MD5 | `2E348C158CFF19C9CE5E79E9B32C3825`
SHA1 | `32CC26E16B9D5A90DE232043001862CD4B28116A`
SHA256 | `2EAA6C7F08331BC24CAE6F68D5E99BA0050AB293D9B8FC935074E1E0D9758F5F`
SHA384 | `D0B3DC51077258BEB2699176420A66934C3CBD60254934D6F9A93739E7FFCC0102E51DE29CBA100E275D12DA52740168`
SHA512 | `F330629A1E5F09068F9B3BAFCD90E0A5C0C44F3ADEC4AEDE340E0944306AD021EFBFFEF00B67C83467AF868ED3BB72AFA4003DCBEB12F9FCEEB66BCBDF91A35B`
SSDEEP | `12288:VnZzc5OKRG8Sb45I7oqmKHJklpNTxyedsx:VZzeOaSb45IssJklpNTLsx`
IMP | `3DF6EFE26236BC1B0D866E5BCCEEB49C`
PESHA1 | `F3ECEEC388F3D4590F4B35C2FEA09316FF806224`
PE256 | `87669D18A694B8932C48860B2EDA90775A6354DD33D6D6ECEC627949D44B491C`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EvtArchiveExportedLog` | 2 (0x2) | Exported Function | 0x000000018002ae90 | 0x0002ae90
`EvtIntRetractConfig` | 26 (0x1a) | Exported Function | 0x0000000180002140 | 0x00002140
`EvtIntSysprepCleanup` | 1 (0x1) | Exported Function | 0x000000018002cf80 | 0x0002cf80
`EvtIntWriteXmlEventToLocalLogfile` | 27 (0x1b) | Exported Function | 0x000000018002e140 | 0x0002e140
`EvtNext` | 28 (0x1c) | Exported Function | 0x0000000180004be0 | 0x00004be0
`EvtNextChannelPath` | 29 (0x1d) | Exported Function | 0x0000000180011fb0 | 0x00011fb0
`EvtNextEventMetadata` | 30 (0x1e) | Exported Function | 0x000000018002c130 | 0x0002c130
`EvtNextPublisherId` | 31 (0x1f) | Exported Function | 0x0000000180011ef0 | 0x00011ef0
`EvtOpenChannelConfig` | 32 (0x20) | Exported Function | 0x0000000180006750 | 0x00006750
`EvtOpenChannelEnum` | 33 (0x21) | Exported Function | 0x0000000180011700 | 0x00011700
`EvtOpenEventMetadataEnum` | 34 (0x22) | Exported Function | 0x000000018002c300 | 0x0002c300
`EvtOpenLog` | 35 (0x23) | Exported Function | 0x00000001800107a0 | 0x000107a0
`EvtOpenPublisherEnum` | 36 (0x24) | Exported Function | 0x0000000180011860 | 0x00011860
`EvtOpenPublisherMetadata` | 37 (0x25) | Exported Function | 0x0000000180005740 | 0x00005740
`EvtOpenSession` | 38 (0x26) | Exported Function | 0x0000000180001890 | 0x00001890
`EvtQuery` | 39 (0x27) | Exported Function | 0x000000018000abb0 | 0x0000abb0
`EvtRender` | 40 (0x28) | Exported Function | 0x0000000180002280 | 0x00002280
`EvtSaveChannelConfig` | 41 (0x29) | Exported Function | 0x000000018002c4c0 | 0x0002c4c0
`EvtSeek` | 42 (0x2a) | Exported Function | 0x000000018000c200 | 0x0000c200
`EvtSetChannelConfigProperty` | 43 (0x2b) | Exported Function | 0x000000018002c620 | 0x0002c620
`EvtIntReportEventAndSourceAsync` | 25 (0x19) | Exported Function | ntdll.EvtIntReportEventAndSourceAsync | 0x00058f3f
`EvtSubscribe` | 44 (0x2c) | Exported Function | 0x000000018000afd0 | 0x0000afd0
`EvtIntReportAuthzEventAndSourceAsync` | 24 (0x18) | Exported Function | ntdll.EvtIntReportAuthzEventAndSourceAsync | 0x00058ef4
`EvtIntGetClassicLogDisplayName` | 22 (0x16) | Exported Function | 0x0000000180012d10 | 0x00012d10
`EvtCancel` | 3 (0x3) | Exported Function | 0x000000018002b0f0 | 0x0002b0f0
`EvtClearLog` | 4 (0x4) | Exported Function | 0x000000018002b270 | 0x0002b270
`EvtClose` | 5 (0x5) | Exported Function | 0x0000000180006a40 | 0x00006a40
`EvtCreateBookmark` | 6 (0x6) | Exported Function | 0x000000018000c340 | 0x0000c340
`EvtCreateRenderContext` | 7 (0x7) | Exported Function | 0x0000000180005b20 | 0x00005b20
`EvtExportLog` | 8 (0x8) | Exported Function | 0x000000018002b4e0 | 0x0002b4e0
`EvtFormatMessage` | 9 (0x9) | Exported Function | 0x000000018000f210 | 0x0000f210
`EvtGetChannelConfigProperty` | 10 (0xa) | Exported Function | 0x000000018000ca40 | 0x0000ca40
`EvtGetEventInfo` | 11 (0xb) | Exported Function | 0x000000018002b890 | 0x0002b890
`EvtGetEventMetadataProperty` | 12 (0xc) | Exported Function | 0x000000018002b9a0 | 0x0002b9a0
`EvtGetExtendedStatus` | 13 (0xd) | Exported Function | 0x000000018002bb50 | 0x0002bb50
`EvtGetLogInfo` | 14 (0xe) | Exported Function | 0x000000018000fa50 | 0x0000fa50
`EvtGetObjectArrayProperty` | 15 (0xf) | Exported Function | 0x0000000180010c70 | 0x00010c70
`EvtGetObjectArraySize` | 16 (0x10) | Exported Function | 0x0000000180012640 | 0x00012640
`EvtGetPublisherMetadataProperty` | 17 (0x11) | Exported Function | 0x000000018000e6e0 | 0x0000e6e0
`EvtGetQueryInfo` | 18 (0x12) | Exported Function | 0x000000018002bb70 | 0x0002bb70
`EvtIntAssertConfig` | 19 (0x13) | Exported Function | 0x000000018000d950 | 0x0000d950
`EvtIntCreateBinXMLFromCustomXML` | 20 (0x14) | Exported Function | 0x000000018002d990 | 0x0002d990
`EvtIntCreateLocalLogfile` | 21 (0x15) | Exported Function | 0x000000018002d9e0 | 0x0002d9e0
`EvtIntRenderResourceEventTemplate` | 23 (0x17) | Exported Function | 0x000000018002db90 | 0x0002db90
`EvtUpdateBookmark` | 45 (0x2d) | Exported Function | 0x0000000180002850 | 0x00002850


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wevtapi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/2eaa6c7f08331bc24cae6f68d5e99ba0050ab293d9b8fc935074e1e0d9758f5f/detection/





MIT License. Copyright (c) 2020 Strontic.


