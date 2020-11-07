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

Function Name | Ordinal | Type
-- | -- | --
`DsrGetDcNameEx2` | 1 | Exported Function
`NetIGetEncTypes` | 22 | Exported Function
`InitSecurityInterfaceW` | 21 | Exported Function
`I_NetNotifyTrustedDomain` | 20 | Exported Function
`I_NetNotifyRole` | 19 | Exported Function
`I_NetNotifyNtdsDsaDeletion` | 18 | Exported Function
`I_NetNotifyNetlogonDllHandle` | 17 | Exported Function
`I_NetNotifyMachineAccount` | 16 | Exported Function
`I_NetNotifyDsChange` | 15 | Exported Function
`I_NetNotifyDelta` | 14 | Exported Function
`I_NetLogonSetServiceBits` | 13 | Exported Function
`I_NetLogonSendToSamOnDc` | 12 | Exported Function
`I_NetLogonReadChangeLog` | 11 | Exported Function
`I_NetLogonNewChangeLog` | 10 | Exported Function
`I_NetLogonMixedDomain` | 9 | Exported Function
`I_NetLogonLdapLookupEx` | 8 | Exported Function
`I_NetLogonGetSerialNumber` | 7 | Exported Function
`I_NetLogonGetAuthDataEx` | 6 | Exported Function
`I_NetLogonFree` | 5 | Exported Function
`I_NetLogonCloseChangeLog` | 4 | Exported Function
`I_NetLogonAppendChangeLog` | 3 | Exported Function
`I_NetLogonAddressToSiteName` | 2 | Exported Function
`NetILogonSamLogon` | 23 | Exported Function
`NlNetlogonMain` | 24 | Exported Function


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


