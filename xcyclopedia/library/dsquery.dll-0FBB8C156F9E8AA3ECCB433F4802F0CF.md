---
title: dsquery.dll | Directory Service Find
excerpt: What is dsquery.dll?
---

# dsquery.dll 

* File Path: `C:\Windows\SysWOW64\dsquery.dll`
* Description: Directory Service Find

## Hashes

Type | Hash
-- | --
MD5 | `0FBB8C156F9E8AA3ECCB433F4802F0CF`
SHA1 | `E03870CB2C170B0F28792B61B76A96F683BB113A`
SHA256 | `CB04463FE3CBCD54E5D95BAF9909F8809645CC81E3F5162AA46E66B0FB2C630B`
SHA384 | `3962DD6699C664094ECD6BC95C47B51BF4D66B727CFFA10549EB15A5666AA452EDCC5B55678A257D900566B6BF488F9A`
SHA512 | `1F02A91D0D952017AB0F890315AAC1CE8260350ED91D9E523B5AF33DCDC95EAE819B89F1CCE6E875E53DBDFB8199E40DB8EAA62E8F71B00548FD6E3426FB1DF9`
SSDEEP | `3072:HkjHLcTSfTlF1jkQoKC/cY60sATgVj/rcC:EfcTSJF1jvfCUY60sFN/r`
IMP | `9D0AF265A6A779CE145B8B7C6FAE48BD`
PESHA1 | `4565473189D84AFF8BFC5100E4E8A08B81F4391C`
PE256 | `2B778EF17E9EE8193A9083D0C26795EF5A11CE97F8882C105EA36610D6DE00A7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`OpenQueryWindow` | 258 | Exported Function
`DllUnregisterServer` | 263 | Exported Function
`OpenSavedDsQueryW` | 257 | Exported Function
`OpenSavedDsQuery` | 256 | Exported Function
`DllGetClassObject` | 260 | Exported Function
`DllCanUnloadNow` | 259 | Exported Function
`DllRegisterServer` | 262 | Exported Function
`DllInstall` | 261 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dsquery.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/cb04463fe3cbcd54e5d95baf9909f8809645cc81e3f5162aa46e66b0fb2c630b/detection/


## Possible Misuse

*The following table contains possible examples of `dsquery.dll` being misused. While `dsquery.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_dsquery_domain_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dsquery_domain_trust_discovery.yml) | `- Image\|endswith: '\dsquery.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- dsquery.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `description: Identifies execution of nltest.exe and dsquery.exe for domain trust discovery. This technique is used by attackers to enumerate Active Directory trusts.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `- Image\|endswith: '\dsquery.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "Adversaries may attempt to get a listing of local system or domain accounts. \n\n### Windows\n\nExample commands that can acquire this information are <code>net user</code>, <code>net group <groupname></code>, and <code>net localgroup <groupname></code> using the [Net](https://attack.mitre.org/software/S0039) utility or through use of [dsquery](https://attack.mitre.org/software/S0105). If adversaries attempt to identify the primary user, currently logged in user, or set of users that commonly uses a system, [System Owner/User Discovery](https://attack.mitre.org/techniques/T1033) may apply.\n\n### Mac\n\nOn Mac, groups can be enumerated through the <code>groups</code> and <code>id</code> commands. In mac specifically, <code>dscl . list /Groups</code> and <code>dscacheutil -q group</code> can also be used to enumerate groups and users.\n\n### Linux\n\nOn Linux, local users can be enumerated through the use of the <code>/etc/passwd</code> file which is world readable. In mac, this same file is only used in single-user mode in addition to the <code>/etc/master.passwd</code> file.\n\nAlso, groups can be enumerated through the <code>groups</code> and <code>id</code> commands.\n\n### Office 365 and Azure AD\n\nWith authenticated access there are several tools that can be used to find accounts. The <code>Get-MsolRoleMember</code> PowerShell cmdlet can be used to obtain account names given a role or permissions group.(Citation: Microsoft msolrolemember)(Citation: GitHub Raindance)\n\nAzure CLI (AZ CLI) also provides an interface to obtain user accounts with authenticated access to a domain. The command <code>az ad user list</code> will list all users within a domain.(Citation: Microsoft AZ CLI)(Citation: Black Hills Red Teaming MS AD Azure, 2018) \n\nThe <code>Get-GlobalAddressList</code> PowerShell cmdlet can be used to obtain email addresses and accounts from a domain using an authenticated session.(Citation: Microsoft getglobaladdresslist)(Citation: Black Hills Attacking Exchange MailSniper, 2016)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: Windows - Discover domain trusts with dsquery [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: Windows - Discover domain trusts with dsquery [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | - [Atomic Test #1 - Windows - Discover domain trusts with dsquery](#atomic-test-1---windows---discover-domain-trusts-with-dsquery) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | ## Atomic Test #1 - Windows - Discover domain trusts with dsquery | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | Uses the dsquery command to discover domain trusts. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | Requires the installation of dsquery via Windows RSAT or the Windows Server AD DS role. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | dsquery * -filter "(objectClass=trustedDomain)" -attr * | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


