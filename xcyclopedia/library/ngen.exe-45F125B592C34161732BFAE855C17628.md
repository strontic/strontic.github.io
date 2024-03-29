﻿---
title: ngen.exe | Microsoft Common Language Runtime native compiler
excerpt: What is ngen.exe?
---

# ngen.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngen.exe`
* Description: Microsoft Common Language Runtime native compiler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `45F125B592C34161732BFAE855C17628`
SHA1 | `959EAB169395284F92717E7785CA9C7A2936CC60`
SHA256 | `C555CF03BCBC780F8A39CBF8B95254FD3798A703BA71B84AF84EF33E36D0D761`
SHA384 | `F6F90EC78EEFB9E0B67DD75DF912788D812A3A2E46FF8358F77500F0C438C7771FF7B00AB6F4A300ACAD35B8B844A43B`
SHA512 | `B31E5EAD08F82F70618198DBEA2312822258CA8F58441A02B96F474623F8AEFE16CFF8A4AE75EC53E514283B308FCC8602C623D748B47075F54CCD8DAE41B9E7`
SSDEEP | `3072:OxJajVR3IHq658DCCOHuN4hIdpEGaYjs27MlZ:OnajVj6581jLzTssM3`
IMP | `05EC6CF51708237D25182181F0BEADEE`
PESHA1 | `3452F853658646B494A12FB8A7A2BA9A52BF28E5`
PE256 | `1FBE058D58B06CD5C479CD623B4EDCF2E8D06F3A4EC638CD0D944DFB9FA23277`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) CLR Native Image Generator - Version 4.8.4084.0
Copyright (c) Microsoft Corporation.  All rights reserved.

Error: Unrecognized option --help
WARNING: This syntax is deprecated or you mis-typed your command.  Run "ngen /?" to display a list of the currently supported parameters.

Usage: ngen <action> [args] [/nologo] [/silent] [/verbose]
       ngen /? or /help

    /nologo    - Prevents displaying of logo
    /silent    - Prevents displaying of success messages
    /verbose   - Displays verbose output for debugging

Actions:
    ngen install <assembly name> [scenarios] [config] [/queue[:[1|2|3]]
        Generate native images for an assembly and its dependencies
        and install them in the Native Images Cache
        If /queue is specified compilation job is queued up.  If a priority 
        is not specified, the default priority used is 3.
    ngen uninstall <assembly name> [scenarios] [config]
        Delete the native images of an assembly and its dependencies from
        the Native Images Cache.
    ngen update [/queue]
        Update native images that have become invalid
        If /queue is specified compilation jobs are queued up.
    ngen display [assembly name]
        Display the ngen state
    ngen executeQueuedItems [1|2|3]
        Executes queued compilation jobs.
        If priority is not specified all queued compilation jobs are done.
        If priority is specified compilation jobs with greater or equal
        priority than the specified are done. (Short form: eqi)
    ngen queue [pause|continue|status]
        Allows the user to pause and continue the NGen Service, and to
        query its status.
    ngen createPDB <path to native image> <directory to store PDB>
                    [/lines  [<search path for managed PDB>] ]
        Generates a native PDB file for a native image that was previously
        generated by NGen.  The generated PDB file includes names of methods
        and ranges of IP offsets that map to those methods.
        If /lines is specified, then additional information is written to the
        PDB to map ranges of IP offsets to source file line numbers.  /lines
        requires access to the managed PDB generated by the language compiler.
        <search path for managed PDB> may optionally be specified to help NGen
        find the managed PDB

Scenarios:
    /Debug          - Generate images that can be used under a debugger
    /Profile        - Generate images that can be used under a profiler
    /NoDependencies - Generate the minimal number of native images
                      required by this scenario

Config:
    /ExeConfig:<path to exe> - Use the configuration of the specified
                 executable assembly
    /AppBase:<path to appbase directory> - Use the specified directory as
                 the appbase



```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ngen.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ngen.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/c555cf03bcbc780f8a39cbf8b95254fd3798a703ba71b84af84ef33e36d0d761/detection


## Possible Misuse

*The following table contains possible examples of `ngen.exe` being misused. While `ngen.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"value": "%WINDIR%\\system32\\drivers\\NGEN Framework\\NGEN.exe",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `C:\Windows\system32\drivers\NGEN Framework\NGEN.exe`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [invisimole](https://github.com/eset/malware-ioc/blob/master/invisimole/README.adoc) | `"Application"="C:\Windows\system32\drivers\NGEN Framework\NGEN.exe"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_speedfan_chain.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_speedfan_chain.yml) | `- '\Windows\system32\drivers\NGEN Framework\NGEN.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_speedfan_chain.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_speedfan_chain.yml) | `- '\NGEN.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_speedfan_chain.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_speedfan_chain.yml) | `Details\|endswith: '\drivers\NGEN Framework\NGEN.exe'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


