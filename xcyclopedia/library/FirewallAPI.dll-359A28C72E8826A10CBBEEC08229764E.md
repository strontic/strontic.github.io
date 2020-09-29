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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 8 (0x8) | Exported Function | 0x0000000180001700 | 0x00001700
`FWRevertTransaction` | 98 (0x62) | Exported Function | 0x0000000180043140 | 0x00043140
`FWSelectConSecRule` | 99 (0x63) | Exported Function | 0x00000001800432b0 | 0x000432b0
`FwServicesEnum` | 155 (0x9b) | Exported Function | 0x0000000180021f70 | 0x00021f70
`FwServicesSet` | 156 (0x9c) | Exported Function | 0x0000000180022150 | 0x00022150
`FWSetAuthenticationSet` | 100 (0x64) | Exported Function | 0x00000001800434f0 | 0x000434f0
`FWSetConfig` | 101 (0x65) | Exported Function | 0x00000001800436c0 | 0x000436c0
`FWSetConnectionSecurityRule` | 102 (0x66) | Exported Function | 0x0000000180043800 | 0x00043800
`FWSetCryptoSet` | 103 (0x67) | Exported Function | 0x00000001800439d0 | 0x000439d0
`FWSetFirewallRule` | 104 (0x68) | Exported Function | 0x0000000180043b70 | 0x00043b70
`FWSetGlobalConfig` | 105 (0x69) | Exported Function | 0x0000000180043df0 | 0x00043df0
`FWSetGlobalConfig2` | 106 (0x6a) | Exported Function | 0x0000000180043f90 | 0x00043f90
`FWSetMainModeRule` | 107 (0x6b) | Exported Function | 0x0000000180044120 | 0x00044120
`FWStatusMessageFromStatusCode` | 108 (0x6c) | Exported Function | 0x0000000180044290 | 0x00044290
`FwStringToAddresses` | 157 (0x9d) | Exported Function | 0x0000000180044b00 | 0x00044b00
`FwStringToPorts` | 158 (0x9e) | Exported Function | 0x0000000180044bc0 | 0x00044bc0
`FWUnregisterProduct` | 109 (0x6d) | Exported Function | 0x0000000180044470 | 0x00044470
`FWVerifyAuthenticationSet` | 110 (0x6e) | Exported Function | 0x0000000180044540 | 0x00044540
`FWVerifyAuthenticationSetQuery` | 111 (0x6f) | Exported Function | 0x00000001800445a0 | 0x000445a0
`FWVerifyConnectionSecurityRule` | 112 (0x70) | Exported Function | 0x0000000180044600 | 0x00044600
`FWVerifyConnectionSecurityRuleQuery` | 113 (0x71) | Exported Function | 0x0000000180044660 | 0x00044660
`FWVerifyCryptoSet` | 114 (0x72) | Exported Function | 0x00000001800446c0 | 0x000446c0
`FWRestoreGPODefaults` | 97 (0x61) | Exported Function | 0x0000000180042f90 | 0x00042f90
`FWRestoreDefaults` | 96 (0x60) | Exported Function | 0x0000000180042c70 | 0x00042c70
`FwRestoreDefaults` | 154 (0x9a) | Exported Function | 0x0000000180021ee0 | 0x00021ee0
`FWResetIndicatedTupleInUse` | 95 (0x5f) | Exported Function | 0x0000000180008610 | 0x00008610
`FWIsTargetAProxy` | 85 (0x55) | Exported Function | 0x0000000180042100 | 0x00042100
`FwLogSettingsSet` | 142 (0x8e) | Exported Function | 0x0000000180020ef0 | 0x00020ef0
`FwMergeAddresses` | 143 (0x8f) | Exported Function | 0x0000000180044ae0 | 0x00044ae0
`FwMulticastBroadcastResponsesEnum` | 144 (0x90) | Exported Function | 0x0000000180021130 | 0x00021130
`FwMulticastBroadcastResponsesSet` | 145 (0x91) | Exported Function | 0x00000001800212b0 | 0x000212b0
`FwNotificationsEnum` | 146 (0x92) | Exported Function | 0x0000000180021420 | 0x00021420
`FwNotificationsSet` | 147 (0x93) | Exported Function | 0x00000001800215a0 | 0x000215a0
`FWOpenPolicyStore` | 86 (0x56) | Exported Function | 0x00000001800061d0 | 0x000061d0
`FwOpModesEnum` | 148 (0x94) | Exported Function | 0x0000000180021710 | 0x00021710
`FwOpModesSet` | 149 (0x95) | Exported Function | 0x0000000180021890 | 0x00021890
`FWVerifyCryptoSetQuery` | 115 (0x73) | Exported Function | 0x0000000180044720 | 0x00044720
`FwPortOpeningsAdd` | 150 (0x96) | Exported Function | 0x00000001800219f0 | 0x000219f0
`FwProfileTypeCurrentGet` | 152 (0x98) | Exported Function | 0x0000000180021d80 | 0x00021d80
`FwProfileTypeGet` | 153 (0x99) | Exported Function | 0x0000000180021e30 | 0x00021e30
`FWQueryAuthenticationSets` | 87 (0x57) | Exported Function | 0x0000000180042360 | 0x00042360
`FWQueryConnectionSecurityRules` | 88 (0x58) | Exported Function | 0x00000001800424e0 | 0x000424e0
`FWQueryCryptoSets` | 89 (0x59) | Exported Function | 0x0000000180042650 | 0x00042650
`FWQueryFirewallRules` | 90 (0x5a) | Exported Function | 0x0000000180007b10 | 0x00007b10
`FWQueryIsolationType` | 91 (0x5b) | Exported Function | 0x00000001800427d0 | 0x000427d0
`FWQueryMainModeRules` | 92 (0x5c) | Exported Function | 0x0000000180042970 | 0x00042970
`FWRegisterProduct` | 93 (0x5d) | Exported Function | 0x0000000180042ad0 | 0x00042ad0
`FWResetIndicatedPortInUse` | 94 (0x5e) | Exported Function | 0x0000000180008740 | 0x00008740
`FwPortOpeningsDelete` | 151 (0x97) | Exported Function | 0x0000000180021c00 | 0x00021c00
`FwIsRemoteManagementEnabled` | 141 (0x8d) | Exported Function | 0x000000018001ca30 | 0x0001ca30
`FWVerifyFirewallRule` | 116 (0x74) | Exported Function | 0x0000000180044780 | 0x00044780
`FWVerifyMainModeRule` | 118 (0x76) | Exported Function | 0x00000001800447e0 | 0x000447e0
`NetworkIsolationDeleteAllInterfacesContainer` | 183 (0xb7) | Exported Function | 0x0000000180045c70 | 0x00045c70
`NetworkIsolationDeleteAllowEnterpriseIdRule` | 184 (0xb8) | Exported Function | 0x0000000180045e00 | 0x00045e00
`NetworkIsolationDeleteAppContainer` | 185 (0xb9) | Exported Function | 0x0000000180007ff0 | 0x00007ff0
`NetworkIsolationDeleteAppContainerLoopbackRules` | 186 (0xba) | Exported Function | 0x0000000180045f10 | 0x00045f10
`NetworkIsolationDeleteContainer` | 187 (0xbb) | Exported Function | 0x0000000180046290 | 0x00046290
`NetworkIsolationDeleteInterfaceContainer` | 188 (0xbc) | Exported Function | 0x0000000180046620 | 0x00046620
`NetworkIsolationDeleteUserAppContainers` | 189 (0xbd) | Exported Function | 0x0000000180046760 | 0x00046760
`NetworkIsolationDiagnoseConnectFailure` | 190 (0xbe) | Exported Function | 0x0000000180004c90 | 0x00004c90
`NetworkIsolationDiagnoseConnectFailureAndGetInfo` | 191 (0xbf) | Exported Function | 0x0000000180001770 | 0x00001770
`NetworkIsolationDiagnoseListen` | 192 (0xc0) | Exported Function | 0x00000001800469f0 | 0x000469f0
`NetworkIsolationDiagnoseSocketCreation` | 193 (0xc1) | Exported Function | 0x0000000180046b70 | 0x00046b70
`NetworkIsolationEnumAppContainers` | 194 (0xc2) | Exported Function | 0x0000000180046ce0 | 0x00046ce0
`NetworkIsolationEnumerateAppContainerRules` | 195 (0xc3) | Exported Function | 0x0000000180046ed0 | 0x00046ed0
`NetworkIsolationFreeAppContainers` | 7 (0x7) | Exported Function | 0x0000000180008230 | 0x00008230
`NetworkIsolationGetAppContainer` | 196 (0xc4) | Exported Function | 0x0000000180046fa0 | 0x00046fa0
`NetworkIsolationGetAppContainerConfig` | 197 (0xc5) | Exported Function | 0x0000000180003700 | 0x00003700
`NetworkIsolationGetEnterpriseId` | 198 (0xc6) | Exported Function | 0x0000000180047160 | 0x00047160
`NetworkIsolationGetEnterpriseIdAsync` | 199 (0xc7) | Exported Function | 0x00000001800018a0 | 0x000018a0
`NetworkIsolationGetEnterpriseIdClose` | 200 (0xc8) | Exported Function | 0x00000001800011c0 | 0x000011c0
`NetworkIsolationRegisterForAppContainerChanges` | 201 (0xc9) | Exported Function | 0x00000001800471e0 | 0x000471e0
`NetworkIsolationSetAppContainerConfig` | 202 (0xca) | Exported Function | 0x0000000180047670 | 0x00047670
`NetworkIsolationCreateInterfaceContainer` | 182 (0xb6) | Exported Function | 0x0000000180045930 | 0x00045930
`NetworkIsolationCreateContainer` | 181 (0xb5) | Exported Function | 0x0000000180045520 | 0x00045520
`NetworkIsolationCreateAppContainerLoopbackRules` | 180 (0xb4) | Exported Function | 0x0000000180045170 | 0x00045170
`NetworkIsolationCreateAppContainer` | 179 (0xb3) | Exported Function | 0x0000000180007d90 | 0x00007d90
`FWVerifyMainModeRuleQuery` | 119 (0x77) | Exported Function | 0x0000000180044840 | 0x00044840
`GetDisabledInterfaces` | 6 (0x6) | Exported Function | 0x000000018001b2c0 | 0x0001b2c0
`IcfAddrChangeNotificationCreate` | 159 (0x9f) | Exported Function | 0x00000001800035d0 | 0x000035d0
`IcfChangeNotificationCreate` | 160 (0xa0) | Exported Function | 0x00000001800034f0 | 0x000034f0
`IcfChangeNotificationDestroy` | 161 (0xa1) | Exported Function | 0x000000018001cc30 | 0x0001cc30
`IcfConnect` | 162 (0xa2) | Exported Function | 0x000000018001ccc0 | 0x0001ccc0
`IcfDisconnect` | 163 (0xa3) | Exported Function | 0x0000000180007d20 | 0x00007d20
`IcfFreeDynamicFwPorts` | 164 (0xa4) | Exported Function | 0x000000018001cce0 | 0x0001cce0
`IcfFreeProfile` | 165 (0xa5) | Exported Function | 0x000000018001cdb0 | 0x0001cdb0
`IcfFreeTickets` | 166 (0xa6) | Exported Function | 0x000000018001d0d0 | 0x0001d0d0
`FWVerifyFirewallRuleQuery` | 117 (0x75) | Exported Function | 0x00000001800034a0 | 0x000034a0
`IcfGetCurrentProfileType` | 167 (0xa7) | Exported Function | 0x000000018001d170 | 0x0001d170
`IcfGetOperationalMode` | 169 (0xa9) | Exported Function | 0x000000018001d560 | 0x0001d560
`IcfGetProfile` | 170 (0xaa) | Exported Function | 0x000000018001d700 | 0x0001d700
`IcfGetTickets` | 171 (0xab) | Exported Function | 0x000000018001da60 | 0x0001da60
`IcfIsPortAllowed` | 172 (0xac) | Exported Function | 0x0000000180022f40 | 0x00022f40
`IcfOpenDynamicFwPortWithoutSocket` | 173 (0xad) | Exported Function | 0x0000000180007d20 | 0x00007d20
`IcfSubNetsGetScope` | 174 (0xae) | Exported Function | 0x000000018001dd60 | 0x0001dd60
`IsFirewallInCoExistanceMode` | 175 (0xaf) | Exported Function | 0x00000001800039a0 | 0x000039a0
`IsPortOrICMPAllowed` | 176 (0xb0) | Exported Function | 0x0000000180023060 | 0x00023060
`NetworkIsolationAddAllowEnterpriseIdRule` | 177 (0xb1) | Exported Function | 0x0000000180044ca0 | 0x00044ca0
`NetworkIsolationCreateAllInterfacesContainer` | 178 (0xb2) | Exported Function | 0x0000000180044e40 | 0x00044e40
`IcfGetDynamicFwPorts` | 168 (0xa8) | Exported Function | 0x000000018001d220 | 0x0001d220
`FwIsGroupPolicyEnforced` | 140 (0x8c) | Exported Function | 0x0000000180001440 | 0x00001440
`FwInterfaceTypesToBstr` | 5 (0x5) | Exported Function | 0x0000000180018910 | 0x00018910
`FWIndicateTupleInUse2` | 84 (0x54) | Exported Function | 0x0000000180041f10 | 0x00041f10
`FwCopyAuthSet` | 130 (0x82) | Exported Function | 0x0000000180044920 | 0x00044920
`FWCopyConnectionSecurityRule` | 23 (0x17) | Exported Function | 0x000000018003e9e0 | 0x0003e9e0
`FWCopyCryptoSet` | 24 (0x18) | Exported Function | 0x000000018003ea40 | 0x0003ea40
`FWCopyFirewallRule` | 25 (0x19) | Exported Function | 0x000000018003eaa0 | 0x0003eaa0
`FwCopyMainModeRule` | 131 (0x83) | Exported Function | 0x0000000180044980 | 0x00044980
`FwCopyWFAddressesContents` | 132 (0x84) | Exported Function | 0x00000001800449e0 | 0x000449e0
`FWDeleteAllAuthenticationSets` | 26 (0x1a) | Exported Function | 0x000000018003eb00 | 0x0003eb00
`FWDeleteAllConnectionSecurityRules` | 27 (0x1b) | Exported Function | 0x000000018003ec30 | 0x0003ec30
`FWDeleteAllCryptoSets` | 28 (0x1c) | Exported Function | 0x000000018003ed60 | 0x0003ed60
`FWDeleteAllFirewallRules` | 29 (0x1d) | Exported Function | 0x000000018003ee90 | 0x0003ee90
`FWDeleteAllMainModeRules` | 30 (0x1e) | Exported Function | 0x000000018003efc0 | 0x0003efc0
`FWDeleteAuthenticationSet` | 31 (0x1f) | Exported Function | 0x000000018003f0f0 | 0x0003f0f0
`FWDeleteConnectionSecurityRule` | 32 (0x20) | Exported Function | 0x000000018003f220 | 0x0003f220
`FWDeleteCryptoSet` | 33 (0x21) | Exported Function | 0x000000018003f350 | 0x0003f350
`FWDeleteFirewallRule` | 34 (0x22) | Exported Function | 0x000000018003f480 | 0x0003f480
`FWDeleteMainModeRule` | 35 (0x23) | Exported Function | 0x000000018003f5b0 | 0x0003f5b0
`FWDeletePhase1SAs` | 36 (0x24) | Exported Function | 0x000000018003f6e0 | 0x0003f6e0
`FWDeletePhase2SAs` | 37 (0x25) | Exported Function | 0x000000018003f7f0 | 0x0003f7f0
`FWDeleteSecurityRealm` | 38 (0x26) | Exported Function | 0x000000018003f900 | 0x0003f900
`FWDiagGetAppList` | 39 (0x27) | Exported Function | 0x000000018003f930 | 0x0003f930
`FwEmptyWFAddresses` | 133 (0x85) | Exported Function | 0x0000000180008210 | 0x00008210
`FWCopyAuthenticationSet` | 22 (0x16) | Exported Function | 0x000000018003e980 | 0x0003e980
`FwConvertIPv6SubNetToRange` | 129 (0x81) | Exported Function | 0x0000000180044900 | 0x00044900
`FWClosePolicyStore` | 21 (0x15) | Exported Function | 0x0000000180005350 | 0x00005350
`FWChangeTransactionalState` | 20 (0x14) | Exported Function | 0x000000018003e7a0 | 0x0003e7a0
`DllGetClassObject` | 9 (0x9) | Exported Function | 0x00000001800033e0 | 0x000033e0
`DllRegisterServer` | 10 (0xa) | Exported Function | 0x0000000180016820 | 0x00016820
`DllUnregisterServer` | 11 (0xb) | Exported Function | 0x0000000180016880 | 0x00016880
`FwActivate` | 120 (0x78) | Exported Function | 0x000000018001e320 | 0x0001e320
`FWAddAuthenticationSet` | 12 (0xc) | Exported Function | 0x000000018003dc00 | 0x0003dc00
`FWAddConnectionSecurityRule` | 13 (0xd) | Exported Function | 0x000000018003dde0 | 0x0003dde0
`FWAddCryptoSet` | 14 (0xe) | Exported Function | 0x000000018003dfb0 | 0x0003dfb0
`FWAddFirewallRule` | 15 (0xf) | Exported Function | 0x000000018003e150 | 0x0003e150
`FWAddMainModeRule` | 16 (0x10) | Exported Function | 0x000000018003e3d0 | 0x0003e3d0
`FWAddSecurityRealm` | 17 (0x11) | Exported Function | 0x000000018003e550 | 0x0003e550
`FWEnumAdapters` | 40 (0x28) | Exported Function | 0x000000018003fa30 | 0x0003fa30
`FwAlloc` | 121 (0x79) | Exported Function | 0x0000000180002620 | 0x00002620
`FwAllowedProgramsAdd` | 123 (0x7b) | Exported Function | 0x0000000180020740 | 0x00020740
`FwAllowedProgramsDelete` | 124 (0x7c) | Exported Function | 0x0000000180020920 | 0x00020920
`FwAnalyzeFirewallPolicy` | 125 (0x7d) | Exported Function | 0x0000000180003660 | 0x00003660
`FwAnalyzeFirewallPolicyOnProfile` | 126 (0x7e) | Exported Function | 0x0000000180004330 | 0x00004330
`FwApiHelperFree` | 127 (0x7f) | Exported Function | 0x0000000180020a90 | 0x00020a90
`FwApiHelperInit` | 128 (0x80) | Exported Function | 0x0000000180020b10 | 0x00020b10
`FwBstrToInterfaceTypes` | 1 (0x1) | Exported Function | 0x0000000180017e80 | 0x00017e80
`FwBstrToPorts` | 2 (0x2) | Exported Function | 0x0000000180017fb0 | 0x00017fb0
`FWChangeNotificationCreate` | 18 (0x12) | Exported Function | 0x00000001800034f0 | 0x000034f0
`FWChangeNotificationDestroy` | 19 (0x13) | Exported Function | 0x000000018001cc30 | 0x0001cc30
`FwAllocCheckSize` | 122 (0x7a) | Exported Function | 0x00000001800448a0 | 0x000448a0
`FWEnumAuthenticationSets` | 41 (0x29) | Exported Function | 0x000000018003fb40 | 0x0003fb40
`FWEnumConnectionSecurityRules` | 42 (0x2a) | Exported Function | 0x000000018003fd30 | 0x0003fd30
`FWEnumCryptoSets` | 43 (0x2b) | Exported Function | 0x000000018003ff20 | 0x0003ff20
`FWFreeMainModeRulesByHandle` | 68 (0x44) | Exported Function | 0x0000000180041480 | 0x00041480
`FWFreeNetworks` | 69 (0x45) | Exported Function | 0x0000000180008230 | 0x00008230
`FWFreePhase1SAs` | 70 (0x46) | Exported Function | 0x0000000180041570 | 0x00041570
`FWFreePhase2SAs` | 71 (0x47) | Exported Function | 0x0000000180041670 | 0x00041670
`FwFreePorts` | 136 (0x88) | Exported Function | 0x0000000180044a40 | 0x00044a40
`FWFreeProducts` | 72 (0x48) | Exported Function | 0x0000000180008230 | 0x00008230
`FwGetAddressesAsString` | 137 (0x89) | Exported Function | 0x0000000180044a80 | 0x00044a80
`FWGetConfig` | 73 (0x49) | Exported Function | 0x0000000180004b40 | 0x00004b40
`FWGetConfig2` | 74 (0x4a) | Exported Function | 0x0000000180041740 | 0x00041740
`FwGetCurrentProfile` | 3 (0x3) | Exported Function | 0x000000018001b1f0 | 0x0001b1f0
`FWFreeMainModeRules` | 67 (0x43) | Exported Function | 0x00000001800413b0 | 0x000413b0
`FWGetGlobalConfig` | 75 (0x4b) | Exported Function | 0x0000000180003810 | 0x00003810
`FWGetGlobalConfig3` | 77 (0x4d) | Exported Function | 0x0000000180041890 | 0x00041890
`FWGetIndicatedPortInUse` | 78 (0x4e) | Exported Function | 0x0000000180008820 | 0x00008820
`FwGetVersionField` | 4 (0x4) | Exported Function | 0x00000001800182b0 | 0x000182b0
`FwIcmpSettingsEnum` | 138 (0x8a) | Exported Function | 0x0000000180020be0 | 0x00020be0
`FwIcmpSettingsSet` | 139 (0x8b) | Exported Function | 0x0000000180020d70 | 0x00020d70
`FWImportPolicy` | 79 (0x4f) | Exported Function | 0x00000001800419f0 | 0x000419f0
`FWIndicatePortInUse` | 80 (0x50) | Exported Function | 0x0000000180008250 | 0x00008250
`FWIndicateProxyForUrl` | 81 (0x51) | Exported Function | 0x0000000180041b90 | 0x00041b90
`FWIndicateProxyResolverRefresh` | 82 (0x52) | Exported Function | 0x0000000180041d10 | 0x00041d10
`FWIndicateTupleInUse` | 83 (0x53) | Exported Function | 0x0000000180041d20 | 0x00041d20
`FWGetGlobalConfig2` | 76 (0x4c) | Exported Function | 0x000000018000b760 | 0x0000b760
`NetworkIsolationSetupAppContainerBinaries` | 203 (0xcb) | Exported Function | 0x00000001800477c0 | 0x000477c0
`FWFreeMainModeRule` | 66 (0x42) | Exported Function | 0x0000000180041390 | 0x00041390
`FWFreeFirewallRulesByHandle` | 64 (0x40) | Exported Function | 0x00000001800411d0 | 0x000411d0
`FWEnumFirewallRules` | 44 (0x2c) | Exported Function | 0x00000001800400e0 | 0x000400e0
`FWEnumMainModeRules` | 45 (0x2d) | Exported Function | 0x0000000180040370 | 0x00040370
`FWEnumNetworks` | 46 (0x2e) | Exported Function | 0x0000000180040510 | 0x00040510
`FWEnumPhase1SAs` | 47 (0x2f) | Exported Function | 0x0000000180040620 | 0x00040620
`FWEnumPhase2SAs` | 48 (0x30) | Exported Function | 0x0000000180040750 | 0x00040750
`FWEnumProducts` | 49 (0x31) | Exported Function | 0x0000000180040880 | 0x00040880
`FWExportPolicy` | 50 (0x32) | Exported Function | 0x0000000180040990 | 0x00040990
`FwFree` | 134 (0x86) | Exported Function | 0x0000000180008230 | 0x00008230
`FWFreeAdapters` | 51 (0x33) | Exported Function | 0x0000000180008230 | 0x00008230
`FwFreeAddresses` | 135 (0x87) | Exported Function | 0x0000000180008210 | 0x00008210
`FWFreeFirewallRulesOld` | 65 (0x41) | Exported Function | 0x00000001800412c0 | 0x000412c0
`FWFreeAuthenticationSet` | 52 (0x34) | Exported Function | 0x0000000180040b30 | 0x00040b30
`FWFreeAuthenticationSetsByHandle` | 54 (0x36) | Exported Function | 0x0000000180040c10 | 0x00040c10
`FWFreeConnectionSecurityRule` | 55 (0x37) | Exported Function | 0x0000000180040d00 | 0x00040d00
`FWFreeConnectionSecurityRules` | 56 (0x38) | Exported Function | 0x0000000180040d20 | 0x00040d20
`FWFreeConnectionSecurityRulesByHandle` | 57 (0x39) | Exported Function | 0x0000000180040df0 | 0x00040df0
`FWFreeCryptoSet` | 58 (0x3a) | Exported Function | 0x0000000180040ee0 | 0x00040ee0
`FWFreeCryptoSets` | 59 (0x3b) | Exported Function | 0x0000000180040f00 | 0x00040f00
`FWFreeCryptoSetsByHandle` | 60 (0x3c) | Exported Function | 0x0000000180040fd0 | 0x00040fd0
`FWFreeDiagAppList` | 61 (0x3d) | Exported Function | 0x0000000180008230 | 0x00008230
`FWFreeFirewallRule` | 62 (0x3e) | Exported Function | 0x00000001800410f0 | 0x000410f0
`FWFreeFirewallRules` | 63 (0x3f) | Exported Function | 0x0000000180041110 | 0x00041110
`FWFreeAuthenticationSets` | 53 (0x35) | Exported Function | 0x0000000180040b50 | 0x00040b50
`NetworkIsolationUnregisterForAppContainerChanges` | 204 (0xcc) | Exported Function | 0x0000000180047b50 | 0x00047b50


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


