---
title: isxps.exe |  
excerpt: What is isxps.exe?
---

# isxps.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\isxps.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `AF89FFAABC747CEF26946917F10E3A3C`
SHA1 | `BB8C726C147803BD8B88697ADD2B642B342A81BC`
SHA256 | `1F9A84854DCF8C73D6BD3DB89F08451E0C09767CF602F837CBF8E97072E5CD25`
SHA384 | `0EF09C18D4A075EB8E6DE9A6F8564610F3F2A82778FA7C886F7F9689EB79AF4E9BA0E9549ACD8731B71C1FA19A489279`
SHA512 | `0BAF8E45705E8E9B2723242A53E4B3B7CD1EAEEAD6338245C7BDA565CFF27507B9F8E5B23B267994A439245309F4A1347130B12A4622933AD1641049F079AE9B`
SSDEEP | `3072:FYhy2j14ml3I2LC7bRbH2gVMnayzmXtMqRNf1UuDiMvTCfrqUoIg04YUf/oK0PJT:ay4ScaZbH2gGanxf1`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `C74F6773BD91994515889F2A9C91B69C7D7897DE`
PE256 | `9006F7EF17E145F466306593C01A4A16646D555E42DC17A2EC0F0AC31A97B152`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\isxps.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\isxps.exe](isxps.exe-48B4F83B356B12C2FCA2EEB394B4B1AC.md) | 86




MIT License. Copyright (c) 2020 Strontic.


