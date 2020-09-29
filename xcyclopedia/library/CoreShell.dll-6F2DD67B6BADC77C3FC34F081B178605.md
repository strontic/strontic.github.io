---
title: CoreShell.dll | CoreShell
excerpt: What is CoreShell.dll?
---

# CoreShell.dll 

* File Path: `C:\Windows\system32\CoreShell.dll`
* Description: CoreShell

## Hashes

Type | Hash
-- | --
MD5 | `6F2DD67B6BADC77C3FC34F081B178605`
SHA1 | `7DD766A2A6FBD5BEE00960F2F7E43D2F522C7583`
SHA256 | `8923463F70CD7DA68C8B45590F373EF30BD8DAB9AAE8BBA5AD5AAD2E41E7EEE0`
SHA384 | `B55D6D7CACA1D261ED7749F92207072B2062BDB32BEE6D261635F31EB56F1F433EA67ABB770FF198B976DBB7172F83F0`
SHA512 | `54C65E4D44BC96A6299AB762057998DAC734F122E2CBBD9938B5811942BFB2A2BD5B83D9C73509CC19975FA43112AD86F761C6AF914FB1A6E7FC8175C53AC118`
SSDEEP | `49152:dwBimC/wjvLKc+5J/1UsHTd23OOBSB9XH9A/:xBSmc+B`
IMP | `48C36E59155B0300D1A4F5D51EAC6FFB`
PESHA1 | `E534DA49DCB3B52875A402C6D808E2C64EC31383`
PE256 | `9E37B5BF804C5F2DFFD5978921751D604FC5F0D057A0DCB6CDC5C32397CD2B52`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x0000000180009bd0 | 0x00009bd0
`DllGetActivationFactory` | 2 (0x2) | Exported Function | 0x00000001800098d0 | 0x000098d0
`DllGetClassObject` | 3 (0x3) | Exported Function | 0x0000000180009ab0 | 0x00009ab0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CoreShell.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.388 (WinBuild.160101.0800)
* Product Version: 10.0.19041.388
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/8923463f70cd7da68c8b45590f373ef30bd8dab9aae8bba5ad5aad2e41e7eee0/detection/


## Possible Misuse

*The following table contains possible examples of `CoreShell.dll` being misused. While `CoreShell.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt28.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt28.yar) | $s0 = "coreshell.dll" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt28.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt28.yar) | $s0 = "coreshell.dll" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | description = "CORESHELL/SOURFACE Implant by APT28" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


