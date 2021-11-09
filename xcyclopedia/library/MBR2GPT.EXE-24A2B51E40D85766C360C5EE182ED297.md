---
title: MBR2GPT.EXE | 
excerpt: What is MBR2GPT.EXE?
---

# MBR2GPT.EXE 

* File Path: `C:\WINDOWS\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `24A2B51E40D85766C360C5EE182ED297`
SHA1 | `8188B8F879908F5F67A890CE2376839F63CBA920`
SHA256 | `421285682F92EBD05BC7340243ABD153403E0DD4B6770E46C0E921A1FB5890CB`
SHA384 | `EFEB7AB17AF1F3652A3EF17F80EA8CAB19DEDED29890BFA826A16AF74AB7221734E6B982C7B9B0DB2D558FC486CD9F02`
SHA512 | `AFD8BE5F516DE91140538B01E393464A02B15B7118DB839A93E9456A769A990A00C18EEBA370B02132AC87624C5011BE0489248D7B78C17050FEF4E0765BF78D`
SSDEEP | `6144:jWTaxRIvG8xjTDE44yOsCwXOSK1Gu97tdKuRC/yqqMqhuU/T0yixG2csHXJb+yLw:jWTYIvXRkzyOsCwXOSK1Gu97tdRC/yq8`
IMP | `8D2376D3422E7FFF208616261F742B90`
PESHA1 | `AE3086CCDBC48ED036DA799070B88812F2D1BA94`
PE256 | `7A1C2BE4F1C03394543F54749BAFBFEE1D0708AA5317AB8C1613EC007ED049D0`

## Runtime Data

### Usage (stdout):
```cmhg

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```cmhg
Invalid argument: --help

Invalid arguments


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MBR2GPT.EXE |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/421285682f92ebd05bc7340243abd153403e0dd4b6770e46c0e921a1fb5890cb/detection





MIT License. Copyright (c) 2020-2021 Strontic.


