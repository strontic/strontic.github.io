---
title: rmclient.dll | Resource Manager Client
excerpt: What is rmclient.dll?
---

# rmclient.dll 

* File Path: `C:\Windows\system32\rmclient.dll`
* Description: Resource Manager Client

## Hashes

Type | Hash
-- | --
MD5 | `098EB94F871D45CB49944E62A94BDC7B`
SHA1 | `02202BD049F6926C234472ED451DF520662DC4B0`
SHA256 | `C6D29C2EE9B247CF103451236CA28FACEA84D9BF519DACEB5762BF7D3B9ACF66`
SHA384 | `34AA99B6E7305F1DDBB38880F57F794A5B01E74E9FF3C9B58F1E794C312E5D1A4C22B68274E1C646A0DCC6CA0195217C`
SHA512 | `C59C49985011FD8865EE254817D1A0BFD86211AB59D455C7CD933EA0A444721F187C69FB1AE594DB1A32B16AFCA0D0E7E30377D051E1545D6294C58DB7AF5A32`
SSDEEP | `3072:8qDWZCiNGuz00lrl/+sqP9SM88Jy40iI/:XRIzLlxqQ4n`
IMP | `A3D4661525D47C934F5B10E197A23FC4`
PESHA1 | `B194BB8242F4348A346CD2FE231168A3D7CAA999`
PE256 | `0E967052132B3CC6ADBFB14FF5A6907494CC62854A77394123E47999734F963F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateResourceManagerClientProxy` | 1 (0x1) | Exported Function | 0x0000000180009610 | 0x00009610
`RmAcquireResourceSet` | 99 (0x63) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`RmAcquireResources` | 101 (0x65) | Exported Function | 0x0000000180010090 | 0x00010090
`RmAccessCheckOnSelf` | 98 (0x62) | Exported Function | 0x0000000180010060 | 0x00010060
`RmAccessCheck` | 97 (0x61) | Exported Function | 0x0000000180010020 | 0x00010020
`HamUpdateActivityProperties` | 96 (0x60) | Exported Function | 0x0000000180006630 | 0x00006630
`HamTryEstimateRemainingQuiesceTime` | 95 (0x5f) | Exported Function | 0x00000001800091b0 | 0x000091b0
`HamTerminateSelfOnProcessExit` | 94 (0x5e) | Exported Function | 0x00000001800117f0 | 0x000117f0
`HamTerminateSelf` | 93 (0x5d) | Exported Function | 0x0000000180011780 | 0x00011780
`HamTerminateIfSuspendedByProcess` | 92 (0x5c) | Exported Function | 0x0000000180011700 | 0x00011700
`HamTerminateHostOnProcessExit` | 91 (0x5b) | Exported Function | 0x0000000180005df0 | 0x00005df0
`HamTerminateActivityHostEx` | 90 (0x5a) | Exported Function | 0x0000000180001470 | 0x00001470
`HamTerminateActivityHost` | 89 (0x59) | Exported Function | 0x0000000180001100 | 0x00001100
`HamStopActivity` | 88 (0x58) | Exported Function | 0x0000000180006090 | 0x00006090
`HamStartExtendedExecutionAsync` | 87 (0x57) | Exported Function | 0x00000001800045c0 | 0x000045c0
`RmAcquireResourceSetEx` | 100 (0x64) | Exported Function | 0x0000000180005aa0 | 0x00005aa0
`HamStartActivityAsync` | 86 (0x56) | Exported Function | 0x00000001800065d0 | 0x000065d0
`HamSetCommitProperties` | 84 (0x54) | Exported Function | 0x0000000180011580 | 0x00011580
`HamSessionStateLogoffUser` | 83 (0x53) | Exported Function | 0x00000001800114d0 | 0x000114d0
`HamSessionStateLogoffSession` | 82 (0x52) | Exported Function | 0x0000000180011460 | 0x00011460
`HamServicingTerminatePackage` | 81 (0x51) | Exported Function | 0x0000000180001630 | 0x00001630
`HamServicingQueryActiveAppsInPackage` | 80 (0x50) | Exported Function | 0x00000001800017a0 | 0x000017a0
`HamServicingOpenPackageHandle` | 79 (0x4f) | Exported Function | 0x0000000180001690 | 0x00001690
`HamServicingEnableServicing` | 78 (0x4e) | Exported Function | 0x00000001800015e0 | 0x000015e0
`HamServicingClosePackageHandle` | 77 (0x4d) | Exported Function | 0x0000000180001750 | 0x00001750
`HamResetExternalResourcePriority` | 76 (0x4c) | Exported Function | 0x00000001800113e0 | 0x000113e0
`HamRemoveHostDependency` | 75 (0x4b) | Exported Function | 0x0000000180011360 | 0x00011360
`HamRemoveDependency` | 74 (0x4a) | Exported Function | 0x00000001800112e0 | 0x000112e0
`HamQueryTaskCompletionsForTerminateGraph` | 73 (0x49) | Exported Function | 0x0000000180011240 | 0x00011240
`HamQueryPackageUsageInfo` | 72 (0x48) | Exported Function | 0x0000000180011040 | 0x00011040
`HamQueryCallerTerminateReason` | 71 (0x47) | Exported Function | 0x0000000180007440 | 0x00007440
`HamSetExternalResourcePriority` | 85 (0x55) | Exported Function | 0x0000000180011680 | 0x00011680
`HamQueryApplicationUsageInfo` | 70 (0x46) | Exported Function | 0x0000000180010ee0 | 0x00010ee0
`RmActivityImportanceInitialize` | 102 (0x66) | Exported Function | 0x0000000180008be0 | 0x00008be0
`RmApplyResourceSet` | 104 (0x68) | Exported Function | 0x0000000180005d90 | 0x00005d90
`RmUnregisterActivityHostCallbacks` | 134 (0x86) | Exported Function | 0x0000000180003a30 | 0x00003a30
`RmUnregisterActivityHost` | 133 (0x85) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`RmSetHostLimit` | 132 (0x84) | Exported Function | 0x000000018000f900 | 0x0000f900
`RmResourceSetPropertiesInitialize` | 131 (0x83) | Exported Function | 0x0000000180008660 | 0x00008660
`RmResourceLimitsInitialize` | 130 (0x82) | Exported Function | 0x000000018000f8d0 | 0x0000f8d0
`RmResourceLimitFlagsInitialize` | 129 (0x81) | Exported Function | 0x000000018000f8c0 | 0x0000f8c0
`RmReleaseResourceSetEx` | 127 (0x7f) | Exported Function | 0x0000000180003a20 | 0x00003a20
`RmReleaseResourceSet` | 126 (0x7e) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`RmReleaseResources` | 128 (0x80) | Exported Function | 0x0000000180010280 | 0x00010280
`RmRegisterResource` | 125 (0x7d) | Exported Function | 0x0000000180010220 | 0x00010220
`RmRegisterForGameMode` | 124 (0x7c) | Exported Function | 0x000000018000e0e0 | 0x0000e0e0
`RmRegisterActivityHostCallbacks` | 123 (0x7b) | Exported Function | 0x0000000180005870 | 0x00005870
`RmQueryHostMemoryLimitValues` | 122 (0x7a) | Exported Function | 0x000000018000f820 | 0x0000f820
`RmGetNotification` | 121 (0x79) | Exported Function | 0x00000001800101d0 | 0x000101d0
`RmActivityImportanceTakeMostImportant` | 103 (0x67) | Exported Function | 0x000000018000f7c0 | 0x0000f7c0
`RmGameModeUnregisterProcessById` | 120 (0x78) | Exported Function | 0x000000018000e010 | 0x0000e010
`RmGameModeRegisterProcessById` | 118 (0x76) | Exported Function | 0x000000018000de30 | 0x0000de30
`RmGameModeRegisterProcess` | 117 (0x75) | Exported Function | 0x000000018000dd30 | 0x0000dd30
`RmGameModeRegisterPairedAuxiliaryProcessById` | 116 (0x74) | Exported Function | 0x000000018000dc20 | 0x0000dc20
`RmGameModeRegisterPairedAuxiliaryProcess` | 115 (0x73) | Exported Function | 0x000000018000db10 | 0x0000db10
`RmGameModeReenableForRegisteredProcessById` | 114 (0x72) | Exported Function | 0x000000018000da40 | 0x0000da40
`RmGameModeReenableForRegisteredProcess` | 113 (0x71) | Exported Function | 0x000000018000d960 | 0x0000d960
`RmGameModeInitializeResourceRequest` | 112 (0x70) | Exported Function | 0x000000018000d920 | 0x0000d920
`RmGameModeGetLargestValidResourceRequest` | 111 (0x6f) | Exported Function | 0x000000018000d840 | 0x0000d840
`RmGameModeDisableForRegisteredProcessById` | 110 (0x6e) | Exported Function | 0x000000018000d770 | 0x0000d770
`RmGameModeDisableForRegisteredProcess` | 109 (0x6d) | Exported Function | 0x000000018000d690 | 0x0000d690
`RmDisconnectFromResourceManager` | 108 (0x6c) | Exported Function | 0x000000018000f7e0 | 0x0000f7e0
`RmConnectToResourceManager` | 107 (0x6b) | Exported Function | 0x00000001800095b0 | 0x000095b0
`RmAvailabilityCheck` | 106 (0x6a) | Exported Function | 0x0000000180010150 | 0x00010150
`RmApplyResourceSetToHost` | 105 (0x69) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`RmGameModeUnregisterProcess` | 119 (0x77) | Exported Function | 0x000000018000df30 | 0x0000df30
`HamPopulateActivityPropertiesByClass` | 69 (0x45) | Exported Function | 0x0000000180007c60 | 0x00007c60
`HamPopulateActivityProperties` | 68 (0x44) | Exported Function | 0x0000000180007130 | 0x00007130
`HamIsHostBeingDebugged` | 67 (0x43) | Exported Function | 0x0000000180010dd0 | 0x00010dd0
`HamConnectForSessionState` | 31 (0x1f) | Exported Function | 0x0000000180009200 | 0x00009200
`HamConnectForServicing` | 30 (0x1e) | Exported Function | 0x00000001800092f0 | 0x000092f0
`HamConnectForFullTrust` | 29 (0x1d) | Exported Function | 0x0000000180010470 | 0x00010470
`HamConnectForExtendedExecution` | 28 (0x1c) | Exported Function | 0x0000000180004f20 | 0x00004f20
`HamConnectForDebugging` | 27 (0x1b) | Exported Function | 0x0000000180009270 | 0x00009270
`HamCompleteExtendedExecution` | 26 (0x1a) | Exported Function | 0x00000001800040e0 | 0x000040e0
`HamCloseActivity` | 25 (0x19) | Exported Function | 0x00000001800063c0 | 0x000063c0
`HamAddHostDependency` | 24 (0x18) | Exported Function | 0x0000000180004340 | 0x00004340
`HamAddDependency` | 23 (0x17) | Exported Function | 0x00000001800042e0 | 0x000042e0
`DllGetClassObject` | 22 (0x16) | Exported Function | 0x000000018000d590 | 0x0000d590
`DllGetActivationFactory` | 21 (0x15) | Exported Function | 0x00000001800086f0 | 0x000086f0
`DllCanUnloadNow` | 20 (0x14) | Exported Function | 0x0000000180001840 | 0x00001840
`DeleteResourceManagerClientProxy` | 2 (0x2) | Exported Function | 0x000000018000fbf0 | 0x0000fbf0
`CrmWorkStop` | 19 (0x13) | Exported Function | 0x0000000180008f60 | 0x00008f60
`HamConnectForStateChangeNotifications` | 32 (0x20) | Exported Function | 0x0000000180009130 | 0x00009130
`CrmWorkStart` | 18 (0x12) | Exported Function | 0x0000000180008f60 | 0x00008f60
`CrmUnregister` | 16 (0x10) | Exported Function | 0x00000001800012b0 | 0x000012b0
`CrmSubscribe` | 15 (0xf) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`CrmRegister` | 14 (0xe) | Exported Function | 0x0000000180003a40 | 0x00003a40
`CrmActivityWindowClosedReasonUnsubscribe` | 13 (0xd) | Exported Function | 0x0000000180011b30 | 0x00011b30
`CrmActivityWindowClosedReasonSubscribe` | 12 (0xc) | Exported Function | 0x0000000180009010 | 0x00009010
`CrmActivityStop` | 11 (0xb) | Exported Function | 0x0000000180003d90 | 0x00003d90
`CrmActivityStart` | 10 (0xa) | Exported Function | 0x0000000180003d80 | 0x00003d80
`CrmActivityRequestAndWait` | 9 (0x9) | Exported Function | 0x0000000180011b20 | 0x00011b20
`CrmActivityRequest` | 8 (0x8) | Exported Function | 0x0000000180008b90 | 0x00008b90
`CrmActivityRenew` | 7 (0x7) | Exported Function | 0x0000000180008f60 | 0x00008f60
`CrmActivityQueryWindowClosedReasons` | 6 (0x6) | Exported Function | 0x0000000180003bd0 | 0x00003bd0
`CrmActivityFreeWindowClosedReasons` | 5 (0x5) | Exported Function | 0x0000000180008b60 | 0x00008b60
`CrmActivityFree` | 4 (0x4) | Exported Function | 0x0000000180003cb0 | 0x00003cb0
`CrmActivityAllocate` | 3 (0x3) | Exported Function | 0x0000000180003e80 | 0x00003e80
`CrmUnsubscribe` | 17 (0x11) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`HamConnectToServer` | 33 (0x21) | Exported Function | 0x00000001800038b0 | 0x000038b0
`HamConnectToServerEx` | 34 (0x22) | Exported Function | 0x00000001800038c0 | 0x000038c0
`HamCreateActivity` | 35 (0x23) | Exported Function | 0x00000001800060e0 | 0x000060e0
`HamInitializeStateChangeFlags` | 66 (0x42) | Exported Function | 0x0000000180008be0 | 0x00008be0
`HamInitializeActivityDynamicProperties` | 65 (0x41) | Exported Function | 0x0000000180008c50 | 0x00008c50
`HamInitializeActivityAutoRestartProperties` | 64 (0x40) | Exported Function | 0x0000000180008be0 | 0x00008be0
`HamHostIdRetrieveDynamicId` | 63 (0x3f) | Exported Function | 0x00000001800014f0 | 0x000014f0
`HamHostIdInitializeKey` | 62 (0x3e) | Exported Function | 0x0000000180006fd0 | 0x00006fd0
`HamHostIdFindOrCreate` | 61 (0x3d) | Exported Function | 0x0000000180005690 | 0x00005690
`HamHostIdCreateSingleUse` | 60 (0x3c) | Exported Function | 0x0000000180010d00 | 0x00010d00
`HamGetPackageInterruptiveUIState` | 59 (0x3b) | Exported Function | 0x0000000180010ba0 | 0x00010ba0
`HamGetInterruptiveUIStateForAumid` | 58 (0x3a) | Exported Function | 0x0000000180010a40 | 0x00010a40
`HamGetApplicationStateForPsmKey` | 57 (0x39) | Exported Function | 0x0000000180006f10 | 0x00006f10
`HamGetApplicationInterruptiveUIState` | 56 (0x38) | Exported Function | 0x0000000180001330 | 0x00001330
`HamFullTrustTerminatePackage` | 55 (0x37) | Exported Function | 0x00000001800109c0 | 0x000109c0
`HamFullTrustOpenPackageHandle` | 54 (0x36) | Exported Function | 0x00000001800108e0 | 0x000108e0
`HamFullTrustClosePackageHandle` | 53 (0x35) | Exported Function | 0x0000000180010860 | 0x00010860
`HamDisconnectFromServer` | 52 (0x34) | Exported Function | 0x0000000180002250 | 0x00002250
`HamDisconnectForStateChangeNotifications` | 51 (0x33) | Exported Function | 0x0000000180002250 | 0x00002250
`HamDisconnectForSessionState` | 50 (0x32) | Exported Function | 0x0000000180002250 | 0x00002250
`HamCreateActivityEx` | 36 (0x24) | Exported Function | 0x0000000180006110 | 0x00006110
`HamCreateActivityForProcess` | 37 (0x25) | Exported Function | 0x0000000180005e70 | 0x00005e70
`HamCreateAutoRestartActivity` | 38 (0x26) | Exported Function | 0x0000000180011b40 | 0x00011b40
`HamCreateExtendedExecution` | 39 (0x27) | Exported Function | 0x00000001800043a0 | 0x000043a0
`HamDebugClosePackageHandle` | 40 (0x28) | Exported Function | 0x0000000180010500 | 0x00010500
`HamDebugModeEnable` | 41 (0x29) | Exported Function | 0x0000000180010580 | 0x00010580
`RmUnregisterForGameMode` | 135 (0x87) | Exported Function | 0x000000018000e0e0 | 0x0000e0e0
`HamDebugOpenPackageHandle` | 42 (0x2a) | Exported Function | 0x0000000180010600 | 0x00010600
`HamDebugSuspendPackage` | 44 (0x2c) | Exported Function | 0x0000000180010750 | 0x00010750
`HamDebugTerminatePackage` | 45 (0x2d) | Exported Function | 0x00000001800107d0 | 0x000107d0
`HamDisconnectForDebugging` | 46 (0x2e) | Exported Function | 0x0000000180002250 | 0x00002250
`HamDisconnectForExtendedExecution` | 47 (0x2f) | Exported Function | 0x0000000180004610 | 0x00004610
`HamDisconnectForFullTrust` | 48 (0x30) | Exported Function | 0x0000000180002250 | 0x00002250
`HamDisconnectForServicing` | 49 (0x31) | Exported Function | 0x0000000180002250 | 0x00002250
`HamDebugQueryPackageState` | 43 (0x2b) | Exported Function | 0x00000001800106d0 | 0x000106d0
`RmUpdateResourceSetProperties` | 136 (0x88) | Exported Function | 0x0000000180008d90 | 0x00008d90


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: rmclient.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c6d29c2ee9b247cf103451236ca28facea84d9bf519daceb5762bf7d3b9acf66/detection/





MIT License. Copyright (c) 2020 Strontic.


