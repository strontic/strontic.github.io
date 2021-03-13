---
title: ComparePackage.exe |  
excerpt: What is ComparePackage.exe?
---

# ComparePackage.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ComparePackage.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `3851B4FDACA45C3636F0E4EC916A2ACA`
SHA1 | `5D13FD81746FA50EB04B6E60845B9FC26A4C1E56`
SHA256 | `4F6558FE6BE1AE6A06A8366D7B478BA92791EA7635089D774D1A768AE2E3FAC5`
SHA384 | `D989AC2B2DD8E478744849469EC6203F0DE8DEAF68B47F3020BC4E2CE63DFB169C2C13C05D9E4AA764A8C347E8C56C42`
SHA512 | `30029DE606B395B6B241841EEF1CD919F6F55F75CE0B61246B1F1E3C26D275E075F4065FCE9631BC5B784D57F6B6AFE26199C67D37DAECEA5C51E336BFFACA7A`
SSDEEP | `768:pTF5BzCz6SHsrZEtOUHDrRyXnbT/23VRfN8l2Hg:LCeKsrKtOUj9y//AVRfN8lqg`
PESHA1 | `DFA349D71F56D36E361B21652D04725DEE4F0944`
PE256 | `ACF96E9F3887E0C62CD8EBEC68A0EB1E588E7DEA331E601310ADFDB90B17C523`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ComparePackage Tool
Copyright (C) 2018 Microsoft.  All rights reserved.
Log file is located under: C:\Users\user\AppData\Local\Temp\ComparePackage\Logs_1\Log.txt

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
Path error: help not found
Check the paths in your arguments. We couldn't find the files at the paths specified.
Error: The argument <original package path> should be a valid file.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ComparePackage.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\ComparePackage.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/4f6558fe6be1ae6a06a8366d7b478ba92791ea7635089d774d1a768ae2e3fac5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\ComparePackage.exe](ComparePackage.exe-D8816D5E19E91A30AA09CC036ECB1F32.md) | 88




MIT License. Copyright (c) 2020-2021 Strontic.


