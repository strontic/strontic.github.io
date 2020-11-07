---
title: cmlua.dll | Connection Manager Admin API Helper
excerpt: What is cmlua.dll?
---

# cmlua.dll 

* File Path: `C:\Windows\SysWOW64\cmlua.dll`
* Description: Connection Manager Admin API Helper

## Hashes

Type | Hash
-- | --
MD5 | `982150AE441158CD3226E4BFF758F320`
SHA1 | `536F60DA7DB4EB0EE19863405BE59A10F73913A4`
SHA256 | `84D354B08008323DADCE6A62746DB4D08ED09670A2A69636E452EEB87C0C8289`
SHA384 | `C9D6AD71AF9B964AA01425E052FFBDABD68B652004012CDDEC696767ECC4AE38CCD77984BE5A326FD05BC7A9B69BB23C`
SHA512 | `92C517F7BA4FECF1CB68E092F8AC6F63D8721D186D5195701DEB7A1A6029FEE4E54B54A026FEC618937F376F302029309F42FC77FE0C5D1741B594F4DEC344FD`
SSDEEP | `384:Q3Oq518hQpkEqBl8494q8LgrQiI6Nfuym1T8BjZW+drNKIOqrpqr8X/8rAtWgYWI:Q1518WFi9NJfuRyBV0qFqwUinqZ`
IMP | `3A0A431DAB919A456D2102D837D6D274`
PESHA1 | `1879F17775DA45A940774D57D0B6C14775ED21BC`
PE256 | `CA4786D3F2ED4E45CFABCA47C0A57C3CD141B56400DADF7F799667BBEA8AD1E6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`_GetCoCreateInstanceAsAdminHandle` | 6 | Exported Function
`_RemoveShieldIcon` | 7 | Exported Function
`_SetShieldButton` | 8 | Exported Function
`_SetShieldIcon` | 9 | Exported Function
`_ThrowErrorBox` | 10 | Exported Function
`DllAddRef` | 1 | Exported Function
`DllCanUnloadNow` | 2 | Exported Function
`DllGetClassObject` | 3 | Exported Function
`DllMain` | 4 | Exported Function
`DllRelease` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CMLUA.DLL.MUI
* Product Name: Microsoft(R) Connection Manager
* Company Name: Microsoft Corporation
* File Version: 7.2.19041.1 (WinBuild.160101.0800)
* Product Version: 7.2.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/84d354b08008323dadce6a62746db4d08ed09670a2a69636e452eeb87c0c8289/detection/


## Possible Misuse

*The following table contains possible examples of `cmlua.dll` being misused. While `cmlua.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


