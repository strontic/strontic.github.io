---
title: samsrv.dll | SAM Server DLL
excerpt: What is samsrv.dll?
---

# samsrv.dll 

* File Path: `C:\Windows\system32\samsrv.dll`
* Description: SAM Server DLL

## Hashes

Type | Hash
-- | --
MD5 | `14F52E3233F916D8B38909AA0964DE67`
SHA1 | `6D7637388CCE9506F492553215BB8A13894AE740`
SHA256 | `D22E2D443ECF619BAE0AD31B0A3B7366D17D47EF2AE16A2E58480B9907ABFD2B`
SHA384 | `3AC694AC1BA4FAA8C39F5DAD984AD3602F8787966D41B7B52D857173AFD154FDF4C6919DC5220B4DF802A64645E77346`
SHA512 | `755791B8F7484ECAE128533F8CF6172F2B17018946403B6BB51671C29DBAD04F07D58233378F4EE70D6D83393369E011FD37DD9892EBBCFDF6FDAFC746B1468C`
SSDEEP | `24576:Kr/eZvMOWXv7aBhbmtG5IzFXQzl0pd7i:a/yvMOWXeDbPRzl0pd7i`
IMP | `A01096B38FDDA4701E06C7CE575B694B`
PESHA1 | `B111182CE8AD831E36247DCB5D16C88E71245E39`
PE256 | `6C84C6A420AC147501D6656E719E8790A9ADD57C731EA3AD0A2555938AAB7D93`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`RtlDeleteElementGenericTable2` | 1 (0x1) | Exported Function | 0x000000018000d500 | 0x0000d500
`SampIncrementActiveThreads` | 223 (0xdf) | Exported Function | 0x00000001800041c0 | 0x000041c0
`SampIncreaseBadPwdCountLoopback` | 222 (0xde) | Exported Function | 0x0000000180072780 | 0x00072780
`SampImpersonateClient` | 221 (0xdd) | Exported Function | 0x000000018000b690 | 0x0000b690
`SampGetWillNeverTime` | 220 (0xdc) | Exported Function | 0x000000018008cc00 | 0x0008cc00
`SampGetUserAccountSettings` | 219 (0xdb) | Exported Function | 0x000000018000a200 | 0x0000a200
`SampGetUserAccountControlComputed` | 218 (0xda) | Exported Function | 0x0000000180085370 | 0x00085370
`SampGetUnicodeStringAttribute` | 217 (0xd9) | Exported Function | 0x0000000180007da0 | 0x00007da0
`SampIncrementNetlogonChangeLogSerialNumber` | 224 (0xe0) | Exported Function | 0x000000018008cc10 | 0x0008cc10
`SampGetUlongArrayAttribute` | 216 (0xd8) | Exported Function | 0x0000000180021ba0 | 0x00021ba0
`SampGetSidAttribute` | 214 (0xd6) | Exported Function | 0x000000018002b960 | 0x0002b960
`SampGetSidArrayAttribute` | 213 (0xd5) | Exported Function | 0x000000018000dbb0 | 0x0000dbb0
`SampGetServerObjectName` | 212 (0xd4) | Exported Function | 0x00000001800221c0 | 0x000221c0
`SampGetSerialNumberDomain2` | 211 (0xd3) | Exported Function | 0x0000000180069e20 | 0x00069e20
`SampGetSamSubsystemName` | 210 (0xd2) | Exported Function | 0x0000000180020430 | 0x00020430
`SampGetReverseMembershipTransitive` | 209 (0xd1) | Exported Function | 0x000000018000a290 | 0x0000a290
`SampGetPasswordMustChangeWithUF_UAC` | 208 (0xd0) | Exported Function | 0x0000000180085240 | 0x00085240
`SampGetSuccessAccountAuditingEnabled` | 215 (0xd7) | Exported Function | 0x0000000180020930 | 0x00020930
`SampInvalidateDomainCache` | 225 (0xe1) | Exported Function | 0x0000000180021790 | 0x00021790
`SampIsAccountBuiltIn` | 226 (0xe2) | Exported Function | 0x0000000180020570 | 0x00020570
`SampIsAuditingEnabled` | 227 (0xe3) | Exported Function | 0x000000018001fba0 | 0x0001fba0
`SampQueryUserSupplementalCredentialsRegistry` | 244 (0xf4) | Exported Function | 0x000000018001f930 | 0x0001f930
`SampQueryInformationUserInternal` | 243 (0xf3) | Exported Function | 0x0000000180006d30 | 0x00006d30
`SampQueryCapabilities` | 242 (0xf2) | Exported Function | 0x0000000180014510 | 0x00014510
`SampPositionOfHighestBit` | 241 (0xf1) | Exported Function | 0x000000018008cf20 | 0x0008cf20
`SampPasswordChangeNotifyWorker` | 240 (0xf0) | Exported Function | 0x000000018001dfa0 | 0x0001dfa0
`SampPasswordChangeNotify` | 239 (0xef) | Exported Function | 0x000000018001f7c0 | 0x0001f7c0
`SampNotifyReplicatedInChange` | 238 (0xee) | Exported Function | 0x0000000180011e40 | 0x00011e40
`SampNotifyAuditChange` | 237 (0xed) | Exported Function | 0x000000018001e270 | 0x0001e270
`SampNetLogonNotificationRequired` | 236 (0xec) | Exported Function | 0x000000018001d7b0 | 0x0001d7b0
`SampNeedUserAccountSettingsDuringQuery` | 235 (0xeb) | Exported Function | 0x0000000180009850 | 0x00009850
`SampMarkPerAttributeInvalidFromWhichFields` | 234 (0xea) | Exported Function | 0x000000018001c290 | 0x0001c290
`SampLookupContext` | 233 (0xe9) | Exported Function | 0x0000000180006c90 | 0x00006c90
`SampLogPrint` | 232 (0xe8) | Exported Function | 0x0000000180071930 | 0x00071930
`SampIsSetupInProgress` | 231 (0xe7) | Exported Function | 0x0000000180026ca0 | 0x00026ca0
`SampIsServiceRunning` | 230 (0xe6) | Exported Function | 0x000000018008ccd0 | 0x0008ccd0
`SampIsDomainHosted` | 229 (0xe5) | Exported Function | 0x000000018001ded0 | 0x0001ded0
`SampIsBuiltinDomain` | 228 (0xe4) | Exported Function | 0x000000018001fb80 | 0x0001fb80
`SampGetObjectTypeNameFromIndex` | 207 (0xcf) | Exported Function | 0x000000018001fce0 | 0x0001fce0
`SampReadExtendedAttributes` | 245 (0xf5) | Exported Function | 0x000000018000cad0 | 0x0000cad0
`SampGetObjectSD` | 206 (0xce) | Exported Function | 0x000000018002dc60 | 0x0002dc60
`SampGetNoGcLogonEnforceNTLMCheck` | 205 (0xcd) | Exported Function | 0x000000018008cbf0 | 0x0008cbf0
`SampGetDisableResetBadPwdCountForward` | 183 (0xb7) | Exported Function | 0x000000018008cb10 | 0x0008cb10
`SampGetDisableOutboundRSO` | 181 (0xb5) | Exported Function | 0x000000018008caf0 | 0x0008caf0
`SampGetCurrentOwnerAndPrimaryGroup` | 180 (0xb4) | Exported Function | 0x0000000180021200 | 0x00021200
`SampGetBehaviorVersion` | 179 (0xb3) | Exported Function | 0x00000001800208a0 | 0x000208a0
`SampGetAccountDomainInfo` | 178 (0xb2) | Exported Function | 0x000000018002c310 | 0x0002c310
`SampGetAccessAttribute` | 177 (0xb1) | Exported Function | 0x00000001800557b0 | 0x000557b0
`SampGenerateRandomPassword` | 176 (0xb0) | Exported Function | 0x00000001800772c0 | 0x000772c0
`SampGetDisableRSOOnPDCForward` | 182 (0xb6) | Exported Function | 0x000000018008cb00 | 0x0008cb00
`SampFreeUserInfo` | 175 (0xaf) | Exported Function | 0x00000001800680c0 | 0x000680c0
`SampFreeOemUserInfo` | 173 (0xad) | Exported Function | 0x0000000180068090 | 0x00068090
`SampFreeOemGroupInfo` | 172 (0xac) | Exported Function | 0x0000000180068090 | 0x00068090
`SampFreeMachineInfo` | 171 (0xab) | Exported Function | 0x0000000180068060 | 0x00068060
`SampFreeGroupInfo` | 170 (0xaa) | Exported Function | 0x0000000180068060 | 0x00068060
`SampFlagsToAccountControl` | 169 (0xa9) | Exported Function | 0x0000000180015580 | 0x00015580
`SampExtendDefinedDomains` | 168 (0xa8) | Exported Function | 0x0000000180022190 | 0x00022190
`SampExamineSid` | 167 (0xa7) | Exported Function | 0x0000000180028760 | 0x00028760
`SampFreeUnicodeString` | 174 (0xae) | Exported Function | 0x00000001800035d0 | 0x000035d0
`SampGetDisableSingleObjectRepl` | 184 (0xb8) | Exported Function | 0x000000018008cb20 | 0x0008cb20
`SampGetDnsDomainNameFromIndex` | 185 (0xb9) | Exported Function | 0x00000001800203e0 | 0x000203e0
`SampGetDomainContextFromIndex` | 186 (0xba) | Exported Function | 0x000000018001fd00 | 0x0001fd00
`SampGetNoGcLogonEnforceKerberosIpCheck` | 204 (0xcc) | Exported Function | 0x000000018008cbe0 | 0x0008cbe0
`SampGetNextUnmodifiedRidFromIndex` | 203 (0xcb) | Exported Function | 0x000000018008cbc0 | 0x0008cbc0
`SampGetNewAccountSecurityNt4` | 202 (0xca) | Exported Function | 0x000000018007d440 | 0x0007d440
`SampGetLogLevel` | 200 (0xc8) | Exported Function | 0x000000018001fc40 | 0x0001fc40
`SampGetIgnoreGCFailures` | 199 (0xc7) | Exported Function | 0x000000018008cbb0 | 0x0008cbb0
`SampGetHasNeverTime` | 198 (0xc6) | Exported Function | 0x000000018008cba0 | 0x0008cba0
`SampGetFixedAttributes` | 197 (0xc5) | Exported Function | 0x000000018002ba20 | 0x0002ba20
`SampGetExternalNameFromIndex` | 196 (0xc4) | Exported Function | 0x000000018008cb80 | 0x0008cb80
`SampGetExtendedAttribute` | 195 (0xc3) | Exported Function | 0x000000018000c7b0 | 0x0000c7b0
`SampGetDownLevelDomainControllersPresent` | 194 (0xc2) | Exported Function | 0x0000000180020410 | 0x00020410
`SampGetDomainUpgradeTasks` | 193 (0xc1) | Exported Function | 0x00000001800221a0 | 0x000221a0
`SampGetDomainSidListForSam` | 192 (0xc0) | Exported Function | 0x00000001800115e0 | 0x000115e0
`SampGetDomainSidFromIndex` | 191 (0xbf) | Exported Function | 0x0000000180021710 | 0x00021710
`SampGetDomainSidFromAccountContext` | 190 (0xbe) | Exported Function | 0x000000018001eed0 | 0x0001eed0
`SampGetDomainServerRoleFromIndex` | 189 (0xbd) | Exported Function | 0x000000018008cb60 | 0x0008cb60
`SampGetDomainObjectFromIndex` | 188 (0xbc) | Exported Function | 0x0000000180021ff0 | 0x00021ff0
`SampGetDomainObjectFromAccountContext` | 187 (0xbb) | Exported Function | 0x000000018008cb30 | 0x0008cb30
`SampGetNT4UpgradeInProgress` | 201 (0xc9) | Exported Function | 0x00000001800221d0 | 0x000221d0
`SampEncryptCredentialData` | 166 (0xa6) | Exported Function | 0x0000000180017c90 | 0x00017c90
`SampRecordSystemSchemaVerisonInRegistry` | 246 (0xf6) | Exported Function | 0x0000000180081940 | 0x00081940
`SampRegObjToDsObj` | 248 (0xf8) | Exported Function | 0x000000018001cc00 | 0x0001cc00
`SamrEnumerateUsersInDomain2` | 305 (0x131) | Exported Function | 0x000000018000ea00 | 0x0000ea00
`SamrEnumerateUsersInDomain` | 304 (0x130) | Exported Function | 0x000000018000eb00 | 0x0000eb00
`SamrDeleteUser` | 303 (0x12f) | Exported Function | 0x0000000180087020 | 0x00087020
`SamrDeleteGroup` | 302 (0x12e) | Exported Function | 0x000000018006fd10 | 0x0006fd10
`SamrDeleteAlias` | 301 (0x12d) | Exported Function | 0x00000001800532f0 | 0x000532f0
`SamrCreateUserInDomain` | 300 (0x12c) | Exported Function | 0x000000018006b940 | 0x0006b940
`SamrCreateUser2InDomain` | 299 (0x12b) | Exported Function | 0x000000018006b7a0 | 0x0006b7a0
`SamrGetAliasMembership` | 306 (0x132) | Exported Function | 0x000000018002f030 | 0x0002f030
`SamrCloseHandle` | 298 (0x12a) | Exported Function | 0x0000000180008360 | 0x00008360
`SamrAddMemberToAlias` | 296 (0x128) | Exported Function | 0x0000000180027750 | 0x00027750
`SampWriteGroupType` | 295 (0x127) | Exported Function | 0x0000000180013bc0 | 0x00013bc0
`SampWriteEventLog` | 294 (0x126) | Exported Function | 0x000000018002dd70 | 0x0002dd70
`SampValidateRegAttributes` | 293 (0x125) | Exported Function | 0x000000018000b120 | 0x0000b120
`SampValidatePwdSettingAttempt` | 292 (0x124) | Exported Function | 0x0000000180014d20 | 0x00014d20
`SampValidateDomainControllerCreation` | 291 (0x123) | Exported Function | 0x000000018007f1f0 | 0x0007f1f0
`SampValidateDomainCacheCallback` | 290 (0x122) | Exported Function | 0x0000000180011560 | 0x00011560
`SamrAddMemberToGroup` | 297 (0x129) | Exported Function | 0x000000018006fb80 | 0x0006fb80
`SamrGetGroupsForUser` | 307 (0x133) | Exported Function | 0x000000018002ef00 | 0x0002ef00
`SamrGetMembersInAlias` | 308 (0x134) | Exported Function | 0x000000018000e5d0 | 0x0000e5d0
`SamrLookupIdsInDomain` | 309 (0x135) | Exported Function | 0x000000018000c2e0 | 0x0000c2e0
`SamrSetInformationUser` | 326 (0x146) | Exported Function | 0x0000000180087b60 | 0x00087b60
`SamrSetInformationGroup` | 325 (0x145) | Exported Function | 0x0000000180070850 | 0x00070850
`SamrSetInformationAlias` | 324 (0x144) | Exported Function | 0x0000000180053d50 | 0x00053d50
`SamrRidToSid` | 323 (0x143) | Exported Function | 0x000000018000c130 | 0x0000c130
`SamrRemoveMemberFromGroup` | 322 (0x142) | Exported Function | 0x00000001800706c0 | 0x000706c0
`SamrRemoveMemberFromAlias` | 321 (0x141) | Exported Function | 0x00000001800539b0 | 0x000539b0
`SamrQuerySecurityObject` | 320 (0x140) | Exported Function | 0x000000018000f490 | 0x0000f490
`SamrQueryInformationUser2` | 319 (0x13f) | Exported Function | 0x000000018000c650 | 0x0000c650
`SamrQueryInformationUser` | 318 (0x13e) | Exported Function | 0x000000018000c6f0 | 0x0000c6f0
`SamrQueryInformationDomain` | 317 (0x13d) | Exported Function | 0x0000000180021580 | 0x00021580
`SamrQueryDisplayInformation` | 316 (0x13c) | Exported Function | 0x0000000180068890 | 0x00068890
`SamrOpenUser` | 315 (0x13b) | Exported Function | 0x000000018000bb80 | 0x0000bb80
`SamrOpenGroup` | 314 (0x13a) | Exported Function | 0x0000000180020310 | 0x00020310
`SamrOpenDomain` | 313 (0x139) | Exported Function | 0x0000000180006bc0 | 0x00006bc0
`SamrOpenAlias` | 312 (0x138) | Exported Function | 0x000000018000d000 | 0x0000d000
`SamrLookupNamesInDomain2` | 311 (0x137) | Exported Function | 0x0000000180003e00 | 0x00003e00
`SamrLookupNamesInDomain` | 310 (0x136) | Exported Function | 0x0000000180002810 | 0x00002810
`SampUsingDsData` | 289 (0x121) | Exported Function | 0x0000000180023390 | 0x00023390
`SampReferenceContext` | 247 (0xf7) | Exported Function | 0x000000018001f160 | 0x0001f160
`SampUpgradeUserParmsActual` | 288 (0x120) | Exported Function | 0x00000001800209f0 | 0x000209f0
`SampUpdateMixedModeAndFindDomain` | 286 (0x11e) | Exported Function | 0x000000018001f170 | 0x0001f170
`SampSetAccessAttribute` | 264 (0x108) | Exported Function | 0x000000018001c920 | 0x0001c920
`SampRtlWellKnownPrivilegeCheck` | 263 (0x107) | Exported Function | 0x0000000180002680 | 0x00002680
`SampRevertToSelf` | 262 (0x106) | Exported Function | 0x00000001800025a0 | 0x000025a0
`SampRetrieveUserV1aFixed` | 261 (0x105) | Exported Function | 0x00000001800099c0 | 0x000099c0
`SampRetrieveUserPasswords` | 260 (0x104) | Exported Function | 0x0000000180009a40 | 0x00009a40
`SampRetrieveMultipleCredentials` | 259 (0x103) | Exported Function | 0x0000000180015be0 | 0x00015be0
`SampRetrieveGroupV1Fixed` | 258 (0x102) | Exported Function | 0x0000000180020290 | 0x00020290
`SampSetAdminPassword` | 265 (0x109) | Exported Function | 0x0000000180078420 | 0x00078420
`SampReplaceUserV1aFixed` | 257 (0x101) | Exported Function | 0x0000000180029660 | 0x00029660
`SampRenameKrbtgtAccount` | 255 (0xff) | Exported Function | 0x0000000180010f00 | 0x00010f00
`SampRemoveUserFromGroup` | 254 (0xfe) | Exported Function | 0x000000018006f8c0 | 0x0006f8c0
`SampRemoveSameDomainMemberFromGlobalOrUniversalGroup` | 253 (0xfd) | Exported Function | 0x000000018006f800 | 0x0006f800
`SampRemoveAccountFromGroupMembers` | 252 (0xfc) | Exported Function | 0x000000018006f5d0 | 0x0006f5d0
`SampReleaseWriteLock` | 251 (0xfb) | Exported Function | 0x0000000180028f20 | 0x00028f20
`SampReleaseSamLockExclusive` | 250 (0xfa) | Exported Function | 0x0000000180011e00 | 0x00011e00
`SampReleaseReadLock` | 249 (0xf9) | Exported Function | 0x000000018000ae30 | 0x0000ae30
`SampReplaceUserLogonHours` | 256 (0x100) | Exported Function | 0x0000000180085e10 | 0x00085e10
`SampSetAttributeAccess` | 266 (0x10a) | Exported Function | 0x0000000180014840 | 0x00014840
`SampSetComputerObjectDsName` | 267 (0x10b) | Exported Function | 0x0000000180022020 | 0x00022020
`SampSetDSRMPasswordWorker` | 268 (0x10c) | Exported Function | 0x000000018006ce10 | 0x0006ce10
`SampUpdateComputedUserAccountControlBits` | 285 (0x11d) | Exported Function | 0x000000018000a030 | 0x0000a030
`SampUpdateAccountDisabledFlag` | 284 (0x11c) | Exported Function | 0x0000000180009890 | 0x00009890
`SampTraceEvent` | 283 (0x11b) | Exported Function | 0x0000000180009030 | 0x00009030
`SampStringFromGuid` | 282 (0x11a) | Exported Function | 0x000000018008d870 | 0x0008d870
`SampStoreObjectAttributes` | 281 (0x119) | Exported Function | 0x0000000180029930 | 0x00029930
`SampSplitSid` | 280 (0x118) | Exported Function | 0x000000018002a430 | 0x0002a430
`SampSetUserAccountControl` | 279 (0x117) | Exported Function | 0x0000000180012fd0 | 0x00012fd0
`SampSetUnicodeStringAttribute` | 278 (0x116) | Exported Function | 0x0000000180018fe0 | 0x00018fe0
`SampSetTransactionWithinDomain` | 277 (0x115) | Exported Function | 0x000000018008d670 | 0x0008d670
`SampSetTransactionDomain` | 276 (0x114) | Exported Function | 0x0000000180003a10 | 0x00003a10
`SampSetSerialNumberDomain2` | 275 (0x113) | Exported Function | 0x000000018006b370 | 0x0006b370
`SampSetPasswordInfoOnPdcByIndex` | 274 (0x112) | Exported Function | 0x00000001800734b0 | 0x000734b0
`SampSetPasswordInfoOnPdcByHandle` | 273 (0x111) | Exported Function | 0x0000000180073420 | 0x00073420
`SampSetPassword` | 272 (0x110) | Exported Function | 0x0000000180078550 | 0x00078550
`SampSetGlobalDsSids` | 271 (0x10f) | Exported Function | 0x0000000180021320 | 0x00021320
`SampSetFixedAttributes` | 270 (0x10e) | Exported Function | 0x00000001800296e0 | 0x000296e0
`SampSetExtendedAttributeAccess` | 269 (0x10d) | Exported Function | 0x00000001800105e0 | 0x000105e0
`SampUpdatePerformanceCounters` | 287 (0x11f) | Exported Function | 0x000000018000e4e0 | 0x0000e4e0
`SampDuplicateUserInfo` | 165 (0xa5) | Exported Function | 0x0000000180067ef0 | 0x00067ef0
`SampDuplicateUnicodeString` | 164 (0xa4) | Exported Function | 0x0000000180014ef0 | 0x00014ef0
`SampDuplicateOemUserInfo` | 163 (0xa3) | Exported Function | 0x0000000180067e90 | 0x00067e90
`SamILoadDownlevelDatabase` | 58 (0x3a) | Exported Function | 0x0000000180074770 | 0x00074770
`SamIIsSetupInProgress` | 57 (0x39) | Exported Function | 0x000000018002eef0 | 0x0002eef0
`SamIIsRebootAfterPromotion` | 56 (0x38) | Exported Function | 0x000000018007fc40 | 0x0007fc40
`SamIIsExtendedSidMode` | 55 (0x37) | Exported Function | 0x000000018006ee60 | 0x0006ee60
`SamIIsDownlevelDcUpgrade` | 54 (0x36) | Exported Function | 0x000000018007fc30 | 0x0007fc30
`SamIInitialize` | 53 (0x35) | Exported Function | 0x00000001800243e0 | 0x000243e0
`SamIImpersonateNullSession` | 52 (0x34) | Exported Function | 0x0000000180021050 | 0x00021050
`SamILookupNamesBySid` | 59 (0x3b) | Exported Function | 0x0000000180069390 | 0x00069390
`SamIHandleObjectUpdate` | 51 (0x33) | Exported Function | 0x0000000180015470 | 0x00015470
`SamIGetUserLogonInformation3` | 49 (0x31) | Exported Function | 0x000000018001fbd0 | 0x0001fbd0
`SamIGetUserLogonInformation2` | 48 (0x30) | Exported Function | 0x000000018002c770 | 0x0002c770
`SamIGetUserLogonInformation` | 47 (0x2f) | Exported Function | 0x000000018008a7f0 | 0x0008a7f0
`SamIGetResourceGroupMembershipsTransitive2` | 46 (0x2e) | Exported Function | 0x0000000180013cb0 | 0x00013cb0
`SamIGetResourceGroupMembershipsTransitive` | 45 (0x2d) | Exported Function | 0x0000000180003e30 | 0x00003e30
`SamIGetDefaultAdministratorName` | 44 (0x2c) | Exported Function | 0x000000018008b930 | 0x0008b930
`SamIGetConfigurationOidList` | 43 (0x2b) | Exported Function | 0x000000018008a700 | 0x0008a700
`SamIGetUserLogonInformationEx` | 50 (0x32) | Exported Function | 0x0000000180020590 | 0x00020590
`SamILookupNamesInDomain` | 60 (0x3c) | Exported Function | 0x0000000180005ff0 | 0x00005ff0
`SamILookupSidsByName` | 61 (0x3d) | Exported Function | 0x0000000180069680 | 0x00069680
`SamILoopbackConnect` | 62 (0x3e) | Exported Function | 0x000000018001f3b0 | 0x0001f3b0
`SamIRemoveDSNameFromAlias` | 79 (0x4f) | Exported Function | 0x0000000180052010 | 0x00052010
`SamIRandomizeStoredPasswordWithoutExpirationCheck` | 78 (0x4e) | Exported Function | 0x0000000180072550 | 0x00072550
`SamIRandomizeStoredPassword` | 77 (0x4d) | Exported Function | 0x0000000180071ea0 | 0x00071ea0
`SamIQueryServerRole2` | 76 (0x4c) | Exported Function | 0x0000000180021950 | 0x00021950
`SamIQueryServerRole` | 75 (0x4b) | Exported Function | 0x000000018001fc50 | 0x0001fc50
`SamIQueryRealmList` | 74 (0x4a) | Exported Function | 0x000000018002ead0 | 0x0002ead0
`SamIQueryCapabilities` | 73 (0x49) | Exported Function | 0x00000001800144c0 | 0x000144c0
`SamIQueryAccountSecretsCachability` | 72 (0x48) | Exported Function | 0x000000018008a920 | 0x0008a920
`SamIPurgeSecrets` | 71 (0x47) | Exported Function | 0x000000018008a840 | 0x0008a840
`SamIPromoteUndo` | 70 (0x46) | Exported Function | 0x0000000180074970 | 0x00074970
`SamIPromote` | 69 (0x45) | Exported Function | 0x0000000180011140 | 0x00011140
`SamIOpenUserByAlternateId` | 68 (0x44) | Exported Function | 0x00000001800827f0 | 0x000827f0
`SamINT4UpgradeInProgress` | 65 (0x41) | Exported Function | 0x00000001800221d0 | 0x000221d0
`SamINotifyRoleChange` | 67 (0x43) | Exported Function | 0x0000000180069960 | 0x00069960
`SamINetLogonPing` | 66 (0x42) | Exported Function | 0x0000000180013ab0 | 0x00013ab0
`SamIMixedDomain2` | 64 (0x40) | Exported Function | 0x0000000180020440 | 0x00020440
`SamIMixedDomain` | 63 (0x3f) | Exported Function | 0x0000000180021760 | 0x00021760
`SamIGetAliasMembership` | 42 (0x2a) | Exported Function | 0x0000000180006420 | 0x00006420
`SamIReplaceDownlevelDatabase` | 80 (0x50) | Exported Function | 0x0000000180074990 | 0x00074990
`SamIFreeVoid` | 33 (0x21) | Exported Function | 0x000000018000f0d0 | 0x0000f0d0
`SamIFreeSidAndAttributesList` | 31 (0x1f) | Exported Function | 0x000000018000ebf0 | 0x0000ebf0
`SamIDecodeClaimsBlob` | 17 (0x11) | Exported Function | 0x0000000180065a60 | 0x00065a60
`SamICreateKrbTgt` | 16 (0x10) | Exported Function | 0x000000018006cb80 | 0x0006cb80
`SamICopyCurrentDomainAccountSettings` | 15 (0xf) | Exported Function | 0x000000018008a6a0 | 0x0008a6a0
`SamIConvertSecurityAttributesToClaimsBlob` | 14 (0xe) | Exported Function | 0x00000001800657f0 | 0x000657f0
`SamIConnect` | 13 (0xd) | Exported Function | 0x000000018002ec10 | 0x0002ec10
`SamIClaimIsValid` | 12 (0xc) | Exported Function | 0x0000000180065730 | 0x00065730
`SamIChangePasswordForeignUser` | 11 (0xb) | Exported Function | 0x00000001800823e0 | 0x000823e0
`SamIDecodeClaimsBlobIntoClaimsSet` | 18 (0x12) | Exported Function | 0x0000000180065ab0 | 0x00065ab0
`SamIAddDSNameToAlias` | 10 (0xa) | Exported Function | 0x0000000180019eb0 | 0x00019eb0
`SamDsExtFree` | 8 (0x8) | Exported Function | 0x000000018000f0d0 | 0x0000f0d0
`SamDsExtAlloc` | 7 (0x7) | Exported Function | 0x0000000180009830 | 0x00009830
`SAM_MIDL_user_free` | 6 (0x6) | Exported Function | 0x000000018000f0d0 | 0x0000f0d0
`SAM_MIDL_user_allocate` | 5 (0x5) | Exported Function | 0x0000000180009830 | 0x00009830
`RtlLookupElementGenericTable2` | 4 (0x4) | Exported Function | 0x0000000180003be0 | 0x00003be0
`RtlInsertElementGenericTable2` | 3 (0x3) | Exported Function | 0x0000000180002cb0 | 0x00002cb0
`RtlInitializeGenericTable2` | 2 (0x2) | Exported Function | 0x00000001800220a0 | 0x000220a0
`SamIAccountRestrictions` | 9 (0x9) | Exported Function | 0x000000018002c3d0 | 0x0002c3d0
`SamIDecodeClaimsBlobToAuthz` | 19 (0x13) | Exported Function | 0x0000000180055a20 | 0x00055a20
`SamIDemote` | 20 (0x14) | Exported Function | 0x00000001800746a0 | 0x000746a0
`SamIDemoteUndo` | 21 (0x15) | Exported Function | 0x0000000180074740 | 0x00074740
`SamIFreeSecurityAttributesInfo` | 30 (0x1e) | Exported Function | 0x0000000180065bf0 | 0x00065bf0
`SamIFreeRealmList` | 29 (0x1d) | Exported Function | 0x000000018000ef20 | 0x0000ef20
`SamIFreeOidList` | 28 (0x1c) | Exported Function | 0x000000018008a6c0 | 0x0008a6c0
`SamIFreeLookupSidsInfo` | 27 (0x1b) | Exported Function | 0x000000018007b880 | 0x0007b880
`SamIFreeLookupNamesInfo` | 26 (0x1a) | Exported Function | 0x000000018007b740 | 0x0007b740
`SamIFreeDecodedClaimsSet` | 25 (0x19) | Exported Function | 0x0000000180065b30 | 0x00065b30
`SamIFreeClaimsBlob` | 24 (0x18) | Exported Function | 0x000000018001f860 | 0x0001f860
`SamIFreeAuthzSecurityAttributesInfo` | 23 (0x17) | Exported Function | 0x0000000180055a70 | 0x00055a70
`SamIFree_UserInternal6Information` | 41 (0x29) | Exported Function | 0x000000018002d050 | 0x0002d050
`SamIFree_SAMPR_USER_INFO_BUFFER` | 40 (0x28) | Exported Function | 0x000000018000edb0 | 0x0000edb0
`SamIFree_SAMPR_ULONG_ARRAY` | 39 (0x27) | Exported Function | 0x000000018000eed0 | 0x0000eed0
`SamIFree_SAMPR_RETURNED_USTRING_ARRAY` | 38 (0x26) | Exported Function | 0x000000018000ef70 | 0x0000ef70
`SamIFree_SAMPR_GET_GROUPS_BUFFER` | 37 (0x25) | Exported Function | 0x000000018007ba90 | 0x0007ba90
`SamIFree_SAMPR_ENUMERATION_BUFFER` | 36 (0x24) | Exported Function | 0x000000018002a7d0 | 0x0002a7d0
`SamIFree_SAMPR_DOMAIN_INFO_BUFFER` | 35 (0x23) | Exported Function | 0x00000001800220d0 | 0x000220d0
`SamIFree_SAMPR_DISPLAY_INFO_BUFFER` | 34 (0x22) | Exported Function | 0x000000018007ba50 | 0x0007ba50
`SamIDoFSMORoleChange` | 22 (0x16) | Exported Function | 0x0000000180069350 | 0x00069350
`SamIFreeSidArray` | 32 (0x20) | Exported Function | 0x000000018000ec70 | 0x0000ec70
`SamIReplicateAccountData` | 81 (0x51) | Exported Function | 0x000000018008ba20 | 0x0008ba20
`SamIResetBadPwdCountOnPdc` | 82 (0x52) | Exported Function | 0x0000000180072590 | 0x00072590
`SamIRetrieveMultiplePrimaryCredentials` | 83 (0x53) | Exported Function | 0x0000000180014410 | 0x00014410
`SampCreateUserInDomain` | 141 (0x8d) | Exported Function | 0x0000000180018630 | 0x00018630
`SampCreateGroupInDomain` | 140 (0x8c) | Exported Function | 0x00000001800127e0 | 0x000127e0
`SampCreateFullSid` | 139 (0x8b) | Exported Function | 0x000000018000c210 | 0x0000c210
`SampCreateDefaultUPN` | 138 (0x8a) | Exported Function | 0x0000000180012400 | 0x00012400
`SampCreateContextEx` | 137 (0x89) | Exported Function | 0x00000001800056d0 | 0x000056d0
`SampCreateAliasInDomain` | 136 (0x88) | Exported Function | 0x0000000180013590 | 0x00013590
`SampCreateAccountContext2` | 135 (0x87) | Exported Function | 0x0000000180005270 | 0x00005270
`SampCurrentThreadOwnsLock` | 142 (0x8e) | Exported Function | 0x0000000180003b00 | 0x00003b00
`SampCopyUserSupplementalCredentialsForDCPromo` | 134 (0x86) | Exported Function | 0x000000018001d490 | 0x0001d490
`SampConnect` | 132 (0x84) | Exported Function | 0x0000000180006940 | 0x00006940
`SampComputePasswordExpired` | 131 (0x83) | Exported Function | 0x00000001800842c0 | 0x000842c0
`SampCompareDisplayStrings` | 130 (0x82) | Exported Function | 0x000000018001da20 | 0x0001da20
`SampCommitBufferedWrites` | 129 (0x81) | Exported Function | 0x000000018001f1f0 | 0x0001f1f0
`SampCheckSidType` | 128 (0x80) | Exported Function | 0x0000000180010750 | 0x00010750
`SampCheckGroupTypeBits` | 127 (0x7f) | Exported Function | 0x00000001800209a0 | 0x000209a0
`SampCheckForAccountLockout` | 126 (0x7e) | Exported Function | 0x0000000180083e10 | 0x00083e10
`SampConvertUiListToApiList` | 133 (0x85) | Exported Function | 0x000000018008c420 | 0x0008c420
`SampDecrementActiveThreads` | 144 (0x90) | Exported Function | 0x00000001800144f0 | 0x000144f0
`SampDecryptCredentialData` | 145 (0x91) | Exported Function | 0x000000018001faa0 | 0x0001faa0
`SampDeleteContext` | 146 (0x92) | Exported Function | 0x0000000180005d60 | 0x00005d60
`SampDuplicateOemGroupInfo` | 162 (0xa2) | Exported Function | 0x0000000180067e90 | 0x00067e90
`SampDuplicateMachineInfo` | 161 (0xa1) | Exported Function | 0x0000000180067de0 | 0x00067de0
`SampDuplicateGroupInfo` | 160 (0xa0) | Exported Function | 0x0000000180067de0 | 0x00067de0
`SampDsUpdateContextAttributes` | 159 (0x9f) | Exported Function | 0x000000018001b300 | 0x0001b300
`SampDsSetPasswordUser` | 158 (0x9e) | Exported Function | 0x0000000180014a00 | 0x00014a00
`SampDsSetDomainPolicy` | 157 (0x9d) | Exported Function | 0x0000000180010b30 | 0x00010b30
`SampDsSetBuiltinDomainPolicy` | 156 (0x9c) | Exported Function | 0x0000000180010a10 | 0x00010a10
`SampDsMakeAttrBlock` | 155 (0x9b) | Exported Function | 0x000000018001bc50 | 0x0001bc50
`SampDsIsRunning` | 154 (0x9a) | Exported Function | 0x0000000180024c50 | 0x00024c50
`SampDsInitializeSingleDomain` | 153 (0x99) | Exported Function | 0x000000018001d050 | 0x0001d050
`SampDsGetPrimaryDomainStart` | 152 (0x98) | Exported Function | 0x000000018000e1c0 | 0x0000e1c0
`SampDsConvertReadAttrBlock` | 151 (0x97) | Exported Function | 0x000000018001be50 | 0x0001be50
`SampDsChangePasswordUser` | 150 (0x96) | Exported Function | 0x0000000180084ae0 | 0x00084ae0
`SampDeReferenceContext` | 143 (0x8f) | Exported Function | 0x0000000180008a80 | 0x00008a80
`SampDeltaChangeNotify` | 149 (0x95) | Exported Function | 0x000000018001e740 | 0x0001e740
`SampDeleteKeyForPostBootPromote` | 148 (0x94) | Exported Function | 0x0000000180076ab0 | 0x00076ab0
`SampDeleteDsDirsToDeleteKey` | 147 (0x93) | Exported Function | 0x00000001800769f0 | 0x000769f0
`SampChangeUserAccountName` | 125 (0x7d) | Exported Function | 0x0000000180083a90 | 0x00083a90
`SampChangeGroupAccountName` | 124 (0x7c) | Exported Function | 0x000000018006f0f0 | 0x0006f0f0
`SampChangeAliasAccountName` | 123 (0x7b) | Exported Function | 0x00000001800521c0 | 0x000521c0
`SampCalculateLmAndNtOwfPasswords` | 122 (0x7a) | Exported Function | 0x0000000180014890 | 0x00014890
`SamIValidateNewAccountName` | 100 (0x64) | Exported Function | 0x0000000180012d20 | 0x00012d20
`SamIValidateAccountName` | 99 (0x63) | Exported Function | 0x000000018008bbd0 | 0x0008bbd0
`SamIUPNFromUserHandle` | 95 (0x5f) | Exported Function | 0x0000000180013e80 | 0x00013e80
`SamIUpdateLogonStatistics` | 98 (0x62) | Exported Function | 0x00000001800281c0 | 0x000281c0
`SamIUnLoadDownlevelDatabase` | 96 (0x60) | Exported Function | 0x0000000180074d40 | 0x00074d40
`SamIUninitialize` | 97 (0x61) | Exported Function | 0x000000018007bad0 | 0x0007bad0
`SamITransformClaims` | 94 (0x5e) | Exported Function | 0x0000000180065c40 | 0x00065c40
`SamIStorePrimaryCredentials` | 93 (0x5d) | Exported Function | 0x0000000180067700 | 0x00067700
`SamISetPasswordInfoOnDc` | 92 (0x5c) | Exported Function | 0x00000001800725e0 | 0x000725e0
`SamISetPasswordForeignUser3` | 91 (0x5b) | Exported Function | 0x0000000180082990 | 0x00082990
`SamISetPasswordForeignUser2` | 90 (0x5a) | Exported Function | 0x0000000180082950 | 0x00082950
`SamISetMachinePassword` | 89 (0x59) | Exported Function | 0x00000001800828d0 | 0x000828d0
`SamISetAuditingInformation` | 88 (0x58) | Exported Function | 0x000000018008bb60 | 0x0008bb60
`SamIScorePassword` | 87 (0x57) | Exported Function | 0x0000000180013f60 | 0x00013f60
`SamIRevertNullSession` | 86 (0x56) | Exported Function | 0x0000000180020a90 | 0x00020a90
`SamIRetrievePrimaryCredentials` | 85 (0x55) | Exported Function | 0x00000001800676a0 | 0x000676a0
`SamIRetrieveNGCKeyCredential` | 84 (0x54) | Exported Function | 0x0000000180067600 | 0x00067600
`SampAccountControlToFlags` | 101 (0x65) | Exported Function | 0x000000018001eff0 | 0x0001eff0
`SamrSetSecurityObject` | 327 (0x147) | Exported Function | 0x000000018007e400 | 0x0007e400
`SampAcquireReadLock` | 102 (0x66) | Exported Function | 0x0000000180009920 | 0x00009920
`SampAcquireWriteLock` | 104 (0x68) | Exported Function | 0x0000000180028080 | 0x00028080
`SampBuildSamProtection` | 121 (0x79) | Exported Function | 0x000000018002b540 | 0x0002b540
`SampBuildDsNameFromSid` | 120 (0x78) | Exported Function | 0x000000018001d730 | 0x0001d730
`SampAuditSidHistory` | 119 (0x77) | Exported Function | 0x00000001800797d0 | 0x000797d0
`SampAuditGroupTypeChange` | 118 (0x76) | Exported Function | 0x0000000180079480 | 0x00079480
`SampAuditAnyEvent` | 117 (0x75) | Exported Function | 0x000000018000e870 | 0x0000e870
`SampAuditAccountNameChange` | 116 (0x74) | Exported Function | 0x0000000180078d70 | 0x00078d70
`SampAuditAccountEnableDisableChange` | 115 (0x73) | Exported Function | 0x000000018001ef00 | 0x0001ef00
`SampAssignPrimaryGroup` | 114 (0x72) | Exported Function | 0x0000000180082f80 | 0x00082f80
`SampApplyDomainUpdatesForAllDomains` | 113 (0x71) | Exported Function | 0x00000001800226f0 | 0x000226f0
`SampAllocateNextCurrentRidFromIndex` | 112 (0x70) | Exported Function | 0x000000018008bc20 | 0x0008bc20
`SampAlInvalidateAliasInformation` | 111 (0x6f) | Exported Function | 0x0000000180021070 | 0x00021070
`SampAddUserToGroup` | 110 (0x6e) | Exported Function | 0x000000018006f030 | 0x0006f030
`SampAddSameDomainMemberToGlobalOrUniversalGroup` | 109 (0x6d) | Exported Function | 0x000000018001a440 | 0x0001a440
`SampAddNonLocalDomainRelativeMemberships` | 108 (0x6c) | Exported Function | 0x0000000180075060 | 0x00075060
`SampAddDeltaTime` | 107 (0x6b) | Exported Function | 0x00000001800044c0 | 0x000044c0
`SampAddAccountToGroupMembers` | 105 (0x69) | Exported Function | 0x000000018001aca0 | 0x0001aca0
`SampAddAccountsAndApplyMemberships` | 106 (0x6a) | Exported Function | 0x0000000180074dd0 | 0x00074dd0
`SampAcquireSamLockExclusive` | 103 (0x67) | Exported Function | 0x0000000180011fa0 | 0x00011fa0
`SamrValidatePassword` | 328 (0x148) | Exported Function | 0x00000001800119c0 | 0x000119c0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: samsrv.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/d22e2d443ecf619bae0ad31b0a3b7366d17d47ef2ae16a2e58480b9907abfd2b/detection/


## Possible Misuse

*The following table contains possible examples of `samsrv.dll` being misused. While `samsrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_skeletonkey.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_skeletonkey.yar) | $dll2 = "samsrv.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


