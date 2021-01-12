---
title: umdh.exe | NT Security Test- UMDH
excerpt: What is umdh.exe?
---

# umdh.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\umdh.exe`
* Description: NT Security Test: UMDH

## Hashes

Type | Hash
-- | --
MD5 | `A9B13D96A16154B1E7B82F823B6A5182`
SHA1 | `DE5B3BDE4D0E134B9AB9AB1462D71BDA6B0A6EEC`
SHA256 | `B608A4FFBF5E68F47992F22F69DDFC07E18E8858DC3C56A8E77A1577DAEFAE78`
SHA384 | `052B947F1FF8908D673F91DE1B25164A7BF3F7A12AF02B0F795A137DB6C15AD05157A0B2991F6E597CCC3DF143FB1F9B`
SHA512 | `0F4FEB10F917311AFD1906274D2640400972D3F659D4E4069317099ED5938DF13C00BD39517688A1088683A82F849465F8476F2F48BC1ABA4D5D4FD3844F2879`
SSDEEP | `1536:gH7vJgA+biyjpOTJ8hMXBzIWv0XxdEgU:iJgA0jpOTkWBIk0rEgU`
IMP | `5936EEEFB448F0EE7ABF50CCDA83543E`
PESHA1 | `A5CE2C91C7E212A212AEB5C61DADD0FB1E69A1F6`
PE256 | `70547A9C01EFF36C409DD51E878EDED8CB3AB5F59C6543B4233B648AFEDF1379`

## Runtime Data

### Usage (stdout):
```cmhg
// _NT_SYMBOL_PATH set by default to C:\Windows\symbols
// Debug library initialized ...
//                                                                          
// Each log entry has the following syntax:                                 
//                                                                          
// + BYTES_DELTA (NEW_BYTES - OLD_BYTES) NEW_COUNT allocs BackTrace TRACEID 
// + COUNT_DELTA (NEW_COUNT - OLD_COUNT) BackTrace TRACEID allocations      
//     ... stack trace ...                                                  
//                                                                          
// where:                                                                   
//                                                                          
//     BYTES_DELTA - increase in bytes between before and after log         
//     NEW_BYTES - bytes in after log                                       
//     OLD_BYTES - bytes in before log                                      
//     COUNT_DELTA - increase in allocations between before and after log   
//     NEW_COUNT - number of allocations in after log                       
//     OLD_COUNT - number of allocations in before log                      
//     TRACEID - decimal index of the stack trace in the trace database     
//         (can be used to search for allocation instances in the original  
//         UMDH logs).                                                      
//                                                                          



Total decrease ==      0 requested +      0 overhead =      0

```

### Usage (stderr):
```cmhg
                                                                               
     UMDH                                                                      
                                                                               
MODE 1                                                                         
                                                                               
  umdh {-p:Process-id|-pn:ProcessName} [-f:Filename] [-g]                      
                                                                               
    Creates a dump of the heap allocations.                                    
                                                                               
    -p  Indicates the Process-ID to examine.                                   
    -pn Indicates the Process name to examine.                                 
    -f  Indicates output file.                                                 
    -g  Dumps the heap blocks which have no references in the process.         
                                                                               
MODE 2                                                                         
                                                                               
  umdh [-d] {File1} [File2] [-f:Filename]                                      
                                                                               
     Compares two dumps and resolves the symbols.                              
                                                                               
    -d  Output in decimal (default is hexadecimal)                             
    -f  Indicates output file.                                                 
                                                                               
EXAMPLE:                                                                       
                                                                               
    -1- umdh.exe -pn:application_name.exe -f:FirstDump.txt                     
    -2- ... exercise the application                                           
    -3- umdh.exe -pn:application_name.exe -f:SecondDump.txt                    
    -4- umdh.exe FirstDump.txt SecondDump.txt -f:Result.txt                    
           Compares allocations from the two dumps.                            
                                                                               
    umdh.exe Dump.txt                                                          
           Investigate a single dump.                                          
                                                                               
NOTES:                                                                         
                                                                               
    Uses the dbghelp library to resolve symbols                                
    therefore _NT_SYMBOL_PATH must be set appropriately.                       
                                                                               
                                                                               

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\umdh.exe |
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

* Original Filename: UMDH.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/b608a4ffbf5e68f47992f22f69ddfc07e18e8858dc3c56a8e77a1577daefae78/detection





MIT License. Copyright (c) 2020 Strontic.


