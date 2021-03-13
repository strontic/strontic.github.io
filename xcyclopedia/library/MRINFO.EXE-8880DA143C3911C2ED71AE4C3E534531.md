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
MD5 | `8880DA143C3911C2ED71AE4C3E534531`
SHA1 | `5FCE5C7D3F1F077141889E407348DA4706D85C31`
SHA256 | `59EEA6E8904771A620559EC4F55AED2CA0F5BCF9B14C6D030301F165AA59EB2C`
SHA384 | `94BE9F7996021FC719F1CF81093395B42DDAA793149827C0ED57F289CE74950209273B0A23E9C2DAD6C923350CD638A7`
SHA512 | `00A0318225F59DDE6E1489655B81B609A53034C32E197F96B60C25D731847ACF363E6E82302C0FA2ACAF8581A318ECACF4FAE9CAD6DDAAF374EFCA30A815A073`
SSDEEP | `384:YFt53LJeMkQ6QknlMFwoDomCCmNKMfyPEHsWe8W:YrBrkT8huCmNKMfjH4`
IMP | `293E4CA0CECE9CF71F0DB8AA9DCA02F6`
PESHA1 | `FC22C045AF29EAA62E62CF92A0ABB21DF702EC3E`
PE256 | `7112895823DFA9518BDBCD62173904100AFE11324A47299BBEA8979193B2A5A5`

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
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MRINFO.EXE |
C:\Windows\SYSTEM32\ntdll.dll |


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/59eea6e8904771a620559ec4f55aed2ca0f5bcf9b14c6d030301f165aa59eb2c/detection





MIT License. Copyright (c) 2020-2021 Strontic.


