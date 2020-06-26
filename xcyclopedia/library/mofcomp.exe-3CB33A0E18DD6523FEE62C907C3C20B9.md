---
title: mofcomp.exe | The Managed Object Format (MOF) Compiler 
---

# mofcomp.exe 

* File Path: `C:\WINDOWS\system32\wbem\mofcomp.exe`
* Description: The Managed Object Format (MOF) Compiler 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3CB33A0E18DD6523FEE62C907C3C20B9`
SHA1 | `F727B5B990BAC20F495E067293643AE681712DAE`
SHA256 | `F74EEC05ED51FEB73FF444F0CC592216F7BAF77CD5414019B755926B54900DA3`
SHA384 | `02775DB24FDDE694E0FD7AAE0DD6686213CA53CD96D6280261D37DFC9A416E29DC0A4BA73A9901CC6ED5CC743CD1310C`
SHA512 | `7F54DEF044013138A76AD7850F73533B8CBF4D7F4233D3371D9685C2E2D88FF05E97408BB480B2A57045F28F2831511E2A33F231EF8B5203BA662981A65F53BA`
SSDEEP | `768:QopcFf/9FROtGRy0H3hW2Nl0U4NvoaW/r+L:RcPOt0yU+dNgaW/r+L`

## Runtime Data

### Usage (stdout):
```Batchfile
Microsoft (R) MOF Compiler Version 10.0.18362.1
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

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mofcomp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


