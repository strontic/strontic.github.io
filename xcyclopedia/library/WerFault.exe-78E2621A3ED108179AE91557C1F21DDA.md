
# WerFault.exe 

* File Path: `C:\Windows\SysWOW64\WerFault.exe`
* Description: Windows Problem Reporting
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `78E2621A3ED108179AE91557C1F21DDA`
SHA1 | `404270D013E237FE8FAB2753CC09FA2F778414EB`
SHA256 | `4BC022BB58B3AF9F724410E32B56BC61479226A1D0DF1065EEC6FA4909C33F4F`
SHA384 | `106A722728C23F036C856074CC8205DDE74EBDAE26BADAA7FF5760C7BF6A931A209E39BEFF1B3EE14E36C65B1AA6F727`
SHA512 | `DC9504F60CFB16A154C8AD357A6C29646294CF658569EF56BA92B220489C7ACA91101E1630817F941CF14C6261A832E6E204D2678E48D6636855157481F0D9F9`
SSDEEP | `6144:Yeo6g5XV78CqRujwNY9MVJyB60OHyLC7vdw:1g/gCqRBN5c2Hywy`

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
[C:\Windows\system32\WerFault.exe](WerFault.exe-DDAA52E54923C29A2AC75BDA3CD7DADB.md) | 40
[C:\WINDOWS\system32\WerFaultSecure.exe](WerFaultSecure.exe-6B384653F71F69C620F18506FF8D5CEB.md) | 52
[C:\Windows\system32\WerFaultSecure.exe](WerFaultSecure.exe-C0055D829C7FF7734EE77EE11B188A05.md) | 50
[C:\Windows\system32\wermgr.exe](wermgr.exe-5EEBCCABE74604D756E9F7D9A3D30C2C.md) | 50
[C:\WINDOWS\system32\wermgr.exe](wermgr.exe-C96DD16FBFACF3E22A1C0B7DCFDFCBBB.md) | 46
[C:\WINDOWS\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-5DF1A6DC202D24CED14830637F145F48.md) | 47
[C:\Windows\SysWOW64\WerFaultSecure.exe](WerFaultSecure.exe-F511182849011A1DBF635A34C1278C63.md) | 55
[C:\Windows\SysWOW64\wermgr.exe](wermgr.exe-0F652BF7ADA772981E8AAB0D108FCC92.md) | 55
[C:\WINDOWS\SysWOW64\wermgr.exe](wermgr.exe-481E9D9BA530530EFE3C8871DEAEF37F.md) | 38

## Possible Misuse

*The following table contains possible examples of `WerFault.exe` being misused. While this file is **not** malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lsass_dump.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_lsass_dump.yml) | `        Image\|endswith: '\werfault.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


