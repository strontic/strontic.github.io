---
title: mountvol.exe | Mount Volume Utility
excerpt: What is mountvol.exe?
---

# mountvol.exe 

* File Path: `C:\WINDOWS\SysWOW64\mountvol.exe`
* Description: Mount Volume Utility

## Hashes

Type | Hash
-- | --
MD5 | `536BD3A480C51E47A12C3CF671E1989F`
SHA1 | `94FDCD424E8268F138DBEC69311EFC43E1F57FFC`
SHA256 | `89FBC91B6B91B83A7D58F7D4942B205C110980D36E86941C16F9893617EF5541`
SHA384 | `34F3664A034ECC8EE85F93D2F8553C9F7AACE042673402192C4BD085C1CF38A8217A0F889E79F841C7D20649D938888C`
SHA512 | `C713ECDA23F975A8CE341E078695EF5D6E14ED0F959FB88312FC28F34A5C1C84B4349696F8476C0BA26129DE902293E9D5CD6D459D3738124E4D741D6C654F42`
SSDEEP | `192:vJ+py6zcOF0Vz1tgz3WcwRu/pq+DyHcUOxgYgQJwGEU2NuOkEWkFWVV:vI0J1uz3Wcsu/pCHyxkQe5NuJEWkFW`
IMP | `30F2C65A9103A7536B77118A741917B8`
PESHA1 | `6A065C26C6FF69F3B43280F0F19F25D386A5A1A1`
PE256 | `6D753E4DC7D9764E369C05EEB7B141E34E44F0CA06FEF8A11BE50A0C624EB42D`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\mountvol.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MOUNTVOL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/89fbc91b6b91b83a7d58f7d4942b205c110980d36e86941c16f9893617ef5541/detection



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


