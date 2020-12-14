---
title: nltest.exe | Microsoft Logon Server Test Utility
excerpt: What is nltest.exe?
---

# nltest.exe 

* File Path: `C:\WINDOWS\system32\nltest.exe`
* Description: Microsoft Logon Server Test Utility

## Hashes

Type | Hash
-- | --
MD5 | `7F64502F377A449DCB9DA94CC4D9F52D`
SHA1 | `31DD323774335F8D01C24646E6783A493EDD5A92`
SHA256 | `7FADD9DB73F868040413C2B0466C9F4898372224E83C712F3A7A1494B8F66992`
SHA384 | `A02E0FBDD440278999926E40F982F41DF7636806872A84D6F3B06BB428DFF423CCEC28B3DA0EB6EC9C29887C3F01EEE0`
SHA512 | `9A40DE21123494D10CB72DDF8F11B29F859B30B8FC7C61B9192B186EC6D76E045137C784EA47A7DF9E1FAD9CCC00CDBCB0FA52CB75773DF124A89E18E71DC5C0`
SSDEEP | `6144:JWwAJOKO9xjpOiUoiYXHU6/yxpxwIUzGHk:0w19xjpWUk+a`

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
        /TRY_NEXT_CLOSEST_SITE /SITE:<SiteName> /ACCOUNT:<AccountName> /RET_DNS /RET_NETBIOS
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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nltestrk.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `nltest.exe` being misused. While `nltest.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_dsquery_domain_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dsquery_domain_trust_discovery.yml) | `- Image\|endswith: '\nltest.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_trickbot_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_trickbot_recon_activity.yml) | `- '\nltest.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `description: Identifies execution of nltest.exe and dsquery.exe for domain trust discovery. This technique is used by attackers to enumerate Active Directory trusts.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_trust_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_trust_discovery.yml) | `- Image\|endswith: '\nltest.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Nltest.yml) | `Name: Nltest.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Nltest.yml) | `- Command: nltest.exe /SERVER:192.168.1.10 /QUERY` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Nltest.yml) | `- c:\windows\system32\nltest.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Nltest.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/LOLUtilz/OSBinaries/Nltest.yml) | `- https://ss64.com/nt/nltest.html` | 
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
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1482.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1482/T1482.md) | WHERE nltest.exe >NUL 2>&1  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


