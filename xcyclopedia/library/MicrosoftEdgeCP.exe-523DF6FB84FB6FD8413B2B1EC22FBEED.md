---
title: MicrosoftEdgeCP.exe | Microsoft Edge Content Process
excerpt: What is MicrosoftEdgeCP.exe?
---

# MicrosoftEdgeCP.exe 

* File Path: `C:\WINDOWS\system32\MicrosoftEdgeCP.exe`
* Description: Microsoft Edge Content Process

## Hashes

Type | Hash
-- | --
MD5 | `523DF6FB84FB6FD8413B2B1EC22FBEED`
SHA1 | `9DC8FD03CA170C74E1C42F700550C3DD01BF256A`
SHA256 | `1EEEEF0FD28F7106AA5F23E9A5EC38E85982FAAEC892C9C9BEA67C4376EF71F1`
SHA384 | `3E3B400ABEB9F4EE0A9BC67053C9EFEC91A825C94BFF7FB1CBDAAA28AF3D5B6EC49786F6AD74501363E18569DCA740D9`
SHA512 | `02D3580A67BFA536D5EA386F1443A93BE7EF315864CD8891D88E4C34DB7253924A700AC17741C4754744245F889D5C543CE57405B4DC9C91531E76FB6B5ACF2C`
SSDEEP | `1536:IPdH7KHtys03IAcpuypCTpYJ8O8QwCINTHYr4noNVslnP8Ro:CyQhiVpSYyOlwjYMoXaP8Ro`
IMP | `72CFE4B53F527AF5F154A65EF34D5C4C`
PESHA1 | `059C907D801B21E18AE1FD08B6D7DE73241C8357`
PE256 | `93A1FE1F9E04ED5556124932E4FB3EEF8A07A5691168F37EA3AAAEAF3D7C7549`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MicrosoftEdgeCP.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeCP.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.22000.1 (WinBuild.160101.0800)
* Product Version: 11.00.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1eeeef0fd28f7106aa5f23e9a5ec38e85982faaec892c9c9bea67c4376ef71f1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\MicrosoftEdgeBCHost.exe](MicrosoftEdgeBCHost.exe-523DF6FB84FB6FD8413B2B1EC22FBEED.md) | 100
[C:\WINDOWS\system32\MicrosoftEdgeDevTools.exe](MicrosoftEdgeDevTools.exe-523DF6FB84FB6FD8413B2B1EC22FBEED.md) | 100

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_vhd_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_vhd_download.yml) | `- microsoftedgecp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedgecp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


