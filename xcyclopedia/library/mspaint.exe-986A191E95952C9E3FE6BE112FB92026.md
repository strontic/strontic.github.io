---
title: mspaint.exe | Paint
excerpt: What is mspaint.exe?
---

# mspaint.exe 

* File Path: `C:\Windows\SysWOW64\mspaint.exe`
* Description: Paint

## Screenshot

![mspaint.exe](screenshots/mspaint.exe-8A6A020DABFB0024BE80D988C59F8F2A-3.png)

## Hashes

Type | Hash
-- | --
MD5 | `986A191E95952C9E3FE6BE112FB92026`
SHA1 | `1E2A48F1088CA5AB78617A7EEB8AA5F62ABD4846`
SHA256 | `8BD3C3D2A3E6285D004AFD50262D80939FA588B39C5ECB404D12D364216E73B2`
SHA384 | `05DCA8E9021857F4AC731191D0DDEE1972DB016DFDAE6914FF91F783D211ABAB02287C883C054ADFC76E5F88DBE8ADBF`
SHA512 | `044294049FED0C5165D2C204D4DFEF8DDC65CBC872D499531A2D4F179E3AE2345142510FFC9C12C32E0C316EAC3250D60B0B316A74A3D7D31B0A9699DC8529F7`
SSDEEP | `12288:fk4MXNLmDguv3NU+5cqI648Hd+qKoN26/XtqG/OqNj+mJ5Fw9qF6fDKog0+QLkR:6XNLmDguF7/4899KoN2OqG/5j15Fw9qb`
IMP | `056D9B704775F8E465E0485902904B4E`
PESHA1 | `85074F0F9492693754DD9882E6B6D4F7C36AB048`
PE256 | `7D7F56CFA17592E07016FA0FD7A6568BB5F3E45709A711C29D910087B56889A9`

## Runtime Data

### Window Title:
Paint

### Open Handles:

Path | Type
-- | --
(R--)   C:\Users\user\--help | File
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\MFC42u.dll.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(R-D)   C:\Windows\SystemResources\mspaint.exe.mun | File
(R-D)   C:\Windows\SysWOW64\en-US\mspaint.exe.mui | File
(R-D)   C:\Windows\SysWOW64\en-US\UIRibbon.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RW-)   C:\Windows\debug\WIA\wiatrace.log | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_11b1e5df2ffd8627 | File
(RW-)   C:\Windows\WinSxS\x86_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.685_none_4299dbb28a92ae3e | File
\BaseNamedObjects\__ComCatalogCache__ | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\BaseNamedObjects\RotHintTable | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\mspaint.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSPAINT.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/8bd3c3d2a3e6285d004afd50262d80939fa588b39c5ecb404d12d364216e73b2/detection


## Possible Misuse

*The following table contains possible examples of `mspaint.exe` being misused. While `mspaint.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\mspaint.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe (a 2009 file)``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `.`mspaint.exe``{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s4 = "mspaint.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


