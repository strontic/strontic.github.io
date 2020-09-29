---
title: fwpolicyiomgr.dll | FwPolicyIoMgr DLL
excerpt: What is fwpolicyiomgr.dll?
---

# fwpolicyiomgr.dll 

* File Path: `C:\Windows\SysWOW64\fwpolicyiomgr.dll`
* Description: FwPolicyIoMgr DLL

## Hashes

Type | Hash
-- | --
MD5 | `5624578C166E46DFF61ED029E020E289`
SHA1 | `3E89AF0D0B7BB9CA35BEE73B5E667EB008B98D14`
SHA256 | `3986314E5C0298DD8758835A5CFA1089C34CFC486D9889DCCCD247BD59CE14E3`
SHA384 | `26EDA3B435EF48DE33E683A2EB2D96529A004E4BD797E35F6EA1E4B5D157C6C9428AFF72D488A837D5B31FE3440BE68D`
SHA512 | `D519FF6BBC74AB0BE4375222683E3906147987ED42840A70F15C592B84D1E99A35B61E9510B4243B69651D723F8074A095E8DE842412C3127FABB18866316519`
SSDEEP | `3072:Pr0s/BlICROQeVSo8eRYDOjdGXuLfC5mkFEPbTITBm4nHeJlASO+RuF7Zw+MNYnJ:5/OL7UfHwlALC+NnDbi/Wl`
IMP | `BF92E1F26FC0C6A7380E0BAAECA25249`
PESHA1 | `A7EFAF0E4E67907555A50816AFD642BC76B0B3B8`
PE256 | `D7BFE19515DA7AB061EAE5F4A88E44335E125E0F30289998AB0F51AE62752EDB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CalculateOpenPortOrAuthAppAddrStringSize` | 16 (0x10) | Exported Function | 0x100167d0 | 0x000167d0
`FwRemoveDuplicateAddresses` | 106 (0x6a) | Exported Function | 0x1000d300 | 0x0000d300
`FwReduceObjectsToVersion` | 105 (0x69) | Exported Function | 0x100185a0 | 0x000185a0
`FWPrimitivesSetGPHelperFnPtrs` | 24 (0x18) | Exported Function | 0x1001a710 | 0x0001a710
`FwPolioMergeAddresses` | 104 (0x68) | Exported Function | 0x1000ae60 | 0x0000ae60
`FwPolioEmptyWFAddresses` | 103 (0x67) | Exported Function | 0x100062d0 | 0x000062d0
`FwPolioCopyWFAddressesContents` | 102 (0x66) | Exported Function | 0x1000cae0 | 0x0000cae0
`FwPolioCopyAuthSet` | 101 (0x65) | Exported Function | 0x1000c500 | 0x0000c500
`FwPolioConvertIPv6SubNetToRange` | 100 (0x64) | Exported Function | 0x10017500 | 0x00017500
`FwParseInterfaceType` | 13 (0xd) | Exported Function | 0x1001a500 | 0x0001a500
`FwParseICMPTypeCodes` | 12 (0xc) | Exported Function | 0x1000bab0 | 0x0000bab0
`FwParseAllPortVersions` | 11 (0xb) | Exported Function | 0x10005920 | 0x00005920
`FwParseAddressToken` | 99 (0x63) | Exported Function | 0x10018540 | 0x00018540
`FwOpenPolicyStore` | 98 (0x62) | Exported Function | 0x10007480 | 0x00007480
`FwOpenOfflinePolicyStore` | 97 (0x61) | Exported Function | 0x1001cb70 | 0x0001cb70
`FWOpenGPOAndGetRegKey` | 23 (0x17) | Exported Function | 0x1001a840 | 0x0001a840
`FwOpenAppCDbPolicyStore` | 96 (0x60) | Exported Function | 0x100069b0 | 0x000069b0
`FwNegateAddresses` | 95 (0x5f) | Exported Function | 0x1000b080 | 0x0000b080
`FWGPLock` | 18 (0x12) | Exported Function | 0x10007c90 | 0x00007c90
`FWGPOCleanup` | 19 (0x13) | Exported Function | 0x1001a7e0 | 0x0001a7e0
`FWGPOSave` | 20 (0x14) | Exported Function | 0x1001a810 | 0x0001a810
`FWGPUnlockEx` | 21 (0x15) | Exported Function | 0x100079e0 | 0x000079e0
`FwICFProfileToWfProfile` | 86 (0x56) | Exported Function | 0x100182d0 | 0x000182d0
`FwICFProtocolToWfProtocol` | 87 (0x57) | Exported Function | 0x10018310 | 0x00018310
`FWResolveGPONames` | 25 (0x19) | Exported Function | 0x1001a740 | 0x0001a740
`FWInitExtensionDllCriticalSection` | 22 (0x16) | Exported Function | 0x10006790 | 0x00006790
`FwIPV6RangeContainsMulticast` | 89 (0x59) | Exported Function | 0x10018360 | 0x00018360
`FwIsV6AddrLoopback` | 90 (0x5a) | Exported Function | 0x10018380 | 0x00018380
`FwMigrateLegacyAuthenticatedBypassSddl` | 93 (0x5d) | Exported Function | 0x100184c0 | 0x000184c0
`FwMigrateLegacySettings` | 94 (0x5e) | Exported Function | 0x1001caf0 | 0x0001caf0
`FwMMRuleFree` | 91 (0x5b) | Exported Function | 0x10018420 | 0x00018420
`FwMMRuleVerify` | 92 (0x5c) | Exported Function | 0x10018490 | 0x00018490
`FwIPV4RangeContainsMulticast` | 88 (0x58) | Exported Function | 0x10018340 | 0x00018340
`FwGetRule` | 85 (0x55) | Exported Function | 0x1001ca20 | 0x0001ca20
`FwRuleResolveFlags` | 107 (0x6b) | Exported Function | 0x10007ef0 | 0x00007ef0
`FwSetConfig` | 109 (0x6d) | Exported Function | 0x1001ce60 | 0x0001ce60
`StringToOpenPortOrAuthAppAddress` | 139 (0x8b) | Exported Function | 0x1000d0f0 | 0x0000d0f0
`OpenPortOrAuthAppAddrToStringInt2` | 137 (0x89) | Exported Function | 0x10008580 | 0x00008580
`OpenPortOrAuthAppAddrToString` | 136 (0x88) | Exported Function | 0x100190c0 | 0x000190c0
`MakeAbsoluteInterfaces` | 135 (0x87) | Exported Function | 0x10019000 | 0x00019000
`LoadGPExtensionDll` | 134 (0x86) | Exported Function | 0x1000ce00 | 0x0000ce00
`Isv4Orv6AddressesEmpty` | 133 (0x85) | Exported Function | 0x10018fc0 | 0x00018fc0
`IsUnicastExplicitAddressesEmpty` | 132 (0x84) | Exported Function | 0x1000b160 | 0x0000b160
`IsRulePerInterfaceOpenPort` | 131 (0x83) | Exported Function | 0x10018ed0 | 0x00018ed0
`IsRulePerInterfaceIcmp` | 130 (0x82) | Exported Function | 0x10018e80 | 0x00018e80
`IsRuleLegacyICMPSettings` | 129 (0x81) | Exported Function | 0x1001e7d0 | 0x0001e7d0
`IsPortsEmpty` | 128 (0x80) | Exported Function | 0x10018e50 | 0x00018e50
`IsEqualAddresses` | 127 (0x7f) | Exported Function | 0x1000d390 | 0x0000d390
`GetRemoteAdminSettings` | 14 (0xe) | Exported Function | 0x100155e0 | 0x000155e0
`GetOpenPortorAuthAppAsBSTR` | 126 (0x7e) | Exported Function | 0x10018d60 | 0x00018d60
`GetOpenPortOrAuthAppAddrScope` | 124 (0x7c) | Exported Function | 0x10018d20 | 0x00018d20
`GetOpenPortorAuthAppAddrAsString` | 125 (0x7d) | Exported Function | 0x10006600 | 0x00006600
`FwWfProtocolToICFProtocol` | 123 (0x7b) | Exported Function | 0x10018cf0 | 0x00018cf0
`FwSetGlobalConfig` | 110 (0x6e) | Exported Function | 0x1001cfc0 | 0x0001cfc0
`FwSetGlobalConfigInLocalTempStore` | 111 (0x6f) | Exported Function | 0x100068e0 | 0x000068e0
`FWSetGPHelperFnPtrs` | 26 (0x1a) | Exported Function | 0x1000d400 | 0x0000d400
`FwSetResolveFlags` | 112 (0x70) | Exported Function | 0x1000c3c0 | 0x0000c3c0
`FwSetRule` | 113 (0x71) | Exported Function | 0x10005760 | 0x00005760
`FwSetSet` | 114 (0x72) | Exported Function | 0x1001d150 | 0x0001d150
`FwSddlStringVerify` | 108 (0x6c) | Exported Function | 0x10018ae0 | 0x00018ae0
`FwSidAndAttributesCopy` | 115 (0x73) | Exported Function | 0x1000b1a0 | 0x0000b1a0
`FwSidCopy` | 117 (0x75) | Exported Function | 0x1000b240 | 0x0000b240
`FwSidsToString` | 118 (0x76) | Exported Function | 0x10018b50 | 0x00018b50
`FwStringToSids` | 119 (0x77) | Exported Function | 0x1000d190 | 0x0000d190
`FwSubtractAddresses` | 120 (0x78) | Exported Function | 0x1000d4e0 | 0x0000d4e0
`FwUniteWFAddressesContents` | 121 (0x79) | Exported Function | 0x1000ccc0 | 0x0000ccc0
`FwVerifyWFRuleSemantics` | 122 (0x7a) | Exported Function | 0x10008180 | 0x00008180
`FwSidAndAttributesFree` | 116 (0x74) | Exported Function | 0x10018b10 | 0x00018b10
`FwGetGlobalConfigFromLocalTempStore` | 84 (0x54) | Exported Function | 0x1001c990 | 0x0001c990
`FwGetGlobalConfig` | 83 (0x53) | Exported Function | 0x100076f0 | 0x000076f0
`FwGetConfig` | 82 (0x52) | Exported Function | 0x10007030 | 0x00007030
`FwCopyCryptoSet` | 51 (0x33) | Exported Function | 0x1000bfc0 | 0x0000bfc0
`FwCopyAuthSetToLowerVersion` | 48 (0x30) | Exported Function | 0x10017670 | 0x00017670
`FwCopyAuthsetToHigherVersion` | 49 (0x31) | Exported Function | 0x10017970 | 0x00017970
`FwCopyAuthSetListToLowerVersion` | 47 (0x2f) | Exported Function | 0x100175b0 | 0x000175b0
`FwConvertIPv6SubNetToRange` | 46 (0x2e) | Exported Function | 0x10017500 | 0x00017500
`FwCompareFWRule` | 45 (0x2d) | Exported Function | 0x10016ff0 | 0x00016ff0
`FwCompareCSRule` | 44 (0x2c) | Exported Function | 0x10016c40 | 0x00016c40
`FwClosePolicyStore` | 43 (0x2b) | Exported Function | 0x100063f0 | 0x000063f0
`FwCleanupPhase1Sa` | 42 (0x2a) | Exported Function | 0x10016c00 | 0x00016c00
`FwChkBuildSidAndAttributesFree` | 41 (0x29) | Exported Function | 0x10016ba0 | 0x00016ba0
`FwBinariesFree` | 36 (0x24) | Exported Function | 0x10005600 | 0x00005600
`FwAuthSetFree` | 35 (0x23) | Exported Function | 0x10016970 | 0x00016970
`FwAreAllContainedInAddresses` | 34 (0x22) | Exported Function | 0x10016910 | 0x00016910
`FwAppContainerChangeFree` | 33 (0x21) | Exported Function | 0x10016820 | 0x00016820
`FwAdvPolicyVerifyFirewallRule` | 32 (0x20) | Exported Function | 0x1001d5a0 | 0x0001d5a0
`FwAdvPolicyEncodeRule` | 31 (0x1f) | Exported Function | 0x100088d0 | 0x000088d0
`FwAdvPolicyDecodeFirewallRule` | 30 (0x1e) | Exported Function | 0x1001d350 | 0x0001d350
`CalculateOpenPortOrAuthAppAddrStringSize2` | 15 (0xf) | Exported Function | 0x10006670 | 0x00006670
`CopyIcmpSettings` | 1 (0x1) | Exported Function | 0x10015520 | 0x00015520
`CopyIcmpV4Rules` | 2 (0x2) | Exported Function | 0x10015560 | 0x00015560
`CopyIcmpV6Rules` | 3 (0x3) | Exported Function | 0x100155a0 | 0x000155a0
`CreateDefaultAuthAppRule` | 4 (0x4) | Exported Function | 0x10015650 | 0x00015650
`CreateDefaultIcmpRule` | 5 (0x5) | Exported Function | 0x100156e0 | 0x000156e0
`FwCopyCSRule` | 50 (0x32) | Exported Function | 0x1000c780 | 0x0000c780
`CreateDefaultOpenPortRule` | 6 (0x6) | Exported Function | 0x100157f0 | 0x000157f0
`CreateDefaultPerInterfaceOpenPortRule` | 8 (0x8) | Exported Function | 0x10015ad0 | 0x00015ad0
`CreateDefaultRemoteAdminRule` | 9 (0x9) | Exported Function | 0x10015bc0 | 0x00015bc0
`CreateDefaultRule` | 10 (0xa) | Exported Function | 0x10005630 | 0x00005630
`FreeAbsoluteInterfaces` | 27 (0x1b) | Exported Function | 0x100167f0 | 0x000167f0
`FwAddRule` | 28 (0x1c) | Exported Function | 0x10006b80 | 0x00006b80
`FwAddSet` | 29 (0x1d) | Exported Function | 0x1001c450 | 0x0001c450
`CreateDefaultPerInterfaceIcmpRule` | 7 (0x7) | Exported Function | 0x100158f0 | 0x000158f0
`FwCopyICMPTypeCode` | 52 (0x34) | Exported Function | 0x10006510 | 0x00006510
`FwCopyInterfaceIndexes` | 53 (0x35) | Exported Function | 0x10017c00 | 0x00017c00
`FwCopyInterfaceLuids` | 54 (0x36) | Exported Function | 0x10017c80 | 0x00017c80
`FWDestroyExtensionDllCriticalSection` | 17 (0x11) | Exported Function | 0x1001a6d0 | 0x0001a6d0
`FwDestroyLocalTempStore` | 69 (0x45) | Exported Function | 0x1001c900 | 0x0001c900
`FwDoNothingOnObject` | 70 (0x46) | Exported Function | 0x1000a8e0 | 0x0000a8e0
`FwDownlevelAuthSetFree` | 71 (0x47) | Exported Function | 0x100181a0 | 0x000181a0
`FwDownlevelFirewallRuleEmpty` | 72 (0x48) | Exported Function | 0x100181d0 | 0x000181d0
`FwEmptyWFRule` | 73 (0x49) | Exported Function | 0x100181f0 | 0x000181f0
`FwDeleteSet` | 68 (0x44) | Exported Function | 0x1001c820 | 0x0001c820
`FwEnumRules` | 74 (0x4a) | Exported Function | 0x10006f60 | 0x00006f60
`FwEraseGPOStoreBaseKey` | 76 (0x4c) | Exported Function | 0x1001c970 | 0x0001c970
`FwFindMatchingOpenPortRule` | 77 (0x4d) | Exported Function | 0x10018210 | 0x00018210
`FwFreeObjects` | 78 (0x4e) | Exported Function | 0x10018280 | 0x00018280
`FwFreeRules` | 79 (0x4f) | Exported Function | 0x10005ee0 | 0x00005ee0
`FwFreeSets` | 80 (0x50) | Exported Function | 0x1000cbd0 | 0x0000cbd0
`FwFreeWFRule` | 81 (0x51) | Exported Function | 0x10005420 | 0x00005420
`FwEnumSets` | 75 (0x4b) | Exported Function | 0x1000c250 | 0x0000c250
`StringToOpenPortOrAuthAppAddress2` | 138 (0x8a) | Exported Function | 0x1000d110 | 0x0000d110
`FwDeleteRule` | 67 (0x43) | Exported Function | 0x10006a60 | 0x00006a60
`FwDeleteAllRules` | 65 (0x41) | Exported Function | 0x1001c6a0 | 0x0001c6a0
`FwCopyLUID` | 55 (0x37) | Exported Function | 0x1000b290 | 0x0000b290
`FwCopyMMRule` | 56 (0x38) | Exported Function | 0x10017d00 | 0x00017d00
`FwCopyPlatform` | 57 (0x39) | Exported Function | 0x10006510 | 0x00006510
`FwCopyPortRange` | 58 (0x3a) | Exported Function | 0x10006510 | 0x00006510
`FwCopyPortsContents` | 59 (0x3b) | Exported Function | 0x10018040 | 0x00018040
`FwCopyRule` | 60 (0x3c) | Exported Function | 0x10005960 | 0x00005960
`FwDeleteAllSets` | 66 (0x42) | Exported Function | 0x1001c750 | 0x0001c750
`FwCountAuthAppRules` | 61 (0x3d) | Exported Function | 0x100180b0 | 0x000180b0
`FwCreateLocalTempStore` | 63 (0x3f) | Exported Function | 0x1001c560 | 0x0001c560
`FwCryptoSetFree` | 64 (0x40) | Exported Function | 0x10018150 | 0x00018150
`FwCSRuleEmpty` | 37 (0x25) | Exported Function | 0x100169c0 | 0x000169c0
`FwCSRuleEmptyByBinaryVersion` | 38 (0x26) | Exported Function | 0x100169e0 | 0x000169e0
`FwCSRuleFree` | 39 (0x27) | Exported Function | 0x10016b00 | 0x00016b00
`FwCSRuleVerify` | 40 (0x28) | Exported Function | 0x10016b70 | 0x00016b70
`FwCountGlobalOpenPortRules` | 62 (0x3e) | Exported Function | 0x10018100 | 0x00018100
`ValidatePortOrAppAddressString` | 140 (0x8c) | Exported Function | 0x100190f0 | 0x000190f0


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FwPolicyIoMgr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/3986314e5c0298dd8758835a5cfa1089c34cfc486d9889dcccd247bd59ce14e3/detection/





MIT License. Copyright (c) 2020 Strontic.


