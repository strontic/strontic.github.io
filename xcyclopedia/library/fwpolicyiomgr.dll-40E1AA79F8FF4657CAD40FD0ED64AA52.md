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

Function Name | Ordinal | Type
-- | -- | --
`CalculateOpenPortOrAuthAppAddrStringSize` | 15 | Exported Function
`FwRemoveDuplicateAddresses` | 106 | Exported Function
`FwReduceObjectsToVersion` | 105 | Exported Function
`FWPrimitivesSetGPHelperFnPtrs` | 24 | Exported Function
`FwPolioMergeAddresses` | 104 | Exported Function
`FwPolioEmptyWFAddresses` | 103 | Exported Function
`FwPolioCopyWFAddressesContents` | 102 | Exported Function
`FwPolioCopyAuthSet` | 101 | Exported Function
`FwPolioConvertIPv6SubNetToRange` | 100 | Exported Function
`FwParseInterfaceType` | 13 | Exported Function
`FwParseICMPTypeCodes` | 12 | Exported Function
`FwParseAllPortVersions` | 11 | Exported Function
`FwParseAddressToken` | 99 | Exported Function
`FwOpenPolicyStore` | 98 | Exported Function
`FwOpenOfflinePolicyStore` | 97 | Exported Function
`FWOpenGPOAndGetRegKey` | 23 | Exported Function
`FwOpenAppCDbPolicyStore` | 96 | Exported Function
`FwNegateAddresses` | 95 | Exported Function
`FWGPLock` | 18 | Exported Function
`FWGPOCleanup` | 19 | Exported Function
`FWGPOSave` | 20 | Exported Function
`FWGPUnlockEx` | 21 | Exported Function
`FwICFProfileToWfProfile` | 86 | Exported Function
`FwICFProtocolToWfProtocol` | 87 | Exported Function
`FWResolveGPONames` | 25 | Exported Function
`FWInitExtensionDllCriticalSection` | 22 | Exported Function
`FwIPV6RangeContainsMulticast` | 89 | Exported Function
`FwIsV6AddrLoopback` | 90 | Exported Function
`FwMigrateLegacyAuthenticatedBypassSddl` | 93 | Exported Function
`FwMigrateLegacySettings` | 94 | Exported Function
`FwMMRuleFree` | 91 | Exported Function
`FwMMRuleVerify` | 92 | Exported Function
`FwIPV4RangeContainsMulticast` | 88 | Exported Function
`FwGetRule` | 85 | Exported Function
`FwRuleResolveFlags` | 107 | Exported Function
`FwSetConfig` | 109 | Exported Function
`StringToOpenPortOrAuthAppAddress` | 138 | Exported Function
`OpenPortOrAuthAppAddrToStringInt2` | 137 | Exported Function
`OpenPortOrAuthAppAddrToString` | 136 | Exported Function
`MakeAbsoluteInterfaces` | 135 | Exported Function
`LoadGPExtensionDll` | 134 | Exported Function
`Isv4Orv6AddressesEmpty` | 133 | Exported Function
`IsUnicastExplicitAddressesEmpty` | 132 | Exported Function
`IsRulePerInterfaceOpenPort` | 131 | Exported Function
`IsRulePerInterfaceIcmp` | 130 | Exported Function
`IsRuleLegacyICMPSettings` | 129 | Exported Function
`IsPortsEmpty` | 128 | Exported Function
`IsEqualAddresses` | 127 | Exported Function
`GetRemoteAdminSettings` | 14 | Exported Function
`GetOpenPortorAuthAppAsBSTR` | 126 | Exported Function
`GetOpenPortOrAuthAppAddrScope` | 124 | Exported Function
`GetOpenPortorAuthAppAddrAsString` | 125 | Exported Function
`FwWfProtocolToICFProtocol` | 123 | Exported Function
`FwSetGlobalConfig` | 110 | Exported Function
`FwSetGlobalConfigInLocalTempStore` | 111 | Exported Function
`FWSetGPHelperFnPtrs` | 26 | Exported Function
`FwSetResolveFlags` | 112 | Exported Function
`FwSetRule` | 113 | Exported Function
`FwSetSet` | 114 | Exported Function
`FwSddlStringVerify` | 108 | Exported Function
`FwSidAndAttributesCopy` | 115 | Exported Function
`FwSidCopy` | 117 | Exported Function
`FwSidsToString` | 118 | Exported Function
`FwStringToSids` | 119 | Exported Function
`FwSubtractAddresses` | 120 | Exported Function
`FwUniteWFAddressesContents` | 121 | Exported Function
`FwVerifyWFRuleSemantics` | 122 | Exported Function
`FwSidAndAttributesFree` | 116 | Exported Function
`FwGetGlobalConfigFromLocalTempStore` | 84 | Exported Function
`FwGetGlobalConfig` | 83 | Exported Function
`FwGetConfig` | 82 | Exported Function
`FwCopyCryptoSet` | 51 | Exported Function
`FwCopyAuthSetToLowerVersion` | 48 | Exported Function
`FwCopyAuthsetToHigherVersion` | 49 | Exported Function
`FwCopyAuthSetListToLowerVersion` | 47 | Exported Function
`FwConvertIPv6SubNetToRange` | 46 | Exported Function
`FwCompareFWRule` | 45 | Exported Function
`FwCompareCSRule` | 44 | Exported Function
`FwClosePolicyStore` | 43 | Exported Function
`FwCleanupPhase1Sa` | 42 | Exported Function
`FwChkBuildSidAndAttributesFree` | 41 | Exported Function
`FwBinariesFree` | 36 | Exported Function
`FwAuthSetFree` | 35 | Exported Function
`FwAreAllContainedInAddresses` | 34 | Exported Function
`FwAppContainerChangeFree` | 33 | Exported Function
`FwAdvPolicyVerifyFirewallRule` | 32 | Exported Function
`FwAdvPolicyEncodeRule` | 31 | Exported Function
`FwAdvPolicyDecodeFirewallRule` | 30 | Exported Function
`CalculateOpenPortOrAuthAppAddrStringSize2` | 16 | Exported Function
`CopyIcmpSettings` | 1 | Exported Function
`CopyIcmpV4Rules` | 2 | Exported Function
`CopyIcmpV6Rules` | 3 | Exported Function
`CreateDefaultAuthAppRule` | 4 | Exported Function
`CreateDefaultIcmpRule` | 5 | Exported Function
`FwCopyCSRule` | 50 | Exported Function
`CreateDefaultOpenPortRule` | 6 | Exported Function
`CreateDefaultPerInterfaceOpenPortRule` | 8 | Exported Function
`CreateDefaultRemoteAdminRule` | 9 | Exported Function
`CreateDefaultRule` | 10 | Exported Function
`FreeAbsoluteInterfaces` | 27 | Exported Function
`FwAddRule` | 28 | Exported Function
`FwAddSet` | 29 | Exported Function
`CreateDefaultPerInterfaceIcmpRule` | 7 | Exported Function
`FwCopyICMPTypeCode` | 52 | Exported Function
`FwCopyInterfaceIndexes` | 53 | Exported Function
`FwCopyInterfaceLuids` | 54 | Exported Function
`FWDestroyExtensionDllCriticalSection` | 17 | Exported Function
`FwDestroyLocalTempStore` | 69 | Exported Function
`FwDoNothingOnObject` | 70 | Exported Function
`FwDownlevelAuthSetFree` | 71 | Exported Function
`FwDownlevelFirewallRuleEmpty` | 72 | Exported Function
`FwEmptyWFRule` | 73 | Exported Function
`FwDeleteSet` | 68 | Exported Function
`FwEnumRules` | 74 | Exported Function
`FwEraseGPOStoreBaseKey` | 76 | Exported Function
`FwFindMatchingOpenPortRule` | 77 | Exported Function
`FwFreeObjects` | 78 | Exported Function
`FwFreeRules` | 79 | Exported Function
`FwFreeSets` | 80 | Exported Function
`FwFreeWFRule` | 81 | Exported Function
`FwEnumSets` | 75 | Exported Function
`StringToOpenPortOrAuthAppAddress2` | 139 | Exported Function
`FwDeleteRule` | 67 | Exported Function
`FwDeleteAllRules` | 65 | Exported Function
`FwCopyLUID` | 55 | Exported Function
`FwCopyMMRule` | 56 | Exported Function
`FwCopyPlatform` | 57 | Exported Function
`FwCopyPortRange` | 58 | Exported Function
`FwCopyPortsContents` | 59 | Exported Function
`FwCopyRule` | 60 | Exported Function
`FwDeleteAllSets` | 66 | Exported Function
`FwCountAuthAppRules` | 61 | Exported Function
`FwCreateLocalTempStore` | 63 | Exported Function
`FwCryptoSetFree` | 64 | Exported Function
`FwCSRuleEmpty` | 37 | Exported Function
`FwCSRuleEmptyByBinaryVersion` | 38 | Exported Function
`FwCSRuleFree` | 39 | Exported Function
`FwCSRuleVerify` | 40 | Exported Function
`FwCountGlobalOpenPortRules` | 62 | Exported Function
`ValidatePortOrAppAddressString` | 140 | Exported Function


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


