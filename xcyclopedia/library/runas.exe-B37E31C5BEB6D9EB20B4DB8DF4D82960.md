﻿---
title: runas.exe | Run As Utility
excerpt: What is runas.exe?
---

# runas.exe 

* File Path: `C:\Windows\system32\runas.exe`
* Description: Run As Utility

## Hashes

Type | Hash
-- | --
MD5 | `B37E31C5BEB6D9EB20B4DB8DF4D82960`
SHA1 | `29796ACA36A723D625595214E7FDA2735BAE26B2`
SHA256 | `4FA830B5E1794FF72C691B19174C3CAFC8FB4DAE97455560B75866E19A4FFF1A`
SHA384 | `565ABABAAA04EBB19EE9985B75013B1BE75B3CC89658139C9F18C5DD959BF8B13DE1D7D297762ED5D5597801D655E4AC`
SHA512 | `25B8677B9DFCDBCCB127E2FF73E62BA498D8739D1123909CC04BF32F17AA81B6248C547DB2EFB5E0238CE590985ECB842A1DABA7DBDC3D05166A010A40EBB205`
SSDEEP | `384:x13usNRQfKgFEcgEABcSGpSW24GYGYorKq9bOOWSLTOBoV82ydWWOW:7esftQEcgEQi724GzYo9Y6Lgoby7`
IMP | `5B7B2489AAE1B4C266ABE004F393E61C`
PESHA1 | `B48904F8884788E4D53F4234EAD9DF1824925FFD`
PE256 | `BC4866FC6E935F94517A822D10EAE615B11B3C3C123800F40B9C5972663F738D`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\runas.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNAS.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/4fa830b5e1794ff72c691b19174c3cafc8fb4dae97455560b75866e19a4fff1a/detection


## Possible Misuse

*The following table contains possible examples of `runas.exe` being misused. While `runas.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_overpass_the_hash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_overpass_the_hash.yml) | `- Runas command-line tool using /netonly parameter`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_logon_explicit_credentials.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_logon_explicit_credentials.yml) | `- Administrators that use the RunAS command or scheduled tasks`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_powershell_exploit_scripts.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_powershell_exploit_scripts.yml) | `- '\Invoke-RunAs.ps1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_malicious_commandlets.yml) | `- "Invoke-RunAs"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- runas.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_uac_bypass_sdclt.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_uac_bypass_sdclt.yml) | `TargetObject\|endswith: Software\Classes\exefile\shell\runas\command\isolatedCommand`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Windows uses access tokens to determine the ownership of a running process. A user can manipulate access tokens to make a running process appear as though it belongs to someone other than the user that started the process. When this occurs, the process also takes on the security context associated with the new token. For example, Microsoft promotes the use of access tokens as a security best practice. Administrators should log in as a standard user but run their tools with administrator privileges using the built-in access token manipulation command <code>runas</code>.(Citation: Microsoft runas)\n  \nAdversaries may use access tokens to operate under a different user or system security context to perform actions and evade detection. An adversary can use built-in Windows API functions to copy access tokens from existing processes; this is known as token stealing. An adversary must already be in a privileged user context (i.e. administrator) to steal a token. However, adversaries commonly use token stealing to elevate their security context from the administrator level to the SYSTEM level. An adversary can use a token to authenticate to a remote system as the account for that token if the account has appropriate permissions on the remote system.(Citation: Pentestlab Token Manipulation)\n\nAccess tokens can be leveraged by adversaries through three methods:(Citation: BlackHat Atkinson Winchester Token Manipulation)\n\n**Token Impersonation/Theft** - An adversary creates a new access token that duplicates an existing token using <code>DuplicateToken(Ex)</code>. The token can then be used with <code>ImpersonateLoggedOnUser</code> to allow the calling thread to impersonate a logged on user's security context, or with <code>SetThreadToken</code> to assign the impersonated token to a thread. This is useful for when the target user has a non-network logon session on the system.\n\n**Create Process with a Token** - An adversary creates a new access token with <code>DuplicateToken(Ex)</code> and uses it with <code>CreateProcessWithTokenW</code> to create a new process running under the security context of the impersonated user. This is useful for creating a new process under the security context of a different user.\n\n**Make and Impersonate Token** - An adversary has a username and password but the user is not logged onto the system. The adversary can then create a logon session for the user using the <code>LogonUser</code> function. The function will return a copy of the new session's access token and the adversary can use <code>SetThreadToken</code> to assign the token to a thread.\n\nAny standard user can use the <code>runas</code> command, and the Windows API functions, to create impersonation tokens; it does not require access to an administrator account.\n\nMetasploit’s Meterpreter payload allows arbitrary token manipulation and uses token impersonation to escalate privileges.(Citation: Metasploit access token) The Cobalt Strike beacon payload allows arbitrary token impersonation and can also create tokens. (Citation: Cobalt Strike Access Token)",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `lpe-runas-flags`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [rtm](https://github.com/eset/malware-ioc/blob/master/rtm/README.adoc) | `runas`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1207.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1207/T1207.md) | $dc = Start-Process -FilePath cmd.exe -Verb Runas -ArgumentList "/c #{psexec_path} /accepteula -d -s #{mimikatz_path} $mimikatzParam" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | # create batch file with commands to run in a separate "runas /netonly" session | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | # its output goes to golden.txt temp file, because we cannot capture "runas /netonly" output otherwise | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.001/T1558.001.md) | echo "foo" \| runas /netonly /user:fake "$env:TEMP\golden.bat" \| Out-Null | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_between-hk-and-burma.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_between-hk-and-burma.yar) | $file8 = "\\Microsoft\\Internet Explorer\\runas.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s2 = "runas" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


