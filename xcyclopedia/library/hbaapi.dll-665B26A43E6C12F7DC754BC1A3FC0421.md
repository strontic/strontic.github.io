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

Function Name | Ordinal | Type
-- | -- | --
`HBA_CloseAdapter` | 1 | Exported Function
`SMHBA_GetPersistentBinding` | 67 | Exported Function
`SMHBA_GetNumberOfPorts` | 66 | Exported Function
`SMHBA_GetLUNStatistics` | 65 | Exported Function
`SMHBA_GetFCPhyAttributes` | 64 | Exported Function
`SMHBA_GetDiscoveredPortAttributes` | 63 | Exported Function
`SMHBA_GetBindingSupport` | 62 | Exported Function
`SMHBA_GetBindingCapability` | 61 | Exported Function
`SMHBA_GetAdapterPortAttributes` | 60 | Exported Function
`SMHBA_GetAdapterAttributes` | 59 | Exported Function
`HbaGetAdapterNameByDeviceInstanceId` | 58 | Exported Function
`HBA_SetRNIDMgmtInfo` | 57 | Exported Function
`HBA_SetPersistentBindingV2` | 56 | Exported Function
`HBA_SetBindingSupport` | 55 | Exported Function
`HBA_SendSRL` | 53 | Exported Function
`HBA_SendScsiInquiry` | 54 | Exported Function
`HBA_SendRPS` | 50 | Exported Function
`HBA_SendRPL` | 49 | Exported Function
`HBA_SendRNIDV2` | 48 | Exported Function
`HBA_SendRNID` | 47 | Exported Function
`SMHBA_GetPhyStatistics` | 68 | Exported Function
`SMHBA_GetPortAttributesByWWN` | 69 | Exported Function
`SMHBA_GetPortType` | 70 | Exported Function
`SMHBA_GetProtocolStatistics` | 71 | Exported Function
`SMHBA_SendTEST` | 91 | Exported Function
`SMHBA_SendSMPPassThru` | 90 | Exported Function
`SMHBA_SendECHO` | 89 | Exported Function
`SMHBA_ScsiReportLuns` | 88 | Exported Function
`SMHBA_ScsiReadCapacity` | 87 | Exported Function
`SMHBA_ScsiInquiry` | 86 | Exported Function
`SMHBA_RemovePersistentBinding` | 85 | Exported Function
`SMHBA_RemoveAllPersistentBindings` | 84 | Exported Function
`SMHBA_RegisterLibrary` | 83 | Exported Function
`HBA_SendRLS` | 46 | Exported Function
`SMHBA_RegisterForTargetEvents` | 82 | Exported Function
`SMHBA_RegisterForAdapterPortEvents` | 80 | Exported Function
`SMHBA_RegisterForAdapterPhyStatEvents` | 79 | Exported Function
`SMHBA_RegisterForAdapterEvents` | 78 | Exported Function
`SMHBA_RegisterForAdapterAddEvents` | 77 | Exported Function
`SMHBA_GetWrapperLibraryAttributes` | 76 | Exported Function
`SMHBA_GetVersion` | 75 | Exported Function
`SMHBA_GetVendorLibraryAttributes` | 74 | Exported Function
`SMHBA_GetTargetMapping` | 73 | Exported Function
`SMHBA_GetSASPhyAttributes` | 72 | Exported Function
`SMHBA_RegisterForAdapterPortStatEvents` | 81 | Exported Function
`SMHBA_SetBindingSupport` | 92 | Exported Function
`HBA_SendReportLUNs` | 52 | Exported Function
`HBA_SendLIRR` | 45 | Exported Function
`HBA_GetVendorLibraryAttributes` | 20 | Exported Function
`HBA_GetRNIDMgmtInfo` | 19 | Exported Function
`HBA_GetPortStatistics` | 18 | Exported Function
`HBA_GetPortAttributesByWWN` | 17 | Exported Function
`HBA_GetPersistentBindingV2` | 16 | Exported Function
`HBA_GetNumberOfAdapters` | 15 | Exported Function
`HBA_GetFcpTargetMappingV2` | 14 | Exported Function
`HBA_GetFcpTargetMapping` | 13 | Exported Function
`HBA_GetFCPStatistics` | 11 | Exported Function
`HBA_GetFcpPersistentBinding` | 12 | Exported Function
`HBA_GetFC4Statistics` | 10 | Exported Function
`HBA_GetEventBuffer` | 9 | Exported Function
`HBA_GetDiscoveredPortAttributes` | 8 | Exported Function
`HBA_GetBindingSupport` | 7 | Exported Function
`HBA_GetBindingCapability` | 6 | Exported Function
`HBA_GetAdapterPortAttributes` | 5 | Exported Function
`HBA_GetAdapterName` | 4 | Exported Function
`HBA_GetAdapterAttributes` | 3 | Exported Function
`HBA_FreeLibrary` | 2 | Exported Function
`HBA_GetVersion` | 21 | Exported Function
`HBA_GetWrapperLibraryAttributes` | 22 | Exported Function
`HBA_LoadLibrary` | 23 | Exported Function
`HBA_OpenAdapter` | 24 | Exported Function
`HBA_SendCTPassThruV2` | 44 | Exported Function
`HBA_SendCTPassThru` | 43 | Exported Function
`HBA_ScsiReportLUNsV2` | 42 | Exported Function
`HBA_ScsiReadCapacityV2` | 41 | Exported Function
`HBA_ScsiInquiryV2` | 40 | Exported Function
`HBA_ResetStatistics` | 39 | Exported Function
`HBA_RemovePersistentBinding` | 38 | Exported Function
`HBA_RemoveCallback` | 37 | Exported Function
`HBA_RemoveAllPersistentBindings` | 36 | Exported Function
`HBA_SendReadCapacity` | 51 | Exported Function
`HBA_RegisterLibraryV2` | 35 | Exported Function
`HBA_RegisterForTargetEvents` | 33 | Exported Function
`HBA_RegisterForLinkEvents` | 32 | Exported Function
`HBA_RegisterForAdapterPortStatEvents` | 31 | Exported Function
`HBA_RegisterForAdapterPortEvents` | 30 | Exported Function
`HBA_RegisterForAdapterEvents` | 29 | Exported Function
`HBA_RegisterForAdapterAddEvents` | 28 | Exported Function
`HBA_RefreshInformation` | 27 | Exported Function
`HBA_RefreshAdapterConfiguration` | 26 | Exported Function
`HBA_OpenAdapterByWWN` | 25 | Exported Function
`HBA_RegisterLibrary` | 34 | Exported Function
`SMHBA_SetPersistentBinding` | 93 | Exported Function


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


