---
title: chkntfs.exe | NTFS Volume Maintenance Utility
excerpt: What is chkntfs.exe?
---

# chkntfs.exe 

* File Path: `C:\Windows\SysWOW64\chkntfs.exe`
* Description: NTFS Volume Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `A9B42ED1B14BB22EF07CCC8228697408`
SHA1 | `DC7CDC53D24CF94D66A77A9AD5AB84551056659A`
SHA256 | `A7E7965C36A54135BF192AA34ED32065C151691EECC5F5C17FFC1DB2C767478A`
SHA384 | `F00BC15CB97A506932BA060578D14AA0333FBC70DF116B7E9AD430DFD16A689F0B273116F17AD00A1AF53C0577D55F27`
SHA512 | `49378910D09003A3A97EAF4B320BFC42C00F2EC87C1D5C3344E96C0B9D2E3D562736EC4DC6F13F830821C9A04CCBF60DE210A9F93A426A75DE31F6D5D6A4EC30`
SSDEEP | `192:dlvgZmvQxNwXMTnCzdZDqAWjVcEXKYgQrSKidzdrLROUazLUq7sgkN7nQWJ46WzG:7IKYNwuidowQrS9RBELDo7N8Wi6Wz2j`
IMP | `D0F4E345E64F27143A66B4C09C8B88D7`
PESHA1 | `542624BB008B84F7B17200C87F44E1AD76A1C51B`
PE256 | `4B0511952DF051F42B191F02B566D90429529AC6902114FF2173CAC0DB2C5915`

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
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\chkntfs.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHKNTFS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/a7e7965c36a54135bf192aa34ed32065c151691eecc5f5c17ffc1db2c767478a/detection



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


