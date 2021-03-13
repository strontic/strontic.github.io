---
title: sxstrace.exe | Sxs Tracing Tool
excerpt: What is sxstrace.exe?
---

# sxstrace.exe 

* File Path: `C:\Windows\SysWOW64\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `AC788961CF9E2CB97D0089A21EB5173E`
SHA1 | `D6EBB4F71EEDDF97DDA88EF8E50197BE44469AE7`
SHA256 | `55E0805F0BEB5D8D1B395A9000599CED21A8CC9B824F2A2FA4CEEC0DCFA88D8B`
SHA384 | `7E4A78AB58D915338F0CF990721CE7B1E46F1A5AB4AB5A42E11A3A6E95C2A098300DB724F54A4256EC567F887A7F9C59`
SHA512 | `C63297EC2C1B0DA7091D191526A840D95A10C24BB3724ECF9F3508FDB79F6841DCFE14894A737410B71BD1B17958DFB3907EA59C1D46DBD171760CDFCA0F87E3`
SSDEEP | `384:8Kj6d1wF3TSsbFO7lS5NVyjjGvLkRRShKiNj8BGDT0GFcTFLFttrWXqQw+sNdua4:LISpMuy/pru0Gu5lrH7mltf/HD`
IMP | `E5F700CF708ED01F967809EB3E520C38`
PESHA1 | `67DF17D8A02789BE58D0B82F87999E6061844A69`
PE256 | `57F276C589B64A434EC7A48FE13B8D5E5DAB47955400B2CC65D9250862A8D137`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\sxstrace.exe |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/55e0805f0beb5d8d1b395a9000599ced21a8cc9b824f2a2fa4ceec0dcfa88d8b/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\sxstrace.exe](sxstrace.exe-E7EFC0672E4211B56DD13E9BD698E96E.md) | 96
[C:\Windows\SysWOW64\sxstrace.exe](sxstrace.exe-F509469ED866462CC44D79E9C7A6543D.md) | 96


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



MIT License. Copyright (c) 2020-2021 Strontic.


