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
MD5 | `C7B3C2CDD7778366B007965BCB661147`
SHA1 | `5C8D77B7552C6325AFF417B398EB643696281947`
SHA256 | `7F2C546AB66AA9AED47EEAD71170BDA9DB6D5ECD6CFDC0CE0A7BC80B92D157E8`
SHA384 | `1B8C0D2DBC9B1F62418B605B69222B2E69BA7B0D9256E26CBE2B06555B59561BFB41EAE4C05606297401C19AC2B61829`
SHA512 | `AB889DEE6CE6F1B4592969428788C4E82B61B364E133F5811AFE04982E348749EEBD7A111192A9C33EDA970046647BCD610EA23BFC676B728479984384F9C651`
SSDEEP | `384:JHo0S2ZwW8OmCh3ivEEUN0Wd6Wgjc0Kg:JNS2ZbmwyQlY`
IMP | `D0F4E345E64F27143A66B4C09C8B88D7`
PESHA1 | `DEA0805CA18D170E99445C481A02B44A7971308E`
PE256 | `64BADC87AC5753C19AC0825226B90F9F3C9F9E0DDE6B1B7821315251828A209A`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CHKNTFS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/7f2c546ab66aa9aed47eead71170bda9db6d5ecd6cfdc0ce0a7bc80b92d157e8/detection/



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


