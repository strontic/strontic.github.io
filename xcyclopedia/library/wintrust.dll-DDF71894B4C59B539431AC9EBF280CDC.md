---
title: wintrust.dll | Microsoft Trust Verification APIs
excerpt: What is wintrust.dll?
---

# wintrust.dll 

* File Path: `C:\Windows\SysWOW64\wintrust.dll`
* Description: Microsoft Trust Verification APIs

## Hashes

Type | Hash
-- | --
MD5 | `DDF71894B4C59B539431AC9EBF280CDC`
SHA1 | `BD142FBAE2160DB48673CE865A79E7E7DE8DC505`
SHA256 | `2640C5C44A74F92CE9B49057B0BF13753531D2F1E34019E138FBCB305BC4722E`
SHA384 | `E285AC2AA1C201742944392CF17FD146FF838EE3BE7CBD56E8B6EC9BFE03DECCB6634B01FCBF0297DF88BEDDA1C5F4B5`
SHA512 | `68E4DCA30241065167D3CAB79A715B76255E46AAD0BB37F3D89A02F0A42BA16B8702ED30FA13BC12AA909D5330BD9100DA7A91959AB6EA29AC34CE3C731009FD`
SSDEEP | `6144:IQ4eqwfDE9u5/oEM0nYxxYOfSdtypWJS0Vcwm+KErng:vqS4C/oEMdZSd4pWJ5nKEk`
IMP | `6033F0783D372BAFC0F54C4546B04D24`
PESHA1 | `0BCD45CD13E58556F278AD516265FC1972BAAB82`
PE256 | `88730E23A2348152CD78329CA24F1D4E1B6ACFC6ECD411EE1CF71BAFB9F67DF2`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddPersonalTrustDBPages` | 12 (0xc) | Exported Function | 0x4762bfc0 | 0x0002bfc0
`WintrustUserWriteabilityCheck` | 155 (0x9b) | Exported Function | 0x4762e3b0 | 0x0002e3b0
`WinVerifyTrust` | 144 (0x90) | Exported Function | 0x4760b340 | 0x0000b340
`WinVerifyTrustEx` | 145 (0x91) | Exported Function | 0x47622250 | 0x00022250
`WTConvertCertCtxToChainInfo` | 90 (0x5a) | Exported Function | 0x4762dcc0 | 0x0002dcc0
`WTGetBioSignatureInfo` | 91 (0x5b) | Exported Function | 0x47623a90 | 0x00023a90
`WTGetPluginSignatureInfo` | 92 (0x5c) | Exported Function | 0x47623c10 | 0x00023c10
`WTGetSignatureInfo` | 93 (0x5d) | Exported Function | 0x476107d0 | 0x000107d0
`WintrustSetRegPolicyFlags` | 154 (0x9a) | Exported Function | 0x476211f0 | 0x000211f0
`WTHelperCertCheckValidSignature` | 94 (0x5e) | Exported Function | 0x476223a0 | 0x000223a0
`WTHelperCertIsSelfSigned` | 95 (0x5f) | Exported Function | 0x4761efe0 | 0x0001efe0
`WTHelperCheckCertUsage` | 96 (0x60) | Exported Function | 0x476223d0 | 0x000223d0
`WTHelperGetAgencyInfo` | 97 (0x61) | Exported Function | 0x476224c0 | 0x000224c0
`WTHelperGetFileHandle` | 98 (0x62) | Exported Function | 0x47622550 | 0x00022550
`WTHelperGetFileHash` | 99 (0x63) | Exported Function | 0x47622190 | 0x00022190
`WTHelperGetFileName` | 100 (0x64) | Exported Function | 0x4760fc70 | 0x0000fc70
`WTHelperGetKnownUsages` | 101 (0x65) | Exported Function | 0x47622590 | 0x00022590
`WTHelperCertFindIssuerCertificate` | 11 (0xb) | Exported Function | 0x4761efb0 | 0x0001efb0
`WTHelperGetProvCertFromChain` | 102 (0x66) | Exported Function | 0x47608c90 | 0x00008c90
`WintrustSetDefaultIncludePEPageHashes` | 153 (0x99) | Exported Function | 0x47629280 | 0x00029280
`WintrustLoadFunctionPointers` | 151 (0x97) | Exported Function | 0x4760c040 | 0x0000c040
`SoftpubFreeDefUsageCallData` | 9 (0x9) | Exported Function | 0x4762be40 | 0x0002be40
`SoftpubInitialize` | 81 (0x51) | Exported Function | 0x4760c830 | 0x0000c830
`SoftpubLoadDefUsageCallData` | 10 (0xa) | Exported Function | 0x4762be80 | 0x0002be80
`SoftpubLoadMessage` | 82 (0x52) | Exported Function | 0x4760ba70 | 0x0000ba70
`SoftpubLoadSignature` | 83 (0x53) | Exported Function | 0x4760b9b0 | 0x0000b9b0
`SrpCheckSmartlockerEAandProcessToken` | 84 (0x54) | Exported Function | 0x47632560 | 0x00032560
`TrustDecode` | 85 (0x55) | Exported Function | 0x476218d0 | 0x000218d0
`WintrustRemoveActionID` | 152 (0x98) | Exported Function | 0x47620e60 | 0x00020e60
`TrustFindIssuerCertificate` | 86 (0x56) | Exported Function | 0x47621960 | 0x00021960
`TrustIsCertificateSelfSigned` | 88 (0x58) | Exported Function | 0x47621b00 | 0x00021b00
`TrustOpenStores` | 89 (0x59) | Exported Function | 0x47621b70 | 0x00021b70
`WintrustAddActionID` | 146 (0x92) | Exported Function | 0x47620ce0 | 0x00020ce0
`WintrustAddDefaultForUsage` | 147 (0x93) | Exported Function | 0x47621ca0 | 0x00021ca0
`WintrustCertificateTrust` | 148 (0x94) | Exported Function | 0x4760b1b0 | 0x0000b1b0
`WintrustGetDefaultForUsage` | 149 (0x95) | Exported Function | 0x47621ed0 | 0x00021ed0
`WintrustGetRegPolicyFlags` | 150 (0x96) | Exported Function | 0x47621160 | 0x00021160
`TrustFreeDecode` | 87 (0x57) | Exported Function | 0x47621ad0 | 0x00021ad0
`SoftpubDumpStructure` | 80 (0x50) | Exported Function | 0x47630860 | 0x00030860
`WTHelperGetProvPrivateDataFromChain` | 103 (0x67) | Exported Function | 0x4760a280 | 0x0000a280
`WTHelperIsChainedToMicrosoft` | 105 (0x69) | Exported Function | 0x47622610 | 0x00022610
`WVTAsn1SpcFinancialCriteriaInfoDecode` | 126 (0x7e) | Exported Function | 0x4761fe00 | 0x0001fe00
`WVTAsn1SpcFinancialCriteriaInfoEncode` | 127 (0x7f) | Exported Function | 0x4761fed0 | 0x0001fed0
`WVTAsn1SpcIndirectDataContentDecode` | 128 (0x80) | Exported Function | 0x4761ff00 | 0x0001ff00
`WVTAsn1SpcIndirectDataContentEncode` | 129 (0x81) | Exported Function | 0x47620050 | 0x00020050
`WVTAsn1SpcLinkDecode` | 130 (0x82) | Exported Function | 0x47620120 | 0x00020120
`WVTAsn1SpcLinkEncode` | 131 (0x83) | Exported Function | 0x476086e0 | 0x000086e0
`WVTAsn1SpcMinimalCriteriaInfoDecode` | 132 (0x84) | Exported Function | 0x47620200 | 0x00020200
`WVTAsn1SealingTimestampAttributeEncode` | 125 (0x7d) | Exported Function | 0x4761fdb0 | 0x0001fdb0
`WVTAsn1SpcMinimalCriteriaInfoEncode` | 133 (0x85) | Exported Function | 0x476202d0 | 0x000202d0
`WVTAsn1SpcPeImageDataEncode` | 135 (0x87) | Exported Function | 0x47614c80 | 0x00014c80
`WVTAsn1SpcSigInfoDecode` | 136 (0x88) | Exported Function | 0x47620420 | 0x00020420
`WVTAsn1SpcSigInfoEncode` | 137 (0x89) | Exported Function | 0x476204f0 | 0x000204f0
`WVTAsn1SpcSpAgencyInfoDecode` | 138 (0x8a) | Exported Function | 0x47620530 | 0x00020530
`WVTAsn1SpcSpAgencyInfoEncode` | 139 (0x8b) | Exported Function | 0x47620760 | 0x00020760
`WVTAsn1SpcSpOpusInfoDecode` | 140 (0x8c) | Exported Function | 0x47620900 | 0x00020900
`WVTAsn1SpcSpOpusInfoEncode` | 141 (0x8d) | Exported Function | 0x47620a40 | 0x00020a40
`WVTAsn1SpcPeImageDataDecode` | 134 (0x86) | Exported Function | 0x47620300 | 0x00020300
`WTHelperGetProvSignerFromChain` | 104 (0x68) | Exported Function | 0x47613620 | 0x00013620
`WVTAsn1SealingTimestampAttributeDecode` | 124 (0x7c) | Exported Function | 0x4761fcd0 | 0x0001fcd0
`WVTAsn1SealingSignatureAttributeDecode` | 122 (0x7a) | Exported Function | 0x4761fb50 | 0x0001fb50
`WTHelperIsChainedToMicrosoftFromStateData` | 106 (0x6a) | Exported Function | 0x47622720 | 0x00022720
`WTHelperIsInRootStore` | 107 (0x6b) | Exported Function | 0x476227c0 | 0x000227c0
`WTHelperOpenKnownStores` | 108 (0x6c) | Exported Function | 0x47622880 | 0x00022880
`WTHelperProvDataFromStateData` | 109 (0x6d) | Exported Function | 0x47613850 | 0x00013850
`WTIsFirstConfigCiResultPreferred` | 110 (0x6e) | Exported Function | 0x4762dd10 | 0x0002dd10
`WTLogConfigCiScriptEvent` | 111 (0x6f) | Exported Function | 0x4762dd70 | 0x0002dd70
`WTLogConfigCiSignerEvent` | 112 (0x70) | Exported Function | 0x4762e160 | 0x0002e160
`WVTAsn1SealingSignatureAttributeEncode` | 123 (0x7b) | Exported Function | 0x4761fc30 | 0x0001fc30
`WTValidateBioSignaturePolicy` | 113 (0x71) | Exported Function | 0x47623d30 | 0x00023d30
`WVTAsn1CatMemberInfo2Encode` | 115 (0x73) | Exported Function | 0x4761f850 | 0x0001f850
`WVTAsn1CatMemberInfoDecode` | 116 (0x74) | Exported Function | 0x4761f8f0 | 0x0001f8f0
`WVTAsn1CatMemberInfoEncode` | 117 (0x75) | Exported Function | 0x4761f9d0 | 0x0001f9d0
`WVTAsn1CatNameValueDecode` | 118 (0x76) | Exported Function | 0x47612b30 | 0x00012b30
`WVTAsn1CatNameValueEncode` | 119 (0x77) | Exported Function | 0x4761fa10 | 0x0001fa10
`WVTAsn1IntentToSealAttributeDecode` | 120 (0x78) | Exported Function | 0x4761fa60 | 0x0001fa60
`WVTAsn1IntentToSealAttributeEncode` | 121 (0x79) | Exported Function | 0x4761fb20 | 0x0001fb20
`WVTAsn1CatMemberInfo2Decode` | 114 (0x72) | Exported Function | 0x47613140 | 0x00013140
`WVTAsn1SpcStatementTypeDecode` | 142 (0x8e) | Exported Function | 0x47620b10 | 0x00020b10
`SoftpubDllUnregisterServer` | 79 (0x4f) | Exported Function | 0x4762fed0 | 0x0002fed0
`SoftpubDefCertInit` | 8 (0x8) | Exported Function | 0x4762bd70 | 0x0002bd70
`CryptCATCDFEnumAttributesWithCDFTag` | 31 (0x1f) | Exported Function | 0x47626180 | 0x00026180
`CryptCATCDFEnumCatAttributes` | 32 (0x20) | Exported Function | 0x476261c0 | 0x000261c0
`CryptCATCDFEnumMembers` | 33 (0x21) | Exported Function | 0x47626280 | 0x00026280
`CryptCATCDFEnumMembersByCDFTag` | 34 (0x22) | Exported Function | 0x476262d0 | 0x000262d0
`CryptCATCDFEnumMembersByCDFTagEx` | 35 (0x23) | Exported Function | 0x47626310 | 0x00026310
`CryptCATCDFOpen` | 36 (0x24) | Exported Function | 0x47626350 | 0x00026350
`CryptCATClose` | 38 (0x26) | Exported Function | 0x47609370 | 0x00009370
`CryptCATCDFEnumAttributes` | 30 (0x1e) | Exported Function | 0x47626150 | 0x00026150
`CryptCATEnumerateAttr` | 39 (0x27) | Exported Function | 0x47609210 | 0x00009210
`CryptCATEnumerateMember` | 41 (0x29) | Exported Function | 0x47623f90 | 0x00023f90
`CryptCATFreeSortedMemberInfo` | 42 (0x2a) | Exported Function | 0x47624050 | 0x00024050
`CryptCATGetAttrInfo` | 43 (0x2b) | Exported Function | 0x476091b0 | 0x000091b0
`CryptCATGetCatAttrInfo` | 44 (0x2c) | Exported Function | 0x47609270 | 0x00009270
`CryptCATGetMemberInfo` | 45 (0x2d) | Exported Function | 0x47624090 | 0x00024090
`CryptCATHandleFromStore` | 46 (0x2e) | Exported Function | 0x47613850 | 0x00013850
`CryptCATOpen` | 47 (0x2f) | Exported Function | 0x47611f50 | 0x00011f50
`CryptCATEnumerateCatAttr` | 40 (0x28) | Exported Function | 0x476092d0 | 0x000092d0
`CryptCATPersistStore` | 48 (0x30) | Exported Function | 0x47624140 | 0x00024140
`CryptCATCDFClose` | 29 (0x1d) | Exported Function | 0x476260d0 | 0x000260d0
`CryptCATAllocSortedMemberInfo` | 28 (0x1c) | Exported Function | 0x47612090 | 0x00012090
`CatalogCompactHashDatabase` | 13 (0xd) | Exported Function | 0x476138b0 | 0x000138b0
`ComputeFirstPageHash` | 1 (0x1) | Exported Function | 0x47623060 | 0x00023060
`ConfigCiFinalPolicy` | 14 (0xe) | Exported Function | 0x4762d4a0 | 0x0002d4a0
`ConfigCiPackageFamilyNameCheck` | 15 (0xf) | Exported Function | 0x4762d840 | 0x0002d840
`CryptCATAdminAcquireContext` | 17 (0x11) | Exported Function | 0x4760cec0 | 0x0000cec0
`CryptCATAdminAcquireContext2` | 16 (0x10) | Exported Function | 0x47610240 | 0x00010240
`CryptCATAdminAddCatalog` | 18 (0x12) | Exported Function | 0x476247e0 | 0x000247e0
`CryptCATCatalogInfoFromContext` | 37 (0x25) | Exported Function | 0x476089c0 | 0x000089c0
`CryptCATAdminCalcHashFromFileHandle` | 21 (0x15) | Exported Function | 0x47624ba0 | 0x00024ba0
`CryptCATAdminCalcHashFromFileHandle3` | 20 (0x14) | Exported Function | 0x47624b40 | 0x00024b40
`CryptCATAdminEnumCatalogFromHash` | 22 (0x16) | Exported Function | 0x4760cf40 | 0x0000cf40
`CryptCATAdminPauseServiceForBackup` | 23 (0x17) | Exported Function | 0x47624c40 | 0x00024c40
`CryptCATAdminReleaseCatalogContext` | 24 (0x18) | Exported Function | 0x47608b40 | 0x00008b40
`CryptCATAdminReleaseContext` | 25 (0x19) | Exported Function | 0x47610490 | 0x00010490
`CryptCATAdminRemoveCatalog` | 26 (0x1a) | Exported Function | 0x47624c80 | 0x00024c80
`CryptCATAdminResolveCatalogPath` | 27 (0x1b) | Exported Function | 0x47624cc0 | 0x00024cc0
`CryptCATAdminCalcHashFromFileHandle2` | 19 (0x13) | Exported Function | 0x47624ac0 | 0x00024ac0
`SoftpubDllRegisterServer` | 78 (0x4e) | Exported Function | 0x4762fca0 | 0x0002fca0
`CryptCATPutAttrInfo` | 49 (0x31) | Exported Function | 0x47624180 | 0x00024180
`CryptCATPutMemberInfo` | 51 (0x33) | Exported Function | 0x47624500 | 0x00024500
`HTTPSCertificateTrust` | 7 (0x7) | Exported Function | 0x4760aa80 | 0x0000aa80
`HTTPSFinalProv` | 67 (0x43) | Exported Function | 0x4760a990 | 0x0000a990
`IsCatalogFile` | 68 (0x44) | Exported Function | 0x47627270 | 0x00027270
`mscat32DllRegisterServer` | 156 (0x9c) | Exported Function | 0x47613930 | 0x00013930
`mscat32DllUnregisterServer` | 157 (0x9d) | Exported Function | 0x47613930 | 0x00013930
`MsCatConstructHashTag` | 69 (0x45) | Exported Function | 0x476115c0 | 0x000115c0
`MsCatFreeHashTag` | 70 (0x46) | Exported Function | 0x476274a0 | 0x000274a0
`GetAuthenticodeSha256Hash` | 66 (0x42) | Exported Function | 0x4762db10 | 0x0002db10
`mssip32DllRegisterServer` | 158 (0x9e) | Exported Function | 0x47627fc0 | 0x00027fc0
`OfficeCleanupPolicy` | 71 (0x47) | Exported Function | 0x4762f680 | 0x0002f680
`OfficeInitializePolicy` | 72 (0x48) | Exported Function | 0x4762f680 | 0x0002f680
`OpenPersonalTrustDBDialog` | 73 (0x49) | Exported Function | 0x4762bfe0 | 0x0002bfe0
`OpenPersonalTrustDBDialogEx` | 74 (0x4a) | Exported Function | 0x4762c000 | 0x0002c000
`SoftpubAuthenticode` | 75 (0x4b) | Exported Function | 0x4760a440 | 0x0000a440
`SoftpubCheckCert` | 76 (0x4c) | Exported Function | 0x47613680 | 0x00013680
`SoftpubCleanup` | 77 (0x4d) | Exported Function | 0x4760c820 | 0x0000c820
`mssip32DllUnregisterServer` | 159 (0x9f) | Exported Function | 0x47628200 | 0x00028200
`CryptCATPutCatAttrInfo` | 50 (0x32) | Exported Function | 0x476242f0 | 0x000242f0
`GenericChainFinalProv` | 6 (0x6) | Exported Function | 0x4762b7b0 | 0x0002b7b0
`FindCertsByIssuer` | 65 (0x41) | Exported Function | 0x4762f360 | 0x0002f360
`CryptCATStoreFromHandle` | 52 (0x34) | Exported Function | 0x47613850 | 0x00013850
`CryptCATVerifyMember` | 2 (0x2) | Exported Function | 0x47623f40 | 0x00023f40
`CryptSIPCreateIndirectData` | 53 (0x35) | Exported Function | 0x47610c70 | 0x00010c70
`CryptSIPGetCaps` | 54 (0x36) | Exported Function | 0x47610bc0 | 0x00010bc0
`CryptSIPGetInfo` | 3 (0x3) | Exported Function | 0x47627ce0 | 0x00027ce0
`CryptSIPGetRegWorkingFlags` | 4 (0x4) | Exported Function | 0x47627cd0 | 0x00027cd0
`CryptSIPGetSealedDigest` | 55 (0x37) | Exported Function | 0x47627d20 | 0x00027d20
`GenericChainCertificateTrust` | 5 (0x5) | Exported Function | 0x4762b510 | 0x0002b510
`CryptSIPGetSignedDataMsg` | 56 (0x38) | Exported Function | 0x47613bb0 | 0x00013bb0
`CryptSIPRemoveSignedDataMsg` | 58 (0x3a) | Exported Function | 0x47627e50 | 0x00027e50
`CryptSIPVerifyIndirectData` | 59 (0x3b) | Exported Function | 0x47627ed0 | 0x00027ed0
`DllRegisterServer` | 60 (0x3c) | Exported Function | 0x4761f1e0 | 0x0001f1e0
`DllUnregisterServer` | 61 (0x3d) | Exported Function | 0x4761f220 | 0x0001f220
`DriverCleanupPolicy` | 62 (0x3e) | Exported Function | 0x4760a2e0 | 0x0000a2e0
`DriverFinalPolicy` | 63 (0x3f) | Exported Function | 0x47609bc0 | 0x00009bc0
`DriverInitializePolicy` | 64 (0x40) | Exported Function | 0x4760a0c0 | 0x0000a0c0
`CryptSIPPutSignedDataMsg` | 57 (0x39) | Exported Function | 0x47627db0 | 0x00027db0
`WVTAsn1SpcStatementTypeEncode` | 143 (0x8f) | Exported Function | 0x47620c40 | 0x00020c40


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/2640c5c44a74f92ce9b49057b0bf13753531d2f1e34019e138fbcb305bc4722e/detection/





MIT License. Copyright (c) 2020 Strontic.


