---
title: WinMDExp.exe | Microsoft .NET Framework Windows Metadata Exporter
excerpt: What is WinMDExp.exe?
---

# WinMDExp.exe 

* File Path: `C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WinMDExp.exe`
* Description: Microsoft .NET Framework Windows Metadata Exporter
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `FD3EDAFFA3865DF5D5B25E6F493539CE`
SHA1 | `EF6F720470F4421D4928BF1F6698930D7E79226C`
SHA256 | `7C45E0E0996978D6A54C44DF159A45850E01A30DAA94FD80149641CB310183D6`
SHA384 | `B3EBC6C14ABB5E155B86F75433A138BBF384AA375AF038589321BD14D190282EAB3F688A929BD315CF51118C87951CC7`
SHA512 | `D5DEAACBA461C855660F43BD434D8E77774886C6F045E4B26BA98A75ECC03D5F11D4A8F2C0ECFAD3E261BDB99F3C6A144B04E5F0B3D8305136DAA223BBB746E1`
SSDEEP | `24576:CcjdWgRJLUfPi/HxRYZO3mWW8Y9d+19VAtwzLb7yPWmTw9+4BuqoNlB518ZtE:CeFR5vc3+rVSwzsqKt518Z+`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `87E70073E71571599754F128AA1B70B399CEBCCA`
PE256 | `71E474EA35E67E51BCB477404ED6955CF0C3B48D8664D199788E0E85C65D3D5F`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) .NET Framework Windows Metadata Exporter 4.8.4084.0 
Copyright (C) Microsoft Corporation.  All rights reserved. 
 
Error parsing the command line: Argument '--help' is unknown.. 
 
Usage: WinMDExp.exe [arguments] <winmdmodule> 
 
Arguments: 
 /d:<docfile> or /doc:<docfile> 
   Specify the name of the output XML documentation file 
 
 /md:<docfile> or /moduledoc:<docfile> 
   Specify the name of the XML documentation file for the winmdmodule being exported 
 
 /mp:<symbolfile> or /modulepdb:<symbolfile> 
   Specify the name of the PDB file containing symbols for the winmdmodule being exported 
 
 /nowarn:<warning> 
   Suppress the given warning number 
 
 /o:<file> or /out:<file> 
   Specify the name of the output Windows Metadata file 
 
 /p:<symbolfile> or /pdb:<symbolfile> 
   Specify the name of the PDB file to contain the symbols for the exported Windows Metadata file 
 
 /r:<winmd> or /reference:<winmd> 
   Adds a winmd file to reference during export 
 
 /warnaserror+ 
   Treat all warnings as errors. 
 
 /utf8output 
   Output messages in UTF-8 encoding. 
 
 
 /assemblyunificationpolicy:<policy> or /up:<policy> 
   Set the assembly unification policy, choices are: 
 
   HighestVersion - Unify assemblies to the highest referenced version.  Unification will only succeed if the unified assembly version is greater than or equal to the referenced assembly version.  Unification applies to assemblies with identical names, public key tokens, and cultures. [default] 
 
   ExactMatch - Do not unify assemblies, instead require exact version matching 
 
/windowsRuntimeVersion:<version> 
   The Windows Runtime Version to target(1.2, 1.3, etc). The default is to use the highest version from the referenced winmd files. 
 
Arguments and assemblies can also be provided in a response file provided on the command line prefixed with an @. Each line in the response file should contain a single argument or assembly name. 
 

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft SDKs\Windows\v10.0A\bin\NETFX 4.8 Tools\WinMDExp.exe |
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

* Original Filename: WinMDExp.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/7c45e0e0996978d6a54c44df159a45850e01a30daa94fd80149641cb310183d6/detection





MIT License. Copyright (c) 2020-2021 Strontic.


