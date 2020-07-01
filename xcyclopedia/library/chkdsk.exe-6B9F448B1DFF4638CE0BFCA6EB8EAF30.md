---
title: chkdsk.exe | Check Disk Utility
---

# chkdsk.exe 

* File Path: `C:\windows\system32\chkdsk.exe`
* Description: Check Disk Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6B9F448B1DFF4638CE0BFCA6EB8EAF30`
SHA1 | `050234634CDB25047E7975D9929AA318C3CC6EBF`
SHA256 | `035A22149CFBB1415D293AD3C3664B2990191B0336D595E1564EC86BA7337DA2`
SHA384 | `742E8EB1D49813C47339308B54938654B9EB5928EA55A1C9607D93B3BF8298E6512FCBC40AAF4C1209F836AD58E599A1`
SHA512 | `F39D0C2E3C9D29D7E215430661B54B5C9DE5211219A31CE64061FB0DA5BD9DA63C10B4D5750F2E4111C23CE79D67B2C53F96ED80F3C9520A6EF1C2FC4B0CCFC2`
SSDEEP | `384:nf9q3RI7DyDgpCpWODGhK2lZvEHBsnrQ0al+hdl0ITUaerNqWSFMhW:f9q3RI7DlCoOK8tWnrQ0awP3IraM`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\chkdsk.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CHKDSK.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


