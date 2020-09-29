---
title: secur32.dll | Security Support Provider Interface
excerpt: What is secur32.dll?
---

# secur32.dll 

* File Path: `C:\Windows\system32\secur32.dll`
* Description: Security Support Provider Interface

## Hashes

Type | Hash
-- | --
MD5 | `9F8334746D4E526E8CD540826CFF5EDB`
SHA1 | `B79E8581A4D7F96A38AC933D3AA90750DF1107DF`
SHA256 | `3C8CD20CE224FE9D033090D6C5C7AACBF6F03D0815632B849E7F310EE3CB1DC6`
SHA384 | `C08CC63028916308F42EB178AF0536A15C73F327B79E5EADE4090054B07C79FEED6B58464AF381D9BA66AB1EAA6F9257`
SHA512 | `72BB72E3236DA58DDF94EA140914F0EEC54ED076E07E2593CAD40FCC8FE6BDB5629987ACAC6EC44717FB60AB9C4CC5B8D79CB757CCF79BC5B5B0809B4258EEDA`
SSDEEP | `768:UwkaSXK7HsV7uTeW5pddqP4o5jr/1kOzS:1Sa7H67uN5HdqP4oB/1kn`
IMP | `F90C2A389F295606533D615109FB248B`
PESHA1 | `81C734ED7978417F73B858D29A1DF3FEC82E4D68`
PE256 | `3A0B1CEE16766187223E91310F75E80054309D75B4B326594A982C2B68B4B7C3`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 4 (0x4) | Exported Function | SSPICLI.AcceptSecurityContext | 0x000051a5
`SeciFreeCallContext` | 73 (0x49) | Exported Function | SSPICLI.SeciFreeCallContext | 0x00005fff
`SeciAllocateAndSetIPAddress` | 72 (0x48) | Exported Function | SSPICLI.SeciAllocateAndSetIPAddress | 0x00005fc7
`SeciAllocateAndSetCallFlags` | 71 (0x47) | Exported Function | SSPICLI.SeciAllocateAndSetCallFlags | 0x00005f87
`SealMessage` | 70 (0x46) | Exported Function | SSPICLI.SealMessage | 0x00005f57
`SaslSetContextOption` | 69 (0x45) | Exported Function | SSPICLI.SaslSetContextOption | 0x00005f2e
`SaslInitializeSecurityContextW` | 68 (0x44) | Exported Function | SSPICLI.SaslInitializeSecurityContextW | 0x00005ef2
`SaslInitializeSecurityContextA` | 67 (0x43) | Exported Function | SSPICLI.SaslInitializeSecurityContextA | 0x00005eac
`SaslIdentifyPackageW` | 66 (0x42) | Exported Function | SSPICLI.SaslIdentifyPackageW | 0x00005e70
`SaslIdentifyPackageA` | 65 (0x41) | Exported Function | SSPICLI.SaslIdentifyPackageA | 0x00005e3e
`SaslGetProfilePackageW` | 64 (0x40) | Exported Function | SSPICLI.SaslGetProfilePackageW | 0x00005e0a
`SaslGetProfilePackageA` | 63 (0x3f) | Exported Function | SSPICLI.SaslGetProfilePackageA | 0x00005dd4
`SaslGetContextOption` | 62 (0x3e) | Exported Function | SSPICLI.SaslGetContextOption | 0x00005da0
`SaslEnumerateProfilesW` | 61 (0x3d) | Exported Function | SSPICLI.SaslEnumerateProfilesW | 0x00005d6c
`SaslEnumerateProfilesA` | 60 (0x3c) | Exported Function | SSPICLI.SaslEnumerateProfilesA | 0x00005d36
`SaslAcceptSecurityContext` | 59 (0x3b) | Exported Function | SSPICLI.SaslAcceptSecurityContext | 0x00005cfd
`RevertSecurityContext` | 58 (0x3a) | Exported Function | SSPICLI.RevertSecurityContext | 0x00005cc5
`QuerySecurityPackageInfoW` | 57 (0x39) | Exported Function | SSPICLI.QuerySecurityPackageInfoW | 0x00005c8d
`QuerySecurityPackageInfoA` | 56 (0x38) | Exported Function | SSPICLI.QuerySecurityPackageInfoA | 0x00005c51
`QuerySecurityContextToken` | 55 (0x37) | Exported Function | SSPICLI.QuerySecurityContextToken | 0x00005c15
`QueryCredentialsAttributesW` | 54 (0x36) | Exported Function | SSPICLI.QueryCredentialsAttributesW | 0x00005bd7
`QueryCredentialsAttributesA` | 53 (0x35) | Exported Function | SSPICLI.QueryCredentialsAttributesA | 0x00005b97
`SecpFreeMemory` | 74 (0x4a) | Exported Function | 0x0000000180001f80 | 0x00001f80
`SecpTranslateName` | 75 (0x4b) | Exported Function | 0x0000000180001850 | 0x00001850
`SecpTranslateNameEx` | 76 (0x4c) | Exported Function | 0x0000000180001040 | 0x00001040
`SetContextAttributesA` | 77 (0x4d) | Exported Function | SSPICLI.SetContextAttributesA | 0x00006066
`TranslateNameW` | 99 (0x63) | Exported Function | 0x0000000180003ac0 | 0x00003ac0
`TranslateNameA` | 98 (0x62) | Exported Function | 0x00000001800038f0 | 0x000038f0
`SspiZeroAuthIdentity` | 97 (0x61) | Exported Function | SSPICLI.SspiZeroAuthIdentity | 0x000064c7
`SspiValidateAuthIdentity` | 96 (0x60) | Exported Function | SSPICLI.SspiValidateAuthIdentity | 0x00006491
`SspiUnmarshalAuthIdentity` | 95 (0x5f) | Exported Function | SSPICLI.SspiUnmarshalAuthIdentity | 0x00006456
`SspiPrepareForCredWrite` | 94 (0x5e) | Exported Function | SSPICLI.SspiPrepareForCredWrite | 0x0000641c
`SspiPrepareForCredRead` | 93 (0x5d) | Exported Function | SSPICLI.SspiPrepareForCredRead | 0x000063e5
`SspiMarshalAuthIdentity` | 92 (0x5c) | Exported Function | SSPICLI.SspiMarshalAuthIdentity | 0x000063ae
`SspiLocalFree` | 91 (0x5b) | Exported Function | SSPICLI.SspiLocalFree | 0x00006380
`SspiIsAuthIdentityEncrypted` | 90 (0x5a) | Exported Function | SSPICLI.SspiIsAuthIdentityEncrypted | 0x0000634e
`QueryContextAttributesW` | 52 (0x34) | Exported Function | SSPICLI.QueryContextAttributesW | 0x00005b5b
`SspiGetTargetHostName` | 89 (0x59) | Exported Function | SSPICLI.SspiGetTargetHostName | 0x00006314
`SspiExcludePackage` | 87 (0x57) | Exported Function | SSPICLI.SspiExcludePackage | 0x000062b1
`SspiEncryptAuthIdentity` | 86 (0x56) | Exported Function | SSPICLI.SspiEncryptAuthIdentity | 0x0000627e
`SspiEncodeStringsAsAuthIdentity` | 85 (0x55) | Exported Function | SSPICLI.SspiEncodeStringsAsAuthIdentity | 0x0000623e
`SspiEncodeAuthIdentityAsStrings` | 84 (0x54) | Exported Function | SSPICLI.SspiEncodeAuthIdentityAsStrings | 0x000061f6
`SspiDecryptAuthIdentity` | 83 (0x53) | Exported Function | SSPICLI.SspiDecryptAuthIdentity | 0x000061b6
`SspiCopyAuthIdentity` | 82 (0x52) | Exported Function | SSPICLI.SspiCopyAuthIdentity | 0x00006181
`SspiCompareAuthIdentities` | 81 (0x51) | Exported Function | SSPICLI.SspiCompareAuthIdentities | 0x0000614a
`SetCredentialsAttributesW` | 80 (0x50) | Exported Function | SSPICLI.SetCredentialsAttributesW | 0x0000610e
`SetCredentialsAttributesA` | 79 (0x4f) | Exported Function | SSPICLI.SetCredentialsAttributesA | 0x000060d2
`SetContextAttributesW` | 78 (0x4e) | Exported Function | SSPICLI.SetContextAttributesW | 0x0000609a
`SspiFreeAuthIdentity` | 88 (0x58) | Exported Function | SSPICLI.SspiFreeAuthIdentity | 0x000062e1
`UnsealMessage` | 100 (0x64) | Exported Function | SSPICLI.UnsealMessage | 0x00006510
`QueryContextAttributesA` | 51 (0x33) | Exported Function | SSPICLI.QueryContextAttributesA | 0x00005b23
`MakeSignature` | 50 (0x32) | Exported Function | SSPICLI.MakeSignature | 0x00005af5
`EnumerateSecurityPackagesW` | 23 (0x17) | Exported Function | SSPICLI.EnumerateSecurityPackagesW | 0x00005560
`EnumerateSecurityPackagesA` | 22 (0x16) | Exported Function | SSPICLI.EnumerateSecurityPackagesA | 0x00005522
`EncryptMessage` | 21 (0x15) | Exported Function | SSPICLI.EncryptMessage | 0x000054f0
`DeleteSecurityPackageW` | 20 (0x14) | Exported Function | SSPICLI.DeleteSecurityPackageW | 0x000054c2
`DeleteSecurityPackageA` | 19 (0x13) | Exported Function | SSPICLI.DeleteSecurityPackageA | 0x0000548c
`DeleteSecurityContext` | 18 (0x12) | Exported Function | SSPICLI.DeleteSecurityContext | 0x00005457
`DecryptMessage` | 17 (0x11) | Exported Function | SSPICLI.DecryptMessage | 0x0000542a
`CredUnmarshalTargetInfo` | 16 (0x10) | Exported Function | SSPICLI.CredUnmarshalTargetInfo | 0x000053fb
`CredMarshalTargetInfo` | 15 (0xf) | Exported Function | SSPICLI.CredMarshalTargetInfo | 0x000053c5
`CompleteAuthToken` | 14 (0xe) | Exported Function | SSPICLI.CompleteAuthToken | 0x00005395
`CollectLsaPerformanceData` | 2 (0x2) | Exported Function | 0x00000001800030a0 | 0x000030a0
`CloseLsaPerformanceData` | 1 (0x1) | Exported Function | 0x0000000180003030 | 0x00003030
`ChangeAccountPasswordW` | 13 (0xd) | Exported Function | SSPICLI.ChangeAccountPasswordW | 0x00005364
`ChangeAccountPasswordA` | 12 (0xc) | Exported Function | SSPICLI.ChangeAccountPasswordA | 0x0000532e
`ApplyControlToken` | 11 (0xb) | Exported Function | SSPICLI.ApplyControlToken | 0x000052fd
`AddSecurityPackageW` | 10 (0xa) | Exported Function | SSPICLI.AddSecurityPackageW | 0x000052cf
`AddSecurityPackageA` | 9 (0x9) | Exported Function | SSPICLI.AddSecurityPackageA | 0x0000529f
`AddCredentialsW` | 8 (0x8) | Exported Function | SSPICLI.AddCredentialsW | 0x00005273
`AddCredentialsA` | 7 (0x7) | Exported Function | SSPICLI.AddCredentialsA | 0x0000524b
`AcquireCredentialsHandleW` | 6 (0x6) | Exported Function | SSPICLI.AcquireCredentialsHandleW | 0x00005219
`AcquireCredentialsHandleA` | 5 (0x5) | Exported Function | SSPICLI.AcquireCredentialsHandleA | 0x000051dd
`ExportSecurityContext` | 24 (0x18) | Exported Function | SSPICLI.ExportSecurityContext | 0x00005599
`FreeContextBuffer` | 25 (0x19) | Exported Function | SSPICLI.FreeContextBuffer | 0x000055c9
`FreeCredentialsHandle` | 26 (0x1a) | Exported Function | SSPICLI.FreeCredentialsHandle | 0x000055f9
`GetComputerObjectNameA` | 27 (0x1b) | Exported Function | 0x0000000180003790 | 0x00003790
`LsaUnregisterPolicyChangeNotification` | 49 (0x31) | Exported Function | SSPICLI.LsaUnregisterPolicyChangeNotification | 0x00005ab9
`LsaRegisterPolicyChangeNotification` | 48 (0x30) | Exported Function | SSPICLI.LsaRegisterPolicyChangeNotification | 0x00005a67
`LsaRegisterLogonProcess` | 47 (0x2f) | Exported Function | SSPICLI.LsaRegisterLogonProcess | 0x00005a23
`LsaLookupAuthenticationPackage` | 46 (0x2e) | Exported Function | SSPICLI.LsaLookupAuthenticationPackage | 0x000059e4
`LsaLogonUser` | 45 (0x2d) | Exported Function | SSPICLI.LsaLogonUser | 0x000059b0
`LsaGetLogonSessionData` | 44 (0x2c) | Exported Function | SSPICLI.LsaGetLogonSessionData | 0x00005984
`LsaFreeReturnBuffer` | 43 (0x2b) | Exported Function | SSPICLI.LsaFreeReturnBuffer | 0x00005951
`LsaEnumerateLogonSessions` | 42 (0x2a) | Exported Function | SSPICLI.LsaEnumerateLogonSessions | 0x0000591b
`LsaDeregisterLogonProcess` | 41 (0x29) | Exported Function | SSPICLI.LsaDeregisterLogonProcess | 0x000058df
`LsaConnectUntrusted` | 40 (0x28) | Exported Function | SSPICLI.LsaConnectUntrusted | 0x000058a9
`OpenLsaPerformanceData` | 3 (0x3) | Exported Function | 0x0000000180003620 | 0x00003620
`LsaCallAuthenticationPackage` | 39 (0x27) | Exported Function | SSPICLI.LsaCallAuthenticationPackage | 0x00005870
`InitSecurityInterfaceA` | 35 (0x23) | Exported Function | SSPICLI.InitSecurityInterfaceA | 0x00005782
`InitializeSecurityContextW` | 38 (0x26) | Exported Function | SSPICLI.InitializeSecurityContextW | 0x00005830
`InitializeSecurityContextA` | 37 (0x25) | Exported Function | SSPICLI.InitializeSecurityContextA | 0x000057f2
`ImportSecurityContextW` | 34 (0x22) | Exported Function | SSPICLI.ImportSecurityContextW | 0x0000574c
`ImportSecurityContextA` | 33 (0x21) | Exported Function | SSPICLI.ImportSecurityContextA | 0x00005716
`ImpersonateSecurityContext` | 32 (0x20) | Exported Function | SSPICLI.ImpersonateSecurityContext | 0x000056dc
`GetUserNameExW` | 31 (0x1f) | Exported Function | SSPICLI.GetUserNameExW | 0x000056aa
`GetUserNameExA` | 30 (0x1e) | Exported Function | SSPICLI.GetUserNameExA | 0x00005684
`GetSecurityUserInfo` | 29 (0x1d) | Exported Function | SSPICLI.GetSecurityUserInfo | 0x00005659
`GetComputerObjectNameW` | 28 (0x1c) | Exported Function | 0x00000001800014d0 | 0x000014d0
`InitSecurityInterfaceW` | 36 (0x24) | Exported Function | SSPICLI.InitSecurityInterfaceW | 0x000057b8
`VerifySignature` | 101 (0x65) | Exported Function | SSPICLI.VerifySignature | 0x00006536


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: secur32.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/3c8cd20ce224fe9d033090d6c5c7aacbf6f03d0815632b849e7f310ee3cb1dc6/detection/


## Possible Misuse

*The following table contains possible examples of `secur32.dll` being misused. While `secur32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $g15 = "Secur32.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


