
# mountvol.exe 

* File Path: `C:\WINDOWS\SysWOW64\mountvol.exe`
* Description: Mount Volume Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0B61BCAED563051163D83B4F835F7AAA`
SHA1 | `0DF2C0165B126AAB629E000570B95949822AA812`
SHA256 | `1031661048C6EF1CD70B29470D9B012C6F18C6E2D81BC7E8862F6C2223C0E0BB`
SHA384 | `9D36F7AFB9B31692537BFCA1FAEB803016B4E689DE47F1891519B32B638E919862E1779937D1D5CB3D0FE1A6CAF55B77`
SHA415 | `9187C7BAAAD190D5ABF410522BFA446F38E942E43433E4BA2CC583EF0FD11723E9BFAACA6BAB1A55FA2C348D127C6F89AE5FB3A235947FE6D902A8A46FB1F449`
SSDEEP | `192:qyFxxnyEs5Esjdd2gOWESCCwzWZztdeK8uUOxPtLWwI7E92Nuzk0WmFWlIu:q8JQddrOWgPzYOK8YxVLpIzNuI0WmFW`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MOUNTVOL.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


