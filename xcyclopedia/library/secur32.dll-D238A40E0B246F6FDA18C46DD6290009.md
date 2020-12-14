---
title: secur32.dll | Security Support Provider Interface
excerpt: What is secur32.dll?
---

# secur32.dll 

* File Path: `C:\Windows\SysWOW64\secur32.dll`
* Description: Security Support Provider Interface

## Hashes

Type | Hash
-- | --
MD5 | `D238A40E0B246F6FDA18C46DD6290009`
SHA1 | `EEDAB6074CD6DF0981B0C0B0619B9ACAE9C28172`
SHA256 | `BEF1669B4E21AE1AD463065294164B3E1793A6A123DEB4DB5043033362BEE9D1`
SHA384 | `A97A31667322AF384E50E9D2FF83B88F7CA61E82E55D15FA08C0C125DAFC9256F5A5FF99A79288EAA488B64184A6CA1F`
SHA512 | `99020D3DE3C156C3B08ED1F2447858CE536335E41EA4630E7464036F2A748B8127D6F631E14B3279509854EDE85F17C91CFA4D3A4732CD5DAB2CD9DBF12C7B6A`
SSDEEP | `384:D5uL7jiVVvNORNHzxdXaP4osxlUo8YuC/EHqWiOCW:Ezc2RDdqP4oLoL/EHR`
IMP | `1365C05DD369ADB729410FD6427AD34D`
PESHA1 | `924DBEBBEA2B037EE2ACBE0A6AE90E77709097CF`
PE256 | `BA0E409679AA832569B418AC053CA52654299F6B31D046A6D2EC30B3285969B3`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/bef1669b4e21ae1ad463065294164b3e1793a6a123deb4db5043033362bee9d1/detection/


## Possible Misuse

*The following table contains possible examples of `secur32.dll` being misused. While `secur32.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $g15 = "Secur32.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


