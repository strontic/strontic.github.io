---
title: SensorsNativeApi.dll | Sensors Native API
excerpt: What is SensorsNativeApi.dll?
---

# SensorsNativeApi.dll 

* File Path: `C:\Windows\SysWOW64\SensorsNativeApi.dll`
* Description: Sensors Native API

## Hashes

Type | Hash
-- | --
MD5 | `B225433240CA85FBC916A8EB6377EB13`
SHA1 | `DAFA8EA9E9A66BA464786410ECAAF67F24E84CE1`
SHA256 | `3443EC51ED1248320CD8B8FAB4F6236C42F221C8F38CC712D2F69A5FCF741D3B`
SHA384 | `E706224ACE7FFB7C2E119538AECBCF126233471A58FC11E9CA964DAA976A095D845A83D018C16321791FF933627E42A3`
SHA512 | `C8B1F8ABDD18EF22A478A1CCBD3FBBF786A7BC748652AAE5D801C6C6537975AE4412AB09690B9DE078DB254F207AFF52DCC652C1171444271853AFD68279B100`
SSDEEP | `768:0MUsMjAAZ4PjLmLt9qnQD6s0at7KQibhNekjify8SVp5W+20UI1PN3w:XUQAZ4PnmxyQD6sQ/Eagy8SVvJDP6`
IMP | `7FE9AEA5946396941B86D7C6E11427E6`
PESHA1 | `9885418E30F469838327C2FAB53B2D6A2069F902`
PE256 | `4611D9BEC262C0826A4522C15B41473D14199FBBBBAFBA696F91BD0D39DB0550`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllMain` | 2 (0x2) | Exported Function | 0x10008120 | 0x00008120
`SensorGetTypeFromInterfacePath` | 34 (0x22) | Exported Function | 0x100053b0 | 0x000053b0
`SensorIsWakeEnabled` | 35 (0x23) | Exported Function | 0x10006c30 | 0x00006c30
`SensorNotificationConfigure` | 36 (0x24) | Exported Function | 0x10006e70 | 0x00006e70
`SensorNotificationStart` | 37 (0x25) | Exported Function | 0x10006f00 | 0x00006f00
`SensorNotificationStop` | 38 (0x26) | Exported Function | 0x10006f80 | 0x00006f80
`SensorOpen` | 39 (0x27) | Exported Function | 0x10005e00 | 0x00005e00
`SensorOpenByInterface` | 40 (0x28) | Exported Function | 0x10005530 | 0x00005530
`SensorOpenByType` | 41 (0x29) | Exported Function | 0x10005ca0 | 0x00005ca0
`SensorRegisterEvent` | 42 (0x2a) | Exported Function | 0x10006900 | 0x00006900
`SensorSelectBestDevice` | 43 (0x2b) | Exported Function | 0x10005700 | 0x00005700
`SensorSetAccThresholds` | 44 (0x2c) | Exported Function | 0x10007be0 | 0x00007be0
`SensorSetAlsThresholds` | 45 (0x2d) | Exported Function | 0x10007c80 | 0x00007c80
`SensorSetAlsWithColorThresholds` | 46 (0x2e) | Exported Function | 0x10007d20 | 0x00007d20
`SensorSetBarThresholds` | 47 (0x2f) | Exported Function | 0x10007dd0 | 0x00007dd0
`SensorSetDataDeliveryMode` | 48 (0x30) | Exported Function | 0x100073b0 | 0x000073b0
`SensorSetDataInterval` | 49 (0x31) | Exported Function | 0x100065a0 | 0x000065a0
`SensorSetFusThresholds` | 50 (0x32) | Exported Function | 0x10007fb0 | 0x00007fb0
`SensorSetGyrThresholds` | 51 (0x33) | Exported Function | 0x10007e70 | 0x00007e70
`SensorSetMagThresholds` | 52 (0x34) | Exported Function | 0x10007f10 | 0x00007f10
`SensorSetOrientationSensorThresholds` | 53 (0x35) | Exported Function | 0x10008050 | 0x00008050
`SensorSetRangeResolution` | 54 (0x36) | Exported Function | 0x10006df0 | 0x00006df0
`SensorSetReportLatency` | 55 (0x37) | Exported Function | 0x10007320 | 0x00007320
`SensorSetThresholds` | 56 (0x38) | Exported Function | 0x10006510 | 0x00006510
`SensorStart` | 57 (0x39) | Exported Function | 0x100067e0 | 0x000067e0
`SensorStartCollection` | 58 (0x3a) | Exported Function | 0x10006870 | 0x00006870
`SensorStartHistory` | 59 (0x3b) | Exported Function | 0x10007090 | 0x00007090
`SensorStop` | 60 (0x3c) | Exported Function | 0x10006a10 | 0x00006a10
`SensorGetThresholds` | 33 (0x21) | Exported Function | 0x10006480 | 0x00006480
`SensorGetSupportedDataFields` | 32 (0x20) | Exported Function | 0x100066c0 | 0x000066c0
`SensorGetRangeResolution` | 31 (0x1f) | Exported Function | 0x10006d60 | 0x00006d60
`SensorGetPrxData` | 30 (0x1e) | Exported Function | 0x100079f0 | 0x000079f0
`SensorCancelHistoryRetrieval` | 3 (0x3) | Exported Function | 0x100072a0 | 0x000072a0
`SensorClearHistory` | 4 (0x4) | Exported Function | 0x10007190 | 0x00007190
`SensorClose` | 5 (0x5) | Exported Function | 0x10005fa0 | 0x00005fa0
`SensorDetermineStackByPropertyStore` | 6 (0x6) | Exported Function | 0x10005470 | 0x00005470
`SensorDeviceIoControl` | 7 (0x7) | Exported Function | 0x10006cb0 | 0x00006cb0
`SensorDisableIoPathForDataNotifications` | 8 (0x8) | Exported Function | 0x100074d0 | 0x000074d0
`SensorDisableWake` | 9 (0x9) | Exported Function | 0x10006bb0 | 0x00006bb0
`SensorEnableIdleOperation` | 10 (0xa) | Exported Function | 0x10006ab0 | 0x00006ab0
`SensorEnableWake` | 11 (0xb) | Exported Function | 0x10006b30 | 0x00006b30
`SensorGetAccData` | 12 (0xc) | Exported Function | 0x10007550 | 0x00007550
`SensorGetAlsData` | 13 (0xd) | Exported Function | 0x10007630 | 0x00007630
`SensorGetAlsDataWithColor` | 14 (0xe) | Exported Function | 0x100076e0 | 0x000076e0
`SensorGetBarData` | 15 (0xf) | Exported Function | 0x100077d0 | 0x000077d0
`SensorStopHistory` | 61 (0x3d) | Exported Function | 0x10007110 | 0x00007110
`SensorGetCapabilities` | 16 (0x10) | Exported Function | 0x10006210 | 0x00006210
`SensorGetCurrentReading` | 18 (0x12) | Exported Function | 0x10006180 | 0x00006180
`SensorGetData` | 19 (0x13) | Exported Function | 0x10006060 | 0x00006060
`SensorGetDataCollection` | 20 (0x14) | Exported Function | 0x100060f0 | 0x000060f0
`SensorGetDataDeliveryMode` | 21 (0x15) | Exported Function | 0x10007440 | 0x00007440
`SensorGetDataFieldProperties` | 1 (0x1) | Exported Function | 0x10006750 | 0x00006750
`SensorGetDefaultThresholds` | 22 (0x16) | Exported Function | 0x10006630 | 0x00006630
`SensorGetDeviceId` | 23 (0x17) | Exported Function | 0x10007000 | 0x00007000
`SensorGetFifoMaxSize` | 24 (0x18) | Exported Function | 0x10006360 | 0x00006360
`SensorGetFusData` | 25 (0x19) | Exported Function | 0x10007ad0 | 0x00007ad0
`SensorGetGyrData` | 26 (0x1a) | Exported Function | 0x10007880 | 0x00007880
`SensorGetHistory` | 27 (0x1b) | Exported Function | 0x10007210 | 0x00007210
`SensorGetMagData` | 28 (0x1c) | Exported Function | 0x10007930 | 0x00007930
`SensorGetProperties` | 29 (0x1d) | Exported Function | 0x100063f0 | 0x000063f0
`SensorGetCapabilitiesCollection` | 17 (0x11) | Exported Function | 0x100062a0 | 0x000062a0
`SensorUnregisterEvent` | 62 (0x3e) | Exported Function | 0x10006990 | 0x00006990


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SensorsNativeApi.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3443ec51ed1248320cd8b8fab4f6236c42f221c8f38cc712d2f69a5fcf741d3b/detection/





MIT License. Copyright (c) 2020 Strontic.


