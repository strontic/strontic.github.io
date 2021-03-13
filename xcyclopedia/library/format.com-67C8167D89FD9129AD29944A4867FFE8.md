---
title: format.com | Disk Format Utility
excerpt: What is format.com?
---

# format.com 

* File Path: `C:\Windows\system32\format.com`
* Description: Disk Format Utility

## Hashes

Type | Hash
-- | --
MD5 | `67C8167D89FD9129AD29944A4867FFE8`
SHA1 | `5A8B8DC04819DA03BE57715418B0CFFA0C614109`
SHA256 | `DAABF5ED8438EF1A3357820433895B885D867C6447A085E9975355788EC7F578`
SHA384 | `21D2D5DF296A5F35760DBF7F2BBAC6BBFC738F0D6525DEDBF0401AFE073F73E6BC89949F6DC21C9830CB5E0D0B56804B`
SHA512 | `B0026B6C49FB78B8AACC5D415C3BA8D357E1DEA2686016512FB0409900BA98F6E48E509EEB636944897445F2167AF2587A9B061D32393540CECD349160A41C46`
SSDEEP | `768:lk71fuMa8Eh/hllXBMjNnZa9yJ/l1ryk5ZonxcdmOknu/HOOds:wmJtv/XBMjNnZa9+ryk/oydmOX/HLs`
IMP | `780B135D74D26B1A8BBA809A7367F453`
PESHA1 | `D6EC3AEA38DB9C17314E83278E45F9105F13BF61`
PE256 | `B74292A3ABAC99B54F61C94095B47A49562CB99FA179E95C8A9F8BCB7583140E`

## Runtime Data

