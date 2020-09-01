---
title: KeePass.exe | KeePass
---

# KeePass.exe 

* File Path: `C:\program files (x86)\KeePass Password Safe 2\KeePass.exe`
* Description: KeePass
* Comments: KeePass Password Safe


## Screenshot

![KeePass.exe](screenshots/KeePass.exe-5EA874CE90310328654D49B0A01E5919-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `5EA874CE90310328654D49B0A01E5919`
SHA1 | `511DEBA40F6A066DD17976EF11BB54ED728EDB25`
SHA256 | `1D7F70A6F5AF808A387CC5B23305965772F99BC51E6C89DC91FBA6E160C4A1DA`
SHA384 | `0DB2A08D5EA923B0ED68D53FA9466B3DCCF85390BDCA04F4E1E244E031E6CB5E94310C46BBAD2BEE22C0397359309973`
SHA512 | `91728A7A9C3B61A41E1FE34D50CE222CF41AA93AB515E08C56BBE233BC60A2CA1EAB55E096D848831D887083C7E2836F102EE01416A24AE58D933426001AF67B`
SSDEEP | `49152:XeYyyc1xttuelS6RsOcG41he4dWGdNlPsfob4:OY5y/uelS6uJG41ix`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R--)   C:\Windows\assembly\pubpol5.dat | File
(R-D)   C:\Program Files (x86)\KeePass Password Safe 2\KeePass.exe | File
(R-D)   C:\Program Files (x86)\KeePass Password Safe 2\KeePass.XmlSerializers.dll | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\user32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\winnlsres.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Users\user\Documents | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1_none_b555e41d4684ddec | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_fae7a009761b0b44 | File
\...\Cor_SxSPublic_IPCBlock | Section
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\Cor_Private_IPCBlock_v4_8996 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\1DefaultTIPSharedMemory | Section
\Sessions\1\BaseNamedObjects\2324HWNDInterface:90654 | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\Windows\Theme4048709601 | Section
\Windows\Theme603176458 | Section


### Loaded Modules:

Path |
-- |
C:\program files (x86)\KeePass Password Safe 2\KeePass.exe |
C:\Windows\Microsoft.NET\Framework64\v4.0.30319\mscoreei.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |


## Signature

* Status: Signature verified.
* Serial: `57E66F7FA80DDA7E5D403D6863548CC6`
* Thumbprint: `3B82AC8D746DF6E395B76EC1BDC27CE25793D73B`
* Issuer: CN=Certum Code Signing CA SHA2, OU=Certum Certification Authority, O=Unizeto Technologies S.A., C=PL
* Subject: E=cert@dominik-reichl.de, CN="Open Source Developer, Dominik Reichl", O=Open Source Developer, L=Metzingen, C=DE

## File Metadata

* Original Filename: KeePass.exe
* Product Name: KeePass
* Company Name: Dominik Reichl
* File Version: 2.45.0.0
* Product Version: 2.45.0.0
* Language: Language Neutral
* Legal Copyright: Copyright  2003-2020 Dominik Reichl


## Possible Misuse

*The following table contains possible examples of `KeePass.exe` being misused. While `KeePass.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_wocao.yml) | `            - 'type *keepass\KeePass.config.xml'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       description = "Detects component of KeeTheft - KeePass dump tool - file KeeThief.ps1" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       description = "Detects component of KeeTheft - KeePass dump tool - file KeeTheft.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       $x6 = "*** Interesting... there are multiple .NET runtimes loaded in KeePass" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) |       description = "Detects component of KeeTheft - KeePass dump tool - file Out-Shellcode.ps1" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


