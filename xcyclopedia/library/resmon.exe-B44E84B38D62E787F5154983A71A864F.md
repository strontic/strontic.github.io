---
title: resmon.exe | Resource Monitor
---

# resmon.exe 

* File Path: `C:\WINDOWS\SysWOW64\resmon.exe`
* Description: Resource Monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B44E84B38D62E787F5154983A71A864F`
SHA1 | `869B19128DE3D02A80FBD208B5F45C00AB56D430`
SHA256 | `8FA569F3FAF05A116250786AE2779DE2C924FC714D68BFA7F8EF611FA0ACE904`
SHA384 | `E5BF495D19AB8B8893824BD24248CAD2CAF1DEA94363A8FB5E70030957BF34A700ABFC873DA86E4CC8FE84F82074A526`
SHA512 | `8E1A830C8572983E3A6853543B4590743EE4C27218B9C1D7AFE90DB72DB14F87C7BCAF400DC2263EB5C17B532D1E8F53CC236DBCA2DB9D30673E5C7431594AF8`
SSDEEP | `1536:6OfP5BqY3KtrtizIo9plJSs9kYuZJnGZLzOcE6Ls7HXG84PK05Z34g/CO+sH:Xn5ghtYIo9piswTogiqQKy349`

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
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 69
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 68
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 66
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 93
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 94
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 94
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 74
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 72
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 69
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 94

## Possible Misuse

*The following table contains possible examples of `resmon.exe` being misused. While `resmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `            - '*\resmon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


