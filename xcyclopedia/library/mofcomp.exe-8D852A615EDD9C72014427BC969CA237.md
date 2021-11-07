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
MD5 | `8D852A615EDD9C72014427BC969CA237`
SHA1 | `D659C673E4FD43CD204A59CA0E83C16E421FE5AB`
SHA256 | `555B1F567A3AD1D26E6A286D4F0E16A0E30A305BA8D83A225B889047134DDEF5`
SHA384 | `C09801DBF6453C0CDA76C533B9C601561D6FC766C62478C84AF7FDCEF4E4B0A2BC429DCBD6DFADC2B1FBAF4D362B82B3`
SHA512 | `DD41F731A4ABEE21413C5FCAF30CF246AD136F2DA0BC4C79AEC30B471274EB99CCCAE35B1ED7284139AAE11EC91F327CA5937348B2A0CED61B0F373FEACEBE1F`
SSDEEP | `384:fQL8GsKmxnkWP8CMfpyZ4/5y9/QBh8pbBuyb/YE9pukKy2dd1oahu/VSWKoWBk:oPlUejvEV7BuFdd1oac/VmU`
IMP | `ACD3E0F2D0B3D1E0EF9E8B2AB96C581C`
PESHA1 | `9A8ACCBFA09599C2C204B1F7E3DC8A648EF7E0CE`
PE256 | `10A1D1D530B8A8E4F4D4E8279B058CB8C0EF52D8DA1FB49126D47EC852E0F8B0`

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

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/555b1f567a3ad1d26e6a286d4f0e16a0e30a305ba8d83a225b889047134ddef5/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\wbem\mofcomp.exe](mofcomp.exe-33DCECD8F1424636308C3244A31BAF02.md) | 94
[C:\Windows\SysWOW64\wbem\mofcomp.exe](mofcomp.exe-91FCBB7A7FC4DC1EE2CE72730071904E.md) | 90




MIT License. Copyright (c) 2020-2021 Strontic.


