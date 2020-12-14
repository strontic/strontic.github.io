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

Function Name | Ordinal | Type
-- | -- | --
`LsapDbExpConvertReadLockTrustedDomainListToExclusive` | 182 | Exported Function
`LsapDbExpConvertWriteLockTrustedDomainListToShared` | 183 | Exported Function
`LsapDbExpAcquireReadLockTrustedDomainList` | 180 | Exported Function
`LsapDbExpAcquireWriteLockTrustedDomainList` | 181 | Exported Function
`LsapDbExpIsLockedTrustedDomainList` | 186 | Exported Function
`LsapDbExpMakeCacheBuilding` | 187 | Exported Function
`LsapDbExpIsCacheBuilding` | 184 | Exported Function
`LsapDbExpIsCacheValid` | 185 | Exported Function
`LsapDbEnumerateTrustedDomainsEx` | 179 | Exported Function
`LsapDbCreateObject` | 173 | Exported Function
`LsapDbDeleteAttributesObject` | 174 | Exported Function
`LsapDbCopyUnicodeAttribute` | 171 | Exported Function
`LsapDbCopyUnicodeAttributeNoAlloc` | 172 | Exported Function
`LsapDbDereferenceObject` | 177 | Exported Function
`LsapDbEnumerateSids` | 178 | Exported Function
`LsapDbDeleteObject` | 175 | Exported Function
`LsapDbDereferenceHandle` | 176 | Exported Function
`LsapDbLookupCreateListReferencedDomains` | 199 | Exported Function
`LsapDbLookupGetDomainInfo` | 200 | Exported Function
`LsapDbIsStatusConnectionFailure` | 197 | Exported Function
`LsapDbLookupAddListReferencedDomains` | 198 | Exported Function
`LsapDbLookupNameChainRequest` | 203 | Exported Function
`LsapDbLookupNamesInPrimaryDomain` | 204 | Exported Function
`LsapDbLookupListReferencedDomains` | 201 | Exported Function
`LsapDbLookupMergeDisjointReferencedDomains` | 202 | Exported Function
`LsapDbInitializeAttribute` | 196 | Exported Function
`LsapDbExpReleaseLockTrustedDomainList` | 190 | Exported Function
`LsapDbFreeAttributes` | 191 | Exported Function
`LsapDbExpMakeCacheInvalid` | 188 | Exported Function
`LsapDbExpMakeCacheValid` | 189 | Exported Function
`LsapDbGetDbPolicyHandle` | 194 | Exported Function
`LsapDbGetSecretType` | 195 | Exported Function
`LsapDbFreeTrustedDomainsEx` | 192 | Exported Function
`LsapDbGetDbObjectTypeName` | 193 | Exported Function
`LsapDbCloseObject` | 170 | Exported Function
`LsaIVerifyCachability` | 147 | Exported Function
`LsaIWriteAuditEvent` | 148 | Exported Function
`LsaIUserProfileLoaded` | 145 | Exported Function
`LsaIValidateTargetInfo` | 146 | Exported Function
`LsapAdtAuditingEnabledBySubCategory` | 151 | Exported Function
`LsapAdtAuditingEnabledHint` | 152 | Exported Function
`LsaIWriteKdcAuthenticationEvent` | 149 | Exported Function
`LsapAdtAuditingEnabledByLogonId` | 150 | Exported Function
`LsaIUpdateLogonSession` | 144 | Exported Function
`LsaITransformAuthorizationData` | 138 | Exported Function
`LsaIUnregisterAllPolicyChangeNotificationCallback` | 139 | Exported Function
`LsaISetTokenDacl` | 136 | Exported Function
`LsaISetUserFlags` | 137 | Exported Function
`LsaIUpdateForestTrustInformation` | 142 | Exported Function
`LsaIUpdateKerbMaxTokenSize` | 143 | Exported Function
`LsaIUnregisterLogonSessionCallback` | 140 | Exported Function
`LsaIUnregisterPolicyChangeNotificationCallback` | 141 | Exported Function
`LsapCrServerGetSessionKey` | 164 | Exported Function
`LsapCrServerGetSessionKeySafe` | 165 | Exported Function
`LsapCloseHandle` | 162 | Exported Function
`LsapCompareDomainNames` | 163 | Exported Function
`LsapDbBuildObjectCaches` | 168 | Exported Function
`LsapDbCloseHandle` | 169 | Exported Function
`LsapDbAcquireLockEx` | 166 | Exported Function
`LsapDbApplyTransaction` | 167 | Exported Function
`LsapCheckBootMode` | 161 | Exported Function
`LsapAdtWriteLog` | 155 | Exported Function
`LsapAllocateLsaHeap` | 156 | Exported Function
`LsapAdtGetCallerProcessInfo` | 153 | Exported Function
`LsapAdtInitParametersArray` | 154 | Exported Function
`LsapAuOpenSam` | 158 | Exported Function
`LsapBuildPrivilegeAuditString` | 160 | Exported Function
`LsapAllocatePrivateHeap` | 157 | Exported Function
`LsapAuditFailed` | 159 | Exported Function
`LsapSetErrorInfo` | 251 | Exported Function
`LsapSidListSize` | 252 | Exported Function
`LsapRtlValidateControllerTrustedDomain` | 249 | Exported Function
`LsapRtlValidateControllerTrustedDomainByHandle` | 250 | Exported Function
`LsapTruncateUnicodeString` | 255 | Exported Function
`LsarClose` | 256 | Exported Function
`LsapTraceEvent` | 253 | Exported Function
`LsapTraceEventWithData` | 254 | Exported Function
`LsapRpcCopyUnicodeString` | 248 | Exported Function
`LsapIsBuiltinDomain` | 242 | Exported Function
`LsapIsSamOpened` | 243 | Exported Function
`LsapInitializeLsaDb` | 241 | Exported Function
`LsapInitLsa` | 240 | Exported Function
`LsapRemoveTrailingDot` | 246 | Exported Function
`LsapRpcCopySid` | 247 | Exported Function
`LsapOpenSam` | 244 | Exported Function
`LsapQueryClientInfo` | 245 | Exported Function
`LsarSetInformationPolicy` | 268 | Exported Function
`LsarSetSecret` | 269 | Exported Function
`LsarQueryTrustedDomainInfoByName` | 266 | Exported Function
`LsarRetrievePrivateData` | 267 | Exported Function
`QueryLsaInterface` | 2 | Exported Function
`ServiceInit` | 272 | Exported Function
`LsarSetTrustedDomainInfoByName` | 270 | Exported Function
`LsarStorePrivateData` | 271 | Exported Function
`LsarQuerySecret` | 265 | Exported Function
`LsarEnumerateTrustedDomainsEx` | 259 | Exported Function
`LsarLookupSids` | 260 | Exported Function
`LsarCreateSecret` | 257 | Exported Function
`LsarDeleteObject` | 258 | Exported Function
`LsarQueryDomainInformationPolicy` | 263 | Exported Function
`LsarQueryInformationPolicy` | 264 | Exported Function
`LsarOpenPolicy` | 261 | Exported Function
`LsarOpenSecret` | 262 | Exported Function
`LsapGetWellKnownSid` | 239 | Exported Function
`LsapDbSidToLogicalNameObject` | 216 | Exported Function
`LsapDbSlowEnumerateTrustedDomains` | 217 | Exported Function
`LsapDbReleaseLockEx` | 214 | Exported Function
`LsapDbSecretIsMachineAcc` | 215 | Exported Function
`LsapDbVerifyInfoQueryTrustedDomain` | 220 | Exported Function
`LsapDbVerifyInfoSetTrustedDomain` | 221 | Exported Function
`LsapDbUpdateCountCompUnmappedNames` | 218 | Exported Function
`LsapDbVerifyHandle` | 219 | Exported Function
`LsapDbReferenceObject` | 213 | Exported Function
`LsapDbMakeSidAttribute` | 207 | Exported Function
`LsapDbMakeUnicodeAttribute` | 208 | Exported Function
`LsapDbLookupSidsInPrimaryDomain` | 205 | Exported Function
`LsapDbMakeGuidAttribute` | 206 | Exported Function
`LsapDbReadAttribute` | 211 | Exported Function
`LsapDbReadAttributesObject` | 212 | Exported Function
`LsapDbOpenObject` | 209 | Exported Function
`LsapDbQueryInformationPolicy` | 210 | Exported Function
`LsapGetCapeNamesForCap` | 233 | Exported Function
`LsapGetGlobalRestrictAnonymous` | 234 | Exported Function
`LsapFreeString` | 231 | Exported Function
`LsapGetAccountDomainHandle` | 232 | Exported Function
`LsapGetLookupRestrictIsolatedNameLevel` | 237 | Exported Function
`LsapGetPolicyHandle` | 238 | Exported Function
`LsapGetHourlyLogLevel` | 235 | Exported Function
`LsapGetLogonSessionAccountInfoEx` | 236 | Exported Function
`LsapFreePrivateHeap` | 230 | Exported Function
`LsapDsInitializeDsStateInfo` | 224 | Exported Function
`LsapDssetupInitializeGetPrimaryDomainInformationOpState` | 226 | Exported Function
`LsapDbWriteAttributesObject` | 222 | Exported Function
`LsapDomainRenameHandlerForLogonSessions` | 223 | Exported Function
`LsapDuplicateString` | 228 | Exported Function
`LsapFreeLsaHeap` | 229 | Exported Function
`LsapDsUnitializeDsStateInfo` | 225 | Exported Function
`LsapDuplicateSid` | 227 | Exported Function
`LsaIFlushIdentityCacheForSid` | 44 | Exported Function
`LsaIForestTrustFindMatch` | 45 | Exported Function
`LsaIFilterNamespace` | 42 | Exported Function
`LsaIFilterSids` | 43 | Exported Function
`LsaIFree_LSAI_PRIVATE_DATA` | 50 | Exported Function
`LsaIFree_LSAI_SECRET_ENUM_BUFFER` | 51 | Exported Function
`LsaIFree_LSA_FOREST_TRUST_COLLISION_INFORMATION` | 72 | Exported Function
`LsaIFree_LSA_FOREST_TRUST_INFORMATION` | 73 | Exported Function
`LsaIEventWritePackageNotCacheLogonUser` | 41 | Exported Function
`LsaIDeriveCredentialKey` | 35 | Exported Function
`LsaIDsNotifiedObjectChange` | 36 | Exported Function
`LsaICryptUnprotectDataEx` | 33 | Exported Function
`LsaIDereferenceCredHandle` | 34 | Exported Function
`LsaIEqualSupplementalTokenInfo` | 39 | Exported Function
`LsaIEventWritePackageNoCredential` | 40 | Exported Function
`LsaIEfsAcceptSmartcardCredentials` | 37 | Exported Function
`LsaIEqualLogonProcessName` | 38 | Exported Function
`LsaIFree_LSAPR_SR_SECURITY_DESCRIPTOR` | 59 | Exported Function
`LsaIFree_LSAPR_TRANSLATED_NAMES` | 60 | Exported Function
`LsaIFree_LSAPR_PRIVILEGE_SET` | 57 | Exported Function
`LsaIFree_LSAPR_REFERENCED_DOMAIN_LIST` | 58 | Exported Function
`LsaIFree_LSAPR_TRUSTED_DOMAIN_INFO` | 62 | Exported Function
`LsaIFree_LSAPR_TRUSTED_ENUM_BUFFER` | 63 | Exported Function
`LsaIFree_LSAPR_TRANSLATED_SIDS` | 61 | Exported Function
`LsaIFree_LSAPR_TRUST_INFORMATION` | 65 | Exported Function
`LsaIFree_LSAPR_PRIVILEGE_ENUM_BUFFER` | 56 | Exported Function
`LsaIFree_LSAP_SUBNET_INFO` | 70 | Exported Function
`LsaIFree_LSAP_UPN_SUFFIXES` | 71 | Exported Function
`LsaIFree_LSAP_SITE_INFO` | 69 | Exported Function
`LsaIFree_LSAP_SITENAME_INFO` | 68 | Exported Function
`LsaIFree_LSAPR_POLICY_DOMAIN_INFORMATION` | 54 | Exported Function
`LsaIFree_LSAPR_POLICY_INFORMATION` | 55 | Exported Function
`LsaIFree_LSAPR_ACCOUNT_ENUM_BUFFER` | 52 | Exported Function
`LsaIFree_LSAPR_CR_CIPHER_VALUE` | 53 | Exported Function
`LsaICryptUnprotectData` | 32 | Exported Function
`LsaIAllocateHeapZero` | 9 | Exported Function
`LsaIAllowProtectedCredLogon` | 10 | Exported Function
`LsaIAdtAuditingEnabledBySubCategory` | 7 | Exported Function
`LsaIAllocateHeap` | 8 | Exported Function
`LsaIAuditInitializeParametersAndWriteEvent` | 13 | Exported Function
`LsaIAuditKdcEvent` | 14 | Exported Function
`LsaIAuditAccountLogon` | 11 | Exported Function
`LsaIAuditAccountLogonEx` | 12 | Exported Function
`LsaIAdtAuditingEnabledByCategory` | 6 | Exported Function
`_fgs__LSAPR_TRUSTED_ENUM_BUFFER_EX` | 274 | Exported Function
`_fgu__LSAPR_TRUSTED_DOMAIN_INFO` | 276 | Exported Function
`_fgs__LSAPR_TRUST_INFORMATION` | 275 | Exported Function
`_fgs__LSAPR_TRUSTED_ENUM_BUFFER` | 273 | Exported Function
`LsaIAddNamesToLogonSession` | 4 | Exported Function
`LsaIAdjustTokenObjectIntegrity` | 5 | Exported Function
`InitializeLsaExtension` | 1 | Exported Function
`LsaDbLookupSidChainRequest` | 3 | Exported Function
`LsaIChangeSecretCipherKey` | 26 | Exported Function
`LsaICheckProtectedUserByTokenInfo` | 27 | Exported Function
`LsaICallPackagePassthrough` | 24 | Exported Function
`LsaICancelNotification` | 25 | Exported Function
`LsaICryptProtectData` | 30 | Exported Function
`LsaICryptProtectDataEx` | 31 | Exported Function
`LsaICheckRestrictedMode` | 28 | Exported Function
`LsaIClearOldSyskey` | 29 | Exported Function
`LsaICallPackageEx` | 23 | Exported Function
`LsaIAuditLogonUsingExplicitCreds` | 17 | Exported Function
`LsaIAuditNotifyPackageLoad` | 18 | Exported Function
`LsaIAuditKerberosLogon` | 15 | Exported Function
`LsaIAuditLogonEx` | 16 | Exported Function
`LsaIAuditSamEvent` | 21 | Exported Function
`LsaICallPackage` | 22 | Exported Function
`LsaIAuditPasswordAccessEvent` | 19 | Exported Function
`LsaIAuditReplay` | 20 | Exported Function
`LsaIQueryForestTrustInfo` | 113 | Exported Function
`LsaIQueryForestTrustInformation` | 114 | Exported Function
`LsaINotifyPasswordChanged` | 111 | Exported Function
`LsaIOpenPolicyTrusted` | 112 | Exported Function
`LsaIQuerySiteInfo` | 117 | Exported Function
`LsaIQuerySubnetInfo` | 118 | Exported Function
`LsaIQueryInformationPolicyTrusted` | 115 | Exported Function
`LsaIQueryPackageAttrInLogonSession` | 116 | Exported Function
`LsaINotifyNewPassword` | 110 | Exported Function
`LsaIModifyPerformanceCounter` | 104 | Exported Function
`LsaINoConnectedUserPolicy` | 105 | Exported Function
`LsaILookupUserAccountType` | 102 | Exported Function
`LsaILookupWellKnownName` | 103 | Exported Function
`LsaINotifyGCStatusChange` | 108 | Exported Function
`LsaINotifyNetlogonParametersChangeW` | 109 | Exported Function
`LsaINoMoreWin2KDomain` | 106 | Exported Function
`LsaINotifyChangeNotification` | 107 | Exported Function
`LsaISetClientDnsHostName` | 130 | Exported Function
`LsaISetLogonGuidInLogonSession` | 131 | Exported Function
`LsaISamIndicatedDsStarted` | 128 | Exported Function
`LsaISanitizeSAMName` | 129 | Exported Function
`LsaISetPackageAttrInLogonSession` | 134 | Exported Function
`LsaISetSupplementalTokenInfo` | 135 | Exported Function
`LsaISetLogonInfo` | 132 | Exported Function
`LsaISetNewSyskey` | 133 | Exported Function
`LsaISafeMode` | 127 | Exported Function
`LsaIRegisterLogonSessionCallback` | 121 | Exported Function
`LsaIRegisterNotification` | 122 | Exported Function
`LsaIQueryUpnSuffixes` | 119 | Exported Function
`LsaIReferenceCredHandle` | 120 | Exported Function
`LsaIReplicateClientObject` | 125 | Exported Function
`LsaIRetrieveCurrentUserSid` | 126 | Exported Function
`LsaIRegisterPolicyChangeNotificationCallback` | 123 | Exported Function
`LsaIRenewCertificate` | 124 | Exported Function
`LsaIKerberosRegisterTrustNotification` | 101 | Exported Function
`LsaIGetLogonGuid` | 78 | Exported Function
`LsaIGetNameFromLuid` | 79 | Exported Function
`LsaIGetClientOsInfo` | 76 | Exported Function
`LsaIGetForestTrustInformation` | 77 | Exported Function
`LsaIGetRemoteCredGuardLogonBuffer` | 82 | Exported Function
`LsaIGetRemoteCredGuardSupplementalCreds` | 83 | Exported Function
`LsaIGetNbAndDnsDomainNames` | 80 | Exported Function
`LsaIGetNego2Package` | 81 | Exported Function
`LsaIGetCcgClient` | 75 | Exported Function
`LsaIFree_LSAPR_UNICODE_STRING_BUFFER` | 67 | Exported Function
`LsaIFreeForestTrustInfo` | 46 | Exported Function
`LsaIFree_LSAPR_TRUSTED_ENUM_BUFFER_EX` | 64 | Exported Function
`LsaIFree_LSAPR_UNICODE_STRING` | 66 | Exported Function
`LsaIFreeSupplementalTokenInfo` | 49 | Exported Function
`LsaIGetCallInfo` | 74 | Exported Function
`LsaIFreeHeap` | 47 | Exported Function
`LsaIFreeReturnBuffer` | 48 | Exported Function
`LsaIIsLocalHost` | 95 | Exported Function
`LsaIIsMachineSecureByDefault` | 96 | Exported Function
`LsaIIsInEmulatedDomainJoinMode` | 93 | Exported Function
`LsaIIsLastInteractiveLogonInfoEnabled` | 94 | Exported Function
`LsaIIsTrustedDomainsEnabled` | 99 | Exported Function
`LsaIIsUserMSA` | 100 | Exported Function
`LsaIIsSuppressChannelBindingInfo` | 97 | Exported Function
`LsaIIsTargetPrivate` | 98 | Exported Function
`LsaIIsDsPaused` | 92 | Exported Function
`LsaIGetTokenInformationForLocalUser` | 86 | Exported Function
`LsaIHealthCheck` | 87 | Exported Function
`LsaIGetSiteName` | 84 | Exported Function
`LsaIGetSupplementalTokenInfo` | 85 | Exported Function
`LsaIIsContainerized` | 90 | Exported Function
`LsaIIsDomainWithinForest` | 91 | Exported Function
`LsaIImpersonateClient` | 88 | Exported Function
`LsaIInitializeNetlogonFuncPtrs` | 89 | Exported Function


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

*The following table contains possible examples of `lsasrv.dll` being misused. While `lsasrv.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


