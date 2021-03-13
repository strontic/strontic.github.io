---
title: aspnet_regiis.exe | aspnet_regiis.exe
excerpt: What is aspnet_regiis.exe?
---

# aspnet_regiis.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_regiis.exe`
* Description: aspnet_regiis.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `5D1D74198D75640E889F0A577BBF31FC`
SHA1 | `C558F0E842C43E6B3BC066916B2F5D860C317BA5`
SHA256 | `ED99C2402AC2CCC1CA9EBF21F10C12EE27E8D33F1E67BEA3CB34DA9CD0B4B58C`
SHA384 | `39AE29063EEE2E1673BF140BC37AD4F6AE84C3B0CB4802FE51B59648248319F3E4F344352037ADD3539BD041D21DF806`
SHA512 | `6F597153AC153151FF9E3D9F7E8E162F419535A8905592E0F7ADDB52AC12D2836F63073EB4D1F6F5042CF9A9EA94064D014510941E1F93C8D0F4E5C0F87634FB`
SSDEEP | `384:02DVsXz65YGYJjeUtJbZ/6J5DpuQX3xNR3CcYJqbZEQ3RmS3InWQVWATGpsfQpBR:0Ek6M1/WPRNR34IbwjJ7qWk84`
IMP | `0A40E9198D08B42CB0340923EF895D29`
PESHA1 | `ED447374F8AA7ADDA77CB9F264434CA668A590CE`
PE256 | `431A8E4BC0F91A76017757C665C24E9136E484A69DC22CC07975C325819D4258`

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
C:\Windows\Microsoft.NET\Framework\v4.0.30319\aspnet_regiis.exe |
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

* Original Filename: aspnet_regiis.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/ed99c2402ac2ccc1ca9ebf21f10c12ee27e8d33f1e67bea3cb34da9cd0b4b58c/detection





MIT License. Copyright (c) 2020-2021 Strontic.


