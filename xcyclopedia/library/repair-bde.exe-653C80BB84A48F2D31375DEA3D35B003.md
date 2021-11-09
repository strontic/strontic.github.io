---
title: repair-bde.exe | BitLocker Drive Encryption- Repair Tool
excerpt: What is repair-bde.exe?
---

# repair-bde.exe 

* File Path: `C:\WINDOWS\system32\repair-bde.exe`
* Description: BitLocker Drive Encryption: Repair Tool

## Hashes

Type | Hash
-- | --
MD5 | `653C80BB84A48F2D31375DEA3D35B003`
SHA1 | `0D3F764E97EC0F4B6D57A462E89FAFE2D4B2EE50`
SHA256 | `E9F88DCAAD82AFB7DDE4AE1674D7987725ADAB608B392A11F7FF07F49623E1B2`
SHA384 | `B14CF0CC392572CA82C3DE7793883E9EC8734BB74F69925A563793861083F9E440253B7C9065CB1F0D0315DF80DB1BDC`
SHA512 | `AA711B4C98FA48B83D89FBA2118B5EC1E2E587FEAAA091D7512C6C9E97AD52AF6F74486FFC7E5183D235CB286D75807260FEDC02B8223BD904098C5884ACE368`
SSDEEP | `3072:Wswsmu9MQfkXaBmwnVS570M9kdatGCO+xmBc+hMPhPsx:Nwsmu9nkSVs7nyatGt+SYF`
IMP | `C367E5351E6B578F24E96CE56960C8A1`
PESHA1 | `618F85306D01A4E48D9F96D26F80C5E36BEF555A`
PE256 | `A4259D388270B1353373DFD8751FFDC651DAA35420FCBD5FFE2607AF7290C92D`

## Runtime Data

