---
title: dns.exe | Domain Name System (DNS) Server
---

# dns.exe 

* File Path: `C:\Windows\system32\dns.exe`
* Description: Domain Name System (DNS) Server

## Hashes

Type | Hash
-- | --
MD5 | `97AD7A76D6C0E305373CA049C6873EA5`
SHA1 | `2B47971E533F96CCF453B8902EDDE5150E4EB981`
SHA256 | `2E80D7839970CF9D09B37CA444939049C5BEBDCAA084F4BE15DC4FF55F2057F6`
SHA384 | `5A5C805C25290FB15AAE941C63472A3AFC0F386FA1084CB8F99A807B567CC38E31C99CBFA23024DDECB3BA1F2EEE216E`
SHA512 | `1E223334E181CBCF7B2C7FE3FEE372F9AA4186AEF7BEA0A4303CD1E295AE454687214C32ABE2FCACE5467FB4FD17CB427E0642884DBF8A2C877A06E5FDD6FBBC`
SSDEEP | `49152:LXQlXCpXiT5nRhtUsoprdV+ig65SJSsamAwG/2t1Ob4c0gkkdz6RL75qsx/:juXCpXo5nXtUsudVVg65S4oRG+bOb4nH`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dns.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.719 (WinBuild.160101.0800)
* Product Version: 10.0.17763.719
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `dns.exe` being misused. While `dns.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `ParentImage\|endswith: '\System32\dns.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_1350.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_1350.yml) | `- Unknown but benign sub processes of the Windows DNS service dns.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Dnscmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Dnscmd.yml) | `- Link: https://github.com/dim0x69/dns-exe-persistance/tree/master/dns-plugindll-vcpp` | 



MIT License. Copyright (c) 2020 Strontic.


