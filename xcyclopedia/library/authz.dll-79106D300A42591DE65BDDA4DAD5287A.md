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
`AuthziModifyAuditEvent2` | 52 | Exported Function
`AuthziModifyAuditEventType` | 54 | Exported Function
`AuthziLogAuditEvent` | 51 | Exported Function
`AuthziModifyAuditEvent` | 53 | Exported Function
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3b9d3c6f5174f604fb2f16b6bd82f70c5b476fd98f72b717b5ca563d0c7a7ba3/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\scesrv.dll](scesrv.dll-D91FAA99219AA2FB9EB648EDFDD254DC.md) | 30




MIT License. Copyright (c) 2020 Strontic.


