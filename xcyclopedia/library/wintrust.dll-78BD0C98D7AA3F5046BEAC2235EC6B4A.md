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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AddPersonalTrustDBPages` | 12 (0xc) | Exported Function | 0x000000018002f6a0 | 0x0002f6a0
`WintrustUserWriteabilityCheck` | 155 (0x9b) | Exported Function | 0x0000000180032130 | 0x00032130
`WinVerifyTrust` | 144 (0x90) | Exported Function | 0x0000000180001da0 | 0x00001da0
`WinVerifyTrustEx` | 145 (0x91) | Exported Function | 0x0000000180021030 | 0x00021030
`WTConvertCertCtxToChainInfo` | 90 (0x5a) | Exported Function | 0x0000000180031a10 | 0x00031a10
`WTGetBioSignatureInfo` | 91 (0x5b) | Exported Function | 0x00000001800235c0 | 0x000235c0
`WTGetPluginSignatureInfo` | 92 (0x5c) | Exported Function | 0x0000000180023780 | 0x00023780
`WTGetSignatureInfo` | 93 (0x5d) | Exported Function | 0x0000000180009dc0 | 0x00009dc0
`WintrustSetRegPolicyFlags` | 154 (0x9a) | Exported Function | 0x000000018001f720 | 0x0001f720
`WTHelperCertCheckValidSignature` | 94 (0x5e) | Exported Function | 0x0000000180021180 | 0x00021180
`WTHelperCertIsSelfSigned` | 95 (0x5f) | Exported Function | 0x000000018001c3c0 | 0x0001c3c0
`WTHelperCheckCertUsage` | 96 (0x60) | Exported Function | 0x00000001800211b0 | 0x000211b0
`WTHelperGetAgencyInfo` | 97 (0x61) | Exported Function | 0x0000000180021320 | 0x00021320
`WTHelperGetFileHandle` | 98 (0x62) | Exported Function | 0x0000000180021420 | 0x00021420
`WTHelperGetFileHash` | 99 (0x63) | Exported Function | 0x0000000180020f40 | 0x00020f40
`WTHelperGetFileName` | 100 (0x64) | Exported Function | 0x0000000180009530 | 0x00009530
`WTHelperGetKnownUsages` | 101 (0x65) | Exported Function | 0x0000000180021450 | 0x00021450
`WTHelperCertFindIssuerCertificate` | 11 (0xb) | Exported Function | 0x000000018001c380 | 0x0001c380
`WTHelperGetProvCertFromChain` | 102 (0x66) | Exported Function | 0x00000001800014b0 | 0x000014b0
`WintrustSetDefaultIncludePEPageHashes` | 153 (0x99) | Exported Function | 0x000000018002baf0 | 0x0002baf0
`WintrustLoadFunctionPointers` | 151 (0x97) | Exported Function | 0x0000000180001ba0 | 0x00001ba0
`SoftpubFreeDefUsageCallData` | 9 (0x9) | Exported Function | 0x000000018002f500 | 0x0002f500
`SoftpubInitialize` | 81 (0x51) | Exported Function | 0x000000018000bd80 | 0x0000bd80
`SoftpubLoadDefUsageCallData` | 10 (0xa) | Exported Function | 0x000000018002f550 | 0x0002f550
`SoftpubLoadMessage` | 82 (0x52) | Exported Function | 0x0000000180008670 | 0x00008670
`SoftpubLoadSignature` | 83 (0x53) | Exported Function | 0x000000018000c570 | 0x0000c570
`SrpCheckSmartlockerEAandProcessToken` | 84 (0x54) | Exported Function | 0x0000000180037a70 | 0x00037a70
`TrustDecode` | 85 (0x55) | Exported Function | 0x00000001800201f0 | 0x000201f0
`WintrustRemoveActionID` | 152 (0x98) | Exported Function | 0x000000018001eb20 | 0x0001eb20
`TrustFindIssuerCertificate` | 86 (0x56) | Exported Function | 0x00000001800202e0 | 0x000202e0
`TrustIsCertificateSelfSigned` | 88 (0x58) | Exported Function | 0x0000000180020530 | 0x00020530
`TrustOpenStores` | 89 (0x59) | Exported Function | 0x00000001800205c0 | 0x000205c0
`WintrustAddActionID` | 146 (0x92) | Exported Function | 0x000000018001e900 | 0x0001e900
`WintrustAddDefaultForUsage` | 147 (0x93) | Exported Function | 0x0000000180020720 | 0x00020720
`WintrustCertificateTrust` | 148 (0x94) | Exported Function | 0x000000018000a610 | 0x0000a610
`WintrustGetDefaultForUsage` | 149 (0x95) | Exported Function | 0x0000000180020a70 | 0x00020a70
`WintrustGetRegPolicyFlags` | 150 (0x96) | Exported Function | 0x000000018001f660 | 0x0001f660
`TrustFreeDecode` | 87 (0x57) | Exported Function | 0x0000000180020500 | 0x00020500
`SoftpubDumpStructure` | 80 (0x50) | Exported Function | 0x00000001800352f0 | 0x000352f0
`WTHelperGetProvPrivateDataFromChain` | 103 (0x67) | Exported Function | 0x0000000180021500 | 0x00021500
`WTHelperIsChainedToMicrosoft` | 105 (0x69) | Exported Function | 0x0000000180021560 | 0x00021560
`WVTAsn1SpcFinancialCriteriaInfoDecode` | 126 (0x7e) | Exported Function | 0x000000018001d7c0 | 0x0001d7c0
`WVTAsn1SpcFinancialCriteriaInfoEncode` | 127 (0x7f) | Exported Function | 0x000000018001d880 | 0x0001d880
`WVTAsn1SpcIndirectDataContentDecode` | 128 (0x80) | Exported Function | 0x000000018001d8c0 | 0x0001d8c0
`WVTAsn1SpcIndirectDataContentEncode` | 129 (0x81) | Exported Function | 0x000000018001da70 | 0x0001da70
`WVTAsn1SpcLinkDecode` | 130 (0x82) | Exported Function | 0x000000018001db60 | 0x0001db60
`WVTAsn1SpcLinkEncode` | 131 (0x83) | Exported Function | 0x000000018000d980 | 0x0000d980
`WVTAsn1SpcMinimalCriteriaInfoDecode` | 132 (0x84) | Exported Function | 0x000000018001dc40 | 0x0001dc40
`WVTAsn1SealingTimestampAttributeEncode` | 125 (0x7d) | Exported Function | 0x000000018001d760 | 0x0001d760
`WVTAsn1SpcMinimalCriteriaInfoEncode` | 133 (0x85) | Exported Function | 0x000000018001dd00 | 0x0001dd00
`WVTAsn1SpcPeImageDataEncode` | 135 (0x87) | Exported Function | 0x00000001800100f0 | 0x000100f0
`WVTAsn1SpcSigInfoDecode` | 136 (0x88) | Exported Function | 0x000000018001de70 | 0x0001de70
`WVTAsn1SpcSigInfoEncode` | 137 (0x89) | Exported Function | 0x000000018001df30 | 0x0001df30
`WVTAsn1SpcSpAgencyInfoDecode` | 138 (0x8a) | Exported Function | 0x000000018001dfa0 | 0x0001dfa0
`WVTAsn1SpcSpAgencyInfoEncode` | 139 (0x8b) | Exported Function | 0x000000018001e330 | 0x0001e330
`WVTAsn1SpcSpOpusInfoDecode` | 140 (0x8c) | Exported Function | 0x000000018001e4e0 | 0x0001e4e0
`WVTAsn1SpcSpOpusInfoEncode` | 141 (0x8d) | Exported Function | 0x000000018001e630 | 0x0001e630
`WVTAsn1SpcPeImageDataDecode` | 134 (0x86) | Exported Function | 0x000000018001dd40 | 0x0001dd40
`WTHelperGetProvSignerFromChain` | 104 (0x68) | Exported Function | 0x000000018000e450 | 0x0000e450
`WVTAsn1SealingTimestampAttributeDecode` | 124 (0x7c) | Exported Function | 0x000000018001d680 | 0x0001d680
`WVTAsn1SealingSignatureAttributeDecode` | 122 (0x7a) | Exported Function | 0x000000018001d4e0 | 0x0001d4e0
`WTHelperIsChainedToMicrosoftFromStateData` | 106 (0x6a) | Exported Function | 0x0000000180021710 | 0x00021710
`WTHelperIsInRootStore` | 107 (0x6b) | Exported Function | 0x00000001800217f0 | 0x000217f0
`WTHelperOpenKnownStores` | 108 (0x6c) | Exported Function | 0x0000000180021900 | 0x00021900
`WTHelperProvDataFromStateData` | 109 (0x6d) | Exported Function | 0x000000018000eb60 | 0x0000eb60
`WTIsFirstConfigCiResultPreferred` | 110 (0x6e) | Exported Function | 0x0000000180031aa0 | 0x00031aa0
`WTLogConfigCiScriptEvent` | 111 (0x6f) | Exported Function | 0x0000000180031b00 | 0x00031b00
`WTLogConfigCiSignerEvent` | 112 (0x70) | Exported Function | 0x0000000180031ee0 | 0x00031ee0
`WVTAsn1SealingSignatureAttributeEncode` | 123 (0x7b) | Exported Function | 0x000000018001d5c0 | 0x0001d5c0
`WTValidateBioSignaturePolicy` | 113 (0x71) | Exported Function | 0x0000000180023990 | 0x00023990
`WVTAsn1CatMemberInfo2Encode` | 115 (0x73) | Exported Function | 0x000000018001d190 | 0x0001d190
`WVTAsn1CatMemberInfoDecode` | 116 (0x74) | Exported Function | 0x000000018001d240 | 0x0001d240
`WVTAsn1CatMemberInfoEncode` | 117 (0x75) | Exported Function | 0x000000018001d320 | 0x0001d320
`WVTAsn1CatNameValueDecode` | 118 (0x76) | Exported Function | 0x000000018000c3a0 | 0x0000c3a0
`WVTAsn1CatNameValueEncode` | 119 (0x77) | Exported Function | 0x000000018001d380 | 0x0001d380
`WVTAsn1IntentToSealAttributeDecode` | 120 (0x78) | Exported Function | 0x000000018001d3f0 | 0x0001d3f0
`WVTAsn1IntentToSealAttributeEncode` | 121 (0x79) | Exported Function | 0x000000018001d4a0 | 0x0001d4a0
`WVTAsn1CatMemberInfo2Decode` | 114 (0x72) | Exported Function | 0x000000018000def0 | 0x0000def0
`WVTAsn1SpcStatementTypeDecode` | 142 (0x8e) | Exported Function | 0x000000018001e710 | 0x0001e710
`SoftpubDllUnregisterServer` | 79 (0x4f) | Exported Function | 0x0000000180034690 | 0x00034690
`SoftpubDefCertInit` | 8 (0x8) | Exported Function | 0x000000018002f400 | 0x0002f400
`CryptCATCDFEnumAttributesWithCDFTag` | 31 (0x1f) | Exported Function | 0x0000000180026d60 | 0x00026d60
`CryptCATCDFEnumCatAttributes` | 32 (0x20) | Exported Function | 0x0000000180026db0 | 0x00026db0
`CryptCATCDFEnumMembers` | 33 (0x21) | Exported Function | 0x0000000180026f60 | 0x00026f60
`CryptCATCDFEnumMembersByCDFTag` | 34 (0x22) | Exported Function | 0x0000000180026fd0 | 0x00026fd0
`CryptCATCDFEnumMembersByCDFTagEx` | 35 (0x23) | Exported Function | 0x0000000180027020 | 0x00027020
`CryptCATCDFOpen` | 36 (0x24) | Exported Function | 0x0000000180027070 | 0x00027070
`CryptCATClose` | 38 (0x26) | Exported Function | 0x0000000180003050 | 0x00003050
`CryptCATCDFEnumAttributes` | 30 (0x1e) | Exported Function | 0x0000000180026d40 | 0x00026d40
`CryptCATEnumerateAttr` | 39 (0x27) | Exported Function | 0x000000018000b590 | 0x0000b590
`CryptCATEnumerateMember` | 41 (0x29) | Exported Function | 0x0000000180023c90 | 0x00023c90
`CryptCATFreeSortedMemberInfo` | 42 (0x2a) | Exported Function | 0x0000000180023d80 | 0x00023d80
`CryptCATGetAttrInfo` | 43 (0x2b) | Exported Function | 0x0000000180023dc0 | 0x00023dc0
`CryptCATGetCatAttrInfo` | 44 (0x2c) | Exported Function | 0x0000000180023e70 | 0x00023e70
`CryptCATGetMemberInfo` | 45 (0x2d) | Exported Function | 0x0000000180023f00 | 0x00023f00
`CryptCATHandleFromStore` | 46 (0x2e) | Exported Function | 0x000000018000eb60 | 0x0000eb60
`CryptCATOpen` | 47 (0x2f) | Exported Function | 0x0000000180023fd0 | 0x00023fd0
`CryptCATEnumerateCatAttr` | 40 (0x28) | Exported Function | 0x000000018000b5f0 | 0x0000b5f0
`CryptCATPersistStore` | 48 (0x30) | Exported Function | 0x0000000180024130 | 0x00024130
`CryptCATCDFClose` | 29 (0x1d) | Exported Function | 0x0000000180026c90 | 0x00026c90
`CryptCATAllocSortedMemberInfo` | 28 (0x1c) | Exported Function | 0x0000000180008240 | 0x00008240
`CatalogCompactHashDatabase` | 13 (0xd) | Exported Function | 0x000000018000ece0 | 0x0000ece0
`ComputeFirstPageHash` | 1 (0x1) | Exported Function | 0x0000000180022300 | 0x00022300
`ConfigCiFinalPolicy` | 14 (0xe) | Exported Function | 0x00000001800310e0 | 0x000310e0
`ConfigCiPackageFamilyNameCheck` | 15 (0xf) | Exported Function | 0x00000001800314f0 | 0x000314f0
`CryptCATAdminAcquireContext` | 16 (0x10) | Exported Function | 0x0000000180001310 | 0x00001310
`CryptCATAdminAcquireContext2` | 17 (0x11) | Exported Function | 0x00000001800249b0 | 0x000249b0
`CryptCATAdminAddCatalog` | 18 (0x12) | Exported Function | 0x0000000180024a90 | 0x00024a90
`CryptCATCatalogInfoFromContext` | 37 (0x25) | Exported Function | 0x0000000180001020 | 0x00001020
`CryptCATAdminCalcHashFromFileHandle` | 19 (0x13) | Exported Function | 0x0000000180024de0 | 0x00024de0
`CryptCATAdminCalcHashFromFileHandle3` | 21 (0x15) | Exported Function | 0x0000000180024ec0 | 0x00024ec0
`CryptCATAdminEnumCatalogFromHash` | 22 (0x16) | Exported Function | 0x0000000180003390 | 0x00003390
`CryptCATAdminPauseServiceForBackup` | 23 (0x17) | Exported Function | 0x0000000180024f30 | 0x00024f30
`CryptCATAdminReleaseCatalogContext` | 24 (0x18) | Exported Function | 0x00000001800013b0 | 0x000013b0
`CryptCATAdminReleaseContext` | 25 (0x19) | Exported Function | 0x00000001800010f0 | 0x000010f0
`CryptCATAdminRemoveCatalog` | 26 (0x1a) | Exported Function | 0x0000000180024f80 | 0x00024f80
`CryptCATAdminResolveCatalogPath` | 27 (0x1b) | Exported Function | 0x0000000180024fd0 | 0x00024fd0
`CryptCATAdminCalcHashFromFileHandle2` | 20 (0x14) | Exported Function | 0x0000000180024e40 | 0x00024e40
`SoftpubDllRegisterServer` | 78 (0x4e) | Exported Function | 0x0000000180034420 | 0x00034420
`CryptCATPutAttrInfo` | 49 (0x31) | Exported Function | 0x0000000180024170 | 0x00024170
`CryptCATPutMemberInfo` | 51 (0x33) | Exported Function | 0x00000001800245f0 | 0x000245f0
`HTTPSCertificateTrust` | 7 (0x7) | Exported Function | 0x000000018000a9f0 | 0x0000a9f0
`HTTPSFinalProv` | 67 (0x43) | Exported Function | 0x000000018000d730 | 0x0000d730
`IsCatalogFile` | 68 (0x44) | Exported Function | 0x0000000180028e90 | 0x00028e90
`mscat32DllRegisterServer` | 156 (0x9c) | Exported Function | 0x000000018000ec60 | 0x0000ec60
`mscat32DllUnregisterServer` | 157 (0x9d) | Exported Function | 0x000000018000ec60 | 0x0000ec60
`MsCatConstructHashTag` | 69 (0x45) | Exported Function | 0x0000000180029330 | 0x00029330
`MsCatFreeHashTag` | 70 (0x46) | Exported Function | 0x00000001800291e0 | 0x000291e0
`GetAuthenticodeSha256Hash` | 66 (0x42) | Exported Function | 0x0000000180031800 | 0x00031800
`mssip32DllRegisterServer` | 158 (0x9e) | Exported Function | 0x000000018002a6c0 | 0x0002a6c0
`OfficeCleanupPolicy` | 71 (0x47) | Exported Function | 0x0000000180033c30 | 0x00033c30
`OfficeInitializePolicy` | 72 (0x48) | Exported Function | 0x0000000180033c30 | 0x00033c30
`OpenPersonalTrustDBDialog` | 73 (0x49) | Exported Function | 0x000000018002f6d0 | 0x0002f6d0
`OpenPersonalTrustDBDialogEx` | 74 (0x4a) | Exported Function | 0x000000018002f6e0 | 0x0002f6e0
`SoftpubAuthenticode` | 75 (0x4b) | Exported Function | 0x000000018000b6d0 | 0x0000b6d0
`SoftpubCheckCert` | 76 (0x4c) | Exported Function | 0x000000018000e850 | 0x0000e850
`SoftpubCleanup` | 77 (0x4d) | Exported Function | 0x000000018000ec60 | 0x0000ec60
`mssip32DllUnregisterServer` | 159 (0x9f) | Exported Function | 0x000000018002a910 | 0x0002a910
`CryptCATPutCatAttrInfo` | 50 (0x32) | Exported Function | 0x0000000180024350 | 0x00024350
`GenericChainFinalProv` | 6 (0x6) | Exported Function | 0x000000018002ec20 | 0x0002ec20
`FindCertsByIssuer` | 65 (0x41) | Exported Function | 0x0000000180033820 | 0x00033820
`CryptCATStoreFromHandle` | 52 (0x34) | Exported Function | 0x000000018000eb60 | 0x0000eb60
`CryptCATVerifyMember` | 2 (0x2) | Exported Function | 0x0000000180023c40 | 0x00023c40
`CryptSIPCreateIndirectData` | 53 (0x35) | Exported Function | 0x0000000180007c80 | 0x00007c80
`CryptSIPGetCaps` | 54 (0x36) | Exported Function | 0x0000000180007bf0 | 0x00007bf0
`CryptSIPGetInfo` | 3 (0x3) | Exported Function | 0x000000018002a1c0 | 0x0002a1c0
`CryptSIPGetRegWorkingFlags` | 4 (0x4) | Exported Function | 0x000000018002a1b0 | 0x0002a1b0
`CryptSIPGetSealedDigest` | 55 (0x37) | Exported Function | 0x000000018002a230 | 0x0002a230
`GenericChainCertificateTrust` | 5 (0x5) | Exported Function | 0x000000018002e8e0 | 0x0002e8e0
`CryptSIPGetSignedDataMsg` | 56 (0x38) | Exported Function | 0x000000018002a310 | 0x0002a310
`CryptSIPRemoveSignedDataMsg` | 58 (0x3a) | Exported Function | 0x000000018002a510 | 0x0002a510
`CryptSIPVerifyIndirectData` | 59 (0x3b) | Exported Function | 0x000000018002a5b0 | 0x0002a5b0
`DllRegisterServer` | 60 (0x3c) | Exported Function | 0x000000018001c6b0 | 0x0001c6b0
`DllUnregisterServer` | 61 (0x3d) | Exported Function | 0x000000018001c700 | 0x0001c700
`DriverCleanupPolicy` | 62 (0x3e) | Exported Function | 0x000000018000e220 | 0x0000e220
`DriverFinalPolicy` | 63 (0x3f) | Exported Function | 0x000000018000b130 | 0x0000b130
`DriverInitializePolicy` | 64 (0x40) | Exported Function | 0x0000000180001980 | 0x00001980
`CryptSIPPutSignedDataMsg` | 57 (0x39) | Exported Function | 0x000000018002a430 | 0x0002a430
`WVTAsn1SpcStatementTypeEncode` | 143 (0x8f) | Exported Function | 0x000000018001e840 | 0x0001e840


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


