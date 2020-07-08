---
title: wlanext.exe | Windows Wireless LAN 802.11 Extensibility Framework
---

# wlanext.exe 

* File Path: `C:\WINDOWS\system32\wlanext.exe`
* Description: Windows Wireless LAN 802.11 Extensibility Framework

## Hashes

Type | Hash
-- | --
MD5 | `7D6D8EEED2C7422683301AA560A0135A`
SHA1 | `30ADC03D5D1E93A6C20F665E6D6DB821C92BDD77`
SHA256 | `D70707B830B7A0A4683CA2169328131A385DA0F859B96704653D59C6AFAE04AD`
SHA384 | `225A4CC120CF8A5E01EC25C8578AF6020252614A811BC153D8BD198489D5EE358E26A187F1F7666FE477A1258BBB146F`
SHA512 | `A0ADB083966BFBCAF8B236D81C3D602F2C9946295476417DEDCD66489C6568E16D854C2CE87AB14F0BCACA51CF3EE84CC862A0D850A94CB491FC12794E9A742F`
SSDEEP | `1536:PfiNEpsbvoQy69JM6RafbepzL66p1RCv2u9LO8rReuFG44JB3/bOuTl:3iNEyTUbepzTNqLO8rReu61f5`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wlanext.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `wlanext.exe` being misused. While `wlanext.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\wlanext.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


