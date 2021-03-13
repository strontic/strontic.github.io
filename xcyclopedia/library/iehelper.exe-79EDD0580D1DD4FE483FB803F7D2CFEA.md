---
title: iehelper.exe | Browser Assistant
excerpt: What is iehelper.exe?
---

# iehelper.exe 

* File Path: `C:\program files (x86)\Glary Utilities 5\iehelper.exe`
* Description: Browser Assistant

## Screenshot

![iehelper.exe](screenshots/iehelper.exe-E354C974FFDAD4E02637215C461110E6-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `79EDD0580D1DD4FE483FB803F7D2CFEA`
SHA1 | `049171F75555164652B55574785CACF3FB6DB53F`
SHA256 | `F8AA7DE18BE649F7F2DDCE47E21399EC71BF7B0DCB627D1C9E22B1CF705CAEBB`
SHA384 | `DD1E38CAC8103C070D9EDC3B0578E69576433D5390504B00A3C6B49632B0FC0972FA957DD3AAEB47D81BA9CD4019A3E5`
SHA512 | `669B62BE8E2D8AC340315CF1887DC2B451685EE1257589B179D2994FD27D920AF4F0A0F675E16F277122E8D9FBB84941628020A41AD47FF822DD6537091218E1`
SSDEEP | `24576:KDohnmwcdFOscZEb+PV0Au0hq7SqjsQ0UMd:idFOsNAuLmQg`

## Runtime Data

### Window Title:
Browser Assistant

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_4294d6e08a97344a | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Glary Utilities 5\iehelper.exe |
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

* Original Filename: BrowserHelper.exe
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5, 0, 0, 12
* Product Version: 5.0.0.0
* Language: English (United States)
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\iehelper.exe](iehelper.exe-2636692F22B98F81DAA2D58A7FC3ECB3.md) | 96
[C:\Program Files (x86)\Glary Utilities 5\iehelper.exe](iehelper.exe-E354C974FFDAD4E02637215C461110E6.md) | 96

## Possible Misuse

*The following table contains possible examples of `iehelper.exe` being misused. While `iehelper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_apt_turla_namedpipes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_apt_turla_namedpipes.yml) | `- '\iehelper' # ruag apt case`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x2 = "C:\\PROGRA~2\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x3 = "C:\\DOCUME~1\\ALLUSE~1\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


