---
title: ilasm.exe | Microsoft .NET Framework IL assembler
excerpt: What is ilasm.exe?
---

# ilasm.exe 

* File Path: `C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ilasm.exe`
* Description: Microsoft .NET Framework IL assembler
* Comments: Flavor=Retail


## Hashes

Type | Hash
-- | --
MD5 | `9FBD826E2AC6D3E03F5A39930B7100D7`
SHA1 | `8B2287BD218DF1E68C1F6D95FFF979E1DEBCD4AC`
SHA256 | `8187CB164A61CF4FC4A4F68955F4D3C55C322F7509FC1DBC9B02B2B9FEEECD57`
SHA384 | `3A6E20FF2F42CDED1D43A4F97F47D2DAD779D20C3DD4482A99F2EA71E28F1AE277A414F1B436A89F181CDCFDCA91E9BF`
SHA512 | `85C26D5CD82489E9943E86E95635D6519DAFD0A7B20BA7805D895AD7E83F0ACCEEE0CE150C67C899248FD73B0EC3CBA9901153F54174012F49F0CAEDC51B095A`
SSDEEP | `6144:Nus3jc3hkV0R0nONM7BwzdqUtZP7mT6TEY8ohyJg3s:NuFkmRKOe9w1tZDmT6TEY8oEg3s`
IMP | `75909521ECD39B683082F82FA13EAE5B`
PESHA1 | `6E31EA652E70E9ACB862B933FB480FAADC92C69A`
PE256 | `FD8FD3EB3F2B51810A0709E3404DD85296E2A9CF6BE6786671547E8497E400CD`

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

### Loaded Modules:

Path |
-- |
C:\WINDOWS\Microsoft.NET\Framework\v4.0.30319\ilasm.exe |
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

* Original Filename: ilasm.exe
* Product Name: Microsoft .NET Framework
* Company Name: Microsoft Corporation
* File Version: 4.8.4161.0 built by: NET48REL1
* Product Version: 4.8.4161.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/8187cb164a61cf4fc4a4f68955f4d3c55c322f7509fc1dbc9b02b2b9feeecd57/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\Microsoft.NET\Framework\v4.0.30319\ilasm.exe](ilasm.exe-2B2AE2C9C5D693D2306EF388583B1A03.md) | 86

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


