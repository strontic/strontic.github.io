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
MD5 | `18132416C71D1B3A225D5BCC7F686381`
SHA1 | `7BE07A001105BC39FB4C6828B9F50AEFADCCA476`
SHA256 | `6B74BB2BFE0CDA5617EAC3A3EEFCCC9554186B098DC70DA573B153AF36525569`
SHA384 | `DBA56541E2900942BFA78BBDEAC7944BA359B3A2C76C6FE605B4F219E9043F7B348047C5806C8F9C4CDA3C944F5980B0`
SHA512 | `40BE189B8971BB968F013AD2CC769B4D14D966BB4F0C5F163E14048AA363ED5AD964E14596C5EAB1AC1C6355A0FC720F086D253156B45EBBBB5D55AAD560DA82`
SSDEEP | `384:Vt/0delwgfKrQwK79+14CkELZta4L+fyvoahl/liW1oWn1tV:VtMdcB5XfyvoaH/lxB1`
IMP | `3B603DD27AB650AF3F5B7F82AE17797D`
PESHA1 | `F73F240758D2FDBD85A2C986559F4BD0FEADBDCE`
PE256 | `DA0D740311A8C64B8C7BE8743707DAEA640894FD410DACF3894EABF9655A2278`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) MOF Compiler Version 10.0.17763.1
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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/6b74bb2bfe0cda5617eac3a3eefccc9554186b098dc70da573b153af36525569/detection/





MIT License. Copyright (c) 2020 Strontic.


