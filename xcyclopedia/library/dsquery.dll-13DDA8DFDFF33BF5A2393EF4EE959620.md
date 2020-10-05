---
title: dsquery.dll | Directory Service Find
excerpt: What is dsquery.dll?
---

# dsquery.dll 

* File Path: `C:\Windows\system32\dsquery.dll`
* Description: Directory Service Find

## Hashes

Type | Hash
-- | --
MD5 | `13DDA8DFDFF33BF5A2393EF4EE959620`
SHA1 | `002C63CD58DBE7648AC710789D603BD06B1AEF18`
SHA256 | `73447CA6422C5E1EAA8FEA7A53282EBA7512A7935675F2E2F69B1CAAF944A743`
SHA384 | `F53A668E93B53F4A5BDC5BE290AF59157DACE4CA3C157D28CD19738771890D06F9F72420310803878D145E84742AA13C`
SHA512 | `51508E6BE005B66AE107D7BE49C109CB139B19AEF5798D5D85979FFBD6727168A04FC66DF49008656AF5E6F99387E2C9F8EAC3F7FC6990349654640C4C5B2D4E`
SSDEEP | `3072:h3aQWfzFb4L/GtvIbdLv4Us3WFRnKtNSYZObGe:hgLdO/ovIhLwUs3snYZOb`
IMP | `9E787E46E809A16571CCCEC5D72F7785`
PESHA1 | `D8BE5BC31B1C190268547DE0A37E1265224D2FD0`
PE256 | `63A2D8689D6FDF313FB8129F386E0644581ABEAACC2080281690D30FFAD458B6`

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

* Original Filename: dsquery.dll.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/73447ca6422c5e1eaa8fea7a53282eba7512a7935675f2e2f69b1caaf944a743/detection/


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


