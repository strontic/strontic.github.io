---
title: MRINFO.EXE | Multicast Information
excerpt: What is MRINFO.EXE?
---

# MRINFO.EXE 

* File Path: `C:\WINDOWS\system32\MRINFO.EXE`
* Description: Multicast Information

## Hashes

Type | Hash
-- | --
MD5 | `32CE8ED607CFCDAA930E14C9A0686F86`
SHA1 | `3AA00DEDB88E5986B15B1C0040A71312A95D0A90`
SHA256 | `4214609049B89F27930A8B9BCF40B7565C99F012C52AE0B8FE1E8C9181F2EACA`
SHA384 | `CB344B8ED531AB2F1A27D144C87E9B2DE21502D9FF4BE7CB16AA5E7774C8DE53900358F18EC3F3D855555D7B279D96D7`
SHA512 | `DD87CD573B9D8E4A66BE9349F40295480E11A310F3BE865D87471C98F6B6BE04AF2E0CB82512058E523F2704DE49E829E516BB28137822D3346ADE1FA298354F`
SSDEEP | `384:ZSgdrCKZPbDZFWsHLeViRPaVaLRUWd8W:ZSgkUbVFWKbSVaLRP`
IMP | `5C469A86BBF49E6E0233EE6DD4B37AAA`
PESHA1 | `CB32FE04F54BD37B0EAE8505D0994B0B32F0D3BF`
PE256 | `58F4F215F7893E0EDF3F95F8CAED86E8037588FA79BE145B324A88C9FF42A0A8`

## Runtime Data

### Usage (stdout):
```cmhg

Usage: mrinfo [-n?] [-i address] [-t secs] [-r retries] destination
       
 -n           Display IP addresses in numeric format
 -i address   Address of local interface to send query out
 -t seconds   Timeout in seconds for IGMP queries (default = 3 seconds) 
 -r retries   Number of extra times to send the SNMP queries (default = 0)         
 -?           Print Usage
 destination  Address or name of destination


```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows\System32 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\MRINFO.EXE |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/4214609049b89f27930a8b9bcf40b7565c99f012c52ae0b8fe1e8c9181f2eaca/detection





MIT License. Copyright (c) 2020-2021 Strontic.


