---
title: gpedit.dll | GPEdit
excerpt: What is gpedit.dll?
---

# gpedit.dll 

* File Path: `C:\Windows\SysWOW64\gpedit.dll`
* Description: GPEdit

## Hashes

Type | Hash
-- | --
MD5 | `DDB10D1903B0959367055AB0AA03E00A`
SHA1 | `9A85D1773AA4F416835DB6304B1C247B9323C915`
SHA256 | `4581983905AADBC229E91D1B1BE39591D605899BCF187C61C929188A25D15051`
SHA384 | `E0F63B49A9DCA827DF36A03A79CFD1CA5351C275D624C4D805793C8ECBC0A682D9904382991578B223D1B3F488E21426`
SHA512 | `3B45B9A2842D1644C14D1CB9A9995417CF385A5226DB4171B5E3C6C89AB8AAAA12F5EC91A7D1B096E5358882707E41F6AA875C3F41784B76B6DB2BCBBF83529B`
SSDEEP | `6144:d6SNdQWFtc0AMXUJd/z4iH3ozDcsY5DWhGjVQm21lJYZ/chJYK6y3:8U/XXUD74oSDcsBhHm21lJYZeYK6a`
IMP | `7976742F42F712E2BA609D28059C12C4`
PESHA1 | `159BE05636EA9B50E44116C1C088033A3660E4E2`
PE256 | `E9F4D3D509647F539A4FEFEE9A52DB2375DB27FB061C47DFCB71F57621486F1E`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`BrowseForGPO` | 104 (0x68) | Exported Function | 0x5f5c6770 | 0x00046770
`CreateGPOLink` | 105 (0x69) | Exported Function | 0x5f5b8820 | 0x00038820
`DeleteAllGPOLinks` | 106 (0x6a) | Exported Function | 0x5f5b8a80 | 0x00038a80
`DeleteGPOLink` | 107 (0x6b) | Exported Function | 0x5f5b8b60 | 0x00038b60
`DllCanUnloadNow` | 108 (0x6c) | Exported Function | 0x5f5b7b80 | 0x00037b80
`DllGetClassObject` | 109 (0x6d) | Exported Function | 0x5f5b7bb0 | 0x00037bb0
`ExportRSoPData` | 110 (0x6e) | Exported Function | 0x5f5c94c0 | 0x000494c0
`ImportRSoPData` | 111 (0x6f) | Exported Function | 0x5f5c8ec0 | 0x00048ec0
`Ordinal100` | 100 (0x64) | Exported Function | 0x5f5ca4a0 | 0x0004a4a0
`Ordinal101` | 101 (0x65) | Exported Function | 0x5f5ca8e0 | 0x0004a8e0
`Ordinal102` | 102 (0x66) | Exported Function | 0x5f5caaf0 | 0x0004aaf0
`Ordinal103` | 103 (0x67) | Exported Function | 0x5f5cad80 | 0x0004ad80


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gpedit.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/4581983905aadbc229e91d1b1be39591d605899bcf187c61c929188a25d15051/detection/


## Possible Misuse

*The following table contains possible examples of `gpedit.dll` being misused. While `gpedit.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_disable_event_logging.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_disable_event_logging.yml) | `description: 'Detects scenarios where system auditing (ie: windows event log auditing) is disabled. This may be used in a scenario where an entity would want to bypass local logging to evade detection when windows event logging is enabled and reviewed. Also, it is recommended to turn off "Local Group Policy Object Processing" via GPO, which will make sure that Active Directory GPOs take precedence over local/edited computer policies via something such as "gpedit.msc". Please note, that disabling "Local Group Policy Object Processing" may cause an issue in scenarios of one off specific GPO modifications -- however it is recommended to perform these modifications in Active Directory anyways.'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


