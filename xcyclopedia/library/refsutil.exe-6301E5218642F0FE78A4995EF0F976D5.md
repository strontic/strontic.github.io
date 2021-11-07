---
title: refsutil.exe | refsutil.exe
excerpt: What is refsutil.exe?
---

# refsutil.exe 

* File Path: `C:\Windows\system32\refsutil.exe`
* Description: refsutil.exe

## Hashes

Type | Hash
-- | --
MD5 | `6301E5218642F0FE78A4995EF0F976D5`
SHA1 | `66FA89D85B279207EC1394B95BD0BD4FFBB4F8E8`
SHA256 | `CE4B9871E0C700095E53BAEC341B8BEA5C4B6D5046561594E5A88F90BBA9E2B5`
SHA384 | `A3D5D526AD59AA26AD58DCF70ADED66B46013090ACBA2E083FDE5ADEBF60F69F90E21D2BEB6D979D6D45B0D7A25690CC`
SHA512 | `91DCFA64D627732415E9783FC293DA074A2FA8C673099806F32244D56B543F5C72C20DF2F48529939D9A80657849365DD6F91C6FDE24B65757A3F13D408E997F`
SSDEEP | `24576:gA7zUA6luPPxxJFuSGzQi9Cnu4eBJbZmB:g4AA6oPPxxJFuSW3Eu4ezFmB`
IMP | `7398FDC9F8A8D73CB40BE75B53BCBE28`
PESHA1 | `F3616828EF23E56633616351079E20A6221166F6`
PE256 | `6C2A4C8B493E595357917E8B8335CEF1F294255999E9314C687335184B620511`

## Runtime Data

### Usage (stdout):
```cmhg
---- Commands Supported ----
fixboot   Repair boot sectors
leak      Leak Detection and Fixing
salvage   Salvage operations for corrupt volume
triage    Handle corruptions

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\refsutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: refsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1151 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1151
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/ce4b9871e0c700095e53baec341b8bea5c4b6d5046561594e5a88f90bba9e2b5/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ReFSUtil

>Applies to: Windows Server 2022, Windows Server 2019, Windows 10

ReFSUtil is a tool included in Windows and Windows Server that attempts to diagnose heavily damaged ReFS volumes, identify remaining files, and copy those files to another volume. This comes in Windows 10 in the `%SystemRoot%\Windows\System32` folder or in Windows Server in the `%SystemRoot%\System32` folder.

ReFS salvage is the primary function of ReFSUtil, and is useful for recovering data from volumes that show as RAW in Disk Management. ReFS Salvage has two phases: Scan Phase and a Copy Phase. In automatic mode, the Scan Phase and Copy Phase will run sequentially. In manual
mode, each phase can be run separately. Progress and logs are saved in a working directory to allow phases to be run separately as well as Scan Phase to be paused and resumed. You shouldn't need to use the ReFSutil tool unless the volume is RAW. If read-only, then data is still accessible.

### Parameters

| Parameter | Description |
|--|--|
| `<source volume>` | Specifies the ReFS volume to process. The drive letter must be formatted as "L:", or you must provide a path to the volume mount point. |
| `<working directory>` | Specifies the location to store temporary information and logs. It must **not** be located on the `<source volume>`. |
| `<target directory>` | Specifies the location where identified files are copied to. It must **not** be located on the `<source volume>`. |
| \-m | Recovers all possible files including deleted ones.<p>**WARNING:** Not only does this parameter cause the process to take longer to run, but it can also lead to unexpected results. |
| \-v | Specifies to use verbose mode. |
| \-x | Forces the volume to dismount first, if necessary. All opened handles to the volume are then invalid. For example, `refsutil salvage -QA R: N:\WORKING N:\DATA -x`. |

### Usage and available options

#### Quick automatic mode command line usage

Performs a Quick Scan Phase followed by a Copy Phase. This mode runs quicker as it assumes some critical structures of the volume aren't corrupted and so there's no need to scan the entire volume to locate them. This also reduces the recovery of stale files/directories/volumes.

```
refsutil salvage -QA <source volume> <working directory> <target directory> <options>
```

#### Full automatic mode command line usage

Performs a Full Scan Phase followed by a Copy Phase. This mode may take a long time as it will scan the entire volume for any recoverable files/directories/volumes.

```
refsutil salvage -FA <source volume> <working directory> <target directory> <options>
```

#### Diagnose phase command line usage (manual mode)

First, try to determine if the `<source volume>` is an ReFS volume and determine if the volume is mountable. If a volume isn't mountable, the reason(s) will be provided. This is a standalone phase.

```
refsutil salvage -D <source volume> <working directory> <options>
```

#### Quick Scan phase command line usage

Performs a Quick Scan of the `<source volume>` for any recoverable files. This mode runs quicker as it assumes some critical structures of the volume are not corrupted and so there's no need to scan the entire volume to locate them. This also reduces the recovery of stale files/directories/volumes. Discovered files are logged to the `foundfiles.<volume signature>.txt` file, located in your `<working directory>`. If the Scan Phase was previously stopped, running with the **-QS** flag again resumes the scan from where it left off.

```
refsutil salvage -QS <source volume> <working directory> <options>
```

#### Full Scan phase command line usage

Scans the entire `<source volume>` for any recoverable files. This mode may take a long time as it will scan the entire volume for any recoverable files. Discovered files will be logged to the `foundfiles.<volume signature>.txt` file, located in your `<working directory>`. If the Scan Phase was previously stopped, running with the **-FS** flag again resumes the scan from where it left off.

```
refsutil salvage -FS <source volume> <working directory> <options>
```

#### Copy phase command line usage

Copies all files described in the `foundfiles.<volume signature>.txt` file to your `<target directory>`. If you stop the Scan Phase too early, it's possible that the the `foundfiles.<volume signature>.txt` file might not yet exist, so no file is copied to the `<target directory>`.

```
refsutil salvage -C <source volume> <working directory> <target directory> <options>
```

#### Copy phase with list command line usage

Copies all the files in the `<file list>` from the `<source volume>` to your `<target directory>`. The files in the `<file list>` must have first been identified by the Scan Phase, though the scan need not have been run to completion. The `<file list>` can be generated by copying `foundfiles.<volume signature>.txt` to a new file, removing lines referencing files that shouldn't be restored, and preserving files that should be restored. The PowerShell cmdlet **Select-String** may be helpful in filtering `foundfiles.<volume signature>.txt` to only include desired paths, extensions, or file names.

```
refsutil salvage -SL <source volume> <working directory> <target directory> <file list> <options>
```

#### Copy phase with interactive console

Advanced users can salvage files using an interactive console. This mode also requires files generated from either of the Scan Phases.

```
refsutil salvage -IC <source volume> <working directory> <options>
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


