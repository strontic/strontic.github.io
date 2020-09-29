---
title: sechost.dll | Host for SCM/SDDL/LSA Lookup APIs
excerpt: What is sechost.dll?
---

# sechost.dll 

* File Path: `C:\Windows\SysWOW64\sechost.dll`
* Description: Host for SCM/SDDL/LSA Lookup APIs

## Hashes

Type | Hash
-- | --
MD5 | `8B48EEF3187479886F2468D5092E2FC3`
SHA1 | `562B1B38B89240357CAB83169A46816DBEF27D5C`
SHA256 | `63B4E2CA466D37E4452D8D7A678EFBF479795AB202BE973FD67F55F83D126409`
SHA384 | `38521905EDFC14176FC9669EAF1598804586FD564B28654B502452C44BA6B7AE47C3DCC154A93DF7925B02CC9C4C3570`
SHA512 | `E356839319C6CAED14D7AC8E5E3B110B7DC8C957FF7A8830B368E3228E080AE63B7DE5D55DE4BC57FF7696C104DFD6B0DACF358D67BF7B49697972ED2E8EDE50`
SSDEEP | `6144:+5N6ZAWaOXicLSfvzGJiwvPzLYUqzJL0Vx1zJZgFv8njhmQOdYsJhqvEmGasJGS:ybGJiwTjqNoVxlIF0cJ2snqvZGaX`
IMP | `938E7EF741C79C98B2F57128B2F6C3CB`
PESHA1 | `BA8852097CEDF961CD0A9006E9E932655EE30815`
PE256 | `45C98E78CDE5BC83AC057586AC8A3535B869322B7FB7873D8D720DC4ABCDA694`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuditComputeEffectivePolicyBySid` | 3 (0x3) | Exported Function | 0x100258f0 | 0x000258f0
`LsaAddAccountRights` | 138 (0x8a) | Exported Function | 0x10051020 | 0x00051020
`LsaClose` | 139 (0x8b) | Exported Function | 0x10022410 | 0x00022410
`LsaCreateSecret` | 140 (0x8c) | Exported Function | 0x100518a0 | 0x000518a0
`LsaDelete` | 141 (0x8d) | Exported Function | 0x10051220 | 0x00051220
`LsaEnumerateAccountRights` | 142 (0x8e) | Exported Function | 0x10024370 | 0x00024370
`LsaEnumerateAccountsWithUserRight` | 143 (0x8f) | Exported Function | 0x100510c0 | 0x000510c0
`LsaFreeMemory` | 144 (0x90) | Exported Function | 0x10020d90 | 0x00020d90
`LsaICLookupNames` | 145 (0x91) | Exported Function | 0x10021f20 | 0x00021f20
`LsaICLookupNamesWithCreds` | 146 (0x92) | Exported Function | 0x100512b0 | 0x000512b0
`LsaICLookupSids` | 147 (0x93) | Exported Function | 0x100222d0 | 0x000222d0
`LsaICLookupSidsWithCreds` | 148 (0x94) | Exported Function | 0x10051410 | 0x00051410
`LsaLookupClose` | 149 (0x95) | Exported Function | 0x10014a80 | 0x00014a80
`LsaLookupFreeMemory` | 150 (0x96) | Exported Function | 0x10020d90 | 0x00020d90
`LsaLookupGetDomainInfo` | 151 (0x97) | Exported Function | 0x100141d0 | 0x000141d0
`LsaLookupManageSidNameMapping` | 152 (0x98) | Exported Function | 0x10014c50 | 0x00014c50
`LsaLookupNames2` | 153 (0x99) | Exported Function | 0x10021ed0 | 0x00021ed0
`LsaLookupOpenLocalPolicy` | 154 (0x9a) | Exported Function | 0x10014ae0 | 0x00014ae0
`LsaLookupSids` | 156 (0x9c) | Exported Function | 0x10022190 | 0x00022190
`LsaLookupSids2` | 155 (0x9b) | Exported Function | 0x100515a0 | 0x000515a0
`LsaLookupTranslateNames` | 157 (0x9d) | Exported Function | 0x10025ab0 | 0x00025ab0
`LsaLookupTranslateSids` | 158 (0x9e) | Exported Function | 0x100148b0 | 0x000148b0
`LsaLookupUserAccountType` | 159 (0x9f) | Exported Function | 0x10014be0 | 0x00014be0
`LsaOpenPolicy` | 160 (0xa0) | Exported Function | 0x10022490 | 0x00022490
`LookupAccountSidLocalW` | 137 (0x89) | Exported Function | 0x10014590 | 0x00014590
`LsaOpenSecret` | 161 (0xa1) | Exported Function | 0x10051960 | 0x00051960
`LookupAccountSidLocalA` | 136 (0x88) | Exported Function | 0x10031510 | 0x00031510
`LookupAccountNameLocalA` | 134 (0x86) | Exported Function | 0x10031400 | 0x00031400
`GetServiceRegistryStateKey` | 113 (0x71) | Exported Function | 0x10015200 | 0x00015200
`I_QueryTagInformation` | 114 (0x72) | Exported Function | 0x10017060 | 0x00017060
`I_RegisterSvchostNotificationCallback` | 115 (0x73) | Exported Function | 0x10021a60 | 0x00021a60
`I_ScBroadcastServiceControlMessage` | 116 (0x74) | Exported Function | 0x10022c10 | 0x00022c10
`I_ScIsSecurityProcess` | 117 (0x75) | Exported Function | 0x10026010 | 0x00026010
`I_ScPnPGetServiceName` | 118 (0x76) | Exported Function | 0x10022990 | 0x00022990
`I_ScQueryServiceConfig` | 119 (0x77) | Exported Function | 0x10016f80 | 0x00016f80
`I_ScRegisterDeviceNotification` | 120 (0x78) | Exported Function | 0x10020de0 | 0x00020de0
`I_ScRegisterPreshutdownRestart` | 121 (0x79) | Exported Function | 0x1004bde0 | 0x0004bde0
`I_ScReparseServiceDatabase` | 122 (0x7a) | Exported Function | 0x1004be80 | 0x0004be80
`I_ScRpcBindA` | 123 (0x7b) | Exported Function | 0x1004ce40 | 0x0004ce40
`I_ScRpcBindW` | 124 (0x7c) | Exported Function | 0x100240a0 | 0x000240a0
`I_ScSendPnPMessage` | 125 (0x7d) | Exported Function | 0x10017760 | 0x00017760
`I_ScSendTSMessage` | 126 (0x7e) | Exported Function | 0x10022c10 | 0x00022c10
`I_ScSetServiceBitsA` | 1 (0x1) | Exported Function | 0x1004af40 | 0x0004af40
`I_ScSetServiceBitsW` | 2 (0x2) | Exported Function | 0x10025790 | 0x00025790
`I_ScUnregisterDeviceNotification` | 127 (0x7f) | Exported Function | 0x10021820 | 0x00021820
`I_ScValidatePnPService` | 128 (0x80) | Exported Function | 0x100228f0 | 0x000228f0
`LocalGetConditionForString` | 129 (0x81) | Exported Function | 0x10024820 | 0x00024820
`LocalGetReferencedTokenTypesForCondition` | 130 (0x82) | Exported Function | 0x10034720 | 0x00034720
`LocalGetStringForCondition` | 131 (0x83) | Exported Function | 0x10035620 | 0x00035620
`LocalRpcBindingCreateWithSecurity` | 132 (0x84) | Exported Function | 0x1004aae0 | 0x0004aae0
`LocalRpcBindingSetAuthInfoEx` | 133 (0x85) | Exported Function | 0x1004ac90 | 0x0004ac90
`LookupAccountNameLocalW` | 135 (0x87) | Exported Function | 0x10014240 | 0x00014240
`LsaQueryInformationPolicy` | 162 (0xa2) | Exported Function | 0x100220f0 | 0x000220f0
`LsaQuerySecret` | 163 (0xa3) | Exported Function | 0x10051a20 | 0x00051a20
`LsaRemoveAccountRights` | 164 (0xa4) | Exported Function | 0x10051180 | 0x00051180
`RegisterServiceCtrlHandlerA` | 193 (0xc1) | Exported Function | 0x1004c6d0 | 0x0004c6d0
`RegisterServiceCtrlHandlerExA` | 194 (0xc2) | Exported Function | 0x10014f50 | 0x00014f50
`RegisterServiceCtrlHandlerExW` | 195 (0xc3) | Exported Function | 0x10016500 | 0x00016500
`RegisterServiceCtrlHandlerW` | 196 (0xc4) | Exported Function | 0x10015120 | 0x00015120
`RegisterTraceGuidsA` | 197 (0xc5) | Exported Function | NTDLL.EtwRegisterTraceGuidsA | 0x00066a99
`ReleaseIdentityProviderEnumContext` | 198 (0xc6) | Exported Function | 0x10020410 | 0x00020410
`RemoveTraceCallback` | 199 (0xc7) | Exported Function | 0x1004e3f0 | 0x0004e3f0
`RpcClientCapabilityCheck` | 200 (0xc8) | Exported Function | 0x10020bd0 | 0x00020bd0
`SetLocalRpcServerInterfaceSecurity` | 201 (0xc9) | Exported Function | 0x1004ad50 | 0x0004ad50
`SetLocalRpcServerProtseqSecurity` | 202 (0xca) | Exported Function | 0x1004adf0 | 0x0004adf0
`SetServiceObjectSecurity` | 203 (0xcb) | Exported Function | 0x100256d0 | 0x000256d0
`SetServiceStatus` | 204 (0xcc) | Exported Function | 0x10017340 | 0x00017340
`SetTraceCallback` | 205 (0xcd) | Exported Function | 0x1004e4d0 | 0x0004e4d0
`StartServiceA` | 206 (0xce) | Exported Function | 0x1000ff10 | 0x0000ff10
`StartServiceCtrlDispatcherA` | 207 (0xcf) | Exported Function | 0x10025540 | 0x00025540
`StartServiceCtrlDispatcherW` | 208 (0xd0) | Exported Function | 0x10015780 | 0x00015780
`StartServiceW` | 209 (0xd1) | Exported Function | 0x100164a0 | 0x000164a0
`StartTraceA` | 210 (0xd2) | Exported Function | 0x1004f4e0 | 0x0004f4e0
`StartTraceW` | 211 (0xd3) | Exported Function | 0x10019230 | 0x00019230
`StopTraceW` | 212 (0xd4) | Exported Function | 0x10024060 | 0x00024060
`SubscribeServiceChangeNotifications` | 213 (0xd5) | Exported Function | 0x100152b0 | 0x000152b0
`TraceQueryInformation` | 214 (0xd6) | Exported Function | 0x1004f980 | 0x0004f980
`TraceSetInformation` | 215 (0xd7) | Exported Function | 0x1004fc70 | 0x0004fc70
`QueryUserServiceNameForContext` | 192 (0xc0) | Exported Function | 0x1004c500 | 0x0004c500
`QueryUserServiceName` | 191 (0xbf) | Exported Function | 0x10017230 | 0x00017230
`QueryTransientObjectSecurityDescriptor` | 190 (0xbe) | Exported Function | 0x10010390 | 0x00010390
`QueryTraceProcessingHandle` | 189 (0xbd) | Exported Function | 0x1004e200 | 0x0004e200
`LsaRetrievePrivateData` | 165 (0xa5) | Exported Function | 0x10022c90 | 0x00022c90
`LsaSetInformationPolicy` | 166 (0xa6) | Exported Function | 0x100515d0 | 0x000515d0
`LsaSetSecret` | 167 (0xa7) | Exported Function | 0x10051e10 | 0x00051e10
`LsaStorePrivateData` | 168 (0xa8) | Exported Function | 0x10051fd0 | 0x00051fd0
`NotifyServiceStatusChange` | 169 (0xa9) | Exported Function | 0x10016ae0 | 0x00016ae0
`NotifyServiceStatusChangeA` | 170 (0xaa) | Exported Function | 0x100100e0 | 0x000100e0
`NotifyServiceStatusChangeW` | 171 (0xab) | Exported Function | 0x10016ae0 | 0x00016ae0
`OpenSCManagerA` | 172 (0xac) | Exported Function | 0x10017960 | 0x00017960
`OpenSCManagerW` | 173 (0xad) | Exported Function | 0x10017a50 | 0x00017a50
`OpenServiceA` | 174 (0xae) | Exported Function | 0x1000feb0 | 0x0000feb0
`OpenServiceW` | 175 (0xaf) | Exported Function | 0x100179e0 | 0x000179e0
`GetServiceProcessToken` | 112 (0x70) | Exported Function | 0x1004bd50 | 0x0004bd50
`OpenTraceW` | 176 (0xb0) | Exported Function | 0x10015820 | 0x00015820
`QueryAllTracesA` | 178 (0xb2) | Exported Function | 0x1004f4a0 | 0x0004f4a0
`QueryAllTracesW` | 179 (0xb3) | Exported Function | 0x1004f4c0 | 0x0004f4c0
`QueryLocalUserServiceName` | 180 (0xb4) | Exported Function | 0x1004bf20 | 0x0004bf20
`QueryServiceConfig2A` | 181 (0xb5) | Exported Function | 0x1004c150 | 0x0004c150
`QueryServiceConfig2W` | 182 (0xb6) | Exported Function | 0x10017400 | 0x00017400
`QueryServiceConfigA` | 183 (0xb7) | Exported Function | 0x1004c390 | 0x0004c390
`QueryServiceConfigW` | 184 (0xb8) | Exported Function | 0x10017820 | 0x00017820
`QueryServiceDynamicInformation` | 185 (0xb9) | Exported Function | 0x1004c660 | 0x0004c660
`QueryServiceObjectSecurity` | 186 (0xba) | Exported Function | 0x1004c450 | 0x0004c450
`QueryServiceStatus` | 187 (0xbb) | Exported Function | 0x10017000 | 0x00017000
`QueryServiceStatusEx` | 188 (0xbc) | Exported Function | 0x100178e0 | 0x000178e0
`ProcessTrace` | 177 (0xb1) | Exported Function | 0x10015db0 | 0x00015db0
`UnsubscribeServiceChangeNotifications` | 216 (0xd8) | Exported Function | 0x10021a80 | 0x00021a80
`GetServiceKeyNameW` | 111 (0x6f) | Exported Function | 0x10022b60 | 0x00022b60
`GetServiceDirectory` | 109 (0x6d) | Exported Function | 0x10025880 | 0x00025880
`ControlTraceA` | 31 (0x1f) | Exported Function | 0x1004ead0 | 0x0004ead0
`ControlTraceW` | 32 (0x20) | Exported Function | 0x10018170 | 0x00018170
`ConvertSDToStringSDRootDomainW` | 33 (0x21) | Exported Function | 0x10033230 | 0x00033230
`ConvertSecurityDescriptorToStringSecurityDescriptorW` | 34 (0x22) | Exported Function | 0x10010cb0 | 0x00010cb0
`ConvertSidToStringSidW` | 35 (0x23) | Exported Function | 0x10014d20 | 0x00014d20
`ConvertStringSDToSDDomainA` | 36 (0x24) | Exported Function | 0x10033290 | 0x00033290
`ConvertStringSDToSDDomainW` | 37 (0x25) | Exported Function | 0x10033350 | 0x00033350
`ConvertStringSDToSDRootDomainW` | 38 (0x26) | Exported Function | 0x100333d0 | 0x000333d0
`ConvertStringSecurityDescriptorToSecurityDescriptorW` | 39 (0x27) | Exported Function | 0x10010c50 | 0x00010c50
`ConvertStringSidToSidW` | 40 (0x28) | Exported Function | 0x10010d20 | 0x00010d20
`CreateIsolatedProcess` | 41 (0x29) | Exported Function | 0x1005fde0 | 0x0005fde0
`CreateIsolationContainer` | 42 (0x2a) | Exported Function | 0x1005fe50 | 0x0005fe50
`CreateServiceA` | 43 (0x2b) | Exported Function | 0x1004b460 | 0x0004b460
`CreateServiceEx` | 44 (0x2c) | Exported Function | 0x1004b800 | 0x0004b800
`CreateServiceW` | 45 (0x2d) | Exported Function | 0x1004ba90 | 0x0004ba90
`CredBackupCredentials` | 46 (0x2e) | Exported Function | 0x10052d50 | 0x00052d50
`CredDeleteA` | 47 (0x2f) | Exported Function | 0x10052e80 | 0x00052e80
`CredDeleteW` | 48 (0x30) | Exported Function | 0x100240c0 | 0x000240c0
`CredEncryptAndMarshalBinaryBlob` | 49 (0x31) | Exported Function | 0x10053d60 | 0x00053d60
`CredEnumerateA` | 50 (0x32) | Exported Function | 0x10052f40 | 0x00052f40
`CredEnumerateW` | 51 (0x33) | Exported Function | 0x100243f0 | 0x000243f0
`CredFindBestCredentialA` | 52 (0x34) | Exported Function | 0x10053030 | 0x00053030
`CredFindBestCredentialW` | 53 (0x35) | Exported Function | 0x10053110 | 0x00053110
`ControlServiceExW` | 30 (0x1e) | Exported Function | 0x10015050 | 0x00015050
`CredFree` | 54 (0x36) | Exported Function | 0x10024090 | 0x00024090
`ControlServiceExA` | 29 (0x1d) | Exported Function | 0x1004b360 | 0x0004b360
`CloseTrace` | 27 (0x1b) | Exported Function | 0x10016050 | 0x00016050
`AuditEnumerateCategories` | 4 (0x4) | Exported Function | 0x100523f0 | 0x000523f0
`AuditEnumeratePerUserPolicy` | 5 (0x5) | Exported Function | 0x100524f0 | 0x000524f0
`AuditEnumerateSubCategories` | 6 (0x6) | Exported Function | 0x10052570 | 0x00052570
`AuditFree` | 7 (0x7) | Exported Function | 0x10024090 | 0x00024090
`AuditLookupCategoryNameW` | 8 (0x8) | Exported Function | 0x10052670 | 0x00052670
`AuditLookupSubCategoryNameW` | 9 (0x9) | Exported Function | 0x10052780 | 0x00052780
`AuditQueryGlobalSaclW` | 10 (0xa) | Exported Function | 0x10052890 | 0x00052890
`AuditQueryPerUserPolicy` | 11 (0xb) | Exported Function | 0x100259c0 | 0x000259c0
`AuditQuerySecurity` | 12 (0xc) | Exported Function | 0x100528e0 | 0x000528e0
`AuditQuerySystemPolicy` | 13 (0xd) | Exported Function | 0x10025a40 | 0x00025a40
`AuditSetGlobalSaclW` | 14 (0xe) | Exported Function | 0x10052990 | 0x00052990
`AuditSetPerUserPolicy` | 15 (0xf) | Exported Function | 0x100529e0 | 0x000529e0
`AuditSetSecurity` | 16 (0x10) | Exported Function | 0x10052a70 | 0x00052a70
`AuditSetSystemPolicy` | 17 (0x11) | Exported Function | 0x10052b60 | 0x00052b60
`BuildSecurityDescriptorForSharingAccess` | 18 (0x12) | Exported Function | 0x10021140 | 0x00021140
`BuildSecurityDescriptorForSharingAccessEx` | 19 (0x13) | Exported Function | 0x10021170 | 0x00021170
`CapabilityCheck` | 20 (0x14) | Exported Function | 0x10020c70 | 0x00020c70
`CapabilityCheckForSingleSessionSku` | 21 (0x15) | Exported Function | 0x1004a970 | 0x0004a970
`ChangeServiceConfig2A` | 22 (0x16) | Exported Function | 0x1004b090 | 0x0004b090
`ChangeServiceConfig2W` | 23 (0x17) | Exported Function | 0x10025800 | 0x00025800
`ChangeServiceConfigA` | 24 (0x18) | Exported Function | 0x1004b1c0 | 0x0004b1c0
`ChangeServiceConfigW` | 25 (0x19) | Exported Function | 0x10014fb0 | 0x00014fb0
`CloseServiceHandle` | 26 (0x1a) | Exported Function | 0x10017b10 | 0x00017b10
`ControlService` | 28 (0x1c) | Exported Function | 0x100151a0 | 0x000151a0
`CredGetSessionTypes` | 55 (0x37) | Exported Function | 0x100531f0 | 0x000531f0
`CredGetTargetInfoA` | 56 (0x38) | Exported Function | 0x10053270 | 0x00053270
`CredGetTargetInfoW` | 57 (0x39) | Exported Function | 0x10053350 | 0x00053350
`CredUnprotectW` | 80 (0x50) | Exported Function | 0x10054120 | 0x00054120
`CredWriteA` | 81 (0x51) | Exported Function | 0x10053af0 | 0x00053af0
`CredWriteDomainCredentialsA` | 82 (0x52) | Exported Function | 0x10053ba0 | 0x00053ba0
`CredWriteDomainCredentialsW` | 83 (0x53) | Exported Function | 0x10053c80 | 0x00053c80
`CredWriteW` | 84 (0x54) | Exported Function | 0x10024150 | 0x00024150
`DeleteIsolationContainer` | 91 (0x5b) | Exported Function | 0x1005fec0 | 0x0005fec0
`DeleteService` | 92 (0x5c) | Exported Function | 0x1004bcd0 | 0x0004bcd0
`EnableTraceEx2` | 93 (0x5d) | Exported Function | 0x10018690 | 0x00018690
`EnumDependentServicesW` | 94 (0x5e) | Exported Function | 0x100229e0 | 0x000229e0
`EnumerateIdentityProviders` | 96 (0x60) | Exported Function | 0x100201a0 | 0x000201a0
`EnumerateTraceGuidsEx` | 97 (0x61) | Exported Function | 0x10021920 | 0x00021920
`EnumServicesStatusExW` | 95 (0x5f) | Exported Function | 0x10016e90 | 0x00016e90
`EtwQueryRealtimeConsumer` | 98 (0x62) | Exported Function | 0x1004e190 | 0x0004e190
`EventAccessControl` | 99 (0x63) | Exported Function | 0x1004f120 | 0x0004f120
`EventAccessQuery` | 100 (0x64) | Exported Function | 0x1004f170 | 0x0004f170
`EventAccessRemove` | 101 (0x65) | Exported Function | 0x1004f320 | 0x0004f320
`FreeContainer` | 102 (0x66) | Exported Function | 0x10054af0 | 0x00054af0
`FreeTransientObjectSecurityDescriptor` | 103 (0x67) | Exported Function | 0x10020ce0 | 0x00020ce0
`GetDefaultIdentityProvider` | 104 (0x68) | Exported Function | 0x10023eb0 | 0x00023eb0
`GetEmbeddedContainerIsolationPolicy` | 105 (0x69) | Exported Function | 0x10054b30 | 0x00054b30
`GetEmbeddedImageMitigationPolicy` | 106 (0x6a) | Exported Function | 0x10020af0 | 0x00020af0
`GetIdentityProviderInfoByGUID` | 107 (0x6b) | Exported Function | 0x10023e10 | 0x00023e10
`GetIdentityProviderInfoByName` | 108 (0x6c) | Exported Function | 0x10031340 | 0x00031340
`CredUnprotectEx` | 79 (0x4f) | Exported Function | 0x100239e0 | 0x000239e0
`CredUnprotectA` | 78 (0x4e) | Exported Function | 0x10053fe0 | 0x00053fe0
`CredUnmarshalCredentialW` | 77 (0x4d) | Exported Function | 0x10021cf0 | 0x00021cf0
`CredUnmarshalCredentialA` | 76 (0x4c) | Exported Function | 0x10053f70 | 0x00053f70
`CredIsMarshaledCredentialW` | 58 (0x3a) | Exported Function | 0x10023f60 | 0x00023f60
`CredIsProtectedA` | 59 (0x3b) | Exported Function | 0x10053d90 | 0x00053d90
`CredIsProtectedW` | 60 (0x3c) | Exported Function | 0x10021c50 | 0x00021c50
`CredMarshalCredentialA` | 61 (0x3d) | Exported Function | 0x10053e00 | 0x00053e00
`CredMarshalCredentialW` | 62 (0x3e) | Exported Function | 0x10023320 | 0x00023320
`CredParseUserNameWithType` | 63 (0x3f) | Exported Function | 0x10021b70 | 0x00021b70
`CredpConvertCredential` | 85 (0x55) | Exported Function | 0x100241e0 | 0x000241e0
`CredpConvertOneCredentialSize` | 86 (0x56) | Exported Function | 0x10024f00 | 0x00024f00
`CredpConvertTargetInfo` | 87 (0x57) | Exported Function | 0x10054150 | 0x00054150
`CredpDecodeCredential` | 88 (0x58) | Exported Function | 0x10023ff0 | 0x00023ff0
`CredpEncodeCredential` | 89 (0x59) | Exported Function | 0x100254d0 | 0x000254d0
`GetServiceDisplayNameW` | 110 (0x6e) | Exported Function | 0x10022a80 | 0x00022a80
`CredpEncodeSecret` | 90 (0x5a) | Exported Function | 0x10054360 | 0x00054360
`CredProfileLoadedEx` | 65 (0x41) | Exported Function | 0x10021e70 | 0x00021e70
`CredProfileUnloaded` | 66 (0x42) | Exported Function | 0x100534b0 | 0x000534b0
`CredProtectA` | 67 (0x43) | Exported Function | 0x10053e60 | 0x00053e60
`CredProtectEx` | 68 (0x44) | Exported Function | 0x10023130 | 0x00023130
`CredProtectW` | 69 (0x45) | Exported Function | 0x10023100 | 0x00023100
`CredReadA` | 70 (0x46) | Exported Function | 0x10053530 | 0x00053530
`CredReadByTokenHandle` | 71 (0x47) | Exported Function | 0x10053610 | 0x00053610
`CredReadDomainCredentialsA` | 72 (0x48) | Exported Function | 0x10053700 | 0x00053700
`CredReadDomainCredentialsW` | 73 (0x49) | Exported Function | 0x100537f0 | 0x000537f0
`CredReadW` | 74 (0x4a) | Exported Function | 0x100538e0 | 0x000538e0
`CredRestoreCredentials` | 75 (0x4b) | Exported Function | 0x100539c0 | 0x000539c0
`CredProfileLoaded` | 64 (0x40) | Exported Function | 0x10053430 | 0x00053430
`WaitServiceState` | 217 (0xd9) | Exported Function | 0x10015c40 | 0x00015c40


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sechost.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/63b4e2ca466d37e4452d8d7a678efbf479795ab202be973fd67f55f83d126409/detection/





MIT License. Copyright (c) 2020 Strontic.


