---
title: rdpclip.exe | RDP Clipboard Monitor
---

# rdpclip.exe 

* File Path: `C:\Windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `D887E718FB0F4C99B9F01C5BD59F8B90`
SHA1 | `5B0571263A137364E26A7C8642D0844126542A50`
SHA256 | `ACFA1128B4EDD953F6364FA6216337A59C0522A01349263A11259A827838A56F`
SHA384 | `65B22EFDDB3B48D9296EBEE109D927C011F16936AD55A27B41D1BFDB32F5D1F6E08A42F99ADE54644B655FB7C7EDAF3B`
SHA512 | `0BBADDCF0A208228F5876A5BF5DDFAD6F7C472D637E00C0AD636D0F49616249A5CB2FA2411E46220EF285EDD3405A363255E5CBB2E0AEE24BB6D2AB129B804B9`
SSDEEP | `12288:/9AysJajZlBVobhyvz9Oh8KunUnz9hg+ZJuKy3wGrxrkqobbNYz:/+ysJ+3BVobsvz9Oh8KunUnz9L3uFJru`

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

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `        Image: '*\rdpclip.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


