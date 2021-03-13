---
title: xpsconverter.exe |  
excerpt: What is xpsconverter.exe?
---

# xpsconverter.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\xpsconverter.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `60069FF023259C7E9EE32871CF7D4D3E`
SHA1 | `E7FF81F55246E6B96C54F53DFE69AB93E5BACDF8`
SHA256 | `A58154AAE284695006237A713654C5B9A40AAF707821AD81C17453669B92951E`
SHA384 | `877AAF2980D14B07137ACB47A10AD7A07FAE236E1FB7DCA5A4DBC5F9B7B546B66E36D5D4D5AE5289D31DAA2C33052912`
SHA512 | `85F93EE8CA8E98F80B978EEA60AF7FBB0127444FA8438807793C26DA4FDCF564A046E9FB9BA42AA6025FBBCECBFE5D14BD4C7D235ADB5E9875223BEBE51211F9`
SSDEEP | `768:MGo1Z4e3p1I2j8yiD9Ivd8sTzDPz8aVa9XWVPjpB+CxElhoP:MG8bI2j8yiKvdXQaVIXWsh`
PESHA1 | `E991EC4A9FE9CA32256B9FF5D6A4975E509D886E`
PE256 | `6EAE569FFB2EC4B235CE19F17A8EF594C461748C596BA9776F738CF9C2252A31`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid conversion option. Expected /OpenXPS or /XPS

XpsConverter
Copyright (c) 2010 Microsoft Corporation. All rights reserved.

Usage:
  XpsConverter /OpenXPS | /XPS
  [/InputFile=<input file name> /OutputFile=<output file name>]
  [/InputFolder=<input folder name> /OutputFolder=<output folder name>]
  [OptionalSwitches]

  /OpenXPS - convert to OpenXPS format.
  /XPS     - convert to XPS format.

  [/InputFile=<input file> /OutputFile=<output file>]
    - convert a single file.

  [/InputFolder=<input folder> /OutputFolder=<output folder>]
    Convert all the files in <input folder> and save them to <output folder>
    Files in <input folder> must have .xps or .oxps extensions.
    Converting a folder is a recursive operation.

  -logger:<LoggerType>
	: The logger to use (File, Console, WTT).
	  the default logger is "CONSOLE".
  -logfile:<LogFile>
	: The log file to write to when using the File logger.
	  the default log file is "XpsConverter.txt".
  -device:<DeviceString>
	: The device string to use with the WTT logger.
	  the default device is "$LogFile:file=XpsConverter.wtl,WriteMode=append".
  /?	: Display this help

Sample Usage:

  XpsConverter /OpenXPS /InputFile=Test.xps /OutputFile=Test.oxps
  XpsConverter /XPS /InputFolder=c:\OpenXps /OutputFolder=c:\MSXPS

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\xpsconverter.exe |
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

* Original Filename: XpsConverter.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\xpsconverter.exe](xpsconverter.exe-0440AB91F1E98F58A9711BF480191A5E.md) | 83




MIT License. Copyright (c) 2020-2021 Strontic.


