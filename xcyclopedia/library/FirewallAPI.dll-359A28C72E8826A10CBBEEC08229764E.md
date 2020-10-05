---
title: FirewallAPI.dll | Windows Defender Firewall API
excerpt: What is FirewallAPI.dll?
---

# FirewallAPI.dll 

* File Path: `C:\Windows\system32\FirewallAPI.dll`
* Description: Windows Defender Firewall API

## Hashes

Type | Hash
-- | --
MD5 | `359A28C72E8826A10CBBEEC08229764E`
SHA1 | `2A92E8232FF6EED56D33651E83CB6523FBBE7AF7`
SHA256 | `67CD9C7F5AB8855E1F39AEA3C663235BD7EF9F155184EB28FDD0783D53D9F91B`
SHA384 | `A08FC6E9A6A643A22798601C2B21A3A734F2C6DD18BC8A47DBC203904ACE2B9A401EF44442B6A223610B92016E40B337`
SHA512 | `1A722E439CB57C9B9F89F2D1D5957014F4448365284DD4ED8551CFA7822697BE2ACF1A674FCA765EE713B56489C0D2AFCF926BCEB3532CDBA4110588BF194E27`
SSDEEP | `12288:f21N+JIr2FDUtIs9QwxE0OwcUJ5mwFs1CBg4hc:f26PxucUjmwOG9`
IMP | `AE71D5D800E2E697BADE59EF2A9D288B`
PESHA1 | `E64D7A91F2ADD49B82F85749B7C437BEDBB0230C`
PE256 | `3264949F4DE1E7D7A11CFA2F300B82F22E57C6904823E988128280BEFCECF22A`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`FWSetConnectionSecurityRule` | 102 | Exported Function
`FWSetConfig` | 101 | Exported Function
`FWSetAuthenticationSet` | 100 | Exported Function
`FWSetGlobalConfig` | 105 | Exported Function
`FWSetFirewallRule` | 104 | Exported Function
`FWSetCryptoSet` | 103 | Exported Function
`FWRevertTransaction` | 98 | Exported Function
`FWRestoreGPODefaults` | 97 | Exported Function
`FWRestoreDefaults` | 96 | Exported Function
`FwServicesSet` | 156 | Exported Function
`FwServicesEnum` | 155 | Exported Function
`FWSelectConSecRule` | 99 | Exported Function
`FWSetGlobalConfig2` | 106 | Exported Function
`FWVerifyConnectionSecurityRuleQuery` | 113 | Exported Function
`FWVerifyConnectionSecurityRule` | 112 | Exported Function
`FWVerifyAuthenticationSetQuery` | 111 | Exported Function
`FWVerifyFirewallRule` | 116 | Exported Function
`FWVerifyCryptoSetQuery` | 115 | Exported Function
`FWVerifyCryptoSet` | 114 | Exported Function
`FwStringToAddresses` | 157 | Exported Function
`FWStatusMessageFromStatusCode` | 108 | Exported Function
`FWSetMainModeRule` | 107 | Exported Function
`FWVerifyAuthenticationSet` | 110 | Exported Function
`FWUnregisterProduct` | 109 | Exported Function
`FwStringToPorts` | 158 | Exported Function
`FwRestoreDefaults` | 154 | Exported Function
`FwNotificationsSet` | 147 | Exported Function
`FwNotificationsEnum` | 146 | Exported Function
`FwMulticastBroadcastResponsesSet` | 145 | Exported Function
`FwOpModesSet` | 149 | Exported Function
`FwOpModesEnum` | 148 | Exported Function
`FWOpenPolicyStore` | 86 | Exported Function
`FWIsTargetAProxy` | 85 | Exported Function
`FwIsRemoteManagementEnabled` | 141 | Exported Function
`FwIsGroupPolicyEnforced` | 140 | Exported Function
`FwMulticastBroadcastResponsesEnum` | 144 | Exported Function
`FwMergeAddresses` | 143 | Exported Function
`FwLogSettingsSet` | 142 | Exported Function
`FwPortOpeningsAdd` | 150 | Exported Function
`FWQueryMainModeRules` | 92 | Exported Function
`FWQueryIsolationType` | 91 | Exported Function
`FWQueryFirewallRules` | 90 | Exported Function
`FWResetIndicatedTupleInUse` | 95 | Exported Function
`FWResetIndicatedPortInUse` | 94 | Exported Function
`FWRegisterProduct` | 93 | Exported Function
`FwProfileTypeGet` | 153 | Exported Function
`FwProfileTypeCurrentGet` | 152 | Exported Function
`FwPortOpeningsDelete` | 151 | Exported Function
`FWQueryCryptoSets` | 89 | Exported Function
`FWQueryConnectionSecurityRules` | 88 | Exported Function
`FWQueryAuthenticationSets` | 87 | Exported Function
`NetworkIsolationDeleteUserAppContainers` | 189 | Exported Function
`NetworkIsolationDeleteInterfaceContainer` | 188 | Exported Function
`NetworkIsolationDeleteContainer` | 187 | Exported Function
`NetworkIsolationDiagnoseListen` | 192 | Exported Function
`NetworkIsolationDiagnoseConnectFailureAndGetInfo` | 191 | Exported Function
`NetworkIsolationDiagnoseConnectFailure` | 190 | Exported Function
`NetworkIsolationDeleteAllInterfacesContainer` | 183 | Exported Function
`NetworkIsolationCreateInterfaceContainer` | 182 | Exported Function
`NetworkIsolationCreateContainer` | 181 | Exported Function
`NetworkIsolationDeleteAppContainerLoopbackRules` | 186 | Exported Function
`NetworkIsolationDeleteAppContainer` | 185 | Exported Function
`NetworkIsolationDeleteAllowEnterpriseIdRule` | 184 | Exported Function
`NetworkIsolationDiagnoseSocketCreation` | 193 | Exported Function
`NetworkIsolationRegisterForAppContainerChanges` | 201 | Exported Function
`NetworkIsolationGetEnterpriseIdClose` | 200 | Exported Function
`NetworkIsolationGetEnterpriseIdAsync` | 199 | Exported Function
`NetworkIsolationUnregisterForAppContainerChanges` | 204 | Exported Function
`NetworkIsolationSetupAppContainerBinaries` | 203 | Exported Function
`NetworkIsolationSetAppContainerConfig` | 202 | Exported Function
`NetworkIsolationFreeAppContainers` | 7 | Exported Function
`NetworkIsolationEnumerateAppContainerRules` | 195 | Exported Function
`NetworkIsolationEnumAppContainers` | 194 | Exported Function
`NetworkIsolationGetEnterpriseId` | 198 | Exported Function
`NetworkIsolationGetAppContainerConfig` | 197 | Exported Function
`NetworkIsolationGetAppContainer` | 196 | Exported Function
`NetworkIsolationCreateAppContainerLoopbackRules` | 180 | Exported Function
`IcfDisconnect` | 163 | Exported Function
`IcfConnect` | 162 | Exported Function
`IcfChangeNotificationDestroy` | 161 | Exported Function
`IcfFreeTickets` | 166 | Exported Function
`IcfFreeProfile` | 165 | Exported Function
`IcfFreeDynamicFwPorts` | 164 | Exported Function
`FWVerifyMainModeRuleQuery` | 119 | Exported Function
`FWVerifyMainModeRule` | 118 | Exported Function
`FWVerifyFirewallRuleQuery` | 117 | Exported Function
`IcfChangeNotificationCreate` | 160 | Exported Function
`IcfAddrChangeNotificationCreate` | 159 | Exported Function
`GetDisabledInterfaces` | 6 | Exported Function
`IcfGetCurrentProfileType` | 167 | Exported Function
`IsPortOrICMPAllowed` | 176 | Exported Function
`IsFirewallInCoExistanceMode` | 175 | Exported Function
`IcfSubNetsGetScope` | 174 | Exported Function
`NetworkIsolationCreateAppContainer` | 179 | Exported Function
`NetworkIsolationCreateAllInterfacesContainer` | 178 | Exported Function
`NetworkIsolationAddAllowEnterpriseIdRule` | 177 | Exported Function
`IcfGetProfile` | 170 | Exported Function
`IcfGetOperationalMode` | 169 | Exported Function
`IcfGetDynamicFwPorts` | 168 | Exported Function
`IcfOpenDynamicFwPortWithoutSocket` | 173 | Exported Function
`IcfIsPortAllowed` | 172 | Exported Function
`IcfGetTickets` | 171 | Exported Function
`FWDeleteAllConnectionSecurityRules` | 27 | Exported Function
`FWDeleteAllAuthenticationSets` | 26 | Exported Function
`FwCopyWFAddressesContents` | 132 | Exported Function
`FWDeleteAllMainModeRules` | 30 | Exported Function
`FWDeleteAllFirewallRules` | 29 | Exported Function
`FWDeleteAllCryptoSets` | 28 | Exported Function
`FWCopyConnectionSecurityRule` | 23 | Exported Function
`FwCopyAuthSet` | 130 | Exported Function
`FWCopyAuthenticationSet` | 22 | Exported Function
`FwCopyMainModeRule` | 131 | Exported Function
`FWCopyFirewallRule` | 25 | Exported Function
`FWCopyCryptoSet` | 24 | Exported Function
`FWDeleteAuthenticationSet` | 31 | Exported Function
`FwEmptyWFAddresses` | 133 | Exported Function
`FWDiagGetAppList` | 39 | Exported Function
`FWDeleteSecurityRealm` | 38 | Exported Function
`FWEnumConnectionSecurityRules` | 42 | Exported Function
`FWEnumAuthenticationSets` | 41 | Exported Function
`FWEnumAdapters` | 40 | Exported Function
`FWDeleteFirewallRule` | 34 | Exported Function
`FWDeleteCryptoSet` | 33 | Exported Function
`FWDeleteConnectionSecurityRule` | 32 | Exported Function
`FWDeletePhase2SAs` | 37 | Exported Function
`FWDeletePhase1SAs` | 36 | Exported Function
`FWDeleteMainModeRule` | 35 | Exported Function
`FwConvertIPv6SubNetToRange` | 129 | Exported Function
`FWAddFirewallRule` | 15 | Exported Function
`FWAddCryptoSet` | 14 | Exported Function
`FWAddConnectionSecurityRule` | 13 | Exported Function
`FwAlloc` | 121 | Exported Function
`FWAddSecurityRealm` | 17 | Exported Function
`FWAddMainModeRule` | 16 | Exported Function
`DllRegisterServer` | 10 | Exported Function
`DllGetClassObject` | 9 | Exported Function
`DllCanUnloadNow` | 8 | Exported Function
`FWAddAuthenticationSet` | 12 | Exported Function
`FwActivate` | 120 | Exported Function
`DllUnregisterServer` | 11 | Exported Function
`FwAllocCheckSize` | 122 | Exported Function
`FWChangeNotificationCreate` | 18 | Exported Function
`FwBstrToPorts` | 2 | Exported Function
`FwBstrToInterfaceTypes` | 1 | Exported Function
`FWClosePolicyStore` | 21 | Exported Function
`FWChangeTransactionalState` | 20 | Exported Function
`FWChangeNotificationDestroy` | 19 | Exported Function
`FwAnalyzeFirewallPolicy` | 125 | Exported Function
`FwAllowedProgramsDelete` | 124 | Exported Function
`FwAllowedProgramsAdd` | 123 | Exported Function
`FwApiHelperInit` | 128 | Exported Function
`FwApiHelperFree` | 127 | Exported Function
`FwAnalyzeFirewallPolicyOnProfile` | 126 | Exported Function
`FWGetConfig` | 73 | Exported Function
`FwGetAddressesAsString` | 137 | Exported Function
`FWFreeProducts` | 72 | Exported Function
`FWGetGlobalConfig` | 75 | Exported Function
`FwGetCurrentProfile` | 3 | Exported Function
`FWGetConfig2` | 74 | Exported Function
`FWFreeNetworks` | 69 | Exported Function
`FWFreeMainModeRulesByHandle` | 68 | Exported Function
`FWFreeMainModeRules` | 67 | Exported Function
`FwFreePorts` | 136 | Exported Function
`FWFreePhase2SAs` | 71 | Exported Function
`FWFreePhase1SAs` | 70 | Exported Function
`FWGetGlobalConfig2` | 76 | Exported Function
`FWIndicateProxyResolverRefresh` | 82 | Exported Function
`FWIndicateProxyForUrl` | 81 | Exported Function
`FWIndicatePortInUse` | 80 | Exported Function
`FwInterfaceTypesToBstr` | 5 | Exported Function
`FWIndicateTupleInUse2` | 84 | Exported Function
`FWIndicateTupleInUse` | 83 | Exported Function
`FwGetVersionField` | 4 | Exported Function
`FWGetIndicatedPortInUse` | 78 | Exported Function
`FWGetGlobalConfig3` | 77 | Exported Function
`FWImportPolicy` | 79 | Exported Function
`FwIcmpSettingsSet` | 139 | Exported Function
`FwIcmpSettingsEnum` | 138 | Exported Function
`FWFreeMainModeRule` | 66 | Exported Function
`FwFree` | 134 | Exported Function
`FWExportPolicy` | 50 | Exported Function
`FWEnumProducts` | 49 | Exported Function
`FWFreeAuthenticationSet` | 52 | Exported Function
`FwFreeAddresses` | 135 | Exported Function
`FWFreeAdapters` | 51 | Exported Function
`FWEnumMainModeRules` | 45 | Exported Function
`FWEnumFirewallRules` | 44 | Exported Function
`FWEnumCryptoSets` | 43 | Exported Function
`FWEnumPhase2SAs` | 48 | Exported Function
`FWEnumPhase1SAs` | 47 | Exported Function
`FWEnumNetworks` | 46 | Exported Function
`FWFreeAuthenticationSets` | 53 | Exported Function
`FWFreeFirewallRule` | 62 | Exported Function
`FWFreeDiagAppList` | 61 | Exported Function
`FWFreeCryptoSetsByHandle` | 60 | Exported Function
`FWFreeFirewallRulesOld` | 65 | Exported Function
`FWFreeFirewallRulesByHandle` | 64 | Exported Function
`FWFreeFirewallRules` | 63 | Exported Function
`FWFreeConnectionSecurityRules` | 56 | Exported Function
`FWFreeConnectionSecurityRule` | 55 | Exported Function
`FWFreeAuthenticationSetsByHandle` | 54 | Exported Function
`FWFreeCryptoSets` | 59 | Exported Function
`FWFreeCryptoSet` | 58 | Exported Function
`FWFreeConnectionSecurityRulesByHandle` | 57 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FirewallAPI.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/67cd9c7f5ab8855e1f39aea3c663235bd7ef9f155184eb28fdd0783d53d9f91b/detection/





MIT License. Copyright (c) 2020 Strontic.


