---
title: dbengprx.exe | Microsoft Windows Debugger Transport Proxy Server
excerpt: What is dbengprx.exe?
---

# dbengprx.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbengprx.exe`
* Description: Microsoft Windows Debugger Transport Proxy Server

## Hashes

Type | Hash
-- | --
MD5 | `90E3A624B75BB6DFE21185A444F0E68C`
SHA1 | `3D13D9BD1362B64E55AF53D155D4A35DFA668DAD`
SHA256 | `7B20AA2BAFA06805C8B827CDC80A680FC7E6D2A56C539EB95F684FE131564115`
SHA384 | `F5219328BC9F4FD633FB23F89203D99CC0291D9BC586DC4715F1DF63A1F2570227D662EE9CB7624D8FBF480C3083C6F3`
SHA512 | `7D65210F3011E2FB2FB3012C74205A6E9965AB63C0DF89BBF5578754185675E4D23566F1DCC879F0E42F3976459544A07B7FBB588D5E6C7390E20A643EAC7685`
SSDEEP | `1536:vOmoWWTuaPhD2GWmLbOhCl9Hg7AxUApY/0WkrtIyoG6Kin/1rcdv:WmoWWTuaPvxVHMYGkrEGbin/1rc`
IMP | `7388D969348BFF044602F6C4C8F478D9`
PESHA1 | `001742D9CABE3A2DBEBA14E1CBAB7E582B97657E`
PE256 | `602A6E9CE78F6C4542C964BE18C3A21BD8A23815C9AC9F6C0193272DFA0A2ACE`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbengprx.exe |
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

* Original Filename: dbengprx.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\dbengprx.exe](dbengprx.exe-19635FE581E85E6D5A006C2B96C0AA83.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\kdbgctrl.exe](kdbgctrl.exe-8B7FABEC2F39E2B008AF214729E02B03.md) | 30
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\kdsrv.exe](kdsrv.exe-F3DE7A8CF47EA326CA0FDB114288A42F.md) | 29
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\srcsrv.dll](srcsrv.dll-AAC597DA6A2F14113669DC4B5AFC5F2C.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\srcsrv\srcsrv.dll](srcsrv.dll-CF86385CFDBC9EE731F62CA639600D68.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kdbgctrl.exe](kdbgctrl.exe-30B54B17E08EC8E07B8AF7E4B73AF74A.md) | 29
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kdsrv.exe](kdsrv.exe-583B05D3B0756D346D0EE95D64105FB1.md) | 27
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv.dll](srcsrv.dll-E57E4A243226C83D8640341369E8C3DF.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\srcsrv\srcsrv.dll](srcsrv.dll-7A145B96713C75BB870D13B6D651EB06.md) | 38




MIT License. Copyright (c) 2020-2021 Strontic.


