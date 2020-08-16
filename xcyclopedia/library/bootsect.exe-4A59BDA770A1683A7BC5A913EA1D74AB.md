---
title: bootsect.exe | Boot Sector Manipulation Tool
---

# bootsect.exe 

* File Path: `C:\Windows\system32\bootsect.exe`
* Description: Boot Sector Manipulation Tool

## Hashes

Type | Hash
-- | --
MD5 | `4A59BDA770A1683A7BC5A913EA1D74AB`
SHA1 | `C65466640BD627F40C67C7BA07814BCAE4B69E2F`
SHA256 | `2D7CE2DD4A9CE5FBED2C150720280CF50808B0CD5D7D988CDAAF5BD1E9E292F3`
SHA384 | `F9CCB58F7BDCBB2D2491728FE48F8C4333EBB379519FC9BBDC9617459F05CBD993201EBE7A7849A9EA80795C094C4E66`
SHA512 | `846DDC20123C8F47F2E9205D17DCF5FF53CA962891B309E7AEBB0098ED6EB10EE56C53AC81C89745AC43B6FF8C4868A8144CAC8C35B090A38C4D70FD9ECD6D24`
SSDEEP | `768:rt9O59BuIAee9VkuIvsdzsyCY5eNildVUt7/8tK4ZcvNoXxrkWqVsiawjprT3lxU:RTB5egI78tKKc7XHui2IH5vgY83JDPxb`

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

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootsect.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\tzutil.exe](tzutil.exe-BBE2C493401937EABC8D1408305E2D0A.md) | 25
[C:\Windows\system32\tzutil.exe](tzutil.exe-D707382B7D60EB8830A2DA9D6480062A.md) | 30

## Possible Misuse

*The following table contains possible examples of `bootsect.exe` being misused. While `bootsect.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) |       $f3 = "bootsect.bak" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


