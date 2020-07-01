---
title: mountvol.exe | Mount Volume Utility
---

# mountvol.exe 

* File Path: `C:\windows\system32\mountvol.exe`
* Description: Mount Volume Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `EC0B096A9297C03C9D4B3053B4351C48`
SHA1 | `DAF87809F408C24E7AB57550B850BEBC48E960AF`
SHA256 | `ABE94659F6A4AA670705EE1C8F948E765F7E7D5C43BE98F34825B31BB24C2919`
SHA384 | `25DEFE34B71E993BC51463BFF648840DB3F0FEBA97D6D9EC5FD50A75A999D41093EEA39C896CA796B89DDC970EDD70C6`
SHA512 | `D665B5F470C3794527338D6647BA7C9FB311B12F5DA3A817CDF8B0F73E6D909AE9B1DB77E5B62D2C2A29EADF8FC989BE39B44C4B73686AD703C6FCC2C03F3301`
SSDEEP | `384:wLdNxE6IoP5aIDMlhAp6H/snzx2lJA3jJjTeUWEsjkW5FW:65E6JPYIDMlhAcsnz8fCjKGsjL`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\mountvol.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: MOUNTVOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



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



MIT License. Copyright (c) 2020 Strontic.


