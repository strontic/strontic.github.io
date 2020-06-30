---
title: manage-bde.exe | BitLocker Drive Encryption: Configuration Tool
---

# manage-bde.exe 

* File Path: `C:\Windows\system32\manage-bde.exe`
* Description: BitLocker Drive Encryption: Configuration Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `84021D418863A3E530D2E3F65F5D154C`
SHA1 | `4EEE495D9121CB6BB510A1298E209B175454B1AD`
SHA256 | `38F20A75E04BB9A53C563152A90A5B29AB689AFF58D6ABD3E005D156EE4E4C73`
SHA384 | `E82F9D96B62FBB7494F9329F3C8F288270A517D0268BBAE8AC6EE4B1B134A35EBBA20EBB86898B9C9EAF9781CEEE7F5F`
SHA512 | `AEDCC746BF543DB4BB7529F5C2FF678DFC386AC53A7A0D1E51A3B46FBD62BB7455A0630E1EAAA73CD73CB1D340DF65677CF3CACB261619C636CDD073842B4B75`
SSDEEP | `6144:9sZ+OW0m5L6kLZc87GF1lqq1Bmt5Vs7nyatGt+SYF:9snWBhPS8lH+S+`

## Runtime Data

### Usage (stdout):
```Batchfile
BitLocker Drive Encryption: Configuration Tool version 10.0.19041
Copyright (C) 2013 Microsoft Corporation. All rights reserved.

manage-bde[.exe] -parameter [arguments]

Description:
    Configures BitLocker Drive Encryption on disk volumes.

Parameter List:
    -status     Provides information about BitLocker-capable volumes.
    -on         Encrypts the volume and turns BitLocker protection on.
    -off        Decrypts the volume and turns BitLocker protection off.
    -pause      Pauses encryption, decryption, or free space wipe.
    -resume     Resumes encryption, decryption, or free space wipe.
    -lock       Prevents access to BitLocker-encrypted data.
    -unlock     Allows access to BitLocker-encrypted data.
    -autounlock Manages automatic unlocking of data volumes.
    -protectors Manages protection methods for the encryption key.
    -SetIdentifier or -si
                Configures the identification field for a volume.
    -ForceRecovery or -fr
                Forces a BitLocker-protected OS to recover on restarts.
    -changepassword
                Modifies password for a data volume.
    -changepin  Modifies PIN for a volume.
    -changekey  Modifies startup key for a volume.
    -KeyPackage or -kp
                Generates a key package for a volume.
    -upgrade    Upgrades the BitLocker version.
    -WipeFreeSpace or -w
                Wipes the free space on the volume.
    -ComputerName or -cn
                Runs on another computer. Examples: "ComputerX", "127.0.0.1"
    -? or /?    Displays brief help. Example: "-ParameterSet -?"
    -Help or -h Displays complete help. Example: "-ParameterSet -h"

Examples:
    manage-bde -status
    manage-bde -on C: -RecoveryPassword -RecoveryKey F:\
    manage-bde -unlock E: -RecoveryKey F:\84E151C1...7A62067A512.bek

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: manage-bde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-124495DF347DBB3FE50CAF55B211CBD9.md) | 54
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-1DE833E454562483BD0CD60D96B3CA0C.md) | 49
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-A5BCC0E852AC6B17F3D0E6C9F95E95D4.md) | 50
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-29B6905327F9571F99697BA8951F60D5.md) | 47
[C:\WINDOWS\system32\BdeHdCfg.exe](BdeHdCfg.exe-49993078062CFCCFE5EE1ACCF47B1EAF.md) | 49
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-89D0572C9B53F34230C8514F6B11BD56.md) | 49
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-23C71245731416DD69B78A64BDB8A230.md) | 40
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-6DF8548ED3BA2DF3C682A5E342DA7BE4.md) | 36
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-7EDA3DEC2AC9206D153AF752F20B4B92.md) | 40
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-1F7EC0D141821C5BB3B51C054E7CA8D4.md) | 47
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-6B919B72E58391B39A09EE388FA89BBB.md) | 50
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-A9C78F189E2111734F7E961EBE38188A.md) | 50
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-46A96812D5A434C3794F06DB978D0C19.md) | 54
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-68A4D7474F142060F46C37BCE45FABFE.md) | 47
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-7B6ADCD4165DE7732C61E2381D69BEA3.md) | 50
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-1DDE0327CAF5309EC597B21726028153.md) | 50
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-D7B50B5843EFD63DBAAE341B8E70856D.md) | 41
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-EE3C814D1035CDCDF48E232742D6FA43.md) | 47
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-1B9EC98C9542EF45D511E3D003E00369.md) | 50
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-1FDC5C40B2DE4167895EFFCAB0854C0C.md) | 47
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-57935115ADFEC73AB98655EEA54DF706.md) | 44
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-146C56E1598A4F568B6F0342A485DD84.md) | 58
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-D44D57F5AAF9D5FD64EFC00C4761C304.md) | 57
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-0858920D41400F8C585AFE31B80FF884.md) | 46
[C:\WINDOWS\system32\repair-bde.exe](repair-bde.exe-7DE31602235A9B4A6C1EBCFB6E6E30E2.md) | 49
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-9FA5C71841FDE30C7D62CC95E5389E6A.md) | 46

## Possible Misuse

*The following table contains possible examples of `manage-bde.exe` being misused. While `manage-bde.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `Name: Manage-bde.wsf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `  - Command: set comspec=c:\windows\system32\calc.exe & cscript c:\windows\system32\manage-bde.wsf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `    Description: Set the comspec variable to another executable prior to calling manage-bde.wsf for execution.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `  - Command: copy c:\users\person\evil.exe c:\users\public\manage-bde.exe & cd c:\users\public\ & cscript.exe c:\windows\system32\manage-bde.wsf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `    Description: Run the manage-bde.wsf script with a payload named manage-bde.exe in the same directory to run the payload file.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `  - Path: C:\Windows\System32\manage-bde.wsf` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `  - IOC: Manage-bde.wsf should normally not be invoked by a user` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) |   - Atomic Test #2: manage-bde.wsf Signed Script Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) |   - Atomic Test #2: manage-bde.wsf Signed Script Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | - [Atomic Test #2 - manage-bde.wsf Signed Script Command Execution](#atomic-test-2---manage-bdewsf-signed-script-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | ## Atomic Test #2 - manage-bde.wsf Signed Script Command Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Executes the signed manage-bde.wsf script with options to execute an arbitrary command. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | cscript manage-bde.wsf | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## manage-bde

Turns on or turns off BitLocker, specifies unlock mechanisms, updates recovery methods, and unlocks BitLocker-protected data drives.

> [!NOTE]
> This command-line tool can be used in place of the **BitLocker Drive Encryption** Control Panel item.

### Syntax

```
manage-bde [-status] [â€“on] [â€“off] [â€“pause] [â€“resume] [â€“lock] [â€“unlock] [â€“autounlock] [â€“protectors] [â€“tpm]
[â€“setidentifier] [-forcerecovery] [â€“changepassword] [â€“changepin] [â€“changekey] [-keypackage] [â€“upgrade] [-wipefreespace] [{-?|/?}] [{-help|-h}]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| [manage-bde status](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-status.md) | Provides information about all drives on the computer, whether or not they are BitLocker-protected. |
| [manage-bde on](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-on.md) | Encrypts the drive and turns on BitLocker. |
| [manage-bde off](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-off.md) | Decrypts the drive and turns off BitLocker. All key protectors are removed when decryption is complete. |
| [manage-bde pause](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-pause.md) | Pauses encryption or decryption. |
| [manage-bde resume](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-resume.md) | Resumes encryption or decryption. |
| [manage-bde lock](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-lock.md) | Prevents access to BitLocker-protected data. |
| [manage-bde unlock](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-unlock.md) | Allows access to BitLocker-protected data with a recovery password or a recovery key. |
| [manage-bde autounlock](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-autounlock.md) | Manages automatic unlocking of data drives. |
| [manage-bde protectors](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-protectors.md) | Manages protection methods for the encryption key. |
| [manage-bde tpm](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-tpm.md) | Configures the computer's Trusted Platform Module (TPM). This command isn't supported on computers running Windows 8 or **win8_server_2**. To manage the TPM on these computers, use either the TPM Management MMC snap-in or the TPM Management cmdlets for Windows PowerShell. |
| [manage-bde setidentifier](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-setidentifier.md)   | Sets the drive identifier field on the drive to the value specified in the **Provide the unique identifiers for your organization** Group Policy setting. |
| [manage-bde ForceRecovery](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-forcerecovery.md) | Forces a BitLocker-protected drive into recovery mode on restart. This command deletes all TPM-related key protectors from the drive. When the computer restarts, only a recovery password or recovery key can be used to unlock the drive. |
| [manage-bde changepassword](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-changepassword.md) | Modifies the password for a data drive. |
| [manage-bde changepin](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-changepin.md) | Modifies the PIN for an operating system drive. |
| [manage-bde changekey](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-changekey.md) | Modifies the startup key for an operating system drive. |
| [manage-bde KeyPackage](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-keypackage.md) | Generates a key package for a drive. |
| [manage-bde upgrade](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-upgrade.md) | Upgrades the BitLocker version. |
| [manage-bde WipeFreeSpace](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/manage-bde-wipefreespace.md) | Wipes the free space on a drive. |
| -? or /? | Displays brief Help at the command prompt. |
| -help or -h | Displays complete Help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Enabling BitLocker by Using the Command Line](https://technet.microsoft.com/library/dd894351(v=ws.10).aspx)

---



MIT License. Copyright (c) 2020 Strontic.


