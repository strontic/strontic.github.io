---
title: ScriptRunner.exe |  
---

# ScriptRunner.exe 

* File Path: `C:\WINDOWS\system32\ScriptRunner.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `C024FF9A88E26EEB26A1A942260489BC`
SHA1 | `0190BAD268F28BBDC5B27BB952A98E70184FE569`
SHA256 | `973A32DD7CC4FAE82A5A5A86F61D3CC5BF8C8C8D4B3C9D0ACC392398780E33DC`
SHA384 | `0DCC0898520322B38FE36F6C258044515094C5FBCC0DAB8187CF5F691A1C09101687C0A1501B71BE1ACBDDE2832ACB1F`
SHA512 | `2FE2BA7A3BB5C8EE0F9A717CE4980E921D9A849F54BACEB9A9586984613B5EF46BC4F53C05CC23224ABD72F078DE44C13B4A2CDCD0D05B803BA72F3A2536B972`
SSDEEP | `384:u9zXIqagu/0Ei6wmsWl5wWJSD1IDBRJtA02l9n1k:CzdG/0T32GI1Pb`

## Runtime Data

### Usage (stdout):
```cmhg
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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScriptRunner.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.815
* Product Version: 10.0.18362.815
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Common Files\Microsoft Shared\ink\TabTip32.exe](TabTip32.exe-DCB3378628CC715C93B9D53DF1857029.md) | 33
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 32
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-8159944C79034D2BCABF73D461A7E643.md) | 25
[C:\WINDOWS\system32\DeviceCensus.exe](DeviceCensus.exe-AC7BD0E738FDE12FB29DA98D88C903EA.md) | 29
[C:\Windows\system32\dllhost.exe](dllhost.exe-C6723950D1A8CD49D93C8D082B175D41.md) | 36
[C:\Windows\system32\NDKPing.exe](NDKPing.exe-5FC26E00B9012CC0188F65BB999174E9.md) | 33
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-EA059E3BA7E07347BDE08EF016E09D50.md) | 33
[C:\Windows\system32\prproc.exe](prproc.exe-912400A90CA88E80ABC6CB8F30C1BB41.md) | 36
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-100E032F234550530487627EC8FACAA8.md) | 35
[C:\WINDOWS\system32\ResetEngine.exe](ResetEngine.exe-5A802B773089A709FC7E731368C4E328.md) | 41
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-71B9062F02950BAA4441E2FB79677E99.md) | 58
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 57
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-E099F50577EC360B96513A9251480D99.md) | 47
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-FD18CDC89BFD664E85644B460C37D85B.md) | 36
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-7582BF723A39B56BCCEF2C170E330BD7.md) | 32
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 35
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-AB2C7BC86F9E1BB245E43C81A01A7380.md) | 29
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-BE467A8F33CDEB0538E98CF10101E9E0.md) | 32

## Possible Misuse

*The following table contains possible examples of `ScriptRunner.exe` being misused. While `ScriptRunner.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\scriptrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\scriptrunner.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `Name: Scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: Scriptrunner.exe -appvscript calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Command: ScriptRunner.exe -appvscript "\\fileserver\calc.cmd"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\System32\scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- Path: C:\Windows\SysWOW64\scriptrunner.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Scriptrunner.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Scriptrunner.yml) | `- IOC: Scriptrunner.exe should not be in use unless App-v is deployed` | 



MIT License. Copyright (c) 2020 Strontic.


