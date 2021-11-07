---
title: ngentask.exe | Microsoft .NET Framework optimization service
excerpt: What is ngentask.exe?
---

# ngentask.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe`
* Description: Microsoft .NET Framework optimization service
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `AE933850C93D3B3001AB21BB65C3EFA1`
SHA1 | `FB4BEBBA7A1407C6D3931F77FD721CFFEE78DDD2`
SHA256 | `21CFA6BBC96779923E21CA05F14A32AB24CF45EB0C448AA0C4F60B71635924D8`
SHA384 | `4F9438A0E8AFAE029606211F181925DB326BD0F25C60AF8F79E1987D38FC01F6DB525A0BA6C363A327D71DFAE778CEE1`
SHA512 | `2F97921CBFCCCAC46DF95BE7FE113CB348F182C82196FCC44D16CC6757E3292B8541A2698D99AB5BFC9B7CB93B08F6922A09D4CB957835A282D35A8D131461FE`
SSDEEP | `1536:MHbMtCb5ZAP889Z9Qqw8NsbcpKs8fnFdhh820gc:8UCbg88reyp98fF58p`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `8BE8D2B49F7F01107736C276261CFE0E3F023A55`
PE256 | `97BD23D58EC8247EBD9F6E7C56382FF720087A20D427B913A555792F162A9CDF`

## Runtime Data

### Usage (stdout):
```cmhg
NGen Task starting, command line: "C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe" --help
Unrecognized command line option --help

```

### Usage (stderr):
```cmhg
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe [options...]
 This tool reads from the usage log data produced by the runtime, and triggers NGen to occur.
   /RuntimeWide - Parse the fusion stream of the usage logs instead of the App stream. Task runs in machine-wide mode.
   /Critical - Runs as a critical idle task.

```

### Child Processes:
powershell.exe

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4320.0 built by: NET48REL1LAST_C
* Product Version: 4.8.4320.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/21cfa6bbc96779923e21ca05f14a32ab24cf45eb0c448aa0c4f60b71635924d8/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngentask.exe](ngentask.exe-C6CE045CA7809169A017F73D45C21462.md) | 55

## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


