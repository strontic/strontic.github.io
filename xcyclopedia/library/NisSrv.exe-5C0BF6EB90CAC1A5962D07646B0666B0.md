﻿---
title: NisSrv.exe | Microsoft Network Realtime Inspection Service
excerpt: What is NisSrv.exe?
---

# NisSrv.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2001.10-0\NisSrv.exe`
* Description: Microsoft Network Realtime Inspection Service

## Hashes

Type | Hash
-- | --
MD5 | `5C0BF6EB90CAC1A5962D07646B0666B0`
SHA1 | `CB506AA96F06F35BAA46B2E19626C18E1C235564`
SHA256 | `A9C1546530183F9AF38F38ADAA531DF514E1E35EB62FC289D7F7AF27551D1979`
SHA384 | `05D0FE53592BBB78070BC1CA40BE42E04D91EACDED594AFAF9AA8EE53CE63B176086240D30B9D5BC872A8D6554C76DE2`
SHA512 | `3A811894467E8BAFD77F1028C269B15AEF38A7E48DABACE4A0EA1AE9E4F50C26824C5DC7F9E1C9941782CF7CB3A4B3C8E4CA0A2829C59BBAB283E3BAC8043E22`
SSDEEP | `49152:2k5mE897MNoMDbRTbkLIOjVvNwWZQ+RzUM6yC8r37Uncpgt:DcEgF2W6+FUqr37Tpgt`

## Signature

* Status: Signature verified.
* Serial: `3300000216CA389B93E0C73695000000000216`
* Thumbprint: `7D827CF26BD7A3AFA75051801568E35191389BF5`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NisSrv.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2001.10 (WinBuild.160101.0800)
* Product Version: 4.18.2001.10
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2004.6-0\NisSrv.exe](NisSrv.exe-D6404DFDB734E1990E35A2BD1808C08A.md) | 32

## Possible Misuse

*The following table contains possible examples of `NisSrv.exe` being misused. While `NisSrv.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_reg_disable_sec_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_reg_disable_sec_services.yml) | `- '\NisSrv'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


