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
MD5 | `91FCBB7A7FC4DC1EE2CE72730071904E`
SHA1 | `A5D380C5A50C5C52902D3389293A519E592B1E17`
SHA256 | `130DC78122599E4593A464BE53BD2A9F6A6F2CC3D7D92A43B94CFDED69184381`
SHA384 | `7125F79AB679C55AD5E7BF34C1708D7E04415FFBA3ACB54B326F4560AB97F16C932F0C61A4391C138CB21679314DB913`
SHA512 | `B87D74A52A718BFA92EE7B64FF3D643FC26A46297EFE799754CDD8FDD5303B92CED37237E64F64D129AC21B3AF78DEB85F5B386E8C964E7C0AEE043B18CE443B`
SSDEEP | `384:flL8GsKmxK6P8CMfpyZ4/5y9/QBh8pbBuyb/YE9pukKy2dd1oahD/VWWmoWPk:dPlUYjvEV7BuFdd1oah/VOy`
IMP | `ACD3E0F2D0B3D1E0EF9E8B2AB96C581C`
PESHA1 | `94DC83FC015A8CCD300E7271BE54E9A0B2BB5BC0`
PE256 | `DE03E58D19DC8BE2E4F01A140F28BA852446705A7931B0F93F7F0973E8237EA8`

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
* Serial: `33000002EC6579AD1E670890130000000002EC`
* Thumbprint: `F7C2F2C96A328C13CDA8CDB57B715BDEA2CBD1D9`
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

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/130dc78122599e4593a464be53bd2a9f6a6f2cc3d7d92a43b94cfded69184381/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wbem\mofcomp.exe](mofcomp.exe-33DCECD8F1424636308C3244A31BAF02.md) | 90
[C:\Windows\SysWOW64\wbem\mofcomp.exe](mofcomp.exe-8D852A615EDD9C72014427BC969CA237.md) | 90




MIT License. Copyright (c) 2020-2021 Strontic.


