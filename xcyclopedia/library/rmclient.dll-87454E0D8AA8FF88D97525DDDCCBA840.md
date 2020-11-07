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

Function Name | Ordinal | Type
-- | -- | --
`CreateResourceManagerClientProxy` | 1 | Exported Function
`RmAcquireResourceSet` | 99 | Exported Function
`RmAcquireResources` | 101 | Exported Function
`RmAccessCheckOnSelf` | 98 | Exported Function
`RmAccessCheck` | 97 | Exported Function
`HamUpdateActivityProperties` | 96 | Exported Function
`HamTryEstimateRemainingQuiesceTime` | 95 | Exported Function
`HamTerminateSelfOnProcessExit` | 94 | Exported Function
`HamTerminateSelf` | 93 | Exported Function
`HamTerminateIfSuspendedByProcess` | 92 | Exported Function
`HamTerminateHostOnProcessExit` | 91 | Exported Function
`HamTerminateActivityHostEx` | 90 | Exported Function
`HamTerminateActivityHost` | 89 | Exported Function
`HamStopActivity` | 88 | Exported Function
`HamStartExtendedExecutionAsync` | 87 | Exported Function
`RmAcquireResourceSetEx` | 100 | Exported Function
`HamStartActivityAsync` | 86 | Exported Function
`HamSetCommitProperties` | 84 | Exported Function
`HamSessionStateLogoffUser` | 83 | Exported Function
`HamSessionStateLogoffSession` | 82 | Exported Function
`HamServicingTerminatePackage` | 81 | Exported Function
`HamServicingQueryActiveAppsInPackage` | 80 | Exported Function
`HamServicingOpenPackageHandle` | 79 | Exported Function
`HamServicingEnableServicing` | 78 | Exported Function
`HamServicingClosePackageHandle` | 77 | Exported Function
`HamResetExternalResourcePriority` | 76 | Exported Function
`HamRemoveHostDependency` | 75 | Exported Function
`HamRemoveDependency` | 74 | Exported Function
`HamQueryTaskCompletionsForTerminateGraph` | 73 | Exported Function
`HamQueryPackageUsageInfo` | 72 | Exported Function
`HamQueryCallerTerminateReason` | 71 | Exported Function
`HamSetExternalResourcePriority` | 85 | Exported Function
`HamQueryApplicationUsageInfo` | 70 | Exported Function
`RmActivityImportanceInitialize` | 102 | Exported Function
`RmApplyResourceSet` | 104 | Exported Function
`RmUnregisterActivityHostCallbacks` | 134 | Exported Function
`RmUnregisterActivityHost` | 133 | Exported Function
`RmSetHostLimit` | 132 | Exported Function
`RmResourceSetPropertiesInitialize` | 131 | Exported Function
`RmResourceLimitsInitialize` | 130 | Exported Function
`RmResourceLimitFlagsInitialize` | 129 | Exported Function
`RmReleaseResourceSetEx` | 127 | Exported Function
`RmReleaseResourceSet` | 126 | Exported Function
`RmReleaseResources` | 128 | Exported Function
`RmRegisterResource` | 125 | Exported Function
`RmRegisterForGameMode` | 124 | Exported Function
`RmRegisterActivityHostCallbacks` | 123 | Exported Function
`RmQueryHostMemoryLimitValues` | 122 | Exported Function
`RmGetNotification` | 121 | Exported Function
`RmActivityImportanceTakeMostImportant` | 103 | Exported Function
`RmGameModeUnregisterProcessById` | 120 | Exported Function
`RmGameModeRegisterProcessById` | 118 | Exported Function
`RmGameModeRegisterProcess` | 117 | Exported Function
`RmGameModeRegisterPairedAuxiliaryProcessById` | 116 | Exported Function
`RmGameModeRegisterPairedAuxiliaryProcess` | 115 | Exported Function
`RmGameModeReenableForRegisteredProcessById` | 114 | Exported Function
`RmGameModeReenableForRegisteredProcess` | 113 | Exported Function
`RmGameModeInitializeResourceRequest` | 112 | Exported Function
`RmGameModeGetLargestValidResourceRequest` | 111 | Exported Function
`RmGameModeDisableForRegisteredProcessById` | 110 | Exported Function
`RmGameModeDisableForRegisteredProcess` | 109 | Exported Function
`RmDisconnectFromResourceManager` | 108 | Exported Function
`RmConnectToResourceManager` | 107 | Exported Function
`RmAvailabilityCheck` | 106 | Exported Function
`RmApplyResourceSetToHost` | 105 | Exported Function
`RmGameModeUnregisterProcess` | 119 | Exported Function
`HamPopulateActivityPropertiesByClass` | 69 | Exported Function
`HamPopulateActivityProperties` | 68 | Exported Function
`HamIsHostBeingDebugged` | 67 | Exported Function
`HamConnectForSessionState` | 31 | Exported Function
`HamConnectForServicing` | 30 | Exported Function
`HamConnectForFullTrust` | 29 | Exported Function
`HamConnectForExtendedExecution` | 28 | Exported Function
`HamConnectForDebugging` | 27 | Exported Function
`HamCompleteExtendedExecution` | 26 | Exported Function
`HamCloseActivity` | 25 | Exported Function
`HamAddHostDependency` | 24 | Exported Function
`HamAddDependency` | 23 | Exported Function
`DllGetClassObject` | 22 | Exported Function
`DllGetActivationFactory` | 21 | Exported Function
`DllCanUnloadNow` | 20 | Exported Function
`DeleteResourceManagerClientProxy` | 2 | Exported Function
`CrmWorkStop` | 19 | Exported Function
`HamConnectForStateChangeNotifications` | 32 | Exported Function
`CrmWorkStart` | 18 | Exported Function
`CrmUnregister` | 16 | Exported Function
`CrmSubscribe` | 15 | Exported Function
`CrmRegister` | 14 | Exported Function
`CrmActivityWindowClosedReasonUnsubscribe` | 13 | Exported Function
`CrmActivityWindowClosedReasonSubscribe` | 12 | Exported Function
`CrmActivityStop` | 11 | Exported Function
`CrmActivityStart` | 10 | Exported Function
`CrmActivityRequestAndWait` | 9 | Exported Function
`CrmActivityRequest` | 8 | Exported Function
`CrmActivityRenew` | 7 | Exported Function
`CrmActivityQueryWindowClosedReasons` | 6 | Exported Function
`CrmActivityFreeWindowClosedReasons` | 5 | Exported Function
`CrmActivityFree` | 4 | Exported Function
`CrmActivityAllocate` | 3 | Exported Function
`CrmUnsubscribe` | 17 | Exported Function
`HamConnectToServer` | 33 | Exported Function
`HamConnectToServerEx` | 34 | Exported Function
`HamCreateActivity` | 35 | Exported Function
`HamInitializeStateChangeFlags` | 66 | Exported Function
`HamInitializeActivityDynamicProperties` | 65 | Exported Function
`HamInitializeActivityAutoRestartProperties` | 64 | Exported Function
`HamHostIdRetrieveDynamicId` | 63 | Exported Function
`HamHostIdInitializeKey` | 62 | Exported Function
`HamHostIdFindOrCreate` | 61 | Exported Function
`HamHostIdCreateSingleUse` | 60 | Exported Function
`HamGetPackageInterruptiveUIState` | 59 | Exported Function
`HamGetInterruptiveUIStateForAumid` | 58 | Exported Function
`HamGetApplicationStateForPsmKey` | 57 | Exported Function
`HamGetApplicationInterruptiveUIState` | 56 | Exported Function
`HamFullTrustTerminatePackage` | 55 | Exported Function
`HamFullTrustOpenPackageHandle` | 54 | Exported Function
`HamFullTrustClosePackageHandle` | 53 | Exported Function
`HamDisconnectFromServer` | 52 | Exported Function
`HamDisconnectForStateChangeNotifications` | 51 | Exported Function
`HamDisconnectForSessionState` | 50 | Exported Function
`HamCreateActivityEx` | 36 | Exported Function
`HamCreateActivityForProcess` | 37 | Exported Function
`HamCreateAutoRestartActivity` | 38 | Exported Function
`HamCreateExtendedExecution` | 39 | Exported Function
`HamDebugClosePackageHandle` | 40 | Exported Function
`HamDebugModeEnable` | 41 | Exported Function
`RmUnregisterForGameMode` | 135 | Exported Function
`HamDebugOpenPackageHandle` | 42 | Exported Function
`HamDebugSuspendPackage` | 44 | Exported Function
`HamDebugTerminatePackage` | 45 | Exported Function
`HamDisconnectForDebugging` | 46 | Exported Function
`HamDisconnectForExtendedExecution` | 47 | Exported Function
`HamDisconnectForFullTrust` | 48 | Exported Function
`HamDisconnectForServicing` | 49 | Exported Function
`HamDebugQueryPackageState` | 43 | Exported Function
`RmUpdateResourceSetProperties` | 136 | Exported Function


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


