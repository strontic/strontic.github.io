---
title: MBR2GPT.EXE | 
excerpt: What is MBR2GPT.EXE?
---

# MBR2GPT.EXE 

* File Path: `C:\Windows\system32\MBR2GPT.EXE`

## Hashes

Type | Hash
-- | --
MD5 | `FFA7448C64B359D176256F313E8A4C44`
SHA1 | `B1C94DC0E8493DF6690BD79CF1338F9143A2F599`
SHA256 | `AEC30F1A41779734895A54503D3151C727D584454BA320E1C0A7270375A4832A`
SHA384 | `0EA359B22FBC410665AB574DE6F88B9015D091C90922968A596525AC112FE82ED6BF746A2547379C6A95546D11E67367`
SHA512 | `1E0453EF2DA4FEC878C0AB5056FB064A05DD46996BB761CAF2EC6D1F82B2239E247E2E0B817DFCFBB7A964F4101342F09668AE1F8E40DAEF5E82C2746182E7AC`
SSDEEP | `12288:rohI+WFpFLQ8AqGZAGGYGaZvtgbQ9bAXfL+7oqM5PYhrv+gVcuq4tWZiT0cgfD7a:EhIf1SqyAnnhS7oqMlSygGuq4t+1D7a`
IMP | `D9311FE666B004EAC7209E9F97EC1B5A`
PESHA1 | `837C8E77231B469C7F3E8CEF88D8776AE7CFA576`
PE256 | `910ED325E6F21271FB328FB5A48F00C19E142631B358E7BFE2689A5D1D612017`

## Runtime Data

### Usage (stdout):
```cmhg

Converts a disk from MBR to GPT partitioning without modifying or deleting data on the disk.

MBR2GPT.exe /validate|convert [/disk:<diskNumber>] [/logs:<logDirectory>] [/map:<source>=<destination>] [/allowFullOS]

Where:

 /validate
         - Validates that the selected disk can be converted
           without performing the actual conversion.

 /convert
         - Validates that the selected disk can be converted
           and performs the actual conversion.

 /disk:<diskNumber>
         - Specifies the disk number of the disk to be processed.
           If not specified, the system disk is processed.

 /logs:<logDirectory>
         - Specifies the directory for logging. By default logs
           are created in the %windir% directory.

 /map:<source>=<destination>
         - Specifies the GPT partition type to be used for a
           given MBR partition type not recognized by Windows.
           Multiple /map switches are allowed.

 /allowFullOS
         - Allows the tool to be used from the full Windows
           environment. By default, this tool can only be used
           from the Windows Preinstallation Environment.


```

### Usage (stderr):
```cmhg
Invalid argument: --help

Invalid arguments


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MBR2GPT.EXE |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/aec30f1a41779734895a54503d3151c727d584454ba320e1c0a7270375a4832a/detection





MIT License. Copyright (c) 2020 Strontic.