### Usage (stdout):
```cmhg
Formats a disk for use with Windows.

FORMAT volume [/FS:file-system] [/V:label] [/Q] [/L[:state]] [/A:size] [/C] [/I:state] [/X] [/P:passes] [/S:state]
FORMAT volume [/V:label] [/Q] [/F:size] [/P:passes]
FORMAT volume [/V:label] [/Q] [/T:tracks /N:sectors] [/P:passes]
FORMAT volume [/V:label] [/Q] [/P:passes]
FORMAT volume [/Q]

  volume          Specifies the drive letter (followed by a colon),
                  mount point, or volume name.
  /FS:filesystem  Specifies the type of the file system (FAT, FAT32, exFAT,
                  NTFS, UDF, ReFS).
  /V:label        Specifies the volume label.
  /Q              Performs a quick format. Note that this switch overrides /P.
  /C              NTFS only: Files created on the new volume will be compressed
                  by default.
  /X              Forces the volume to dismount first if necessary.  All opened
                  handles to the volume would no longer be valid.
  /R:revision     UDF only: Forces the format to a specific UDF version
                  (1.02, 1.50, 2.00, 2.01, 2.50).  The default
                  revision is 2.01.
  /D              UDF 2.50 only: Metadata will be duplicated.
  /L[:state]      NTFS Only: Overrides the default size of file record.
                  By default, a non-tiered volume will be formatted with small
                  size file records and a tiered volume will be formatted with
                  large size file records.  /L and /L:enable forces format to
                  use large size file records and /L:disable forces format to
                  use small size file records.
  /A:size         Overrides the default allocation unit size. Default settings
                  are strongly recommended for general use.
                  ReFS supports 4096, 64K.
                  NTFS supports 512, 1024, 2048, 4096, 8192, 16K, 32K, 64K,
                  128K, 256K, 512K, 1M, 2M.
                  FAT supports 512, 1024, 2048, 4096, 8192, 16K, 32K, 64K,
                  (128K, 256K for sector size > 512 bytes).
                  FAT32 supports 512, 1024, 2048, 4096, 8192, 16K, 32K, 64K,
                  (128K, 256K for sector size > 512 bytes).
                  exFAT supports 512, 1024, 2048, 4096, 8192, 16K, 32K, 64K,
                  128K, 256K, 512K, 1M, 2M, 4M, 8M, 16M, 32M.

                  Note that the FAT and FAT32 files systems impose the
                  following restrictions on the number of clusters on a volume:

                  FAT: Number of clusters <= 65526
                  FAT32: 65526 < Number of clusters < 4177918

                  Format will immediately stop processing if it decides that
                  the above requirements cannot be met using the specified
                  cluster size.

                  NTFS compression is not supported for allocation unit sizes
                  above 4096.

  /F:size         Specifies the size of the floppy disk to format (1.44)
  /T:tracks       Specifies the number of tracks per disk side.
  /N:sectors      Specifies the number of sectors per track.
  /P:count        Zero every sector on the volume.  After that, the volume
                  will be overwritten "count" times using a different
                  random number each time.  If "count" is zero, no additional
                  overwrites are made after zeroing every sector.  This switch
                  is ignored when /Q is specified.
  /S:state        Specifies support for short filenames (enable, disable)
                  Short names are disabled by default
  /TXF:state      Specifies txf is enabled/disabled (enabled, disabled)
                  TxF is enabled by default
  /I:state        ReFS only: Specifies whether integrity should be enabled on
                  the new volume. "state" is either "enable" or "disable"
                  Integrity is enabled on storage that supports data redundancy
                  by default.
  /DAX[:state]    NTFS Only: Enable direct access storage (DAX) mode for this
                  volume.  In DAX mode, the volume is accessed via the memory
                  bus, boosting IO performance.  A volume can be formatted
                  with DAX mode only if the hardware is DAX capable.
                  State can specify "enable" or "disable".  /DAX is considered
                  as /DAX:enable.
  /LogSize[:size] NTFS Only: Specifies the size for NTFS log file in kilobytes.
                  The minimum supported size is 2MB, so specifying size smaller
                  than 2MB will result in a 2MB log file.  Zero indicates the
                  default value which generally depend on the volume size.
  /NoRepairLogs   NTFS Only: Disables NTFS repair logs.  If the flag is set
                  spotfix (i.e. chkdsk /spotfix) will not work.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\format.com |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: format.com
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/daabf5ed8438ef1a3357820433895b885d867c6447a085e9975355788ec7f578/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## Format

> Applies to: Windows 10, Windows Server 2016

Formats a disk to accept Windows files. You must be a member of the Administrators group to format a hard drive.

> [!NOTE]
> You can also use the **format** command, with different parameters, from the Recovery Console. For more information about the recovery console, see [Windows Recovery Environment (Windows RE)](/windows-hardware/manufacture/desktop/windows-recovery-environment--windows-re--technical-reference).

### Syntax

```
format <volume> [/fs:{FAT|FAT32|NTFS}] [/v:<label>] [/q] [/a:<unitsize>] [/c] [/x] [/p:<passes>]
format <volume> [/v:<label>] [/q] [/f:<size>] [/p:<passes>]
format <volume> [/v:<label>] [/q] [/t:<tracks> /n:<sectors>] [/p:<passes>]
format <volume> [/v:<label>] [/q] [/p:<passes>]
format <volume> [/q]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<volume>` | Specifies the mount point, volume name, or drive letter (followed by a colon) of the drive that you want to format. If you do not specify any of the following command-line options, **format** uses the volume type to determine the default format for the disk. |
| /fs:{FAT | FAT32 | NTFS} | Specifies the type of file system (FAT, FAT32, NTFS). |
| /v:`<label>` | Specifies the volume label. If you omit the **/v** command-line option or use it without specifying a volume label, **format** prompts you for the volume label after the formatting is complete. Use the syntax **/v:** to prevent the prompt for a volume label. If you use a single **format** command to format more than one disk, all of the disks will be given the same volume label. |
| /a:`<unitsize>` | Specifies the allocation unit size to use on FAT, FAT32, or NTFS volumes. If you don't specify *unitsize*, it's chosen based on volume size. Default settings are strongly recommended for general use. The following list presents valid values for NTFS, FAT, and FAT32 *unitsize*:<ul><li>512</li><li>1024</li><li>2048</li><li>4096</li><li>8192</li><li>16K</li><li>32K</li><li>64K</li></ul>FAT and FAT32 also support 128K and 256K for a sector size greater than 512 bytes. |
| /q | Performs a quick format. Deletes the file table and the root directory of a previously formatted volume, but does not perform a sector-by-sector scan for bad areas. You should use the **/q** command-line option to format only previously formatted volumes that you know are in good condition. Note that **/q** overrides **/p**. |
| /f:`<size>` | Specifies the size of the floppy disk to format. When possible, use this command-line option instead of the **/t** and **/n** command-line options. Windows accepts the following values for size:<ul><li>1440 or 1440k or 1440kb</li><li>1.44 or 1.44m or 1.44mb</li><li>1.44-MB, double-sided, quadruple-density, 3.5-inch disk</li></ul> |
| /t:`<tracks>` | Specifies the number of tracks on the disk. When possible, use the **/f** command-line option instead. If you use the **/t** option, you must also use the **/n** option. These options together provide an alternative method of specifying the size of the disk that is being formatted. This option is not valid with the **/f** option. |
| /n:`<sectors>` | Specifies the number of sectors per track. When possible, use the **/f** command-line option instead of **/n**. If you use **/n**, you must also use **/t**. These two options together provide an alternative method of specifying the size of the disk that is being formatted. This option is not valid with the **/f** option. |
| /p:`<passes>` | Zeros every sector on the volume for the number of passes specified. This option is not valid with the **/q** option. |
| /c | NTFS only. Files created on the new volume will be compressed by default. |
| /x | Causes the volume to dismount, if necessary, before it's formatted. Any open handles to the volume will no longer be valid. |
| /? | Displays help at the command prompt. |

##### Remarks

- The **format** command creates a new root directory and file system for the disk. It can also check for bad areas on the disk, and it can delete all data on the disk. To be able to use a new disk, you must first use this command to format the disk.

- After formatting a floppy disk, **format** displays the following message:

    `Volume label (11 characters, ENTER for none)?`

    To add a volume label, type up to 11 characters (including spaces). If you do not want to add a volume label to the disk, press ENTER.

- When you use the **format** command to format a hard disk, a warning message similar to the following displays:

  ```
  WARNING, ALL DATA ON NON-REMOVABLE DISK
  DRIVE x: WILL BE LOST!
  Proceed with Format (Y/N)? _
  ```

  To format the hard disk, press **Y**; if you do not want to format the disk, press **N**.

- FAT file systems restrict the number of clusters to no more than 65526. FAT32 file systems restrict the number of clusters to between 65527 and 4177917.

- NTFS compression is not supported for allocation unit sizes above 4096.

  > [!NOTE]
  > **Format** will immediately stop processing if it determines that the previous requirements can't be met using the specified cluster size.

- When formatting is complete, **format** displays messages that show the total disk space, the spaces marked as defective, and the space available for your files.

- You can speed up the formatting process by using the **/q** command-line option. Use this option only if there are no bad sectors on your hard disk.

- You shouldn't use the **format** command on a drive that was prepared by using the **subst** command. You can't format disks over a network.

- The following table lists each exit code and a brief description of its meaning.

  | Exit code | Description |
  | --------- | ----------- |
  | 0 | The format operation was successful. |
  | 1 | Incorrect parameters were supplied. |
  | 4 | A fatal error occurred (which is any error other than 0, 1, or 5). |
  | 5 | The user pressed N in response to the prompt "Proceed with Format (Y/N)?" to stop the process. |

  You can check these exit codes by using the ERRORLEVEL environment variable with the **if** batch command.

#### Examples

To format a new floppy disk in drive A using the default size, type:

```
format a:
```

To perform a quick format operation on a previously formatted floppy disk in drive A, type:

```
format a: /q
```

To format a floppy disk in drive A and assign it the volume label *DATA*, type:

```
format a: /v:DATA
```

### Additional References

- [Command-Line Syntax Key](/previous-versions/windows/it-pro/windows-server-2012-R2-and-2012/cc771080(v=ws.11))

---



MIT License. Copyright (c) 2020-2021 Strontic.


