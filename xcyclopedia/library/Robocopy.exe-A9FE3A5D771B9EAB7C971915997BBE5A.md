﻿---
title: Robocopy.exe | Microsoft Robocopy
excerpt: What is Robocopy.exe?
---

# Robocopy.exe 

* File Path: `C:\windows\SysWOW64\Robocopy.exe`
* Description: Microsoft Robocopy

## Hashes

Type | Hash
-- | --
MD5 | `A9FE3A5D771B9EAB7C971915997BBE5A`
SHA1 | `C9495F0BA6ABE6CAF06687E75562657B473B22B2`
SHA256 | `7CFF03F890334150CE3F369C395781E0809911623543150B418357724D2CC459`
SHA384 | `79762093654E1A9CFF8C557FE18E4B5C4493B51C3C0F6A3F3EA85CE20588AE7FF2989C280FD6C92A9F66498668748AB7`
SHA512 | `E15B334A41CEF31C06DF89BAF673726D11FEA355AAD14F0171AD227699CD2D704532F503110818289E96A1A4AE389DE12EA34DF2B94A973F121A308021636EB7`
SSDEEP | `3072:7npwwnzfTkNa5LTERtJF4qr8Q7SiStmZ/4Pd3RJudKDm:zpwqBTEz0PtGC3i`

## Signature

* Status: The file C:\windows\SysWOW64\Robocopy.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: robocopy.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Robocopy.exe` being misused. While `Robocopy.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\robocopy.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- robocopy.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_lateral_movement.yml) | `- '\robocopy.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `Name: Robocopy.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- Command: Robocopy.exe C:\SourceFolder C:\DestFolder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- Command: Robocopy.exe \\SERVER\SourceFolder C:\DestFolder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Robocopy.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Robocopy.yml) | `- https://social.technet.microsoft.com/wiki/contents/articles/1073.robocopy-and-a-few-examples.aspx`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## robocopy

Copies file data from one location to another.

### Syntax

```
robocopy <source> <destination> [<file>[ ...]] [<options>]
```

For example, to copy a file named *yearly-report.mov* from *c:\reports* to a file share *\\\\marketing\videos* while enabling multi-threading for higher performance (with the **/mt** parameter) and the ability to restart the transfer in case it's interrupted (with the **/z** parameter), type:

```dos
robocopy c:\reports '\\marketing\videos' yearly-report.mov /mt /z
```

#### Parameters

