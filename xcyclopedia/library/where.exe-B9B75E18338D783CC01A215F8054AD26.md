---
title: where.exe | Where - Lists location of files
excerpt: What is where.exe?
---

# where.exe 

* File Path: `C:\Windows\SysWOW64\where.exe`
* Description: Where - Lists location of files

## Hashes

Type | Hash
-- | --
MD5 | `B9B75E18338D783CC01A215F8054AD26`
SHA1 | `6E837DC826A80F37D81B86971FED0EA1A073C5E9`
SHA256 | `E4220435F20B966623B7646C247397DDAF5CE0D8A2A5EF2BC9915E6D111EA765`
SHA384 | `1E865BAEEBC671A0F505342DB4E61C9E8E2F7C5B7D48A300B2742F9C65EE7AD81E5799F9DB40392026606DE7DA024F75`
SHA512 | `1791CEDD57D8C3DE47DB2E41418BAF6185266C9EA70776D1C582746F3E4E4BD335AC2AD19BA5C229716C91A41E20E98E201819BA17A66D8EE41F96ED63F99E88`
SSDEEP | `768:JW9XPN2yhpD212KNJxFhwGkGp5Uqa/u9xufOBF:JaXPN2yhpS1lNvkCfVxhB`
IMP | `C6F8BF70A2BF252E595BCF3EB4236860`
PESHA1 | `DCCBC628056C7FD94720C31A45B44B48EBA14454`
PE256 | `A8C0E500BB3D85A64C79A8033FA86DBCC27544E01942ED36E3BA6CF481792D76`

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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\where.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: where.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/e4220435f20b966623b7646c247397ddaf5ce0d8a2a5ef2bc9915e6d111ea765/detection/


## Possible Misuse

*The following table contains possible examples of `where.exe` being misused. While `where.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
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


