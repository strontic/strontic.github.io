---
title: junction64.exe | Creates and lists directory links
excerpt: What is junction64.exe?
---

# junction64.exe 

* File Path: `C:\SysinternalsSuite\junction64.exe`
* Description: Creates and lists directory links

## Hashes

Type | Hash
-- | --
MD5 | `A87678BBF8F7752A85ECA00BA3FC6775`
SHA1 | `7F57A7E6F18FF5D70C38A24737AA2817FBD5C85E`
SHA256 | `98720D8675036560545DB93DA0427B46361F565F7F517F77C11DB7F72D9C8CDD`
SHA384 | `49CB646DFA274366CC95F18116E43DD8B583F8475DA7DA47A05BF35F1F4DAD44BCEDF025FF046872DC8030A7EFCD9295`
SHA512 | `42556EDC0CFF7637253EDBF14B53340773633A4512277CAD346C3D5A64B0780AF8EF730466923456021CC08B7DC32F94F8D46215908D36A95DE96121B9D489CB`
SSDEEP | `6144:feZVqF4bIm19CIB8R8+2EHMw/Qi2LvRJoT3wVAg8SoWbEXuufCuRhyv65jEK:aV07mg2EHMw/Qi2LvQTgVEpfJ3/`
IMP | `88D0A5152AC5965C1C0CC39BE43F6F87`
PESHA1 | `0A85F457C3084B248C1D7874D68A80B7A31B8FD4`
PE256 | `764BCDEC61F32F1044CF917539B87122E044D929A0020E1DA1AF580C3F2FBF9A`

## Runtime Data

### Usage (stdout):
```cmhg

Junction v1.07 - Creates and lists directory links
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

The first usage is for displaying reparse point information, the
second usage is for creating a junction point, and the last for
deleting a junction point:
usage: C:\SysinternalsSuite\junction64.exe [-s] [-q] <file or directory>
       -q     Don't print error messages (quiet)
       -s     Recurse subdirectories

usage: C:\SysinternalsSuite\junction64.exe <junction directory> <junction target>
       example: junction d:\link c:\windows

usage: C:\SysinternalsSuite\junction64.exe -d <junction directory>

Common Options:
       -nobanner    Do not display the startup banner and copyright message.
       -accepteula  Suppress the display of the license dialog and accept the EULA.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\junction64.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: junction.exe
* Product Name: Sysinternals Junction
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.07
* Product Version: 1.07
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2016 Mark Russinovich
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/98720d8675036560545db93da0427b46361f565f7f517f77c11db7f72d9c8cdd/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


