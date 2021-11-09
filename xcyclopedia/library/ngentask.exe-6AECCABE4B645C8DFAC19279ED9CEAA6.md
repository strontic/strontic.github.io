---
title: ngentask.exe | Microsoft .NET Framework optimization service
excerpt: What is ngentask.exe?
---

# ngentask.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ngentask.exe`
* Description: Microsoft .NET Framework optimization service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `6AECCABE4B645C8DFAC19279ED9CEAA6`
SHA1 | `2E89B75E1CEF5C1705869E4F2DE51D331886D16C`
SHA256 | `999AF53DE73A2C4F0CDB8D9A19ED29D03827F89AA0F4533BB9C2D54E9B7A2137`
SHA384 | `20986D10BA9E8B48F25223340C8E90A3B1A555310D9B9C20C890726A5C65B141EC09A6156DF2534FE1773AB3D58A68F9`
SHA512 | `C370B7F7846B9E02CB9C52B3DB0AE75250B0D5C3167E164D00BEF6F706B29E598A1EF7B819F6C92E626D2F718D6BFB73FC0E3B3B2F85A000873157A1703DDAA8`
SSDEEP | `1536:lHbMtCb5ZAP889Z9Qqw8NsbcpKs8fnFdLnfHa:dUCbg88reyp98fFhf6`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `ED16471CAD67127C42A83711D6D4BE2DA1CE6431`
PE256 | `DA009E5565F23876428E039A9A749BBA8D58B1B0BED4CDB2C5D6ABB087DC9395`

## Runtime Data

### Usage (stdout):
```cmhg
NGen Task starting, command line: "C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ngentask.exe" --help
Unrecognized command line option --help

```

### Usage (stderr):
```cmhg
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ngentask.exe [options...]
 This tool reads from the usage log data produced by the runtime, and triggers NGen to occur.
   /RuntimeWide - Parse the fusion stream of the usage logs instead of the App stream. Task runs in machine-wide mode.
   /Critical - Runs as a critical idle task.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ngentask.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4341.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4341.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/999af53de73a2c4f0cdb8d9a19ed29d03827f89aa0f4533bb9c2d54e9b7a2137/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe](ngentask.exe-AE933850C93D3B3001AB21BB65C3EFA1.md) | 83
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe](ngentask.exe-C6CE045CA7809169A017F73D45C21462.md) | 57

## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


