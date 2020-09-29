---
title: InstallService.dll | InstallService
excerpt: What is InstallService.dll?
---

# InstallService.dll 

* File Path: `C:\Windows\system32\InstallService.dll`
* Description: InstallService

## Hashes

Type | Hash
-- | --
MD5 | `717AE463E153F90DBAE5F9B6D2769E93`
SHA1 | `D799F1719E2025D0356BB3F5B0E66C9BE45C068F`
SHA256 | `0C65249900ABE37FDC674DDB7B6F071650EB4990915E3F98AEF511CD91652B88`
SHA384 | `23D9ADFBBAF5343CF0298C7C3B301DE2B4D11DBADDD7AA743777ACFEBC0B9A93FE8E89CE2F447329FA6EF6D7EC487CE2`
SHA512 | `7ED2C6C48028DEBCBDFD0D960EDA065AED2BDFC2CF957EFA1240CC119D5C353EBFA365AB2E722696E508BDA606347F6AC164D943BD735AE89498BEFD580D84B6`
SSDEEP | `24576:dvPRVpFCpbvfi909mcoiIEfebSwc8JQmPJ8WxG77nN4r3n3mj/7BeOihEgUb1Qm:dvPRnMb8Ko5ywc8JQm6WwXnNK4dw2BD`
IMP | `5C59E21C071F53BE38A3A7D8125C6D48`
PESHA1 | `99D78481D702C126E5957E37708E178BF664E7A2`
PE256 | `5E7680E2F5761724975B9EB57B70D6FC8E21D8F17E4A3DFA2A24D40C7A839B93`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 2 (0x2) | Exported Function | 0x00000001800094f0 | 0x000094f0
`DllGetActivationFactory` | 3 (0x3) | Exported Function | 0x0000000180009660 | 0x00009660
`DllGetClassObject` | 4 (0x4) | Exported Function | 0x0000000180009530 | 0x00009530
`ServiceMain` | 1 (0x1) | Exported Function | 0x000000018000a5b0 | 0x0000a5b0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: InstallService.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/0c65249900abe37fdc674ddb7b6f071650eb4990915e3f98aef511cd91652b88/detection/


## Possible Misuse

*The following table contains possible examples of `InstallService.dll` being misused. While `InstallService.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "InstallService" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


