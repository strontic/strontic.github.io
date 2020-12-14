---
title: iehelper.exe | Browser Assistant
excerpt: What is iehelper.exe?
---

# iehelper.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\iehelper.exe`
* Description: Browser Assistant

## Screenshot

![iehelper.exe](screenshots/iehelper.exe-E354C974FFDAD4E02637215C461110E6-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `2636692F22B98F81DAA2D58A7FC3ECB3`
SHA1 | `F980E3E044E7F0420C66D3B5D54C695CB2EE17F3`
SHA256 | `9BA369D645FB4B5962D19B5B6C3F8804BE740E0D43EC6057939B13628B7ADC97`
SHA384 | `E280D1BF7602905EA678DE42C3AB567D506191DCF916A992CA55D91E50DA753D77969B9C9CCF4BD7E80E30C642096C4E`
SHA512 | `3742EA495B3AC29FEF1E8A460D023218562061105F75C747CE657AC0348FF30969829AFECA7B3F4643145F832AF4913D519B8896B1287C63830E69AE3A9CC9CD`
SSDEEP | `24576:TDohnmwcdFOscZEb+PV0Au0hq7SqjsQ0UM+:ldFOsNAuLmQz`
IMP | `FDD9BEBA9AF7AFEAFBD5A1DD50969629`
PESHA1 | `91D1F0FF565D6A5AD22A72C77CA7BFF892DBB34C`
PE256 | `6F0689F0CBFEF6105A6E7E3549F2E79B638007881AE13B4C451FE7DAF99D34FC`

## Runtime Data

### Window Title:
Browser Assistant

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\SysWOW64\en-US\user32.dll.mui | File
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Glary Utilities 5\iehelper.exe |
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 1/67
* VirusTotal Link: https://www.virustotal.com/gui/file/9ba369d645fb4b5962d19b5b6c3f8804be740e0d43ec6057939b13628b7adc97/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Glary Utilities 5\iehelper.exe](iehelper.exe-79EDD0580D1DD4FE483FB803F7D2CFEA.md) | 96
[C:\Program Files (x86)\Glary Utilities 5\iehelper.exe](iehelper.exe-E354C974FFDAD4E02637215C461110E6.md) | 96

## Possible Misuse

*The following table contains possible examples of `iehelper.exe` being misused. While `iehelper.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_apt_turla_namedpipes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_apt_turla_namedpipes.yml) | `- '\iehelper' # ruag apt case` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x2 = "C:\\PROGRA~2\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x3 = "C:\\DOCUME~1\\ALLUSE~1\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


