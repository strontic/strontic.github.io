---
title: authz.dll | Authorization Framework
excerpt: What is authz.dll?
---

# authz.dll 

* File Path: `C:\Windows\SysWOW64\authz.dll`
* Description: Authorization Framework

## Hashes

Type | Hash
-- | --
MD5 | `79106D300A42591DE65BDDA4DAD5287A`
SHA1 | `DD40E873891EC2ED3C131D5EE8CAFB2629EB4D9E`
SHA256 | `3B9D3C6F5174F604FB2F16B6BD82F70C5B476FD98F72B717B5CA563D0C7A7BA3`
SHA384 | `CBFB7887DBD9C92122C1BC36D151F383317F16C1C5FA2F64EF3E88CB1B8E5DB9BC711452FC46D76024333147616714AD`
SHA512 | `A9C87F0436731A682E68E71A23B8C006AC8F7C1E816484A8A37EE99F0778051FFA84C75BE7B4B9719B6EA57830CBE899A44EDCEFE20495DCEEF9C54C4D55BD93`
SSDEEP | `3072:2aOXicLYDVANUyp6ht6NarHMz4hXgB8bV92fBxv8wRe4ifr/5DrABZKKYyB:2aOXicLYDLyWPTA4djI5Ow4zSBZKKYC`
IMP | `B537A6DCF8732C14BFA75AB78FBF1F39`
PESHA1 | `6A57062C0B69858495F227E00820ABE011756006`
PE256 | `0BD9A87375A9C24D0311AD3230ECC2F5EADDF7C30216D4EFCB0E93CB5AE407BB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuthzAccessCheck` | 1 (0x1) | Exported Function | 0x10009290 | 0x00009290
`AuthzInitializeObjectAccessAuditEvent` | 17 (0x11) | Exported Function | 0x10012770 | 0x00012770
`AuthzInitializeObjectAccessAuditEvent2` | 18 (0x12) | Exported Function | 0x1000b440 | 0x0000b440
`AuthzInitializeRemoteAccessCheck` | 19 (0x13) | Exported Function | 0x100127a0 | 0x000127a0
`AuthzInitializeRemoteResourceManager` | 20 (0x14) | Exported Function | 0x100127d0 | 0x000127d0
`AuthzInitializeResourceManager` | 21 (0x15) | Exported Function | 0x1000a2f0 | 0x0000a2f0
`AuthzInitializeResourceManagerEx` | 22 (0x16) | Exported Function | 0x10012800 | 0x00012800
`AuthzInstallSecurityEventSource` | 23 (0x17) | Exported Function | 0x10012870 | 0x00012870
`AuthziQuerySecurityAttributes` | 57 (0x39) | Exported Function | 0x10013840 | 0x00013840
`AuthziSourceAudit` | 58 (0x3a) | Exported Function | 0x10007630 | 0x00007630
`AuthzModifyClaims` | 24 (0x18) | Exported Function | 0x10012b60 | 0x00012b60
`AuthzModifySecurityAttributes` | 25 (0x19) | Exported Function | 0x10012bd0 | 0x00012bd0
`AuthzModifySids` | 26 (0x1a) | Exported Function | 0x10012c30 | 0x00012c30
`AuthzOpenObjectAudit` | 27 (0x1b) | Exported Function | 0x10012ca0 | 0x00012ca0
`AuthzRegisterCapChangeNotification` | 28 (0x1c) | Exported Function | 0x10012e40 | 0x00012e40
`AuthzInitializeContextFromToken` | 16 (0x10) | Exported Function | 0x10007bd0 | 0x00007bd0
`AuthzRegisterSecurityEventSource` | 29 (0x1d) | Exported Function | 0x10012ed0 | 0x00012ed0
`AuthzReportSecurityEventFromParams` | 31 (0x1f) | Exported Function | 0x10013040 | 0x00013040
`AuthzSetAppContainerInformation` | 32 (0x20) | Exported Function | 0x10013170 | 0x00013170
`AuthzShutdownRemoteAccessCheck` | 33 (0x21) | Exported Function | 0x100131b0 | 0x000131b0
`AuthzUninstallSecurityEventSource` | 34 (0x22) | Exported Function | 0x100131c0 | 0x000131c0
`AuthzUnregisterCapChangeNotification` | 35 (0x23) | Exported Function | 0x10013240 | 0x00013240
`AuthzUnregisterSecurityEventSource` | 36 (0x24) | Exported Function | 0x10013290 | 0x00013290
`FreeClaimDefinitions` | 59 (0x3b) | Exported Function | 0x1001f2d0 | 0x0001f2d0
`FreeClaimDictionary` | 60 (0x3c) | Exported Function | 0x1001f340 | 0x0001f340
`GenerateNewCAPID` | 61 (0x3d) | Exported Function | 0x100194b0 | 0x000194b0
`GetCentralAccessPoliciesByCapID` | 62 (0x3e) | Exported Function | 0x1001e1b0 | 0x0001e1b0
`GetCentralAccessPoliciesByDN` | 63 (0x3f) | Exported Function | 0x1001e4f0 | 0x0001e4f0
`GetClaimDefinitions` | 64 (0x40) | Exported Function | 0x1001f360 | 0x0001f360
`GetClaimDomainInfo` | 65 (0x41) | Exported Function | 0x1001f400 | 0x0001f400
`GetDefaultCAPESecurityDescriptor` | 66 (0x42) | Exported Function | 0x10019590 | 0x00019590
`AuthzReportSecurityEvent` | 30 (0x1e) | Exported Function | 0x10012fa0 | 0x00012fa0
`AuthzInitializeContextFromSid` | 15 (0xf) | Exported Function | 0x100077d0 | 0x000077d0
`AuthzInitializeContextFromAuthzContext` | 14 (0xe) | Exported Function | 0x100126e0 | 0x000126e0
`AuthzInitializeCompoundContext` | 13 (0xd) | Exported Function | 0x10012610 | 0x00012610
`AuthzAddSidsToContext` | 2 (0x2) | Exported Function | 0x10011a70 | 0x00011a70
`AuthzCachedAccessCheck` | 3 (0x3) | Exported Function | 0x10011b10 | 0x00011b10
`AuthzComputeEffectivePermission` | 4 (0x4) | Exported Function | 0x1001fb40 | 0x0001fb40
`AuthzEnumerateSecurityEventSources` | 5 (0x5) | Exported Function | 0x10011f80 | 0x00011f80
`AuthzEvaluateSacl` | 6 (0x6) | Exported Function | 0x10012520 | 0x00012520
`AuthzFreeAuditEvent` | 7 (0x7) | Exported Function | 0x1000a220 | 0x0000a220
`AuthzFreeCentralAccessPolicyCache` | 8 (0x8) | Exported Function | 0x10012590 | 0x00012590
`AuthzFreeContext` | 9 (0x9) | Exported Function | 0x1000b090 | 0x0000b090
`AuthzFreeHandle` | 10 (0xa) | Exported Function | 0x100125a0 | 0x000125a0
`AuthzFreeResourceManager` | 11 (0xb) | Exported Function | 0x1000b870 | 0x0000b870
`AuthzGetInformationFromContext` | 12 (0xc) | Exported Function | 0x1000b6d0 | 0x0000b6d0
`AuthziAccessCheckEx` | 37 (0x25) | Exported Function | 0x10013340 | 0x00013340
`AuthziAllocateAuditParams` | 38 (0x26) | Exported Function | 0x10007770 | 0x00007770
`AuthziCheckContextMembership` | 39 (0x27) | Exported Function | 0x10013390 | 0x00013390
`AuthziFreeAuditEventType` | 40 (0x28) | Exported Function | 0x1000a9b0 | 0x0000a9b0
`AuthziFreeAuditParams` | 41 (0x29) | Exported Function | 0x10007720 | 0x00007720
`AuthziFreeAuditQueue` | 42 (0x2a) | Exported Function | 0x100133e0 | 0x000133e0
`AuthziModifySecurityAttributes` | 56 (0x38) | Exported Function | 0x100137e0 | 0x000137e0
`AuthziModifyAuditQueue` | 55 (0x37) | Exported Function | 0x10013770 | 0x00013770
`AuthziModifyAuditEventType` | 54 (0x36) | Exported Function | 0x10013720 | 0x00013720
`AuthziModifyAuditEvent2` | 52 (0x34) | Exported Function | 0x10013660 | 0x00013660
`AuthziModifyAuditEvent` | 53 (0x35) | Exported Function | 0x100136f0 | 0x000136f0
`AuthziLogAuditEvent` | 51 (0x33) | Exported Function | 0x1000aa80 | 0x0000aa80
`InitializeClaimDictionary` | 67 (0x43) | Exported Function | 0x1001f4a0 | 0x0001f4a0
`AuthziInitializeContextFromSid` | 50 (0x32) | Exported Function | 0x100135d0 | 0x000135d0
`AuthziInitializeAuditParamsWithRM` | 48 (0x30) | Exported Function | 0x1000bd60 | 0x0000bd60
`AuthziInitializeAuditParamsFromArray` | 47 (0x2f) | Exported Function | 0x10013480 | 0x00013480
`AuthziInitializeAuditParams` | 46 (0x2e) | Exported Function | 0x1000a570 | 0x0000a570
`AuthziInitializeAuditEventType` | 45 (0x2d) | Exported Function | 0x1000ae60 | 0x0000ae60
`AuthziInitializeAuditEvent` | 44 (0x2c) | Exported Function | 0x1000b230 | 0x0000b230
`AuthziGenerateAdminAlertAuditW` | 43 (0x2b) | Exported Function | 0x10011460 | 0x00011460
`AuthziInitializeAuditQueue` | 49 (0x31) | Exported Function | 0x1000c0e0 | 0x0000c0e0
`RefreshClaimDictionary` | 68 (0x44) | Exported Function | 0x1001f5f0 | 0x0001f5f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: authz.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3b9d3c6f5174f604fb2f16b6bd82f70c5b476fd98f72b717b5ca563d0c7a7ba3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\scesrv.dll](scesrv.dll-D91FAA99219AA2FB9EB648EDFDD254DC.md) | 30




MIT License. Copyright (c) 2020 Strontic.


