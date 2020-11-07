---
title: mofcomp.exe | The Managed Object Format (MOF) Compiler 
excerpt: What is mofcomp.exe?
---

# mofcomp.exe 

* File Path: `C:\Windows\system32\wbem\mofcomp.exe`
* Description: The Managed Object Format (MOF) Compiler 

## Hashes

Type | Hash
-- | --
MD5 | `E09EEB349A313277FABBC4204360D005`
SHA1 | `8A34E39B4969D6F593CBECD662A7A77E9E87A798`
SHA256 | `C6997C7079F983FAC9A928FA87CA9824CF7BEF3979735AC5C1F690EBDCEBA770`
SHA384 | `77B5F69AECA4AB899E37C39FB68A81866EB6B5D9BEBEEA4183B592832866C4BBCFEE5C33F1FCDE221C333642E5740F52`
SHA512 | `AE8E40B4C9E8AE396C40F92E8E50EEFA74D5457164835079AE2EFBA62B05D4F5606040DE107C1F82FF56DDAC5A0ECCC186F93BB5E79E83AF0DF2EFFED4B65AD5`
SSDEEP | `768:M0C+hz3bD5Y3fKWIdqjl0cT4i1oa9/TRNV2:vC+DgfKWH+bi2a9/TRb2`
IMP | `9A6A5E4D269C5D18366CA5BF7D1981EB`
PESHA1 | `AA642E5C8658003C052A272244A6B4B8E9A08F01`
PE256 | `DE9BED5DB33CADAC09554BAA387E586A72A82A4AF2F92D511B0FEFB5525FD9AD`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\wbem\mofcomp.exe |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/c6997c7079f983fac9a928fa87ca9824cf7bef3979735ac5c1f690ebdceba770/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\mofcomp.exe](mofcomp.exe-96AA37E4CF7382B9E939A2F57F4A5C1F.md) | 55




MIT License. Copyright (c) 2020 Strontic.


