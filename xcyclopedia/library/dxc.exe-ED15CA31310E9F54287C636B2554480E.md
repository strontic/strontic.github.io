---
title: dxc.exe | DX Compiler
excerpt: What is dxc.exe?
---

# dxc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\dxc.exe`
* Description: DX Compiler

## Hashes

Type | Hash
-- | --
MD5 | `ED15CA31310E9F54287C636B2554480E`
SHA1 | `A631498E24572965897C7AEB841BC20B787120B3`
SHA256 | `0FFF44C2F61C2C61423F08C74ABA325049A1E14EDED5B491EFECB7839CCD9737`
SHA384 | `1DDCB60E2E6F53CCA11CBE3069AA82B325B7DC586CC11D8ADF4C6B805958CB5AFB643DAD87979D599D41BA8ADC2BAA09`
SHA512 | `5A50BBB364D130AB0D6F6C171B074480549914537F47CC502FBE18ED92E18C6B69956401A4D6E6ECDDB63D757D8A8A60586E6B0EC981A4FF5E20AD8AF12C721C`
SSDEEP | `1536:N+MtxZCPfnfsHZ4jweYJA2hjhlT4oFKuxbr41b8ULcGJPxaMusWUpIMY22HREE2j:rlDhjrKHyxGJPxaZUpIMKEE2+4iTHu`
IMP | `A00314C6AABC1FFCB1C05166CB2A3943`
PESHA1 | `6D2EDB4BDE69A0798F15CBADC807C0B1AC68A470`
PE256 | `E0747A9D6A94427C2D5E226746C0A4E1B36039B5D842C09E56397A95B83CD3E1`

## Runtime Data

