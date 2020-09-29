---
title: dnsapi.dll | DNS Client API DLL
excerpt: What is dnsapi.dll?
---

# dnsapi.dll 

* File Path: `C:\Windows\system32\dnsapi.dll`
* Description: DNS Client API DLL

## Hashes

Type | Hash
-- | --
MD5 | `403BAB9BFBDD33E52451F59FE02629C1`
SHA1 | `8EBE44527723C6773619AE7E7EE150835C3A7D26`
SHA256 | `26B49242879CABD209A5B314A196672FE25E22CA5288C03AA0944D6F235810D5`
SHA384 | `021D516FCD70E9341AE659B3E6A5F5C9BCB79075837B35B7FC19A1A186E1B4A3B951397E75797EB7F36936A141144037`
SHA512 | `90097BD49DD2AAFF99329E42406E47A76CB6F167913B6DF002769CDFD0CB854F6A12B23777C3AE57684CBA9E5C37ACFBC3B43E279581B6F30152B272B575EC11`
SSDEEP | `12288:hvpnIz4jtuv1I4/GZnd15nxthWo2Kkc4oZyOB6jHOEWzWnoGJSG9aM/wXaCxzfNk:FoI4/Kd15rhWoT4oMK6L1noGJbwLBVk`
IMP | `774A00D28C195928DB9DA4B638C79D07`
PESHA1 | `1824CABAAA1F38E6E78CA149A7CCD2497F06AE87`
PE256 | `0AD8365D46901866FBDEE0A384703EC650CD3B6795670EB6ABE1B4E066598800`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AdaptiveTimeout_ClearInterfaceSpecificConfiguration` | 1 (0x1) | Exported Function | 0x0000000180001370 | 0x00001370
`DnsServiceRegister` | 156 (0x9c) | Exported Function | 0x000000018006a0b0 | 0x0006a0b0
`DnsServiceFreeInstance` | 155 (0x9b) | Exported Function | 0x000000018006a010 | 0x0006a010
`DnsServiceDeRegister` | 154 (0x9a) | Exported Function | 0x0000000180069ef0 | 0x00069ef0
`DnsServiceCopyInstance` | 153 (0x99) | Exported Function | 0x0000000180069e90 | 0x00069e90
`DnsServiceConstructInstance` | 152 (0x98) | Exported Function | 0x0000000180069a40 | 0x00069a40
`DnsServiceBrowseCancel` | 151 (0x97) | Exported Function | 0x0000000180069990 | 0x00069990
`DnsServiceRegisterCancel` | 157 (0x9d) | Exported Function | 0x000000018006a290 | 0x0006a290
`DnsServiceBrowse` | 150 (0x96) | Exported Function | 0x00000001800696e0 | 0x000696e0
`DnsResolverQueryHvsi` | 148 (0x94) | Exported Function | 0x0000000180055310 | 0x00055310
`DnsResolverOp` | 147 (0x93) | Exported Function | 0x0000000180028ae0 | 0x00028ae0
`DnsResetQueryRetryTimeouts` | 146 (0x92) | Exported Function | 0x000000018004e620 | 0x0004e620
`DnsReplaceRecordSetW` | 145 (0x91) | Exported Function | 0x000000018005c280 | 0x0005c280
`DnsReplaceRecordSetUTF8` | 144 (0x90) | Exported Function | 0x000000018005c250 | 0x0005c250
`DnsReplaceRecordSetA` | 143 (0x8f) | Exported Function | 0x000000018005c220 | 0x0005c220
`DnsScreenLocalAddrsForRegistration` | 149 (0x95) | Exported Function | 0x00000001800510d0 | 0x000510d0
`DnsRemoveRegistrations` | 142 (0x8e) | Exported Function | 0x000000018004f1a0 | 0x0004f1a0
`DnsServiceResolve` | 158 (0x9e) | Exported Function | 0x000000018006a340 | 0x0006a340
`DnsSetConfigDword` | 160 (0xa0) | Exported Function | 0x000000018004b3f0 | 0x0004b3f0
`DnsUpdateMachinePresence` | 174 (0xae) | Exported Function | 0x0000000180025fa0 | 0x00025fa0
`DnsUpdate` | 173 (0xad) | Exported Function | 0x0000000180066690 | 0x00066690
`DnsUnicodeToUtf8` | 172 (0xac) | Exported Function | 0x000000018004f210 | 0x0004f210
`DnsTraceServerConfig` | 171 (0xab) | Exported Function | 0x0000000180020240 | 0x00020240
`DnsStringCopyAllocateEx` | 170 (0xaa) | Exported Function | 0x000000018004f1f0 | 0x0004f1f0
`DnsStopMulticastQuery` | 169 (0xa9) | Exported Function | 0x00000001800066d0 | 0x000066d0
`DnsServiceResolveCancel` | 159 (0x9f) | Exported Function | 0x000000018006a410 | 0x0006a410
`DnsStatusString` | 168 (0xa8) | Exported Function | 0x000000018004f1b0 | 0x0004f1b0
`DnsSetSettings` | 166 (0xa6) | Exported Function | 0x000000018004eba0 | 0x0004eba0
`DnsSetQueryRetryTimeouts` | 165 (0xa5) | Exported Function | 0x000000018004ea40 | 0x0004ea40
`DnsSetNrptRules` | 164 (0xa4) | Exported Function | 0x0000000180060cb0 | 0x00060cb0
`DnsSetNrptRule` | 163 (0xa3) | Exported Function | 0x0000000180060c60 | 0x00060c60
`DnsSetInterfaceSettings` | 162 (0xa2) | Exported Function | 0x000000018004e6c0 | 0x0004e6c0
`DnsSetConfigValue` | 161 (0xa1) | Exported Function | 0x000000018004b440 | 0x0004b440
`DnsStartMulticastQuery` | 167 (0xa7) | Exported Function | 0x0000000180006090 | 0x00006090
`DnsUpdateTest_A` | 175 (0xaf) | Exported Function | 0x000000018005c2b0 | 0x0005c2b0
`DnsRemoveNrptRule` | 141 (0x8d) | Exported Function | 0x0000000180060930 | 0x00060930
`DnsRegisterLocal` | 139 (0x8b) | Exported Function | 0x000000018006aab0 | 0x0006aab0
`DnsQueryConfig` | 117 (0x75) | Exported Function | 0x000000018001e940 | 0x0001e940
`DnsQuery_W` | 126 (0x7e) | Exported Function | 0x0000000180007a70 | 0x00007a70
`DnsQuery_UTF8` | 125 (0x7d) | Exported Function | 0x00000001800238a0 | 0x000238a0
`DnsQuery_A` | 124 (0x7c) | Exported Function | 0x00000001800552b0 | 0x000552b0
`DnsNotifyResolverEx` | 116 (0x74) | Exported Function | 0x0000000180028a90 | 0x00028a90
`DnsNotifyResolverClusterIp` | 115 (0x73) | Exported Function | 0x0000000180066680 | 0x00066680
`DnsQueryConfigAllocEx` | 118 (0x76) | Exported Function | 0x000000018001e890 | 0x0001e890
`DnsNotifyResolver` | 114 (0x72) | Exported Function | 0x00000001800285c0 | 0x000285c0
`DnsNetworkInfo_CreateFromFAZ` | 112 (0x70) | Exported Function | 0x0000000180052a00 | 0x00052a00
`DnsNameCopyAllocate` | 111 (0x6f) | Exported Function | 0x000000018004f010 | 0x0004f010
`DnsNameCopy` | 110 (0x6e) | Exported Function | 0x000000018004f000 | 0x0004f000
`DnsNameCompareEx_W` | 106 (0x6a) | Exported Function | 0x000000018004efc0 | 0x0004efc0
`DnsNameCompareEx_UTF8` | 105 (0x69) | Exported Function | 0x000000018004efa0 | 0x0004efa0
`DnsNameCompareEx_A` | 104 (0x68) | Exported Function | 0x000000018004ef80 | 0x0004ef80
`DnsNetworkInformation_CreateFromFAZ` | 113 (0x71) | Exported Function | 0x0000000180052cf0 | 0x00052cf0
`DnsReleaseContextHandle` | 140 (0x8c) | Exported Function | 0x000000018005c1d0 | 0x0005c1d0
`DnsQueryConfigDword` | 119 (0x77) | Exported Function | 0x0000000180027710 | 0x00027710
`DnsQueryExA` | 121 (0x79) | Exported Function | 0x00000001800551a0 | 0x000551a0
`DnsRecordTypeForName` | 138 (0x8a) | Exported Function | 0x000000018004f190 | 0x0004f190
`DnsRecordStringForWritableType` | 137 (0x89) | Exported Function | 0x000000018004f150 | 0x0004f150
`DnsRecordStringForType` | 136 (0x88) | Exported Function | 0x000000018004f120 | 0x0004f120
`DnsRecordSetDetach` | 135 (0x87) | Exported Function | 0x000000018004f110 | 0x0004f110
`DnsRecordSetCopyEx` | 134 (0x86) | Exported Function | 0x000000018004f0f0 | 0x0004f0f0
`DnsRecordSetCompare` | 133 (0x85) | Exported Function | 0x000000018004f0d0 | 0x0004f0d0
`DnsQueryEx` | 120 (0x78) | Exported Function | 0x000000018000b300 | 0x0000b300
`DnsRecordListUnmapV4MappedAAAAInPlace` | 132 (0x84) | Exported Function | 0x00000001800296d0 | 0x000296d0
`DnsRecordCopyEx` | 130 (0x82) | Exported Function | 0x000000018004f050 | 0x0004f050
`DnsRecordCompare` | 129 (0x81) | Exported Function | 0x000000018004f040 | 0x0004f040
`DnsRecordBuild_W` | 128 (0x80) | Exported Function | 0x000000018004f030 | 0x0004f030
`DnsRecordBuild_UTF8` | 127 (0x7f) | Exported Function | 0x000000018004f020 | 0x0004f020
`DnsQueryExW` | 123 (0x7b) | Exported Function | 0x0000000180055240 | 0x00055240
`DnsQueryExUTF8` | 122 (0x7a) | Exported Function | 0x00000001800551f0 | 0x000551f0
`DnsRecordListFree` | 131 (0x83) | Exported Function | 0x000000018004f060 | 0x0004f060
`DnsUpdateTest_UTF8` | 176 (0xb0) | Exported Function | 0x000000018005c360 | 0x0005c360
`DnsUpdateTest_W` | 177 (0xb1) | Exported Function | 0x000000018005c410 | 0x0005c410
`DnsUtf8ToUnicode` | 178 (0xb2) | Exported Function | 0x000000018004f220 | 0x0004f220
`Send_OpenTcpConnectionAndSend` | 269 (0x10d) | Exported Function | 0x0000000180058310 | 0x00058310
`Send_MessagePrivateEx` | 268 (0x10c) | Exported Function | 0x00000001800134c0 | 0x000134c0
`Send_MessagePrivate` | 267 (0x10b) | Exported Function | 0x0000000180058300 | 0x00058300
`Send_AndRecvUdpWithParam` | 266 (0x10a) | Exported Function | 0x0000000180010580 | 0x00010580
`Security_ContextListTimeout` | 265 (0x109) | Exported Function | 0x000000018004f4b0 | 0x0004f4b0
`Reg_ReadUpdateInfo` | 264 (0x108) | Exported Function | 0x0000000180023560 | 0x00023560
`Socket_CacheCleanup` | 270 (0x10e) | Exported Function | 0x0000000180066680 | 0x00066680
`Reg_ReadGlobalsEx` | 263 (0x107) | Exported Function | 0x000000018000c3f0 | 0x0000c3f0
`Reg_FreeUpdateInfo` | 261 (0x105) | Exported Function | 0x00000001800239c0 | 0x000239c0
`QueryDirectEx` | 258 (0x102) | Exported Function | 0x0000000180053ba0 | 0x00053ba0
`Query_Main` | 260 (0x104) | Exported Function | 0x00000001800085a0 | 0x000085a0
`Query_Cancel` | 259 (0x103) | Exported Function | 0x0000000180053da0 | 0x00053da0
`NetInfo_UpdateServerReachability` | 257 (0x101) | Exported Function | 0x00000001800282c0 | 0x000282c0
`NetInfo_UpdateNetworkProperties` | 256 (0x100) | Exported Function | 0x0000000180028730 | 0x00028730
`Reg_GetValueEx` | 262 (0x106) | Exported Function | 0x0000000180019210 | 0x00019210
`NetInfo_UpdateDnsInterfaceConfigChange` | 255 (0xff) | Exported Function | 0x0000000180052220 | 0x00052220
`Socket_CacheInit` | 271 (0x10f) | Exported Function | 0x0000000180020aa0 | 0x00020aa0
`Socket_ClearMessageSockets` | 273 (0x111) | Exported Function | 0x00000001800589a0 | 0x000589a0
`Util_IsIp6Running` | 287 (0x11f) | Exported Function | 0x000000018005e2b0 | 0x0005e2b0
`Update_ReplaceAddressRecordsW` | 286 (0x11e) | Exported Function | 0x000000018005d060 | 0x0005d060
`Trace_Reset` | 285 (0x11d) | Exported Function | 0x00000001800296c0 | 0x000296c0
`Socket_TcpListen` | 284 (0x11c) | Exported Function | 0x0000000180058a40 | 0x00058a40
`Socket_SetTtl` | 283 (0x11b) | Exported Function | 0x0000000180027b50 | 0x00027b50
`Socket_SetMulticastLoopBack` | 282 (0x11a) | Exported Function | 0x0000000180028520 | 0x00028520
`Socket_CleanupWinsock` | 272 (0x110) | Exported Function | 0x0000000180066680 | 0x00066680
`Socket_SetMulticastInterface` | 281 (0x119) | Exported Function | 0x0000000180015da0 | 0x00015da0
`Socket_JoinMulticast` | 279 (0x117) | Exported Function | 0x00000001800278f0 | 0x000278f0
`Socket_InitWinsock` | 278 (0x116) | Exported Function | 0x00000001800666b0 | 0x000666b0
`Socket_CreateMulticast` | 277 (0x115) | Exported Function | 0x00000001800666c0 | 0x000666c0
`Socket_Create` | 276 (0x114) | Exported Function | 0x0000000180028e00 | 0x00028e00
`Socket_CloseMessageSockets` | 275 (0x113) | Exported Function | 0x00000001800589c0 | 0x000589c0
`Socket_CloseEx` | 274 (0x112) | Exported Function | 0x0000000180028100 | 0x00028100
`Socket_RecvFrom` | 280 (0x118) | Exported Function | 0x000000018001d7c0 | 0x0001d7c0
`NetInfo_ResetServerPriorities` | 254 (0xfe) | Exported Function | 0x00000001800024d0 | 0x000024d0
`NetInfo_IsTcpipConfigChange` | 253 (0xfd) | Exported Function | 0x0000000180023450 | 0x00023450
`NetInfo_IsForUpdate` | 252 (0xfc) | Exported Function | 0x00000001800532d0 | 0x000532d0
`ExtraInfo_Init` | 232 (0xe8) | Exported Function | 0x000000018005e030 | 0x0005e030
`DnsWriteReverseNameStringForIpAddress` | 191 (0xbf) | Exported Function | 0x000000018004f3c0 | 0x0004f3c0
`DnsWriteQuestionToBuffer_W` | 190 (0xbe) | Exported Function | 0x0000000180055fd0 | 0x00055fd0
`DnsWriteQuestionToBuffer_UTF8` | 189 (0xbd) | Exported Function | 0x0000000180055ee0 | 0x00055ee0
`DnsValidateUtf8Byte` | 188 (0xbc) | Exported Function | 0x000000018004f3b0 | 0x0004f3b0
`DnsValidateServerStatus` | 185 (0xb9) | Exported Function | 0x000000018005e510 | 0x0005e510
`Faz_AreServerListsInSameNameSpace` | 233 (0xe9) | Exported Function | 0x000000018004f4c0 | 0x0004f4c0
`DnsValidateServerArray_W` | 184 (0xb8) | Exported Function | 0x000000018005e4a0 | 0x0005e4a0
`DnsValidateServer_W` | 187 (0xbb) | Exported Function | 0x000000018005e6a0 | 0x0005e6a0
`DnsValidateServer_A` | 186 (0xba) | Exported Function | 0x000000018005e5c0 | 0x0005e5c0
`DnsValidateNameOrIp_TempW` | 179 (0xb3) | Exported Function | 0x0000000180051850 | 0x00051850
`DnsValidateName_W` | 182 (0xb6) | Exported Function | 0x0000000180028c40 | 0x00028c40
`DnsValidateName_UTF8` | 181 (0xb5) | Exported Function | 0x000000018004f300 | 0x0004f300
`DnsValidateName_A` | 180 (0xb4) | Exported Function | 0x000000018004f260 | 0x0004f260
`DnsValidateServerArray_A` | 183 (0xb7) | Exported Function | 0x000000018005e3c0 | 0x0005e3c0
`FlushDnsPolicyUnreachableStatus` | 234 (0xea) | Exported Function | 0x0000000180028be0 | 0x00028be0
`GetCurrentTimeInSeconds` | 235 (0xeb) | Exported Function | 0x000000018002b410 | 0x0002b410
`HostsFile_Close` | 236 (0xec) | Exported Function | 0x000000018002bca0 | 0x0002bca0
`NetInfo_IsAddrConfig` | 251 (0xfb) | Exported Function | 0x000000018001e570 | 0x0001e570
`NetInfo_GetAdapterByName` | 250 (0xfa) | Exported Function | 0x0000000180023900 | 0x00023900
`NetInfo_GetAdapterByInterfaceIndex` | 249 (0xf9) | Exported Function | 0x000000018001da80 | 0x0001da80
`NetInfo_GetAdapterByAddress` | 248 (0xf8) | Exported Function | 0x0000000180051fd0 | 0x00051fd0
`NetInfo_Free` | 247 (0xf7) | Exported Function | 0x0000000180017be0 | 0x00017be0
`NetInfo_CreatePerNetworkNetinfo` | 246 (0xf6) | Exported Function | 0x000000018001c6e0 | 0x0001c6e0
`NetInfo_CopyNetworkIndex` | 245 (0xf5) | Exported Function | 0x0000000180051d80 | 0x00051d80
`NetInfo_Copy` | 244 (0xf4) | Exported Function | 0x000000018001ca30 | 0x0001ca30
`NetInfo_Clean` | 243 (0xf3) | Exported Function | 0x0000000180003c50 | 0x00003c50
`NetInfo_Build` | 242 (0xf2) | Exported Function | 0x0000000180017190 | 0x00017190
`Local_GetRecordsForLocalNameEx` | 241 (0xf1) | Exported Function | 0x0000000180051360 | 0x00051360
`Local_GetRecordsForLocalName` | 240 (0xf0) | Exported Function | 0x0000000180051340 | 0x00051340
`IpHelp_IsAddrOnLink` | 239 (0xef) | Exported Function | 0x0000000180050ec0 | 0x00050ec0
`HostsFile_ReadLine` | 238 (0xee) | Exported Function | 0x000000018002afb0 | 0x0002afb0
`HostsFile_Open` | 237 (0xed) | Exported Function | 0x000000018002b720 | 0x0002b720
`DnsNameCompare_W` | 109 (0x6d) | Exported Function | 0x000000018001d9c0 | 0x0001d9c0
`Util_IsRunningOnXboxOne` | 288 (0x120) | Exported Function | 0x000000018002b990 | 0x0002b990
`DnsNameCompare_UTF8` | 108 (0x6c) | Exported Function | 0x000000018004eff0 | 0x0004eff0
`DnsModifyRecordsInSet_W` | 103 (0x67) | Exported Function | 0x000000018005c180 | 0x0005c180
`DnsAllocateRecord` | 11 (0xb) | Exported Function | 0x000000018004ed60 | 0x0004ed60
`DnsAcquireContextHandle_W` | 10 (0xa) | Exported Function | 0x000000018005c0a0 | 0x0005c0a0
`DnsAcquireContextHandle_A` | 9 (0x9) | Exported Function | 0x000000018005c060 | 0x0005c060
`Dns_WriteRecordStructureToPacketEx` | 231 (0xe7) | Exported Function | 0x0000000180056b70 | 0x00056b70
`Dns_WriteQuestionToMessage` | 230 (0xe6) | Exported Function | 0x0000000180056980 | 0x00056980
`Dns_WriteDottedNameToPacket` | 229 (0xe5) | Exported Function | 0x000000018000fbe0 | 0x0000fbe0
`DnsApiAlloc` | 12 (0xc) | Exported Function | 0x000000018001deb0 | 0x0001deb0
`Dns_UpdateLibEx` | 228 (0xe4) | Exported Function | 0x0000000180066690 | 0x00066690
`Dns_SkipToRecord` | 226 (0xe2) | Exported Function | 0x00000001800567e0 | 0x000567e0
`Dns_SkipPacketName` | 225 (0xe1) | Exported Function | 0x0000000180004eb0 | 0x00004eb0
`Dns_SetRecordsTtl` | 224 (0xe0) | Exported Function | 0x00000001800567c0 | 0x000567c0
`Dns_SetRecordsSection` | 223 (0xdf) | Exported Function | 0x0000000180056790 | 0x00056790
`Dns_SetRecordDatalength` | 222 (0xde) | Exported Function | 0x0000000180056780 | 0x00056780
`Dns_SendEx` | 221 (0xdd) | Exported Function | 0x0000000180057b50 | 0x00057b50
`Dns_UpdateLib` | 227 (0xe3) | Exported Function | 0x0000000180066690 | 0x00066690
`Dns_SendAndRecvUdp` | 220 (0xdc) | Exported Function | 0x0000000180057a90 | 0x00057a90
`DnsApiAllocZero` | 13 (0xd) | Exported Function | 0x00000001800517b0 | 0x000517b0
`DnsApiHeapReset` | 15 (0xf) | Exported Function | 0x00000001800517c0 | 0x000517c0
`DnsConnectionFreeProxyInfo` | 29 (0x1d) | Exported Function | 0x000000018006c830 | 0x0006c830
`DnsConnectionFreeNameList` | 28 (0x1c) | Exported Function | 0x000000018006c7b0 | 0x0006c7b0
`DnsConnectionDeleteProxyInfo` | 27 (0x1b) | Exported Function | 0x000000018006c7a0 | 0x0006c7a0
`DnsConnectionDeletePolicyEntriesPrivate` | 26 (0x1a) | Exported Function | 0x000000018002a990 | 0x0002a990
`DnsConnectionDeletePolicyEntries` | 25 (0x19) | Exported Function | 0x000000018002ac80 | 0x0002ac80
`DnsCleanupTcpConnections` | 24 (0x18) | Exported Function | 0x0000000180020770 | 0x00020770
`DnsApiFree` | 14 (0xe) | Exported Function | 0x0000000180017ed0 | 0x00017ed0
`DnsCheckNrptRules` | 23 (0x17) | Exported Function | 0x000000018005f950 | 0x0005f950
`DnsCancelQuery` | 21 (0x15) | Exported Function | 0x0000000180054fc0 | 0x00054fc0
`DnsAsyncRegisterTerm` | 20 (0x14) | Exported Function | 0x0000000180020aa0 | 0x00020aa0
`DnsAsyncRegisterInit` | 19 (0x13) | Exported Function | 0x000000018004ed80 | 0x0004ed80
`DnsAsyncRegisterHostAddrs` | 18 (0x12) | Exported Function | 0x000000018004ed70 | 0x0004ed70
`DnsApiSetDebugGlobals` | 17 (0x11) | Exported Function | 0x0000000180066650 | 0x00066650
`DnsApiRealloc` | 16 (0x10) | Exported Function | 0x00000001800517e0 | 0x000517e0
`DnsCheckNrptRuleIntegrity` | 22 (0x16) | Exported Function | 0x000000018005f4e0 | 0x0005f4e0
`DnsConnectionFreeProxyInfoEx` | 30 (0x1e) | Exported Function | 0x0000000180015bd0 | 0x00015bd0
`Dns_ResetNetworkInfo` | 219 (0xdb) | Exported Function | 0x0000000180051a20 | 0x00051a20
`Dns_ReadRecordStructureFromPacket` | 217 (0xd9) | Exported Function | 0x0000000180056650 | 0x00056650
`Dns_CleanupWinsock` | 198 (0xc6) | Exported Function | 0x0000000180066680 | 0x00066680
`Dns_CacheServiceStopIssued` | 197 (0xc5) | Exported Function | 0x000000018004db90 | 0x0004db90
`Dns_CacheServiceInit` | 196 (0xc4) | Exported Function | 0x000000018002bab0 | 0x0002bab0
`Dns_CacheServiceCleanup` | 195 (0xc3) | Exported Function | 0x000000018004db50 | 0x0004db50
`Dns_BuildPacket` | 194 (0xc2) | Exported Function | 0x000000018000f840 | 0x0000f840
`Dns_AllocateMsgBuf` | 193 (0xc1) | Exported Function | 0x00000001800279f0 | 0x000279f0
`Dns_CloseConnection` | 199 (0xc7) | Exported Function | 0x000000018004f3d0 | 0x0004f3d0
`Dns_AddRecordsToMessage` | 192 (0xc0) | Exported Function | 0x0000000180027000 | 0x00027000
`DelaySortDAServerlist` | 8 (0x8) | Exported Function | 0x0000000180029320 | 0x00029320
`CombineRecordsInBlob` | 6 (0x6) | Exported Function | 0x0000000180054d70 | 0x00054d70
`Coalesce_UpdateNetVersion` | 5 (0x5) | Exported Function | 0x00000001800296b0 | 0x000296b0
`BreakRecordsIntoBlob` | 4 (0x4) | Exported Function | 0x0000000180054c40 | 0x00054c40
`AddRefQueryBlobEx` | 3 (0x3) | Exported Function | 0x0000000180007160 | 0x00007160
`AdaptiveTimeout_ResetAdaptiveTimeout` | 2 (0x2) | Exported Function | 0x0000000180029630 | 0x00029630
`DeRefQueryBlobEx` | 7 (0x7) | Exported Function | 0x000000018000a900 | 0x0000a900
`Dns_RecvTcp` | 218 (0xda) | Exported Function | 0x0000000180057800 | 0x00057800
`Dns_CloseSocket` | 200 (0xc8) | Exported Function | 0x000000018004f3e0 | 0x0004f3e0
`Dns_CreateSocket` | 202 (0xca) | Exported Function | 0x000000018004f3f0 | 0x0004f3f0
`Dns_ReadPacketNameAllocate` | 216 (0xd8) | Exported Function | 0x0000000180056550 | 0x00056550
`Dns_ReadPacketName` | 215 (0xd7) | Exported Function | 0x0000000180014530 | 0x00014530
`Dns_PingAdapterServers` | 214 (0xd6) | Exported Function | 0x000000018002d240 | 0x0002d240
`Dns_ParsePacketRecord` | 213 (0xd5) | Exported Function | 0x00000001800564e0 | 0x000564e0
`Dns_ParseMessage` | 212 (0xd4) | Exported Function | 0x0000000180013e70 | 0x00013e70
`Dns_OpenTcpConnectionAndSend` | 211 (0xd3) | Exported Function | 0x00000001800577b0 | 0x000577b0
`Dns_CreateMulticastSocket` | 201 (0xc9) | Exported Function | 0x00000001800666a0 | 0x000666a0
`Dns_InitializeWinsock` | 210 (0xd2) | Exported Function | 0x00000001800666b0 | 0x000666b0
`Dns_InitializeMsgBuf` | 208 (0xd0) | Exported Function | 0x00000001800104e0 | 0x000104e0
`Dns_GetRandomXid` | 207 (0xcf) | Exported Function | 0x00000001800563d0 | 0x000563d0
`Dns_FreeMsgBuf` | 206 (0xce) | Exported Function | 0x0000000180005890 | 0x00005890
`Dns_FindAuthoritativeZoneLib` | 205 (0xcd) | Exported Function | 0x00000001800666b0 | 0x000666b0
`Dns_ExtractRecordsFromMessage` | 204 (0xcc) | Exported Function | 0x00000001800133a0 | 0x000133a0
`Dns_CreateSocketEx` | 203 (0xcb) | Exported Function | 0x000000018004f420 | 0x0004f420
`Dns_InitializeMsgRemoteSockaddr` | 209 (0xd1) | Exported Function | 0x0000000180057760 | 0x00057760
`DnsConnectionFreeProxyList` | 31 (0x1f) | Exported Function | 0x000000018006c840 | 0x0006c840
`DnsConnectionGetHandleForHostUrlPrivate` | 32 (0x20) | Exported Function | 0x000000018006c850 | 0x0006c850
`DnsConnectionGetNameList` | 33 (0x21) | Exported Function | 0x000000018006c940 | 0x0006c940
`DnsGetNrptRuleNamesList` | 84 (0x54) | Exported Function | 0x0000000180060500 | 0x00060500
`DnsGetLastFailedUpdateInfo` | 83 (0x53) | Exported Function | 0x0000000180066660 | 0x00066660
`DnsGetInterfaceSettings` | 82 (0x52) | Exported Function | 0x000000018004e000 | 0x0004e000
`DnsGetDomainName` | 81 (0x51) | Exported Function | 0x000000018004ee90 | 0x0004ee90
`DnsGetDnsServerList` | 80 (0x50) | Exported Function | 0x000000018004ee60 | 0x0004ee60
`DnsGetCacheDataTableEx` | 79 (0x4f) | Exported Function | 0x000000018004ddc0 | 0x0004ddc0
`DnsGetPolicyTableInfo` | 85 (0x55) | Exported Function | 0x000000018004e180 | 0x0004e180
`DnsGetCacheDataTable` | 78 (0x4e) | Exported Function | 0x000000018004dd90 | 0x0004dd90
`DnsGetApplicationIdentifier` | 76 (0x4c) | Exported Function | 0x0000000180012430 | 0x00012430
`DnsGetAdaptersInfo` | 75 (0x4b) | Exported Function | 0x0000000180007780 | 0x00007780
`DnsFreeProxyName` | 74 (0x4a) | Exported Function | 0x000000018004dd70 | 0x0004dd70
`DnsFreePolicyConfig` | 73 (0x49) | Exported Function | 0x000000018004dca0 | 0x0004dca0
`DnsFreeNrptRuleNamesList` | 72 (0x48) | Exported Function | 0x00000001800604a0 | 0x000604a0
`DnsFreeNrptRule` | 71 (0x47) | Exported Function | 0x00000001800603c0 | 0x000603c0
`DnsGetBufferLengthForStringCopy` | 77 (0x4d) | Exported Function | 0x000000018004ee30 | 0x0004ee30
`DnsFreeConfigStructure` | 70 (0x46) | Exported Function | 0x000000018004b360 | 0x0004b360
`DnsGetPolicyTableInfoPrivate` | 86 (0x56) | Exported Function | 0x0000000180028340 | 0x00028340
`DnsGetProxyInfoPrivate` | 88 (0x58) | Exported Function | 0x000000018001ef00 | 0x0001ef00
`DnsModifyRecordsInSet_UTF8` | 102 (0x66) | Exported Function | 0x000000018005c130 | 0x0005c130
`DnsModifyRecordsInSet_A` | 101 (0x65) | Exported Function | 0x000000018005c0e0 | 0x0005c0e0
`DnsMapRcodeToStatus` | 100 (0x64) | Exported Function | 0x000000018004ef70 | 0x0004ef70
`DnsLogEvent` | 99 (0x63) | Exported Function | 0x0000000180059600 | 0x00059600
`DnsIsStringCountValidForTextType` | 98 (0x62) | Exported Function | 0x000000018004ef60 | 0x0004ef60
`DnsIsStatusRcode` | 97 (0x61) | Exported Function | 0x000000018004ef50 | 0x0004ef50
`DnsGetPrimaryDomainName_A` | 87 (0x57) | Exported Function | 0x000000018004eec0 | 0x0004eec0
`DnsIsNSECType` | 96 (0x60) | Exported Function | 0x000000018004ef30 | 0x0004ef30
`DnsIpv6StringToAddress` | 94 (0x5e) | Exported Function | 0x000000018004ef00 | 0x0004ef00
`DnsIpv6AddressToString` | 93 (0x5d) | Exported Function | 0x000000018004eee0 | 0x0004eee0
`DnsGlobals` | 92 (0x5c) | Exported Function | 0x00000001800b69c0 | 0x000b69c0
`DnsGetSettings` | 91 (0x5b) | Exported Function | 0x000000018004e4f0 | 0x0004e4f0
`DnsGetQueryRetryTimeouts` | 90 (0x5a) | Exported Function | 0x0000000180025be0 | 0x00025be0
`DnsGetProxyInformation` | 89 (0x59) | Exported Function | 0x00000001800071c0 | 0x000071c0
`DnsIsAMailboxType` | 95 (0x5f) | Exported Function | 0x000000018004ef10 | 0x0004ef10
`DnsFreeAdaptersInfo` | 69 (0x45) | Exported Function | 0x000000018001eab0 | 0x0001eab0
`DnsFree` | 68 (0x44) | Exported Function | 0x00000001800059d0 | 0x000059d0
`DnsFlushResolverCacheEntry_W` | 67 (0x43) | Exported Function | 0x0000000180001700 | 0x00001700
`DnsDhcpRegisterHostAddrs` | 47 (0x2f) | Exported Function | 0x000000018004b4d0 | 0x0004b4d0
`DnsDhcpRegisterAddrs` | 46 (0x2e) | Exported Function | 0x00000001800289b0 | 0x000289b0
`DnsDeRegisterLocal` | 45 (0x2d) | Exported Function | 0x000000018006aa30 | 0x0006aa30
`DnsCreateStringCopy` | 44 (0x2c) | Exported Function | 0x000000018004ee00 | 0x0004ee00
`DnsCreateStandardDnsNameCopy` | 43 (0x2b) | Exported Function | 0x000000018004edf0 | 0x0004edf0
`DnsCreateReverseNameStringForIpAddress` | 42 (0x2a) | Exported Function | 0x000000018004ede0 | 0x0004ede0
`DnsDhcpRegisterInit` | 48 (0x30) | Exported Function | 0x000000018002bce0 | 0x0002bce0
`DnsCopyStringEx` | 41 (0x29) | Exported Function | 0x000000018004ed90 | 0x0004ed90
`DnsConnectionSetProxyInfo` | 39 (0x27) | Exported Function | 0x000000018006c970 | 0x0006c970
`DnsConnectionSetPolicyEntriesPrivate` | 38 (0x26) | Exported Function | 0x000000018002a5d0 | 0x0002a5d0
`DnsConnectionSetPolicyEntries` | 37 (0x25) | Exported Function | 0x000000018002ae00 | 0x0002ae00
`DnsConnectionGetProxyList` | 36 (0x24) | Exported Function | 0x000000018006c960 | 0x0006c960
`DnsConnectionGetProxyInfoForHostUrl` | 35 (0x23) | Exported Function | 0x0000000180011680 | 0x00011680
`DnsConnectionGetProxyInfo` | 34 (0x22) | Exported Function | 0x000000018006c950 | 0x0006c950
`DnsConnectionUpdateIfIndexTable` | 40 (0x28) | Exported Function | 0x0000000180024b50 | 0x00024b50
`DnsDhcpRegisterTerm` | 49 (0x31) | Exported Function | 0x0000000180020aa0 | 0x00020aa0
`DnsDhcpRemoveRegistrations` | 50 (0x32) | Exported Function | 0x000000018004b580 | 0x0004b580
`DnsDhcpSrvRegisterHostAddr` | 51 (0x33) | Exported Function | 0x000000018004c160 | 0x0004c160
`DnsFlushResolverCacheEntry_UTF8` | 66 (0x42) | Exported Function | 0x00000001800575e0 | 0x000575e0
`DnsFlushResolverCacheEntry_A` | 65 (0x41) | Exported Function | 0x00000001800575d0 | 0x000575d0
`DnsFlushResolverCache` | 64 (0x40) | Exported Function | 0x0000000180057430 | 0x00057430
`DnsFindAuthoritativeZone` | 63 (0x3f) | Exported Function | 0x00000001800528c0 | 0x000528c0
`DnsExtractRecordsFromMessage_W` | 62 (0x3e) | Exported Function | 0x0000000180055ec0 | 0x00055ec0
`DnsExtractRecordsFromMessage_UTF8` | 61 (0x3d) | Exported Function | 0x0000000180055ea0 | 0x00055ea0
`DnsDowncaseDnsNameLabel` | 60 (0x3c) | Exported Function | 0x000000018004ee20 | 0x0004ee20
`DnsDisableIdnEncoding` | 59 (0x3b) | Exported Function | 0x000000018005fab0 | 0x0005fab0
`DnsDhcpSrvRegisterTerm` | 58 (0x3a) | Exported Function | 0x000000018004c670 | 0x0004c670
`DnsDhcpSrvRegisterInitialize` | 57 (0x39) | Exported Function | 0x000000018004ee10 | 0x0004ee10
`DnsDhcpSrvRegisterInitEx` | 56 (0x38) | Exported Function | 0x000000018004c650 | 0x0004c650
`DnsDhcpSrvRegisterInit` | 55 (0x37) | Exported Function | 0x000000018004c430 | 0x0004c430
`DnsDhcpSrvRegisterHostNameEx` | 54 (0x36) | Exported Function | 0x000000018004c2e0 | 0x0004c2e0
`DnsDhcpSrvRegisterHostName` | 53 (0x35) | Exported Function | 0x000000018004c260 | 0x0004c260
`DnsDhcpSrvRegisterHostAddrEx` | 52 (0x34) | Exported Function | 0x000000018004c1f0 | 0x0004c1f0
`DnsNameCompare_A` | 107 (0x6b) | Exported Function | 0x000000018004efe0 | 0x0004efe0
`WriteDnsNrptRulesToRegistry` | 289 (0x121) | Exported Function | 0x0000000180062760 | 0x00062760


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/26b49242879cabd209a5b314a196672fe25e22ca5288c03aa0944d6f235810d5/detection/


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


