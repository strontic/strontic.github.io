---
title: aspnet_regiis.exe | aspnet_regiis.exe
excerpt: What is aspnet_regiis.exe?
---

# aspnet_regiis.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_regiis.exe`
* Description: aspnet_regiis.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `06138ABFF3EEE34172D46C49BFD48978`
SHA1 | `A91AC3BF8967B40A5DC128DEC75AC269661FA725`
SHA256 | `038F55A19B3EB3B4B5C6433B96F2E0BC1BDA40B071820F16AC3B5C74C56E308D`
SHA384 | `A677FAB1CFE3AF0AF7F0DC30214DF6B90CC5B2A916AA7BE8A297C48AA1EB5D47621C433C936FBC3019389AB67DCA08F6`
SHA512 | `277E0C8B6468AAFC052F582ACA0A8E7920A1656ACA14014C0835A46AEAEF46A2127BE35027F9DB763D84AC9F5F14F758AD63F477F16965CA9695CD5BCA9AA60F`
SSDEEP | `768:SzlGxPcOQomCr1rNDuKiA1d2qWwK8t6TXEJq:89grFuKt1Cwnt6V`
IMP | `6D868D8CB1EC5BC1E6BE42EF04B1146C`
PESHA1 | `D384C748B3846FDDC95B6E4784934705A7CB7C20`
PE256 | `5877C4905776E01863A9B4A60FE73800F70494F3B47264D6CF936E9BCD23B5DA`

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
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_regiis.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/038f55a19b3eb3b4b5c6433b96f2e0bc1bda40b071820f16ac3b5c74c56e308d/detection





MIT License. Copyright (c) 2020 Strontic.


