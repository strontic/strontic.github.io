---
title: MBR2GPT.EXE | 
excerpt: What is MBR2GPT.EXE?
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `94D5863638E33A86DD35F69BBCA83E94`
SHA1 | `217BCC9FAFD1260AD99B8B9AC71E667F62884054`
SHA256 | `D2B0776313596FCF10488BDD1F09C7044F93F06F4D85D25A44A39A5D33622E34`
SHA384 | `294DF3ADD45AD2EF6DD98025CB8B85E8103304E90FB70BFE146B99E46DAD91E5B913983C572A21B1261B31E4BF7051FC`
SHA512 | `3220B732533FE492271E3D60F6D72F5E599471A047CCC626C5EF1CED56545B7D5056D81C27B068A7106A6EFAFEA140C502E8F2599B5732086B9E1943D7127A55`
SSDEEP | `12288:EjsAb0eiTg2b1wj4KpuFBGuaYPYhztJ+CGBJNamTxQldNQO6GbsEae:E5b3kYMFMu/kDWKf`

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
C:\Windows\system32\MBR2GPT.EXE |
C:\Windows\SYSTEM32\ntdll.dll |


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


