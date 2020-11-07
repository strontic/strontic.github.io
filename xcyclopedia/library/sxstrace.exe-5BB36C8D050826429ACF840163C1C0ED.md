---
title: sxstrace.exe | Sxs Tracing Tool
excerpt: What is sxstrace.exe?
---

# sxstrace.exe 

* File Path: `C:\Windows\system32\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `5BB36C8D050826429ACF840163C1C0ED`
SHA1 | `BE88EC2680991B502A193DE71E0709C6D0D344A2`
SHA256 | `4C1283E3538BF2299B62D0C18440C242822775658BA0A9ADDDA2133CF2F16CB0`
SHA384 | `10046C4C585DFED01A4454F6415EA649C106D633EB33C6832DEED0839C193E28AACAB81E05F2661457F71AD092F02E52`
SHA512 | `4BDF7FF5054CE24E4782B51E9A8E2247D4D5E1C7A7A2BCBC0E925036F8FFF0FAE2D7BE79D5F13AAD7C826F1B9F2A40DCB3C731610E2B6710B2F293E11673B947`
SSDEEP | `768:+RhzpU+uAS9PWNBWLVx9n/Q42aXOfDd3EbBUfHICGrxHJ2D40J6+P:+R3W9PLPZEro2P9Gr/kJJ6+P`
IMP | `608C121F28B6837B15D6067BE234792E`
PESHA1 | `1276F2E0DF259A8AD137BE252C9909739E95044E`
PE256 | `9ED3FC80DC36D6F41B1CDE0514C43548AA02FB796990EF9FCD1F37A9C710C535`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\sxstrace.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: sxstrace.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/4c1283e3538bf2299b62d0c18440c242822775658ba0a9addda2133cf2f16cb0/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## sxstrace

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


