---
title: ncrypt.dll | Windows NCrypt Router
excerpt: What is ncrypt.dll?
---

# ncrypt.dll 

* File Path: `C:\Windows\SysWOW64\ncrypt.dll`
* Description: Windows NCrypt Router

## Hashes

Type | Hash
-- | --
MD5 | `EFBAC120346831ADFC627194DA1F1909`
SHA1 | `CB97A5EE04627A0559D6D9D0FDCD31447904ECD3`
SHA256 | `78B12C291A1EE38F08D20A04A5CE1EDDC539EF2080B5E17B91F6E6D8484C39B6`
SHA384 | `BA96C1CEE8CB4A8683CB098D42580A92F23DAFBF0451B138384556922E87470DF30EC41843969333DDFFF8CCB00886E1`
SHA512 | `C981D243AF6CB6EC3D64C59E59A3C6101C1143C7BEFC39BD226914FCCE2F284A9C7534BF2C76EF985A2DB1333D88C01FB26EAEBC28BFF7617E0F2728CC29F799`
SSDEEP | `1536:ZD8XnTLNWzju84oeFPuKEttTlolS1A6QzFGZZsmQ9DUvZE+iiDxoEJ9EzvP3p:wNWzEg5TSlSmze7Q9ghIEJ9EzvPp`
IMP | `75A030081D48AE34B620F6E918AD6941`
PESHA1 | `233318D8D875AACC560B0FF6E4753CD2FDF02066`
PE256 | `233C9AA67A649A1C7B3976E8342DE2EEA5A9341EE5EB095ECC38AFD3E1181991`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BCryptAddContextFunction` | 1 (0x1) | Exported Function | BCRYPT.BCryptAddContextFunction | 0x0001791e
`NCryptStreamOpenToProtect` | 96 (0x60) | Exported Function | 0x10012eb0 | 0x00012eb0
`NCryptStreamOpenToUnprotect` | 97 (0x61) | Exported Function | 0x10013120 | 0x00013120
`NCryptStreamOpenToUnprotectEx` | 98 (0x62) | Exported Function | 0x100131e0 | 0x000131e0
`NCryptStreamUpdate` | 99 (0x63) | Exported Function | 0x100132a0 | 0x000132a0
`NCryptTranslateHandle` | 100 (0x64) | Exported Function | 0x1000f1b0 | 0x0000f1b0
`NCryptUnprotectKey` | 101 (0x65) | Exported Function | 0x10010880 | 0x00010880
`NCryptStreamClose` | 95 (0x5f) | Exported Function | 0x10012e60 | 0x00012e60
`NCryptUnprotectSecret` | 102 (0x66) | Exported Function | 0x100123e0 | 0x000123e0
`NCryptVerifySignature` | 104 (0x68) | Exported Function | 0x1000f7a0 | 0x0000f7a0
`SslChangeNotify` | 105 (0x69) | Exported Function | 0x1000d010 | 0x0000d010
`SslComputeClientAuthHash` | 106 (0x6a) | Exported Function | 0x1000d020 | 0x0000d020
`SslComputeEapKeyBlock` | 107 (0x6b) | Exported Function | 0x1000d0d0 | 0x0000d0d0
`SslComputeFinishedHash` | 108 (0x6c) | Exported Function | 0x10005330 | 0x00005330
`SslComputeSessionHash` | 109 (0x6d) | Exported Function | 0x100047f0 | 0x000047f0
`NCryptVerifyClaim` | 103 (0x67) | Exported Function | 0x1000f640 | 0x0000f640
`NCryptSignHash` | 94 (0x5e) | Exported Function | 0x10006800 | 0x00006800
`NCryptSetProperty` | 93 (0x5d) | Exported Function | 0x10005050 | 0x00005050
`NCryptSetAuditingInterface` | 92 (0x5c) | Exported Function | 0x10007200 | 0x00007200
`NCryptGetProperty` | 77 (0x4d) | Exported Function | 0x100065a0 | 0x000065a0
`NCryptGetProtectionDescriptorInfo` | 78 (0x4e) | Exported Function | 0x10012070 | 0x00012070
`NCryptImportKey` | 79 (0x4f) | Exported Function | 0x10002ff0 | 0x00002ff0
`NCryptIsAlgSupported` | 80 (0x50) | Exported Function | 0x10006510 | 0x00006510
`NCryptIsKeyHandle` | 81 (0x51) | Exported Function | 0x100072b0 | 0x000072b0
`NCryptKeyDerivation` | 82 (0x52) | Exported Function | 0x1000edd0 | 0x0000edd0
`NCryptNotifyChangeKey` | 83 (0x53) | Exported Function | 0x1000ef50 | 0x0000ef50
`NCryptOpenKey` | 84 (0x54) | Exported Function | 0x100044f0 | 0x000044f0
`NCryptOpenKeyProtector` | 85 (0x55) | Exported Function | 0x100105a0 | 0x000105a0
`NCryptOpenStorageProvider` | 86 (0x56) | Exported Function | 0x10005680 | 0x00005680
`NCryptProtectKey` | 87 (0x57) | Exported Function | 0x100107a0 | 0x000107a0
`NCryptProtectSecret` | 88 (0x58) | Exported Function | 0x10012100 | 0x00012100
`NCryptQueryProtectionDescriptorName` | 89 (0x59) | Exported Function | 0x10012770 | 0x00012770
`NCryptRegisterProtectionDescriptorName` | 90 (0x5a) | Exported Function | 0x10012890 | 0x00012890
`NCryptSecretAgreement` | 91 (0x5b) | Exported Function | 0x100048a0 | 0x000048a0
`SslCreateClientAuthHash` | 110 (0x6e) | Exported Function | 0x10003fe0 | 0x00003fe0
`SslCreateEphemeralKey` | 111 (0x6f) | Exported Function | 0x10004cc0 | 0x00004cc0
`SslCreateHandshakeHash` | 112 (0x70) | Exported Function | 0x10004db0 | 0x00004db0
`SslDecrementProviderReferenceCount` | 113 (0x71) | Exported Function | 0x10004410 | 0x00004410
`SslFreeObject` | 133 (0x85) | Exported Function | 0x100038d0 | 0x000038d0
`SslGenerateMasterKey` | 134 (0x86) | Exported Function | 0x10004a20 | 0x00004a20
`SslGeneratePreMasterKey` | 135 (0x87) | Exported Function | 0x1000dcd0 | 0x0000dcd0
`SslGenerateSessionKeys` | 136 (0x88) | Exported Function | 0x10004b70 | 0x00004b70
`SslGetCipherSuitePRFHashAlgorithm` | 137 (0x89) | Exported Function | 0x10004990 | 0x00004990
`SslGetKeyProperty` | 138 (0x8a) | Exported Function | 0x1000de20 | 0x0000de20
`SslGetProviderProperty` | 139 (0x8b) | Exported Function | 0x1000df00 | 0x0000df00
`SslHashHandshake` | 140 (0x8c) | Exported Function | 0x10003b30 | 0x00003b30
`SslImportKey` | 141 (0x8d) | Exported Function | 0x10003ee0 | 0x00003ee0
`SslImportMasterKey` | 142 (0x8e) | Exported Function | 0x1000e0b0 | 0x0000e0b0
`SslIncrementProviderReferenceCount` | 143 (0x8f) | Exported Function | 0x10004340 | 0x00004340
`SslLookupCipherLengths` | 144 (0x90) | Exported Function | 0x100040e0 | 0x000040e0
`SslLookupCipherSuiteInfo` | 145 (0x91) | Exported Function | 0x10004190 | 0x00004190
`SslOpenPrivateKey` | 146 (0x92) | Exported Function | 0x10006460 | 0x00006460
`SslOpenProvider` | 147 (0x93) | Exported Function | 0x10004670 | 0x00004670
`SslFreeBuffer` | 132 (0x84) | Exported Function | 0x10006d80 | 0x00006d80
`NCryptFreeObject` | 76 (0x4c) | Exported Function | 0x100035c0 | 0x000035c0
`SslExtractMasterKey` | 131 (0x83) | Exported Function | 0x1000db80 | 0x0000db80
`SslExtractEarlyKey` | 129 (0x81) | Exported Function | 0x1000d8a0 | 0x0000d8a0
`SslDecryptPacket` | 114 (0x72) | Exported Function | 0x10003be0 | 0x00003be0
`SslDuplicateTranscriptHash` | 115 (0x73) | Exported Function | 0x10007b00 | 0x00007b00
`SslEncryptPacket` | 116 (0x74) | Exported Function | 0x10003e20 | 0x00003e20
`SslEnumCipherSuites` | 117 (0x75) | Exported Function | 0x1000d160 | 0x0000d160
`SslEnumCipherSuitesEx` | 118 (0x76) | Exported Function | 0x100068e0 | 0x000068e0
`SslEnumEccCurves` | 119 (0x77) | Exported Function | 0x10006ad0 | 0x00006ad0
`SslEnumProtocolProviders` | 120 (0x78) | Exported Function | 0x10006e50 | 0x00006e50
`SslExpandBinderKey` | 121 (0x79) | Exported Function | 0x10007c40 | 0x00007c40
`SslExpandExporterMasterKey` | 122 (0x7a) | Exported Function | 0x1000d320 | 0x0000d320
`SslExpandPreSharedKey` | 123 (0x7b) | Exported Function | 0x10007d70 | 0x00007d70
`SslExpandResumptionMasterKey` | 124 (0x7c) | Exported Function | 0x10007eb0 | 0x00007eb0
`SslExpandTrafficKeys` | 125 (0x7d) | Exported Function | 0x1000d490 | 0x0000d490
`SslExpandWriteKey` | 126 (0x7e) | Exported Function | 0x1000d6a0 | 0x0000d6a0
`SslExportKey` | 127 (0x7f) | Exported Function | 0x10003ca0 | 0x00003ca0
`SslExportKeyingMaterial` | 128 (0x80) | Exported Function | 0x1000d7f0 | 0x0000d7f0
`SslExtractHandshakeKey` | 130 (0x82) | Exported Function | 0x1000da00 | 0x0000da00
`SslSignHash` | 148 (0x94) | Exported Function | 0x100063d0 | 0x000063d0
`NCryptFreeBuffer` | 75 (0x4b) | Exported Function | 0x10007120 | 0x00007120
`NCryptExportKey` | 73 (0x49) | Exported Function | 0x10003d50 | 0x00003d50
`BCryptEnumContextFunctions` | 21 (0x15) | Exported Function | BCRYPT.BCryptEnumContextFunctions | 0x00017d10
`BCryptEnumContexts` | 22 (0x16) | Exported Function | BCRYPT.BCryptEnumContexts | 0x00017d45
`BCryptEnumProviders` | 23 (0x17) | Exported Function | BCRYPT.BCryptEnumProviders | 0x00017d73
`BCryptEnumRegisteredProviders` | 24 (0x18) | Exported Function | BCRYPT.BCryptEnumRegisteredProviders | 0x00017dac
`BCryptExportKey` | 25 (0x19) | Exported Function | BCRYPT.BCryptExportKey | 0x00017de1
`BCryptFinalizeKeyPair` | 26 (0x1a) | Exported Function | BCRYPT.BCryptFinalizeKeyPair | 0x00017e0e
`BCryptEnumContextFunctionProviders` | 20 (0x14) | Exported Function | BCRYPT.BCryptEnumContextFunctionProviders | 0x00017ccb
`BCryptFinishHash` | 27 (0x1b) | Exported Function | BCRYPT.BCryptFinishHash | 0x00017e3c
`BCryptGenerateKeyPair` | 30 (0x1e) | Exported Function | BCRYPT.BCryptGenerateKeyPair | 0x00017eba
`BCryptGenerateSymmetricKey` | 31 (0x1f) | Exported Function | BCRYPT.BCryptGenerateSymmetricKey | 0x00017ef2
`BCryptGenRandom` | 29 (0x1d) | Exported Function | BCRYPT.BCryptGenRandom | 0x00017e8d
`BCryptGetFipsAlgorithmMode` | 32 (0x20) | Exported Function | BCRYPT.BCryptGetFipsAlgorithmMode | 0x00017f2f
`BCryptGetProperty` | 33 (0x21) | Exported Function | BCRYPT.BCryptGetProperty | 0x00017f63
`BCryptHash` | 34 (0x22) | Exported Function | BCRYPT.BCryptHash | 0x00017f87
`BCryptFreeBuffer` | 28 (0x1c) | Exported Function | BCRYPT.BCryptFreeBuffer | 0x00017e65
`BCryptEnumAlgorithms` | 19 (0x13) | Exported Function | BCRYPT.BCryptEnumAlgorithms | 0x00017c8c
`BCryptEncrypt` | 18 (0x12) | Exported Function | BCRYPT.BCryptEncrypt | 0x00017c62
`BCryptDuplicateKey` | 17 (0x11) | Exported Function | BCRYPT.BCryptDuplicateKey | 0x00017c3a
`BCryptAddContextFunctionProvider` | 2 (0x2) | Exported Function | BCRYPT.BCryptAddContextFunctionProvider | 0x0001795f
`BCryptCloseAlgorithmProvider` | 3 (0x3) | Exported Function | BCRYPT.BCryptCloseAlgorithmProvider | 0x000179a4
`BCryptConfigureContext` | 4 (0x4) | Exported Function | BCRYPT.BCryptConfigureContext | 0x000179df
`BCryptConfigureContextFunction` | 5 (0x5) | Exported Function | BCRYPT.BCryptConfigureContextFunction | 0x00017a1c
`BCryptCreateContext` | 6 (0x6) | Exported Function | BCRYPT.BCryptCreateContext | 0x00017a56
`BCryptCreateHash` | 7 (0x7) | Exported Function | BCRYPT.BCryptCreateHash | 0x00017a82
`BCryptDecrypt` | 8 (0x8) | Exported Function | BCRYPT.BCryptDecrypt | 0x00017aa8
`BCryptDeleteContext` | 9 (0x9) | Exported Function | BCRYPT.BCryptDeleteContext | 0x00017ad1
`BCryptDeriveKey` | 10 (0xa) | Exported Function | BCRYPT.BCryptDeriveKey | 0x00017afc
`BCryptDeriveKeyCapi` | 11 (0xb) | Exported Function | BCRYPT.BCryptDeriveKeyCapi | 0x00017b27
`BCryptDeriveKeyPBKDF2` | 12 (0xc) | Exported Function | BCRYPT.BCryptDeriveKeyPBKDF2 | 0x00017b58
`BCryptDestroyHash` | 13 (0xd) | Exported Function | BCRYPT.BCryptDestroyHash | 0x00017b87
`BCryptDestroyKey` | 14 (0xe) | Exported Function | BCRYPT.BCryptDestroyKey | 0x00017bb1
`BCryptDestroySecret` | 15 (0xf) | Exported Function | BCRYPT.BCryptDestroySecret | 0x00017bdd
`BCryptDuplicateHash` | 16 (0x10) | Exported Function | BCRYPT.BCryptDuplicateHash | 0x00017c0c
`BCryptHashData` | 35 (0x23) | Exported Function | BCRYPT.BCryptHashData | 0x00017fa8
`BCryptImportKey` | 36 (0x24) | Exported Function | BCRYPT.BCryptImportKey | 0x00017fce
`BCryptImportKeyPair` | 37 (0x25) | Exported Function | BCRYPT.BCryptImportKeyPair | 0x00017ff9
`BCryptKeyDerivation` | 38 (0x26) | Exported Function | BCRYPT.BCryptKeyDerivation | 0x00018028
`GetKeyStorageInterface` | 58 (0x3a) | Exported Function | 0x1000e3d0 | 0x0000e3d0
`GetSChannelInterface` | 59 (0x3b) | Exported Function | 0x1000e3d0 | 0x0000e3d0
`NCryptCloseKeyProtector` | 60 (0x3c) | Exported Function | 0x10010440 | 0x00010440
`NCryptCloseProtectionDescriptor` | 61 (0x3d) | Exported Function | 0x10011e10 | 0x00011e10
`NCryptCreateClaim` | 62 (0x3e) | Exported Function | 0x1000e6b0 | 0x0000e6b0
`NCryptCreatePersistedKey` | 63 (0x3f) | Exported Function | 0x10004f40 | 0x00004f40
`NCryptCreateProtectionDescriptor` | 64 (0x40) | Exported Function | 0x10011e80 | 0x00011e80
`NCryptDecrypt` | 65 (0x41) | Exported Function | 0x1000e840 | 0x0000e840
`NCryptDeleteKey` | 66 (0x42) | Exported Function | 0x10007080 | 0x00007080
`NCryptDeriveKey` | 67 (0x43) | Exported Function | 0x100052b0 | 0x000052b0
`NCryptDuplicateKeyProtectorHandle` | 68 (0x44) | Exported Function | 0x10010510 | 0x00010510
`NCryptEncrypt` | 69 (0x45) | Exported Function | 0x1000e970 | 0x0000e970
`NCryptEnumAlgorithms` | 70 (0x46) | Exported Function | 0x1000eaa0 | 0x0000eaa0
`NCryptEnumKeys` | 71 (0x47) | Exported Function | 0x10006ba0 | 0x00006ba0
`NCryptEnumStorageProviders` | 72 (0x48) | Exported Function | 0x1000ec30 | 0x0000ec30
`GetIsolationServerInterface` | 57 (0x39) | Exported Function | 0x1000e3d0 | 0x0000e3d0
`NCryptFinalizeKey` | 74 (0x4a) | Exported Function | 0x10004e90 | 0x00004e90
`BCryptVerifySignature` | 56 (0x38) | Exported Function | BCRYPT.BCryptVerifySignature | 0x0001849a
`BCryptUnregisterConfigChangeNotify` | 54 (0x36) | Exported Function | BCRYPT.BCryptUnregisterConfigChangeNotify | 0x00018421
`BCryptOpenAlgorithmProvider` | 39 (0x27) | Exported Function | BCRYPT.BCryptOpenAlgorithmProvider | 0x0001805f
`BCryptQueryContextConfiguration` | 40 (0x28) | Exported Function | BCRYPT.BCryptQueryContextConfiguration | 0x000180a2
`BCryptQueryContextFunctionConfiguration` | 41 (0x29) | Exported Function | BCRYPT.BCryptQueryContextFunctionConfiguration | 0x000180f1
`BCryptQueryContextFunctionProperty` | 42 (0x2a) | Exported Function | BCRYPT.BCryptQueryContextFunctionProperty | 0x00018143
`BCryptQueryProviderRegistration` | 43 (0x2b) | Exported Function | BCRYPT.BCryptQueryProviderRegistration | 0x0001818d
`BCryptRegisterConfigChangeNotify` | 44 (0x2c) | Exported Function | BCRYPT.BCryptRegisterConfigChangeNotify | 0x000181d5
`BCryptRegisterProvider` | 45 (0x2d) | Exported Function | BCRYPT.BCryptRegisterProvider | 0x00018214
`BCryptRemoveContextFunction` | 46 (0x2e) | Exported Function | BCRYPT.BCryptRemoveContextFunction | 0x0001824e
`BCryptRemoveContextFunctionProvider` | 47 (0x2f) | Exported Function | BCRYPT.BCryptRemoveContextFunctionProvider | 0x00018295
`BCryptResolveProviders` | 48 (0x30) | Exported Function | BCRYPT.BCryptResolveProviders | 0x000182d7
`BCryptSecretAgreement` | 49 (0x31) | Exported Function | BCRYPT.BCryptSecretAgreement | 0x0001830b
`BCryptSetAuditingInterface` | 50 (0x32) | Exported Function | BCRYPT.BCryptSetAuditingInterface | 0x00018343
`BCryptSetContextFunctionProperty` | 51 (0x33) | Exported Function | BCRYPT.BCryptSetContextFunctionProperty | 0x00018386
`BCryptSetProperty` | 52 (0x34) | Exported Function | BCRYPT.BCryptSetProperty | 0x000183c0
`BCryptSignHash` | 53 (0x35) | Exported Function | BCRYPT.BCryptSignHash | 0x000183e8
`BCryptUnregisterProvider` | 55 (0x37) | Exported Function | BCRYPT.BCryptUnregisterProvider | 0x00018464
`SslVerifySignature` | 149 (0x95) | Exported Function | 0x1000e200 | 0x0000e200


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ncrypt.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/78b12c291a1ee38f08d20a04a5ce1eddc539ef2080b5e17b91f6e6d8484c39b6/detection/


## Possible Misuse

*The following table contains possible examples of `ncrypt.dll` being misused. While `ncrypt.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "NCryptOpenStorageProvider") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "NCryptEnumKeys") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "NCryptOpenKey") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "NCryptDecrypt") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "BCryptGenerateSymmetricKey") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "BCryptGetProperty") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "BCryptDecrypt") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_png_dropper_nov18.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_png_dropper_nov18.yar) | pe.imports("ncrypt.dll", "BCryptEncrypt") and | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


