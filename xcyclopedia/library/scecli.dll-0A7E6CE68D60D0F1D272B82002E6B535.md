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

Function Name | Ordinal | Type
-- | -- | --
`SceSetupBackupSecurity` | 52 | Exported Function
`SceSetupConfigureServices` | 53 | Exported Function
`SceRollbackTransaction` | 50 | Exported Function
`SceSetDatabaseSetting` | 51 | Exported Function
`SceSetupGenerateTemplate` | 54 | Exported Function
`SceSetupSystemByInfName` | 57 | Exported Function
`SceSetupUnwindSecurityFile` | 58 | Exported Function
`SceSetupMoveSecurityFile` | 55 | Exported Function
`SceSetupRootSecurity` | 56 | Exported Function
`SceLookupPrivRightName` | 47 | Exported Function
`SceNotifyPolicyDelta` | 6 | Exported Function
`SceGetTimeStamp` | 45 | Exported Function
`SceIsSystemDatabase` | 46 | Exported Function
`SceOpenPolicy` | 7 | Exported Function
`SceProcessSecurityPolicyGPOEx` | 9 | Exported Function
`SceRegisterRegValues` | 49 | Exported Function
`SceOpenProfile` | 48 | Exported Function
`SceProcessSecurityPolicyGPO` | 8 | Exported Function
`SceSetupUpdateSecurityFile` | 59 | Exported Function
`SceSysPrep` | 10 | Exported Function
`SceSysPrepOffline` | 11 | Exported Function
`SceSvcSetInformationTemplate` | 69 | Exported Function
`SceSvcUpdateInfo` | 70 | Exported Function
`SceUpdateObjectInfo` | 71 | Exported Function
`SceWrapperImportSecurityProfile` | 74 | Exported Function
`SceWriteSecurityProfileInfo` | 75 | Exported Function
`SceUpdateSecurityProfile` | 72 | Exported Function
`SceWrapperExportSecurityProfile` | 73 | Exported Function
`SceStartTransaction` | 62 | Exported Function
`SceSvcConvertSDToText` | 63 | Exported Function
`SceSetupUpdateSecurityKey` | 60 | Exported Function
`SceSetupUpdateSecurityService` | 61 | Exported Function
`SceSvcConvertTextToSD` | 64 | Exported Function
`SceSvcQueryInfo` | 67 | Exported Function
`SceSvcSetInfo` | 68 | Exported Function
`SceSvcFree` | 65 | Exported Function
`SceSvcGetInformationTemplate` | 66 | Exported Function
`SceGetServerProductType` | 44 | Exported Function
`SceCloseProfile` | 20 | Exported Function
`SceCommitTransaction` | 21 | Exported Function
`SceAppendSecurityProfileInfo` | 18 | Exported Function
`SceBrowseDatabaseTable` | 19 | Exported Function
`SceCompareNameList` | 22 | Exported Function
`SceConfigureSystem` | 24 | Exported Function
`SceCopyBaseProfile` | 25 | Exported Function
`SceCompareSecurityDescriptors` | 23 | Exported Function
`SceConfigureConvertedFileSecurity` | 4 | Exported Function
`DllRegisterServer` | 12 | Exported Function
`DllUnregisterServer` | 13 | Exported Function
`ConvertSecurityDescriptorToText` | 1 | Exported Function
`DeltaNotify` | 2 | Exported Function
`InitializeChangeNotify` | 3 | Exported Function
`SceAddToObjectList` | 16 | Exported Function
`SceAnalyzeSystem` | 17 | Exported Function
`SceAddToNameList` | 14 | Exported Function
`SceAddToNameStatusList` | 15 | Exported Function
`SceCreateDirectory` | 26 | Exported Function
`SceGetAreas` | 37 | Exported Function
`SceGetDatabaseSetting` | 38 | Exported Function
`SceGenerateRollback` | 35 | Exported Function
`SceGetAnalysisAreaSummary` | 36 | Exported Function
`SceGetDbTime` | 39 | Exported Function
`SceGetScpProfileDescription` | 42 | Exported Function
`SceGetSecurityProfileInfo` | 43 | Exported Function
`SceGetObjectChildren` | 40 | Exported Function
`SceGetObjectSecurity` | 41 | Exported Function
`SceDcPromoteSecurity` | 29 | Exported Function
`SceDcPromoteSecurityEx` | 30 | Exported Function
`SceDcPromoCreateGPOsInSysvol` | 27 | Exported Function
`SceDcPromoCreateGPOsInSysvolEx` | 28 | Exported Function
`SceEnforceSecurityPolicyPropagation` | 31 | Exported Function
`SceFreeProfileMemory` | 34 | Exported Function
`SceGenerateGroupPolicy` | 5 | Exported Function
`SceEnumerateServices` | 32 | Exported Function
`SceFreeMemory` | 33 | Exported Function


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


