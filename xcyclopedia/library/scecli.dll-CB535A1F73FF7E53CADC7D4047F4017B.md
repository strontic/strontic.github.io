---
title: scecli.dll | Windows Security Configuration Editor Client Engine
excerpt: What is scecli.dll?
---

# scecli.dll 

* File Path: `C:\Windows\SysWOW64\scecli.dll`
* Description: Windows Security Configuration Editor Client Engine

## Hashes

Type | Hash
-- | --
MD5 | `CB535A1F73FF7E53CADC7D4047F4017B`
SHA1 | `72611B34D5A7B3DF56676324FD3E1358F2703F5B`
SHA256 | `B16EAFC25630AB974DAFEE09F4DE86CA297EE83A32E3BA19C67A03D2B15146A7`
SHA384 | `2CF92866EE53567DADAC04B9EB29B0D9132EDC9B1145EF86EC31EDF03319E5E7BC7EE0BAD2F44F2E7B6EBCEA33AF872D`
SHA512 | `F8B66226448840CCB68AEA83CB0157B17536A55CE3908DC49AF2E49B0478A03268071F081E28BAEBF66D9CEA803A95003491B34146960B5D08AB4C6CC4E41BC7`
SSDEEP | `6144:54hHa5PL3JOZBTrBUmXkPN4vpbDlsPP7fTY5k:5+HA3nPN4RY7fGk`
IMP | `68A3AA11EA11FF56B9AAC8E318AD1B3B`
PESHA1 | `4810AD64CB1016EA13AD6E6DE7A19AE4167AEE09`
PE256 | `E3462A875FC07D28E1940EE8C47A5068C7B75DB207A67A3E4EA1B9AC34FA89AE`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`ConvertSecurityDescriptorToText` | 1 (0x1) | Exported Function | 0x5fd19700 | 0x00019700
`SceSetupRootSecurity` | 56 (0x38) | Exported Function | 0x5fd32570 | 0x00032570
`SceSetupMoveSecurityFile` | 55 (0x37) | Exported Function | 0x5fd32490 | 0x00032490
`SceSetupGenerateTemplate` | 54 (0x36) | Exported Function | 0x5fd32360 | 0x00032360
`SceSetupConfigureServices` | 53 (0x35) | Exported Function | 0x5fd32280 | 0x00032280
`SceSetupBackupSecurity` | 52 (0x34) | Exported Function | 0x5fd31aa0 | 0x00031aa0
`SceSetDatabaseSetting` | 51 (0x33) | Exported Function | 0x5fd2e050 | 0x0002e050
`SceRollbackTransaction` | 50 (0x32) | Exported Function | 0x5fd2dfd0 | 0x0002dfd0
`SceRegisterRegValues` | 49 (0x31) | Exported Function | 0x5fd2dc10 | 0x0002dc10
`SceProcessSecurityPolicyGPOEx` | 9 (0x9) | Exported Function | 0x5fd25e20 | 0x00025e20
`SceProcessSecurityPolicyGPO` | 8 (0x8) | Exported Function | 0x5fd25cc0 | 0x00025cc0
`SceOpenProfile` | 48 (0x30) | Exported Function | 0x5fd2da40 | 0x0002da40
`SceOpenPolicy` | 7 (0x7) | Exported Function | 0x5fd27e00 | 0x00027e00
`SceNotifyPolicyDelta` | 6 (0x6) | Exported Function | 0x5fd27d70 | 0x00027d70
`SceLookupPrivRightName` | 47 (0x2f) | Exported Function | 0x5fd192b0 | 0x000192b0
`SceIsSystemDatabase` | 46 (0x2e) | Exported Function | 0x5fd16a30 | 0x00016a30
`SceSetupSystemByInfName` | 57 (0x39) | Exported Function | 0x5fd32bc0 | 0x00032bc0
`SceGetTimeStamp` | 45 (0x2d) | Exported Function | 0x5fd2d7d0 | 0x0002d7d0
`SceSetupUnwindSecurityFile` | 58 (0x3a) | Exported Function | 0x5fd33280 | 0x00033280
`SceSetupUpdateSecurityKey` | 60 (0x3c) | Exported Function | 0x5fd33420 | 0x00033420
`SceWrapperExportSecurityProfile` | 73 (0x49) | Exported Function | 0x5fd33c30 | 0x00033c30
`SceUpdateSecurityProfile` | 72 (0x48) | Exported Function | 0x5fd2e3b0 | 0x0002e3b0
`SceUpdateObjectInfo` | 71 (0x47) | Exported Function | 0x5fd2e210 | 0x0002e210
`SceSysPrepOffline` | 11 (0xb) | Exported Function | 0x5fd2f4b0 | 0x0002f4b0
`SceSysPrep` | 10 (0xa) | Exported Function | 0x5fd2f320 | 0x0002f320
`SceSvcUpdateInfo` | 70 (0x46) | Exported Function | 0x5fd2e180 | 0x0002e180
`SceSvcSetInformationTemplate` | 69 (0x45) | Exported Function | 0x5fd22b70 | 0x00022b70
`SceSvcSetInfo` | 68 (0x44) | Exported Function | 0x5fd33aa0 | 0x00033aa0
`SceSvcQueryInfo` | 67 (0x43) | Exported Function | 0x5fd33900 | 0x00033900
`SceSvcGetInformationTemplate` | 66 (0x42) | Exported Function | 0x5fd1f780 | 0x0001f780
`SceSvcFree` | 65 (0x41) | Exported Function | 0x5fd338e0 | 0x000338e0
`SceSvcConvertTextToSD` | 64 (0x40) | Exported Function | 0x5fd338b0 | 0x000338b0
`SceSvcConvertSDToText` | 63 (0x3f) | Exported Function | 0x5fd33880 | 0x00033880
`SceStartTransaction` | 62 (0x3e) | Exported Function | 0x5fd2e100 | 0x0002e100
`SceSetupUpdateSecurityService` | 61 (0x3d) | Exported Function | 0x5fd33740 | 0x00033740
`SceSetupUpdateSecurityFile` | 59 (0x3b) | Exported Function | 0x5fd33370 | 0x00033370
`SceWrapperImportSecurityProfile` | 74 (0x4a) | Exported Function | 0x5fd33c90 | 0x00033c90
`SceGetServerProductType` | 44 (0x2c) | Exported Function | 0x5fd2d710 | 0x0002d710
`SceGetScpProfileDescription` | 42 (0x2a) | Exported Function | 0x5fd2d420 | 0x0002d420
`SceConfigureConvertedFileSecurity` | 4 (0x4) | Exported Function | 0x5fd2eee0 | 0x0002eee0
`SceCompareSecurityDescriptors` | 23 (0x17) | Exported Function | 0x5fd19030 | 0x00019030
`SceCompareNameList` | 22 (0x16) | Exported Function | 0x5fd18fb0 | 0x00018fb0
`SceCommitTransaction` | 21 (0x15) | Exported Function | 0x5fd2c8c0 | 0x0002c8c0
`SceCloseProfile` | 20 (0x14) | Exported Function | 0x5fd2c810 | 0x0002c810
`SceBrowseDatabaseTable` | 19 (0x13) | Exported Function | 0x5fd2c660 | 0x0002c660
`SceAppendSecurityProfileInfo` | 18 (0x12) | Exported Function | 0x5fd22b40 | 0x00022b40
`SceAnalyzeSystem` | 17 (0x11) | Exported Function | 0x5fd2c430 | 0x0002c430
`SceAddToObjectList` | 16 (0x10) | Exported Function | 0x5fd18f80 | 0x00018f80
`SceAddToNameStatusList` | 15 (0xf) | Exported Function | 0x5fd18f60 | 0x00018f60
`SceAddToNameList` | 14 (0xe) | Exported Function | 0x5fd18f30 | 0x00018f30
`InitializeChangeNotify` | 3 (0x3) | Exported Function | 0x5fd09f20 | 0x00009f20
`DllUnregisterServer` | 13 (0xd) | Exported Function | 0x5fd2ece0 | 0x0002ece0
`DllRegisterServer` | 12 (0xc) | Exported Function | 0x5fd2e8b0 | 0x0002e8b0
`DeltaNotify` | 2 (0x2) | Exported Function | 0x5fd27c60 | 0x00027c60
`SceConfigureSystem` | 24 (0x18) | Exported Function | 0x5fd2c940 | 0x0002c940
`SceGetSecurityProfileInfo` | 43 (0x2b) | Exported Function | 0x5fd2d4b0 | 0x0002d4b0
`SceCopyBaseProfile` | 25 (0x19) | Exported Function | 0x5fd2ca70 | 0x0002ca70
`SceDcPromoCreateGPOsInSysvol` | 27 (0x1b) | Exported Function | 0x5fd316b0 | 0x000316b0
`SceGetObjectSecurity` | 41 (0x29) | Exported Function | 0x5fd2d350 | 0x0002d350
`SceGetObjectChildren` | 40 (0x28) | Exported Function | 0x5fd2d260 | 0x0002d260
`SceGetDbTime` | 39 (0x27) | Exported Function | 0x5fd2d100 | 0x0002d100
`SceGetDatabaseSetting` | 38 (0x26) | Exported Function | 0x5fd2d000 | 0x0002d000
`SceGetAreas` | 37 (0x25) | Exported Function | 0x5fd27a30 | 0x00027a30
`SceGetAnalysisAreaSummary` | 36 (0x24) | Exported Function | 0x5fd2cf80 | 0x0002cf80
`SceGenerateRollback` | 35 (0x23) | Exported Function | 0x5fd2ce00 | 0x0002ce00
`SceGenerateGroupPolicy` | 5 (0x5) | Exported Function | 0x5fd24ce0 | 0x00024ce0
`SceFreeProfileMemory` | 34 (0x22) | Exported Function | 0x5fd17960 | 0x00017960
`SceFreeMemory` | 33 (0x21) | Exported Function | 0x5fd17400 | 0x00017400
`SceEnumerateServices` | 32 (0x20) | Exported Function | 0x5fd190b0 | 0x000190b0
`SceEnforceSecurityPolicyPropagation` | 31 (0x1f) | Exported Function | 0x5fd31a90 | 0x00031a90
`SceDcPromoteSecurityEx` | 30 (0x1e) | Exported Function | 0x5fd31990 | 0x00031990
`SceDcPromoteSecurity` | 29 (0x1d) | Exported Function | 0x5fd31970 | 0x00031970
`SceDcPromoCreateGPOsInSysvolEx` | 28 (0x1c) | Exported Function | 0x5fd316e0 | 0x000316e0
`SceCreateDirectory` | 26 (0x1a) | Exported Function | 0x5fd19090 | 0x00019090
`SceWriteSecurityProfileInfo` | 75 (0x4b) | Exported Function | 0x5fd22d10 | 0x00022d10


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
* File Version: 10.0.19041.450 (WinBuild.160101.0800)
* Product Version: 10.0.19041.450
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/b16eafc25630ab974dafee09f4de86ca297ee83a32e3ba19c67a03d2b15146a7/detection/





MIT License. Copyright (c) 2020 Strontic.


