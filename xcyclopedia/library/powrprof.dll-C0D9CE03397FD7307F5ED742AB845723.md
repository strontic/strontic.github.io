---
title: powrprof.dll | Power Profile Helper DLL
excerpt: What is powrprof.dll?
---

# powrprof.dll 

* File Path: `C:\Windows\system32\powrprof.dll`
* Description: Power Profile Helper DLL

## Hashes

Type | Hash
-- | --
MD5 | `C0D9CE03397FD7307F5ED742AB845723`
SHA1 | `50E31E70EA5D3397D7287A44E401220C933649DE`
SHA256 | `A9E7C54BA076393FC9037849F0ADACC7C1350325DF326C907B9238AEF50F5565`
SHA384 | `13F19B05569D9789942678E5414F472AA1BA31479BDE450F805271A0AE9E35A163C093C7D63DEA1AFBC049EBEEFE0A15`
SHA512 | `BA99AFAC1B6A31725846B1CFDE74C8866131CF4E4D14562F7161F87C2D4989449A58804518E48D6104C4FDFCF5D48A869CB4B7D0759DBB9D7EB60FD1EB2DDE0D`
SSDEEP | `6144:m3nwY5IO12FmKA/JbdI/PjQfmDdYs8nkZ0Yj:QwtO12FmKA/JGnsfmZ751`
IMP | `1767FC1F6BC4E7E9EA7A40C5731B08E9`
PESHA1 | `E4EA434107005C61CAAAAABC4BA53E6754A74A69`
PE256 | `4C39B8750410C7F6AF77429F4213F2E300523F17C9067BEED16CA81F6DC650EF`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CallNtPowerInformation` | 1 (0x1) | Exported Function | 0x0000000180001a30 | 0x00001a30
`PowerSettingAccessCheckEx` | 93 (0x5d) | Exported Function | 0x000000018000c570 | 0x0000c570
`PowerSettingAccessCheck` | 92 (0x5c) | Exported Function | 0x0000000180001140 | 0x00001140
`PowerSetBrightnessAndTransitionTimes` | 90 (0x5a) | Exported Function | 0x000000018000fb30 | 0x0000fb30
`PowerSetAlsBrightnessOffset` | 89 (0x59) | Exported Function | 0x000000018000fae0 | 0x0000fae0
`PowerSetActiveScheme` | 88 (0x58) | Exported Function | 0x00000001800010d0 | 0x000010d0
`PowerSetActiveOverlayScheme` | 87 (0x57) | Exported Function | 0x000000018000f8a0 | 0x0000f8a0
`PowerRestoreIndividualDefaultPowerScheme` | 86 (0x56) | Exported Function | 0x000000018000c340 | 0x0000c340
`PowerRestoreDefaultPowerSchemes` | 85 (0x55) | Exported Function | 0x000000018000c2b0 | 0x0000c2b0
`PowerRestoreDCDefaultIndex` | 84 (0x54) | Exported Function | 0x000000018000e640 | 0x0000e640
`PowerRestoreACDefaultIndex` | 83 (0x53) | Exported Function | 0x000000018000e550 | 0x0000e550
`PowerReportThermalEvent` | 82 (0x52) | Exported Function | 0x000000018000c250 | 0x0000c250
`PowerReportLimitsEvent` | 81 (0x51) | Exported Function | 0x0000000180011f50 | 0x00011f50
`PowerReplaceDefaultPowerSchemes` | 80 (0x50) | Exported Function | 0x000000018000c1b0 | 0x0000c1b0
`PowerRemovePowerSetting` | 79 (0x4f) | Exported Function | 0x000000018000e4b0 | 0x0000e4b0
`PowerRegisterSuspendResumeNotification` | 78 (0x4e) | Exported Function | 0x00000001800029b0 | 0x000029b0
`PowerRegisterLimitsPolicy` | 77 (0x4d) | Exported Function | 0x0000000180011cb0 | 0x00011cb0
`PowerRegisterLimitsMitigation` | 76 (0x4c) | Exported Function | 0x0000000180011500 | 0x00011500
`PowerRegisterForEffectivePowerModeNotifications` | 75 (0x4b) | Exported Function | 0x000000018000fd30 | 0x0000fd30
`PowerRegisterEnvironmentalMonitor` | 74 (0x4a) | Exported Function | 0x0000000180010930 | 0x00010930
`PowerReapplyActiveScheme` | 73 (0x49) | Exported Function | 0x000000018000f810 | 0x0000f810
`PowerReadValueUnitsSpecifier` | 72 (0x48) | Exported Function | 0x000000018000de20 | 0x0000de20
`PowerReadValueMin` | 71 (0x47) | Exported Function | 0x000000018000dd20 | 0x0000dd20
`PowerReadValueMax` | 70 (0x46) | Exported Function | 0x000000018000dc20 | 0x0000dc20
`PowerReadValueIncrement` | 69 (0x45) | Exported Function | 0x000000018000db20 | 0x0000db20
`PowerReadSettingAttributes` | 68 (0x44) | Exported Function | 0x000000018000d930 | 0x0000d930
`PowerReadSecurityDescriptor` | 67 (0x43) | Exported Function | 0x000000018000d750 | 0x0000d750
`PowerReadPossibleValue` | 66 (0x42) | Exported Function | 0x000000018000d650 | 0x0000d650
`PowerSettingRegisterNotification` | 94 (0x5e) | Exported Function | 0x0000000180001fa0 | 0x00001fa0
`PowerSettingRegisterNotificationEx` | 95 (0x5f) | Exported Function | 0x0000000180001fd0 | 0x00001fd0
`PowerSettingUnregisterNotification` | 96 (0x60) | Exported Function | 0x0000000180002590 | 0x00002590
`PowerSetUserAwayPrediction` | 91 (0x5b) | Exported Function | 0x000000018000c3e0 | 0x0000c3e0
`WriteGlobalPwrPolicy` | 124 (0x7c) | Exported Function | 0x00000001800072c0 | 0x000072c0
`ValidatePowerPolicies` | 123 (0x7b) | Exported Function | 0x0000000180007160 | 0x00007160
`SetSuspendState` | 122 (0x7a) | Exported Function | 0x0000000180006c40 | 0x00006c40
`SetActivePwrScheme` | 121 (0x79) | Exported Function | 0x00000001800069e0 | 0x000069e0
`ReadPwrScheme` | 120 (0x78) | Exported Function | 0x00000001800067a0 | 0x000067a0
`ReadProcessorPwrScheme` | 119 (0x77) | Exported Function | 0x0000000180006620 | 0x00006620
`ReadGlobalPwrPolicy` | 118 (0x76) | Exported Function | 0x0000000180006440 | 0x00006440
`PowerWriteValueUnitsSpecifier` | 117 (0x75) | Exported Function | 0x000000018000f4e0 | 0x0000f4e0
`PowerWriteValueMin` | 116 (0x74) | Exported Function | 0x000000018000f400 | 0x0000f400
`PowerWriteValueMax` | 115 (0x73) | Exported Function | 0x000000018000f320 | 0x0000f320
`PowerWriteValueIncrement` | 114 (0x72) | Exported Function | 0x000000018000f240 | 0x0000f240
`PowerWriteSettingAttributes` | 113 (0x71) | Exported Function | 0x000000018000f160 | 0x0000f160
`PowerWriteSecurityDescriptor` | 112 (0x70) | Exported Function | 0x000000018000f060 | 0x0000f060
`PowerReadPossibleFriendlyName` | 65 (0x41) | Exported Function | 0x000000018000d600 | 0x0000d600
`PowerWritePossibleValue` | 111 (0x6f) | Exported Function | 0x000000018000ef70 | 0x0000ef70
`PowerWritePossibleDescription` | 109 (0x6d) | Exported Function | 0x000000018000ed90 | 0x0000ed90
`PowerWriteIconResourceSpecifier` | 108 (0x6c) | Exported Function | 0x000000018000eca0 | 0x0000eca0
`PowerWriteFriendlyName` | 107 (0x6b) | Exported Function | 0x000000018000ebc0 | 0x0000ebc0
`PowerWriteDescription` | 106 (0x6a) | Exported Function | 0x000000018000ead0 | 0x0000ead0
`PowerWriteDCValueIndex` | 105 (0x69) | Exported Function | 0x000000018000e9e0 | 0x0000e9e0
`PowerWriteDCDefaultIndex` | 104 (0x68) | Exported Function | 0x000000018000e900 | 0x0000e900
`PowerWriteACValueIndex` | 103 (0x67) | Exported Function | 0x000000018000e810 | 0x0000e810
`PowerWriteACDefaultIndex` | 102 (0x66) | Exported Function | 0x000000018000e730 | 0x0000e730
`PowerUpdateLimitsMitigation` | 101 (0x65) | Exported Function | 0x0000000180011760 | 0x00011760
`PowerUpdateEnvironmentalMonitorThresholds` | 100 (0x64) | Exported Function | 0x0000000180010c20 | 0x00010c20
`PowerUpdateEnvironmentalMonitorState` | 99 (0x63) | Exported Function | 0x0000000180010b60 | 0x00010b60
`PowerUnregisterSuspendResumeNotification` | 98 (0x62) | Exported Function | 0x0000000180002bf0 | 0x00002bf0
`PowerUnregisterFromEffectivePowerModeNotifications` | 97 (0x61) | Exported Function | 0x0000000180010130 | 0x00010130
`PowerWritePossibleFriendlyName` | 110 (0x6e) | Exported Function | 0x000000018000ee80 | 0x0000ee80
`PowerReadPossibleDescription` | 64 (0x40) | Exported Function | 0x000000018000d5b0 | 0x0000d5b0
`PowerReadIconResourceSpecifier` | 63 (0x3f) | Exported Function | 0x000000018000d560 | 0x0000d560
`PowerReadFriendlyName` | 62 (0x3e) | Exported Function | 0x0000000180001360 | 0x00001360
`PowerCreateSetting` | 29 (0x1d) | Exported Function | 0x000000018000dfc0 | 0x0000dfc0
`PowerCreatePossibleSetting` | 28 (0x1c) | Exported Function | 0x000000018000df10 | 0x0000df10
`PowerCloseLimitsPolicy` | 27 (0x1b) | Exported Function | 0x0000000180011bd0 | 0x00011bd0
`PowerCloseLimitsMitigation` | 26 (0x1a) | Exported Function | 0x0000000180011370 | 0x00011370
`PowerCloseEnvironmentalMonitor` | 25 (0x19) | Exported Function | 0x00000001800107c0 | 0x000107c0
`PowerClearUserAwayPrediction` | 24 (0x18) | Exported Function | 0x000000018000b980 | 0x0000b980
`PowerCanRestoreIndividualDefaultPowerScheme` | 23 (0x17) | Exported Function | 0x000000018000b860 | 0x0000b860
`PowerApplySettingChanges` | 22 (0x16) | Exported Function | 0x000000018000de70 | 0x0000de70
`PowerApplyPowerRequestOverride` | 21 (0x15) | Exported Function | 0x000000018000f5c0 | 0x0000f5c0
`MergeLegacyPwrScheme` | 20 (0x14) | Exported Function | 0x0000000180005d10 | 0x00005d10
`LoadCurrentPwrScheme` | 19 (0x13) | Exported Function | 0x0000000180005d10 | 0x00005d10
`IsPwrSuspendAllowed` | 18 (0x12) | Exported Function | 0x0000000180005cb0 | 0x00005cb0
`IsPwrShutdownAllowed` | 17 (0x11) | Exported Function | 0x0000000180005c60 | 0x00005c60
`PowerDebugDifPowerPolicies` | 30 (0x1e) | Exported Function | 0x0000000180007820 | 0x00007820
`IsPwrHibernateAllowed` | 16 (0x10) | Exported Function | 0x0000000180005c00 | 0x00005c00
`GUIDFormatToPowerPolicy` | 10 (0xa) | Exported Function | 0x000000018000b240 | 0x0000b240
`GUIDFormatToGlobalPowerPolicy` | 9 (0x9) | Exported Function | 0x000000018000ad80 | 0x0000ad80
`GetPwrDiskSpindownRange` | 14 (0xe) | Exported Function | 0x0000000180005b90 | 0x00005b90
`GetPwrCapabilities` | 13 (0xd) | Exported Function | 0x00000001800026f0 | 0x000026f0
`GetCurrentPowerPolicies` | 12 (0xc) | Exported Function | 0x0000000180005b00 | 0x00005b00
`GetActivePwrScheme` | 11 (0xb) | Exported Function | 0x0000000180005a40 | 0x00005a40
`EnumPwrSchemes` | 8 (0x8) | Exported Function | 0x00000001800053d0 | 0x000053d0
`DevicePowerSetDeviceState` | 7 (0x7) | Exported Function | 0x000000018000a6b0 | 0x0000a6b0
`DevicePowerOpen` | 6 (0x6) | Exported Function | 0x000000018000a630 | 0x0000a630
`DevicePowerEnumDevices` | 5 (0x5) | Exported Function | 0x0000000180009ff0 | 0x00009ff0
`DevicePowerClose` | 4 (0x4) | Exported Function | 0x0000000180009ee0 | 0x00009ee0
`DeletePwrScheme` | 3 (0x3) | Exported Function | 0x0000000180005260 | 0x00005260
`CanUserWritePwrScheme` | 2 (0x2) | Exported Function | 0x00000001800051b0 | 0x000051b0
`IsAdminOverrideActive` | 15 (0xf) | Exported Function | 0x0000000180005bf0 | 0x00005bf0
`WriteProcessorPwrScheme` | 125 (0x7d) | Exported Function | 0x0000000180006620 | 0x00006620
`PowerDebugDifSystemPowerPolicies` | 31 (0x1f) | Exported Function | 0x00000001800080e0 | 0x000080e0
`PowerDebugDumpPowerScheme` | 33 (0x21) | Exported Function | 0x0000000180008bb0 | 0x00008bb0
`PowerReadDescription` | 61 (0x3d) | Exported Function | 0x000000018000d510 | 0x0000d510
`PowerReadDCValueIndexEx` | 60 (0x3c) | Exported Function | 0x000000018000d4e0 | 0x0000d4e0
`PowerReadDCValueIndex` | 59 (0x3b) | Exported Function | 0x000000018000d4a0 | 0x0000d4a0
`PowerReadDCValue` | 58 (0x3a) | Exported Function | 0x000000018000d3b0 | 0x0000d3b0
`PowerReadDCDefaultIndex` | 57 (0x39) | Exported Function | 0x000000018000d2b0 | 0x0000d2b0
`PowerReadACValueIndexEx` | 56 (0x38) | Exported Function | 0x000000018000d280 | 0x0000d280
`PowerReadACValueIndex` | 55 (0x37) | Exported Function | 0x0000000180001700 | 0x00001700
`PowerReadACValue` | 54 (0x36) | Exported Function | 0x0000000180001010 | 0x00001010
`PowerReadACDefaultIndex` | 53 (0x35) | Exported Function | 0x000000018000d180 | 0x0000d180
`PowerPolicyToGUIDFormat` | 52 (0x34) | Exported Function | 0x000000018000bc40 | 0x0000bc40
`PowerOpenUserPowerKey` | 51 (0x33) | Exported Function | 0x000000018000bbc0 | 0x0000bbc0
`PowerOpenSystemPowerKey` | 50 (0x32) | Exported Function | 0x000000018000bb40 | 0x0000bb40
`PowerIsSettingRangeDefined` | 49 (0x31) | Exported Function | 0x000000018000cf80 | 0x0000cf80
`PowerDebugDumpPowerPolicy` | 32 (0x20) | Exported Function | 0x00000001800087c0 | 0x000087c0
`PowerInformationWithPrivileges` | 48 (0x30) | Exported Function | 0x0000000180002e90 | 0x00002e90
`PowerGetUserAwayMinPredictionConfidence` | 46 (0x2e) | Exported Function | 0x000000018000ba10 | 0x0000ba10
`PowerGetOverlaySchemes` | 45 (0x2d) | Exported Function | 0x000000018000ce30 | 0x0000ce30
`PowerGetEffectiveOverlayScheme` | 44 (0x2c) | Exported Function | 0x000000018000f730 | 0x0000f730
`PowerGetAdaptiveStandbyDiagnostics` | 43 (0x2b) | Exported Function | 0x000000018000f940 | 0x0000f940
`PowerGetActualOverlayScheme` | 42 (0x2a) | Exported Function | 0x000000018000f650 | 0x0000f650
`PowerGetActiveScheme` | 41 (0x29) | Exported Function | 0x00000001800018e0 | 0x000018e0
`PowerEnumerate` | 40 (0x28) | Exported Function | 0x0000000180001290 | 0x00001290
`PowerDuplicateScheme` | 39 (0x27) | Exported Function | 0x000000018000e100 | 0x0000e100
`PowerDeterminePlatformRoleEx` | 38 (0x26) | Exported Function | 0x0000000180002910 | 0x00002910
`PowerDeterminePlatformRole` | 37 (0x25) | Exported Function | 0x00000001800028c0 | 0x000028c0
`PowerDeleteScheme` | 36 (0x24) | Exported Function | 0x000000018000e060 | 0x0000e060
`PowerDebugDumpSystemPowerPolicy` | 35 (0x23) | Exported Function | 0x0000000180009820 | 0x00009820
`PowerDebugDumpSystemPowerCapabilities` | 34 (0x22) | Exported Function | 0x00000001800095b0 | 0x000095b0
`PowerImportPowerScheme` | 47 (0x2f) | Exported Function | 0x000000018000e2f0 | 0x0000e2f0
`WritePwrScheme` | 126 (0x7e) | Exported Function | 0x0000000180007620 | 0x00007620


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: POWRPROF.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/a9e7c54ba076393fc9037849f0adacc7c1350325df326c907b9238aef50f5565/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\powrprof.dll](powrprof.dll-D280B4BF77C6B3CD8CA5D38E14F7A020.md) | 52




MIT License. Copyright (c) 2020 Strontic.


