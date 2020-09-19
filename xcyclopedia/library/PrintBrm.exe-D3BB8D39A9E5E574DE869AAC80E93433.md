---
title: PrintBrm.exe | Print BRM command line tool
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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\spool\tools\PrintBrm.exe |


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





MIT License. Copyright (c) 2020 Strontic.


