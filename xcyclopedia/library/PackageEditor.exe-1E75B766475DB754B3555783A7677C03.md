---
title: PackageEditor.exe |  
excerpt: What is PackageEditor.exe?
---

# PackageEditor.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\PackageEditor.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `1E75B766475DB754B3555783A7677C03`
SHA1 | `C044DEDA31963AB4E158F350F1BCA69DA37C5C93`
SHA256 | `ED466077A085490970841F1C982664F6E1B75EE1F21338A045A4983C8F6E22AE`
SHA384 | `30F88CB226A7FBBA7B2DFD83AC792C674E107E6429F200D0BE6D2BC57307F5190D33C2285B1071D0A46C5836DB56C228`
SHA512 | `54788269D8AC9BA61BE5ECA84CF681F67E793EB52CC95E0EEDFC8D89A16B98EE1FB104E2A943D606A00445B5DAEDD54DC5C2BBBFB6BC862CFE0A1836455099CB`
SSDEEP | `384:sO8n8mWa19kkrF8Q5SAH26xN6yAdYQKF0/dLCl+jRzgRCWHsWD:sdGl0FhjzQj/dLClym1`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `021F4D7EC490C035FF62BC17130DC587C4162635`
PE256 | `82E9C005B49B4E0EE1C1EBD4D415F642A11E028B1815F6CC46D7D0D1D2A7FFB3`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) PackageEditor Tool
Copyright (C) 2018 Microsoft.  All rights reserved.
Log file is located under: C:\Users\user\AppData\Local\Temp\PackageEditor\Logs_8\Log.txt

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\PackageEditor.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\PackageEditor.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/ed466077a085490970841f1c982664f6e1b75ee1f21338a045a4983c8f6e22ae/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\PackageEditor.exe](PackageEditor.exe-0FF1FE44A592150E689460B7D6A4E9BE.md) | 93




MIT License. Copyright (c) 2020 Strontic.


