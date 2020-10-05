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

Function Name | Ordinal | Type
-- | -- | --
`AuthzModifyClaims` | 24 | Exported Function
`AuthzModifySecurityAttributes` | 25 | Exported Function
`AuthziQuerySecurityAttributes` | 57 | Exported Function
`AuthziSourceAudit` | 58 | Exported Function
`AuthzRegisterCapChangeNotification` | 28 | Exported Function
`AuthzRegisterSecurityEventSource` | 29 | Exported Function
`AuthzModifySids` | 26 | Exported Function
`AuthzOpenObjectAudit` | 27 | Exported Function
`AuthzInstallSecurityEventSource` | 23 | Exported Function
`AuthzInitializeObjectAccessAuditEvent` | 17 | Exported Function
`AuthzInitializeObjectAccessAuditEvent2` | 18 | Exported Function
`AuthzInitializeContextFromSid` | 15 | Exported Function
`AuthzInitializeContextFromToken` | 16 | Exported Function
`AuthzInitializeResourceManager` | 21 | Exported Function
`AuthzInitializeResourceManagerEx` | 22 | Exported Function
`AuthzInitializeRemoteAccessCheck` | 19 | Exported Function
`AuthzInitializeRemoteResourceManager` | 20 | Exported Function
`GetCentralAccessPoliciesByDN` | 63 | Exported Function
`GetClaimDefinitions` | 64 | Exported Function
`GenerateNewCAPID` | 61 | Exported Function
`GetCentralAccessPoliciesByCapID` | 62 | Exported Function
`InitializeClaimDictionary` | 67 | Exported Function
`RefreshClaimDictionary` | 68 | Exported Function
`GetClaimDomainInfo` | 65 | Exported Function
`GetDefaultCAPESecurityDescriptor` | 66 | Exported Function
`FreeClaimDictionary` | 60 | Exported Function
`AuthzSetAppContainerInformation` | 32 | Exported Function
`AuthzShutdownRemoteAccessCheck` | 33 | Exported Function
`AuthzReportSecurityEvent` | 30 | Exported Function
`AuthzReportSecurityEventFromParams` | 31 | Exported Function
`AuthzUnregisterSecurityEventSource` | 36 | Exported Function
`FreeClaimDefinitions` | 59 | Exported Function
`AuthzUninstallSecurityEventSource` | 34 | Exported Function
`AuthzUnregisterCapChangeNotification` | 35 | Exported Function
`AuthzGetInformationFromContext` | 12 | Exported Function
`AuthziAccessCheckEx` | 37 | Exported Function
`AuthzFreeHandle` | 10 | Exported Function
`AuthzFreeResourceManager` | 11 | Exported Function
`AuthziFreeAuditEventType` | 40 | Exported Function
`AuthziFreeAuditParams` | 41 | Exported Function
`AuthziAllocateAuditParams` | 38 | Exported Function
`AuthziCheckContextMembership` | 39 | Exported Function
`AuthzFreeContext` | 9 | Exported Function
`AuthzCachedAccessCheck` | 3 | Exported Function
`AuthzComputeEffectivePermission` | 4 | Exported Function
`AuthzAccessCheck` | 1 | Exported Function
`AuthzAddSidsToContext` | 2 | Exported Function
`AuthzFreeAuditEvent` | 7 | Exported Function
`AuthzFreeCentralAccessPolicyCache` | 8 | Exported Function
`AuthzEnumerateSecurityEventSources` | 5 | Exported Function
`AuthzEvaluateSacl` | 6 | Exported Function
`AuthziModifyAuditEvent2` | 53 | Exported Function
`AuthziModifyAuditEventType` | 54 | Exported Function
`AuthziLogAuditEvent` | 51 | Exported Function
`AuthziModifyAuditEvent` | 52 | Exported Function
`AuthzInitializeCompoundContext` | 13 | Exported Function
`AuthzInitializeContextFromAuthzContext` | 14 | Exported Function
`AuthziModifyAuditQueue` | 55 | Exported Function
`AuthziModifySecurityAttributes` | 56 | Exported Function
`AuthziInitializeContextFromSid` | 50 | Exported Function
`AuthziInitializeAuditEvent` | 44 | Exported Function
`AuthziInitializeAuditEventType` | 45 | Exported Function
`AuthziFreeAuditQueue` | 42 | Exported Function
`AuthziGenerateAdminAlertAuditW` | 43 | Exported Function
`AuthziInitializeAuditParamsWithRM` | 48 | Exported Function
`AuthziInitializeAuditQueue` | 49 | Exported Function
`AuthziInitializeAuditParams` | 46 | Exported Function
`AuthziInitializeAuditParamsFromArray` | 47 | Exported Function


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


