---
title: wpaexporter.exe | Windows Performance Analyzer
excerpt: What is wpaexporter.exe?
---

# wpaexporter.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpaexporter.exe`
* Description: Windows Performance Analyzer

## Hashes

Type | Hash
-- | --
MD5 | `53DE1C9E113BEFB76CFBB87C39482701`
SHA1 | `68CF10102FC6283F4E5571DA82C003C7BB034173`
SHA256 | `ADACD487B34A2F6BA9B5994ADC745D64B84717FE478A85DB9BFB1A61E6653C8A`
SHA384 | `2D952AFFBA9251CE8805F0966D8E4216AEAEE37ED1B531ADA980ECC0445775608B5FBF11016D42E7C6ACCFD9D39016E2`
SHA512 | `F51731DE1B14A4F1C36A863F1E885D49A56185EA9DF664B28A357A4772065676FA388FDBE65D1083027672C604CA988B8684F81DC78D3701A276CD2936061818`
SSDEEP | `3072:1TerEHkU0SiT7gGAs1PqlKN/vwvIazOv5eTg:JHkU0Z1Pqw6vh+yg`
IMP | `n/a`
PESHA1 | `8319EE8741872FF437AE77280A26C6C3399AC4F8`
PE256 | `B29E8DB1360AA401CD17C4EE0E7BFF4D096DDB7F6F37DA87C05C9005EF9B1D57`

## Runtime Data

### Usage (stdout):
```cmhg
Microsoft (R) Windows Performance Analyzer Version 10.0.19041.1 (WinBuild.160101.0800)
Copyright (C) 2021 Microsoft Corporation.  All rights reserved.

Usage:

    wpaexporter.exe <<[-i] <trace.etl> [trace specific options]> -profile profile.wpaProfile> ... [general options] 
    wpaexporter.exe -exporterconfig <config_file> [general options] 

                             -INPUT FILE OPTIONS-

    -profile <profile.wpaprofile>    WPA profile containing the tables to export,
                                     as well as any optional regions XML or stack
                                     tags files.
    -exporterconfig <config_file>    A configuration file describing the traces
                                     and profiles to export

                           -TRACE SPECIFIC OPTIONS-

    -slot <m>         Assigns the trace to profile slot m, where m is an
                      integer.
    -range <T1 T2>    Zoom to time range [T1,T2]. If units are not specified,
                      then the units are assumed to be nanoseconds.
                          Example: -range 10s 20s
                          Example: -range 5 15

    -marks <name1> <name2>    Zoom to the time range which starts at the first
                              mark and ends at the second mark.
    -region <name>    Zoom to the time range defined by a region.

                              -GENERAL OPTIONS-

    -delimeter <char>    Character to use as a separator between values in the
                         CSV. Defaults to , (comma)
    -prefix <prefix>     String to prepend to all the output filenames.
    -outputfolder <folder>    Folder to which to output the exported tables.
    -symbols             Enable symbol loading.
    -symcacheonly        Symbol loading only uses existing symcache files.
    -sysconfig <table>,...    Export System Configuration tables
    -h, /?               Display help screen.


```

### Usage (stderr):
```cmhg
No data to export was specified

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpaexporter.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wpaexporter.exe
* Product Name: Microsoft Windows Performance Analyzer
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  2019 Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/adacd487b34a2f6ba9b5994adc745d64b84717fe478a85db9bfb1a61e6653c8a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\wpa.exe](wpa.exe-F7BF05BE5FD192120CF8390AF1A84EED.md) | 44




MIT License. Copyright (c) 2020 Strontic.


