---
title: runas.exe | Run As Utility
excerpt: What is runas.exe?
---

# runas.exe 

* File Path: `C:\Windows\SysWOW64\runas.exe`
* Description: Run As Utility

## Hashes

Type | Hash
-- | --
MD5 | `3C9AD13D268D1DFB106DD8C2017478C2`
SHA1 | `9645690A9F0F22E66259C36DCCECB170EF8B4887`
SHA256 | `C42AB0055B380E36BB4A5E5C3824F7ABFA5BC028B2747743271964065B1EF8BA`
SHA384 | `1028D3B5A1F4CF092E2CBB2BAAF382BA624A731EB568671CDCD7AA07F56861A3A625766AD82107FC4C29920D9657E015`
SHA512 | `3C22DBD4D831746D13198C3BE7149092D2C10873A58D64B291F1A8D447E55C0C54C70DB17A92CE4CE6F08464AFF1A5CAB145DFC604545EE58A0705DAAF4E68CA`
SSDEEP | `384:1jCBBv49184sWKMVaMgYCHq18FuNWWOW:AjY1tjgMT8Fur`
IMP | `63B4267CB5383EAE01A9DE96021E1731`
PESHA1 | `A05DC9552DED89D5DA0AA8BAEFCA3970C8AEBE7D`
PE256 | `78E576A653CC9C414F5BB1979F3AB65BFF8AB5BA977E1CD827E4B3E6CA8093A0`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\runas.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNAS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/c42ab0055b380e36bb4a5e5c3824f7abfa5bc028b2747743271964065b1ef8ba/detection


## Possible Misuse

*The following table contains possible examples of `runas.exe` being misused. While `runas.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_overpass_the_hash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_overpass_the_hash.yml) | `- Runas command-line tool using /netonly parameter` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_exploit_scripts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_powershell_exploit_scripts.yml) | `- '*\Invoke-RunAs.ps1'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_malicious_commandlets.yml) | `- "*Invoke-RunAs*"` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- runas.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `description: Detects changes to HKCU:\Software\Classes\exefile\shell\runas\command\isolatedCommand` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `TargetObject: 'HKU\\*_Classes\exefile\shell\runas\command\isolatedCommand'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Windows uses access tokens to determine the ownership of a running process. A user can manipulate access tokens to make a running process appear as though it belongs to someone other than the user that started the process. When this occurs, the process also takes on the security context associated with the new token. For example, Microsoft promotes the use of access tokens as a security best practice. Administrators should log in as a standard user but run their tools with administrator privileges using the built-in access token manipulation command <code>runas</code>.(Citation: Microsoft runas)\n  \nAdversaries may use access tokens to operate under a different user or system security context to perform actions and evade detection. An adversary can use built-in Windows API functions to copy access tokens from existing processes; this is known as token stealing. An adversary must already be in a privileged user context (i.e. administrator) to steal a token. However, adversaries commonly use token stealing to elevate their security context from the administrator level to the SYSTEM level. An adversary can use a token to authenticate to a remote system as the account for that token if the account has appropriate permissions on the remote system.(Citation: Pentestlab Token Manipulation)\n\nAccess tokens can be leveraged by adversaries through three methods:(Citation: BlackHat Atkinson Winchester Token Manipulation)\n\n**Token Impersonation/Theft** - An adversary creates a new access token that duplicates an existing token using <code>DuplicateToken(Ex)</code>. The token can then be used with <code>ImpersonateLoggedOnUser</code> to allow the calling thread to impersonate a logged on user's security context, or with <code>SetThreadToken</code> to assign the impersonated token to a thread. This is useful for when the target user has a non-network logon session on the system.\n\n**Create Process with a Token** - An adversary creates a new access token with <code>DuplicateToken(Ex)</code> and uses it with <code>CreateProcessWithTokenW</code> to create a new process running under the security context of the impersonated user. This is useful for creating a new process under the security context of a different user.\n\n**Make and Impersonate Token** - An adversary has a username and password but the user is not logged onto the system. The adversary can then create a logon session for the user using the <code>LogonUser</code> function. The function will return a copy of the new session's access token and the adversary can use <code>SetThreadToken</code> to assign the token to a thread.\n\nAny standard user can use the <code>runas</code> command, and the Windows API functions, to create impersonation tokens; it does not require access to an administrator account.\n\nMetasploit’s Meterpreter payload allows arbitrary token manipulation and uses token impersonation to escalate privileges.(Citation: Metasploit access token) The Cobalt Strike beacon payload allows arbitrary token impersonation and can also create tokens. (Citation: Cobalt Strike Access Token)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `lpe-runas-flags` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `runas` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_between-hk-and-burma.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_between-hk-and-burma.yar) | $file8 = "\\Microsoft\\Internet Explorer\\runas.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s2 = "runas" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


