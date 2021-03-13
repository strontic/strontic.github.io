---
title: kdnet.exe | Net debugging configuration tool
excerpt: What is kdnet.exe?
---

# kdnet.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kdnet.exe`
* Description: Net debugging configuration tool

## Hashes

Type | Hash
-- | --
MD5 | `BA2F9DB032F5CE7341625A810A115474`
SHA1 | `02244155ED4C367F3513A6117117900EC0395433`
SHA256 | `CF70EC7740426FA7DBA91C505C9F8A510BE65180451278B64A94970B93ABEBA4`
SHA384 | `A628491D77459B6672D9FC63395D97E988A20136F190D8D6262BA6A2B889F8BB753143D44DC05F17C6C0D6114A0C4CCD`
SHA512 | `6BF758DDB093A290670D9FB6FD01549DCB27577C8F909D7026A4A49A50C1F6E3CE34EE77DFF9E2701C239D2E1BC481A89053505A0B5BF6F9EAE40E35847B251C`
SSDEEP | `768:fmb5ZFGtbawzNjFITc0YkMY6vw+3Vl86aEr:f2ZmDzN70YJRvw+3Vl82r`
IMP | `A222286A15F27F406532CE0FEDEFB706`
PESHA1 | `E7B9C9A737A03E1F900AAB1FEDEB2DE4424FD4DB`
PE256 | `4C94BD80B29E640EF30FC1171C8B04385EBC9A79C4D4F2CD125F4A76F785A238`

## Runtime Data

### Usage (stdout):
```cmhg

kdnet.exe [debug_host] [debug_port]
  [debug_host] is the name of the host machine running the debugger.
  [debug_port] is the network port to use for debugging this machine.

kdnet.exe /xml

kdnet.exe /busparams [debug_device] [debug_host] [debug_port]
  [debug_device] is the busparams of the debug Device to configure.
  [debug_host] is the name of the host machine running the debugger.
  [debug_port] is the network port to use for debugging this machine.

When run without parameters, kdnet.exe identifies the NICs and USB3
controllers which support network debugging. When run with parameters
kdnet.exe enables network debugging using the specified information.
If [debug_port] is not specified then it will be set to a default
value of 5364.

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kdnet.exe |
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

* Original Filename: kdnet.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/cf70ec7740426fa7dba91c505c9f8a510be65180451278b64a94970b93abeba4/detection





MIT License. Copyright (c) 2020-2021 Strontic.


