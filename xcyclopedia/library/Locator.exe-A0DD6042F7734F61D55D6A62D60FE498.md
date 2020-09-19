---
title: Locator.exe | Rpc Locator
---

# Locator.exe 

* File Path: `C:\Windows\system32\Locator.exe`
* Description: Rpc Locator

## Hashes

Type | Hash
-- | --
MD5 | `A0DD6042F7734F61D55D6A62D60FE498`
SHA1 | `47D3CD96D2D9776F4CCE212859EAD98E2B4FC4DF`
SHA256 | `8B5743D4ACF8C571F039F83464672306D9F899E4C8512FAB9538807C43DF4A67`
SHA384 | `5BC396F747EAE4121C26326C4BE82B51B7ABE860B1B8C057D528CF6E7E8942424FC03D72F67C02C6F2BCB151F5933880`
SHA512 | `2DE5658F244D5196D501D5E3ED56256995FCCBF6691B78B843BC2866B10CC4CE46F8573E8FCC01BE7AD6914FF81CD7F4A25D724083A17A99ABBEE55C23B26D1A`
SSDEEP | `192:GkJX2saUpB315IDs0sCESBFJDK0zK5T9PCGFrsa1q18oDDoie21mDyW/lW:GcjF3u5E+JiPCArpo1ZDOLDyW/lW`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: locator.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\Locator.exe](Locator.exe-A089120B99842F0A3CE8AE586A31BD56.md) | 66
[C:\Windows\system32\Locator.exe](Locator.exe-D45676C47616B9ABBFAEC97DD3B240A8.md) | 41

## Possible Misuse

*The following table contains possible examples of `Locator.exe` being misused. While `Locator.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Regsvr32.exe is a command-line program used to register and unregister object linking and embedding controls, including dynamic link libraries (DLLs), on Windows systems. Regsvr32.exe can be used to execute arbitrary binaries. (Citation: Microsoft Regsvr32)\n\nAdversaries may take advantage of this functionality to proxy execution of code to avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of whitelists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe is also a Microsoft signed binary.\n\nRegsvr32.exe can also be used to specifically bypass process whitelisting using functionality to load COM scriptlets to execute DLLs under user permissions. Since regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: SubTee Regsvr32 Whitelisting Bypass) This variation of the technique is often referred to as a \"Squiblydoo\" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov)\n\nRegsvr32.exe can also be leveraged to register a COM Object used to establish Persistence via Component Object Model Hijacking. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nDetection: Use process monitoring to monitor the execution and arguments of regsvr32.exe. Compare recent invocations of regsvr32.exe with prior history of known good arguments and loaded files to determine anomalous and potentially adversarial activity. Command arguments used before and after the regsvr32.exe invocation may also be useful in determining the origin and purpose of the script or DLL being loaded. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nPlatforms: Windows\n\nData Sources: Loaded DLLs, Process monitoring, Process command-line parameters, Windows Registry\n\nDefense Bypassed: Process whitelisting, Anti-virus\n\nPermissions Required: User, Administrator\n\nRemote Support: No\n\nContributors: Casey Smith",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | Malicious usage of Regsvr32.exe may avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of allowlists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe can also be used to specifically bypass application control using functionality to load COM scriptlets to execute DLLs under user permissions. Since Regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: LOLBAS Regsvr32) This variation of the technique is often referred to as a "Squiblydoo" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | 		$s4 = "Network Configuration Locator" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


