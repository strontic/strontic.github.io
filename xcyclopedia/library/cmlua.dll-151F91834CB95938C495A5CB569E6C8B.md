---
title: cmlua.dll | Connection Manager Admin API Helper
excerpt: What is cmlua.dll?
---

# cmlua.dll 

* File Path: `C:\Windows\system32\cmlua.dll`
* Description: Connection Manager Admin API Helper

## Hashes

Type | Hash
-- | --
MD5 | `151F91834CB95938C495A5CB569E6C8B`
SHA1 | `B39D7F63F4888CCB21DD1739C7508891EF4B5C2D`
SHA256 | `D00D1C5FE0268B650ABB16F3D66B469C049066E8C0508DF64801749D09F312A4`
SHA384 | `8D2A07DEE0792F4E9E790BDB2A9216E3C3B96E2E4388B35EC7CFB5399DB332171AA497A25E2B700940F5BF2BE0CF0CEE`
SHA512 | `344FE1DFDE5EF3E5A643F8DAAC72AB68114B660E710D838B5EEF9621CC2E2AC87E69557C97FD7A0E1615F882771507C73147DF2BD14C7BBA09BDE678A303DF67`
SSDEEP | `768:GAE/7oBqW63EdOZMzgzgsDBAGc95tWMOAOBqBm5VMoZxzPqvblZtn:Gr/7BEdOZMzgzgsBAGc92BFBqBm5VMe+`
IMP | `3514D3EDF9CCCD1F3C1737C8DDE6A257`
PESHA1 | `1A3AC7C853C083AC3F077892CC7F5A4D5E2923CC`
PE256 | `84450AE0015E74180E97C6632940AC31FE03738C6924B31266AA291C2CF83532`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`_GetCoCreateInstanceAsAdminHandle` | 6 (0x6) | Exported Function | 0x00000001800012f0 | 0x000012f0
`_RemoveShieldIcon` | 7 (0x7) | Exported Function | 0x00000001800014b0 | 0x000014b0
`_SetShieldButton` | 8 (0x8) | Exported Function | 0x00000001800014f0 | 0x000014f0
`_SetShieldIcon` | 9 (0x9) | Exported Function | 0x0000000180001410 | 0x00001410
`_ThrowErrorBox` | 10 (0xa) | Exported Function | 0x0000000180001260 | 0x00001260
`DllAddRef` | 1 (0x1) | Exported Function | 0x00000001800010f0 | 0x000010f0
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x0000000180001110 | 0x00001110
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x0000000180001150 | 0x00001150
`DllMain` | 4 (0x4) | Exported Function | 0x00000001800010c0 | 0x000010c0
`DllRelease` | 5 (0x5) | Exported Function | 0x0000000180001100 | 0x00001100


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d00d1c5fe0268b650abb16f3d66b469c049066e8c0508df64801749d09f312a4/detection/


## Possible Misuse

*The following table contains possible examples of `cmlua.dll` being misused. While `cmlua.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_cmstp_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_cmstp_execution.yml) | `CallTrace: '*cmlua.dll*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


