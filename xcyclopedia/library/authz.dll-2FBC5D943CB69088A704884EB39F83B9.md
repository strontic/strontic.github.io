---
title: authz.dll | Authorization Framework
excerpt: What is authz.dll?
---

# authz.dll 

* File Path: `C:\Windows\system32\authz.dll`
* Description: Authorization Framework

## Hashes

Type | Hash
-- | --
MD5 | `2FBC5D943CB69088A704884EB39F83B9`
SHA1 | `D94FEB9CC09D2F924A880E3871A417F913BC3272`
SHA256 | `4E4EF8C31583ECE0A3B8ED92FF5CC9D04D6CEAF90FA00CDB8ADEE3808A835BDB`
SHA384 | `B37E6BC41EF069709C27935EE0660B9038C07E8C5AC747EAC4A6EF414C1119495D43EB00D10607DBDBA9D7EB9F6200AA`
SHA512 | `7D0BAE806D968A281197674D9A5477F73A3EE172536C35BF5CBFA568D875C16C9804AB7E67C197DB3502792A23CBE3899507C8AEB9B1FCF3FFD82C92ABFBA50F`
SSDEEP | `6144:VU17m15OeWv1cDDQzoVoRoJNNxVXiF8KXXNy:VM7cknW/ZJDxVRKXX`
IMP | `7B1BC95845D27CF40466108A31A982D3`
PESHA1 | `A06CC6A50056FCB0E3EECC39173D9DA13E5E4E33`
PE256 | `14D3D64044AF81CBA121B366147915605F9BC343B956727E52395AFF3E8C13E6`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`AuthzAccessCheck` | 1 (0x1) | Exported Function | 0x0000000180001e00 | 0x00001e00
`AuthzInitializeObjectAccessAuditEvent` | 17 (0x11) | Exported Function | 0x00000001800130f0 | 0x000130f0
`AuthzInitializeObjectAccessAuditEvent2` | 18 (0x12) | Exported Function | 0x0000000180004f20 | 0x00004f20
`AuthzInitializeRemoteAccessCheck` | 19 (0x13) | Exported Function | 0x0000000180008ce0 | 0x00008ce0
`AuthzInitializeRemoteResourceManager` | 20 (0x14) | Exported Function | 0x0000000180013140 | 0x00013140
`AuthzInitializeResourceManager` | 21 (0x15) | Exported Function | 0x00000001800059b0 | 0x000059b0
`AuthzInitializeResourceManagerEx` | 22 (0x16) | Exported Function | 0x00000001800090d0 | 0x000090d0
`AuthzInstallSecurityEventSource` | 23 (0x17) | Exported Function | 0x0000000180013180 | 0x00013180
`AuthziQuerySecurityAttributes` | 57 (0x39) | Exported Function | 0x00000001800145f0 | 0x000145f0
`AuthziSourceAudit` | 58 (0x3a) | Exported Function | 0x0000000180001010 | 0x00001010
`AuthzModifyClaims` | 24 (0x18) | Exported Function | 0x00000001800135a0 | 0x000135a0
`AuthzModifySecurityAttributes` | 25 (0x19) | Exported Function | 0x0000000180013610 | 0x00013610
`AuthzModifySids` | 26 (0x1a) | Exported Function | 0x0000000180013680 | 0x00013680
`AuthzOpenObjectAudit` | 27 (0x1b) | Exported Function | 0x00000001800136f0 | 0x000136f0
`AuthzRegisterCapChangeNotification` | 28 (0x1c) | Exported Function | 0x0000000180013910 | 0x00013910
`AuthzInitializeContextFromToken` | 16 (0x10) | Exported Function | 0x0000000180002d70 | 0x00002d70
`AuthzRegisterSecurityEventSource` | 29 (0x1d) | Exported Function | 0x0000000180013a00 | 0x00013a00
`AuthzReportSecurityEventFromParams` | 31 (0x1f) | Exported Function | 0x0000000180013bb0 | 0x00013bb0
`AuthzSetAppContainerInformation` | 32 (0x20) | Exported Function | 0x0000000180013d50 | 0x00013d50
`AuthzShutdownRemoteAccessCheck` | 33 (0x21) | Exported Function | 0x0000000180013da0 | 0x00013da0
`AuthzUninstallSecurityEventSource` | 34 (0x22) | Exported Function | 0x0000000180013db0 | 0x00013db0
`AuthzUnregisterCapChangeNotification` | 35 (0x23) | Exported Function | 0x0000000180013e70 | 0x00013e70
`AuthzUnregisterSecurityEventSource` | 36 (0x24) | Exported Function | 0x0000000180013ee0 | 0x00013ee0
`FreeClaimDefinitions` | 59 (0x3b) | Exported Function | 0x0000000180021130 | 0x00021130
`FreeClaimDictionary` | 60 (0x3c) | Exported Function | 0x00000001800211e0 | 0x000211e0
`GenerateNewCAPID` | 61 (0x3d) | Exported Function | 0x0000000180019450 | 0x00019450
`GetCentralAccessPoliciesByCapID` | 62 (0x3e) | Exported Function | 0x000000018001f1d0 | 0x0001f1d0
`GetCentralAccessPoliciesByDN` | 63 (0x3f) | Exported Function | 0x000000018001f840 | 0x0001f840
`GetClaimDefinitions` | 64 (0x40) | Exported Function | 0x0000000180021200 | 0x00021200
`GetClaimDomainInfo` | 65 (0x41) | Exported Function | 0x00000001800212e0 | 0x000212e0
`GetDefaultCAPESecurityDescriptor` | 66 (0x42) | Exported Function | 0x0000000180019580 | 0x00019580
`AuthzReportSecurityEvent` | 30 (0x1e) | Exported Function | 0x0000000180013af0 | 0x00013af0
`AuthzInitializeContextFromSid` | 15 (0xf) | Exported Function | 0x0000000180002820 | 0x00002820
`AuthzInitializeContextFromAuthzContext` | 14 (0xe) | Exported Function | 0x0000000180008940 | 0x00008940
`AuthzInitializeCompoundContext` | 13 (0xd) | Exported Function | 0x0000000180012ff0 | 0x00012ff0
`AuthzAddSidsToContext` | 2 (0x2) | Exported Function | 0x0000000180012200 | 0x00012200
`AuthzCachedAccessCheck` | 3 (0x3) | Exported Function | 0x0000000180012320 | 0x00012320
`AuthzComputeEffectivePermission` | 4 (0x4) | Exported Function | 0x0000000180021c00 | 0x00021c00
`AuthzEnumerateSecurityEventSources` | 5 (0x5) | Exported Function | 0x0000000180012880 | 0x00012880
`AuthzEvaluateSacl` | 6 (0x6) | Exported Function | 0x0000000180012eb0 | 0x00012eb0
`AuthzFreeAuditEvent` | 7 (0x7) | Exported Function | 0x0000000180005cc0 | 0x00005cc0
`AuthzFreeCentralAccessPolicyCache` | 8 (0x8) | Exported Function | 0x0000000180012f40 | 0x00012f40
`AuthzFreeContext` | 9 (0x9) | Exported Function | 0x0000000180002900 | 0x00002900
`AuthzFreeHandle` | 10 (0xa) | Exported Function | 0x0000000180012f50 | 0x00012f50
`AuthzFreeResourceManager` | 11 (0xb) | Exported Function | 0x0000000180005520 | 0x00005520
`AuthzGetInformationFromContext` | 12 (0xc) | Exported Function | 0x0000000180002650 | 0x00002650
`AuthziAccessCheckEx` | 37 (0x25) | Exported Function | 0x0000000180013fa0 | 0x00013fa0
`AuthziAllocateAuditParams` | 38 (0x26) | Exported Function | 0x00000001800011f0 | 0x000011f0
`AuthziCheckContextMembership` | 39 (0x27) | Exported Function | 0x0000000180014040 | 0x00014040
`AuthziFreeAuditEventType` | 40 (0x28) | Exported Function | 0x0000000180005ca0 | 0x00005ca0
`AuthziFreeAuditParams` | 41 (0x29) | Exported Function | 0x0000000180001190 | 0x00001190
`AuthziFreeAuditQueue` | 42 (0x2a) | Exported Function | 0x00000001800140a0 | 0x000140a0
`AuthziModifySecurityAttributes` | 56 (0x38) | Exported Function | 0x0000000180014580 | 0x00014580
`AuthziModifyAuditQueue` | 55 (0x37) | Exported Function | 0x0000000180014500 | 0x00014500
`AuthziModifyAuditEventType` | 54 (0x36) | Exported Function | 0x0000000180014490 | 0x00014490
`AuthziModifyAuditEvent2` | 53 (0x35) | Exported Function | 0x0000000180008270 | 0x00008270
`AuthziModifyAuditEvent` | 52 (0x34) | Exported Function | 0x0000000180014450 | 0x00014450
`AuthziLogAuditEvent` | 51 (0x33) | Exported Function | 0x0000000180005e00 | 0x00005e00
`InitializeClaimDictionary` | 67 (0x43) | Exported Function | 0x00000001800213b0 | 0x000213b0
`AuthziInitializeContextFromSid` | 50 (0x32) | Exported Function | 0x0000000180014340 | 0x00014340
`AuthziInitializeAuditParamsWithRM` | 48 (0x30) | Exported Function | 0x00000001800087c0 | 0x000087c0
`AuthziInitializeAuditParamsFromArray` | 47 (0x2f) | Exported Function | 0x00000001800141a0 | 0x000141a0
`AuthziInitializeAuditParams` | 46 (0x2e) | Exported Function | 0x00000001800065d0 | 0x000065d0
`AuthziInitializeAuditEventType` | 45 (0x2d) | Exported Function | 0x0000000180006350 | 0x00006350
`AuthziInitializeAuditEvent` | 44 (0x2c) | Exported Function | 0x00000001800050a0 | 0x000050a0
`AuthziGenerateAdminAlertAuditW` | 43 (0x2b) | Exported Function | 0x0000000180011b10 | 0x00011b10
`AuthziInitializeAuditQueue` | 49 (0x31) | Exported Function | 0x00000001800092a0 | 0x000092a0
`RefreshClaimDictionary` | 68 (0x44) | Exported Function | 0x0000000180021550 | 0x00021550


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/4e4ef8c31583ece0a3b8ed92ff5cc9d04d6ceaf90fa00cdb8adee3808a835bdb/detection/





MIT License. Copyright (c) 2020 Strontic.


