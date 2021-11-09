---
title: ilasm.exe | Microsoft .NET Framework IL assembler
excerpt: What is ilasm.exe?
---

# ilasm.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe`
* Description: Microsoft .NET Framework IL assembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `D7DD99CCEA186AEBF467FC25C5C5EBB5`
SHA1 | `DEDDBB1ADBECC38E6E9316D0A17F5CE6345ABD0C`
SHA256 | `486BE223BCF745332CB86A2B0BB3399E5BC89FC2C31C4B3AC6A9EA13CF82FB3F`
SHA384 | `671435AFCAD8B634D3852A1FB1B7DEDBE5825AB80163F031FFD3A90D66541B8B2D7F6393ABD6E32A1AFA2BDC515383C4`
SHA512 | `D8F4A8E0F2163F253F6B4C1A2C37E91492763359A850ED8452FEC82DFDA8788982A0C4B60054C77F242AFE0FD4E7010C6AE9FA4C6EB925EA910F5CC6CCB8F2CD`
SSDEEP | `6144:KG/TojdEL0iXFsTK0Z1a2kO72qfux5B0cEsQEsY2eCutVkO9kP:KG/ToZbiXFsTTwfOq4ECP`
IMP | `B5ACD3F4BA7467B8D6211B3A8B8E24E2`
PESHA1 | `2D6035E6F18833E72832DC4CF125C9930721ADAC`
PE256 | `E5F2A30769B4C7F8F47919CE0E0E83F75A80DA5B31645EEAEE0062AA426E60AA`

## Runtime Data

### Usage (stdout):
```cmhg

Microsoft (R) .NET Framework IL Assembler version 4.8.4161.0
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

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe |
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

* Original Filename: ilasm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/486be223bcf745332cb86a2b0bb3399e5bc89fc2c31c4b3ac6a9ea13cf82fb3f/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework64\v4.0.30319\ilasm.exe](ilasm.exe-5C0E98A6D6B8B42B165C2F415837DE1E.md) | 90

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


