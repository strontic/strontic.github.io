---
title: plmdebug.exe | Microsoft PLMDebug
excerpt: What is plmdebug.exe?
---

# plmdebug.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\plmdebug.exe`
* Description: Microsoft PLMDebug

## Hashes

Type | Hash
-- | --
MD5 | `922A5881058A7DAA6D956E819647A1D9`
SHA1 | `F3A73FA7D8C3360884B2A7FC67011AD7379BB4F0`
SHA256 | `37B375473839139DFB7291DEF96368C56979F7CEFE66971EC6ECDF439E2D05C2`
SHA384 | `E5705872F17181E09C28C3E6DBB029914DF4D87CC4654125EBC3665BB630FD6DE8B0777B0D2F16AE26B199AD964D745B`
SHA512 | `6F022685DABB9C280D8E9F12438DDDB6D9E8F85A337B095E6590305069CE94CC102169CC1A6990EC17248C74A35892E1086763B29930454B105E7A73F41C9DEC`
SSDEEP | `3072:/drXR16LPEO/IudqcSvP03MtB8RXjoN5Nqh+UaS1jw2fkWwSY:wLX/NdqFvc3MKjoN5Nqh+UH1E2fTxY`
IMP | `42C899D013217E2C12090934DFA2E285`
PESHA1 | `370B20683F614073D023644934EBC15AE56CE220`
PE256 | `CD97FD24A19F354F4D7D86B67C3576EE4AA3EC3D5D6F7ABB25D69DBE11251036`

## Runtime Data

### Usage (stdout):
```cmhg
plmdebug.exe /query [pkgname]
plmdebug.exe /enableDebug pkgname ["debugger"] ["environment str1" ...]
plmdebug.exe /terminate|/forceterminate|/cleanterminate pkgname
plmdebug.exe /suspend|/resume|/disableDebug pkgname
plmdebug.exe /enumerateBgTasks pkgname
plmdebug.exe /activateBgTask taskid

    pkgname can be package full name or a process ID for one of the processes running for the package.

/query: List running states for all installed packages or a specified package.
/enableDebug: Call the PLM debug API to increment debug ref count on a package. PLM
Does not suspend a package if it has non zero debug ref count.
    debugger: Optional string to start debugger.
        Eg: "C:\Program Files\Windows Kits\8.0\Debuggers\x64\windbg.exe" -server npipe:pipe=test"
    environment strings: Optional list of environment strings for debug session.
        Eg: "var1=val1" "var2=val2"
/terminate|/forceterminate: Call the PLM debug API to terminate all processes running for the package.
/cleanterminate: Call the PLM debug API to suspend and then terminate all processes running for the package.
/suspend: Call the PLM debug API to asynchronously suspend all processes running for the package.
/resume: Call the PLM debug API to resume a package.
/disableDebug: Call the PLM debug API to decrement debug ref count on a package.
/enumerateBgTasks: Enumerate background task ids for a package
/activateBgTask: Activates a background task
    ** NOTE: Not all background tasks can be activated using plmdebug **

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\plmdebug.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: plmdebug.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