| Parameter | Description |
|--|--|
| `<source>` | Specifies the path to the source directory. |
| `<destination>` | Specifies the path to the destination directory. |
| `<file>` | Specifies the file or files to be copied. Wildcard characters (**&#42;** or **?**) are supported. If you don't specify this parameter, `*.*` is used as the default value. |
| `<options>` | Specifies the options to use with the **robocopy** command, including **copy**, **file**, **retry**, **logging**, and **job** options. |

##### Copy options

| Option | Description |
|--|--|
| /s | Copies subdirectories. This option automatically excludes empty directories. |
| /e | Copies subdirectories. This option automatically includes empty directories. |
| /lev:`<n>` | Copies only the top *n* levels of the source directory tree. |
| /z | Copies files in restartable mode. In restartable mode, should a file copy be interrupted, Robocopy can pick up where it left off rather than re-copying the entire file. |
| /b | Copies files in backup mode. Backup mode allows Robocopy to override file and folder permission settings (ACLs). This allows you to copy files you might otherwise not have access to, assuming it's being run under an account with sufficient privileges.|
| /zb | Copies files in restartable mode. If file access is denied, switches to backup mode. |
| /j | Copies using unbuffered I/O (recommended for large files). |
| /efsraw | Copies all encrypted files in EFS RAW mode. |
| /copy:`<copyflags>` | Specifies which file properties to copy. The valid values for this option are:<ul><li>**D** - Data</li><li>**A** - Attributes</li><li>**T** - Time stamps</li><li>**S** - NTFS access control list (ACL)</li><li>**O** - Owner information</li><li>**U** - Auditing information</li></ul>The default value for this option is **DAT** (data, attributes, and time stamps). |
| /dcopy:`<copyflags>`| Specifies what to copy in directories. The valid values for this option are:<ul><li>**D** - Data</li><li>**A** - Attributes</li><li>**T** - Time stamps</li></ul>The default value for this option is **DA** (data and attributes). |
| /sec | Copies files with security (equivalent to **/copy:DATS**). |
| /copyall | Copies all file information (equivalent to **/copy:DATSOU**). |
| /nocopy | Copies no file information (useful with **/purge**). |
| /secfix | Fixes file security on all files, even skipped ones. |
| /timfix | Fixes file times on all files, even skipped ones. |
| /purge | Deletes destination files and directories that no longer exist in the source. Using this option with the **/e** option and a destination directory, allows the destination directory security settings to not be overwritten. |
| /mir | Mirrors a directory tree (equivalent to **/e** plus **/purge**). Using this option with the **/e** option and a destination directory, overwrites the destination directory security settings. |
| /mov | Moves files, and deletes them from the source after they are copied. |
| /move | Moves files and directories, and deletes them from the source after they are copied. |
| /a+:[RASHCNET] | Adds the specified attributes to copied files.  The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li></ul> |
| /a-:[RASHCNET] | Removes the specified attributes from copied files. The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li></ul> |
| /create | Creates a directory tree and zero-length files only. |
| /fat | Creates destination files by using 8.3 character-length FAT file names only. |
| /256 | Turns off support for paths longer than 256 characters. |
| /mon:`<n>` | Monitors the source, and runs again when more than *n* changes are detected. |
| /mot:`<m>` | Monitors the source, and runs again in *m* minutes, if changes are detected. |
| /MT`[:n]` | Creates multi-threaded copies with *n* threads. *n* must be an integer between 1 and 128. The default value for *n* is 8. For better performance, redirect your output using **/log** option.<p>The **/mt** parameter can't be used with the **/ipg** and **/efsraw** parameters. |
| /rh:hhmm-hhmm | Specifies run times when new copies may be started. |
| /pf | Checks run times on a per-file (not per-pass) basis. |
| /ipg:n | Specifies the inter-packet gap to free bandwidth on slow lines. |
| /sl | Don't follow symbolic links and instead create a copy of the link. |
| /nodcopy | Copies no directory info (the default **/dcopy:DA** is done). |
| /nooffload | Copies files without using the Windows Copy Offload mechanism. |
| /compress | Requests network compression during file transfer, if applicable. |

> [!IMPORTANT]
> When using the **/secfix** copy option, specify the type of security information you want to copy, using one of these additional copy options:
>
>- **/copyall**
>- **/copy:o**
>- **/copy:s**
>- **/copy:u**
>- **/sec**

##### File selection options

| Option | Description |
|--|--|
| /a | Copies only files for which the **Archive** attribute is set. |
| /m | Copies only files for which the **Archive** attribute is set, and resets the **Archive** attribute. |
| /ia:`[RASHCNETO]` | Includes only files for which any of the specified attributes are set.  The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li><li>**O** - Offline</li></ul> |
| /xa:`[RASHCNETO]` | Excludes files for which any of the specified attributes are set. The valid values for this option are: <ul><li>**R** - Read only</li><li>**A** - Archive</li><li>**S** - System</li><li>**H** - Hidden</li><li>**C** - Compressed</li><li>**N** - Not content indexed</li><li>**E** - Encrypted</li><li>**T** - Temporary</li><li>**O** - Offline</li></ul> |
| /xf `<filename>[ ...]` | Excludes files that match the specified names or paths. Wildcard characters (**&#42;** and **?**) are supported. |
| /xd `<directory>[ ...]` | Excludes directories that match the specified names and paths. |
| /xc | Excludes changed files. |
| /xn | Excludes newer files. |
| /xo | Excludes older files. |
| /xx | Excludes extra files and directories. |
| /xl | Excludes "lonely" files and directories. |
| /im | Include modified files (differing change times). |
| /is | Includes the same files. |
| /it | Includes tweaked files. |
| /xc | Excludes existing files with the same timestamp, but different file sizes. |
| /xn | Excludes existing files newer than the copy in the source directory. |
| /xo | Excludes existing files older than the copy in the source directory. |
| /xx | Excludes extra files and directories present in the destination but not the source. Excluding extra files will not delete files from the destination.  |
| /xl | Excludes "lonely" files and directories present in the source but not the destination. Excluding lonely files prevents any new files from being added to the destination. |
| /is | Includes the same files. Same files are identical in name, size, times, and all attributes. |
| /it | Includes "tweaked" files. Tweaked files have the same name, size, and times, but different attributes. |
| /max:`<n>` | Specifies the maximum file size (to exclude files bigger than *n* bytes). |
| /min:`<n>` | Specifies the minimum file size (to exclude files smaller than *n* bytes). |
| /maxage:`<n>` | Specifies the maximum file age (to exclude files older than *n* days or date). |
| /minage:`<n>` | Specifies the minimum file age (exclude files newer than *n* days or date). |
| /maxlad:`<n>` | Specifies the maximum last access date (excludes files unused since *n*). |
| /minlad:`<n>` | Specifies the minimum last access date (excludes files used since *n*) If *n* is less than 1900, *n* specifies the number of days. Otherwise, *n* specifies a date in the format YYYYMMDD. |
| /xj | Excludes junction points, which are normally included by default. |
| /fft | Assumes FAT file times (two-second precision). |
| /dst | Compensates for one-hour DST time differences. |
| /xjd | Excludes junction points for directories. |
| /xjf | Excludes junction points for files. |

##### Retry options

| Option | Description |
|--|--|
| /r:`<n>` | Specifies the number of retries on failed copies. The default value of *n* is 1,000,000 (one million retries). |
| /w:`<n>` | Specifies the wait time between retries, in seconds. The default value of *n* is 30 (wait time 30 seconds). |
| /reg | Saves the values specified in the **/r** and **/w** options as default settings in the registry. |
| /tbd | Specifies that the system will wait for share names to be defined (retry error 67). |

##### Logging options

| Option | Description |
|--|--|
| /l | Specifies that files are to be listed only (and not copied, deleted, or time stamped). |
| /x | Reports all extra files, not just those that are selected. |
| /v | Produces verbose output, and shows all skipped files. |
| /ts | Includes source file time stamps in the output. |
| /fp | Includes the full path names of the files in the output. |
| /bytes | Prints sizes, as bytes. |
| /ns | Specifies that file sizes are not to be logged. |
| /nc | Specifies that file classes are not to be logged. |
| /nfl | Specifies that file names are not to be logged. |
| /ndl | Specifies that directory names are not to be logged. |
| /np | Specifies that the progress of the copying operation (the number of files or directories copied so far) will not be displayed. |
| /eta | Shows the estimated time of arrival (ETA) of the copied files. |
| /log:`<logfile>` | Writes the status output to the log file (overwrites the existing log file). |
| /log+:`<logfile>` | Writes the status output to the log file (appends the output to the existing log file). |
| /unicode | Displays the status output as Unicode text. |
| /unilog:`<logfile>` | Writes the status output to the log file as Unicode text (overwrites the existing log file). |
| /unilog+:`<logfile>` | Writes the status output to the log file as Unicode text (appends the output to the existing log file). |
| /tee | Writes the status output to the console window, as well as to the log file. |
| /njh | Specifies that there is no job header. |
| /njs | Specifies that there is no job summary. |

##### Job options

| Option | Description |
|--|--|
| /job:`<jobname>` | Specifies that parameters are to be derived from the named job file. |
| /save:`<jobname>` | Specifies that parameters are to be saved to the named job file. |
| /quit | Quits after processing command line (to view parameters). |
| /nosd | Indicates that no source directory is specified. |
| /nodd | Indicates that no destination directory is specified. |
| /if | Includes the specified files. |

#### Exit (return) codes

| Value | Description |
|--|--|
| 0 | No files were copied. No failure was encountered. No files were mismatched. The files already exist in the destination directory; therefore, the copy operation was skipped. |
| 1 | All files were copied successfully. |
| 2 | There are some additional files in the destination directory that are not present in the source directory. No files were copied. |
| 3 | Some files were copied. Additional files were present. No failure was encountered. |
| 5 | Some files were copied. Some files were mismatched. No failure was encountered. |
| 6 | Additional files and mismatched files exist. No files were copied and no failures were encountered. This means that the files already exist in the destination directory. |
| 7 | Files were copied, a file mismatch was present, and additional files were present. |
| 8 | Several files did not copy. |

> [!NOTE]
> Any value greater than **8** indicates that there was at least one failure during the copy operation.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


