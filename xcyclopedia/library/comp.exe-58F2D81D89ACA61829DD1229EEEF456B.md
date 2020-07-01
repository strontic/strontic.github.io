---
title: comp.exe | File Compare Utility
---

# comp.exe 

* File Path: `C:\windows\system32\comp.exe`
* Description: File Compare Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `58F2D81D89ACA61829DD1229EEEF456B`
SHA1 | `B17959BF22F60A304DDF4FB44D9CD05D6578B0A7`
SHA256 | `6794FE30AE38477488CC128FD89AE781F986168513B6B922E33092E6E2B54D74`
SHA384 | `E1375FB2AC71E1929F7B97DA41957D807DF35394A1EFE03EABEF84CD06F79115DF1717CC6E45EC1459AACED7B05060D2`
SHA512 | `A7D12C5B2C13B4D856FE9BFDD957BCB78CE9E56741D46F5D976A17251E24EC0FDEEF9862C68138ABA7DC084B4607E2A6249A52F9B850EC9710D7FF3F4A63F211`
SSDEEP | `384:JSy5zhxuAJIH9iFftZd4MRBLMWIHmmHm4eY+PWXbHNTWKcW:dF7JIH8naMzM/GFGbHz`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\comp.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Comp.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


