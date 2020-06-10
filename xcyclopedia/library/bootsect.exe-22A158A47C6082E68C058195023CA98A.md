
# bootsect.exe 
* File Path: `C:\WINDOWS\system32\bootsect.exe`
* Description: Boot Sector Manipulation Tool
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `22A158A47C6082E68C058195023CA98A`
SHA1 | `1A87499345AC8B5AE72B5767622953D996D72927`
SHA256 | `879332FE86CA885636A5ECE7C5551B75EAB93D0FAD45D5D79F3D378B9149DB48`
SHA384 | `0C3D21308752842865763C338AF1DC6E88990C5F5CFAE4A16B15BACEC440348F8E5B1110B7A21D8611A0F01A585FE8E6`
SHA415 | `F144B139036AD101E01AFA8CF586AB2166CEC2BAC0FA0C4153C756F19A3C7F134AE8932FA02E0AED1C9F0B2CF4428695C36088F0003496404A5084C6E4FF8424`
SSDEEP | `1536:9qOIGiQ/GZpRNI1H/oHuYbwg0l53QiJP3JHpP9:9EZoGRN66/0T3QCv/1`

## Runtime Data
### Usage (stdout):
```Batchfile

bootsect {/help|/nt60|/nt52} {SYS|ALL|<DriveLetter>:} [/force] [/mbr]

Boot sector restoration tool

Bootsect.exe updates the master boot code for hard disk partitions in order to
switch between BOOTMGR and NTLDR.  You can use this tool to restore the boot
sector on your computer.

/help   Displays these usage instructions.

/nt52   Applies the master boot code that is compatible with NTLDR to SYS,
        ALL, or <DriveLetter>.  The operating system installed on SYS, ALL, or
        <DriveLetter> must be older than Windows Vista.

/nt60   Applies the master boot code that is compatible with BOOTMGR to SYS,
        ALL, or <DriveLetter>.  The operating system installed on SYS, ALL, or
        <DriveLetter> must be Windows Vista, Windows Server 2008 or later.

SYS     Updates the master boot code on the system partition used to boot
        Windows.

ALL     Updates the master boot code on all partitions.  ALL does not
        necessarily update the boot code for each volume.  Instead, this
        option updates the boot code on volumes that could be used as Windows
        boot volumes, which excludes any dynamic volumes that are not
        connected with an underlying disk partition.  This restriction is
        present because boot code must be located at the beginning of a disk
        partition.

<DriveLetter> Updates the master boot code on the volume associated with this
        drive letter.  Boot code will not be updated if either 1)
        <DriveLetter> is not associated with a volume or 2) <DriveLetter> is
        associated with a volume not connected to an underlying disk
        partition.

/force  Forcibly dismounts the volume(s) during the boot code update.  You
        should use this option with caution.

        If Bootsect.exe cannot gain exclusive volume access then the file
        system may overwrite the boot code before the next reboot.
        Bootsect.exe always attempts to lock and dismount the volume before
        each update.  When /force is specified, a forced dismount is attempted
        if the initial lock attempt fails.  A lock can fail, for example, if
        files on the target volume are currently opened by other programs.

        When successful, a forced dismount allows exclusive volume access and
        a reliable boot code update even though the initial lock failed.  At
        the same time, a forced dismount invalidates all open handles to files
        on the target volume.  This could result in unexpected behavior from
        the programs that opened these files.  Therefore, you should use this
        option with caution.

/mbr    Updates the Master Boot Record without changing the partition table on
        sector 0 of the disk that contains the partition specified by SYS, ALL,
        or drive letter.  When used with /nt52 option, the master boot record
        is compatible with operating systems older than Windows Vista.  When
        used with the /nt60 option, the master boot record is compatible with
        Windows Vista, Windows Server 2008 or later.

Example:

To apply the master boot code that is compatible with NTLDR to the volume
labeled E:, use the following command:

bootsect /nt52 E:

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

* Original Filename: bootsect.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


