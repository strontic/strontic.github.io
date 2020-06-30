---
title: resmon.exe | Resource Monitor
---

# resmon.exe 

* File Path: `C:\WINDOWS\system32\resmon.exe`
* Description: Resource Monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FF8CA7D9F879E176A1284F16A05A618C`
SHA1 | `B3F01A2F8F2E144BE0C4BBFD2C15B4037B856F14`
SHA256 | `B5CE6FCC43B79F85D20D679B29BA54E9D618501ED7B39119383C570EBABD1F57`
SHA384 | `0621E0879A62DF24E0ABB0FEF564BF158D6B20EB2F4872D3929AE0DB960A0FD1A321DA39BF71EB653EE2A0A3B35E0AC5`
SHA512 | `CC3FED09EAC570A64DD5CE221944D7059DCF72808573034B662F1B225F868CB8BFB5BD32EEC6EAE13B444053BB88745D21F5F8AF0674B925F8F9FAF87449A5DE`
SSDEEP | `1536:FYyM5BqY3KtrtizIo9plJSs9kYuZJnGZLzOcE6Ls7HXG84PK05Z34g/CO+sH:/M5ghtYIo9piswTogiqQKy349`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
perfmon.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: resmon.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\perfmon.exe](perfmon.exe-52BC3295597B70B1380FAA6E32BEFAD3.md) | 69
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 69
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 68
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 66
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 93
[C:\Windows\system32\resmon.exe](resmon.exe-A01AB6C669DCC17E87C84C0C07D2CFAE.md) | 91
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 93
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 74
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 75
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 72
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-97F73727B423C2FEE513EB7A06E357E5.md) | 66
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 96
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 94
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-C182C3463D5E5DFFED8F949D2BB781D3.md) | 94

## Possible Misuse

*The following table contains possible examples of `resmon.exe` being misused. While `resmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `            - '*\resmon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


