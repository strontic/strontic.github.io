﻿---
title: splwow64.exe | Print driver host for applications
excerpt: What is splwow64.exe?
---

# splwow64.exe 

* File Path: `C:\Windows\splwow64.exe`
* Description: Print driver host for applications

## Hashes

Type | Hash
-- | --
MD5 | `9FCD31635CC99F1DAFB64AB3F963E0C1`
SHA1 | `8338462C217EE185DCA0FCA863A67D98582870FC`
SHA256 | `FC6896EA784628446643DC1470D6C80C56CEE888D7E170680792E4029372A6A3`
SHA384 | `831E86365A336A3019EE7186E0B0FF0E90AB1E89540429A4266FD79A0AE3B1DA0C37AD001204507D04DC6C47CB10F7AD`
SHA512 | `2E6C16C02E58061127792AC63072A76AEE7E66F3EBE838448044F4F7099C685800F0384EF97120909F8AF24D65B29C81503FEF3BCF04B0EE3BE43ABCFD045BFA`
SSDEEP | `3072:o8TRN4WRNsoGlAi++KWwrZsQgWlUHQbPRyZ2pPTZ:BTRN4yNsoGlAi2tsFUU8AZ2`

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
* File Version: 10.0.19041.329 (WinBuild.160101.0800)
* Product Version: 10.0.19041.329
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\splwow64.exe](splwow64.exe-09EC082A13633BAEDE8FF155A0ACCF9E.md) | 72
[C:\WINDOWS\splwow64.exe](splwow64.exe-7FF9B78730CCCCEE4DA267DED5C5C7DA.md) | 33
[C:\WINDOWS\splwow64.exe](splwow64.exe-906E1DFC3A3A64D3452C5BA124AC9A4C.md) | 41
[C:\Windows\splwow64.exe](splwow64.exe-93A8D365CB20A105CB97FF41451B85D5.md) | 41
[C:\Windows\splwow64.exe](splwow64.exe-AA4138C0FBC6D41F9EBC5C4EFE20ECCA.md) | 86
[C:\Windows\splwow64.exe](splwow64.exe-B626F1C0194C73D55529E729A63209A2.md) | 43
[C:\Windows\splwow64.exe](splwow64.exe-B73202D296AE4FDB8ECC29CC97F8A444.md) | 43
[C:\Windows\splwow64.exe](splwow64.exe-BD86784ABDA6C4FD8ACFD3912AC192E9.md) | 44
[C:\windows\splwow64.exe](splwow64.exe-BE96C8815DE31A42E93A3BE09C2EECCC.md) | 44
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-95E50C824C9C9B4362AA3522B8449E29.md) | 43
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-A7BF96D6CC09A5012C1EA0F990D65567.md) | 49
[C:\WINDOWS\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-A9C07279ACC0EF6251C200B4688849CF.md) | 44
[C:\Windows\system32\PrintIsolationHost.exe](PrintIsolationHost.exe-B59C716809F72A87CF72C66AB7BD5082.md) | 41

## Possible Misuse

*The following table contains possible examples of `splwow64.exe` being misused. While `splwow64.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `title: Suspicious Splwow64 Without Params`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `description: Detects suspicious Splwow64.exe process without any command line parameters`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `Image\|endswith: '\splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_splwow64.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_splwow64.yml) | `CommandLine\|endswith: 'splwow64.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


