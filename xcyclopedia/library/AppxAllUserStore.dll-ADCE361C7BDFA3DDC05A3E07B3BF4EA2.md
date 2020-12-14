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

Function Name | Ordinal | Type
-- | -- | --
`IsPackageInUsersUpgradeKey` | 55 | Exported Function
`IsPackageOnPreinstalledVolume` | 56 | Exported Function
`IsPackageInUpgradeKey` | 54 | Exported Function
`IsPackageInEndOfLifeKey` | 52 | Exported Function
`IsPackageInStagedKey` | 53 | Exported Function
`PackageIdBasicFromFullName` | 60 | Exported Function
`PackageSidToPackageCapabilitySid` | 61 | Exported Function
`PackageFamilyNameFromId` | 59 | Exported Function
`IsSystemInAuditBoot` | 57 | Exported Function
`MarkStatusOfMainPackageForUser` | 58 | Exported Function
`IsInboxPackage` | 45 | Exported Function
`IsNonInboxAllUserPackage` | 46 | Exported Function
`IsEnterprisePolicyEnabled` | 44 | Exported Function
`HasStagedPackages` | 42 | Exported Function
`IsCleanupTaskComplete` | 43 | Exported Function
`IsPackageFamilyInUninstallBlocklistByPackageFullName` | 50 | Exported Function
`IsPackageInDownlevelInstalledKey` | 51 | Exported Function
`IsPackageFamilyInUninstallBlocklist` | 49 | Exported Function
`IsNonInboxAllUserPackageSpecificPackage` | 47 | Exported Function
`IsPackageEndOfLife` | 48 | Exported Function
`RemoveDeprovisionedPackageMarking` | 62 | Exported Function
`TakeOwnershipOnFolder` | 76 | Exported Function
`TryGetDownlevelInstalledPackageFullName` | 77 | Exported Function
`SetTargetOsVersionOnPreinstalledVolume` | 75 | Exported Function
`SetAllUserStorePathForTest` | 73 | Exported Function
`SetPackageOverrideSetupPhase` | 74 | Exported Function
`UpdatePackageSetupPhase` | 81 | Exported Function
`UpdateUpgradePackageInRegistryStore` | 82 | Exported Function
`UpdatePackageInRegistryStore` | 80 | Exported Function
`TryGetEndOfLifePackageFullName` | 78 | Exported Function
`UpdateFrameworkPackageInRegistryStore` | 79 | Exported Function
`RemovePackageFromRegistryStore` | 66 | Exported Function
`RemovePackageFromRegistryStoreConfigIfExists` | 67 | Exported Function
`RemoveInboxInstalledStatusOfPackageForUser` | 65 | Exported Function
`RemoveDownlevelInstalledPackagesFromRegistryStore` | 63 | Exported Function
`RemoveEndOfLifePackageMarkingForAllUsers` | 64 | Exported Function
`RestoreDownlevelAllUserStore` | 71 | Exported Function
`RollbackTakeOwnershipSession` | 72 | Exported Function
`RemoveUpgradePackagesFromRegistryStore` | 70 | Exported Function
`RemoveStagedPackageFromRegistryStore` | 68 | Exported Function
`RemoveStatusOfMainPackageForAllUsers` | 69 | Exported Function
`ApplySharedFileACLs` | 14 | Exported Function
`CheckPackagePreinstallPolicy` | 15 | Exported Function
`ApplyPackageRootFolderACLs` | 13 | Exported Function
`ApplyDependencyTargetPackageRootFolderACLs` | 11 | Exported Function
`ApplyFrameworkPackageRootFolderACLs` | 12 | Exported Function
`DeletePackageInfo` | 19 | Exported Function
`DeleteUpdatedPackageKey` | 20 | Exported Function
`DeleteAllPackagesFromPackageArray` | 18 | Exported Function
`CommitTakeOwnershipSession` | 16 | Exported Function
`DeleteAllPackagesFromMainPackageArray` | 17 | Exported Function
`AddEndOfLifePackageMarkingForAllUsers` | 4 | Exported Function
`AddPackageToPreinstalledAppsVolume` | 5 | Exported Function
`AddEndOfLifePackageMarking` | 3 | Exported Function
`AddDeprovisionedPackageMarking` | 1 | Exported Function
`AddDownlevelInstalledPackageToRegistryStore` | 2 | Exported Function
`AddUpgradePackageToPreinstalledVolume` | 9 | Exported Function
`AddUpgradePackageToRegistryStore` | 10 | Exported Function
`AddStagedPackageToRegistryStore` | 8 | Exported Function
`AddPackageToRegistryStore` | 6 | Exported Function
`AddStagedPackageToPreinstalledAppsVolume` | 7 | Exported Function
`DeleteUserRegistryKeyFromAllUserStore` | 21 | Exported Function
`GetOptionalPackageInfoForPackage` | 35 | Exported Function
`GetPackageOverrideSetupPhase` | 36 | Exported Function
`GetFoldersToKeepForPBR` | 34 | Exported Function
`GetAllUpdatedPackages` | 32 | Exported Function
`GetAppxProvisionFactory` | 33 | Exported Function
`GetUpgradePackageVolumeKey` | 40 | Exported Function
`HasCentennial` | 41 | Exported Function
`GetStatusOfPackageFamilyForUser` | 39 | Exported Function
`GetPackageSetupPhase` | 37 | Exported Function
`GetPackagesThatMayNeedPreinstallPackageStatusMarked` | 38 | Exported Function
`FindExistingVersionInRegistryStore` | 25 | Exported Function
`FindFullNameForFamilyNameInAppxAllUserStore` | 26 | Exported Function
`FamilyMonikerStringToSid` | 24 | Exported Function
`DidAppSurviveOSUpgradeForUser` | 22 | Exported Function
`DoesPerUserStoreExist` | 23 | Exported Function
`GetAllPackagesToBeInstalledForUser` | 30 | Exported Function
`GetAllStagedPackagesForMainPackageFromRegistryStore` | 31 | Exported Function
`GetAllPackagesToBeInstalledForSetupPhase` | 29 | Exported Function
`GetAllInboxPackages` | 27 | Exported Function
`GetAllNonInboxPackagesFromRegistryStore` | 28 | Exported Function


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