### Usage (stdout):
```cmhg
OVERVIEW: HLSL Compiler

Version: dxcompiler.dll: 1.5 - 10.0.19041.1; dxil.dll: 1.5(10.0.19041.1)

USAGE: dxc.exe [options] <inputs>

Common Options:
  -help              Display available options
  -nologo            Suppress copyright message
  -Qunused-arguments Don't emit warning for unused driver arguments

Compilation Options:
  -all_resources_bound    Enables agressive flattening
  -auto-binding-space <value>
                          Set auto binding space - enables auto resource binding in libraries
  -Cc                     Output color coded assembly listings
  -default-linkage <value>
                          Set default linkage for non-shader functions when compiling or linking to a library target (internal, external)
  -denorm <value>         select denormal value options (any, preserve, ftz). any is the default.
  -D <value>              Define macro
  -enable-16bit-types     Enable 16bit types and disable min precision types. Available in HLSL 2018 and shader model 6.2
  -export-shaders-only    Only export shaders when compiling a library
  -exports <value>        Specify exports when compiling a library: export1[[,export1_clone,...]=internal_name][;...]
  -E <value>              Entry point name
  -Fc <file>              Output assembly code listing file
  -Fd <file>              Write debug information to the given file, or automatically named file in directory when ending in '\'
  -Fe <file>              Output warnings and errors to the given file
  -Fh <file>              Output header file containing object code
  -flegacy-macro-expansion
                          Expand the operands before performing token-pasting operation (fxc behavior)
  -flegacy-resource-reservation
                          Reserve unused explicit register assignments for compatibility with shader model 5.0 and below
  -force_rootsig_ver <profile>
                          force root signature version (rootsig_1_1 if omitted)
  -Fo <file>              Output object file
  -Gec                    Enable backward compatibility mode
  -Ges                    Enable strict mode
  -Gfa                    Avoid flow control constructs
  -Gfp                    Prefer flow control constructs
  -Gis                    Force IEEE strictness
  -HV <value>             HLSL version (2016, 2017, 2018). Default is 2018
  -H                      Show header includes and nesting depth
  -ignore-line-directives Ignore line directives
  -I <value>              Add directory to include search path
  -Lx                     Output hexadecimal literals
  -Ni                     Output instruction numbers in assembly listings
  -no-warnings            Suppress warnings
  -not_use_legacy_cbuf_load
                          Do not use legacy cbuffer load
  -No                     Output instruction byte offsets in assembly listings
  -Odump                  Print the optimizer commands.
  -Od                     Disable optimizations
  -pack_optimized         Optimize signature packing assuming identical signature provided for each connecting stage
  -pack_prefix_stable     (default) Pack signatures preserving prefix-stable property - appended elements will not disturb placement of prior elements
  -recompile              recompile from DXIL container with Debug Info or Debug Info bitcode file
  -res_may_alias          Assume that UAVs/SRVs may alias
  -rootsig-define <value> Read root signature from a #define
  -T <profile>            Set target profile. 
	<profile>: ps_6_0, ps_6_1, ps_6_2, ps_6_3, ps_6_4, ps_6_5, 
		 vs_6_0, vs_6_1, vs_6_2, vs_6_3, vs_6_4, vs_6_5, 
		 cs_6_0, cs_6_1, cs_6_2, cs_6_3, cs_6_4, cs_6_5, 
		 gs_6_0, gs_6_1, gs_6_2, gs_6_3, gs_6_4, gs_6_5, 
		 ds_6_0, ds_6_1, ds_6_2, ds_6_3, ds_6_4, ds_6_5, 
		 hs_6_0, hs_6_1, hs_6_2, hs_6_3, hs_6_4, hs_6_5, 
		 lib_6_3, lib_6_4, lib_6_5, ms_6_5, as_6_5
  -Vd                     Disable validation
  -Vi                     Display details about the include process.
  -Vn <name>              Use <name> as variable name in header file
  -WX                     Treat warnings as errors
  -Zi                     Enable debug information
  -Zpc                    Pack matrices in column-major order
  -Zpr                    Pack matrices in row-major order
  -Zsb                    Build debug name considering only output binary
  -Zss                    Build debug name considering source information

Optimization Options:
  -O0 Optimization Level 0
  -O1 Optimization Level 1
  -O2 Optimization Level 2
  -O3 Optimization Level 3 (Default)

SPIR-V CodeGen Options:
  -fspv-debug=<value>     Specify whitelist of debug info category (file -> source -> line, tool)
  -fspv-extension=<value> Specify SPIR-V extension permitted to use
  -fspv-flatten-resource-arrays
                          Flatten arrays of resources so each array element takes one binding number
  -fspv-reflect           Emit additional SPIR-V instructions to aid reflection
  -fspv-target-env=<value>
                          Specify the target environment: vulkan1.0 (default) or vulkan1.1
  -fvk-b-shift <shift> <space>
                          Specify Vulkan binding number shift for b-type register
  -fvk-bind-globals <binding> <set>
                          Specify Vulkan binding number and set number for the $Globals cbuffer
  -fvk-bind-register <type-number> <space> <binding> <set>
                          Specify Vulkan descriptor set and binding for a specific register
  -fvk-invert-y           Negate SV_Position.y before writing to stage output in VS/DS/GS to accommodate Vulkan's coordinate system
  -fvk-s-shift <shift> <space>
                          Specify Vulkan binding number shift for s-type register
  -fvk-t-shift <shift> <space>
                          Specify Vulkan binding number shift for t-type register
  -fvk-u-shift <shift> <space>
                          Specify Vulkan binding number shift for u-type register
  -fvk-use-dx-layout      Use DirectX memory layout for Vulkan resources
  -fvk-use-dx-position-w  Reciprocate SV_Position.w after reading from stage input in PS to accommodate the difference between Vulkan and DirectX
  -fvk-use-gl-layout      Use strict OpenGL std140/std430 memory layout for Vulkan resources
  -fvk-use-scalar-layout  Use scalar memory layout for Vulkan resources
  -Oconfig=<value>        Specify a comma-separated list of SPIRV-Tools passes to customize optimization configuration (see http://khr.io/hlsl2spirv#optimization)
  -spirv                  Generate SPIR-V code

Utility Options:
  -dumpbin              Load a binary file rather than compiling
  -extractrootsignature Extract root signature from shader bytecode (must be used with /Fo <file>)
  -getprivate <file>    Save private data from shader blob
  -P <value>            Preprocess to file (must be used alone)
  -Qembed_debug         Embed PDB in shader container (must be used with /Zi)
  -Qstrip_debug         Strip debug information from 4_0+ shader bytecode  (must be used with /Fo <file>)
  -Qstrip_priv          Strip private data from shader bytecode  (must be used with /Fo <file>)
  -Qstrip_reflect       Strip reflection data from shader bytecode  (must be used with /Fo <file>)
  -Qstrip_rootsignature Strip root signature data from shader bytecode  (must be used with /Fo <file>)
  -setprivate <file>    Private data to add to compiled shader blob
  -setrootsignature <file>
                        Attach root signature to shader bytecode
  -verifyrootsignature <file>
                        Verify shader bytecode with root signature


```

### Usage (stderr):
```cmhg
dxc failed : Target profile argument is missing

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\dxc.exe |
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

* Original Filename: dxc.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\dxc.exe](dxc.exe-C0D576515CB38D7788DC8B95DD3128CF.md) | 40




MIT License. Copyright (c) 2020 Strontic.


