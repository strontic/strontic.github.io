﻿---
title: where.exe | Where - Lists location of files
excerpt: What is where.exe?
---

# where.exe 

* File Path: `C:\WINDOWS\system32\where.exe`
* Description: Where - Lists location of files

## Hashes

Type | Hash
-- | --
MD5 | `E72BCE4A23FF0B4CDC18AFC2A221BC3A`
SHA1 | `8F1224FDC84F0209CAB18D32F27A643964F1C35A`
SHA256 | `0DA0911372136E3A1E78A4E118F51C7B82A6E1E71580D44DAA4C529D4ECD65D8`
SHA384 | `F78D07115847FE918AC574A96D90D9E3CE00C4FA7DBC6AAC32F6AD542EDA8124D12135BD2E09D0BCE3619606D31C8D39`
SHA512 | `14B36FD4BACCE413FE70C9F93597990D8013F1E6761A2533FDFF7824450EE85A8F1F9C8D7E653BAC357FA1CD8CDED72E0526F042BDBB0034A3B87AFC8293A8EA`
SSDEEP | `768:Y7+ErcKHhbMFgytHaFxkWY93/JOYYCVC3/5JByx+LZ9T:pHTOYYsC3/4x89T`

## Runtime Data

### Usage (stdout):
```cmhg

WHERE [/R dir] [/Q] [/F] [/T] pattern...

Description:
    Displays the location of files that match the search pattern.
    By default, the search is done along the current directory and
    in the paths specified by the PATH environment variable.

Parameter List:
    /R       Recursively searches and displays the files that match the
             given pattern starting from the specified directory.

    /Q       Returns only the exit code, without displaying the list
             of matched files. (Quiet mode)

    /F       Displays the matched filename in double quotes.

    /T       Displays the file size, last modified date and time for all
             matched files.

    pattern  Specifies the search pattern for the files to match.
             Wildcards * and ? can be used in the pattern. The
             "$env:pattern" and "path:pattern" formats can also be
             specified, where "env" is an environment variable and
             the search is done in the specified paths of the "env"
             environment variable. These formats should not be used
             with /R. The search is also done by appending the
             extensions of the PATHEXT variable to the pattern.

     /?      Displays this help message.

  NOTE: The tool returns an error level of 0 if the search is
        successful, of 1 if the search is unsuccessful and
        of 2 for failures or errors.

Examples:
    WHERE /?
    WHERE myfilename1 myfile????.*
    WHERE $windir:*.* 
    WHERE /R c:\windows *.exe *.dll *.bat  
    WHERE /Q ??.??? 
    WHERE "c:\windows;c:\windows\system32:*.dll"
    WHERE /F /T *.dll 

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument or option - '/h'.
Type "WHERE /?" for usage help.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: where.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `where.exe` being misused. While `where.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## where



Displays the location of files that match the given search pattern.



### Syntax

```
where [/r <Dir>] [/q] [/f] [/t] [$<ENV>:|<Path>:]<Pattern>[ ...]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|/r \<Dir>|Indicates a recursive search, starting with the specified directory.|
|/q|Returns an exit code (**0** for success, **1** for failure) without displaying the list of matched files.|
|/f|Displays the results of the **where** command in quotation marks.|
|/t|Displays the file size and the last modified date and time of each matched file.|
|[$\<ENV>:\|\<Path>:]\<Pattern>[ ...]|Specifies the search pattern for the files to match. At least one pattern is required, and the pattern can include wildcard characters (**&#42;** and **?**). By default, **where** searches the current directory and the paths that are specified in the PATH environment variable. You can specify a different path to search by using the format $*ENV*:*Pattern* (where *ENV* is an existing environment variable containing one or more paths) or by using the format *Path*:*Pattern* (where *Path* is the directory path you want to search). These optional formats should not be used with the **/r** command-line option.|
|/?|Displays help at the command prompt.|

### Remarks

-   If you do not specify a file name extension, the extensions listed in the PATHEXT environment variable are appended to the pattern by default.
-   **Where** can run recursive searches, display file information such as date or size, and accept environment variables in place of paths on local computers.

### Examples

To find all files named Test in drive C of the current computer and its subdirectories, type:
```
where /r c:\ test
```
To list all files in the Public directory, type:
```
where $public:*.*
```
To find all files named Notepad in drive C of the remote computer, Computer1, and its subdirectories, type:
```
where /r \\computer1\c notepad.*
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


