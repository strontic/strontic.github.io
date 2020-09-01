---
title: sxstrace.exe | Sxs Tracing Tool
---

# sxstrace.exe 

* File Path: `C:\windows\SysWOW64\sxstrace.exe`
* Description: Sxs Tracing Tool

## Hashes

Type | Hash
-- | --
MD5 | `66CF561128C67CC750E797DED53CA414`
SHA1 | `8172C181802C6EECFE8120C1FB82BEB66C17892A`
SHA256 | `CD1EB2BFBA4F7CED178A1DFE059B36F6E09E7A12F6F765D10D8C827FEC1F4849`
SHA384 | `EA702E5CE523E928B7AFE44DADA4AD1C25B2A30C7265B218BD486E092902069DD6A501970E715F29D29D53F311E4EBAE`
SHA512 | `A8710742C217AA227CFC025919FB8C052A3D81695ED34B3E671D0EA2E72A9D26F6423B7E70E7804C1B56853737E12447C80B5C1E8A25CD0A6410FBB26C45657E`
SSDEEP | `384:nuTRNwF4FG2+PAIlyjz/TZigSqIz7BV140qUsyBNSwX8eFY43E8K2KHd8AJNRdEB:n46A+PQr0gH0qRcopvB9dRd1Q7`

### Loaded Modules:

Path |
-- |
C:\program files\LibreOffice\program\swriter.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\SYSTEM32\VCRUNTIME140.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: The file C:\windows\SysWOW64\sxstrace.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: sxstrace.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


