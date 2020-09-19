---
title: sxstrace.exe | Sxs Tracing Tool
---

# sxstrace.exe 

* File Path: `C:\Windows\system32\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `E2AF11DCF02930A6D31C7C01C6B6B66B`
SHA1 | `CC679E9AB4FE6FB7B55FDAAD70463CEEA76BADD8`
SHA256 | `5BCA119BCDA248F6DCA945A755C0A072FBFDA8776774EB53035691C8385ABA0C`
SHA384 | `76FDB47B470CC045BB277677FBA6BB5C875A9156DD7652B9C030372CA7AFDC2879000F8593E2FB82CFEF90DF9FB00FB6`
SHA512 | `F7A877AE9394697F53C99FAED902F5DE8D9433F78CC9ECC200A76B534BBE093EDE8C3B03AF3E3B792697E461FCD7EEAFCE3A9B3979FCA64C3E913FAE42621192`
SSDEEP | `768:vRQDJUODpd9PWNR2LVx9HvQ4GaX1Pzd3kbBU/sSIC2x3pmh0X0hUDR:vRcT9P7vp/ro2R92P9EhuR`

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
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
[C:\Windows\system32\sxstrace.exe](sxstrace.exe-E918D28137910464614E480C64C81761.md) | 93


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


