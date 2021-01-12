---
title: isxps.exe |  
excerpt: What is isxps.exe?
---

# isxps.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\isxps.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `48B4F83B356B12C2FCA2EEB394B4B1AC`
SHA1 | `58A792C0DF74F7C5C8CDDCCA9F691A10D20DC826`
SHA256 | `23A4C90D11048C5C8B11A980DF7DB44B5A3B62377E97650B045ACA7E8E57D3CA`
SHA384 | `4F52862EF923D3245CFD9C8167A45BA436C74D1514D2D2DAE3CF4155B2BBB168AA83A52FBCA83A641C0C899251E4A43F`
SHA512 | `ED4BA91C2F99B16AB23EC4FAD379AFEFE9A89DFB94CC5AE403DC196174F7E83290C82D309B5705CA82288C6669E9EF070CEB15043792A70B22D4F3EC310B34FF`
SSDEEP | `3072:xYhy2j14ml3I2LDZm1bRxH2gVMnayzmXtMqRnf1UEDiMvTCfrqUoIg04YUf/oK0t:ey4ScLZIxH2gGanTf1`
IMP | `n/a`
PESHA1 | `EC260A0D7DA6108BE981F0124EFFAEB4953B6E0A`
PE256 | `BF3A7C9F36D5FF633BE144C6222895DE442C9E18D4D2A58B715D6CEE0DACF243`

## Runtime Data

### Usage (stdout):
```cmhg
Filename is required, but was not specified
isXPS v2.0
Copyright (c) 2009 Microsoft Corporation. All rights reserved.

Usage---------------------------------------------
isXPS.exe -t=<XPS | OXPS> -f=<FilePattern> [OptionalSwitches]
e.g. isXPS.exe -t=XPS -f=SomeFile.xps -logger:File
e.g. isXPS.exe -t=OXPS -f=*.oxps /s -logger:File
Most Used Switches:
  -t=<XPS | OXPS>
		: Validate against XPS or OpenXPS. The default value is XPS.
  -f=<FilePath>	: The file to perform the validation on.
  /s		: Apply pattern to all subdirectories
  -logger:<LoggerType>
		: The logger to use (File, Console, WTT).
  		  the default logger is "CONSOLE".
  -logfile:<LogFile>
		: The log file to write to when using the File logger.
  		  the default log file is "isXPSLog.txt".
  /?		: Display this help
Xsd Switches (optional for custom XSDs):
  -x:<S0Xsd>	: The path to the S0 xsd
  -r:<RSCXsd>	: The path to the Resource dictionary key xsd
  -doc:<DOCXsd>	: The path to the Document Structure xsd
Advanced Switches:
  -logprefix:<Prefix>
		: specifies the prefix to append to log files from this run.
  		  Setting this will enable log file splitting output (for large runs)
  		  With log file splitting (File logger only), the setup will be output
  		  to the specified log file while the actual test results will be stored
  		  in the log file "prefix_#to#.log files"
  -logsplit:<Number>
		: How often should isXPS split the log file (Default: 0)
  		  Setting this will enable log file splitting output (for large runs)
  -BadDir=<Quarantine path>	: Copy invalid packages to this directory.
  /DelBad	: Delete invalid packages.
  /OnlyLogFailures	: Log failures only to create small log files.
  /OnlyOPC	: Only validate against the OPC specification. This will only work with ZIP-based OPC packages
  /SkipResParts	: Don't validate resource parts content.
  /NoInterleave	: Turn off interleaving validation.
  /NoPTConform	: Turn off PTConform (Advanced PrintTicket validation).
  /DisallowForeignParts	: Generate an error on non-XPS parts.
  -device:<DeviceString>
		: The device string to use with the WTT logger.
  		: the default device is "$LogFile:file=isXPSLog.wtl,WriteMode=append".

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\isxps.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: IsXps.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\isxps.exe](isxps.exe-AF89FFAABC747CEF26946917F10E3A3C.md) | 86




MIT License. Copyright (c) 2020 Strontic.


