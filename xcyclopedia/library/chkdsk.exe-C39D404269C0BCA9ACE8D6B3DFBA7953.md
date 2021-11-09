---
title: chkdsk.exe | Check Disk Utility
excerpt: What is chkdsk.exe?
---

# chkdsk.exe 

* File Path: `C:\WINDOWS\system32\chkdsk.exe`
* Description: Check Disk Utility

## Hashes

Type | Hash
-- | --
MD5 | `C39D404269C0BCA9ACE8D6B3DFBA7953`
SHA1 | `DB7148C5F6DC8B36D2EA4C7AF3F40C95212687BB`
SHA256 | `C0BFF1ABEC9BAC3287C0BD6F3E76D364095EC17A25EE9C8E9A98E6B46E019D6A`
SHA384 | `9C341D9D799A93DA85BDD247D6138D64A7BD960F3B87CAC30756B881EF534C3F92160DCA97B6D1B77D4652EAE33C7089`
SHA512 | `66498E545A1FB148EDA0E7FC2078A18B0000DB8CB049C42E63D8F25A1A1BAAB4BFA78DA197076C9587A54C6481D034E7DC5C982860CDF3AEE0BC0B63124350A9`
SSDEEP | `384:IEzC9vIYSC65/eWqVSyF1JjTad8Ne+r9oKHcaJ9OCuj0Ed+jONyWSFBhWw:rzuAYSC6fqVd9oKHcafO50e+66B`
IMP | `7DE8E5CA5FC1515B950ABCD411D3A9E5`
PESHA1 | `8F25DF1EF24032D80F13C0488965359B214CB885`
PE256 | `659580FDC3AF4C17D3AFEAFB9A1F07D06135F0A5E5056C91C608D4FACDCC67C3`

## Runtime Data

