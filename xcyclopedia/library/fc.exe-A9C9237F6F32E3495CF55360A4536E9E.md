---
title: fc.exe | DOS 5 File Compare Utility
excerpt: What is fc.exe?
---

# fc.exe 

* File Path: `C:\WINDOWS\system32\fc.exe`
* Description: DOS 5 File Compare Utility

## Hashes

Type | Hash
-- | --
MD5 | `A9C9237F6F32E3495CF55360A4536E9E`
SHA1 | `EE9CA2958497A21277A482A8118282A793BF2CBF`
SHA256 | `75219D57A31BBBDB097E56ED576050170FFCC46A083D5C617115C4F5CDBF3B90`
SHA384 | `9F892B4EB62486D229E24B0064751C6CCF45CE127DB1FE440053C9198082BB8ABC431FC43D99DD14E5D09D0ADC452B2C`
SHA512 | `161C7D6137195CD39656A78ABF94691F5AB8497C346BA75D5B87A11D864714BFE8EA4173DF993E211588F6FB38D3E895889E0E50884943047F1B4F73879F17C2`
SSDEEP | `384:Hh3qiBAHuFEajwAbgoOMrGrtagTag6oFYHlf7WWWYW:B3rFtlIfV6z7e`
IMP | `16AB204CB65661F82910C423B12232BE`
PESHA1 | `9EF4542CE46093C75D37458E6B53D77B95F96F12`
PE256 | `168B4A8E061AE4247CDAA53F45E5BCCA6F854C58DD7951BBD93C14B2B58745A8`

## Runtime Data

### Usage (stdout):
```cmhg
Compares two files or sets of files and displays the differences between
them


FC [/A] [/C] [/L] [/LBn] [/N] [/OFF[LINE]] [/T] [/U] [/W] [/nnnn]
   [drive1:][path1]filename1 [drive2:][path2]filename2
FC /B [drive1:][path1]filename1 [drive2:][path2]filename2

  /A         Displays only first and last lines for each set of differences.
  /B         Performs a binary comparison.
  /C         Disregards the case of letters.
  /L         Compares files as ASCII text.
  /LBn       Sets the maximum consecutive mismatches to the specified
             number of lines.
  /N         Displays the line numbers on an ASCII comparison.
  /OFF[LINE] Do not skip files with offline attribute set.
  /T         Does not expand tabs to spaces.
  /U         Compare files as UNICODE text files.
  /W         Compresses white space (tabs and spaces) for comparison.
  /nnnn      Specifies the number of consecutive lines that must match
             after a mismatch.
  [drive1:][path1]filename1
             Specifies the first file or set of files to compare.
  [drive2:][path2]filename2
             Specifies the second file or set of files to compare.


```

### Usage (stderr):
```cmhg
FC: Insufficient number of file specifications


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\fc.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: FC.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/75219d57a31bbbdb097e56ed576050170ffcc46a083d5c617115c4f5cdbf3b90/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


