---
title: MicrosoftEdgeCP.exe | Microsoft Edge Content Process
excerpt: What is MicrosoftEdgeCP.exe?
---

# MicrosoftEdgeCP.exe 

* File Path: `C:\Windows\system32\MicrosoftEdgeCP.exe`
* Description: Microsoft Edge Content Process

## Hashes

Type | Hash
-- | --
MD5 | `3FAE70080E7D900A469355C85ADACBDB`
SHA1 | `DEA5960571532F73D886F5DD79B0F7EED6F10582`
SHA256 | `34B6D32D2345DB5DFE803573F4AA74479EA961004B2F72D25A486D55369AECD8`
SHA384 | `A0AC924BDB2BC8B264BE59D9A3C29B7A511D0BB1A603319215849FDFC589F8A61A19248E3256A0CBC2EFD913A67B2E01`
SHA512 | `C8909FAD5F3FCEAB7A825C30B033844645E49F171C285A560CF8E0DFD0D848356B8E2CC0DF8019E42B1EFE69623B715BF3237D7DD42D3EC63A462D2682711ABD`
SSDEEP | `1536:zermIcat/7LnbR8l/DNRo04HwnVC8AknP8RsK:zeryK3V8l/804oV3TP8Rs`
IMP | `0D3AB4A466B72F3ECB4D7E053A19134B`
PESHA1 | `DA7999586252647430728A1B6E2F7027596B0256`
PE256 | `DD31F49F1D8F63BC55BAFF847A74D28C6D0408298B0E211B48CA5AE03E36F7B4`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MicrosoftEdgeCP.exe |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\WINTRUST.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeCP.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.17763.1 (WinBuild.160101.0800)
* Product Version: 11.00.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/34b6d32d2345db5dfe803573f4aa74479ea961004b2f72d25a486d55369aecd8/detection/


## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedgecp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


