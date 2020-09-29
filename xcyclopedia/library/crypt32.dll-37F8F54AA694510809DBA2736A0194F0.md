---
title: crypt32.dll | Crypto API32
excerpt: What is crypt32.dll?
---

# crypt32.dll 

* File Path: `C:\Windows\system32\crypt32.dll`
* Description: Crypto API32

## Hashes

Type | Hash
-- | --
MD5 | `37F8F54AA694510809DBA2736A0194F0`
SHA1 | `DEDFDA425C0B3D7815A1B7FB00FFB04705340258`
SHA256 | `08ED695DCE1F42B48D18A3752FB2AFC0CEBD899F04B4BCB994F8F5E4810A1EFF`
SHA384 | `A963711D7C4C4E8D0B74683F63739C9961E76CE5B28B7E4B2FD6ACD710D30E779E2198A94A7D4BAC18749B0941CEDB42`
SHA512 | `10CD2E7A9499E4346FD3A17403CADC611F9A5419ACA08C3D1173CAB5A0DE337F74A8C33832E0CD552FC53F14F1FED3E923967EF822C8CCD1A045034D7F8ECF55`
SSDEEP | `24576:VBOTZPa5PWh+Yd5mQBi/ioxQnm6LbKDZnFZs8BA1do/nZNAvTfKVyZBg:+TZPaBWLd5mpaoBUsFq8BAgTA+VyM`
IMP | `D9C37EA27DDC4B8CE07F3722E40E06E9`
PESHA1 | `4CC401142F90023495CBD3AF663ACA12EC4DB4F9`
PE256 | `A7DA195ACE62A6807D0E41656743848ADB54C562AFB7A2CD8672A7B80D49169A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`CertAddCertificateContextToStore` | 1024 (0x400) | Exported Function | 0x0000000180047820 | 0x00047820
`CryptSignMessage` | 1233 (0x4d1) | Exported Function | 0x0000000180094270 | 0x00094270
`CryptSignCertificate` | 1232 (0x4d0) | Exported Function | 0x000000018004ab60 | 0x0004ab60
`CryptSignAndEncryptMessage` | 1231 (0x4cf) | Exported Function | 0x0000000180094110 | 0x00094110
`CryptSignAndEncodeCertificate` | 1230 (0x4ce) | Exported Function | 0x000000018004a9c0 | 0x0004a9c0
`CryptSetOIDFunctionValue` | 1229 (0x4cd) | Exported Function | 0x00000001800a15a0 | 0x000a15a0
`CryptSetKeyIdentifierProperty` | 1228 (0x4cc) | Exported Function | 0x0000000180084160 | 0x00084160
`CryptSetAsyncParam` | 1227 (0x4cb) | Exported Function | 0x0000000180091f60 | 0x00091f60
`CryptRetrieveTimeStamp` | 1214 (0x4be) | Exported Function | 0x00000001800ed9e0 | 0x000ed9e0
`CryptRegisterOIDInfo` | 1213 (0x4bd) | Exported Function | 0x00000001800a2e90 | 0x000a2e90
`CryptRegisterOIDFunction` | 1212 (0x4bc) | Exported Function | 0x00000001800a14a0 | 0x000a14a0
`CryptRegisterDefaultOIDFunction` | 1211 (0x4bb) | Exported Function | 0x00000001800a1180 | 0x000a1180
`CryptQueryObject` | 1210 (0x4ba) | Exported Function | 0x0000000180001390 | 0x00001390
`CryptProtectMemory` | 1209 (0x4b9) | Exported Function | DPAPI.CryptProtectMemory | 0x001414e8
`CryptProtectData` | 1208 (0x4b8) | Exported Function | 0x000000018001b690 | 0x0001b690
`CryptObjectLocatorRelease` | 1018 (0x3fa) | Exported Function | 0x00000001800d56a0 | 0x000d56a0
`CryptSignMessageWithKey` | 1234 (0x4d2) | Exported Function | 0x0000000180094380 | 0x00094380
`CryptObjectLocatorIsChanged` | 1017 (0x3f9) | Exported Function | 0x00000001800d5670 | 0x000d5670
`CryptSIPAddProvider` | 1215 (0x4bf) | Exported Function | 0x00000001800ed3a0 | 0x000ed3a0
`CryptSIPGetCaps` | 1217 (0x4c1) | Exported Function | 0x0000000180024510 | 0x00024510
`CryptUnregisterDefaultOIDFunction` | 1240 (0x4d8) | Exported Function | 0x00000001800a16b0 | 0x000a16b0
`CryptUnprotectMemory` | 1239 (0x4d7) | Exported Function | DPAPI.CryptUnprotectMemory | 0x001417d1
`CryptUnprotectData` | 1238 (0x4d6) | Exported Function | 0x0000000180014910 | 0x00014910
`CryptUninstallDefaultContext` | 1237 (0x4d5) | Exported Function | 0x00000001800b3e60 | 0x000b3e60
`CryptStringToBinaryW` | 1236 (0x4d4) | Exported Function | 0x0000000180009b60 | 0x00009b60
`CryptStringToBinaryA` | 1235 (0x4d3) | Exported Function | 0x0000000180009d00 | 0x00009d00
`CryptSIPVerifyIndirectData` | 1226 (0x4ca) | Exported Function | 0x000000018004c870 | 0x0004c870
`CryptSIPRetrieveSubjectGuidForCatalogFile` | 1225 (0x4c9) | Exported Function | 0x0000000180016690 | 0x00016690
`CryptSIPRetrieveSubjectGuid` | 1224 (0x4c8) | Exported Function | 0x0000000180016320 | 0x00016320
`CryptSIPRemoveSignedDataMsg` | 1223 (0x4c7) | Exported Function | 0x00000001800ed910 | 0x000ed910
`CryptSIPRemoveProvider` | 1222 (0x4c6) | Exported Function | 0x00000001800ed580 | 0x000ed580
`CryptSIPPutSignedDataMsg` | 1221 (0x4c5) | Exported Function | 0x00000001800ed820 | 0x000ed820
`CryptSIPLoad` | 1220 (0x4c4) | Exported Function | 0x0000000180024870 | 0x00024870
`CryptSIPGetSignedDataMsg` | 1219 (0x4c3) | Exported Function | 0x000000018001b210 | 0x0001b210
`CryptSIPGetSealedDigest` | 1218 (0x4c2) | Exported Function | 0x00000001800ed730 | 0x000ed730
`CryptSIPCreateIndirectData` | 1216 (0x4c0) | Exported Function | 0x00000001800245f0 | 0x000245f0
`CryptObjectLocatorInitialize` | 1016 (0x3f8) | Exported Function | 0x00000001800d52f0 | 0x000d52f0
`CryptObjectLocatorGetUpdated` | 1015 (0x3f7) | Exported Function | 0x00000001800d52a0 | 0x000d52a0
`CryptObjectLocatorGetContent` | 1014 (0x3f6) | Exported Function | 0x00000001800d51e0 | 0x000d51e0
`CryptLoadSip` | 1189 (0x4a5) | Exported Function | 0x00000001800ed2f0 | 0x000ed2f0
`CryptInstallOIDFunctionAddress` | 1188 (0x4a4) | Exported Function | 0x0000000180011110 | 0x00011110
`CryptInstallDefaultContext` | 1187 (0x4a3) | Exported Function | 0x00000001800b3c90 | 0x000b3c90
`CryptInitOIDFunctionSet` | 1186 (0x4a2) | Exported Function | 0x0000000180011180 | 0x00011180
`CryptImportPublicKeyInfoEx2` | 1185 (0x4a1) | Exported Function | 0x0000000180037ed0 | 0x00037ed0
`CryptImportPublicKeyInfoEx` | 1184 (0x4a0) | Exported Function | 0x0000000180024f20 | 0x00024f20
`CryptImportPublicKeyInfo` | 1183 (0x49f) | Exported Function | 0x0000000180005bf0 | 0x00005bf0
`CryptImportPKCS8` | 1182 (0x49e) | Exported Function | 0x00000001800d8dd0 | 0x000d8dd0
`CryptHashToBeSigned` | 1181 (0x49d) | Exported Function | 0x0000000180037290 | 0x00037290
`CryptHashPublicKeyInfo` | 1180 (0x49c) | Exported Function | 0x0000000180002c20 | 0x00002c20
`CryptHashMessage` | 1179 (0x49b) | Exported Function | 0x0000000180093ea0 | 0x00093ea0
`CryptHashCertificate2` | 1178 (0x49a) | Exported Function | 0x000000018002fd10 | 0x0002fd10
`CryptHashCertificate` | 1177 (0x499) | Exported Function | 0x000000018004ac70 | 0x0004ac70
`CryptGetOIDFunctionValue` | 1176 (0x498) | Exported Function | 0x00000001800a1080 | 0x000a1080
`CryptGetOIDFunctionAddress` | 1175 (0x497) | Exported Function | 0x0000000180039260 | 0x00039260
`CryptMemAlloc` | 1190 (0x4a6) | Exported Function | 0x0000000180015b10 | 0x00015b10
`CryptMemFree` | 1191 (0x4a7) | Exported Function | 0x0000000180015200 | 0x00015200
`CryptMemRealloc` | 1192 (0x4a8) | Exported Function | 0x00000001800b4120 | 0x000b4120
`CryptMsgCalculateEncodedLength` | 1193 (0x4a9) | Exported Function | 0x00000001800ef2b0 | 0x000ef2b0
`CryptObjectLocatorGet` | 1013 (0x3f5) | Exported Function | 0x00000001800d51a0 | 0x000d51a0
`CryptObjectLocatorFree` | 1012 (0x3f4) | Exported Function | 0x00000001800d5150 | 0x000d5150
`CryptMsgVerifyCountersignatureEncodedEx` | 1207 (0x4b7) | Exported Function | 0x00000001800fa6f0 | 0x000fa6f0
`CryptMsgVerifyCountersignatureEncoded` | 1206 (0x4b6) | Exported Function | 0x00000001800fa690 | 0x000fa690
`CryptMsgUpdate` | 1205 (0x4b5) | Exported Function | 0x000000018003d6e0 | 0x0003d6e0
`CryptMsgSignCTL` | 1204 (0x4b4) | Exported Function | 0x00000001800faac0 | 0x000faac0
`CryptMsgOpenToEncode` | 1203 (0x4b3) | Exported Function | 0x00000001800fa580 | 0x000fa580
`CryptUnregisterOIDFunction` | 1241 (0x4d9) | Exported Function | 0x00000001800a1970 | 0x000a1970
`CryptMsgOpenToDecode` | 1202 (0x4b2) | Exported Function | 0x0000000180025220 | 0x00025220
`CryptMsgGetAndVerifySigner` | 1200 (0x4b0) | Exported Function | 0x0000000180007fb0 | 0x00007fb0
`CryptMsgEncodeAndSignCTL` | 1199 (0x4af) | Exported Function | 0x00000001800fa9c0 | 0x000fa9c0
`CryptMsgDuplicate` | 1198 (0x4ae) | Exported Function | 0x000000018001bc00 | 0x0001bc00
`CryptMsgCountersignEncoded` | 1197 (0x4ad) | Exported Function | 0x00000001800fa1e0 | 0x000fa1e0
`CryptMsgCountersign` | 1196 (0x4ac) | Exported Function | 0x00000001800fa040 | 0x000fa040
`CryptMsgControl` | 1195 (0x4ab) | Exported Function | 0x000000018004bb00 | 0x0004bb00
`CryptMsgClose` | 1194 (0x4aa) | Exported Function | 0x0000000180036c70 | 0x00036c70
`CryptMsgGetParam` | 1201 (0x4b1) | Exported Function | 0x0000000180047b10 | 0x00047b10
`CryptGetMessageSignerCount` | 1174 (0x496) | Exported Function | 0x0000000180093df0 | 0x00093df0
`CryptUnregisterOIDInfo` | 1242 (0x4da) | Exported Function | 0x00000001800a3090 | 0x000a3090
`CryptVerifyCertificateSignature` | 1244 (0x4dc) | Exported Function | 0x00000001800872d0 | 0x000872d0
`I_CryptWalkAllLruCacheEntries` | 1298 (0x512) | Exported Function | 0x0000000180016060 | 0x00016060
`I_CryptUnregisterSmartCardStore` | 1297 (0x511) | Exported Function | 0x0000000180091f60 | 0x00091f60
`I_CryptUninstallOssGlobal` | 1296 (0x510) | Exported Function | 0x00000001800b7fb0 | 0x000b7fb0
`I_CryptUninstallAsn1Module` | 1295 (0x50f) | Exported Function | 0x000000018000d640 | 0x0000d640
`I_CryptTouchLruEntry` | 1294 (0x50e) | Exported Function | 0x0000000180005660 | 0x00005660
`I_CryptSetTls` | 1293 (0x50d) | Exported Function | 0x0000000180041420 | 0x00041420
`I_CryptRemoveLruEntry` | 1292 (0x50c) | Exported Function | 0x0000000180005aa0 | 0x00005aa0
`I_CryptReleaseLruEntry` | 1291 (0x50b) | Exported Function | 0x000000018001c3c0 | 0x0001c3c0
`I_CryptRegisterSmartCardStore` | 1290 (0x50a) | Exported Function | 0x0000000180091f60 | 0x00091f60
`I_CryptReadTrustedPublisherDWORDValueFromRegistry` | 1289 (0x509) | Exported Function | 0x00000001800447e0 | 0x000447e0
`I_CryptInstallOssGlobal` | 1288 (0x508) | Exported Function | 0x00000001800b7fb0 | 0x000b7fb0
`I_CryptInstallAsn1Module` | 1287 (0x507) | Exported Function | 0x000000018000d660 | 0x0000d660
`I_CryptInsertLruEntry` | 1286 (0x506) | Exported Function | 0x000000018001bcc0 | 0x0001bcc0
`I_CryptGetTls` | 1285 (0x505) | Exported Function | 0x000000018003d130 | 0x0003d130
`I_CryptGetOssGlobal` | 1284 (0x504) | Exported Function | 0x00000001800b7fb0 | 0x000b7fb0
`I_PFXDecrypt` | 1299 (0x513) | Exported Function | 0x00000001800dab40 | 0x000dab40
`I_CryptGetLruEntryIdentifier` | 1283 (0x503) | Exported Function | 0x00000001800ced40 | 0x000ced40
`I_PFXHMAC` | 1300 (0x514) | Exported Function | 0x00000001800daf60 | 0x000daf60
`Ordinal1001` | 1001 (0x3e9) | Exported Function | 0x000000018004c030 | 0x0004c030
`PFXImportCertStore` | 1304 (0x518) | Exported Function | 0x00000001800d7930 | 0x000d7930
`PFXExportCertStoreEx` | 1303 (0x517) | Exported Function | 0x00000001800d7680 | 0x000d7680
`PFXExportCertStore2` | 1302 (0x516) | Exported Function | 0x00000001800d7660 | 0x000d7660
`PFXExportCertStore` | 1301 (0x515) | Exported Function | 0x00000001800d7500 | 0x000d7500
`Ordinal2000` | 2000 (0x7d0) | Exported Function | 0x00000001800dd0e0 | 0x000dd0e0
`Ordinal1011` | 1011 (0x3f3) | Exported Function | 0x000000018006d290 | 0x0006d290
`Ordinal1010` | 1010 (0x3f2) | Exported Function | 0x000000018006d3a0 | 0x0006d3a0
`Ordinal1009` | 1009 (0x3f1) | Exported Function | 0x000000018006d370 | 0x0006d370
`Ordinal1008` | 1008 (0x3f0) | Exported Function | 0x000000018006d2f0 | 0x0006d2f0
`Ordinal1007` | 1007 (0x3ef) | Exported Function | 0x000000018006d2b0 | 0x0006d2b0
`Ordinal1006` | 1006 (0x3ee) | Exported Function | 0x000000018006d3c0 | 0x0006d3c0
`Ordinal1005` | 1005 (0x3ed) | Exported Function | 0x000000018006d3e0 | 0x0006d3e0
`Ordinal1004` | 1004 (0x3ec) | Exported Function | 0x000000018006d310 | 0x0006d310
`Ordinal1003` | 1003 (0x3eb) | Exported Function | 0x000000018006d330 | 0x0006d330
`Ordinal1002` | 1002 (0x3ea) | Exported Function | 0x000000018006d830 | 0x0006d830
`I_PFXImportCertStoreEx` | 1019 (0x3fb) | Exported Function | 0x00000001800d6a40 | 0x000d6a40
`I_CryptGetLruEntryData` | 1282 (0x502) | Exported Function | 0x000000018001c0e0 | 0x0001c0e0
`I_CryptGetFileVersion` | 1281 (0x501) | Exported Function | 0x000000018006d510 | 0x0006d510
`I_CryptGetDefaultCryptProvForEncrypt` | 1280 (0x500) | Exported Function | 0x00000001800b3fe0 | 0x000b3fe0
`I_CertUpdateStore` | 1259 (0x4eb) | Exported Function | 0x0000000180005b20 | 0x00005b20
`I_CertSyncStore` | 1258 (0x4ea) | Exported Function | 0x0000000180084320 | 0x00084320
`I_CertSrvProtectFunction` | 1257 (0x4e9) | Exported Function | 0x000000018001b490 | 0x0001b490
`I_CertProtectFunction` | 1256 (0x4e8) | Exported Function | 0x000000018001f930 | 0x0001f930
`I_CertProcessSslHandshake` | 1255 (0x4e7) | Exported Function | 0x00000001800299b0 | 0x000299b0
`I_CertFinishSslHandshake` | 1254 (0x4e6) | Exported Function | 0x0000000180029770 | 0x00029770
`I_CertDiagControl` | 1253 (0x4e5) | Exported Function | 0x000000018000e470 | 0x0000e470
`I_CertChainEngineIsDisallowedCertificate` | 1252 (0x4e4) | Exported Function | 0x00000001800265f0 | 0x000265f0
`CryptVerifyTimeStampSignature` | 1251 (0x4e3) | Exported Function | 0x0000000180003d60 | 0x00003d60
`CryptVerifyMessageSignatureWithKey` | 1250 (0x4e2) | Exported Function | 0x00000001800947c0 | 0x000947c0
`CryptVerifyMessageSignature` | 1249 (0x4e1) | Exported Function | 0x0000000180094740 | 0x00094740
`CryptVerifyMessageHash` | 1248 (0x4e0) | Exported Function | 0x00000001800946f0 | 0x000946f0
`CryptVerifyDetachedMessageSignature` | 1247 (0x4df) | Exported Function | 0x0000000180094670 | 0x00094670
`CryptVerifyDetachedMessageHash` | 1246 (0x4de) | Exported Function | 0x0000000180094610 | 0x00094610
`CryptVerifyCertificateSignatureEx` | 1245 (0x4dd) | Exported Function | 0x000000018002dfe0 | 0x0002dfe0
`I_CertWnfEnableFlushCache` | 1260 (0x4ec) | Exported Function | 0x000000018004eb00 | 0x0004eb00
`I_CryptAddRefLruEntry` | 1261 (0x4ed) | Exported Function | 0x00000001800cec40 | 0x000cec40
`I_CryptAddSmartCardCertToStore` | 1262 (0x4ee) | Exported Function | 0x00000001800b7c20 | 0x000b7c20
`I_CryptAllocTls` | 1263 (0x4ef) | Exported Function | 0x000000018000d650 | 0x0000d650
`I_CryptGetDefaultCryptProv` | 1279 (0x4ff) | Exported Function | 0x0000000180025340 | 0x00025340
`I_CryptGetAsn1Encoder` | 1278 (0x4fe) | Exported Function | 0x0000000180040eb0 | 0x00040eb0
`I_CryptGetAsn1Decoder` | 1277 (0x4fd) | Exported Function | 0x000000018003bf20 | 0x0003bf20
`I_CryptFreeTls` | 1276 (0x4fc) | Exported Function | 0x000000018000de20 | 0x0000de20
`I_CryptFreeLruCache` | 1275 (0x4fb) | Exported Function | 0x000000018001be20 | 0x0001be20
`I_CryptFlushLruCache` | 1274 (0x4fa) | Exported Function | 0x0000000180029710 | 0x00029710
`I_CryptFindSmartCardCertInStore` | 1273 (0x4f9) | Exported Function | 0x00000001800b7d40 | 0x000b7d40
`CryptUpdateProtectedState` | 1243 (0x4db) | Exported Function | DPAPI.CryptUpdateProtectedState | 0x0014185a
`I_CryptFindLruEntryData` | 1272 (0x4f8) | Exported Function | 0x00000001800ced10 | 0x000ced10
`I_CryptEnumMatchingLruEntries` | 1270 (0x4f6) | Exported Function | 0x00000001800056c0 | 0x000056c0
`I_CryptEnableLruOfEntries` | 1269 (0x4f5) | Exported Function | 0x00000001800ceca0 | 0x000ceca0
`I_CryptDisableLruOfEntries` | 1268 (0x4f4) | Exported Function | 0x00000001800cec50 | 0x000cec50
`I_CryptDetachTls` | 1267 (0x4f3) | Exported Function | 0x0000000180015d00 | 0x00015d00
`I_CryptCreateLruEntry` | 1266 (0x4f2) | Exported Function | 0x000000018002da10 | 0x0002da10
`I_CryptCreateLruCache` | 1265 (0x4f1) | Exported Function | 0x000000018002dcc0 | 0x0002dcc0
`I_CryptAllocTlsEx` | 1264 (0x4f0) | Exported Function | 0x000000018000dd50 | 0x0000dd50
`I_CryptFindLruEntry` | 1271 (0x4f7) | Exported Function | 0x00000001800128e0 | 0x000128e0
`PFXIsPFXBlob` | 1305 (0x519) | Exported Function | 0x00000001800d7960 | 0x000d7960
`CryptGetMessageCertificates` | 1173 (0x495) | Exported Function | 0x0000000180093db0 | 0x00093db0
`CryptGetDefaultOIDFunctionAddress` | 1171 (0x493) | Exported Function | 0x00000001800254e0 | 0x000254e0
`CertFindCTLInStore` | 1071 (0x42f) | Exported Function | 0x0000000180083a20 | 0x00083a20
`CertFindCRLInStore` | 1070 (0x42e) | Exported Function | 0x000000018002cf00 | 0x0002cf00
`CertFindChainInStore` | 1074 (0x432) | Exported Function | 0x000000018008d180 | 0x0008d180
`CertFindCertificateInStore` | 1073 (0x431) | Exported Function | 0x000000018002de10 | 0x0002de10
`CertFindCertificateInCRL` | 1072 (0x430) | Exported Function | 0x000000018001af20 | 0x0001af20
`CertFindAttribute` | 1069 (0x42d) | Exported Function | 0x0000000180023f90 | 0x00023f90
`CertEnumSystemStoreLocation` | 1068 (0x42c) | Exported Function | 0x000000018008c400 | 0x0008c400
`CertEnumSystemStore` | 1067 (0x42b) | Exported Function | 0x000000018008c070 | 0x0008c070
`CertEnumSubjectInSortedCTL` | 1066 (0x42a) | Exported Function | 0x00000001800838b0 | 0x000838b0
`CertEnumPhysicalStore` | 1065 (0x429) | Exported Function | 0x000000018008c050 | 0x0008c050
`CertEnumCTLsInStore` | 1062 (0x426) | Exported Function | 0x0000000180048e60 | 0x00048e60
`CertEnumCTLContextProperties` | 1061 (0x425) | Exported Function | 0x0000000180083890 | 0x00083890
`CertEnumCRLsInStore` | 1060 (0x424) | Exported Function | 0x0000000180005d80 | 0x00005d80
`CertEnumCRLContextProperties` | 1059 (0x423) | Exported Function | 0x0000000180083890 | 0x00083890
`CertEnumCertificatesInStore` | 1064 (0x428) | Exported Function | 0x000000018002d030 | 0x0002d030
`CertFindExtension` | 1075 (0x433) | Exported Function | 0x0000000180028290 | 0x00028290
`CertEnumCertificateContextProperties` | 1063 (0x427) | Exported Function | 0x0000000180083890 | 0x00083890
`CertFindRDNAttr` | 1076 (0x434) | Exported Function | 0x0000000180086d70 | 0x00086d70
`CertFindSubjectInSortedCTL` | 1078 (0x436) | Exported Function | 0x0000000180041550 | 0x00041550
`CertGetIssuerCertificateFromStore` | 1093 (0x445) | Exported Function | 0x0000000180083b70 | 0x00083b70
`CertGetIntendedKeyUsage` | 1092 (0x444) | Exported Function | 0x0000000180027090 | 0x00027090
`CertGetEnhancedKeyUsage` | 1091 (0x443) | Exported Function | 0x0000000180028600 | 0x00028600
`CertGetCTLContextProperty` | 1088 (0x440) | Exported Function | 0x0000000180035530 | 0x00035530
`CertGetCRLFromStore` | 1087 (0x43f) | Exported Function | 0x0000000180083a80 | 0x00083a80
`CertGetCRLContextProperty` | 1086 (0x43e) | Exported Function | 0x0000000180035530 | 0x00035530
`CertGetCertificateContextProperty` | 1090 (0x442) | Exported Function | 0x0000000180035530 | 0x00035530
`CertGetCertificateChain` | 1089 (0x441) | Exported Function | 0x000000018002bde0 | 0x0002bde0
`CertFreeServerOcspResponseContext` | 1085 (0x43d) | Exported Function | 0x0000000180086590 | 0x00086590
`CertFreeCTLContext` | 1080 (0x438) | Exported Function | 0x000000018001a7f0 | 0x0001a7f0
`CertFreeCRLContext` | 1079 (0x437) | Exported Function | 0x000000018001a7f0 | 0x0001a7f0
`CertFreeCertificateContext` | 1084 (0x43c) | Exported Function | 0x000000018002eb80 | 0x0002eb80
`CertFreeCertificateChainList` | 1083 (0x43b) | Exported Function | 0x000000018008d550 | 0x0008d550
`CertFreeCertificateChainEngine` | 1082 (0x43a) | Exported Function | 0x00000001800cd9d0 | 0x000cd9d0
`CertFreeCertificateChain` | 1081 (0x439) | Exported Function | 0x0000000180022a70 | 0x00022a70
`CertFindSubjectInCTL` | 1077 (0x435) | Exported Function | 0x0000000180023350 | 0x00023350
`CertDuplicateStore` | 1058 (0x422) | Exported Function | 0x000000018001a130 | 0x0001a130
`CertDuplicateCTLContext` | 1055 (0x41f) | Exported Function | 0x0000000180019480 | 0x00019480
`CertDuplicateCRLContext` | 1054 (0x41e) | Exported Function | 0x0000000180019480 | 0x00019480
`CertAddStoreToCollection` | 1035 (0x40b) | Exported Function | 0x0000000180045bd0 | 0x00045bd0
`CertAddSerializedElementToStore` | 1034 (0x40a) | Exported Function | 0x00000001800221b0 | 0x000221b0
`CertAddRefServerOcspResponseContext` | 1033 (0x409) | Exported Function | 0x0000000180086500 | 0x00086500
`CertAddRefServerOcspResponse` | 1032 (0x408) | Exported Function | 0x00000001800864e0 | 0x000864e0
`CertAddEnhancedKeyUsageIdentifier` | 1031 (0x407) | Exported Function | 0x0000000180084ae0 | 0x00084ae0
`CertAddEncodedCTLToStore` | 1027 (0x403) | Exported Function | 0x0000000180008400 | 0x00008400
`CertAddEncodedCRLToStore` | 1026 (0x402) | Exported Function | 0x0000000180019b10 | 0x00019b10
`CertAddEncodedCertificateToSystemStoreW` | 1030 (0x406) | Exported Function | 0x00000001800843c0 | 0x000843c0
`CertAddEncodedCertificateToSystemStoreA` | 1029 (0x405) | Exported Function | 0x0000000180084340 | 0x00084340
`CertAddEncodedCertificateToStore` | 1028 (0x404) | Exported Function | 0x000000018002fa00 | 0x0002fa00
`CertAddCTLLinkToStore` | 1023 (0x3ff) | Exported Function | 0x00000001800832d0 | 0x000832d0
`CertAddCTLContextToStore` | 1022 (0x3fe) | Exported Function | 0x0000000180083250 | 0x00083250
`CertAddCRLLinkToStore` | 1021 (0x3fd) | Exported Function | 0x00000001800832d0 | 0x000832d0
`CertAddCRLContextToStore` | 1020 (0x3fc) | Exported Function | 0x0000000180083250 | 0x00083250
`CertAddCertificateLinkToStore` | 1025 (0x401) | Exported Function | 0x00000001800832d0 | 0x000832d0
`CertAlgIdToOID` | 1036 (0x40c) | Exported Function | 0x0000000180086d10 | 0x00086d10
`CertCloseServerOcspResponse` | 1037 (0x40d) | Exported Function | 0x0000000180086520 | 0x00086520
`CertCloseStore` | 1038 (0x40e) | Exported Function | 0x0000000180031650 | 0x00031650
`CertCompareCertificate` | 1039 (0x40f) | Exported Function | 0x00000001800175c0 | 0x000175c0
`CertDuplicateCertificateContext` | 1057 (0x421) | Exported Function | 0x000000018002aeb0 | 0x0002aeb0
`CertDuplicateCertificateChain` | 1056 (0x420) | Exported Function | 0x000000018001a170 | 0x0001a170
`CertDeleteCTLFromStore` | 1052 (0x41c) | Exported Function | 0x0000000180083870 | 0x00083870
`CertDeleteCRLFromStore` | 1051 (0x41b) | Exported Function | 0x0000000180083870 | 0x00083870
`CertDeleteCertificateFromStore` | 1053 (0x41d) | Exported Function | 0x0000000180083870 | 0x00083870
`CertCreateSelfSignCertificate` | 1050 (0x41a) | Exported Function | 0x0000000180087320 | 0x00087320
`CertCreateCTLEntryFromCertificateContextProperties` | 1046 (0x416) | Exported Function | 0x0000000180083330 | 0x00083330
`CertGetNameStringA` | 1094 (0x446) | Exported Function | 0x000000018008e100 | 0x0008e100
`CertCreateCTLContext` | 1045 (0x415) | Exported Function | 0x00000001800083c0 | 0x000083c0
`CertCreateContext` | 1049 (0x419) | Exported Function | 0x000000018001ec90 | 0x0001ec90
`CertCreateCertificateContext` | 1048 (0x418) | Exported Function | 0x0000000180016010 | 0x00016010
`CertCreateCertificateChainEngine` | 1047 (0x417) | Exported Function | 0x00000001800cd9c0 | 0x000cd9c0
`CertControlStore` | 1043 (0x413) | Exported Function | 0x000000018001f2d0 | 0x0001f2d0
`CertComparePublicKeyInfo` | 1042 (0x412) | Exported Function | 0x0000000180036550 | 0x00036550
`CertCompareIntegerBlob` | 1041 (0x411) | Exported Function | 0x0000000180086d50 | 0x00086d50
`CertCompareCertificateName` | 1040 (0x410) | Exported Function | 0x0000000180027450 | 0x00027450
`CertCreateCRLContext` | 1044 (0x414) | Exported Function | 0x0000000180019ad0 | 0x00019ad0
`CryptGetKeyIdentifierProperty` | 1172 (0x494) | Exported Function | 0x0000000180084040 | 0x00084040
`CertGetNameStringW` | 1095 (0x447) | Exported Function | 0x0000000180027660 | 0x00027660
`CertGetServerOcspResponseContext` | 1097 (0x449) | Exported Function | 0x00000001800865e0 | 0x000865e0
`CryptDecodeObjectEx` | 1151 (0x47f) | Exported Function | 0x0000000180036940 | 0x00036940
`CryptDecodeObject` | 1150 (0x47e) | Exported Function | 0x0000000180036900 | 0x00036900
`CryptDecodeMessage` | 1149 (0x47d) | Exported Function | 0x0000000180093990 | 0x00093990
`CryptCreateKeyIdentifierFromCSP` | 1148 (0x47c) | Exported Function | 0x000000018008f6e0 | 0x0008f6e0
`CryptCreateAsyncHandle` | 1147 (0x47b) | Exported Function | 0x0000000180091f90 | 0x00091f90
`CryptCloseAsyncHandle` | 1146 (0x47a) | Exported Function | 0x0000000180091f60 | 0x00091f60
`CryptBinaryToStringW` | 1145 (0x479) | Exported Function | 0x00000001800217c0 | 0x000217c0
`CryptBinaryToStringA` | 1144 (0x478) | Exported Function | 0x0000000180021900 | 0x00021900
`CryptAcquireCertificatePrivateKey` | 1143 (0x477) | Exported Function | 0x000000018004cdb0 | 0x0004cdb0
`CertVerifyValidityNesting` | 1142 (0x476) | Exported Function | 0x0000000180087150 | 0x00087150
`CertVerifyTimeValidity` | 1141 (0x475) | Exported Function | 0x00000001800450c0 | 0x000450c0
`CertVerifySubjectCertificateContext` | 1140 (0x474) | Exported Function | 0x0000000180083ef0 | 0x00083ef0
`CertVerifyRevocation` | 1139 (0x473) | Exported Function | 0x0000000180024950 | 0x00024950
`CertVerifyCTLUsage` | 1137 (0x471) | Exported Function | 0x0000000180090d60 | 0x00090d60
`CertVerifyCRLTimeValidity` | 1136 (0x470) | Exported Function | 0x0000000180087090 | 0x00087090
`CryptDecryptAndVerifyMessageSignature` | 1152 (0x480) | Exported Function | 0x0000000180093a30 | 0x00093a30
`CertVerifyCRLRevocation` | 1135 (0x46f) | Exported Function | 0x0000000180087000 | 0x00087000
`CryptDecryptMessage` | 1153 (0x481) | Exported Function | 0x0000000180093c60 | 0x00093c60
`CryptEncodeObjectEx` | 1155 (0x483) | Exported Function | 0x0000000180038e30 | 0x00038e30
`CryptGetDefaultOIDDllList` | 1170 (0x492) | Exported Function | 0x0000000180025430 | 0x00025430
`CryptGetAsyncParam` | 1169 (0x491) | Exported Function | 0x0000000180091fc0 | 0x00091fc0
`CryptFreeOIDFunctionAddress` | 1168 (0x490) | Exported Function | 0x00000001800250b0 | 0x000250b0
`CryptFormatObject` | 1167 (0x48f) | Exported Function | 0x00000001800ae500 | 0x000ae500
`CryptFindOIDInfo` | 1166 (0x48e) | Exported Function | 0x0000000180037930 | 0x00037930
`CryptFindLocalizedName` | 1165 (0x48d) | Exported Function | 0x00000001800a2de0 | 0x000a2de0
`CryptFindCertificateKeyProvInfo` | 1164 (0x48c) | Exported Function | 0x00000001800871b0 | 0x000871b0
`CryptExportPublicKeyInfoFromBCryptKeyHandle` | 1163 (0x48b) | Exported Function | 0x000000018008f7b0 | 0x0008f7b0
`CryptExportPublicKeyInfoEx` | 1162 (0x48a) | Exported Function | 0x000000018004d150 | 0x0004d150
`CryptExportPublicKeyInfo` | 1161 (0x489) | Exported Function | 0x000000018008f770 | 0x0008f770
`CryptExportPKCS8` | 1160 (0x488) | Exported Function | 0x00000001800d89d0 | 0x000d89d0
`CryptEnumOIDInfo` | 1159 (0x487) | Exported Function | 0x00000001800a2ce0 | 0x000a2ce0
`CryptEnumOIDFunction` | 1158 (0x486) | Exported Function | 0x00000001800439f0 | 0x000439f0
`CryptEnumKeyIdentifierProperties` | 1157 (0x485) | Exported Function | 0x0000000180083f40 | 0x00083f40
`CryptEncryptMessage` | 1156 (0x484) | Exported Function | 0x0000000180093cd0 | 0x00093cd0
`CryptEncodeObject` | 1154 (0x482) | Exported Function | 0x000000018001a540 | 0x0001a540
`CertVerifyCertificateChainPolicy` | 1138 (0x472) | Exported Function | 0x0000000180039570 | 0x00039570
`CertUnregisterSystemStore` | 1134 (0x46e) | Exported Function | 0x000000018008c9f0 | 0x0008c9f0
`CertUnregisterPhysicalStore` | 1133 (0x46d) | Exported Function | 0x000000018008c8d0 | 0x0008c8d0
`CertRDNValueToStrA` | 1112 (0x458) | Exported Function | 0x000000018008e1c0 | 0x0008e1c0
`CertOpenSystemStoreW` | 1111 (0x457) | Exported Function | 0x00000001800844c0 | 0x000844c0
`CertOpenSystemStoreA` | 1110 (0x456) | Exported Function | 0x0000000180084440 | 0x00084440
`CertOpenStore` | 1109 (0x455) | Exported Function | 0x000000018003d180 | 0x0003d180
`CertOpenServerOcspResponse` | 1108 (0x454) | Exported Function | 0x00000001800866c0 | 0x000866c0
`CertOIDToAlgId` | 1107 (0x453) | Exported Function | 0x0000000180023530 | 0x00023530
`CertNameToStrW` | 1106 (0x452) | Exported Function | 0x0000000180018430 | 0x00018430
`CertNameToStrA` | 1105 (0x451) | Exported Function | 0x000000018004c420 | 0x0004c420
`CertIsWeakHash` | 1104 (0x450) | Exported Function | 0x000000018002c720 | 0x0002c720
`CertIsValidCRLForCertificate` | 1103 (0x44f) | Exported Function | 0x00000001800091f0 | 0x000091f0
`CertIsStrongHashToSign` | 1102 (0x44e) | Exported Function | 0x00000001800901e0 | 0x000901e0
`CertIsRDNAttrsInCertificateName` | 1101 (0x44d) | Exported Function | 0x0000000180086de0 | 0x00086de0
`CertGetValidUsages` | 1100 (0x44c) | Exported Function | 0x0000000180027cb0 | 0x00027cb0
`CertGetSubjectCertificateFromStore` | 1099 (0x44b) | Exported Function | 0x0000000180019e70 | 0x00019e70
`CertGetStoreProperty` | 1098 (0x44a) | Exported Function | 0x0000000180083c70 | 0x00083c70
`CertRDNValueToStrW` | 1113 (0x459) | Exported Function | 0x000000018008e290 | 0x0008e290
`CertRegisterPhysicalStore` | 1114 (0x45a) | Exported Function | 0x000000018008c500 | 0x0008c500
`CertRegisterSystemStore` | 1115 (0x45b) | Exported Function | 0x000000018008c7c0 | 0x0008c7c0
`CertRemoveEnhancedKeyUsageIdentifier` | 1116 (0x45c) | Exported Function | 0x0000000180084cb0 | 0x00084cb0
`CertStrToNameW` | 1132 (0x46c) | Exported Function | 0x0000000180009680 | 0x00009680
`CertStrToNameA` | 1131 (0x46b) | Exported Function | 0x000000018008e440 | 0x0008e440
`CertSetStoreProperty` | 1130 (0x46a) | Exported Function | 0x0000000180083e70 | 0x00083e70
`CertSetEnhancedKeyUsage` | 1129 (0x469) | Exported Function | 0x0000000180084db0 | 0x00084db0
`CertSetCTLContextProperty` | 1126 (0x466) | Exported Function | 0x0000000180019aa0 | 0x00019aa0
`CertSetCRLContextProperty` | 1125 (0x465) | Exported Function | 0x0000000180019aa0 | 0x00019aa0
`CertSetCertificateContextProperty` | 1128 (0x468) | Exported Function | 0x0000000180019aa0 | 0x00019aa0
`CertGetPublicKeyLength` | 1096 (0x448) | Exported Function | 0x0000000180024e10 | 0x00024e10
`CertSetCertificateContextPropertiesFromCTLEntry` | 1127 (0x467) | Exported Function | 0x00000001800071f0 | 0x000071f0
`CertSerializeCRLStoreElement` | 1122 (0x462) | Exported Function | 0x0000000180016a00 | 0x00016a00
`CertSerializeCertificateStoreElement` | 1124 (0x464) | Exported Function | 0x0000000180016a00 | 0x00016a00
`CertSelectCertificateChains` | 1121 (0x461) | Exported Function | 0x000000018008d570 | 0x0008d570
`CertSaveStore` | 1120 (0x460) | Exported Function | 0x0000000180017cd0 | 0x00017cd0
`CertRetrieveLogoOrBiometricInfo` | 1119 (0x45f) | Exported Function | 0x0000000180090540 | 0x00090540
`CertResyncCertificateChainEngine` | 1118 (0x45e) | Exported Function | 0x00000001800cda10 | 0x000cda10
`CertRemoveStoreFromCollection` | 1117 (0x45d) | Exported Function | 0x0000000180019750 | 0x00019750
`CertSerializeCTLStoreElement` | 1123 (0x463) | Exported Function | 0x0000000180016a00 | 0x00016a00
`PFXVerifyPassword` | 1306 (0x51a) | Exported Function | 0x00000001800d79f0 | 0x000d79f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CRYPT32.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/08ed695dce1f42b48d18a3752fb2afc0cebd899f04b4bcb994f8f5e4810a1eff/detection/


## Possible Misuse

*The following table contains possible examples of `crypt32.dll` being misused. While `crypt32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Data is encrypted before being exfiltrated in order to hide the information that is being exfiltrated from detection or to make the exfiltration less conspicuous upon inspection by a defender. The encryption is performed by a utility, programming library, or custom algorithm on the data itself and is considered separate from any encryption performed by the command and control or file transfer protocol. Common file archive formats that can encrypt files are RAR and zip.\n\nOther exfiltration techniques likely apply as well to transfer the information out of the network, such as Exfiltration Over Command and Control Channel and Exfiltration Over Alternative Protocol\n\nDetection: Encryption software and encrypted files can be detected in many ways. Common utilities that may be present on the system or brought in by an adversary may be detectable through process monitoring and monitoring for command-line arguments for known encryption utilities. This may yield a significant amount of benign events, depending on how systems in the environment are typically used. Often the encryption key is stated within command-line invocation of the software. \n\nA process that loads the Windows DLL crypt32.dll may be used to perform encryption, decryption, or verification of file signatures. \n\nNetwork traffic may also be analyzed for entropy to determine if encrypted data is being transmitted. (Citation: Zhang 2013) If the communications channel is unencrypted, encrypted files of known file types can be detected in transit during exfiltration with a network intrusion detection or data loss prevention system analyzing file headers. (Citation: Wikipedia File Header Signatures)\n\nPlatforms: Linux, macOS, Windows\n\nData Sources: File monitoring, Binary file metadata, Process command-line parameters, Process monitoring\n\nRequires Network: No",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `crypt32.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-turla-lightneuron-event.json](https://github.com/eset/malware-ioc/blob/master/turla/misp-turla-lightneuron-event.json) | `"description": "Data is encrypted before being exfiltrated in order to hide the information that is being exfiltrated from detection or to make the exfiltration less conspicuous upon inspection by a defender. The encryption is performed by a utility, programming library, or custom algorithm on the data itself and is considered separate from any encryption performed by the command and control or file transfer protocol. Common file archive formats that can encrypt files are RAR and zip.\n\nOther exfiltration techniques likely apply as well to transfer the information out of the network, such as Exfiltration Over Command and Control Channel and Exfiltration Over Alternative Protocol\n\nDetection: Encryption software and encrypted files can be detected in many ways. Common utilities that may be present on the system or brought in by an adversary may be detectable through process monitoring and monitoring for command-line arguments for known encryption utilities. This may yield a significant amount of benign events, depending on how systems in the environment are typically used. Often the encryption key is stated within command-line invocation of the software. \n\nA process that loads the Windows DLL crypt32.dll may be used to perform encryption, decryption, or verification of file signatures. \n\nNetwork traffic may also be analyzed for entropy to determine if encrypted data is being transmitted. (Citation: Zhang 2013) If the communications channel is unencrypted, encrypted files of known file types can be detected in transit during exfiltration with a network intrusion detection or data loss prevention system analyzing file headers. (Citation: Wikipedia File Header Signatures)\n\nPlatforms: Linux, macOS, Windows\n\nData Sources: File monitoring, Binary file metadata, Process command-line parameters, Process monitoring\n\nRequires Network: No",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


