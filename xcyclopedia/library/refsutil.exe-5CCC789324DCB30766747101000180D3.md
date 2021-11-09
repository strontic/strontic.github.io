---
title: refsutil.exe | refsutil.exe
excerpt: What is refsutil.exe?
---

# refsutil.exe 

* File Path: `C:\WINDOWS\system32\refsutil.exe`
* Description: refsutil.exe

## Hashes

Type | Hash
-- | --
MD5 | `5CCC789324DCB30766747101000180D3`
SHA1 | `173746C97F3309A65DB189BFF315690924725CCC`
SHA256 | `D389F047FD6E6CE8AD3E4C300ADD255009C7F812F9FAF5CF70BB33647D3F7178`
SHA384 | `7959FBFBC0D2ABAF66478BB02299B8EC37981BA5D04BB2FC7FB58D209274C26A5DB6DE3F54245F718978668636442DC2`
SHA512 | `2E2DD2C001E289C3D1D202667111985A1ABEE6C3383A52EF5BE379E3822DCCB188D234FA2644E9CEC5D8007877C4CF186E9C00EC1EB63ECD12B18F9995B8EEC4`
SSDEEP | `24576:wRauzyKh1fgaeSc4PxSKjzNUOIgu/m14yfa:wRauzB1fgaeZ4PxJZDIro4yfa`
IMP | `9D7E7AE63DD0595F0753412A9B687AC2`
PESHA1 | `6892E52C882EF6C248CF6B07E2F70FB3BEEB6F69`
PE256 | `61756FD1387FF6C0654686066852167310F2C29E9DDBC724CADAD2847E35A349`

## Runtime Data

### Usage (stdout):
```cmhg
---- Commands Supported ----
fixboot         Repair boot sectors
leak            Leak Detection and Fixing
salvage         Salvage operations for corrupt volume
triage          Handle corruptions
streamsnapshot  Stream snapshot management

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\refsutil.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: refsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/d389f047fd6e6ce8ad3e4c300add255009c7f812f9faf5cf70bb33647d3f7178/detection



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