### Usage (stdout):
```cmhg
BitLocker Drive Encryption: Repair Tool version 10.0.22000
Copyright (C) 2013 Microsoft Corporation. All rights reserved.

Usage:

repair-bde[.exe] InputVolume
                  { OutputVolumeOrImage }
                  { {-RecoveryPassword|-rp} NumericalPassword |
                    {-RecoveryKey|-rk} PathToExternalKeyFile |
                    {-Password|-pw} }
                  [{-KeyPackage|-kp} PathToKeyPackage]
                  [{-LogFile|-lf} PathToLogFile]
                  [{-?|/?}]

Description:
  Attempts to repair or decrypt a damaged BitLocker-encrypted volume using the
  supplied recovery information. If BitLocker was in the process of encryption
  or decryption or had been suspended prior to volume failure a clear key will
  be present on the volume. Repair-bde attempts to use this clear key by
  default if another key is not specified.

  WARNING! To avoid additional data loss, you should have a spare hard drive
  available. Use this spare drive to store decrypted output or to back up the
  contents of the damaged volume.  

Parameters:
  InputVolume
                The BitLocker-encrypted volume to repair.
                Example: "C:",
                         "\\?\Volume{26a21bda-a627-11d7-9931-806e6f6e6963}".

  OutputVolumeOrImage
                The volume to store decrypted contents, or the file
                location to create an image file of the contents.
                Examples: "D:", "D:\imagefile.img".
                
                WARNING! All information on this output volume will be
                overwritten.

  -rk  or -RecoveryKey
                Provide an external key to unlock the volume. 
                Example: "F:\RecoveryKey.bek".

  -rp  or -RecoveryPassword
                Provide a numerical password to unlock the volume.
                Example: "111111-222222-333333-...".

  -pw  or -Password
                Provide a password to unlock the volume.

  -kp  or -KeyPackage
                Optional. Provide a key package to unlock the volume.
                Example: "F:\ExportedKeyPackage"
                
            If this option is blank, the tool will look for the key package
            automatically. This option is needed only if required by the tool.
	
  -lf  or -LogFile
                Optional. Provide a path to a file that will store progress
                information. Example: "F:\log.txt".

  -f   or -Force
                Optional. When used, forces a volume to be dismounted even if
                it cannot be locked. This option is needed only if required by
                the tool.

  -?   or /?    
                Shows this screen.

Examples:
  repair-bde C: D: -rk F:\RecoveryKey.bek -Force
  repair-bde C: D: -rp 111111-222222-[...] -lf F:\log.txt
  repair-bde C: D: -kp F:\KeyPackage -rp 111111-222222-[...]
  repair-bde C: D:\imagefile.img -kp F:\KeyPackage -rk F:\RecoveryKey.bek
  repair-bde C: D: -pw


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\repair-bde.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: repair-bde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/e9f88dcaad82afb7dde4ae1674d7987725adab608b392a11f7ff07f49623e1b2/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-124495DF347DBB3FE50CAF55B211CBD9.md) | 74
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-1DE833E454562483BD0CD60D96B3CA0C.md) | 77
[C:\windows\system32\baaupdate.exe](baaupdate.exe-5B49CC654ADC1CE20F2756FB61C1E3A4.md) | 74
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-6B16BB0AE5A0D92ACB86E24F0C3CAA70.md) | 79
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-A5BCC0E852AC6B17F3D0E6C9F95E95D4.md) | 79
[C:\WINDOWS\system32\BdeHdCfg.exe](BdeHdCfg.exe-131722BA9E3867893E6208BD71B3169E.md) | 71
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-29B6905327F9571F99697BA8951F60D5.md) | 71
[C:\WINDOWS\system32\BdeHdCfg.exe](BdeHdCfg.exe-49993078062CFCCFE5EE1ACCF47B1EAF.md) | 69
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-89D0572C9B53F34230C8514F6B11BD56.md) | 69
[C:\windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-A0B0BD83DF86073C86D4111FDF4B82AB.md) | 74
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-23C71245731416DD69B78A64BDB8A230.md) | 44
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-6DF8548ED3BA2DF3C682A5E342DA7BE4.md) | 49
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-7EDA3DEC2AC9206D153AF752F20B4B92.md) | 41
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-EDF00F2F7E123623C07A144A1CE5CEF4.md) | 47
[C:\windows\system32\bdeunlock.exe](bdeunlock.exe-F1422C3B0232F78BFB19B51CBC88BB50.md) | 50
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-FEF5D67150C249DB3C1F4B30A2A5A22E.md) | 44
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-119E2408FA19D735A736AA10591AB138.md) | 80
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-1F7EC0D141821C5BB3B51C054E7CA8D4.md) | 79
[C:\windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-3F4811D92D68006E636245486A8D92B9.md) | 82
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-6B919B72E58391B39A09EE388FA89BBB.md) | 77
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-6D30C96F29F64B34BC98E4C81D9B0EE8.md) | 75
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-A9C78F189E2111734F7E961EBE38188A.md) | 75
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-46A96812D5A434C3794F06DB978D0C19.md) | 79
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-68A4D7474F142060F46C37BCE45FABFE.md) | 80
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-7B6ADCD4165DE7732C61E2381D69BEA3.md) | 79
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-8AC5A3A20CF18AE2308C64FD707EEB81.md) | 74
[C:\windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-9F4A6D072BF84183E96E8B4D6D536D73.md) | 80
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-A2F993D2E0F1265E592451D6238BD627.md) | 77
[C:\Windows\system32\fvecpl.dll](fvecpl.dll-7809069116F870A3555AE330B0AD66F3.md) | 40
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-1DDE0327CAF5309EC597B21726028153.md) | 71
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-4A6E8C3685044E623543C30A31342D98.md) | 60
[C:\windows\system32\fvenotify.exe](fvenotify.exe-6A7644DD7F83120D7230C67D74C180EB.md) | 69
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-D7B50B5843EFD63DBAAE341B8E70856D.md) | 65
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-EE3C814D1035CDCDF48E232742D6FA43.md) | 65
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-1B9EC98C9542EF45D511E3D003E00369.md) | 69
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-1FDC5C40B2DE4167895EFFCAB0854C0C.md) | 66
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-57935115ADFEC73AB98655EEA54DF706.md) | 65
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-C34C77567C966CD30CE8274D38BBE7FF.md) | 74
[C:\windows\system32\fveprompt.exe](fveprompt.exe-D1A5A16C5C361DFC062E7ADFD3D0C49F.md) | 69
[C:\Windows\system32\fveui.dll](fveui.dll-F5FBB09919FBE03401751FEE4046DA67.md) | 54
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-146C56E1598A4F568B6F0342A485DD84.md) | 49
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-84021D418863A3E530D2E3F65F5D154C.md) | 52
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-D44D57F5AAF9D5FD64EFC00C4761C304.md) | 50
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-E6577869DB69338E38173CD20C06A53E.md) | 41
[C:\windows\system32\manage-bde.exe](manage-bde.exe-F7E627DDF4C3B09BDB8954E02B4A375C.md) | 52
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-0858920D41400F8C585AFE31B80FF884.md) | 74
[C:\WINDOWS\system32\repair-bde.exe](repair-bde.exe-7DE31602235A9B4A6C1EBCFB6E6E30E2.md) | 72
[C:\windows\system32\repair-bde.exe](repair-bde.exe-8A8A24256B145338E025DCD848CBC1EF.md) | 72
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-9FA5C71841FDE30C7D62CC95E5389E6A.md) | 68


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## repair-bde

Attempts to reconstruct critical parts of a severely damaged drive and salvage recoverable data if the drive was encrypted by using BitLocker and if it has a valid recovery password or recovery key for decryption.

> [!IMPORTANT]
> If the BitLocker metadata data on the drive is corrupt, you must be able to supply a backup key package in addition to the recovery password or recovery key. If you used the default key back up setting for Active Directory Domain Services, your key package is backed up there. You can use the [BitLocker: Use BitLocker Recovery Password Viewer](/windows/security/information-protection/bitlocker/bitlocker-use-bitlocker-recovery-password-viewer) to obtain the key package from AD DS.
>
> Using the key package and either the recovery password or recovery key, you can decrypt portions of a BitLocker-protected drive, even if the disk is corrupted. Each key package works only for a drive with the corresponding drive identifier.

### Syntax

```
repair-bde <inputvolume> <outputvolumeorimage> [-rk] [â€“rp] [-pw] [â€“kp] [â€“lf] [-f] [{-?|/?}]
```

> [!WARNING]
> The contents of the output volume will be **completely deleted and overwritten** by the decrypted contents from the damaged BitLocker drive. If you want to save any existing data on the selected target drive, move the existing data to other reliable backup media first, before running the `repair-bde` command.

#### Parameters

| Parameter | Description |
| --- | --- |
| `<inputvolume>` | Identifies the drive letter of the BitLocker-encrypted drive that you want to repair. The drive letter must include a colon; for example: **C:**. If the path to a key package isn't specified, this command searches the drive for a key package. In the event that the hard drive is damaged, this command might not be able to find the package and will prompt you to provide the path. |
| `<outputvolumeorimage>` | Identifies the drive on which to store the content of the repaired drive. All information on the output drive will be overwritten. |
| -rk | Identifies the location of the recovery key that should be used to unlock the volume. This command can also be specified as **-recoverykey**. |
| -rp | Identifies the numerical recovery password that should be used to unlock the volume. This command can also be specified as **-recoverypassword**. |
| -pw | Identifies the password that should be used to unlock the volume. This command can also be specified as **-password** |
| -kp | Identifies the recovery key package that can be used to unlock the volume. This command can also be specified as **-keypackage**. |
| -lf | Specifies the path to the file that will store Repair-bde error, warning, and information messages. This command may also be specified as **-logfile**. |
| -f | Forces a volume to be dismounted even if it cannot be locked. This command can also be specified as **-force**. |
| -? or /? | Displays Help at the command prompt. |

#### Limitations

The following limitations exist for the this command:

- This command can't repair a drive that failed during the encryption or decryption process.

- This command assumes that if the drive has any encryption, then the drive has been fully encrypted.

### Examples

To attempt to repair drive C:, to write the content from drive C: to drive D: using the recovery key file (RecoveryKey.bek) stored on drive F:, and to write the results of this attempt to the log file (log.txt) on drive Z:, type:

```
repair-bde C: D: -rk F:\RecoveryKey.bek â€“lf Z:\log.txt
```

To attempt to repair drive C: and to write the content from drive C: to drive D: using the 48-digit recovery password specified, type:

```
repair-bde C: D: -rp 111111-222222-333333-444444-555555-666666-777777-888888
```

> [!NOTE]
> The recovery password should be typed in eight blocks of six digits with a hyphen separating each block.

To force drive C: to dismount, attempt to repair drive C:, and then to write the content from drive C: to drive D: using the recovery key package and recovery key file (RecoveryKey.bek) stored on drive F:, type:

```
repair-bde C: D: -kp F:\RecoveryKeyPackage -rk F:\RecoveryKey.bek -f
```

To attempt to repair drive C: and to write the content from drive C: to drive D:, where you must type a password to unlock drive C: (when prompted), type:

```
repair-bde C: D: -pw
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


