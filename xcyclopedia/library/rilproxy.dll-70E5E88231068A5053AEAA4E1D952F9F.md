---
title: rilproxy.dll | Windows Cellular RIL Proxy
excerpt: What is rilproxy.dll?
---

# rilproxy.dll 

* File Path: `C:\Windows\system32\rilproxy.dll`
* Description: Windows Cellular RIL Proxy

## Hashes

Type | Hash
-- | --
MD5 | `70E5E88231068A5053AEAA4E1D952F9F`
SHA1 | `B1BE0D3EC94D1F993B6D19D68F90C387CB026799`
SHA256 | `8FBF5ECB938268D5DF468D723BFF8FF9EC6A17FBEE04C8847E889A027190A2F9`
SHA384 | `6F0926D347D58A274ADF2ED5FBF51A99CD36D9D7F34559A9F322612A1CCAA322B59B3863AA99479AFDAEFE44CB227614`
SHA512 | `A2AAEE081FDFBB3D515DEE30E92CDEEAEF8551ACC3673618421DA5ACC99E79199BD4D1FB85E480CD25FC9F008624C2A3D21BDE84952022B329190E474C6B94DB`
SSDEEP | `768:5SeTJsDf+jk12Q1BnZxLFeX3ofC+Z0GGaDCbv/GaKPv6h8B51iWwGrEc/00vbf8a:3bqxFeX3o5kiv88g7GrEc/00vbf8Y+k`
IMP | `BDDB3C0FDC4E1ABAF87814053B2C07F8`
PESHA1 | `C2AAA8B7C8F82C230B30C5B828F2523D76B39D92`
PE256 | `806368F989CA5E1EECFE89FD78C693AE295F263630431A014D92C836D5C21718`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`RIL_AddCallForwarding` | 55 (0x37) | Exported Function | 0x00000001800033b0 | 0x000033b0
`RIL_SetCallBarringStatus` | 58 (0x3a) | Exported Function | 0x0000000180003590 | 0x00003590
`RIL_SendUiccToolkitEnvelope` | 94 (0x5e) | Exported Function | 0x0000000180005590 | 0x00005590
`RIL_SendUiccToolkitCmdResponse` | 48 (0x30) | Exported Function | 0x00000001800054b0 | 0x000054b0
`RIL_SendSupServiceDataResponse` | 97 (0x61) | Exported Function | 0x0000000180003c10 | 0x00003c10
`RIL_SendSupServiceData` | 67 (0x43) | Exported Function | 0x0000000180003b20 | 0x00003b20
`RIL_SendRTT` | 138 (0x8a) | Exported Function | 0x0000000180003d40 | 0x00003d40
`RIL_SendRestrictedUiccCmd` | 17 (0x11) | Exported Function | 0x0000000180004210 | 0x00004210
`RIL_SendMsgAck_V1` | 101 (0x65) | Exported Function | 0x00000001800028c0 | 0x000028c0
`RIL_SendMsgAck` | 129 (0x81) | Exported Function | 0x0000000180002940 | 0x00002940
`RIL_SendMsg` | 80 (0x50) | Exported Function | 0x0000000180002810 | 0x00002810
`RIL_SendFlash` | 66 (0x42) | Exported Function | 0x0000000180003a40 | 0x00003a40
`RIL_SendDTMF` | 68 (0x44) | Exported Function | 0x0000000180003de0 | 0x00003de0
`RIL_ResetModem` | 125 (0x7d) | Exported Function | 0x0000000180001f60 | 0x00001f60
`RIL_RemoveCallForwarding` | 56 (0x38) | Exported Function | 0x00000001800034b0 | 0x000034b0
`RIL_SetCallForwardingStatus` | 54 (0x36) | Exported Function | 0x0000000180003330 | 0x00003330
`RIL_RegisterUiccToolkitService` | 91 (0x5b) | Exported Function | 0x0000000180005370 | 0x00005370
`RIL_ReadMsg` | 72 (0x48) | Exported Function | 0x00000001800024c0 | 0x000024c0
`RIL_RadioStatePasswordCompare` | 88 (0x58) | Exported Function | 0x0000000180001c40 | 0x00001c40
`RIL_RadioStateGetPasswordRetryCount` | 89 (0x59) | Exported Function | 0x0000000180001ce0 | 0x00001ce0
`RIL_OpenUiccLogicalChannel` | 105 (0x69) | Exported Function | 0x00000001800045c0 | 0x000045c0
`RIL_ManageCalls_V3` | 132 (0x84) | Exported Function | 0x0000000180002f30 | 0x00002f30
`RIL_ManageCalls_V2` | 118 (0x76) | Exported Function | 0x0000000180002e20 | 0x00002e20
`RIL_ManageCalls_V1` | 51 (0x33) | Exported Function | 0x0000000180002db0 | 0x00002db0
`RIL_ManageCalls` | 137 (0x89) | Exported Function | 0x00000001800030c0 | 0x000030c0
`RIL_Initialize` | 1 (0x1) | Exported Function | 0x0000000180001fe0 | 0x00001fe0
`RIL_GetUiccToolkitProfile` | 93 (0x5d) | Exported Function | 0x0000000180005490 | 0x00005490
`RIL_GetUiccServiceState` | 110 (0x6e) | Exported Function | 0x0000000180005670 | 0x00005670
`RIL_GetUiccServiceLock` | 23 (0x17) | Exported Function | 0x0000000180004950 | 0x00004950
`RIL_GetUiccRecordStatus` | 16 (0x10) | Exported Function | 0x00000001800041a0 | 0x000041a0
`RIL_GetUiccPRLID` | 19 (0x13) | Exported Function | 0x00000001800044c0 | 0x000044c0
`RIL_ReadPhonebookEntries` | 31 (0x1f) | Exported Function | 0x0000000180004ee0 | 0x00004ee0
`RIL_GetUiccLockState` | 22 (0x16) | Exported Function | 0x0000000180004900 | 0x00004900
`RIL_SetCallWaitingStatus` | 61 (0x3d) | Exported Function | 0x00000001800038d0 | 0x000038d0
`RIL_SetDMProfileConfigInfo` | 96 (0x60) | Exported Function | 0x0000000180001230 | 0x00001230
`RIL_WriteAdditionalNumberString` | 99 (0x63) | Exported Function | 0x0000000180005240 | 0x00005240
`RIL_WatchUiccFileChange` | 18 (0x12) | Exported Function | 0x00000001800043d0 | 0x000043d0
`RIL_VerifyUiccLock` | 24 (0x18) | Exported Function | 0x00000001800049a0 | 0x000049a0
`RIL_UnblockUiccLock` | 26 (0x1a) | Exported Function | 0x0000000180004b60 | 0x00004b60
`RIL_StopModemLogs` | 123 (0x7b) | Exported Function | 0x00000001800058c0 | 0x000058c0
`RIL_StopDTMF` | 70 (0x46) | Exported Function | 0x0000000180003f10 | 0x00003f10
`RIL_StartModemLogs` | 122 (0x7a) | Exported Function | 0x00000001800058a0 | 0x000058a0
`RIL_StartDTMF` | 69 (0x45) | Exported Function | 0x0000000180003ed0 | 0x00003ed0
`RIL_SetUiccToolkitProfile` | 92 (0x5c) | Exported Function | 0x00000001800053b0 | 0x000053b0
`RIL_SetUiccServiceState` | 111 (0x6f) | Exported Function | 0x00000001800056b0 | 0x000056b0
`RIL_SetUiccLockEnabled` | 25 (0x19) | Exported Function | 0x0000000180004a80 | 0x00004a80
`RIL_SetTerminalCapability` | 134 (0x86) | Exported Function | 0x0000000180004800 | 0x00004800
`RIL_SetSystemSelectionPrefs_V1` | 41 (0x29) | Exported Function | 0x00000001800014a0 | 0x000014a0
`RIL_SetSystemSelectionPrefs` | 126 (0x7e) | Exported Function | 0x0000000180001590 | 0x00001590
`RIL_SetCellBroadcastMsgConfig` | 76 (0x4c) | Exported Function | 0x0000000180002620 | 0x00002620
`RIL_SetSMSC` | 82 (0x52) | Exported Function | 0x0000000180002a10 | 0x00002a10
`RIL_SetRFState_V1` | 102 (0x66) | Exported Function | 0x0000000180001de0 | 0x00001de0
`RIL_SetRFState` | 119 (0x77) | Exported Function | 0x0000000180001e20 | 0x00001e20
`RIL_SetRadioStateDetails` | 87 (0x57) | Exported Function | 0x0000000180001b60 | 0x00001b60
`RIL_SetRadioConfiguration` | 37 (0x25) | Exported Function | 0x0000000180001380 | 0x00001380
`RIL_SetPSMediaConfiguration` | 130 (0x82) | Exported Function | 0x00000001800018f0 | 0x000018f0
`RIL_SetPreferredOperatorList` | 109 (0x6d) | Exported Function | 0x0000000180001760 | 0x00001760
`RIL_SetNotificationFilterState` | 11 (0xb) | Exported Function | 0x0000000180001320 | 0x00001320
`RIL_SetMsgMemoryStatus` | 79 (0x4f) | Exported Function | 0x00000001800027d0 | 0x000027d0
`RIL_SetMsgInUiccStatus` | 78 (0x4e) | Exported Function | 0x0000000180002760 | 0x00002760
`RIL_SetGeolocationData` | 133 (0x85) | Exported Function | 0x0000000180001a50 | 0x00001a50
`RIL_SetExecutorRFState` | 116 (0x74) | Exported Function | 0x00000001800040c0 | 0x000040c0
`RIL_SetExecutorFocus` | 113 (0x71) | Exported Function | 0x0000000180003f70 | 0x00003f70
`RIL_SetExecutorConfig` | 39 (0x27) | Exported Function | 0x00000001800013e0 | 0x000013e0
`RIL_SetEquipmentState` | 10 (0xa) | Exported Function | 0x00000001800012e0 | 0x000012e0
`RIL_SetSlotPower` | 15 (0xf) | Exported Function | 0x0000000180004160 | 0x00004160
`RIL_WriteMsg` | 73 (0x49) | Exported Function | 0x0000000180002500 | 0x00002500
`RIL_GetUiccATR` | 104 (0x68) | Exported Function | 0x0000000180004580 | 0x00004580
`RIL_GetTerminalCapability` | 135 (0x87) | Exported Function | 0x00000001800048e0 | 0x000048e0
`RIL_GetCardInfo` | 14 (0xe) | Exported Function | 0x0000000180004120 | 0x00004120
`RIL_GetCallWaitingSettings` | 60 (0x3c) | Exported Function | 0x0000000180003860 | 0x00003860
`RIL_GetCallForwardingSettings` | 53 (0x35) | Exported Function | 0x00000001800032c0 | 0x000032c0
`RIL_GetCallerIdSettings` | 62 (0x3e) | Exported Function | 0x0000000180003940 | 0x00003940
`RIL_GetCallBarringStatus` | 57 (0x39) | Exported Function | 0x0000000180003520 | 0x00003520
`RIL_GetAllEmergencyNumbers` | 36 (0x24) | Exported Function | 0x0000000180005350 | 0x00005350
`RIL_GetAllAdditionalNumberStrings` | 35 (0x23) | Exported Function | 0x0000000180005200 | 0x00005200
`RIL_ExchangeUiccAPDU` | 108 (0x6c) | Exported Function | 0x0000000180004710 | 0x00004710
`RIL_EnumerateSlots` | 13 (0xd) | Exported Function | 0x0000000180004100 | 0x00004100
`RIL_EnableNotifications` | 4 (0x4) | Exported Function | 0x00000001800021c0 | 0x000021c0
`RIL_EnableModemFilters` | 120 (0x78) | Exported Function | 0x0000000180005820 | 0x00005820
`RIL_EmergencyModeControl` | 52 (0x34) | Exported Function | 0x0000000180003280 | 0x00003280
`RIL_DrainModemLogs` | 124 (0x7c) | Exported Function | 0x00000001800058e0 | 0x000058e0
`RIL_DisableNotifications` | 5 (0x5) | Exported Function | 0x00000001800022b0 | 0x000022b0
`RIL_GetCellBroadcastMsgConfig` | 75 (0x4b) | Exported Function | 0x00000001800025e0 | 0x000025e0
`RIL_DisableModemFilters` | 121 (0x79) | Exported Function | 0x0000000180005860 | 0x00005860
`RIL_Dial` | 117 (0x75) | Exported Function | 0x0000000180002c20 | 0x00002c20
`RIL_DevSpecific` | 90 (0x5a) | Exported Function | 0x0000000180001d20 | 0x00001d20
`RIL_DeletePhonebookEntry` | 33 (0x21) | Exported Function | 0x00000001800050c0 | 0x000050c0
`RIL_DeleteMsg` | 74 (0x4a) | Exported Function | 0x00000001800025a0 | 0x000025a0
`RIL_DeleteAdditionalNumberString` | 100 (0x64) | Exported Function | 0x0000000180005310 | 0x00005310
`RIL_Deinitialize` | 2 (0x2) | Exported Function | 0x0000000180002080 | 0x00002080
`RIL_DeactivatePerso` | 30 (0x1e) | Exported Function | 0x0000000180004e40 | 0x00004e40
`RIL_CloseUiccLogicalChannelGroup` | 107 (0x6b) | Exported Function | 0x00000001800046d0 | 0x000046d0
`RIL_CloseUiccLogicalChannel` | 106 (0x6a) | Exported Function | 0x0000000180004690 | 0x00004690
`RIL_ChangeUiccLockPassword` | 27 (0x1b) | Exported Function | 0x0000000180004c90 | 0x00004c90
`RIL_ChangeCallBarringPassword` | 59 (0x3b) | Exported Function | 0x00000001800036a0 | 0x000036a0
`RIL_CancelSupServiceDataSession` | 98 (0x62) | Exported Function | 0x0000000180003d00 | 0x00003d00
`RIL_CancelGetOperatorList` | 127 (0x7f) | Exported Function | 0x0000000180001870 | 0x00001870
`RIL_AvoidCDMASystem` | 128 (0x80) | Exported Function | 0x0000000180001fa0 | 0x00001fa0
`RIL_Dial_V1` | 50 (0x32) | Exported Function | 0x0000000180002b30 | 0x00002b30
`RIL_GetUiccAppPersoCheckState` | 28 (0x1c) | Exported Function | 0x0000000180004dc0 | 0x00004dc0
`RIL_GetCurrentRegStatus` | 45 (0x2d) | Exported Function | 0x0000000180001830 | 0x00001830
`RIL_GetDeviceInfo` | 8 (0x8) | Exported Function | 0x00000001800011b0 | 0x000011b0
`RIL_GetSystemSelectionPrefs` | 42 (0x2a) | Exported Function | 0x00000001800016a0 | 0x000016a0
`RIL_GetSubscriberNumbers` | 21 (0x15) | Exported Function | 0x0000000180004540 | 0x00004540
`RIL_GetSMSC` | 81 (0x51) | Exported Function | 0x00000001800029d0 | 0x000029d0
`RIL_GetSignalQuality` | 46 (0x2e) | Exported Function | 0x00000001800019d0 | 0x000019d0
`RIL_GetRFState` | 103 (0x67) | Exported Function | 0x0000000180001f40 | 0x00001f40
`RIL_GetRadioStateGroups` | 85 (0x55) | Exported Function | 0x0000000180001ae0 | 0x00001ae0
`RIL_GetRadioStateDetails` | 86 (0x56) | Exported Function | 0x0000000180001b20 | 0x00001b20
`RIL_GetRadioConfiguration` | 38 (0x26) | Exported Function | 0x00000001800013c0 | 0x000013c0
`RIL_GetPSMediaConfiguration` | 131 (0x83) | Exported Function | 0x00000001800018b0 | 0x000018b0
`RIL_GetPreferredOperatorList` | 44 (0x2c) | Exported Function | 0x0000000180001720 | 0x00001720
`RIL_GetPositionInfo` | 84 (0x54) | Exported Function | 0x0000000180001a10 | 0x00001a10
`RIL_GetPhonebookOptions` | 34 (0x22) | Exported Function | 0x00000001800051c0 | 0x000051c0
`RIL_GetPersoDeactivationState` | 29 (0x1d) | Exported Function | 0x0000000180004e00 | 0x00004e00
`RIL_GetOperatorList` | 43 (0x2b) | Exported Function | 0x00000001800016e0 | 0x000016e0
`RIL_GetDevCaps` | 7 (0x7) | Exported Function | 0x0000000180001170 | 0x00001170
`RIL_GetNumberOfModems` | 3 (0x3) | Exported Function | 0x00000001800020c0 | 0x000020c0
`RIL_GetMsgServiceOptions` | 71 (0x47) | Exported Function | 0x0000000180002480 | 0x00002480
`RIL_GetMsgInUiccStatus` | 77 (0x4d) | Exported Function | 0x0000000180002720 | 0x00002720
`RIL_GetIMSStatus` | 83 (0x53) | Exported Function | 0x0000000180002af0 | 0x00002af0
`RIL_GetIMSI` | 20 (0x14) | Exported Function | 0x0000000180004500 | 0x00004500
`RIL_GetHideIdSettings` | 65 (0x41) | Exported Function | 0x0000000180003a00 | 0x00003a00
`RIL_GetHideConnectedIdSettings` | 64 (0x40) | Exported Function | 0x00000001800039c0 | 0x000039c0
`RIL_GetExecutorRFState` | 115 (0x73) | Exported Function | 0x0000000180004080 | 0x00004080
`RIL_GetExecutorFocus` | 112 (0x70) | Exported Function | 0x0000000180003f50 | 0x00003f50
`RIL_GetExecutorConfig` | 40 (0x28) | Exported Function | 0x0000000180001460 | 0x00001460
`RIL_GetEquipmentState` | 9 (0x9) | Exported Function | 0x00000001800012c0 | 0x000012c0
`RIL_GetEmergencyMode` | 114 (0x72) | Exported Function | 0x0000000180004040 | 0x00004040
`RIL_GetDriverVersion` | 6 (0x6) | Exported Function | 0x0000000180001130 | 0x00001130
`RIL_GetDMProfileConfigInfo` | 95 (0x5f) | Exported Function | 0x00000001800011f0 | 0x000011f0
`RIL_GetDialedIdSettings` | 63 (0x3f) | Exported Function | 0x0000000180003980 | 0x00003980
`RIL_GetNotificationFilterState` | 12 (0xc) | Exported Function | 0x0000000180001360 | 0x00001360
`RIL_WritePhonebookEntry` | 32 (0x20) | Exported Function | 0x0000000180004f50 | 0x00004f50


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RilProxy.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8fbf5ecb938268d5df468d723bff8ff9ec6a17fbee04c8847e889a027190a2f9/detection/





MIT License. Copyright (c) 2020 Strontic.


