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
MD5 | `1472361DB9BC28F6C4CB327FE5E35393`
SHA1 | `5675BF13004943DEBD19A6B1CAD3707076CD2A2B`
SHA256 | `91A954FECD74F20B4A25708D7323E64FB4DD4E03997BCF234E7B810F9EB03A95`
SHA384 | `2BB29A5C674127BF2AEE4091240E22B889B90C4A4B50E9C7D5915B88E6DA08D0FB9DB592D8964C81A894809FBABD657A`
SHA512 | `B3675480F4B234098B485A7F63799BD95877C879E85456D4FCF9EAC3CC2FD6C7383AF7419E0BE8297289B3C577839E046B343E18B655EADD184501117D1C13AB`
SSDEEP | `1536:pIYH0romDAy7+O0eNz2sRZjDM0Q1/UqjbB877rnjrd1nP8RX:pI7omcy17kf0Qy7/jpVP8RX`
IMP | `CCC8877CD76F451BC5955A4881A228DF`
PESHA1 | `A25347CEA622305D99259E6E26FDE44DEA31ED1A`
PE256 | `4D2C6A7DDA1533B6995EBFD587717D298BB0E7C5EB5734D7FD97352E074B1C63`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\apphelp.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MicrosoftEdgeCP.exe |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MicrosoftEdgeCP.exe
* Product Name: Microsoft Edge Web Platform
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/91a954fecd74f20b4a25708d7323e64fb4dd4e03997bcf234e7b810f9eb03a95/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\MicrosoftEdgeBCHost.exe](MicrosoftEdgeBCHost.exe-1472361DB9BC28F6C4CB327FE5E35393.md) | 100
[C:\Windows\system32\MicrosoftEdgeDevTools.exe](MicrosoftEdgeDevTools.exe-1472361DB9BC28F6C4CB327FE5E35393.md) | 100

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [file_event_mal_vhd_download.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/file_event_mal_vhd_download.yml) | `- microsoftedgecp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `- '\microsoftedgecp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


