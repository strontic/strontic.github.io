---
title: comp.exe | File Compare Utility
excerpt: What is comp.exe?
---

# comp.exe 

* File Path: `C:\WINDOWS\SysWOW64\comp.exe`
* Description: File Compare Utility

## Hashes

Type | Hash
-- | --
MD5 | `F365EB405C9584B8C9A16A25F4CDBBF4`
SHA1 | `197AF91EFB891069BE3409B27AD4967EE4218E6C`
SHA256 | `2A828597833BAFE049022A5853D6EFB3FF44997D34974F4BC096C18C729105D8`
SHA384 | `6032CB66408B7447749092F84C0AA286D5D81C3A6E34F44B513EBE42541109E64E6136388E908F21D3984BF695D90246`
SHA512 | `9DBC6C7BD247F70A7E5DEE3F754C3333E1B78501F3835BBB8195F7C3C7B2E328FEA0772A4CABB1C17CD4FDC3CD26F823B468D82D633D2511CD7DF15929D30584`
SSDEEP | `384:EciWxiKyQ71zJxVWJRDRc4dLDZM1A39c4EA6ONjWDcW:piWxiKpBzGR+4w+WBOq`
IMP | `C5DC0432C35B6D80851F60294D3B3BD7`
PESHA1 | `FB71F7FC178EB73B80E901141318208B2AB5D94A`
PE256 | `D15F3F61F01C9D27B279DF6EC0835547FC8ACDCD72896A8EF306C3996733973D`

## Runtime Data

### Usage (stdout):
```cmhg
Compares the contents of two files or sets of files.

COMP [data1] [data2] [/D] [/A] [/L] [/N=number] [/C] [/OFF[LINE]] [/M]

  data1      Specifies location and name(s) of first file(s) to compare.
  data2      Specifies location and name(s) of second files to compare.
  /D         Displays differences in decimal format.
  /A         Displays differences in ASCII characters.
  /L         Displays line numbers for differences.
  /N=number  Compares only the first specified number of lines in each file.
  /C         Disregards case of ASCII letters when comparing files.
  /OFF[LINE] Do not skip files with offline attribute set.
  /M         Do not prompt for compare more files.

To compare sets of files, use wildcards in data1 and data2 parameters.

```

### Usage (stderr):
```cmhg
Name of second file to compare: 
```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\ulib.dll.mui | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\comp.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Comp.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/2a828597833bafe049022a5853d6efb3ff44997d34974f4bc096c18c729105d8/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## comp

Compares the contents of two files or sets of files byte-by-byte. These files can be stored on the same drive or on different drives, and in the same directory or in different directories. When this command compares files, it displays their location and file names. If used without parameters, **comp** prompts you to enter the files to compare.

### Syntax

```
comp [<data1>] [<data2>] [/d] [/a] [/l] [/n=<number>] [/c]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<data1>` | Specifies the location and name of the first file or set of files that you want to compare. You can use wildcard characters (**&#42;** and **?**) to specify multiple files. |
| `<data2>` | Specifies the location and name of the second file or set of files that you want to compare. You can use wildcard characters (**&#42;** and **?**) to specify multiple files. |
| /d | Displays differences in decimal format. (The default format is hexadecimal.) |
| /a | Displays differences as characters. |
| /l | Displays the number of the line where a difference occurs, instead of displaying the byte offset. |
| /n=`<number>` | Compares only the number of lines that are specified for each file, even if the files are different sizes. |
| /c | Performs a comparison that is not case-sensitive. |
| /off[line] | Processes files with the offline attribute set. |
| /? | Displays Help at the command prompt. |

### Remarks

- During the comparison, **comp** displays messages that identify the locations of unequal information between the files. Each message indicates the offset memory address of the unequal bytes and the contents of the bytes (in hexadecimal notation unless the **/a** or **/d** command-line parameter is specified). Messages appear in the following format:

    ```
    Compare error at OFFSET xxxxxxxx
    file1 = xx
    file2 = xx
    ```

    After ten unequal comparisons, **comp** stops comparing the files and displays the following message:

    `10 Mismatches - ending compare`

- If you omit necessary components of either *data1* or *data2*, or if you omit *data2* entirely, this command prompts you for the missing information.

- If *data1* contains only a drive letter or a directory name with no file name, this command compares all of the files in the specified directory to the file specified in *data1*.

- If *data2* contains only a drive letter or a directory name, the default file name for *data2* becomes the same name as for *data1*.

- If the **comp** command can't find the specified files, it will prompt you with a message about whether you want to compare additional files.

- The files that you compare can have the same file name, provided they're in different directories or on different drives. You can use wildcard characters (**&#42;** and **?**) to specify file names.

- You must specify **/n** to compare files of different sizes. If the file sizes are different and **/n** isn't specified, the following message is displayed:

    ```
    Files are different sizes
    Compare more files (Y/N)?
    ```

    To compare these files anyway, press **N** to stop the command. Then, run the **comp** command again, using the **/n** option to compare only the first portion of each file.

- If you use wildcard characters (**&#42;** and **?**) to specify multiple files, **comp** finds the first file that matches *data1* and compares it with the corresponding file in *data2*, if it exists. The **comp** command reports the results of the comparison for each file matching *data1*. When finished, **comp** displays the following message:

    `Compare more files (Y/N)?`

    To compare more files, press **Y**. The **comp** command prompts you for the locations and names of the new files. To stop the comparisons, press **N**. When you press **Y**, you're prompted for which command-line options to use. If you don't specify any command-line options, **comp** uses the ones you specified before.

### Examples

To compare the contents of the directory *c:\reports* with the backup directory `\\sales\backup\april`, type:

```
comp c:\reports \\sales\backup\april
```

To compare the first ten lines of the text files in the *\invoice* directory and display the result in decimal format, type:

```
comp \invoice\*.txt \invoice\backup\*.txt /n=10 /d
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


