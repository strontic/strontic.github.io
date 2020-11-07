---
title: samcli.dll | Security Accounts Manager Client DLL
excerpt: What is samcli.dll?
---

# samcli.dll 

* File Path: `C:\Windows\SysWOW64\samcli.dll`
* Description: Security Accounts Manager Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `D22D42C4D6BDF0A1B96A59F6540BCC5C`
SHA1 | `0E7BFEDDCA1FD2577CF70B2DD526F513FF9980C7`
SHA256 | `54C1E5FDE7995EAE47F77F31067DE065AF3EB097233A601DB8D754BA8AAF7B2C`
SHA384 | `21184D24B5CCD5C033305C160CA21414B24B30853A73468BC20192297F77CE8973CBB250AB1F1BC3F3B66B88FEA49BCB`
SHA512 | `242C1273DADAD8FBB2507EE2251B145877A905CFAC5A52265868E7913596DEEECA0A8C6058DC460535F5A6166051D00E654B934DB89B9CAEF022EB35F411424B`
SSDEEP | `1536:Q4zLkDoUu33D96+pvdQPEgcjvDZn1FbSztBIlrHSlbsd5:Q4z4DgHD4+vd2sjvDZaclrHco`
IMP | `C930C3C276E75A1DEBDE90CD31EBCFBC`
PESHA1 | `81A2CF5B69AA28732287B7907FD5A4B3169E1134`
PE256 | `067E1DA64D2CB376A38AA4A48A59D53BE8394915B3A910AEDEDC79D536A890EC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`NetGetDisplayInformationIndex` | 1 | Exported Function
`NetLocalGroupSetMembers` | 21 | Exported Function
`NetQueryDisplayInformation` | 22 | Exported Function
`NetUserAdd` | 23 | Exported Function
`NetUserChangePassword` | 24 | Exported Function
`NetUserDel` | 25 | Exported Function
`NetUserEnum` | 26 | Exported Function
`NetLocalGroupSetInfo` | 20 | Exported Function
`NetUserGetGroups` | 27 | Exported Function
`NetUserGetInternetIdentityInfo` | 29 | Exported Function
`NetUserGetLocalGroups` | 30 | Exported Function
`NetUserModalsGet` | 31 | Exported Function
`NetUserModalsSet` | 32 | Exported Function
`NetUserSetGroups` | 33 | Exported Function
`NetUserSetInfo` | 34 | Exported Function
`NetUserGetInfo` | 28 | Exported Function
`NetLocalGroupGetMembers` | 19 | Exported Function
`NetLocalGroupGetInfo` | 18 | Exported Function
`NetLocalGroupEnum` | 17 | Exported Function
`NetGroupAdd` | 2 | Exported Function
`NetGroupAddUser` | 3 | Exported Function
`NetGroupDel` | 4 | Exported Function
`NetGroupDelUser` | 5 | Exported Function
`NetGroupEnum` | 6 | Exported Function
`NetGroupGetInfo` | 7 | Exported Function
`NetGroupGetUsers` | 8 | Exported Function
`NetGroupSetInfo` | 9 | Exported Function
`NetGroupSetUsers` | 10 | Exported Function
`NetLocalGroupAdd` | 11 | Exported Function
`NetLocalGroupAddMember` | 12 | Exported Function
`NetLocalGroupAddMembers` | 13 | Exported Function
`NetLocalGroupDel` | 14 | Exported Function
`NetLocalGroupDelMember` | 15 | Exported Function
`NetLocalGroupDelMembers` | 16 | Exported Function
`NetValidatePasswordPolicy` | 35 | Exported Function
`NetValidatePasswordPolicyFree` | 36 | Exported Function


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/54c1e5fde7995eae47f77f31067de065af3eb097233a601db8d754ba8aaf7b2c/detection/


## Possible Misuse

*The following table contains possible examples of `samcli.dll` being misused. While `samcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [part1.adoc](https://github.com/eset/malware-ioc/blob/master/sednit/part1.adoc) | `api-ms-win-samcli-dnsapi-0-0-0.dll` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


