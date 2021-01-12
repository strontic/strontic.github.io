---
title: ifilttst.exe | IFilter command line test tool
excerpt: What is ifilttst.exe?
---

# ifilttst.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ifilttst.exe`
* Description: IFilter command line test tool

## Hashes

Type | Hash
-- | --
MD5 | `55966155C02033E554E8634996173D76`
SHA1 | `EE2A16D29C7F6B0C1390825C091A8C64AC4CC11F`
SHA256 | `C42A1986082967157F511F5CC56818D83CF4F1E19F731D2E0C67A8003A9053DE`
SHA384 | `AFA41206A430C59302F2CC49B08DBD5079D20A2A9DD0A699371D68CC03869FEC0468992DA262843E9B9B8661ECE42B96`
SHA512 | `8A40445EF5A2665682E127141AA2EB414F156B0092B46F1F295FFFCFEC92E5C69D18C04A7B62A252B93073DA8038E3E316E9F4BAC1EB757F8AB6DC9FFE192D0E`
SSDEEP | `1536:RjjcibSuAtD30ntPT3IzU6cysInYhAiGCzaQy+Go+Jb6ba9aeL3XnVvAZeVqwiO/:Fchuc0ntPT3IzU6cj2tVXXlpPX`
IMP | `BF1D07799190ADC65BC0DE67CB6C0FD0`
PESHA1 | `B74A57C3A36CB2E4A04A733A79CF9F6E4C889E04`
PE256 | `C71FBA6AFB75B3FC8FB5E549477A0E679575AA766EF1264849EC92A6AB5E2E3D`

## Runtime Data

### Usage (stdout):
```cmhg

USAGE:
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ifilttst.exe /i <input file>[...] [/ini <ini file>] [/l [<log file>]] [/d] [/-l] [/-d] [/legit] [/stress] [/v <verbosity>] [/t <threads>] [/r [<depth>]] [/c <loops>]

	<input file> is the file/directory/pattern to which to bind.
		Wildcards are OK. More than one input file is OK.
	<ini file> is the initialization file to use.  If none is
		specified, it defaults to ifilttst.ini.
	[/l] enables logging to a file. By default, the log filename
		is the input file name with a .log extension. If you
		specify a log file name, all the log messages will be sent
		to a single file.
	[/d] enables dumping to a file.  The dump filename is the
		input file name with a .dmp extension.
	[/-l] disables logging.  This flag overrides /l.
	[/-d] disables dumping.  This flag overrides /d.
	[/legit] forces the test to run only the Validation Test.
		The Consistency and Invalid Input Tests are skipped.
	[/stress] forces the test to run in stress mode. This is the
		 same as specifying /-l /-d /legit /v 0 /c 0
	<verbosity> is an integer representing the verbosity level
		Acceptable values are from 0 through 3, with 3 being the
		most verbose. (default is 3)
	<threads> is an integer representing the number of threads
		to launch. Only useful if filtering multiple files.
		(default is 1)
	<depth> is an integer representing the depth to recurse.
		No value or a value of 0 indicates full recursion. (default is 1)
	<loops> is an integer representing the number of times to
		loop.  A value of 0 means loop infinetly. (default is 1)
ERROR: An input file must be specified

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ifilttst.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: iFiltTst.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\ifilttst.exe](ifilttst.exe-3FDB649AFB0FFDC2C1E63AAB02B7F766.md) | 38




MIT License. Copyright (c) 2020 Strontic.


