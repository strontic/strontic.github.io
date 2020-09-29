---
title: dnsapi.dll | DNS Client API DLL
excerpt: What is dnsapi.dll?
---

# dnsapi.dll 

* File Path: `C:\Windows\SysWOW64\dnsapi.dll`
* Description: DNS Client API DLL

## Hashes

Type | Hash
-- | --
MD5 | `4116BF1EEA2BA39A56C83274AA6D92D8`
SHA1 | `B4C5F89C56F2F281F7D3476F97E15186167C8584`
SHA256 | `1DF0241421AB302C3086DA54D6EB100B0CD155426BF640C3F0CE8620F79B6D19`
SHA384 | `5B2F9A5035DC45DE8BF74F116187DA8C8FF8FF4AC1EFEFBE20B71DCF52DB36383AB2FD2DB547EA94C8D483AA03BED93B`
SHA512 | `B14F7B8E70328078715CD026E54518FF91167BBDE7B2AFCDDF26AE2D9A92BEA44D583755FF540AC680865C5C393A04170CF3F9901C38002B345B4295BA3A1E65`
SSDEEP | `12288:TZiGAx2/xVFFGZCft6WPJOVEvYbndfH0iKoFL/unkrKNR:ToLkTF9gWOVVbdPYw/unkrKL`
IMP | `7113933192DB4996FA2203BD225ABBDE`
PESHA1 | `B0797FCF5771553709EFC22FDF25CDDCD21CEF19`
PE256 | `6323484A5D93BCC596B14F1DB38A3B07B42BEB8A1DCF9E1B9B91E117C3341B7D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AdaptiveTimeout_ClearInterfaceSpecificConfiguration` | 13 (0xd) | Exported Function | 0x5fdac6d0 | 0x0002c6d0
`DnsServiceRegister` | 163 (0xa3) | Exported Function | 0x5fddf840 | 0x0005f840
`DnsServiceFreeInstance` | 162 (0xa2) | Exported Function | 0x5fddf7c0 | 0x0005f7c0
`DnsServiceDeRegister` | 161 (0xa1) | Exported Function | 0x5fddf6e0 | 0x0005f6e0
`DnsServiceCopyInstance` | 160 (0xa0) | Exported Function | 0x5fddf690 | 0x0005f690
`DnsServiceConstructInstance` | 159 (0x9f) | Exported Function | 0x5fddf2e0 | 0x0005f2e0
`DnsServiceBrowseCancel` | 158 (0x9e) | Exported Function | 0x5fddf250 | 0x0005f250
`DnsServiceRegisterCancel` | 164 (0xa4) | Exported Function | 0x5fddf9d0 | 0x0005f9d0
`DnsServiceBrowse` | 157 (0x9d) | Exported Function | 0x5fddefe0 | 0x0005efe0
`DnsResolverQueryHvsi` | 155 (0x9b) | Exported Function | 0x5fdb7fd0 | 0x00037fd0
`DnsResolverOp` | 154 (0x9a) | Exported Function | 0x5fdb25f0 | 0x000325f0
`DnsResetQueryRetryTimeouts` | 153 (0x99) | Exported Function | 0x5fdd1ab0 | 0x00051ab0
`DnsReplaceRecordSetW` | 152 (0x98) | Exported Function | 0x5fdd84b0 | 0x000584b0
`DnsReplaceRecordSetUTF8` | 151 (0x97) | Exported Function | 0x5fdd8480 | 0x00058480
`DnsReplaceRecordSetA` | 150 (0x96) | Exported Function | 0x5fdd8450 | 0x00058450
`DnsScreenLocalAddrsForRegistration` | 156 (0x9c) | Exported Function | 0x5fdd36a0 | 0x000536a0
`DnsRemoveRegistrations` | 149 (0x95) | Exported Function | 0x5fdd2230 | 0x00052230
`DnsServiceResolve` | 165 (0xa5) | Exported Function | 0x5fddfa60 | 0x0005fa60
`DnsSetConfigDword` | 167 (0xa7) | Exported Function | 0x5fdcf9b0 | 0x0004f9b0
`DnsUpdateMachinePresence` | 179 (0xb3) | Exported Function | 0x5fdaf0e0 | 0x0002f0e0
`DnsUpdate` | 178 (0xb2) | Exported Function | 0x5fddcc20 | 0x0005cc20
`DnsUnicodeToUtf8` | 7 (0x7) | Exported Function | 0x5fdd1d60 | 0x00051d60
`DnsTraceServerConfig` | 177 (0xb1) | Exported Function | 0x5fda97e0 | 0x000297e0
`DnsStringCopyAllocateEx` | 176 (0xb0) | Exported Function | 0x5fdd2240 | 0x00052240
`DnsStopMulticastQuery` | 175 (0xaf) | Exported Function | 0x5fdabef0 | 0x0002bef0
`DnsServiceResolveCancel` | 166 (0xa6) | Exported Function | 0x5fddfb10 | 0x0005fb10
`DnsStatusString` | 6 (0x6) | Exported Function | 0x5fdd1d30 | 0x00051d30
`DnsSetSettings` | 173 (0xad) | Exported Function | 0x5fdb5fa0 | 0x00035fa0
`DnsSetQueryRetryTimeouts` | 172 (0xac) | Exported Function | 0x5fdd1b30 | 0x00051b30
`DnsSetNrptRules` | 171 (0xab) | Exported Function | 0x5fdbc0e0 | 0x0003c0e0
`DnsSetNrptRule` | 170 (0xaa) | Exported Function | 0x5fdbc0a0 | 0x0003c0a0
`DnsSetInterfaceSettings` | 169 (0xa9) | Exported Function | 0x5fdb5d30 | 0x00035d30
`DnsSetConfigValue` | 168 (0xa8) | Exported Function | 0x5fdb5250 | 0x00035250
`DnsStartMulticastQuery` | 174 (0xae) | Exported Function | 0x5fdaaaf0 | 0x0002aaf0
`DnsUpdateTest_A` | 180 (0xb4) | Exported Function | 0x5fdd84e0 | 0x000584e0
`DnsRemoveNrptRule` | 148 (0x94) | Exported Function | 0x5fdbbfd0 | 0x0003bfd0
`DnsRegisterLocal` | 146 (0x92) | Exported Function | 0x5fddfc80 | 0x0005fc80
`DnsQueryConfig` | 124 (0x7c) | Exported Function | 0x5fda9ac0 | 0x00029ac0
`DnsQuery_W` | 133 (0x85) | Exported Function | 0x5fd93530 | 0x00013530
`DnsQuery_UTF8` | 132 (0x84) | Exported Function | 0x5fd934f0 | 0x000134f0
`DnsQuery_A` | 131 (0x83) | Exported Function | 0x5fdd60d0 | 0x000560d0
`DnsNotifyResolverEx` | 123 (0x7b) | Exported Function | 0x5fdb2970 | 0x00032970
`DnsNotifyResolverClusterIp` | 122 (0x7a) | Exported Function | 0x5fddcc10 | 0x0005cc10
`DnsQueryConfigAllocEx` | 125 (0x7d) | Exported Function | 0x5fda9a40 | 0x00029a40
`DnsNotifyResolver` | 121 (0x79) | Exported Function | 0x5fdb1dd0 | 0x00031dd0
`DnsNetworkInfo_CreateFromFAZ` | 119 (0x77) | Exported Function | 0x5fdd4750 | 0x00054750
`DnsNameCopyAllocate` | 118 (0x76) | Exported Function | 0x5fdd2060 | 0x00052060
`DnsNameCopy` | 117 (0x75) | Exported Function | 0x5fdd2030 | 0x00052030
`DnsNameCompareEx_W` | 113 (0x71) | Exported Function | 0x5fdd1fd0 | 0x00051fd0
`DnsNameCompareEx_UTF8` | 112 (0x70) | Exported Function | 0x5fdd1fb0 | 0x00051fb0
`DnsNameCompareEx_A` | 111 (0x6f) | Exported Function | 0x5fdd1f90 | 0x00051f90
`DnsNetworkInformation_CreateFromFAZ` | 120 (0x78) | Exported Function | 0x5fdd49b0 | 0x000549b0
`DnsReleaseContextHandle` | 147 (0x93) | Exported Function | 0x5fdd8420 | 0x00058420
`DnsQueryConfigDword` | 126 (0x7e) | Exported Function | 0x5fdb0660 | 0x00030660
`DnsQueryExA` | 128 (0x80) | Exported Function | 0x5fdd5ff0 | 0x00055ff0
`DnsRecordTypeForName` | 145 (0x91) | Exported Function | 0x5fdd2210 | 0x00052210
`DnsRecordStringForWritableType` | 144 (0x90) | Exported Function | 0x5fdd21d0 | 0x000521d0
`DnsRecordStringForType` | 143 (0x8f) | Exported Function | 0x5fdd21b0 | 0x000521b0
`DnsRecordSetDetach` | 142 (0x8e) | Exported Function | 0x5fdd2190 | 0x00052190
`DnsRecordSetCopyEx` | 141 (0x8d) | Exported Function | 0x5fdd2170 | 0x00052170
`DnsRecordSetCompare` | 140 (0x8c) | Exported Function | 0x5fdd2140 | 0x00052140
`DnsQueryEx` | 127 (0x7f) | Exported Function | 0x5fd99380 | 0x00019380
`DnsRecordListUnmapV4MappedAAAAInPlace` | 139 (0x8b) | Exported Function | 0x5fdb28f0 | 0x000328f0
`DnsRecordCopyEx` | 137 (0x89) | Exported Function | 0x5fdd2100 | 0x00052100
`DnsRecordCompare` | 136 (0x88) | Exported Function | 0x5fdd20e0 | 0x000520e0
`DnsRecordBuild_W` | 135 (0x87) | Exported Function | 0x5fdd20b0 | 0x000520b0
`DnsRecordBuild_UTF8` | 134 (0x86) | Exported Function | 0x5fdd2080 | 0x00052080
`DnsQueryExW` | 130 (0x82) | Exported Function | 0x5fdd6070 | 0x00056070
`DnsQueryExUTF8` | 129 (0x81) | Exported Function | 0x5fdd6030 | 0x00056030
`DnsRecordListFree` | 138 (0x8a) | Exported Function | 0x5fdd2120 | 0x00052120
`DnsUpdateTest_UTF8` | 181 (0xb5) | Exported Function | 0x5fdd8550 | 0x00058550
`DnsUpdateTest_W` | 182 (0xb6) | Exported Function | 0x5fdd85c0 | 0x000585c0
`DnsUtf8ToUnicode` | 8 (0x8) | Exported Function | 0x5fdd1d70 | 0x00051d70
`Send_OpenTcpConnectionAndSend` | 269 (0x10d) | Exported Function | 0x5fdd7420 | 0x00057420
`Send_MessagePrivateEx` | 268 (0x10c) | Exported Function | 0x5fda0640 | 0x00020640
`Send_MessagePrivate` | 267 (0x10b) | Exported Function | 0x5fd94430 | 0x00014430
`Send_AndRecvUdpWithParam` | 266 (0x10a) | Exported Function | 0x5fd9f930 | 0x0001f930
`Security_ContextListTimeout` | 265 (0x109) | Exported Function | 0x5fdd24b0 | 0x000524b0
`Reg_ReadUpdateInfo` | 264 (0x108) | Exported Function | 0x5fdb2390 | 0x00032390
`Socket_CacheCleanup` | 270 (0x10e) | Exported Function | 0x5fdac760 | 0x0002c760
`Reg_ReadGlobalsEx` | 263 (0x107) | Exported Function | 0x5fd9c470 | 0x0001c470
`Reg_FreeUpdateInfo` | 261 (0x105) | Exported Function | 0x5fdb2890 | 0x00032890
`QueryDirectEx` | 258 (0x102) | Exported Function | 0x5fdd53e0 | 0x000553e0
`Query_Main` | 260 (0x104) | Exported Function | 0x5fd9cfc0 | 0x0001cfc0
`Query_Cancel` | 259 (0x103) | Exported Function | 0x5fd9b270 | 0x0001b270
`NetInfo_UpdateServerReachability` | 257 (0x101) | Exported Function | 0x5fdb1620 | 0x00031620
`NetInfo_UpdateNetworkProperties` | 256 (0x100) | Exported Function | 0x5fdb20e0 | 0x000320e0
`Reg_GetValueEx` | 262 (0x106) | Exported Function | 0x5fda9f40 | 0x00029f40
`NetInfo_UpdateDnsInterfaceConfigChange` | 255 (0xff) | Exported Function | 0x5fdd4090 | 0x00054090
`Socket_CacheInit` | 271 (0x10f) | Exported Function | 0x5fdb4ae0 | 0x00034ae0
`Socket_ClearMessageSockets` | 273 (0x111) | Exported Function | 0x5fd94050 | 0x00014050
`Util_IsIp6Running` | 287 (0x11f) | Exported Function | 0x5fdd9ef0 | 0x00059ef0
`Update_ReplaceAddressRecordsW` | 286 (0x11e) | Exported Function | 0x5fdd9060 | 0x00059060
`Trace_Reset` | 285 (0x11d) | Exported Function | 0x5fdb27f0 | 0x000327f0
`Socket_TcpListen` | 284 (0x11c) | Exported Function | 0x5fdd7690 | 0x00057690
`Socket_SetTtl` | 283 (0x11b) | Exported Function | 0x5fd93880 | 0x00013880
`Socket_SetMulticastLoopBack` | 282 (0x11a) | Exported Function | 0x5fdb1d60 | 0x00031d60
`Socket_CleanupWinsock` | 272 (0x110) | Exported Function | 0x5fdac760 | 0x0002c760
`Socket_SetMulticastInterface` | 281 (0x119) | Exported Function | 0x5fd93910 | 0x00013910
`Socket_JoinMulticast` | 279 (0x117) | Exported Function | 0x5fdb0df0 | 0x00030df0
`Socket_InitWinsock` | 278 (0x116) | Exported Function | 0x5fddcca0 | 0x0005cca0
`Socket_CreateMulticast` | 277 (0x115) | Exported Function | 0x5fddcc80 | 0x0005cc80
`Socket_Create` | 276 (0x114) | Exported Function | 0x5fdb2270 | 0x00032270
`Socket_CloseMessageSockets` | 275 (0x113) | Exported Function | 0x5fd94000 | 0x00014000
`Socket_CloseEx` | 274 (0x112) | Exported Function | 0x5fdafaa0 | 0x0002faa0
`Socket_RecvFrom` | 280 (0x118) | Exported Function | 0x5fd90e60 | 0x00010e60
`NetInfo_ResetServerPriorities` | 254 (0xfe) | Exported Function | 0x5fda8770 | 0x00028770
`NetInfo_IsTcpipConfigChange` | 253 (0xfd) | Exported Function | 0x5fdb0fb0 | 0x00030fb0
`NetInfo_IsForUpdate` | 252 (0xfc) | Exported Function | 0x5fdd4e60 | 0x00054e60
`ExtraInfo_Init` | 232 (0xe8) | Exported Function | 0x5fdd9e40 | 0x00059e40
`DnsWriteReverseNameStringForIpAddress` | 195 (0xc3) | Exported Function | 0x5fdd23b0 | 0x000523b0
`DnsWriteQuestionToBuffer_W` | 194 (0xc2) | Exported Function | 0x5fdd6780 | 0x00056780
`DnsWriteQuestionToBuffer_UTF8` | 193 (0xc1) | Exported Function | 0x5fdd66e0 | 0x000566e0
`DnsValidateUtf8Byte` | 192 (0xc0) | Exported Function | 0x5fdd2390 | 0x00052390
`DnsValidateServerStatus` | 189 (0xbd) | Exported Function | 0x5fdda020 | 0x0005a020
`Faz_AreServerListsInSameNameSpace` | 233 (0xe9) | Exported Function | 0x5fdd24d0 | 0x000524d0
`DnsValidateServerArray_W` | 188 (0xbc) | Exported Function | 0x5fdd9fd0 | 0x00059fd0
`DnsValidateServer_W` | 191 (0xbf) | Exported Function | 0x5fdda170 | 0x0005a170
`DnsValidateServer_A` | 190 (0xbe) | Exported Function | 0x5fdda0c0 | 0x0005a0c0
`DnsValidateNameOrIp_TempW` | 183 (0xb7) | Exported Function | 0x5fdd3a30 | 0x00053a30
`DnsValidateName_W` | 186 (0xba) | Exported Function | 0x5fda7300 | 0x00027300
`DnsValidateName_UTF8` | 185 (0xb9) | Exported Function | 0x5fdd2300 | 0x00052300
`DnsValidateName_A` | 184 (0xb8) | Exported Function | 0x5fdd2270 | 0x00052270
`DnsValidateServerArray_A` | 187 (0xbb) | Exported Function | 0x5fdd9f20 | 0x00059f20
`FlushDnsPolicyUnreachableStatus` | 234 (0xea) | Exported Function | 0x5fdb22a0 | 0x000322a0
`GetCurrentTimeInSeconds` | 235 (0xeb) | Exported Function | 0x5fdd2490 | 0x00052490
`HostsFile_Close` | 236 (0xec) | Exported Function | 0x5fd944c0 | 0x000144c0
`NetInfo_IsAddrConfig` | 251 (0xfb) | Exported Function | 0x5fd94950 | 0x00014950
`NetInfo_GetAdapterByName` | 250 (0xfa) | Exported Function | 0x5fdb2800 | 0x00032800
`NetInfo_GetAdapterByInterfaceIndex` | 249 (0xf9) | Exported Function | 0x5fd91370 | 0x00011370
`NetInfo_GetAdapterByAddress` | 248 (0xf8) | Exported Function | 0x5fdd3f70 | 0x00053f70
`NetInfo_Free` | 247 (0xf7) | Exported Function | 0x5fda2140 | 0x00022140
`NetInfo_CreatePerNetworkNetinfo` | 246 (0xf6) | Exported Function | 0x5fd92920 | 0x00012920
`NetInfo_CopyNetworkIndex` | 245 (0xf5) | Exported Function | 0x5fdd3dc0 | 0x00053dc0
`NetInfo_Copy` | 244 (0xf4) | Exported Function | 0x5fd9ec30 | 0x0001ec30
`NetInfo_Clean` | 243 (0xf3) | Exported Function | 0x5fd95750 | 0x00015750
`NetInfo_Build` | 242 (0xf2) | Exported Function | 0x5fda7aa0 | 0x00027aa0
`Local_GetRecordsForLocalNameEx` | 241 (0xf1) | Exported Function | 0x5fdd38a0 | 0x000538a0
`Local_GetRecordsForLocalName` | 240 (0xf0) | Exported Function | 0x5fdd3880 | 0x00053880
`IpHelp_IsAddrOnLink` | 239 (0xef) | Exported Function | 0x5fd90a50 | 0x00010a50
`HostsFile_ReadLine` | 238 (0xee) | Exported Function | 0x5fda4da0 | 0x00024da0
`HostsFile_Open` | 237 (0xed) | Exported Function | 0x5fd93190 | 0x00013190
`DnsNameCompare_W` | 116 (0x74) | Exported Function | 0x5fd90dc0 | 0x00010dc0
`Util_IsRunningOnXboxOne` | 288 (0x120) | Exported Function | 0x5fd93420 | 0x00013420
`DnsNameCompare_UTF8` | 115 (0x73) | Exported Function | 0x5fdd2010 | 0x00052010
`DnsModifyRecordsInSet_W` | 110 (0x6e) | Exported Function | 0x5fdd83f0 | 0x000583f0
`DnsAllocateRecord` | 23 (0x17) | Exported Function | 0x5fdd1da0 | 0x00051da0
`DnsAcquireContextHandle_W` | 22 (0x16) | Exported Function | 0x5fdd8350 | 0x00058350
`DnsAcquireContextHandle_A` | 21 (0x15) | Exported Function | 0x5fdd8310 | 0x00058310
`Dns_WriteRecordStructureToPacketEx` | 231 (0xe7) | Exported Function | 0x5fdd6d90 | 0x00056d90
`Dns_WriteQuestionToMessage` | 230 (0xe6) | Exported Function | 0x5fd9f330 | 0x0001f330
`Dns_WriteDottedNameToPacket` | 12 (0xc) | Exported Function | 0x5fd9f3d0 | 0x0001f3d0
`DnsApiAlloc` | 24 (0x18) | Exported Function | 0x5fd91350 | 0x00011350
`Dns_UpdateLibEx` | 229 (0xe5) | Exported Function | 0x5fddcc70 | 0x0005cc70
`Dns_SkipToRecord` | 227 (0xe3) | Exported Function | 0x5fdd6be0 | 0x00056be0
`Dns_SkipPacketName` | 11 (0xb) | Exported Function | 0x5fda6b60 | 0x00026b60
`Dns_SetRecordsTtl` | 226 (0xe2) | Exported Function | 0x5fdd6bb0 | 0x00056bb0
`Dns_SetRecordsSection` | 225 (0xe1) | Exported Function | 0x5fdd6b80 | 0x00056b80
`Dns_SetRecordDatalength` | 224 (0xe0) | Exported Function | 0x5fdd6b60 | 0x00056b60
`Dns_SendEx` | 223 (0xdf) | Exported Function | 0x5fdd7360 | 0x00057360
`Dns_UpdateLib` | 228 (0xe4) | Exported Function | 0x5fddcc20 | 0x0005cc20
`Dns_SendAndRecvUdp` | 222 (0xde) | Exported Function | 0x5fdd72b0 | 0x000572b0
`DnsApiAllocZero` | 25 (0x19) | Exported Function | 0x5fd91350 | 0x00011350
`DnsApiHeapReset` | 27 (0x1b) | Exported Function | 0x5fdd39e0 | 0x000539e0
`DnsConnectionFreeProxyInfo` | 41 (0x29) | Exported Function | 0x5fde0eb0 | 0x00060eb0
`DnsConnectionFreeNameList` | 40 (0x28) | Exported Function | 0x5fde0e90 | 0x00060e90
`DnsConnectionDeleteProxyInfo` | 39 (0x27) | Exported Function | 0x5fde0e70 | 0x00060e70
`DnsConnectionDeletePolicyEntriesPrivate` | 38 (0x26) | Exported Function | 0x5fdb2e50 | 0x00032e50
`DnsConnectionDeletePolicyEntries` | 37 (0x25) | Exported Function | 0x5fdb2a90 | 0x00032a90
`DnsCleanupTcpConnections` | 36 (0x24) | Exported Function | 0x5fdb8c20 | 0x00038c20
`DnsApiFree` | 26 (0x1a) | Exported Function | 0x5fd91170 | 0x00011170
`DnsCheckNrptRules` | 35 (0x23) | Exported Function | 0x5fdbbc50 | 0x0003bc50
`DnsCancelQuery` | 33 (0x21) | Exported Function | 0x5fdd5e90 | 0x00055e90
`DnsAsyncRegisterTerm` | 32 (0x20) | Exported Function | 0x5fdc54a0 | 0x000454a0
`DnsAsyncRegisterInit` | 31 (0x1f) | Exported Function | 0x5fdd1dd0 | 0x00051dd0
`DnsAsyncRegisterHostAddrs` | 30 (0x1e) | Exported Function | 0x5fdd1dc0 | 0x00051dc0
`DnsApiSetDebugGlobals` | 29 (0x1d) | Exported Function | 0x5fddcbd0 | 0x0005cbd0
`DnsApiRealloc` | 28 (0x1c) | Exported Function | 0x5fdd3a10 | 0x00053a10
`DnsCheckNrptRuleIntegrity` | 34 (0x22) | Exported Function | 0x5fdbb830 | 0x0003b830
`DnsConnectionFreeProxyInfoEx` | 42 (0x2a) | Exported Function | 0x5fd94b30 | 0x00014b30
`Dns_ResetNetworkInfo` | 221 (0xdd) | Exported Function | 0x5fdd3b10 | 0x00053b10
`Dns_ReadRecordStructureFromPacket` | 219 (0xdb) | Exported Function | 0x5fdd6a70 | 0x00056a70
`Dns_CleanupWinsock` | 202 (0xca) | Exported Function | 0x5fdac760 | 0x0002c760
`Dns_CacheServiceStopIssued` | 201 (0xc9) | Exported Function | 0x5fdd1820 | 0x00051820
`Dns_CacheServiceInit` | 200 (0xc8) | Exported Function | 0x5fdb4880 | 0x00034880
`Dns_CacheServiceCleanup` | 199 (0xc7) | Exported Function | 0x5fdd17f0 | 0x000517f0
`Dns_BuildPacket` | 198 (0xc6) | Exported Function | 0x5fd9ef30 | 0x0001ef30
`Dns_AllocateMsgBuf` | 197 (0xc5) | Exported Function | 0x5fdb0d40 | 0x00030d40
`Dns_CloseConnection` | 203 (0xcb) | Exported Function | 0x5fdd23d0 | 0x000523d0
`Dns_AddRecordsToMessage` | 196 (0xc4) | Exported Function | 0x5fdae860 | 0x0002e860
`DelaySortDAServerlist` | 20 (0x14) | Exported Function | 0x5fdb22f0 | 0x000322f0
`CombineRecordsInBlob` | 18 (0x12) | Exported Function | 0x5fdd5ce0 | 0x00055ce0
`Coalesce_UpdateNetVersion` | 17 (0x11) | Exported Function | 0x5fdb2960 | 0x00032960
`BreakRecordsIntoBlob` | 16 (0x10) | Exported Function | 0x5fdd5be0 | 0x00055be0
`AddRefQueryBlobEx` | 15 (0xf) | Exported Function | 0x5fdab520 | 0x0002b520
`AdaptiveTimeout_ResetAdaptiveTimeout` | 14 (0xe) | Exported Function | 0x5fd94210 | 0x00014210
`DeRefQueryBlobEx` | 19 (0x13) | Exported Function | 0x5fd9ac90 | 0x0001ac90
`Dns_RecvTcp` | 220 (0xdc) | Exported Function | 0x5fdb0960 | 0x00030960
`Dns_CloseSocket` | 204 (0xcc) | Exported Function | 0x5fdd23f0 | 0x000523f0
`Dns_CreateSocket` | 206 (0xce) | Exported Function | 0x5fdd2410 | 0x00052410
`Dns_ReadPacketNameAllocate` | 10 (0xa) | Exported Function | 0x5fdd64e0 | 0x000564e0
`Dns_ReadPacketName` | 9 (0x9) | Exported Function | 0x5fda4c10 | 0x00024c10
`Dns_PingAdapterServers` | 218 (0xda) | Exported Function | 0x5fddcc60 | 0x0005cc60
`Dns_ParsePacketRecord` | 217 (0xd9) | Exported Function | 0x5fdd6a20 | 0x00056a20
`Dns_ParseMessage` | 216 (0xd8) | Exported Function | 0x5fda4260 | 0x00024260
`Dns_OpenTcpConnectionAndSend` | 215 (0xd7) | Exported Function | 0x5fdd7260 | 0x00057260
`Dns_CreateMulticastSocket` | 205 (0xcd) | Exported Function | 0x5fddcc30 | 0x0005cc30
`Dns_InitializeWinsock` | 214 (0xd6) | Exported Function | 0x5fddcc50 | 0x0005cc50
`Dns_InitializeMsgBuf` | 212 (0xd4) | Exported Function | 0x5fd9f260 | 0x0001f260
`Dns_GetRandomXid` | 211 (0xd3) | Exported Function | 0x5fdd6950 | 0x00056950
`Dns_FreeMsgBuf` | 210 (0xd2) | Exported Function | 0x5fdb1680 | 0x00031680
`Dns_FindAuthoritativeZoneLib` | 209 (0xd1) | Exported Function | 0x5fddcc40 | 0x0005cc40
`Dns_ExtractRecordsFromMessage` | 208 (0xd0) | Exported Function | 0x5fda3e60 | 0x00023e60
`Dns_CreateSocketEx` | 207 (0xcf) | Exported Function | 0x5fdd2430 | 0x00052430
`Dns_InitializeMsgRemoteSockaddr` | 213 (0xd5) | Exported Function | 0x5fdd7210 | 0x00057210
`DnsConnectionFreeProxyList` | 43 (0x2b) | Exported Function | 0x5fde0ed0 | 0x00060ed0
`DnsConnectionGetHandleForHostUrlPrivate` | 44 (0x2c) | Exported Function | 0x5fde0ef0 | 0x00060ef0
`DnsConnectionGetNameList` | 45 (0x2d) | Exported Function | 0x5fde0f90 | 0x00060f90
`DnsGetNrptRuleNamesList` | 95 (0x5f) | Exported Function | 0x5fdbbe70 | 0x0003be70
`DnsGetLastFailedUpdateInfo` | 94 (0x5e) | Exported Function | 0x5fddcbf0 | 0x0005cbf0
`DnsGetInterfaceSettings` | 93 (0x5d) | Exported Function | 0x5fdb5810 | 0x00035810
`DnsGetDomainName` | 1 (0x1) | Exported Function | 0x5fdd1c90 | 0x00051c90
`DnsGetDnsServerList` | 92 (0x5c) | Exported Function | 0x5fdd1ef0 | 0x00051ef0
`DnsGetCacheDataTableEx` | 91 (0x5b) | Exported Function | 0x5fdb5660 | 0x00035660
`DnsGetPolicyTableInfo` | 96 (0x60) | Exported Function | 0x5fdd19e0 | 0x000519e0
`DnsGetCacheDataTable` | 90 (0x5a) | Exported Function | 0x5fdd19b0 | 0x000519b0
`DnsGetApplicationIdentifier` | 88 (0x58) | Exported Function | 0x5fd96b90 | 0x00016b90
`DnsGetAdaptersInfo` | 87 (0x57) | Exported Function | 0x5fdb54b0 | 0x000354b0
`DnsFreeProxyName` | 86 (0x56) | Exported Function | 0x5fdd1990 | 0x00051990
`DnsFreePolicyConfig` | 85 (0x55) | Exported Function | 0x5fdd18e0 | 0x000518e0
`DnsFreeNrptRuleNamesList` | 84 (0x54) | Exported Function | 0x5fdbbe30 | 0x0003be30
`DnsFreeNrptRule` | 83 (0x53) | Exported Function | 0x5fdbbd60 | 0x0003bd60
`DnsGetBufferLengthForStringCopy` | 89 (0x59) | Exported Function | 0x5fdd1ec0 | 0x00051ec0
`DnsFreeConfigStructure` | 82 (0x52) | Exported Function | 0x5fdcf910 | 0x0004f910
`DnsGetPolicyTableInfoPrivate` | 97 (0x61) | Exported Function | 0x5fdb1ec0 | 0x00031ec0
`DnsGetProxyInfoPrivate` | 99 (0x63) | Exported Function | 0x5fd92480 | 0x00012480
`DnsModifyRecordsInSet_UTF8` | 109 (0x6d) | Exported Function | 0x5fdd83c0 | 0x000583c0
`DnsModifyRecordsInSet_A` | 108 (0x6c) | Exported Function | 0x5fdd8390 | 0x00058390
`DnsMapRcodeToStatus` | 5 (0x5) | Exported Function | 0x5fdd1d10 | 0x00051d10
`DnsLogEvent` | 107 (0x6b) | Exported Function | 0x5fdd79c0 | 0x000579c0
`DnsIsStringCountValidForTextType` | 106 (0x6a) | Exported Function | 0x5fdd1f70 | 0x00051f70
`DnsIsStatusRcode` | 4 (0x4) | Exported Function | 0x5fdd1d00 | 0x00051d00
`DnsGetPrimaryDomainName_A` | 98 (0x62) | Exported Function | 0x5fdd1f10 | 0x00051f10
`DnsIsNSECType` | 3 (0x3) | Exported Function | 0x5fdd1ce0 | 0x00051ce0
`DnsIpv6StringToAddress` | 105 (0x69) | Exported Function | 0x5fdd1f50 | 0x00051f50
`DnsIpv6AddressToString` | 104 (0x68) | Exported Function | 0x5fdd1f30 | 0x00051f30
`DnsGlobals` | 103 (0x67) | Exported Function | 0x5fdfd5e0 | 0x0007d5e0
`DnsGetSettings` | 102 (0x66) | Exported Function | 0x5fdb5c40 | 0x00035c40
`DnsGetQueryRetryTimeouts` | 101 (0x65) | Exported Function | 0x5fdb4670 | 0x00034670
`DnsGetProxyInformation` | 100 (0x64) | Exported Function | 0x5fd92210 | 0x00012210
`DnsIsAMailboxType` | 2 (0x2) | Exported Function | 0x5fdd1cc0 | 0x00051cc0
`DnsFreeAdaptersInfo` | 81 (0x51) | Exported Function | 0x5fdb5440 | 0x00035440
`DnsFree` | 80 (0x50) | Exported Function | 0x5fda1de0 | 0x00021de0
`DnsFlushResolverCacheEntry_W` | 79 (0x4f) | Exported Function | 0x5fdad230 | 0x0002d230
`DnsDhcpRegisterHostAddrs` | 59 (0x3b) | Exported Function | 0x5fdcf9f0 | 0x0004f9f0
`DnsDhcpRegisterAddrs` | 58 (0x3a) | Exported Function | 0x5fdb2550 | 0x00032550
`DnsDeRegisterLocal` | 57 (0x39) | Exported Function | 0x5fddfc20 | 0x0005fc20
`DnsCreateStringCopy` | 56 (0x38) | Exported Function | 0x5fdd1e60 | 0x00051e60
`DnsCreateStandardDnsNameCopy` | 55 (0x37) | Exported Function | 0x5fdd1e40 | 0x00051e40
`DnsCreateReverseNameStringForIpAddress` | 54 (0x36) | Exported Function | 0x5fdd1e20 | 0x00051e20
`DnsDhcpRegisterInit` | 60 (0x3c) | Exported Function | 0x5fdb4ab0 | 0x00034ab0
`DnsCopyStringEx` | 53 (0x35) | Exported Function | 0x5fdd1de0 | 0x00051de0
`DnsConnectionSetProxyInfo` | 51 (0x33) | Exported Function | 0x5fde0ff0 | 0x00060ff0
`DnsConnectionSetPolicyEntriesPrivate` | 50 (0x32) | Exported Function | 0x5fdb4390 | 0x00034390
`DnsConnectionSetPolicyEntries` | 49 (0x31) | Exported Function | 0x5fdb4120 | 0x00034120
`DnsConnectionGetProxyList` | 48 (0x30) | Exported Function | 0x5fde0fd0 | 0x00060fd0
`DnsConnectionGetProxyInfoForHostUrl` | 47 (0x2f) | Exported Function | 0x5fd959e0 | 0x000159e0
`DnsConnectionGetProxyInfo` | 46 (0x2e) | Exported Function | 0x5fde0fb0 | 0x00060fb0
`DnsConnectionUpdateIfIndexTable` | 52 (0x34) | Exported Function | 0x5fdad4a0 | 0x0002d4a0
`DnsDhcpRegisterTerm` | 61 (0x3d) | Exported Function | 0x5fdc54a0 | 0x000454a0
`DnsDhcpRemoveRegistrations` | 62 (0x3e) | Exported Function | 0x5fdcfa70 | 0x0004fa70
`DnsDhcpSrvRegisterHostAddr` | 63 (0x3f) | Exported Function | 0x5fdd0380 | 0x00050380
`DnsFlushResolverCacheEntry_UTF8` | 78 (0x4e) | Exported Function | 0x5fdd7170 | 0x00057170
`DnsFlushResolverCacheEntry_A` | 77 (0x4d) | Exported Function | 0x5fdd7150 | 0x00057150
`DnsFlushResolverCache` | 76 (0x4c) | Exported Function | 0x5fd90c80 | 0x00010c80
`DnsFindAuthoritativeZone` | 75 (0x4b) | Exported Function | 0x5fdd4640 | 0x00054640
`DnsExtractRecordsFromMessage_W` | 74 (0x4a) | Exported Function | 0x5fdd66c0 | 0x000566c0
`DnsExtractRecordsFromMessage_UTF8` | 73 (0x49) | Exported Function | 0x5fdd66a0 | 0x000566a0
`DnsDowncaseDnsNameLabel` | 72 (0x48) | Exported Function | 0x5fdd1ea0 | 0x00051ea0
`DnsDisableIdnEncoding` | 71 (0x47) | Exported Function | 0x5fdda760 | 0x0005a760
`DnsDhcpSrvRegisterTerm` | 70 (0x46) | Exported Function | 0x5fdd0740 | 0x00050740
`DnsDhcpSrvRegisterInitialize` | 69 (0x45) | Exported Function | 0x5fdd1e80 | 0x00051e80
`DnsDhcpSrvRegisterInitEx` | 68 (0x44) | Exported Function | 0x5fdd0710 | 0x00050710
`DnsDhcpSrvRegisterInit` | 67 (0x43) | Exported Function | 0x5fdd0580 | 0x00050580
`DnsDhcpSrvRegisterHostNameEx` | 66 (0x42) | Exported Function | 0x5fdd0480 | 0x00050480
`DnsDhcpSrvRegisterHostName` | 65 (0x41) | Exported Function | 0x5fdd0440 | 0x00050440
`DnsDhcpSrvRegisterHostAddrEx` | 64 (0x40) | Exported Function | 0x5fdd03f0 | 0x000503f0
`DnsNameCompare_A` | 114 (0x72) | Exported Function | 0x5fdd1ff0 | 0x00051ff0
`WriteDnsNrptRulesToRegistry` | 289 (0x121) | Exported Function | 0x5fdbd340 | 0x0003d340


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dnsapi
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.508 (WinBuild.160101.0800)
* Product Version: 10.0.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/64
* VirusTotal Link: https://www.virustotal.com/gui/file/1df0241421ab302c3086da54d6eb100b0cd155426bf640c3f0ce8620f79b6d19/detection/


## Possible Misuse

*The following table contains possible examples of `dnsapi.dll` being misused. While `dnsapi.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [proxy_download_susp_dyndns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/proxy/proxy_download_susp_dyndns.yml) | `- '*.dnsapi.info'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`dnsapi.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `dnsapi.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `api-ms-win-samcli-dnsapi-0-0-0.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s1 = "DnsApi.dll" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


