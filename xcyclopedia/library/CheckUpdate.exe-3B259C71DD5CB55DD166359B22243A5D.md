---
title: CheckUpdate.exe | Glary Utilities CheckUpdate
excerpt: What is CheckUpdate.exe?
---

# CheckUpdate.exe 

* File Path: `C:\program files (x86)\Glary Utilities 5\CheckUpdate.exe`
* Description: Glary Utilities CheckUpdate

## Hashes

Type | Hash
-- | --
MD5 | `3B259C71DD5CB55DD166359B22243A5D`
SHA1 | `824A52AB41390C03D218457E547318DADE24713C`
SHA256 | `11036E46B0D34259346C897EDFC137FA314F3385511BE8981AF4D1BDA9FD5760`
SHA384 | `48FFBB4E588BC4DDE1728CCCC1494876955E748FFFA60FD845D993CD096B5C2EF0D2F6C70D6182C9DDCB63094D8D5588`
SHA512 | `D1FA6BE17AAF167F3D49498DDE0FE46DE9501D11421C86E885B93326DADA20AE0CD0EDAA718B84F9199D0EEDBC0A2F48ADB2AA47AB65472C4E33B311D41114A5`
SSDEEP | `768:AggXKDOdccAUaTsiAzOBzzHYER3zzzyfzqhTzEsIXC7fm4lupOcGdMeKgixV1DGi:DgOOdcc6siAzOBzz4EhzzzyfzqhTzEsw`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\mswsock.dll.mui | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_4294d6e08a97344a | File
\BaseNamedObjects\F932B6C7-3A20-46A0-B8A0-8894AA421973 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-2047949552-857980807-821054962-504 | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Glary Utilities 5\CheckUpdate.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0F05AE21CDC17B9F3CF09D7BFC659BA3`
* Thumbprint: `362EBB303E088105BDCC07D94E6B7875D30C0D06`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Glarysoft LTD, O=Glarysoft LTD, S=Beijing, C=CN

## File Metadata

* Original Filename: CheckUpdate.exe
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5, 0, 0, 26
* Product Version: 5.0.0.1
* Language: Chinese (Simplified, China)
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\CheckUpdate.exe](CheckUpdate.exe-5D0D62731FF110F355D225E7B7DABE19.md) | 96
[C:\Program Files (x86)\Glary Utilities 5\CheckUpdate.exe](CheckUpdate.exe-70AEAEF426193BC2540197258FF058B8.md) | 94

## Possible Misuse

*The following table contains possible examples of `CheckUpdate.exe` being misused. While `CheckUpdate.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $c1 = "svchost64.swp\",checkUpdate" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $c2 = "svchost64.swp,checkUpdate" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


