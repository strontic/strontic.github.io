---
title: hbaapi.dll | HBA API data interface dll for HBA_API_Rev_2-18_2002MAR1.doc
excerpt: What is hbaapi.dll?
---

# hbaapi.dll 

* File Path: `C:\Windows\system32\hbaapi.dll`
* Description: HBA API data interface dll for HBA_API_Rev_2-18_2002MAR1.doc

## Hashes

Type | Hash
-- | --
MD5 | `665B26A43E6C12F7DC754BC1A3FC0421`
SHA1 | `74187A58F970F776BE22FBC721DDD38A6644615D`
SHA256 | `CEB8139599BD2ECCF416E16C0A604227B42FD21E99D404479816779C115E53CC`
SHA384 | `5F64F30591927544BBE80BBF5DF7173ADE0AB9F9B39E06FCBBAD6C4297EAECC230D170231B3129420BE56A235FA9266C`
SHA512 | `A51B3E5A44784D19798EF2BA74859BDDD0FD1B3F6817204D440408ED4928043613F3423990275C6E95354CAC91CD4EEFBE0ADF23A926D039485CE5ACBD12FA90`
SSDEEP | `1536:9/C5ueNr0ua5mwRK0gT2zudbj1EWyk3enIsUkNTmmtU+6x95/7HDv:MguQVRFzudPTeIQNT5HId7Hj`
IMP | `280BEEAD0BE75E854A8EC16890E9E9D7`
PESHA1 | `26BFA9D9FE25A889E0918A5010C7026E3E02F10D`
PE256 | `73D19296A9E9739F56FF6C537EB33B3DCBB41D146B7927E2F0E4FF7FD7457DB2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`HBA_CloseAdapter` | 1 (0x1) | Exported Function | 0x00000001800021a0 | 0x000021a0
`SMHBA_GetPersistentBinding` | 67 (0x43) | Exported Function | 0x000000018000bd00 | 0x0000bd00
`SMHBA_GetNumberOfPorts` | 66 (0x42) | Exported Function | 0x000000018000a6d0 | 0x0000a6d0
`SMHBA_GetLUNStatistics` | 65 (0x41) | Exported Function | 0x000000018000b7f0 | 0x0000b7f0
`SMHBA_GetFCPhyAttributes` | 64 (0x40) | Exported Function | 0x000000018000b540 | 0x0000b540
`SMHBA_GetDiscoveredPortAttributes` | 63 (0x3f) | Exported Function | 0x000000018000af90 | 0x0000af90
`SMHBA_GetBindingSupport` | 62 (0x3e) | Exported Function | 0x000000018000bae0 | 0x0000bae0
`SMHBA_GetBindingCapability` | 61 (0x3d) | Exported Function | 0x000000018000b9b0 | 0x0000b9b0
`SMHBA_GetAdapterPortAttributes` | 60 (0x3c) | Exported Function | 0x000000018000b3b0 | 0x0000b3b0
`SMHBA_GetAdapterAttributes` | 59 (0x3b) | Exported Function | 0x000000018000a720 | 0x0000a720
`HbaGetAdapterNameByDeviceInstanceId` | 58 (0x3a) | Exported Function | 0x0000000180001dd0 | 0x00001dd0
`HBA_SetRNIDMgmtInfo` | 57 (0x39) | Exported Function | 0x0000000180006300 | 0x00006300
`HBA_SetPersistentBindingV2` | 56 (0x38) | Exported Function | 0x0000000180009530 | 0x00009530
`HBA_SetBindingSupport` | 55 (0x37) | Exported Function | 0x0000000180008f20 | 0x00008f20
`HBA_SendSRL` | 53 (0x35) | Exported Function | 0x0000000180006a60 | 0x00006a60
`HBA_SendScsiInquiry` | 54 (0x36) | Exported Function | 0x000000018000dbf0 | 0x0000dbf0
`HBA_SendRPS` | 50 (0x32) | Exported Function | 0x0000000180006800 | 0x00006800
`HBA_SendRPL` | 49 (0x31) | Exported Function | 0x00000001800065a0 | 0x000065a0
`HBA_SendRNIDV2` | 48 (0x30) | Exported Function | 0x0000000180005ff0 | 0x00005ff0
`HBA_SendRNID` | 47 (0x2f) | Exported Function | 0x0000000180005e60 | 0x00005e60
`SMHBA_GetPhyStatistics` | 68 (0x44) | Exported Function | 0x000000018000ae30 | 0x0000ae30
`SMHBA_GetPortAttributesByWWN` | 69 (0x45) | Exported Function | 0x000000018000b100 | 0x0000b100
`SMHBA_GetPortType` | 70 (0x46) | Exported Function | 0x000000018000b270 | 0x0000b270
`SMHBA_GetProtocolStatistics` | 71 (0x47) | Exported Function | 0x000000018000a500 | 0x0000a500
`SMHBA_SendTEST` | 91 (0x5b) | Exported Function | 0x000000018000d110 | 0x0000d110
`SMHBA_SendSMPPassThru` | 90 (0x5a) | Exported Function | 0x000000018000d470 | 0x0000d470
`SMHBA_SendECHO` | 89 (0x59) | Exported Function | 0x000000018000d280 | 0x0000d280
`SMHBA_ScsiReportLuns` | 88 (0x58) | Exported Function | 0x000000018000cc10 | 0x0000cc10
`SMHBA_ScsiReadCapacity` | 87 (0x57) | Exported Function | 0x000000018000cea0 | 0x0000cea0
`SMHBA_ScsiInquiry` | 86 (0x56) | Exported Function | 0x000000018000c970 | 0x0000c970
`SMHBA_RemovePersistentBinding` | 85 (0x55) | Exported Function | 0x000000018000c4b0 | 0x0000c4b0
`SMHBA_RemoveAllPersistentBindings` | 84 (0x54) | Exported Function | 0x000000018000c830 | 0x0000c830
`SMHBA_RegisterLibrary` | 83 (0x53) | Exported Function | 0x0000000180008380 | 0x00008380
`HBA_SendRLS` | 46 (0x2e) | Exported Function | 0x0000000180006f10 | 0x00006f10
`SMHBA_RegisterForTargetEvents` | 82 (0x52) | Exported Function | 0x0000000180005270 | 0x00005270
`SMHBA_RegisterForAdapterPortEvents` | 80 (0x50) | Exported Function | 0x00000001800050c0 | 0x000050c0
`SMHBA_RegisterForAdapterPhyStatEvents` | 79 (0x4f) | Exported Function | 0x00000001800055e0 | 0x000055e0
`SMHBA_RegisterForAdapterEvents` | 78 (0x4e) | Exported Function | 0x0000000180005090 | 0x00005090
`SMHBA_RegisterForAdapterAddEvents` | 77 (0x4d) | Exported Function | 0x0000000180005060 | 0x00005060
`SMHBA_GetWrapperLibraryAttributes` | 76 (0x4c) | Exported Function | 0x000000018000a400 | 0x0000a400
`SMHBA_GetVersion` | 75 (0x4b) | Exported Function | 0x000000018000a3f0 | 0x0000a3f0
`SMHBA_GetVendorLibraryAttributes` | 74 (0x4a) | Exported Function | 0x000000018000a4f0 | 0x0000a4f0
`SMHBA_GetTargetMapping` | 73 (0x49) | Exported Function | 0x000000018000e6e0 | 0x0000e6e0
`SMHBA_GetSASPhyAttributes` | 72 (0x48) | Exported Function | 0x000000018000b6c0 | 0x0000b6c0
`SMHBA_RegisterForAdapterPortStatEvents` | 81 (0x51) | Exported Function | 0x0000000180005460 | 0x00005460
`SMHBA_SetBindingSupport` | 92 (0x5c) | Exported Function | 0x000000018000bc00 | 0x0000bc00
`HBA_SendReportLUNs` | 52 (0x34) | Exported Function | 0x000000018000de80 | 0x0000de80
`HBA_SendLIRR` | 45 (0x2d) | Exported Function | 0x0000000180006cb0 | 0x00006cb0
`HBA_GetVendorLibraryAttributes` | 20 (0x14) | Exported Function | 0x00000001800084a0 | 0x000084a0
`HBA_GetRNIDMgmtInfo` | 19 (0x13) | Exported Function | 0x0000000180006450 | 0x00006450
`HBA_GetPortStatistics` | 18 (0x12) | Exported Function | 0x0000000180008aa0 | 0x00008aa0
`HBA_GetPortAttributesByWWN` | 17 (0x11) | Exported Function | 0x0000000180005980 | 0x00005980
`HBA_GetPersistentBindingV2` | 16 (0x10) | Exported Function | 0x00000001800091e0 | 0x000091e0
`HBA_GetNumberOfAdapters` | 15 (0xf) | Exported Function | 0x00000001800021b0 | 0x000021b0
`HBA_GetFcpTargetMappingV2` | 14 (0xe) | Exported Function | 0x000000018000e370 | 0x0000e370
`HBA_GetFcpTargetMapping` | 13 (0xd) | Exported Function | 0x000000018000e1f0 | 0x0000e1f0
`HBA_GetFCPStatistics` | 11 (0xb) | Exported Function | 0x0000000180007280 | 0x00007280
`HBA_GetFcpPersistentBinding` | 12 (0xc) | Exported Function | 0x0000000180009010 | 0x00009010
`HBA_GetFC4Statistics` | 10 (0xa) | Exported Function | 0x0000000180007160 | 0x00007160
`HBA_GetEventBuffer` | 9 (0x9) | Exported Function | 0x00000001800073f0 | 0x000073f0
`HBA_GetDiscoveredPortAttributes` | 8 (0x8) | Exported Function | 0x0000000180005830 | 0x00005830
`HBA_GetBindingSupport` | 7 (0x7) | Exported Function | 0x0000000180008e30 | 0x00008e30
`HBA_GetBindingCapability` | 6 (0x6) | Exported Function | 0x0000000180008d40 | 0x00008d40
`HBA_GetAdapterPortAttributes` | 5 (0x5) | Exported Function | 0x00000001800088f0 | 0x000088f0
`HBA_GetAdapterName` | 4 (0x4) | Exported Function | 0x0000000180001f80 | 0x00001f80
`HBA_GetAdapterAttributes` | 3 (0x3) | Exported Function | 0x00000001800084b0 | 0x000084b0
`HBA_FreeLibrary` | 2 (0x2) | Exported Function | 0x0000000180008390 | 0x00008390
`HBA_GetVersion` | 21 (0x15) | Exported Function | 0x0000000180008380 | 0x00008380
`HBA_GetWrapperLibraryAttributes` | 22 (0x16) | Exported Function | 0x00000001800083a0 | 0x000083a0
`HBA_LoadLibrary` | 23 (0x17) | Exported Function | 0x0000000180008390 | 0x00008390
`HBA_OpenAdapter` | 24 (0x18) | Exported Function | 0x0000000180002010 | 0x00002010
`HBA_SendCTPassThruV2` | 44 (0x2c) | Exported Function | 0x0000000180005bd0 | 0x00005bd0
`HBA_SendCTPassThru` | 43 (0x2b) | Exported Function | 0x0000000180005b80 | 0x00005b80
`HBA_ScsiReportLUNsV2` | 42 (0x2a) | Exported Function | 0x000000018000dc70 | 0x0000dc70
`HBA_ScsiReadCapacityV2` | 41 (0x29) | Exported Function | 0x000000018000def0 | 0x0000def0
`HBA_ScsiInquiryV2` | 40 (0x28) | Exported Function | 0x000000018000d9b0 | 0x0000d9b0
`HBA_ResetStatistics` | 39 (0x27) | Exported Function | 0x0000000180006240 | 0x00006240
`HBA_RemovePersistentBinding` | 38 (0x26) | Exported Function | 0x00000001800097c0 | 0x000097c0
`HBA_RemoveCallback` | 37 (0x25) | Exported Function | 0x00000001800045a0 | 0x000045a0
`HBA_RemoveAllPersistentBindings` | 36 (0x24) | Exported Function | 0x0000000180009ad0 | 0x00009ad0
`HBA_SendReadCapacity` | 51 (0x33) | Exported Function | 0x000000018000e0f0 | 0x0000e0f0
`HBA_RegisterLibraryV2` | 35 (0x23) | Exported Function | 0x0000000180008380 | 0x00008380
`HBA_RegisterForTargetEvents` | 33 (0x21) | Exported Function | 0x0000000180004d50 | 0x00004d50
`HBA_RegisterForLinkEvents` | 32 (0x20) | Exported Function | 0x0000000180004ee0 | 0x00004ee0
`HBA_RegisterForAdapterPortStatEvents` | 31 (0x1f) | Exported Function | 0x0000000180004b90 | 0x00004b90
`HBA_RegisterForAdapterPortEvents` | 30 (0x1e) | Exported Function | 0x0000000180004a20 | 0x00004a20
`HBA_RegisterForAdapterEvents` | 29 (0x1d) | Exported Function | 0x0000000180004900 | 0x00004900
`HBA_RegisterForAdapterAddEvents` | 28 (0x1c) | Exported Function | 0x00000001800048d0 | 0x000048d0
`HBA_RefreshInformation` | 27 (0x1b) | Exported Function | 0x00000001800021d0 | 0x000021d0
`HBA_RefreshAdapterConfiguration` | 26 (0x1a) | Exported Function | 0x00000001800021c0 | 0x000021c0
`HBA_OpenAdapterByWWN` | 25 (0x19) | Exported Function | 0x00000001800020d0 | 0x000020d0
`HBA_RegisterLibrary` | 34 (0x22) | Exported Function | 0x0000000180008380 | 0x00008380
`SMHBA_SetPersistentBinding` | 93 (0x5d) | Exported Function | 0x000000018000c100 | 0x0000c100


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hbaapi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/ceb8139599bd2eccf416e16c0a604227b42fd21e99d404479816779c115e53cc/detection/





MIT License. Copyright (c) 2020 Strontic.


