---
title: mftrace.exe | Media Foundation Tracing Application
excerpt: What is mftrace.exe?
---

# mftrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mftrace.exe`
* Description: Media Foundation Tracing Application

## Hashes

Type | Hash
-- | --
MD5 | `C4E8F0C917D4AD90670DB8684FF0AC41`
SHA1 | `5A7D5CC81B2662C69D80D580E9F13C49D6595F5F`
SHA256 | `C8450299DBA10DAF152B3568517C6DF5935DEF941FAB4067AE39E829152FF3B1`
SHA384 | `C12F361DD20DD6CB90C32A3F5C5CFA59C63BB3C58FADFA98E0B758690962EB8963C740FEEAC84E304A4AB913A6FA2CA1`
SHA512 | `0E543E79BC3A89F2C972DEAA717782A2EE26B4D2ADD10F81019F173B1D714E1411BB4336357156DC311205564A3D47BBC77724AA5156155D3B021B896AC16F62`
SSDEEP | `6144:KsWcdSeCwA4JufPCkXZ/6EVAMgzjcW48ibHMT5pZJ5pZxEOx:ZWeSezAnXCkXZ/6EWI0T5pZJ5pZxd`
IMP | `5CAF5F64A6BFCA4E3879DCC7700176A3`
PESHA1 | `A7F37F3D75D8622E1CF02A9BD8D0086036F99464`
PE256 | `088846088C70ACF2B5D9130A0AD817811AC02DEA22BA52B226F2EB4875FD8BFC`

## Runtime Data

