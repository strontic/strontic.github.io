---
title: splwow64.exe | Print driver host for applications
excerpt: What is splwow64.exe?
---

# splwow64.exe 

* File Path: `C:\Windows\splwow64.exe`
* Description: Print driver host for applications

## Hashes

Type | Hash
-- | --
MD5 | `B626F1C0194C73D55529E729A63209A2`
SHA1 | `5CA36C70A1942504CB0E65D94885139CBF653CF0`
SHA256 | `BCC166B2E9FA1483CA5FE851F0C5D7477AB1D029F20CF5EBBB1BCB01B9BFE506`
SHA384 | `A75D934CA1E22488C029E3272F36782B091802E63162CA1E61276BC50CA667176F6C1567C7E31FF81F32E026B2C0CE45`
SHA512 | `030FAD141DEA3E972082DFA352EBBF5CEF556E23599DE6B3A249FB6E743151F326C6D93565FDDD136132D4AD3320C7BC7B0ABCFE618A7ACB70DCFD782A360181`
SSDEEP | `3072:SXVXRFVRrpRbtbgfw6muHQbPRyZ2pPTU:mVXhFTBc4fu8AZ2`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: splwow64.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.3630 (rs1_release.200407-1730)
* Product Version: 10.0.14393.3630
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\splwow64.exe](splwow64.exe-09EC082A13633BAEDE8FF155A0ACCF9E.md) | 41
[C:\WINDOWS\splwow64.exe](splwow64.exe-906E1DFC3A3A64D3452C5BA124AC9A4C.md) | 46
[C:\Windows\splwow64.exe](splwow64.exe-93A8D365CB20A105CB97FF41451B85D5.md) | 41
[C:\Windows\splwow64.exe](splwow64.exe-9FCD31635CC99F1DAFB64AB3F963E0C1.md) | 43
[C:\Windows\splwow64.exe](splwow64.exe-AA4138C0FBC6D41F9EBC5C4EFE20ECCA.md) | 40
[C:\Windows\splwow64.exe](splwow64.exe-B73202D296AE4FDB8ECC29CC97F8A444.md) | 46
[C:\Windows\splwow64.exe](splwow64.exe-BD86784ABDA6C4FD8ACFD3912AC192E9.md) | 50
[C:\windows\splwow64.exe](splwow64.exe-BE96C8815DE31A42E93A3BE09C2EECCC.md) | 44
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-95E50C824C9C9B4362AA3522B8449E29.md) | 50
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-A7BF96D6CC09A5012C1EA0F990D65567.md) | 49
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-B59C716809F72A87CF72C66AB7BD5082.md) | 50

## Possible Misuse

*The following table contains possible examples of `splwow64.exe` being misused. While `splwow64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `title: Suspicious Splwow64 Without Params`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `description: Detects suspicious Splwow64.exe process without any command line parameters`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `Image\|endswith: '\splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `CommandLine\|endswith: 'splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


