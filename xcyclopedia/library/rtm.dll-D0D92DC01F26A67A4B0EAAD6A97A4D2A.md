---
title: rtm.dll | Routing Table Manager
excerpt: What is rtm.dll?
---

# rtm.dll 

* File Path: `C:\Windows\system32\rtm.dll`
* Description: Routing Table Manager

## Hashes

Type | Hash
-- | --
MD5 | `D0D92DC01F26A67A4B0EAAD6A97A4D2A`
SHA1 | `A1E655E512EC59D61AD0F165A96C605C364C6D0F`
SHA256 | `CAB2C389A9C76424214031CAD44BD27DEB9CCB9C489D7C4389625F170418A5D7`
SHA384 | `7BB75AA5FCDE3604CCA392464526EAFC9DE0B2FC948E8DF2D53CEC6E9BCAD7BC02ECCEB576CD09CCEFF2982EA33C0983`
SHA512 | `911856FF21B951261F4BE8D1721B6668BA99C57AD7021E1BD5AC814EF27DAAF8B224D52449F55B334DBA91DF6EB5E74307B393C2D491BB1C8CBE555EBA2EA257`
SSDEEP | `3072:xXHty/aBbvxSrQhBCQMK/Csh2PIHZZxxNpn4fntTH7xzMAW6Y:Py/UbJbBCQI9yZbxNpn4fntbZM7`
IMP | `868AD53E853505D77114423CCDC0B20C`
PESHA1 | `384A485AAB7FF4104FAEB2DB9F4A60C570F8BFB6`
PE256 | `8F521C4A41FCEEC8C2EEC1FBA6D8A818819EE348DC9F5A99D8921B691B489F76`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BestMatchInTable` | 1 (0x1) | Exported Function | 0x00000001800014e0 | 0x000014e0
`RtmGetRoutePointer` | 85 (0x55) | Exported Function | 0x000000018000cfc0 | 0x0000cfc0
`RtmGetRouteInfo` | 84 (0x54) | Exported Function | 0x0000000180006c20 | 0x00006c20
`RtmGetRouteAge` | 83 (0x53) | Exported Function | 0x000000018000fde0 | 0x0000fde0
`RtmGetRegisteredEntities` | 82 (0x52) | Exported Function | 0x000000018000ad50 | 0x0000ad50
`RtmGetOpaqueInformationPointer` | 81 (0x51) | Exported Function | 0x000000018000b070 | 0x0000b070
`RtmGetNextRoute` | 80 (0x50) | Exported Function | 0x0000000180010ed0 | 0x00010ed0
`RtmGetNextHopPointer` | 79 (0x4f) | Exported Function | 0x0000000180008bd0 | 0x00008bd0
`RtmGetNextHopInfo` | 78 (0x4e) | Exported Function | 0x0000000180006d30 | 0x00006d30
`RtmGetNetworkCount` | 77 (0x4d) | Exported Function | 0x000000018000fd80 | 0x0000fd80
`RtmGetMostSpecificDestination` | 76 (0x4c) | Exported Function | 0x000000018000a3e0 | 0x0000a3e0
`RtmGetListEnumRoutes` | 75 (0x4b) | Exported Function | 0x00000001800072a0 | 0x000072a0
`RtmGetLessSpecificDestination` | 74 (0x4a) | Exported Function | 0x000000018000a4e0 | 0x0000a4e0
`RtmGetInstances` | 73 (0x49) | Exported Function | 0x0000000180007db0 | 0x00007db0
`RtmGetInstanceInfo` | 72 (0x48) | Exported Function | 0x0000000180008090 | 0x00008090
`RtmGetFirstRoute` | 71 (0x47) | Exported Function | 0x0000000180010c90 | 0x00010c90
`RtmGetExactMatchRoute` | 70 (0x46) | Exported Function | 0x000000018000a5c0 | 0x0000a5c0
`RtmGetExactMatchDestination` | 69 (0x45) | Exported Function | 0x000000018000a2f0 | 0x0000a2f0
`RtmGetEnumRoutes` | 68 (0x44) | Exported Function | 0x0000000180005e10 | 0x00005e10
`RtmGetEnumNextHops` | 67 (0x43) | Exported Function | 0x0000000180006460 | 0x00006460
`RtmGetEnumDests` | 66 (0x42) | Exported Function | 0x0000000180005350 | 0x00005350
`RtmGetEnumBestRoutes` | 65 (0x41) | Exported Function | 0x0000000180005b50 | 0x00005b50
`RtmGetEntityMethods` | 64 (0x40) | Exported Function | 0x0000000180007b50 | 0x00007b50
`RtmGetEntityInfo` | 63 (0x3f) | Exported Function | 0x0000000180006980 | 0x00006980
`RtmGetDestInfo` | 62 (0x3e) | Exported Function | 0x00000001800069d0 | 0x000069d0
`RtmGetChangeStatus` | 60 (0x3c) | Exported Function | 0x00000001800027d0 | 0x000027d0
`RtmHoldDestination` | 86 (0x56) | Exported Function | 0x000000018000cec0 | 0x0000cec0
`RtmGetChangedDests` | 61 (0x3d) | Exported Function | 0x0000000180002280 | 0x00002280
`RtmIgnoreChangedDests` | 87 (0x57) | Exported Function | 0x0000000180002710 | 0x00002710
`RtmInvokeMethod` | 89 (0x59) | Exported Function | 0x0000000180007be0 | 0x00007be0
`RtmWriteAddressFamilyConfig` | 114 (0x72) | Exported Function | 0x00000001800048f0 | 0x000048f0
`RtmUpdateAndUnlockRoute` | 113 (0x71) | Exported Function | 0x000000018000d0c0 | 0x0000d0c0
`RtmReleaseRoutes` | 112 (0x70) | Exported Function | 0x0000000180006210 | 0x00006210
`RtmReleaseRouteInfo` | 111 (0x6f) | Exported Function | 0x0000000180006ed0 | 0x00006ed0
`RtmReleaseNextHops` | 110 (0x6e) | Exported Function | 0x00000001800066b0 | 0x000066b0
`RtmReleaseNextHopInfo` | 109 (0x6d) | Exported Function | 0x0000000180006f90 | 0x00006f90
`RtmReleaseEntityInfo` | 108 (0x6c) | Exported Function | 0x0000000180006df0 | 0x00006df0
`RtmReleaseEntities` | 107 (0x6b) | Exported Function | 0x000000018000afc0 | 0x0000afc0
`RtmReleaseDests` | 106 (0x6a) | Exported Function | 0x0000000180005600 | 0x00005600
`RtmReleaseDestInfo` | 105 (0x69) | Exported Function | 0x0000000180006e00 | 0x00006e00
`RtmReleaseChangedDests` | 104 (0x68) | Exported Function | 0x00000001800026a0 | 0x000026a0
`RtmRegisterForChangeNotification` | 103 (0x67) | Exported Function | 0x0000000180001fd0 | 0x00001fd0
`RtmRegisterEntity` | 102 (0x66) | Exported Function | 0x000000018000a800 | 0x0000a800
`RtmRegisterClient` | 101 (0x65) | Exported Function | 0x000000018000e3a0 | 0x0000e3a0
`RtmReferenceHandles` | 100 (0x64) | Exported Function | 0x0000000180006920 | 0x00006920
`RtmReadInstanceConfig` | 99 (0x63) | Exported Function | 0x0000000180003e50 | 0x00003e50
`RtmReadAddressFamilyConfig` | 98 (0x62) | Exported Function | 0x00000001800042c0 | 0x000042c0
`RtmMarkDestForChangeNotification` | 97 (0x61) | Exported Function | 0x0000000180002880 | 0x00002880
`RtmLookupIPDestination` | 96 (0x60) | Exported Function | 0x00000001800111e0 | 0x000111e0
`RtmLockRoute` | 95 (0x5f) | Exported Function | 0x000000018000d000 | 0x0000d000
`RtmLockNextHop` | 94 (0x5e) | Exported Function | 0x0000000180008c00 | 0x00008c00
`RtmLockDestination` | 93 (0x5d) | Exported Function | 0x000000018000b010 | 0x0000b010
`RtmIsRoute` | 92 (0x5c) | Exported Function | 0x000000018000fc30 | 0x0000fc30
`RtmIsMarkedForChangeNotification` | 91 (0x5b) | Exported Function | 0x0000000180002920 | 0x00002920
`RtmIsBestRoute` | 90 (0x5a) | Exported Function | 0x000000018000a730 | 0x0000a730
`RtmInsertInRouteList` | 88 (0x58) | Exported Function | 0x0000000180007080 | 0x00007080
`RtmGetAddressFamilyInfo` | 59 (0x3b) | Exported Function | 0x00000001800082e0 | 0x000082e0
`RtmFindNextHop` | 58 (0x3a) | Exported Function | 0x0000000180008a70 | 0x00008a70
`RtmEnumerateGetNextRoute` | 57 (0x39) | Exported Function | 0x00000001800100d0 | 0x000100d0
`MgmTakeInterfaceOwnership` | 26 (0x1a) | Exported Function | 0x00000001800132c0 | 0x000132c0
`MgmReleaseInterfaceOwnership` | 25 (0x19) | Exported Function | 0x0000000180013550 | 0x00013550
`MgmRegisterMProtocol` | 24 (0x18) | Exported Function | 0x0000000180012d50 | 0x00012d50
`MgmInitialize` | 23 (0x17) | Exported Function | 0x0000000180012030 | 0x00012030
`MgmGroupEnumerationStart` | 22 (0x16) | Exported Function | 0x0000000180015150 | 0x00015150
`MgmGroupEnumerationGetNext` | 21 (0x15) | Exported Function | 0x0000000180015330 | 0x00015330
`MgmGroupEnumerationEnd` | 20 (0x14) | Exported Function | 0x0000000180015480 | 0x00015480
`MgmGetProtocolOnInterface` | 19 (0x13) | Exported Function | 0x0000000180013950 | 0x00013950
`MgmGetNextMfeStats` | 18 (0x12) | Exported Function | 0x0000000180015020 | 0x00015020
`MgmGetNextMfe` | 17 (0x11) | Exported Function | 0x0000000180014c80 | 0x00014c80
`MgmGetMfeStats` | 16 (0x10) | Exported Function | 0x0000000180014db0 | 0x00014db0
`MgmGetMfe` | 15 (0xf) | Exported Function | 0x0000000180014a10 | 0x00014a10
`MgmGetFirstMfeStats` | 14 (0xe) | Exported Function | 0x0000000180014ed0 | 0x00014ed0
`MgmGetFirstMfe` | 13 (0xd) | Exported Function | 0x0000000180014b30 | 0x00014b30
`MgmDeRegisterMProtocol` | 11 (0xb) | Exported Function | 0x00000001800130d0 | 0x000130d0
`MgmDeleteGroupMembershipEntry` | 12 (0xc) | Exported Function | 0x00000001800144e0 | 0x000144e0
`MgmDeInitialize` | 10 (0xa) | Exported Function | 0x0000000180012790 | 0x00012790
`MgmAddGroupMembershipEntry` | 9 (0x9) | Exported Function | 0x0000000180013b60 | 0x00013b60
`InsertIntoTable` | 8 (0x8) | Exported Function | 0x0000000180001080 | 0x00001080
`EnumOverTable` | 7 (0x7) | Exported Function | 0x0000000180001610 | 0x00001610
`DumpTable` | 6 (0x6) | Exported Function | 0x0000000180001870 | 0x00001870
`DestroyTable` | 5 (0x5) | Exported Function | 0x00000001800017e0 | 0x000017e0
`DeleteFromTable` | 4 (0x4) | Exported Function | 0x0000000180001240 | 0x00001240
`CreateTable` | 3 (0x3) | Exported Function | 0x0000000180001010 | 0x00001010
`CheckTable` | 2 (0x2) | Exported Function | 0x0000000180001830 | 0x00001830
`NextMatchInTable` | 27 (0x1b) | Exported Function | 0x00000001800015f0 | 0x000015f0
`RtmAddNextHop` | 28 (0x1c) | Exported Function | 0x0000000180008590 | 0x00008590
`RtmAddRoute` | 29 (0x1d) | Exported Function | 0x000000018000f040 | 0x0000f040
`RtmAddRouteToDest` | 30 (0x1e) | Exported Function | 0x000000018000b390 | 0x0000b390
`RtmDeregisterFromChangeNotification` | 56 (0x38) | Exported Function | 0x0000000180002960 | 0x00002960
`RtmDeregisterEntity` | 55 (0x37) | Exported Function | 0x000000018000aaf0 | 0x0000aaf0
`RtmDeregisterClient` | 54 (0x36) | Exported Function | 0x000000018000e560 | 0x0000e560
`RtmDereferenceHandles` | 53 (0x35) | Exported Function | 0x0000000180006950 | 0x00006950
`RtmDequeueRouteChangeMessage` | 52 (0x34) | Exported Function | 0x000000018000e730 | 0x0000e730
`RtmDeleteRouteToDest` | 51 (0x33) | Exported Function | 0x000000018000c630 | 0x0000c630
`RtmDeleteRouteTable` | 50 (0x32) | Exported Function | 0x000000018000e1e0 | 0x0000e1e0
`RtmDeleteRouteList` | 49 (0x31) | Exported Function | 0x00000001800073c0 | 0x000073c0
`RtmDeleteRoute` | 48 (0x30) | Exported Function | 0x000000018000f990 | 0x0000f990
`RtmDeleteNextHop` | 47 (0x2f) | Exported Function | 0x00000001800088b0 | 0x000088b0
`RtmDeleteEnumHandle` | 46 (0x2e) | Exported Function | 0x0000000180006720 | 0x00006720
`RtmCreateRouteListEnum` | 45 (0x2d) | Exported Function | 0x00000001800071a0 | 0x000071a0
`RtmWriteInstanceConfig` | 115 (0x73) | Exported Function | 0x0000000180004080 | 0x00004080
`RtmCreateRouteList` | 44 (0x2c) | Exported Function | 0x0000000180006ff0 | 0x00006ff0
`RtmCreateNextHopEnum` | 42 (0x2a) | Exported Function | 0x0000000180006280 | 0x00006280
`RtmCreateEnumerationHandle` | 41 (0x29) | Exported Function | 0x000000018000fe50 | 0x0000fe50
`RtmCreateDestEnum` | 40 (0x28) | Exported Function | 0x0000000180005140 | 0x00005140
`RtmCreateBestRouteEnum` | 39 (0x27) | Exported Function | 0x0000000180005670 | 0x00005670
`RtmConvertNetAddressToIpv6AddressAndLength` | 38 (0x26) | Exported Function | 0x000000018000dd90 | 0x0000dd90
`RtmConvertIpv6AddressAndLengthToNetAddress` | 37 (0x25) | Exported Function | 0x000000018000de30 | 0x0000de30
`RtmCloseEnumerationHandle` | 36 (0x24) | Exported Function | 0x00000001800102a0 | 0x000102a0
`RtmCleanupInstances` | 35 (0x23) | Exported Function | 0x0000000180007940 | 0x00007940
`RtmBlockSetRouteEnable` | 34 (0x22) | Exported Function | 0x0000000180010970 | 0x00010970
`RtmBlockMethods` | 33 (0x21) | Exported Function | 0x0000000180007d50 | 0x00007d50
`RtmBlockDeleteRoutes` | 32 (0x20) | Exported Function | 0x00000001800103c0 | 0x000103c0
`RtmBlockConvertRoutesToStatic` | 31 (0x1f) | Exported Function | 0x0000000180010690 | 0x00010690
`RtmCreateRouteEnum` | 43 (0x2b) | Exported Function | 0x0000000180005800 | 0x00005800
`SearchInTable` | 116 (0x74) | Exported Function | 0x0000000180001370 | 0x00001370


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RTM.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/cab2c389a9c76424214031cad44bd27deb9ccb9c489d7c4389625f170418a5d7/detection/





MIT License. Copyright (c) 2020 Strontic.


