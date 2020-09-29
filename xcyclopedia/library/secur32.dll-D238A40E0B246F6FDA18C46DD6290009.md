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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 4 (0x4) | Exported Function | SSPICLI.AcceptSecurityContext | 0x000037d5
`SeciFreeCallContext` | 73 (0x49) | Exported Function | SSPICLI.SeciFreeCallContext | 0x0000462f
`SeciAllocateAndSetIPAddress` | 72 (0x48) | Exported Function | SSPICLI.SeciAllocateAndSetIPAddress | 0x000045f7
`SeciAllocateAndSetCallFlags` | 71 (0x47) | Exported Function | SSPICLI.SeciAllocateAndSetCallFlags | 0x000045b7
`SealMessage` | 70 (0x46) | Exported Function | SSPICLI.SealMessage | 0x00004587
`SaslSetContextOption` | 69 (0x45) | Exported Function | SSPICLI.SaslSetContextOption | 0x0000455e
`SaslInitializeSecurityContextW` | 68 (0x44) | Exported Function | SSPICLI.SaslInitializeSecurityContextW | 0x00004522
`SaslInitializeSecurityContextA` | 67 (0x43) | Exported Function | SSPICLI.SaslInitializeSecurityContextA | 0x000044dc
`SaslIdentifyPackageW` | 66 (0x42) | Exported Function | SSPICLI.SaslIdentifyPackageW | 0x000044a0
`SaslIdentifyPackageA` | 65 (0x41) | Exported Function | SSPICLI.SaslIdentifyPackageA | 0x0000446e
`SaslGetProfilePackageW` | 64 (0x40) | Exported Function | SSPICLI.SaslGetProfilePackageW | 0x0000443a
`SaslGetProfilePackageA` | 63 (0x3f) | Exported Function | SSPICLI.SaslGetProfilePackageA | 0x00004404
`SaslGetContextOption` | 62 (0x3e) | Exported Function | SSPICLI.SaslGetContextOption | 0x000043d0
`SaslEnumerateProfilesW` | 61 (0x3d) | Exported Function | SSPICLI.SaslEnumerateProfilesW | 0x0000439c
`SaslEnumerateProfilesA` | 60 (0x3c) | Exported Function | SSPICLI.SaslEnumerateProfilesA | 0x00004366
`SaslAcceptSecurityContext` | 59 (0x3b) | Exported Function | SSPICLI.SaslAcceptSecurityContext | 0x0000432d
`RevertSecurityContext` | 58 (0x3a) | Exported Function | SSPICLI.RevertSecurityContext | 0x000042f5
`QuerySecurityPackageInfoW` | 57 (0x39) | Exported Function | SSPICLI.QuerySecurityPackageInfoW | 0x000042bd
`QuerySecurityPackageInfoA` | 56 (0x38) | Exported Function | SSPICLI.QuerySecurityPackageInfoA | 0x00004281
`QuerySecurityContextToken` | 55 (0x37) | Exported Function | SSPICLI.QuerySecurityContextToken | 0x00004245
`QueryCredentialsAttributesW` | 54 (0x36) | Exported Function | SSPICLI.QueryCredentialsAttributesW | 0x00004207
`QueryCredentialsAttributesA` | 53 (0x35) | Exported Function | SSPICLI.QueryCredentialsAttributesA | 0x000041c7
`SecpFreeMemory` | 74 (0x4a) | Exported Function | 0x51b82930 | 0x00002930
`SecpTranslateName` | 75 (0x4b) | Exported Function | 0x51b82940 | 0x00002940
`SecpTranslateNameEx` | 76 (0x4c) | Exported Function | 0x51b82ec0 | 0x00002ec0
`SetContextAttributesA` | 77 (0x4d) | Exported Function | SSPICLI.SetContextAttributesA | 0x00004696
`TranslateNameW` | 99 (0x63) | Exported Function | 0x51b83150 | 0x00003150
`TranslateNameA` | 98 (0x62) | Exported Function | 0x51b83020 | 0x00003020
`SspiZeroAuthIdentity` | 97 (0x61) | Exported Function | SSPICLI.SspiZeroAuthIdentity | 0x00004af7
`SspiValidateAuthIdentity` | 96 (0x60) | Exported Function | SSPICLI.SspiValidateAuthIdentity | 0x00004ac1
`SspiUnmarshalAuthIdentity` | 95 (0x5f) | Exported Function | SSPICLI.SspiUnmarshalAuthIdentity | 0x00004a86
`SspiPrepareForCredWrite` | 94 (0x5e) | Exported Function | SSPICLI.SspiPrepareForCredWrite | 0x00004a4c
`SspiPrepareForCredRead` | 93 (0x5d) | Exported Function | SSPICLI.SspiPrepareForCredRead | 0x00004a15
`SspiMarshalAuthIdentity` | 92 (0x5c) | Exported Function | SSPICLI.SspiMarshalAuthIdentity | 0x000049de
`SspiLocalFree` | 91 (0x5b) | Exported Function | SSPICLI.SspiLocalFree | 0x000049b0
`SspiIsAuthIdentityEncrypted` | 90 (0x5a) | Exported Function | SSPICLI.SspiIsAuthIdentityEncrypted | 0x0000497e
`QueryContextAttributesW` | 52 (0x34) | Exported Function | SSPICLI.QueryContextAttributesW | 0x0000418b
`SspiGetTargetHostName` | 89 (0x59) | Exported Function | SSPICLI.SspiGetTargetHostName | 0x00004944
`SspiExcludePackage` | 87 (0x57) | Exported Function | SSPICLI.SspiExcludePackage | 0x000048e1
`SspiEncryptAuthIdentity` | 86 (0x56) | Exported Function | SSPICLI.SspiEncryptAuthIdentity | 0x000048ae
`SspiEncodeStringsAsAuthIdentity` | 85 (0x55) | Exported Function | SSPICLI.SspiEncodeStringsAsAuthIdentity | 0x0000486e
`SspiEncodeAuthIdentityAsStrings` | 84 (0x54) | Exported Function | SSPICLI.SspiEncodeAuthIdentityAsStrings | 0x00004826
`SspiDecryptAuthIdentity` | 83 (0x53) | Exported Function | SSPICLI.SspiDecryptAuthIdentity | 0x000047e6
`SspiCopyAuthIdentity` | 82 (0x52) | Exported Function | SSPICLI.SspiCopyAuthIdentity | 0x000047b1
`SspiCompareAuthIdentities` | 81 (0x51) | Exported Function | SSPICLI.SspiCompareAuthIdentities | 0x0000477a
`SetCredentialsAttributesW` | 80 (0x50) | Exported Function | SSPICLI.SetCredentialsAttributesW | 0x0000473e
`SetCredentialsAttributesA` | 79 (0x4f) | Exported Function | SSPICLI.SetCredentialsAttributesA | 0x00004702
`SetContextAttributesW` | 78 (0x4e) | Exported Function | SSPICLI.SetContextAttributesW | 0x000046ca
`SspiFreeAuthIdentity` | 88 (0x58) | Exported Function | SSPICLI.SspiFreeAuthIdentity | 0x00004911
`UnsealMessage` | 100 (0x64) | Exported Function | SSPICLI.UnsealMessage | 0x00004b40
`QueryContextAttributesA` | 51 (0x33) | Exported Function | SSPICLI.QueryContextAttributesA | 0x00004153
`MakeSignature` | 50 (0x32) | Exported Function | SSPICLI.MakeSignature | 0x00004125
`EnumerateSecurityPackagesW` | 23 (0x17) | Exported Function | SSPICLI.EnumerateSecurityPackagesW | 0x00003b90
`EnumerateSecurityPackagesA` | 22 (0x16) | Exported Function | SSPICLI.EnumerateSecurityPackagesA | 0x00003b52
`EncryptMessage` | 21 (0x15) | Exported Function | SSPICLI.EncryptMessage | 0x00003b20
`DeleteSecurityPackageW` | 20 (0x14) | Exported Function | SSPICLI.DeleteSecurityPackageW | 0x00003af2
`DeleteSecurityPackageA` | 19 (0x13) | Exported Function | SSPICLI.DeleteSecurityPackageA | 0x00003abc
`DeleteSecurityContext` | 18 (0x12) | Exported Function | SSPICLI.DeleteSecurityContext | 0x00003a87
`DecryptMessage` | 17 (0x11) | Exported Function | SSPICLI.DecryptMessage | 0x00003a5a
`CredUnmarshalTargetInfo` | 16 (0x10) | Exported Function | SSPICLI.CredUnmarshalTargetInfo | 0x00003a2b
`CredMarshalTargetInfo` | 15 (0xf) | Exported Function | SSPICLI.CredMarshalTargetInfo | 0x000039f5
`CompleteAuthToken` | 14 (0xe) | Exported Function | SSPICLI.CompleteAuthToken | 0x000039c5
`CollectLsaPerformanceData` | 2 (0x2) | Exported Function | 0x51b818c0 | 0x000018c0
`CloseLsaPerformanceData` | 1 (0x1) | Exported Function | 0x51b81870 | 0x00001870
`ChangeAccountPasswordW` | 13 (0xd) | Exported Function | SSPICLI.ChangeAccountPasswordW | 0x00003994
`ChangeAccountPasswordA` | 12 (0xc) | Exported Function | SSPICLI.ChangeAccountPasswordA | 0x0000395e
`ApplyControlToken` | 11 (0xb) | Exported Function | SSPICLI.ApplyControlToken | 0x0000392d
`AddSecurityPackageW` | 10 (0xa) | Exported Function | SSPICLI.AddSecurityPackageW | 0x000038ff
`AddSecurityPackageA` | 9 (0x9) | Exported Function | SSPICLI.AddSecurityPackageA | 0x000038cf
`AddCredentialsW` | 8 (0x8) | Exported Function | SSPICLI.AddCredentialsW | 0x000038a3
`AddCredentialsA` | 7 (0x7) | Exported Function | SSPICLI.AddCredentialsA | 0x0000387b
`AcquireCredentialsHandleW` | 6 (0x6) | Exported Function | SSPICLI.AcquireCredentialsHandleW | 0x00003849
`AcquireCredentialsHandleA` | 5 (0x5) | Exported Function | SSPICLI.AcquireCredentialsHandleA | 0x0000380d
`ExportSecurityContext` | 24 (0x18) | Exported Function | SSPICLI.ExportSecurityContext | 0x00003bc9
`FreeContextBuffer` | 25 (0x19) | Exported Function | SSPICLI.FreeContextBuffer | 0x00003bf9
`FreeCredentialsHandle` | 26 (0x1a) | Exported Function | SSPICLI.FreeCredentialsHandle | 0x00003c29
`GetComputerObjectNameA` | 27 (0x1b) | Exported Function | 0x51b82690 | 0x00002690
`LsaUnregisterPolicyChangeNotification` | 49 (0x31) | Exported Function | SSPICLI.LsaUnregisterPolicyChangeNotification | 0x000040e9
`LsaRegisterPolicyChangeNotification` | 48 (0x30) | Exported Function | SSPICLI.LsaRegisterPolicyChangeNotification | 0x00004097
`LsaRegisterLogonProcess` | 47 (0x2f) | Exported Function | SSPICLI.LsaRegisterLogonProcess | 0x00004053
`LsaLookupAuthenticationPackage` | 46 (0x2e) | Exported Function | SSPICLI.LsaLookupAuthenticationPackage | 0x00004014
`LsaLogonUser` | 45 (0x2d) | Exported Function | SSPICLI.LsaLogonUser | 0x00003fe0
`LsaGetLogonSessionData` | 44 (0x2c) | Exported Function | SSPICLI.LsaGetLogonSessionData | 0x00003fb4
`LsaFreeReturnBuffer` | 43 (0x2b) | Exported Function | SSPICLI.LsaFreeReturnBuffer | 0x00003f81
`LsaEnumerateLogonSessions` | 42 (0x2a) | Exported Function | SSPICLI.LsaEnumerateLogonSessions | 0x00003f4b
`LsaDeregisterLogonProcess` | 41 (0x29) | Exported Function | SSPICLI.LsaDeregisterLogonProcess | 0x00003f0f
`LsaConnectUntrusted` | 40 (0x28) | Exported Function | SSPICLI.LsaConnectUntrusted | 0x00003ed9
`OpenLsaPerformanceData` | 3 (0x3) | Exported Function | 0x51b81c90 | 0x00001c90
`LsaCallAuthenticationPackage` | 39 (0x27) | Exported Function | SSPICLI.LsaCallAuthenticationPackage | 0x00003ea0
`InitSecurityInterfaceA` | 35 (0x23) | Exported Function | SSPICLI.InitSecurityInterfaceA | 0x00003db2
`InitializeSecurityContextW` | 38 (0x26) | Exported Function | SSPICLI.InitializeSecurityContextW | 0x00003e60
`InitializeSecurityContextA` | 37 (0x25) | Exported Function | SSPICLI.InitializeSecurityContextA | 0x00003e22
`ImportSecurityContextW` | 34 (0x22) | Exported Function | SSPICLI.ImportSecurityContextW | 0x00003d7c
`ImportSecurityContextA` | 33 (0x21) | Exported Function | SSPICLI.ImportSecurityContextA | 0x00003d46
`ImpersonateSecurityContext` | 32 (0x20) | Exported Function | SSPICLI.ImpersonateSecurityContext | 0x00003d0c
`GetUserNameExW` | 31 (0x1f) | Exported Function | SSPICLI.GetUserNameExW | 0x00003cda
`GetUserNameExA` | 30 (0x1e) | Exported Function | SSPICLI.GetUserNameExA | 0x00003cb4
`GetSecurityUserInfo` | 29 (0x1d) | Exported Function | SSPICLI.GetSecurityUserInfo | 0x00003c89
`GetComputerObjectNameW` | 28 (0x1c) | Exported Function | 0x51b82790 | 0x00002790
`InitSecurityInterfaceW` | 36 (0x24) | Exported Function | SSPICLI.InitSecurityInterfaceW | 0x00003de8
`VerifySignature` | 101 (0x65) | Exported Function | SSPICLI.VerifySignature | 0x00004b66


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

*The following table contains possible examples of `secur32.dll` being misused. While `secur32.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $g15 = "Secur32.dll" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


