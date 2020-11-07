---
title: srvcli.dll | Server Service Client DLL
excerpt: What is srvcli.dll?
---

# srvcli.dll 

* File Path: `C:\Windows\system32\srvcli.dll`
* Description: Server Service Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `E945938D33A3A7667D1F551D08125168`
SHA1 | `E8BE342F5E005F464C577951AE4F0BB4751C85ED`
SHA256 | `16CAE239912A5FF886D0408C7B44C91136EDBB32D39A9CBBCD1BCA5A081DC10B`
SHA384 | `9EA0A56D93AFC9F35508B8680083DE85D35526EF8670DA952295900722211222FEF36912A49B11FC214891D54EE557BB`
SHA512 | `383E500C3E6D78DC35A877B141F2BC256CA566860CADEADA6B01C533B9A5EE5F4914F7F893ADACF78504C927F6E06EC7E72D6175F1FCEBB1281A6B8F725BF9FD`
SSDEEP | `3072:DpaVg+ksoXFLt+KMdIjGufXXW4yDP/X7hK6Ovc:IVg+ksoXFLlRfXXW4yDPf7h0c`
IMP | `A09FF3616CBB41B2263E0AEA182A8311`
PESHA1 | `624E812A2F9735F8121D493A62DA132265FA7057`
PE256 | `55568296C99772F47001D7BB153C8175BC6370D501A8B34ADA4E6CCCB016B0C7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`I_NetDfsGetVersion` | 1 | Exported Function
`NetpsPathCanonicalize` | 59 | Exported Function
`NetpsPathCompare` | 60 | Exported Function
`NetpsPathType` | 61 | Exported Function
`NetRemoteTOD` | 30 | Exported Function
`NetServerAliasAdd` | 31 | Exported Function
`NetServerAliasDel` | 32 | Exported Function
`NetServerAliasEnum` | 33 | Exported Function
`NetServerComputerNameAdd` | 34 | Exported Function
`NetServerComputerNameDel` | 35 | Exported Function
`NetServerDiskEnum` | 36 | Exported Function
`NetServerGetInfo` | 37 | Exported Function
`NetServerSetInfo` | 38 | Exported Function
`NetServerStatisticsGet` | 39 | Exported Function
`NetServerTransportAdd` | 40 | Exported Function
`NetServerTransportAddEx` | 41 | Exported Function
`NetServerTransportDel` | 42 | Exported Function
`NetServerTransportEnum` | 43 | Exported Function
`NetSessionDel` | 44 | Exported Function
`NetSessionEnum` | 45 | Exported Function
`NetSessionGetInfo` | 46 | Exported Function
`NetShareAdd` | 47 | Exported Function
`NetShareCheck` | 48 | Exported Function
`NetShareDel` | 49 | Exported Function
`NetShareDelEx` | 50 | Exported Function
`NetShareDelSticky` | 51 | Exported Function
`NetShareEnum` | 52 | Exported Function
`NetShareEnumSticky` | 53 | Exported Function
`NetpsNameValidate` | 58 | Exported Function
`NetShareGetInfo` | 54 | Exported Function
`NetpsNameCompare` | 57 | Exported Function
`NetFileGetInfo` | 29 | Exported Function
`I_NetServerSetServiceBits` | 2 | Exported Function
`I_NetServerSetServiceBitsEx` | 3 | Exported Function
`LocalAliasGet` | 4 | Exported Function
`LocalFileClose` | 5 | Exported Function
`LocalFileEnum` | 6 | Exported Function
`LocalFileEnumEx` | 7 | Exported Function
`LocalFileGetInfo` | 8 | Exported Function
`LocalFileGetInfoEx` | 9 | Exported Function
`LocalServerCertificateMappingAdd` | 10 | Exported Function
`LocalServerCertificateMappingEnum` | 11 | Exported Function
`LocalServerCertificateMappingGet` | 12 | Exported Function
`LocalServerCertificateMappingRemove` | 13 | Exported Function
`LocalSessionDel` | 14 | Exported Function
`LocalSessionEnum` | 15 | Exported Function
`LocalSessionEnumEx` | 16 | Exported Function
`LocalSessionGetInfo` | 17 | Exported Function
`LocalSessionGetInfoEx` | 18 | Exported Function
`LocalShareAdd` | 19 | Exported Function
`LocalShareDelEx` | 20 | Exported Function
`LocalShareEnum` | 21 | Exported Function
`LocalShareEnumEx` | 22 | Exported Function
`LocalShareGetInfo` | 23 | Exported Function
`LocalShareGetInfoEx` | 24 | Exported Function
`LocalShareSetInfo` | 25 | Exported Function
`NetConnectionEnum` | 26 | Exported Function
`NetFileClose` | 27 | Exported Function
`NetFileEnum` | 28 | Exported Function
`NetpsNameCanonicalize` | 56 | Exported Function
`NetShareSetInfo` | 55 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SRVCLI.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/16cae239912a5ff886d0408c7b44c91136edbb32d39a9cbbcd1bca5a081dc10b/detection/


## Possible Misuse

*The following table contains possible examples of `srvcli.dll` being misused. While `srvcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'srvcli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


