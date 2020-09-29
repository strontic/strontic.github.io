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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DsrGetDcNameEx2` | 1 (0x1) | Exported Function | 0x501d2450 | 0x00052450
`NetIGetEncTypes` | 22 (0x16) | Exported Function | 0x501d7a60 | 0x00057a60
`InitSecurityInterfaceW` | 21 (0x15) | Exported Function | 0x501c2f10 | 0x00042f10
`I_NetNotifyTrustedDomain` | 20 (0x14) | Exported Function | 0x501c69a0 | 0x000469a0
`I_NetNotifyRole` | 19 (0x13) | Exported Function | 0x501c6970 | 0x00046970
`I_NetNotifyNtdsDsaDeletion` | 18 (0x12) | Exported Function | 0x501c6900 | 0x00046900
`I_NetNotifyNetlogonDllHandle` | 17 (0x11) | Exported Function | 0x501c68a0 | 0x000468a0
`I_NetNotifyMachineAccount` | 16 (0x10) | Exported Function | 0x501c67a0 | 0x000467a0
`I_NetNotifyDsChange` | 15 (0xf) | Exported Function | 0x501c66c0 | 0x000466c0
`I_NetNotifyDelta` | 14 (0xe) | Exported Function | 0x501c66a0 | 0x000466a0
`I_NetLogonSetServiceBits` | 13 (0xd) | Exported Function | 0x501c6610 | 0x00046610
`I_NetLogonSendToSamOnDc` | 12 (0xc) | Exported Function | 0x501d2d10 | 0x00052d10
`I_NetLogonReadChangeLog` | 11 (0xb) | Exported Function | 0x501c7240 | 0x00047240
`I_NetLogonNewChangeLog` | 10 (0xa) | Exported Function | 0x501c71f0 | 0x000471f0
`I_NetLogonMixedDomain` | 9 (0x9) | Exported Function | 0x501fc270 | 0x0007c270
`I_NetLogonLdapLookupEx` | 8 (0x8) | Exported Function | 0x50203fa0 | 0x00083fa0
`I_NetLogonGetSerialNumber` | 7 (0x7) | Exported Function | 0x501c65b0 | 0x000465b0
`I_NetLogonGetAuthDataEx` | 6 (0x6) | Exported Function | 0x501d2a20 | 0x00052a20
`I_NetLogonFree` | 5 (0x5) | Exported Function | 0x501df000 | 0x0005f000
`I_NetLogonCloseChangeLog` | 4 (0x4) | Exported Function | 0x501c71a0 | 0x000471a0
`I_NetLogonAppendChangeLog` | 3 (0x3) | Exported Function | 0x501c7170 | 0x00047170
`I_NetLogonAddressToSiteName` | 2 (0x2) | Exported Function | 0x501e7240 | 0x00067240
`NetILogonSamLogon` | 23 (0x17) | Exported Function | 0x501d3170 | 0x00053170
`NlNetlogonMain` | 24 (0x18) | Exported Function | 0x501e2940 | 0x00062940


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

*The following table contains possible examples of `netlogon.dll` being misused. While `netlogon.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


