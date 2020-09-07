---
title: comp.exe | File Compare Utility
---

# comp.exe 

* File Path: `C:\WINDOWS\SysWOW64\comp.exe`
* Description: File Compare Utility

## Hashes

Type | Hash
-- | --
MD5 | `C172B6DEB87969CAC56B659ECAD820D1`
SHA1 | `FFD9025F629742C5C48388804CB01CBD7B4DE647`
SHA256 | `8BDE67B60CF4ED3F63EE3733B00238ACD6E8480DC7CF1078470DEF7A618D3759`
SHA384 | `1B11126E86385B13B178FEAC95D2AD78F55C1665F5C3D2469E981EAEB5B867A614FCFEB2484EFF12C6DCC1E0A880BFBA`
SHA512 | `B0BA70243900E27016FA2A3D0A12367B33E37351FA09CACEBD6040AE080E861FA6296B56F3117604C1E3BAC189FBA21E2551BD18B8276C4BE7CED552CF8D4BB4`
SSDEEP | `384:jIi+eXNbX/T/gQWlZoMQg86iRitODgx65meNvD31lONzW9cWxP4:Ei+eXNbKJQgpiRittEZx1lOQH`

## Runtime Data

### Usage (stdout):
```Batchfile
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
```Batchfile
Name of second file to compare: 
```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Comp.Exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


