
# mountvol.exe 

* File Path: `C:\Windows\system32\mountvol.exe`
* Description: Mount Volume Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E343A47AD45B4F959CA483FF84BA4922`
SHA1 | `B73CF960A9F378D86D63C624CE2607F9B810FBEB`
SHA256 | `CE3C232D94FF7940D89F4D5F4888BD19A1E9D71BD6EC9A50715E785400C84652`
SHA384 | `C026EAA113C3AD97F44BE7B14852F21254D5D267E886F3B9ADEE03413C3E62136A253849F49B48EC5CE881566C4B0383`
SHA415 | `1820CB47139C7671E635B1CCD5C3945F24FFD9DDA5E40FE7582D7F3C55F735B0B66081DE4FCEDBF7F3511F355D7CFF6CE2111C4B6AD9AB5541BE0E2E7A0B88A2`
SSDEEP | `384:s9vzPgsDpAi6UhLec2zKkmMg/Chtwpo49UWEFW:s9vzPhDpBMzEh2wpouC`

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
        C:\

    \\?\Volume{00000000-0000-0000-0000-000000000000}\
        *** NO MOUNT POINTS ***


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MOUNTVOL.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


