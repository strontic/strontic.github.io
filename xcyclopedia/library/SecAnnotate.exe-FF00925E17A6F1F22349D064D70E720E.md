---
title: SecAnnotate.exe | Microsoft .NET Framework Security Transparency Annotator
excerpt: What is SecAnnotate.exe?
---

# SecAnnotate.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\SecAnnotate.exe`
* Description: Microsoft .NET Framework Security Transparency Annotator
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `FF00925E17A6F1F22349D064D70E720E`
SHA1 | `E83F4F4057EE2B6B4E48D126A014AA3575A8C9BA`
SHA256 | `7E2E24188B61B19F872BA72DBF30D6D2324EE9E67F1AD95280DC873BC0E49F5B`
SHA384 | `CEB32EBD24A137A1C1F829524FDC2A07D81481251F22A0CE5EFB85317D7F125FDE7743C214A72FED2DAB7702009B6281`
SHA512 | `AB67473A71609D09D3D238590B53AE0AAFB38E5FECD38B4187AB182353E5B53FCF55000863CAC2A2581E8B1376F27BCFA07E5EEB64CD1F5BEC7C71563634536D`
SSDEEP | `12288:GArvHQvWXXAiY5+jJw3rrP18TZJwU4oEKDPbn7v8AqIsy7Fmx88hK+DLZ:GArOAhY59cLBLghIs/x88hK+DLZ`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `6175488458E724DA98D0250A17B65804EE3911E7`
PE256 | `B0C20B7EF2B896B21A9F8713BFC074AE382C60D14FD67E5C3AB9E973030302A1`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Security Transparency Annotator 4.8.4084.0 
Copyright (C) Microsoft Corporation.  All rights reserved. 
 
Usage: SecAnnotate.exe [arguments] assemblies 
 
Arguments: 
 /a or /showstatistics 
   Show statistics about the use of transparency in assemblies being analyzed. 
 
 /d:directory or /referencedir:directory 
   Include the specified directory when searching for dependent assemblies during annotation. 
 
 /i or /includesignatures 
   Include extended signature information in the annotation report file. 
 
 /n or /nogac 
   Suppress searching for referenced assemblies in the Global Assembly Cache. 
 
 /o:output.xml or /out:output.xml 
   Specifies the output annotation file. 
 
 /p:maxpasses or /maximumpasses:maxpasses 
   Specify the maximum number of annotation passes to make on assemblies before stopping the generation of new annotations. 
 
 /q or /quiet 
   Quiet mode: annotator will only output error information and no status messages. 
 
 /r:assembly or /referenceassembly:assembly 
   Include the specified assembly when resolving dependent assemblies during annotation. Reference assemblies are given priority over assemblies found in the reference path. 
 
 /s:rulename or /suppressrule:rulename 
   Suppress running a transparency rule on the input assemblies. 
 
 /t or /forcetransparent 
   Forces Annotator to treat all assemblies without any transparency annotations as if they were entirely transparent. 
 
 /t:assembly or /forcetransparent:assembly 
   Force the given assembly to be transparent, regardless of its current assembly level annotations. 
 
 /v or /verify 
   Verify that an assembly's annotations are correct only, do not attempt to make multiple passes to find all required annotations if the assembly does not verify. 
 
 /x or /verbose 
   Verbose output while annotating 
 
 /y:directory or /symbolpath:directory 
   Include the specified directory when searching for symbol files during annotation. 
 
Arguments and assemblies may also be provided in a response file provided on the command line prefixed with an @. Each line in the response file should contain a single argument or assembly name. 
 

```

### Usage (stderr):
```cmhg
Error running annotator: Assembly 'C:\Users\user\help' could not be loaded. Check to ensure the file exists, and is a valid assembly. 

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\SecAnnotate.exe |
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

* Original Filename: SecAnnotate.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/7e2e24188b61b19f872ba72dbf30d6d2324ee9e67f1ad95280dc873bc0e49f5b/detection





MIT License. Copyright (c) 2020-2021 Strontic.


