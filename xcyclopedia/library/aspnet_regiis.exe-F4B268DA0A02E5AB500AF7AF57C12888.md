---
title: aspnet_regiis.exe | aspnet_regiis.exe
excerpt: What is aspnet_regiis.exe?
---

# aspnet_regiis.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_regiis.exe`
* Description: aspnet_regiis.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `F4B268DA0A02E5AB500AF7AF57C12888`
SHA1 | `074C556502535C63DF629F1779C0CA59D603C029`
SHA256 | `86B52AE9FCF0E8DD7943DBAB5AE9AD88B11F15401C499B1CB3338E75E0DCE900`
SHA384 | `C5D66B6A6CB19A689F632562B4D23C6AFFC851BAD5C79312729AEB5548315D36D8C52755A7CA9B465E58AF06507D1EDA`
SHA512 | `8364B5EAEAFA7D8F3E78411DBBADA9C1A334526EDCBF090AA562BBDA89FF78D44F81A529A1A0D74DAF174139DFEF8CAD939EC27AFFB8EAA89A9C27F152D749F7`
SSDEEP | `384:+DVsXz65YGYJjeUtJbZ/6J5DpuQX3xNR3CcYJqbZEQ3RmS3InWuVWGT+s6v3c+pi:Mk6M1/WPRNR34IbwxLwW9gO`
IMP | `0A40E9198D08B42CB0340923EF895D29`
PESHA1 | `C08872B47E002C7C01D20E9E54DCD762E876FD4F`
PE256 | `BB873C00AEE8F51D863DFAC5789F5A0E9A9BAC04FD08BBB6A3914C6F650BF2F6`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ASP.NET RegIIS version 4.0.30319.0
Administration utility to install and uninstall ASP.NET on the local machine.
Copyright (C) Microsoft Corporation.  All rights reserved.


                       -- ASP.NET REGISTRATION OPTIONS --

-i                  Install this version of ASP.NET and update IIS
                    configuration at the root level to use this version of
                    ASP.Net.

-ir                 Install this version of ASP.NET, register only. Do not
                    change any web applications to use this version.

-iru                Install this version of ASP.NET. If there are any existing
                    applications that uses ASP.NET, it will not change IIS
                    configuration to use this version.

-enable             When -enable is specified with -i, -ir or -r, ASP.NET will
                    be enabled in the IIS security console (IIS 6.0 or later).

-disable            When -disable is specified with -i, -ir or -r, ASP.NET will
                    be disabled in the IIS security console (IIS 6.0 or later).

-s <path>           Install scriptmaps for this version at the specified path,
                    recursively.
                    E.g. aspnet_regiis.exe -s W3SVC/1/ROOT/SampleApp1

-sn <path>          Install scriptmaps for this version at the specified path,
                    non-recursively.

-r                  Install this version of ASP.NET and update scriptmaps at
                    the IIS metabase root and for all scriptmaps below the
                    root. Existing scriptmaps are upgraded to this version
                    regardless of the original versions.

-u                  Uninstall this version of ASP.NET. Existing scriptmaps to
                    this version are remapped to highest remaining version of
                    ASP.NET installed on the machine.

-ua                 Uninstall all versions of ASP.NET on the machine.

-k <path>           Remove all scriptmaps to any version of ASP.NET from the
                    specified path, recursively (not supported on Windows Vista
                    and higher versions).
                    E.g. aspnet_regiis.exe -k W3SVC/1/ROOT/SampleApp1

-kn <path>          Remove all scriptmaps to any version ASP.NET from the
                    specified path, non-recursively (not supported on Windows
                    Vista and higher versions).

-lv                 List all versions of ASP.NET that are installed on the
                    machine, with status and installation path.

-lk                 List all the path of all IIS metabase keys where ASP.NET is
                    scriptmapped, together with the version. Keys that inherit
                    ASP.NET scriptmaps from a parent key will not be displayed
                    (not supported on Windows Vista and higher versions).

-c                  Install the client side scripts for this version to the
                    aspnet_client subdirectory of each IIS site directory.

-e                  Remove the client side scripts for this version from the
                    aspnet_client subdirectory of each IIS site directory.

-ea                 Remove the client side scripts for all versions from the
                    aspnet_client subdirectory of each IIS site directory.

-ga <user>          Grant the specified user or group access to the IIS
                    metabase and other directories used by ASP.NET.



                     -- CONFIGURATION ENCRYPTION OPTIONS --

-pe section         Encrypt the configuration section. Optional arguments:
                    [-prov provider] Use this provider to encrypt.
                    [-app virtual-path] Encrypt at this virtual path. Virtual
                    path must begin with a forward slash. If it is '/', then it
                    refers to the root of the site. If -app is not specified,
                    the root web.config will be encrypted.
                    [-site site-name-or-ID] The site of the virtual path
                    specified in -app. If not specified, the default web site
                    will be used.
                    [-location sub-path] Location sub path.
                    [-pkm] Encrypt/decrypt the machine.config instead of
                    web.config.

-pd section         Decrypt the configuration section. Optional arguments:
                    [-app virtual-path] Decrypt at this virtual path. Virtual
                    path must begin with a forward slash. If it is '/', then it
                    refers to the root of the site. If -app is not specified,
                    the root web.config will be decrypted.
                    [-site site-name-or-ID] The site of the virtual path
                    specified in -app. If not specified, the default web site
                    will be used.
                    [-location sub-path] Location sub path.
                    [-pkm] Encrypt/decrypt the machine.config instead of
                    web.config.

-pef section web-app-physical-dir
                    Encrypt the configuration section. Optional arguments:
                    [-prov provider] Use this provider to encrypt.

-pdf section web-app-physical-dir
                    Decrypt the configuration section.

-pc container       Create an RSA keypair in ContainerName. Optional arguments:
                    [-size key-size] Key-size. Default is 1024.
                    [-pku] User container instead of machine container.
                    [-exp] Make the private keys exportable.
                    [-csp provider] Csp Provider to use.

-pz container       Delete the ContainerName. Optional arguments:
                    [-pku] User container instead of machine container.

-pi container file  Import an RSA keypair from the Xml file. Optional
                    arguments:
                    [-pku] User container instead of machine container.
                    [-exp] Create exportable keys.
                    [-csp provider] Csp Provider to use.

-px container file  Export an RSA keypair to the Xml file. Optional arguments:
                    [-pku] User container instead of machine container.
                    [-pri] Include private keys.
                    [-csp provider] Csp Provider to use.

-pa container account
                    Add access for the account to the container. Arguments:
                    [-pku] User container instead of machine container.
                    [-csp provider] Csp Provider to use.
                    [-full] Add full access (default is Read access).

-pr container account
                    Remove access for the account from the container.
                    Arguments:
                    [-pku] User container instead of machine container.
                    [-csp provider] Csp Provider to use.



                   -- CONFIGURATION REMOTE ACCESS OPTIONS --

-config+            Enable remote access of configuration.

-config-            Disable remote access of configuration.


```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\aspnet_regiis.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: aspnet_regiis.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/86b52ae9fcf0e8dd7943dbab5ae9ad88b11f15401c499b1cb3338e75e0dce900/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_regiis.exe](aspnet_regiis.exe-5D1D74198D75640E889F0A577BBF31FC.md) | 85




MIT License. Copyright (c) 2020-2021 Strontic.


