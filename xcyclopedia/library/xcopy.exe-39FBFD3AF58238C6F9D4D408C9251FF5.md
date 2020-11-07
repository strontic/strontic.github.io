---
title: xcopy.exe | Extended Copy Utility
excerpt: What is xcopy.exe?
---

# xcopy.exe 

* File Path: `C:\Windows\system32\xcopy.exe`
* Description: Extended Copy Utility

## Hashes

Type | Hash
-- | --
MD5 | `39FBFD3AF58238C6F9D4D408C9251FF5`
SHA1 | `C5BD7815ED18F7E3D1CE93CC47AECF58D908DCA8`
SHA256 | `269EB0728413654856F4B2EE1FA7838CD69672EBC11BAED4CAA63F58C2DF5823`
SHA384 | `27409A9A6F56C88F47482C79A5E63C9D28FF87AAF2E77DDF2C6A90111CC90CE24C0447CFB9DB72A79A45C2CAED64F9A7`
SHA512 | `B1CF7952F4C5D049C6BF076A34ABA5789833EF208C3E8AB1DE300D96C9E7FFCFD13E0B458FF608105395B57CEC7FE0F2DD240C942E9E727E13BF5686C752E336`
SSDEEP | `768:MMrZVvJJntoBFNqe9BGJ3t+yzXzDbJX5t30fRynjjZgxMae:M8ZVvLCB/qOBGJ3tnDzDFLE8nax7e`
IMP | `1EFFE65A4F251E4AE9FA8551F9FCDABB`
PESHA1 | `8694FF3A1C3A67F338DB5C391C989BDB76E99DB9`
PE256 | `6ADD938B26A573378BEFEB6C5CD9E539476C1378227C0979AA62F45D738C03AF`

## Runtime Data

### Usage (stdout):
```cmhg
Copies files and directory trees.

XCOPY source [destination] [/A | /M] [/D[:date]] [/P] [/S [/E]] [/V] [/W]
                           [/C] [/I] [/Q] [/F] [/L] [/G] [/H] [/R] [/T] [/U]
                           [/K] [/N] [/O] [/X] [/Y] [/-Y] [/Z] [/B] [/J]
                           [/EXCLUDE:file1[+file2][+file3]...] [/COMPRESS]

  source       Specifies the file(s) to copy.
  destination  Specifies the location and/or name of new files.
  /A           Copies only files with the archive attribute set,
               doesn't change the attribute.
  /M           Copies only files with the archive attribute set,
               turns off the archive attribute.
  /D:m-d-y     Copies files changed on or after the specified date.
               If no date is given, copies only those files whose
               source time is newer than the destination time.
  /EXCLUDE:file1[+file2][+file3]...
               Specifies a list of files containing strings.  Each string
               should be in a separate line in the files.  When any of the
               strings match any part of the absolute path of the file to be
               copied, that file will be excluded from being copied.  For
               example, specifying a string like \obj\ or .obj will exclude
               all files underneath the directory obj or all files with the
               .obj extension respectively.
  /P           Prompts you before creating each destination file.
  /S           Copies directories and subdirectories except empty ones.
  /E           Copies directories and subdirectories, including empty ones.
               Same as /S /E. May be used to modify /T.
  /V           Verifies the size of each new file.
  /W           Prompts you to press a key before copying.
  /C           Continues copying even if errors occur.
  /I           If destination does not exist and copying more than one file,
               assumes that destination must be a directory.
  /Q           Does not display file names while copying.
  /F           Displays full source and destination file names while copying.
  /L           Displays files that would be copied.
  /G           Allows the copying of encrypted files to destination that does
               not support encryption.
  /H           Copies hidden and system files also.
  /R           Overwrites read-only files.
  /T           Creates directory structure, but does not copy files. Does not
               include empty directories or subdirectories. /T /E includes
               empty directories and subdirectories.
  /U           Copies only files that already exist in destination.
  /K           Copies attributes. Normal Xcopy will reset read-only attributes.
  /N           Copies using the generated short names.
  /O           Copies file ownership and ACL information.
  /X           Copies file audit settings (implies /O).
  /Y           Suppresses prompting to confirm you want to overwrite an
               existing destination file.
  /-Y          Causes prompting to confirm you want to overwrite an
               existing destination file.
  /Z           Copies networked files in restartable mode.
  /B           Copies the Symbolic Link itself versus the target of the link.
  /J           Copies using unbuffered I/O. Recommended for very large files.
  /COMPRESS    Request network compression during file transfer where
               applicable.

The switch /Y may be preset in the COPYCMD environment variable.
This may be overridden with /-Y on the command line.

```

### Usage (stderr):
```cmhg
File cannot be copied onto itself

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\xcopy.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: XCOPY.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/269eb0728413654856f4b2ee1fa7838cd69672ebc11baed4caa63f58c2df5823/detection


## Possible Misuse

*The following table contains possible examples of `xcopy.exe` being misused. While `xcopy.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_bear_activity_gtr19.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_bear_activity_gtr19.yml) | `Image: '*\xcopy.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- xcopy.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_system32.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_system32.yml) | `- 'xcopy*\System32\'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1505.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1505.003/T1505.003.md) | xcopy #{web_shells} #{web_shell_path} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## xcopy

