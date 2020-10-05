---
title: appvcleaner.exe | AppVCleaner
excerpt: What is appvcleaner.exe?
---

# appvcleaner.exe 

* File Path: `C:\Program Files\Common Files\microsoft shared\ClickToRun\appvcleaner.exe`
* Description: AppVCleaner

## Hashes

Type | Hash
-- | --
MD5 | `B8D69FA2755C3AB1F12F8866A8E2A4F7`
SHA1 | `8E3CDFB20E158C2906323BA0094A18C7DD2AAF2D`
SHA256 | `7E0976036431640AE1D9F1C0B52BCEA5DD37EF86CD3F5304DC8A96459D9483CD`
SHA384 | `6645EC6C7EB6C0AABC0029373195D53E85F713C6E859631399A5AF8D7117E5EE8DBC8930E1B2A00F39B334EB91AEF960`
SHA512 | `5ACAC46068B331216978500F67A7FA5257BC5B05133FAB6D88280B670AE4885EF2D5D1F531169B66BF1952E082F56B1AD2BC3901479B740F96C53EA405ADDA18`
SSDEEP | `24576:GCbRquA/m2z+L5WqJdrHCYRFiV+XenmE3Pnzc344:GCbRquA/m2yL5zbfFiV+XenmE3/z`
IMP | `754A865A9EEBB214E7A6F31DBFFC6594`
PESHA1 | `78C710AEB2DCA1C47FC7FE4B2C8F452E40F4C9D8`
PE256 | `9FB39D207B897ECE6E3115D1AC628E545E97B67484AF3586265C526FA0316BCD`

## Runtime Data

### Usage (stdout):
```cmhg
AppVCleaner.exe [/?] [/help] [/M:mode] [/PID:package ID] [/RSP:registy path] [/DD:directory] [/x86MP:file] [/x86DDC:file] [/x64MP:file] [/x64DDC:file] [/ABD:directory] [/PD:directory]

Description:
Use this tool to clean up extension points locally.

Parameters:
? or help: This information
M: Mode (optional). - store: Store based clean up - In this mode, the cleanup will use registry data of App-V.
           This mode requires registry store location (RSP) and file store location (DD).
           It also requires the package ID (PID), which can be explicitly provided, or can be extracted from a manifest if a 
           manifest location is provided.
  - manifest: Manifest-based clean up - In this mode, the cleanup uses package manifest to perform the cleanup.
              This mode requires at least one manifest location to be provided. On a 32-bit system,
              the x86 manifest location (x86MP), on a 64-bit system, either the x86 manifest location (x86MP)
              or the x64ManifestLocation (x64MP) must be provided. If both are provided, then cleanup will use both manifests,
              to ensure clean up succeeds regardless of the bitness of the package that was published.
              Following parameters are mandatory for this mode: x86MP and/or x64MP, ABD, PD
              Following parameters are optional for this mode: x86DDC, x64DDC
  - best (default): Best effort. If a mode (M) is not specified or this mode is specified explictly, this tool will attempt the store-based cleanup
                    if enough arguments are provided to perform the cleanup and the store locations provided do exist on the machine. 
                    If store-based cleanup cannot be accomplished, then manifest-based cleanup is attempted
PID: The GUID of the package to be cleaned up (optional). Registry style GUIDs with or without '{', '}' are accepted
RSP: Registry store path. The stingified key in the registry under which the AppV stores reside (optional). 
     This location can only be be under HKLM and HKLM prefix should not be provided
DD: Data directory. The directory on disk where backup shortcuts reside (optional). Environment variables are supported (e.g. %APPDATA%)
x86MP: The path of the 32-bit package manifest (optional)
x86DDC: The path of the 32-bit dynamic deployment configuration (optional)
x64MP: The path of the 64-bit package manifest (optional). This parameter can only be defined if 64-bit manifest is defined
x64DDC: The path of the 64-bit dynamic deployment configuration (optional). This parameter can only be defined if 64-bit manifest is defined
ABD: AppV Binary directory. The directory on disk where AppV Binaries reside (optional). Environment variables are supported (e.g. %APPDATA%)


```

### Usage (stderr):
```cmhg
Error: One or more of the command line arguments not understood. Please correct and try again. Error code: A9201401-10000003


```

### Loaded Modules:

Path |
-- |
C:\Program Files\Common Files\microsoft shared\ClickToRun\appvcleaner.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AppVCleaner.exe
* Product Name: Microsoft Application Virtualization (App-V)
* Company Name: Microsoft Corporation
* File Version: 5.1.154.0
* Product Version: 5.1.154.0
* Language: English (United States)
* Legal Copyright:  2015 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7e0976036431640ae1d9f1c0b52bcea5dd37ef86cd3f5304dc8a96459d9483cd/detection/





MIT License. Copyright (c) 2020 Strontic.


