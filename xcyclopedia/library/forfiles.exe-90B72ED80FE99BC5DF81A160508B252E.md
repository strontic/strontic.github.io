
# forfiles.exe 
* File Path: `C:\WINDOWS\system32\forfiles.exe`
* Description: ForFiles - Executes a command on selected files
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `90B72ED80FE99BC5DF81A160508B252E`
SHA1 | `5FB84B5B8D2A27538ADE6FC583DE9DD5E5203856`
SHA256 | `0027CE0037FDEE37F189AA74FACF0EB7683524A0306C124621DB79B366CE9FF9`
SHA384 | `A977A30A9DFBEA5A05AEFA7A88C41FB7A76E50C803DBFB33A384E625B23F8C9CC415474A67F1014FEAB3C33F3D45CB45`
SHA415 | `F3CA9DA6A4C32B3E864A11E0178F1A4FDE2A6D1C2FCDC2BD60BAC08DB3BA752B5D6B4DF7F209AFBCADCD51AE75DC85D71A350373FAFCEC096C195FF461211195`
SSDEEP | `768:VyIUxvUUy2SucVhKmirwPrKQcncfOV4NjYxD3gZCuXKoF4ZTGt6Xxlex2T4kRG:gICUDucV3zKQcncfBXXKfZTGt6XGx27M`

## Runtime Data
### Usage (stdout):
```Batchfile

FORFILES [/P pathname] [/M searchmask] [/S]
         [/C command] [/D [+ | -] {MM/dd/yyyy | dd}]

Description:
    Selects a file (or set of files) and executes a 
    command on that file. This is helpful for batch jobs.

Parameter List:
    /P    pathname      Indicates the path to start searching.
                        The default folder is the current working
                        directory (.).

    /M    searchmask    Searches files according to a searchmask.
                        The default searchmask is '*' .

    /S                  Instructs forfiles to recurse into
                        subdirectories. Like "DIR /S".

    /C    command       Indicates the command to execute for each file.
                        Command strings should be wrapped in double
                        quotes. 

                        The default command is "cmd /c echo @file".

                        The following variables can be used in the
                        command string:
                        @file    - returns the name of the file.
                        @fname   - returns the file name without
                                   extension.
                        @ext     - returns only the extension of the
                                   file.
                        @path    - returns the full path of the file.
                        @relpath - returns the relative path of the
                                   file.
                        @isdir   - returns "TRUE" if a file type is
                                   a directory, and "FALSE" for files.
                        @fsize   - returns the size of the file in
                                   bytes.
                        @fdate   - returns the last modified date of the
                                   file.
                        @ftime   - returns the last modified time of the
                                   file.

                        To include special characters in the command 
                        line, use the hexadecimal code for the character
                        in 0xHH format (ex. 0x09 for tab). Internal
                        CMD.exe commands should be preceded with
                        "cmd /c".

    /D    date          Selects files with a last modified date greater
                        than or equal to (+), or less than or equal to
                        (-), the specified date using the
                        "MM/dd/yyyy" format; or selects files with a
                        last modified date greater than or equal to (+)
                        the current date plus "dd" days, or less than or
                        equal to (-) the current date minus "dd" days. A
                        valid "dd" number of days can be any number in
                        the range of 0 - 32768.
                        "+" is taken as default sign if not specified.

    /?                  Displays this help message.

Examples:
    FORFILES /?
    FORFILES  
    FORFILES /P C:\WINDOWS /S /M DNS*.* 
    FORFILES /S /M *.txt /C "cmd /c type @file | more"
    FORFILES /P C:\ /S /M *.bat
    FORFILES /D -30 /M *.exe
             /C "cmd /c echo @path 0x09 was changed 30 days ago"
    FORFILES /D 01/01/2001
             /C "cmd /c echo @fname is new since Jan 1st 2001"
    FORFILES /D +6/4/2020 /C "cmd /c echo @fname is new today"
    FORFILES /M *.exe /D +1
    FORFILES /S /M *.doc /C "cmd /c echo @fsize" 
    FORFILES /M *.txt /C "cmd /c if @isdir==FALSE notepad.exe @file"

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "FORFILES /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: forfiles.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


