---
title: rtm.dll | Routing Table Manager
excerpt: What is rtm.dll?
---

# rtm.dll 

* File Path: `C:\Windows\SysWOW64\rtm.dll`
* Description: Routing Table Manager

## Hashes

Type | Hash
-- | --
MD5 | `10FF183C87F54B7F0076E179F157F93A`
SHA1 | `21FF5A06DB0465C77387A3C061CB864D8B269C2C`
SHA256 | `459017FF1F10D5BB293E7BE62C952E9D97F8BC0E755FF387657E95E470516C91`
SHA384 | `155C6B97FDCCD44532369DE22547B184CA2E38E0C37A3C9EC23B61A8352D477CA52AB8B066870742100C079BCB88CE6F`
SHA512 | `75C3A066784DBE8882208E3C7E03FC08D644788D576D91D13A4FA59D4F40832491D0A350E547B716E65B10A6E20473D96DB9EB7D906943901A5CA1DBE83027B6`
SSDEEP | `3072:FntjnDCjrZUpHSVyaiDdgDGm71GR0Bo66YN:FntLEIHSVmyBoaN`
IMP | `2BE7750B6CD0B361BB9DA7E77EB67AE9`
PESHA1 | `E68DE44ACA805A54CDBAC1FDE58DED9FD82388D9`
PE256 | `2EEF27BFCFBF24DDF128506CBCC4E1303D7C15C416636BC18CB421FD7AAC1EC8`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BestMatchInTable` | 1 (0x1) | Exported Function | 0x10007970 | 0x00007970
`RtmGetRoutePointer` | 85 (0x55) | Exported Function | 0x100110a0 | 0x000110a0
`RtmGetRouteInfo` | 84 (0x54) | Exported Function | 0x1000bee0 | 0x0000bee0
`RtmGetRouteAge` | 83 (0x53) | Exported Function | 0x100137f0 | 0x000137f0
`RtmGetRegisteredEntities` | 82 (0x52) | Exported Function | 0x1000f230 | 0x0000f230
`RtmGetOpaqueInformationPointer` | 81 (0x51) | Exported Function | 0x1000f4f0 | 0x0000f4f0
`RtmGetNextRoute` | 80 (0x50) | Exported Function | 0x100147c0 | 0x000147c0
`RtmGetNextHopPointer` | 79 (0x4f) | Exported Function | 0x1000d5d0 | 0x0000d5d0
`RtmGetNextHopInfo` | 78 (0x4e) | Exported Function | 0x1000bfb0 | 0x0000bfb0
`RtmGetNetworkCount` | 77 (0x4d) | Exported Function | 0x100137a0 | 0x000137a0
`RtmGetMostSpecificDestination` | 76 (0x4c) | Exported Function | 0x1000eb10 | 0x0000eb10
`RtmGetListEnumRoutes` | 75 (0x4b) | Exported Function | 0x1000c390 | 0x0000c390
`RtmGetLessSpecificDestination` | 74 (0x4a) | Exported Function | 0x1000ebd0 | 0x0000ebd0
`RtmGetInstances` | 73 (0x49) | Exported Function | 0x1000cbd0 | 0x0000cbd0
`RtmGetInstanceInfo` | 72 (0x48) | Exported Function | 0x1000cdd0 | 0x0000cdd0
`RtmGetFirstRoute` | 71 (0x47) | Exported Function | 0x100145b0 | 0x000145b0
`RtmGetExactMatchRoute` | 70 (0x46) | Exported Function | 0x1000eca0 | 0x0000eca0
`RtmGetExactMatchDestination` | 69 (0x45) | Exported Function | 0x1000ea70 | 0x0000ea70
`RtmGetEnumRoutes` | 68 (0x44) | Exported Function | 0x1000b340 | 0x0000b340
`RtmGetEnumNextHops` | 67 (0x43) | Exported Function | 0x1000b890 | 0x0000b890
`RtmGetEnumDests` | 66 (0x42) | Exported Function | 0x1000ab60 | 0x0000ab60
`RtmGetEnumBestRoutes` | 65 (0x41) | Exported Function | 0x1000b130 | 0x0000b130
`RtmGetEntityMethods` | 64 (0x40) | Exported Function | 0x1000c9f0 | 0x0000c9f0
`RtmGetEntityInfo` | 63 (0x3f) | Exported Function | 0x1000bc80 | 0x0000bc80
`RtmGetDestInfo` | 62 (0x3e) | Exported Function | 0x1000bcd0 | 0x0000bcd0
`RtmGetChangeStatus` | 60 (0x3c) | Exported Function | 0x10008830 | 0x00008830
`RtmHoldDestination` | 86 (0x56) | Exported Function | 0x10010fe0 | 0x00010fe0
`RtmGetChangedDests` | 61 (0x3d) | Exported Function | 0x10008350 | 0x00008350
`RtmIgnoreChangedDests` | 87 (0x57) | Exported Function | 0x10008790 | 0x00008790
`RtmInvokeMethod` | 89 (0x59) | Exported Function | 0x1000ca60 | 0x0000ca60
`RtmWriteAddressFamilyConfig` | 114 (0x72) | Exported Function | 0x1000a4a0 | 0x0000a4a0
`RtmUpdateAndUnlockRoute` | 113 (0x71) | Exported Function | 0x10011170 | 0x00011170
`RtmReleaseRoutes` | 112 (0x70) | Exported Function | 0x1000b6b0 | 0x0000b6b0
`RtmReleaseRouteInfo` | 111 (0x6f) | Exported Function | 0x1000c0d0 | 0x0000c0d0
`RtmReleaseNextHops` | 110 (0x6e) | Exported Function | 0x1000ba60 | 0x0000ba60
`RtmReleaseNextHopInfo` | 109 (0x6d) | Exported Function | 0x1000c170 | 0x0000c170
`RtmReleaseEntityInfo` | 108 (0x6c) | Exported Function | 0x1000c020 | 0x0000c020
`RtmReleaseEntities` | 107 (0x6b) | Exported Function | 0x1000f450 | 0x0000f450
`RtmReleaseDests` | 106 (0x6a) | Exported Function | 0x1000ad60 | 0x0000ad60
`RtmReleaseDestInfo` | 105 (0x69) | Exported Function | 0x1000c030 | 0x0000c030
`RtmReleaseChangedDests` | 104 (0x68) | Exported Function | 0x10008750 | 0x00008750
`RtmRegisterForChangeNotification` | 103 (0x67) | Exported Function | 0x10008110 | 0x00008110
`RtmRegisterEntity` | 102 (0x66) | Exported Function | 0x1000ee90 | 0x0000ee90
`RtmRegisterClient` | 101 (0x65) | Exported Function | 0x100122a0 | 0x000122a0
`RtmReferenceHandles` | 100 (0x64) | Exported Function | 0x1000bc20 | 0x0000bc20
`RtmReadInstanceConfig` | 99 (0x63) | Exported Function | 0x10009cc0 | 0x00009cc0
`RtmReadAddressFamilyConfig` | 98 (0x62) | Exported Function | 0x10009f60 | 0x00009f60
`RtmMarkDestForChangeNotification` | 97 (0x61) | Exported Function | 0x100088b0 | 0x000088b0
`RtmLookupIPDestination` | 96 (0x60) | Exported Function | 0x10014ad0 | 0x00014ad0
`RtmLockRoute` | 95 (0x5f) | Exported Function | 0x100110e0 | 0x000110e0
`RtmLockNextHop` | 94 (0x5e) | Exported Function | 0x1000d610 | 0x0000d610
`RtmLockDestination` | 93 (0x5d) | Exported Function | 0x1000f490 | 0x0000f490
`RtmIsRoute` | 92 (0x5c) | Exported Function | 0x10013680 | 0x00013680
`RtmIsMarkedForChangeNotification` | 91 (0x5b) | Exported Function | 0x10008930 | 0x00008930
`RtmIsBestRoute` | 90 (0x5a) | Exported Function | 0x1000edb0 | 0x0000edb0
`RtmInsertInRouteList` | 88 (0x58) | Exported Function | 0x1000c220 | 0x0000c220
`RtmGetAddressFamilyInfo` | 59 (0x3b) | Exported Function | 0x1000cf90 | 0x0000cf90
`RtmFindNextHop` | 58 (0x3a) | Exported Function | 0x1000d4d0 | 0x0000d4d0
`RtmEnumerateGetNextRoute` | 57 (0x39) | Exported Function | 0x10013a30 | 0x00013a30
`MgmTakeInterfaceOwnership` | 26 (0x1a) | Exported Function | 0x10016540 | 0x00016540
`MgmReleaseInterfaceOwnership` | 25 (0x19) | Exported Function | 0x100167b0 | 0x000167b0
`MgmRegisterMProtocol` | 24 (0x18) | Exported Function | 0x10016170 | 0x00016170
`MgmInitialize` | 23 (0x17) | Exported Function | 0x10015680 | 0x00015680
`MgmGroupEnumerationStart` | 22 (0x16) | Exported Function | 0x100181b0 | 0x000181b0
`MgmGroupEnumerationGetNext` | 21 (0x15) | Exported Function | 0x10018360 | 0x00018360
`MgmGroupEnumerationEnd` | 20 (0x14) | Exported Function | 0x100184b0 | 0x000184b0
`MgmGetProtocolOnInterface` | 19 (0x13) | Exported Function | 0x10016b90 | 0x00016b90
`MgmGetNextMfeStats` | 18 (0x12) | Exported Function | 0x10018080 | 0x00018080
`MgmGetNextMfe` | 17 (0x11) | Exported Function | 0x10017cf0 | 0x00017cf0
`MgmGetMfeStats` | 16 (0x10) | Exported Function | 0x10017e20 | 0x00017e20
`MgmGetMfe` | 15 (0xf) | Exported Function | 0x10017aa0 | 0x00017aa0
`MgmGetFirstMfeStats` | 14 (0xe) | Exported Function | 0x10017f40 | 0x00017f40
`MgmGetFirstMfe` | 13 (0xd) | Exported Function | 0x10017bc0 | 0x00017bc0
`MgmDeRegisterMProtocol` | 11 (0xb) | Exported Function | 0x100163c0 | 0x000163c0
`MgmDeleteGroupMembershipEntry` | 12 (0xc) | Exported Function | 0x100175a0 | 0x000175a0
`MgmDeInitialize` | 10 (0xa) | Exported Function | 0x10015c60 | 0x00015c60
`MgmAddGroupMembershipEntry` | 9 (0x9) | Exported Function | 0x10016d80 | 0x00016d80
`InsertIntoTable` | 8 (0x8) | Exported Function | 0x10007700 | 0x00007700
`EnumOverTable` | 7 (0x7) | Exported Function | 0x10007a10 | 0x00007a10
`DumpTable` | 6 (0x6) | Exported Function | 0x10007ba0 | 0x00007ba0
`DestroyTable` | 5 (0x5) | Exported Function | 0x10007b40 | 0x00007b40
`DeleteFromTable` | 4 (0x4) | Exported Function | 0x100077b0 | 0x000077b0
`CreateTable` | 3 (0x3) | Exported Function | 0x100076b0 | 0x000076b0
`CheckTable` | 2 (0x2) | Exported Function | 0x10007b70 | 0x00007b70
`NextMatchInTable` | 27 (0x1b) | Exported Function | 0x100079e0 | 0x000079e0
`RtmAddNextHop` | 28 (0x1c) | Exported Function | 0x1000d1b0 | 0x0000d1b0
`RtmAddRoute` | 29 (0x1d) | Exported Function | 0x10012c70 | 0x00012c70
`RtmAddRouteToDest` | 30 (0x1e) | Exported Function | 0x1000f700 | 0x0000f700
`RtmDeregisterFromChangeNotification` | 56 (0x38) | Exported Function | 0x10008970 | 0x00008970
`RtmDeregisterEntity` | 55 (0x37) | Exported Function | 0x1000f070 | 0x0000f070
`RtmDeregisterClient` | 54 (0x36) | Exported Function | 0x100123f0 | 0x000123f0
`RtmDereferenceHandles` | 53 (0x35) | Exported Function | 0x1000bc50 | 0x0000bc50
`RtmDequeueRouteChangeMessage` | 52 (0x34) | Exported Function | 0x10012570 | 0x00012570
`RtmDeleteRouteToDest` | 51 (0x33) | Exported Function | 0x10010800 | 0x00010800
`RtmDeleteRouteTable` | 50 (0x32) | Exported Function | 0x10012170 | 0x00012170
`RtmDeleteRouteList` | 49 (0x31) | Exported Function | 0x1000c480 | 0x0000c480
`RtmDeleteRoute` | 48 (0x30) | Exported Function | 0x10013440 | 0x00013440
`RtmDeleteNextHop` | 47 (0x2f) | Exported Function | 0x1000d380 | 0x0000d380
`RtmDeleteEnumHandle` | 46 (0x2e) | Exported Function | 0x1000bab0 | 0x0000bab0
`RtmCreateRouteListEnum` | 45 (0x2d) | Exported Function | 0x1000c2f0 | 0x0000c2f0
`RtmWriteInstanceConfig` | 115 (0x73) | Exported Function | 0x10009e10 | 0x00009e10
`RtmCreateRouteList` | 44 (0x2c) | Exported Function | 0x1000c1c0 | 0x0000c1c0
`RtmCreateNextHopEnum` | 42 (0x2a) | Exported Function | 0x1000b700 | 0x0000b700
`RtmCreateEnumerationHandle` | 41 (0x29) | Exported Function | 0x10013840 | 0x00013840
`RtmCreateDestEnum` | 40 (0x28) | Exported Function | 0x1000a9a0 | 0x0000a9a0
`RtmCreateBestRouteEnum` | 39 (0x27) | Exported Function | 0x1000ada0 | 0x0000ada0
`RtmConvertNetAddressToIpv6AddressAndLength` | 38 (0x26) | Exported Function | 0x10011cc0 | 0x00011cc0
`RtmConvertIpv6AddressAndLengthToNetAddress` | 37 (0x25) | Exported Function | 0x10011d50 | 0x00011d50
`RtmCloseEnumerationHandle` | 36 (0x24) | Exported Function | 0x10013bf0 | 0x00013bf0
`RtmCleanupInstances` | 35 (0x23) | Exported Function | 0x1000c810 | 0x0000c810
`RtmBlockSetRouteEnable` | 34 (0x22) | Exported Function | 0x10014290 | 0x00014290
`RtmBlockMethods` | 33 (0x21) | Exported Function | 0x1000cb80 | 0x0000cb80
`RtmBlockDeleteRoutes` | 32 (0x20) | Exported Function | 0x10013d00 | 0x00013d00
`RtmBlockConvertRoutesToStatic` | 31 (0x1f) | Exported Function | 0x10013fc0 | 0x00013fc0
`RtmCreateRouteEnum` | 43 (0x2b) | Exported Function | 0x1000aee0 | 0x0000aee0
`SearchInTable` | 116 (0x74) | Exported Function | 0x10007890 | 0x00007890


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RTM.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.450 (WinBuild.160101.0800)
* Product Version: 10.0.19041.450
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/459017ff1f10d5bb293e7be62c952e9d97f8bc0e755ff387657e95e470516c91/detection/





MIT License. Copyright (c) 2020 Strontic.


