---
title: manage-bde.wsf | 
excerpt: What is manage-bde.wsf?
---

# manage-bde.wsf 

* File Path: `C:\Windows\system32\manage-bde.wsf`

## Hashes

Type | Hash
-- | --
MD5 | `7A495CA1402C2F9F5D035092AD808669`
SHA1 | `5D46BBD1DD2A82CCC7F7FF5CB17A8C37AC92B258`
SHA256 | `79A54FBBE4C882A0E08ACED234F312A8D46CB4B5433469F705FB063746E5AF26`
SHA384 | `837B8F9067A563D7FF9D54E6427344D10B8679B2F7071DF903979479FD8F9DA80912541765257A6D8171950CE4D8C5D5`
SHA512 | `593B00D665E50C3D0B5EC60CC37A83F49AEE932CEC2D2B92EB9484D6149606C9C6637034A0C63A4226A1BFB9FF1090BF5C59781832981DC1339E66751926EEA1`
SSDEEP | `24:nT9Ax9PJAZ+DffvF9CUlkouOYkWVqf+viBzg8Qpj2QpTDAOMZn:TkGZwFDo2BzHQEQEZ`
PESHA1 | `5D46BBD1DD2A82CCC7F7FF5CB17A8C37AC92B258`
PE256 | `79A54FBBE4C882A0E08ACED234F312A8D46CB4B5433469F705FB063746E5AF26`

## Runtime Data

### Usage (stdout):
```cmhg
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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/79a54fbbe4c882a0e08aced234f312a8d46cb4b5433469f705fb063746e5af26/detection


## Possible Misuse

*The following table contains possible examples of `manage-bde.wsf` being misused. While `manage-bde.wsf` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `Name: Manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Command: set comspec=c:\windows\system32\calc.exe & cscript c:\windows\system32\manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `Description: Set the comspec variable to another executable prior to calling manage-bde.wsf for execution.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Command: copy c:\users\person\evil.exe c:\users\public\manage-bde.exe & cd c:\users\public\ & cscript.exe c:\windows\system32\manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `Description: Run the manage-bde.wsf script with a payload named manage-bde.exe in the same directory to run the payload file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- Path: C:\Windows\System32\manage-bde.wsf`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Manage-bde.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Manage-bde.yml) | `- IOC: Manage-bde.wsf should normally not be invoked by a user`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: manage-bde.wsf Signed Script Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: manage-bde.wsf Signed Script Command Execution [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | - [Atomic Test #2 - manage-bde.wsf Signed Script Command Execution](#atomic-test-2---manage-bdewsf-signed-script-command-execution) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | ## Atomic Test #2 - manage-bde.wsf Signed Script Command Execution | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | Executes the signed manage-bde.wsf script with options to execute an arbitrary command. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | cscript %windir%\System32\manage-bde.wsf | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

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

- [Enabling BitLocker by Using the Command Line](/previous-versions/windows/it-pro/windows-7/dd894351(v=ws.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


