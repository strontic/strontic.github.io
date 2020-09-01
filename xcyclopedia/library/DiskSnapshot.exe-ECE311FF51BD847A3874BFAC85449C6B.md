---
title: DiskSnapshot.exe | DiskSnapshot.exe
---

# DiskSnapshot.exe 

* File Path: `C:\Windows\system32\DiskSnapshot.exe`
* Description: DiskSnapshot.exe

## Hashes

Type | Hash
-- | --
MD5 | `ECE311FF51BD847A3874BFAC85449C6B`
SHA1 | `61B4D8D4757E15259E1E92C8236F37237B5380D1`
SHA256 | `C7B9591EB4DD78286615401C138C7C1A89F0E358CAAE1786DE2C3B08E904FFDC`
SHA384 | `EFB43B763BC7F7E42D0EC01FBF1458913A38FE08F120A17E70B70E353B7BF33613AEB70564817BC0582FCE5F1784547E`
SHA512 | `8334FCD3E551FCAF21FE2AA88218A411A7C6BA8FFB91EB2880F5970BA3AC4893EF214318EB0DA298353C515370A18124FEE9970BED55002CD9145CAFAA181FD8`
SSDEEP | `1536:ew6HOlxhH1IFf9mNm+QfjgU4H+En4x9Xl0B4ki/5co:esk2fAgUq+En43l0BdmP`

## Runtime Data

### Usage (stderr):
```Batchfile
DiskSnapshot: illegal option: --
DiskSnapshot.exe [options]
	-c console output
	-i (deprecated) detail data to console
	-s (deprecated) summary data to console
	-u process large volumes (no limit)
	-j [config] specifies an alternate config file
	-w [output-file] dumps MFT to a file (v arg required) for testing or reparsing
	-r [input-file] parses a previously dumped MFT file
	-v [volume][path] specifies volume(+path) to process, e.g. "d:" or "d:\foo" 
	-d [input-file] print encoded versions of the strings in the input file, for decoding purposes
	-e prints out escalation keywords
	-k calculate checksums for files, used to investigate duplicated on-disk content (c arg required).

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\Administrator\Documents | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\system32\DiskSnapshot.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DiskSnapshot.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.652 (WinBuild.160101.0800)
* Product Version: 10.0.17763.652
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


