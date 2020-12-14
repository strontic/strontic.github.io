---
title: TSTheme.exe | TSTheme Server Module
excerpt: What is TSTheme.exe?
---

# TSTheme.exe 

* File Path: `C:\Windows\system32\TSTheme.exe`
* Description: TSTheme Server Module

## Hashes

Type | Hash
-- | --
MD5 | `7F664C2449A91878B131716D2DD79553`
SHA1 | `9BF3F1EF045E15BF6B2B941A67BB4918222DB362`
SHA256 | `0DA195AECD8794062AB5CB3BDEF2BE0230C1E76050C7B11CF609E4F3F23A9DDC`
SHA384 | `9D7526C80131BA671970B3BB7962D61955F2B2708750DE17B20298C3C504D70D1DED7EA58E073DE7BE0D566BCA2E7F9A`
SHA512 | `4986387C88D7165CB8B871C48478235C76B9845F8B3053A093936269C5D2A662A940E385744E001703428945E477D3600899E380854A60D4BC54D582AA6163A9`
SSDEEP | `1536:YhT+AO0YYhOi/oX6CJYX0YOWbKuhuEiiGWv2:Y9+qpoX1U0YOshuEi9W+`
IMP | `B70390445EE6DE87340DFE5CB7439893`
PESHA1 | `D3392E1A944486152FA4C0CF8BA23843E0BBAD34`
PE256 | `66D627187EC252BD70A503D6FB35F0B4B362EA9EC77A67AEC7A86056F2FD9DF0`

## Runtime Data

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\TSTheme.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\RPC Control\DSECA50 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\system32\TSTheme.exe |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TSThemeS.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/0da195aecd8794062ab5cb3bdef2be0230c1e76050c7b11cf609e4f3f23a9ddc/detection/


## Possible Misuse

*The following table contains possible examples of `TSTheme.exe` being misused. While `TSTheme.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\tstheme.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


