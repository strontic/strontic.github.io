---
title: compact.exe | File Compress Utility
excerpt: What is compact.exe?
---

# compact.exe 

* File Path: `C:\Windows\SysWOW64\compact.exe`
* Description: File Compress Utility

## Hashes

Type | Hash
-- | --
MD5 | `D9A6C940D8AF7BFBA08D010B85F155A2`
SHA1 | `C6E7DF7BBDAE0AE442C0D95B4DA31BEE14918D48`
SHA256 | `23867E6ED3A2A7355E5E129C6C795EBE9C858A5ABB13ED575B9E7814CCD19282`
SHA384 | `0A57AD415A991040A6B61D2BD2F279F772CD0E1A46AB004EFC4CC3F6D82C38043B8EB86595FEFBCF033390841227808B`
SHA512 | `CDB480BF5FF087671EF5A7D4E655289C859AE6A2B8A7CB41C0C7A8D29BCA59E8FD1E8491A15050C293E3363FC2CB8FD376C0605670D6AD5F118D8A104CA581D3`
SSDEEP | `768:CZQMj1pHpILF3CP7rGE5ibfI3A8nkLwV6r0kftjjo8X82HSDWYvzPxjGr5u1KJda:CZQMj1pHpcF3uTUwwr06tHlYvzpjGr5n`
IMP | `F62B024CE3F1C2441731CA2486368509`
PESHA1 | `3ABB1968AA8E11F94919FAECFBDF9225F0FFF5AB`
PE256 | `CC64E79E6B2487AF6620C733A0E3A791C334B78569D5608C177E55D095A98758`

## Runtime Data

### Usage (stdout):
```cmhg
Displays or alters the compression of files on NTFS partitions.

COMPACT [/C | /U] [/S[:dir]] [/A] [/I] [/F] [/Q] [/EXE[:algorithm]]
        [/CompactOs[:option] [/WinDir:dir]] [filename [...]]

  /C         Compresses the specified files.  Directories will be marked
             so that files added afterward will be compressed unless /EXE
             is specified.
  /U         Uncompresses the specified files.  Directories will be marked
             so that files added afterward will not be compressed.  If
             /EXE is specified, only files compressed as executables will
             be uncompressed; if this is omitted, only NTFS compressed
             files will be uncompressed.
  /S         Performs the specified operation on files in the given
             directory and all subdirectories.  Default "dir" is the
             current directory.
  /A         Displays files with the hidden or system attributes.  These
             files are omitted by default.
  /I         Continues performing the specified operation even after errors
             have occurred.  By default, COMPACT stops when an error is
             encountered.
  /F         Forces the compress operation on all specified files, even
             those which are already compressed.  Already-compressed files
             are skipped by default.
  /Q         Reports only the most essential information.
  /EXE       Use compression optimized for executable files which are read
             frequently and not modified.  Supported algorithms are:
             XPRESS4K  (fastest) (default)
             XPRESS8K
             XPRESS16K
             LZX       (most compact)
  /CompactOs Set or query the system's compression state.  Supported options are:
             query  - Query the system's Compact state.
             always - Compress all OS binaries and set the system state to Compact
                      which remains unless administrator changes it.
             never  - Uncompress all OS binaries and set the system state to non
                      Compact which remains unless administrator changes it.
  /WinDir    Used with /CompactOs:query, when querying the offline OS. Specifies
             the directory where Windows is installed.
  filename   Specifies a pattern, file, or directory.

  Used without parameters, COMPACT displays the compression state of
  the current directory and any files it contains. You may use multiple
  filenames and wildcards.  You must put spaces between multiple
  parameters.

```

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: COMPACT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.831 (WinBuild.160101.0800)
* Product Version: 10.0.17763.831
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/23867e6ed3a2a7355e5e129c6c795ebe9c858a5abb13ed575b9e7814ccd19282/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\compact.exe](compact.exe-2FF6DBD252522101AB50FDFF9BC73164.md) | 41
[C:\Windows\SysWOW64\compact.exe](compact.exe-5CB107F69062D6D387F4F7A14737220E.md) | 35
[C:\Windows\SysWOW64\WofUtil.dll](WofUtil.dll-14ABE0012FF8B7BA24C775A664E65772.md) | 40

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


