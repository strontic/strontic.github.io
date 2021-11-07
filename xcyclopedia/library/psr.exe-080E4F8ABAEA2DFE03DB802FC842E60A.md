---
title: psr.exe | Steps Recorder
excerpt: What is psr.exe?
---

# psr.exe 

* File Path: `C:\Windows\system32\psr.exe`
* Description: Steps Recorder

## Hashes

Type | Hash
-- | --
MD5 | `080E4F8ABAEA2DFE03DB802FC842E60A`
SHA1 | `DBD7D7E8A9AEBD5AA615F5FDC970F9C231A34F0C`
SHA256 | `88160871721148021A86D945BCB04FCD483776FF3F1480DE33EA8FD56BF4EA87`
SHA384 | `6A84E3CF50BCF8141D0821EC07634CF43AA7BC599213AE05A5BB4218AAE64535CC41A17F87FE66DF1E751C9A98546E3C`
SHA512 | `404D9746956325B1B4F1BED2D7E73CF182C6A47D5066961677DF08BC005EB45B60AD20D5545DAAD010CA806480CB83723B96BBB7FA37BC6370BF6CDE1C85E8C3`
SSDEEP | `6144:KnH4+bmsLdjcwQjk/g3SvUnOwi0Lpi8Qgm:KnH4mu95ivqOwiECg`
IMP | `03EDC1179F035D69376C75EFF57B51D0`
PESHA1 | `5DAB4BB28A360494086DA57FD2A2508A46800703`
PE256 | `4CF7C0D4F1BF9B89F310CD8E15DEC7EA393DC0C084AD6A05DE46C9B394A39B5D`

## Runtime Data

### Window Title:
Steps Recorder Error

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\Fonts\StaticCache.dat | File
(R-D)   C:\Windows\System32\en-US\psr.exe.mui | File
(R-D)   C:\Windows\SystemResources\imageres.dll.mun | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21 | File
(RW-)   C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.685_none_faeca4db76168538 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\Windows\Theme1175649999 | Section
\Windows\Theme601709542 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\psr.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.19041.488_none_ca04af081b815d21\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: psr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/88160871721148021a86d945bcb04fcd483776ff3f1480de33ea8fd56bf4ea87/detection


## Possible Misuse

*The following table contains possible examples of `psr.exe` being misused. While `psr.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `title: Psr.exe Capture Screenshots`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `description: The psr.exe captures desktop screenshots and saves them on the local machine`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psr_capture_screenshots.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psr_capture_screenshots.yml) | `Image\|endswith: '\Psr.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `Name: Psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /start /gui 0 /output c:\users\user\out.zip`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /start /maxsc 100 /gui 0 /output c:\users\user\out.zip`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `- Command: psr.exe /stop`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `- C:\Windows\System32\Psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Psr.yml) | `- C:\Windows\SysWOW64\Psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `Name: Psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Command: psr.exe /start /output D:\test.zip /sc 1 /gui 0`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `Description: Record a user screen without creating a GUI. You should use "psr.exe /stop" to stop recording and create output file.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Path: c:\windows\system32\psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- Path: c:\windows\syswow64\psr.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Psr.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Psr.yml) | `- IOC: psr.exe spawned`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | Use Psr.exe binary to collect screenshots of user display. Test will do left mouse click to simulate user behaviour | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | cmd /c start /b psr.exe /start /output #{output_file} /sc 1 /gui 0 /stopevent 12 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1113.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1113/T1113.md) | cmd /c "timeout #{recording_time} > NULL && psr.exe /stop" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


