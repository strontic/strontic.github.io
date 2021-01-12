---
title: compact.exe | File Compress Utility
excerpt: What is compact.exe?
---

# compact.exe 

* File Path: `C:\Windows\system32\compact.exe`
* Description: File Compress Utility

## Hashes

Type | Hash
-- | --
MD5 | `278549BBD0CE09F011C1B8481576CA0C`
SHA1 | `8AD4FF0884AD295489495EDCCEECAF2595D96FF3`
SHA256 | `6245640E75E1E55AF426F8D9A779B8478F8034479AD5CA7D49E5BEBEB823B76A`
SHA384 | `4DD1DCDD1E49D0D078A0908383C1AEBA29E723C5844103E9E7443D24751357BDB1A0A2D3E4D2AF0A4FBECF10B55DB9DB`
SHA512 | `AB07478DDF1A38B1E39D1EA31FCB47CB4B3B24D68B2091109D303216F8490CAE94EE9BD468B53B6B15CBBE50E513160FDED583BABFEC575B10A8F39A4E34C26B`
SSDEEP | `768:pq9T3sJh6bx2X1YMDgvILb107Y7fKHvApyMuuoJQcTlpHpoaqEzsztq5uIVTZ:whXt0YcgvIP14t493oJQcTlpHp1qzzts`
IMP | `928C9114035A0164EB94B966F4A358C8`
PESHA1 | `E914796C6714E0B6BA3024A07635E4A33BFD4363`
PE256 | `2EB1147B3CAF5FA01B4F1D76DA9420CAA6949B4B1E09D46A3981F63634996CA2`

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

### Loaded Modules:

Path |
-- |
C:\Windows\system32\compact.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: COMPACT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/6245640e75e1e55af426f8d9a779b8478f8034479ad5ca7d49e5bebeb823b76a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\compact.exe](compact.exe-A3BBBFB18D598EF2E494F6FCC77EE26B.md) | 38
[C:\WINDOWS\system32\compact.exe](compact.exe-BD1137CD6B2CEB849D1018709AE8084C.md) | 38
[C:\Windows\system32\WofUtil.dll](WofUtil.dll-15FB7F0BC6665C5F339E6D0811EE2205.md) | 35

## Possible Misuse

*The following table contains possible examples of `compact.exe` being misused. While `compact.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [adjectives.txt](https://github.com/eset/malware-ioc/blob/master/kryptocibule/adjectives.txt) | `compact` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020 Strontic.


