
# mountvol.exe 

* File Path: `C:\Windows\SysWOW64\mountvol.exe`
* Description: Mount Volume Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F76F57233EF3F5F0CEBC324E9D6C5028`
SHA1 | `A9BB067E91A70C06212C48A0EDB98E34A50E1FEC`
SHA256 | `9B3D74A45ABACE6B7B20B5A7E52045910444BDC906195D2AAADEB4EB2CE99575`
SHA384 | `8E85D9C6F17351AFB5244BA028F8B615B389B178C7828695C702088A89125DB95EB8F9BD984D28942C4F90A9456D00C5`
SHA415 | `D88A0E0DADD55C15058F16CFD387AA2575DB5D8B8D6320DA2C0E8284ACDD711AB471B089BA303C2E2BA72D04D9C14FCA96DDADE67ED2345437E4B02CDBF4838A`
SSDEEP | `384:P9f2UAVjv89nDWWsXX2jZAONSp/ht+paisWEFW0m:FeUMw9nDWWM2e3x+paiqnm`

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


