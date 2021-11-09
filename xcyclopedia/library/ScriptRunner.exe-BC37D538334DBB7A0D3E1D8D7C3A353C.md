---
title: ScriptRunner.exe |  
excerpt: What is ScriptRunner.exe?
---

# ScriptRunner.exe 

* File Path: `C:\WINDOWS\system32\ScriptRunner.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `BC37D538334DBB7A0D3E1D8D7C3A353C`
SHA1 | `B78EE40C8AB482B7EA42A210A402432101DFF031`
SHA256 | `D6F41E2EE1A83E96EB6D0D24E1F924673F3C5DF51579D8567504E0E15D4C9DEB`
SHA384 | `990B5D566838FA57D68CB69CECD5D5908E3A602C645F0E6446906B8F99FE1A15B9275467CA7AE2A70F2A2B8EE9E8DE36`
SHA512 | `CB3B7B58F8F91F42D02A92BACDF0D508969309E188A475D0EBBB5A12FFDFD8B4C3654CC4A352E31B71AF4DE20D9E471AC6F43B58B40B5597D5AC70FE899EB6EC`
SSDEEP | `384:KpJmagu/0Ei6EF7WljwWRDBRJT5dNl87zwg:aEG/0T/U71PwD`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `2A2B988EEE310691D1751A48F71711B78F745315`
PE256 | `0ACB57C0AC2CDE18C64CF255F723E5D436578D41278718E0CB3B522C45FE1BDF`

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
C:\WINDOWS\System32\KERNEL32.dll |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\MSCOREE.DLL |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\ScriptRunner.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScriptRunner.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.282
* Product Version: 10.0.22000.282
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/d6f41e2ee1a83e96eb6d0d24e1f924673f3c5df51579d8567504e0e15d4c9deb/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 46
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 47
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 47
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-C64357854C5214AC178B78EF1A17042F.md) | 47
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-E099F50577EC360B96513A9251480D99.md) | 52
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-EA8C42A5C14B808D6B73AC5A6A871379.md) | 46

## Possible Misuse

*The following table contains possible examples of `ScriptRunner.exe` being misused. While `ScriptRunner.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\scriptrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\scriptrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_servu_process_pattern.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_servu_process_pattern.yml) | `- '\scriptrunner.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `Name: Scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: Scriptrunner.exe -appvscript calc.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: ScriptRunner.exe -appvscript "\\fileserver\calc.cmd"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\System32\scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\SysWOW64\scriptrunner.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- IOC: Scriptrunner.exe should not be in use unless App-v is deployed`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


