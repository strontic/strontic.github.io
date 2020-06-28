---
title: sxstrace.exe | Sxs Tracing Tool
---

# sxstrace.exe 

* File Path: `C:\Windows\SysWOW64\sxstrace.exe`
* Description: Sxs Tracing Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E7EFC0672E4211B56DD13E9BD698E96E`
SHA1 | `6047AD6C2CBAEF897B9AFDCA4489CAE58BCCABB0`
SHA256 | `1B6DBE28BB0FA4D8C1534A91B6A43D42B3E3B0C42CE4635E1DC609D739B15292`
SHA384 | `3240D5BC497E5D7E9AB796CCCA568A31FF3ECCAAFEEA6B3566DA1D5234BA0AE51DBACAEDA296B0E7908F85AD0D623A83`
SHA512 | `AF4CA80ECBD081580302552908EF5942C2A1FCC38D2FA304669AF09973D47AF65A135E9334807CDD5845EBDA9AB57A7BF1374432AC83DC5B731ED5D1A5E8E111`
SSDEEP | `384:cKj6d1wFxTSsbFO7lS5NVyjjGvLkRRShKiNj8BGDT0GFcTFLFttrWXqQw+sNduax:rISbMuy/pru0Gu5lrH7mbyfdXb`

## Runtime Data

### Usage (stdout):
```Batchfile
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

### Usage (stderr):
```Batchfile

```

### Child Processes:


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


