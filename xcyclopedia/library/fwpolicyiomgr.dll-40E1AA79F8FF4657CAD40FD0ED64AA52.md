---
title: fwpolicyiomgr.dll | FwPolicyIoMgr DLL
excerpt: What is fwpolicyiomgr.dll?
---

# fwpolicyiomgr.dll 

* File Path: `C:\Windows\system32\fwpolicyiomgr.dll`
* Description: FwPolicyIoMgr DLL

## Hashes

Type | Hash
-- | --
MD5 | `40E1AA79F8FF4657CAD40FD0ED64AA52`
SHA1 | `D4329DFD6D0E94878A4FE42EEFE259293F8B66FA`
SHA256 | `E4A21AB5BC78F0549624B40D9E1BA097CA37EFA95F50B78126FFAC1EDB31091E`
SHA384 | `CBDB424D1933D46B52E76BC2BD9103CC6917332B2302CAE0E112B4854867A4C1FBBF712CF4951933F882DAF48944104A`
SHA512 | `AF7A78DAFAE3221059101FF2747263DDA9A33685F01F3DC32152AEBAA0770D0EF2B8816A88396FB004C145EA7FBF811775A9DFB1E4FE3907BD6E90584D859DD9`
SSDEEP | `3072:1ijXKKkN3m2jwjAYIo9u9GQmMsM4a5NaYukNGtZfuLz0FgSdXvuAjL:82KStjtzo90XmMr4a6Y4GSd`
IMP | `821C49EA2F743BC52BEE1BB517D96DA8`
PESHA1 | `38DF02FF49A819AE21871668AA3F9D0B0EAFD28F`
PE256 | `D34117C4D852EF5DD66475B1A2727BF952B3C10CB51EECA6BBF9FD8EAF1A1609`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CalculateOpenPortOrAuthAppAddrStringSize` | 15 (0xf) | Exported Function | 0x0000000180016100 | 0x00016100
`FwRemoveDuplicateAddresses` | 106 (0x6a) | Exported Function | 0x00000001800084c0 | 0x000084c0
`FwReduceObjectsToVersion` | 105 (0x69) | Exported Function | 0x00000001800185a0 | 0x000185a0
`FWPrimitivesSetGPHelperFnPtrs` | 24 (0x18) | Exported Function | 0x000000018001aea0 | 0x0001aea0
`FwPolioMergeAddresses` | 104 (0x68) | Exported Function | 0x0000000180008210 | 0x00008210
`FwPolioEmptyWFAddresses` | 103 (0x67) | Exported Function | 0x0000000180007f20 | 0x00007f20
`FwPolioCopyWFAddressesContents` | 102 (0x66) | Exported Function | 0x00000001800031a0 | 0x000031a0
`FwPolioCopyAuthSet` | 101 (0x65) | Exported Function | 0x000000018000a0f0 | 0x0000a0f0
`FwPolioConvertIPv6SubNetToRange` | 100 (0x64) | Exported Function | 0x0000000180017140 | 0x00017140
`FwParseInterfaceType` | 13 (0xd) | Exported Function | 0x000000018001ac10 | 0x0001ac10
`FwParseICMPTypeCodes` | 12 (0xc) | Exported Function | 0x00000001800092f0 | 0x000092f0
`FwParseAllPortVersions` | 11 (0xb) | Exported Function | 0x000000018001ab60 | 0x0001ab60
`FwParseAddressToken` | 99 (0x63) | Exported Function | 0x00000001800184e0 | 0x000184e0
`FwOpenPolicyStore` | 98 (0x62) | Exported Function | 0x0000000180004080 | 0x00004080
`FwOpenOfflinePolicyStore` | 97 (0x61) | Exported Function | 0x000000018001dfc0 | 0x0001dfc0
`FWOpenGPOAndGetRegKey` | 23 (0x17) | Exported Function | 0x000000018001afe0 | 0x0001afe0
`FwOpenAppCDbPolicyStore` | 96 (0x60) | Exported Function | 0x0000000180003f20 | 0x00003f20
`FwNegateAddresses` | 95 (0x5f) | Exported Function | 0x0000000180008140 | 0x00008140
`FWGPLock` | 18 (0x12) | Exported Function | 0x00000001800049c0 | 0x000049c0
`FWGPOCleanup` | 19 (0x13) | Exported Function | 0x000000018001af90 | 0x0001af90
`FWGPOSave` | 20 (0x14) | Exported Function | 0x000000018001afb0 | 0x0001afb0
`FWGPUnlockEx` | 21 (0x15) | Exported Function | 0x000000018000ae80 | 0x0000ae80
`FwICFProfileToWfProfile` | 86 (0x56) | Exported Function | 0x0000000180018250 | 0x00018250
`FwICFProtocolToWfProtocol` | 87 (0x57) | Exported Function | 0x0000000180018280 | 0x00018280
`FWResolveGPONames` | 25 (0x19) | Exported Function | 0x000000018001aec0 | 0x0001aec0
`FWInitExtensionDllCriticalSection` | 22 (0x16) | Exported Function | 0x0000000180003df0 | 0x00003df0
`FwIPV6RangeContainsMulticast` | 89 (0x59) | Exported Function | 0x00000001800182c0 | 0x000182c0
`FwIsV6AddrLoopback` | 90 (0x5a) | Exported Function | 0x00000001800182e0 | 0x000182e0
`FwMigrateLegacyAuthenticatedBypassSddl` | 93 (0x5d) | Exported Function | 0x00000001800184b0 | 0x000184b0
`FwMigrateLegacySettings` | 94 (0x5e) | Exported Function | 0x000000018001df20 | 0x0001df20
`FwMMRuleFree` | 91 (0x5b) | Exported Function | 0x00000001800183d0 | 0x000183d0
`FwMMRuleVerify` | 92 (0x5c) | Exported Function | 0x0000000180018470 | 0x00018470
`FwIPV4RangeContainsMulticast` | 88 (0x58) | Exported Function | 0x00000001800182a0 | 0x000182a0
`FwGetRule` | 85 (0x55) | Exported Function | 0x000000018001de10 | 0x0001de10
`FwRuleResolveFlags` | 107 (0x6b) | Exported Function | 0x0000000180007d30 | 0x00007d30
`FwSetConfig` | 109 (0x6d) | Exported Function | 0x000000018001e3b0 | 0x0001e3b0
`StringToOpenPortOrAuthAppAddress` | 138 (0x8a) | Exported Function | 0x000000018000b020 | 0x0000b020
`OpenPortOrAuthAppAddrToStringInt2` | 137 (0x89) | Exported Function | 0x0000000180005940 | 0x00005940
`OpenPortOrAuthAppAddrToString` | 136 (0x88) | Exported Function | 0x0000000180019330 | 0x00019330
`MakeAbsoluteInterfaces` | 135 (0x87) | Exported Function | 0x0000000180019220 | 0x00019220
`LoadGPExtensionDll` | 134 (0x86) | Exported Function | 0x000000018000abf0 | 0x0000abf0
`Isv4Orv6AddressesEmpty` | 133 (0x85) | Exported Function | 0x00000001800191f0 | 0x000191f0
`IsUnicastExplicitAddressesEmpty` | 132 (0x84) | Exported Function | 0x0000000180004de0 | 0x00004de0
`IsRulePerInterfaceOpenPort` | 131 (0x83) | Exported Function | 0x00000001800190c0 | 0x000190c0
`IsRulePerInterfaceIcmp` | 130 (0x82) | Exported Function | 0x0000000180019070 | 0x00019070
`IsRuleLegacyICMPSettings` | 129 (0x81) | Exported Function | 0x0000000180020620 | 0x00020620
`IsPortsEmpty` | 128 (0x80) | Exported Function | 0x0000000180019050 | 0x00019050
`IsEqualAddresses` | 127 (0x7f) | Exported Function | 0x0000000180008540 | 0x00008540
`GetRemoteAdminSettings` | 14 (0xe) | Exported Function | 0x0000000180014570 | 0x00014570
`GetOpenPortorAuthAppAsBSTR` | 126 (0x7e) | Exported Function | 0x0000000180018f20 | 0x00018f20
`GetOpenPortOrAuthAppAddrScope` | 124 (0x7c) | Exported Function | 0x0000000180018ee0 | 0x00018ee0
`GetOpenPortorAuthAppAddrAsString` | 125 (0x7d) | Exported Function | 0x00000001800055a0 | 0x000055a0
`FwWfProtocolToICFProtocol` | 123 (0x7b) | Exported Function | 0x0000000180018eb0 | 0x00018eb0
`FwSetGlobalConfig` | 110 (0x6e) | Exported Function | 0x000000018001e570 | 0x0001e570
`FwSetGlobalConfigInLocalTempStore` | 111 (0x6f) | Exported Function | 0x0000000180005500 | 0x00005500
`FWSetGPHelperFnPtrs` | 26 (0x1a) | Exported Function | 0x000000018000b240 | 0x0000b240
`FwSetResolveFlags` | 112 (0x70) | Exported Function | 0x0000000180009ee0 | 0x00009ee0
`FwSetRule` | 113 (0x71) | Exported Function | 0x000000018001e770 | 0x0001e770
`FwSetSet` | 114 (0x72) | Exported Function | 0x000000018001e970 | 0x0001e970
`FwSddlStringVerify` | 108 (0x6c) | Exported Function | 0x0000000180018bc0 | 0x00018bc0
`FwSidAndAttributesCopy` | 115 (0x73) | Exported Function | 0x00000001800039a0 | 0x000039a0
`FwSidCopy` | 117 (0x75) | Exported Function | 0x0000000180003a70 | 0x00003a70
`FwSidsToString` | 118 (0x76) | Exported Function | 0x0000000180018c50 | 0x00018c50
`FwStringToSids` | 119 (0x77) | Exported Function | 0x000000018000b0f0 | 0x0000b0f0
`FwSubtractAddresses` | 120 (0x78) | Exported Function | 0x00000001800085c0 | 0x000085c0
`FwUniteWFAddressesContents` | 121 (0x79) | Exported Function | 0x0000000180007ff0 | 0x00007ff0
`FwVerifyWFRuleSemantics` | 122 (0x7a) | Exported Function | 0x0000000180007fb0 | 0x00007fb0
`FwSidAndAttributesFree` | 116 (0x74) | Exported Function | 0x0000000180018bf0 | 0x00018bf0
`FwGetGlobalConfigFromLocalTempStore` | 84 (0x54) | Exported Function | 0x000000018001dd40 | 0x0001dd40
`FwGetGlobalConfig` | 83 (0x53) | Exported Function | 0x0000000180004490 | 0x00004490
`FwGetConfig` | 82 (0x52) | Exported Function | 0x00000001800016d0 | 0x000016d0
`FwCopyCryptoSet` | 51 (0x33) | Exported Function | 0x0000000180009990 | 0x00009990
`FwCopyAuthSetToLowerVersion` | 48 (0x30) | Exported Function | 0x0000000180017320 | 0x00017320
`FwCopyAuthsetToHigherVersion` | 49 (0x31) | Exported Function | 0x00000001800176b0 | 0x000176b0
`FwCopyAuthSetListToLowerVersion` | 47 (0x2f) | Exported Function | 0x0000000180017210 | 0x00017210
`FwConvertIPv6SubNetToRange` | 46 (0x2e) | Exported Function | 0x0000000180017140 | 0x00017140
`FwCompareFWRule` | 45 (0x2d) | Exported Function | 0x0000000180016bc0 | 0x00016bc0
`FwCompareCSRule` | 44 (0x2c) | Exported Function | 0x0000000180016790 | 0x00016790
`FwClosePolicyStore` | 43 (0x2b) | Exported Function | 0x0000000180003620 | 0x00003620
`FwCleanupPhase1Sa` | 42 (0x2a) | Exported Function | 0x0000000180016740 | 0x00016740
`FwChkBuildSidAndAttributesFree` | 41 (0x29) | Exported Function | 0x0000000180016690 | 0x00016690
`FwBinariesFree` | 36 (0x24) | Exported Function | 0x00000001800163a0 | 0x000163a0
`FwAuthSetFree` | 35 (0x23) | Exported Function | 0x0000000180016320 | 0x00016320
`FwAreAllContainedInAddresses` | 34 (0x22) | Exported Function | 0x00000001800162b0 | 0x000162b0
`FwAppContainerChangeFree` | 33 (0x21) | Exported Function | 0x0000000180016150 | 0x00016150
`FwAdvPolicyVerifyFirewallRule` | 32 (0x20) | Exported Function | 0x000000018001eec0 | 0x0001eec0
`FwAdvPolicyEncodeRule` | 31 (0x1f) | Exported Function | 0x00000001800060e0 | 0x000060e0
`FwAdvPolicyDecodeFirewallRule` | 30 (0x1e) | Exported Function | 0x000000018001ec10 | 0x0001ec10
`CalculateOpenPortOrAuthAppAddrStringSize2` | 16 (0x10) | Exported Function | 0x0000000180005650 | 0x00005650
`CopyIcmpSettings` | 1 (0x1) | Exported Function | 0x00000001800144a0 | 0x000144a0
`CopyIcmpV4Rules` | 2 (0x2) | Exported Function | 0x00000001800144f0 | 0x000144f0
`CopyIcmpV6Rules` | 3 (0x3) | Exported Function | 0x0000000180014530 | 0x00014530
`CreateDefaultAuthAppRule` | 4 (0x4) | Exported Function | 0x00000001800146a0 | 0x000146a0
`CreateDefaultIcmpRule` | 5 (0x5) | Exported Function | 0x0000000180014760 | 0x00014760
`FwCopyCSRule` | 50 (0x32) | Exported Function | 0x000000018000a550 | 0x0000a550
`CreateDefaultOpenPortRule` | 6 (0x6) | Exported Function | 0x00000001800148a0 | 0x000148a0
`CreateDefaultPerInterfaceOpenPortRule` | 8 (0x8) | Exported Function | 0x0000000180014c10 | 0x00014c10
`CreateDefaultRemoteAdminRule` | 9 (0x9) | Exported Function | 0x0000000180014d40 | 0x00014d40
`CreateDefaultRule` | 10 (0xa) | Exported Function | 0x0000000180015090 | 0x00015090
`FreeAbsoluteInterfaces` | 27 (0x1b) | Exported Function | 0x0000000180016110 | 0x00016110
`FwAddRule` | 28 (0x1c) | Exported Function | 0x0000000180004f00 | 0x00004f00
`FwAddSet` | 29 (0x1d) | Exported Function | 0x000000018001d5e0 | 0x0001d5e0
`CreateDefaultPerInterfaceIcmpRule` | 7 (0x7) | Exported Function | 0x00000001800149e0 | 0x000149e0
`FwCopyICMPTypeCode` | 52 (0x34) | Exported Function | 0x0000000180003990 | 0x00003990
`FwCopyInterfaceIndexes` | 53 (0x35) | Exported Function | 0x00000001800179d0 | 0x000179d0
`FwCopyInterfaceLuids` | 54 (0x36) | Exported Function | 0x0000000180017a70 | 0x00017a70
`FWDestroyExtensionDllCriticalSection` | 17 (0x11) | Exported Function | 0x0000000180001540 | 0x00001540
`FwDestroyLocalTempStore` | 69 (0x45) | Exported Function | 0x000000018001dc80 | 0x0001dc80
`FwDoNothingOnObject` | 70 (0x46) | Exported Function | 0x0000000180004a60 | 0x00004a60
`FwDownlevelAuthSetFree` | 71 (0x47) | Exported Function | 0x00000001800180e0 | 0x000180e0
`FwDownlevelFirewallRuleEmpty` | 72 (0x48) | Exported Function | 0x0000000180018110 | 0x00018110
`FwEmptyWFRule` | 73 (0x49) | Exported Function | 0x0000000180018120 | 0x00018120
`FwDeleteSet` | 68 (0x44) | Exported Function | 0x000000018001db50 | 0x0001db50
`FwEnumRules` | 74 (0x4a) | Exported Function | 0x00000001800015a0 | 0x000015a0
`FwEraseGPOStoreBaseKey` | 76 (0x4c) | Exported Function | 0x000000018001dd20 | 0x0001dd20
`FwFindMatchingOpenPortRule` | 77 (0x4d) | Exported Function | 0x0000000180018130 | 0x00018130
`FwFreeObjects` | 78 (0x4e) | Exported Function | 0x00000001800181d0 | 0x000181d0
`FwFreeRules` | 79 (0x4f) | Exported Function | 0x0000000180002780 | 0x00002780
`FwFreeSets` | 80 (0x50) | Exported Function | 0x000000018000a3c0 | 0x0000a3c0
`FwFreeWFRule` | 81 (0x51) | Exported Function | 0x0000000180018220 | 0x00018220
`FwEnumSets` | 75 (0x4b) | Exported Function | 0x0000000180009ce0 | 0x00009ce0
`StringToOpenPortOrAuthAppAddress2` | 139 (0x8b) | Exported Function | 0x000000018000b040 | 0x0000b040
`FwDeleteRule` | 67 (0x43) | Exported Function | 0x0000000180004e30 | 0x00004e30
`FwDeleteAllRules` | 65 (0x41) | Exported Function | 0x000000018001d950 | 0x0001d950
`FwCopyLUID` | 55 (0x37) | Exported Function | 0x0000000180008620 | 0x00008620
`FwCopyMMRule` | 56 (0x38) | Exported Function | 0x0000000180017b10 | 0x00017b10
`FwCopyPlatform` | 57 (0x39) | Exported Function | 0x0000000180003990 | 0x00003990
`FwCopyPortRange` | 58 (0x3a) | Exported Function | 0x0000000180003990 | 0x00003990
`FwCopyPortsContents` | 59 (0x3b) | Exported Function | 0x0000000180017f10 | 0x00017f10
`FwCopyRule` | 60 (0x3c) | Exported Function | 0x0000000180002c00 | 0x00002c00
`FwDeleteAllSets` | 66 (0x42) | Exported Function | 0x000000018001da40 | 0x0001da40
`FwCountAuthAppRules` | 61 (0x3d) | Exported Function | 0x0000000180017f90 | 0x00017f90
`FwCreateLocalTempStore` | 63 (0x3f) | Exported Function | 0x000000018001d720 | 0x0001d720
`FwCryptoSetFree` | 64 (0x40) | Exported Function | 0x0000000180018070 | 0x00018070
`FwCSRuleEmpty` | 37 (0x25) | Exported Function | 0x0000000180016400 | 0x00016400
`FwCSRuleEmptyByBinaryVersion` | 38 (0x26) | Exported Function | 0x0000000180016410 | 0x00016410
`FwCSRuleFree` | 39 (0x27) | Exported Function | 0x00000001800165b0 | 0x000165b0
`FwCSRuleVerify` | 40 (0x28) | Exported Function | 0x0000000180016650 | 0x00016650
`FwCountGlobalOpenPortRules` | 62 (0x3e) | Exported Function | 0x0000000180018000 | 0x00018000
`ValidatePortOrAppAddressString` | 140 (0x8c) | Exported Function | 0x0000000180019350 | 0x00019350


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FwPolicyIoMgr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/e4a21ab5bc78f0549624b40d9e1ba097ca37efa95f50b78126ffac1edb31091e/detection/





MIT License. Copyright (c) 2020 Strontic.


