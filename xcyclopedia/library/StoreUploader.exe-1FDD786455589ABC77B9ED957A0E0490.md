---
title: StoreUploader.exe |  
excerpt: What is StoreUploader.exe?
---

# StoreUploader.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\StoreUploader.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `1FDD786455589ABC77B9ED957A0E0490`
SHA1 | `590C4FC371399683FE58AB69AFB61444347F0FAF`
SHA256 | `3D6205A3A7ED3DC6C5BB7B3CE7BCFE579632BFD2694E8E16064123FF06DC61AF`
SHA384 | `C1707631B687EA0EBC572E282E9A2D9D8268392FCB317ACB32E1D32BB9D1421B2910D2CA8A7ABA5D5C5CB17DFF78C870`
SHA512 | `678BD66FA7F55AC2B6FD53C79E0406761DD585F1E0DBF9124F1ADA66FA57C7D244DEFC37DFEC08F53FC0DE13B60A064A0EEAFA4CCA66EBA4B42A38C540CF0A82`
SSDEEP | `384:CdSyoWQcYcl3h0iAJUkwEADVTc2yOWPUWf:Cg1ml3WKBTYx`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `D1686DCD6F455AB098E3058E042AEAB40CF7CF26`
PE256 | `955B2B4A0C00A59C4711F79A9935CBE318A83D895079E4F1E4AF5EB8889BC9D7`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\StoreUploader.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\StoreUploader.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/3d6205a3a7ed3dc6c5bb7b3ce7bcfe579632bfd2694e8e16064123ff06dc61af/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\StoreUploader.exe](StoreUploader.exe-E40460FB29D0454B06C959EE030289E2.md) | 90




MIT License. Copyright (c) 2020 Strontic.


