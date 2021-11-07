---
title: junction.exe | Creates and lists directory links
excerpt: What is junction.exe?
---

# junction.exe 

* File Path: `C:\SysinternalsSuite\junction.exe`
* Description: Creates and lists directory links

## Hashes

Type | Hash
-- | --
MD5 | `D53E00822AF1527611E5E5C5CE588678`
SHA1 | `1FBE93056A0458EEFD02B29436FEAA1CF85553D7`
SHA256 | `6FB4DF6555A69C2F3C117764D33B48803AE19A8BA40B12F3211195247D9C508F`
SHA384 | `F462D0F2C3B8A0722CC98ECE8D52289A27C34FA7F46C72B2008D17B8A5155CD023CF32230F0D7873C357CBC0C11F496A`
SHA512 | `58D7D61AD03E8AA5720B65D1B12C004B6C5E3567E5720D4F9B6FAE73BD10000CEA12CF88789E83093744358F49734AB81DC2434EAE14074574DEC2AEF57FB5F8`
SSDEEP | `6144:XslFpnG9A1eWOKKi6/s6AoPgwIV1+z576LfzayKMkeL4:+FpJ1eWOjiCs/mQVc9g1keL4`
IMP | `D252BDC4EC1867967C54FF17556BA9AA`
PESHA1 | `1F856785DFDB52856ED98EC22F18E4D255796E1E`
PE256 | `DA3B0D6EE341226394B14E8CC2C1AB5AD1F3C52E6ADA0873E3FEADC2DA537D78`

## Runtime Data

### Usage (stdout):
```cmhg

Junction v1.07 - Creates and lists directory links
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

The first usage is for displaying reparse point information, the
second usage is for creating a junction point, and the last for
deleting a junction point:
usage: C:\SysinternalsSuite\junction.exe [-s] [-q] <file or directory>
       -q     Don't print error messages (quiet)
       -s     Recurse subdirectories

usage: C:\SysinternalsSuite\junction.exe <junction directory> <junction target>
       example: junction d:\link c:\windows

usage: C:\SysinternalsSuite\junction.exe -d <junction directory>

Common Options:
       -nobanner    Do not display the startup banner and copyright message.
       -accepteula  Suppress the display of the license dialog and accept the EULA.

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\junction.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/6fb4df6555a69c2f3c117764d33b48803ae19a8ba40b12f3211195247d9c508f/detection/


## Possible Misuse

*The following table contains possible examples of `junction.exe` being misused. While `junction.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "The Windows module loader can be instructed to load DLLs from arbitrary local paths and arbitrary Universal Naming Convention (UNC) network paths. This functionality resides in NTDLL.dll and is part of the Windows Native API which is called from functions like CreateProcess(), LoadLibrary(), etc. of the Win32 API. (Citation: Wikipedia Windows Library Files)\n\nThe module loader can load DLLs:\n\n* via specification of the (fully-qualified or relative) DLL pathname in the IMPORT directory;\n    \n* via EXPORT forwarded to another DLL, specified with (fully-qualified or relative) pathname (but without extension);\n    \n* via an NTFS junction or symlink program.exe.local with the fully-qualified or relative pathname of a directory containing the DLLs specified in the IMPORT directory or forwarded EXPORTs;\n    \n* via <code>&#x3c;file name=\"filename.extension\" loadFrom=\"fully-qualified or relative pathname\"&#x3e;</code> in an embedded or external \"application manifest\". The file name refers to an entry in the IMPORT directory or a forwarded EXPORT.\n\nAdversaries can use this functionality as a way to execute arbitrary code on a system.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "The Windows module loader can be instructed to load DLLs from arbitrary local paths and arbitrary Universal Naming Convention (UNC) network paths. This functionality resides in NTDLL.dll and is part of the Windows Native API which is called from functions like CreateProcess(), LoadLibrary(), etc. of the Win32 API. (Citation: Wikipedia Windows Library Files)\n\nThe module loader can load DLLs:\n\n* via specification of the (fully-qualified or relative) DLL pathname in the IMPORT directory;\n    \n* via EXPORT forwarded to another DLL, specified with (fully-qualified or relative) pathname (but without extension);\n    \n* via an NTFS junction or symlink program.exe.local with the fully-qualified or relative pathname of a directory containing the DLLs specified in the IMPORT directory or forwarded EXPORTs;\n    \n* via <code>&#x3c;file name=\"filename.extension\" loadFrom=\"fully-qualified or relative pathname\"&#x3e;</code> in an embedded or external \"application manifest\". The file name refers to an entry in the IMPORT directory or a forwarded EXPORT.\n\nAdversaries can use this functionality as a way to execute arbitrary code on a system.",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


