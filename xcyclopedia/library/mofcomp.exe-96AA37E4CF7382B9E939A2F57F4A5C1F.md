---
title: mofcomp.exe | The Managed Object Format (MOF) Compiler 
---

# mofcomp.exe 

* File Path: `C:\Windows\system32\wbem\mofcomp.exe`
* Description: The Managed Object Format (MOF) Compiler 
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `96AA37E4CF7382B9E939A2F57F4A5C1F`
SHA1 | `9588EEF1C46149C38E5A706CB504677A5E1C2040`
SHA256 | `F70F849225F5DAFE5890AD8308CB6B136385FA84DBE148805FB9A63DC91F70F4`
SHA384 | `5C777EE5FBB8DD8828E7257E374C411691CD7C71BBF32DADA2B7F39567E9ED35CECB03AD7BE40C41646D31499CC9A2EA`
SHA512 | `5CBF23A732BA043A34B705A94F4A9DDD6E0258325DF295E69BD0D43E6BDE016FDAFD1CE866CC409E25448E5689E669AD946860B15215CB471B257342F3B3916C`
SSDEEP | `384:deSbrAKT+hD3ooueJ61KifPxgp3sZoFt4SvgZEyo6z4Ctl2RMiUKV4i1oah7/WeY:UEj+hD3LE5Y3PaWlql0T4i1oa9/WEOm`

## Runtime Data

### Usage (stdout):
```Batchfile
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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


