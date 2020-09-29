---
title: FWPUCLNT.DLL | FWP/IPsec User-Mode API
excerpt: What is FWPUCLNT.DLL?
---

# FWPUCLNT.DLL 

* File Path: `C:\Windows\system32\FWPUCLNT.DLL`
* Description: FWP/IPsec User-Mode API

## Hashes

Type | Hash
-- | --
MD5 | `AA60A4FA1A7357C47F547B149B50E5A7`
SHA1 | `AEF8712FC6728A39B26556EFF30ADB588C238BD9`
SHA256 | `CA2F04AE902EE1F2597C95BAAEF39750322EAED185F544C3CF64A3D47AFC73BB`
SHA384 | `7CD009AF42A8FB6590878C21CFA2A6BE6FB637C155247003E1933D2198954548AC6A352B4C5348B505B2593547B6EA52`
SHA512 | `6C8D8BB976CBE0CCBF3A3BDBB3029F28148CE63021AA6609BE2939F13F3A39194CA9AEE14C90DBBFA6308BEE71CD44EB6B379738D7B6F72457931D5CA5504C6C`
SSDEEP | `6144:7oQhzdKIsxt0IvFBvYqz8GsQy+6t89c1hjwpOKuqZb1W/p5G0c:7oUCF2qdQ`
IMP | `1F8E964D47605C1A83330DB1AB288BF3`
PESHA1 | `48944D3A86ED518C7811FD63043B1F583C62CDE7`
PE256 | `4868A785BB8DA4A0858C150A456788894AC7BB0C31540BEF6C55A6062F2C8729`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`FwpiExpandCriteria0` | 1 (0x1) | Exported Function | 0x0000000180009b20 | 0x00009b20
`FwpsAleGetPortStatus0` | 176 (0xb0) | Exported Function | 0x0000000180010ca0 | 0x00010ca0
`FwpsClassifyUser0` | 177 (0xb1) | Exported Function | 0x0000000180010d40 | 0x00010d40
`FwpsFreeMemory0` | 178 (0xb2) | Exported Function | 0x0000000180001600 | 0x00001600
`FwpsGetInProcReplicaOffset0` | 179 (0xb3) | Exported Function | 0x0000000180015ba0 | 0x00015ba0
`FwpsLayerCreateInProcReplica0` | 180 (0xb4) | Exported Function | 0x0000000180015c30 | 0x00015c30
`FwpsLayerReleaseInProcReplica0` | 181 (0xb5) | Exported Function | 0x0000000180015cb0 | 0x00015cb0
`FwpsOpenToken0` | 182 (0xb6) | Exported Function | 0x0000000180010ea0 | 0x00010ea0
`FwpsQueryIPsecDosFWUsed0` | 183 (0xb7) | Exported Function | 0x0000000180011040 | 0x00011040
`FwpsQueryIPsecOffloadDone0` | 184 (0xb8) | Exported Function | 0x00000001800110c0 | 0x000110c0
`GetUnifiedTraceHandle` | 185 (0xb9) | Exported Function | 0x0000000180011140 | 0x00011140
`IkeextGetConfigParameters0` | 235 (0xeb) | Exported Function | 0x0000000180015d80 | 0x00015d80
`IkeextGetStatistics0` | 236 (0xec) | Exported Function | 0x0000000180015f50 | 0x00015f50
`IkeextGetStatistics1` | 237 (0xed) | Exported Function | 0x0000000180015fe0 | 0x00015fe0
`IkeextSaCreateEnumHandle0` | 238 (0xee) | Exported Function | 0x0000000180016100 | 0x00016100
`FwpsAleExplicitCredentialsQuery0` | 175 (0xaf) | Exported Function | 0x0000000180010c10 | 0x00010c10
`IkeextSaDbGetSecurityInfo0` | 239 (0xef) | Exported Function | 0x00000001800161a0 | 0x000161a0
`IkeextSaDeleteById0` | 241 (0xf1) | Exported Function | 0x00000001800163e0 | 0x000163e0
`IkeextSaDestroyEnumHandle0` | 242 (0xf2) | Exported Function | 0x0000000180016470 | 0x00016470
`IkeextSaEnum0` | 243 (0xf3) | Exported Function | 0x0000000180016500 | 0x00016500
`IkeextSaEnum1` | 244 (0xf4) | Exported Function | 0x0000000180016610 | 0x00016610
`IkeextSaEnum2` | 245 (0xf5) | Exported Function | 0x0000000180016720 | 0x00016720
`IkeextSaGetById0` | 246 (0xf6) | Exported Function | 0x00000001800167f0 | 0x000167f0
`IkeextSaGetById1` | 247 (0xf7) | Exported Function | 0x00000001800168c0 | 0x000168c0
`IkeextSaGetById2` | 248 (0xf8) | Exported Function | 0x0000000180016990 | 0x00016990
`IkeextSaUpdateAdditionalAddressesByTunnelId0` | 249 (0xf9) | Exported Function | 0x0000000180016a50 | 0x00016a50
`IkeextSaUpdatePreferredAddressesByTunnelId0` | 250 (0xfa) | Exported Function | 0x0000000180016b80 | 0x00016b80
`IkeextSetConfigParameters0` | 251 (0xfb) | Exported Function | 0x0000000180016cb0 | 0x00016cb0
`IPsecDospGetSecurityInfo0` | 186 (0xba) | Exported Function | 0x0000000180011160 | 0x00011160
`IPsecDospGetStatistics0` | 187 (0xbb) | Exported Function | 0x0000000180011270 | 0x00011270
`IPsecDospSetSecurityInfo0` | 188 (0xbc) | Exported Function | 0x0000000180011300 | 0x00011300
`IkeextSaDbSetSecurityInfo0` | 240 (0xf0) | Exported Function | 0x00000001800162c0 | 0x000162c0
`FwpsAleEndpointSetSecurityInfo0` | 174 (0xae) | Exported Function | 0x0000000180010b10 | 0x00010b10
`FwpsAleEndpointGetSecurityInfo0` | 173 (0xad) | Exported Function | 0x0000000180010a00 | 0x00010a00
`FwpsAleEndpointGetById0` | 172 (0xac) | Exported Function | 0x0000000180010970 | 0x00010970
`FwpmSessionEnum0` | 141 (0x8d) | Exported Function | 0x000000018000f290 | 0x0000f290
`FwpmSubLayerAdd0` | 142 (0x8e) | Exported Function | 0x0000000180004aa0 | 0x00004aa0
`FwpmSubLayerCreateEnumHandle0` | 143 (0x8f) | Exported Function | 0x000000018000f330 | 0x0000f330
`FwpmSubLayerDeleteByKey0` | 144 (0x90) | Exported Function | 0x000000018000f3b0 | 0x0000f3b0
`FwpmSubLayerDestroyEnumHandle0` | 145 (0x91) | Exported Function | 0x000000018000f450 | 0x0000f450
`FwpmSubLayerEnum0` | 146 (0x92) | Exported Function | 0x000000018000f4d0 | 0x0000f4d0
`FwpmSubLayerGetByKey0` | 147 (0x93) | Exported Function | 0x000000018000f570 | 0x0000f570
`FwpmSubLayerGetSecurityInfoByKey0` | 148 (0x94) | Exported Function | 0x000000018000f600 | 0x0000f600
`FwpmSubLayerSetSecurityInfoByKey0` | 149 (0x95) | Exported Function | 0x000000018000f710 | 0x0000f710
`FwpmSubLayerSubscribeChanges0` | 150 (0x96) | Exported Function | 0x000000018000f830 | 0x0000f830
`FwpmSubLayerSubscriptionsGet0` | 151 (0x97) | Exported Function | 0x000000018000f990 | 0x0000f990
`FwpmSubLayerUnsubscribeChanges0` | 152 (0x98) | Exported Function | 0x000000018000fa20 | 0x0000fa20
`FwpmSystemPortsGet0` | 153 (0x99) | Exported Function | 0x0000000180014640 | 0x00014640
`FwpmSystemPortsSubscribe0` | 154 (0x9a) | Exported Function | 0x0000000180014680 | 0x00014680
`FwpmSystemPortsUnsubscribe0` | 155 (0x9b) | Exported Function | 0x0000000180014750 | 0x00014750
`FwpmTraceRestoreDefaults0` | 156 (0x9c) | Exported Function | 0x0000000180014aa0 | 0x00014aa0
`FwpmTransactionAbort0` | 157 (0x9d) | Exported Function | 0x000000018000fad0 | 0x0000fad0
`FwpsAleEndpointEnum0` | 171 (0xab) | Exported Function | 0x00000001800108d0 | 0x000108d0
`FwpsAleEndpointDestroyEnumHandle0` | 170 (0xaa) | Exported Function | 0x0000000180010850 | 0x00010850
`FwpsAleEndpointCreateEnumHandle0` | 169 (0xa9) | Exported Function | 0x00000001800107d0 | 0x000107d0
`FwppIPsecSaContextCreate` | 168 (0xa8) | Exported Function | 0x00000001800103e0 | 0x000103e0
`FwppGetMD5HashBytes` | 167 (0xa7) | Exported Function | 0x00000001800103c0 | 0x000103c0
`FwppConnectionGetS2STunnelId` | 166 (0xa6) | Exported Function | 0x0000000180010170 | 0x00010170
`IPsecDospStateCreateEnumHandle0` | 189 (0xbd) | Exported Function | 0x0000000180011400 | 0x00011400
`FwppConnectionGetByS2STunnelId` | 165 (0xa5) | Exported Function | 0x00000001800100e0 | 0x000100e0
`FwpmvSwitchEventUnsubscribe0` | 161 (0xa1) | Exported Function | 0x000000018000fcd0 | 0x0000fcd0
`FwpmvSwitchEventSubscribe0` | 160 (0xa0) | Exported Function | 0x000000018000fb70 | 0x0000fb70
`FwpmvSwitchEventsSetSecurityInfo0` | 163 (0xa3) | Exported Function | 0x000000018000fea0 | 0x0000fea0
`FwpmvSwitchEventsGetSecurityInfo0` | 162 (0xa2) | Exported Function | 0x000000018000fd90 | 0x0000fd90
`FwpmTransactionCommit0` | 159 (0x9f) | Exported Function | 0x0000000180002270 | 0x00002270
`FwpmTransactionBegin0` | 158 (0x9e) | Exported Function | 0x0000000180003450 | 0x00003450
`FwppConnectionGetByIPsecInfo` | 164 (0xa4) | Exported Function | 0x0000000180010050 | 0x00010050
`FwpmSessionDestroyEnumHandle0` | 140 (0x8c) | Exported Function | 0x000000018000f210 | 0x0000f210
`IPsecDospStateDestroyEnumHandle0` | 190 (0xbe) | Exported Function | 0x0000000180011480 | 0x00011480
`IPsecGetKeyFromDictator0` | 192 (0xc0) | Exported Function | 0x0000000180011a00 | 0x00011a00
`IPsecSaCreateEnumHandle0` | 228 (0xe4) | Exported Function | 0x0000000180013530 | 0x00013530
`IPsecSaDbGetSecurityInfo0` | 229 (0xe5) | Exported Function | 0x00000001800135b0 | 0x000135b0
`IPsecSaDbSetSecurityInfo0` | 230 (0xe6) | Exported Function | 0x00000001800136c0 | 0x000136c0
`IPsecSaDestroyEnumHandle0` | 231 (0xe7) | Exported Function | 0x00000001800137c0 | 0x000137c0
`IPsecSaEnum0` | 232 (0xe8) | Exported Function | 0x0000000180013840 | 0x00013840
`IPsecSaEnum1` | 233 (0xe9) | Exported Function | 0x0000000180013950 | 0x00013950
`IPsecSaInitiateAsync0` | 234 (0xea) | Exported Function | 0x00000001800139f0 | 0x000139f0
`NamespaceCallout` | 252 (0xfc) | Exported Function | 0x0000000180002900 | 0x00002900
`WfpCloseDPConfigureHandle` | 260 (0x104) | Exported Function | 0x0000000180033be0 | 0x00033be0
`WfpConfigureDPSecurityDescriptor` | 261 (0x105) | Exported Function | 0x0000000180033c00 | 0x00033c00
`WfpCreateDPConfigureHandle` | 262 (0x106) | Exported Function | 0x0000000180033c60 | 0x00033c60
`WfpRIOChannelClose` | 263 (0x107) | Exported Function | 0x0000000180033be0 | 0x00033be0
`WfpRIOCleanupRequestQueue` | 264 (0x108) | Exported Function | 0x0000000180033fc0 | 0x00033fc0
`WfpRIOCloseCompletionQueue` | 265 (0x109) | Exported Function | 0x0000000180034070 | 0x00034070
`IPsecSaContextUpdate0` | 227 (0xe3) | Exported Function | 0x00000001800134b0 | 0x000134b0
`WfpRIOCreateChannel` | 266 (0x10a) | Exported Function | 0x0000000180034110 | 0x00034110
`WfpRIOCreateRequestQueue` | 268 (0x10c) | Exported Function | 0x0000000180034300 | 0x00034300
`WFPRIODequeueCompletion` | 253 (0xfd) | Exported Function | 0x0000000180033a70 | 0x00033a70
`WfpRIODeregisterBuffer` | 269 (0x10d) | Exported Function | 0x00000001800344d0 | 0x000344d0
`WfpRIOIndicateActivityThreshold` | 270 (0x10e) | Exported Function | 0x0000000180034550 | 0x00034550
`WfpRIONotify` | 271 (0x10f) | Exported Function | 0x00000001800345c0 | 0x000345c0
`WfpRIOReceive` | 272 (0x110) | Exported Function | 0x0000000180034640 | 0x00034640
`WfpRIORegisterBuffer` | 273 (0x111) | Exported Function | 0x0000000180034720 | 0x00034720
`WfpRIOResume` | 274 (0x112) | Exported Function | 0x00000001800347f0 | 0x000347f0
`WfpRIOSend` | 275 (0x113) | Exported Function | 0x0000000180034860 | 0x00034860
`WfpRIOSuspend` | 276 (0x114) | Exported Function | 0x0000000180034940 | 0x00034940
`WSADeleteSocketPeerTargetName` | 254 (0xfe) | Exported Function | 0x0000000180016e10 | 0x00016e10
`WSAImpersonateSocketPeer` | 255 (0xff) | Exported Function | 0x0000000180016e60 | 0x00016e60
`WSAQuerySocketSecurity` | 256 (0x100) | Exported Function | 0x0000000180017050 | 0x00017050
`WSARevertImpersonation` | 257 (0x101) | Exported Function | 0x00000001800170d0 | 0x000170d0
`WfpRIOCreateCompletionQueue` | 267 (0x10b) | Exported Function | 0x0000000180034130 | 0x00034130
`IPsecSaContextUnsubscribe0` | 226 (0xe2) | Exported Function | 0x0000000180013400 | 0x00013400
`IPsecSaContextSubscriptionsGet0` | 225 (0xe1) | Exported Function | 0x0000000180013370 | 0x00013370
`IPsecSaContextSubscribe0` | 224 (0xe0) | Exported Function | 0x0000000180013210 | 0x00013210
`IPsecGetStatistics0` | 193 (0xc1) | Exported Function | 0x0000000180011b10 | 0x00011b10
`IPsecGetStatistics1` | 194 (0xc2) | Exported Function | 0x0000000180011bf0 | 0x00011bf0
`IPsecKeyDictationCheck0` | 195 (0xc3) | Exported Function | 0x0000000180011c80 | 0x00011c80
`IPsecKeyManagerAddAndRegister0` | 196 (0xc4) | Exported Function | 0x0000000180011d10 | 0x00011d10
`IPsecKeyManagerGetSecurityInfoByKey0` | 197 (0xc5) | Exported Function | 0x0000000180011f10 | 0x00011f10
`IPsecKeyManagerSetSecurityInfoByKey0` | 198 (0xc6) | Exported Function | 0x0000000180012020 | 0x00012020
`IPsecKeyManagersGet0` | 200 (0xc8) | Exported Function | 0x0000000180012210 | 0x00012210
`IPsecKeyManagerUnregisterAndDelete0` | 199 (0xc7) | Exported Function | 0x0000000180012140 | 0x00012140
`IPsecKeyModuleAdd0` | 201 (0xc9) | Exported Function | 0x00000001800122b0 | 0x000122b0
`IPsecKeyModuleDelete0` | 202 (0xca) | Exported Function | 0x0000000180012430 | 0x00012430
`IPsecKeyModuleUpdateAcquire0` | 203 (0xcb) | Exported Function | 0x00000001800124e0 | 0x000124e0
`IPsecKeyNotification0` | 204 (0xcc) | Exported Function | 0x0000000180012560 | 0x00012560
`IPsecSaContextAddInbound0` | 205 (0xcd) | Exported Function | 0x00000001800125e0 | 0x000125e0
`IPsecSaContextAddInbound1` | 206 (0xce) | Exported Function | 0x00000001800126a0 | 0x000126a0
`IPsecSaContextAddInboundAndTrackConnection` | 207 (0xcf) | Exported Function | 0x0000000180012730 | 0x00012730
`IPsecSaContextAddOutbound0` | 208 (0xd0) | Exported Function | 0x00000001800127d0 | 0x000127d0
`IPsecSaContextAddOutbound1` | 209 (0xd1) | Exported Function | 0x0000000180012890 | 0x00012890
`IPsecSaContextSetSpi0` | 223 (0xdf) | Exported Function | 0x0000000180013170 | 0x00013170
`IPsecSaContextGetSpi1` | 222 (0xde) | Exported Function | 0x00000001800130e0 | 0x000130e0
`IPsecSaContextGetSpi0` | 221 (0xdd) | Exported Function | 0x0000000180013020 | 0x00013020
`IPsecSaContextGetById1` | 220 (0xdc) | Exported Function | 0x0000000180012f90 | 0x00012f90
`IPsecSaContextGetById0` | 219 (0xdb) | Exported Function | 0x0000000180012ec0 | 0x00012ec0
`IPsecSaContextExpire0` | 218 (0xda) | Exported Function | 0x0000000180012e50 | 0x00012e50
`IPsecDospStateEnum0` | 191 (0xbf) | Exported Function | 0x0000000180011500 | 0x00011500
`IPsecSaContextEnum1` | 217 (0xd9) | Exported Function | 0x0000000180012db0 | 0x00012db0
`IPsecSaContextDestroyEnumHandle0` | 215 (0xd7) | Exported Function | 0x0000000180012c20 | 0x00012c20
`IPsecSaContextDeleteById0` | 214 (0xd6) | Exported Function | 0x0000000180012bb0 | 0x00012bb0
`IPsecSaContextCreateEnumHandle0` | 213 (0xd5) | Exported Function | 0x0000000180012b30 | 0x00012b30
`IPsecSaContextCreate1` | 212 (0xd4) | Exported Function | 0x0000000180012a80 | 0x00012a80
`IPsecSaContextCreate0` | 211 (0xd3) | Exported Function | 0x00000001800129c0 | 0x000129c0
`IPsecSaContextAddOutboundAndTrackConnection` | 210 (0xd2) | Exported Function | 0x0000000180012920 | 0x00012920
`IPsecSaContextEnum0` | 216 (0xd8) | Exported Function | 0x0000000180012ca0 | 0x00012ca0
`FwpmSessionCreateEnumHandle0` | 139 (0x8b) | Exported Function | 0x000000018000f190 | 0x0000f190
`FwpmProviderUnsubscribeChanges0` | 138 (0x8a) | Exported Function | 0x000000018000f0e0 | 0x0000f0e0
`FwpmProviderSubscriptionsGet0` | 137 (0x89) | Exported Function | 0x000000018000f050 | 0x0000f050
`FwpmConnectionSubscribe0` | 37 (0x25) | Exported Function | 0x000000018000aa80 | 0x0000aa80
`FwpmConnectionUnsubscribe0` | 38 (0x26) | Exported Function | 0x000000018000abe0 | 0x0000abe0
`FwpmDiagnoseNetFailure0` | 39 (0x27) | Exported Function | 0x00000001800140f0 | 0x000140f0
`FwpmEngineClose0` | 40 (0x28) | Exported Function | 0x00000001800048c0 | 0x000048c0
`FwpmEngineGetOption0` | 41 (0x29) | Exported Function | 0x000000018000aca0 | 0x0000aca0
`FwpmEngineGetSecurityInfo0` | 42 (0x2a) | Exported Function | 0x000000018000ad30 | 0x0000ad30
`FwpmEngineOpen0` | 43 (0x2b) | Exported Function | 0x0000000180005610 | 0x00005610
`FwpmEngineSetOption0` | 44 (0x2c) | Exported Function | 0x0000000180003a70 | 0x00003a70
`FwpmEngineSetSecurityInfo0` | 45 (0x2d) | Exported Function | 0x000000018000ae40 | 0x0000ae40
`FwpmEventProviderCreate0` | 46 (0x2e) | Exported Function | 0x0000000180003890 | 0x00003890
`FwpmEventProviderDestroy0` | 47 (0x2f) | Exported Function | 0x0000000180014600 | 0x00014600
`FwpmEventProviderFireNetEvent0` | 48 (0x30) | Exported Function | 0x0000000180014630 | 0x00014630
`FwpmEventProviderIsNetEventTypeEnabled0` | 49 (0x31) | Exported Function | 0x0000000180001e50 | 0x00001e50
`FwpmFilterAdd0` | 50 (0x32) | Exported Function | 0x00000001800020a0 | 0x000020a0
`FwpmConnectionSetSecurityInfo0` | 36 (0x24) | Exported Function | 0x000000018000a980 | 0x0000a980
`FwpmFilterCreateEnumHandle0` | 51 (0x33) | Exported Function | 0x0000000180004b90 | 0x00004b90
`FwpmFilterDeleteByKey0` | 53 (0x35) | Exported Function | 0x0000000180005480 | 0x00005480
`FwpmFilterDestroyEnumHandle0` | 54 (0x36) | Exported Function | 0x0000000180004bf0 | 0x00004bf0
`FwpmFilterEnum0` | 55 (0x37) | Exported Function | 0x0000000180004c60 | 0x00004c60
`FwpmFilterGetById0` | 56 (0x38) | Exported Function | 0x000000018000af40 | 0x0000af40
`FwpmFilterGetByKey0` | 57 (0x39) | Exported Function | 0x00000001800034a0 | 0x000034a0
`FwpmFilterGetSecurityInfoByKey0` | 58 (0x3a) | Exported Function | 0x000000018000afd0 | 0x0000afd0
`FwpmFilterSetSecurityInfoByKey0` | 59 (0x3b) | Exported Function | 0x000000018000b0e0 | 0x0000b0e0
`FwpmFilterSubscribeChanges0` | 60 (0x3c) | Exported Function | 0x0000000180004790 | 0x00004790
`FwpmFilterSubscriptionsGet0` | 61 (0x3d) | Exported Function | 0x000000018000b200 | 0x0000b200
`FwpmFilterUnsubscribeChanges0` | 62 (0x3e) | Exported Function | 0x000000018000b290 | 0x0000b290
`FwpmFreeMemory0` | 63 (0x3f) | Exported Function | 0x0000000180001600 | 0x00001600
`FwpmGetAppIdFromFileName0` | 64 (0x40) | Exported Function | 0x000000018000b340 | 0x0000b340
`FwpmGetSidFromOnlineId0` | 65 (0x41) | Exported Function | 0x0000000180037970 | 0x00037970
`FwpmIPsecS2STunnelAddConditions0` | 66 (0x42) | Exported Function | 0x000000018000b450 | 0x0000b450
`FwpmFilterDeleteById0` | 52 (0x34) | Exported Function | 0x0000000180001010 | 0x00001010
`FwpmConnectionGetSecurityInfo0` | 35 (0x23) | Exported Function | 0x000000018000a870 | 0x0000a870
`FwpmConnectionGetById0` | 34 (0x22) | Exported Function | 0x000000018000a7e0 | 0x0000a7e0
`FwpmConnectionEnum0` | 33 (0x21) | Exported Function | 0x000000018000a740 | 0x0000a740
`FwpiFreeCriteria0` | 2 (0x2) | Exported Function | 0x0000000180009bd0 | 0x00009bd0
`FwpiVpnTriggerAddAppSids` | 3 (0x3) | Exported Function | 0x00000001800332e0 | 0x000332e0
`FwpiVpnTriggerAddFilePaths` | 4 (0x4) | Exported Function | 0x0000000180033360 | 0x00033360
`FwpiVpnTriggerAddSecurityDescriptor` | 5 (0x5) | Exported Function | 0x00000001800333e0 | 0x000333e0
`FwpiVpnTriggerConfigureParameters` | 6 (0x6) | Exported Function | 0x00000001800334c0 | 0x000334c0
`FwpiVpnTriggerEventSubscribe0` | 7 (0x7) | Exported Function | 0x0000000180033530 | 0x00033530
`FwpiVpnTriggerEventUnsubscribe0` | 8 (0x8) | Exported Function | 0x0000000180033690 | 0x00033690
`FwpiVpnTriggerInitializeNrptTriggering` | 9 (0x9) | Exported Function | 0x0000000180033750 | 0x00033750
`FwpiVpnTriggerRemoveAppSids` | 10 (0xa) | Exported Function | 0x00000001800337d0 | 0x000337d0
`FwpiVpnTriggerRemoveFilePaths` | 11 (0xb) | Exported Function | 0x0000000180033840 | 0x00033840
`FwpiVpnTriggerRemoveSecurityDescriptor` | 12 (0xc) | Exported Function | 0x00000001800338b0 | 0x000338b0
`FwpiVpnTriggerResetNrptTriggering` | 13 (0xd) | Exported Function | 0x0000000180033920 | 0x00033920
`FwpiVpnTriggerSetStateDisconnected` | 14 (0xe) | Exported Function | 0x0000000180033990 | 0x00033990
`FwpiVpnTriggerUninitializeNrptTriggering` | 15 (0xf) | Exported Function | 0x0000000180033a00 | 0x00033a00
`FwpmBitmapIndexFree0` | 16 (0x10) | Exported Function | 0x0000000180009bf0 | 0x00009bf0
`FwpmBitmapIndexGet0` | 17 (0x11) | Exported Function | 0x0000000180009cb0 | 0x00009cb0
`FwpmCalloutAdd0` | 18 (0x12) | Exported Function | 0x0000000180005370 | 0x00005370
`FwpmConnectionDestroyEnumHandle0` | 32 (0x20) | Exported Function | 0x000000018000a6c0 | 0x0000a6c0
`FwpmConnectionCreateEnumHandle0` | 31 (0x1f) | Exported Function | 0x000000018000a640 | 0x0000a640
`FwpmCalloutUnsubscribeChanges0` | 30 (0x1e) | Exported Function | 0x000000018000a590 | 0x0000a590
`FwpmCalloutSubscriptionsGet0` | 29 (0x1d) | Exported Function | 0x000000018000a500 | 0x0000a500
`FwpmCalloutSubscribeChanges0` | 28 (0x1c) | Exported Function | 0x000000018000a3a0 | 0x0000a3a0
`FwpmCalloutSetSecurityInfoByKey0` | 27 (0x1b) | Exported Function | 0x000000018000a280 | 0x0000a280
`FwpmIPsecS2STunnelAddInterfaceToCompartment0` | 67 (0x43) | Exported Function | 0x000000018000b540 | 0x0000b540
`FwpmCalloutGetSecurityInfoByKey0` | 26 (0x1a) | Exported Function | 0x000000018000a170 | 0x0000a170
`FwpmCalloutGetById0` | 24 (0x18) | Exported Function | 0x000000018000a050 | 0x0000a050
`FwpmCalloutEnum0` | 23 (0x17) | Exported Function | 0x0000000180009fb0 | 0x00009fb0
`FwpmCalloutDestroyEnumHandle0` | 22 (0x16) | Exported Function | 0x0000000180009f30 | 0x00009f30
`FwpmCalloutDeleteByKey0` | 21 (0x15) | Exported Function | 0x0000000180009e90 | 0x00009e90
`FwpmCalloutDeleteById0` | 20 (0x14) | Exported Function | 0x0000000180009df0 | 0x00009df0
`FwpmCalloutCreateEnumHandle0` | 19 (0x13) | Exported Function | 0x0000000180009d70 | 0x00009d70
`FwpmCalloutGetByKey0` | 25 (0x19) | Exported Function | 0x000000018000a0e0 | 0x0000a0e0
`FwpmIPsecS2STunnelGetInterfaceForCompartment0` | 68 (0x44) | Exported Function | 0x000000018000b5c0 | 0x0000b5c0
`FwpmIPsecS2STunnelRemoveConditions0` | 69 (0x45) | Exported Function | 0x000000018000b640 | 0x0000b640
`FwpmIPsecS2STunnelRemoveInterfaceFromCompartment0` | 70 (0x46) | Exported Function | 0x000000018000b730 | 0x0000b730
`FwpmProviderContextAdd2` | 106 (0x6a) | Exported Function | 0x000000018000d750 | 0x0000d750
`FwpmProviderContextAdd3` | 107 (0x6b) | Exported Function | 0x0000000180004550 | 0x00004550
`FwpmProviderContextCreateEnumHandle0` | 108 (0x6c) | Exported Function | 0x000000018000d830 | 0x0000d830
`FwpmProviderContextDeleteById0` | 109 (0x6d) | Exported Function | 0x000000018000d8b0 | 0x0000d8b0
`FwpmProviderContextDeleteByKey0` | 110 (0x6e) | Exported Function | 0x000000018000d950 | 0x0000d950
`FwpmProviderContextDestroyEnumHandle0` | 111 (0x6f) | Exported Function | 0x000000018000d9f0 | 0x0000d9f0
`FwpmProviderContextEnum0` | 112 (0x70) | Exported Function | 0x000000018000da70 | 0x0000da70
`FwpmProviderContextEnum1` | 113 (0x71) | Exported Function | 0x000000018000dbb0 | 0x0000dbb0
`FwpmProviderContextEnum2` | 114 (0x72) | Exported Function | 0x000000018000dcf0 | 0x0000dcf0
`FwpmProviderContextEnum3` | 115 (0x73) | Exported Function | 0x000000018000de00 | 0x0000de00
`FwpmProviderContextGetById0` | 116 (0x74) | Exported Function | 0x000000018000dea0 | 0x0000dea0
`FwpmProviderContextGetById1` | 117 (0x75) | Exported Function | 0x000000018000df90 | 0x0000df90
`FwpmProviderContextGetById2` | 118 (0x76) | Exported Function | 0x000000018000e080 | 0x0000e080
`FwpmProviderContextGetById3` | 119 (0x77) | Exported Function | 0x000000018000e150 | 0x0000e150
`FwpmProviderContextGetByKey0` | 120 (0x78) | Exported Function | 0x000000018000e1e0 | 0x0000e1e0
`FwpmProviderContextGetByKey1` | 121 (0x79) | Exported Function | 0x000000018000e2d0 | 0x0000e2d0
`FwpmProviderContextGetByKey2` | 122 (0x7a) | Exported Function | 0x000000018000e3c0 | 0x0000e3c0
`FwpmProviderSubscribeChanges0` | 136 (0x88) | Exported Function | 0x000000018000eef0 | 0x0000eef0
`FwpmProviderSetSecurityInfoByKey0` | 135 (0x87) | Exported Function | 0x000000018000edd0 | 0x0000edd0
`FwpmProviderGetSecurityInfoByKey0` | 134 (0x86) | Exported Function | 0x000000018000ecc0 | 0x0000ecc0
`FwpmProviderGetByKey0` | 133 (0x85) | Exported Function | 0x000000018000ec30 | 0x0000ec30
`FwpmProviderEnum0` | 132 (0x84) | Exported Function | 0x000000018000eb90 | 0x0000eb90
`FwpmProviderDestroyEnumHandle0` | 131 (0x83) | Exported Function | 0x000000018000eb10 | 0x0000eb10
`FwpmProviderContextAdd1` | 105 (0x69) | Exported Function | 0x000000018000d680 | 0x0000d680
`FwpmProviderDeleteByKey0` | 130 (0x82) | Exported Function | 0x000000018000ea70 | 0x0000ea70
`FwpmProviderContextUnsubscribeChanges0` | 128 (0x80) | Exported Function | 0x000000018000e940 | 0x0000e940
`FwpmProviderContextSubscriptionsGet0` | 127 (0x7f) | Exported Function | 0x000000018000e8b0 | 0x0000e8b0
`FwpmProviderContextSubscribeChanges0` | 126 (0x7e) | Exported Function | 0x000000018000e750 | 0x0000e750
`FwpmProviderContextSetSecurityInfoByKey0` | 125 (0x7d) | Exported Function | 0x000000018000e630 | 0x0000e630
`FwpmProviderContextGetSecurityInfoByKey0` | 124 (0x7c) | Exported Function | 0x000000018000e520 | 0x0000e520
`FwpmProviderContextGetByKey3` | 123 (0x7b) | Exported Function | 0x000000018000e490 | 0x0000e490
`FwpmProviderCreateEnumHandle0` | 129 (0x81) | Exported Function | 0x000000018000e9f0 | 0x0000e9f0
`WSASetSocketPeerTargetName` | 258 (0x102) | Exported Function | 0x0000000180017110 | 0x00017110
`FwpmProviderContextAdd0` | 104 (0x68) | Exported Function | 0x0000000180003f10 | 0x00003f10
`FwpmProcessNameResolutionEvent0` | 102 (0x66) | Exported Function | 0x000000018000d400 | 0x0000d400
`FwpmIPsecTunnelAdd0` | 71 (0x47) | Exported Function | 0x000000018000b7a0 | 0x0000b7a0
`FwpmIPsecTunnelAdd1` | 72 (0x48) | Exported Function | 0x000000018000b920 | 0x0000b920
`FwpmIPsecTunnelAdd2` | 73 (0x49) | Exported Function | 0x000000018000baa0 | 0x0000baa0
`FwpmIPsecTunnelAdd3` | 74 (0x4a) | Exported Function | 0x000000018000bbf0 | 0x0000bbf0
`FwpmIPsecTunnelAddConditions0` | 75 (0x4b) | Exported Function | 0x000000018000bd80 | 0x0000bd80
`FwpmIPsecTunnelDeleteByKey0` | 76 (0x4c) | Exported Function | 0x000000018000be50 | 0x0000be50
`FwpmLayerCreateEnumHandle0` | 77 (0x4d) | Exported Function | 0x000000018000bed0 | 0x0000bed0
`FwpmLayerDestroyEnumHandle0` | 78 (0x4e) | Exported Function | 0x000000018000bf50 | 0x0000bf50
`FwpmLayerEnum0` | 79 (0x4f) | Exported Function | 0x000000018000bfd0 | 0x0000bfd0
`FwpmLayerGetById0` | 80 (0x50) | Exported Function | 0x000000018000c070 | 0x0000c070
`FwpmLayerGetByKey0` | 81 (0x51) | Exported Function | 0x000000018000c100 | 0x0000c100
`FwpmLayerGetSecurityInfoByKey0` | 82 (0x52) | Exported Function | 0x000000018000c190 | 0x0000c190
`FwpmLayerSetSecurityInfoByKey0` | 83 (0x53) | Exported Function | 0x000000018000c2a0 | 0x0000c2a0
`FwpmNetEventCreateEnumHandle0` | 84 (0x54) | Exported Function | 0x000000018000c3c0 | 0x0000c3c0
`FwpmNetEventDestroyEnumHandle0` | 85 (0x55) | Exported Function | 0x000000018000c440 | 0x0000c440
`FwpmNetEventEnum0` | 86 (0x56) | Exported Function | 0x000000018000c4c0 | 0x0000c4c0
`FwpmNetEventEnum1` | 87 (0x57) | Exported Function | 0x000000018000c5d0 | 0x0000c5d0
`FwpmNetEventUnsubscribe0` | 98 (0x62) | Exported Function | 0x000000018000d0c0 | 0x0000d0c0
`FwpmNetEventSubscriptionsGet0` | 97 (0x61) | Exported Function | 0x000000018000d030 | 0x0000d030
`FwpmNetEventSubscribe4` | 96 (0x60) | Exported Function | 0x0000000180003de0 | 0x00003de0
`FwpmNetEventSubscribe3` | 95 (0x5f) | Exported Function | 0x000000018000ced0 | 0x0000ced0
`FwpmNetEventSubscribe2` | 94 (0x5e) | Exported Function | 0x000000018000cd70 | 0x0000cd70
`FwpmNetEventSubscribe1` | 93 (0x5d) | Exported Function | 0x000000018000cc10 | 0x0000cc10
`FwpmProviderAdd0` | 103 (0x67) | Exported Function | 0x00000001800049d0 | 0x000049d0
`FwpmNetEventSubscribe0` | 92 (0x5c) | Exported Function | 0x000000018000cab0 | 0x0000cab0
`FwpmNetEventsLost0` | 100 (0x64) | Exported Function | 0x000000018000d280 | 0x0000d280
`FwpmNetEventsGetSecurityInfo0` | 99 (0x63) | Exported Function | 0x000000018000d170 | 0x0000d170
`FwpmNetEventEnum5` | 91 (0x5b) | Exported Function | 0x000000018000ca10 | 0x0000ca10
`FwpmNetEventEnum4` | 90 (0x5a) | Exported Function | 0x000000018000c900 | 0x0000c900
`FwpmNetEventEnum3` | 89 (0x59) | Exported Function | 0x000000018000c7f0 | 0x0000c7f0
`FwpmNetEventEnum2` | 88 (0x58) | Exported Function | 0x000000018000c6e0 | 0x0000c6e0
`FwpmNetEventsSetSecurityInfo0` | 101 (0x65) | Exported Function | 0x000000018000d300 | 0x0000d300
`WSASetSocketSecurity` | 259 (0x103) | Exported Function | 0x0000000180017160 | 0x00017160


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fwpuclnt.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/ca2f04ae902ee1f2597c95baaef39750322eaed185f544c3cf64a3d47afc73bb/detection/





MIT License. Copyright (c) 2020 Strontic.


