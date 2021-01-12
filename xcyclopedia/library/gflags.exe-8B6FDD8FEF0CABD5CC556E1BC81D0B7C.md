---
title: gflags.exe | Microsoft NT Global Flags Manipulator
excerpt: What is gflags.exe?
---

# gflags.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\gflags.exe`
* Description: Microsoft NT Global Flags Manipulator

## Hashes

Type | Hash
-- | --
MD5 | `8B6FDD8FEF0CABD5CC556E1BC81D0B7C`
SHA1 | `19B5B811B6B72EB3747D46F6906FC216B9FBDFDD`
SHA256 | `FA1B9EA024C6C7FABE70063DBF5AF5C63A11C57E1B305BDB61A42596CC032E9A`
SHA384 | `8E1E2D47ED8DAB9A40A9BBC45D6551FC3C7804977D61506E46F741B9915F0D70CAA1F9D116F182D3DBF25800F38F3068`
SHA512 | `5C9E856A688EEF3A2322CD92EECDBC7D333E393C01B3A5FAF234A15A8369F38D53026153937B0A0DC45DE2E825A9A2A60320440E83A4903FA824EFEBA72D3362`
SSDEEP | `768:7PnlUMWZi2meQwB7kb9ijEbhI+ZZ3E1CgNk6zVTgs0tMMTmiVz04+u:Ln+QehYI4bhI+ZwCg390/T/Vzd`
IMP | `75F1792141528D908A41983417EE84F2`
PESHA1 | `D07590DB0425B6832BC8828B7D7FF6670C186A3F`
PE256 | `347750733BD21C8C42A738714194E6E12AA5F7DFE276789DE77AA80DC68A0ACF`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\gflags.exe |
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

* Original Filename: GFLAGS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/fa1b9ea024c6c7fabe70063dbf5af5c63a11c57e1b305bdb61a42596cc032e9a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\gflags.exe](gflags.exe-256EEDC52F3FFF7020F3286D5BA635A8.md) | 43

## Possible Misuse

*The following table contains possible examples of `gflags.exe` being misused. While `gflags.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can be set directly via the Registry or in Global Flags via the GFlags tool. (Citation: Microsoft GFlags Mar 2017) IFEOs are represented as <code>Debugger</code> values in the Registry under <code>HKLM\SOFTWARE{\Wow6432Node}\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\<executable></code> where <code>&lt;executable&gt;</code> is the binary on which the debugger is attached. (Citation: Microsoft Dev Blog IFEO Mar 2010) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | IFEOs can also enable an arbitrary monitor program to be launched when a specified program silently exits (i.e. is prematurely terminated by itself or a second, non kernel-mode process). (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) Similar to debuggers, silent exit monitoring can be enabled through GFlags and/or by directly modifying IFEO and silent process exit Registry values in <code>HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\SilentProcessExit\</code>. (Citation: Microsoft Silent Process Exit NOV 2017) (Citation: Oddvar Moe IFEO APR 2018) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


