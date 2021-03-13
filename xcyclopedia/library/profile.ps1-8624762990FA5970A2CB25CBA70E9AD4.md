---
title: profile.ps1 | 
excerpt: What is profile.ps1?
---

# profile.ps1 

* File Path: `C:\Windows\system32\WindowsPowerShell\v1.0\Examples\profile.ps1`

## Hashes

Type | Hash
-- | --
MD5 | `8624762990FA5970A2CB25CBA70E9AD4`
SHA1 | `30E18F1BB325F85290C85131FC2232C141C8086F`
SHA256 | `9F51461C6BB0FA44DEA4B80D3BFD23E266BA2592E2F4C29D004C7F01A14E078A`
SHA384 | `27D7955AE85AB077385E925A17525C883D3A51AABDFCCACF6071F64EEA1280DC10F4FD5740CE10F2628359DE4FD92033`
SHA512 | `2DBDA62735C575CAE5FBEC87405FE9D128F6797B4710C3CA14232C6CE6509910E122E8BE04A1E8168E90A7A75750889CC2188132BCE146FF76B981E86B9DEEEC`
SSDEEP | `12:/BFNYPy/NytrHuIS03ESKsWHvHUJhOkXC/LJFLUbFQ2A2hPK2bFBJwFaK2yLn:/DOPINkHuIKs4vyhOkXC/LMFjA2hVytL`
PESHA1 | `30E18F1BB325F85290C85131FC2232C141C8086F`
PE256 | `9F51461C6BB0FA44DEA4B80D3BFD23E266BA2592E2F4C29D004C7F01A14E078A`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/9f51461c6bb0fa44dea4b80d3bfd23e266ba2592e2f4c29d004c7f01a14e078a/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\WindowsPowerShell\v1.0\Examples\profile.ps1](profile.ps1-8624762990FA5970A2CB25CBA70E9AD4.md) | 100

## Possible Misuse

*The following table contains possible examples of `profile.ps1` being misused. While `profile.ps1` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_profile_create.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_profile_create.yml) | `title: Powershell Profile.ps1 Modification`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_profile_create.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_profile_create.yml) | `description: Detects a change in profile.ps1 of the Powershell profile`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_profile_create.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_profile_create.yml) | `- '\profile.ps1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.013.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.013/T1546.013.md) | <blockquote>Adversaries may gain persistence and elevate privileges by executing malicious content triggered by PowerShell profiles. A PowerShell profile  (<code>profile.ps1</code>) is a script that runs when [PowerShell](https://attack.mitre.org/techniques/T1059/001) starts and can be used as a logon script to customize user environments. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


