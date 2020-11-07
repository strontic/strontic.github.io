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

Function Name | Ordinal | Type
-- | -- | --
`BestMatchInTable` | 1 | Exported Function
`RtmGetRoutePointer` | 85 | Exported Function
`RtmGetRouteInfo` | 84 | Exported Function
`RtmGetRouteAge` | 83 | Exported Function
`RtmGetRegisteredEntities` | 82 | Exported Function
`RtmGetOpaqueInformationPointer` | 81 | Exported Function
`RtmGetNextRoute` | 80 | Exported Function
`RtmGetNextHopPointer` | 79 | Exported Function
`RtmGetNextHopInfo` | 78 | Exported Function
`RtmGetNetworkCount` | 77 | Exported Function
`RtmGetMostSpecificDestination` | 76 | Exported Function
`RtmGetListEnumRoutes` | 75 | Exported Function
`RtmGetLessSpecificDestination` | 74 | Exported Function
`RtmGetInstances` | 73 | Exported Function
`RtmGetInstanceInfo` | 72 | Exported Function
`RtmGetFirstRoute` | 71 | Exported Function
`RtmGetExactMatchRoute` | 70 | Exported Function
`RtmGetExactMatchDestination` | 69 | Exported Function
`RtmGetEnumRoutes` | 68 | Exported Function
`RtmGetEnumNextHops` | 67 | Exported Function
`RtmGetEnumDests` | 66 | Exported Function
`RtmGetEnumBestRoutes` | 65 | Exported Function
`RtmGetEntityMethods` | 64 | Exported Function
`RtmGetEntityInfo` | 63 | Exported Function
`RtmGetDestInfo` | 62 | Exported Function
`RtmGetChangeStatus` | 60 | Exported Function
`RtmHoldDestination` | 86 | Exported Function
`RtmGetChangedDests` | 61 | Exported Function
`RtmIgnoreChangedDests` | 87 | Exported Function
`RtmInvokeMethod` | 89 | Exported Function
`RtmWriteAddressFamilyConfig` | 114 | Exported Function
`RtmUpdateAndUnlockRoute` | 113 | Exported Function
`RtmReleaseRoutes` | 112 | Exported Function
`RtmReleaseRouteInfo` | 111 | Exported Function
`RtmReleaseNextHops` | 110 | Exported Function
`RtmReleaseNextHopInfo` | 109 | Exported Function
`RtmReleaseEntityInfo` | 108 | Exported Function
`RtmReleaseEntities` | 107 | Exported Function
`RtmReleaseDests` | 106 | Exported Function
`RtmReleaseDestInfo` | 105 | Exported Function
`RtmReleaseChangedDests` | 104 | Exported Function
`RtmRegisterForChangeNotification` | 103 | Exported Function
`RtmRegisterEntity` | 102 | Exported Function
`RtmRegisterClient` | 101 | Exported Function
`RtmReferenceHandles` | 100 | Exported Function
`RtmReadInstanceConfig` | 99 | Exported Function
`RtmReadAddressFamilyConfig` | 98 | Exported Function
`RtmMarkDestForChangeNotification` | 97 | Exported Function
`RtmLookupIPDestination` | 96 | Exported Function
`RtmLockRoute` | 95 | Exported Function
`RtmLockNextHop` | 94 | Exported Function
`RtmLockDestination` | 93 | Exported Function
`RtmIsRoute` | 92 | Exported Function
`RtmIsMarkedForChangeNotification` | 91 | Exported Function
`RtmIsBestRoute` | 90 | Exported Function
`RtmInsertInRouteList` | 88 | Exported Function
`RtmGetAddressFamilyInfo` | 59 | Exported Function
`RtmFindNextHop` | 58 | Exported Function
`RtmEnumerateGetNextRoute` | 57 | Exported Function
`MgmTakeInterfaceOwnership` | 26 | Exported Function
`MgmReleaseInterfaceOwnership` | 25 | Exported Function
`MgmRegisterMProtocol` | 24 | Exported Function
`MgmInitialize` | 23 | Exported Function
`MgmGroupEnumerationStart` | 22 | Exported Function
`MgmGroupEnumerationGetNext` | 21 | Exported Function
`MgmGroupEnumerationEnd` | 20 | Exported Function
`MgmGetProtocolOnInterface` | 19 | Exported Function
`MgmGetNextMfeStats` | 18 | Exported Function
`MgmGetNextMfe` | 17 | Exported Function
`MgmGetMfeStats` | 16 | Exported Function
`MgmGetMfe` | 15 | Exported Function
`MgmGetFirstMfeStats` | 14 | Exported Function
`MgmGetFirstMfe` | 13 | Exported Function
`MgmDeRegisterMProtocol` | 11 | Exported Function
`MgmDeleteGroupMembershipEntry` | 12 | Exported Function
`MgmDeInitialize` | 10 | Exported Function
`MgmAddGroupMembershipEntry` | 9 | Exported Function
`InsertIntoTable` | 8 | Exported Function
`EnumOverTable` | 7 | Exported Function
`DumpTable` | 6 | Exported Function
`DestroyTable` | 5 | Exported Function
`DeleteFromTable` | 4 | Exported Function
`CreateTable` | 3 | Exported Function
`CheckTable` | 2 | Exported Function
`NextMatchInTable` | 27 | Exported Function
`RtmAddNextHop` | 28 | Exported Function
`RtmAddRoute` | 29 | Exported Function
`RtmAddRouteToDest` | 30 | Exported Function
`RtmDeregisterFromChangeNotification` | 56 | Exported Function
`RtmDeregisterEntity` | 55 | Exported Function
`RtmDeregisterClient` | 54 | Exported Function
`RtmDereferenceHandles` | 53 | Exported Function
`RtmDequeueRouteChangeMessage` | 52 | Exported Function
`RtmDeleteRouteToDest` | 51 | Exported Function
`RtmDeleteRouteTable` | 50 | Exported Function
`RtmDeleteRouteList` | 49 | Exported Function
`RtmDeleteRoute` | 48 | Exported Function
`RtmDeleteNextHop` | 47 | Exported Function
`RtmDeleteEnumHandle` | 46 | Exported Function
`RtmCreateRouteListEnum` | 45 | Exported Function
`RtmWriteInstanceConfig` | 115 | Exported Function
`RtmCreateRouteList` | 44 | Exported Function
`RtmCreateNextHopEnum` | 42 | Exported Function
`RtmCreateEnumerationHandle` | 41 | Exported Function
`RtmCreateDestEnum` | 40 | Exported Function
`RtmCreateBestRouteEnum` | 39 | Exported Function
`RtmConvertNetAddressToIpv6AddressAndLength` | 38 | Exported Function
`RtmConvertIpv6AddressAndLengthToNetAddress` | 37 | Exported Function
`RtmCloseEnumerationHandle` | 36 | Exported Function
`RtmCleanupInstances` | 35 | Exported Function
`RtmBlockSetRouteEnable` | 34 | Exported Function
`RtmBlockMethods` | 33 | Exported Function
`RtmBlockDeleteRoutes` | 32 | Exported Function
`RtmBlockConvertRoutesToStatic` | 31 | Exported Function
`RtmCreateRouteEnum` | 43 | Exported Function
`SearchInTable` | 116 | Exported Function


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


