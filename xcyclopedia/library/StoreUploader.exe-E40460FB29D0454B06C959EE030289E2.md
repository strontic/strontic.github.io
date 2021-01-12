---
title: StoreUploader.exe |  
excerpt: What is StoreUploader.exe?
---

# StoreUploader.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\StoreUploader.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `E40460FB29D0454B06C959EE030289E2`
SHA1 | `7C9FEA76DAA83EF6777A5A620DAE58A9CF35FC54`
SHA256 | `1D8FBB29BB811FA0719A57D2F5EA74780737BCE0C37988A3EBE59E32FE15BDD1`
SHA384 | `D3D226CA4CA6562C7F2AB69CDB7EFE29BF34E0CF8AACE66663B9D73BB2C5EF239EC7B29AB0472264C2C8D47D1EB7559A`
SHA512 | `64344A5BE081D358DF6B5787719A7E170D7B2DBC4A76988FB79BAFE529E1D87A7410CF1CEBE346C250210F466CE9531DAB8011E05FAC983B561DB426CC9FAAFB`
SSDEEP | `384:mdSyoWQcWl3h0iAJUkwEADVTc2y9yWPUWf:mg1jl3WKBT+x`
IMP | `n/a`
PESHA1 | `DD171185495DAE919F826F156976FF26BF4C54A5`
PE256 | `75FFD5666AEE71D643152A768CE689542CE5643AECF32BB28088FB8EB657A2AE`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) StoreUploader Tool
Copyright (C) 2018 Microsoft.  All rights reserved.
Version 10.0.0.0

StoreUploader is a tool to submit packages to the store efficiently.


Usage: StoreUploader.exe [options]

Options:
  -h        Shown the usage
  -version  Show the tool's version
  -i        Runs the tool in interactive mode.
  -cd       Specifies that the tool should attempt to upload the full package if the delta extraction step fails.
  -np       Runs the tool in serial mode (no parallelism).
  -v        Enables verbose output of messages.
  -c        Path to the config file containing Store parameters and information about the packages to upload.
  -td       Directory where MakeAppx.exe, ComparePackage.exe, and PackageEditor.exe reside.
  -l        Directory under which the tool should save the logs.

Examples:
StoreUploader.exe -c <path to config file> [-i] [-cd] [-np] [-td <sdk tools directory>] [-l <output logs directory>] [-v]
StoreUploader.exe -c C:\StoreUploader\UploadJob.config -l C:\StoreUploaderLogs


```

### Usage (stderr):
```cmhg
Unrecognized command or argument 'help'

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\StoreUploader.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\StoreUploader.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: StoreUploader.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1d8fbb29bb811fa0719a57d2f5ea74780737bce0c37988a3ebe59e32fe15bdd1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\StoreUploader.exe](StoreUploader.exe-1FDD786455589ABC77B9ED957A0E0490.md) | 90




MIT License. Copyright (c) 2020 Strontic.


