---
title: refsutil.exe | refsutil.exe
---

# refsutil.exe 

* File Path: `C:\windows\system32\refsutil.exe`
* Description: refsutil.exe
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `247E40196DBDB030E3FE53795BD23D11`
SHA1 | `82521B5DD6BCD0FF9928C09A3B7253BE0EAB7FD6`
SHA256 | `9ECACE2A69D7A34B5B98D72412DEBA5610AD0227B68312CBF631EB0C9C172BCA`
SHA384 | `4FDF16463656061D4E5A422FA0050E3D81F3E7B7847DEBEC7630EC876FB20FDD96CBC0662E93EE842631097A401BDDC8`
SHA512 | `A8AB5B0FA0329C17C473005B3B15327FFF669A5DEEC38CC65DC194FD3B095C471764968BCE0D7825C3B7F1170C5D56B5FEF90DA560BB72E5C9BFA9A7550B4D93`
SSDEEP | `24576:idDk+o6rUDSDCOpBpfa/cZDARYjDheKCrDSRidqYitMK:Yw+/rUeBdw2DA4wK2DyidRitM`

## Runtime Data

### Usage (stdout):
```Batchfile
---- Commands Supported ----
fixboot   Repair boot sectors
leak      Leak Detection and Fixing
salvage   Salvage operations for corrupt volume
triage    Handle corruptions

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: refsutil.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## ReFSUtil

>Applies to: Windows Server 2019, Windows 10

ReFSUtil is a tool included in Windows and Windows Server that attempts to diagnose heavily damaged ReFS volumes, identify remaining files, and copy those files to another volume. This comes in Windows 10 in the %SystemRoot%\Windows\System32 folder or in Windows Server in the %SystemRoot%\\System32 folder.

ReFS salvage is the primary function of ReFSUtil at present, and is useful for recovering data from volumes that show as RAW in Disk Management. ReFS Salvage has two phases: Scan Phase and a Copy Phase. In automatic mode, the Scan Phase and Copy Phase will run sequentially. In manual
mode, each phase can be run separately. Progress and logs are saved in a working directory to allow phases to be run separately as well as Scan Phase to be paused and resumed. ReFSutil should not need to be used unless the volume is
RAW. If read-only, then data is still accessible.

### Automatic mode command line usage

#### Quick automatic mode command line usage

```dos
refsutil salvage -QA <source volume> <working directory> <target directory> <options>
```
It will perform a Quick Scan Phase followed by a Copy Phase. This mode runs
quicker as it assumes some critical structures of the volume are not corrupted
and so there is no need to scan the entire volume to locate them. This also
reduces the recovery of stale files/directories/volumes.

#### Full automatic mode command line usage

```dos
refsutil salvage -FA <source volume> <working directory> <target directory> <options>
```

It will perform a Full Scan Phase followed by a Copy Phase. This mode may take a
long time as it will scan the entire volume for any recoverable
files/directories/volumes.

### Manual mode command line usage

#### Diagnose phase command line usage

```dos
refsutil salvage -D <source volume> <working directory> <options>
```

First, try to determine if \<source volume\> is an ReFS volume and determine if
the volume is mountable. When a volume is not-mountable, reason(s) will be
determined. This is a standalone phase.

#### Quick Scan phase command line usage

```dos
refsutil salvage -QS <source volume> <working directory> <options>
```

Quick Scan \<source volume\> for any recoverable files. This mode runs quicker
as it assumes some critical structures of the volume are not corrupted and so
there is no need to scan the entire volume to locate them. This also reduces the
recovery of stale files/directories/volumes. Discovered files will be logged to
"foundfiles.\<volume signature\>.txt" under \<working directory\>. If the Scan
Phase was previously stopped, running with the -QS flag again will resume the
scan from where it left off.

#### Full Scan phase command line usage

```dos
refsutil salvage -FS <source volume> <working directory> <options>
```

Scan entire \<source volume\> for any recoverable files. This mode may take a
long time as it will scan the entire volume for any recoverable files.
Discovered files will be logged to "foundfiles.\<volume signature\>.txt" under
\<working directory\>. If the Scan Phase was previously stopped, running with
the -FS flag again will resume the scan from where it left off.

#### Copy phase command line usage

```dos
refsutil salvage -C <source volume> <working directory> <target directory>
<options>
```

Copy all files described in "foundfiles.\<volume signature\>.txt" to \<target
directory\>. If Scan Phase is stopped too early, "foundfiles.\<volume
signature\>.txt" may not have been written yet and so no file will be copied to
\<target directory\>.

#### Copy phase with list command line usage

```dos
refsutil salvage -SL <source volume> <working directory> <target
directory> <file list> <options>
```

Copy all the files in \<file list\> from \<source volume\> to \<target
directory\>. The files in \<file list\> must have first been identified by the
Scan Phase though the scan need not have been run to completion. \<file list\>
can be generated by copying "foundfiles.\<volume signature\>.txt" to a new file,
removing lines referencing files that shouldn't be restored, and preserving
files that should be restored. The PowerShell cmdlet Select-String may be
helpful in filtering "foundfiles.\<volume signature\>.txt" to only include
desired paths, extensions, or file names.

#### Copy phase with interactive console

```dos
refsutil salvage -IC <source volume> <working directory> <options>
```

Salvage files in an interactive console for advanced users. This mode also
requires files generated from either of the Scan Phases.

### Parameters

| Parameter             | Description                                                                     |
| --------------------- | --------------------------------------------------------------------------------------- |
| \<source volume\>     | ReFS volume to process. Drive letter in format "L:", or a path to the volume mount point.           |
| \<working directory\> | Location to store temporary information and logs. It must **not** be located on \<source volume\>.  |
| \<target directory\>  | Location where identified files will be copied to. It must **not** be located on \<source volume\>. |
| \-m         | Recover all possible files including deleted ones. This option will be ignored on refsutil salvage v1. WARNING: Not only this will take longer time to run, it can lead to unexpected result. |
| \-v         | Verbose mode                                                                                           |
| \-x         | Force the volume to dismount first if necessary. All opened handles to the volume would then be invalid. Eg: refsutil salvage -QA R: N:\\WORKING N:\\DATA -x                                  |

---



MIT License. Copyright (c) 2020 Strontic.


