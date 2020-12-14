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

Function Name | Ordinal | Type
-- | -- | --
`SaslInitializeSecurityContextW` | 68 | Exported Function
`SaslSetContextOption` | 69 | Exported Function
`SealMessage` | 70 | Exported Function
`SaslIdentifyPackageA` | 65 | Exported Function
`SaslIdentifyPackageW` | 66 | Exported Function
`SaslInitializeSecurityContextA` | 67 | Exported Function
`SecpFreeMemory` | 74 | Exported Function
`SecpTranslateName` | 75 | Exported Function
`SecpTranslateNameEx` | 76 | Exported Function
`SeciAllocateAndSetCallFlags` | 71 | Exported Function
`SeciAllocateAndSetIPAddress` | 72 | Exported Function
`SeciFreeCallContext` | 73 | Exported Function
`SaslGetProfilePackageW` | 64 | Exported Function
`QuerySecurityContextToken` | 55 | Exported Function
`QuerySecurityPackageInfoA` | 56 | Exported Function
`QuerySecurityPackageInfoW` | 57 | Exported Function
`QueryContextAttributesW` | 52 | Exported Function
`QueryCredentialsAttributesA` | 53 | Exported Function
`QueryCredentialsAttributesW` | 54 | Exported Function
`SaslEnumerateProfilesW` | 61 | Exported Function
`SaslGetContextOption` | 62 | Exported Function
`SaslGetProfilePackageA` | 63 | Exported Function
`RevertSecurityContext` | 58 | Exported Function
`SaslAcceptSecurityContext` | 59 | Exported Function
`SaslEnumerateProfilesA` | 60 | Exported Function
`SspiPrepareForCredRead` | 93 | Exported Function
`SspiPrepareForCredWrite` | 94 | Exported Function
`SspiUnmarshalAuthIdentity` | 95 | Exported Function
`SspiIsAuthIdentityEncrypted` | 90 | Exported Function
`SspiLocalFree` | 91 | Exported Function
`SspiMarshalAuthIdentity` | 92 | Exported Function
`TranslateNameW` | 99 | Exported Function
`UnsealMessage` | 100 | Exported Function
`VerifySignature` | 101 | Exported Function
`SspiValidateAuthIdentity` | 96 | Exported Function
`SspiZeroAuthIdentity` | 97 | Exported Function
`TranslateNameA` | 98 | Exported Function
`SspiGetTargetHostName` | 89 | Exported Function
`SetCredentialsAttributesW` | 80 | Exported Function
`SspiCompareAuthIdentities` | 81 | Exported Function
`SspiCopyAuthIdentity` | 82 | Exported Function
`SetContextAttributesA` | 77 | Exported Function
`SetContextAttributesW` | 78 | Exported Function
`SetCredentialsAttributesA` | 79 | Exported Function
`SspiEncryptAuthIdentity` | 86 | Exported Function
`SspiExcludePackage` | 87 | Exported Function
`SspiFreeAuthIdentity` | 88 | Exported Function
`SspiDecryptAuthIdentity` | 83 | Exported Function
`SspiEncodeAuthIdentityAsStrings` | 84 | Exported Function
`SspiEncodeStringsAsAuthIdentity` | 85 | Exported Function
`QueryContextAttributesA` | 51 | Exported Function
`DeleteSecurityContext` | 18 | Exported Function
`DeleteSecurityPackageA` | 19 | Exported Function
`DeleteSecurityPackageW` | 20 | Exported Function
`CredMarshalTargetInfo` | 15 | Exported Function
`CredUnmarshalTargetInfo` | 16 | Exported Function
`DecryptMessage` | 17 | Exported Function
`ExportSecurityContext` | 24 | Exported Function
`FreeContextBuffer` | 25 | Exported Function
`FreeCredentialsHandle` | 26 | Exported Function
`EncryptMessage` | 21 | Exported Function
`EnumerateSecurityPackagesA` | 22 | Exported Function
`EnumerateSecurityPackagesW` | 23 | Exported Function
`CompleteAuthToken` | 14 | Exported Function
`AddCredentialsA` | 7 | Exported Function
`AddCredentialsW` | 8 | Exported Function
`AddSecurityPackageA` | 9 | Exported Function
`AcceptSecurityContext` | 4 | Exported Function
`AcquireCredentialsHandleA` | 5 | Exported Function
`AcquireCredentialsHandleW` | 6 | Exported Function
`ChangeAccountPasswordW` | 13 | Exported Function
`CloseLsaPerformanceData` | 1 | Exported Function
`CollectLsaPerformanceData` | 2 | Exported Function
`AddSecurityPackageW` | 10 | Exported Function
`ApplyControlToken` | 11 | Exported Function
`ChangeAccountPasswordA` | 12 | Exported Function
`LsaFreeReturnBuffer` | 43 | Exported Function
`LsaGetLogonSessionData` | 44 | Exported Function
`LsaLogonUser` | 45 | Exported Function
`LsaConnectUntrusted` | 40 | Exported Function
`LsaDeregisterLogonProcess` | 41 | Exported Function
`LsaEnumerateLogonSessions` | 42 | Exported Function
`LsaUnregisterPolicyChangeNotification` | 49 | Exported Function
`MakeSignature` | 50 | Exported Function
`OpenLsaPerformanceData` | 3 | Exported Function
`LsaLookupAuthenticationPackage` | 46 | Exported Function
`LsaRegisterLogonProcess` | 47 | Exported Function
`LsaRegisterPolicyChangeNotification` | 48 | Exported Function
`LsaCallAuthenticationPackage` | 39 | Exported Function
`GetUserNameExA` | 30 | Exported Function
`GetUserNameExW` | 31 | Exported Function
`ImpersonateSecurityContext` | 32 | Exported Function
`GetComputerObjectNameA` | 27 | Exported Function
`GetComputerObjectNameW` | 28 | Exported Function
`GetSecurityUserInfo` | 29 | Exported Function
`InitializeSecurityContextW` | 38 | Exported Function
`InitSecurityInterfaceA` | 35 | Exported Function
`InitSecurityInterfaceW` | 36 | Exported Function
`ImportSecurityContextA` | 33 | Exported Function
`ImportSecurityContextW` | 34 | Exported Function
`InitializeSecurityContextA` | 37 | Exported Function


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

*The following table contains possible examples of `secur32.dll` being misused. While `secur32.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $g15 = "Secur32.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


