---
title: compact.exe | File Compress Utility
excerpt: What is compact.exe?
---

# compact.exe 

* File Path: `C:\windows\SysWOW64\compact.exe`
* Description: File Compress Utility

## Hashes

Type | Hash
-- | --
MD5 | `DEBCA8079506F74FF7DDA17693520B45`
SHA1 | `136011FDB1C935B5982F02FF4A7137D0AFFCBA10`
SHA256 | `0B0656A8DDB957214E0F65BA52874E3BE58DEC9A2878E8C88A71957295712D87`
SHA384 | `F98B46C511C27F763AB1CB633A70D4B2DF17B7DE048BF4B624D7F5544F3B1258E7C2685427EF879DAF58943EF2669A66`
SHA512 | `0D8AAC7CD1B49D8F0AF2F83859C631ABABCD3730DC5CD0BD63C15F891B3891863535D1E60892E8D8FD9B3FB81BBF72016B4B6B94C26B272ECAFFFED4EA402D02`
SSDEEP | `384:2pPaGty0//RiCha4LkTZJP6mXjm942X/Kw7jNJWkiWrkpu:WPaGty0xiChBLk1Idv57jLHY`

## Signature

* Status: The file C:\windows\SysWOW64\compact.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: COMPACT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `compact.exe` being misused. While `compact.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [adjectives.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/adjectives.txt) | `compact`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## compact

Displays or alters the compression of files or directories on NTFS partitions. If used without parameters, **compact** displays the compression state of the current directory and any files it contains.

### Syntax

```
compact [/C | /U] [/S[:dir]] [/A] [/I] [/F] [/Q] [/EXE[:algorithm]] [/CompactOs[:option] [/windir:dir]] [filename [...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /c | Compresses the specified directory or file. Directories are marked so any files added afterwards are compressed, unless the /EXE parameter is specified. |
| /u | Uncompresses the specified directory or file. Directories are marked so any files added afterwards aren't compressed. If the /EXE parameter is specified, only files compressed as executables are uncompressed; if you don't specify the /EXE parameter, only NTFS compressed files are uncompressed. |
| /s`[:<dir>]` | Performs the chosen operation on files in the specified directory and all subdirectories. By default, the current directory is used as the `<dir>` value. |
| /a | Displays hidden or system files. By default, these files aren't included. |
| /i | Continues performing the specified operation, ignoring errors. By default, this command stops when an error is encountered. |
| /f | Forces compression or uncompression of the specified directory or file. Already-compressed files are skipped by default. The **/f** parameter is used in the case of a file that was partly compressed when the operation was interrupted by a system crash. To force the file to be compressed in its entirety, use the **/c** and **/f** parameters and specify the partially compressed file. |
| /q | Reports only the most essential information. |
| /EXE | Uses compression optimized for executable files that are read frequently, but not modified. Supported algorithms are:<ul><li>**XPRESS4K** (fastest and default value)</li><li>**XPRESS8K**</li><li>**XPRESS16K**</li><li>**LZX** (most compact)</li></ul> |
| /CompactOs | Sets or queries the system's compression state. Supported options are:<ul><li>**query** - Queries the system's **Compact** state.</li><li>**always** - Compresses all operating system binaries and sets the system state to Compact, which remains unless administrator changes it.</li><li>**never** - Uncompresses all operating system binaries and sets the system state to non-Compact, which remains unless administrator changes it.</li></ul> |
| /windir | Used with the **/CompactOs:query** parameter, when querying the offline operating system. Specifies the directory where Windows is installed. |
| `<filename>` | Specifies a pattern, file, or directory. You can use multiple file names, and the **&#42;** and **?** wildcard characters. |
| /? | Displays help at the command prompt. |

##### Remarks

- This command is the command-line version of the NTFS file system compression feature. The compression state of a directory indicates whether files are automatically compressed when they are added to the directory. Setting the compression state of a directory does not necessarily change the compression state of files that are already in the directory.

- You can't use this command to read, write, or mount volumes compressed using DriveSpace or DoubleSpace. You also can't use this command to compress file allocation table (FAT) or FAT32 partitions.

### Examples

To set the compression state of the current directory, its subdirectories, and existing files, type:

```
compact /c /s
```

To set the compression state of files and subdirectories within the current directory, without altering the compression state of the current directory itself, type:

```
compact /c /s *.*
```

To compress a volume, from the root directory of the volume, type:

```
compact /c /i /s:\
```

> [!NOTE]
> This example sets the compression state of all directories (including the root directory on the volume) and compresses every file on the volume. The **/i** parameter prevents error messages from interrupting the compression process.

To compress all files with the .bmp file name extension in the \tmp directory and all subdirectories of \tmp, without modifying the compressed attribute of the directories, type:

```
compact /c /s:\tmp *.bmp
```

To force complete compression of the file *zebra.bmp*, which was partially compressed during a system crash, type:

```
compact /c /f zebra.bmp
```

To remove the compressed attribute from the directory c:\tmp, without changing the compression state of any files in that directory, type:

```
compact /u c:\tmp
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


