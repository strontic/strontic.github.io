---
title: aspnet_merge.exe | aspnet_merge.exe
excerpt: What is aspnet_merge.exe?
---

# aspnet_merge.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\aspnet_merge.exe`
* Description: aspnet_merge.exe
* Comments: aspnet_merge.exe


## Hashes

Type | Hash
-- | --
MD5 | `80365B1BCA6859C13EDDC66D6E323597`
SHA1 | `2000C24EF20B90E09EB6BBFA1324CA1CC98D7C4E`
SHA256 | `261FE302BE15AD77E6CAD8C15BF7DB7D326D493B1C790F234E2F652B58F362D1`
SHA384 | `EBB78FB40E5C5719EECEA3420BB59A55F0880DF02EA0C4B3FC4BF4793EE6A7877B22855DBB165E336F5E74CE19E66BA0`
SHA512 | `2577E21AB9E21D5691B81DF41697A90F3ADA9F05B74E27E7AE321F3BEAF111AA672B958FB8157F52C19F2CE426E8F17384E80AFE54F4F46D622A64A48B67069B`
SSDEEP | `12288:p346MW/wmJ47iF0H+zzPxF3dv2E/5RTw3xjI3Zh3UnfNKWK:i6Mavb/5RTc6Zh3Un1xK`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `8FD1395ED31174BC1FAE6B1740AB26FF7AA167B9`
PE256 | `A0A446836AADC46E80603FBD6F6C6B16638CC416FC0C0AC2F115772F644023A4`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) ASP.NET Merge Tool version 4.8.4084.0.
Please note, new versions of the ASP.NET Merge Tool will no longer be included in the .NET SDK. Instead, new versions are now exclusively available via NuGet. For details, go to http://go.microsoft.com/fwlink/?LinkId=528812
Utility to merge precompiled ASP.NET assemblies.
Copyright (c) Microsoft Corporation. All rights reserved.

Usage: 
aspnet_merge [-?] applicationPath [-keyfile filename [-delaysign]]
             [-o assemblyname | -w assemblyname | -prefix prefix]
             [-copyattrs [assemblyfile]] [-debug] [-nologo]
             [-errorstack] [-r] [-xmldocs] [-a] [-log logfile]
             [-allowattrs filename]

-?                  Display this help text.
applicationPath     The physical path of the precompiled application.
-keyfile            The physical path to the strong name keyfile.
-delaysign          Delay sign the merged assemblies.
-o                  Merge the entire application into a single assembly with
                    the given name. This option cannot be combined with the
                    -prefix or -w options.
-w                  Merge the application Web files into a single assembly with
                    the given name. This option cannot be combined with the -o
                    or -prefix options.
-prefix             Prefix the merged assembly names with a specified string.
                    This option cannot be combined with the -o or -w options.
-copyattrs          Copy the assembly level attributes from the input assembly.
                    If input assembly is not specified, the main App_Code
                    assembly will be used instead.
-debug              Preserve debug information in the merged assembly. The
                    default is to remove debug information.
-nologo             Suppress the copyright message.
-errorstack         Show additional information that can help debug certain
                    conditions.
-r                  Remove the .compiled files for main code assembly. This
                    option should not be used if your application contains any
                    explicit type references to the main code assembly.
-xmldocs            Merge the xml documentation files associated with the input
                    assemblies.
-a                  Force merge the assemblies.
-log                Log messages to the specified file.
-allowattrs         Use the specified text file which contains attributes to
                    exclude when checking consistency of attributes in merged
                    assemblies. Each line of the file can either be a fully
                    qualified name of an attribute, or a namespace. If a
                    namespace is specified, all attributes found in the
                    namespace will be excluded.

Examples:

The following command merges the assemblies in the precompiled application
under C:\MyTarget:
    aspnet_merge c:\MyTarget

The following command merges the assemblies in C:\MyTarget and signs the merged
assemblies using the Keyfile.snk file:
    aspnet_merge -keyfile keyfile.snk c:\MyTarget

The following command merges all Web application assemblies into a single
assembly and names the resulting assembly MyApp.dll:
    aspnet_merge -o MyApp.dll c:\MyTarget


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\aspnet_merge.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: aspnet_merge.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0
* Product Version: 4.8.4084.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/261fe302be15ad77e6cad8c15bf7db7d326d493b1c790f234e2f652b58f362d1/detection





MIT License. Copyright (c) 2020 Strontic.


