---
title: wevtapi.dll | Eventing Consumption and Configuration API
excerpt: What is wevtapi.dll?
---

# wevtapi.dll 

* File Path: `C:\Windows\SysWOW64\wevtapi.dll`
* Description: Eventing Consumption and Configuration API

## Hashes

Type | Hash
-- | --
MD5 | `242C77077405305295308319527B9EE9`
SHA1 | `FF42ADE0170F7B1256AF0DE2425477EC821B951E`
SHA256 | `76680F5A1166DFF888DA051192C0FC16EDA5CF2CC34B241C3F22A3F14805B6AC`
SHA384 | `BA3F274B3C0C0FEE54123E304A79B1A9C8BBAEFF983A663B278785770FBDB69FFFDD7ED6A6D1CCAD456A76ACB7034E82`
SHA512 | `DC59FA6942D41366FCD1E82532DDE17B8A70414A2B70C6100EC0B76E3200D8DBE8F3EFE6F6DC8C88D5F040D8F273BBD567F3877EA4368F4A3D52825ABF1337AF`
SSDEEP | `6144:egfjDrdCm3UvBWOyFS5jJ9BtMIWRTGhtJ5foXmT+6s7w2x8v:LjDAm3UkrS59P0T4T5fzT27w2xs`
IMP | `E3D7AE7AB3152F3647BBFA118EF216E5`
PESHA1 | `D20C5CA7F6074BE3FDE3A4249F3E2F9443A21156`
PE256 | `3C9C4CE44628440E8CE13A4A230491B37B38FDDB3AAE1989B98B362FA73CE251`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EvtArchiveExportedLog` | 2 (0x2) | Exported Function | 0x10029360 | 0x00029360
`EvtIntRetractConfig` | 26 (0x1a) | Exported Function | 0x1002c3a0 | 0x0002c3a0
`EvtIntSysprepCleanup` | 1 (0x1) | Exported Function | 0x1002b170 | 0x0002b170
`EvtIntWriteXmlEventToLocalLogfile` | 27 (0x1b) | Exported Function | 0x1002c4f0 | 0x0002c4f0
`EvtNext` | 28 (0x1c) | Exported Function | 0x1000a630 | 0x0000a630
`EvtNextChannelPath` | 29 (0x1d) | Exported Function | 0x1002a280 | 0x0002a280
`EvtNextEventMetadata` | 30 (0x1e) | Exported Function | 0x1002a330 | 0x0002a330
`EvtNextPublisherId` | 31 (0x1f) | Exported Function | 0x1002a450 | 0x0002a450
`EvtOpenChannelConfig` | 32 (0x20) | Exported Function | 0x10013860 | 0x00013860
`EvtOpenChannelEnum` | 33 (0x21) | Exported Function | 0x1002a500 | 0x0002a500
`EvtOpenEventMetadataEnum` | 34 (0x22) | Exported Function | 0x1002a670 | 0x0002a670
`EvtOpenLog` | 35 (0x23) | Exported Function | 0x1002a780 | 0x0002a780
`EvtOpenPublisherEnum` | 36 (0x24) | Exported Function | 0x1002a910 | 0x0002a910
`EvtOpenPublisherMetadata` | 37 (0x25) | Exported Function | 0x10010580 | 0x00010580
`EvtOpenSession` | 38 (0x26) | Exported Function | 0x10013be0 | 0x00013be0
`EvtQuery` | 39 (0x27) | Exported Function | 0x10008c30 | 0x00008c30
`EvtRender` | 40 (0x28) | Exported Function | 0x1000abc0 | 0x0000abc0
`EvtSaveChannelConfig` | 41 (0x29) | Exported Function | 0x1002aa80 | 0x0002aa80
`EvtSeek` | 42 (0x2a) | Exported Function | 0x10008020 | 0x00008020
`EvtSetChannelConfigProperty` | 43 (0x2b) | Exported Function | 0x1002ab60 | 0x0002ab60
`EvtIntReportEventAndSourceAsync` | 25 (0x19) | Exported Function | ntdll.EvtIntReportEventAndSourceAsync | 0x0003eb9f
`EvtSubscribe` | 44 (0x2c) | Exported Function | 0x10009740 | 0x00009740
`EvtIntReportAuthzEventAndSourceAsync` | 24 (0x18) | Exported Function | ntdll.EvtIntReportAuthzEventAndSourceAsync | 0x0003eb54
`EvtIntGetClassicLogDisplayName` | 22 (0x16) | Exported Function | 0x1002bae0 | 0x0002bae0
`EvtCancel` | 3 (0x3) | Exported Function | 0x100294b0 | 0x000294b0
`EvtClearLog` | 4 (0x4) | Exported Function | 0x100295c0 | 0x000295c0
`EvtClose` | 5 (0x5) | Exported Function | 0x1000edd0 | 0x0000edd0
`EvtCreateBookmark` | 6 (0x6) | Exported Function | 0x100102c0 | 0x000102c0
`EvtCreateRenderContext` | 7 (0x7) | Exported Function | 0x1000ef10 | 0x0000ef10
`EvtExportLog` | 8 (0x8) | Exported Function | 0x10029750 | 0x00029750
`EvtFormatMessage` | 9 (0x9) | Exported Function | 0x10010b30 | 0x00010b30
`EvtGetChannelConfigProperty` | 10 (0xa) | Exported Function | 0x10013dd0 | 0x00013dd0
`EvtGetEventInfo` | 11 (0xb) | Exported Function | 0x100299a0 | 0x000299a0
`EvtGetEventMetadataProperty` | 12 (0xc) | Exported Function | 0x10029a50 | 0x00029a50
`EvtGetExtendedStatus` | 13 (0xd) | Exported Function | 0x10029b50 | 0x00029b50
`EvtGetLogInfo` | 14 (0xe) | Exported Function | 0x10029b70 | 0x00029b70
`EvtGetObjectArrayProperty` | 15 (0xf) | Exported Function | 0x10029c20 | 0x00029c20
`EvtGetObjectArraySize` | 16 (0x10) | Exported Function | 0x10029d10 | 0x00029d10
`EvtGetPublisherMetadataProperty` | 17 (0x11) | Exported Function | 0x10029db0 | 0x00029db0
`EvtGetQueryInfo` | 18 (0x12) | Exported Function | 0x10029eb0 | 0x00029eb0
`EvtIntAssertConfig` | 19 (0x13) | Exported Function | 0x10010320 | 0x00010320
`EvtIntCreateBinXMLFromCustomXML` | 20 (0x14) | Exported Function | 0x1002b9a0 | 0x0002b9a0
`EvtIntCreateLocalLogfile` | 21 (0x15) | Exported Function | 0x1002b9d0 | 0x0002b9d0
`EvtIntRenderResourceEventTemplate` | 23 (0x17) | Exported Function | 0x1002be70 | 0x0002be70
`EvtUpdateBookmark` | 45 (0x2d) | Exported Function | 0x10008810 | 0x00008810


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wevtapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/76680f5a1166dff888da051192c0fc16eda5cf2cc34b241c3f22a3f14805b6ac/detection/





MIT License. Copyright (c) 2020 Strontic.


