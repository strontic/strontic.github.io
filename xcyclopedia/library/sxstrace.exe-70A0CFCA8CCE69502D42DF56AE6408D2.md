﻿---
title: sxstrace.exe | Sxs Tracing Tool
excerpt: What is sxstrace.exe?
---

# sxstrace.exe 

* File Path: `C:\Windows\system32\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `70A0CFCA8CCE69502D42DF56AE6408D2`
SHA1 | `B949C2BD2DF5E6005D0D17019C352EAD30629B91`
SHA256 | `85BDD568FEDC81B48FE18F5C4B2E2799ACEAC8049F6F36A42E5A7868E83DE938`
SHA384 | `CD6CDA3D89867FF7B757278B636E705D78E6962DE19721BA332EA30B2CD1905BDEFBC84961DF3CBD70794E5DD5E302D0`
SHA512 | `9FB4BBBC3AF7B6F1CA49C078A50F7FD7418CA0BFE9D1CF7DE8C28D8A8458B6D34562807B6E91DF6B4EAB06E34E324D469672A18E520CA2914D713276227FDD51`
SSDEEP | `768:pDyWlTdSnfYlJmA/GJpAD9aWgrs4a8wxmlmxDoyIC94rK0R8:1JmA/GTO8AZJhoy9KrPR8`
IMP | `608C121F28B6837B15D6067BE234792E`
PESHA1 | `3ABDF8163B31F30FBAF610401E8DB41B852BE78E`
PE256 | `AC119984B238BC3A28C2CD64389196DF08380F1A0A3F3E42A0F88B19374CD54E`

## Runtime Data

### Usage (stdout):
```cmhg
WinSxs Tracing Utility.
Usage: SxsTrace [Options]
Options:
   Trace -logfile:FileName [-nostop]
       Enabling tracing for sxs.
       Tracing log is saved to FileName.
       If -nostop is specified, will not prompt to stop tracing.
   Parse -logfile:FileName -outfile:ParsedFile  [-filter:AppName]
       Translate the raw trace file into a human readable format and save the result to ParsedFile.
       Use -filter option to filter the output.
   Stoptrace
       Stop the trace if it is not stopped before.
Example:  SxsTrace Trace -logfile:SxsTrace.etl
          SxsTrace Parse -logfile:SxsTrace.etl -outfile:SxsTrace.txt

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sxstrace.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/85bdd568fedc81b48fe18f5c4b2e2799aceac8049f6f36a42e5a7868e83de938/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sxstrace

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Diagnoses side-by-side problems.

### Syntax

```
sxstrace [{[trace -logfile:<filename> [-nostop]|[parse -logfile:<filename> -outfile:<parsedfile>  [-filter:<appname>]}]
```

#### Parameters

| Parameter | Description |
|--|--|
| trace | Enables tracing for side-by-side. |
| -logfile | Specifies the raw log file. |
| `<filename>` | Saves tracing log to `<filename`. |
| -nostop | Specifies that you shouldn't receive a prompt to stop tracing. |
| parse | Translates the raw trace file. |
| -outfile | Specifies the output filename. |
| `<parsedfile>` | Specifies the filename of the parsed file. |
| -filter | Allows the output to be filtered. |
| `<appname>` | Specifies the name of the application. |
| stoptrace | Stops the trace, if it wasn't stopped before. |
| -? | Displays help at the command prompt. |

### Examples

To enable tracing and to save the trace file to *sxstrace.etl*, type:

```
sxstrace trace -logfile:sxstrace.etl
```

To translate the raw trace file into a human readable format and to save the result to *sxstrace.txt*, type:

```
sxstrace parse -logfile:sxstrace.etl -outfile:sxstrace.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


