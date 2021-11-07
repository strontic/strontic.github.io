---
title: putty.exe | SSH, Telnet, Rlogin, and SUPDUP client
excerpt: What is putty.exe?
---

# putty.exe 

* File Path: `C:\Program Files\PuTTY\putty.exe`
* Description: SSH, Telnet, Rlogin, and SUPDUP client

## Screenshot

![putty.exe](screenshots/putty.exe-AA8F39DFDF0CA430002CE3820A002324-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `BC0A62703FDC93FF2AEC56D3FF46F9B9`
SHA1 | `44EDA29E797E0D988AB6D32EBAE44E3925AC3B02`
SHA256 | `2553BF7AC7894F547FA5E7702266B7002CDC3DD42999BAECE00619BCBAB7334F`
SHA384 | `7935266A895BFB7CDCFFC3DFFE652C7B38842803315DBF0CDE9224F9A37B29F41670395644AE2B9056FD01ACD088B34F`
SHA512 | `7FBD6E64F095452F097EDE02F45BB9C69790E7D27FF57B39F6F5A7816FCF22F9C52DE3ED27510369935261C3C1AEFA413BF346E306619065B1EBBE6D09F639CA`
SSDEEP | `12288:Sw/FCzU/EG+Gsdtc7bw0hkOmMvC/CpQ3EETdUl32JX:SwIEES7sjMc3EQiMX`
IMP | `13235F12BEC0089819ABB93D2E545004`
PESHA1 | `BC27A8ABC59AABD857435EB79AC171860CBAED98`
PE256 | `BD740DFAD922AF816C7B4253B4C0281BFA0E4A94753AB0A7AF4F19DD854F3981`

## Runtime Data

### Window Title:
PuTTY Command Line Error

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_5.82.19041.1110_none_792d1c772443f647 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.1110_none_60b5254171f9507e | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme449731986 | Section
\Windows\Theme1396518710 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files\PuTTY\putty.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\COMDLG32.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHLWAPI.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `7C1118CBBADC95DA3752C46E47A27438`
* Thumbprint: `5B9E273CF11941FD8C6BE3F038C4797BBE884268`
* Issuer: CN=COMODO RSA Code Signing CA, O=COMODO CA Limited, L=Salford, S=Greater Manchester, C=GB
* Subject: CN=Simon Tatham, O=Simon Tatham, L=Cambridge, S=Cambridgeshire, C=GB

## File Metadata

* Original Filename: PuTTY
* Product Name: PuTTY suite
* Company Name: Simon Tatham
* File Version: Release 0.76 (without embedded help)
* Product Version: Release 0.76
* Language: English (United Kingdom)
* Legal Copyright: Copyright  1997-2021 Simon Tatham.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/2553bf7ac7894f547fa5e7702266b7002cdc3dd42999baece00619bcbab7334f/detection


## Possible Misuse

*The following table contains possible examples of `putty.exe` being misused. While `putty.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_apt_wocao.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_apt_wocao.yml) | `- 'reg query HKEY_CURRENT_USER\Software\\*\PuTTY\Sessions\'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Enumeration for PuTTY Credentials in Registry [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Enumeration for PuTTY Credentials in Registry [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.002/T1552.002.md) | - [Atomic Test #2 - Enumeration for PuTTY Credentials in Registry](#atomic-test-2---enumeration-for-putty-credentials-in-registry) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.002/T1552.002.md) | ## Atomic Test #2 - Enumeration for PuTTY Credentials in Registry | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.002/T1552.002.md) | Queries to enumerate for PuTTY credentials in the Registry. PuTTY must be installed for this test to work. If any registry | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1552.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1552.002/T1552.002.md) | reg query HKCU\Software\SimonTatham\PuTTY\Sessions /t REG_SZ /s | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [generic_anomalies.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/generic_anomalies.yar) | description = "Detects a putty version with a size different than the one provided by Simon Tatham (could be caused by an additional signature or malware)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


