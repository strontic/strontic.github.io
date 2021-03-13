---
title: Wex.Services.exe | Wex.Services [v10.43k]
excerpt: What is Wex.Services.exe?
---

# Wex.Services.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\x64\Wex.Services.exe`
* Description: Wex.Services [v10.43k]

## Hashes

Type | Hash
-- | --
MD5 | `03B28C029FA5895D2391B4308CAB54FE`
SHA1 | `6647094E3C6DBF71C9D3DE471D8C7A36A0AB1D28`
SHA256 | `AB50B0EEB9B42DD6D3785C05829F3D84DA589C48E3E8F969DF17D3C6ACB067CF`
SHA384 | `B724BB0D36184F638E879E2B61EFEA5B245E546A761DC58D9BFA04CADF704F9912F2A20C5B80003FCCED1CF9505D0EA0`
SHA512 | `ED21AA62D25AD835B5A07E98E6CBD605A997315CE0C8C282B59C06393AAC09CE87FEAF1903A6A6BE7B523F606C0B21DBE8E4C12B002E32253093C986947BA72B`
SSDEEP | `3072:fxazRnvaontvdlC/AngmWU4AsQ/6+xBD5BSpzqWZAxQNJ1vl/xOAYgIrQBZVhB:fUdnvHvdlCIn8U4e99OcqAUl/8rQBZvB`
IMP | `A95834891C8CA2E5398E162B8C6AAE96`
PESHA1 | `4DA4C4B0CDF22BE03CFE5E7B9953A923791A5C7B`
PE256 | `33D943245940BBC92F9C2178FFC0BC99C1DA6C7A325FABAE9050375BE4398182`

## Runtime Data

### Usage (stdout):
```cmhg

[Wex.Services.exe] Runs, installs, or removes Test Authoring and Execution Framework services

Usage: Wex.Services [/install:<service name>
                  [/remove:<service name>]
                  [/run:<service name>]
                  [/list]
                  [/?]
                  [/help]

                             Service installation or removal requires running 
                             Wex.Services.exe from an elevated command prompt.

    /install:<name>          Specify a service name name to install                             

    /remove:<name>           Specify a service name name to remove

    /run:<name>              Runs the specified service in the context of the current user

    /list                    Lists the names and descriptions of all available services
                             
    /? or /help              Prints this help message
 
Examples:

    Wex.Services.exe /install:Te.Service

        Interpretation: "Install 'Te.Service' service"

    Wex.Services.exe /remove:Te.Service

        Interpretation: "Remove 'Te.Service' service"



```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\x64\Wex.Services.exe |
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

* Original Filename: Wex.Services.exe
* Product Name: Test Authoring and Execution Framework
* Company Name: Microsoft Corporation
* File Version: 10.43.1909.04003
* Product Version: 10.43.190904003-develop
* Language: English (United States)
* Legal Copyright: Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Testing\Runtimes\TAEF\x64\MinTe\Wex.Services.exe](Wex.Services.exe-03B28C029FA5895D2391B4308CAB54FE.md) | 100




MIT License. Copyright (c) 2020-2021 Strontic.


