---
title: MRINFO.EXE | Multicast Information
excerpt: What is MRINFO.EXE?
---

# MRINFO.EXE 

* File Path: `C:\Windows\system32\MRINFO.EXE`
* Description: Multicast Information

## Hashes

Type | Hash
-- | --
MD5 | `E770C27BF6BF43B7F9796511CF6361F2`
SHA1 | `21CA4B8CC54479095E817ED8B8355454011F70AF`
SHA256 | `20BB1370F14AD18C0AD78BD2C16FAE467CA9912F31EE77352C87BC5CBAD38206`
SHA384 | `333CB3D21C62AF132C10ECF22E74F8B1AE055F649EE88CCE4BC296312D2A69D7974F19EB6145785F96DD588CCA24A4C6`
SHA512 | `3E386BC86C6C5A41AB92BF26DAD288EABD40E3AA343AF65BA281E9BB9EB3FF576D6A9C2CCDFCE08330D8D6EF7E6223686B4A86E6C483A95CDD66DD6A895989F4`
SSDEEP | `384:YBezrKfXxCcqJKYAfGPiUl13MfyPiK0WJ8W:YEsX8gNful13Mf5Kb`
IMP | `293E4CA0CECE9CF71F0DB8AA9DCA02F6`
PESHA1 | `430F64F08B0D695918E85801672AC6E58CD4CC41`
PE256 | `20122AFF5D6A3DE5DE04C252C1D45EA15B20653F2B52CD9EDE59CC8FADAAC0B5`

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
csrss.exe winlogon.exe conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\DNSAPI.dll |
C:\Windows\SYSTEM32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MRINFO.EXE |
C:\Windows\System32\msvcrt.dll |
C:\Windows\System32\mswsock.dll |
C:\Windows\System32\NSI.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/20bb1370f14ad18c0ad78bd2c16fae467ca9912f31ee77352c87bc5cbad38206/detection/





MIT License. Copyright (c) 2020 Strontic.


