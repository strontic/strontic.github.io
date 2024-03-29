﻿---
title: MicrosoftEdgeCP.exe | Microsoft Edge Content Process
excerpt: What is MicrosoftEdgeCP.exe?
---

# MicrosoftEdgeCP.exe 

* File Path: `C:\WINDOWS\system32\MicrosoftEdgeCP.exe`
* Description: Microsoft Edge Content Process

## Hashes

Type | Hash
-- | --
MD5 | `0E954887FC791F668CE388F89BC3D6C6`
SHA1 | `ECB05717E416D965255387F4EDC196889AA12C67`
SHA256 | `EE7174EE353E7D29CE17D29D66411B3623C39D9DEC3F439E35AF47A7E7A7C895`
SHA384 | `871D1DBFE438393CD972E13AD1A36034985F813E4258A57BCE1F212D02252ABC3880D851E994C4FA4291F2182639D2CD`
SHA512 | `19D81B619A111E9CF10E48E0F7EA27878F192DDD14A39A0F69AE7A7084406AA22C8CA1932B719E665E89F50A4AD03FE67E4B954947C63D56A9F7E790F5C0E220`
SSDEEP | `1536:nnadCUC/KixG5bPc33lj8yC2aj+7KxxL2/m4nVrs6FhnP8Ru:nndL85gFjt1a6W2/tVg6F5P8Ru`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeCP.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.18362.1 (WinBuild.160101.0800)
* Product Version: 11.00.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\MicrosoftEdgeBCHost.exe](MicrosoftEdgeBCHost.exe-0E954887FC791F668CE388F89BC3D6C6.md) | 100
[C:\WINDOWS\system32\MicrosoftEdgeDevTools.exe](MicrosoftEdgeDevTools.exe-0E954887FC791F668CE388F89BC3D6C6.md) | 100

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_vhd_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_vhd_download.yml) | `- microsoftedgecp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedgecp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


