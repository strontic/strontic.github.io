---
title: mountvol.exe | Mount Volume Utility
excerpt: What is mountvol.exe?
---

# mountvol.exe 

* File Path: `C:\WINDOWS\system32\mountvol.exe`
* Description: Mount Volume Utility

## Hashes

Type | Hash
-- | --
MD5 | `A5FEF5DBEE68C170E84217D69D1C1014`
SHA1 | `FFEA3780B259CD3DF1C2C5F60EA2C31A356A1001`
SHA256 | `6C52F7A534820BF3B59482C66884D58ACF083EAF928BC7E7D2890D7EED376C31`
SHA384 | `70103CF0000F939C36EE842C1E1149CFD1A2C3600DF56416C492F4EC0F8BB0B8AE17D06180D7A830EF0D4ABD614EB588`
SHA512 | `03C129044174B1DF7939B2B5341E731A8E58F2BA1ED05AE3309E759C8A0DACBACFD63DB38A95CBD11BD320CED26107A989ABA8D1F2453762361ABB11F8EB72FD`
SSDEEP | `384:aNTZNUI1Tv2KPtAD45eeqDQNUAmNvhzcWkFW:afSuTvjPtADgeeoq+Nvhz6`
IMP | `72D2CD1301A2466A3D1834DC3B95BE3F`
PESHA1 | `6D0F4CD9F1BFA3F96ABCBE5D48A11528039B9232`
PE256 | `589DFBA49B31CC5B531650B28275DA307D70D396ACE881DFC8AF64135D3BE5D1`

## Runtime Data

### Usage (stdout):
```cmhg
Creates, deletes, or lists a volume mount point.

MOUNTVOL [drive:]path VolumeName
MOUNTVOL [drive:]path /D
MOUNTVOL [drive:]path /L
MOUNTVOL [drive:]path /P
MOUNTVOL /R
MOUNTVOL /N
MOUNTVOL /E
MOUNTVOL drive: /S

    path        Specifies the existing NTFS directory where the mount
                point will reside.
    VolumeName  Specifies the volume name that is the target of the mount
                point.
    /D          Removes the volume mount point from the specified directory.
    /L          Lists the mounted volume name for the specified directory.
    /P          Removes the volume mount point from the specified directory,
                dismounts the volume, and makes the volume not mountable.
                You can make the volume mountable again by creating a volume
                mount point.
    /R          Removes volume mount point directories and registry settings
                for volumes that are no longer in the system.
    /N          Disables automatic mounting of new volumes.
    /E          Re-enables automatic mounting of new volumes.
    /S          Mount the EFI System Partition on the given drive.

Possible values for VolumeName along with current mount points are:

    \\?\Volume{903bcfde-507f-4ff6-a8a2-55a4e2a4e63e}\
        *** NO MOUNT POINTS ***

    \\?\Volume{25dbfd7a-f93b-4eaf-8f3a-6c71148dd61e}\
        C:\

    \\?\Volume{c40fae89-13d4-4152-9ab6-2723782c6898}\
        *** NO MOUNT POINTS ***

    \\?\Volume{38046b78-ca28-4a54-b9a0-8f64fe67fdfd}\
        *** NO MOUNT POINTS ***

    \\?\Volume{3dbb1c81-1b8b-11eb-9242-806e6f6e6963}\
        D:\


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\mountvol.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MOUNTVOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6c52f7a534820bf3b59482c66884d58acf083eaf928bc7e7d2890d7eed376c31/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mountvol

Creates, deletes, or lists a volume mount point. You can also link volumes without requiring a drive letter.

### Syntax

```
mountvol [<drive>:]<path volumename>
mountvol [<drive>:]<path> /d
mountvol [<drive>:]<path> /l
mountvol [<drive>:]<path> /p
mountvol /r
mountvol [/n|/e]
mountvol <drive>: /s
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `[<drive>:]<path>` | Specifies the existing NTFS directory where the mount point will reside. |
| `<volumename>` | Specifies the volume name that is the target of the mount point. The volume name uses the following syntax, where *GUID* is a globally unique identifier: `\\?\volume\{GUID}\`. The brackets `{ }` are required. |
| /d | Removes the volume mount point from the specified folder. |
| /l | Lists the mounted volume name for the specified folder. |
| /p | Removes the volume mount point from the specified directory, dismounts the basic volume, and takes the basic volume offline, making it unmountable. If other processes are using the volume, **mountvol** closes any open handles before dismounting the volume. |
| /r | Removes volume mount point directories and registry settings for volumes that are no longer in the system, preventing them from being automatically mounted and given their former volume mount point(s) when added back to the system. |
| /n | Disables automatic mounting of new basic volumes. New volumes are not mounted automatically when added to the system. |
| /e | Re-enables automatic mounting of new basic volumes. |
| /s | Mounts the EFI system partition on the specified drive. |
| /? | Displays help at the command prompt. |

### Remarks

- If you dismount your volume while using the **/p** parameter, the volume list will show the volume as not mounted until a volume mount point is created.

- If your volume has more than one mount point, use **/d** to remove the additional mount points before using **/p**. You can make the basic volume mountable again by assigning a volume mount point.

- If you need to expand your volume space without reformatting or replacing a hard drive, you can add a mount path to another volume. The benefit of using one volume with several mount paths is that you can access all local volumes by using a single drive letter (such as `C:`). You don't need to remember which volume corresponds to which drive letterâ€”although you can still mount local volumes and assign them drive letters.

### Examples

To create a mount point, type:

```
mountvol \sysmount \\?\volume\{2eca078d-5cbc-43d3-aff8-7e8511f60d0e}\
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