Copies files and directories, including subdirectories.

For examples of how to use this command, see [Examples](#examples).

### Syntax

```
Xcopy <Source> [<Destination>] [/w] [/p] [/c] [/v] [/q] [/f] [/l] [/g] [/d [:MM-DD-YYYY]] [/u] [/i] [/s [/e]] [/t] [/k] [/r] [/h] [{/a | /m}] [/n] [/o] [/x] [/exclude:FileName1[+[FileName2]][+[FileName3]] [{/y | /-y}] [/z] [/b] [/j]
```

#### Parameters

|Parameter|Description|
|---------|-----------|
|\<Source>|Required. Specifies the location and names of the files you want to copy. This parameter must include either a drive or a path.|
|[\<Destination>]|Specifies the destination of the files you want to copy. This parameter can include a drive letter and colon, a directory name, a file name, or a combination of these.|
|/w|Displays the following message and waits for your response before starting to copy files:</br>**Press any key to begin copying file(s)**|
|/p|Prompts you to confirm whether you want to create each destination file.|
|/c|Ignores errors.|
|/v|Verifies each file as it is written to the destination file to make sure that the destination files are identical to the source files.|
|/q|Suppresses the display of **xcopy** messages.|
|/f|Displays source and destination file names while copying.|
|/l|Displays a list of files that are to be copied.|
|/g|Creates decrypted *Destination* files when the destination does not support encryption.|
|/d [:MM-DD-YYYY]|Copies source files changed on or after the specified date only. If you do not include a *MM-DD-YYYY* value, **xcopy** copies all *Source* files that are newer than existing *Destination* files. This command-line option allows you to update files that have changed.|
|/u|Copies files from *Source* that exist on *Destination* only.|
|/i|If *Source* is a directory or contains wildcards and *Destination* does not exist, **xcopy** assumes *Destination* specifies a directory name and creates a new directory. Then, **xcopy** copies all specified files into the new directory. By default, **xcopy** prompts you to specify whether *Destination* is a file or a directory.|
|/s|Copies directories and subdirectories, unless they are empty. If you omit **/s**, **xcopy** works within a single directory.|
|/e|Copies all subdirectories, even if they are empty. Use **/e** with the **/s** and **/t** command-line options.|
|/t|Copies the subdirectory structure (that is, the tree) only, not files. To copy empty directories, you must include the **/e** command-line option.|
|/k|Copies files and retains the read-only attribute on *Destination* files if present on the *Source* files. By default, **xcopy** removes the read-only attribute.|
|/r|Copies read-only files.|
|/h|Copies files with hidden and system file attributes. By default, **xcopy** does not copy hidden or system files|
|/a|Copies only *Source* files that have their archive file attributes set. **/a** does not modify the archive file attribute of the source file. For information about how to set the archive file attribute by using **attrib**, see [Additional References](#additional-references).|
|/m|Copies *Source* files that have their archive file attributes set. Unlike **/a**, **/m** turns off archive file attributes in the files that are specified in the source. For information about how to set the archive file attribute by using **attrib**, see [Additional References](#additional-references).|
|/n|Creates copies by using the NTFS short file or directory names. **/n** is required when you copy files or directories from an NTFS volume to a FAT volume or when the FAT file system naming convention (that is, 8.3 characters) is required on the *Destination* file system. The *Destination* file system can be FAT or NTFS.|
|/o|Copies file ownership and discretionary access control list (DACL) information.|
|/x|Copies file audit settings and system access control list (SACL) information (implies **/o**).|
|/exclude:FileName1[+[FileName2][+[FileName3]( \)]|Specifies a list of files. At least one file must be specified. Each file will contain search strings with each string on a separate line in the file.</br>When any of the strings match any part of the absolute path of the file to be copied, that file will be excluded from being copied. For example, specifying the string **obj** will exclude all files underneath the directory **obj** or all files with the **.obj** extension.|
|/y|Suppresses prompting to confirm that you want to overwrite an existing destination file.|
|/-y|Prompts to confirm that you want to overwrite an existing destination file.|
|/z|Copies over a network in restartable mode.|
|/b|Copies the symbolic link instead of the files. This parameter was introduced in Windows VistaÂ®.|
|/j|Copies files without buffering. Recommended for very large files. This parameter was added in Windows Server 2008 R2.|
|/?|Displays help at the command prompt.|

### Remarks

- Using **/z**

  If you lose your connection during the copy phase (for example, if the server going offline severs the connection), it resumes after you reestablish the connection. **/z** also displays the percentage of the copy operation completed for each file.

- Using **/y** in the COPYCMD environment variable.

  You can use **/y** in the COPYCMD environment variable. You can override this command by using **/-y** on the command line. By default, you are prompted to overwrite.

- Copying encrypted files

  Copying encrypted files to a volume that does not support EFS results in an error. Decrypt the files first or copy the files to a volume that does support EFS.

- Appending files

  To append files, specify a single file for destination, but multiple files for source (that is, by using wildcards or file1+file2+file3 format).

- Default value for *Destination*

  If you omit *Destination*, the **xcopy** command copies the files to the current directory.

- Specifying whether *Destination* is a file or directory

  If *Destination* does not contain an existing directory and does not end with a backslash (\), the following message appears:

  ```
  Does <Destination> specify a file name or directory name on the target(F = file, D = directory)?
  ```

Press F if you want the file or files to be copied to a file. Press D if you want the file or files to be copied to a directory.

  You can suppress this message by using the **/i** command-line option, which causes **xcopy** to assume that the destination is a directory if the source is more than one file or a directory.
- Using the **xcopy** command to set archive attribute for *Destination* files

  The **xcopy** command creates files with the archive attribute set, whether or not this attribute was set in the source file. For more information about file attributes and **attrib**, see [Additional References](#additional-references).

- Comparing **xcopy** and **diskcopy**

  If you have a disk that contains files in subdirectories and you want to copy it to a disk that has a different format, use the **xcopy** command instead of **diskcopy**. Because the **diskcopy** command copies disks track by track, your source and destination disks must have the same format. The **xcopy** command does not have this requirement. Use **xcopy** unless you need a complete disk image copy.

- Exit codes for **xcopy**

  To process exit codes returned by **xcopy**, use the **ErrorLevel** parameter on the **if** command line in a batch program. For an example of a batch program that processes exit codes using **if**, see [Additional References](#additional-references). The following table lists each exit code and a description.

  |Exit code|Description|
  |---------|-----------|
  |0|Files were copied without error.|
  |1|No files were found to copy.|
  |2|The user pressed CTRL+C to terminate **xcopy**.|
  |4|Initialization error occurred. There is not enough memory or disk space, or you entered an invalid drive name or invalid syntax on the command line.|
  |5|Disk write error occurred.|

### Examples

**1.** To copy all the files and subdirectories (including any empty subdirectories) from drive A to drive B, type:

```
xcopy a: b: /s /e
```

**2.** To include any system or hidden files in the previous example, add the<strong>/h</strong> command-line option as follows:

```
xcopy a: b: /s /e /h
```

**3.** To update files in the \Reports directory with the files in the \Rawdata directory that have changed since December 29, 1993, type:

```
xcopy \rawdata \reports /d:12-29-1993
```

**4.** To update all the files that exist in \Reports in the previous example, regardless of date, type:

```
xcopy \rawdata \reports /u
```

**5.** To obtain a list of the files to be copied by the previous command (that is, without actually copying the files), type:

```
xcopy \rawdata \reports /d:12-29-1993 /l > xcopy.out
```

The file xcopy.out lists every file that is to be copied.

**6.** To copy the \Customer directory and all subdirectories to the directory \\\\Public\Address on network drive H:, retain the read-only attribute, and be prompted when a new file is created on H:, type:

```
xcopy \customer h:\public\address /s /e /k /p
```

**7.** To issue the previous command, ensure that **xcopy** creates the \Address directory if it does not exist, and suppress the message that appears when you create a new directory, add the **/i** command-line option as follows:

```
xcopy \customer h:\public\address /s /e /k /p /i
```

**8.** You can create a batch program to perform **xcopy** operations and use the batch **if** command to process the exit code if an error occurs. For example, the following batch program uses replaceable parameters for the **xcopy** source and destination parameters:

```
@echo off
rem COPYIT.BAT transfers all files in all subdirectories of
rem the source drive or directory (%1) to the destination
rem drive or directory (%2)
xcopy %1 %2 /s /e
if errorlevel 4 goto lowmemory
if errorlevel 2 goto abort
if errorlevel 0 goto exit
:lowmemory
echo Insufficient memory to copy files or
echo invalid drive or command-line syntax.
goto exit
:abort
echo You pressed CTRL+C to end the copy operation.
goto exit
:exit
```

To use the preceding batch program to copy all files in the C:\Prgmcode directory and its subdirectories to drive B, type:

```
copyit c:\prgmcode b:
```

The command interpreter substitutes **C:\Prgmcode** for *%1* and **B:** for *%2*, then uses **xcopy** with the **/e** and **/s** command-line options. If **xcopy** encounters an error, the batch program reads the exit code and goes to the label indicated in the appropriate **IF ERRORLEVEL** statement, then displays the appropriate message and exits from the batch program.

**9.** This example copies all the non-empty directories, plus files whose name match the pattern given with the asterisk symbol.

```
xcopy .\toc*.yml ..\..\Copy-To\ /S /Y

rem Output example.
rem  .\d1\toc.yml
rem  .\d1\d12\toc.yml
rem  .\d2\toc.yml
rem  3 File(s) copied
```

In the preceding example, this particular source parameter value **.\\toc\*.yml** copies the same 3 files even if its two path characters **.\\** were removed. However, no files would be copied if the asterisk wildcard was removed from the source parameter, making it just **.\\toc.yml**.

### Additional References

- [Copy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/copy.md)
- [Move](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/move.md)
- [Dir](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/dir.md)
- [Attrib](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/attrib.md)
- [Diskcopy](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/diskcopy.md)
- [If](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/if.md)
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


