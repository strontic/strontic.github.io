---
title: policymanager.dll | Policy Manager DLL
excerpt: What is policymanager.dll?
---

# policymanager.dll 

* File Path: `C:\Windows\system32\policymanager.dll`
* Description: Policy Manager DLL

## Hashes

Type | Hash
-- | --
MD5 | `662FE2AA3C46EECDCE8928B75F303164`
SHA1 | `AC28F9B9D8027D003E01A4EFF35EAC815146E83E`
SHA256 | `29B8F2F3E045C198A02230865576444E8F5D3B6EBD6BD88D7A75DDD9C31D09C0`
SHA384 | `11CCAEC6DE940143F28F5031FBFAAE007697C65B1387CFA592DBE0D6C5C7A44A2E89077B58BEA462AE476D15D91BB5CB`
SHA512 | `60AAFFDB5475CD717CEE7C54E4065B690D5C474B8EB608A5CB39F0CB9AADC7AF895C813ECCC31E0645C12F76D8BA778295E0FE52F5AA7F9702E05E7D6EDC7396`
SSDEEP | `12288:Y+o85taLQwHYmApsodcA/bnasEJqQHJuL+1x+qwu5frvFwXt0QFy48y0LiH:YB85taLQwHYmosodc148jLiH`
IMP | `F370B64F13BF11C7409C5F71272A21E2`
PESHA1 | `8A7CF771C8DDE6A52527080E2A41045360AAC0C4`
PE256 | `76FE5A158154525A31FBACE32F93E343D82072CA88B7817472F021A1793CB16E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`EnterprisePolicyManagerStore_AcquireMergeLock` | 3 (0x3) | Exported Function | 0x000000018000b7b0 | 0x0000b7b0
`PolicyManager_GetDeviceLockPolicy_DevicePasswordEnabled` | 97 (0x61) | Exported Function | 0x0000000180005670 | 0x00005670
`PolicyManager_GetDeviceLockPolicy_AlphanumericDevicePasswordRequired` | 96 (0x60) | Exported Function | 0x000000018001e850 | 0x0001e850
`PolicyManager_GetDeviceLockPolicy_AllowSimpleDevicePassword` | 95 (0x5f) | Exported Function | 0x000000018001e830 | 0x0001e830
`PolicyManager_GetDeviceLockPolicy_AllowIdleReturnWithoutPassword` | 94 (0x5e) | Exported Function | 0x000000018001e810 | 0x0001e810
`PolicyManager_GetConnectivityPolicy_AllowUSBConnection` | 93 (0x5d) | Exported Function | 0x000000018001e7f0 | 0x0001e7f0
`PolicyManager_GetConnectivityPolicy_AllowNFC` | 92 (0x5c) | Exported Function | 0x000000018001e7d0 | 0x0001e7d0
`PolicyManager_GetCameraPolicy_AllowCamera` | 91 (0x5b) | Exported Function | 0x000000018001e7b0 | 0x0001e7b0
`PolicyManager_GetBrowserPolicy_AllowBrowser` | 90 (0x5a) | Exported Function | 0x00000001800056d0 | 0x000056d0
`PolicyManager_GetApplicationManagementPolicy_ApplicationRestrictions` | 89 (0x59) | Exported Function | 0x000000018001e790 | 0x0001e790
`PolicyManager_GetApplicationManagementPolicy_AllowStore` | 88 (0x58) | Exported Function | 0x000000018001e770 | 0x0001e770
`PolicyManager_GetAccountsPolicy_AllowMicrosoftAccountConnection` | 87 (0x57) | Exported Function | 0x0000000180005610 | 0x00005610
`PolicyManager_GetAccountsPolicy_AllowAddingNonMicrosoftAccountsManually` | 86 (0x56) | Exported Function | 0x000000018001e750 | 0x0001e750
`PolicyManager_GetAboveLockPolicy_AllowActionCenterNotifications` | 85 (0x55) | Exported Function | 0x000000018001e730 | 0x0001e730
`PolicyManager_GetDeviceLockPolicy_DevicePasswordExpiration` | 98 (0x62) | Exported Function | 0x000000018001e870 | 0x0001e870
`PolicyManager_FreeStringValues` | 84 (0x54) | Exported Function | 0x000000018001e6b0 | 0x0001e6b0
`PolicyManager_FreeGroupAreaPolicyCollection` | 82 (0x52) | Exported Function | 0x000000018000b0f0 | 0x0000b0f0
`PolicyManager_FreeGetPolicyData` | 81 (0x51) | Exported Function | 0x0000000180009000 | 0x00009000
`PolicyManager_FreeBinaryValue` | 80 (0x50) | Exported Function | 0x00000001800094d0 | 0x000094d0
`MDMWinsOverGP_IsGPPolicySetByMDMEx` | 79 (0x4f) | Exported Function | 0x000000018001ddf0 | 0x0001ddf0
`EnterprisePolicyManagerStore_VerifyAdmxPoliciesAreNotSet` | 78 (0x4e) | Exported Function | 0x000000018000f210 | 0x0000f210
`EnterprisePolicyManagerStore_SetProviderContextSidAreaPolicyValue` | 77 (0x4d) | Exported Function | 0x0000000180028e40 | 0x00028e40
`EnterprisePolicyManagerStore_SetGlobalValueChangedDirtyFlagInCurrentForArea` | 76 (0x4c) | Exported Function | 0x000000018000da90 | 0x0000da90
`EnterprisePolicyManagerStore_SetEnrollmentDormantState` | 75 (0x4b) | Exported Function | 0x0000000180021ce0 | 0x00021ce0
`EnterprisePolicyManagerStore_ReleaseMergeLock` | 74 (0x4a) | Exported Function | 0x000000018000b890 | 0x0000b890
`EnterprisePolicyManagerStore_RefreshAll` | 73 (0x49) | Exported Function | 0x000000018002c440 | 0x0002c440
`EnterprisePolicyManagerStore_ReadPolicyMetadata` | 72 (0x48) | Exported Function | 0x0000000180007020 | 0x00007020
`EnterprisePolicyManagerStore_PublishPolicyWNFCache` | 71 (0x47) | Exported Function | 0x00000001800442a0 | 0x000442a0
`EnterprisePolicyManagerStore_PublishAnyDelayedWnfs` | 70 (0x46) | Exported Function | 0x0000000180043df0 | 0x00043df0
`PolicyManager_FreeStringValue` | 83 (0x53) | Exported Function | 0x00000001800094d0 | 0x000094d0
`PolicyManager_GetDeviceLockPolicy_DevicePasswordHistory` | 99 (0x63) | Exported Function | 0x000000018001e890 | 0x0001e890
`PolicyManager_GetDeviceLockPolicy_MaxDevicePasswordFailedAttempts` | 100 (0x64) | Exported Function | 0x000000018001e8b0 | 0x0001e8b0
`PolicyManager_GetDeviceLockPolicy_MaxInactivityTimeDeviceLock` | 101 (0x65) | Exported Function | 0x000000018001e8d0 | 0x0001e8d0
`PolicyManager_PublishPolicyWNFCache` | 129 (0x81) | Exported Function | 0x000000018001ec90 | 0x0001ec90
`PolicyManager_IsPolicySetByMobileDeviceManager` | 128 (0x80) | Exported Function | 0x0000000180007d30 | 0x00007d30
`PolicyManager_GetWiFiPolicy_AllowWiFi` | 127 (0x7f) | Exported Function | 0x000000018001ec70 | 0x0001ec70
`PolicyManager_GetWiFiPolicy_AllowManualWiFiConfiguration` | 126 (0x7e) | Exported Function | 0x000000018001ec50 | 0x0001ec50
`PolicyManager_GetWiFiPolicy_AllowInternetSharing` | 125 (0x7d) | Exported Function | 0x000000018001ec30 | 0x0001ec30
`PolicyManager_GetWiFiPolicy_AllowAutoConnectToWiFiSenseHotspots` | 124 (0x7c) | Exported Function | 0x000000018001ec10 | 0x0001ec10
`PolicyManager_GetSystemPolicy_AllowUserToResetPhone` | 123 (0x7b) | Exported Function | 0x000000018001ebf0 | 0x0001ebf0
`PolicyManager_GetSystemPolicy_AllowStorageCard` | 122 (0x7a) | Exported Function | 0x000000018001ebd0 | 0x0001ebd0
`PolicyManager_GetSystemPolicy_AllowLocation` | 121 (0x79) | Exported Function | 0x0000000180005650 | 0x00005650
`PolicyManager_GetSecurityPolicy_RequireDeviceEncryption` | 120 (0x78) | Exported Function | 0x000000018001eb80 | 0x0001eb80
`PolicyManager_GetSecurityPolicy_AllowManualRootCertificateInstallation` | 119 (0x77) | Exported Function | 0x000000018001eb60 | 0x0001eb60
`PolicyManager_GetSearchPolicy_SafeSearchPermissions` | 118 (0x76) | Exported Function | 0x000000018001eb40 | 0x0001eb40
`PolicyManager_GetSearchPolicy_AllowSearchToUseLocation` | 117 (0x75) | Exported Function | 0x0000000180005630 | 0x00005630
`PolicyManager_GetPolicyStringValues` | 116 (0x74) | Exported Function | 0x000000018001e9f0 | 0x0001e9f0
`PolicyManager_GetPolicyStringGivenEnrollmentId` | 115 (0x73) | Exported Function | 0x000000018001e9e0 | 0x0001e9e0
`PolicyManager_GetPolicyString` | 114 (0x72) | Exported Function | 0x00000001800059b0 | 0x000059b0
`PolicyManager_GetPolicyIntGivenEnrollmentId` | 113 (0x71) | Exported Function | 0x000000018001e9d0 | 0x0001e9d0
`PolicyManager_GetPolicyInt` | 112 (0x70) | Exported Function | 0x00000001800069a0 | 0x000069a0
`PolicyManager_GetPolicyBinaryGivenEnrollmentId` | 111 (0x6f) | Exported Function | 0x000000018001e9c0 | 0x0001e9c0
`PolicyManager_GetPolicyBinary` | 110 (0x6e) | Exported Function | 0x000000018001e990 | 0x0001e990
`PolicyManager_GetPolicy` | 109 (0x6d) | Exported Function | 0x00000001800060e0 | 0x000060e0
`PolicyManager_GetGroupAreaPolicyCollectionGivenGroupName` | 108 (0x6c) | Exported Function | 0x000000018000b200 | 0x0000b200
`PolicyManager_GetExperiencePolicy_AllowVoiceRecording` | 107 (0x6b) | Exported Function | 0x0000000180005690 | 0x00005690
`PolicyManager_GetExperiencePolicy_AllowSyncMySettings` | 2 (0x2) | Exported Function | 0x000000018001e970 | 0x0001e970
`PolicyManager_GetExperiencePolicy_AllowScreenCapture` | 106 (0x6a) | Exported Function | 0x000000018001e950 | 0x0001e950
`PolicyManager_GetExperiencePolicy_AllowCortana` | 105 (0x69) | Exported Function | 0x00000001800056b0 | 0x000056b0
`PolicyManager_GetExperiencePolicy_AllowCopyPaste` | 104 (0x68) | Exported Function | 0x000000018001e930 | 0x0001e930
`PolicyManager_GetDeviceLockPolicy_MinDevicePasswordLength` | 103 (0x67) | Exported Function | 0x000000018001e910 | 0x0001e910
`PolicyManager_GetDeviceLockPolicy_MinDevicePasswordComplexCharacters` | 102 (0x66) | Exported Function | 0x000000018001e8f0 | 0x0001e8f0
`EnterprisePolicyManagerStore_PerformEvaluatorMerge` | 69 (0x45) | Exported Function | 0x0000000180021c20 | 0x00021c20
`EnterprisePolicyManagerStore_IsValidPolicy` | 68 (0x44) | Exported Function | 0x0000000180028d80 | 0x00028d80
`EnterprisePolicyManagerStore_IsValidArea` | 67 (0x43) | Exported Function | 0x0000000180028cc0 | 0x00028cc0
`EnterprisePolicyManagerStore_IsURISetByProvider` | 66 (0x42) | Exported Function | 0x000000018002c270 | 0x0002c270
`EnterprisePolicyManagerStore_EnsureProviderContextSidAreaExist` | 32 (0x20) | Exported Function | 0x0000000180027240 | 0x00027240
`EnterprisePolicyManagerStore_EnsureProviderContextNameExist` | 31 (0x1f) | Exported Function | 0x00000001800271e0 | 0x000271e0
`EnterprisePolicyManagerStore_EDPCSPConfigSourceAreaPolicySetValue` | 30 (0x1e) | Exported Function | 0x0000000180025820 | 0x00025820
`EnterprisePolicyManagerStore_EDPCSPConfigSourceAreaPolicyGetValue` | 29 (0x1d) | Exported Function | 0x0000000180025770 | 0x00025770
`EnterprisePolicyManagerStore_EDPCSPConfigSourceAreaDeleteChild` | 28 (0x1c) | Exported Function | 0x0000000180025630 | 0x00025630
`EnterprisePolicyManagerStore_DoesProviderExist` | 27 (0x1b) | Exported Function | 0x0000000180027170 | 0x00027170
`EnterprisePolicyManagerStore_DoesProviderContextSidAreaPolicyValueExist` | 26 (0x1a) | Exported Function | 0x000000018001d6f0 | 0x0001d6f0
`EnterprisePolicyManagerStore_DoesProviderContextSidAreaExist` | 25 (0x19) | Exported Function | 0x00000001800270f0 | 0x000270f0
`EnterprisePolicyManagerStore_DoesProviderContextNameExist` | 24 (0x18) | Exported Function | 0x0000000180027060 | 0x00027060
`EnterprisePolicyManagerStore_DeleteVirtuallyDeletedHive` | 23 (0x17) | Exported Function | 0x000000018002b510 | 0x0002b510
`EnterprisePolicyManagerStore_DeleteProviderIdAndMergeScopeData` | 22 (0x16) | Exported Function | 0x0000000180027030 | 0x00027030
`EnterprisePolicyManagerStore_DeleteProviderIdAndMerge` | 21 (0x15) | Exported Function | 0x0000000180026fa0 | 0x00026fa0
`EnterprisePolicyManagerStore_DeleteProviderContextSidAreaPolicy` | 20 (0x14) | Exported Function | 0x0000000180026a10 | 0x00026a10
`EnterprisePolicyManagerStore_DeleteProviderContextSidArea` | 19 (0x13) | Exported Function | 0x0000000180026760 | 0x00026760
`EnterprisePolicyManagerStore_DeleteProvider` | 18 (0x12) | Exported Function | 0x00000001800263d0 | 0x000263d0
`EnterprisePolicyManagerStore_DeleteEnrollmentAppSettingTypeAdmxMetadata` | 17 (0x11) | Exported Function | 0x000000018000f130 | 0x0000f130
`EnterprisePolicyManagerStore_DeleteEnrollmentAppAdmxMetadata` | 16 (0x10) | Exported Function | 0x000000018005f920 | 0x0005f920
`EnterprisePolicyManagerStore_DeleteEnrollmentAdmxMetadata` | 15 (0xf) | Exported Function | 0x000000018005f8c0 | 0x0005f8c0
`EnterprisePolicyManagerStore_CSPResultGetAreaChildNodeNames` | 13 (0xd) | Exported Function | 0x00000001800255a0 | 0x000255a0
`EnterprisePolicyManagerStore_CSPResultAreaPolicyGetValue` | 12 (0xc) | Exported Function | 0x0000000180025490 | 0x00025490
`EnterprisePolicyManagerStore_CSPResultAreaGetChildNodeNames` | 11 (0xb) | Exported Function | 0x00000001800253d0 | 0x000253d0
`EnterprisePolicyManagerStore_CSPConfigSourceDeleteChild` | 10 (0xa) | Exported Function | 0x0000000180025340 | 0x00025340
`EnterprisePolicyManagerStore_CSPConfigSourceAreaPolicySetValue` | 9 (0x9) | Exported Function | 0x00000001800252c0 | 0x000252c0
`EnterprisePolicyManagerStore_CSPConfigSourceAreaPolicyGetValue` | 8 (0x8) | Exported Function | 0x0000000180025230 | 0x00025230
`EnterprisePolicyManagerStore_CSPConfigSourceAreaPolicyCreateNodeInstance` | 7 (0x7) | Exported Function | 0x0000000180025080 | 0x00025080
`EnterprisePolicyManagerStore_CSPConfigSourceAreaGetChildNodeNames` | 6 (0x6) | Exported Function | 0x0000000180024fc0 | 0x00024fc0
`EnterprisePolicyManagerStore_CSPConfigSourceAreaDeleteChild` | 5 (0x5) | Exported Function | 0x0000000180024ef0 | 0x00024ef0
`EnterprisePolicyManagerStore_CSPConfigSourceAreaCreateNodeInstance` | 4 (0x4) | Exported Function | 0x0000000180024e40 | 0x00024e40
`EnterprisePolicyManagerStore_CreateProviderHive` | 14 (0xe) | Exported Function | 0x0000000180026380 | 0x00026380
`EnterprisePolicyManagerStore_EvaluatePoliciesUpdateCurrent` | 33 (0x21) | Exported Function | 0x000000018001f280 | 0x0001f280
`SettingsManagerStore_GetWnfsForSettingPath` | 130 (0x82) | Exported Function | 0x000000018000c650 | 0x0000c650
`EnterprisePolicyManagerStore_FreeURIsOfProviders` | 34 (0x22) | Exported Function | 0x000000018002ba30 | 0x0002ba30
`EnterprisePolicyManagerStore_GetAllCurrentSidAreaPolicies` | 36 (0x24) | Exported Function | 0x00000001800272a0 | 0x000272a0
`EnterprisePolicyManagerStore_IsPolicySetByMobileDeviceManager` | 65 (0x41) | Exported Function | 0x0000000180043da0 | 0x00043da0
`EnterprisePolicyManagerStore_IsPolicyAreaForIngestedAdmx` | 64 (0x40) | Exported Function | 0x000000018000f1a0 | 0x0000f1a0
`EnterprisePolicyManagerStore_IsAreaPolicySLAPIAllowedGivenSLAPIPolicyString` | 63 (0x3f) | Exported Function | 0x0000000180028b90 | 0x00028b90
`EnterprisePolicyManagerStore_IsAreaPolicySLAPIAllowed` | 62 (0x3e) | Exported Function | 0x00000001800289f0 | 0x000289f0
`EnterprisePolicyManagerStore_IsADMXIngestionAllowed` | 61 (0x3d) | Exported Function | 0x0000000180028860 | 0x00028860
`EnterprisePolicyManagerStore_IngestAdmxTextBlob` | 60 (0x3c) | Exported Function | 0x000000018005fac0 | 0x0005fac0
`EnterprisePolicyManagerStore_GetWinningProvider` | 59 (0x3b) | Exported Function | 0x0000000180043d50 | 0x00043d50
`EnterprisePolicyManagerStore_GetTrueArea` | 58 (0x3a) | Exported Function | 0x000000018002c220 | 0x0002c220
`EnterprisePolicyManagerStore_GetStringPolicyValue` | 57 (0x39) | Exported Function | 0x0000000180005ae0 | 0x00005ae0
`EnterprisePolicyManagerStore_GetSnapshotOfPolicyValue` | 56 (0x38) | Exported Function | 0x0000000180043cb0 | 0x00043cb0
`EnterprisePolicyManagerStore_GetProviderContextSidAreaPolicyValue` | 55 (0x37) | Exported Function | 0x0000000180028500 | 0x00028500
`EnterprisePolicyManagerStore_GetPolicyTypeFromMetadata` | 54 (0x36) | Exported Function | 0x00000001800284e0 | 0x000284e0
`EnterprisePolicyManagerStore_GetPolicyLowHighRangeFromMetadata` | 53 (0x35) | Exported Function | 0x0000000180028290 | 0x00028290
`EnterprisePolicyManagerStore_GetPolicyDoNotAllowFromMetadata` | 52 (0x34) | Exported Function | 0x0000000180028150 | 0x00028150
`EnterprisePolicyManagerStore_GetIntPolicyValue` | 51 (0x33) | Exported Function | 0x0000000180006000 | 0x00006000
`EnterprisePolicyManagerStore_GetEnrollmentTypeFromEnrollment` | 50 (0x32) | Exported Function | 0x000000018000d4a0 | 0x0000d4a0
`EnterprisePolicyManagerStore_GetEnrollmentState` | 49 (0x31) | Exported Function | 0x0000000180028070 | 0x00028070
`EnterprisePolicyManagerStore_GetCurrentPolicyValue` | 48 (0x30) | Exported Function | 0x0000000180043920 | 0x00043920
`EnterprisePolicyManagerStore_GetBinaryPolicyValue` | 47 (0x2f) | Exported Function | 0x0000000180027da0 | 0x00027da0
`EnterprisePolicyManagerStore_GetAllURIsOfProviders` | 46 (0x2e) | Exported Function | 0x000000018002bab0 | 0x0002bab0
`EnterprisePolicyManagerStore_GetAllProviderPolicyStringValues` | 45 (0x2d) | Exported Function | 0x0000000180027930 | 0x00027930
`EnterprisePolicyManagerStore_GetAllProviderIds` | 44 (0x2c) | Exported Function | 0x0000000180027870 | 0x00027870
`EnterprisePolicyManagerStore_GetAllProviderContextSids` | 43 (0x2b) | Exported Function | 0x00000001800277f0 | 0x000277f0
`EnterprisePolicyManagerStore_GetAllProviderContextSidAreas` | 42 (0x2a) | Exported Function | 0x0000000180027760 | 0x00027760
`EnterprisePolicyManagerStore_GetAllProviderContextSidAreaPolicies` | 41 (0x29) | Exported Function | 0x00000001800276b0 | 0x000276b0
`EnterprisePolicyManagerStore_GetAllDefaultAreas` | 40 (0x28) | Exported Function | 0x0000000180027620 | 0x00027620
`EnterprisePolicyManagerStore_GetAllDefaultAreaPolicies` | 39 (0x27) | Exported Function | 0x0000000180027560 | 0x00027560
`EnterprisePolicyManagerStore_GetAllCurrentSids` | 38 (0x26) | Exported Function | 0x0000000180027480 | 0x00027480
`EnterprisePolicyManagerStore_GetAllCurrentSidAreas` | 37 (0x25) | Exported Function | 0x00000001800273a0 | 0x000273a0
`EnterprisePolicyManagerStore_GetAdmxFileData` | 35 (0x23) | Exported Function | 0x000000018005f980 | 0x0005f980
`SettingsManagerStore_ReleaseWnfNames` | 131 (0x83) | Exported Function | 0x000000018000d430 | 0x0000d430


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PolicyManager.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/62
* VirusTotal Link: https://www.virustotal.com/gui/file/29b8f2f3e045c198a02230865576444e8f5d3b6ebd6bd88d7a75ddd9c31d09c0/detection/





MIT License. Copyright (c) 2020 Strontic.


