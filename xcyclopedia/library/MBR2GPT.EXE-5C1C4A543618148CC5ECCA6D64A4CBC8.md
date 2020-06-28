---
title: MBR2GPT.EXE | 
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`
* Description: 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `5C1C4A543618148CC5ECCA6D64A4CBC8`
SHA1 | `2C9C2FD6813E70A19A9230BA8E3139FB4618CA69`
SHA256 | `8E7572420E11657B69A2F98B268A612C51F780B47B2E3F704158F918571F491E`
SHA384 | `24FC9874EA04A2D76DD50F0A57D37C0A2145752A14C4522E025A24C0E515AD3829EF171BED69A5D3DCC87A427A0DD238`
SHA512 | `ECF7B55237DAEDA5C6BB5B032E8A1A95DF7ACE34AF5762E23CB2F5875FFD6C29962ACB45A1244BEDDE89876420F3CDCEA7A447EF60298B7C5BE8E8AB08922F36`
SSDEEP | `12288:dBkgUjW7moZ1YaziJAwoaM1237Zj3SxFh92OMfCQLXjdo7a/2+pl5BNJtzGRmHeS:TkVCSoXmJlorxN2zjuG/Tz7CFztSW`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
Invalid argument: -help

Invalid arguments


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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





MIT License. Copyright (c) 2020 Strontic.


