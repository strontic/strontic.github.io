---
title: sspicli.dll | Security Support Provider Interface
excerpt: What is sspicli.dll?
---

# sspicli.dll 

* File Path: `C:\Windows\system32\sspicli.dll`
* Description: Security Support Provider Interface

## Hashes

Type | Hash
-- | --
MD5 | `B7FFC692E3B83F5AC00945C9CD211587`
SHA1 | `D67E26284D153FE4397910B0E70613E2BAAFFBB0`
SHA256 | `5B32E57D55764F4236B955B980CC62E4E1C73B3D3E24028352D0A22371D1BA4A`
SHA384 | `043A9B36FEFE86F4997D75B782AFF62127628AC6271DD56D89DA39CF746F1AE15DD3BFCEEC067443E157F1A564092911`
SHA512 | `49903F681534B1827E504FEBEFA69C3C4FFC28B09660C37EBD6A1DD70416784735F3DE9EA12EDD8D7DB13595F4308F6AF284E28FA6512076A035CCF192012919`
SSDEEP | `6144:wn41AsIaPmj6XJ4Hnf1kMV9ud+TZGEDEIwrUT:gCCaPmji4Hnf6MVTjiU`
IMP | `EDF7740E83D503BFEED85BB6FC892940`
PESHA1 | `A1B26001AA6B0DFF1A5E30B7B83187002671FAF9`
PE256 | `5E561FD6E7BD91CE90894660F9078D0A35A41AEFB4F8D2A3A907EADB5F29B57E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 4 (0x4) | Exported Function | 0x00000001800024c0 | 0x000024c0
`SeciFreeCallContext` | 78 (0x4e) | Exported Function | 0x000000018000c7b0 | 0x0000c7b0
`SeciAllocateAndSetIPAddress` | 77 (0x4d) | Exported Function | 0x000000018000c440 | 0x0000c440
`SeciAllocateAndSetCallTarget` | 76 (0x4c) | Exported Function | 0x000000018000da60 | 0x0000da60
`SeciAllocateAndSetCallFlags` | 75 (0x4b) | Exported Function | 0x000000018000c9d0 | 0x0000c9d0
`SecDeleteUserModeContext` | 1 (0x1) | Exported Function | 0x0000000180024ad0 | 0x00024ad0
`SecCacheSspiPackages` | 74 (0x4a) | Exported Function | 0x0000000180022cd0 | 0x00022cd0
`SealMessage` | 73 (0x49) | Exported Function | 0x0000000180002790 | 0x00002790
`SaslSetContextOption` | 72 (0x48) | Exported Function | 0x0000000180026c50 | 0x00026c50
`SaslInitializeSecurityContextW` | 71 (0x47) | Exported Function | 0x0000000180026a90 | 0x00026a90
`SaslInitializeSecurityContextA` | 70 (0x46) | Exported Function | 0x00000001800268d0 | 0x000268d0
`SeciIsProtectedUser` | 79 (0x4f) | Exported Function | 0x000000018000cb40 | 0x0000cb40
`SaslIdentifyPackageW` | 69 (0x45) | Exported Function | 0x0000000180026890 | 0x00026890
`SaslGetProfilePackageW` | 67 (0x43) | Exported Function | 0x0000000180026800 | 0x00026800
`SaslGetProfilePackageA` | 66 (0x42) | Exported Function | 0x0000000180026780 | 0x00026780
`SaslGetContextOption` | 65 (0x41) | Exported Function | 0x0000000180026640 | 0x00026640
`SaslEnumerateProfilesW` | 64 (0x40) | Exported Function | 0x0000000180026630 | 0x00026630
`SaslEnumerateProfilesA` | 63 (0x3f) | Exported Function | 0x0000000180026620 | 0x00026620
`SaslAcceptSecurityContext` | 62 (0x3e) | Exported Function | 0x0000000180026420 | 0x00026420
`RevertSecurityContext` | 61 (0x3d) | Exported Function | 0x000000018000d5a0 | 0x0000d5a0
`QuerySecurityPackageInfoW` | 60 (0x3c) | Exported Function | 0x000000018000c340 | 0x0000c340
`QuerySecurityPackageInfoA` | 59 (0x3b) | Exported Function | 0x0000000180025700 | 0x00025700
`QuerySecurityContextToken` | 58 (0x3a) | Exported Function | 0x000000018000db70 | 0x0000db70
`SaslIdentifyPackageA` | 68 (0x44) | Exported Function | 0x0000000180026850 | 0x00026850
`SecInitUserModeContext` | 2 (0x2) | Exported Function | 0x0000000180024b50 | 0x00024b50
`SetContextAttributesA` | 80 (0x50) | Exported Function | 0x0000000180025740 | 0x00025740
`SetContextAttributesW` | 81 (0x51) | Exported Function | 0x0000000180001c80 | 0x00001c80
`SspiZeroAuthIdentity` | 103 (0x67) | Exported Function | 0x000000018000e280 | 0x0000e280
`SspiValidateAuthIdentity` | 102 (0x66) | Exported Function | 0x000000018000e180 | 0x0000e180
`SspiUnmarshalAuthIdentityInternal` | 3 (0x3) | Exported Function | 0x0000000180020310 | 0x00020310
`SspiUnmarshalAuthIdentity` | 101 (0x65) | Exported Function | 0x0000000180021570 | 0x00021570
`SspiPrepareForCredWrite` | 100 (0x64) | Exported Function | 0x000000018000b0f0 | 0x0000b0f0
`SspiPrepareForCredRead` | 99 (0x63) | Exported Function | 0x000000018000b4e0 | 0x0000b4e0
`SspiMarshalAuthIdentity` | 98 (0x62) | Exported Function | 0x0000000180021260 | 0x00021260
`SspiLocalFree` | 97 (0x61) | Exported Function | 0x000000018000cdb0 | 0x0000cdb0
`SspiIsAuthIdentityEncrypted` | 96 (0x60) | Exported Function | 0x0000000180021dd0 | 0x00021dd0
`SspiGetTargetHostName` | 95 (0x5f) | Exported Function | 0x000000018000ac60 | 0x0000ac60
`SspiGetComputerNameForSPN` | 94 (0x5e) | Exported Function | 0x0000000180022020 | 0x00022020
`SspiFreeAuthIdentity` | 93 (0x5d) | Exported Function | 0x000000018000e1d0 | 0x0000e1d0
`SspiExcludePackage` | 92 (0x5c) | Exported Function | 0x0000000180020ec0 | 0x00020ec0
`SspiEncryptAuthIdentityEx` | 91 (0x5b) | Exported Function | 0x000000018000dc40 | 0x0000dc40
`SspiEncryptAuthIdentity` | 90 (0x5a) | Exported Function | 0x000000018000dc20 | 0x0000dc20
`SspiEncodeStringsAsAuthIdentity` | 89 (0x59) | Exported Function | 0x00000001800208f0 | 0x000208f0
`SspiEncodeAuthIdentityAsStrings` | 88 (0x58) | Exported Function | 0x000000018000afa0 | 0x0000afa0
`SspiDecryptAuthIdentityEx` | 87 (0x57) | Exported Function | 0x0000000180021bf0 | 0x00021bf0
`SspiDecryptAuthIdentity` | 86 (0x56) | Exported Function | 0x0000000180021bd0 | 0x00021bd0
`SspiCopyAuthIdentity` | 85 (0x55) | Exported Function | 0x000000018000df30 | 0x0000df30
`SspiCompareAuthIdentities` | 84 (0x54) | Exported Function | 0x0000000180020610 | 0x00020610
`SetCredentialsAttributesW` | 83 (0x53) | Exported Function | 0x00000001800258b0 | 0x000258b0
`SetCredentialsAttributesA` | 82 (0x52) | Exported Function | 0x0000000180025800 | 0x00025800
`QueryCredentialsAttributesW` | 57 (0x39) | Exported Function | 0x0000000180001be0 | 0x00001be0
`UnsealMessage` | 104 (0x68) | Exported Function | 0x0000000180002830 | 0x00002830
`QueryCredentialsAttributesExW` | 56 (0x38) | Exported Function | 0x000000018000ce30 | 0x0000ce30
`QueryCredentialsAttributesA` | 54 (0x36) | Exported Function | 0x00000001800255b0 | 0x000255b0
`FreeCredentialsHandle` | 26 (0x1a) | Exported Function | 0x0000000180001e80 | 0x00001e80
`FreeContextBuffer` | 25 (0x19) | Exported Function | 0x00000001800053c0 | 0x000053c0
`ExportSecurityContext` | 24 (0x18) | Exported Function | 0x0000000180025300 | 0x00025300
`EnumerateSecurityPackagesW` | 23 (0x17) | Exported Function | 0x0000000180003c50 | 0x00003c50
`EnumerateSecurityPackagesA` | 22 (0x16) | Exported Function | 0x0000000180025260 | 0x00025260
`EncryptMessage` | 21 (0x15) | Exported Function | 0x0000000180002790 | 0x00002790
`DeleteSecurityPackageW` | 20 (0x14) | Exported Function | 0x000000018000ce20 | 0x0000ce20
`DeleteSecurityPackageA` | 19 (0x13) | Exported Function | 0x000000018000ce20 | 0x0000ce20
`DeleteSecurityContext` | 18 (0x12) | Exported Function | 0x0000000180002040 | 0x00002040
`DecryptMessage` | 17 (0x11) | Exported Function | 0x0000000180002830 | 0x00002830
`GetSecurityUserInfo` | 27 (0x1b) | Exported Function | 0x0000000180021580 | 0x00021580
`CredUnmarshalTargetInfo` | 16 (0x10) | Exported Function | 0x000000018000b760 | 0x0000b760
`CompleteAuthToken` | 14 (0xe) | Exported Function | 0x00000001800251d0 | 0x000251d0
`ChangeAccountPasswordW` | 13 (0xd) | Exported Function | 0x0000000180025180 | 0x00025180
`ChangeAccountPasswordA` | 12 (0xc) | Exported Function | 0x0000000180025130 | 0x00025130
`ApplyControlToken` | 11 (0xb) | Exported Function | 0x00000001800250a0 | 0x000250a0
`AddSecurityPackageW` | 10 (0xa) | Exported Function | 0x0000000180021610 | 0x00021610
`AddSecurityPackageA` | 9 (0x9) | Exported Function | 0x0000000180021590 | 0x00021590
`AddCredentialsW` | 8 (0x8) | Exported Function | 0x0000000180024f70 | 0x00024f70
`AddCredentialsA` | 7 (0x7) | Exported Function | 0x0000000180024e40 | 0x00024e40
`AcquireCredentialsHandleW` | 6 (0x6) | Exported Function | 0x000000018000c590 | 0x0000c590
`AcquireCredentialsHandleA` | 5 (0x5) | Exported Function | 0x000000018000c530 | 0x0000c530
`CredMarshalTargetInfo` | 15 (0xf) | Exported Function | 0x000000018000bea0 | 0x0000bea0
`GetUserNameExA` | 28 (0x1c) | Exported Function | 0x0000000180004090 | 0x00004090
`GetUserNameExW` | 29 (0x1d) | Exported Function | 0x0000000180008020 | 0x00008020
`ImpersonateSecurityContext` | 30 (0x1e) | Exported Function | 0x000000018000d620 | 0x0000d620
`QueryContextAttributesW` | 53 (0x35) | Exported Function | 0x0000000180002700 | 0x00002700
`QueryContextAttributesExW` | 52 (0x34) | Exported Function | 0x0000000180001d40 | 0x00001d40
`QueryContextAttributesExA` | 51 (0x33) | Exported Function | 0x0000000180001f80 | 0x00001f80
`QueryContextAttributesA` | 50 (0x32) | Exported Function | 0x000000018000d510 | 0x0000d510
`MakeSignature` | 49 (0x31) | Exported Function | 0x000000018000e450 | 0x0000e450
`LsaUnregisterPolicyChangeNotification` | 48 (0x30) | Exported Function | 0x000000018000e670 | 0x0000e670
`LsaRegisterPolicyChangeNotification` | 47 (0x2f) | Exported Function | 0x0000000180024c40 | 0x00024c40
`LsaRegisterLogonProcess` | 46 (0x2e) | Exported Function | 0x000000018000a890 | 0x0000a890
`LsaLookupAuthenticationPackage` | 45 (0x2d) | Exported Function | 0x0000000180003b80 | 0x00003b80
`LsaLogonUser` | 44 (0x2c) | Exported Function | 0x0000000180002e20 | 0x00002e20
`LsaGetLogonSessionData` | 43 (0x2b) | Exported Function | 0x0000000180003560 | 0x00003560
`LsaFreeReturnBuffer` | 42 (0x2a) | Exported Function | 0x00000001800085f0 | 0x000085f0
`LsaEnumerateLogonSessions` | 41 (0x29) | Exported Function | 0x0000000180024c00 | 0x00024c00
`LsaDeregisterLogonProcess` | 40 (0x28) | Exported Function | 0x000000018000a690 | 0x0000a690
`LsaConnectUntrusted` | 39 (0x27) | Exported Function | 0x000000018000a6a0 | 0x0000a6a0
`LsaCallAuthenticationPackage` | 38 (0x26) | Exported Function | 0x0000000180003a20 | 0x00003a20
`LogonUserExExW` | 37 (0x25) | Exported Function | 0x00000001800049b0 | 0x000049b0
`InitSecurityInterfaceW` | 34 (0x22) | Exported Function | 0x000000018000cd80 | 0x0000cd80
`InitSecurityInterfaceA` | 33 (0x21) | Exported Function | 0x0000000180025570 | 0x00025570
`InitializeSecurityContextW` | 36 (0x24) | Exported Function | 0x0000000180001f00 | 0x00001f00
`InitializeSecurityContextA` | 35 (0x23) | Exported Function | 0x0000000180001e00 | 0x00001e00
`ImportSecurityContextW` | 32 (0x20) | Exported Function | 0x0000000180025490 | 0x00025490
`ImportSecurityContextA` | 31 (0x1f) | Exported Function | 0x00000001800253b0 | 0x000253b0
`QueryCredentialsAttributesExA` | 55 (0x37) | Exported Function | 0x0000000180025650 | 0x00025650
`VerifySignature` | 105 (0x69) | Exported Function | 0x000000018000e4f0 | 0x0000e4f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sspicli.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/62
* VirusTotal Link: https://www.virustotal.com/gui/file/5b32e57d55764f4236b955b980cc62e4e1c73b3d3e24028352d0a22371d1ba4a/detection/





MIT License. Copyright (c) 2020 Strontic.


