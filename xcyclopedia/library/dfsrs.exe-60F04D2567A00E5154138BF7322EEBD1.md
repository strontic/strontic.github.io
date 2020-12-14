---
title: dfsrs.exe | Distributed File System Replication
excerpt: What is dfsrs.exe?
---

# dfsrs.exe 

* File Path: `C:\Windows\system32\dfsrs.exe`
* Description: Distributed File System Replication

## Hashes

Type | Hash
-- | --
MD5 | `60F04D2567A00E5154138BF7322EEBD1`
SHA1 | `7A55CF8917646682470771855DC869D88512FD19`
SHA256 | `E62B792B77C49B4EDAF95492991CFA6A764E2E01C76CFB95A06D84461C639214`
SHA384 | `33AB0D50223BA593C3F122E43B5712B3082D1933AF63708F4D735CAD15F947D8220148073C6BF5616CCC9AF789D961CD`
SHA512 | `59F45BA60813A685C9B52218F05368DF227BE91E34619B8090A1DCD9E90308CAA49B6D2BF30684651B37F8AA879899E28343A11487A09D27F5E17921FA240617`
SSDEEP | `49152:Pxx6KqYgJOyNN6VvBmo/HiBkKpLMKILIEO9zUaYPspCYH/CK0DTWte2vqt:HYN2exQssKZ`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dfsr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `dfsrs.exe` being misused. While `dfsrs.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `- '\dfsrs.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


