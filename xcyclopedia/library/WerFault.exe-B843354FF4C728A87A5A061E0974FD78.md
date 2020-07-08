---
title: WerFault.exe | Windows Problem Reporting
---

# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting

## Hashes

Type | Hash
-- | --
MD5 | `B843354FF4C728A87A5A061E0974FD78`
SHA1 | `F1158A8418EDDAA55B7CB6A809E7A3C440D9C267`
SHA256 | `26F9D0295B00AE31C5FB42F727E394D6377BC433118D8E405D932B4C51476ABF`
SHA384 | `5C7F527FD7F94A0E8E8A5413D3C359BB6A3F1AADC5D69CD33BB730EA329FFB85618E9042518B38297BF2B14DED0D63CD`
SHA512 | `FDB3AB2CC9835C6AE06ADB815291B7220D68AFF97352509E5C463176557B34DBEFD7AE4D2170F3A7F403F45E9DCAACE1140FEC58D59D78F4DEAB773CE6BC4364`
SSDEEP | `6144:irQgRATtuSfoENXz0oF87o/AGgxVMfh3UeHX/ucL6qPS8Rg+6F5ZVJyB60OHyLCG:LrhX4/74AGggj/3pSegDF5Hc2Hywy`

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: WerFault.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\WerFault.exe](WerFault.exe-5D51C4B5991B8C112E61537B1391E060.md) | 33
[C:\WINDOWS\system32\WerFault.exe](WerFault.exe-88D9F2F0D7AD7839A3F88428421A3D27.md) | 35
[C:\Windows\system32\WerFault.exe](WerFault.exe-DDAA52E54923C29A2AC75BDA3CD7DADB.md) | 32
[C:\WINDOWS\system32\WerFaultSecure.exe](WerFaultSecure.exe-6B384653F71F69C620F18506FF8D5CEB.md) | 35
[C:\Windows\system32\WerFaultSecure.exe](WerFaultSecure.exe-813CD5FD7FB059B4ED2D67A99FCBEEC0.md) | 41
[C:\Windows\system32\WerFaultSecure.exe](WerFaultSecure.exe-9A393C5A2213248F772F6F8AAF26CBC8.md) | 38
[C:\Windows\system32\WerFaultSecure.exe](WerFaultSecure.exe-C0055D829C7FF7734EE77EE11B188A05.md) | 33
[C:\Windows\system32\wermgr.exe](wermgr.exe-51F8D9C50CCF160D67388651DB19AC28.md) | 35
[C:\Windows\system32\wermgr.exe](wermgr.exe-5EEBCCABE74604D756E9F7D9A3D30C2C.md) | 33
[C:\WINDOWS\system32\wermgr.exe](wermgr.exe-C96DD16FBFACF3E22A1C0B7DCFDFCBBB.md) | 32
[C:\Windows\system32\wermgr.exe](wermgr.exe-E4F582A493C2570A23B30CAE2CEEAC19.md) | 33
[C:\windows\system32\wermgr.exe](wermgr.exe-F88816F787B827695928ACE239A9F61C.md) | 33
[C:\Windows\SysWOW64\WerFault.exe](WerFault.exe-78E2621A3ED108179AE91557C1F21DDA.md) | 33
[C:\windows\SysWOW64\WerFault.exe](WerFault.exe-FF88EC2E38C3CDDA92ED566272477098.md) | 27
[C:\Windows\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-3A8ED7F8072921BB83E6C9A143983073.md) | 38
[C:\Windows\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-504211A31F3A16D3FAD61A8451D08EFD.md) | 32
[C:\WINDOWS\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-5DF1A6DC202D24CED14830637F145F48.md) | 35
[C:\Windows\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-F511182849011A1DBF635A34C1278C63.md) | 35
[C:\Windows\SysWOW64\wermgr.exe](wermgr.exe-0F652BF7ADA772981E8AAB0D108FCC92.md) | 35
[C:\windows\SysWOW64\wermgr.exe](wermgr.exe-1908E6DCCB5C330CCF3F0AD7E83FA4FD.md) | 30
[C:\Windows\SysWOW64\wermgr.exe](wermgr.exe-2B5F4FFF330CD1B3B921DAF77330C205.md) | 33
[C:\WINDOWS\SysWOW64\wermgr.exe](wermgr.exe-481E9D9BA530530EFE3C8871DEAEF37F.md) | 32

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While `WerFault.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `        Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


