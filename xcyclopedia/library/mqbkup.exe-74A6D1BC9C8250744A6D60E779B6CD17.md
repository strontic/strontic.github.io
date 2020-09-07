---
title: mqbkup.exe | Message Queuing Backup/Restore Utility
---

# mqbkup.exe 

* File Path: `C:\Windows\system32\mqbkup.exe`
* Description: Message Queuing Backup/Restore Utility

## Hashes

Type | Hash
-- | --
MD5 | `74A6D1BC9C8250744A6D60E779B6CD17`
SHA1 | `48EB07F13061BCFFA8BC1D17B5D0FAC1A5D0871B`
SHA256 | `60A34D99E8A2DE0125DD3D70BCED2B683D65F23D1FA8E4A66ADD94F43F0C62C6`
SHA384 | `21ADE0B8690BDD699049BD14203C631CBCDDD23CBE1551E1DAF2F1D738FB64C578B2754B6F2322F6DA86C9133FF739C4`
SHA512 | `EC67A68D559794B0B344C573B2870D1E15F8CCF1D61D6A7030C2C961345CD4E0D91C2F638D5E548BD45EB21A7EA4653BE8041E9E9A3A030201D580A073C7A716`
SSDEEP | `768:Cch+k0cErStjguUYzzUBtjLZ/YIaw8dj8/4S+y8JMD0GsvQ2f+iHhx:Hz0cEr8UBYzzUBpLZwK8dIwg4c2ftr`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) Message Queue Backup\Restore Utility Version 5.00
Copyright (C) Microsoft 1997-2009. All rights reserved.

Usage:	mqbkup [-b | -r] backup_path  [-y] [-c msmq_resource_name] [-p new_storage_path] [-s] 

Arguments:
-b	backup to backup_path
-r	restore from backup_path
-y	don't prompt (Yes to all questions)
-c	cluster resource; please specify the MSMQ resource name
-p	restore storage to new_storage_path
-s	only restore system configuration
-?	print this help

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MQBKUP.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mqbkup

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Backs up MSMQ message files and registry settings to a storage device and restores previously-stored messages and settings.

Both the backup and the restore operations stop the local MSMQ service. If the MSMQ service was started beforehand, the utility will attempt to restart the MSMQ service at the end of the backup or the restore operation. If the service was already stopped before running the utility, no attempt to restart the service is made.

Before using the MSMQ Message Backup/Restore utility you must close all local applications that are using MSMQ.

### Syntax

```
mqbkup {/b | /r} <folder path_to_storage_device>
```

#### Parameters

| Parameter | Description |
| ------- | -------- |
| /b | Specifies backup operation. |
| /r | Specifies restore operation. |
| `<folder path_to_storage_device>` | Specifies the path where the MSMQ message files and registry settings are stored. |
| /? | Displays help at the command prompt. |

##### Remarks

- If a specified folder doesn't exist while performing either the backup or restore operation, the folder is automatically created by the utility.

- If you choose to specify an existing folder, it must be empty. If you specify a non-empty folder, the utility deletes every file and subfolder contained within it. In this case, you'll be prompted to give permission to delete existing files and subfolders. You can use the **/y** parameter to indicate that you agree beforehand to the deletion of all existing files and subfolders in the specified folder.

- The locations of folders used to store MSMQ message files are stored in the registry. Therefore, the utility restores MSMQ message files to the folders specified in the registry and not to the storage folders used before the restore operation.

#### Examples

To backup all MSMQ message files and registry settings, and to store them in the *msmqbkup* folder on your C: drive, type:

```
mqbkup /b c:\msmqbkup
```

To delete all existing files and subfolders in the *oldbkup* folder on your C: drive, and then to store MSMQ message files and registry settings in the folder, type:

```
mqbkup /b /y c:\oldbkup
```

To restore MSMQ messages and registry settings, type:

```
mqbkup /r c:\msmqbkup
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [MSMQ Powershell Reference](/powershell/module/msmq/?view=win10-ps)

---



MIT License. Copyright (c) 2020 Strontic.


