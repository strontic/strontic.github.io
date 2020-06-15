
# mountvol.exe 

* File Path: `C:\WINDOWS\system32\mountvol.exe`
* Description: Mount Volume Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F642F1A177ED7E0DEDC560F07BDAE210`
SHA1 | `FDD67A9C0365FFB8137E1599C831B7D68AE27452`
SHA256 | `CB3CD8ED33EA7A5754E171E41C2F1FFF1EE0F4C341E321481D9E4CB6D20FBE56`
SHA384 | `A4A6326915DEB7D14D0B414EF570DDD9FB676DCE1BBC7FE4E3E94E8C70F4AF7291681345D3415DC598CFAC975F3A936C`
SHA512 | `8A006F25C32C3BFACDF2AE7B8A38D004BA0714C6AC6D22D8D9C441E1CF812210D643FBFAA56F50C9BC57974EF3042197072EA2A3BE5913D94116D77A3E641127`
SSDEEP | `384:6UWTPsV288DIAUlJhiNKjlyGVXIgHDlTI6NvxsWmFW:6UWTPsMJDEle4JfjvNvxg`

## Runtime Data

### Usage (stdout):
```Batchfile
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

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        *** NO MOUNT POINTS ***

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        C:\

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        *** NO MOUNT POINTS ***

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        C:\ProgramData\Microsoft\Windows\Containers\BaseImages\00000000-0000-0000-0000-000000000000\BaseLayer\

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        *** NO MOUNT POINTS ***


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

* Original Filename: MOUNTVOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# mountvol

Creates, deletes, or lists a volume mount point. You can also link volumes without requiring a drive letter.

## Syntax

```
mountvol [<drive>:]<path volumename>
mountvol [<drive>:]<path> /d
mountvol [<drive>:]<path> /l
mountvol [<drive>:]<path> /p
mountvol /r
mountvol [/n|/e]
mountvol <drive>: /s
```

### Parameters

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

## Remarks

- If you dismount your volume while using the **/p** parameter, the volume list will show the volume as not mounted until a volume mount point is created.

- If your volume has more than one mount point, use **/d** to remove the additional mount points before using **/p**. You can make the basic volume mountable again by assigning a volume mount point.

- If you need to expand your volume space without reformatting or replacing a hard drive, you can add a mount path to another volume. The benefit of using one volume with several mount paths is that you can access all local volumes by using a single drive letter (such as `C:`). You don't need to remember which volume corresponds to which drive letterâ€”although you can still mount local volumes and assign them drive letters.

## Examples

To create a mount point, type:

```
mountvol \sysmount \\?\volume\{2eca078d-5cbc-43d3-aff8-7e8511f60d0e}\
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


