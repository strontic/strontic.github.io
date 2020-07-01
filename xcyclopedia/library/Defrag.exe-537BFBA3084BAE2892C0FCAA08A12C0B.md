---
title: Defrag.exe | Disk Defragmenter Module
---

# Defrag.exe 

* File Path: `C:\windows\system32\Defrag.exe`
* Description: Disk Defragmenter Module
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `537BFBA3084BAE2892C0FCAA08A12C0B`
SHA1 | `7E11C73D5836D7AF8EA774F1ACA5A8613511FE66`
SHA256 | `E12F5A5804519A4C8F4EDA5B27B3477D89AA4B80E5D9BFA359C1D6794D947965`
SHA384 | `1BBAC5C6B279B2C9DF4C23FE7F1057DB64D7A5DBC3D6D385C826EFDBB8FC04BD051E7F186F2D82A46C646A3D92BB14EB`
SHA512 | `6AEA8A9A0AE2F08B9BDD6F50F7AE11B2E6C478C2B9FCF366BA3F7E343393594CAE4B1D0F05D9050AC5F97767A16F5A93440C0B9703721695D63336CB5818019C`
SSDEEP | `3072:Iw3qMDpKdhTivZeCCwpVb4C6c5Q3eSjlR+8qxLijgJyfFOG83Yj34YFnw6OC2c9+:b3tpghEeUc3lRGOUZGKc4YFnwjCpW`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\Defrag.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Defrag.EXE.MUI
* Product Name: Windows Drive Optimizer
* Company Name: Microsoft Corp.
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  2013 Microsoft Corp.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\Defrag.exe](Defrag.exe-15EFD404D3065B560876BBE567CE981A.md) | 75
[C:\Windows\system32\Defrag.exe](Defrag.exe-BCBD8C0BFD620A4761C8ACDF96D9CDAE.md) | 71
[C:\Windows\system32\Defrag.exe](Defrag.exe-D340F5AE00E1C33F8BDC538D9888C459.md) | 71
[C:\Windows\system32\Defrag.exe](Defrag.exe-F7AC2F29879A0789A74F87012861A956.md) | 65

## Possible Misuse

*The following table contains possible examples of `Defrag.exe` being misused. While `Defrag.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_slingshot.yml) | `title: Defrag Deactivation` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_slingshot.yml) | `            - '*schtasks* /delete *Defrag\ScheduledDefrag*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_slingshot.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_slingshot.yml) | `        TaskName: '\Microsoft\Windows\Defrag\ScheduledDefrag'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\defrag.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `            - '\defrag.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## defrag

> Applies to: Windows 10, Windows Server (Semi-Annual Channel), Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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

- You can't schedule to defragment a Solid State Drive (SSD) or a volume on a Virtual Hard Disk (VHD) that resides on an SSD.

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

  - **Traditional optimization processes**. Includes **traditional defragmentation**, for example moving files to make them reasonably contiguous and **retrim**. This is done once per month. However, if both **traditional defragmentation** and **retrim** are skipped, then **analysis** isn't run.

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

- [Optimize-Volume Powershell](https://docs.microsoft.com/powershell/module/storage/optimize-volume?view=win10-ps)

---



MIT License. Copyright (c) 2020 Strontic.


