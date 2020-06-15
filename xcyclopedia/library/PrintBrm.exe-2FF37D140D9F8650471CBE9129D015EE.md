
# PrintBrm.exe 

* File Path: `C:\Windows\system32\spool\tools\PrintBrm.exe`
* Description: Print BRM command line tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2FF37D140D9F8650471CBE9129D015EE`
SHA1 | `B133C6F2A1CD05B4EE9FF769B2D662E00BF3BAC7`
SHA256 | `1FE86D2C761B0CF8DE373875D225CCC1B1D9364F284E581BDE8BD16B146E03F4`
SHA384 | `7322F95BE2B4B4011730C33BE2512A80C042C0DF824606D66B3AD425F6EF2CAC5560F18380566AF2401F5D7D8404CDF7`
SHA512 | `225A865B1161873DF5044F7C796A2AEDB4CA7EABD78257186A3ED4DA9A4B25949B71E984A9A39BB02CFF87768328F295A9959A611CC176F9A9CF049BC694D31E`
SSDEEP | `384:FGrr3jeHW0/MMEMbOY9y7QLhDcuC0uJA5zRMdtBbNke63SN0GO0rSTOccxLjYVWo:0Hje20/cng4l0bzQbv+SF5rSTLcxgE`

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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PrintBrm.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


