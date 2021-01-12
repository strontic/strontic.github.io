---
title: ifilttst.exe | IFilter command line test tool
excerpt: What is ifilttst.exe?
---

# ifilttst.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ifilttst.exe`
* Description: IFilter command line test tool

## Hashes

Type | Hash
-- | --
MD5 | `AB5820BC5A51830590259DE174F9C9E2`
SHA1 | `0B9CDE65E9FF44E2F70AD97F2C504CC8F30F6879`
SHA256 | `2225A37A21C190FED2A4BBCCBCE2D64A715B2A11F28A4AAD462A1E651FB1AC33`
SHA384 | `833AD4ACCF7C6F77B38676D73F372033C9EF0B32D18D00322C301465272175246FE9DEE121851AE2134E0C9DC228A747`
SHA512 | `A6975246449BEDE77C6CAEF7C7D6317432CE60251970538933280B1AC74648BA029578BB3E24E658E03B8B063581714991C9E0AB241286C2C02043998FCD251A`
SSDEEP | `1536:JSawyeGI+Jbaba9609r3Xv1vgZuPiih4Qce2IvUQm+5YBvylKOqB0gIqqWuxV3JV:BPX3n4+5I0gIvWSVZQhUSm`
IMP | `4A7FC3B8540EE2F0DF50E5D69D0EF689`
PESHA1 | `CA9420B06DB898CD5A3283DB97E6121B8396000F`
PE256 | `10F6CB9517D8AF5D2AAD51E227FC3880A55735C85815B9CAE125EE79F9DF1578`

## Runtime Data

### Usage (stdout):
```cmhg

USAGE:
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ifilttst.exe /i <input file>[...] [/ini <ini file>] [/l [<log file>]] [/d] [/-l] [/-d] [/legit] [/stress] [/v <verbosity>] [/t <threads>] [/r [<depth>]] [/c <loops>]

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ifilttst.exe |
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

* Original Filename: iFiltTst.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\ifilttst.exe](ifilttst.exe-95147BFF2ACFF57F171CBDE7165F74E6.md) | 54




MIT License. Copyright (c) 2020 Strontic.


