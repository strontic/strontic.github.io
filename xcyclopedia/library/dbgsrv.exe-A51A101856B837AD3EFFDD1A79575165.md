---
title: dbgsrv.exe | Microsoft User-Mode Debugger Process Server
excerpt: What is dbgsrv.exe?
---

# dbgsrv.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgsrv.exe`
* Description: Microsoft User-Mode Debugger Process Server

## Hashes

Type | Hash
-- | --
MD5 | `A51A101856B837AD3EFFDD1A79575165`
SHA1 | `FA3823ACDC8ADBADEF06B4D4A906F75CD1347899`
SHA256 | `AFB9FBCF0EBB2789BC0B59CFDFAB144B5DF8FF1FCED15D472A9C4DC506146E38`
SHA384 | `D53E96D869596E3FD6F1D3592522E0DC47E4BCB1655014FF637E845090C8F4BC922006DB75D9D07B94B5CE4CD00DF3CF`
SHA512 | `4A147A01725E0C82076A88DB8F34068A2B4E87F580815F9F840F306C2D67BBFED2050CFEA6B65EA59F00C784B0349CA347E18ECD394A202FEBCCFDE9D11C0846`
SSDEEP | `768:ymoW4gP2TuaMgthdufu7EdEpSOWP5Wwt6Xc85qkQ+Ejd0Cc:ymoWATuajvv7EdEoOS5WwttkQdm`
IMP | `97692A2CA1616DD5AF6732FB35BA7360`
PESHA1 | `22E50190347B37A1B287932DB7FA55547E994D97`
PE256 | `972699F2911147842012310FB5DB0C6004ADE960749CE37C86EFE97A74BF8AEF`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid Command Line: Usage: dbgsrv -t <transport> [-sifeo <image.ext>] [-x] [-c[s] <args...>] [-pc <args...>]
       transport: tcp | npipe | ssl | spipe | 1394 | com | hyperv 
           for tcp use: port=<socket port #>
           for npipe use: pipe=<name of pipe>
           for 1394 use: channel=<channel #>
           for com use: port=<COM port>,baud=<baud rate>,
                        channel=<channel #>
           for hyperv use: vmid=<vm id GUID>,serviceid=<service id GUID>
           for ssl and spipe see the documentation

Example: dbgsrv -t npipe:pipe=foobar

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgsrv.exe |
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

* Original Filename: dbgsrv.exe
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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\dbgsrv.exe](dbgsrv.exe-5343914AF3737258C825B5F3BBD943A3.md) | 38




MIT License. Copyright (c) 2020 Strontic.


