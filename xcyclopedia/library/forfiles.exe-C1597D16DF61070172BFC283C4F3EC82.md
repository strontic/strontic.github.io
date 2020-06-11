
# forfiles.exe 

* File Path: `C:\Windows\system32\forfiles.exe`
* Description: ForFiles - Executes a command on selected files
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C1597D16DF61070172BFC283C4F3EC82`
SHA1 | `83DA939493AE1C44FC0DEE93DD5B8E095AB0C441`
SHA256 | `5B2BA93B56D9DA593CBD896FD153414BF6C2C301F5FB034974D1504FA087B955`
SHA384 | `9AB8F605385530FE87FD86E7E374C0FBEAAC22C47AAAFAEDD44C3B15ADCAE1824C9BFFCBDA314F9A3CE53046C27794C3`
SHA415 | `A16A4BE24D47F5CD59B7F8CA388543632DB1B8DE45D5AF53F5AD1D20F3BA2B91BEE45CB85E7CD9F233DF5E388EFFEE1CDC46AAD4A17433DE1F59D3AD0A80DB3D`
SSDEEP | `1536:3JfxGF15zZseSwsR13mI3SRNok+t6ZVxypHO0:z+1JZseSwsR1RSs0VxypH`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: forfiles.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


