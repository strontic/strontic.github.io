---
title: BdeHdCfg.exe | BitLocker Drive Encryption: Drive Preparation Tool
---

# BdeHdCfg.exe 

* File Path: `C:\WINDOWS\system32\BdeHdCfg.exe`
* Description: BitLocker Drive Encryption: Drive Preparation Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `49993078062CFCCFE5EE1ACCF47B1EAF`
SHA1 | `34597C2BF5FA0BD247C74195B4D5A06FFD8BC461`
SHA256 | `B513A5CFF54702917DE47ADC85E717BAD75ADA41967253A55FB928365DF2E020`
SHA384 | `06CA05C82F119FC12922D0B20F9F02F2D9CD1218472D1C8790427F8EAC5AD0A940EB79440289D4BC595BF740E31B73D2`
SHA512 | `AA832DF6A6EC05C915EF5798B7577F5FF0968C4A2449D9019ABFF2FA64B61E502CFEBAAFE05D523CF5882E2C780BAB21DC331083BB15852ABD3D0D440157CC5E`
SSDEEP | `3072:qVSiRmzT/b1a+PKHVZzwnVS570M9kdatGCO+xmBc+hMPhPsx:q8x3KHVZ8Vs7nyatGt+SYF`

## Runtime Data

### Usage (stdout):
```Batchfile
BitLocker Drive Preparation Tool version 10.0.18362
Copyright (C) 2013 Microsoft Corporation. All rights reserved.

Usage:

BdeHdCfg[.exe] 
               [-driveinfo]
               [-target {default | unallocated | 
                         TargetDriveLetter {shrink | merge}}]
               [-newdriveletter DriveLetter]
               [-size SizeInMegabytes]
               [-quiet] [-restart] [{-? | /?}]

Description:
  This command prepares your hard drive for BitLocker Drive Encryption.

  Command line parameters are not case-sensitive.

Parameters:
  -driveinfo
        Displays information about valid target drives.

  -target
        Specifies the target and operation.

        Specify 'shrink' to create a new active partition.
        Specify 'merge' to make an existing partition active.
        Specify 'unallocated' to use unformatted space on disk.
        Specify 'default' for the target to be chosen automatically.

        Examples: -target D: merge
                  -target C: shrink
                  -target unallocated
                  -target default

  -newdriveletter
        Specifies the desired drive letter for the new drive. This option is
        only valid when a new drive is created.

        Example: -newdriveletter S:

  -size
        Specifies the desired size of the new drive. This option is only valid
        when a new drive is created.

        If not specified, the Drive Preparation Tool assumes the required
        minimum size of 550 megabytes.

        Example: -size 700
        
  -quiet
        Specifies operation in quiet mode. No output from the drive preparation
        tool is displayed.

  -restart
        Enables an automatic restart after drive preparation.

        You must restart your computer before enabling BitLocker.

  -? or /?
        Displays help for this command.

Examples:
    BdeHdCfg -target c: shrink -newdriveletter x: -size 550 -quiet -restart
    BdeHdCfg -target d: merge -quiet -restart
    BdeHdCfg -target unallocated -newdriveletter s:
    BdeHdCfg -target default


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

* Original Filename: BdeHdCfg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-1DE833E454562483BD0CD60D96B3CA0C.md) | 74
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-A5BCC0E852AC6B17F3D0E6C9F95E95D4.md) | 72
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-89D0572C9B53F34230C8514F6B11BD56.md) | 88
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-6DF8548ED3BA2DF3C682A5E342DA7BE4.md) | 46
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-7EDA3DEC2AC9206D153AF752F20B4B92.md) | 41
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-6B919B72E58391B39A09EE388FA89BBB.md) | 75
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-A9C78F189E2111734F7E961EBE38188A.md) | 74
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-68A4D7474F142060F46C37BCE45FABFE.md) | 74
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-7B6ADCD4165DE7732C61E2381D69BEA3.md) | 72
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-1DDE0327CAF5309EC597B21726028153.md) | 66
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-D7B50B5843EFD63DBAAE341B8E70856D.md) | 63
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-1B9EC98C9542EF45D511E3D003E00369.md) | 68
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-1FDC5C40B2DE4167895EFFCAB0854C0C.md) | 66
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-146C56E1598A4F568B6F0342A485DD84.md) | 54
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-84021D418863A3E530D2E3F65F5D154C.md) | 49
[C:\WINDOWS\system32\repair-bde.exe](repair-bde.exe-7DE31602235A9B4A6C1EBCFB6E6E30E2.md) | 69
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-9FA5C71841FDE30C7D62CC95E5389E6A.md) | 66


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## bdehdcfg

Prepares a hard drive with the partitions necessary for BitLocker Drive Encryption. Most installations of Windows 7 will not need to use this tool because BitLocker setup includes the ability to prepare and repartition drives as required.

> [!WARNING]
> There is a known conflict with the **Deny write access to fixed drives not protected by BitLocker** Group Policy setting located in **Computer Configuration\Administrative Templates\Windows Components\BitLocker Drive Encryption\Fixed Data Drives**.
>
>If bdehdcfg is run on a computer when this policy setting is enabled, you may encounter the following issues:
>
>- If you attempted to shrink the drive and create the system drive, the drive size will be successfully reduced and a raw partition will be created. However, the raw partition will not be formatted. The following error message is displayed: The new active Drive cannot be formatted. You may need to manually prepare your drive for BitLocker.
>
>- If you attempted to use unallocated space to create the system drive, a raw partition will be created. However, the raw partition will not be formatted. The following error message is displayed: The new active Drive cannot be formatted. You may need to manually prepare your drive for BitLocker.
>
>- If you attempted to merge an existing drive into the system drive, the tool will fail to copy the required boot file onto the target drive to create the system drive. The following error message is displayed: BitLocker setup failed to copy boot files. You may need to manually prepare your drive for BitLocker.
>
>- If this policy setting is being enforced, a hard drive cannot be repartitioned because the drive is protected. If you are upgrading computers in your organization from a previous version of Windows and those computers were configured with a single partition, you should create the required BitLocker system partition before applying the policy setting to the computers.

### Syntax

```
bdehdcfg [â€“driveinfo <drive_letter>] [-target {default|unallocated|<drive_letter> shrink|<drive_letter> merge}] [â€“newdriveletter] [â€“size <size_in_mb>] [-quiet]
```

##### Parameters

| Parameter | Description |
| --------- |----------- |
| [bdehdcfg: driveinfo](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-driveinfo.md) | Displays the drive letter, the total size, the maximum free space, and the partition characteristics of the partitions on the drive specified. Only valid partitions are listed. Unallocated space is not listed if four primary or extended partitions already exist. |
| [bdehdcfg: target](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-target.md) | Defines which portion of a drive to use as the system drive and makes the portion active. |
| [bdehdcfg: newdriveletter](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-newdriveletter.md) | Assigns a new drive letter to the portion of a drive used as the system drive. |
| [bdehdcfg: size](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-size.md) | Determines the size of the system partition when a new system drive is being created. |
| [bdehdcfg: quiet](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-quiet.md) | Prevents the display of all actions and errors in the command-line interface and directs bdehdcfg to use the Yes answer to any Yes/No prompts that may occur during subsequent drive preparation. |
| [bdehdcfg: restart](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/bdehdcfg-restart.md) | Directs the computer to restart after the drive preparation has finished. |
| /? | Displays Help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


