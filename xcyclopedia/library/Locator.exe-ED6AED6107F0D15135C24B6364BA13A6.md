---
title: Locator.exe | Rpc Locator
excerpt: What is Locator.exe?
---

# Locator.exe 

* File Path: `C:\WINDOWS\system32\Locator.exe`
* Description: Rpc Locator

## Hashes

Type | Hash
-- | --
MD5 | `ED6AED6107F0D15135C24B6364BA13A6`
SHA1 | `37F51DCEAD08D1D30E887239DEA74C631126CAD2`
SHA256 | `CC4D3B788B293D812DABF8A90F57B7E9EC332E5AB2B7E15057C7FC61DA5ABEFC`
SHA384 | `58B46D227A328044E80B7FD6CDA371274F578916FFF206DEE5085C407563307A317DC2A1F3F0EDE42567EE9F8A8D54D4`
SHA512 | `7D9B9D86BB3DB24BB6AB9529981FDCF886C0FB9DB735ADFC7A860C52F679BEB0EF1B21F6A58435161BAEF9111F3FFB740753C990F1A27298A0B52657BB6C5A75`
SSDEEP | `192:mBRZbTOOzD1m/EE1xyo43ttTsa1q18oD6QGeB11mDyWblW:k/O6DY/H/ydt1po1Z6qB+DyWblW`
IMP | `CBECBDF0E16268273DCA4CB132D15D23`
PESHA1 | `737B501F0BBD844DA547D9F3B94422C0DE6CC7A2`
PE256 | `4098B70A081AD73723B58ADC580D9F2908FAB951DACCEFB9EBBF2D3DC47448E8`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\Locator.exe |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: locator.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/cc4d3b788b293d812dabf8a90f57b7e9ec332e5ab2b7e15057c7fc61da5abefc/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\system32\Locator.exe](Locator.exe-A089120B99842F0A3CE8AE586A31BD56.md) | 43
[C:\Windows\system32\Locator.exe](Locator.exe-A0DD6042F7734F61D55D6A62D60FE498.md) | 40
[C:\Windows\system32\Locator.exe](Locator.exe-D45676C47616B9ABBFAEC97DD3B240A8.md) | 40

## Possible Misuse

*The following table contains possible examples of `Locator.exe` being misused. While `Locator.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [oceanlotus-rtf_ocx_campaigns.misp.event.json](https://github.com/eset/malware-ioc/blob/master/oceanlotus/oceanlotus-rtf_ocx_campaigns.misp.event.json) | `"description": "Regsvr32.exe is a command-line program used to register and unregister object linking and embedding controls, including dynamic link libraries (DLLs), on Windows systems. Regsvr32.exe can be used to execute arbitrary binaries. (Citation: Microsoft Regsvr32)\n\nAdversaries may take advantage of this functionality to proxy execution of code to avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of whitelists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe is also a Microsoft signed binary.\n\nRegsvr32.exe can also be used to specifically bypass process whitelisting using functionality to load COM scriptlets to execute DLLs under user permissions. Since regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: SubTee Regsvr32 Whitelisting Bypass) This variation of the technique is often referred to as a \"Squiblydoo\" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov)\n\nRegsvr32.exe can also be leveraged to register a COM Object used to establish Persistence via Component Object Model Hijacking. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nDetection: Use process monitoring to monitor the execution and arguments of regsvr32.exe. Compare recent invocations of regsvr32.exe with prior history of known good arguments and loaded files to determine anomalous and potentially adversarial activity. Command arguments used before and after the regsvr32.exe invocation may also be useful in determining the origin and purpose of the script or DLL being loaded. (Citation: Carbon Black Squiblydoo Apr 2016)\n\nPlatforms: Windows\n\nData Sources: Loaded DLLs, Process monitoring, Process command-line parameters, Windows Registry\n\nDefense Bypassed: Process whitelisting, Anti-virus\n\nPermissions Required: User, Administrator\n\nRemote Support: No\n\nContributors: Casey Smith",`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.010/T1218.010.md) | Malicious usage of Regsvr32.exe may avoid triggering security tools that may not monitor execution of, and modules loaded by, the regsvr32.exe process because of allowlists or false positives from Windows using regsvr32.exe for normal operations. Regsvr32.exe can also be used to specifically bypass application control using functionality to load COM scriptlets to execute DLLs under user permissions. Since Regsvr32.exe is network and proxy aware, the scripts can be loaded by passing a uniform resource locator (URL) to file on an external Web server as an argument during invocation. This method makes no changes to the Registry as the COM object is not actually registered, only executed. (Citation: LOLBAS Regsvr32) This variation of the technique is often referred to as a "Squiblydoo" attack and has been used in campaigns targeting governments. (Citation: Carbon Black Squiblydoo Apr 2016) (Citation: FireEye Regsvr32 Targeting Mongolian Gov) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s4 = "Network Configuration Locator" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


