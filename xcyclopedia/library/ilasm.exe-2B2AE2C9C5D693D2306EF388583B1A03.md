---
title: ilasm.exe | Microsoft .NET Framework IL assembler
excerpt: What is ilasm.exe?
---

# ilasm.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework\v4.0.30319\ilasm.exe`
* Description: Microsoft .NET Framework IL assembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `2B2AE2C9C5D693D2306EF388583B1A03`
SHA1 | `D0D62969D155207B1067C3030B56FCCDB0C6A637`
SHA256 | `2BD4200161FC147790022F47F90A2E08A2E058BB8269D7D4035D5D46DEFFCE6A`
SHA384 | `5F0E758657D40996538D7F0D61D6F05E76694ED8D51A7321A84612CFB6309C1356B14690434A191616CD6B4B732EF30A`
SHA512 | `374718584035AB37AB10AA4C380887C1601632D9EB86E262DFAA91764E7964128B06BAFB62747DA7D7FEB40A3617FA14F656FF2A9CC3DB04E766EACB67B623A0`
SSDEEP | `6144:Ius35+ihkV0R0nONM7BwzdqUtZP7mT6TEY8ohydg3h:Iu+kmRKOe9w1tZDmT6TEY8oUg3h`
IMP | `75909521ECD39B683082F82FA13EAE5B`
PESHA1 | `B7667A66635D08BA022A9976D5FC389B0C10BB2C`
PE256 | `C0CA2A77A8845B73E9E90C8711554D91B57F0C0B188F0F198D17EB16496477D0`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) .NET Framework IL Assembler version 4.8.4084.0
Copyright (c) Microsoft Corporation.  All rights reserved.



Usage: ilasm [Options] <sourcefile> [Options]

Options:
/NOLOGO         Don't type the logo
/QUIET          Don't report assembly progress
/NOAUTOINHERIT  Disable inheriting from System.Object by default
/DLL            Compile to .dll
/EXE            Compile to .exe (default)
/PDB            Create the PDB file without enabling debug info tracking
/APPCONTAINER   Create an AppContainer exe or dll
/DEBUG          Disable JIT optimization, create PDB file, use sequence points from PDB
/DEBUG=IMPL     Disable JIT optimization, create PDB file, use implicit sequence points
/DEBUG=OPT      Enable JIT optimization, create PDB file, use implicit sequence points
/OPTIMIZE       Optimize long instructions to short
/FOLD           Fold the identical method bodies into one
/CLOCK          Measure and report compilation times
/RESOURCE=<res_file>    Link the specified resource file (*.res) 
			into resulting .exe or .dll
/OUTPUT=<targetfile>    Compile to file with specified name 
			(user must provide extension, if any)
/KEY=<keyfile>      Compile with strong signature 
			(<keyfile> contains private key)
/KEY=@<keysource>   Compile with strong signature 
			(<keysource> is the private key source name)
/INCLUDE=<path>     Set path to search for #include'd files
/SUBSYSTEM=<int>    Set Subsystem value in the NT Optional header
/SSVER=<int>.<int>  Set Subsystem version number in the NT Optional header
/FLAGS=<int>        Set CLR ImageFlags value in the CLR header
/ALIGNMENT=<int>    Set FileAlignment value in the NT Optional header
/BASE=<int>     Set ImageBase value in the NT Optional header (max 2GB for 32-bit images)
/STACK=<int>    Set SizeOfStackReserve value in the NT Optional header
/MDV=<version_string>   Set Metadata version string
/MSV=<int>.<int>   Set Metadata stream version (<major>.<minor>)
/PE64           Create a 64bit image (PE32+)
/HIGHENTROPYVA  Set High Entropy Virtual Address capable PE32+ images (default for /APPCONTAINER)
/NOCORSTUB      Suppress generation of CORExeMain stub
/STRIPRELOC     Indicate that no base relocations are needed
/ITANIUM        Target processor: Intel Itanium
/X64            Target processor: 64bit AMD processor
/ARM            Target processor: ARM processor
/32BITPREFERRED Create a 32BitPreferred image (PE32)
/ENC=<file>     Create Edit-and-Continue deltas from specified source file

Key may be '-' or '/'
Options are recognized by first 3 characters
Default source file extension is .il

Target defaults:
/PE64      => /PE64 /ITANIUM
/ITANIUM   => /PE64 /ITANIUM
/X64       => /PE64 /X64


```

### Usage (stderr):
```cmhg
Error : Invalid Option: --help

```

### Loaded Modules:

Path |
-- |
C:\Windows\Microsoft.NET\Framework\v4.0.30319\ilasm.exe |
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

* Original Filename: ilasm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/2bd4200161fc147790022f47f90a2e08a2e058bb8269d7d4035d5d46deffce6a/detection


## Possible Misuse

*The following table contains possible examples of `ilasm.exe` being misused. While `ilasm.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `Name: Ilasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `- Command: ilasm.exe C:\public\test.txt /exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `- Command: ilasm.exe C:\public\test.txt /dll`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework\v4.0.30319\ilasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `- Path: C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ilasm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ilasm.yml) | `- Link: https://github.com/LuxNoBulIshit/BeforeCompileBy-ilasm/blob/master/hello_world.txt`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


