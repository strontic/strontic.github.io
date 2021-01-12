---
title: dbengprx.exe | Microsoft Windows Debugger Transport Proxy Server
excerpt: What is dbengprx.exe?
---

# dbengprx.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbengprx.exe`
* Description: Microsoft Windows Debugger Transport Proxy Server

## Hashes

Type | Hash
-- | --
MD5 | `CDB45C99D88514AEF61951A476E90FA8`
SHA1 | `8909E36F7DF4D607CEF27D68D113DE3C537DC3B0`
SHA256 | `0D535A4065BA70EF55D2C996F1AE1D7EC07FF90FF955067EEA9D8F6D411C44E7`
SHA384 | `A47CB873EDDF46CD09FB314D9D7D9DCD9131CF1AB8CB2BCF9AC335E39B5231E166478DE8DB5EF617658E6523E449CD94`
SHA512 | `A3863994FCF0770C8A9B48C78A356B6706FA65B989D4439579DD19A035602A2F93F14B08FF5DA874A0420764F85534502DE7779EF3F068CAF3067E2D6BF49CD2`
SSDEEP | `3072:sNrYdnUBMOXYR1UjJLbzmpmTeKNtKWoSJlIqarNl:sNrDM8UUVXamlIqar`
IMP | `FFD1762CC41F187D04C2E43B1563CE2F`
PESHA1 | `F3654EB9615975E0D4E1E470A0EA57952AE42070`
PE256 | `56AA7BA628AF65B80D901997D46136A684EDE59EA2B1A9E3B4CB4347913928C8`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid Command Line: Usage: dbengprx [-p] -c <transport> -s <transport>
       transport: tcp | npipe
           for tcp use: port=<socket port #>
           for npipe use: pipe=<name of pipe>

Example: machine A = server, B = proxy, C = client
    A: start cdb -server tcp:port=1234 <...>
    B: start dbengprx -c tcp:port=1234,server=A -s tcp:port=1235
    C: start cdb -remote tcp:port=1235,server=B

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbengprx.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dbengprx.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/0d535a4065ba70ef55d2c996f1ae1d7ec07ff90ff955067eea9d8f6d411c44e7/detection





MIT License. Copyright (c) 2020 Strontic.


