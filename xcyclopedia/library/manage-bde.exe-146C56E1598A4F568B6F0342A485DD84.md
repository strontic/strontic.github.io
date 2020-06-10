
# manage-bde.exe 
* File Path: `C:\WINDOWS\system32\manage-bde.exe`
* Description: BitLocker Drive Encryption: Configuration Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `146C56E1598A4F568B6F0342A485DD84`
SHA1 | `B49C5B846CB0BF31612A4357B7BD4647F4C71641`
SHA256 | `7C4D5E3CE3B97EBF2533C8529789EE4B1FCB846C95D21DCC9EC87EB1309A5BC9`
SHA384 | `A684AF67831592564E6FCC00AC0493F0B4728B152D2BE841E783FA5A1F0B0723008D337349C790F5FF25C26EB1BAC3D8`
SHA415 | `9486B32CA343BFA76DD6369B040CE317F56BBCCA6E4706EC81FAD80E1E4A4037AB3607B5A77DF135104DECDB952D098BDF192C6F94AF0CC048801939B4F662B9`
SSDEEP | `6144:bo2xdPdE8j77GF1Gqq1PmToVs7nyatGt+SYF:E2xdPL6OH+S+`

## Runtime Data
### Usage (stdout):
```Batchfile
BitLocker Drive Encryption: Configuration Tool version 10.0.18362
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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: manage-bde.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


