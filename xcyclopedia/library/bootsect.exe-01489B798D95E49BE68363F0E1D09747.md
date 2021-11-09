---
title: bootsect.exe | Boot Sector Manipulation Tool
excerpt: What is bootsect.exe?
---

# bootsect.exe 

* File Path: `C:\WINDOWS\system32\bootsect.exe`
* Description: Boot Sector Manipulation Tool

## Hashes

Type | Hash
-- | --
MD5 | `01489B798D95E49BE68363F0E1D09747`
SHA1 | `763C5F20DBA1F53923EC884BE02F2BFF97FAAF55`
SHA256 | `216F86CD0E78A8F90DE5EA8B6007DAF0E7E57A0FB72AA3A0B68F6A775BB43AA1`
SHA384 | `F94A48A2AD1EAB0725D05D710E3A3CAA0F36CABE2E3531A0AA67915286295BB7B74DDA8D188916E94E36B30C88613F47`
SHA512 | `D81F14A6DCADBA2193492E5F0D8E5E34D46BB61C1A1E3715B0254ED6EAA0506E03C95B14B6E0BDFF22A7EDE73BD8EA21790FEA40AB29A9A2241F9781A32D6E00`
SSDEEP | `1536:BqB6t2aelpJvRLIn9uDwcBY5q3B3JPPcLi:BG6t2aKpFRLaMDDoAdxkLi`
IMP | `197B5F5CF02964BF07B3A72286DE3102`
PESHA1 | `94D561CFE91EC40FE8C655182CBF87471896E0BA`
PE256 | `AF832B9A86D9A6AD6694D2434D2A8A2311FF3AFB8216C22615956070A729F7CD`

## Runtime Data

### Usage (stdout):
```cmhg

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\bootsect.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: bootsect.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/216f86cd0e78a8f90de5ea8b6007daf0e7e57a0fb72aa3a0b68f6a775bb43aa1/detection


## Possible Misuse

*The following table contains possible examples of `bootsect.exe` being misused. While `bootsect.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_ragna_locker.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_ragna_locker.yar) | $f3 = "bootsect.bak" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


