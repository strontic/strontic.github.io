---
title: gflags.exe | Microsoft NT Global Flags Manipulator
excerpt: What is gflags.exe?
---

# gflags.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\gflags.exe`
* Description: Microsoft NT Global Flags Manipulator

## Hashes

Type | Hash
-- | --
MD5 | `2687AF1BBEF4BB00CE45541A6D6F2FE1`
SHA1 | `A6BAB85D956788720CBA5F5465260C251A1999E5`
SHA256 | `1604B95CF7D9CF278D619C0F73902790CE925C1E5C3A3F542E92293754160F64`
SHA384 | `612DAC1469287DC4C2B033CE885A6D57ACDAD3E3BE86FA741F8192F7CD5E16E4C36AB5987F682AAAA4EDD627723ADA5A`
SHA512 | `8C1B22D822466D45096819310B09E1A8310AD5D95F5DCE9D6A7EADCEB708E5A2712A816F707CFD494B51437B45328007EE3C75D70E8B71BCAEE65CACDC8C3B51`
SSDEEP | `1536:ou9HiFGPMBcno64xGtCZ5UfMt7HcmcAKxjouKT3K2jXBR+geRtk/VXfW9065:onfjxrKxjouG3jX+geRtk9X+9065`
IMP | `B8B3384C59DB7CB2D5236D97D33B7D3F`
PESHA1 | `1C0E38E0B16941A3C612F636712B43268AD72128`
PE256 | `BE6C68FF24FF786EE3F863B85D847A3B12AA50015DF3B5F69A1E6E823CBDA5F6`

## Runtime Data

### Usage (stderr):
```cmhg
GFLAGS: Unexpected argument - '-help'
                                                                         
usage: GFLAGS [-r [<Flags>]] |                                           
              [-r +spp TAG | -r +spp SIZE | -r -spp |               
              [-k [<Flags>]] |                                           
              [-k +spp TAG | -k +spp SIZE | -k -spp] |
              [-ro [-d | { -i <ImageFileName> | -t <PoolTag>[;<PoolTag>...] } [-p] ] | 
              [-ko [-d | { -i <ImageFileName> | -t <PoolTag>[;<PoolTag>...] } [-p] ] | 
              [-i <ImageFileName> [<Flags>]] |          
              [-i <ImageFileName> -tracedb <SizeInMb>] |
              [-p <PageHeapOptions>] (use `-p ?' for help)  |            
                                                                         
where: <Flags> is a 32 bit hex number (0x12345678) that specifies        
       one or more global flags to set.                                  
       -r operates on system registry settings.                          
       -r +spp TAG - Set Special Pool tag value.                         
                     TAG can have up to four characters.                  
       -r +spp SIZE - Set Special Pool block size value.                 
                      SIZE must be in hex format, starting with characters 0x. 
       -r -spp      - Disable Special Pool tag or block size.            
       -k operates on kernel settings of the running system.             
          -k +spp TAG   - Set Special Pool tag value at run time.
                          TAG can have up to four characters.
          -k +spp SIZE  - Set Special Pool block size value at run time.
                          SIZE must be in hex format, starting with characters 0x.
          -k -spp       - Disable Special Pool tag or block size at run time.
       -ro operates on object reference tracing at boot time.            
       -ko operates on object reference tracing at run time.             
          -d disables object reference tracing. Do not specify any       
             other tracing options.                                      
          -i <ImageFileName> specifies the image name for which          
             to capture traces. All processes started up with this       
             image file will be traced.                                  
          -t <PoolTag>[;<PoolTag>...] specifies the pool tags for which  
             to capture traces. Pool tags should be 4 letters each,      
             separated by ';'. This value is case sensitive.             
          -p maintains traces after the objects are destroyed(permanent).
             By default traces are temporary.                            
          Unless you are using -d you must specify at least one of the   
          -i or the -p options. You may specify both in which case       
          objects with a pool tag that is among the list of pool tags    
          you specify, created by processes with the image filename      
          you specify will be traced. -ko settings override -ro settings.
          Also, if you specify a new set of -ko settings the previous    
          -ko settings, if any, are lost (same for -ro).                   
       -i operates on settings for a specific image file.                
           [ignored when not suported in the current OS versions]        
                                                                         
       If only the switch is specified, then current settings            
       are displayed, not modified.  If flags specified for -i           
       option are FFFFFFFF, then registry entry for that image           
       is deleted                                                        
                                                                         
The `-tracedb' option is used to set the size of the stack trace         
database used to store runtime stack traces. The actual database         
will be created if the `+ust' flag is set in a previous command.         
`-tracedb 0' will revert to the default size for the database.           
                                                                         
If no arguments are specified to GFLAGS then it displays                 
a dialog box that allows the user to modify the global                   
flag settings.                                                           
Note: The dialog box is only displayed if the GflagsUI dll is available. 
                                                                         
Flags may either be a single hex number that specifies all               
32-bits of the GlobalFlags value, or it can be one or more               
arguments, each beginning with a + or -, where the + means               
to set the corresponding bit(s) in the GlobalFlags and a -               
means to clear the corresponding bit(s).  After the + or -               
may be either a hex number or a three letter abbreviation                
for a GlobalFlag.  Valid abbreviations are:                              
                                                                         
    soe - Stop On Exception
    sls - Show Loader Snaps
    dic - Debug Initial Command
    shg - Stop on Hung GUI
    htc - Enable heap tail checking
    hfc - Enable heap free checking
    hpc - Enable heap parameter checking
    hvc - Enable heap validation on call
    vrf - Enable application verifier
    ptg - Enable pool tagging
    htg - Enable heap tagging
    ust - Create user mode stack trace database
    kst - Create kernel mode stack trace database
    otl - Maintain a list of objects for each type
    htd - Enable heap tagging by DLL
    dse - Disable stack extensions
    d32 - Enable debugging of Win32 Subsystem
    ksl - Enable loading of kernel debugger symbols
    dps - Disable paging of kernel stacks
    scb - Enable system critical breaks
    dhc - Disable Heap Coalesce on Free
    ece - Enable close exception
    eel - Enable exception logging
    eot - Enable object handle type tagging
    hpa - Enable page heap
    dwl - Debug WINLOGON
    ddp - Disable kernel mode DbgPrint output
    cse - Early critical section event creation
    sue - Stop on Unhandled Exception
    bhd - Enable bad handles detection
    dpd - Disable protected DLL verification
    lpg - Load image using large pages if possible

All images with ust enabled can be accessed in the
USTEnabled key under 'Image File Options'.

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\gflags.exe |
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

* Original Filename: GFLAGS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/1604b95cf7d9cf278d619c0f73902790ce925c1e5c3a3f542e92293754160f64/detection


## Possible Misuse

*The following table contains possible examples of `gflags.exe` being misused. While `gflags.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can be set directly via the Registry or in Global Flags via the GFlags tool. (Citation: Microsoft GFlags Mar 2017) IFEOs are represented as <code>Debugger</code> values in the Registry under <code>HKLM\SOFTWARE{\Wow6432Node}\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\<executable></code> where <code>&lt;executable&gt;</code> is the binary on which the debugger is attached. (Citation: Microsoft Dev Blog IFEO Mar 2010) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can also enable an arbitrary monitor program to be launched when a specified program silently exits (i.e. is prematurely terminated by itself or a second, non kernel-mode process). (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) Similar to debuggers, silent exit monitoring can be enabled through GFlags and/or by directly modifying IFEO and silent process exit Registry values in <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\</code>. (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


