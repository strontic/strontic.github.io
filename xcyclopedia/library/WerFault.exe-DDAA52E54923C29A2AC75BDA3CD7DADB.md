
# WerFault.exe 

* File Path: `C:\Windows\system32\WerFault.exe`
* Description: Windows Problem Reporting
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DDAA52E54923C29A2AC75BDA3CD7DADB`
SHA1 | `FB699EDE9E65E4605CBEB32ECBFF2D113EA71932`
SHA256 | `46CABAE805B8C9E95255814366F0E5517E30AB7E7414E4F288D6AC5072D6D140`
SHA384 | `D4A06DB8DFE757AA774961C8001CBE6B2CCC5C190B205D75AD85D499390686887F22DE52375D6B48928A5B1D24A69A25`
SHA512 | `FD9623031C7E7E8B8052A504AE45B03FD152C4D18D424AA22C477B1060DF2BFD38E288E5F26343C775C0F147BF0235C05E8D96E960343600520BC82F01DDC975`
SSDEEP | `6144:lcka7+n9gSLLQpIDniJ4buGUlCWWkgVJyB60OHyLC7v:/9gSXQpmiJRYW4c2Hyw`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\WerFaultSecure.exe](WerFaultSecure.exe-6B384653F71F69C620F18506FF8D5CEB.md) | 49
[C:\Windows\system32\WerFaultSecure.exe](WerFaultSecure.exe-C0055D829C7FF7734EE77EE11B188A05.md) | 47
[C:\Windows\system32\wermgr.exe](wermgr.exe-5EEBCCABE74604D756E9F7D9A3D30C2C.md) | 46
[C:\WINDOWS\system32\wermgr.exe](wermgr.exe-C96DD16FBFACF3E22A1C0B7DCFDFCBBB.md) | 44
[C:\Windows\SysWOW64\WerFault.exe](WerFault.exe-78E2621A3ED108179AE91557C1F21DDA.md) | 40
[C:\WINDOWS\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-5DF1A6DC202D24CED14830637F145F48.md) | 47
[C:\Windows\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-F511182849011A1DBF635A34C1278C63.md) | 47
[C:\Windows\SysWOW64\wermgr.exe](wermgr.exe-0F652BF7ADA772981E8AAB0D108FCC92.md) | 43
[C:\WINDOWS\SysWOW64\wermgr.exe](wermgr.exe-481E9D9BA530530EFE3C8871DEAEF37F.md) | 41

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `        Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


