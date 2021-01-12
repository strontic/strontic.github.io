---
title: wintrust.dll | Microsoft Trust Verification APIs
excerpt: What is wintrust.dll?
---

# wintrust.dll 

* File Path: `C:\Program Files (x86)\Windows Kits\10\App Certification Kit\wintrust.dll`
* Description: Microsoft Trust Verification APIs

## Hashes

Type | Hash
-- | --
MD5 | `77DD662A14FFA41FF1245989C6492DC2`
SHA1 | `048DAE934C14079136A31DEA18401520EE114183`
SHA256 | `5F763147E9D11CBCE01CC34F6995A2FF4FFCF565296C1FE6F83D532563FEF0FF`
SHA384 | `A5CAD8BFAD68069AE79E6F7A3C8A1EC5A92FEE01D4DFA4A7EC49B663B57E8BFA164716914AA1795D74886A31B4554A62`
SHA512 | `826A8DF35F5AE008420AD0EA4A9808AC44ADE22A793911C073D334D6F799B6234C94245B1F5F3BA492163F0371ECE3A6661CB637487ED3247129344212A6AE01`
SSDEEP | `6144:U/x2+lF8O8pPC5ZiL9pxsrsZDgPoOtsXJ59qgsJ85zXn:Sx2+njKLfVZgPeJHqgsJOXn`
IMP | `1462E35AAABFF9CCC2D4FD42DDF692B4`
PESHA1 | `3EE7DC66D13623C7C017BF17F5C318395EC98525`
PE256 | `9592DA52C31849D99A060645C6C5378BF7A0D9B695FC10C54DC5F68B3D7F9129`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`WintrustSetRegPolicyFlags` | 147 | Exported Function
`WintrustSetDefaultIncludePEPageHashes` | 146 | Exported Function
`WinVerifyTrustEx` | 134 | Exported Function
`WinVerifyTrust` | 133 | Exported Function
`WintrustRemoveActionID` | 145 | Exported Function
`WintrustGetDefaultForUsage` | 142 | Exported Function
`WintrustCryptSIPRetrieveSubjectGuid` | 141 | Exported Function
`WintrustLoadFunctionPointers` | 144 | Exported Function
`WintrustGetRegPolicyFlags` | 143 | Exported Function
`WTHelperGetFileHash` | 92 | Exported Function
`WTHelperGetFileHandle` | 91 | Exported Function
`WTHelperGetKnownUsages` | 94 | Exported Function
`WTHelperGetFileName` | 93 | Exported Function
`WTHelperGetAgencyInfo` | 90 | Exported Function
`WTHelperCertFindIssuerCertificate` | 10 | Exported Function
`WTHelperCertCheckValidSignature` | 87 | Exported Function
`WTHelperCheckCertUsage` | 89 | Exported Function
`WTHelperCertIsSelfSigned` | 88 | Exported Function
`WintrustCryptSIPLoad` | 140 | Exported Function
`SoftpubLoadMessage` | 80 | Exported Function
`SoftpubLoadDefUsageCallData` | 9 | Exported Function
`TrustDecode` | 82 | Exported Function
`SoftpubLoadSignature` | 81 | Exported Function
`SoftpubInitialize` | 79 | Exported Function
`SoftpubDllUnregisterServer` | 77 | Exported Function
`SoftpubDllRegisterServer` | 76 | Exported Function
`SoftpubFreeDefUsageCallData` | 8 | Exported Function
`SoftpubDumpStructure` | 78 | Exported Function
`WintrustCertificateTrust` | 137 | Exported Function
`WintrustAddDefaultForUsage` | 136 | Exported Function
`WintrustCryptSIPGetSealedDigest` | 139 | Exported Function
`WintrustCryptSIPGetCaps` | 138 | Exported Function
`WintrustAddActionID` | 135 | Exported Function
`TrustFreeDecode` | 84 | Exported Function
`TrustFindIssuerCertificate` | 83 | Exported Function
`TrustOpenStores` | 86 | Exported Function
`TrustIsCertificateSelfSigned` | 85 | Exported Function
`WTHelperGetProvCertFromChain` | 95 | Exported Function
`WVTAsn1SpcMinimalCriteriaInfoDecode` | 121 | Exported Function
`WVTAsn1SpcLinkEncode` | 120 | Exported Function
`WVTAsn1SpcPeImageDataDecode` | 123 | Exported Function
`WVTAsn1SpcMinimalCriteriaInfoEncode` | 122 | Exported Function
`WVTAsn1SpcLinkDecode` | 119 | Exported Function
`WVTAsn1SpcFinancialCriteriaInfoEncode` | 116 | Exported Function
`WVTAsn1SpcFinancialCriteriaInfoDecode` | 115 | Exported Function
`WVTAsn1SpcIndirectDataContentEncode` | 118 | Exported Function
`WVTAsn1SpcIndirectDataContentDecode` | 117 | Exported Function
`WVTAsn1SpcSpOpusInfoEncode` | 130 | Exported Function
`WVTAsn1SpcSpOpusInfoDecode` | 129 | Exported Function
`WVTAsn1SpcStatementTypeEncode` | 132 | Exported Function
`WVTAsn1SpcStatementTypeDecode` | 131 | Exported Function
`WVTAsn1SpcSpAgencyInfoEncode` | 128 | Exported Function
`WVTAsn1SpcSigInfoDecode` | 125 | Exported Function
`WVTAsn1SpcPeImageDataEncode` | 124 | Exported Function
`WVTAsn1SpcSpAgencyInfoDecode` | 127 | Exported Function
`WVTAsn1SpcSigInfoEncode` | 126 | Exported Function
`WVTAsn1SealingTimestampAttributeEncode` | 114 | Exported Function
`WTHelperProvDataFromStateData` | 102 | Exported Function
`WTHelperOpenKnownStores` | 101 | Exported Function
`WVTAsn1CatMemberInfo2Encode` | 104 | Exported Function
`WVTAsn1CatMemberInfo2Decode` | 103 | Exported Function
`WTHelperIsInRootStore` | 100 | Exported Function
`WTHelperGetProvSignerFromChain` | 97 | Exported Function
`WTHelperGetProvPrivateDataFromChain` | 96 | Exported Function
`WTHelperIsChainedToMicrosoftFromStateData` | 99 | Exported Function
`WTHelperIsChainedToMicrosoft` | 98 | Exported Function
`WVTAsn1SealingSignatureAttributeDecode` | 111 | Exported Function
`WVTAsn1IntentToSealAttributeEncode` | 110 | Exported Function
`WVTAsn1SealingTimestampAttributeDecode` | 113 | Exported Function
`WVTAsn1SealingSignatureAttributeEncode` | 112 | Exported Function
`WVTAsn1IntentToSealAttributeDecode` | 109 | Exported Function
`WVTAsn1CatMemberInfoEncode` | 106 | Exported Function
`WVTAsn1CatMemberInfoDecode` | 105 | Exported Function
`WVTAsn1CatNameValueEncode` | 108 | Exported Function
`WVTAsn1CatNameValueDecode` | 107 | Exported Function
`SoftpubDefCertInit` | 7 | Exported Function
`CryptCATClose` | 36 | Exported Function
`CryptCATCDFOpen` | 34 | Exported Function
`CryptCATEnumerateCatAttr` | 38 | Exported Function
`CryptCATEnumerateAttr` | 37 | Exported Function
`CryptCATCDFEnumMembersByCDFTagEx` | 33 | Exported Function
`CryptCATCDFEnumCatAttributes` | 30 | Exported Function
`CryptCATCDFEnumAttributesWithCDFTag` | 29 | Exported Function
`CryptCATCDFEnumMembersByCDFTag` | 32 | Exported Function
`CryptCATCDFEnumMembers` | 31 | Exported Function
`CryptCATOpen` | 45 | Exported Function
`CryptCATHandleFromStore` | 44 | Exported Function
`CryptCATPutAttrInfo` | 47 | Exported Function
`CryptCATPersistStore` | 46 | Exported Function
`CryptCATGetMemberInfo` | 43 | Exported Function
`CryptCATFreeSortedMemberInfo` | 40 | Exported Function
`CryptCATEnumerateMember` | 39 | Exported Function
`CryptCATGetCatAttrInfo` | 42 | Exported Function
`CryptCATGetAttrInfo` | 41 | Exported Function
`CryptCATCDFEnumAttributes` | 28 | Exported Function
`CryptCATAdminAddCatalog` | 17 | Exported Function
`CryptCATAdminAcquireContext2` | 16 | Exported Function
`CryptCATAdminCalcHashFromFileHandle2` | 19 | Exported Function
`CryptCATAdminCalcHashFromFileHandle` | 18 | Exported Function
`CryptCATAdminAcquireContext` | 15 | Exported Function
`CatalogCompactHashDatabase` | 12 | Exported Function
`AddPersonalTrustDBPages` | 11 | Exported Function
`ConfigCiPackageFamilyNameCheck` | 14 | Exported Function
`ConfigCiFinalPolicy` | 13 | Exported Function
`CryptCATAllocSortedMemberInfo` | 26 | Exported Function
`CryptCATAdminResolveCatalogPath` | 25 | Exported Function
`CryptCATCDFClose` | 27 | Exported Function
`CryptCATCatalogInfoFromContext` | 35 | Exported Function
`CryptCATAdminRemoveCatalog` | 24 | Exported Function
`CryptCATAdminPauseServiceForBackup` | 21 | Exported Function
`CryptCATAdminEnumCatalogFromHash` | 20 | Exported Function
`CryptCATAdminReleaseContext` | 23 | Exported Function
`CryptCATAdminReleaseCatalogContext` | 22 | Exported Function
`CryptCATPutCatAttrInfo` | 48 | Exported Function
`mscat32DllUnregisterServer` | 149 | Exported Function
`mscat32DllRegisterServer` | 148 | Exported Function
`MsCatFreeHashTag` | 68 | Exported Function
`MsCatConstructHashTag` | 67 | Exported Function
`IsCatalogFile` | 66 | Exported Function
`GetAuthenticodeSha256Hash` | 64 | Exported Function
`GenericChainFinalProv` | 5 | Exported Function
`HTTPSFinalProv` | 65 | Exported Function
`HTTPSCertificateTrust` | 6 | Exported Function
`SoftpubAuthenticode` | 73 | Exported Function
`OpenPersonalTrustDBDialogEx` | 72 | Exported Function
`SoftpubCleanup` | 75 | Exported Function
`SoftpubCheckCert` | 74 | Exported Function
`OpenPersonalTrustDBDialog` | 71 | Exported Function
`mssip32DllUnregisterServer` | 151 | Exported Function
`mssip32DllRegisterServer` | 150 | Exported Function
`OfficeInitializePolicy` | 70 | Exported Function
`OfficeCleanupPolicy` | 69 | Exported Function
`GenericChainCertificateTrust` | 4 | Exported Function
`CryptSIPGetRegWorkingFlags` | 3 | Exported Function
`CryptSIPGetInfo` | 2 | Exported Function
`CryptSIPGetSignedDataMsg` | 54 | Exported Function
`CryptSIPGetSealedDigest` | 53 | Exported Function
`CryptSIPGetCaps` | 52 | Exported Function
`CryptCATStoreFromHandle` | 50 | Exported Function
`CryptCATPutMemberInfo` | 49 | Exported Function
`CryptSIPCreateIndirectData` | 51 | Exported Function
`CryptCATVerifyMember` | 1 | Exported Function
`DriverFinalPolicy` | 61 | Exported Function
`DriverCleanupPolicy` | 60 | Exported Function
`FindCertsByIssuer` | 63 | Exported Function
`DriverInitializePolicy` | 62 | Exported Function
`DllUnregisterServer` | 59 | Exported Function
`CryptSIPRemoveSignedDataMsg` | 56 | Exported Function
`CryptSIPPutSignedDataMsg` | 55 | Exported Function
`DllRegisterServer` | 58 | Exported Function
`CryptSIPVerifyIndirectData` | 57 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WINTRUST.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\wintrust.dll](wintrust.dll-4F6B7467D69BF875B9EED5340FABA75B.md) | 97




MIT License. Copyright (c) 2020 Strontic.


