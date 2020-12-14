---
title: Locator.exe | Rpc Locator
excerpt: What is Locator.exe?
---

# Locator.exe 

* File Path: `C:\Windows\system32\Locator.exe`
* Description: Rpc Locator

## Hashes

Type | Hash
-- | --
MD5 | `109C1D609951E886D3643B15C1EDD1C2`
SHA1 | `20E9173558D9B594D40D5EBB4A7C4019BFF0BF3A`
SHA256 | `347D8E7C50EC7F96217C7421D9BC8A42C9DF50B94169CB58DCF857A63C33C2EA`
SHA384 | `985B85F8B137025A33F89F26CA001AA51E95A1AEF3B864DEA3DF7686E8A2D211237A2EF5599E1ABC18363B86E72E5AE2`
SHA512 | `3F723B2A46F45469B76AC9B75D6D4AF5689167139720D14534AB64ACD58493A19CA40F12CEFA71ABAC6E14AE298C43A802002E06FB6C24880E35E1F3320E0A46`
SSDEEP | `192:h+KPfrjBKb15VbkP1NC+XwkKjGLIIQG5Va1F18oDkoJeumD6WrlW:Zvgb3w1Y+gkKjFIQuk/1Zk1rD6WrlW`

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: locator.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `Locator.exe` being misused. While `Locator.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Regsvr32.exe is a command-line program used to register and unregister object linking and embedding controls, including dynamic link libraries (DLLs), on Windows systems. Regsvr32.exe can be used to execute arbitrary binaries. (Citation: Microsoft Regsvr32)\n\nAdversaries may take advantage of this functionality to proxy execution of code to avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of whitelists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe is also a Microsoft signed binary.\n\nRegsvr32.exe can also be used to specifically bypass process whitelisting using functionality to load COM scriptlets to execute DLLs under user permissions. Since regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: SubTee Regsvr32 Whitelisting Bypass) This variation of the technique is often referred to as a \"Squiblydoo\" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov)\n\nRegsvr32.exe can also be leveraged to register a COM Object used to establish Persistence via Component Object Model Hijacking. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nDetection: Use process monitoring to monitor the execution and arguments of regsvr32.exe. Compare recent invocations of regsvr32.exe with prior history of known good arguments and loaded files to determine anomalous and potentially adversarial activity. Command arguments used before and after the regsvr32.exe invocation may also be useful in determining the origin and purpose of the script or DLL being loaded. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nPlatforms: Windows\n\nData Sources: Loaded DLLs, Process monitoring, Process command-line parameters, Windows Registry\n\nDefense Bypassed: Process whitelisting, Anti-virus\n\nPermissions Required: User, Administrator\n\nRemote Support: No\n\nContributors: Casey Smith",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | Malicious usage of Regsvr32.exe may avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of allowlists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe can also be used to specifically bypass application control using functionality to load COM scriptlets to execute DLLs under user permissions. Since Regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: LOLBAS Regsvr32) This variation of the technique is often referred to as a "Squiblydoo" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s4 = "Network Configuration Locator" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


