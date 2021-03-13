---
title: fxc.exe | 
excerpt: What is fxc.exe?
---

# fxc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\fxc.exe`

## Hashes

Type | Hash
-- | --
MD5 | `1AC5E88D6C1E4A9E40CC4915244E44F5`
SHA1 | `372FC943325FED85B6FEE180BE5C51B3C65EC51D`
SHA256 | `8CAECB6664EB715387CAD72FD1571419A44F596FE7DDEE0D9B1173AE947074AC`
SHA384 | `87441F25B28A6791FDB2DAEE32FDB5042808B6C67DB3C01D0E65F6226F22CF92863EF5D72650EF484B821E5C8035560A`
SHA512 | `D1C6479B33D7C54D8EE96A8F98DF6C63FF86E006540BE4CBB349E5B8A869035154DD452892FBDA4E3745A898F9050BDF753A48EC0D9175E5C270FDBEF98A7600`
SSDEEP | `3072:bhWqqWn2yhdrNuNVcyI2raTgJH4PppxqUrOUa+iR2PjXr:bhWqqWn2UdrNuNVcyaTgJapt6dxMPf`
IMP | `286B7A74BCE52FC2963DE05C923E40B1`
PESHA1 | `48B612FA8C7A3B8D2C141B73CD32144B914D1A96`
PE256 | `61AA908863F9A14205F5FA7439D9BF79399F5450971C089354461982B01BCD11`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\fxc.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/8caecb6664eb715387cad72fd1571419a44f596fe7ddee0d9b1173ae947074ac/detection





MIT License. Copyright (c) 2020-2021 Strontic.


