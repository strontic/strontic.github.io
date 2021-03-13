---
title: Initialize.exe | Glary Utilities Initialize
excerpt: What is Initialize.exe?
---

# Initialize.exe 

* File Path: `C:\program files (x86)\Glary Utilities 5\Initialize.exe`
* Description: Glary Utilities Initialize

## Hashes

Type | Hash
-- | --
MD5 | `EA2C6AEB03E449D1948991332A3BE9EE`
SHA1 | `8F33C4F3B1BBF8A6C639F0D4D11B8FC88E052E66`
SHA256 | `E5AA1A943F0FC4EE07E7AC52925A5EC6CF20F9B81EF790DBAE017D4CFC623A55`
SHA384 | `E043F6F4BE461C98D9622602A7CE033AFCF10186E7DF02CE74575D3445820950EB53D4EB670071A9E04A73136A16161D`
SHA512 | `ED84DEEDF2641BCD8CAACA413D595701695F5B6AA7DDF5527EA61338819704711760501656D00460F4DCFF594389AAB065D93BD6AA4609A8E9356EFCABEFA45E`
SSDEEP | `3072:v1kmHv3g0DQ/sHKyMUyjknO0rpKXnVgwqU4VU:tv3g0sUHcUfO0l2qUD`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Program Files (x86)\Glary Utilities 5 | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.vc90.crt_1fc8b3b9a1e18e3b_9.0.30729.9625_none_508ef7e4bcbbe589 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_fd031af45b0106f2 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_4294d6e08a97344a | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\Glary Utilities 5\Initialize.exe |
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


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\Initialize.exe](Initialize.exe-7511532801542AAE6C31871614B53872.md) | 93
[C:\Program Files (x86)\Glary Utilities 5\Initialize.exe](Initialize.exe-A90CF1DC124C7EC7B4F2725D18EC2D7D.md) | 93

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



MIT License. Copyright (c) 2020-2021 Strontic.


