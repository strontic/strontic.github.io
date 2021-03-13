---
title: ilasm.exe | Microsoft .NET Framework IL assembler
excerpt: What is ilasm.exe?
---

# ilasm.exe 

* File Path: `C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe`
* Description: Microsoft .NET Framework IL assembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `5C0E98A6D6B8B42B165C2F415837DE1E`
SHA1 | `6B1E04703BAFC0DCE38231055217E9B936073B0C`
SHA256 | `584DBDAA56A351BD6EC6E02165060BCFAB6E6B572FF8E3E694D4B3F90475AAC9`
SHA384 | `8FDC5DDF2777C2B74B6D9C98DE74D376590835803892E549040E61CFBE7B8AD5BBA998F3379A7FBCD862522576FDA0A9`
SHA512 | `652F77DA742F7A176BFA518C7087BD79F472804FCE203C510F9E27785AFC5ACF83F26C7DD79CFE2B224A37F5C7056343D0C3A3F3E95CE960E8A2EB5BB950DB68`
SSDEEP | `6144:VG/TojdEL0iXFsTK0Z1a2kO72qfux5B0cEsQEsY0c6utVkO98:VG/ToZbiXFsTTwfOq4Eu`
IMP | `B5ACD3F4BA7467B8D6211B3A8B8E24E2`
PESHA1 | `98F1D2AB20277D41D7A0B2327BA789F6358A6A2F`
PE256 | `9076FB059989C803C391BF3F25697440846478A175994C4382111E4333028213`

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
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe |
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

* Original Filename: ilasm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4084.0 built by: NET48REL1
* Product Version: 4.8.4084.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/584dbdaa56a351bd6ec6e02165060bcfab6e6b572ff8e3e694d4b3f90475aac9/detection


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


