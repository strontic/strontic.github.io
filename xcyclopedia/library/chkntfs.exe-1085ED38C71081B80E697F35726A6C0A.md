---
title: chkntfs.exe | NTFS Volume Maintenance Utility
---

# chkntfs.exe 

* File Path: `C:\windows\SysWOW64\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1085ED38C71081B80E697F35726A6C0A`
SHA1 | `99BCC54F461190927E9EB8C4EFD8DF9BADBE3445`
SHA256 | `E0B09EC52E8733FB6BE9688478D2640ECAA5B091FCA4B2F8CB0FD383F738D112`
SHA384 | `FBD30814753841749D210DA0178CC28BFFEB51AAD7A2202621301FEF50EBCC96EE4106AE406F62E84D4C607AAA2C7958`
SHA512 | `A7BBC2876AE50B4AEEA6DB8554CA566DE57E51A54FB3D5ADB69959E15D8B4FC1CA1FF28EFB03E374C33CCD990BC2EE778DCAFFD9E0679CD98064382CD99B4463`
SSDEEP | `384:X8W/Jf5/E60PPmb8TX0YN9kVBnYl1MNkWE6W:X5V5/E60nmojNWnEMs`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\chkntfs.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CHKNTFS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## chkntfs

Displays or modifies automatic disk checking when the computer is started. If used without options, **chkntfs** displays the file system of the specified volume. If automatic file checking is scheduled to run, **chkntfs** displays whether the specified volume is dirty or is scheduled to be checked the next time the computer is started.

> [!NOTE]
> To run **chkntfs**, you must be a member of the Administrators group.

### Syntax

```
chkntfs <volume> [...]
chkntfs [/d]
chkntfs [/t[:<time>]]
chkntfs [/x <volume> [...]]
chkntfs [/c <volume> [...]]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<volume>` [...] | Specifies one or more volumes to check when the computer starts. Valid volumes include drive letters (followed by a colon), mount points, or volume names. |
| /d | Restores all **chkntfs** default settings, except the countdown time for automatic file checking. By default, all volumes are checked when the computer is started, and **chkdsk** runs on those that are dirty. |
| /t [`:<time>`] | Changes the Autochk.exe initiation countdown time to the amount of time specified in seconds. If you do not enter a time, **/t** displays the current countdown time. |
| /x `<volume>` [...] | Specifies one or more volumes to exclude from checking when the computer is started, even if the volume is marked as requiring **chkdsk**. |
| /c `<volume>` [...] | Schedules one or more volumes to be checked when the computer is started, and runs **chkdsk** on those that are dirty. |
| /? | Displays help at the command prompt. |

### Examples

To display the type of file system for drive C, type:

```
chkntfs c:
```

> [!NOTE]
> If automatic file checking is scheduled to run, additional output will display, indicating whether the drive is dirty or has been manually scheduled to be checked the next time the computer is started.

To display the Autochk.exe initiation countdown time, type:

```
chkntfs /t
```

To change the Autochk.exe initiation countdown time to 30 seconds, type:

```
chkntfs /t:30
```

> [!NOTE]
> Although you can set the Autochk.exe initiation countdown time to zero, doing so will prevent you from canceling a potentially time-consuming automatic file check.

To exclude multiple volumes from being checked, you must list each of them in a single command. For example, to exclude both the D and E volumes, type:

```
chkntfs /x d: e:
```

> [!IMPORTANT]
> The **/x** command-line option isn't accumulative. If you type it more than once, the most recent entry overrides the previous entry.

To schedule automatic file checking on the D volume, but not the C or E volumes, type the following commands in order:

```
chkntfs /d
chkntfs /x c: d: e:
chkntfs /c d:
```

> [!IMPORTANT]
> The **/c** command-line option is accumulative. If you type **/c** more than once, each entry remains. To ensure that only a particular volume is checked, reset the defaults to clear all previous commands, exclude all volumes from being checked, and then schedule automatic file checking on the desired volume.

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


