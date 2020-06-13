
# Defrag.exe 

* File Path: `C:\WINDOWS\system32\Defrag.exe`
* Description: Disk Defragmenter Module
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `15EFD404D3065B560876BBE567CE981A`
SHA1 | `DAF77FBBA1671CDFD23C76B3D7E05859D695DCDE`
SHA256 | `2630901B1B24EDE6AA117163BB738B90921D3D67F5AEB233CAC0715A836BACE3`
SHA384 | `36FB405C2FF40F14D54CC0957A75E73EB04329DFEBA1FB8062CF29D003FF3985279D22FA2D2D57C047234132F537C1DF`
SHA512 | `3B556CE7E80FB3E054A289BC35593240DB41915B8C28E0D8EB09417553640338273CB2AABA7B17603FA48034A90828912FE7FF8C3A359FAF9B59277F30625A7D`
SSDEEP | `3072:UtzyHzVHRADkbo0pwIuUEb4C6c5Q3eSjlR+8qxLijgJyfFOG83Yj34YFnw6OC2cs:UcTFRWKT3lRGOUZGKc4YFnwjCpW`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft Drive Optimizer
Copyright (c) Microsoft Corp.

Please specify a volume to perform the operation on. (0x89000007)

Description:

	Optimizes and defragments files on local volumes to
	improve system performance.

Syntax:

	defrag <volumes> | /C | /E <volumes> [<task(s)>] [/H] [/M [n] | [/U] [/V]] [/I n]

	Where <task(s)> is omitted (traditional defrag), or as follows:
		/A | [/D] [/K] [/L] | /O | /X

	Or, to track an operation already in progress on a volume:
	defrag <volume> /T

Parameters:

	Value	Description
	/A	Perform analysis on the specified volumes.
	/C	Perform the operation on all volumes.
	/D	Perform traditional defrag (this is the default).  On a tiered volume
		though, traditional defrag is performed only on the Capacity tier.
	/E	Perform the operation on all volumes except those specified.
	/G	Optimize the storage tiers on the specified volumes.
	/H	Run the operation at normal priority (default is low).
	/I n	Tier optimization would run for at most n seconds on each volume.
	/K	Perform slab consolidation on the specified volumes.
	/L	Perform retrim on the specified volumes.
	/M [n]	Run the operation on each volume in parallel in the background.
		At most n threads optimize the storage tiers in parallel.
	/O	Perform the proper optimization for each media type.
	/T	Track an operation already in progress on the specified volume.
	/U	Print the progress of the operation on the screen.
	/V	Print verbose output containing the fragmentation statistics.
	/X	Perform free space consolidation on the specified volumes.

Examples:

	defrag C: /U /V
	defrag C: D: /M
	defrag C:\mountpoint /A /U
	defrag /C /H /V

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Defrag.EXE.MUI
* Product Name: Windows Drive Optimizer
* Company Name: Microsoft Corp.
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corp.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---
# defrag

> Applies to: Windows 10, Windows Server (Semi-Annual Channel), Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Locates and consolidates fragmented files on local volumes to improve system performance.

Membership in the local **Administrators** group, or equivalent, is the minimum required to run this command.

## Syntax

```
defrag <volumes> | /c | /e <volumes>    [/h] [/m [n]| [/u] [v]]
defrag <volumes> | /c | /e <volumes> /a [/h] [/m [n]| [/u] [v]]
defrag <volumes> | /c | /e <volumes> /x [/h] [/m [n]| [/u] [v]]
defrag <volume> [<parameters>]
```

### Parameters

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

#### Remarks

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

## Examples

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

## Scheduled task

The defragmentation process runs scheduled task as a maintenance task, which typically runs every week. As an Administrator, you can change the how often the task runs by using the **Optimize Drives** app.

- When run from the scheduled task, **defrag** uses the below policy guidelines for SSDs:

  - **Traditional optimization processes**. Includes **traditional defragmentation**, for example moving files to make them reasonably contiguous and **retrim**. This is done once per month. However, if both **traditional defragmentation** and **retrim** are skipped, then **analysis** isn't run.

  - If you manually run **traditional defragmentation** on a SSD, between your normally scheduled runs, the next scheduled task run performs **analysis** and **retrim**, but skips **traditional defragmentation** on that SSD.

  - If you skip **analysis**, you won't see an updated **Last run** time in the **Optimize Drives** app. Because of that, the **Last run** time can be up to a month old.

  - You might find that scheduled task hasn't defragmented all volumes. This is typically because:

    - The process won't wake the computer to run.

    - The computer isn't plugged in. The process won't run if the computer is running on battery power.

    - The computer started back up (resumed from idle).

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [chkdsk](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/chkdsk.md)

- [fsutil](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil.md)

- [fsutil dirty](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/fsutil-dirty.md)

- [Optimize-Volume Powershell](https://docs.microsoft.com/powershell/module/storage/optimize-volume?view=win10-ps)

---


MIT License. Copyright (c) 2020 Strontic.


