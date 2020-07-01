---
title: repair-bde.exe | BitLocker Drive Encryption: Repair Tool
---

# repair-bde.exe 

* File Path: `C:\Windows\system32\repair-bde.exe`
* Description: BitLocker Drive Encryption: Repair Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9FA5C71841FDE30C7D62CC95E5389E6A`
SHA1 | `B00760877633FB4A34FCE53C1C5142F2FFD43284`
SHA256 | `13930144928B4C55AC75120678F3C523B6E6E1730B0E5BC972A15FAEAE399259`
SHA384 | `5B0087441AD8ECDAA326ACE1605B5F71FBA1BD2E0BAB3BFEAEB4648D54D556E9DA336F89335348F07956449E2AB5B877`
SHA512 | `B37C82EC0F6ECAB0887263BE677B1A1D6CFCABB775D22C4AF62A22AE544D6BDE8B31D2F99CB3BCBCD9A9C160692F69EFDAEEF387596434A3971D2E1E0EBDE412`
SSDEEP | `3072:Tv2Xi0hGCIG1PfGWxa637wnVS570M9kdatGCO+xmBc+hMPhPsx:Tv2Xi0hGCZUWaVs7nyatGt+SYF`

## Runtime Data

### Usage (stdout):
```Batchfile
BitLocker Drive Encryption: Repair Tool version 10.0.19041
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

* Original Filename: repair-bde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-124495DF347DBB3FE50CAF55B211CBD9.md) | 71
[C:\WINDOWS\system32\baaupdate.exe](baaupdate.exe-1DE833E454562483BD0CD60D96B3CA0C.md) | 74
[C:\windows\system32\baaupdate.exe](baaupdate.exe-5B49CC654ADC1CE20F2756FB61C1E3A4.md) | 74
[C:\Windows\system32\baaupdate.exe](baaupdate.exe-A5BCC0E852AC6B17F3D0E6C9F95E95D4.md) | 74
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-29B6905327F9571F99697BA8951F60D5.md) | 69
[C:\WINDOWS\system32\BdeHdCfg.exe](BdeHdCfg.exe-49993078062CFCCFE5EE1ACCF47B1EAF.md) | 66
[C:\Windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-89D0572C9B53F34230C8514F6B11BD56.md) | 65
[C:\windows\system32\BdeHdCfg.exe](BdeHdCfg.exe-A0B0BD83DF86073C86D4111FDF4B82AB.md) | 68
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-23C71245731416DD69B78A64BDB8A230.md) | 44
[C:\Windows\system32\bdeunlock.exe](bdeunlock.exe-6DF8548ED3BA2DF3C682A5E342DA7BE4.md) | 46
[C:\WINDOWS\system32\bdeunlock.exe](bdeunlock.exe-7EDA3DEC2AC9206D153AF752F20B4B92.md) | 41
[C:\windows\system32\bdeunlock.exe](bdeunlock.exe-F1422C3B0232F78BFB19B51CBC88BB50.md) | 50
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-1F7EC0D141821C5BB3B51C054E7CA8D4.md) | 74
[C:\windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-3F4811D92D68006E636245486A8D92B9.md) | 74
[C:\WINDOWS\system32\BitLockerWizard.exe](BitLockerWizard.exe-6B919B72E58391B39A09EE388FA89BBB.md) | 74
[C:\Windows\system32\BitLockerWizard.exe](BitLockerWizard.exe-A9C78F189E2111734F7E961EBE38188A.md) | 71
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-46A96812D5A434C3794F06DB978D0C19.md) | 72
[C:\Windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-68A4D7474F142060F46C37BCE45FABFE.md) | 72
[C:\WINDOWS\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-7B6ADCD4165DE7732C61E2381D69BEA3.md) | 72
[C:\windows\system32\BitLockerWizardElev.exe](BitLockerWizardElev.exe-9F4A6D072BF84183E96E8B4D6D536D73.md) | 74
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-1DDE0327CAF5309EC597B21726028153.md) | 63
[C:\windows\system32\fvenotify.exe](fvenotify.exe-6A7644DD7F83120D7230C67D74C180EB.md) | 63
[C:\WINDOWS\system32\fvenotify.exe](fvenotify.exe-D7B50B5843EFD63DBAAE341B8E70856D.md) | 61
[C:\Windows\system32\fvenotify.exe](fvenotify.exe-EE3C814D1035CDCDF48E232742D6FA43.md) | 60
[C:\WINDOWS\system32\fveprompt.exe](fveprompt.exe-1B9EC98C9542EF45D511E3D003E00369.md) | 65
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-1FDC5C40B2DE4167895EFFCAB0854C0C.md) | 63
[C:\Windows\system32\fveprompt.exe](fveprompt.exe-57935115ADFEC73AB98655EEA54DF706.md) | 61
[C:\windows\system32\fveprompt.exe](fveprompt.exe-D1A5A16C5C361DFC062E7ADFD3D0C49F.md) | 68
[C:\WINDOWS\system32\manage-bde.exe](manage-bde.exe-146C56E1598A4F568B6F0342A485DD84.md) | 49
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-84021D418863A3E530D2E3F65F5D154C.md) | 46
[C:\Windows\system32\manage-bde.exe](manage-bde.exe-D44D57F5AAF9D5FD64EFC00C4761C304.md) | 47
[C:\windows\system32\manage-bde.exe](manage-bde.exe-F7E627DDF4C3B09BDB8954E02B4A375C.md) | 52
[C:\Windows\system32\repair-bde.exe](repair-bde.exe-0858920D41400F8C585AFE31B80FF884.md) | 69
[C:\WINDOWS\system32\repair-bde.exe](repair-bde.exe-7DE31602235A9B4A6C1EBCFB6E6E30E2.md) | 69
[C:\windows\system32\repair-bde.exe](repair-bde.exe-8A8A24256B145338E025DCD848CBC1EF.md) | 68


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## repair-bde



