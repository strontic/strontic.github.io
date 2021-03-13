---
title: dbgrpc.exe | RPC Extended Debugging Utility
excerpt: What is dbgrpc.exe?
---

# dbgrpc.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgrpc.exe`
* Description: RPC Extended Debugging Utility

## Hashes

Type | Hash
-- | --
MD5 | `A69AFA400FF6F3CFD96BEB8F997EC2A1`
SHA1 | `1BB268EB9353BE4A7F7C344E34B6A17527216FF3`
SHA256 | `C532C4AFFA1F444472FF6E837FE5419FED36ECA57541E4015CAA21ADDBA69C05`
SHA384 | `67343D94ABC9AEF3408764FB5A261063CD786AB6773ACC4FC098A9C48A7F7EC87AC9EEEFCC407B31068CFC600B9AC0B5`
SHA512 | `2D5FF90C58966C0D8116BBBA752EB9938B7D6A3EF43C0F118CD89E5C0799CACA2E1096A9F899118F4DE40142AE9DE100F2722B468FEF386F6E74C9D7546F061C`
SSDEEP | `384:RGUbHD9q4bzeWOVc/c14Xdv+/d6t51Q2sDjxts/CWIdWJIwGyvCCTluN:RrbTbiLyUpaKj0/sqIECCy`
IMP | `DC32ED141E304EB5A540B8285C4296B0`
PESHA1 | `519125F42C19C046965346E09A16DA9296DE7FE3`
PE256 | `F9D3358E2A27D89E4493F160C2F36A3A8BF4BCBF5126E35FDB1CF627245ADC50`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgrpc.exe: -s <server> -p <protseq> -C <CallID> -I <IfStart>
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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\dbgrpc.exe |
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

* Original Filename: RpcDbg.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown





MIT License. Copyright (c) 2020-2021 Strontic.


