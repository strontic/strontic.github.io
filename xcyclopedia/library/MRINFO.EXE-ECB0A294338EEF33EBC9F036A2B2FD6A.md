---
title: MRINFO.EXE | Multicast Information
---

# MRINFO.EXE 

* File Path: `C:\Windows\SysWOW64\MRINFO.EXE`
* Description: Multicast Information
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `ECB0A294338EEF33EBC9F036A2B2FD6A`
SHA1 | `3FB50537FB008A27B92CAACF0C5251BE9E6280A0`
SHA256 | `7442C2AD1EB752832FB6D4F6AD0E66C8163A055D27CCF894F65ADB8441D4F2D2`
SHA384 | `F7AFB386266DE5BB09FBEECCCE0B92FDA1D86FB4D70B14294C6D9B9D0FC26E46A96AC9F66E6EB62309B28F3EE160215D`
SHA512 | `E69CDDC46FFF47BFFAD50AD43F1BD5EA55A18B33E0DA4E414F211F0411DF095226B832FBE2D20822BF55D15FBB78F742D5A3FE2864C916FD516594B3F9A5C432`
SSDEEP | `384:ZyokBIlWjwAIY39p0pT2pQ/kMfbP3B8WJ8WgUA:ZylBIlc0EHASpykMfLBTa`

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

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mrinfo.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


