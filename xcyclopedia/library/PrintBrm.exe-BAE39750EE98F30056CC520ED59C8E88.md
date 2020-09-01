---
title: PrintBrm.exe | Print BRM command line tool
---

# PrintBrm.exe 

* File Path: `C:\Windows\system32\spool\tools\PrintBrm.exe`
* Description: Print BRM command line tool

## Hashes

Type | Hash
-- | --
MD5 | `BAE39750EE98F30056CC520ED59C8E88`
SHA1 | `E97628C7DE13D0F631BFADE8994F6E4445F5ECBA`
SHA256 | `68DFB48A2A78893FFDCD8D02D24DC8BBF95699857DA95862B034E6EB885B6EF2`
SHA384 | `8899A738A78120332E366E54A6D751BD31527FEB6E042E0E77EEC1D98D689392DC7D3D0CD0E6227B9B1AF822E4E4D81F`
SHA512 | `D40F8C33423854C2F6B4181458D12F5AF9AA6B2658FA32D1D2AC8035F8899A97845DC6C62BDDB43DF0E2BFE23AA453B389BCBED3B36B3BF6703903C0748CD769`
SSDEEP | `384:VygfGoA3q3S/j6ae3m2vIOfgwi57MdLpdEjGt/Uy6ZbqY2+O5PP9WWhW:PGoA3qC/YX+SdFUzoY2ZPL`

## Runtime Data

### Usage (stdout):
```Batchfile
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
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\spool\tools\PrintBrm.exe |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
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
[C:\Windows\system32\spool\tools\PrintBrm.exe](PrintBrm.exe-7AE2A5715DB7E235C7D6A4D4417E9335.md) | 90




MIT License. Copyright (c) 2020 Strontic.


