---
title: nltest.exe | Microsoft Logon Server Test Utility
excerpt: What is nltest.exe?
---

# nltest.exe 

* File Path: `C:\Windows\system32\nltest.exe`
* Description: Microsoft Logon Server Test Utility

## Hashes

Type | Hash
-- | --
MD5 | `396EC29E0B1F77824E6479D8D810D315`
SHA1 | `5E2FEB9DD4EF65A59579A53BF6240E1A630ADAC4`
SHA256 | `A0AB27588BAA72C13F1BDD3A59CC6B76B1C9789EF9E30F0B8BEF968316BE77B5`
SHA384 | `B0C1FA42B5F40A8803D7B2F9F3A62ABA9F66B53DD495ACD241465432A6E98BA428EFFB9FD40C6D8FCA6FA421374BA93C`
SHA512 | `EAC37CAE455A235959028FD8C68DEFD8806ACA07E2BAEB197D8B0EEA68A086781F1BADBDF6617DB0F93E1ED2E8EBF20BCA36F6AF6C6921BCFA1311C586DC9140`
SSDEEP | `6144:fhCtTfmDzLPxjpOMUoikXV3OV87zWzN0cOXXn3:f4q/PxjpEzJ`
IMP | `BDE16641FA6CCBD4479899C4CA44D983`
PESHA1 | `39B470A4537784860CDAE537B1C2221CE902ECE3`
PE256 | `07C4C6449B0C92752B301F34A28EB76C6D8FBB7D60A7A8D6F0DC4341084B1144`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: nltest [/OPTIONS]


    /SERVER:<ServerName> - Specify <ServerName>

    /QUERY - Query <ServerName> netlogon service
    /REPL - Force partial sync on <ServerName> BDC
    /SYNC - Force full sync on <ServerName> BDC
    /PDC_REPL - Force UAS change message from <ServerName> PDC

    /SC_QUERY:<DomainName> - Query secure channel for <Domain> on <ServerName>
    /SC_RESET:<DomainName>[\<DcName>] - Reset secure channel for <Domain> on <ServerName> to <DcName>
    /SC_VERIFY:<DomainName> - Verify secure channel for <Domain> on <ServerName>
    /SC_CHANGE_PWD:<DomainName> - Change a secure channel  password for <Domain> on <ServerName>
    /DCLIST:<DomainName> - Get list of DC's for <DomainName>
    /DCNAME:<DomainName> - Get the PDC name for <DomainName>
    /DSGETDC:<DomainName> - Call DsGetDcName /PDC /DS /DSP /GC /KDC
        /TIMESERV /GTIMESERV /WS /NETBIOS /DNS /IP /FORCE /WRITABLE /AVOIDSELF /LDAPONLY /BACKG /DS_6 /DS_8 /DS_9 /DS_10
        /KEYLIST /TRY_NEXT_CLOSEST_SITE /SITE:<SiteName> /ACCOUNT:<AccountName> /RET_DNS /RET_NETBIOS
    /DNSGETDC:<DomainName> - Call DsGetDcOpen/Next/Close /PDC /GC
        /KDC /WRITABLE /LDAPONLY /FORCE /SITESPEC
    /DSGETFTI:<DomainName> - Call DsGetForestTrustInformation
        /UPDATE_TDO
    /DSGETSITE - Call DsGetSiteName
    /DSGETSITECOV - Call DsGetDcSiteCoverage
    /DSADDRESSTOSITE:[MachineName] - Call DsAddressToSiteNamesEx
        /ADDRESSES:<Address1,Address2,...>
    /PARENTDOMAIN - Get the name of the parent domain of this machine
    /WHOWILL:<Domain>* <User> [<Iteration>] - See if <Domain> will log on <User>
    /FINDUSER:<User> - See which trusted domain will log on <User>
    /TRANSPORT_NOTIFY - Notify netlogon of new transport

    /DBFLAG:<HexFlags> - New debug flag

    /USER:<UserName> - Query User info on <ServerName>

    /TIME:<Hex LSL> <Hex MSL> - Convert NT GMT time to ascii
    /LOGON_QUERY - Query number of cumulative logon attempts
    /DOMAIN_TRUSTS - Query domain trusts on <ServerName>
        /PRIMARY /FOREST /DIRECT_OUT /DIRECT_IN /ALL_TRUSTS /V
    /DSREGDNS - Force registration of all DC-specific DNS records
    /DSDEREGDNS:<DnsHostName> - Deregister DC-specific DNS records for specified DC
        /DOM:<DnsDomainName> /DOMGUID:<DomainGuid> /DSAGUID:<DsaGuid>
    /DSQUERYDNS - Query the status of the last update for all DC-specific DNS records

    /BDC_QUERY:<DomainName> - Query replication status of BDCs for <DomainName>

    /LIST_DELTAS:<FileName> - display the content of given change log file 

    /CDIGEST:<Message> /DOMAIN:<DomainName> - Get client digest
    /SDIGEST:<Message> /RID:<RID in hex> - Get server digest

    /SHUTDOWN:<Reason> [<Seconds>] - Shutdown <ServerName> for <Reason>
    /SHUTDOWN_ABORT - Abort a system shutdown


