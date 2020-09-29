---
title: wlanapi.dll | Windows WLAN AutoConfig Client Side API DLL
excerpt: What is wlanapi.dll?
---

# wlanapi.dll 

* File Path: `C:\Windows\SysWOW64\wlanapi.dll`
* Description: Windows WLAN AutoConfig Client Side API DLL

## Hashes

Type | Hash
-- | --
MD5 | `B75D82AA6853853CEAB9EDAC5D8A595D`
SHA1 | `BE4F299176079328229DD01CEB1291E5F0EECD06`
SHA256 | `F240D09A4AB90EE4A6A2D0500B09CE915659283B5D311BE7F1422377AF06DDA9`
SHA384 | `7C6A04E521B343C30084B05B2B0324DF64BDF22CE6FEA8E9B8F1416DB4A56E8C5E4835AAA7951F3915453D5015776804`
SHA512 | `8A0D524B4FA2B0121915D6D0D9A0D9422EADA08FDB56F064A2754E48A5F95E4EBF5311730757C86733E51EF4E64D2B3F53CCB1C54D42B51743DB2817AC1C1362`
SSDEEP | `6144:gwvX/0Fua0qey68WCWEN0ISo6axOnZs1x9a4VFgrVx4Fqs3IUsmPPzn:d0t0qei0ISo6axOnca4VFgrVNmIUs0r`
IMP | `0FDEBC706D206E887BDEAFCA72BD6DA9`
PESHA1 | `732A41994C6BDDBD87BB81B6F2E8DD87D8212E9D`
PE256 | `B212D160510C0B806190B674B30F18F341181FC85BA33E404C421107B4DA207F`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`QueryNetconStatus` | 1 (0x1) | Exported Function | 0x1000bd30 | 0x0000bd30
`WlanInitPlapParams` | 164 (0xa4) | Exported Function | 0x1001e5c0 | 0x0001e5c0
`WlanInternalCancelFTMRequest` | 165 (0xa5) | Exported Function | 0x1000fd40 | 0x0000fd40
`WlanInternalGetNetworkBssListWithFTMData` | 166 (0xa6) | Exported Function | 0x1000fef0 | 0x0000fef0
`WlanInternalNonDisruptiveScan` | 167 (0xa7) | Exported Function | 0x1001e5e0 | 0x0001e5e0
`WlanInternalNonDisruptiveScanEx` | 168 (0xa8) | Exported Function | 0x100100b0 | 0x000100b0
`WlanInternalRequestFTM` | 169 (0xa9) | Exported Function | 0x10010370 | 0x00010370
`WlanInternalScan` | 170 (0xaa) | Exported Function | 0x1001e600 | 0x0001e600
`WlanIsActiveConsoleUser` | 171 (0xab) | Exported Function | 0x1002a040 | 0x0002a040
`WlanIsNetworkSuppressed` | 172 (0xac) | Exported Function | 0x1001e710 | 0x0001e710
`WlanIsUIRequestPending` | 173 (0xad) | Exported Function | 0x1001e870 | 0x0001e870
`WlanLowPrivCloseHandle` | 174 (0xae) | Exported Function | 0x100224f0 | 0x000224f0
`WlanLowPrivEnumInterfaces` | 175 (0xaf) | Exported Function | 0x10022690 | 0x00022690
`WlanLowPrivFreeMemory` | 176 (0xb0) | Exported Function | 0x1000baf0 | 0x0000baf0
`WlanIhvControl` | 163 (0xa3) | Exported Function | 0x10017ff0 | 0x00017ff0
`WlanLowPrivNotifyVsIeProviderInt` | 177 (0xb1) | Exported Function | 0x10022860 | 0x00022860
`WlanLowPrivQueryInterface` | 179 (0xb3) | Exported Function | 0x10022b40 | 0x00022b40
`WlanLowPrivSetInterface` | 180 (0xb4) | Exported Function | 0x10022d20 | 0x00022d20
`WlanNotifyVsIeProviderExInt` | 181 (0xb5) | Exported Function | 0x100218b0 | 0x000218b0
`WlanNotifyVsIeProviderInt` | 182 (0xb6) | Exported Function | 0x100218e0 | 0x000218e0
`WlanOpenHandle` | 183 (0xb7) | Exported Function | 0x1000a5a0 | 0x0000a5a0
`WlanParseProfileXmlBasicSettings` | 184 (0xb8) | Exported Function | 0x10023520 | 0x00023520
`WlanPrivateCanDeleteProfile` | 185 (0xb9) | Exported Function | 0x1000e770 | 0x0000e770
`WlanPrivateClearAnqpCache` | 186 (0xba) | Exported Function | 0x1001e970 | 0x0001e970
`WlanPrivateDeleteProfile` | 187 (0xbb) | Exported Function | 0x1000e970 | 0x0000e970
`WlanPrivateEnableAnqpOsuRegistration` | 188 (0xbc) | Exported Function | 0x1001ea70 | 0x0001ea70
`WlanPrivateGetAnqpCacheResponse` | 189 (0xbd) | Exported Function | 0x1001eb70 | 0x0001eb70
`WlanPrivateGetAnqpOSUProviderList` | 190 (0xbe) | Exported Function | 0x1001ec80 | 0x0001ec80
`WlanPrivateGetAnqpOsuRegistrationStatus` | 191 (0xbf) | Exported Function | 0x1001edf0 | 0x0001edf0
`WlanLowPrivOpenHandle` | 178 (0xb2) | Exported Function | 0x10022890 | 0x00022890
`WlanPrivateGetAvailableNetworkList` | 192 (0xc0) | Exported Function | 0x1000c130 | 0x0000c130
`WlanHostedNetworkStopUsing` | 162 (0xa2) | Exported Function | 0x10017f50 | 0x00017f50
`WlanHostedNetworkSetWCNSettings` | 160 (0xa0) | Exported Function | 0x1001e4e0 | 0x0001e4e0
`WlanGetInterfaceCapability` | 132 (0x84) | Exported Function | 0x10016500 | 0x00016500
`WlanGetMFPNegotiated` | 133 (0x85) | Exported Function | 0x1001daf0 | 0x0001daf0
`WlanGetNetworkBssList` | 134 (0x86) | Exported Function | 0x10016710 | 0x00016710
`WlanGetProfile` | 135 (0x87) | Exported Function | 0x1000c570 | 0x0000c570
`WlanGetProfileCustomUserData` | 136 (0x88) | Exported Function | 0x10016930 | 0x00016930
`WlanGetProfileEapUserDataInfo` | 137 (0x89) | Exported Function | 0x1001dbd0 | 0x0001dbd0
`WlanGetProfileIndex` | 138 (0x8a) | Exported Function | 0x1000c000 | 0x0000c000
`WlanGetProfileKeyInfo` | 139 (0x8b) | Exported Function | 0x1001dcc0 | 0x0001dcc0
`WlanGetProfileList` | 140 (0x8c) | Exported Function | 0x10016b60 | 0x00016b60
`WlanGetProfileMetadata` | 141 (0x8d) | Exported Function | 0x1000bec0 | 0x0000bec0
`WlanGetProfileMetadataWithProfileGuid` | 142 (0x8e) | Exported Function | 0x1001ddc0 | 0x0001ddc0
`WlanGetProfileSsidList` | 143 (0x8f) | Exported Function | 0x10023330 | 0x00023330
`WlanGetRadioInformation` | 144 (0x90) | Exported Function | 0x1001e0b0 | 0x0001e0b0
`WlanHostedNetworkStartUsing` | 161 (0xa1) | Exported Function | 0x10017ec0 | 0x00017ec0
`WlanGetSecuritySettings` | 145 (0x91) | Exported Function | 0x10016d60 | 0x00016d60
`WlanGetSupportedDeviceServices` | 147 (0x93) | Exported Function | 0x10016f80 | 0x00016f80
`WlanHostedNetworkForceStart` | 148 (0x94) | Exported Function | 0x10017190 | 0x00017190
`WlanHostedNetworkForceStop` | 149 (0x95) | Exported Function | 0x10017220 | 0x00017220
`WlanHostedNetworkFreeWCNSettings` | 150 (0x96) | Exported Function | 0x1001e290 | 0x0001e290
`WlanHostedNetworkHlpQueryEverUsed` | 151 (0x97) | Exported Function | 0x1001e330 | 0x0001e330
`WlanHostedNetworkInitSettings` | 152 (0x98) | Exported Function | 0x100172b0 | 0x000172b0
`WlanHostedNetworkQueryProperty` | 153 (0x99) | Exported Function | 0x10017340 | 0x00017340
`WlanHostedNetworkQuerySecondaryKey` | 154 (0x9a) | Exported Function | 0x10017550 | 0x00017550
`WlanHostedNetworkQueryStatus` | 155 (0x9b) | Exported Function | 0x100177e0 | 0x000177e0
`WlanHostedNetworkQueryWCNSettings` | 156 (0x9c) | Exported Function | 0x1001e400 | 0x0001e400
`WlanHostedNetworkRefreshSecuritySettings` | 157 (0x9d) | Exported Function | 0x100179d0 | 0x000179d0
`WlanHostedNetworkSetProperty` | 158 (0x9e) | Exported Function | 0x10017a60 | 0x00017a60
`WlanHostedNetworkSetSecondaryKey` | 159 (0x9f) | Exported Function | 0x10017c90 | 0x00017c90
`WlanGetStoredRadioState` | 146 (0x92) | Exported Function | 0x1001e1a0 | 0x0001e1a0
`WlanPrivateParseAnqpRawData` | 193 (0xc1) | Exported Function | 0x1001ef00 | 0x0001ef00
`WlanPrivateQuery11adPairedConfig` | 194 (0xc2) | Exported Function | 0x10018250 | 0x00018250
`WlanPrivateQueryInterface` | 195 (0xc3) | Exported Function | 0x10018400 | 0x00018400
`WlanSetProfilePosition` | 229 (0xe5) | Exported Function | 0x1001a3f0 | 0x0001a3f0
`WlanSetProtectedScenario` | 230 (0xe6) | Exported Function | 0x100106f0 | 0x000106f0
`WlanSetPsdIEDataList` | 231 (0xe7) | Exported Function | 0x1001a600 | 0x0001a600
`WlanSetSecuritySettings` | 232 (0xe8) | Exported Function | 0x1001a7a0 | 0x0001a7a0
`WlanSetUIForwardingNetworkList` | 233 (0xe9) | Exported Function | 0x1001f790 | 0x0001f790
`WlanSignalValueToBar` | 234 (0xea) | Exported Function | 0x1002a140 | 0x0002a140
`WlanSignalValueToBarEx` | 235 (0xeb) | Exported Function | 0x1002a160 | 0x0002a160
`WlanSsidToDisplayName` | 236 (0xec) | Exported Function | 0x1002a190 | 0x0002a190
`WlanStartAP` | 237 (0xed) | Exported Function | 0x1001f880 | 0x0001f880
`WlanStartMovementDetector` | 238 (0xee) | Exported Function | 0x10010710 | 0x00010710
`WlanStopAP` | 239 (0xef) | Exported Function | 0x1001fb30 | 0x0001fb30
`WlanStopMovementDetector` | 240 (0xf0) | Exported Function | 0x10010730 | 0x00010730
`WlanStoreRadioStateOnEnteringAirPlaneMode` | 241 (0xf1) | Exported Function | 0x1001fc00 | 0x0001fc00
`WlanSetProfileMetadata` | 228 (0xe4) | Exported Function | 0x1001f690 | 0x0001f690
`WlanStringToSsid` | 242 (0xf2) | Exported Function | 0x1002a330 | 0x0002a330
`WlanTryUpgradeCurrentConnectionAuthCipher` | 244 (0xf4) | Exported Function | 0x1001fcf0 | 0x0001fcf0
`WlanUpdateBasicProfileSecurity` | 245 (0xf5) | Exported Function | 0x1001a990 | 0x0001a990
`WlanUpdateProfileWithAuthCipher` | 246 (0xf6) | Exported Function | 0x100207f0 | 0x000207f0
`WlanUtf8SsidToDisplayName` | 247 (0xf7) | Exported Function | 0x1002a4a0 | 0x0002a4a0
`WlanVerifyProfileIpConfiguration` | 249 (0xf9) | Exported Function | 0x10010e40 | 0x00010e40
`WlanVMgrQueryCurrentScenariosInt` | 248 (0xf8) | Exported Function | 0x10021910 | 0x00021910
`WlanWcmDisconnect` | 250 (0xfa) | Exported Function | 0x10020a00 | 0x00020a00
`WlanWcmGetInterface` | 251 (0xfb) | Exported Function | 0x10020ae0 | 0x00020ae0
`WlanWcmGetProfileList` | 252 (0xfc) | Exported Function | 0x10020bd0 | 0x00020bd0
`WlanWcmSetInterface` | 253 (0xfd) | Exported Function | 0x10020d30 | 0x00020d30
`WlanWcmSetProfile` | 254 (0xfe) | Exported Function | 0x10020e20 | 0x00020e20
`WlanWfdGetPeerInfo` | 256 (0x100) | Exported Function | 0x10021090 | 0x00021090
`WlanWfdGOSetWCNSettings` | 255 (0xff) | Exported Function | 0x10020fb0 | 0x00020fb0
`WlanStringToUtf8Ssid` | 243 (0xf3) | Exported Function | 0x1002a3e0 | 0x0002a3e0
`WlanSetProfileListForOffload` | 227 (0xe3) | Exported Function | 0x1001a210 | 0x0001a210
`WlanSetProfileList` | 226 (0xe2) | Exported Function | 0x1001a010 | 0x0001a010
`WlanSetProfileEapXmlUserData` | 225 (0xe1) | Exported Function | 0x10019b00 | 0x00019b00
`WlanPrivateRefreshAnqpCache` | 196 (0xc4) | Exported Function | 0x1001f010 | 0x0001f010
`WlanPrivateSetInterface` | 197 (0xc5) | Exported Function | 0x100185c0 | 0x000185c0
`WlanPrivateSetProfile` | 198 (0xc6) | Exported Function | 0x1000eb70 | 0x0000eb70
`WlanProfileIpConfigurationGetAddressList` | 199 (0xc7) | Exported Function | 0x10010db0 | 0x00010db0
`WlanProfileIpConfigurationGetDnsServerList` | 200 (0xc8) | Exported Function | 0x10010de0 | 0x00010de0
`WlanProfileIpConfigurationGetGatewayList` | 201 (0xc9) | Exported Function | 0x10010e10 | 0x00010e10
`WlanQueryAutoConfigParameter` | 202 (0xca) | Exported Function | 0x10018760 | 0x00018760
`WlanQueryCreateAllUserProfileRestricted` | 203 (0xcb) | Exported Function | 0x100239f0 | 0x000239f0
`WlanQueryInterface` | 204 (0xcc) | Exported Function | 0x1000c2f0 | 0x0000c2f0
`WlanQueryPlapCredentials` | 205 (0xcd) | Exported Function | 0x1001f120 | 0x0001f120
`WlanQueryPreConnectInput` | 206 (0xce) | Exported Function | 0x1001f220 | 0x0001f220
`WlanQueryVirtualInterfaceType` | 207 (0xcf) | Exported Function | 0x1000bb40 | 0x0000bb40
`WlanReasonCodeToString` | 208 (0xd0) | Exported Function | 0x10018960 | 0x00018960
`WlanRefreshConnections` | 209 (0xd1) | Exported Function | 0x1001f3c0 | 0x0001f3c0
`WlanRegisterDeviceServiceNotification` | 210 (0xd2) | Exported Function | 0x1000eda0 | 0x0000eda0
`WlanRegisterNotification` | 211 (0xd3) | Exported Function | 0x1000bc40 | 0x0000bc40
`WlanRegisterVirtualStationNotification` | 212 (0xd4) | Exported Function | 0x100189d0 | 0x000189d0
`WlanRemoveUIForwardingNetworkList` | 213 (0xd5) | Exported Function | 0x1001f4d0 | 0x0001f4d0
`WlanRenameProfile` | 214 (0xd6) | Exported Function | 0x10018bb0 | 0x00018bb0
`WlanSaveTemporaryProfile` | 215 (0xd7) | Exported Function | 0x10018db0 | 0x00018db0
`WlanScan` | 216 (0xd8) | Exported Function | 0x10018fe0 | 0x00018fe0
`WlanSendUIResponse` | 217 (0xd9) | Exported Function | 0x1001f5b0 | 0x0001f5b0
`WlanSetAllUserProfileRestricted` | 218 (0xda) | Exported Function | 0x10023ca0 | 0x00023ca0
`WlanSetAutoConfigParameter` | 219 (0xdb) | Exported Function | 0x100191d0 | 0x000191d0
`WlanSetFilterList` | 220 (0xdc) | Exported Function | 0x10019350 | 0x00019350
`WlanSetInterface` | 221 (0xdd) | Exported Function | 0x100194e0 | 0x000194e0
`WlanSetProfile` | 222 (0xde) | Exported Function | 0x10019680 | 0x00019680
`WlanSetProfileCustomUserData` | 223 (0xdf) | Exported Function | 0x100196b0 | 0x000196b0
`WlanSetProfileEapUserData` | 224 (0xe0) | Exported Function | 0x100198c0 | 0x000198c0
`WlanGetFilterList` | 131 (0x83) | Exported Function | 0x10016350 | 0x00016350
`WlanGetAvailableNetworkList2` | 129 (0x81) | Exported Function | 0x100161f0 | 0x000161f0
`WlanGetAvailableNetworkList` | 130 (0x82) | Exported Function | 0x100162a0 | 0x000162a0
`WlanGenerateProfileXmlBasicSettings` | 128 (0x80) | Exported Function | 0x10023040 | 0x00023040
`WFDGetVisibleDevicesInt` | 35 (0x23) | Exported Function | 0x10021480 | 0x00021480
`WFDIsInterfaceWiFiDirect` | 36 (0x24) | Exported Function | 0x1001bcd0 | 0x0001bcd0
`WFDIsWiFiDirectRunningOnWiFiAdapter` | 37 (0x25) | Exported Function | 0x1001bdd0 | 0x0001bdd0
`WFDLowPrivCancelOpenSessionInt` | 38 (0x26) | Exported Function | 0x100220e0 | 0x000220e0
`WFDLowPrivCloseHandleInt` | 39 (0x27) | Exported Function | 0x10022100 | 0x00022100
`WFDLowPrivCloseLegacySessionInt` | 40 (0x28) | Exported Function | 0x10022120 | 0x00022120
`WFDLowPrivCloseSessionInt` | 41 (0x29) | Exported Function | 0x10022140 | 0x00022140
`WFDLowPrivConfigureFirewallForSessionInt` | 42 (0x2a) | Exported Function | 0x10022160 | 0x00022160
`WFDLowPrivDeclineDeviceApiConnectionRequestInt` | 43 (0x2b) | Exported Function | 0x10022180 | 0x00022180
`WFDLowPrivGetPendingGroupRequestDetailsInt` | 44 (0x2c) | Exported Function | 0x100221a0 | 0x000221a0
`WFDLowPrivGetSessionEndpointPairsInt` | 45 (0x2d) | Exported Function | 0x100221c0 | 0x000221c0
`WFDLowPrivIsWfdSupportedInt` | 46 (0x2e) | Exported Function | 0x100221e0 | 0x000221e0
`WFDLowPrivOpenHandleInt` | 47 (0x2f) | Exported Function | 0x10022200 | 0x00022200
`WFDGetVisibleDevicesExInt` | 34 (0x22) | Exported Function | 0x10021460 | 0x00021460
`WFDLowPrivOpenLegacySessionInt` | 48 (0x30) | Exported Function | 0x10022220 | 0x00022220
`WFDLowPrivQueryPropertyInt` | 50 (0x32) | Exported Function | 0x10022280 | 0x00022280
`WFDLowPrivRegisterNotificationInt` | 51 (0x33) | Exported Function | 0x100222a0 | 0x000222a0
`WFDLowPrivRegisterVMgrCallerInt` | 52 (0x34) | Exported Function | 0x100222d0 | 0x000222d0
`WFDLowPrivSetPropertyInt` | 53 (0x35) | Exported Function | 0x100222f0 | 0x000222f0
`WFDLowPrivStartDeviceApiConnectionRequestListenerInt` | 54 (0x36) | Exported Function | 0x10022310 | 0x00022310
`WFDLowPrivStartUsingGroupInt` | 55 (0x37) | Exported Function | 0x10022330 | 0x00022330
`WFDLowPrivStopDeviceApiConnectionRequestListenerInt` | 56 (0x38) | Exported Function | 0x10022350 | 0x00022350
`WFDLowPrivStopUsingGroupInt` | 57 (0x39) | Exported Function | 0x10022370 | 0x00022370
`WFDLowPrivUnregisterVMgrCallerInt` | 58 (0x3a) | Exported Function | 0x10022390 | 0x00022390
`WFDOpenHandle` | 59 (0x3b) | Exported Function | 0x1000b2c0 | 0x0000b2c0
`WFDOpenHandleInt` | 60 (0x3c) | Exported Function | 0x1000b2c0 | 0x0000b2c0
`WFDOpenLegacySession` | 61 (0x3d) | Exported Function | 0x1001abf0 | 0x0001abf0
`WFDOpenLegacySessionInt` | 62 (0x3e) | Exported Function | 0x100214a0 | 0x000214a0
`WFDLowPrivOpenSessionByDafObjectIdInt` | 49 (0x31) | Exported Function | 0x10022240 | 0x00022240
`WFDGetSessionEndpointPairsInt` | 33 (0x21) | Exported Function | 0x10021440 | 0x00021440
`WFDGetProfileKeyInfoInt` | 32 (0x20) | Exported Function | 0x10021410 | 0x00021410
`WFDGetPrimaryAdapterStateInt` | 31 (0x1f) | Exported Function | 0x100213f0 | 0x000213f0
`QueryNetconVirtualCharacteristic` | 2 (0x2) | Exported Function | 0x1001b4f0 | 0x0001b4f0
`WFDAbortSessionInt` | 3 (0x3) | Exported Function | 0x100211a0 | 0x000211a0
`WFDAcceptConnectRequestAndOpenSessionInt` | 4 (0x4) | Exported Function | 0x100107b0 | 0x000107b0
`WFDAcceptGroupRequestAndOpenSessionInt` | 5 (0x5) | Exported Function | 0x100211c0 | 0x000211c0
`WFDCancelConnectorPairWithOOB` | 6 (0x6) | Exported Function | 0x10021930 | 0x00021930
`WFDCancelListenerPairWithOOB` | 7 (0x7) | Exported Function | 0x1001b5e0 | 0x0001b5e0
`WFDCancelOpenSession` | 8 (0x8) | Exported Function | 0x1001ab90 | 0x0001ab90
`WFDCancelOpenSessionInt` | 9 (0x9) | Exported Function | 0x1001ab90 | 0x0001ab90
`WFDCloseHandle` | 10 (0xa) | Exported Function | 0x1001abb0 | 0x0001abb0
`WFDCloseHandleInt` | 11 (0xb) | Exported Function | 0x1001abb0 | 0x0001abb0
`WFDCloseLegacySessionInt` | 12 (0xc) | Exported Function | 0x10021200 | 0x00021200
`WFDCloseOOBPairingSession` | 13 (0xd) | Exported Function | 0x1001b840 | 0x0001b840
`WFDCloseSession` | 14 (0xe) | Exported Function | 0x1001abd0 | 0x0001abd0
`WFDCloseSessionInt` | 15 (0xf) | Exported Function | 0x1001abd0 | 0x0001abd0
`WFDConfigureFirewallForSessionInt` | 16 (0x10) | Exported Function | 0x10021220 | 0x00021220
`WFDCreateDHPrivatePublicKeyPairInt` | 17 (0x11) | Exported Function | 0x10021240 | 0x00021240
`WFDDeclineConnectRequestInt` | 18 (0x12) | Exported Function | 0x10021270 | 0x00021270
`WFDDeclineGroupRequestInt` | 19 (0x13) | Exported Function | 0x10021290 | 0x00021290
`WFDDiscoverDeviceServiceInformationInt` | 20 (0x14) | Exported Function | 0x100212b0 | 0x000212b0
`WFDDiscoverDevicesExInt` | 21 (0x15) | Exported Function | 0x100212e0 | 0x000212e0
`WFDDiscoverDevicesInt` | 22 (0x16) | Exported Function | 0x10021300 | 0x00021300
`WFDFlushVisibleDeviceListInt` | 23 (0x17) | Exported Function | 0x10021320 | 0x00021320
`WFDForceDisconnectInt` | 24 (0x18) | Exported Function | 0x10021340 | 0x00021340
`WFDForceDisconnectLegacyPeerInt` | 25 (0x19) | Exported Function | 0x10021360 | 0x00021360
`WFDFreeMemoryInt` | 26 (0x1a) | Exported Function | 0x1000baf0 | 0x0000baf0
`WFDGetDefaultGroupProfileInt` | 27 (0x1b) | Exported Function | 0x10021380 | 0x00021380
`WFDGetDeviceDescriptorForPendingRequestInt` | 28 (0x1c) | Exported Function | 0x100213a0 | 0x000213a0
`WFDGetNFCCarrierConfigBlobInt` | 29 (0x1d) | Exported Function | 0x100213c0 | 0x000213c0
`WFDGetOOBBlob` | 30 (0x1e) | Exported Function | 0x1001ba20 | 0x0001ba20
`WFDPairCancelByDeviceAddressInt` | 63 (0x3f) | Exported Function | 0x100214c0 | 0x000214c0
`WlanWfdStartGO` | 257 (0x101) | Exported Function | 0x10021190 | 0x00021190
`WFDPairCancelInt` | 64 (0x40) | Exported Function | 0x100214e0 | 0x000214e0
`WFDPairEnumerateCeremoniesInt` | 66 (0x42) | Exported Function | 0x100107e0 | 0x000107e0
`WFDSvcLowPrivGetProvisioningInfoInt` | 100 (0x64) | Exported Function | 0x10022450 | 0x00022450
`WFDSvcLowPrivGetSessionEndpointPairsInt` | 101 (0x65) | Exported Function | 0x10022480 | 0x00022480
`WFDSvcLowPrivOpenAdvertiserSessionInt` | 102 (0x66) | Exported Function | 0x10010810 | 0x00010810
`WFDSvcLowPrivOpenSeekerSessionInt` | 103 (0x67) | Exported Function | 0x10010840 | 0x00010840
`WFDSvcLowPrivPublishServiceInt` | 104 (0x68) | Exported Function | 0x100224a0 | 0x000224a0
`WFDSvcLowPrivUnpublishServiceInt` | 105 (0x69) | Exported Function | 0x100224d0 | 0x000224d0
`WFDUnregisterVMgrCallerInt` | 106 (0x6a) | Exported Function | 0x10021830 | 0x00021830
`WFDUpdateDeviceVisibility` | 107 (0x6b) | Exported Function | 0x1001ac40 | 0x0001ac40
`WiFiDisplayResetSinkStateInt` | 108 (0x6c) | Exported Function | 0x10021850 | 0x00021850
`WiFiDisplaySetSinkClientHandleInt` | 109 (0x6d) | Exported Function | 0x10021870 | 0x00021870
`WiFiDisplaySetSinkStateInt` | 110 (0x6e) | Exported Function | 0x10021890 | 0x00021890
`WlanAllocateMemory` | 111 (0x6f) | Exported Function | 0x10015380 | 0x00015380
`WlanAllocateProfileIpConfiguration` | 112 (0x70) | Exported Function | 0x10010d20 | 0x00010d20
`WFDSvcLowPrivConnectSessionInt` | 99 (0x63) | Exported Function | 0x10022430 | 0x00022430
`WlanCancelPlap` | 113 (0x71) | Exported Function | 0x1001c530 | 0x0001c530
`WlanConnect` | 115 (0x73) | Exported Function | 0x10015690 | 0x00015690
`WlanConnectEx` | 116 (0x74) | Exported Function | 0x100156f0 | 0x000156f0
`WlanConnectWithInput` | 117 (0x75) | Exported Function | 0x1001c610 | 0x0001c610
`WlanDeinitPlapParams` | 118 (0x76) | Exported Function | 0x1001c7b0 | 0x0001c7b0
`WlanDeleteProfile` | 119 (0x77) | Exported Function | 0x10015750 | 0x00015750
`WlanDeviceServiceCommand` | 120 (0x78) | Exported Function | 0x10015780 | 0x00015780
`WlanDisconnect` | 121 (0x79) | Exported Function | 0x10015a00 | 0x00015a00
`WlanDoesBssMatchSecurity` | 123 (0x7b) | Exported Function | 0x1001d810 | 0x0001d810
`WlanDoPlap` | 122 (0x7a) | Exported Function | 0x1001c7c0 | 0x0001c7c0
`WlanEnumAllInterfaces` | 124 (0x7c) | Exported Function | 0x1001d9c0 | 0x0001d9c0
`WlanEnumInterfaces` | 125 (0x7d) | Exported Function | 0x1000c7e0 | 0x0000c7e0
`WlanExtractPsdIEDataList` | 126 (0x7e) | Exported Function | 0x10015be0 | 0x00015be0
`WlanFreeMemory` | 127 (0x7f) | Exported Function | 0x1000baf0 | 0x0000baf0
`WlanCloseHandle` | 114 (0x72) | Exported Function | 0x1000cdf0 | 0x0000cdf0
`WFDSvcLowPrivConfigureSessionInt` | 98 (0x62) | Exported Function | 0x10022410 | 0x00022410
`WFDSvcLowPrivCloseSessionInt` | 97 (0x61) | Exported Function | 0x100223f0 | 0x000223f0
`WFDSvcLowPrivCancelSessionInt` | 96 (0x60) | Exported Function | 0x100223d0 | 0x000223d0
`WFDPairSelectCeremonyInt` | 67 (0x43) | Exported Function | 0x10021520 | 0x00021520
`WFDPairWithDeviceAndOpenSessionExInt` | 68 (0x44) | Exported Function | 0x10021540 | 0x00021540
`WFDPairWithDeviceAndOpenSessionInt` | 69 (0x45) | Exported Function | 0x10021570 | 0x00021570
`WFDParseOOBBlob` | 70 (0x46) | Exported Function | 0x1001bec0 | 0x0001bec0
`WFDParseOOBBlobTypeAndGetPayloadInt` | 71 (0x47) | Exported Function | 0x1001bf70 | 0x0001bf70
`WFDParseProfileXmlInt` | 72 (0x48) | Exported Function | 0x100215a0 | 0x000215a0
`WFDParseWfaNfcCarrierConfigBlobInt` | 73 (0x49) | Exported Function | 0x100215c0 | 0x000215c0
`WFDQueryPropertyInt` | 74 (0x4a) | Exported Function | 0x100215e0 | 0x000215e0
`WFDRegisterNotificationInt` | 75 (0x4b) | Exported Function | 0x10021600 | 0x00021600
`WFDRegisterVMgrCallerInt` | 76 (0x4c) | Exported Function | 0x10021630 | 0x00021630
`WFDResetSelectedWfdMgrInt` | 77 (0x4d) | Exported Function | 0x10021650 | 0x00021650
`WFDSetAdditionalIEsInt` | 78 (0x4e) | Exported Function | 0x10021670 | 0x00021670
`WFDSetPropertyInt` | 79 (0x4f) | Exported Function | 0x10021680 | 0x00021680
`WFDSetSecondaryDeviceTypeListInt` | 80 (0x50) | Exported Function | 0x100216a0 | 0x000216a0
`WFDSetSelectedWfdMgrInt` | 81 (0x51) | Exported Function | 0x100216c0 | 0x000216c0
`WFDStartBackgroundDiscoveryInt` | 82 (0x52) | Exported Function | 0x100216e0 | 0x000216e0
`WFDStartConnectorPairWithOOB` | 83 (0x53) | Exported Function | 0x100219e0 | 0x000219e0
`WFDStartListenerPairWithOOB` | 84 (0x54) | Exported Function | 0x1001c080 | 0x0001c080
`WFDStartOffloadedDiscoveryInt` | 85 (0x55) | Exported Function | 0x10021700 | 0x00021700
`WFDStartOpenSession` | 86 (0x56) | Exported Function | 0x1001ac10 | 0x0001ac10
`WFDStartOpenSessionInt` | 87 (0x57) | Exported Function | 0x10021720 | 0x00021720
`WFDStartUsingGroupExInt` | 88 (0x58) | Exported Function | 0x10021750 | 0x00021750
`WFDStartUsingGroupInt` | 89 (0x59) | Exported Function | 0x10021770 | 0x00021770
`WFDStopBackgroundDiscoveryInt` | 90 (0x5a) | Exported Function | 0x10021790 | 0x00021790
`WFDStopDiscoverDevicesExInt` | 91 (0x5b) | Exported Function | 0x100217b0 | 0x000217b0
`WFDStopDiscoverDevicesInt` | 92 (0x5c) | Exported Function | 0x100217d0 | 0x000217d0
`WFDStopOffloadedDiscoveryInt` | 93 (0x5d) | Exported Function | 0x100217f0 | 0x000217f0
`WFDStopUsingGroupInt` | 94 (0x5e) | Exported Function | 0x10021810 | 0x00021810
`WFDSvcLowPrivAcceptSessionInt` | 95 (0x5f) | Exported Function | 0x100223b0 | 0x000223b0
`WFDPairContinuePairWithDeviceInt` | 65 (0x41) | Exported Function | 0x10021500 | 0x00021500
`WlanWfdStopGO` | 258 (0x102) | Exported Function | 0x10021190 | 0x00021190


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanapi.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/f240d09a4ab90ee4a6a2d0500b09ce915659283b5d311be7f1422377af06dda9/detection/


## Possible Misuse

*The following table contains possible examples of `wlanapi.dll` being misused. While `wlanapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `ImageLoaded: '*\wlanapi.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


