---
title: FirewallAPI.dll | Windows Defender Firewall API
excerpt: What is FirewallAPI.dll?
---

# FirewallAPI.dll 

* File Path: `C:\Windows\SysWOW64\FirewallAPI.dll`
* Description: Windows Defender Firewall API

## Hashes

Type | Hash
-- | --
MD5 | `A1D534FF08E38DD57A1158ED352959E9`
SHA1 | `683910DC36D983730B5B55785C1DA219E5984DED`
SHA256 | `D4DD047F970CD6BDE2A789C69E0E87EF700C9A11C89763413E7013821FEE84ED`
SHA384 | `D785E6466CBE56F31A5BEDCAF900D95633354A6F39BC2C2D85F633782E401F52E87854FE80749A83C323BEC2E793BAF6`
SHA512 | `26DF074E4BC0CD1DFD34299530AA6937BD0A2E761DA027E7749F84DF95C47CB58A61720A650E5065C44D357852ECF4E5EDCB390CD19C00C80AFC378972D0143F`
SSDEEP | `6144:v7cmcAOZ4QoREoGGDNGotGz8YI3pT3Ems90JM4HNEdSr5fx+bsv2fJFa81R3qi:TnOZotGz8YQVX80JM46dSl5vvyF36`
IMP | `A219D71AADA18BFCFCD8630071EBF18D`
PESHA1 | `4E5445AC0EC536CF5D13E55617E7FBD09F26086E`
PE256 | `40ECD9C1107874EFEA103F56E6BB83786A288508E67085659367384EE554A8A0`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 8 (0x8) | Exported Function | 0x10012db0 | 0x00012db0
`FWRevertTransaction` | 98 (0x62) | Exported Function | 0x10042d90 | 0x00042d90
`FWSelectConSecRule` | 99 (0x63) | Exported Function | 0x10042ec0 | 0x00042ec0
`FwServicesEnum` | 155 (0x9b) | Exported Function | 0x1002ae60 | 0x0002ae60
`FwServicesSet` | 156 (0x9c) | Exported Function | 0x1002aff0 | 0x0002aff0
`FWSetAuthenticationSet` | 100 (0x64) | Exported Function | 0x10043030 | 0x00043030
`FWSetConfig` | 101 (0x65) | Exported Function | 0x100431c0 | 0x000431c0
`FWSetConnectionSecurityRule` | 102 (0x66) | Exported Function | 0x100432b0 | 0x000432b0
`FWSetCryptoSet` | 103 (0x67) | Exported Function | 0x10043430 | 0x00043430
`FWSetFirewallRule` | 104 (0x68) | Exported Function | 0x10043580 | 0x00043580
`FWSetGlobalConfig` | 106 (0x6a) | Exported Function | 0x10043900 | 0x00043900
`FWSetGlobalConfig2` | 105 (0x69) | Exported Function | 0x100437b0 | 0x000437b0
`FWSetMainModeRule` | 107 (0x6b) | Exported Function | 0x10043a40 | 0x00043a40
`FWStatusMessageFromStatusCode` | 108 (0x6c) | Exported Function | 0x10043b70 | 0x00043b70
`FwStringToAddresses` | 157 (0x9d) | Exported Function | 0x10044240 | 0x00044240
`FwStringToPorts` | 158 (0x9e) | Exported Function | 0x100442d0 | 0x000442d0
`FWUnregisterProduct` | 109 (0x6d) | Exported Function | 0x10043d10 | 0x00043d10
`FWVerifyAuthenticationSet` | 110 (0x6e) | Exported Function | 0x10043dc0 | 0x00043dc0
`FWVerifyAuthenticationSetQuery` | 111 (0x6f) | Exported Function | 0x10043e10 | 0x00043e10
`FWVerifyConnectionSecurityRule` | 112 (0x70) | Exported Function | 0x10043e60 | 0x00043e60
`FWVerifyConnectionSecurityRuleQuery` | 113 (0x71) | Exported Function | 0x10043eb0 | 0x00043eb0
`FWVerifyCryptoSet` | 114 (0x72) | Exported Function | 0x10043f00 | 0x00043f00
`FWRestoreGPODefaults` | 97 (0x61) | Exported Function | 0x10042c20 | 0x00042c20
`FWRestoreDefaults` | 96 (0x60) | Exported Function | 0x10042980 | 0x00042980
`FwRestoreDefaults` | 154 (0x9a) | Exported Function | 0x1002adf0 | 0x0002adf0
`FWResetIndicatedTupleInUse` | 95 (0x5f) | Exported Function | 0x10016280 | 0x00016280
`FWIsTargetAProxy` | 85 (0x55) | Exported Function | 0x100420d0 | 0x000420d0
`FwLogSettingsSet` | 142 (0x8e) | Exported Function | 0x1002a1b0 | 0x0002a1b0
`FwMergeAddresses` | 143 (0x8f) | Exported Function | 0x10044230 | 0x00044230
`FwMulticastBroadcastResponsesEnum` | 144 (0x90) | Exported Function | 0x1002a360 | 0x0002a360
`FwMulticastBroadcastResponsesSet` | 145 (0x91) | Exported Function | 0x1002a490 | 0x0002a490
`FwNotificationsEnum` | 146 (0x92) | Exported Function | 0x1002a5c0 | 0x0002a5c0
`FwNotificationsSet` | 147 (0x93) | Exported Function | 0x1002a6f0 | 0x0002a6f0
`FWOpenPolicyStore` | 86 (0x56) | Exported Function | 0x10014e40 | 0x00014e40
`FwOpModesEnum` | 148 (0x94) | Exported Function | 0x1002a820 | 0x0002a820
`FwOpModesSet` | 149 (0x95) | Exported Function | 0x1002a950 | 0x0002a950
`FWVerifyCryptoSetQuery` | 115 (0x73) | Exported Function | 0x10043f50 | 0x00043f50
`FwPortOpeningsAdd` | 150 (0x96) | Exported Function | 0x1002aa70 | 0x0002aa70
`FwProfileTypeCurrentGet` | 152 (0x98) | Exported Function | 0x1002acf0 | 0x0002acf0
`FwProfileTypeGet` | 153 (0x99) | Exported Function | 0x1002ad70 | 0x0002ad70
`FWQueryAuthenticationSets` | 87 (0x57) | Exported Function | 0x100422b0 | 0x000422b0
`FWQueryConnectionSecurityRules` | 88 (0x58) | Exported Function | 0x100423c0 | 0x000423c0
`FWQueryCryptoSets` | 89 (0x59) | Exported Function | 0x100424d0 | 0x000424d0
`FWQueryFirewallRules` | 90 (0x5a) | Exported Function | 0x10015c90 | 0x00015c90
`FWQueryIsolationType` | 91 (0x5b) | Exported Function | 0x100425e0 | 0x000425e0
`FWQueryMainModeRules` | 92 (0x5c) | Exported Function | 0x10042720 | 0x00042720
`FWRegisterProduct` | 93 (0x5d) | Exported Function | 0x10042820 | 0x00042820
`FWResetIndicatedPortInUse` | 94 (0x5e) | Exported Function | 0x10015f40 | 0x00015f40
`FwPortOpeningsDelete` | 151 (0x97) | Exported Function | 0x1002abc0 | 0x0002abc0
`FwIsRemoteManagementEnabled` | 141 (0x8d) | Exported Function | 0x10011a80 | 0x00011a80
`FWVerifyFirewallRule` | 116 (0x74) | Exported Function | 0x10043fa0 | 0x00043fa0
`FWVerifyMainModeRule` | 118 (0x76) | Exported Function | 0x10044000 | 0x00044000
`NetworkIsolationDeleteAllInterfacesContainer` | 183 (0xb7) | Exported Function | 0x10044e30 | 0x00044e30
`NetworkIsolationDeleteAllowEnterpriseIdRule` | 184 (0xb8) | Exported Function | 0x10044fc0 | 0x00044fc0
`NetworkIsolationDeleteAppContainer` | 185 (0xb9) | Exported Function | 0x10015880 | 0x00015880
`NetworkIsolationDeleteAppContainerLoopbackRules` | 186 (0xba) | Exported Function | 0x100450b0 | 0x000450b0
`NetworkIsolationDeleteContainer` | 187 (0xbb) | Exported Function | 0x10045330 | 0x00045330
`NetworkIsolationDeleteInterfaceContainer` | 188 (0xbc) | Exported Function | 0x100455f0 | 0x000455f0
`NetworkIsolationDeleteUserAppContainers` | 189 (0xbd) | Exported Function | 0x10045700 | 0x00045700
`NetworkIsolationDiagnoseConnectFailure` | 190 (0xbe) | Exported Function | 0x10012f50 | 0x00012f50
`NetworkIsolationDiagnoseConnectFailureAndGetInfo` | 191 (0xbf) | Exported Function | 0x10045910 | 0x00045910
`NetworkIsolationDiagnoseListen` | 192 (0xc0) | Exported Function | 0x10045a50 | 0x00045a50
`NetworkIsolationDiagnoseSocketCreation` | 193 (0xc1) | Exported Function | 0x10045b50 | 0x00045b50
`NetworkIsolationEnumAppContainers` | 194 (0xc2) | Exported Function | 0x10045c40 | 0x00045c40
`NetworkIsolationEnumerateAppContainerRules` | 195 (0xc3) | Exported Function | 0x10045dc0 | 0x00045dc0
`NetworkIsolationFreeAppContainers` | 7 (0x7) | Exported Function | 0x10012f40 | 0x00012f40
`NetworkIsolationGetAppContainer` | 196 (0xc4) | Exported Function | 0x10045e70 | 0x00045e70
`NetworkIsolationGetAppContainerConfig` | 197 (0xc5) | Exported Function | 0x100157a0 | 0x000157a0
`NetworkIsolationGetEnterpriseId` | 198 (0xc6) | Exported Function | 0x10045fc0 | 0x00045fc0
`NetworkIsolationGetEnterpriseIdAsync` | 199 (0xc7) | Exported Function | 0x10046030 | 0x00046030
`NetworkIsolationGetEnterpriseIdClose` | 200 (0xc8) | Exported Function | 0x100463d0 | 0x000463d0
`NetworkIsolationRegisterForAppContainerChanges` | 201 (0xc9) | Exported Function | 0x100465a0 | 0x000465a0
`NetworkIsolationSetAppContainerConfig` | 202 (0xca) | Exported Function | 0x10046950 | 0x00046950
`NetworkIsolationCreateInterfaceContainer` | 182 (0xb6) | Exported Function | 0x10044c30 | 0x00044c30
`NetworkIsolationCreateContainer` | 181 (0xb5) | Exported Function | 0x10044950 | 0x00044950
`NetworkIsolationCreateAppContainerLoopbackRules` | 180 (0xb4) | Exported Function | 0x100446d0 | 0x000446d0
`NetworkIsolationCreateAppContainer` | 179 (0xb3) | Exported Function | 0x10015a80 | 0x00015a80
`FWVerifyMainModeRuleQuery` | 119 (0x77) | Exported Function | 0x10044050 | 0x00044050
`GetDisabledInterfaces` | 6 (0x6) | Exported Function | 0x10025ae0 | 0x00025ae0
`IcfAddrChangeNotificationCreate` | 159 (0x9f) | Exported Function | 0x10026d50 | 0x00026d50
`IcfChangeNotificationCreate` | 160 (0xa0) | Exported Function | 0x10012ed0 | 0x00012ed0
`IcfChangeNotificationDestroy` | 161 (0xa1) | Exported Function | 0x10026dd0 | 0x00026dd0
`IcfConnect` | 162 (0xa2) | Exported Function | 0x10026e40 | 0x00026e40
`IcfDisconnect` | 163 (0xa3) | Exported Function | 0x10015730 | 0x00015730
`IcfFreeDynamicFwPorts` | 164 (0xa4) | Exported Function | 0x10026e60 | 0x00026e60
`IcfFreeProfile` | 165 (0xa5) | Exported Function | 0x10026ee0 | 0x00026ee0
`IcfFreeTickets` | 166 (0xa6) | Exported Function | 0x100270f0 | 0x000270f0
`FWVerifyFirewallRuleQuery` | 117 (0x75) | Exported Function | 0x10013950 | 0x00013950
`IcfGetCurrentProfileType` | 167 (0xa7) | Exported Function | 0x10027160 | 0x00027160
`IcfGetOperationalMode` | 169 (0xa9) | Exported Function | 0x10027460 | 0x00027460
`IcfGetProfile` | 170 (0xaa) | Exported Function | 0x10027590 | 0x00027590
`IcfGetTickets` | 171 (0xab) | Exported Function | 0x10027840 | 0x00027840
`IcfIsPortAllowed` | 172 (0xac) | Exported Function | 0x1002baa0 | 0x0002baa0
`IcfOpenDynamicFwPortWithoutSocket` | 173 (0xad) | Exported Function | 0x10027a80 | 0x00027a80
`IcfSubNetsGetScope` | 174 (0xae) | Exported Function | 0x10027a90 | 0x00027a90
`IsFirewallInCoExistanceMode` | 175 (0xaf) | Exported Function | 0x10028020 | 0x00028020
`IsPortOrICMPAllowed` | 176 (0xb0) | Exported Function | 0x1002bb50 | 0x0002bb50
`NetworkIsolationAddAllowEnterpriseIdRule` | 177 (0xb1) | Exported Function | 0x10044370 | 0x00044370
`NetworkIsolationCreateAllInterfacesContainer` | 178 (0xb2) | Exported Function | 0x100444d0 | 0x000444d0
`IcfGetDynamicFwPorts` | 168 (0xa8) | Exported Function | 0x100271f0 | 0x000271f0
`FwIsGroupPolicyEnforced` | 140 (0x8c) | Exported Function | 0x100118c0 | 0x000118c0
`FwInterfaceTypesToBstr` | 5 (0x5) | Exported Function | 0x10023b70 | 0x00023b70
`FWIndicateTupleInUse2` | 83 (0x53) | Exported Function | 0x10041e50 | 0x00041e50
`FwCopyAuthSet` | 130 (0x82) | Exported Function | 0x100440b0 | 0x000440b0
`FWCopyConnectionSecurityRule` | 23 (0x17) | Exported Function | 0x1003f9d0 | 0x0003f9d0
`FWCopyCryptoSet` | 24 (0x18) | Exported Function | 0x1003fa20 | 0x0003fa20
`FWCopyFirewallRule` | 25 (0x19) | Exported Function | 0x1003fa70 | 0x0003fa70
`FwCopyMainModeRule` | 131 (0x83) | Exported Function | 0x10044100 | 0x00044100
`FwCopyWFAddressesContents` | 132 (0x84) | Exported Function | 0x10044150 | 0x00044150
`FWDeleteAllAuthenticationSets` | 26 (0x1a) | Exported Function | 0x1003fac0 | 0x0003fac0
`FWDeleteAllConnectionSecurityRules` | 27 (0x1b) | Exported Function | 0x1003fbb0 | 0x0003fbb0
`FWDeleteAllCryptoSets` | 28 (0x1c) | Exported Function | 0x1003fca0 | 0x0003fca0
`FWDeleteAllFirewallRules` | 29 (0x1d) | Exported Function | 0x1003fd90 | 0x0003fd90
`FWDeleteAllMainModeRules` | 30 (0x1e) | Exported Function | 0x1003fe80 | 0x0003fe80
`FWDeleteAuthenticationSet` | 31 (0x1f) | Exported Function | 0x1003ff70 | 0x0003ff70
`FWDeleteConnectionSecurityRule` | 32 (0x20) | Exported Function | 0x10040060 | 0x00040060
`FWDeleteCryptoSet` | 33 (0x21) | Exported Function | 0x10040150 | 0x00040150
`FWDeleteFirewallRule` | 34 (0x22) | Exported Function | 0x10040240 | 0x00040240
`FWDeleteMainModeRule` | 35 (0x23) | Exported Function | 0x10040330 | 0x00040330
`FWDeletePhase1SAs` | 36 (0x24) | Exported Function | 0x10040420 | 0x00040420
`FWDeletePhase2SAs` | 37 (0x25) | Exported Function | 0x10040500 | 0x00040500
`FWDeleteSecurityRealm` | 38 (0x26) | Exported Function | 0x100405e0 | 0x000405e0
`FWDiagGetAppList` | 39 (0x27) | Exported Function | 0x10040600 | 0x00040600
`FwEmptyWFAddresses` | 133 (0x85) | Exported Function | 0x10012f30 | 0x00012f30
`FWCopyAuthenticationSet` | 22 (0x16) | Exported Function | 0x1003f980 | 0x0003f980
`FwConvertIPv6SubNetToRange` | 129 (0x81) | Exported Function | 0x100440a0 | 0x000440a0
`FWClosePolicyStore` | 21 (0x15) | Exported Function | 0x10013f60 | 0x00013f60
`FWChangeTransactionalState` | 20 (0x14) | Exported Function | 0x1003f7e0 | 0x0003f7e0
`DllGetClassObject` | 9 (0x9) | Exported Function | 0x10012ea0 | 0x00012ea0
`DllRegisterServer` | 10 (0xa) | Exported Function | 0x100220e0 | 0x000220e0
`DllUnregisterServer` | 11 (0xb) | Exported Function | 0x10022100 | 0x00022100
`FwActivate` | 120 (0x78) | Exported Function | 0x10027f40 | 0x00027f40
`FWAddAuthenticationSet` | 12 (0xc) | Exported Function | 0x1003ee20 | 0x0003ee20
`FWAddConnectionSecurityRule` | 13 (0xd) | Exported Function | 0x1003efb0 | 0x0003efb0
`FWAddCryptoSet` | 14 (0xe) | Exported Function | 0x1003f130 | 0x0003f130
`FWAddFirewallRule` | 15 (0xf) | Exported Function | 0x1003f280 | 0x0003f280
`FWAddMainModeRule` | 16 (0x10) | Exported Function | 0x1003f4b0 | 0x0003f4b0
`FWAddSecurityRealm` | 17 (0x11) | Exported Function | 0x1003f5e0 | 0x0003f5e0
`FWEnumAdapters` | 40 (0x28) | Exported Function | 0x100406c0 | 0x000406c0
`FwAlloc` | 121 (0x79) | Exported Function | 0x10011e20 | 0x00011e20
`FwAllowedProgramsAdd` | 123 (0x7b) | Exported Function | 0x10029bc0 | 0x00029bc0
`FwAllowedProgramsDelete` | 124 (0x7c) | Exported Function | 0x10029d10 | 0x00029d10
`FwAnalyzeFirewallPolicy` | 125 (0x7d) | Exported Function | 0x100130e0 | 0x000130e0
`FwAnalyzeFirewallPolicyOnProfile` | 126 (0x7e) | Exported Function | 0x10013de0 | 0x00013de0
`FwApiHelperFree` | 127 (0x7f) | Exported Function | 0x10029e40 | 0x00029e40
`FwApiHelperInit` | 128 (0x80) | Exported Function | 0x10029eb0 | 0x00029eb0
`FwBstrToInterfaceTypes` | 1 (0x1) | Exported Function | 0x10023360 | 0x00023360
`FwBstrToPorts` | 2 (0x2) | Exported Function | 0x10023450 | 0x00023450
`FWChangeNotificationCreate` | 18 (0x12) | Exported Function | 0x10012ed0 | 0x00012ed0
`FWChangeNotificationDestroy` | 19 (0x13) | Exported Function | 0x10026dd0 | 0x00026dd0
`FwAllocCheckSize` | 122 (0x7a) | Exported Function | 0x10016250 | 0x00016250
`FWEnumAuthenticationSets` | 41 (0x29) | Exported Function | 0x10040780 | 0x00040780
`FWEnumConnectionSecurityRules` | 42 (0x2a) | Exported Function | 0x10040910 | 0x00040910
`FWEnumCryptoSets` | 43 (0x2b) | Exported Function | 0x10040aa0 | 0x00040aa0
`FWFreeMainModeRulesByHandle` | 68 (0x44) | Exported Function | 0x10041890 | 0x00041890
`FWFreeNetworks` | 69 (0x45) | Exported Function | 0x10012f40 | 0x00012f40
`FWFreePhase1SAs` | 70 (0x46) | Exported Function | 0x10041950 | 0x00041950
`FWFreePhase2SAs` | 71 (0x47) | Exported Function | 0x10041a10 | 0x00041a10
`FwFreePorts` | 136 (0x88) | Exported Function | 0x100441a0 | 0x000441a0
`FWFreeProducts` | 72 (0x48) | Exported Function | 0x10012f40 | 0x00012f40
`FwGetAddressesAsString` | 137 (0x89) | Exported Function | 0x100441d0 | 0x000441d0
`FWGetConfig` | 74 (0x4a) | Exported Function | 0x10013a80 | 0x00013a80
`FWGetConfig2` | 73 (0x49) | Exported Function | 0x100117c0 | 0x000117c0
`FwGetCurrentProfile` | 3 (0x3) | Exported Function | 0x10025a40 | 0x00025a40
`FWFreeMainModeRules` | 67 (0x43) | Exported Function | 0x100417f0 | 0x000417f0
`FWGetGlobalConfig` | 77 (0x4d) | Exported Function | 0x10018300 | 0x00018300
`FWGetGlobalConfig3` | 76 (0x4c) | Exported Function | 0x10041ab0 | 0x00041ab0
`FWGetIndicatedPortInUse` | 78 (0x4e) | Exported Function | 0x10016000 | 0x00016000
`FwGetVersionField` | 4 (0x4) | Exported Function | 0x10023680 | 0x00023680
`FwIcmpSettingsEnum` | 138 (0x8a) | Exported Function | 0x10029f40 | 0x00029f40
`FwIcmpSettingsSet` | 139 (0x8b) | Exported Function | 0x1002a080 | 0x0002a080
`FWImportPolicy` | 79 (0x4f) | Exported Function | 0x10041bc0 | 0x00041bc0
`FWIndicatePortInUse` | 80 (0x50) | Exported Function | 0x10013ab0 | 0x00013ab0
`FWIndicateProxyForUrl` | 81 (0x51) | Exported Function | 0x10041d20 | 0x00041d20
`FWIndicateProxyResolverRefresh` | 82 (0x52) | Exported Function | 0x10041e40 | 0x00041e40
`FWIndicateTupleInUse` | 84 (0x54) | Exported Function | 0x10041f90 | 0x00041f90
`FWGetGlobalConfig2` | 75 (0x4b) | Exported Function | 0x100181c0 | 0x000181c0
`NetworkIsolationSetupAppContainerBinaries` | 203 (0xcb) | Exported Function | 0x10015d90 | 0x00015d90
`FWFreeMainModeRule` | 66 (0x42) | Exported Function | 0x100417e0 | 0x000417e0
`FWFreeFirewallRulesByHandle` | 64 (0x40) | Exported Function | 0x10041680 | 0x00041680
`FWEnumFirewallRules` | 44 (0x2c) | Exported Function | 0x10011be0 | 0x00011be0
`FWEnumMainModeRules` | 45 (0x2d) | Exported Function | 0x10040c00 | 0x00040c00
`FWEnumNetworks` | 46 (0x2e) | Exported Function | 0x10040d40 | 0x00040d40
`FWEnumPhase1SAs` | 47 (0x2f) | Exported Function | 0x10040e00 | 0x00040e00
`FWEnumPhase2SAs` | 48 (0x30) | Exported Function | 0x10040ef0 | 0x00040ef0
`FWEnumProducts` | 49 (0x31) | Exported Function | 0x10040fe0 | 0x00040fe0
`FWExportPolicy` | 50 (0x32) | Exported Function | 0x100410a0 | 0x000410a0
`FwFree` | 134 (0x86) | Exported Function | 0x10012f40 | 0x00012f40
`FWFreeAdapters` | 51 (0x33) | Exported Function | 0x10012f40 | 0x00012f40
`FwFreeAddresses` | 135 (0x87) | Exported Function | 0x10012f30 | 0x00012f30
`FWFreeFirewallRulesOld` | 65 (0x41) | Exported Function | 0x10041740 | 0x00041740
`FWFreeAuthenticationSet` | 52 (0x34) | Exported Function | 0x10041200 | 0x00041200
`FWFreeAuthenticationSetsByHandle` | 54 (0x36) | Exported Function | 0x100412b0 | 0x000412b0
`FWFreeConnectionSecurityRule` | 55 (0x37) | Exported Function | 0x10041370 | 0x00041370
`FWFreeConnectionSecurityRules` | 56 (0x38) | Exported Function | 0x10041380 | 0x00041380
`FWFreeConnectionSecurityRulesByHandle` | 57 (0x39) | Exported Function | 0x10041420 | 0x00041420
`FWFreeCryptoSet` | 58 (0x3a) | Exported Function | 0x100414e0 | 0x000414e0
`FWFreeCryptoSets` | 59 (0x3b) | Exported Function | 0x100414f0 | 0x000414f0
`FWFreeCryptoSetsByHandle` | 60 (0x3c) | Exported Function | 0x10041590 | 0x00041590
`FWFreeDiagAppList` | 61 (0x3d) | Exported Function | 0x10012f40 | 0x00012f40
`FWFreeFirewallRule` | 62 (0x3e) | Exported Function | 0x10041670 | 0x00041670
`FWFreeFirewallRules` | 63 (0x3f) | Exported Function | 0x100119f0 | 0x000119f0
`FWFreeAuthenticationSets` | 53 (0x35) | Exported Function | 0x10041210 | 0x00041210
`NetworkIsolationUnregisterForAppContainerChanges` | 204 (0xcc) | Exported Function | 0x10046a70 | 0x00046a70


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FirewallAPI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/d4dd047f970cd6bde2a789c69e0e87ef700c9a11c89763413e7013821fee84ed/detection/





MIT License. Copyright (c) 2020 Strontic.


