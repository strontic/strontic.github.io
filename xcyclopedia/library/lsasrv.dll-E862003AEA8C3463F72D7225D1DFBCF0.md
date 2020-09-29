---
title: lsasrv.dll | LSA Server DLL
excerpt: What is lsasrv.dll?
---

# lsasrv.dll 

* File Path: `C:\Windows\system32\lsasrv.dll`
* Description: LSA Server DLL

## Hashes

Type | Hash
-- | --
MD5 | `E862003AEA8C3463F72D7225D1DFBCF0`
SHA1 | `76984B029B2E34E882B5FA21ECECCF0B3D78BC2D`
SHA256 | `D68BA79A092B4EFD9CBB22D1C752A35C6C85FC40D9372CFEB350167E33693760`
SHA384 | `BEF38095EB0582F4EC811B0B529733490787EA3D0487F098FF816404D37C7FE0D6B85948373AF57C037AC681BDEFD756`
SHA512 | `D0C8F0E19FF264372E2093C37CDB84BAF3DF3C5908264911304AF8AE4A2CB7DD20CE9BC56EC5F895D1E70DC6ED0B5B21244EF405D08D21D290C630AAC08F9D8A`
SSDEEP | `24576:4d/j7gBbtD9bmmo7PoyLOHcMCi/Fhcut56gj8K4Ml96b9KxaCB4DG:GXsbtDWzOnCi/FhcQNYoyDG`
IMP | `2A46D61E8B92D9E7ED4FA2EDB1AE3FAF`
PESHA1 | `06A378EF3F338CA8E31D34A7D57567FC1FF27909`
PE256 | `5A06FAE4EACD734F0369B53755CA2AD18C48F68835F0056F070AC20791D3E45D`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_fgs__LSAPR_TRUST_INFORMATION` | 275 (0x113) | Exported Function | 0x0000000180042830 | 0x00042830
`LsapDbCreateObject` | 173 (0xad) | Exported Function | 0x00000001800fee30 | 0x000fee30
`LsapDbDeleteAttributesObject` | 174 (0xae) | Exported Function | 0x00000001800ff2e0 | 0x000ff2e0
`LsapDbDeleteObject` | 175 (0xaf) | Exported Function | 0x00000001800ff380 | 0x000ff380
`LsapDbDereferenceHandle` | 176 (0xb0) | Exported Function | 0x000000018002c170 | 0x0002c170
`LsapDbDereferenceObject` | 177 (0xb1) | Exported Function | 0x000000018002e900 | 0x0002e900
`LsapDbEnumerateSids` | 178 (0xb2) | Exported Function | 0x0000000180046aa0 | 0x00046aa0
`LsapDbEnumerateTrustedDomainsEx` | 179 (0xb3) | Exported Function | 0x0000000180100e40 | 0x00100e40
`LsapDbExpAcquireReadLockTrustedDomainList` | 180 (0xb4) | Exported Function | 0x0000000180101960 | 0x00101960
`LsapDbExpAcquireWriteLockTrustedDomainList` | 181 (0xb5) | Exported Function | 0x0000000180101990 | 0x00101990
`LsapDbExpConvertReadLockTrustedDomainListToExclusive` | 182 (0xb6) | Exported Function | 0x00000001801019c0 | 0x001019c0
`LsapDbExpConvertWriteLockTrustedDomainListToShared` | 183 (0xb7) | Exported Function | 0x00000001801019e0 | 0x001019e0
`LsapDbExpIsCacheBuilding` | 184 (0xb8) | Exported Function | 0x0000000180101a00 | 0x00101a00
`LsapDbExpIsCacheValid` | 185 (0xb9) | Exported Function | 0x0000000180101a20 | 0x00101a20
`LsapDbExpIsLockedTrustedDomainList` | 186 (0xba) | Exported Function | 0x0000000180101a40 | 0x00101a40
`LsapDbCopyUnicodeAttributeNoAlloc` | 172 (0xac) | Exported Function | 0x00000001801000b0 | 0x001000b0
`LsapDbExpMakeCacheBuilding` | 187 (0xbb) | Exported Function | 0x0000000180101a90 | 0x00101a90
`LsapDbExpMakeCacheValid` | 189 (0xbd) | Exported Function | 0x0000000180101ad0 | 0x00101ad0
`LsapDbExpReleaseLockTrustedDomainList` | 190 (0xbe) | Exported Function | 0x0000000180101af0 | 0x00101af0
`LsapDbFreeAttributes` | 191 (0xbf) | Exported Function | 0x000000018004f830 | 0x0004f830
`LsapDbFreeTrustedDomainsEx` | 192 (0xc0) | Exported Function | 0x0000000180100ff0 | 0x00100ff0
`LsapDbGetDbObjectTypeName` | 193 (0xc1) | Exported Function | 0x0000000180101b10 | 0x00101b10
`LsapDbGetDbPolicyHandle` | 194 (0xc2) | Exported Function | 0x0000000180101b30 | 0x00101b30
`LsapDbGetSecretType` | 195 (0xc3) | Exported Function | 0x0000000180030950 | 0x00030950
`LsapDbInitializeAttribute` | 196 (0xc4) | Exported Function | 0x0000000180043460 | 0x00043460
`LsapDbIsStatusConnectionFailure` | 197 (0xc5) | Exported Function | 0x00000001800f6190 | 0x000f6190
`LsapDbLookupAddListReferencedDomains` | 198 (0xc6) | Exported Function | 0x0000000180005980 | 0x00005980
`LsapDbLookupCreateListReferencedDomains` | 199 (0xc7) | Exported Function | 0x00000001800f61c0 | 0x000f61c0
`LsapDbLookupGetDomainInfo` | 200 (0xc8) | Exported Function | 0x000000018003d5c0 | 0x0003d5c0
`LsapDbLookupListReferencedDomains` | 201 (0xc9) | Exported Function | 0x000000018000aa30 | 0x0000aa30
`LsapDbLookupMergeDisjointReferencedDomains` | 202 (0xca) | Exported Function | 0x00000001800f67e0 | 0x000f67e0
`LsapDbExpMakeCacheInvalid` | 188 (0xbc) | Exported Function | 0x0000000180101ab0 | 0x00101ab0
`LsapDbCopyUnicodeAttribute` | 171 (0xab) | Exported Function | 0x000000018004ef50 | 0x0004ef50
`LsapDbCloseObject` | 170 (0xaa) | Exported Function | 0x000000018002fc40 | 0x0002fc40
`LsapDbCloseHandle` | 169 (0xa9) | Exported Function | 0x00000001800fec50 | 0x000fec50
`LsaITransformAuthorizationData` | 138 (0x8a) | Exported Function | 0x00000001800fcbd0 | 0x000fcbd0
`LsaIUnregisterAllPolicyChangeNotificationCallback` | 139 (0x8b) | Exported Function | 0x00000001800fb000 | 0x000fb000
`LsaIUnregisterLogonSessionCallback` | 140 (0x8c) | Exported Function | 0x00000001800baec0 | 0x000baec0
`LsaIUnregisterPolicyChangeNotificationCallback` | 141 (0x8d) | Exported Function | 0x00000001800fb130 | 0x000fb130
`LsaIUpdateForestTrustInformation` | 142 (0x8e) | Exported Function | 0x00000001800f8760 | 0x000f8760
`LsaIUpdateKerbMaxTokenSize` | 143 (0x8f) | Exported Function | 0x00000001800c60c0 | 0x000c60c0
`LsaIUpdateLogonSession` | 144 (0x90) | Exported Function | 0x0000000180003370 | 0x00003370
`LsaIUserProfileLoaded` | 145 (0x91) | Exported Function | 0x00000001800dcd20 | 0x000dcd20
`LsaIValidateTargetInfo` | 146 (0x92) | Exported Function | 0x00000001800c9b30 | 0x000c9b30
`LsaIVerifyCachability` | 147 (0x93) | Exported Function | 0x00000001800f87d0 | 0x000f87d0
`LsaIWriteAuditEvent` | 148 (0x94) | Exported Function | 0x00000001800db4d0 | 0x000db4d0
`LsaIWriteKdcAuthenticationEvent` | 149 (0x95) | Exported Function | 0x00000001800db590 | 0x000db590
`LsapAdtAuditingEnabledByLogonId` | 150 (0x96) | Exported Function | 0x000000018001a7c0 | 0x0001a7c0
`LsapAdtAuditingEnabledBySubCategory` | 151 (0x97) | Exported Function | 0x00000001800173f0 | 0x000173f0
`LsapAdtAuditingEnabledHint` | 152 (0x98) | Exported Function | 0x00000001800de540 | 0x000de540
`LsapAdtGetCallerProcessInfo` | 153 (0x99) | Exported Function | 0x0000000180012090 | 0x00012090
`LsapAdtInitParametersArray` | 154 (0x9a) | Exported Function | 0x000000018001bd30 | 0x0001bd30
`LsapDbBuildObjectCaches` | 168 (0xa8) | Exported Function | 0x000000018004e670 | 0x0004e670
`LsapDbApplyTransaction` | 167 (0xa7) | Exported Function | 0x0000000180030740 | 0x00030740
`LsapDbAcquireLockEx` | 166 (0xa6) | Exported Function | 0x000000018002ef80 | 0x0002ef80
`LsapCrServerGetSessionKeySafe` | 165 (0xa5) | Exported Function | 0x00000001800e00e0 | 0x000e00e0
`LsapCrServerGetSessionKey` | 164 (0xa4) | Exported Function | 0x0000000180043c60 | 0x00043c60
`LsapCompareDomainNames` | 163 (0xa3) | Exported Function | 0x000000018000b910 | 0x0000b910
`LsapDbLookupNameChainRequest` | 203 (0xcb) | Exported Function | 0x00000001800f6a80 | 0x000f6a80
`LsapCloseHandle` | 162 (0xa2) | Exported Function | 0x000000018002f960 | 0x0002f960
`LsapBuildPrivilegeAuditString` | 160 (0xa0) | Exported Function | 0x00000001800fcd80 | 0x000fcd80
`LsapAuOpenSam` | 158 (0x9e) | Exported Function | 0x0000000180055870 | 0x00055870
`LsapAuditFailed` | 159 (0x9f) | Exported Function | 0x00000001800decd0 | 0x000decd0
`LsapAllocatePrivateHeap` | 157 (0x9d) | Exported Function | 0x0000000180035f00 | 0x00035f00
`LsapAllocateLsaHeap` | 156 (0x9c) | Exported Function | 0x0000000180035f00 | 0x00035f00
`LsapAdtWriteLog` | 155 (0x9b) | Exported Function | 0x0000000180040540 | 0x00040540
`LsapCheckBootMode` | 161 (0xa1) | Exported Function | 0x0000000180054ac0 | 0x00054ac0
`LsaISetUserFlags` | 137 (0x89) | Exported Function | 0x000000018000eca0 | 0x0000eca0
`LsapDbLookupNamesInPrimaryDomain` | 204 (0xcc) | Exported Function | 0x00000001800fa2b0 | 0x000fa2b0
`LsapDbMakeGuidAttribute` | 206 (0xce) | Exported Function | 0x0000000180100120 | 0x00100120
`LsapIsBuiltinDomain` | 242 (0xf2) | Exported Function | 0x00000001800f7130 | 0x000f7130
`LsapIsSamOpened` | 243 (0xf3) | Exported Function | 0x0000000180101c70 | 0x00101c70
`LsapOpenSam` | 244 (0xf4) | Exported Function | 0x00000001800dd020 | 0x000dd020
`LsapQueryClientInfo` | 245 (0xf5) | Exported Function | 0x000000018002fa20 | 0x0002fa20
`LsapRemoveTrailingDot` | 246 (0xf6) | Exported Function | 0x00000001800a7b60 | 0x000a7b60
`LsapRpcCopySid` | 247 (0xf7) | Exported Function | 0x000000018000aaa0 | 0x0000aaa0
`LsapRpcCopyUnicodeString` | 248 (0xf8) | Exported Function | 0x00000001800043c0 | 0x000043c0
`LsapRtlValidateControllerTrustedDomain` | 249 (0xf9) | Exported Function | 0x00000001800f7170 | 0x000f7170
`LsapRtlValidateControllerTrustedDomainByHandle` | 250 (0xfa) | Exported Function | 0x00000001800f7310 | 0x000f7310
`LsapSetErrorInfo` | 251 (0xfb) | Exported Function | 0x00000001800be8f0 | 0x000be8f0
`LsapSidListSize` | 252 (0xfc) | Exported Function | 0x00000001800defc0 | 0x000defc0
`LsapTraceEvent` | 253 (0xfd) | Exported Function | 0x00000001800a7cd0 | 0x000a7cd0
`LsapTraceEventWithData` | 254 (0xfe) | Exported Function | 0x000000018002e890 | 0x0002e890
`LsapTruncateUnicodeString` | 255 (0xff) | Exported Function | 0x00000001800a7ba0 | 0x000a7ba0
`LsapInitLsa` | 240 (0xf0) | Exported Function | 0x000000018004a940 | 0x0004a940
`LsarClose` | 256 (0x100) | Exported Function | 0x000000018002e780 | 0x0002e780
`LsarDeleteObject` | 258 (0x102) | Exported Function | 0x00000001800fcbc0 | 0x000fcbc0
`LsarEnumerateTrustedDomainsEx` | 259 (0x103) | Exported Function | 0x00000001801013d0 | 0x001013d0
`LsarLookupSids` | 260 (0x104) | Exported Function | 0x0000000180042870 | 0x00042870
`LsarOpenPolicy` | 261 (0x105) | Exported Function | 0x00000001800fc0f0 | 0x000fc0f0
`LsarOpenSecret` | 262 (0x106) | Exported Function | 0x00000001800307b0 | 0x000307b0
`LsarQueryDomainInformationPolicy` | 263 (0x107) | Exported Function | 0x0000000180102e80 | 0x00102e80
`LsarQueryInformationPolicy` | 264 (0x108) | Exported Function | 0x000000018002b740 | 0x0002b740
`LsarQuerySecret` | 265 (0x109) | Exported Function | 0x0000000180042e10 | 0x00042e10
`LsarQueryTrustedDomainInfoByName` | 266 (0x10a) | Exported Function | 0x0000000180101540 | 0x00101540
`LsarRetrievePrivateData` | 267 (0x10b) | Exported Function | 0x0000000180103e00 | 0x00103e00
`LsarSetInformationPolicy` | 268 (0x10c) | Exported Function | 0x00000001800fc470 | 0x000fc470
`LsarSetSecret` | 269 (0x10d) | Exported Function | 0x00000001801027b0 | 0x001027b0
`LsarSetTrustedDomainInfoByName` | 270 (0x10e) | Exported Function | 0x0000000180101790 | 0x00101790
`LsarStorePrivateData` | 271 (0x10f) | Exported Function | 0x0000000180103eb0 | 0x00103eb0
`LsarCreateSecret` | 257 (0x101) | Exported Function | 0x00000001801024f0 | 0x001024f0
`LsapInitializeLsaDb` | 241 (0xf1) | Exported Function | 0x0000000180101bf0 | 0x00101bf0
`LsapGetWellKnownSid` | 239 (0xef) | Exported Function | 0x0000000180101bd0 | 0x00101bd0
`LsapGetPolicyHandle` | 238 (0xee) | Exported Function | 0x0000000180101bb0 | 0x00101bb0
`LsapDbMakeSidAttribute` | 207 (0xcf) | Exported Function | 0x0000000180100180 | 0x00100180
`LsapDbMakeUnicodeAttribute` | 208 (0xd0) | Exported Function | 0x0000000180100210 | 0x00100210
`LsapDbOpenObject` | 209 (0xd1) | Exported Function | 0x000000018002d450 | 0x0002d450
`LsapDbQueryInformationPolicy` | 210 (0xd2) | Exported Function | 0x000000018002f160 | 0x0002f160
`LsapDbReadAttribute` | 211 (0xd3) | Exported Function | 0x000000018004f980 | 0x0004f980
`LsapDbReadAttributesObject` | 212 (0xd4) | Exported Function | 0x0000000180043310 | 0x00043310
`LsapDbReferenceObject` | 213 (0xd5) | Exported Function | 0x000000018002b540 | 0x0002b540
`LsapDbReleaseLockEx` | 214 (0xd6) | Exported Function | 0x000000018002d3a0 | 0x0002d3a0
`LsapDbSecretIsMachineAcc` | 215 (0xd7) | Exported Function | 0x0000000180101c80 | 0x00101c80
`LsapDbSidToLogicalNameObject` | 216 (0xd8) | Exported Function | 0x000000018002fdf0 | 0x0002fdf0
`LsapDbSlowEnumerateTrustedDomains` | 217 (0xd9) | Exported Function | 0x0000000180101190 | 0x00101190
`LsapDbUpdateCountCompUnmappedNames` | 218 (0xda) | Exported Function | 0x00000001800fa7f0 | 0x000fa7f0
`LsapDbVerifyHandle` | 219 (0xdb) | Exported Function | 0x000000018002f540 | 0x0002f540
`LsapDbVerifyInfoQueryTrustedDomain` | 220 (0xdc) | Exported Function | 0x0000000180101b40 | 0x00101b40
`LsapDbVerifyInfoSetTrustedDomain` | 221 (0xdd) | Exported Function | 0x0000000180101b60 | 0x00101b60
`LsapDbWriteAttributesObject` | 222 (0xde) | Exported Function | 0x00000001800ff760 | 0x000ff760
`LsapDomainRenameHandlerForLogonSessions` | 223 (0xdf) | Exported Function | 0x00000001800bc5d0 | 0x000bc5d0
`LsapGetLookupRestrictIsolatedNameLevel` | 237 (0xed) | Exported Function | 0x00000001800f7120 | 0x000f7120
`LsapGetLogonSessionAccountInfoEx` | 236 (0xec) | Exported Function | 0x000000018001d7c0 | 0x0001d7c0
`LsapGetHourlyLogLevel` | 235 (0xeb) | Exported Function | 0x0000000180101ba0 | 0x00101ba0
`LsapGetGlobalRestrictAnonymous` | 234 (0xea) | Exported Function | 0x0000000180101b90 | 0x00101b90
`LsapGetCapeNamesForCap` | 233 (0xe9) | Exported Function | 0x00000001800e02c0 | 0x000e02c0
`LsapGetAccountDomainHandle` | 232 (0xe8) | Exported Function | 0x0000000180101b80 | 0x00101b80
`LsapDbLookupSidsInPrimaryDomain` | 205 (0xcd) | Exported Function | 0x0000000180100840 | 0x00100840
`LsapFreeString` | 231 (0xe7) | Exported Function | 0x000000018001e810 | 0x0001e810
`LsapFreeLsaHeap` | 229 (0xe5) | Exported Function | 0x0000000180031cf0 | 0x00031cf0
`LsapDuplicateString` | 228 (0xe4) | Exported Function | 0x000000018001e250 | 0x0001e250
`LsapDuplicateSid` | 227 (0xe3) | Exported Function | 0x000000018001efa0 | 0x0001efa0
`LsapDsUnitializeDsStateInfo` | 225 (0xe1) | Exported Function | 0x00000001800f8880 | 0x000f8880
`LsapDssetupInitializeGetPrimaryDomainInformationOpState` | 226 (0xe2) | Exported Function | 0x00000001800dcfe0 | 0x000dcfe0
`LsapDsInitializeDsStateInfo` | 224 (0xe0) | Exported Function | 0x00000001800f8840 | 0x000f8840
`LsapFreePrivateHeap` | 230 (0xe6) | Exported Function | 0x0000000180031cf0 | 0x00031cf0
`LsaISetTokenDacl` | 136 (0x88) | Exported Function | 0x00000001800dd030 | 0x000dd030
`LsaISetSupplementalTokenInfo` | 135 (0x87) | Exported Function | 0x00000001800410c0 | 0x000410c0
`LsaISetPackageAttrInLogonSession` | 134 (0x86) | Exported Function | 0x00000001800bae10 | 0x000bae10
`LsaIDereferenceCredHandle` | 34 (0x22) | Exported Function | 0x00000001800c87e0 | 0x000c87e0
`LsaIDeriveCredentialKey` | 35 (0x23) | Exported Function | 0x00000001800be760 | 0x000be760
`LsaIDsNotifiedObjectChange` | 36 (0x24) | Exported Function | 0x00000001800f8020 | 0x000f8020
`LsaIEfsAcceptSmartcardCredentials` | 37 (0x25) | Exported Function | 0x00000001800b6820 | 0x000b6820
`LsaIEqualLogonProcessName` | 38 (0x26) | Exported Function | 0x00000001800c9940 | 0x000c9940
`LsaIEqualSupplementalTokenInfo` | 39 (0x27) | Exported Function | 0x0000000180004150 | 0x00004150
`LsaIEventWritePackageNoCredential` | 40 (0x28) | Exported Function | 0x00000001800ba9a0 | 0x000ba9a0
`LsaIEventWritePackageNotCacheLogonUser` | 41 (0x29) | Exported Function | 0x000000018003f2b0 | 0x0003f2b0
`LsaIFilterNamespace` | 42 (0x2a) | Exported Function | 0x00000001800f80c0 | 0x000f80c0
`LsaIFilterSids` | 43 (0x2b) | Exported Function | 0x00000001800f9010 | 0x000f9010
`LsaIFlushIdentityCacheForSid` | 44 (0x2c) | Exported Function | 0x00000001800dcca0 | 0x000dcca0
`LsaIForestTrustFindMatch` | 45 (0x2d) | Exported Function | 0x00000001800f8150 | 0x000f8150
`LsaIFree_LSA_FOREST_TRUST_COLLISION_INFORMATION` | 72 (0x48) | Exported Function | 0x00000001800f81f0 | 0x000f81f0
`LsaIFree_LSA_FOREST_TRUST_INFORMATION` | 73 (0x49) | Exported Function | 0x00000001800f8230 | 0x000f8230
`LsaICryptUnprotectDataEx` | 33 (0x21) | Exported Function | 0x00000001800be6b0 | 0x000be6b0
`LsaIFree_LSAI_PRIVATE_DATA` | 50 (0x32) | Exported Function | 0x00000001800dcd80 | 0x000dcd80
`LsaIFree_LSAP_SITE_INFO` | 69 (0x45) | Exported Function | 0x00000001800f9b10 | 0x000f9b10
`LsaIFree_LSAP_SITENAME_INFO` | 68 (0x44) | Exported Function | 0x00000001800f9ab0 | 0x000f9ab0
`LsaIFree_LSAP_SUBNET_INFO` | 70 (0x46) | Exported Function | 0x00000001800f9b90 | 0x000f9b90
`LsaIFree_LSAP_UPN_SUFFIXES` | 71 (0x47) | Exported Function | 0x00000001800f9b10 | 0x000f9b10
`LsaIFree_LSAPR_ACCOUNT_ENUM_BUFFER` | 52 (0x34) | Exported Function | 0x00000001800dce20 | 0x000dce20
`LsaIFree_LSAPR_CR_CIPHER_VALUE` | 53 (0x35) | Exported Function | 0x0000000180036b10 | 0x00036b10
`LsaIFree_LSAPR_POLICY_DOMAIN_INFORMATION` | 54 (0x36) | Exported Function | 0x00000001800dce40 | 0x000dce40
`LsaIFree_LSAPR_POLICY_INFORMATION` | 55 (0x37) | Exported Function | 0x000000018003e980 | 0x0003e980
`LsaIFree_LSAPR_PRIVILEGE_ENUM_BUFFER` | 56 (0x38) | Exported Function | 0x00000001800dce70 | 0x000dce70
`LsaIFree_LSAPR_PRIVILEGE_SET` | 57 (0x39) | Exported Function | 0x00000001800dcd80 | 0x000dcd80
`LsaIFree_LSAPR_REFERENCED_DOMAIN_LIST` | 58 (0x3a) | Exported Function | 0x00000001800427a0 | 0x000427a0
`LsaIFree_LSAPR_SR_SECURITY_DESCRIPTOR` | 59 (0x3b) | Exported Function | 0x00000001800dce90 | 0x000dce90
`LsaIFree_LSAPR_TRANSLATED_NAMES` | 60 (0x3c) | Exported Function | 0x000000018005b1a0 | 0x0005b1a0
`LsaIFree_LSAPR_TRANSLATED_SIDS` | 61 (0x3d) | Exported Function | 0x00000001800dced0 | 0x000dced0
`LsaIFree_LSAI_SECRET_ENUM_BUFFER` | 51 (0x33) | Exported Function | 0x00000001800dcdb0 | 0x000dcdb0
`LsaICryptUnprotectData` | 32 (0x20) | Exported Function | 0x000000018003f410 | 0x0003f410
`LsaICryptProtectDataEx` | 31 (0x1f) | Exported Function | 0x00000001800be600 | 0x000be600
`LsaICryptProtectData` | 30 (0x1e) | Exported Function | 0x000000018003f880 | 0x0003f880
`_fgs__LSAPR_TRUSTED_ENUM_BUFFER` | 273 (0x111) | Exported Function | 0x00000001800427d0 | 0x000427d0
`_fgs__LSAPR_TRUSTED_ENUM_BUFFER_EX` | 274 (0x112) | Exported Function | 0x00000001800e1600 | 0x000e1600
`_fgu__LSAPR_TRUSTED_DOMAIN_INFO` | 276 (0x114) | Exported Function | 0x00000001800e16c0 | 0x000e16c0
`InitializeLsaExtension` | 1 (0x1) | Exported Function | 0x0000000180054650 | 0x00054650
`LsaDbLookupSidChainRequest` | 3 (0x3) | Exported Function | 0x00000001800f5d40 | 0x000f5d40
`LsaIAddNamesToLogonSession` | 4 (0x4) | Exported Function | 0x000000018001cad0 | 0x0001cad0
`LsaIAdjustTokenObjectIntegrity` | 5 (0x5) | Exported Function | 0x000000018001b270 | 0x0001b270
`LsaIAdtAuditingEnabledByCategory` | 6 (0x6) | Exported Function | 0x0000000180057a00 | 0x00057a00
`LsaIAdtAuditingEnabledBySubCategory` | 7 (0x7) | Exported Function | 0x00000001800da250 | 0x000da250
`LsaIAllocateHeap` | 8 (0x8) | Exported Function | 0x0000000180041090 | 0x00041090
`LsaIAllocateHeapZero` | 9 (0x9) | Exported Function | 0x0000000180035f00 | 0x00035f00
`LsaIAllowProtectedCredLogon` | 10 (0xa) | Exported Function | 0x00000001800c51b0 | 0x000c51b0
`LsaIAuditAccountLogon` | 11 (0xb) | Exported Function | 0x00000001800da340 | 0x000da340
`LsaIAuditAccountLogonEx` | 12 (0xc) | Exported Function | 0x0000000180016cf0 | 0x00016cf0
`LsaIAuditInitializeParametersAndWriteEvent` | 13 (0xd) | Exported Function | 0x00000001800da720 | 0x000da720
`LsaIAuditKdcEvent` | 14 (0xe) | Exported Function | 0x00000001800da7f0 | 0x000da7f0
`LsaIAuditKerberosLogon` | 15 (0xf) | Exported Function | 0x00000001800dabd0 | 0x000dabd0
`LsaIClearOldSyskey` | 29 (0x1d) | Exported Function | 0x00000001800f78d0 | 0x000f78d0
`LsaICheckRestrictedMode` | 28 (0x1c) | Exported Function | 0x00000001800dcc80 | 0x000dcc80
`LsaICheckProtectedUserByTokenInfo` | 27 (0x1b) | Exported Function | 0x000000018001cd40 | 0x0001cd40
`LsaIChangeSecretCipherKey` | 26 (0x1a) | Exported Function | 0x00000001800f7810 | 0x000f7810
`LsaICancelNotification` | 25 (0x19) | Exported Function | 0x000000018003eaa0 | 0x0003eaa0
`LsaICallPackagePassthrough` | 24 (0x18) | Exported Function | 0x00000001800c9810 | 0x000c9810
`LsaIFree_LSAPR_TRUST_INFORMATION` | 65 (0x41) | Exported Function | 0x00000001800dcf80 | 0x000dcf80
`LsaICallPackageEx` | 23 (0x17) | Exported Function | 0x000000018003b110 | 0x0003b110
`LsaIAuditSamEvent` | 21 (0x15) | Exported Function | 0x000000018002fea0 | 0x0002fea0
`LsaIAuditReplay` | 20 (0x14) | Exported Function | 0x00000001800dae50 | 0x000dae50
`LsaIAuditPasswordAccessEvent` | 19 (0x13) | Exported Function | 0x00000001800dac60 | 0x000dac60
`LsaIAuditNotifyPackageLoad` | 18 (0x12) | Exported Function | 0x000000018005b9c0 | 0x0005b9c0
`LsaIAuditLogonUsingExplicitCreds` | 17 (0x11) | Exported Function | 0x0000000180017dc0 | 0x00017dc0
`LsaIAuditLogonEx` | 16 (0x10) | Exported Function | 0x00000001800413e0 | 0x000413e0
`LsaICallPackage` | 22 (0x16) | Exported Function | 0x00000001800c97d0 | 0x000c97d0
`LsaIFree_LSAPR_TRUSTED_DOMAIN_INFO` | 62 (0x3e) | Exported Function | 0x00000001800dcf00 | 0x000dcf00
`LsaIFree_LSAPR_TRUSTED_ENUM_BUFFER` | 63 (0x3f) | Exported Function | 0x00000001800dcf40 | 0x000dcf40
`LsaIFree_LSAPR_TRUSTED_ENUM_BUFFER_EX` | 64 (0x40) | Exported Function | 0x00000001800dcf60 | 0x000dcf60
`LsaILookupWellKnownName` | 103 (0x67) | Exported Function | 0x00000001800f9d80 | 0x000f9d80
`LsaIModifyPerformanceCounter` | 104 (0x68) | Exported Function | 0x0000000180031d50 | 0x00031d50
`LsaINoConnectedUserPolicy` | 105 (0x69) | Exported Function | 0x000000018003dbf0 | 0x0003dbf0
`LsaINoMoreWin2KDomain` | 106 (0x6a) | Exported Function | 0x000000018003fa70 | 0x0003fa70
`LsaINotifyChangeNotification` | 107 (0x6b) | Exported Function | 0x00000001800faf60 | 0x000faf60
`LsaINotifyGCStatusChange` | 108 (0x6c) | Exported Function | 0x00000001800f8450 | 0x000f8450
`LsaINotifyNetlogonParametersChangeW` | 109 (0x6d) | Exported Function | 0x00000001800f9c40 | 0x000f9c40
`LsaINotifyNewPassword` | 110 (0x6e) | Exported Function | 0x00000001800b3ff0 | 0x000b3ff0
`LsaINotifyPasswordChanged` | 111 (0x6f) | Exported Function | 0x00000001800b4000 | 0x000b4000
`LsaIOpenPolicyTrusted` | 112 (0x70) | Exported Function | 0x000000018005b570 | 0x0005b570
`LsaIQueryForestTrustInfo` | 113 (0x71) | Exported Function | 0x00000001800f8490 | 0x000f8490
`LsaIQueryForestTrustInformation` | 114 (0x72) | Exported Function | 0x00000001800f84f0 | 0x000f84f0
`LsaIQueryInformationPolicyTrusted` | 115 (0x73) | Exported Function | 0x000000018003f7b0 | 0x0003f7b0
`LsaIQueryPackageAttrInLogonSession` | 116 (0x74) | Exported Function | 0x000000018003c710 | 0x0003c710
`LsaIQuerySiteInfo` | 117 (0x75) | Exported Function | 0x00000001800f8520 | 0x000f8520
`LsaIQuerySubnetInfo` | 118 (0x76) | Exported Function | 0x00000001800f8570 | 0x000f8570
`LsaIQueryUpnSuffixes` | 119 (0x77) | Exported Function | 0x00000001800f85c0 | 0x000f85c0
`LsaISetNewSyskey` | 133 (0x85) | Exported Function | 0x00000001800f7920 | 0x000f7920
`LsaISetLogonInfo` | 132 (0x84) | Exported Function | 0x000000018003e740 | 0x0003e740
`LsaISetLogonGuidInLogonSession` | 131 (0x83) | Exported Function | 0x00000001800bac20 | 0x000bac20
`LsaISetClientDnsHostName` | 130 (0x82) | Exported Function | 0x00000001800f86c0 | 0x000f86c0
`LsaISanitizeSAMName` | 129 (0x81) | Exported Function | 0x00000001800dcd10 | 0x000dcd10
`LsaISamIndicatedDsStarted` | 128 (0x80) | Exported Function | 0x00000001800f8670 | 0x000f8670
`LsaILookupUserAccountType` | 102 (0x66) | Exported Function | 0x000000018003f570 | 0x0003f570
`LsaISafeMode` | 127 (0x7f) | Exported Function | 0x000000018004f190 | 0x0004f190
`LsaIReplicateClientObject` | 125 (0x7d) | Exported Function | 0x00000001800f8610 | 0x000f8610
`LsaIRenewCertificate` | 124 (0x7c) | Exported Function | 0x00000001800dccf0 | 0x000dccf0
`LsaIRegisterPolicyChangeNotificationCallback` | 123 (0x7b) | Exported Function | 0x0000000180053fb0 | 0x00053fb0
`LsaIRegisterNotification` | 122 (0x7a) | Exported Function | 0x0000000180048f50 | 0x00048f50
`LsaIRegisterLogonSessionCallback` | 121 (0x79) | Exported Function | 0x000000018003faa0 | 0x0003faa0
`LsaIReferenceCredHandle` | 120 (0x78) | Exported Function | 0x00000001800c8820 | 0x000c8820
`LsaIRetrieveCurrentUserSid` | 126 (0x7e) | Exported Function | 0x0000000180036f30 | 0x00036f30
`QueryLsaInterface` | 2 (0x2) | Exported Function | 0x000000018005bea0 | 0x0005bea0
`LsaIKerberosRegisterTrustNotification` | 101 (0x65) | Exported Function | 0x00000001800f8400 | 0x000f8400
`LsaIIsTrustedDomainsEnabled` | 99 (0x63) | Exported Function | 0x00000001800f83f0 | 0x000f83f0
`LsaIFree_LSAPR_UNICODE_STRING` | 66 (0x42) | Exported Function | 0x00000001800dce90 | 0x000dce90
`LsaIFree_LSAPR_UNICODE_STRING_BUFFER` | 67 (0x43) | Exported Function | 0x00000001800dced0 | 0x000dced0
`LsaIFreeForestTrustInfo` | 46 (0x2e) | Exported Function | 0x00000001800f81b0 | 0x000f81b0
`LsaIFreeHeap` | 47 (0x2f) | Exported Function | 0x0000000180031cf0 | 0x00031cf0
`LsaIFreeReturnBuffer` | 48 (0x30) | Exported Function | 0x000000018003b0a0 | 0x0003b0a0
`LsaIFreeSupplementalTokenInfo` | 49 (0x31) | Exported Function | 0x000000018003ec30 | 0x0003ec30
`LsaIGetCallInfo` | 74 (0x4a) | Exported Function | 0x00000001800211f0 | 0x000211f0
`LsaIGetCcgClient` | 75 (0x4b) | Exported Function | 0x00000001800a8f40 | 0x000a8f40
`LsaIGetClientOsInfo` | 76 (0x4c) | Exported Function | 0x0000000180060e20 | 0x00060e20
`LsaIGetForestTrustInformation` | 77 (0x4d) | Exported Function | 0x00000001800f8270 | 0x000f8270
`LsaIGetLogonGuid` | 78 (0x4e) | Exported Function | 0x00000001800db380 | 0x000db380
`LsaIGetNameFromLuid` | 79 (0x4f) | Exported Function | 0x00000001800baac0 | 0x000baac0
`LsaIGetNbAndDnsDomainNames` | 80 (0x50) | Exported Function | 0x000000018003d950 | 0x0003d950
`LsaIGetNego2Package` | 81 (0x51) | Exported Function | 0x0000000180059a50 | 0x00059a50
`LsaIGetRemoteCredGuardLogonBuffer` | 82 (0x52) | Exported Function | 0x00000001800c99a0 | 0x000c99a0
`LsaIGetRemoteCredGuardSupplementalCreds` | 83 (0x53) | Exported Function | 0x00000001800c9a70 | 0x000c9a70
`LsaIGetSiteName` | 84 (0x54) | Exported Function | 0x00000001800f82c0 | 0x000f82c0
`LsaIIsTargetPrivate` | 98 (0x62) | Exported Function | 0x00000001800cb960 | 0x000cb960
`LsaIIsSuppressChannelBindingInfo` | 97 (0x61) | Exported Function | 0x00000001800c6dc0 | 0x000c6dc0
`LsaIIsMachineSecureByDefault` | 96 (0x60) | Exported Function | 0x00000001800dcfd0 | 0x000dcfd0
`LsaIIsLocalHost` | 95 (0x5f) | Exported Function | 0x00000001800c6080 | 0x000c6080
`LsaIIsLastInteractiveLogonInfoEnabled` | 94 (0x5e) | Exported Function | 0x000000018003fbe0 | 0x0003fbe0
`LsaIIsInEmulatedDomainJoinMode` | 93 (0x5d) | Exported Function | 0x00000001800a8f60 | 0x000a8f60
`LsaIIsUserMSA` | 100 (0x64) | Exported Function | 0x00000001800dccd0 | 0x000dccd0
`LsaIIsDsPaused` | 92 (0x5c) | Exported Function | 0x00000001800f83b0 | 0x000f83b0
`LsaIIsContainerized` | 90 (0x5a) | Exported Function | 0x00000001800a8f50 | 0x000a8f50
`LsaIInitializeNetlogonFuncPtrs` | 89 (0x59) | Exported Function | 0x00000001800dcfb0 | 0x000dcfb0
`LsaIImpersonateClient` | 88 (0x58) | Exported Function | 0x000000018003fb00 | 0x0003fb00
`LsaIHealthCheck` | 87 (0x57) | Exported Function | 0x000000018005a580 | 0x0005a580
`LsaIGetTokenInformationForLocalUser` | 86 (0x56) | Exported Function | 0x00000001800dccc0 | 0x000dccc0
`LsaIGetSupplementalTokenInfo` | 85 (0x55) | Exported Function | 0x000000018003c7c0 | 0x0003c7c0
`LsaIIsDomainWithinForest` | 91 (0x5b) | Exported Function | 0x00000001800f8310 | 0x000f8310
`ServiceInit` | 272 (0x110) | Exported Function | 0x0000000180054980 | 0x00054980


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: lsasrv.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d68ba79a092b4efd9cbb22d1c752a35c6c85fc40d9372cfeb350167e33693760/detection/


## Possible Misuse

*The following table contains possible examples of `lsasrv.dll` being misused. While `lsasrv.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`lsasrv.exe`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [airbnb_binaryalert.yar](https://github.com/Neo23x0/signature-base/blob/master/vendor/yara/airbnb_binaryalert.yar) | $s2 = "lsasrv!g_MasterKeyCacheList" fullword ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger_trendmicro.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger_trendmicro.yar) | $str1 = "Fail To Load LSASRV" nocase wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_passthehashtoolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_passthehashtoolkit.yar) | $s0 = "LSASRV.DLL" fullword ascii /* score: '21.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_passthehashtoolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_passthehashtoolkit.yar) | $s7 = "Checking LSASRV.DLL...." fullword ascii /* score: '12.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s16 = ".\\lsasrv.pdb" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_badrabbit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_badrabbit.yar) | $s2 = "lsasrv" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