### Usage (stdout):
```cmhg
For more information on a specific command, type HELP command-name
ASSOC          Displays or modifies file extension associations.
ATTRIB         Displays or changes file attributes.
BREAK          Sets or clears extended CTRL+C checking.
BCDEDIT        Sets properties in boot database to control boot loading.
CACLS          Displays or modifies access control lists (ACLs) of files.
CALL           Calls one batch program from another.
CD             Displays the name of or changes the current directory.
CHCP           Displays or sets the active code page number.
CHDIR          Displays the name of or changes the current directory.
CHKDSK         Checks a disk and displays a status report.
CHKNTFS        Displays or modifies the checking of disk at boot time.
CLS            Clears the screen.
CMD            Starts a new instance of the Windows command interpreter.
COLOR          Sets the default console foreground and background colors.
COMP           Compares the contents of two files or sets of files.
COMPACT        Displays or alters the compression of files on NTFS partitions.
CONVERT        Converts FAT volumes to NTFS.  You cannot convert the
               current drive.
COPY           Copies one or more files to another location.
DATE           Displays or sets the date.
DEL            Deletes one or more files.
DIR            Displays a list of files and subdirectories in a directory.
DISKPART       Displays or configures Disk Partition properties.
DOSKEY         Edits command lines, recalls Windows commands, and 
               creates macros.
DRIVERQUERY    Displays current device driver status and properties.
ECHO           Displays messages, or turns command echoing on or off.
ENDLOCAL       Ends localization of environment changes in a batch file.
ERASE          Deletes one or more files.
EXIT           Quits the CMD.EXE program (command interpreter).
FC             Compares two files or sets of files, and displays the 
               differences between them.
FIND           Searches for a text string in a file or files.
FINDSTR        Searches for strings in files.
FOR            Runs a specified command for each file in a set of files.
FORMAT         Formats a disk for use with Windows.
FSUTIL         Displays or configures the file system properties.
FTYPE          Displays or modifies file types used in file extension 
               associations.
GOTO           Directs the Windows command interpreter to a labeled line in 
               a batch program.
GPRESULT       Displays Group Policy information for machine or user.
GRAFTABL       Enables Windows to display an extended character set in 
               graphics mode.
HELP           Provides Help information for Windows commands.
ICACLS         Display, modify, backup, or restore ACLs for files and 
               directories.
IF             Performs conditional processing in batch programs.
LABEL          Creates, changes, or deletes the volume label of a disk.
MD             Creates a directory.
MKDIR          Creates a directory.
MKLINK         Creates Symbolic Links and Hard Links
MODE           Configures a system device.
MORE           Displays output one screen at a time.
MOVE           Moves one or more files from one directory to another 
               directory.
OPENFILES      Displays files opened by remote users for a file share.
PATH           Displays or sets a search path for executable files.
PAUSE          Suspends processing of a batch file and displays a message.
POPD           Restores the previous value of the current directory saved by 
               PUSHD.
PRINT          Prints a text file.
PROMPT         Changes the Windows command prompt.
PUSHD          Saves the current directory then changes it.
RD             Removes a directory.
RECOVER        Recovers readable information from a bad or defective disk.
REM            Records comments (remarks) in batch files or CONFIG.SYS.
REN            Renames a file or files.
RENAME         Renames a file or files.
REPLACE        Replaces files.
RMDIR          Removes a directory.
ROBOCOPY       Advanced utility to copy files and directory trees
SET            Displays, sets, or removes Windows environment variables.
SETLOCAL       Begins localization of environment changes in a batch file.
SC             Displays or configures services (background processes).
SCHTASKS       Schedules commands and programs to run on a computer.
SHIFT          Shifts the position of replaceable parameters in batch files.
SHUTDOWN       Allows proper local or remote shutdown of machine.
SORT           Sorts input.
START          Starts a separate window to run a specified program or command.
SUBST          Associates a path with a drive letter.
SYSTEMINFO     Displays machine specific properties and configuration.
TASKLIST       Displays all currently running tasks including services.
TASKKILL       Kill or stop a running process or application.
TIME           Displays or sets the system time.
TITLE          Sets the window title for a CMD.EXE session.
TREE           Graphically displays the directory structure of a drive or 
               path.
TYPE           Displays the contents of a text file.
VER            Displays the Windows version.
VERIFY         Tells Windows whether to verify that your files are written
               correctly to a disk.
VOL            Displays a disk volume label and serial number.
XCOPY          Copies files and directory trees.
WMIC           Displays WMI information inside interactive command shell.

For more information on tools see the command-line reference in the online help.
Listening to ETW events (CTRL+C to end)
           __M_F_T_R_A_C_E___LOG__

PID, TID    Time (UTC)    TraceMessage
--------- --------------  ------------
4036,1084 21:44:50.50525 TraceOSVersion @ OS version (BuildLabEx): 19041.1.x86fre.vb_release.191206-1406
4036,1084 21:44:50.50525 TraceMFDetoursVersion @ MFDetours version 1.1.0.1
4036,1084 21:44:50.50547 TraceEnabledKeywords @ Keywords and levels: Default 4, Detours 4, MFDebugHlp 4, Kernel32Export 4, MFExport 4, MFPlatExport 4, MFPlayExport 4, MFReadWriteExport 4, Ole32Export 4, wmvCoreExport 4, MFPublic 4, IMFActivate 4, IMFAsyncCallback 4, IMFAttributes 4, IMFClock 4, IMFClockStateSink 4, IMFMediaEventGenerator 4, IMFMediaSession 4, IMFMediaSink 4, IMFMediaSource 4, IMFMediaStream 4, IMFPMediaPlayer 4, IMFPMediaItem 4
4036,1084 21:44:50.50553 TraceEnabledKeywords @ Keywords and levels: IMFPMediaPlayerCallback 4, IMFPresentationClock 4, IMFQualityAdvise 4, IMFQualityAdvise2 4, IMFQualityManager 4, IMFRateControl 4, IMFSample 4, IMFSinkWriter 4, IMFSourceReader 4, IMFSourceReaderCallback 4, IMFSourceResolver 4, IMFStreamSink 4, IMFTopology 4, IMFTopologyNode 4, IMFTopoLoader 4, IMFTransform 4, IMediaObject 4, IMFSchemeHandler 4, IMFByteStream 4, IMFByteStreamHandler 4
4036,1084 21:44:50.50554 TraceEnabledKeywords @ Keywords and levels: IMFReadWriteClassFactory 4, IFilterGraph 4, IGraphBuilder 4, IMediaControl 4, IMemInputPin 4, IWMReader 4, IWMReaderCallback 4
4036,1084 21:44:50.50645 CMFMediaSessionDetours::Attach @02A64350 Presentation clock @02A69ED0
4036,1084 21:44:50.50646 CMFMediaSessionDetours::Attach @02A64350 Rate control @02A64358
           __M_F_T_R_A_C_E___LOG__
Total events received: 7             

```

### Usage (stderr):
```cmhg
Failed with hr=0x80070057 (ERROR_INVALID_PARAMETER)
Use the '-v' option to get further details

```

### Child Processes:
conhost.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\mftrace.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mftrace.exe
* Product Name: Media Foundation Tracing Application
* Company Name: Microsoft
* File Version: 1.1.0.1
* Product Version: 1.1.0.1
* Language: Language Neutral
* Legal Copyright: (c) Microsoft.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\mftrace.exe](mftrace.exe-4A18EDD320539231C508F88BA080C178.md) | 63

## Possible Misuse

*The following table contains possible examples of `mftrace.exe` being misused. While `mftrace.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\mftrace.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Name: Mftrace.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe cmd.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Description: Launch cmd.exe as a subprocess of Mftrace.exe.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of cmd.exe as a subprocess of Mftrace.exe.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe powershell.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of powershell.exe as a subprocess of Mftrace.exe.`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


