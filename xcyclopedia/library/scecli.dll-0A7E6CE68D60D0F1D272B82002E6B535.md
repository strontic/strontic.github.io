---
title: scecli.dll | Windows Security Configuration Editor Client Engine
excerpt: What is scecli.dll?
---

# scecli.dll 

* File Path: `C:\Windows\system32\scecli.dll`
* Description: Windows Security Configuration Editor Client Engine

## Hashes

Type | Hash
-- | --
MD5 | `0A7E6CE68D60D0F1D272B82002E6B535`
SHA1 | `68822F87590FBB57E9C7C35E43FC204512912879`
SHA256 | `C27C201DF01753AC06609F240CDB8168D3ADC2918A9B4C1D8E1AF06A9AE6A36A`
SHA384 | `FD8D03A8FB38FE8EAC5745BCD6CD60903BF65B92D73C8BF2711BB734DA2745CCCAFF211538C26383AF930156B289BDD1`
SHA512 | `728821DA5AAC1A8A1FB5206BBD59CD5FFAF99546B39FDA93FCEE0CD5BA5A6E5B8BA1941B0F601401DEFC25BB9BF2015F4B79B159BC6A1F1F821559A0BCB6DADA`
SSDEEP | `6144:a93xcDICt14bHtuZo5dK+iPLiylWku2KEsDtZkVcN3VuvcDKdlUvjRB2f:c3xcDLytXUsDtZkcR2f`
IMP | `09F43C674C9460AB7919063533181685`
PESHA1 | `1484B8832DC713438E9B471DB5C8259E283B6406`
PE256 | `BE21D01BF8E6B6A0E50652D1F328EFB835F6B7F676C02475A03CC1CF6190B945`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ConvertSecurityDescriptorToText` | 1 (0x1) | Exported Function | 0x00000001800151d0 | 0x000151d0
`SceSetupRootSecurity` | 56 (0x38) | Exported Function | 0x0000000180036790 | 0x00036790
`SceSetupMoveSecurityFile` | 55 (0x37) | Exported Function | 0x0000000180036660 | 0x00036660
`SceSetupGenerateTemplate` | 54 (0x36) | Exported Function | 0x00000001800364b0 | 0x000364b0
`SceSetupConfigureServices` | 53 (0x35) | Exported Function | 0x0000000180036390 | 0x00036390
`SceSetupBackupSecurity` | 52 (0x34) | Exported Function | 0x0000000180035a30 | 0x00035a30
`SceSetDatabaseSetting` | 51 (0x33) | Exported Function | 0x0000000180030cf0 | 0x00030cf0
`SceRollbackTransaction` | 50 (0x32) | Exported Function | 0x0000000180030c80 | 0x00030c80
`SceRegisterRegValues` | 49 (0x31) | Exported Function | 0x00000001800307c0 | 0x000307c0
`SceProcessSecurityPolicyGPOEx` | 9 (0x9) | Exported Function | 0x00000001800264a0 | 0x000264a0
`SceProcessSecurityPolicyGPO` | 8 (0x8) | Exported Function | 0x0000000180026290 | 0x00026290
`SceOpenProfile` | 48 (0x30) | Exported Function | 0x0000000180030560 | 0x00030560
`SceOpenPolicy` | 7 (0x7) | Exported Function | 0x0000000180029060 | 0x00029060
`SceNotifyPolicyDelta` | 6 (0x6) | Exported Function | 0x0000000180028fb0 | 0x00028fb0
`SceLookupPrivRightName` | 47 (0x2f) | Exported Function | 0x0000000180014b80 | 0x00014b80
`SceIsSystemDatabase` | 46 (0x2e) | Exported Function | 0x0000000180011720 | 0x00011720
`SceSetupSystemByInfName` | 57 (0x39) | Exported Function | 0x0000000180037160 | 0x00037160
`SceGetTimeStamp` | 45 (0x2d) | Exported Function | 0x0000000180030170 | 0x00030170
`SceSetupUnwindSecurityFile` | 58 (0x3a) | Exported Function | 0x0000000180037960 | 0x00037960
`SceSetupUpdateSecurityKey` | 60 (0x3c) | Exported Function | 0x0000000180037ba0 | 0x00037ba0
`SceWrapperExportSecurityProfile` | 73 (0x49) | Exported Function | 0x00000001800385d0 | 0x000385d0
`SceUpdateSecurityProfile` | 72 (0x48) | Exported Function | 0x0000000180031120 | 0x00031120
`SceUpdateObjectInfo` | 71 (0x47) | Exported Function | 0x0000000180030ec0 | 0x00030ec0
`SceSysPrepOffline` | 11 (0xb) | Exported Function | 0x0000000180032760 | 0x00032760
`SceSysPrep` | 10 (0xa) | Exported Function | 0x0000000180032590 | 0x00032590
`SceSvcUpdateInfo` | 70 (0x46) | Exported Function | 0x0000000180030e30 | 0x00030e30
`SceSvcSetInformationTemplate` | 69 (0x45) | Exported Function | 0x0000000180021a20 | 0x00021a20
`SceSvcSetInfo` | 68 (0x44) | Exported Function | 0x00000001800383d0 | 0x000383d0
`SceSvcQueryInfo` | 67 (0x43) | Exported Function | 0x00000001800381a0 | 0x000381a0
`SceSvcGetInformationTemplate` | 66 (0x42) | Exported Function | 0x000000018001d000 | 0x0001d000
`SceSvcFree` | 65 (0x41) | Exported Function | 0x0000000180038190 | 0x00038190
`SceSvcConvertTextToSD` | 64 (0x40) | Exported Function | 0x0000000180038170 | 0x00038170
`SceSvcConvertSDToText` | 63 (0x3f) | Exported Function | 0x0000000180038150 | 0x00038150
`SceStartTransaction` | 62 (0x3e) | Exported Function | 0x0000000180030dc0 | 0x00030dc0
`SceSetupUpdateSecurityService` | 61 (0x3d) | Exported Function | 0x0000000180037f60 | 0x00037f60
`SceSetupUpdateSecurityFile` | 59 (0x3b) | Exported Function | 0x0000000180037aa0 | 0x00037aa0
`SceWrapperImportSecurityProfile` | 74 (0x4a) | Exported Function | 0x0000000180038650 | 0x00038650
`SceGetServerProductType` | 44 (0x2c) | Exported Function | 0x0000000180030090 | 0x00030090
`SceGetScpProfileDescription` | 42 (0x2a) | Exported Function | 0x000000018002fcd0 | 0x0002fcd0
`SceConfigureConvertedFileSecurity` | 4 (0x4) | Exported Function | 0x0000000180032080 | 0x00032080
`SceCompareSecurityDescriptors` | 23 (0x17) | Exported Function | 0x00000001800147f0 | 0x000147f0
`SceCompareNameList` | 22 (0x16) | Exported Function | 0x0000000180014730 | 0x00014730
`SceCommitTransaction` | 21 (0x15) | Exported Function | 0x000000018002ee60 | 0x0002ee60
`SceCloseProfile` | 20 (0x14) | Exported Function | 0x000000018002ed90 | 0x0002ed90
`SceBrowseDatabaseTable` | 19 (0x13) | Exported Function | 0x000000018002eb90 | 0x0002eb90
`SceAppendSecurityProfileInfo` | 18 (0x12) | Exported Function | 0x00000001800219f0 | 0x000219f0
`SceAnalyzeSystem` | 17 (0x11) | Exported Function | 0x000000018002e890 | 0x0002e890
`SceAddToObjectList` | 16 (0x10) | Exported Function | 0x0000000180014700 | 0x00014700
`SceAddToNameStatusList` | 15 (0xf) | Exported Function | 0x00000001800146f0 | 0x000146f0
`SceAddToNameList` | 14 (0xe) | Exported Function | 0x00000001800146d0 | 0x000146d0
`InitializeChangeNotify` | 3 (0x3) | Exported Function | 0x0000000180001700 | 0x00001700
`DllUnregisterServer` | 13 (0xd) | Exported Function | 0x0000000180031df0 | 0x00031df0
`DllRegisterServer` | 12 (0xc) | Exported Function | 0x00000001800317d0 | 0x000317d0
`DeltaNotify` | 2 (0x2) | Exported Function | 0x0000000180028e30 | 0x00028e30
`SceConfigureSystem` | 24 (0x18) | Exported Function | 0x000000018002eed0 | 0x0002eed0
`SceGetSecurityProfileInfo` | 43 (0x2b) | Exported Function | 0x000000018002fd60 | 0x0002fd60
`SceCopyBaseProfile` | 25 (0x19) | Exported Function | 0x000000018002f0c0 | 0x0002f0c0
`SceDcPromoCreateGPOsInSysvol` | 27 (0x1b) | Exported Function | 0x00000001800355b0 | 0x000355b0
`SceGetObjectSecurity` | 41 (0x29) | Exported Function | 0x000000018002fbe0 | 0x0002fbe0
`SceGetObjectChildren` | 40 (0x28) | Exported Function | 0x000000018002fac0 | 0x0002fac0
`SceGetDbTime` | 39 (0x27) | Exported Function | 0x000000018002f8e0 | 0x0002f8e0
`SceGetDatabaseSetting` | 38 (0x26) | Exported Function | 0x000000018002f7a0 | 0x0002f7a0
`SceGetAreas` | 37 (0x25) | Exported Function | 0x0000000180028ba0 | 0x00028ba0
`SceGetAnalysisAreaSummary` | 36 (0x24) | Exported Function | 0x000000018002f720 | 0x0002f720
`SceGenerateRollback` | 35 (0x23) | Exported Function | 0x000000018002f500 | 0x0002f500
`SceGenerateGroupPolicy` | 5 (0x5) | Exported Function | 0x0000000180024f60 | 0x00024f60
`SceFreeProfileMemory` | 34 (0x22) | Exported Function | 0x0000000180012970 | 0x00012970
`SceFreeMemory` | 33 (0x21) | Exported Function | 0x0000000180012390 | 0x00012390
`SceEnumerateServices` | 32 (0x20) | Exported Function | 0x0000000180014880 | 0x00014880
`SceEnforceSecurityPolicyPropagation` | 31 (0x1f) | Exported Function | 0x0000000180035a20 | 0x00035a20
`SceDcPromoteSecurityEx` | 30 (0x1e) | Exported Function | 0x0000000180035900 | 0x00035900
`SceDcPromoteSecurity` | 29 (0x1d) | Exported Function | 0x00000001800358e0 | 0x000358e0
`SceDcPromoCreateGPOsInSysvolEx` | 28 (0x1c) | Exported Function | 0x00000001800355e0 | 0x000355e0
`SceCreateDirectory` | 26 (0x1a) | Exported Function | 0x0000000180014870 | 0x00014870
`SceWriteSecurityProfileInfo` | 75 (0x4b) | Exported Function | 0x0000000180021c00 | 0x00021c00


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: scecli
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/c27c201df01753ac06609f240cdb8168d3adc2918a9b4c1d8e1af06a9ae6a36a/detection/





MIT License. Copyright (c) 2020 Strontic.


