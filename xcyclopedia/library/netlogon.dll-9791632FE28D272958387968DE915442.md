---
title: netlogon.dll | Net Logon Services DLL
excerpt: What is netlogon.dll?
---

# netlogon.dll 

* File Path: `C:\Windows\SysWOW64\netlogon.dll`
* Description: Net Logon Services DLL

## Hashes

Type | Hash
-- | --
MD5 | `9791632FE28D272958387968DE915442`
SHA1 | `A8072D8CF65E69AFE3EC1B2DF176294D05E00514`
SHA256 | `7A345A69C79C58E8CC0622F61EB8943CEB87FC9BC4D258CEA6EF15107C82855B`
SHA384 | `5BBB6E2666081DF505744E3C828ED5403DDAFDDFF1617778E7812FDB868024FD2AB790098EAE007A1F5B42898E7018F9`
SHA512 | `6F6933515AC9E217B24ECF52619A7A8047B70149F2CAA314BCE2B9FAD460B3EAAC8A6D350B43A8FC5D8A22DEDE591C2AE590182AC49DA2EC8F7149B91F45D986`
SSDEEP | `12288:cKU3ctTU7C/4uvGj836NnirxCcNyd/GD2lOEyfl5V7Uh:HUst4C/4uvGj836kNrsdeD2lO5fl5V7`
IMP | `3EC7AD974744FC8B691FC2F34160FF9A`
PESHA1 | `18AC9400BCBED5F52285A149790DA7513278C340`
PE256 | `10539F7706811910C7A414FD7200013C0B997C43FDC77AF960EFB13085A5F16F`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`I_NetNotifyMachineAccount` | 16 | Exported Function
`I_NetNotifyNetlogonDllHandle` | 17 | Exported Function
`I_NetNotifyNtdsDsaDeletion` | 18 | Exported Function
`I_NetLogonSetServiceBits` | 13 | Exported Function
`I_NetNotifyDelta` | 14 | Exported Function
`I_NetNotifyDsChange` | 15 | Exported Function
`NetIGetEncTypes` | 22 | Exported Function
`NetILogonSamLogon` | 23 | Exported Function
`NlNetlogonMain` | 24 | Exported Function
`I_NetNotifyRole` | 19 | Exported Function
`I_NetNotifyTrustedDomain` | 20 | Exported Function
`InitSecurityInterfaceW` | 21 | Exported Function
`I_NetLogonCloseChangeLog` | 4 | Exported Function
`I_NetLogonFree` | 5 | Exported Function
`I_NetLogonGetAuthDataEx` | 6 | Exported Function
`DsrGetDcNameEx2` | 1 | Exported Function
`I_NetLogonAddressToSiteName` | 2 | Exported Function
`I_NetLogonAppendChangeLog` | 3 | Exported Function
`I_NetLogonNewChangeLog` | 10 | Exported Function
`I_NetLogonReadChangeLog` | 11 | Exported Function
`I_NetLogonSendToSamOnDc` | 12 | Exported Function
`I_NetLogonGetSerialNumber` | 7 | Exported Function
`I_NetLogonLdapLookupEx` | 8 | Exported Function
`I_NetLogonMixedDomain` | 9 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NetLogon.DLL
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.450 (WinBuild.160101.0800)
* Product Version: 10.0.19041.450
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/7a345a69c79c58e8cc0622f61eb8943ceb87fc9bc4d258cea6ef15107c82855b/detection/


## Possible Misuse

*The following table contains possible examples of `netlogon.dll` being misused. While `netlogon.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [zeek-dce_rpc_domain_user_enumeration.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek-dce_rpc_domain_user_enumeration.yml) | `#- LsarEnumerateTrustedDomains #potentially too many FPs, removing. caused by netlogon` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [zeek_smb_converted_win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/zeek/zeek_smb_converted_win_lm_namedpipe.yml) | `- 'netlogon'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lm_namedpipe.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lm_namedpipe.yml) | `- 'netlogon'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_vul_cve_2020_1472.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_vul_cve_2020_1472.yml) | `title: Vulnerable Netlogon Secure Channel Connection Allowed` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_vul_cve_2020_1472.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_vul_cve_2020_1472.yml) | `description: Detects that a vulnerable Netlogon secure channel connection was allowed, which could be an indicator of CVE-2020-1472.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_vul_cve_2020_1472.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_vul_cve_2020_1472.yml) | `- https://support.microsoft.com/en-us/help/4557222/how-to-manage-the-changes-in-netlogon-secure-channel-connections-assoc` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_logon_scripts_userinitmprlogonscript_proc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_logon_scripts_userinitmprlogonscript_proc.yml) | `- 'netlogon.bat'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_userinit_child.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_userinit_child.yml) | `CommandLine: '*\\netlogon\\*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dumping_ntdsdit_via_netsync.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_dumping_ntdsdit_via_netsync.yml) | `description: ntds.dit retrieving (only computer accounts) using synchronisation with legit domain controller using Netlogon Remote Protocol` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dumping_ntdsdit_via_netsync.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/win_dumping_ntdsdit_via_netsync.yml) | `RelativeTargetName: 'netlogon'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


