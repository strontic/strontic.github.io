---
title: Defrag.exe | Disk Defragmenter Module
excerpt: What is Defrag.exe?
---

# Defrag.exe 

* File Path: `C:\Windows\system32\Defrag.exe`
* Description: Disk Defragmenter Module

## Hashes

Type | Hash
-- | --
MD5 | `E2601E315E9A9837279A23963F5819B0`
SHA1 | `5BB7FDAF33E556323A1152D36B0F9159CC53D291`
SHA256 | `7A18DBBE6CA138389424A7B2C0135BA4A7541C33E0443227F3CF505B58B52A85`
SHA384 | `AC7671CDAC495D43D49884151DA54E6F01E4E9820556BEDFD0479BBB6257EC4AE3DC44F4AA713DCF2BC61102D75A0073`
SHA512 | `66D899EB1F20DF9096B10EE889512E7BFB51114665E7004D41D31AE89253B8972C2947DEAB71E5E20BA3BB8CD70F7F97B798B54B59642F26DCF1381AB0FCF052`
SSDEEP | `3072:naQNgDUs61d6lzUVRmy3kJKk/VUphUuyib4C6c5Q3eSjlR+8qxLijgJyfFOG83Yc:aubs7qg+Wuc3lRGOUZGKc4YFnwjCpW`
IMP | `9233D07CE8B477A0DE3511C3B6B4B24D`
PESHA1 | `AF3C75FD07E52AFEF78C012F7F5EB4BBEFD6D888`
PE256 | `2CFEE0CCE8160159440DABB8DAAA20A81A65CFA59199EF793179FFF9FD4E1E41`

## Runtime Data

