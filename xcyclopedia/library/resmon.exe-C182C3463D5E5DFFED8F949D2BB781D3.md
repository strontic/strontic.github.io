---
title: resmon.exe | Resource Monitor
---

# resmon.exe 

* File Path: `C:\windows\SysWOW64\resmon.exe`
* Description: Resource Monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C182C3463D5E5DFFED8F949D2BB781D3`
SHA1 | `91C8BA668F5990B610C84EF714D80E5EFAA9449B`
SHA256 | `10D4937D6D559D7B445AF08DFCDC953BDB9079E78C02C3C54BF4343499FB66E5`
SHA384 | `E05B03BA0FFF12CF84195D9F1D11894E6A079B0A83F9E64BE1677FE7C99FB2F320337FF3E309D935877DFD42B9A5EE2B`
SHA512 | `49D9CB1FDB8199484BFA947F0849386558A2F406E45FD7CDC6C98346CEFF1FA944FB2B08C3A0ABA7972E2EB282D53D590E23968B5EE0E77360F017664DF8E613`
SSDEEP | `1536:xbsHBqY3KtrtizIo9plJSs9kYuZJnGZLzOcE6Ls7HXG84PK05Z34g/CO+sH:xwHghtYIo9piswTogiqQKy349`

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: resmon.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\perfmon.exe](perfmon.exe-52BC3295597B70B1380FAA6E32BEFAD3.md) | 72
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 66
[C:\windows\system32\perfmon.exe](perfmon.exe-CB1511A4E14C072450E5A61BD74859E3.md) | 79
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 65
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 69
[C:\windows\system32\resmon.exe](resmon.exe-6C6E586C858BFE1DE453921F67AA9206.md) | 94
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 91
[C:\Windows\system32\resmon.exe](resmon.exe-A01AB6C669DCC17E87C84C0C07D2CFAE.md) | 96
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 93
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 94
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 74
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 75
[C:\windows\SysWOW64\perfmon.exe](perfmon.exe-660927A8213F3A9AB378BDFB195E7277.md) | 69
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 69
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-97F73727B423C2FEE513EB7A06E357E5.md) | 72
[C:\windows\SysWOW64\resmon.exe](resmon.exe-0FB8985E4D0F7D37BC366CFD93B73A52.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 94
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 94

## Possible Misuse

*The following table contains possible examples of `resmon.exe` being misused. While `resmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `            - '*\resmon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


