---
title: DiskSnapshot.exe | DiskSnapshot.exe
excerpt: What is DiskSnapshot.exe?
---

# DiskSnapshot.exe 

* File Path: `C:\WINDOWS\system32\DiskSnapshot.exe`
* Description: DiskSnapshot.exe

## Hashes

Type | Hash
-- | --
MD5 | `C585DA22A4506764748DEFBA4CF8F9EC`
SHA1 | `C6E02E919427330A0087A70FA43A3CD0046067BE`
SHA256 | `4A60E5EBF54BC9EDF9F78688ACBDFF19CA8C4AFFE29A836F78CA70396BE848F7`
SHA384 | `38175580D45C6AC998DA86D76779BF3A486FF0DE6473B5B6906478FEF7588CCBC20FD45E4D8BB528E2DDCCCE424DE5AF`
SHA512 | `8365478477758FBFD9315B632EA43F3A8C48F6B2E894FF7B1365FD3074E7157D763E974971F47886C6999E69913E96CBF56069471D36E26C414FFA127B32952B`
SSDEEP | `1536:0t1XK6Z5eFG2Wj0bXWkA3u+gnp5xSfZymol31:/6/X7j0jWkA3u+gnp5xUyN31`

## Runtime Data

### Usage (stderr):
```cmhg
DiskSnapshot.exe [options]
	-c write detail data to console
	-i write detail data to console (same as -c)
	-s (deprecated) summary data to console
	-u process large volumes (no limit)
	-j [config] specifies an alternate config file
	-v [volume][path] specifies volume(+path) to process, e.g. "d:" or "d:\foo" 
	-d [input-file] print encoded versions of the strings in the input file, for decoding purposes
	-e prints out escalation keywords
	-k calculate checksums for files, used to investigate duplicated on-disk content (c arg required).
	-o [output-file] write detail data to a file

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DiskSnapshot.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.






MIT License. Copyright (c) 2020 Strontic.


