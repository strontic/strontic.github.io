---
title: mftrace.exe | Media Foundation Tracing Application
excerpt: What is mftrace.exe?
---

# mftrace.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mftrace.exe`
* Description: Media Foundation Tracing Application

## Hashes

Type | Hash
-- | --
MD5 | `E95DF4CB73BE53ABB111BEE9F166D716`
SHA1 | `A2980132E440392D20E36B0DF1EFA23A2D0B3D7F`
SHA256 | `737B3264A2C58FC6721ACBAB1EB33A905928B59524BC6B96F29DA7527E7FA2CE`
SHA384 | `3214FAE3686DED13AC843996C40BF7B8293AEE01FBE454EF3066D33C5141D3768FDD0B89B86F100B36BA080FFC0F24D7`
SHA512 | `2B8A3326CFF74B951AF89C9C15800BD360F2FB6E2CD0FF9B6FC67A5BDF5FE21CC3FC8EA5B8F787ACDED1A27266BDF7F43E78CCB3B09F0329085193B5922C7A52`
SSDEEP | `6144:1EyiBAjmdPD0Yq3smMN1h6ftv/C0nJPAEtAz2Ki:1jwPPq8m+mxC0nJPAEU2Ki`
IMP | `42443E9A79C89F639C2DEEF11B71ECC4`
PESHA1 | `C2E8DB26695C4FBD25A4BFD57113CDBD41F3FFCA`
PE256 | `5AA67A6838A8E99A4495618EA64076D5FF4E75ABFAD8BCB28376D5CC3AB31E86`

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
8208,CC8 21:40:07.35592 TraceOSVersion @ OS version (BuildLabEx): 19041.1.amd64fre.vb_release.191206-1406
8208,CC8 21:40:07.35593 TraceMFDetoursVersion @ MFDetours version 1.1.0.1
8208,CC8 21:40:07.35595 TraceEnabledKeywords @ Keywords and levels: Default 4, Detours 4, MFDebugHlp 4, Kernel32Export 4, MFExport 4, MFPlatExport 4, MFPlayExport 4, MFReadWriteExport 4, Ole32Export 4, wmvCoreExport 4, MFPublic 4, IMFActivate 4, IMFAsyncCallback 4, IMFAttributes 4, IMFClock 4, IMFClockStateSink 4, IMFMediaEventGenerator 4, IMFMediaSession 4, IMFMediaSink 4, IMFMediaSource 4, IMFMediaStream 4, IMFPMediaPlayer 4, IMFPMediaItem 4
8208,CC8 21:40:07.35600 TraceEnabledKeywords @ Keywords and levels: IMFPMediaPlayerCallback 4, IMFPresentationClock 4, IMFQualityAdvise 4, IMFQualityAdvise2 4, IMFQualityManager 4, IMFRateControl 4, IMFSample 4, IMFSinkWriter 4, IMFSourceReader 4, IMFSourceReaderCallback 4, IMFSourceResolver 4, IMFStreamSink 4, IMFTopology 4, IMFTopologyNode 4, IMFTopoLoader 4, IMFTransform 4, IMediaObject 4, IMFSchemeHandler 4, IMFByteStream 4, IMFByteStreamHandler 4
8208,CC8 21:40:07.35600 TraceEnabledKeywords @ Keywords and levels: IMFReadWriteClassFactory 4, IFilterGraph 4, IGraphBuilder 4, IMediaControl 4, IMemInputPin 4, IWMReader 4, IWMReaderCallback 4
8208,CC8 21:40:07.35690 CMFMediaSessionDetours::Attach @000001B321C189C0 Presentation clock @000001B321C1EB00
8208,CC8 21:40:07.35708 CMFMediaSessionDetours::Attach @000001B321C189C0 Rate control @000001B321C189D0
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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\mftrace.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a


## Possible Misuse

*The following table contains possible examples of `mftrace.exe` being misused. While `mftrace.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\mftrace.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Name: Mftrace.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe cmd.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Description: Launch cmd.exe as a subprocess of Mftrace.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of cmd.exe as a subprocess of Mftrace.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe powershell.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of powershell.exe as a subprocess of Mftrace.exe.` | 



MIT License. Copyright (c) 2020 Strontic.


