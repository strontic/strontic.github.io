---
title: srvcli.dll | Server Service Client DLL
excerpt: What is srvcli.dll?
---

# srvcli.dll 

* File Path: `C:\Windows\SysWOW64\srvcli.dll`
* Description: Server Service Client DLL

## Hashes

Type | Hash
-- | --
MD5 | `E94F5E89F42683AA1889F4CF83771439`
SHA1 | `A8722949A3FDDF3873567BB1F9F2AE19C21B12B0`
SHA256 | `A876A53AFB9009E5AB2DA08AAA8C466BFD94D76C6C634D2917CBBB012F8AD341`
SHA384 | `8DC17533D38793BE5480768BAC4E6BC1CF5249C1B476F0951CFD439209F2C9F99947743A7F67D7203B83184C607066BC`
SHA512 | `D8CD7A407F1F470732E793D7426A6CE1CA3A23083FE8A47AD2BBA1EF07B9B41D5A950BB099670A705B5EB2B8F69F384AB835340BD0CDF0F5D061AC47D210B9A1`
SSDEEP | `1536:cGxNMGTSQgdRsY19tx9YPP5fY4Y4Bs95i/y2POuuY:cdGrgDsYNYH5fY4rY5Wy22LY`
IMP | `70155BAF488DED515319D30C8191E3D0`
PESHA1 | `77A3B956C5A2DDEB3529EC80489D0B2433D92F78`
PE256 | `0D571BB2A456D14A7B6EFCEE0C3E159C7F8F80C6D81CECEC552AC739A42B676F`

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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/a876a53afb9009e5ab2da08aaa8c466bfd94d76c6c634d2917cbbb012f8ad341/detection/


## Possible Misuse

*The following table contains possible examples of `srvcli.dll` being misused. While `srvcli.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_mimikatz_inmemory_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_mimikatz_inmemory_detection.yml) | `- 'srvcli.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


