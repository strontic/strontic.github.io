---
title: nlbmgr.exe | Network Load Balancing management client
---

# nlbmgr.exe 

* File Path: `C:\Windows\system32\nlbmgr.exe`
* Description: Network Load Balancing management client

## Hashes

Type | Hash
-- | --
MD5 | `EFCB3823A086777E560086F0C8D4824A`
SHA1 | `CDB25D05C4939F73218239E507D0C059E1448A4A`
SHA256 | `B87F4B0E6823906EFD355CCCF95E57DBB89B1841A3BAE1EBDBDF18B4716AD3C4`
SHA384 | `75426260436729DEA5155D2AC92E030E4A5E6E9EABC6120D0C6AE037375D42E4EBBB06A73B7A9AF3504B8FF0414AD069`
SHA512 | `DD3A919B68E06282D431931FE9A2F23DDD903F6C966CBA774A0DBCA0A01D17E59BE7221BBF0A7DB7AABCA0C8F11050DCB9D05448C290AD1680589D8068E0F91F`
SSDEEP | `6144:xYhLX8A43oVJDuTCkGNMwt6Jeu1xWk/2yL5Cj0H/i59KfHPf:xOz8A43Iu8WwAJD1YYL5CK//`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nlbmgr.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## nlbmgr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Configure and manage your Network Load Balancing clusters and all cluster hosts from a single computer, using the Network Load Balancing Manager. You can also use this command to replicate the cluster configuration to other hosts.

You can start the Network Load Balancing Manager from the command-line using the command **nlbmgr.exe**, which is installed in the **systemroot\System32** folder.

### Syntax

```
nlbmgr [/noping][/hostlist <filename>][/autorefresh <interval>][/help | /?]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /noping | Prevents the Network Load Balancing Manager from pinging the hosts prior to trying to contact them through Windows Management Instrumentation (WMI). Use this option if you have disabled Internet Control Message Protocol (ICMP) on all available network adapters. If the Network Load Balancing Manager attempts to contact a host that isn't available, you'll experience a delay when using this option. |
| /hostlist `<filename>` | Loads the hosts specified in filename into the Network Load Balancing Manager. |
| /autorefresh `<interval>` | Causes the Network Load Balancing Manager to refresh its host and cluster information every `<interval>` seconds. If no interval is specified, the information is refreshed every 60 seconds. |
| /? | Displays help at the command prompt. |
| /help | Displays help at the command prompt. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [NetworkLoadBalancingClusters cmdlets reference](/powershell/module/networkloadbalancingclusters)

---



MIT License. Copyright (c) 2020 Strontic.


