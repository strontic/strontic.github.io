---
title: fxc.exe | 
excerpt: What is fxc.exe?
---

# fxc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\fxc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `9DB376CC62713F65E9AF94C294F20177`
SHA1 | `37D27830EB922E9E4C245D1DEAE9FF230777F351`
SHA256 | `CA1954EC33FC845502928744E642AA01FB205067248BECB1018CF6FD68B998FE`
SHA384 | `87A56122A2E4D23D0192429447667097EA1C2CFF7C6C8DE1AD3E09F9C7653D6932D576618BA35749F651C1DE5161C0F3`
SHA512 | `D108F7E22461F916B6FCFDD8AA6E39A45250124EFF0B38958FC9240666B1CBCA01B95F1FB43388594CA14CB87A0EB265FA43E4594D9B09510485031B7C40FA33`
SSDEEP | `1536:EKObo10rG30FqPvYu2KfBGhU+XgtC57L/toKFG6xR4IgmX+fHY0f8SDCYywBu3PP:XOk6h4cV1oKFZxQfHDR32PjT`
IMP | `26CDFD3C494168E05B79F230451C2097`
PESHA1 | `7A2C6DEC193E5971BE13FA4F59D8ADE6FC028302`
PE256 | `9A7659394743240C47F10B336FCE20A601E0EB3E1C8039C9015AE4E0FEA4BA38`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Direct3D Shader Compiler 10.1
Copyright (C) 2013 Microsoft. All rights reserved.

Usage: fxc <options> <files>

   /?, /help           print this message

   /T <profile>        target profile
   /E <name>           entrypoint name
   /I <include>        additional include path
   /Vi                 display details about the include process

   /Od                 disable optimizations
   /Op                 disable preshaders
   /O{0,1,2,3}         optimization level 0..3.  1 is default
   /WX                 treat warnings as errors
   /Vd                 disable validation
   /Zi                 enable debugging information
   /Zss                debug name with source information
   /Zsb                debug name with only binary information
   /Zpr                pack matrices in row-major order
   /Zpc                pack matrices in column-major order

   /Gpp                force partial precision
   /Gfa                avoid flow control constructs
   /Gfp                prefer flow control constructs
   /Gdp                disable effect performance mode
   /Ges                enable strict mode
   /Gec                enable backwards compatibility mode
   /Gis                force IEEE strictness
   /Gch                compile as a child effect for FX 4.x targets

   /Fo <file>          output object file
   /Fl <file>          output a library
   /Fc <file>          output assembly code listing file
   /Fx <file>          output assembly code and hex listing file
   /Fh <file>          output header file containing object code
   /Fe <file>          output warnings and errors to a specific file
   /Fd <file>          extract shader PDB and write to given file
   /Vn <name>          use <name> as variable name in header file
   /Cc                 output color coded assembly listings
   /Ni                 output instruction numbers in assembly listings
   /No                 output instruction byte offset in assembly listings
   /Lx                 output hexadecimal literals

   /P <file>           preprocess to file (must be used alone)

   @<file>             options response file
   /dumpbin            load a binary file rather than compiling
   /Qstrip_reflect     strip reflection data from 4_0+ shader bytecode
   /Qstrip_debug       strip debug information from 4_0+ shader bytecode
   /Qstrip_priv        strip private data from 4_0+ shader bytecode
   /Qstrip_rootsignature         strip root signature from shader bytecode

   /setrootsignature <file>      attach root signature to shader bytecode
   /extractrootsignature <file>  extract root signature from shader bytecode
   /verifyrootsignature <file>   verify shader bytecode against root signature

   /compress           compress DX10 shader bytecode from files
   /decompress         decompress bytecode from first file, output files should
                       be listed in the order they were in during compression
   
   /shtemplate <file>  template shader file for merging/matching resources
   /mergeUAVs          merge UAV slots of template shader and current shader
   /matchUAVs          match template shader UAV slots in current shader
   /res_may_alias      assume that UAVs/SRVs may alias for cs_5_0+
   /enable_unbounded_descriptor_tables  enables unbounded descriptor tables
   /all_resources_bound  enable aggressive flattening in SM5.1+

   /setprivate <file>  private data to add to compiled shader blob
   /getprivate <file>  save private data from shader blob
   /force_rootsig_ver <profile>  force root signature version (rootsig_1_1 if omitted)

   /D <id>=<text>      define macro
   /nologo             suppress copyright message

   <profile>: cs_4_0 cs_4_1 cs_5_0 cs_5_1 ds_5_0 ds_5_1 gs_4_0 gs_4_1 gs_5_0 
      gs_5_1 hs_5_0 hs_5_1 lib_4_0 lib_4_1 lib_4_0_level_9_1 
      lib_4_0_level_9_1_vs_only lib_4_0_level_9_1_ps_only lib_4_0_level_9_3 
      lib_4_0_level_9_3_vs_only lib_4_0_level_9_3_ps_only lib_5_0 ps_2_0 
      ps_2_a ps_2_b ps_2_sw ps_3_0 ps_3_sw ps_4_0 ps_4_0_level_9_1 
      ps_4_0_level_9_3 ps_4_0_level_9_0 ps_4_1 ps_5_0 ps_5_1 rootsig_1_0 
      rootsig_1_1 tx_1_0 vs_1_1 vs_2_0 vs_2_a vs_2_sw vs_3_0 vs_3_sw vs_4_0 
      vs_4_0_level_9_1 vs_4_0_level_9_3 vs_4_0_level_9_0 vs_4_1 vs_5_0 vs_5_1 

```

### Usage (stderr):
```cmhg
C:\Users\user\help(1,1-4): error X3000: unrecognized identifier 'DXGI'

compilation failed; no code produced

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\fxc.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: fxc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\fxc.exe](fxc.exe-38E4CBFAECF88274F501C6ECD0832AEC.md) | 29




MIT License. Copyright (c) 2020-2021 Strontic.


