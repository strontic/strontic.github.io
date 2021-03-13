---
title: ScriptRunner.exe |  
excerpt: What is ScriptRunner.exe?
---

# ScriptRunner.exe 

* File Path: `C:\Windows\system32\ScriptRunner.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `C64357854C5214AC178B78EF1A17042F`
SHA1 | `464B383C00C609B633191FAFC93D72685653C832`
SHA256 | `267D6422A1AE5E633A04129388FC8BEC82FD751E0130E5998F1168BEFEC38058`
SHA384 | `A10621E8323F8809AF7015DF8AC8E701C39CFD0BD271D34DB6003A5B644C920A5C263FC7F1413755802BCA12FF5F8B07`
SHA512 | `2E610EBF219F5B7519B774FFD2029A28EC387E7709C695B7EE66AB261C83606203C44D1F3DA054E0A0727C0E9E8946DB9D7CE0ED60E964FBA672D03595D7B178`
SSDEEP | `384:+9z/IFagu/0Ei6yymaWl4wWHer6wDDBRJ5Sifl+Puh+9:yzKG/0TLyRBer6wD1PP69`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `56328C4174DD67123BA5334C96FAE9FBDB20D5F2`
PE256 | `BB3E29AB0705957FD7EFE7F15F4587E3618B275582DCDF53000A91BD7518A2B1`

## Runtime Data

### Usage (stdout):
```cmhg
Invalid argument specified: --help
Usage:
ScriptRunner.exe
-appvscript scriptFileName [Arguments] [-appvscriptrunnerparameters [-wait] [-timeout=<TimeInSeconds>] [-rollbackonerror]] 
-appvscript scriptFileName [Arguments] [-appvscriptrunnerparameters [-wait] [-timeout=<TimeInSeconds>] [-rollbackonerror]] 
...
Default values for -appvscriptrunnerparameters: No wait, No timeout, No rollback on error
Every parameter must be separated by a unicode space character (U+0020)
Example:
ScriptRunner.exe -appvscript foo.cmd arg1 arg2 -appvscriptrunnerparameters -wait -timeout=30 -rollbackonerror -appvscript foobar.exe arg1 arg2
Error: Invalid argument specified

```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\ScriptRunner.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScriptRunner.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.488
* Product Version: 10.0.19041.488
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/267d6422a1ae5e633a04129388fc8bec82fd751e0130e5998f1168befec38058/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll](6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll-513E16B14C2E8DE6AEA439153A9733FD.md) | 43
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-ABA7E7513886979AF8A3B68A1F4E591D.md) | 29
[C:\Windows\system32\LocationFrameworkPS.dll](LocationFrameworkPS.dll-FBF3B3CCC037AD1D9FC36C28D0E29A25.md) | 33
[C:\Windows\system32\migwiz\migres.dll](migres.dll-E937B164DC2D2A03490AC3EB9D5875B2.md) | 36
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-09C06B0224F439DF8666CF7B411B7B1C.md) | 43
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-5D20EF28D0B222CA57F47524F2D3E8C0.md) | 41
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 50
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 74
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 57
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-E099F50577EC360B96513A9251480D99.md) | 43
[C:\Windows\system32\WerEnc.dll](WerEnc.dll-57896D83DAD20250B3878747AB6115F6.md) | 30
[C:\Windows\SystemApps\MicrosoftWindows.UndockedDevKit_cw5n1h2txyewy\UndockedDevKit.exe](UndockedDevKit.exe-C1FD0D396683E3F59646E4CEC2A55A85.md) | 36
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-F290D12F0351B56708B3DF1EC26CB45B.md) | 32
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-6F3C9485F8F97AC04C8E43EF4463A68C.md) | 32
[C:\Windows\SysWOW64\WerEnc.dll](WerEnc.dll-F4C2183256B20B62EBD7C9397F0C5D85.md) | 40

## Possible Misuse

*The following table contains possible examples of `ScriptRunner.exe` being misused. While `ScriptRunner.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\scriptrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\scriptrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `Name: Scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: Scriptrunner.exe -appvscript calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: ScriptRunner.exe -appvscript "\\fileserver\calc.cmd"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\System32\scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\SysWOW64\scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- IOC: Scriptrunner.exe should not be in use unless App-v is deployed`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


