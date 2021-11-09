---
title: aspnet_regiis.exe | aspnet_regiis.exe
excerpt: What is aspnet_regiis.exe?
---

# aspnet_regiis.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_regiis.exe`
* Description: aspnet_regiis.exe
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D44232C1A1300F973333BF1874B84F65`
SHA1 | `F6A0082C35F4C19FB5DC914F206EA4A457BA642B`
SHA256 | `D0563C49D9E645AE243465F33304A278D966393C4BDB138A7E9565AFE2896124`
SHA384 | `978DF5041960B9FF5C18A48470F75CB8384EAA2E1D0D95A012C94637FFADA6783EB809D08A2711DE4D67056F37B7BE12`
SHA512 | `F1E3B0791C5405859665B812CE963E9F0CF4D6440E62A907B2ABD7E2FBE6416CA782FF40D56E696A68E7A28B7B154E11548AAF0E75209429499395C7A4B94CF7`
SSDEEP | `384:F8rnOBG2lRKf9jaf6PcOZ6om/qrE3orNNJR0HNsuC+/e3NwEXD4OKWuVWKThselJ:VzlGxPcOQomCr1rNDunievzW2Tz`
IMP | `6D868D8CB1EC5BC1E6BE42EF04B1146C`
PESHA1 | `9CDF16B242BC7E8EE8D83164AECCD817CC1B19D0`
PE256 | `4EA30953A126F5C1E6D21D5A49B826A620571005DA457AD97DBC8D8FB076B810`

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
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\aspnet_regiis.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/d0563c49d9e645ae243465f33304a278d966393c4bdb138a7e9565afe2896124/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\aspnet_regiis.exe](aspnet_regiis.exe-06138ABFF3EEE34172D46C49BFD48978.md) | 65




MIT License. Copyright (c) 2020-2021 Strontic.


