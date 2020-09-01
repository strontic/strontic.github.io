---
title: fc.exe | DOS 5 File Compare Utility
---

# fc.exe 

* File Path: `C:\windows\system32\fc.exe`
* Description: DOS 5 File Compare Utility

## Hashes

Type | Hash
-- | --
MD5 | `7C5B6800DA17EB12A3794FA094C695AF`
SHA1 | `9FAC104E1D6F08D73A4DDFE4F27018336BE2B3F5`
SHA256 | `43448F34D3BA3F5E71F4BF061CE3E0EC03957B257DF529A6A26FA5EC20374BC5`
SHA384 | `AA586034685797C939BBBDBB5C2B36490C02B968FC5D60215CE931EC95F9BB23856E4AB9E359903F542AE135246E9001`
SHA512 | `91C75620D5378FFD858568368445B7B5D7CDC9172366F0B14EA53156FA35F9C0485016C1BEB243A8E9FA726FBCFFEB0331557B93ED3967B3A0BA0120E1DA7DA2`
SSDEEP | `384:fWUQpJeZLvDJnTt7dG1snOxSjlSNMarKXFFjaERg5l4A5RkNeGuYeQb3GWHYWv:fTQpJeND1Tt7E1snOCAK1FjaER2GARpq`

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\fc.exe |


## Signature

* Status: The file C:\windows\system32\fc.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: FC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## fc

Compares two files or sets of files and displays the differences between them.

### Syntax

```
fc /a [/c] [/l] [/lb<n>] [/n] [/off[line]] [/t] [/u] [/w] [/<nnnn>] [<drive1>:][<path1>]<filename1> [<drive2>:][<path2>]<filename2>
fc /b [<drive1:>][<path1>]<filename1> [<drive2:>][<path2>]<filename2>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /a | Abbreviates the output of an ASCII comparison. Instead of displaying all of the lines that are different, **fc** displays only the first and last line for each set of differences. |
| /b | Compares the two files in binary mode, byte by byte, and does not attempt to resynchronize the files after finding a mismatch. This is the default mode for comparing files that have the following file extensions: .exe, .com, .sys, .obj, .lib, or .bin. |
| /c | Ignores the letter case. |
| /l | Compares the files in ASCII mode, line-by-line, and attempts to resynchronize the files after finding a mismatch. This is the default mode for comparing files, except files with the following file extensions: .exe, .com, .sys, .obj, .lib, or .bin. |
| /lb`<n>` | Sets the number of lines for the internal line buffer to *N*. The default length of the line buffer is 100 lines. If the files that you are comparing have more than 100 consecutive differing lines, **fc** cancels the comparison. |
| /n | Displays the line numbers during an ASCII comparison. |
| /off[line] | Doesn't skip files that have the offline attribute set. |
| /t | Prevents **fc** from converting tabs to spaces. The default behavior is to treat tabs as spaces, with stops at each eighth character position. |
| /u | Compares files as Unicode text files. |
| /w | Compresses white space (that is, tabs and spaces) during the comparison. If a line contains many consecutive spaces or tabs, **/w** treats these characters as a single space. When used with **/w**, **fc** ignores white space at the beginning and end of a line. |
| /`<nnnn>` | Specifies the number of consecutive lines that must match following a mismatch, before **fc** considers the files to be resynchronized. If the number of matching lines in the files is less than *nnnn*, **fc** displays the matching lines as differences. The default value is 2. |
| `[<drive1>:][<path1>]<filename1>` | Specifies the location and name of the first file or set of files to compare. *filename1* is required. |
| `[<drive2>:][<path2>]<filename2>` | Specifies the location and name of the second file or set of files to compare. *filename2* is required. |
| /? | Displays help at the command prompt. |

##### Remarks

- This command is implemeted by c:\WINDOWS\fc.exe. You can use this command within PowerShell, but be sure to spell out the full executable (fc.exe) since 'fc' is also an alias for Format-Custom.

- When you use **fc** for an ASCII comparison, **fc** displays the differences between two files in the following order:

  - Name of the first file

  - Lines from *filename1* that differ between the files

  - First line to match in both files

  - Name of the second file

  - Lines from *filename2* that differ

  - First line to match

- **/b** displays mismatches that are found during a binary comparison in the following syntax:

    `\<XXXXXXXX: YY ZZ>`

    The value of *XXXXXXXX* specifies the relative hexadecimal address for the pair of bytes, measured from the beginning of the file. Addresses start at 00000000. The hexadecimal values for *YY* and *ZZ* represent the mismatched bytes from *filename1* and *filename2*, respectively.

- You can use wildcard characters (**&#42;** and **?**) in *filename1* and *filename2*. If you use a wildcard in *filename1*, **fc** compares all the specified files to the file or set of files specified by *filename2*. If you use a wildcard in *filename2*, **fc** uses the corresponding value from *filename1*.

- When comparing ASCII files, **fc** uses an internal buffer (large enough to hold 100 lines) as storage. If the files are larger than the buffer, **fc** compares what it can load into the buffer. If **fc** doesn't find a match in the loaded portions of the files, it stops and displays the following message:

    `Resynch failed. Files are too different.`

    When comparing binary files that are larger than the available memory, **fc** compares both files completely, overlaying the portions in memory with the next portions from the disk. The output is the same as that for files that fit completely in memory.

#### Examples

To make an ASCII comparison of two text files, *monthly.rpt* and *sales.rpt*, and display the results in abbreviated format, type:

```
fc /a monthly.rpt sales.rpt
```

To make a binary comparison of two batch files, *profits.bat* and *earnings.bat*, type:

```
fc /b profits.bat earnings.bat
```

Results similar to the following appear:

```
00000002: 72 43
00000004: 65 3A
0000000E: 56 92
000005E8: 00 6E
FC: earnings.bat longer than profits.bat
```

If the profits.bat and earnings.bat files are identical, **fc** displays the following message:

```
Comparing files profits.bat and earnings.bat
FC: no differences encountered
```

To compare every .bat file in the current directory with the file *new.bat*, type:

```
fc *.bat new.bat
```

To compare the file *new.bat* on drive C with the file *new.bat* on drive D, type:

```
fc c:new.bat d:*.bat
```

To compare each batch file in the root directory on drive C to the file with the same name in the root directory on drive D, type:

```
fc c:*.bat d:*.bat
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


