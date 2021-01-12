---
title: umdh.exe | NT Security Test- UMDH
excerpt: What is umdh.exe?
---

# umdh.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\umdh.exe`
* Description: NT Security Test: UMDH

## Hashes

Type | Hash
-- | --
MD5 | `FA2FECB97CE3961E36892AFAB98DA840`
SHA1 | `AB8B34F91F87D384C350EC23EAA04F5938E34E03`
SHA256 | `62C0B8DA8F4F8632D48F8E4D8774F931CF86BB5F9D049969643A7824F37BF897`
SHA384 | `DEB0810BCEA83D5F9F99EC60D18D555D73F8305C215F7BD0C1E93DE520D58BFC5118404A1E1CE0ED0CB619D5178149BE`
SHA512 | `78D7F812B60F52803D85217919DC2BFD380B5CFFF0A157C3BA1198F3E24237D9726E1CCF39E25DE316FDAE7C145FEA979B37FB015224FDC7A581FC7259829517`
SSDEEP | `768:AfjX7tCfxz3hO4klCQbvvUEern2SMORpz/ZF8tFNhEQoExX6edAscX/4myGl:Arrsz3hOL1sTr2SMO3z/ZFMhFxdAsXE`
IMP | `B90E0F9B87800BC3438B2977A6C23A91`
PESHA1 | `4DBAA243DB5E3F704A864278A603592D4B454A54`
PE256 | `48725FF4BD6153027DAD82DAFAD7CA6696D21452CEF65371850DB4D8E386B6BB`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\umdh.exe |
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

* Original Filename: UMDH.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a





MIT License. Copyright (c) 2020 Strontic.


