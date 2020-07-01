---
title: where.exe | Where - Lists location of files
---

# where.exe 

* File Path: `C:\windows\system32\where.exe`
* Description: Where - Lists location of files
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9C7F19C9975979E2ED1B2CE5383BA4E8`
SHA1 | `471B458EDCB8613BEDA1EAED03F696CF72C763C3`
SHA256 | `FD9D35CAE2120C38CB96D38F040737CA80E41F1FC59B1B02324EFB7E091AA255`
SHA384 | `E5A50DAA3386D46040338FFC4983708B73C8854F82871856DD9471B5957270133A1B0E6C3ADB0767AC187404A4AA6B63`
SHA512 | `1164092A2A1CD8767761237A14EFE714041B66A37B77D91262A0B7FEA1BE88FDA86EF3B8416F97242D171CF88FF7B7458D99359FC42D4E3C3D424DB31402A4FA`
SSDEEP | `768:tPSuf/amM13jf0X9Zz3qMXs3wp4MqfHX3/YvHnwx+dp:+fQP4JP3/hxGp`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
ERROR: Invalid argument or option - '/h'.
Type "WHERE /?" for usage help.

```

### Child Processes:


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


## Possible Misuse

*The following table contains possible examples of `where.exe` being misused. While `where.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 }  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


