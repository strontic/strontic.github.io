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
MD5 | `0FB8985E4D0F7D37BC366CFD93B73A52`
SHA1 | `03BA772294D4BF39EB39352DAA2818F28C907B5A`
SHA256 | `3368F84C5C1E52D416AE74615088B6AF101ADF2167B1FB009125BDCD4CA15BF0`
SHA384 | `2F32857147144FD498592B29D56CAB0BE54892431637FDB5744E18C4FE62CFC89C50A16CE74CCE870F80BED1A2121E3A`
SHA512 | `91358DCFD63E2F8FCED842C94606A5D1C309EBD112A9C4CEE2F697DAA0083F1033035323269AE6BD9A64A09D975B837BE96EDCE37E8C2A874C6669176E0EEE67`
SSDEEP | `1536:ND6xTNBqY3KtrtizIo9plJSs9kYuZJnGZLzOcE6Ls7HXG84PK05Z34g/CO+sH:qTNghtYIo9piswTogiqQKy349`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\resmon.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: resmon.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\perfmon.exe](perfmon.exe-52BC3295597B70B1380FAA6E32BEFAD3.md) | 72
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 66
[C:\windows\system32\perfmon.exe](perfmon.exe-CB1511A4E14C072450E5A61BD74859E3.md) | 75
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 68
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 72
[C:\windows\system32\resmon.exe](resmon.exe-6C6E586C858BFE1DE453921F67AA9206.md) | 93
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 90
[C:\Windows\system32\resmon.exe](resmon.exe-A01AB6C669DCC17E87C84C0C07D2CFAE.md) | 93
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 93
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 93
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 74
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 72
[C:\windows\SysWOW64\perfmon.exe](perfmon.exe-660927A8213F3A9AB378BDFB195E7277.md) | 68
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 72
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-97F73727B423C2FEE513EB7A06E357E5.md) | 66
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 93
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 96
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-C182C3463D5E5DFFED8F949D2BB781D3.md) | 94

## Possible Misuse

*The following table contains possible examples of `resmon.exe` being misused. While `resmon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `            - '*\resmon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


