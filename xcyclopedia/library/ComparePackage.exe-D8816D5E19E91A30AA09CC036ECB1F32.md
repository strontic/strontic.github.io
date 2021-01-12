---
title: ComparePackage.exe |  
excerpt: What is ComparePackage.exe?
---

# ComparePackage.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ComparePackage.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `D8816D5E19E91A30AA09CC036ECB1F32`
SHA1 | `50B971B2742CBBF13A753B041D4314B826FE25C8`
SHA256 | `A54360F1AD4414D343365FCC029944C3D8C9A7BD45D7A7BFD6DFF1EF6E31ADCA`
SHA384 | `9C3909AF8E26F2E2333EEF2CD62C2C753663A18A2E1C44675A9DDD40562576B39D3FE97037EA5A64A72270B090C07562`
SHA512 | `3492709243E86051B0E28DC0D1AE175EC0FBB9CC817B88B79878360A84546CC7E387509664641E26C5D399FDB0D30D1CAFB50D8501B346AD9684B0D14D0229FC`
SSDEEP | `768:FTF5BzCz6ArZEtOUHDrRyXnbT/23VRfNHl2Ag:fCeArKtOUj9y//AVRfNHlxg`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `1D0B395820C635DED9AFA61757E7288A77BB0684`
PE256 | `9F2C7ADC1F97EB1D5CB0BC06ABD072D89E56D8C4AD09B8C5BAC24A059F48E9E3`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ComparePackage Tool
Copyright (C) 2018 Microsoft.  All rights reserved.
Log file is located under: C:\Users\user\AppData\Local\Temp\ComparePackage\Logs_10\Log.txt

Compare Package started!
Version 10.0.0.0

Compare Package started!
ComparePackage analyzes the differences between two versions of your package and helps you understand how the changes can impact users' updates.

Usage: ComparePackage.exe [arguments] [options]

Arguments:
  <original package path>  File system path to the original package or the original package's blockmap for comparison
  <new package path>       File system path to the new package or the original package's blockmap for comparison

Options:
  -h        Shown the usage
  -version  Show the tool's version
  -v        Enables verbose output to the console
  -o        Overrides output XML if exists
  -XML      Saves XML version of the output to the path specified in addition to the console output

Examples:
ComparePackage <original package path> <new package path> [-XML <XML path>] [-o] [-v]
ComparePackage mypackage_1.04_x64.msix mypackage_1.05_x64.msix -XML "C:\diffoutputs\mypackage_1.04_1.05_diff.xml"
ComparePackage mypackage_1.04_x64.appx mypackage_1.05_x64.appx -XML "C:\diffoutputs\mypackage_1.04_1.05_diff.xml"

Supported input types:
    .appx/.msix
    .appxbundle/.msixbundle
    .appxbundle/.msixbundle to .appxbundle/.msixbundle
    .eappx/.emsix to .eappx/.emsix
    .eappxbundle/.emsixbundle to .eappxbundle/.emsixbundle
    .xml to .xml (blockmaps only comparison)
    *Only packages encrypted with the test key /kt option in MakeAppx.exe are supported.
Definitions:
    Impact
    - The amount that a particular file impacts the users' update in bytes
    Net Update Impact Size
    - The sum of impact of all changed and added files, can be used to approximate users' update download size as a result of the new version
    Size Difference
    - Difference in file size in bytes between new and original version
    Size
    - File size in bytes of added or deleted files
    Duplicate Files
    - File sets that are exactly the same in the new package(does not consider original package)


```

### Usage (stderr):
```cmhg
Path error: /? not found
Check the paths in your arguments. We couldn't find the files at the paths specified.
Error: The argument <original package path> should be a valid file.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ComparePackage.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ComparePackage.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: ComparePackage.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/a54360f1ad4414d343365fcc029944c3d8c9a7bd45d7a7bfd6dff1ef6e31adca/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ComparePackage.exe](ComparePackage.exe-3851B4FDACA45C3636F0E4EC916A2ACA.md) | 88




MIT License. Copyright (c) 2020 Strontic.


