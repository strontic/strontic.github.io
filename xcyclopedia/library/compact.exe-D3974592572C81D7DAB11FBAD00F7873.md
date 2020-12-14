---
title: compact.exe | File Compress Utility
excerpt: What is compact.exe?
---

# compact.exe 

* File Path: `C:\windows\system32\compact.exe`
* Description: File Compress Utility

## Hashes

Type | Hash
-- | --
MD5 | `D3974592572C81D7DAB11FBAD00F7873`
SHA1 | `2F4EE536AF53073EEF352700929018894A27FA3B`
SHA256 | `E8A17A751E21FA078948AC928AC0EBFE63B8ADFD33C369B5B48B86CAC5AA5990`
SHA384 | `65247865EF4331F396F6A70096D7DBBA582EEB36045F1C9AEC18823E541836CCBE2B83B1D1040BF13D77E65DAF3B7000`
SHA512 | `2034DD513F6166FE172B1C05EAE9B685E703A68629ECE0D8724C5C32CE97FAE073D496D382000E4B6E49E79BFABC6EA9FCBF67748F391D7325B517C8C2F93BAC`
SSDEEP | `384:fMBMTMFBDts0CqD9FtszQx9XiIPs1EvpJ3IaeucCVxGZi4Onk3FCGedNZWkiW:f/M3Dts9qD9bszQfCEvcaeIVxG6kwndL`

## Signature

* Status: The file C:\windows\system32\compact.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[malware-ioc](https://github.com/eset/malware-ioc) | [adjectives.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/adjectives.txt) | `compact` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## compact

Displays or alters the compression of files or directories on NTFS partitions. If used without parameters, **compact** displays the compression state of the current directory and the files it contains.

### Syntax

```
compact [/c | /u] [/s[:<dir>]] [/a] [/i] [/f] [/q] [<filename>[...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /c | Compresses the specified directory or file. |
| /u | Uncompresses the specified directory or file. |
| /s[:`<dir>`] | Applies the **compact** command to all subdirectories of the specified directory (or of the current directory if none is specified). |
| /a | Displays hidden or system files. |
| /i | Ignores errors. |
| /f | Forces compression or uncompression of the specified directory or file. **/f** is used in the case of a file that was partly compressed when the operation was interrupted by a system crash. To force the file to be compressed in its entirety, use the **/c** and **/f** parameters and specify the partially compressed file. |
| /q | Reports only the most essential information. |
| `<filename>` | Specifies the file or directory. You can use multiple file names, and the **&#42;** and **?** wildcard characters. |
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



MIT License. Copyright (c) 2020 Strontic.


