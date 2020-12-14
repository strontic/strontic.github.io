---
title: wintrust.dll | Microsoft Trust Verification APIs
excerpt: What is wintrust.dll?
---

# wintrust.dll 

* File Path: `C:\Windows\system32\wintrust.dll`
* Description: Microsoft Trust Verification APIs

## Hashes

Type | Hash
-- | --
MD5 | `78BD0C98D7AA3F5046BEAC2235EC6B4A`
SHA1 | `AAA853E8C33B63392C862F07784AA500E9949D90`
SHA256 | `B3637CE06C96E121BAB826174D8A795AE52379A3259C63F637D0666B70F030F6`
SHA384 | `8F23032F0F5C543CA6E2AB1AA390C3E10E69C8F83631AC9D8FB8A2F259C93CD91A85301D98964A543F9A2643EA2E9353`
SHA512 | `DA86257FB2083C65BBCF228B9117598E24A56BD238776E69C6E95B4609C37CA627CCBBDBEE3DBBDAAF1E016016C6D8529AD0F58CFD75527DD62C94CA764DF6EC`
SSDEEP | `6144:Gl/sX3INJIH/sFG0lq9i08waioVwzQ+nlTGANns9QJPiKamGK/uLX:Gl/sXeA0FtqW5wzgdK/E`
IMP | `1D5D771A656CEFBB064797EFC76F695F`
PESHA1 | `E0AFD42D3370CA8C46D1A0A7FD3ACC3F739DFF00`
PE256 | `04ECF86BC3D84A1A8B333D09D8C9975FA74F6A8DA65946B026EBF76DEC55ADB5`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WTGetPluginSignatureInfo` | 92 | Exported Function
`WTGetBioSignatureInfo` | 91 | Exported Function
`WTHelperCertCheckValidSignature` | 94 | Exported Function
`WTGetSignatureInfo` | 93 | Exported Function
`WTConvertCertCtxToChainInfo` | 90 | Exported Function
`WintrustUserWriteabilityCheck` | 155 | Exported Function
`WintrustSetRegPolicyFlags` | 154 | Exported Function
`WinVerifyTrustEx` | 145 | Exported Function
`WinVerifyTrust` | 144 | Exported Function
`WTHelperCertFindIssuerCertificate` | 11 | Exported Function
`WTHelperGetKnownUsages` | 101 | Exported Function
`WTHelperGetFileName` | 100 | Exported Function
`WTHelperGetProvPrivateDataFromChain` | 103 | Exported Function
`WTHelperGetProvCertFromChain` | 102 | Exported Function
`WTHelperGetFileHash` | 99 | Exported Function
`WTHelperCheckCertUsage` | 96 | Exported Function
`WTHelperCertIsSelfSigned` | 95 | Exported Function
`WTHelperGetFileHandle` | 98 | Exported Function
`WTHelperGetAgencyInfo` | 97 | Exported Function
`WintrustSetDefaultIncludePEPageHashes` | 153 | Exported Function
`SrpCheckSmartlockerEAandProcessToken` | 84 | Exported Function
`SoftpubLoadSignature` | 83 | Exported Function
`TrustFindIssuerCertificate` | 86 | Exported Function
`TrustDecode` | 85 | Exported Function
`SoftpubLoadMessage` | 82 | Exported Function
`SoftpubFreeDefUsageCallData` | 9 | Exported Function
`SoftpubDumpStructure` | 80 | Exported Function
`SoftpubLoadDefUsageCallData` | 10 | Exported Function
`SoftpubInitialize` | 81 | Exported Function
`TrustFreeDecode` | 87 | Exported Function
`WintrustGetRegPolicyFlags` | 150 | Exported Function
`WintrustGetDefaultForUsage` | 149 | Exported Function
`WintrustRemoveActionID` | 152 | Exported Function
`WintrustLoadFunctionPointers` | 151 | Exported Function
`WintrustCertificateTrust` | 148 | Exported Function
`TrustOpenStores` | 89 | Exported Function
`TrustIsCertificateSelfSigned` | 88 | Exported Function
`WintrustAddDefaultForUsage` | 147 | Exported Function
`WintrustAddActionID` | 146 | Exported Function
`WTHelperGetProvSignerFromChain` | 104 | Exported Function
`WVTAsn1SpcLinkEncode` | 131 | Exported Function
`WVTAsn1SpcLinkDecode` | 130 | Exported Function
`WVTAsn1SpcMinimalCriteriaInfoEncode` | 133 | Exported Function
`WVTAsn1SpcMinimalCriteriaInfoDecode` | 132 | Exported Function
`WVTAsn1SpcIndirectDataContentEncode` | 129 | Exported Function
`WVTAsn1SpcFinancialCriteriaInfoDecode` | 126 | Exported Function
`WVTAsn1SealingTimestampAttributeEncode` | 125 | Exported Function
`WVTAsn1SpcIndirectDataContentDecode` | 128 | Exported Function
`WVTAsn1SpcFinancialCriteriaInfoEncode` | 127 | Exported Function
`WVTAsn1SpcPeImageDataDecode` | 134 | Exported Function
`WVTAsn1SpcSpOpusInfoEncode` | 141 | Exported Function
`WVTAsn1SpcSpOpusInfoDecode` | 140 | Exported Function
`WVTAsn1SpcStatementTypeEncode` | 143 | Exported Function
`WVTAsn1SpcStatementTypeDecode` | 142 | Exported Function
`WVTAsn1SpcSpAgencyInfoEncode` | 139 | Exported Function
`WVTAsn1SpcSigInfoDecode` | 136 | Exported Function
`WVTAsn1SpcPeImageDataEncode` | 135 | Exported Function
`WVTAsn1SpcSpAgencyInfoDecode` | 138 | Exported Function
`WVTAsn1SpcSigInfoEncode` | 137 | Exported Function
`WVTAsn1SealingTimestampAttributeDecode` | 124 | Exported Function
`WTLogConfigCiScriptEvent` | 111 | Exported Function
`WTIsFirstConfigCiResultPreferred` | 110 | Exported Function
`WTValidateBioSignaturePolicy` | 113 | Exported Function
`WTLogConfigCiSignerEvent` | 112 | Exported Function
`WTHelperProvDataFromStateData` | 109 | Exported Function
`WTHelperIsChainedToMicrosoftFromStateData` | 106 | Exported Function
`WTHelperIsChainedToMicrosoft` | 105 | Exported Function
`WTHelperOpenKnownStores` | 108 | Exported Function
`WTHelperIsInRootStore` | 107 | Exported Function
`WVTAsn1CatMemberInfo2Decode` | 114 | Exported Function
`WVTAsn1IntentToSealAttributeEncode` | 121 | Exported Function
`WVTAsn1IntentToSealAttributeDecode` | 120 | Exported Function
`WVTAsn1SealingSignatureAttributeEncode` | 123 | Exported Function
`WVTAsn1SealingSignatureAttributeDecode` | 122 | Exported Function
`WVTAsn1CatNameValueEncode` | 119 | Exported Function
`WVTAsn1CatMemberInfoDecode` | 116 | Exported Function
`WVTAsn1CatMemberInfo2Encode` | 115 | Exported Function
`WVTAsn1CatNameValueDecode` | 118 | Exported Function
`WVTAsn1CatMemberInfoEncode` | 117 | Exported Function
`SoftpubDllUnregisterServer` | 79 | Exported Function
`CryptCATCDFOpen` | 36 | Exported Function
`CryptCATCDFEnumMembersByCDFTagEx` | 35 | Exported Function
`CryptCATEnumerateAttr` | 39 | Exported Function
`CryptCATClose` | 38 | Exported Function
`CryptCATCDFEnumMembersByCDFTag` | 34 | Exported Function
`CryptCATCDFEnumAttributesWithCDFTag` | 31 | Exported Function
`CryptCATCDFEnumAttributes` | 30 | Exported Function
`CryptCATCDFEnumMembers` | 33 | Exported Function
`CryptCATCDFEnumCatAttributes` | 32 | Exported Function
`CryptCATEnumerateCatAttr` | 40 | Exported Function
`CryptCATOpen` | 47 | Exported Function
`CryptCATHandleFromStore` | 46 | Exported Function
`CryptCATPutAttrInfo` | 49 | Exported Function
`CryptCATPersistStore` | 48 | Exported Function
`CryptCATGetMemberInfo` | 45 | Exported Function
`CryptCATFreeSortedMemberInfo` | 42 | Exported Function
`CryptCATEnumerateMember` | 41 | Exported Function
`CryptCATGetCatAttrInfo` | 44 | Exported Function
`CryptCATGetAttrInfo` | 43 | Exported Function
`CryptCATCDFClose` | 29 | Exported Function
`CryptCATAdminAcquireContext2` | 17 | Exported Function
`CryptCATAdminAcquireContext` | 16 | Exported Function
`CryptCATAdminCalcHashFromFileHandle` | 19 | Exported Function
`CryptCATAdminAddCatalog` | 18 | Exported Function
`ConfigCiPackageFamilyNameCheck` | 15 | Exported Function
`CatalogCompactHashDatabase` | 13 | Exported Function
`AddPersonalTrustDBPages` | 12 | Exported Function
`ConfigCiFinalPolicy` | 14 | Exported Function
`ComputeFirstPageHash` | 1 | Exported Function
`CryptCATAdminCalcHashFromFileHandle2` | 20 | Exported Function
`CryptCATAdminResolveCatalogPath` | 27 | Exported Function
`CryptCATAdminRemoveCatalog` | 26 | Exported Function
`CryptCATCatalogInfoFromContext` | 37 | Exported Function
`CryptCATAllocSortedMemberInfo` | 28 | Exported Function
`CryptCATAdminReleaseContext` | 25 | Exported Function
`CryptCATAdminEnumCatalogFromHash` | 22 | Exported Function
`CryptCATAdminCalcHashFromFileHandle3` | 21 | Exported Function
`CryptCATAdminReleaseCatalogContext` | 24 | Exported Function
`CryptCATAdminPauseServiceForBackup` | 23 | Exported Function
`CryptCATPutCatAttrInfo` | 50 | Exported Function
`MsCatConstructHashTag` | 69 | Exported Function
`mscat32DllUnregisterServer` | 157 | Exported Function
`mssip32DllRegisterServer` | 158 | Exported Function
`MsCatFreeHashTag` | 70 | Exported Function
`mscat32DllRegisterServer` | 156 | Exported Function
`HTTPSCertificateTrust` | 7 | Exported Function
`GetAuthenticodeSha256Hash` | 66 | Exported Function
`IsCatalogFile` | 68 | Exported Function
`HTTPSFinalProv` | 67 | Exported Function
`mssip32DllUnregisterServer` | 159 | Exported Function
`SoftpubCleanup` | 77 | Exported Function
`SoftpubCheckCert` | 76 | Exported Function
`SoftpubDllRegisterServer` | 78 | Exported Function
`SoftpubDefCertInit` | 8 | Exported Function
`SoftpubAuthenticode` | 75 | Exported Function
`OfficeInitializePolicy` | 72 | Exported Function
`OfficeCleanupPolicy` | 71 | Exported Function
`OpenPersonalTrustDBDialogEx` | 74 | Exported Function
`OpenPersonalTrustDBDialog` | 73 | Exported Function
`GenericChainFinalProv` | 6 | Exported Function
`CryptSIPGetRegWorkingFlags` | 4 | Exported Function
`CryptSIPGetInfo` | 3 | Exported Function
`CryptSIPGetSignedDataMsg` | 56 | Exported Function
`CryptSIPGetSealedDigest` | 55 | Exported Function
`CryptSIPGetCaps` | 54 | Exported Function
`CryptCATStoreFromHandle` | 52 | Exported Function
`CryptCATPutMemberInfo` | 51 | Exported Function
`CryptSIPCreateIndirectData` | 53 | Exported Function
`CryptCATVerifyMember` | 2 | Exported Function
`CryptSIPPutSignedDataMsg` | 57 | Exported Function
`DriverInitializePolicy` | 64 | Exported Function
`DriverFinalPolicy` | 63 | Exported Function
`GenericChainCertificateTrust` | 5 | Exported Function
`FindCertsByIssuer` | 65 | Exported Function
`DriverCleanupPolicy` | 62 | Exported Function
`CryptSIPVerifyIndirectData` | 59 | Exported Function
`CryptSIPRemoveSignedDataMsg` | 58 | Exported Function
`DllUnregisterServer` | 61 | Exported Function
`DllRegisterServer` | 60 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINTRUST.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.423 (WinBuild.160101.0800)
* Product Version: 10.0.19041.423
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/b3637ce06c96e121bab826174d8a795ae52379a3259c63f637d0666b70f030f6/detection/





MIT License. Copyright (c) 2020 Strontic.


