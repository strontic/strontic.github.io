---
title: dmenrollengine.dll | Enroll Engine DLL
excerpt: What is dmenrollengine.dll?
---

# dmenrollengine.dll 

* File Path: `C:\Windows\SysWOW64\dmenrollengine.dll`
* Description: Enroll Engine DLL

## Hashes

Type | Hash
-- | --
MD5 | `5E12476CA507DA0085E31DC2270D4EA7`
SHA1 | `C92AE2D924E37A2551911489DCE90864FEA359E0`
SHA256 | `D7107BD364E0650E552E554E990B5E687EE68A2F90A479E331872E57F432CBA7`
SHA384 | `002D64D1782C68694400C424E8722F66A4D5DA4E58B37212E86F23D13ADCF8A2F6E0C685FF37227D85D1BA564A796668`
SHA512 | `9CE2560637FE11C3881D226F6BC59E72C518970E6E9F8453DDBA479235B9B79CB06B27A5F3A0CF67032C3ACB83CCFE3F139D4EBE8995CF35C5AEEF5722C7C19C`
SSDEEP | `12288:1nYlHXlHplH1lHlRT0b2z3NZyqE2fZs3zlN9VCm1s+8gJj:1nYlHXlHplH1lHl1023NZ6h3zlN9omt8`
IMP | `57F32211FAC5B8CD5CB1E6B9CCEB33E3`
PESHA1 | `C5B3AA8C6105CE0A4884AFD0F92828623F9E68CC`
PE256 | `759251F9D9C0E3FEBC44A6DA2A07647AD8717588841367A5D8D20992BBF5102A`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_IsManagementRegistrationAllowed` | 16 (0x10) | Exported Function | 0x10047b50 | 0x00047b50
`GetEnrollmentDiscoveryService` | 29 (0x1d) | Exported Function | 0x10047580 | 0x00047580
`GetEnrollmentPartnerOpaqueID` | 30 (0x1e) | Exported Function | 0x100475b0 | 0x000475b0
`GetEnrollmentSID` | 31 (0x1f) | Exported Function | 0x100475e0 | 0x000475e0
`GetEnrollmentState` | 32 (0x20) | Exported Function | 0x10047610 | 0x00047610
`GetEnrollmentType` | 33 (0x21) | Exported Function | 0x10022690 | 0x00022690
`GetEnrollmentUPN` | 34 (0x22) | Exported Function | 0x10047640 | 0x00047640
`GetEnrollmentClientContext` | 7 (0x7) | Exported Function | 0x1004a420 | 0x0004a420
`GetProviderID` | 11 (0xb) | Exported Function | 0x10047670 | 0x00047670
`OpenEnrollmentsHKEY` | 9 (0x9) | Exported Function | 0x100476a0 | 0x000476a0
`SetEnrollmentAadResourceUrl` | 8 (0x8) | Exported Function | 0x100476d0 | 0x000476d0
`SetEnrollmentAadSendDeviceToken` | 17 (0x11) | Exported Function | 0x10047700 | 0x00047700
`SetEnrollmentDormant` | 15 (0xf) | Exported Function | 0x10047730 | 0x00047730
`SetEnrollmentPartnerOpaqueID` | 36 (0x24) | Exported Function | 0x10047760 | 0x00047760
`SetEnrollmentUPN` | 13 (0xd) | Exported Function | 0x10047790 | 0x00047790
`MmpcDiscoverEndpoint` | 35 (0x23) | Exported Function | 0x100288c0 | 0x000288c0
`GetEnrollmentClientCertThumbprint` | 28 (0x1c) | Exported Function | 0x10047550 | 0x00047550
`GetEnrollmentCertStore` | 27 (0x1b) | Exported Function | 0x10047520 | 0x00047520
`GetEnrollmentAadSendDeviceToken` | 26 (0x1a) | Exported Function | 0x100474f0 | 0x000474f0
`AutoEnrollMDM` | 21 (0x15) | Exported Function | 0x10041b30 | 0x00041b30
`CleanupExpiredOMADMSessions` | 3 (0x3) | Exported Function | 0x1004b060 | 0x0004b060
`DiscoverEndpoint` | 1 (0x1) | Exported Function | 0x10028380 | 0x00028380
`DiscoverEndpointEx` | 5 (0x5) | Exported Function | 0x100284d0 | 0x000284d0
`DllCanUnloadNow` | 18 (0x12) | Exported Function | 0x100430d0 | 0x000430d0
`DllGetActivationFactory` | 19 (0x13) | Exported Function | 0x100430f0 | 0x000430f0
`DllGetClassObject` | 20 (0x14) | Exported Function | 0x10043110 | 0x00043110
`EnableLogging` | 4 (0x4) | Exported Function | 0x1004e300 | 0x0004e300
`EnrollEngineInitialize` | 22 (0x16) | Exported Function | 0x10041d40 | 0x00041d40
`FindDiscoveryService` | 2 (0x2) | Exported Function | 0x1005bc60 | 0x0005bc60
`FindDiscoveryServiceEx` | 6 (0x6) | Exported Function | 0x10028510 | 0x00028510
`FreeMmpcDiscoveryResultsData` | 23 (0x17) | Exported Function | 0x10028870 | 0x00028870
`GetCertificatePolicy` | 24 (0x18) | Exported Function | 0x1004aa80 | 0x0004aa80
`GetDatabaseManagerInstance` | 10 (0xa) | Exported Function | 0x100474b0 | 0x000474b0
`GetEnrollmentAadResourceUrl` | 25 (0x19) | Exported Function | 0x100474c0 | 0x000474c0
`SetProviderID` | 12 (0xc) | Exported Function | 0x100477c0 | 0x000477c0
`SwitchAADLinkedEnrollment` | 14 (0xe) | Exported Function | 0x100477f0 | 0x000477f0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dmEnrollEngine.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488 (WinBuild.160101.0800)
* Product Version: 10.0.19041.488
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/65
* VirusTotal Link: https://www.virustotal.com/gui/file/d7107bd364e0650e552e554e990b5e687ee68a2f90a479e331872e57f432cba7/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\mdmregistration.dll](mdmregistration.dll-740E6727C3559B75B031CCE382C0206E.md) | 36
[C:\Windows\SysWOW64\mdmregistration.dll](mdmregistration.dll-366F01C4541B73DF4836CB9B39DA9063.md) | 46




MIT License. Copyright (c) 2020 Strontic.