Accesses encrypted data on a severely damaged hard disk if the drive was encrypted by using BitLocker. Repair-bde can reconstruct critical parts of the drive and salvage recoverable data as long as a valid recovery password or recovery key is used to decrypt the data. If the BitLocker metadata data on the drive has become corrupt, you must be able to supply a backup key package in addition to the recovery password or recovery key. This key package is backed up in Active Directory Domain Services (AD DS) if you used the default setting for AD DS backup. With this key package and either the recovery password or recovery key, you can decrypt portions of a BitLocker-protected drive if the disk is corrupted. Each key package will work only for a drive that has the corresponding drive identifier. You can use the [BitLocker Recovery Password Viewer for Active Directory](https://technet.microsoft.com/library/dd875531(v=ws.10).aspx) to obtain this key package from AD DS.

> [!NOTE]
> The BitLocker Recovery Password Viewer is included as one of the optional management features installable using Server Manage on Windows Server 2012.

The following limitations exist for the Repair-bde command-line tool:
-   Repair-bde cannot repair a drive that failed during the encryption or decryption process.
-   Repair-bde assumes that if the drive has any encryption, then the drive has been fully encrypted.



### Syntax

```
repair-bde <InputVolume> <OutputVolumeorImage> [-rk] [â€“rp] [-pw] [â€“kp] [â€“lf] [-f] [{-?|/?}]
```

##### Parameters

|Parameter|Description|
|---------|-----------|
|\<InputVolume>|Identifies the drive letter of the BitLocker-encrypted drive that you want to repair. The drive letter must include a colon; for example: **C:**.|
|\<OutputVolumeorImage>|Identifies the drive on which to store the content of the repaired drive. All information on the output drive will be overwritten.|
|-rk|Identifies the location of the recovery key that should be used to unlock the volume. This command may also be specified as **-recoverykey**.|
|-rp|Identifies the numerical recovery password that should be used to unlock the volume. This command may also be specified as **-recoverypassword**.|
|-pw|Identifies the password that should be used to unlock the volume. This command may also be specified as **-password**|
|-kp|Identifies the recovery key package that can be used to unlock the volume. This command may also be specified as **-keypackage**.|
|-lf|Specifies the path to the file that will store Repair-bde error, warning, and information messages. This command may also be specified as **-logfile**.|
|-f|Forces a volume to be dismounted even if it cannot be locked. This command may also be specified as **-force**.|
|-? or /?|Displays Help at the command prompt.|

### Remarks

If the path to a key package is not specified, **repair-bde** will search the drive for a key package. However, if the hard drive has been damaged, **repair-bde** may not be able to find the package and will prompt you to provide the path.

### Examples

To attempts to repair drive C and write the content from drive C to drive D by using the recovery key file (RecoveryKey.bek) stored on drive F and writes the results of this attempt to the log file (log.txt) on drive Z.
```
repair-bde C: D: -rk F:\RecoveryKey.bek â€“lf Z:\log.txt
```
To attempts to repair drive C and write the content on drive C to drive D by using the 48-digit recovery password specified. The recovery password should be typed in eight blocks of six digits with a hyphen separating each block.
```
repair-bde C: D: -rp 111111-222222-333333-444444-555555-666666-777777-888888
```
To forces drive C to be dismounted and then attempts to repair drive C and write the content on drive C to drive D by using the recovery key package and recovery key file (RecoveryKey.bek) stored on drive F.
```
repair-bde C: D: -kp F:\RecoveryKeyPackage -rk F:\RecoveryKey.bek -f
```
To attempts to repair drive C and write the content from drive C to drive D and you must type a password to unlock drive C: when prompted:
```
repair-bde C: D: -pw
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


