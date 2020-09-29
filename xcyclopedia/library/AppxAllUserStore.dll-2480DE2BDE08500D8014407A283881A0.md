---
title: AppxAllUserStore.dll | AppX All User Store DLL
excerpt: What is AppxAllUserStore.dll?
---

# AppxAllUserStore.dll 

* File Path: `C:\Windows\SysWOW64\AppxAllUserStore.dll`
* Description: AppX All User Store DLL

## Hashes

Type | Hash
-- | --
MD5 | `2480DE2BDE08500D8014407A283881A0`
SHA1 | `94594B935DAB60B1F918157E4B914F124B7A444B`
SHA256 | `56EC0D7B827D99F429E73DF2F8413EEF1D9E05EC463E35565F1D1EFA9EF74B58`
SHA384 | `B708BEB0402B6AAC1A5109C1CA78563A60007DE1EF35650DCEA8CE107518C92612D003E267EBEC5BC0D32197C97A521A`
SHA512 | `D31FFAFA5AE97F8548A90FDA9E7BEBAE0E8EC1E247EE2186741A2773CF18580D3AA7CFAD9E4C823BDD78CD757973DDBE97DC653C63B818E232225D3BEE57A1E7`
SSDEEP | `6144:vTX/Ul8qAd8cjWtkmlMQCavNbQlRNDhArXf4p:aASdkmlLvNElRN9ArXfQ`
IMP | `8BF9B165CA1D9FCF43C768B0662AC757`
PESHA1 | `1239E53746D4396BCB8E4213D833FF0A817F4AB5`
PE256 | `457229758DB927704765AE5E719CC7362763F6B8AA6CE7603C3009C89EE7D155`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddDeprovisionedPackageMarking` | 1 (0x1) | Exported Function | 0x1001f920 | 0x0001f920
`PackageFamilyNameFromId` | 59 (0x3b) | Exported Function | 0x10033950 | 0x00033950
`MarkStatusOfMainPackageForUser` | 58 (0x3a) | Exported Function | 0x1000f730 | 0x0000f730
`IsSystemInAuditBoot` | 57 (0x39) | Exported Function | 0x100213b0 | 0x000213b0
`IsPackageOnPreinstalledVolume` | 56 (0x38) | Exported Function | 0x100212d0 | 0x000212d0
`IsPackageInUsersUpgradeKey` | 55 (0x37) | Exported Function | 0x10021230 | 0x00021230
`IsPackageInUpgradeKey` | 54 (0x36) | Exported Function | 0x1000e850 | 0x0000e850
`IsPackageInStagedKey` | 53 (0x35) | Exported Function | 0x100211f0 | 0x000211f0
`PackageIdBasicFromFullName` | 60 (0x3c) | Exported Function | 0x10021410 | 0x00021410
`IsPackageInEndOfLifeKey` | 52 (0x34) | Exported Function | 0x10021150 | 0x00021150
`IsPackageFamilyInUninstallBlocklistByPackageFullName` | 50 (0x32) | Exported Function | 0x10021080 | 0x00021080
`IsPackageFamilyInUninstallBlocklist` | 49 (0x31) | Exported Function | 0x10021040 | 0x00021040
`IsPackageEndOfLife` | 48 (0x30) | Exported Function | 0x10020fb0 | 0x00020fb0
`IsNonInboxAllUserPackageSpecificPackage` | 47 (0x2f) | Exported Function | 0x1000faf0 | 0x0000faf0
`IsNonInboxAllUserPackage` | 46 (0x2e) | Exported Function | 0x10010060 | 0x00010060
`IsInboxPackage` | 45 (0x2d) | Exported Function | 0x1000fe90 | 0x0000fe90
`IsEnterprisePolicyEnabled` | 44 (0x2c) | Exported Function | 0x10020f70 | 0x00020f70
`IsPackageInDownlevelInstalledKey` | 51 (0x33) | Exported Function | 0x10021100 | 0x00021100
`PackageSidToPackageCapabilitySid` | 61 (0x3d) | Exported Function | 0x10021430 | 0x00021430
`RemoveDeprovisionedPackageMarking` | 62 (0x3e) | Exported Function | 0x100214c0 | 0x000214c0
`RemoveDownlevelInstalledPackagesFromRegistryStore` | 63 (0x3f) | Exported Function | 0x10021650 | 0x00021650
`UpdatePackageInRegistryStore` | 80 (0x50) | Exported Function | 0x10021f90 | 0x00021f90
`UpdateFrameworkPackageInRegistryStore` | 79 (0x4f) | Exported Function | 0x10021ef0 | 0x00021ef0
`TryGetEndOfLifePackageFullName` | 78 (0x4e) | Exported Function | 0x1000fa00 | 0x0000fa00
`TryGetDownlevelInstalledPackageFullName` | 77 (0x4d) | Exported Function | 0x10021eb0 | 0x00021eb0
`TakeOwnershipOnFolder` | 76 (0x4c) | Exported Function | 0x10021dc0 | 0x00021dc0
`SetTargetOsVersionOnPreinstalledVolume` | 75 (0x4b) | Exported Function | 0x10021d20 | 0x00021d20
`SetPackageOverrideSetupPhase` | 74 (0x4a) | Exported Function | 0x10021d00 | 0x00021d00
`SetAllUserStorePathForTest` | 73 (0x49) | Exported Function | 0x10021ce0 | 0x00021ce0
`RollbackTakeOwnershipSession` | 72 (0x48) | Exported Function | 0x10021c60 | 0x00021c60
`RestoreDownlevelAllUserStore` | 71 (0x47) | Exported Function | 0x10021c20 | 0x00021c20
`RemoveUpgradePackagesFromRegistryStore` | 70 (0x46) | Exported Function | 0x10021b40 | 0x00021b40
`RemoveStatusOfMainPackageForAllUsers` | 69 (0x45) | Exported Function | 0x10021b00 | 0x00021b00
`RemoveStagedPackageFromRegistryStore` | 68 (0x44) | Exported Function | 0x10021a40 | 0x00021a40
`RemovePackageFromRegistryStoreConfigIfExists` | 67 (0x43) | Exported Function | 0x100218f0 | 0x000218f0
`RemovePackageFromRegistryStore` | 66 (0x42) | Exported Function | 0x10021810 | 0x00021810
`RemoveInboxInstalledStatusOfPackageForUser` | 65 (0x41) | Exported Function | 0x10021780 | 0x00021780
`RemoveEndOfLifePackageMarkingForAllUsers` | 64 (0x40) | Exported Function | 0x10021740 | 0x00021740
`IsCleanupTaskComplete` | 43 (0x2b) | Exported Function | 0x10020e90 | 0x00020e90
`HasStagedPackages` | 42 (0x2a) | Exported Function | 0x10020ce0 | 0x00020ce0
`HasCentennial` | 41 (0x29) | Exported Function | 0x10020cc0 | 0x00020cc0
`GetUpgradePackageVolumeKey` | 40 (0x28) | Exported Function | 0x10020c90 | 0x00020c90
`DeleteAllPackagesFromPackageArray` | 18 (0x12) | Exported Function | 0x100120a0 | 0x000120a0
`DeleteAllPackagesFromMainPackageArray` | 17 (0x11) | Exported Function | 0x10011da0 | 0x00011da0
`CommitTakeOwnershipSession` | 16 (0x10) | Exported Function | 0x10020300 | 0x00020300
`CheckPackagePreinstallPolicy` | 15 (0xf) | Exported Function | 0x10020200 | 0x00020200
`ApplySharedFileACLs` | 14 (0xe) | Exported Function | 0x100201e0 | 0x000201e0
`ApplyPackageRootFolderACLs` | 13 (0xd) | Exported Function | 0x100200f0 | 0x000200f0
`ApplyFrameworkPackageRootFolderACLs` | 12 (0xc) | Exported Function | 0x100200d0 | 0x000200d0
`ApplyDependencyTargetPackageRootFolderACLs` | 11 (0xb) | Exported Function | 0x100200b0 | 0x000200b0
`AddUpgradePackageToRegistryStore` | 10 (0xa) | Exported Function | 0x1001ffd0 | 0x0001ffd0
`AddUpgradePackageToPreinstalledVolume` | 9 (0x9) | Exported Function | 0x1001fee0 | 0x0001fee0
`AddStagedPackageToRegistryStore` | 8 (0x8) | Exported Function | 0x1001fe20 | 0x0001fe20
`AddStagedPackageToPreinstalledAppsVolume` | 7 (0x7) | Exported Function | 0x1001fd50 | 0x0001fd50
`AddPackageToRegistryStore` | 6 (0x6) | Exported Function | 0x1001fc90 | 0x0001fc90
`AddPackageToPreinstalledAppsVolume` | 5 (0x5) | Exported Function | 0x1001fc10 | 0x0001fc10
`AddEndOfLifePackageMarkingForAllUsers` | 4 (0x4) | Exported Function | 0x1001fbd0 | 0x0001fbd0
`AddEndOfLifePackageMarking` | 3 (0x3) | Exported Function | 0x1001fb90 | 0x0001fb90
`AddDownlevelInstalledPackageToRegistryStore` | 2 (0x2) | Exported Function | 0x1001faa0 | 0x0001faa0
`DeletePackageInfo` | 19 (0x13) | Exported Function | 0x10020330 | 0x00020330
`UpdatePackageSetupPhase` | 81 (0x51) | Exported Function | 0x100221e0 | 0x000221e0
`DeleteUpdatedPackageKey` | 20 (0x14) | Exported Function | 0x100203d0 | 0x000203d0
`DidAppSurviveOSUpgradeForUser` | 22 (0x16) | Exported Function | 0x100112d0 | 0x000112d0
`GetStatusOfPackageFamilyForUser` | 39 (0x27) | Exported Function | 0x10020b40 | 0x00020b40
`GetPackagesThatMayNeedPreinstallPackageStatusMarked` | 38 (0x26) | Exported Function | 0x10020b10 | 0x00020b10
`GetPackageSetupPhase` | 37 (0x25) | Exported Function | 0x10020aa0 | 0x00020aa0
`GetPackageOverrideSetupPhase` | 36 (0x24) | Exported Function | 0x100119a0 | 0x000119a0
`GetOptionalPackageInfoForPackage` | 35 (0x23) | Exported Function | 0x10020a50 | 0x00020a50
`GetFoldersToKeepForPBR` | 34 (0x22) | Exported Function | 0x10020980 | 0x00020980
`GetAppxProvisionFactory` | 33 (0x21) | Exported Function | 0x10020960 | 0x00020960
`GetAllUpdatedPackages` | 32 (0x20) | Exported Function | 0x10011f40 | 0x00011f40
`GetAllStagedPackagesForMainPackageFromRegistryStore` | 31 (0x1f) | Exported Function | 0x10020860 | 0x00020860
`GetAllPackagesToBeInstalledForUser` | 30 (0x1e) | Exported Function | 0x10012110 | 0x00012110
`GetAllPackagesToBeInstalledForSetupPhase` | 29 (0x1d) | Exported Function | 0x10020830 | 0x00020830
`GetAllNonInboxPackagesFromRegistryStore` | 28 (0x1c) | Exported Function | 0x10020740 | 0x00020740
`GetAllInboxPackages` | 27 (0x1b) | Exported Function | 0x10020720 | 0x00020720
`FindFullNameForFamilyNameInAppxAllUserStore` | 26 (0x1a) | Exported Function | 0x100206c0 | 0x000206c0
`FindExistingVersionInRegistryStore` | 25 (0x19) | Exported Function | 0x10020660 | 0x00020660
`FamilyMonikerStringToSid` | 24 (0x18) | Exported Function | 0x100205a0 | 0x000205a0
`DoesPerUserStoreExist` | 23 (0x17) | Exported Function | 0x100204c0 | 0x000204c0
`DeleteUserRegistryKeyFromAllUserStore` | 21 (0x15) | Exported Function | 0x100203f0 | 0x000203f0
`UpdateUpgradePackageInRegistryStore` | 82 (0x52) | Exported Function | 0x10022380 | 0x00022380


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/56ec0d7b827d99f429e73df2f8413eef1d9e05ec463e35565f1d1efa9ef74b58/detection/





MIT License. Copyright (c) 2020 Strontic.


