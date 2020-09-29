---
title: sspicli.dll | Security Support Provider Interface
excerpt: What is sspicli.dll?
---

# sspicli.dll 

* File Path: `C:\Windows\SysWOW64\sspicli.dll`
* Description: Security Support Provider Interface

## Hashes

Type | Hash
-- | --
MD5 | `65170C3B74F3F65D70DF841AE340852C`
SHA1 | `7FAC095C91208A7DF0B531D5EB016E428F1CD1FD`
SHA256 | `0219DDF7B96FDEE8A86C3A5EA47E1EA3CE74821C10EC0849AB05CBCDA2B40AAA`
SHA384 | `15BE9AB1EE923B68A31168405E3AA5AB184D60297C5C1D9CA405AB05E6E295FFE6167CBE96AFF6B8AC818B52CE6EF78C`
SHA512 | `3DEFCD57E9EADAACAF57D671163A29C4A36D309065CB6AB44D3BA911F5D03EEF042DCF657DB3A225AFD434E9012BFE9B074CD8125C78D49BE1E92C5E8A14B383`
SSDEEP | `3072:ABVoOPqqQPHgxwHeGi8v8AxdCGtUndC1VjN8uOdgii15e5fJ73cdJvfWcmvSofUU:AwHet8v89dndCToQvf3eSofUvSHg3PFG`
IMP | `BE1043FDE2B23ADEADA844731978991C`
PESHA1 | `DF55E18CE29F3DCACC83EB3A83858F5472B850ED`
PE256 | `C8B2A974E0357AB1B0363458B80FF36CF4C9BCAC2976E2AB14D53DD9C9305B14`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AcceptSecurityContext` | 4 (0x4) | Exported Function | 0x1001b5d0 | 0x0001b5d0
`SeciFreeCallContext` | 78 (0x4e) | Exported Function | 0x1001db40 | 0x0001db40
`SeciAllocateAndSetIPAddress` | 77 (0x4d) | Exported Function | 0x1001d9f0 | 0x0001d9f0
`SeciAllocateAndSetCallTarget` | 76 (0x4c) | Exported Function | 0x1001da10 | 0x0001da10
`SeciAllocateAndSetCallFlags` | 75 (0x4b) | Exported Function | 0x1001daf0 | 0x0001daf0
`SecDeleteUserModeContext` | 1 (0x1) | Exported Function | 0x10019900 | 0x00019900
`SecCacheSspiPackages` | 74 (0x4a) | Exported Function | 0x10011a90 | 0x00011a90
`SealMessage` | 73 (0x49) | Exported Function | 0x1001c2b0 | 0x0001c2b0
`SaslSetContextOption` | 72 (0x48) | Exported Function | 0x1001cc80 | 0x0001cc80
`SaslInitializeSecurityContextW` | 71 (0x47) | Exported Function | 0x1001d2b0 | 0x0001d2b0
`SaslInitializeSecurityContextA` | 70 (0x46) | Exported Function | 0x1001d3f0 | 0x0001d3f0
`SeciIsProtectedUser` | 79 (0x4f) | Exported Function | 0x10019c70 | 0x00019c70
`SaslIdentifyPackageW` | 69 (0x45) | Exported Function | 0x1001d9c0 | 0x0001d9c0
`SaslGetProfilePackageW` | 67 (0x43) | Exported Function | 0x1001d270 | 0x0001d270
`SaslGetProfilePackageA` | 66 (0x42) | Exported Function | 0x1001d210 | 0x0001d210
`SaslGetContextOption` | 65 (0x41) | Exported Function | 0x1001cb70 | 0x0001cb70
`SaslEnumerateProfilesW` | 64 (0x40) | Exported Function | 0x1001d1f0 | 0x0001d1f0
`SaslEnumerateProfilesA` | 63 (0x3f) | Exported Function | 0x1001d1d0 | 0x0001d1d0
`SaslAcceptSecurityContext` | 62 (0x3e) | Exported Function | 0x1001d530 | 0x0001d530
`RevertSecurityContext` | 61 (0x3d) | Exported Function | 0x1001bc80 | 0x0001bc80
`QuerySecurityPackageInfoW` | 60 (0x3c) | Exported Function | 0x1001bb00 | 0x0001bb00
`QuerySecurityPackageInfoA` | 59 (0x3b) | Exported Function | 0x1001bb30 | 0x0001bb30
`QuerySecurityContextToken` | 58 (0x3a) | Exported Function | 0x1001bc10 | 0x0001bc10
`SaslIdentifyPackageA` | 68 (0x44) | Exported Function | 0x1001d990 | 0x0001d990
`SecInitUserModeContext` | 2 (0x2) | Exported Function | 0x10019870 | 0x00019870
`SetContextAttributesA` | 80 (0x50) | Exported Function | 0x1001bee0 | 0x0001bee0
`SetContextAttributesW` | 81 (0x51) | Exported Function | 0x1001be70 | 0x0001be70
`SspiZeroAuthIdentity` | 103 (0x67) | Exported Function | 0x1000c500 | 0x0000c500
`SspiValidateAuthIdentity` | 102 (0x66) | Exported Function | 0x1000be60 | 0x0000be60
`SspiUnmarshalAuthIdentityInternal` | 3 (0x3) | Exported Function | 0x1000bb10 | 0x0000bb10
`SspiUnmarshalAuthIdentity` | 101 (0x65) | Exported Function | 0x1000be40 | 0x0000be40
`SspiPrepareForCredWrite` | 100 (0x64) | Exported Function | 0x1000d5e0 | 0x0000d5e0
`SspiPrepareForCredRead` | 99 (0x63) | Exported Function | 0x1000da50 | 0x0000da50
`SspiMarshalAuthIdentity` | 98 (0x62) | Exported Function | 0x1000b850 | 0x0000b850
`SspiLocalFree` | 97 (0x61) | Exported Function | 0x1000a2a0 | 0x0000a2a0
`SspiIsAuthIdentityEncrypted` | 96 (0x60) | Exported Function | 0x1000ee90 | 0x0000ee90
`SspiGetTargetHostName` | 95 (0x5f) | Exported Function | 0x1000cba0 | 0x0000cba0
`SspiGetComputerNameForSPN` | 94 (0x5e) | Exported Function | 0x1000f180 | 0x0000f180
`SspiFreeAuthIdentity` | 93 (0x5d) | Exported Function | 0x1000c470 | 0x0000c470
`SspiExcludePackage` | 92 (0x5c) | Exported Function | 0x1000cc70 | 0x0000cc70
`SspiEncryptAuthIdentityEx` | 91 (0x5b) | Exported Function | 0x1000e850 | 0x0000e850
`SspiEncryptAuthIdentity` | 90 (0x5a) | Exported Function | 0x1000ea30 | 0x0000ea30
`SspiEncodeStringsAsAuthIdentity` | 89 (0x59) | Exported Function | 0x1000b3c0 | 0x0000b3c0
`SspiEncodeAuthIdentityAsStrings` | 88 (0x58) | Exported Function | 0x1000a6d0 | 0x0000a6d0
`SspiDecryptAuthIdentityEx` | 87 (0x57) | Exported Function | 0x1000ebd0 | 0x0000ebd0
`SspiDecryptAuthIdentity` | 86 (0x56) | Exported Function | 0x1000ed90 | 0x0000ed90
`SspiCopyAuthIdentity` | 85 (0x55) | Exported Function | 0x1000bf80 | 0x0000bf80
`SspiCompareAuthIdentities` | 84 (0x54) | Exported Function | 0x1000c770 | 0x0000c770
`SetCredentialsAttributesW` | 83 (0x53) | Exported Function | 0x1001c110 | 0x0001c110
`SetCredentialsAttributesA` | 82 (0x52) | Exported Function | 0x1001c180 | 0x0001c180
`QueryCredentialsAttributesW` | 57 (0x39) | Exported Function | 0x1001bf50 | 0x0001bf50
`UnsealMessage` | 104 (0x68) | Exported Function | 0x1001c310 | 0x0001c310
`QueryCredentialsAttributesExW` | 56 (0x38) | Exported Function | 0x1001bfc0 | 0x0001bfc0
`QueryCredentialsAttributesA` | 54 (0x36) | Exported Function | 0x1001c030 | 0x0001c030
`FreeCredentialsHandle` | 26 (0x1a) | Exported Function | 0x1001b180 | 0x0001b180
`FreeContextBuffer` | 25 (0x19) | Exported Function | 0x1000dae0 | 0x0000dae0
`ExportSecurityContext` | 24 (0x18) | Exported Function | 0x1001c3d0 | 0x0001c3d0
`EnumerateSecurityPackagesW` | 23 (0x17) | Exported Function | 0x1001ba00 | 0x0001ba00
`EnumerateSecurityPackagesA` | 22 (0x16) | Exported Function | 0x1001ba80 | 0x0001ba80
`EncryptMessage` | 21 (0x15) | Exported Function | 0x1001c2b0 | 0x0001c2b0
`DeleteSecurityPackageW` | 20 (0x14) | Exported Function | 0x1000dc40 | 0x0000dc40
`DeleteSecurityPackageA` | 19 (0x13) | Exported Function | 0x1000dc40 | 0x0000dc40
`DeleteSecurityContext` | 18 (0x12) | Exported Function | 0x1001b910 | 0x0001b910
`DecryptMessage` | 17 (0x11) | Exported Function | 0x1001c310 | 0x0001c310
`GetSecurityUserInfo` | 27 (0x1b) | Exported Function | 0x1000dac0 | 0x0000dac0
`CredUnmarshalTargetInfo` | 16 (0x10) | Exported Function | 0x10006b40 | 0x00006b40
`CompleteAuthToken` | 14 (0xe) | Exported Function | 0x1001bb60 | 0x0001bb60
`ChangeAccountPasswordW` | 13 (0xd) | Exported Function | 0x1001ac00 | 0x0001ac00
`ChangeAccountPasswordA` | 12 (0xc) | Exported Function | 0x1001ac30 | 0x0001ac30
`ApplyControlToken` | 11 (0xb) | Exported Function | 0x1001b9a0 | 0x0001b9a0
`AddSecurityPackageW` | 10 (0xa) | Exported Function | 0x1000db90 | 0x0000db90
`AddSecurityPackageA` | 9 (0x9) | Exported Function | 0x1000dbd0 | 0x0000dbd0
`AddCredentialsW` | 8 (0x8) | Exported Function | 0x1001b000 | 0x0001b000
`AddCredentialsA` | 7 (0x7) | Exported Function | 0x1001b0c0 | 0x0001b0c0
`AcquireCredentialsHandleW` | 6 (0x6) | Exported Function | 0x1001ad80 | 0x0001ad80
`AcquireCredentialsHandleA` | 5 (0x5) | Exported Function | 0x1001adb0 | 0x0001adb0
`CredMarshalTargetInfo` | 15 (0xf) | Exported Function | 0x10006820 | 0x00006820
`GetUserNameExA` | 28 (0x1c) | Exported Function | 0x1000efe0 | 0x0000efe0
`GetUserNameExW` | 29 (0x1d) | Exported Function | 0x1000eee0 | 0x0000eee0
`ImpersonateSecurityContext` | 30 (0x1e) | Exported Function | 0x1001bbc0 | 0x0001bbc0
`QueryContextAttributesW` | 53 (0x35) | Exported Function | 0x1001bcd0 | 0x0001bcd0
`QueryContextAttributesExW` | 52 (0x34) | Exported Function | 0x1001bd30 | 0x0001bd30
`QueryContextAttributesExA` | 51 (0x33) | Exported Function | 0x1001be00 | 0x0001be00
`QueryContextAttributesA` | 50 (0x32) | Exported Function | 0x1001bda0 | 0x0001bda0
`MakeSignature` | 49 (0x31) | Exported Function | 0x1001c1f0 | 0x0001c1f0
`LsaUnregisterPolicyChangeNotification` | 48 (0x30) | Exported Function | 0x10019be0 | 0x00019be0
`LsaRegisterPolicyChangeNotification` | 47 (0x2f) | Exported Function | 0x10019bb0 | 0x00019bb0
`LsaRegisterLogonProcess` | 46 (0x2e) | Exported Function | 0x10005ac0 | 0x00005ac0
`LsaLookupAuthenticationPackage` | 45 (0x2d) | Exported Function | 0x10005cf0 | 0x00005cf0
`LsaLogonUser` | 44 (0x2c) | Exported Function | 0x10005d80 | 0x00005d80
`LsaGetLogonSessionData` | 43 (0x2b) | Exported Function | 0x10019c40 | 0x00019c40
`LsaFreeReturnBuffer` | 42 (0x2a) | Exported Function | 0x10005a50 | 0x00005a50
`LsaEnumerateLogonSessions` | 41 (0x29) | Exported Function | 0x10019c10 | 0x00019c10
`LsaDeregisterLogonProcess` | 40 (0x28) | Exported Function | 0x10005ec0 | 0x00005ec0
`LsaConnectUntrusted` | 39 (0x27) | Exported Function | 0x10005be0 | 0x00005be0
`LsaCallAuthenticationPackage` | 38 (0x26) | Exported Function | 0x10005dc0 | 0x00005dc0
`LogonUserExExW` | 37 (0x25) | Exported Function | 0x1001e070 | 0x0001e070
`InitSecurityInterfaceW` | 34 (0x22) | Exported Function | 0x1001c3a0 | 0x0001c3a0
`InitSecurityInterfaceA` | 33 (0x21) | Exported Function | 0x1001c370 | 0x0001c370
`InitializeSecurityContextW` | 36 (0x24) | Exported Function | 0x1001b1d0 | 0x0001b1d0
`InitializeSecurityContextA` | 35 (0x23) | Exported Function | 0x1001b210 | 0x0001b210
`ImportSecurityContextW` | 32 (0x20) | Exported Function | 0x1001c440 | 0x0001c440
`ImportSecurityContextA` | 31 (0x1f) | Exported Function | 0x1001c4d0 | 0x0001c4d0
`QueryCredentialsAttributesExA` | 55 (0x37) | Exported Function | 0x1001c0a0 | 0x0001c0a0
`VerifySignature` | 105 (0x69) | Exported Function | 0x1001c250 | 0x0001c250


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: security.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/0219ddf7b96fdee8a86c3a5ea47e1ea3ce74821c10ec0849ab05cbcda2b40aaa/detection/





MIT License. Copyright (c) 2020 Strontic.


