---
title: xpsconverter.exe |  
excerpt: What is xpsconverter.exe?
---

# xpsconverter.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\xpsconverter.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `0440AB91F1E98F58A9711BF480191A5E`
SHA1 | `A8DD9436E13809008DE004425AA69A7D00CF76CD`
SHA256 | `07D7B85E7805E2E1A22B15861C233F2771B763D0E9261AD6A825424F72BAC7A9`
SHA384 | `42A1E2445FE97451C8EAA75AFEDFAF7FD0B6541126A19490D97D83A21E95CF7C6F29B13FD0AB93D5BA7AE93070BC473C`
SHA512 | `E575DCFD4F24619EE72F87E9FBA408270C9403C3B26B3A4878F340E04310E6BF767BF8BB7B79FA0134E1E4DA5FEF1921FC30EBEF3BB831EB24AE9B1FA136D662`
SSDEEP | `768:bGo1Z4e3p1I2j8yiD9svd8sTzIT8aVa9XWVPjpB+CxEOuFF:bG8bI2j8yiuvdjFaVIXWzu/`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `5E1D1DB515E4FCF48EE1B45F2053DEE2E46A4B31`
PE256 | `8BC5BB03228C32D43E135A41C3F88DC3BC0B5AEA583EA81EB8616DE04FB646D1`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\xpsconverter.exe |
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

* Original Filename: XpsConverter.exe
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
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\xpsconverter.exe](xpsconverter.exe-60069FF023259C7E9EE32871CF7D4D3E.md) | 83




MIT License. Copyright (c) 2020 Strontic.


