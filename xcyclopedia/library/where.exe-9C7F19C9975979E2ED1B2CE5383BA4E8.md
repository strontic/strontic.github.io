---
title: where.exe | Where - Lists location of files
excerpt: What is where.exe?
---

# where.exe 

* File Path: `C:\Windows\system32\where.exe`
* Description: Where - Lists location of files

## Hashes

Type | Hash
-- | --
MD5 | `9C7F19C9975979E2ED1B2CE5383BA4E8`
SHA1 | `471B458EDCB8613BEDA1EAED03F696CF72C763C3`
SHA256 | `FD9D35CAE2120C38CB96D38F040737CA80E41F1FC59B1B02324EFB7E091AA255`
SHA384 | `E5A50DAA3386D46040338FFC4983708B73C8854F82871856DD9471B5957270133A1B0E6C3ADB0767AC187404A4AA6B63`
SHA512 | `1164092A2A1CD8767761237A14EFE714041B66A37B77D91262A0B7FEA1BE88FDA86EF3B8416F97242D171CF88FF7B7458D99359FC42D4E3C3D424DB31402A4FA`
SSDEEP | `768:tPSuf/amM13jf0X9Zz3qMXs3wp4MqfHX3/YvHnwx+dp:+fQP4JP3/hxGp`
IMP | `1B253A651AEF9DCAAFF94AFE777011D1`
PESHA1 | `23D11271D9FE5D9074E97A86FCF577E6C8065817`
PE256 | `277DFEA2D2CDACF8C57EAB63D98B56DA5BD1E153790411E43B1FFA41DB05522D`

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
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\VERSION.dll |
C:\Windows\system32\where.exe |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: where.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/fd9d35cae2120c38cb96d38f040737ca80e41f1fc59b1b02324efb7e091aa255/detection/


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


