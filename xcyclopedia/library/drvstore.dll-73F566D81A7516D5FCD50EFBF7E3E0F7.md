---
title: drvstore.dll | Driver Store API
excerpt: What is drvstore.dll?
---

# drvstore.dll 

* File Path: `C:\Windows\SysWOW64\drvstore.dll`
* Description: Driver Store API

## Hashes

Type | Hash
-- | --
MD5 | `73F566D81A7516D5FCD50EFBF7E3E0F7`
SHA1 | `D7F38412731F932557BEA4FFD413C541019E8867`
SHA256 | `B93A16480E6E57D4970B376DED3CE5622C63DE47E3E8102B376A0518C63595E0`
SHA384 | `B9241E8E87CE7D28FB7BBCBA2910AF1535057BA0AE922B2900FD60E2D13309E9B20CF225B518A9D4E3DA0BF9B1876C92`
SHA512 | `E6A1E49E9675AFEC7818218FCDA24B11A8407660C24B63E2DCB1F4C53A51F60A349DCBE6E543FA183E4775012034D8E668DE0B992F8EEEC45E143B710AC2F9BB`
SSDEEP | `24576:fUlETdJBZ+gunZu7M6XlbZ9XPOzu40cjfQZi8dBoGk57yS9VMNvhUH5Uft:f++Jj+7kM6Xl99s0cjfQZTdKpJkEH5UV`
IMP | `E9AA611E3E5616938A87CABB4F99282F`
PESHA1 | `0638D72ACDC4FCD2AAA9A060F577528F5F9FEB24`
PE256 | `0972D1A23F13AC9E4BDE1A25A83A33725ABD4B99DBFA1D673B8F8327A6BCD04D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DriverPackageClose` | 1 (0x1) | Exported Function | 0x1009f1b0 | 0x0009f1b0
`DriverStoreImportW` | 31 (0x1f) | Exported Function | 0x10041420 | 0x00041420
`DriverStoreMountNodeW` | 32 (0x20) | Exported Function | 0x100454b0 | 0x000454b0
`DriverStoreOfflineAddDriverPackageA` | 33 (0x21) | Exported Function | 0x10070b80 | 0x00070b80
`DriverStoreOfflineAddDriverPackageW` | 34 (0x22) | Exported Function | 0x10070e20 | 0x00070e20
`DriverStoreOfflineDeleteDriverPackageA` | 35 (0x23) | Exported Function | 0x10071160 | 0x00071160
`DriverStoreOfflineDeleteDriverPackageW` | 36 (0x24) | Exported Function | 0x10071230 | 0x00071230
`DriverStoreOfflineEnumDriverPackageA` | 37 (0x25) | Exported Function | 0x10071390 | 0x00071390
`DriverStoreOfflineEnumDriverPackageW` | 38 (0x26) | Exported Function | 0x10071490 | 0x00071490
`DriverStoreOfflineFindDriverPackageA` | 39 (0x27) | Exported Function | 0x100715a0 | 0x000715a0
`DriverStoreOfflineFindDriverPackageW` | 40 (0x28) | Exported Function | 0x100717d0 | 0x000717d0
`DriverStoreOpenW` | 41 (0x29) | Exported Function | 0x10030b40 | 0x00030b40
`DriverStoreGetObjectPropertyW` | 30 (0x1e) | Exported Function | 0x1002ec20 | 0x0002ec20
`DriverStorePublishW` | 42 (0x2a) | Exported Function | 0x1004bc20 | 0x0004bc20
`DriverStoreReflectW` | 44 (0x2c) | Exported Function | 0x1005c020 | 0x0005c020
`DriverStoreRunDllW` | 45 (0x2d) | Exported Function | 0x10074930 | 0x00074930
`DriverStoreSelectNodeW` | 46 (0x2e) | Exported Function | 0x10045600 | 0x00045600
`DriverStoreSetLogContext` | 47 (0x2f) | Exported Function | 0x1003e5a0 | 0x0003e5a0
`DriverStoreSetObjectPropertyW` | 48 (0x30) | Exported Function | 0x10034f80 | 0x00034f80
`DriverStoreUnconfigureW` | 49 (0x31) | Exported Function | 0x10061a20 | 0x00061a20
`DriverStoreUnmountNodeW` | 50 (0x32) | Exported Function | 0x100456e0 | 0x000456e0
`DriverStoreUnpublishW` | 51 (0x33) | Exported Function | 0x1004c230 | 0x0004c230
`DriverStoreUnreflectCriticalW` | 52 (0x34) | Exported Function | 0x1005c0a0 | 0x0005c0a0
`DriverStoreUnreflectW` | 53 (0x35) | Exported Function | 0x1005c0e0 | 0x0005c0e0
`DriverStoreUpdateDevicesW` | 54 (0x36) | Exported Function | 0x100666e0 | 0x000666e0
`DriverStoreReflectCriticalW` | 43 (0x2b) | Exported Function | 0x1005bfe0 | 0x0005bfe0
`DriverStoreGetObjectPropertyKeysW` | 29 (0x1d) | Exported Function | 0x10045950 | 0x00045950
`DriverStoreFindW` | 28 (0x1c) | Exported Function | 0x1002f580 | 0x0002f580
`DriverStoreEnumW` | 27 (0x1b) | Exported Function | 0x10044e40 | 0x00044e40
`DriverPackageEnumClassesW` | 2 (0x2) | Exported Function | 0x1009f250 | 0x0009f250
`DriverPackageEnumComponentsW` | 3 (0x3) | Exported Function | 0x1009f500 | 0x0009f500
`DriverPackageEnumConfigurationsW` | 4 (0x4) | Exported Function | 0x1009f6e0 | 0x0009f6e0
`DriverPackageEnumDevicesW` | 5 (0x5) | Exported Function | 0x1009f880 | 0x0009f880
`DriverPackageEnumDriversW` | 6 (0x6) | Exported Function | 0x1009fae0 | 0x0009fae0
`DriverPackageEnumEventProvidersW` | 7 (0x7) | Exported Function | 0x1009fe10 | 0x0009fe10
`DriverPackageEnumFilesW` | 8 (0x8) | Exported Function | 0x1009fff0 | 0x0009fff0
`DriverPackageEnumFiltersW` | 9 (0x9) | Exported Function | 0x100a0320 | 0x000a0320
`DriverPackageEnumInterfacesW` | 10 (0xa) | Exported Function | 0x100a04f0 | 0x000a04f0
`DriverPackageEnumPropertiesW` | 11 (0xb) | Exported Function | 0x100a07c0 | 0x000a07c0
`DriverPackageEnumRegKeysW` | 12 (0xc) | Exported Function | 0x100a09a0 | 0x000a09a0
`DriverPackageEnumServicesW` | 13 (0xd) | Exported Function | 0x100a0b90 | 0x000a0b90
`DriverPackageEnumSoftwareW` | 14 (0xe) | Exported Function | 0x100a0d70 | 0x000a0d70
`DriverPackageGetPropertyW` | 15 (0xf) | Exported Function | 0x100a1220 | 0x000a1220
`DriverPackageGetVersionInfoW` | 16 (0x10) | Exported Function | 0x100a1c90 | 0x000a1c90
`DriverPackageOpenW` | 17 (0x11) | Exported Function | 0x100a1fd0 | 0x000a1fd0
`DriverStoreClose` | 18 (0x12) | Exported Function | 0x10032da0 | 0x00032da0
`DriverStoreConfigureW` | 19 (0x13) | Exported Function | 0x100619e0 | 0x000619e0
`DriverStoreCopyW` | 20 (0x14) | Exported Function | 0x10044580 | 0x00044580
`DriverStoreDeleteW` | 21 (0x15) | Exported Function | 0x10043f00 | 0x00043f00
`DriverStoreDriverPackageResolveCallbackW` | 22 (0x16) | Exported Function | 0x1003ef00 | 0x0003ef00
`DriverStoreEnumDeviceDriversW` | 23 (0x17) | Exported Function | 0x100665d0 | 0x000665d0
`DriverStoreEnumNodesW` | 24 (0x18) | Exported Function | 0x10045390 | 0x00045390
`DriverStoreEnumObjectsW` | 25 (0x19) | Exported Function | 0x10045820 | 0x00045820
`DriverStoreEnumRelatedDriversW` | 26 (0x1a) | Exported Function | 0x10075d30 | 0x00075d30
`pServerDeleteDriverPackage` | 55 (0x37) | Exported Function | 0x100705b0 | 0x000705b0
`pServerImportDriverPackage` | 56 (0x38) | Exported Function | 0x10070700 | 0x00070700


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DRVSTORE.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/b93a16480e6e57d4970b376ded3ce5622c63de47e3e8102b376a0518c63595e0/detection/





MIT License. Copyright (c) 2020 Strontic.


