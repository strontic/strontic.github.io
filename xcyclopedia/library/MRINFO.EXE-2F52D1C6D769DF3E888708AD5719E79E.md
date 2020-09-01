---
title: MRINFO.EXE | Multicast Information
---

# MRINFO.EXE 

* File Path: `C:\Windows\SysWOW64\MRINFO.EXE`
* Description: Multicast Information

## Hashes

Type | Hash
-- | --
MD5 | `2F52D1C6D769DF3E888708AD5719E79E`
SHA1 | `8C6A94E92D830F4909B19120E4DAE52C610891C4`
SHA256 | `FC150516EC51B4AAA09A85057ECD7645D3BA3A3E34E6863862BA463146383BC9`
SHA384 | `D9E6227153F58528AFDD18EE9EC6CAC4831C140FA1CAF65AD3A1B53EBD0B908BB168ADF47D1E6CE5602A994B5AEFD63D`
SHA512 | `0C4B369982844BF248719801FB76665596BDC7B7BBD3425BE2A0C70211A457FDEB21B3BC551B150D3E57232E4C2BA8840639AC3358C5C20F7256DB8D9963CBD6`
SSDEEP | `192:wdlljMosoQAFqysjhdbXI2PTGpLq5Wvc14S5SDGVkH0Wd8WqSX8Q:WMVobFJ+hlXxbG/zS5qTUWd8WD`

## Runtime Data

### Usage (stdout):
```Batchfile

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\mpnotify.exe |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


