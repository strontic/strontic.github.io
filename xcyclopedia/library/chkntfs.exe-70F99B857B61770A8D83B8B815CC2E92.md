---
title: chkntfs.exe | NTFS Volume Maintenance Utility
excerpt: What is chkntfs.exe?
---

# chkntfs.exe 

* File Path: `C:\WINDOWS\system32\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `70F99B857B61770A8D83B8B815CC2E92`
SHA1 | `631F355D0CE2C3E653916395657498112058757B`
SHA256 | `6E383E528F896345EE9E45A247F66B0603CA30FD30A92A838DAE263C97733B67`
SHA384 | `FAC43DEE7656FAEB58C53476C855B2CA81FA68FB9235D3A4AC5B20C436E9F0B793A7ED0A12CEEA738AE9A5E7B0739640`
SHA512 | `D2E684AC35431386774A36277B91755242456D500FC6E0E9B9A62E87DBE8614DBF5220B054572F3476475731C4743CB0193883E855C4CA089191DF49A1DD54C5`
SSDEEP | `384:xjvdDFr8xweHw4g0ug+vlltxoT9a+B1yJ7Xm+T13NsW56W:pvYweHw4FL+5+T9a+3yJ73B5`
IMP | `D41BF2F313E9EE8CBB20EF9AD2025250`
PESHA1 | `AC5DB43854C8D85A6502701EFEEB9D58FE5C6BC2`
PE256 | `D7B0F9D20837C9B0DFDAB3A28662EACD2265EFC7E908DFA014F55B60716BBFA3`

## Runtime Data

### Usage (stdout):
```cmhg
Displays or modifies the checking of disk at boot time.

CHKNTFS volume [...]
CHKNTFS /D
CHKNTFS /T[:time]
CHKNTFS /X volume [...]
CHKNTFS /C volume [...]

  volume         Specifies the drive letter (followed by a colon),
                 mount point, or volume name.
  /D             Restores the machine to the default behavior; all drives are
                 checked at boot time and chkdsk is run on those that are
                 dirty.
  /T:time        Changes the AUTOCHK initiation countdown time to the
                 specified amount of time in seconds.  If time is not
                 specified, displays the current setting.
  /X             Excludes a drive from the default boot-time check.  Excluded
                 drives are not accumulated between command invocations.
  /C             Schedules a drive to be checked at boot time; chkdsk will run
                 if the drive is dirty.

If no switches are specified, CHKNTFS will display if the specified drive is
dirty or scheduled to be checked on next reboot.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\chkntfs.exe |
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

* Original Filename: CHKNTFS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/6e383e528f896345ee9e45a247f66b0603ca30fd30a92a838dae263c97733b67/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


