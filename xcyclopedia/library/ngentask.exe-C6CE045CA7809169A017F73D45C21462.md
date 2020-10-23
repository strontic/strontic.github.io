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
MD5 | `C6CE045CA7809169A017F73D45C21462`
SHA1 | `7D2504133D8235E91C2E98355C4F223CDF500D4D`
SHA256 | `41019BD2DFF58ECA53A25FFCE26E487AF0B693C3D305E67A0D4E8F8CD60C6EF6`
SHA384 | `93CA8EF603A19035B6CEE21E2A40396C3E5A18366FF9C3D852081D7E072DBDC15E074CE69741346041ED51D83FC07DAC`
SHA512 | `CB42D614F4E543BE090E2D09F0F6C28ECD346B8EA2CA06BA10389A735A23792BD4D4EC189F94C8DCDC0B35707B36BA0DF811C18B7608F8A2CC2B8D429242B205`
SSDEEP | `1536:wHbMtCb5ZAPx89Z9CL8nfQLKc8fnFdTK/9duoF:4UCbgx8rc8YLn8fFA/V`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `C103EDCE2651473DC771440727D999DB39D206F5`
PE256 | `FAA79FDC4C23D0F6A1E3E9B45783AD95AAF7F8784E86A79A29FBBA830FDC4C84`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NGenTask.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/41019bd2dff58eca53a25ffce26e487af0b693c3d305e67a0d4e8f8cd60c6ef6/detection/


## Possible Misuse

*The following table contains possible examples of `ngentask.exe` being misused. While `ngentask.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\ngentask.exe'  # c:\Windows\Microsoft.NET\Framework(64)\ngentask.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


