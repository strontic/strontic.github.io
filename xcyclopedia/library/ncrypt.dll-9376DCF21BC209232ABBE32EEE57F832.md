---
title: ncrypt.dll | Windows NCrypt Router
excerpt: What is ncrypt.dll?
---

# ncrypt.dll 

* File Path: `C:\Windows\system32\ncrypt.dll`
* Description: Windows NCrypt Router

## Hashes

Type | Hash
-- | --
MD5 | `9376DCF21BC209232ABBE32EEE57F832`
SHA1 | `14467E7E7262ACD5CE56B2B834E2BFCA9CE0F95B`
SHA256 | `E860477B315B6965EB008E4548160E589723D5AB26CE3F33D80C3715B4E555BE`
SHA384 | `4408243D660AC61BDDADB64041FA86DCD0CA24ED8E79FF646DD3B3CA6C50DBBB3EDE14FC4062AACF33FC6485EA30506B`
SHA512 | `084A85D1A9923F2C92DD4BF5910DB82557FAA457D6A572CD51445EDE13A3F0D6C0B6B044DB60410F1A79CDA11E35D209789D02875D515611BCAD80C67D48C08C`
SSDEEP | `3072:XXtmvigm02+x2oIKM04hjZeU3T9CUz8ir1ZnT9J3iHQng/lcT4:XXt501ke4hjZeU3RrAeKQng/x`
IMP | `71CE678C1CCE44D29BCEC313566A1C73`
PESHA1 | `F34BA012AE5192D2A40A36E95BD400C6798962C9`
PE256 | `1181F21703BCF72F94FE9A460655BA85CB51EF92FD82A4E6D7A0B3F6D702F055`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BCryptAddContextFunction` | 1 (0x1) | Exported Function | BCRYPT.BCryptAddContextFunction | 0x0001d4ae
`NCryptStreamOpenToProtect` | 96 (0x60) | Exported Function | 0x0000000180013c50 | 0x00013c50
`NCryptStreamOpenToUnprotect` | 97 (0x61) | Exported Function | 0x0000000180013f50 | 0x00013f50
`NCryptStreamOpenToUnprotectEx` | 98 (0x62) | Exported Function | 0x0000000180014040 | 0x00014040
`NCryptStreamUpdate` | 99 (0x63) | Exported Function | 0x0000000180014130 | 0x00014130
`NCryptTranslateHandle` | 100 (0x64) | Exported Function | 0x000000018000ee00 | 0x0000ee00
`NCryptUnprotectKey` | 101 (0x65) | Exported Function | 0x0000000180010ca0 | 0x00010ca0
`NCryptStreamClose` | 95 (0x5f) | Exported Function | 0x0000000180013c00 | 0x00013c00
`NCryptUnprotectSecret` | 102 (0x66) | Exported Function | 0x0000000180012e20 | 0x00012e20
`NCryptVerifySignature` | 104 (0x68) | Exported Function | 0x000000018000f5c0 | 0x0000f5c0
`SslChangeNotify` | 105 (0x69) | Exported Function | 0x000000018000b8d0 | 0x0000b8d0
`SslComputeClientAuthHash` | 106 (0x6a) | Exported Function | 0x000000018000b8e0 | 0x0000b8e0
`SslComputeEapKeyBlock` | 107 (0x6b) | Exported Function | 0x000000018000b9c0 | 0x0000b9c0
`SslComputeFinishedHash` | 108 (0x6c) | Exported Function | 0x00000001800011b0 | 0x000011b0
`SslComputeSessionHash` | 109 (0x6d) | Exported Function | 0x0000000180002280 | 0x00002280
`NCryptVerifyClaim` | 103 (0x67) | Exported Function | 0x000000018000f400 | 0x0000f400
`NCryptSignHash` | 94 (0x5e) | Exported Function | 0x0000000180004840 | 0x00004840
`NCryptSetProperty` | 93 (0x5d) | Exported Function | 0x00000001800038e0 | 0x000038e0
`NCryptSetAuditingInterface` | 92 (0x5c) | Exported Function | 0x0000000180005ae0 | 0x00005ae0
`NCryptGetProperty` | 77 (0x4d) | Exported Function | 0x00000001800029d0 | 0x000029d0
`NCryptGetProtectionDescriptorInfo` | 78 (0x4e) | Exported Function | 0x0000000180012970 | 0x00012970
`NCryptImportKey` | 79 (0x4f) | Exported Function | 0x0000000180001890 | 0x00001890
`NCryptIsAlgSupported` | 80 (0x50) | Exported Function | 0x0000000180004b40 | 0x00004b40
`NCryptIsKeyHandle` | 81 (0x51) | Exported Function | 0x0000000180005bd0 | 0x00005bd0
`NCryptKeyDerivation` | 82 (0x52) | Exported Function | 0x000000018000e940 | 0x0000e940
`NCryptNotifyChangeKey` | 83 (0x53) | Exported Function | 0x000000018000eb30 | 0x0000eb30
`NCryptOpenKey` | 84 (0x54) | Exported Function | 0x0000000180004980 | 0x00004980
`NCryptOpenKeyProtector` | 85 (0x55) | Exported Function | 0x00000001800108b0 | 0x000108b0
`NCryptOpenStorageProvider` | 86 (0x56) | Exported Function | 0x0000000180003300 | 0x00003300
`NCryptProtectKey` | 87 (0x57) | Exported Function | 0x0000000180010b50 | 0x00010b50
`NCryptProtectSecret` | 88 (0x58) | Exported Function | 0x0000000180012a20 | 0x00012a20
`NCryptQueryProtectionDescriptorName` | 89 (0x59) | Exported Function | 0x00000001800132f0 | 0x000132f0
`NCryptRegisterProtectionDescriptorName` | 90 (0x5a) | Exported Function | 0x0000000180013470 | 0x00013470
`NCryptSecretAgreement` | 91 (0x5b) | Exported Function | 0x0000000180003dd0 | 0x00003dd0
`SslCreateClientAuthHash` | 110 (0x6e) | Exported Function | 0x0000000180003b00 | 0x00003b00
`SslCreateEphemeralKey` | 111 (0x6f) | Exported Function | 0x0000000180003570 | 0x00003570
`SslCreateHandshakeHash` | 112 (0x70) | Exported Function | 0x0000000180001470 | 0x00001470
`SslDecrementProviderReferenceCount` | 113 (0x71) | Exported Function | 0x0000000180002d60 | 0x00002d60
`SslFreeObject` | 133 (0x85) | Exported Function | 0x0000000180002be0 | 0x00002be0
`SslGenerateMasterKey` | 134 (0x86) | Exported Function | 0x0000000180001e50 | 0x00001e50
`SslGeneratePreMasterKey` | 135 (0x87) | Exported Function | 0x000000018000cfb0 | 0x0000cfb0
`SslGenerateSessionKeys` | 136 (0x88) | Exported Function | 0x00000001800012a0 | 0x000012a0
`SslGetCipherSuitePRFHashAlgorithm` | 137 (0x89) | Exported Function | 0x00000001800034f0 | 0x000034f0
`SslGetKeyProperty` | 138 (0x8a) | Exported Function | 0x000000018000d180 | 0x0000d180
`SslGetProviderProperty` | 139 (0x8b) | Exported Function | 0x000000018000d250 | 0x0000d250
`SslHashHandshake` | 140 (0x8c) | Exported Function | 0x00000001800010f0 | 0x000010f0
`SslImportKey` | 141 (0x8d) | Exported Function | 0x0000000180002140 | 0x00002140
`SslImportMasterKey` | 142 (0x8e) | Exported Function | 0x000000018000d470 | 0x0000d470
`SslIncrementProviderReferenceCount` | 143 (0x8f) | Exported Function | 0x0000000180003f40 | 0x00003f40
`SslLookupCipherLengths` | 144 (0x90) | Exported Function | 0x00000001800017a0 | 0x000017a0
`SslLookupCipherSuiteInfo` | 145 (0x91) | Exported Function | 0x0000000180003d40 | 0x00003d40
`SslOpenPrivateKey` | 146 (0x92) | Exported Function | 0x000000018000d630 | 0x0000d630
`SslOpenProvider` | 147 (0x93) | Exported Function | 0x0000000180003150 | 0x00003150
`SslFreeBuffer` | 132 (0x84) | Exported Function | 0x0000000180005670 | 0x00005670
`NCryptFreeObject` | 76 (0x4c) | Exported Function | 0x0000000180002e30 | 0x00002e30
`SslExtractMasterKey` | 131 (0x83) | Exported Function | 0x000000018000ce10 | 0x0000ce10
`SslExtractEarlyKey` | 129 (0x81) | Exported Function | 0x000000018000ca60 | 0x0000ca60
`SslDecryptPacket` | 114 (0x72) | Exported Function | 0x00000001800015a0 | 0x000015a0
`SslDuplicateTranscriptHash` | 115 (0x73) | Exported Function | 0x000000018000ba80 | 0x0000ba80
`SslEncryptPacket` | 116 (0x74) | Exported Function | 0x00000001800016a0 | 0x000016a0
`SslEnumCipherSuites` | 117 (0x75) | Exported Function | 0x000000018000bc20 | 0x0000bc20
`SslEnumCipherSuitesEx` | 118 (0x76) | Exported Function | 0x0000000180004f40 | 0x00004f40
`SslEnumEccCurves` | 119 (0x77) | Exported Function | 0x0000000180004c10 | 0x00004c10
`SslEnumProtocolProviders` | 120 (0x78) | Exported Function | 0x00000001800057a0 | 0x000057a0
`SslExpandBinderKey` | 121 (0x79) | Exported Function | 0x000000018000be50 | 0x0000be50
`SslExpandExporterMasterKey` | 122 (0x7a) | Exported Function | 0x000000018000bff0 | 0x0000bff0
`SslExpandPreSharedKey` | 123 (0x7b) | Exported Function | 0x000000018000c1b0 | 0x0000c1b0
`SslExpandResumptionMasterKey` | 124 (0x7c) | Exported Function | 0x000000018000c370 | 0x0000c370
`SslExpandTrafficKeys` | 125 (0x7d) | Exported Function | 0x000000018000c530 | 0x0000c530
`SslExpandWriteKey` | 126 (0x7e) | Exported Function | 0x000000018000c7c0 | 0x0000c7c0
`SslExportKey` | 127 (0x7f) | Exported Function | 0x0000000180001010 | 0x00001010
`SslExportKeyingMaterial` | 128 (0x80) | Exported Function | 0x000000018000c960 | 0x0000c960
`SslExtractHandshakeKey` | 130 (0x82) | Exported Function | 0x000000018000cc30 | 0x0000cc30
`SslSignHash` | 148 (0x94) | Exported Function | 0x0000000180004750 | 0x00004750
`NCryptFreeBuffer` | 75 (0x4b) | Exported Function | 0x00000001800055c0 | 0x000055c0
`NCryptExportKey` | 73 (0x49) | Exported Function | 0x0000000180003c20 | 0x00003c20
`BCryptEnumContextFunctions` | 21 (0x15) | Exported Function | BCRYPT.BCryptEnumContextFunctions | 0x0001d8a0
`BCryptEnumContexts` | 22 (0x16) | Exported Function | BCRYPT.BCryptEnumContexts | 0x0001d8d5
`BCryptEnumProviders` | 23 (0x17) | Exported Function | BCRYPT.BCryptEnumProviders | 0x0001d903
`BCryptEnumRegisteredProviders` | 24 (0x18) | Exported Function | BCRYPT.BCryptEnumRegisteredProviders | 0x0001d93c
`BCryptExportKey` | 25 (0x19) | Exported Function | BCRYPT.BCryptExportKey | 0x0001d971
`BCryptFinalizeKeyPair` | 26 (0x1a) | Exported Function | BCRYPT.BCryptFinalizeKeyPair | 0x0001d99e
`BCryptEnumContextFunctionProviders` | 20 (0x14) | Exported Function | BCRYPT.BCryptEnumContextFunctionProviders | 0x0001d85b
`BCryptFinishHash` | 27 (0x1b) | Exported Function | BCRYPT.BCryptFinishHash | 0x0001d9cc
`BCryptGenerateKeyPair` | 30 (0x1e) | Exported Function | BCRYPT.BCryptGenerateKeyPair | 0x0001da4a
`BCryptGenerateSymmetricKey` | 31 (0x1f) | Exported Function | BCRYPT.BCryptGenerateSymmetricKey | 0x0001da82
`BCryptGenRandom` | 29 (0x1d) | Exported Function | BCRYPT.BCryptGenRandom | 0x0001da1d
`BCryptGetFipsAlgorithmMode` | 32 (0x20) | Exported Function | BCRYPT.BCryptGetFipsAlgorithmMode | 0x0001dabf
`BCryptGetProperty` | 33 (0x21) | Exported Function | BCRYPT.BCryptGetProperty | 0x0001daf3
`BCryptHash` | 34 (0x22) | Exported Function | BCRYPT.BCryptHash | 0x0001db17
`BCryptFreeBuffer` | 28 (0x1c) | Exported Function | BCRYPT.BCryptFreeBuffer | 0x0001d9f5
`BCryptEnumAlgorithms` | 19 (0x13) | Exported Function | BCRYPT.BCryptEnumAlgorithms | 0x0001d81c
`BCryptEncrypt` | 18 (0x12) | Exported Function | BCRYPT.BCryptEncrypt | 0x0001d7f2
`BCryptDuplicateKey` | 17 (0x11) | Exported Function | BCRYPT.BCryptDuplicateKey | 0x0001d7ca
`BCryptAddContextFunctionProvider` | 2 (0x2) | Exported Function | BCRYPT.BCryptAddContextFunctionProvider | 0x0001d4ef
`BCryptCloseAlgorithmProvider` | 3 (0x3) | Exported Function | BCRYPT.BCryptCloseAlgorithmProvider | 0x0001d534
`BCryptConfigureContext` | 4 (0x4) | Exported Function | BCRYPT.BCryptConfigureContext | 0x0001d56f
`BCryptConfigureContextFunction` | 5 (0x5) | Exported Function | BCRYPT.BCryptConfigureContextFunction | 0x0001d5ac
`BCryptCreateContext` | 6 (0x6) | Exported Function | BCRYPT.BCryptCreateContext | 0x0001d5e6
`BCryptCreateHash` | 7 (0x7) | Exported Function | BCRYPT.BCryptCreateHash | 0x0001d612
`BCryptDecrypt` | 8 (0x8) | Exported Function | BCRYPT.BCryptDecrypt | 0x0001d638
`BCryptDeleteContext` | 9 (0x9) | Exported Function | BCRYPT.BCryptDeleteContext | 0x0001d661
`BCryptDeriveKey` | 10 (0xa) | Exported Function | BCRYPT.BCryptDeriveKey | 0x0001d68c
`BCryptDeriveKeyCapi` | 11 (0xb) | Exported Function | BCRYPT.BCryptDeriveKeyCapi | 0x0001d6b7
`BCryptDeriveKeyPBKDF2` | 12 (0xc) | Exported Function | BCRYPT.BCryptDeriveKeyPBKDF2 | 0x0001d6e8
`BCryptDestroyHash` | 13 (0xd) | Exported Function | BCRYPT.BCryptDestroyHash | 0x0001d717
`BCryptDestroyKey` | 14 (0xe) | Exported Function | BCRYPT.BCryptDestroyKey | 0x0001d741
`BCryptDestroySecret` | 15 (0xf) | Exported Function | BCRYPT.BCryptDestroySecret | 0x0001d76d
`BCryptDuplicateHash` | 16 (0x10) | Exported Function | BCRYPT.BCryptDuplicateHash | 0x0001d79c
`BCryptHashData` | 35 (0x23) | Exported Function | BCRYPT.BCryptHashData | 0x0001db38
`BCryptImportKey` | 36 (0x24) | Exported Function | BCRYPT.BCryptImportKey | 0x0001db5e
`BCryptImportKeyPair` | 37 (0x25) | Exported Function | BCRYPT.BCryptImportKeyPair | 0x0001db89
`BCryptKeyDerivation` | 38 (0x26) | Exported Function | BCRYPT.BCryptKeyDerivation | 0x0001dbb8
`GetKeyStorageInterface` | 58 (0x3a) | Exported Function | 0x000000018000df30 | 0x0000df30
`GetSChannelInterface` | 59 (0x3b) | Exported Function | 0x000000018000df30 | 0x0000df30
`NCryptCloseKeyProtector` | 60 (0x3c) | Exported Function | 0x00000001800106e0 | 0x000106e0
`NCryptCloseProtectionDescriptor` | 61 (0x3d) | Exported Function | 0x0000000180012660 | 0x00012660
`NCryptCreateClaim` | 62 (0x3e) | Exported Function | 0x000000018000e170 | 0x0000e170
`NCryptCreatePersistedKey` | 63 (0x3f) | Exported Function | 0x00000001800036a0 | 0x000036a0
`NCryptCreateProtectionDescriptor` | 64 (0x40) | Exported Function | 0x00000001800126f0 | 0x000126f0
`NCryptDecrypt` | 65 (0x41) | Exported Function | 0x000000018000e360 | 0x0000e360
`NCryptDeleteKey` | 66 (0x42) | Exported Function | 0x0000000180005a10 | 0x00005a10
`NCryptDeriveKey` | 67 (0x43) | Exported Function | 0x0000000180002040 | 0x00002040
`NCryptDuplicateKeyProtectorHandle` | 68 (0x44) | Exported Function | 0x00000001800107f0 | 0x000107f0
`NCryptEncrypt` | 69 (0x45) | Exported Function | 0x0000000180004660 | 0x00004660
`NCryptEnumAlgorithms` | 70 (0x46) | Exported Function | 0x000000018000e520 | 0x0000e520
`NCryptEnumKeys` | 71 (0x47) | Exported Function | 0x0000000180004cf0 | 0x00004cf0
`NCryptEnumStorageProviders` | 72 (0x48) | Exported Function | 0x000000018000e720 | 0x0000e720
`GetIsolationServerInterface` | 57 (0x39) | Exported Function | 0x000000018000df30 | 0x0000df30
`NCryptFinalizeKey` | 74 (0x4a) | Exported Function | 0x0000000180003800 | 0x00003800
`BCryptVerifySignature` | 56 (0x38) | Exported Function | BCRYPT.BCryptVerifySignature | 0x0001e02a
`BCryptUnregisterConfigChangeNotify` | 54 (0x36) | Exported Function | BCRYPT.BCryptUnregisterConfigChangeNotify | 0x0001dfb1
`BCryptOpenAlgorithmProvider` | 39 (0x27) | Exported Function | BCRYPT.BCryptOpenAlgorithmProvider | 0x0001dbef
`BCryptQueryContextConfiguration` | 40 (0x28) | Exported Function | BCRYPT.BCryptQueryContextConfiguration | 0x0001dc32
`BCryptQueryContextFunctionConfiguration` | 41 (0x29) | Exported Function | BCRYPT.BCryptQueryContextFunctionConfiguration | 0x0001dc81
`BCryptQueryContextFunctionProperty` | 42 (0x2a) | Exported Function | BCRYPT.BCryptQueryContextFunctionProperty | 0x0001dcd3
`BCryptQueryProviderRegistration` | 43 (0x2b) | Exported Function | BCRYPT.BCryptQueryProviderRegistration | 0x0001dd1d
`BCryptRegisterConfigChangeNotify` | 44 (0x2c) | Exported Function | BCRYPT.BCryptRegisterConfigChangeNotify | 0x0001dd65
`BCryptRegisterProvider` | 45 (0x2d) | Exported Function | BCRYPT.BCryptRegisterProvider | 0x0001dda4
`BCryptRemoveContextFunction` | 46 (0x2e) | Exported Function | BCRYPT.BCryptRemoveContextFunction | 0x0001ddde
`BCryptRemoveContextFunctionProvider` | 47 (0x2f) | Exported Function | BCRYPT.BCryptRemoveContextFunctionProvider | 0x0001de25
`BCryptResolveProviders` | 48 (0x30) | Exported Function | BCRYPT.BCryptResolveProviders | 0x0001de67
`BCryptSecretAgreement` | 49 (0x31) | Exported Function | BCRYPT.BCryptSecretAgreement | 0x0001de9b
`BCryptSetAuditingInterface` | 50 (0x32) | Exported Function | BCRYPT.BCryptSetAuditingInterface | 0x0001ded3
`BCryptSetContextFunctionProperty` | 51 (0x33) | Exported Function | BCRYPT.BCryptSetContextFunctionProperty | 0x0001df16
`BCryptSetProperty` | 52 (0x34) | Exported Function | BCRYPT.BCryptSetProperty | 0x0001df50
`BCryptSignHash` | 53 (0x35) | Exported Function | BCRYPT.BCryptSignHash | 0x0001df78
`BCryptUnregisterProvider` | 55 (0x37) | Exported Function | BCRYPT.BCryptUnregisterProvider | 0x0001dff4
`SslVerifySignature` | 149 (0x95) | Exported Function | 0x000000018000d7a0 | 0x0000d7a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ncrypt.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e860477b315b6965eb008e4548160e589723d5ab26ce3f33d80c3715b4e555be/detection/


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