### Usage (stdout):
```cmhg

Please specify a volume to perform the operation on. (0x89000007)

Defrag <Volumes> <Operations> [<Options>]

Volumes:
  /C | /AllVolumes      On each volume run only the preferred operations from
                        the given list of operations.
  /E | /VolumesExcept <volume paths>
                        Perform all the given operations on each volume except.
                        those specified. If the exception list is empty, this
                        behaves as /AllVolumes.
  volume paths          Specifies the drive letter followed by a colon, mount point
                        or volume name. More than one volume can be specified.  Run
                        all the given operations on each specified volume..

Operations:
  /A | /Analyze         Perform analysis.
  /B | /BootOptimize    Perform boot optimization to increase boot performance.
  /D | /Defrag          Perform traditional defrag (this is the default). On a tiered
                        volume, traditional defrag is performed only on the Capacity
                        tier.
  /G | /TierOptimize    On tiered volumes, optimize files to reside on the appropriate
                        storage tier.
  /K | /SlabConsolidate On thinly provisioned volumes, perform slab consolidation to
                        increase slab usage efficiency.
  /L | /Retrim          On thinly provisioned volumes, perform retrim to release free
                        slabs. On SSDs perform retrim to improve write performance.
  /O | /Optimize        Perform the proper optimization for each media type.
  /T | /TrackProgress   Track progress of a running operation for a given volume. An
                        instance can show progress only for a single volume. To see
                        progress for another volume launch another instance.
  /U | /PrintProgress   Print the progress of the operation on the screen.
  /V | /Verbose         Print verbose output containing the fragmentation statistics.
  /X | /FreespaceConsolidate
                        Perform free space consolidation, moves free space towards
                        the end of the volume (even on thin provisioned volumes). On
                        tiered volumes consolidation is performed only on the Capacity
                        tier.

Options:
  /H | /NormalPriority  Run the operation at normal priority (default is low).
  /I | /MaxRuntime n    Available only with TierOptimize. Tier optimization would
                        run for at most n seconds on each volume.
       /LayoutFile <file path>
                        Available only with BootOptimize. This file contains the list
                        of files to be optimized.  The default location is
                        %windir%\Prefetch\layout.ini.
  /M | /MultiThread [n] Run the operation on each volume in parallel in the background.
                        For TierOptimize, at most n threads optimize the storage tiers
                        in parallel. Default value of n is 8. All other optimizations
                        ignore n.
       /OnlyPreferred   When volumes are specified explicitly, defrag performs all
                        the given operations on each specified volume.  This switch
                        lets defrag run only the preferred operations, from the
                        given list of operations, on each specified volume.

Examples:
  Defrag C: /U /V
  Defrag C: D: /TierOptimize /MultiThread
  Defrag C:\mountpoint /Analysis /U
  Defrag /C /H /V

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\Defrag.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Defrag.EXE.MUI
* Product Name: Windows Drive Optimizer
* Company Name: Microsoft Corp.
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corp.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7a18dbbe6ca138389424a7b2c0135ba4a7541c33e0443227f3cf505b58b52a85/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\Defrag.exe](Defrag.exe-15EFD404D3065B560876BBE567CE981A.md) | 71
[C:\WINDOWS\system32\Defrag.exe](Defrag.exe-4DC461ACA28988B93236664F7E2CA393.md) | 60
[C:\windows\system32\Defrag.exe](Defrag.exe-537BFBA3084BAE2892C0FCAA08A12C0B.md) | 75
[C:\Windows\system32\Defrag.exe](Defrag.exe-BCBD8C0BFD620A4761C8ACDF96D9CDAE.md) | 71
[C:\Windows\system32\Defrag.exe](Defrag.exe-D340F5AE00E1C33F8BDC538D9888C459.md) | 71
[C:\Windows\system32\Defrag.exe](Defrag.exe-F7AC2F29879A0789A74F87012861A956.md) | 74

## Possible Misuse

*The following table contains possible examples of `Defrag.exe` being misused. While `Defrag.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_apt_slingshot.yml) | `title: Defrag Deactivation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_apt_slingshot.yml) | `TaskName: '\Microsoft\Windows\Defrag\ScheduledDefrag'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/create_remote_thread/sysmon_suspicious_remote_thread.yml) | `- '\defrag.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_apt_slingshot.yml) | `title: Defrag Deactivation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_apt_slingshot.yml) | `- '\Microsoft\Windows\Defrag\ScheduledDefrag'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/raw_access_thread/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\defrag.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## defrag

>Applies to: Windows Server 2022, Windows Server 2019, Windows 10, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Locates and consolidates fragmented files on local volumes to improve system performance.

Membership in the local **Administrators** group, or equivalent, is the minimum required to run this command.

### Syntax

```
defrag <volumes> | /c | /e <volumes>    [/h] [/m [n]| [/u] [v]]
defrag <volumes> | /c | /e <volumes> /a [/h] [/m [n]| [/u] [v]]
defrag <volumes> | /c | /e <volumes> /x [/h] [/m [n]| [/u] [v]]
defrag <volume> [<parameters>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<volume>` | Specifies the drive letter or mount point path of the volume to be defragmented or analyzed. |
| /a | Perform analysis on the specified volumes. |
| /c | Perform the operation on all volumes. |
| /d | Perform traditional defrag (this is the default). On a tiered volume though, traditional defrag is performed only on the Capacity tier. |
| /e | Perform the operation on all volumes except those specified. |
| /g | Optimize the storage tiers on the specified volumes. |
| /h | Run the operation at normal priority (default is low). |
| /i [n] | Tier optimization would run for at most n seconds on each volume. |
| /k | Perform slab consolidation on the specified volumes. |
| /l | Perform retrim on the specified volumes. |
| /m [n] | Run the operation on each volume in parallel in the background. At most n threads optimize the storage tiers in parallel. |
| /o | Perform the proper optimization for each media type. |
| /t | Track an operation already in progress on the specified volume. |
| /u | Print the progress of the operation on the screen. |
| /v | Print verbose output containing the fragmentation statistics. |
| /x | Perform free space consolidation on the specified volumes. |
| /? | Displays this help information. |

##### Remarks

- You can't defragment specific file system volumes or drives, including:

  - Volumes locked by the file system.

  - Volumes the file system marked as dirty, indicating possible corruption.<br>You must run `chkdsk` before you can defragment this volume or drive. You can determine if a volume is dirty by using the `fsutil dirty` command.

  - Network drives.

  - CD-ROMs.

  - File system volumes that aren't **NTFS**, **ReFS**, **Fat** or **Fat32**.

- To perform this procedure, you must be a member of the Administrators group on the local computer, or you must have been delegated the appropriate authority. If the computer is joined to a domain, members of the Domain Admins group might be able to perform this procedure. As a security best practice, consider using **Run As** to perform this procedure.

- A volume must have at least 15% free space for **defrag** to completely and adequately defragment it. **defrag** uses this space as a sorting area for file fragments. If a volume has less than 15% free space, **defrag** will only partially defragment it. To increase the free space on a volume, delete unneeded files or move them to another disk.

- While **defrag** is analyzing and defragmenting a volume, it displays a blinking cursor. When **defrag** is finished analyzing and defragmenting the volume, it displays the analysis report, the defragmentation report, or both reports, and then exits to the command prompt.

- By default, **defrag** displays a summary of both the analysis and defragmentation reports if you do not specify the **/a** or **/v** parameters.

- You can send the reports to a text file by typing **>**<em>FileName.txt</em>, where *FileName.txt* is a file name you specify. For example: `defrag volume /v > FileName.txt`

- To interrupt the defragmentation process, at the command line, press **CTRL+C**.

- Running the **defrag** command and Disk defragmenter are mutually exclusive. If you are using Disk defragmenter to defragment a volume and you run the **defrag** command at a command-line, the **defrag** command fails. Conversely, if you run the **defrag** command and open Disk defragmenter, the defragmentation options in Disk defragmenter are unavailable.

### Examples

To defragment the volume on drive C while providing progress and verbose output, type:

```
defrag c: /u /v
```

To defragment the volumes on drives C and D in parallel in the background, type:

```
defrag c: d: /m
```

To perform a fragmentation analysis of a volume mounted on drive C and provide progress, type:

```
defrag c: mountpoint /a /u
```

To defragment all volumes with normal priority and provide verbose output, type:

```
defrag /c /h /v
```

### Scheduled task

The defragmentation process runs scheduled task as a maintenance task, which typically runs every week. As an Administrator, you can change the how often the task runs by using the **Optimize Drives** app.

- When run from the scheduled task, **defrag** uses the below policy guidelines for SSDs:

  - **Traditional optimization processes**. Includes **traditional defragmentation**, for example moving files to make them reasonably contiguous and **retrim**. This is done once per month. However, if both **traditional defragmentation** and **retrim** are skipped, then **analysis** isn't run. Changing the frequency of the scheduled task does not affect the once per month cadence for the SSDs.

  - If you manually run **traditional defragmentation** on a SSD, between your normally scheduled runs, the next scheduled task run performs **analysis** and **retrim**, but skips **traditional defragmentation** on that SSD.

  - If you skip **analysis**, you won't see an updated **Last run** time in the **Optimize Drives** app. Because of that, the **Last run** time can be up to a month old.

  - You might find that scheduled task hasn't defragmented all volumes. This is typically because:

    - The process won't wake the computer to run.

    - The computer isn't plugged in. The process won't run if the computer is running on battery power.

    - The computer started back up (resumed from idle).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [chkdsk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

- [fsutil](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil.md)

- [fsutil dirty](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-dirty.md)

- [Optimize-Volume Powershell](/powershell/module/storage/optimize-volume)

---



MIT License. Copyright (c) 2020-2021 Strontic.


