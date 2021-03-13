---
title: mofcomp.exe | The Managed Object Format (MOF) Compiler 
excerpt: What is mofcomp.exe?
---

# mofcomp.exe 

* File Path: `C:\Windows\SysWOW64\wbem\mofcomp.exe`
* Description: The Managed Object Format (MOF) Compiler 

## Hashes

Type | Hash
-- | --
MD5 | `33DCECD8F1424636308C3244A31BAF02`
SHA1 | `5997AD70F87A6B161EDDC07ABF2B8229E4ACD579`
SHA256 | `FF02023BD6AC4E65644FFC1D300D45544B047CAB7A96E33F63EDAA16A24E067D`
SHA384 | `9587344F5BB48C9AE4A47C99B9413DE42D4F9A5B14DAC9CF6A7DDCB39ACD72867EA43C61FA78B2F73D521F14EFC62D28`
SHA512 | `70C71BAD76C3BF669801E461F7FA8064096F68E69B35B201BF57B7240A5A85433F36A733E36C96244522CDC09AE159AF828299DA85FFA3C8CF5053F0C4155E42`
SSDEEP | `384:fwL8GsKmxnkWP8CMfpyZ4/5y9/QBh8pbBuyb/YE9pukKy2dd1oahu/VqWyoWRk:YPlUejvEV7BuFdd1oac/V2E`
IMP | `ACD3E0F2D0B3D1E0EF9E8B2AB96C581C`
PESHA1 | `1E53B1E4100D4A8044C1F7E113BB31F1333C9847`
PE256 | `40690268B71C7D040880BFD1DC8E06C4355DD4C5B8136F049AE17CC23695FEB7`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) MOF Compiler Version 10.0.19041.1
Copyright (c) Microsoft Corp. 1997-2006. All rights reserved.

usage: mofcomp [-check] [-N:<Path>]
               [-class:updateonly|-class:createonly]
               [-instance:updateonly|-instance:createonly]
               [-B:<filename>] [-P:<Password>] [-U:<UserName>]
               [-A:<Authority>] [-WMI] [-AUTORECOVER]
               [-MOF:<path>] [-MFL:<path>] [-AMENDMENT:<Locale>]
               [-ER:<ResourceName>] [-L:<ResourceLocale>] 
               <MOF filename>

   -check                    Syntax check only
   -N:<path>                 Load into this namespace by default
   -class:updateonly         Do not create new classes
   -class:safeupdate         Update unless conflicts exist
   -class:forceupdate        Update resolving conflicts if possible
   -class:createonly         Do not change existing classes
   -instance:updateonly      Do not create new instances
   -instance:createonly      Do not change existing instances
   -U:<UserName>             User Name
   -P:<Password>             Login password
   -A:<Authority>            Example: NTLMDOMAIN:Domain
   -B:<destination filename> Creates a binary MOF file, does not add to DB
   -WMI                      Do Windows Driver Model (WDM) checks, requires -B switch
   -AUTORECOVER              Adds MOF to list of files compiled during DB recovery
   -Amendment:<LOCALE>       splits MOF into language neutral and specific versions
                             where locale is of the form "MS_4??"
   -MOF:<path>               name of the language neutral output
   -MFL:<path>               name of the language specific output
   -ER:<ResourceName>        extracts binary mof from named resource
   -L:<ResourceLocale>       optional specific locale number when using -ER switch

   Example c:>mofcomp -N:root\default yourmof.mof

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\wbem\mofcomp.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mofcomp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/ff02023bd6ac4e65644ffc1d300d45544b047cab7a96e33f63edaa16a24e067d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wbem\mofcomp.exe](mofcomp.exe-8D852A615EDD9C72014427BC969CA237.md) | 94




MIT License. Copyright (c) 2020-2021 Strontic.


