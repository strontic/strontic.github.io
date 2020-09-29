---
title: netlogon.dll | Net Logon Services DLL
excerpt: What is netlogon.dll?
---

# netlogon.dll 

* File Path: `C:\Windows\system32\netlogon.dll`
* Description: Net Logon Services DLL

## Hashes

Type | Hash
-- | --
MD5 | `70FABD4BE2CD7091F7D1C2DC194D15E2`
SHA1 | `2B39EE2448EBA5C4BD24FC23592DEB8BFF3F95BB`
SHA256 | `781E04607E5D5FA85A97ADDE90BBEC137447B105BC35730093884CCC476FBD90`
SHA384 | `D30B4663E2CAD5C309BFBFE505A89A766F97EB335E857F01E2030A3F97E16A61A59EBCC37042009BDDA05D5F6891ED58`
SHA512 | `6D090093CD15A6698D00A58B516433332C28EE9E69D51ED3AE5D3E5F69D9D83E5553958C84FA58EBC09FD98FCC4AA118A417708EB4429DA3B9EF85A16774BF91`
SSDEEP | `12288:pHPD32gRjyQEA1+PGwUF0/6HAVBEsI/YwtdLQ72rbEWZWvttDzBzf2:hAAqUS/6HAV+sI/YwtxtH1Wt/zf`
IMP | `9AE0211E050634FD33379B7B032E0F6B`
PESHA1 | `8DBE1EFF43DFF10E1D1F145AF8AF5FA087964B73`
PE256 | `56CCD15A60A70DE9496CAB68A25A18031FBC0C6CFBB88D39E9BB2715F5BE3DCC`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DsrGetDcNameEx2` | 1 (0x1) | Exported Function | 0x00000001800145c0 | 0x000145c0
`NetIGetEncTypes` | 22 (0x16) | Exported Function | 0x0000000180025df0 | 0x00025df0
`InitSecurityInterfaceW` | 21 (0x15) | Exported Function | 0x0000000180027b80 | 0x00027b80
`I_NetNotifyTrustedDomain` | 20 (0x14) | Exported Function | 0x0000000180047530 | 0x00047530
`I_NetNotifyRole` | 19 (0x13) | Exported Function | 0x0000000180005780 | 0x00005780
`I_NetNotifyNtdsDsaDeletion` | 18 (0x12) | Exported Function | 0x0000000180047480 | 0x00047480
`I_NetNotifyNetlogonDllHandle` | 17 (0x11) | Exported Function | 0x0000000180047410 | 0x00047410
`I_NetNotifyMachineAccount` | 16 (0x10) | Exported Function | 0x0000000180008a10 | 0x00008a10
`I_NetNotifyDsChange` | 15 (0xf) | Exported Function | 0x00000001800472e0 | 0x000472e0
`I_NetNotifyDelta` | 14 (0xe) | Exported Function | 0x00000001800472c0 | 0x000472c0
`I_NetLogonSetServiceBits` | 13 (0xd) | Exported Function | 0x0000000180006c40 | 0x00006c40
`I_NetLogonSendToSamOnDc` | 12 (0xc) | Exported Function | 0x000000018004e900 | 0x0004e900
`I_NetLogonReadChangeLog` | 11 (0xb) | Exported Function | 0x0000000180047c20 | 0x00047c20
`I_NetLogonNewChangeLog` | 10 (0xa) | Exported Function | 0x0000000180047bd0 | 0x00047bd0
`I_NetLogonMixedDomain` | 9 (0x9) | Exported Function | 0x0000000180064c90 | 0x00064c90
`I_NetLogonLdapLookupEx` | 8 (0x8) | Exported Function | 0x000000018001b500 | 0x0001b500
`I_NetLogonGetSerialNumber` | 7 (0x7) | Exported Function | 0x0000000180027550 | 0x00027550
`I_NetLogonGetAuthDataEx` | 6 (0x6) | Exported Function | 0x000000018004e540 | 0x0004e540
`I_NetLogonFree` | 5 (0x5) | Exported Function | 0x0000000180025d10 | 0x00025d10
`I_NetLogonCloseChangeLog` | 4 (0x4) | Exported Function | 0x0000000180047b80 | 0x00047b80
`I_NetLogonAppendChangeLog` | 3 (0x3) | Exported Function | 0x0000000180047b40 | 0x00047b40
`I_NetLogonAddressToSiteName` | 2 (0x2) | Exported Function | 0x0000000180059360 | 0x00059360
`NetILogonSamLogon` | 23 (0x17) | Exported Function | 0x0000000180012bb0 | 0x00012bb0
`NlNetlogonMain` | 24 (0x18) | Exported Function | 0x0000000180023fb0 | 0x00023fb0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: NetLogon.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/781e04607e5d5fa85a97adde90bbec137447b105bc35730093884ccc476fbd90/detection/


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


