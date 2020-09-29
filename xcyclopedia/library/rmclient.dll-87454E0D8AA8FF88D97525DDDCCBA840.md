---
title: rmclient.dll | Resource Manager Client
excerpt: What is rmclient.dll?
---

# rmclient.dll 

* File Path: `C:\Windows\SysWOW64\rmclient.dll`
* Description: Resource Manager Client

## Hashes

Type | Hash
-- | --
MD5 | `87454E0D8AA8FF88D97525DDDCCBA840`
SHA1 | `9C282D87B0C0F4B635978AAD8313A904086304EB`
SHA256 | `3D830EEF251D220289D999ADEF820BCC8781CFDD3C1516D01E1C3415F572F009`
SHA384 | `771C47831E0C510F7BAF44C44B61252FE219A6029157E36352990EA6C4F3BCCEC1C8D3252BA9294B2A95951A41DC9CC4`
SHA512 | `68A24F9F74C7571E0339594E4AC6829812233FEB9599194E42334728FB6DD3130640A4DDEFEE7D5EA552F6D631B59A4700C21CE4A07CE2CA1E795CECC8C282B5`
SSDEEP | `3072:iOEU5tHvEE0oU9kgcRBmieJKIJ/zt04mSsr2:TPjmTJH9i8`
IMP | `20346EF262599EB883867C449E7C2638`
PESHA1 | `529E3CD0A863705C7A37D734017F03A9BF341EAA`
PE256 | `B9E59AC9C0FA1A9DA56C6CD93065E5B07B1B698251CC957D49E2DAB5457BB3C6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CreateResourceManagerClientProxy` | 1 (0x1) | Exported Function | 0x1000be80 | 0x0000be80
`RmAcquireResourceSet` | 99 (0x63) | Exported Function | 0x10010e70 | 0x00010e70
`RmAcquireResources` | 101 (0x65) | Exported Function | 0x10005510 | 0x00005510
`RmAccessCheckOnSelf` | 98 (0x62) | Exported Function | 0x10011bd0 | 0x00011bd0
`RmAccessCheck` | 97 (0x61) | Exported Function | 0x10005640 | 0x00005640
`HamUpdateActivityProperties` | 96 (0x60) | Exported Function | 0x10008130 | 0x00008130
`HamTryEstimateRemainingQuiesceTime` | 95 (0x5f) | Exported Function | 0x10009600 | 0x00009600
`HamTerminateSelfOnProcessExit` | 94 (0x5e) | Exported Function | 0x10012e00 | 0x00012e00
`HamTerminateSelf` | 93 (0x5d) | Exported Function | 0x10012d90 | 0x00012d90
`HamTerminateIfSuspendedByProcess` | 92 (0x5c) | Exported Function | 0x10012d20 | 0x00012d20
`HamTerminateHostOnProcessExit` | 91 (0x5b) | Exported Function | 0x1000b8e0 | 0x0000b8e0
`HamTerminateActivityHostEx` | 90 (0x5a) | Exported Function | 0x10005a50 | 0x00005a50
`HamTerminateActivityHost` | 89 (0x59) | Exported Function | 0x10005a20 | 0x00005a20
`HamStopActivity` | 88 (0x58) | Exported Function | 0x10007eb0 | 0x00007eb0
`HamStartExtendedExecutionAsync` | 87 (0x57) | Exported Function | 0x1000bba0 | 0x0000bba0
`RmAcquireResourceSetEx` | 100 (0x64) | Exported Function | 0x10010eb0 | 0x00010eb0
`HamStartActivityAsync` | 86 (0x56) | Exported Function | 0x10008860 | 0x00008860
`HamSetCommitProperties` | 84 (0x54) | Exported Function | 0x10012b60 | 0x00012b60
`HamSessionStateLogoffUser` | 83 (0x53) | Exported Function | 0x10012ae0 | 0x00012ae0
`HamSessionStateLogoffSession` | 82 (0x52) | Exported Function | 0x1000b890 | 0x0000b890
`HamServicingTerminatePackage` | 81 (0x51) | Exported Function | 0x10005830 | 0x00005830
`HamServicingQueryActiveAppsInPackage` | 80 (0x50) | Exported Function | 0x10005730 | 0x00005730
`HamServicingOpenPackageHandle` | 79 (0x4f) | Exported Function | 0x100057b0 | 0x000057b0
`HamServicingEnableServicing` | 78 (0x4e) | Exported Function | 0x10005890 | 0x00005890
`HamServicingClosePackageHandle` | 77 (0x4d) | Exported Function | 0x100056e0 | 0x000056e0
`HamResetExternalResourcePriority` | 76 (0x4c) | Exported Function | 0x10012a60 | 0x00012a60
`HamRemoveHostDependency` | 75 (0x4b) | Exported Function | 0x100129e0 | 0x000129e0
`HamRemoveDependency` | 74 (0x4a) | Exported Function | 0x10012970 | 0x00012970
`HamQueryTaskCompletionsForTerminateGraph` | 73 (0x49) | Exported Function | 0x100128e0 | 0x000128e0
`HamQueryPackageUsageInfo` | 72 (0x48) | Exported Function | 0x10012760 | 0x00012760
`HamQueryCallerTerminateReason` | 71 (0x47) | Exported Function | 0x10009a70 | 0x00009a70
`HamSetExternalResourcePriority` | 85 (0x55) | Exported Function | 0x10012ca0 | 0x00012ca0
`HamQueryApplicationUsageInfo` | 70 (0x46) | Exported Function | 0x10012650 | 0x00012650
`RmActivityImportanceInitialize` | 102 (0x66) | Exported Function | 0x1000b430 | 0x0000b430
`RmApplyResourceSet` | 104 (0x68) | Exported Function | 0x10010f00 | 0x00010f00
`RmUnregisterActivityHostCallbacks` | 134 (0x86) | Exported Function | 0x100110f0 | 0x000110f0
`RmUnregisterActivityHost` | 133 (0x85) | Exported Function | 0x10010ea0 | 0x00010ea0
`RmSetHostLimit` | 132 (0x84) | Exported Function | 0x100110d0 | 0x000110d0
`RmResourceSetPropertiesInitialize` | 131 (0x83) | Exported Function | 0x100110b0 | 0x000110b0
`RmResourceLimitsInitialize` | 130 (0x82) | Exported Function | 0x10011090 | 0x00011090
`RmResourceLimitFlagsInitialize` | 129 (0x81) | Exported Function | 0x10011070 | 0x00011070
`RmReleaseResourceSetEx` | 127 (0x7f) | Exported Function | 0x10011050 | 0x00011050
`RmReleaseResourceSet` | 126 (0x7e) | Exported Function | 0x10010e90 | 0x00010e90
`RmReleaseResources` | 128 (0x80) | Exported Function | 0x100055c0 | 0x000055c0
`RmRegisterResource` | 125 (0x7d) | Exported Function | 0x10005b80 | 0x00005b80
`RmRegisterForGameMode` | 124 (0x7c) | Exported Function | 0x1000fb30 | 0x0000fb30
`RmRegisterActivityHostCallbacks` | 123 (0x7b) | Exported Function | 0x10011020 | 0x00011020
`RmQueryHostMemoryLimitValues` | 122 (0x7a) | Exported Function | 0x10010fb0 | 0x00010fb0
`RmGetNotification` | 121 (0x79) | Exported Function | 0x10011c40 | 0x00011c40
`RmActivityImportanceTakeMostImportant` | 103 (0x67) | Exported Function | 0x10010ee0 | 0x00010ee0
`RmGameModeUnregisterProcessById` | 120 (0x78) | Exported Function | 0x1000fa80 | 0x0000fa80
`RmGameModeRegisterProcessById` | 118 (0x76) | Exported Function | 0x1000f920 | 0x0000f920
`RmGameModeRegisterProcess` | 117 (0x75) | Exported Function | 0x1000f870 | 0x0000f870
`RmGameModeRegisterPairedAuxiliaryProcessById` | 116 (0x74) | Exported Function | 0x1000f7c0 | 0x0000f7c0
`RmGameModeRegisterPairedAuxiliaryProcess` | 115 (0x73) | Exported Function | 0x1000f710 | 0x0000f710
`RmGameModeReenableForRegisteredProcessById` | 114 (0x72) | Exported Function | 0x1000f660 | 0x0000f660
`RmGameModeReenableForRegisteredProcess` | 113 (0x71) | Exported Function | 0x1000f5b0 | 0x0000f5b0
`RmGameModeInitializeResourceRequest` | 112 (0x70) | Exported Function | 0x1000f570 | 0x0000f570
`RmGameModeGetLargestValidResourceRequest` | 111 (0x6f) | Exported Function | 0x1000f4c0 | 0x0000f4c0
`RmGameModeDisableForRegisteredProcessById` | 110 (0x6e) | Exported Function | 0x1000f410 | 0x0000f410
`RmGameModeDisableForRegisteredProcess` | 109 (0x6d) | Exported Function | 0x1000f360 | 0x0000f360
`RmDisconnectFromResourceManager` | 108 (0x6c) | Exported Function | 0x10010f70 | 0x00010f70
`RmConnectToResourceManager` | 107 (0x6b) | Exported Function | 0x10010f20 | 0x00010f20
`RmAvailabilityCheck` | 106 (0x6a) | Exported Function | 0x10011c00 | 0x00011c00
`RmApplyResourceSetToHost` | 105 (0x69) | Exported Function | 0x10010e80 | 0x00010e80
`RmGameModeUnregisterProcess` | 119 (0x77) | Exported Function | 0x1000f9d0 | 0x0000f9d0
`HamPopulateActivityPropertiesByClass` | 69 (0x45) | Exported Function | 0x1000a590 | 0x0000a590
`HamPopulateActivityProperties` | 68 (0x44) | Exported Function | 0x100098e0 | 0x000098e0
`HamIsHostBeingDebugged` | 67 (0x43) | Exported Function | 0x10005470 | 0x00005470
`HamConnectForSessionState` | 31 (0x1f) | Exported Function | 0x1000bca0 | 0x0000bca0
`HamConnectForServicing` | 30 (0x1e) | Exported Function | 0x1000bd60 | 0x0000bd60
`HamConnectForFullTrust` | 29 (0x1d) | Exported Function | 0x10011e60 | 0x00011e60
`HamConnectForExtendedExecution` | 28 (0x1c) | Exported Function | 0x10007f00 | 0x00007f00
`HamConnectForDebugging` | 27 (0x1b) | Exported Function | 0x1000bcf0 | 0x0000bcf0
`HamCompleteExtendedExecution` | 26 (0x1a) | Exported Function | 0x1000ba80 | 0x0000ba80
`HamCloseActivity` | 25 (0x19) | Exported Function | 0x10008190 | 0x00008190
`HamAddHostDependency` | 24 (0x18) | Exported Function | 0x1000bbf0 | 0x0000bbf0
`HamAddDependency` | 23 (0x17) | Exported Function | 0x1000bc50 | 0x0000bc50
`DllGetClassObject` | 22 (0x16) | Exported Function | 0x1000f2b0 | 0x0000f2b0
`DllGetActivationFactory` | 21 (0x15) | Exported Function | 0x1000b1b0 | 0x0000b1b0
`DllCanUnloadNow` | 20 (0x14) | Exported Function | 0x100058e0 | 0x000058e0
`DeleteResourceManagerClientProxy` | 2 (0x2) | Exported Function | 0x10011a60 | 0x00011a60
`CrmWorkStop` | 19 (0x13) | Exported Function | 0x100130a0 | 0x000130a0
`HamConnectForStateChangeNotifications` | 32 (0x20) | Exported Function | 0x1000bdb0 | 0x0000bdb0
`CrmWorkStart` | 18 (0x12) | Exported Function | 0x100130a0 | 0x000130a0
`CrmUnregister` | 16 (0x10) | Exported Function | 0x10007e40 | 0x00007e40
`CrmSubscribe` | 15 (0xf) | Exported Function | 0x10010e80 | 0x00010e80
`CrmRegister` | 14 (0xe) | Exported Function | 0x10008af0 | 0x00008af0
`CrmActivityWindowClosedReasonUnsubscribe` | 13 (0xd) | Exported Function | 0x1000b760 | 0x0000b760
`CrmActivityWindowClosedReasonSubscribe` | 12 (0xc) | Exported Function | 0x1000b780 | 0x0000b780
`CrmActivityStop` | 11 (0xb) | Exported Function | 0x10008f80 | 0x00008f80
`CrmActivityStart` | 10 (0xa) | Exported Function | 0x10008ed0 | 0x00008ed0
`CrmActivityRequestAndWait` | 9 (0x9) | Exported Function | 0x10013070 | 0x00013070
`CrmActivityRequest` | 8 (0x8) | Exported Function | 0x1000b850 | 0x0000b850
`CrmActivityRenew` | 7 (0x7) | Exported Function | 0x10013060 | 0x00013060
`CrmActivityQueryWindowClosedReasons` | 6 (0x6) | Exported Function | 0x10007f70 | 0x00007f70
`CrmActivityFreeWindowClosedReasons` | 5 (0x5) | Exported Function | 0x1000b400 | 0x0000b400
`CrmActivityFree` | 4 (0x4) | Exported Function | 0x10008df0 | 0x00008df0
`CrmActivityAllocate` | 3 (0x3) | Exported Function | 0x10008c20 | 0x00008c20
`CrmUnsubscribe` | 17 (0x11) | Exported Function | 0x10013090 | 0x00013090
`HamConnectToServer` | 33 (0x21) | Exported Function | 0x100060d0 | 0x000060d0
`HamConnectToServerEx` | 34 (0x22) | Exported Function | 0x10007dd0 | 0x00007dd0
`HamCreateActivity` | 35 (0x23) | Exported Function | 0x10008100 | 0x00008100
`HamInitializeStateChangeFlags` | 66 (0x42) | Exported Function | 0x1000be60 | 0x0000be60
`HamInitializeActivityDynamicProperties` | 65 (0x41) | Exported Function | 0x1000b4b0 | 0x0000b4b0
`HamInitializeActivityAutoRestartProperties` | 64 (0x40) | Exported Function | 0x1000be60 | 0x0000be60
`HamHostIdRetrieveDynamicId` | 63 (0x3f) | Exported Function | 0x10005910 | 0x00005910
`HamHostIdInitializeKey` | 62 (0x3e) | Exported Function | 0x100096f0 | 0x000096f0
`HamHostIdFindOrCreate` | 61 (0x3d) | Exported Function | 0x1000a950 | 0x0000a950
`HamHostIdCreateSingleUse` | 60 (0x3c) | Exported Function | 0x100125b0 | 0x000125b0
`HamGetPackageInterruptiveUIState` | 59 (0x3b) | Exported Function | 0x100124d0 | 0x000124d0
`HamGetInterruptiveUIStateForAumid` | 58 (0x3a) | Exported Function | 0x100123f0 | 0x000123f0
`HamGetApplicationStateForPsmKey` | 57 (0x39) | Exported Function | 0x10009650 | 0x00009650
`HamGetApplicationInterruptiveUIState` | 56 (0x38) | Exported Function | 0x10008020 | 0x00008020
`HamFullTrustTerminatePackage` | 55 (0x37) | Exported Function | 0x10012370 | 0x00012370
`HamFullTrustOpenPackageHandle` | 54 (0x36) | Exported Function | 0x100122d0 | 0x000122d0
`HamFullTrustClosePackageHandle` | 53 (0x35) | Exported Function | 0x10012260 | 0x00012260
`HamDisconnectFromServer` | 52 (0x34) | Exported Function | 0x1000ada0 | 0x0000ada0
`HamDisconnectForStateChangeNotifications` | 51 (0x33) | Exported Function | 0x10012200 | 0x00012200
`HamDisconnectForSessionState` | 50 (0x32) | Exported Function | 0x10012200 | 0x00012200
`HamCreateActivityEx` | 36 (0x24) | Exported Function | 0x100085e0 | 0x000085e0
`HamCreateActivityForProcess` | 37 (0x25) | Exported Function | 0x10005ce0 | 0x00005ce0
`HamCreateAutoRestartActivity` | 38 (0x26) | Exported Function | 0x100130b0 | 0x000130b0
`HamCreateExtendedExecution` | 39 (0x27) | Exported Function | 0x1000b9d0 | 0x0000b9d0
`HamDebugClosePackageHandle` | 40 (0x28) | Exported Function | 0x10011f00 | 0x00011f00
`HamDebugModeEnable` | 41 (0x29) | Exported Function | 0x10011f70 | 0x00011f70
`RmUnregisterForGameMode` | 135 (0x87) | Exported Function | 0x1000fb40 | 0x0000fb40
`HamDebugOpenPackageHandle` | 42 (0x2a) | Exported Function | 0x10011fe0 | 0x00011fe0
`HamDebugSuspendPackage` | 44 (0x2c) | Exported Function | 0x10012100 | 0x00012100
`HamDebugTerminatePackage` | 45 (0x2d) | Exported Function | 0x10012180 | 0x00012180
`HamDisconnectForDebugging` | 46 (0x2e) | Exported Function | 0x10012200 | 0x00012200
`HamDisconnectForExtendedExecution` | 47 (0x2f) | Exported Function | 0x1000ada0 | 0x0000ada0
`HamDisconnectForFullTrust` | 48 (0x30) | Exported Function | 0x10012200 | 0x00012200
`HamDisconnectForServicing` | 49 (0x31) | Exported Function | 0x10012200 | 0x00012200
`HamDebugQueryPackageState` | 43 (0x2b) | Exported Function | 0x10012080 | 0x00012080
`RmUpdateResourceSetProperties` | 136 (0x88) | Exported Function | 0x10011110 | 0x00011110


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3d830eef251d220289d999adef820bcc8781cfdd3c1516d01e1c3415f572f009/detection/





MIT License. Copyright (c) 2020 Strontic.


