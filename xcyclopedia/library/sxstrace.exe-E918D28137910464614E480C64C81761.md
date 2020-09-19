---
title: sxstrace.exe | Sxs Tracing Tool
---

# sxstrace.exe 

* File Path: `C:\Windows\system32\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `E918D28137910464614E480C64C81761`
SHA1 | `387ED65BC9F0BCC7D0D70645238D1C2D5345892F`
SHA256 | `507F57022283B8D40AD1D3A075FCED8A0EBD830CF433736C0559D0B10B77292E`
SHA384 | `B706A34C7A2810375F09B0C24387DAE465E0B84D0AAA16226A75B0E06BBCADF49AADE6C6C3582EB3E455D74520F63456`
SHA512 | `1B8BD6896B0BAF75520A8B43B8CF248D498E46B1DFF96873A0F7AEC878E79212C184FAE2CB0F7A78DE5A5E7F1E5EAC246F23C5FED8EA26F8393CE54EFCC12CDA`
SSDEEP | `768:KRQDJUODpd9PWNR2LVx9HvQ4GaX1Pzd3kbBU/sSICTqx3pmh0X0UJUDv:KRcT9P7vp/ro2R9TqP9E6uv`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\sxstrace.exe](sxstrace.exe-E2AF11DCF02930A6D31C7C01C6B6B66B.md) | 93


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## sxstrace

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Diagnoses side-by-side problems.

### Syntax
```
sxstrace [{[trace -logfile:<FileName> [-nostop]|[parse -logfile:<FileName> -outfile:<ParsedFile>  [-filter:<AppName>]}]
```

##### Parameters
|Parameter|Description|
|-------|--------|
|trace|Enables tracing for sxs (side-by-side)|
|-logfile|Specifies the raw log file.|
|\<FileName>|Saves tracing log to *FileName*.|
|-nostop|Specifies no prompt to stop tracing.|
|parse|Translates the raw trace file.|
|-outfile|Specifies the output filename.|
|\<ParsedFile>|Specifies the filename of the parsed file.|
|-filter|Allows the output to be filtered.|
|\<AppName>|Specifies the name of the application.|
|stoptrace|Stop the trace if it is not stopped before.|
|-?|Displays help at the command prompt.|

### Examples
Enable tracing and save trace file to **sxstrace.etl**:
```
sxstrace trace -logfile:sxstrace.etl
```
Translate the raw trace file into a human readable format and save the result to **sxstrace.txt**:
```
sxstrace parse -logfile:sxstrace.etl -outfile:sxstrace.txt
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)


---



MIT License. Copyright (c) 2020 Strontic.


