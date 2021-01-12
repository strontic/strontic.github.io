---
title: plmdebug.exe | Microsoft PLMDebug
excerpt: What is plmdebug.exe?
---

# plmdebug.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\plmdebug.exe`
* Description: Microsoft PLMDebug

## Hashes

Type | Hash
-- | --
MD5 | `71BDC992A05A47245D6C7B70DD13476C`
SHA1 | `2B5325047C61FC84EC35B21CE3F159016E47A09E`
SHA256 | `114B63624E7B8BACCBCFA73295BBFBEA8613BC95DCC9FF1A3E2D0DE87C044B62`
SHA384 | `4C3E7D9CA47D585B5B16FFF96DDF9AF421AF79D63762CB9080490556C43E3376A4F6585CD17C670D76CFFB7F7249C5E0`
SHA512 | `5A8B5F11A9C10B845EA6E35638FAD5B07005059BEC03F6920A546A673D78B71700CA4BB28A3F64895DF85F10D56772356E6EDB7F35299F7E36E3C24BA99E6701`
SSDEEP | `3072:irntWIUgTjM60EtNUSdsBYa52vXOKeN72ee+44xfUom4gQ:Kh0M5hi8eKYxfUomt`
IMP | `2D9614E9DF4F5F1A07E899F19700EBD9`
PESHA1 | `E8F70690E17FBB4CD723A3A4FDB4E669317BB25B`
PE256 | `299BE82A836CAAF8D4092B290F34D8D6F7142E6A93BA95877E3274F423F88011`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\plmdebug.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/114b63624e7b8baccbcfa73295bbfbea8613bc95dcc9ff1a3e2d0de87c044b62/detection





MIT License. Copyright (c) 2020 Strontic.


