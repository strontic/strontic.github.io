---
title: AppxAllUserStore.dll | AppX All User Store DLL
excerpt: What is AppxAllUserStore.dll?
---

# AppxAllUserStore.dll 

* File Path: `C:\Windows\system32\AppxAllUserStore.dll`
* Description: AppX All User Store DLL

## Hashes

Type | Hash
-- | --
MD5 | `ADCE361C7BDFA3DDC05A3E07B3BF4EA2`
SHA1 | `DDCB8ECC1FA5360337B03541B89D30A68DFA62DF`
SHA256 | `C0AC0051EA72C718DCC0D249BBC92058CDC60CF5628BF14F7CF21834BDDFC09A`
SHA384 | `EAE7C80A24252A21E7332956727EDA919BE5814C3CCD33F31AE9302E70FC1721205A0B4596FDDB415D4B4D6B2C1FC20F`
SHA512 | `8F3F18102780A7C15F4AF9F1C288B18548E3C5AF8A51D504029315C5B28449C1B1007C9EA317C8A8DA0C3DC6B44F1FBC4175A2919B7A4B6874D69424706C7782`
SSDEEP | `6144:8LVWvf1zCCBz6i4nmYvfEEuTEv4Bqh57njNPE+Y4FOKYCEib3tfxMfHvFpDPH77k:8LVWvf1zCCBz6iqmYvf1XvYqhdnjN8+d`
IMP | `1311B1F659A580D3DA1F2A87CED11DE4`
PESHA1 | `E816C657F6012518EA93BFE0106CBD156F800C57`
PE256 | `8E9DD644E84FF14118AB69EC6F5E8EC2780823D205E2AB1DCA83CBF695630C3A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddDeprovisionedPackageMarking` | 1 (0x1) | Exported Function | 0x0000000180017e30 | 0x00017e30
`PackageFamilyNameFromId` | 59 (0x3b) | Exported Function | 0x00000001800335c0 | 0x000335c0
`MarkStatusOfMainPackageForUser` | 58 (0x3a) | Exported Function | 0x000000018001a050 | 0x0001a050
`IsSystemInAuditBoot` | 57 (0x39) | Exported Function | 0x000000018001a040 | 0x0001a040
`IsPackageOnPreinstalledVolume` | 56 (0x38) | Exported Function | 0x0000000180019f30 | 0x00019f30
`IsPackageInUsersUpgradeKey` | 55 (0x37) | Exported Function | 0x0000000180019e70 | 0x00019e70
`IsPackageInUpgradeKey` | 54 (0x36) | Exported Function | 0x0000000180019dd0 | 0x00019dd0
`IsPackageInStagedKey` | 53 (0x35) | Exported Function | 0x0000000180019d90 | 0x00019d90
`PackageIdBasicFromFullName` | 60 (0x3c) | Exported Function | 0x000000018001a220 | 0x0001a220
`IsPackageInEndOfLifeKey` | 52 (0x34) | Exported Function | 0x0000000180019cd0 | 0x00019cd0
`IsPackageFamilyInUninstallBlocklistByPackageFullName` | 50 (0x32) | Exported Function | 0x0000000180019ba0 | 0x00019ba0
`IsPackageFamilyInUninstallBlocklist` | 49 (0x31) | Exported Function | 0x0000000180019b60 | 0x00019b60
`IsPackageEndOfLife` | 48 (0x30) | Exported Function | 0x0000000180019ab0 | 0x00019ab0
`IsNonInboxAllUserPackageSpecificPackage` | 47 (0x2f) | Exported Function | 0x0000000180001170 | 0x00001170
`IsNonInboxAllUserPackage` | 46 (0x2e) | Exported Function | 0x00000001800013a0 | 0x000013a0
`IsInboxPackage` | 45 (0x2d) | Exported Function | 0x0000000180006870 | 0x00006870
`IsEnterprisePolicyEnabled` | 44 (0x2c) | Exported Function | 0x0000000180019a70 | 0x00019a70
`IsPackageInDownlevelInstalledKey` | 51 (0x33) | Exported Function | 0x0000000180019c80 | 0x00019c80
`PackageSidToPackageCapabilitySid` | 61 (0x3d) | Exported Function | 0x000000018001a230 | 0x0001a230
`RemoveDeprovisionedPackageMarking` | 62 (0x3e) | Exported Function | 0x000000018001a300 | 0x0001a300
`RemoveDownlevelInstalledPackagesFromRegistryStore` | 63 (0x3f) | Exported Function | 0x000000018001a730 | 0x0001a730
`UpdatePackageInRegistryStore` | 80 (0x50) | Exported Function | 0x000000018001b2b0 | 0x0001b2b0
`UpdateFrameworkPackageInRegistryStore` | 79 (0x4f) | Exported Function | 0x000000018001b1e0 | 0x0001b1e0
`TryGetEndOfLifePackageFullName` | 78 (0x4e) | Exported Function | 0x0000000180001280 | 0x00001280
`TryGetDownlevelInstalledPackageFullName` | 77 (0x4d) | Exported Function | 0x000000018001b190 | 0x0001b190
`TakeOwnershipOnFolder` | 76 (0x4c) | Exported Function | 0x000000018001b040 | 0x0001b040
`SetTargetOsVersionOnPreinstalledVolume` | 75 (0x4b) | Exported Function | 0x000000018001af70 | 0x0001af70
`SetPackageOverrideSetupPhase` | 74 (0x4a) | Exported Function | 0x000000018001af60 | 0x0001af60
`SetAllUserStorePathForTest` | 73 (0x49) | Exported Function | 0x000000018001af40 | 0x0001af40
`RollbackTakeOwnershipSession` | 72 (0x48) | Exported Function | 0x000000018001ae80 | 0x0001ae80
`RestoreDownlevelAllUserStore` | 71 (0x47) | Exported Function | 0x000000018001ae60 | 0x0001ae60
`RemoveUpgradePackagesFromRegistryStore` | 70 (0x46) | Exported Function | 0x000000018001ad50 | 0x0001ad50
`RemoveStatusOfMainPackageForAllUsers` | 69 (0x45) | Exported Function | 0x000000018001ad10 | 0x0001ad10
`RemoveStagedPackageFromRegistryStore` | 68 (0x44) | Exported Function | 0x000000018001ac00 | 0x0001ac00
`RemovePackageFromRegistryStoreConfigIfExists` | 67 (0x43) | Exported Function | 0x000000018001aa60 | 0x0001aa60
`RemovePackageFromRegistryStore` | 66 (0x42) | Exported Function | 0x000000018001a950 | 0x0001a950
`RemoveInboxInstalledStatusOfPackageForUser` | 65 (0x41) | Exported Function | 0x000000018001a890 | 0x0001a890
`RemoveEndOfLifePackageMarkingForAllUsers` | 64 (0x40) | Exported Function | 0x000000018001a850 | 0x0001a850
`IsCleanupTaskComplete` | 43 (0x2b) | Exported Function | 0x0000000180019950 | 0x00019950
`HasStagedPackages` | 42 (0x2a) | Exported Function | 0x0000000180019720 | 0x00019720
`HasCentennial` | 41 (0x29) | Exported Function | 0x0000000180019710 | 0x00019710
`GetUpgradePackageVolumeKey` | 40 (0x28) | Exported Function | 0x00000001800196f0 | 0x000196f0
`DeleteAllPackagesFromPackageArray` | 18 (0x12) | Exported Function | 0x0000000180007c40 | 0x00007c40
`DeleteAllPackagesFromMainPackageArray` | 17 (0x11) | Exported Function | 0x0000000180007760 | 0x00007760
`CommitTakeOwnershipSession` | 16 (0x10) | Exported Function | 0x0000000180018c80 | 0x00018c80
`CheckPackagePreinstallPolicy` | 15 (0xf) | Exported Function | 0x0000000180018b50 | 0x00018b50
`ApplySharedFileACLs` | 14 (0xe) | Exported Function | 0x0000000180018b40 | 0x00018b40
`ApplyPackageRootFolderACLs` | 13 (0xd) | Exported Function | 0x0000000180018a10 | 0x00018a10
`ApplyFrameworkPackageRootFolderACLs` | 12 (0xc) | Exported Function | 0x0000000180018a00 | 0x00018a00
`ApplyDependencyTargetPackageRootFolderACLs` | 11 (0xb) | Exported Function | 0x00000001800189f0 | 0x000189f0
`AddUpgradePackageToRegistryStore` | 10 (0xa) | Exported Function | 0x00000001800188e0 | 0x000188e0
`AddUpgradePackageToPreinstalledVolume` | 9 (0x9) | Exported Function | 0x00000001800187b0 | 0x000187b0
`AddStagedPackageToRegistryStore` | 8 (0x8) | Exported Function | 0x00000001800186b0 | 0x000186b0
`AddStagedPackageToPreinstalledAppsVolume` | 7 (0x7) | Exported Function | 0x00000001800185b0 | 0x000185b0
`AddPackageToRegistryStore` | 6 (0x6) | Exported Function | 0x00000001800184b0 | 0x000184b0
`AddPackageToPreinstalledAppsVolume` | 5 (0x5) | Exported Function | 0x0000000180018420 | 0x00018420
`AddEndOfLifePackageMarkingForAllUsers` | 4 (0x4) | Exported Function | 0x00000001800183e0 | 0x000183e0
`AddEndOfLifePackageMarking` | 3 (0x3) | Exported Function | 0x00000001800183a0 | 0x000183a0
`AddDownlevelInstalledPackageToRegistryStore` | 2 (0x2) | Exported Function | 0x0000000180018280 | 0x00018280
`DeletePackageInfo` | 19 (0x13) | Exported Function | 0x0000000180018ca0 | 0x00018ca0
`UpdatePackageSetupPhase` | 81 (0x51) | Exported Function | 0x000000018001b550 | 0x0001b550
`DeleteUpdatedPackageKey` | 20 (0x14) | Exported Function | 0x0000000180018d20 | 0x00018d20
`DidAppSurviveOSUpgradeForUser` | 22 (0x16) | Exported Function | 0x0000000180002a70 | 0x00002a70
`GetStatusOfPackageFamilyForUser` | 39 (0x27) | Exported Function | 0x0000000180019570 | 0x00019570
`GetPackagesThatMayNeedPreinstallPackageStatusMarked` | 38 (0x26) | Exported Function | 0x0000000180019540 | 0x00019540
`GetPackageSetupPhase` | 37 (0x25) | Exported Function | 0x00000001800194c0 | 0x000194c0
`GetPackageOverrideSetupPhase` | 36 (0x24) | Exported Function | 0x0000000180002c70 | 0x00002c70
`GetOptionalPackageInfoForPackage` | 35 (0x23) | Exported Function | 0x0000000180019490 | 0x00019490
`GetFoldersToKeepForPBR` | 34 (0x22) | Exported Function | 0x0000000180019390 | 0x00019390
`GetAppxProvisionFactory` | 33 (0x21) | Exported Function | 0x0000000180019380 | 0x00019380
`GetAllUpdatedPackages` | 32 (0x20) | Exported Function | 0x0000000180001a60 | 0x00001a60
`GetAllStagedPackagesForMainPackageFromRegistryStore` | 31 (0x1f) | Exported Function | 0x0000000180019250 | 0x00019250
`GetAllPackagesToBeInstalledForUser` | 30 (0x1e) | Exported Function | 0x0000000180001b30 | 0x00001b30
`GetAllPackagesToBeInstalledForSetupPhase` | 29 (0x1d) | Exported Function | 0x0000000180019220 | 0x00019220
`GetAllNonInboxPackagesFromRegistryStore` | 28 (0x1c) | Exported Function | 0x0000000180019100 | 0x00019100
`GetAllInboxPackages` | 27 (0x1b) | Exported Function | 0x00000001800190f0 | 0x000190f0
`FindFullNameForFamilyNameInAppxAllUserStore` | 26 (0x1a) | Exported Function | 0x00000001800190a0 | 0x000190a0
`FindExistingVersionInRegistryStore` | 25 (0x19) | Exported Function | 0x0000000180019040 | 0x00019040
`FamilyMonikerStringToSid` | 24 (0x18) | Exported Function | 0x0000000180018f50 | 0x00018f50
`DoesPerUserStoreExist` | 23 (0x17) | Exported Function | 0x0000000180018e30 | 0x00018e30
`DeleteUserRegistryKeyFromAllUserStore` | 21 (0x15) | Exported Function | 0x0000000180018d30 | 0x00018d30
`UpdateUpgradePackageInRegistryStore` | 82 (0x52) | Exported Function | 0x000000018001b770 | 0x0001b770


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppXAllUserStore.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/c0ac0051ea72c718dcc0d249bbc92058cdc60cf5628bf14f7cf21834bddfc09a/detection/





MIT License. Copyright (c) 2020 Strontic.


