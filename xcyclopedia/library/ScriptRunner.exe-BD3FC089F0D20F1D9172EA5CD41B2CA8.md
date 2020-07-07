---
title: ScriptRunner.exe |  
---

# ScriptRunner.exe 

* File Path: `C:\Windows\system32\ScriptRunner.exe`
* Description:  
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `BD3FC089F0D20F1D9172EA5CD41B2CA8`
SHA1 | `52FFADEAFD6FB0C316823DF0B799B63EF1143E8E`
SHA256 | `24F4845C08B5629C78DE41C46411404EC822390F54431205E66D212E620E4F64`
SHA384 | `34FFD728215C172031831F9246F47E51F3F312CAB7B37A4B852D9F0A2F15B4FAD323A0BFDF9B23DB262FAA1D6B298C75`
SHA512 | `858B32A5641BBB4678BD0B67EBEC671D0C370A8D80D717E59BB2FDED848BC59B7BC51BE96F44A41DF0F326A7A4EFD8B52F7B89D6FDD0E1ECBEB209C852FC226B`
SSDEEP | `384:u9z/IFagu/0Ei6yymcWlUwWPr6wDDBRJl5uOMlh2LA:CzKG/0TLy/Fr6wD1PfRA`

## Runtime Data

### Usage (stdout):
```Batchfile
Invalid argument specified: /h
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

### Usage (stderr):
```Batchfile

```

### Child Processes:


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
* File Version: 10.0.19041.264
* Product Version: 10.0.19041.264
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 50
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 57
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-E099F50577EC360B96513A9251480D99.md) | 46

## Possible Misuse

*The following table contains possible examples of `ScriptRunner.exe` being misused. While `ScriptRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `            - '\scriptrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `            - '*\scriptrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `Name: Scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `  - Command: Scriptrunner.exe -appvscript calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `  - Command: ScriptRunner.exe -appvscript "\\fileserver\calc.cmd"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `  - Path: C:\Windows\System32\scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `  - Path: C:\Windows\SysWOW64\scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | ` - IOC: Scriptrunner.exe should not be in use unless App-v is deployed` | 



MIT License. Copyright (c) 2020 Strontic.


