---
title: Initialize.exe | Glary Utilities Initialize
excerpt: What is Initialize.exe?
---

# Initialize.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\Initialize.exe`
* Description: Glary Utilities Initialize

## Hashes

Type | Hash
-- | --
MD5 | `7511532801542AAE6C31871614B53872`
SHA1 | `EFE3C143B1F84CD08B9AFB5717EB13FD40CA21BC`
SHA256 | `35F7BB3D73096D7F2B7ED9FDF23D458521F5B188CACDC00C10615205D912B8D4`
SHA384 | `2BBA9F3BFE83538E9B9902D187E0A021599DACCF0132F0F236C1E57BBE837115D448CD226E85ADB710696E70AFD67266`
SHA512 | `FFBAD6B6AB914E1D04E4332F1D5BE430EB25DDDA322513718DEB526571DAE1F8F9D979CA6693D39365950342CF3F1B8B0E288F31577230389AB5FD1C4A34DE13`
SSDEEP | `3072:F1kmHv3g0DQ/sHKyMUyjknO0rpKXnVgwqU2Vg:Hv3g0sUHcUfO0l2qUJ`
IMP | `209CD9667F1D1DD807EEF7FF39F3D2B4`
PESHA1 | `E06863B426D448403AF9D3FA973ADD8C916360AF`
PE256 | `9B5DCE9DB7BA45A154D9B108A4A6E80FB6D2215E83E486A97D110BADFC7A31E6`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.508_none_429cdbca8a8ffa94 | File
(RW-)   C:\xCyclopedia | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme2547664911 | Section
\Windows\Theme3854699184 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Glary Utilities 5\Initialize.exe |
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

* Original Filename: Initialize.exe
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5, 0, 0, 48
* Product Version: 5.0.0.1
* Language: Chinese (Simplified, China)
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/35f7bb3d73096d7f2b7ed9fdf23d458521f5b188cacdc00c10615205d912b8d4/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\Initialize.exe](Initialize.exe-A90CF1DC124C7EC7B4F2725D18EC2D7D.md) | 93
[C:\program files (x86)\Glary Utilities 5\Initialize.exe](Initialize.exe-EA2C6AEB03E449D1948991332A3BE9EE.md) | 93

## Possible Misuse

*The following table contains possible examples of `Initialize.exe` being misused. While `Initialize.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $1 = "initialize" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $s7 = "initialize" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $6 = "initialize" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $s5 = "initialize" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s2 = "PySystemState.initialize(System.getProperties(), null, argv);" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [threat_lenovo_superfish.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/threat_lenovo_superfish.yar) | $s2 = "Invalid key length used to initialize BlowFish." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


