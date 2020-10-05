---
title: samcli.dll | Security Accounts Manager Client DLL
excerpt: What is samcli.dll?
---

# samcli.dll 

* File Path: `C:\Windows\system32\samcli.dll`
* Description: Security Accounts Manager Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `522D6D616EF142CDE965BD3A450A9E4C`
SHA1 | `2EDABFABFA8066C587AFF1F5C731B9A020F9C934`
SHA256 | `954A0310315E9CC58916A619D3BCD82C607C4925E87034D59F4CD22A0118FD09`
SHA384 | `F92333A63326860D593F4F57B2DBFD14BF8971418FDE705FD2079ECF7E7A968E9EE6B7AEE708E33D6A99705FCD2B52A6`
SHA512 | `D17C06C6150F3406688DA64AD911DBA17DE71F4CA30A7EFC11D8FB0E918DB9B5BB17F349E4AA9592D1C63F22ACBC6AA9E8C3AB8A25466AFAFA941E2A77E58B57`
SSDEEP | `1536:LpGdBAtLXG9c2h0qNYgUbYYTzwc/g3+asq1P7SKsd:LpTS9JJY5YYTzz/g3+M70`
IMP | `85D6E08968ADBF425E9BB17AC987F7AC`
PESHA1 | `DD55ECA37492E8375D8F61F317C53C93BF63940C`
PE256 | `DDFB99C3426D586D2673FEB1C20885398F5820398060D48E7E7A0217232B0FD6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`NetUserDel` | 25 | Exported Function
`NetUserChangePassword` | 24 | Exported Function
`NetUserGetGroups` | 27 | Exported Function
`NetUserEnum` | 26 | Exported Function
`NetUserAdd` | 23 | Exported Function
`NetLocalGroupSetInfo` | 20 | Exported Function
`NetLocalGroupGetMembers` | 19 | Exported Function
`NetQueryDisplayInformation` | 22 | Exported Function
`NetLocalGroupSetMembers` | 21 | Exported Function
`NetUserSetInfo` | 34 | Exported Function
`NetUserSetGroups` | 33 | Exported Function
`NetValidatePasswordPolicyFree` | 36 | Exported Function
`NetValidatePasswordPolicy` | 35 | Exported Function
`NetUserModalsSet` | 32 | Exported Function
`NetUserGetInternetIdentityInfo` | 29 | Exported Function
`NetUserGetInfo` | 28 | Exported Function
`NetUserModalsGet` | 31 | Exported Function
`NetUserGetLocalGroups` | 30 | Exported Function
`NetGroupGetInfo` | 7 | Exported Function
`NetGroupEnum` | 6 | Exported Function
`NetGroupSetInfo` | 9 | Exported Function
`NetGroupGetUsers` | 8 | Exported Function
`NetGroupDelUser` | 5 | Exported Function
`NetGroupAdd` | 2 | Exported Function
`NetGetDisplayInformationIndex` | 1 | Exported Function
`NetGroupDel` | 4 | Exported Function
`NetGroupAddUser` | 3 | Exported Function
`NetLocalGroupDelMembers` | 16 | Exported Function
`NetLocalGroupDelMember` | 15 | Exported Function
`NetLocalGroupGetInfo` | 18 | Exported Function
`NetLocalGroupEnum` | 17 | Exported Function
`NetLocalGroupDel` | 14 | Exported Function
`NetLocalGroupAdd` | 11 | Exported Function
`NetGroupSetUsers` | 10 | Exported Function
`NetLocalGroupAddMembers` | 13 | Exported Function
`NetLocalGroupAddMember` | 12 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SAMCLI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/954a0310315e9cc58916a619d3bcd82c607c4925e87034d59f4cd22a0118fd09/detection/


## Possible Misuse

*The following table contains possible examples of `samcli.dll` being misused. While `samcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `api-ms-win-samcli-dnsapi-0-0-0.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


