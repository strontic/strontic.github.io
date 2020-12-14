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
MD5 | `E9021926EC348EED9D128468AEEC81D0`
SHA1 | `00948076C37870B65B7DB5BE924CFCBDB3594B08`
SHA256 | `F633828387901A9F6DB431A410B5F7FE18BDDDC4F630C6A839A46B061E59860E`
SHA384 | `ED4E034A103C566736CDA3E83F5EDBD05E60BDF04DE51C3116FDEE80A4EC5EDB6F7FFAE67456210F46FD2CDE6A30931E`
SHA512 | `43EEC51A571D196C91F3181F73AC681902986B649D786ED8A40D4A0C19E5DAEB822B383FFD337C55F1E1D9EAE4CBBE756A6D5A8BD0388DD24725E82578F7EAAD`
SSDEEP | `384:Tc2IOvX+3WUq4WMeXMsuscYMHudWBOW0Qr:T2MwWTjMTYMHuArr`
IMP | `63B4267CB5383EAE01A9DE96021E1731`
PESHA1 | `2F05B8132672FC1085EBCBB91614E3D42910A668`
PE256 | `8056884FD7022112A2554523811DDC94933E610EEC341BBC5F3188FA960D9A57`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNAS.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/f633828387901a9f6db431a410b5f7fe18bdddc4f630c6a839a46b061e59860e/detection/


## Possible Misuse

*The following table contains possible examples of `runas.exe` being misused. While `runas.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

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


