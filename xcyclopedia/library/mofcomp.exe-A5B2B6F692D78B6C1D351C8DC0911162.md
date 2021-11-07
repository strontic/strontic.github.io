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
MD5 | `A5B2B6F692D78B6C1D351C8DC0911162`
SHA1 | `926D366CB5E9F6F15F3E71581ABD891CF2F18C3D`
SHA256 | `6E589D7D741587143526C36A5CAD5791031D3C52D9E7E0DBFC39CD5C207F7B2F`
SHA384 | `A6A3CDF8041C31F02D9C93743D6B7E6CC1932B4AB566A6F7B5E22C95F37A338E24F754E4BA056CDDB6C68A0366013DA3`
SHA512 | `16A98F7AACDE453C636AE458CDE270C79CC273B377C14E27A51A1DD372AF1B72E38FE147C17A23E181E45ABCD253355C5E95D9321A156CBF42B48E1DD8170ED7`
SSDEEP | `768:70C+hz3bD5Y3fKWIdqjl061T4i1oa4/TRNVO:AC+DgfKWH+Hi2a4/TRbO`
IMP | `9A6A5E4D269C5D18366CA5BF7D1981EB`
PESHA1 | `5BFA518CD798110AB52CE65A152257EF0AE2A1F8`
PE256 | `7FD13FFD9E586A243862BA0F7AF36FE02866C44BEA646B8FBBF46BAE75CD831A`

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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/6e589d7d741587143526c36a5cad5791031d3c52d9e7e0dbfc39cd5c207f7b2f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\wbem\mofcomp.exe](mofcomp.exe-E09EEB349A313277FABBC4204360D005.md) | 88




MIT License. Copyright (c) 2020-2021 Strontic.


