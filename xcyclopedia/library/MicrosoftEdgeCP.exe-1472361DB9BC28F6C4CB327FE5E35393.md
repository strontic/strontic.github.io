---
title: MicrosoftEdgeCP.exe | Microsoft Edge Content Process
---

# MicrosoftEdgeCP.exe 

* File Path: `C:\Windows\system32\MicrosoftEdgeCP.exe`
* Description: Microsoft Edge Content Process
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1472361DB9BC28F6C4CB327FE5E35393`
SHA1 | `5675BF13004943DEBD19A6B1CAD3707076CD2A2B`
SHA256 | `91A954FECD74F20B4A25708D7323E64FB4DD4E03997BCF234E7B810F9EB03A95`
SHA384 | `2BB29A5C674127BF2AEE4091240E22B889B90C4A4B50E9C7D5915B88E6DA08D0FB9DB592D8964C81A894809FBABD657A`
SHA512 | `B3675480F4B234098B485A7F63799BD95877C879E85456D4FCF9EAC3CC2FD6C7383AF7419E0BE8297289B3C577839E046B343E18B655EADD184501117D1C13AB`
SSDEEP | `1536:pIYH0romDAy7+O0eNz2sRZjDM0Q1/UqjbB877rnjrd1nP8RX:pI7omcy17kf0Qy7/jpVP8RX`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\MicrosoftEdgeBCHost.exe](MicrosoftEdgeBCHost.exe-1472361DB9BC28F6C4CB327FE5E35393.md) | 100
[C:\Windows\system32\MicrosoftEdgeDevTools.exe](MicrosoftEdgeDevTools.exe-1472361DB9BC28F6C4CB327FE5E35393.md) | 100

## Possible Misuse

*The following table contains possible examples of `MicrosoftEdgeCP.exe` being misused. While `MicrosoftEdgeCP.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_powershell_parent_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_powershell_parent_process.yml) | `            - '\microsoftedgecp.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