```

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\nltest.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nltestrk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/a0ab27588baa72c13f1bdd3a59cc6b76b1c9789ef9e30f0b8bef968316be77b5/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\tracefmt.exe](tracefmt.exe-1A132D3C750C4F6E6A49DD0B15037A01.md) | 35
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\tracefmt.exe](tracefmt.exe-A02AC40EA76F0B6AFE2C9FF49BB15692.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\winxp\wmitrace.dll](wmitrace.dll-6C8CAEA4F842FCA3FFE733AB4D9C82F5.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winext\rcdrkd.dll](rcdrkd.dll-17D72886BD70CE923FAB6A6427360028.md) | 41
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\winxp\wmitrace.dll](wmitrace.dll-2B386CB3C2E87D0AE428CDA7EB809640.md) | 29
[C:\Program Files (x86)\Windows Kits\10\Windows Performance Toolkit\perf_wpp.dll](perf_wpp.dll-5570A1894C91C49766FFF4CFDB1BE221.md) | 43
[C:\Windows\system32\nltest.exe](nltest.exe-0C96FBA0F1ABEEF164B077D34F5B6F6A.md) | 35
[C:\Windows\system32\nltest.exe](nltest.exe-1CC927B2EC04AAD119D2C6BD2194DA1F.md) | 33
[C:\Windows\system32\nshwfp.dll](nshwfp.dll-366C76832A6A12850407BF16F2D22441.md) | 35

## Possible Misuse

*The following table contains possible examples of `nltest.exe` being misused. While `nltest.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_nltest.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lolbas_execution_of_nltest.yml) | `title: Correct Execution of Nltest.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_nltest.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lolbas_execution_of_nltest.yml) | `description: The attacker might use LOLBAS nltest.exe for discovery of domain controllers, domain trusts, parent domain and the current user permissions.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_nltest.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lolbas_execution_of_nltest.yml) | `- https://jpcertcc.github.io/ToolAnalysisResultSheet/details/nltest.htm`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_nltest.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lolbas_execution_of_nltest.yml) | `- attack.t1482 # enumerate trusted domains by using commands such as nltest /domain_trusts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_lolbas_execution_of_nltest.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_lolbas_execution_of_nltest.yml) | `ProcessName\|endswith: nltest.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_trickbot_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_trickbot_recon_activity.yml) | `- '\nltest.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_nltest_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_nltest_recon.yml) | `title: Recon Activity with NLTEST`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_nltest_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_nltest_recon.yml) | `description: Detects nltest commands that can be used for information discovery`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_nltest_recon.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_nltest_recon.yml) | `Image\|endswith: '\nltest.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `- \nltest.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `description: Identifies execution of nltest.exe and dsquery.exe for domain trust discovery. This technique is used by attackers to enumerate Active Directory trusts.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `Image\|endswith: '\nltest.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Nltest.yml) | `Name: Nltest.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Nltest.yml) | `- Command: nltest.exe /SERVER:192.168.1.10 /QUERY`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Nltest.yml) | `- c:\windows\system32\nltest.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/Archive-Old-Version/LOLUtilz/OSBinaries/Nltest.yml) | `- https://ss64.com/nt/nltest.html`{:.highlight .language-yaml} | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #2: Windows - Discover domain trusts with nltest [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #3: Remote System Discovery - nltest [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #2: Windows - Discover domain trusts with nltest [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #3: Remote System Discovery - nltest [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn `ipconfig /all`, `net config workstation`, `net view /all /domain`, `nltest /domain_trusts`. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | nltest /domain_trusts | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | - [Atomic Test #3 - Remote System Discovery - nltest](#atomic-test-3---remote-system-discovery---nltest) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | ## Atomic Test #3 - Remote System Discovery - nltest | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute nltest.exe against a target domain to retrieve a list of domain controllers. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | nltest.exe /dclist:#{target_domain} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | <blockquote>Adversaries may attempt to gather information on domain trust relationships that may be used to identify lateral movement opportunities in Windows multi-domain/forest environments. Domain trusts provide a mechanism for a domain to allow access to resources based on the authentication procedures of another domain.(Citation: Microsoft Trusts) Domain trusts allow the users of the trusted domain to access resources in the trusting domain. The information discovered may help the adversary conduct [SID-History Injection](https://attack.mitre.org/techniques/T1134/005), [Pass the Ticket](https://attack.mitre.org/techniques/T1550/003), and [Kerberoasting](https://attack.mitre.org/techniques/T1558/003).(Citation: AdSecurity Forging Trust Tickets)(Citation: Harmj0y Domain Trusts) Domain trusts can be enumerated using the `DSEnumerateDomainTrusts()` Win32 API call, .NET methods, and LDAP.(Citation: Harmj0y Domain Trusts) The Windows utility [Nltest](https://attack.mitre.org/software/S0359) is known to be used by adversaries to enumerate domain trusts.(Citation: Microsoft Operation Wilysupply)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | - [Atomic Test #2 - Windows - Discover domain trusts with nltest](#atomic-test-2---windows---discover-domain-trusts-with-nltest) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | ## Atomic Test #2 - Windows - Discover domain trusts with nltest | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | Uses the nltest command to discover domain trusts. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | Requires the installation of nltest via Windows RSAT or the Windows Server AD DS role. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | nltest /domain_trusts | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | ##### Description: nltest.exe from RSAT must be present on disk | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | WHERE nltest.exe >NUL 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[stockpile](https://github.com/mitre/stockpile) | [26c8b8b5-7b5b-4de1-a128-7d37fb14f517.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/26c8b8b5-7b5b-4de1-a128-7d37fb14f517.yml) | `nltest /dsgetdc:%USERDOMAIN%`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [26c8b8b5-7b5b-4de1-a128-7d37fb14f517.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/26c8b8b5-7b5b-4de1-a128-7d37fb14f517.yml) | `nltest /dsgetdc:$env:USERDOMAIN`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


