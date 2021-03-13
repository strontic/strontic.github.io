---
title: dbgrpc.exe | RPC Extended Debugging Utility
excerpt: What is dbgrpc.exe?
---

# dbgrpc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgrpc.exe`
* Description: RPC Extended Debugging Utility

## Hashes

Type | Hash
-- | --
MD5 | `7B1170DF9EC45B45FD8B3CC3276FD805`
SHA1 | `8EDDDB617A53663B72629C04A70C266F3AB1B55A`
SHA256 | `60BAE2D1F4244411FF0E1ED4224EE54BC78C10BCA84407DEBF28C35B9A110C52`
SHA384 | `C9CE68548C6EA11F7BD2F5487FFA4862A35F2B198121ADE309F7E360C408FC7910703A0FBC048D4069CD0888F1E3D41C`
SHA512 | `EDD7AA08A7653235189F55A68C0858AA41A02AED0E5C6022206A1C4D22BAA8F8CF871FC8CB8543004680C618F4DD9BD9B973A2BD4084E9AF12DCB8B0071E2C57`
SSDEEP | `384:6ZakfbPGxN4BrVsY3knZM6PR5VkSSuv25vXZ4lrOo6MSzGUGjOmrYR/6XiaWIdWD:67fqxN4fV3u1jVaxRX+jMLK7y6Xi0Ex`
IMP | `9BE6C040F9ECFCF8EBDA4E75601DE412`
PESHA1 | `182D013CF697FC1C725DF04EAF3F30281232A06A`
PE256 | `ECA3199B2313888629C1E9DC2BD3765E635946E8ECF3AEDDC3CAE69456363D8D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgrpc.exe: -s <server> -p <protseq> -C <CallID> -I <IfStart>
-N <ProcNum> -P <ProcessID> -L <CellID1.CellID2>
-E <EndpointName> -T <ThreadID> -r <radix> -c -l -e -t -a
Exactly one of -c, -l, -e, -t, or -a have to be specified.
The valid combinations are:
-c [-C <CallID>] [-I <IfStart>] [-N <ProcNum>] [-P <ProcessID>]
-l -P <ProcessID> -L <CellID1.CellID2>
-e [-E <EndpointName>]
-t -P <ProcessID> [-T <ThreadID>]
-a [-C <CallID>] [-I <IfStart>] [-N <ProcNum>] [-P <ProcessID>]
-s, -p and -r are independent to the other options. -r affects
only options after it on the command line. Default is 16 (hex)

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\dbgrpc.exe |
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

* Original Filename: RpcDbg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/60bae2d1f4244411ff0e1ed4224ee54bc78c10bca84407debf28c35b9a110c52/detection





MIT License. Copyright (c) 2020-2021 Strontic.


