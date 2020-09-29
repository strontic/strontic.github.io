---
title: sechost.dll | Host for SCM/SDDL/LSA Lookup APIs
excerpt: What is sechost.dll?
---

# sechost.dll 

* File Path: `C:\Windows\system32\sechost.dll`
* Description: Host for SCM/SDDL/LSA Lookup APIs

## Hashes

Type | Hash
-- | --
MD5 | `232DB0BB52B37B5AAB5586D7208299C3`
SHA1 | `A59DB9473AD005C2F677D927AE61061C81F8B1B6`
SHA256 | `2653AF8A97D2FD52CE8E699C93337B84F893AB08CCFC71DEB3A0794C88BD1E59`
SHA384 | `025957038AE43FB9E46E53FAFFBC005EFECE12EC4A1A3BF426792F6F1F139FCC97D1B347E0A73CA4545AFB0F6877EA2A`
SHA512 | `16ABC016CFAC172411E1BF50FC2F8D35B535E5923160B3FEA96B7C4E0DF7EA21F11E896A44310CDABDA6F990BA2F8544FC6697D0D374909952055A08B1E38887`
SSDEEP | `12288:X/wXwA37sOQ4ZZxXQ3E1VjCsEfjGwZu8qrDdqfeaC6:XYXwi7sOQ4ZZxXeEb7ELGX8q1qfeaC6`
IMP | `CE4BD072766253F6A267D0284CA82002`
PESHA1 | `4D983453F36154E89ABE27AF38A9858D3DF243CD`
PE256 | `5D3E3CD46EA52D176ABF4FBFDE83516EDE569C40007DEC8A64B0F3BBD7D3FB38`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuditComputeEffectivePolicyBySid` | 3 (0x3) | Exported Function | 0x000000018001bc00 | 0x0001bc00
`LsaAddAccountRights` | 138 (0x8a) | Exported Function | 0x000000018004e370 | 0x0004e370
`LsaClose` | 139 (0x8b) | Exported Function | 0x000000018000f720 | 0x0000f720
`LsaCreateSecret` | 140 (0x8c) | Exported Function | 0x000000018004eef0 | 0x0004eef0
`LsaDelete` | 141 (0x8d) | Exported Function | 0x000000018004e5a0 | 0x0004e5a0
`LsaEnumerateAccountRights` | 142 (0x8e) | Exported Function | 0x000000018001a170 | 0x0001a170
`LsaEnumerateAccountsWithUserRight` | 143 (0x8f) | Exported Function | 0x000000018004e410 | 0x0004e410
`LsaFreeMemory` | 144 (0x90) | Exported Function | 0x000000018000d6b0 | 0x0000d6b0
`LsaICLookupNames` | 145 (0x91) | Exported Function | 0x000000018000ee70 | 0x0000ee70
`LsaICLookupNamesWithCreds` | 146 (0x92) | Exported Function | 0x000000018004e640 | 0x0004e640
`LsaICLookupSids` | 147 (0x93) | Exported Function | 0x000000018000f4e0 | 0x0000f4e0
`LsaICLookupSidsWithCreds` | 148 (0x94) | Exported Function | 0x000000018004e850 | 0x0004e850
`LsaLookupClose` | 149 (0x95) | Exported Function | 0x0000000180015630 | 0x00015630
`LsaLookupFreeMemory` | 150 (0x96) | Exported Function | 0x000000018000d6b0 | 0x0000d6b0
`LsaLookupGetDomainInfo` | 151 (0x97) | Exported Function | 0x0000000180014c00 | 0x00014c00
`LsaLookupManageSidNameMapping` | 152 (0x98) | Exported Function | 0x000000018000df60 | 0x0000df60
`LsaLookupNames2` | 153 (0x99) | Exported Function | 0x000000018000ee00 | 0x0000ee00
`LsaLookupOpenLocalPolicy` | 154 (0x9a) | Exported Function | 0x00000001800156a0 | 0x000156a0
`LsaLookupSids` | 155 (0x9b) | Exported Function | 0x000000018000f330 | 0x0000f330
`LsaLookupSids2` | 156 (0x9c) | Exported Function | 0x000000018004eaa0 | 0x0004eaa0
`LsaLookupTranslateNames` | 157 (0x9d) | Exported Function | 0x000000018001bdc0 | 0x0001bdc0
`LsaLookupTranslateSids` | 158 (0x9e) | Exported Function | 0x000000018000d780 | 0x0000d780
`LsaLookupUserAccountType` | 159 (0x9f) | Exported Function | 0x000000018000d8e0 | 0x0000d8e0
`LsaOpenPolicy` | 160 (0xa0) | Exported Function | 0x000000018000f7b0 | 0x0000f7b0
`LookupAccountSidLocalW` | 137 (0x89) | Exported Function | 0x0000000180015130 | 0x00015130
`LsaOpenSecret` | 161 (0xa1) | Exported Function | 0x000000018004f000 | 0x0004f000
`LookupAccountSidLocalA` | 136 (0x88) | Exported Function | 0x000000018002a290 | 0x0002a290
`LookupAccountNameLocalA` | 134 (0x86) | Exported Function | 0x000000018002a110 | 0x0002a110
`GetServiceRegistryStateKey` | 113 (0x71) | Exported Function | 0x000000018000e5f0 | 0x0000e5f0
`I_QueryTagInformation` | 114 (0x72) | Exported Function | 0x00000001800074a0 | 0x000074a0
`I_RegisterSvchostNotificationCallback` | 115 (0x73) | Exported Function | 0x000000018000e760 | 0x0000e760
`I_ScBroadcastServiceControlMessage` | 116 (0x74) | Exported Function | 0x000000018001b9c0 | 0x0001b9c0
`I_ScIsSecurityProcess` | 117 (0x75) | Exported Function | 0x000000018001c720 | 0x0001c720
`I_ScPnPGetServiceName` | 118 (0x76) | Exported Function | 0x000000018000aa40 | 0x0000aa40
`I_ScQueryServiceConfig` | 119 (0x77) | Exported Function | 0x0000000180007380 | 0x00007380
`I_ScRegisterDeviceNotification` | 120 (0x78) | Exported Function | 0x000000018000b920 | 0x0000b920
`I_ScRegisterPreshutdownRestart` | 121 (0x79) | Exported Function | 0x0000000180047360 | 0x00047360
`I_ScReparseServiceDatabase` | 122 (0x7a) | Exported Function | 0x0000000180047430 | 0x00047430
`I_ScRpcBindA` | 123 (0x7b) | Exported Function | 0x0000000180048f30 | 0x00048f30
`I_ScRpcBindW` | 124 (0x7c) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`I_ScSendPnPMessage` | 125 (0x7d) | Exported Function | 0x0000000180007710 | 0x00007710
`I_ScSendTSMessage` | 126 (0x7e) | Exported Function | 0x000000018001b9c0 | 0x0001b9c0
`I_ScSetServiceBitsA` | 1 (0x1) | Exported Function | 0x0000000180045990 | 0x00045990
`I_ScSetServiceBitsW` | 2 (0x2) | Exported Function | 0x000000018001c660 | 0x0001c660
`I_ScUnregisterDeviceNotification` | 127 (0x7f) | Exported Function | 0x000000018000e3c0 | 0x0000e3c0
`I_ScValidatePnPService` | 128 (0x80) | Exported Function | 0x000000018000aa90 | 0x0000aa90
`LocalGetConditionForString` | 129 (0x81) | Exported Function | 0x00000001800100f0 | 0x000100f0
`LocalGetReferencedTokenTypesForCondition` | 130 (0x82) | Exported Function | 0x000000018002e510 | 0x0002e510
`LocalGetStringForCondition` | 131 (0x83) | Exported Function | 0x000000018002f390 | 0x0002f390
`LocalRpcBindingCreateWithSecurity` | 132 (0x84) | Exported Function | 0x0000000180045480 | 0x00045480
`LocalRpcBindingSetAuthInfoEx` | 133 (0x85) | Exported Function | 0x0000000180045630 | 0x00045630
`LookupAccountNameLocalW` | 135 (0x87) | Exported Function | 0x0000000180014ca0 | 0x00014ca0
`LsaQueryInformationPolicy` | 162 (0xa2) | Exported Function | 0x000000018000f1f0 | 0x0000f1f0
`LsaQuerySecret` | 163 (0xa3) | Exported Function | 0x000000018004f110 | 0x0004f110
`LsaRemoveAccountRights` | 164 (0xa4) | Exported Function | 0x000000018004e4f0 | 0x0004e4f0
`RegisterServiceCtrlHandlerA` | 193 (0xc1) | Exported Function | 0x00000001800483b0 | 0x000483b0
`RegisterServiceCtrlHandlerExA` | 194 (0xc2) | Exported Function | 0x0000000180019ce0 | 0x00019ce0
`RegisterServiceCtrlHandlerExW` | 195 (0xc3) | Exported Function | 0x00000001800054f0 | 0x000054f0
`RegisterServiceCtrlHandlerW` | 196 (0xc4) | Exported Function | 0x000000018000e830 | 0x0000e830
`RegisterTraceGuidsA` | 197 (0xc5) | Exported Function | NTDLL.EtwRegisterTraceGuidsA | 0x00089579
`ReleaseIdentityProviderEnumContext` | 198 (0xc6) | Exported Function | 0x000000018000d310 | 0x0000d310
`RemoveTraceCallback` | 199 (0xc7) | Exported Function | 0x000000018004b000 | 0x0004b000
`RpcClientCapabilityCheck` | 200 (0xc8) | Exported Function | 0x000000018000d470 | 0x0000d470
`SetLocalRpcServerInterfaceSecurity` | 201 (0xc9) | Exported Function | 0x0000000180045740 | 0x00045740
`SetLocalRpcServerProtseqSecurity` | 202 (0xca) | Exported Function | 0x0000000180045820 | 0x00045820
`SetServiceObjectSecurity` | 203 (0xcb) | Exported Function | 0x000000018001c4c0 | 0x0001c4c0
`SetServiceStatus` | 204 (0xcc) | Exported Function | 0x0000000180007b90 | 0x00007b90
`SetTraceCallback` | 205 (0xcd) | Exported Function | 0x000000018004b0f0 | 0x0004b0f0
`StartServiceA` | 206 (0xce) | Exported Function | 0x0000000180019e90 | 0x00019e90
`StartServiceCtrlDispatcherA` | 207 (0xcf) | Exported Function | 0x0000000180048420 | 0x00048420
`StartServiceCtrlDispatcherW` | 208 (0xd0) | Exported Function | 0x0000000180005a60 | 0x00005a60
`StartServiceW` | 209 (0xd1) | Exported Function | 0x0000000180005480 | 0x00005480
`StartTraceA` | 210 (0xd2) | Exported Function | 0x000000018004c150 | 0x0004c150
`StartTraceW` | 211 (0xd3) | Exported Function | 0x000000018000a270 | 0x0000a270
`StopTraceW` | 212 (0xd4) | Exported Function | 0x000000018001bb70 | 0x0001bb70
`SubscribeServiceChangeNotifications` | 213 (0xd5) | Exported Function | 0x000000018000de60 | 0x0000de60
`TraceQueryInformation` | 214 (0xd6) | Exported Function | 0x000000018004c680 | 0x0004c680
`TraceSetInformation` | 215 (0xd7) | Exported Function | 0x000000018004ca30 | 0x0004ca30
`QueryUserServiceNameForContext` | 192 (0xc0) | Exported Function | 0x0000000180047f50 | 0x00047f50
`QueryUserServiceName` | 191 (0xbf) | Exported Function | 0x0000000180007c90 | 0x00007c90
`QueryTransientObjectSecurityDescriptor` | 190 (0xbe) | Exported Function | 0x0000000180017f50 | 0x00017f50
`QueryTraceProcessingHandle` | 189 (0xbd) | Exported Function | 0x000000018004ade0 | 0x0004ade0
`LsaRetrievePrivateData` | 165 (0xa5) | Exported Function | 0x000000018001a2b0 | 0x0001a2b0
`LsaSetInformationPolicy` | 166 (0xa6) | Exported Function | 0x000000018004eab0 | 0x0004eab0
`LsaSetSecret` | 167 (0xa7) | Exported Function | 0x000000018004f5b0 | 0x0004f5b0
`LsaStorePrivateData` | 168 (0xa8) | Exported Function | 0x000000018004f800 | 0x0004f800
`NotifyServiceStatusChange` | 169 (0xa9) | Exported Function | 0x0000000180006a70 | 0x00006a70
`NotifyServiceStatusChangeA` | 170 (0xaa) | Exported Function | 0x0000000180019ef0 | 0x00019ef0
`NotifyServiceStatusChangeW` | 171 (0xab) | Exported Function | 0x0000000180006a70 | 0x00006a70
`OpenSCManagerA` | 172 (0xac) | Exported Function | 0x00000001800081b0 | 0x000081b0
`OpenSCManagerW` | 173 (0xad) | Exported Function | 0x0000000180008360 | 0x00008360
`OpenServiceA` | 174 (0xae) | Exported Function | 0x0000000180019e20 | 0x00019e20
`OpenServiceW` | 175 (0xaf) | Exported Function | 0x00000001800082e0 | 0x000082e0
`GetServiceProcessToken` | 112 (0x70) | Exported Function | 0x00000001800472d0 | 0x000472d0
`OpenTraceW` | 176 (0xb0) | Exported Function | 0x000000018000aed0 | 0x0000aed0
`QueryAllTracesA` | 178 (0xb2) | Exported Function | 0x000000018004c140 | 0x0004c140
`QueryAllTracesW` | 179 (0xb3) | Exported Function | 0x00000001800013f0 | 0x000013f0
`QueryLocalUserServiceName` | 180 (0xb4) | Exported Function | 0x00000001800474f0 | 0x000474f0
`QueryServiceConfig2A` | 181 (0xb5) | Exported Function | 0x0000000180047870 | 0x00047870
`QueryServiceConfig2W` | 182 (0xb6) | Exported Function | 0x0000000180007850 | 0x00007850
`QueryServiceConfigA` | 183 (0xb7) | Exported Function | 0x0000000180047ce0 | 0x00047ce0
`QueryServiceConfigW` | 184 (0xb8) | Exported Function | 0x0000000180008090 | 0x00008090
`QueryServiceDynamicInformation` | 185 (0xb9) | Exported Function | 0x0000000180048310 | 0x00048310
`QueryServiceObjectSecurity` | 186 (0xba) | Exported Function | 0x0000000180047e70 | 0x00047e70
`QueryServiceStatus` | 187 (0xbb) | Exported Function | 0x0000000180007b30 | 0x00007b30
`QueryServiceStatusEx` | 188 (0xbc) | Exported Function | 0x0000000180008240 | 0x00008240
`ProcessTrace` | 177 (0xb1) | Exported Function | 0x000000018000b5a0 | 0x0000b5a0
`UnsubscribeServiceChangeNotifications` | 216 (0xd8) | Exported Function | 0x000000018000e7f0 | 0x0000e7f0
`GetServiceKeyNameW` | 111 (0x6f) | Exported Function | 0x0000000180019b90 | 0x00019b90
`GetServiceDirectory` | 109 (0x6d) | Exported Function | 0x000000018000e070 | 0x0000e070
`ControlTraceA` | 31 (0x1f) | Exported Function | 0x000000018004b610 | 0x0004b610
`ControlTraceW` | 32 (0x20) | Exported Function | 0x0000000180009280 | 0x00009280
`ConvertSDToStringSDRootDomainW` | 33 (0x21) | Exported Function | 0x000000018002c9e0 | 0x0002c9e0
`ConvertSecurityDescriptorToStringSecurityDescriptorW` | 34 (0x22) | Exported Function | 0x0000000180010da0 | 0x00010da0
`ConvertSidToStringSidW` | 35 (0x23) | Exported Function | 0x000000018000eb80 | 0x0000eb80
`ConvertStringSDToSDDomainA` | 36 (0x24) | Exported Function | 0x000000018002ca60 | 0x0002ca60
`ConvertStringSDToSDDomainW` | 37 (0x25) | Exported Function | 0x000000018002cba0 | 0x0002cba0
`ConvertStringSDToSDRootDomainW` | 38 (0x26) | Exported Function | 0x000000018002cc70 | 0x0002cc70
`ConvertStringSecurityDescriptorToSecurityDescriptorW` | 39 (0x27) | Exported Function | 0x0000000180010e40 | 0x00010e40
`ConvertStringSidToSidW` | 40 (0x28) | Exported Function | 0x0000000180011870 | 0x00011870
`CreateIsolatedProcess` | 41 (0x29) | Exported Function | 0x00000001800611e0 | 0x000611e0
`CreateIsolationContainer` | 42 (0x2a) | Exported Function | 0x0000000180061270 | 0x00061270
`CreateServiceA` | 43 (0x2b) | Exported Function | 0x0000000180046130 | 0x00046130
`CreateServiceEx` | 44 (0x2c) | Exported Function | 0x0000000180046890 | 0x00046890
`CreateServiceW` | 45 (0x2d) | Exported Function | 0x0000000180046d90 | 0x00046d90
`CredBackupCredentials` | 46 (0x2e) | Exported Function | 0x0000000180050ab0 | 0x00050ab0
`CredDeleteA` | 47 (0x2f) | Exported Function | 0x0000000180050c50 | 0x00050c50
`CredDeleteW` | 48 (0x30) | Exported Function | 0x0000000180050d40 | 0x00050d40
`CredEncryptAndMarshalBinaryBlob` | 49 (0x31) | Exported Function | 0x00000001800520f0 | 0x000520f0
`CredEnumerateA` | 50 (0x32) | Exported Function | 0x0000000180050e30 | 0x00050e30
`CredEnumerateW` | 51 (0x33) | Exported Function | 0x000000018000ecc0 | 0x0000ecc0
`CredFindBestCredentialA` | 52 (0x34) | Exported Function | 0x0000000180050f90 | 0x00050f90
`CredFindBestCredentialW` | 53 (0x35) | Exported Function | 0x00000001800510d0 | 0x000510d0
`ControlServiceExW` | 30 (0x1e) | Exported Function | 0x000000018000e1b0 | 0x0000e1b0
`CredFree` | 54 (0x36) | Exported Function | 0x000000018000e850 | 0x0000e850
`ControlServiceExA` | 29 (0x1d) | Exported Function | 0x0000000180045fd0 | 0x00045fd0
`CloseTrace` | 27 (0x1b) | Exported Function | 0x000000018000b900 | 0x0000b900
`AuditEnumerateCategories` | 4 (0x4) | Exported Function | 0x000000018004fda0 | 0x0004fda0
`AuditEnumeratePerUserPolicy` | 5 (0x5) | Exported Function | 0x000000018004fef0 | 0x0004fef0
`AuditEnumerateSubCategories` | 6 (0x6) | Exported Function | 0x000000018004ff80 | 0x0004ff80
`AuditFree` | 7 (0x7) | Exported Function | 0x000000018000e850 | 0x0000e850
`AuditLookupCategoryNameW` | 8 (0x8) | Exported Function | 0x00000001800500f0 | 0x000500f0
`AuditLookupSubCategoryNameW` | 9 (0x9) | Exported Function | 0x0000000180050270 | 0x00050270
`AuditQueryGlobalSaclW` | 10 (0xa) | Exported Function | 0x00000001800503f0 | 0x000503f0
`AuditQueryPerUserPolicy` | 11 (0xb) | Exported Function | 0x000000018001a0e0 | 0x0001a0e0
`AuditQuerySecurity` | 12 (0xc) | Exported Function | 0x0000000180050460 | 0x00050460
`AuditQuerySystemPolicy` | 13 (0xd) | Exported Function | 0x000000018001a230 | 0x0001a230
`AuditSetGlobalSaclW` | 14 (0xe) | Exported Function | 0x0000000180050530 | 0x00050530
`AuditSetPerUserPolicy` | 15 (0xf) | Exported Function | 0x00000001800505a0 | 0x000505a0
`AuditSetSecurity` | 16 (0x10) | Exported Function | 0x0000000180050650 | 0x00050650
`AuditSetSystemPolicy` | 17 (0x11) | Exported Function | 0x00000001800507b0 | 0x000507b0
`BuildSecurityDescriptorForSharingAccess` | 18 (0x12) | Exported Function | 0x00000001800194c0 | 0x000194c0
`BuildSecurityDescriptorForSharingAccessEx` | 19 (0x13) | Exported Function | 0x0000000180018e30 | 0x00018e30
`CapabilityCheck` | 20 (0x14) | Exported Function | 0x000000018000d550 | 0x0000d550
`CapabilityCheckForSingleSessionSku` | 21 (0x15) | Exported Function | 0x0000000180045270 | 0x00045270
`ChangeServiceConfig2A` | 22 (0x16) | Exported Function | 0x0000000180045b40 | 0x00045b40
`ChangeServiceConfig2W` | 23 (0x17) | Exported Function | 0x000000018001c5d0 | 0x0001c5d0
`ChangeServiceConfigA` | 24 (0x18) | Exported Function | 0x0000000180045cf0 | 0x00045cf0
`ChangeServiceConfigW` | 25 (0x19) | Exported Function | 0x000000018000e470 | 0x0000e470
`CloseServiceHandle` | 26 (0x1a) | Exported Function | 0x0000000180008460 | 0x00008460
`ControlService` | 28 (0x1c) | Exported Function | 0x000000018000e780 | 0x0000e780
`CredGetSessionTypes` | 55 (0x37) | Exported Function | 0x0000000180051210 | 0x00051210
`CredGetTargetInfoA` | 56 (0x38) | Exported Function | 0x00000001800512a0 | 0x000512a0
`CredGetTargetInfoW` | 57 (0x39) | Exported Function | 0x00000001800513e0 | 0x000513e0
`CredUnprotectW` | 80 (0x50) | Exported Function | 0x0000000180052640 | 0x00052640
`CredWriteA` | 81 (0x51) | Exported Function | 0x0000000180051dc0 | 0x00051dc0
`CredWriteDomainCredentialsA` | 82 (0x52) | Exported Function | 0x0000000180051ea0 | 0x00051ea0
`CredWriteDomainCredentialsW` | 83 (0x53) | Exported Function | 0x0000000180051fd0 | 0x00051fd0
`CredWriteW` | 84 (0x54) | Exported Function | 0x000000018000e870 | 0x0000e870
`DeleteIsolationContainer` | 91 (0x5b) | Exported Function | 0x00000001800612d0 | 0x000612d0
`DeleteService` | 92 (0x5c) | Exported Function | 0x0000000180047250 | 0x00047250
`EnableTraceEx2` | 93 (0x5d) | Exported Function | 0x00000001800097d0 | 0x000097d0
`EnumDependentServicesW` | 94 (0x5e) | Exported Function | 0x0000000180019fb0 | 0x00019fb0
`EnumerateIdentityProviders` | 96 (0x60) | Exported Function | 0x000000018000c910 | 0x0000c910
`EnumerateTraceGuidsEx` | 97 (0x61) | Exported Function | 0x000000018000e660 | 0x0000e660
`EnumServicesStatusExW` | 95 (0x5f) | Exported Function | 0x0000000180007e10 | 0x00007e10
`EtwQueryRealtimeConsumer` | 98 (0x62) | Exported Function | 0x000000018004ad60 | 0x0004ad60
`EventAccessControl` | 99 (0x63) | Exported Function | 0x000000018004bc80 | 0x0004bc80
`EventAccessQuery` | 100 (0x64) | Exported Function | 0x000000018004bcd0 | 0x0004bcd0
`EventAccessRemove` | 101 (0x65) | Exported Function | 0x000000018004bf20 | 0x0004bf20
`FreeContainer` | 102 (0x66) | Exported Function | 0x00000001800534c0 | 0x000534c0
`FreeTransientObjectSecurityDescriptor` | 103 (0x67) | Exported Function | 0x00000001800180f0 | 0x000180f0
`GetDefaultIdentityProvider` | 104 (0x68) | Exported Function | 0x000000018001ba80 | 0x0001ba80
`GetEmbeddedContainerIsolationPolicy` | 105 (0x69) | Exported Function | 0x0000000180053510 | 0x00053510
`GetEmbeddedImageMitigationPolicy` | 106 (0x6a) | Exported Function | 0x000000018000d6d0 | 0x0000d6d0
`GetIdentityProviderInfoByGUID` | 107 (0x6b) | Exported Function | 0x000000018001b8f0 | 0x0001b8f0
`GetIdentityProviderInfoByName` | 108 (0x6c) | Exported Function | 0x000000018002a010 | 0x0002a010
`CredUnprotectEx` | 79 (0x4f) | Exported Function | 0x000000018001b380 | 0x0001b380
`CredUnprotectA` | 78 (0x4e) | Exported Function | 0x00000001800524a0 | 0x000524a0
`CredUnmarshalCredentialW` | 77 (0x4d) | Exported Function | 0x00000001800197d0 | 0x000197d0
`CredUnmarshalCredentialA` | 76 (0x4c) | Exported Function | 0x00000001800523f0 | 0x000523f0
`CredIsMarshaledCredentialW` | 58 (0x3a) | Exported Function | 0x0000000180052120 | 0x00052120
`CredIsProtectedA` | 59 (0x3b) | Exported Function | 0x0000000180052160 | 0x00052160
`CredIsProtectedW` | 60 (0x3c) | Exported Function | 0x00000001800196f0 | 0x000196f0
`CredMarshalCredentialA` | 61 (0x3d) | Exported Function | 0x0000000180052200 | 0x00052200
`CredMarshalCredentialW` | 62 (0x3e) | Exported Function | 0x000000018001acc0 | 0x0001acc0
`CredParseUserNameWithType` | 63 (0x3f) | Exported Function | 0x00000001800195e0 | 0x000195e0
`CredpConvertCredential` | 85 (0x55) | Exported Function | 0x000000018000e920 | 0x0000e920
`CredpConvertOneCredentialSize` | 86 (0x56) | Exported Function | 0x0000000180010810 | 0x00010810
`CredpConvertTargetInfo` | 87 (0x57) | Exported Function | 0x0000000180052660 | 0x00052660
`CredpDecodeCredential` | 88 (0x58) | Exported Function | 0x00000001800528c0 | 0x000528c0
`CredpEncodeCredential` | 89 (0x59) | Exported Function | 0x0000000180052910 | 0x00052910
`GetServiceDisplayNameW` | 110 (0x6e) | Exported Function | 0x0000000180019ad0 | 0x00019ad0
`CredpEncodeSecret` | 90 (0x5a) | Exported Function | 0x0000000180052990 | 0x00052990
`CredProfileLoadedEx` | 65 (0x41) | Exported Function | 0x000000018000eb20 | 0x0000eb20
`CredProfileUnloaded` | 66 (0x42) | Exported Function | 0x0000000180019f10 | 0x00019f10
`CredProtectA` | 67 (0x43) | Exported Function | 0x0000000180052270 | 0x00052270
`CredProtectEx` | 68 (0x44) | Exported Function | 0x000000018001aa30 | 0x0001aa30
`CredProtectW` | 69 (0x45) | Exported Function | 0x000000018001aa10 | 0x0001aa10
`CredReadA` | 70 (0x46) | Exported Function | 0x00000001800515a0 | 0x000515a0
`CredReadByTokenHandle` | 71 (0x47) | Exported Function | 0x00000001800516e0 | 0x000516e0
`CredReadDomainCredentialsA` | 72 (0x48) | Exported Function | 0x0000000180051830 | 0x00051830
`CredReadDomainCredentialsW` | 73 (0x49) | Exported Function | 0x0000000180051990 | 0x00051990
`CredReadW` | 74 (0x4a) | Exported Function | 0x0000000180051b00 | 0x00051b00
`CredRestoreCredentials` | 75 (0x4b) | Exported Function | 0x0000000180051c40 | 0x00051c40
`CredProfileLoaded` | 64 (0x40) | Exported Function | 0x0000000180051520 | 0x00051520
`WaitServiceState` | 217 (0xd9) | Exported Function | 0x000000018000daf0 | 0x0000daf0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sechost.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/2653af8a97d2fd52ce8e699c93337b84f893ab08ccfc71deb3a0794c88bd1e59/detection/





MIT License. Copyright (c) 2020 Strontic.


