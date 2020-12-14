---
title: fwbase.dll | Firewall Base DLL
excerpt: What is fwbase.dll?
---

# fwbase.dll 

* File Path: `C:\Windows\SysWOW64\fwbase.dll`
* Description: Firewall Base DLL

## Hashes

Type | Hash
-- | --
MD5 | `93FFE2DF21854E33B679BADCC7C880BA`
SHA1 | `EA2CAE0D19E7CFB3AA794198C384425D5B5A63DB`
SHA256 | `260F936E72B47F8F677EFCED8D6DEDB59FFE511BCAB3FEA8C35B6D623E5D2896`
SHA384 | `DC37E49D6106CFC4A4509A2C711233815DCB2A1A9BFB62D93C5C446F95B0A8B90A4CF4CE59B508DF8981D27F563A1F83`
SHA512 | `A02197A124415024D53B50C7B3D8D000B7909C4AEED100020B1C6D2AE868D86EC982D181C28527B2ADA0661A3B50D4D58F370D0D42EF1BB68B04F28D2E9EFC4B`
SSDEEP | `3072:PAu16uww1102M415KadBvC2qoc+RVFJadz3p7wW:PRGw1102Mwf04zV43p`
IMP | `5004F17C3F1C74D13F3F54D2BBFC0EEF`
PESHA1 | `20BB6AA723EF22A6245F98A394454E9B5AC9DA58`
PE256 | `0497CF32EAC9480A7803698DC2E320E6959D13758F25F73A817648B403906F7D`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`FwReportErrorAsWinError` | 127 | Exported Function
`FwReportErrorAsNtStatus` | 126 | Exported Function
`FwReportReturnError` | 128 | Exported Function
`FwRestructureHashtable` | 130 | Exported Function
`FwResolveIndirectString` | 129 | Exported Function
`FwReleasePrivilege` | 125 | Exported Function
`FwRegQueryNumValues` | 121 | Exported Function
`FwRegQueryNumKeys` | 120 | Exported Function
`FwRegQueryString` | 122 | Exported Function
`FwRegSetString` | 124 | Exported Function
`FwRegSetDWord` | 123 | Exported Function
`FwServiceSidCreateInPlace` | 131 | Exported Function
`FwSortInterfaceLUIDs` | 139 | Exported Function
`FwSortAddresses` | 138 | Exported Function
`FwStaticFwPortEncode` | 140 | Exported Function
`FwStringBuild` | 142 | Exported Function
`FwStaticFwPortEncodeValueName` | 141 | Exported Function
`FwSizeTMultiply` | 137 | Exported Function
`FwShutdownMemoryMgr` | 133 | Exported Function
`FwSetMemLeakPolicy` | 132 | Exported Function
`FwSidCreate` | 134 | Exported Function
`FwSizeTAdd` | 136 | Exported Function
`FwSidDestroy` | 135 | Exported Function
`FwRegQueryDWord` | 119 | Exported Function
`FwMetaDataCopy` | 104 | Exported Function
`FwMetaDataAddEnforcementState` | 103 | Exported Function
`FwMetaDataFree` | 105 | Exported Function
`FwMultiByteToWideChar` | 107 | Exported Function
`FwMetaDataIsEnforcementStatePresent` | 106 | Exported Function
`FwMarshalledMetaDataInitialize` | 102 | Exported Function
`FwLoadIndirectString` | 98 | Exported Function
`FwLicensingIsXbox` | 97 | Exported Function
`FwLoadString` | 99 | Exported Function
`FwMarshalledMetaDataCopy` | 101 | Exported Function
`FwLookupAccountSid` | 100 | Exported Function
`FwParseEdpCloudResourceStringToNrptRuleList` | 108 | Exported Function
`FwRegEnumValueNameAndValueData` | 115 | Exported Function
`FwRegDeleteValue` | 114 | Exported Function
`FwRegNotifyCreate` | 116 | Exported Function
`FwRegOpenKey` | 118 | Exported Function
`FwRegNotifyDestroy` | 117 | Exported Function
`FwRegDeleteKey` | 113 | Exported Function
`FwProfileTypesToString` | 109 | Exported Function
`FwPortsToString` | 3 | Exported Function
`FwRegCloseKey` | 110 | Exported Function
`FwRegDeleteAllValues` | 112 | Exported Function
`FwRegCreateKey` | 111 | Exported Function
`Int_FwValidateComplianceAndReduceFirewallRuleToVersion` | 179 | Exported Function
`Int_FwValidateComplianceAndReduceCryptoSetToVersion` | 178 | Exported Function
`Int_FwValidateComplianceAndReduceMainModeRuleToVersion` | 180 | Exported Function
`Int_FWVerifyAuthenticationSet` | 167 | Exported Function
`Int_FwValidateSecurityDescriptor` | 181 | Exported Function
`Int_FwValidateComplianceAndReduceConnSecRuleToVersion` | 177 | Exported Function
`Int_FwIPV6RangeContainsMulticast` | 173 | Exported Function
`Int_FwIPV4RangeContainsMulticast` | 172 | Exported Function
`Int_FwIsV6AddrLoopback` | 174 | Exported Function
`Int_FwValidateComplianceAndReduceAuthSetToVersion` | 176 | Exported Function
`Int_FwValidateAndMigrateSecurityDescriptor` | 175 | Exported Function
`Int_FWVerifyConnectionSecurityRule` | 168 | Exported Function
`IsRuleOldv1Compliant` | 186 | Exported Function
`IsRuleOldGlobalOpenPort` | 185 | Exported Function
`IsRuleOpenPortOrAuthApp` | 187 | Exported Function
`Isv6AddressesEmpty` | 189 | Exported Function
`Isv4AddressesEmpty` | 188 | Exported Function
`IsRuleOldAuthApp` | 184 | Exported Function
`Int_FWVerifyFirewallRule` | 170 | Exported Function
`Int_FWVerifyCryptoSet` | 169 | Exported Function
`Int_FWVerifyMainModeRule` | 171 | Exported Function
`IsCSRuleTunnelMode` | 183 | Exported Function
`IsAddressesEmpty` | 182 | Exported Function
`FwWcsICmp` | 166 | Exported Function
`FwTriggerGetEventForSource` | 150 | Exported Function
`FwSubstituteDeviceName` | 149 | Exported Function
`FwTriggerRearm` | 151 | Exported Function
`FwTriggerUnregisterWait` | 153 | Exported Function
`FwTriggerRegisterWait` | 152 | Exported Function
`FwSubNetsEncode` | 148 | Exported Function
`FwStringCopy` | 144 | Exported Function
`FwStringCanonicalizeCopy` | 143 | Exported Function
`FwStringCopyA` | 145 | Exported Function
`FwStringCopyWtoAAlloc` | 147 | Exported Function
`FwStringCopyAtoWAlloc` | 146 | Exported Function
`FwUpdateHash` | 154 | Exported Function
`FwVerifyFirewallRuleQuery` | 162 | Exported Function
`FwVerifyFirewallRule` | 161 | Exported Function
`FwVerifyMainModeRule` | 163 | Exported Function
`FwVerifyNoHeapLeaks` | 165 | Exported Function
`FwVerifyMainModeRuleQuery` | 164 | Exported Function
`FwVerifyCryptoSetQuery` | 160 | Exported Function
`FwVerifyAuthenticationSetQuery` | 156 | Exported Function
`FwVerifyAuthenticationSet` | 155 | Exported Function
`FwVerifyConnectionSecurityRule` | 157 | Exported Function
`FwVerifyCryptoSet` | 159 | Exported Function
`FwVerifyConnectionSecurityRuleQuery` | 158 | Exported Function
`FwLicensingIsNetIsolationOnly` | 96 | Exported Function
`FwCriticalSectionDestroy` | 36 | Exported Function
`FwCriticalSectionCreate` | 35 | Exported Function
`FwCriticalSectionEnter` | 37 | Exported Function
`FwDWordMultiply` | 39 | Exported Function
`FwCriticalSectionLeave` | 38 | Exported Function
`FwCreateDirectory` | 34 | Exported Function
`FwChangeSourceSignal` | 30 | Exported Function
`FwChangeSourceShutdown` | 29 | Exported Function
`FwChangeSourceSignalStart` | 31 | Exported Function
`FwConstructRemoteMachineSPN` | 33 | Exported Function
`FwCloseHandle` | 32 | Exported Function
`FwEnableMemTracing` | 40 | Exported Function
`FwFreeRpcCallersProcessInfo` | 47 | Exported Function
`FwFreeCertCriteria` | 46 | Exported Function
`FwGetAppBlockList` | 48 | Exported Function
`FwGetExpandedCanonicalLongPathName` | 50 | Exported Function
`FwGetAuthorizedApp` | 49 | Exported Function
`FwFree` | 45 | Exported Function
`FwExpandEnvironmentStrings` | 42 | Exported Function
`FwEnablePrivilege` | 41 | Exported Function
`FwExtractPortNumber` | 1 | Exported Function
`FwFinalHash` | 44 | Exported Function
`FwFieldNameMatchStringBegining` | 43 | Exported Function
`FwChangeSourceInitialize` | 28 | Exported Function
`FwArrayCat` | 12 | Exported Function
`FwArrayAppend` | 11 | Exported Function
`FwArrayCopy` | 13 | Exported Function
`FwArrayDestroy` | 15 | Exported Function
`FwArrayCreateFromRegistry` | 14 | Exported Function
`FwAllocCheckSize` | 10 | Exported Function
`FwAddrChangeSourceShutdown` | 6 | Exported Function
`FwAddrChangeSourceInitialize` | 5 | Exported Function
`FwAddrChangeSourceSignal` | 7 | Exported Function
`FwAllocArray` | 9 | Exported Function
`FwAlloc` | 8 | Exported Function
`FwArrayErase` | 16 | Exported Function
`FwBuildIndirectString` | 24 | Exported Function
`FwBoolIsEqual` | 23 | Exported Function
`FwCanonizeAuthorizedApps` | 25 | Exported Function
`FwChangeSinkDestroy` | 27 | Exported Function
`FwChangeSinkCreate` | 26 | Exported Function
`FwBaseFree` | 22 | Exported Function
`FwAuthSuiteEmpty` | 17 | Exported Function
`FwAuthorizedAppEncode` | 19 | Exported Function
`FwAuthSuiteEmptyByVersion` | 18 | Exported Function
`FwBaseAllocCheckSize` | 21 | Exported Function
`FwBaseAlloc` | 20 | Exported Function
`FwIcfSubNetsCopy` | 84 | Exported Function
`FwIcfIpV6SubNetsCanonize` | 83 | Exported Function
`FwIcfSubNetsDestroy` | 85 | Exported Function
`FwIcfSubNetsIsEqual` | 87 | Exported Function
`FwIcfSubNetsGetScope` | 86 | Exported Function
`FwIcfIpV4SubNetsCanonize` | 82 | Exported Function
`FwIcfAuthorizedAppCopy` | 78 | Exported Function
`FwIcfAuthBypassSubNetsDestroy` | 77 | Exported Function
`FwIcfAuthorizedAppsCopy` | 79 | Exported Function
`FwIcfDynamicFwPortDestroy` | 81 | Exported Function
`FwIcfAuthorizedAppsDestroy` | 80 | Exported Function
`FwImageListDestroy` | 88 | Exported Function
`FwIsBuiltInPort` | 93 | Exported Function
`FwIpV4SubNetDecode` | 92 | Exported Function
`FwIsMachineLocalHost` | 94 | Exported Function
`FwLicensingIsIoT` | 95 | Exported Function
`FwIsValidPorts` | 2 | Exported Function
`FwIOWritePortUseIndications` | 75 | Exported Function
`FWIndicatePortInUse_Helper` | 4 | Exported Function
`FwImageListHasImage` | 89 | Exported Function
`FwInitializeHashContext` | 91 | Exported Function
`FwIOReadPortUseIndications` | 74 | Exported Function
`FwInitMemoryMgr` | 90 | Exported Function
`FwIcfAuthBypassServicesDestroy` | 76 | Exported Function
`FwGetService` | 58 | Exported Function
`FwGetRpcCallersProcessInfo` | 57 | Exported Function
`FwGetServices` | 60 | Exported Function
`FwGetStaticFwPort` | 61 | Exported Function
`FwGetServiceTypes` | 59 | Exported Function
`FwGetRpcCallersProcessImageName` | 56 | Exported Function
`FwGetLongPathName` | 52 | Exported Function
`FwGetIcmpSettings` | 51 | Exported Function
`FwGetProfileIndexFromProfileType` | 53 | Exported Function
`FwGetRemoteAdminSettings` | 55 | Exported Function
`FwGetProfileTypeFromProfileIndex` | 54 | Exported Function
`FwGetStringId` | 62 | Exported Function
`FwHashtableGetNext` | 71 | Exported Function
`FwHashtableFind` | 70 | Exported Function
`FwHashtableInsert` | 72 | Exported Function
`FwHResultToWindowsError` | 66 | Exported Function
`FwHashtableRemove` | 73 | Exported Function
`FwHashtableEmpty` | 69 | Exported Function
`FwGetSysPathName` | 64 | Exported Function
`FwGetStringIdForStatusCode` | 63 | Exported Function
`FwGetTokenInformation` | 65 | Exported Function
`FwHashtableDestroy` | 68 | Exported Function
`FwHashtableCreate` | 67 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fwbase.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/260f936e72b47f8f677efced8d6dedb59ffe511bcab3fea8c35b6d623e5d2896/detection/





MIT License. Copyright (c) 2020 Strontic.


