---
title: PackageEditor.exe |  
excerpt: What is PackageEditor.exe?
---

# PackageEditor.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\PackageEditor.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `0FF1FE44A592150E689460B7D6A4E9BE`
SHA1 | `DA1470BA906262CF1818EDD02FCEC0DD007E46FE`
SHA256 | `36E83BA30DF4D43E6BAA73DBF2728349662CB40C7E7BB4A104C32C6677D3A967`
SHA384 | `E4D2864FF3E913A65C620399FFF396E48A2EED868E5A7FDC5C2AA43A071EA72B4A4D8C270CDE5B4993A65DE20DF85BFB`
SHA512 | `4F0D577805E2212C90D0F79DB84209B897E4BF33D306483A3DF9966EBFF69B9BB506D94FE8F1758E85384F6BD216EAAC4E94962C8600730EAA98C32A2B4C782B`
SSDEEP | `384:QO8n8mWa19kkrF8Q5jAH26xN6yAdYQKF0/dLCl+jRdgRFWHsWD:QdGl0FhUzQj/dLClyd1`
IMP | `n/a`
PESHA1 | `454DA625EF606218A8ACBF3E5729873ED776674C`
PE256 | `18287FFC7EEE1B376D69CBDD9B530D7A0C5151442F7535A33755A563E22EAD52`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) PackageEditor Tool
Copyright (C) 2018 Microsoft.  All rights reserved.
Log file is located under: C:\Users\user\AppData\Local\Temp\PackageEditor\Logs_2\Log.txt

Version 10.0.0.0

PackageEditor

Usage: PackageEditor.exe [options] [command]

Options:
  -h|-?     For help with a specific command.
  -version  Show the tool's version

Commands:
  createDelta      -- Create a delta package from two package versions.
Usage: 
    PackageEditor createDelta -bp <baseline package> -up <updated package> -dp <delta package>
    PackageEditor createDelta -bb <baseline blockmap file> -bn <baseline package full name> -up <updated package> -dp <delta package>

  update           -- Update a baseline package with a delta package.
Usage: 
    PackageEditor update -appendDelta -bp <baseline package> -dp <delta package>

  updateEncrypted  -- Update an encrypted baseline package with an updated package.
Usage:
    PackageEditor updateEncrypted -appendDelta -bep <baseline package> -dap <delta appended package>

  updateManifest   -- Update the manifest within a package
Usage:
    PackageEditor updateManifest -p <unencrypted package> -m <updated manifest>
    PackageEditor updateManifest -ep <encrypted package> -m <updated manifest>


Examples:
    PackageEditor createDelta -bp <baseline package> -up <updated package> -dp <delta package>
    PackageEditor update -appendDelta -bp <baseline package> -dp <delta package>
    PackageEditor updateEncrypted -appendDelta -bep <baseline package> -dap <delta appended package>
    PackageEditor updateManifest -p <unencrypted package> -m <updated manifest>

Note:
For help with a specific command, provide the -? or -h option, ex.:
    PackageEditor.exe createDelta -?


```

### Usage (stderr):
```cmhg
Unrecognized command or argument 'help'

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\PackageEditor.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\PackageEditor.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: PackageEditor.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/36e83ba30df4d43e6baa73dbf2728349662cb40c7e7bb4a104c32c6677d3a967/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\PackageEditor.exe](PackageEditor.exe-1E75B766475DB754B3555783A7677C03.md) | 93




MIT License. Copyright (c) 2020 Strontic.