### Usage (stdout):
```cmhg
Checks a disk and displays a status report.


CHKDSK [volume[[path]filename]]] [/F] [/V] [/R] [/X] [/I] [/C] [/L[:size]] [/B] [/scan] [/spotfix]


  volume              Specifies the drive letter (followed by a colon),
                      mount point, or volume name.
  filename            FAT/FAT32 only: Specifies the files to check for
                      fragmentation.
  /F                  Fixes errors on the disk.
  /V                  On FAT/FAT32: Displays the full path and name of every
                      file on the disk.
                      On NTFS: Displays cleanup messages if any.
  /R                  Locates bad sectors and recovers readable information
                      (implies /F, when /scan not specified).
  /L:size             NTFS only:  Changes the log file size to the specified
                      number of kilobytes.  If size is not specified, displays
                      current size.
  /X                  Forces the volume to dismount first if necessary.
                      All opened handles to the volume would then be invalid
                      (implies /F).
  /I                  NTFS only: Performs a less vigorous check of index
                      entries.
  /C                  NTFS only: Skips checking of cycles within the folder
                      structure.
  /B                  NTFS only: Re-evaluates bad clusters on the volume
                      (implies /R)
  /scan               NTFS only: Runs an online scan on the volume
  /forceofflinefix    NTFS only: (Must be used with "/scan")
                      Bypass all online repair; all defects found
                      are queued for offline repair (i.e. "chkdsk /spotfix").
  /perf               NTFS only: (Must be used with "/scan")
                      Uses more system resources to complete a scan as fast as
                      possible. This may have a negative performance impact on
                      other tasks running on the system.
  /spotfix            NTFS only: Runs spot fixing on the volume
  /sdcleanup          NTFS only: Garbage collect unneeded security descriptor
                      data (implies /F).
  /offlinescanandfix  Runs an offline scan and fix on the volume.
  /freeorphanedchains FAT/FAT32/exFAT only: Frees any orphaned cluster chains
                      instead of recovering their contents.
  /markclean          FAT/FAT32/exFAT only: Marks the volume clean if no
                      corruption was detected, even if /F was not specified.

The /I or /C switch reduces the amount of time required to run Chkdsk by
skipping certain checks of the volume.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\chkdsk.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHKDSK.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/c0bff1abec9bac3287c0bd6f3e76d364095ec17a25ee9c8e9a98e6b46e019d6a/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## chkdsk

Checks the file system and file system metadata of a volume for logical and physical errors. If used without parameters, **chkdsk** displays only the status of the volume and does not fix any errors. If used with the **/f**, **/r**, **/x**, or **/b** parameters, it fixes errors on the volume.

> [!IMPORTANT]
> Membership in the local **Administrators** group, or equivalent, is the minimum required to run **chkdsk**. To open a command prompt window as an administrator, right-click **Command prompt** in the **Start** menu, and then click **Run as administrator**.

> [!IMPORTANT]
> Interrupting **chkdsk** is not recommended. However, canceling or interrupting **chkdsk** should not leave the volume any more corrupt than it was before **chkdsk** was run. Running **chkdsk** again checks and should repair any remaining corruption on the volume.

> [!NOTE]
> Chkdsk can be used only for local disks. The command cannot be used with a local drive letter that has been redirected over the network.

### Syntax

```
chkdsk [<volume>[[<path>]<filename>]] [/f] [/v] [/r] [/x] [/i] [/c] [/l[:<size>]] [/b]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<volume>` | Specifies the drive letter (followed by a colon), mount point, or volume name. |
| [ `[<path>]<filename>` | Use with file allocation table (FAT) and FAT32 only. Specifies the location and name of a file or set of files that you want **chkdsk** to check for fragmentation. You can use the **?** and **&#42;** wildcard characters to specify multiple files. |
| /f | Fixes errors on the disk. The disk must be locked. If **chkdsk** cannot lock the drive, a message appears that asks you if you want to check the drive the next time you restart the computer. |
| /v | Displays the name of each file in every directory as the disk is checked. |
| /r | Locates bad sectors and recovers readable information. The disk must be locked. **/r** includes the functionality of **/f**, with the additional analysis of physical disk errors. |
| /x | Forces the volume to dismount first, if necessary. All open handles to the drive are invalidated. **/x** also includes the functionality of **/f**.  |
| /i | Use with NTFS only. Performs a less vigorous check of index entries, which reduces the amount of time required to run **chkdsk**. |
| /c | Use with NTFS only. Does not check cycles within the folder structure, which reduces the amount of time required to run **chkdsk**.  |
| /l[:`<size>`] | Use with NTFS only. Changes the log file size to the size you type. If you omit the size parameter, **/l** displays the current size. |
| /b | Use with NTFS only. Clears the list of bad clusters on the volume and rescans all allocated and free clusters for errors. **/b** includes the functionality of **/r**. Use this parameter after imaging a volume to a new hard disk drive. |
| /scan | Use with NTFS only. Runs an online scan on the volume. |
| /forceofflinefix | Use with NTFS only (must be used with **/scan**). Bypass all online repair; all defects found are queued for offline repair (for example, `chkdsk /spotfix`). |
| /perf | Use with NTFS only (must be used with **/scan**). Uses more system resources to complete a scan as fast as possible. This may have a negative performance impact on other tasks running on the system. |
| /spotfix | Use with NTFS only. Runs spot fixing on the volume. |
| /sdcleanup | Use with NTFS only. Garbage collect unneeded security descriptor data (implies **/f**). |
| /offlinescanandfix | Runs an offline scan and fix on the volume. |
| /freeorphanedchains | Use with FAT/FAT32/exFAT only. Frees any orphaned cluster chains instead of recovering their contents. |
| /markclean | Use with FAT/FAT32/exFAT only. Marks the volume clean if no corruption was detected, even if **/f** was not specified. |
| /? | Displays help at the command prompt. |

### Remarks

- The **/i** or **/c** switch reduces the amount of time required to run **chkdsk** by skipping certain volume checks.

- If you want **chkdsk** to correct disk errors, you can't have open files on the drive. If files are open, the following error message appears:

  ```
  Chkdsk cannot run because the volume is in use by another process. Would you like to schedule this volume to be checked the next time the system restarts? (Y/N)
  ```

- If you choose to check the drive the next time you restart the computer, **chkdsk** checks the drive and corrects errors automatically when you restart the computer. If the drive partition is a boot partition, **chkdsk** automatically restarts the computer after it checks the drive.

- You can also use the `chkntfs /c` command to schedule the volume to be checked the next time the computer is restarted. Use the `fsutil dirty set` command to set the volume's dirty bit (indicating corruption), so that Windows runs **chkdsk** when the computer is restarted.

- You should use **chkdsk** occasionally on FAT and NTFS file systems to check for disk errors. **Chkdsk** examines disk space and disk use and provides a status report specific to each file system. The status report shows errors found in the file system. If you run **chkdsk** without the **/f** parameter on an active partition, it might report spurious errors because it cannot lock the drive.

- **Chkdsk** corrects logical disk errors only if you specify the **/f** parameter. **Chkdsk** must be able to lock the drive to correct errors.

  Because repairs on FAT file systems usually change a disk's file allocation table and sometimes cause a loss of data, **chkdsk** might display a confirmation message similar to the following:

  ```
  10 lost allocation units found in 3 chains.
  Convert lost chains to files?
  ```

    - If you press **Y**, Windows saves each lost chain in the root directory as a file with a name in the format File`<nnnn>`.chk. When **chkdsk** finishes, you can check these files to see if they contain any data you need.

    - If you press **N**, Windows fixes the disk, but it does not save the contents of the lost allocation units.

- If you don't use the **/f** parameter, **chkdsk** displays a message that the file needs to be fixed, but it does not fix any errors.

- If you use `chkdsk /f*` on a very large disk or a disk with a very large number of files (for example, millions of files), `chkdsk /f` might take a long time to complete.

- Use the **/r** parameter to find physical disk errors in the file system and attempt to recover data from any affected disk sectors.

- If you specify the **/f** parameter, **chkdsk** displays an error message if there are open files on the disk. If you do not specify the **/f** parameter and open files exist, **chkdsk** might report lost allocation units on the disk. This could happen if open files have not yet been recorded in the file allocation table. If **chkdsk** reports the loss of a large number of allocation units, consider repairing the disk.

- Because the Shadow Copies for Shared Folders source volume cannot be locked while **Shadow Copies for Shared Folders** is enabled, running **chkdsk** against the source volume might report false errors or cause **chkdsk** to unexpectedly quit. You can, however, check shadow copies for errors by running **chkdsk** in Read-only mode (without parameters) to check the Shadow Copies for Shared Folders storage volume.

- The **chkdsk** command, with different parameters, is available from the Recovery Console.

- On servers that are infrequently restarted, you may want to use the **chkntfs** or the `fsutil dirty query` commands to determine whether the volume's dirty bit is already set before running chkdsk.

#### Understanding exit codes

The following table lists the exit codes that **chkdsk** reports after it has finished.

  | Exit code | Description |
  | --------- | ----------- |
  | 0 | No errors were found. |
  | 1 | Errors were found and fixed. |
  | 2 | Performed disk cleanup (such as garbage collection) or did not perform cleanup because **/f** was not specified. |
  | 3 | Could not check the disk, errors could not be fixed, or errors were not fixed because **/f** was not specified. |

### Examples

To check the disk in drive D and have Windows fix errors, type:

```
chkdsk d: /f
```

If it encounters errors, **chkdsk** pauses and displays messages. **Chkdsk** finishes by displaying a report that lists the status of the disk. You cannot open any files on the specified drive until **chkdsk** finishes.

To check all files on a FAT disk in the current directory for noncontiguous blocks, type:

```
chkdsk *.*
```

**Chkdsk** displays a status report, and then lists the files that match the file specifications that have noncontiguous blocks.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


