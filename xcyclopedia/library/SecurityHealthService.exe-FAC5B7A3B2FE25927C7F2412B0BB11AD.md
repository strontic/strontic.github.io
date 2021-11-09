---
title: SecurityHealthService.exe | Windows Security Health Service
excerpt: What is SecurityHealthService.exe?
---

# SecurityHealthService.exe 

* File Path: `C:\WINDOWS\system32\SecurityHealthService.exe`
* Description: Windows Security Health Service

## Hashes

Type | Hash
-- | --
MD5 | `FAC5B7A3B2FE25927C7F2412B0BB11AD`
SHA1 | `0B371E7351BA129D68CE6B5ED1141109686B9A5A`
SHA256 | `1B61DA3E9192984DA05194C58518DFA1AE7306E953905995AF9F0CABF2359540`
SHA384 | `A44A78717CA02E48D9B70953452C28B1A133B86BC4060B79ED804951E3EEEAAB5A1203209AFEB760FD64D25290F896AE`
SHA512 | `515DE8F6AA4B97397B1F4FAD77A3EA3A79FE52365816F071EB51E10FE91A37DA5E3F88B926B970D7914DE86E4283CBF5571C5087F51A08241F8D6392E1AB40CF`
SSDEEP | `3072:ZUB9phuOjMRU9eZuCxJoJ6ARNGHKTeUdOEGO/NY1:eB9mOj/KzJoJ9RktfOc`
IMP | `227BBE9A58F8FF2E813854418476F593`
PESHA1 | `377F1A47CC31DFD9AF91147A18CF2D2814F15F5D`
PE256 | `7E41C5A9CD05F3EE685527D81FB219D72D67FB68411CF3523BD0186AD74C3F77`

## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SecurityHealthService.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.100 (WinBuild.160101.0800)
* Product Version: 10.0.22000.100
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1b61da3e9192984da05194c58518dfa1ae7306e953905995af9f0cabf2359540/detection


## Possible Misuse

*The following table contains possible examples of `SecurityHealthService.exe` being misused. While `SecurityHealthService.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\SecurityHealthService'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


