---
title: PrintBrm.exe | Print BRM command line tool
excerpt: What is PrintBrm.exe?
---

# PrintBrm.exe 

* File Path: `C:\WINDOWS\system32\spool\tools\PrintBrm.exe`
* Description: Print BRM command line tool

## Hashes

Type | Hash
-- | --
MD5 | `F15C1B19C2D045F41E512DE2F4CD7393`
SHA1 | `E0A027FEDF4141DEF8CC524C6B2E6ECB8747AFF2`
SHA256 | `690782126961316F81720BEC4EA9E160C8FDE2837B468487A41BA27568F11207`
SHA384 | `8EA259C41F274FFB496558229B899977B42C398513E1540C99107F209A6B872BF6C22E623C801441D73F80E7A059DDE3`
SHA512 | `10B877C3DD2190AA742226DC5242CAE01E83C8083351146ED7ADB1F5BBA4CF1B77D2A907874C1693DB9051DBAD64DDD49FC373D2F592AF6B10D610E3D1009BAC`
SSDEEP | `384:PN0dFv8UEW0C142UILosjjEcGG5BMTLC9fA8RKPEaEVuSROE3UY5Lz+WFhW:MJ8UEW7T4eEL6fNaH4zOE3Zzl`

## Runtime Data

### Usage (stdout):
```cmhg
Error: A single mode must be selected!

Access the Backup Recovery Migration tool through a command line interface.

PrintBrm -B|R|Q [-S <server>] -F <file> [-D <directory>] [-O FORCE] [-P ALL|ORIG] [-NOBIN] [-LPR2TCP] [-C <config file>] [-NOACL] [-?]
-B               Backup the server to the specified file
-R               Restore the configuration in the file to the server
-Q               Query the server or the backup file
-S <server name> Target server
-F <file name>   Target backup File
-D <directory>   Unpack the backup file to (with -R) or repack a backup file from (with -B) the given directory
-O FORCE         Force overwriting of existing objects
-P ALL|ORIG      Publish all printers in directory, or publish printers that were published originally
-NOBIN           Omit the binaries from the backup
-LPR2TCP         Convert LPR ports to Standard TCP/IP ports on restore
-C <file name>   Use the specified configuration file for BRM
-NOACL           Remove ACLs from print queues on restore
-?               Display this help

```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PrintBrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


