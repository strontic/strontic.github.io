---
title: dsparse.dll | Active Directory Domain Services API
excerpt: What is dsparse.dll?
---

# dsparse.dll 

* File Path: `C:\Windows\SysWOW64\dsparse.dll`
* Description: Active Directory Domain Services API

## Hashes

Type | Hash
-- | --
MD5 | `148047C7E90558ECC092F2D46F370CB3`
SHA1 | `B0D30169236D0F002622ADABEB0D92700DD91236`
SHA256 | `77DB2B5DA00CAF38275B617A5C89D691219426FD2FE66696981CAE7591D548E8`
SHA384 | `68D5C07AD2C855E4BBFEF209F7A1656239C12983AAC5FE7EB8F2CE8E0F250CC47A8699089403A6FB6D1BE42EC4E7E3D7`
SHA512 | `0E281897C52F53918C10646EE204B38F30F2B83C3BD89984CC8CA745A2B960A2D9678FC3D541959C68E71916C20FBFCDB3A81D09CF423A13685EAD7EC554F063`
SSDEEP | `384:7eWbP6Ucdg0kI2lH+LB265Gbr18pl6js0D5u7nnev5x3eIp+lvZuWRTW:7RWXUH5Cng8nK5xOo+xZh`
IMP | `AE6B1186EC8181CBE320D8D73D84A7C0`
PESHA1 | `0D27B4F898B00F50D561293064C190857FB3C2B1`
PE256 | `209380DA9CAF4B6BDA94DB62D545CC6E36B324DFE5A164AD2E50E212DBF94A3E`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DsMakeSpn2W` | 14 | Exported Function
`DsMakeSpnA` | 15 | Exported Function
`DsIsMangledRdnValueW` | 13 | Exported Function
`DsIsMangledDnW` | 11 | Exported Function
`DsIsMangledRdnValueA` | 12 | Exported Function
`DsUnquoteRdnValueA` | 19 | Exported Function
`DsUnquoteRdnValueW` | 20 | Exported Function
`DsQuoteRdnValueW` | 18 | Exported Function
`DsMakeSpnW` | 16 | Exported Function
`DsQuoteRdnValueA` | 17 | Exported Function
`DsCrackSpn4W` | 4 | Exported Function
`DsCrackSpnA` | 5 | Exported Function
`DsCrackSpn3W` | 3 | Exported Function
`DsCrackSpn2A` | 1 | Exported Function
`DsCrackSpn2W` | 2 | Exported Function
`DsGetRdnW` | 9 | Exported Function
`DsIsMangledDnA` | 10 | Exported Function
`DsCrackUnquotedMangledRdnW` | 8 | Exported Function
`DsCrackSpnW` | 6 | Exported Function
`DsCrackUnquotedMangledRdnA` | 7 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsparse.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/77db2b5da00caf38275b617a5c89d691219426fd2fe66696981cae7591d548e8/detection/


## Possible Misuse

*The following table contains possible examples of `dsparse.dll` being misused. While `dsparse.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_office_dsparse_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_office_dsparse_dll_load.yml) | `description: Detects DSParse DLL being loaded by an Office Product` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_office_dsparse_dll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_office_dsparse_dll_load.yml) | `- '*\dsparse.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


