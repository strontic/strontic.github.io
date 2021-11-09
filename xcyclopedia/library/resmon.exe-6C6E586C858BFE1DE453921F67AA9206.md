---
title: resmon.exe | Resource Monitor
excerpt: What is resmon.exe?
---

# resmon.exe 

* File Path: `C:\windows\system32\resmon.exe`
* Description: Resource Monitor

## Hashes

Type | Hash
-- | --
MD5 | `6C6E586C858BFE1DE453921F67AA9206`
SHA1 | `C7744E905331FE56C7619A2423311E16D5F8B976`
SHA256 | `378FCDD22908B063FC8696BCFA25B5544A19C9CCB3B878BC968C690E1F75342E`
SHA384 | `78001F37DD7C6A00E4AEE1CDE4C69E2B661354765152B6CBFC17E8ED7B371706643BEEEC702CE8881B222BDD4F117DC7`
SHA512 | `E865604F44EEB7F44F6A710F99010DD276A34E1AA561092AF2E9EF72793732A0DF62346A6B13152BA99026685F7B83B7751B5099A91BF11586E576AE9AB52958`
SSDEEP | `1536:sYoZ4NBqY3KtrtizIo9plJSs9kYuZJnGZLzOcE6Ls7HXG84PK05Z34g/CO+sH:yZ4NghtYIo9piswTogiqQKy349`

## Signature

* Status: The file C:\windows\system32\resmon.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
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
[C:\Windows\system32\perfmon.exe](perfmon.exe-52BC3295597B70B1380FAA6E32BEFAD3.md) | 69
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-AE3D54BF0D325BDFB785B86511930E37.md) | 71
[C:\WINDOWS\system32\perfmon.exe](perfmon.exe-C90AF971C5FE2427135D6DF8C38B720E.md) | 46
[C:\windows\system32\perfmon.exe](perfmon.exe-CB1511A4E14C072450E5A61BD74859E3.md) | 79
[C:\Windows\system32\perfmon.exe](perfmon.exe-D38AA59C3BEA5456BD6F95C73AD3C964.md) | 65
[C:\Windows\system32\perfmon.exe](perfmon.exe-D761794B0779B9951349E2F2507B25BC.md) | 68
[C:\WINDOWS\system32\resmon.exe](resmon.exe-45D0C6A8CAD3E768E5827BBCEEB1D7E8.md) | 93
[C:\Windows\system32\resmon.exe](resmon.exe-852ACA89972551B00B110EEE6ADA717A.md) | 91
[C:\Windows\system32\resmon.exe](resmon.exe-A01AB6C669DCC17E87C84C0C07D2CFAE.md) | 91
[C:\Windows\system32\resmon.exe](resmon.exe-C9221473CE8A3EF5C0FB8ABB912786FA.md) | 91
[C:\WINDOWS\system32\resmon.exe](resmon.exe-FF8CA7D9F879E176A1284F16A05A618C.md) | 94
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-14ACB06686DC70FAB341DE0721B71BF1.md) | 72
[C:\WINDOWS\SysWOW64\perfmon.exe](perfmon.exe-390A0223147F517FB5AA39B07A44F1A2.md) | 69
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-6284C86A1AE399794C18FBBC86CC8340.md) | 74
[C:\windows\SysWOW64\perfmon.exe](perfmon.exe-660927A8213F3A9AB378BDFB195E7277.md) | 66
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-805F9B64745C730A6BD789083D0EF4E2.md) | 69
[C:\Windows\SysWOW64\perfmon.exe](perfmon.exe-97F73727B423C2FEE513EB7A06E357E5.md) | 68
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-0D30E55CD18D7B17ED753B12031D7640.md) | 93
[C:\windows\SysWOW64\resmon.exe](resmon.exe-0FB8985E4D0F7D37BC366CFD93B73A52.md) | 93
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-29C52C15D2D68A4BBE9A36701D31100E.md) | 94
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-87427E88F06D7C568E3E4A8BD838E380.md) | 93
[C:\WINDOWS\SysWOW64\resmon.exe](resmon.exe-B44E84B38D62E787F5154983A71A864F.md) | 93
[C:\Windows\SysWOW64\resmon.exe](resmon.exe-C182C3463D5E5DFFED8F949D2BB781D3.md) | 94

## Possible Misuse

*The following table contains possible examples of `resmon.exe` being misused. While `resmon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_taskmgr_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_taskmgr_parent.yml) | `- '\resmon.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


