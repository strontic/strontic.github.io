---
title: sxstrace.exe | Sxs Tracing Tool
---

# sxstrace.exe 

* File Path: `C:\windows\system32\sxstrace.exe`
* Description: Sxs Tracing Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A4838CBDD848977479BBB9682B9C688B`
SHA1 | `30CBC0E4D98A377A1184C319D5808A1C6DEE90EC`
SHA256 | `41036CF40DF225E265E8D64879A37751A6B1ACB1BDA7814C835C06D7C68B17D2`
SHA384 | `57ED9A26C5AB972DC86BC55901802D5846513B97D2926037644C24B60733A4549CAB3A5047048F25CA06197F7EB5E021`
SHA512 | `DE612D98135C5498BE9AD21C79789DB409207FF9E04F64B390A8473D55C535C1465BFB1CF159ED6F5B6E4994B8B4E3686C438B93AED01A55B0D3C98E8E90335A`
SSDEEP | `768:n1azuf+5VdcsZ44ivoD46vY2jKNkKVHEwlzg5N18NyH837K+EOKqN:no625ncd2+hNMN18uk7sdqN`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\sxstrace.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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


