---
title: CheckUpdate.exe | Glary Utilities CheckUpdate
excerpt: What is CheckUpdate.exe?
---

# CheckUpdate.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\CheckUpdate.exe`
* Description: Glary Utilities CheckUpdate

## Hashes

Type | Hash
-- | --
MD5 | `5D0D62731FF110F355D225E7B7DABE19`
SHA1 | `DA64DD331BC60D12305552B9FC443552EA9F44A7`
SHA256 | `6BC585A7170CC66A14D5D288FF4A3F466BD25A2859ADA018582272F2199DFC14`
SHA384 | `2D2855A932345F107D6B16D55B30029A9FC0E6265B19694C06A076C4FBB627A52FC802940A8214D055219F07F965BDB5`
SHA512 | `9E5419619FB1C967C49CB3562E0996C5C8F067A8E23AAA91AB449B13E72BCEA4714BA8227CA7CAE32306298D3D8748122284BB61CA4348158255B0FFC4AEE06A`
SSDEEP | `768:AagXKDOdccAUaTsiAzOBzzHYER3zzzyfzqhTzEsIXC7fm4lupOcGdMeKggxV1DGu:lgOOdcc6siAzOBzz4EhzzzyfzqhTzEsC`
IMP | `37CFC386A920FA6CC8B3F6CEF5720B5D`
PESHA1 | `BFE3727C87458DCBB1118B3168641C522256C693`
PE256 | `DEAFA087C92130B061A8EDC22D5DD19177DC0D2E5D04EC79541C32ECF381B6BC`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\mswsock.dll.mui | File
(R-D)   C:\Windows\System32\en-US\propsys.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\F932B6C7-3A20-46A0-B8A0-8894AA421973 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-2047949552-857980807-821054962-504 | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Glary Utilities 5\CheckUpdate.exe |
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/6bc585a7170cc66a14d5d288ff4a3f466bd25a2859ada018582272f2199dfc14/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Glary Utilities 5\CheckUpdate.exe](CheckUpdate.exe-3B259C71DD5CB55DD166359B22243A5D.md) | 96
[C:\Program Files (x86)\Glary Utilities 5\CheckUpdate.exe](CheckUpdate.exe-70AEAEF426193BC2540197258FF058B8.md) | 94

## Possible Misuse

*The following table contains possible examples of `CheckUpdate.exe` being misused. While `CheckUpdate.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $c1 = "svchost64.swp\",checkUpdate" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_wilted_tulip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_wilted_tulip.yar) | $c2 = "svchost64.swp,checkUpdate" wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


