---
title: MsCtfMonitor.dll | MsCtfMonitor DLL
excerpt: What is MsCtfMonitor.dll?
---

# MsCtfMonitor.dll 

* File Path: `C:\Windows\SysWOW64\MsCtfMonitor.dll`
* Description: MsCtfMonitor DLL

## Hashes

Type | Hash
-- | --
MD5 | `CE5CE36D9642277190090768D3D4A87A`
SHA1 | `C24C5CC6F2A5275398582B05DF27FE3B5FF29025`
SHA256 | `BDFE8B537EC8066192807427F239C9231FB46598B24C6A88650482C8F002A9F3`
SHA384 | `3FBEDF032871601E52CF621EC57513D7FE1AF8E4F0402DC2E69AF38A196F88FA9589096F1D541219F34CCE6EA9666759`
SHA512 | `72EFE7AB10F8C4A7CD602D801E564A5390AC0B74966AE5CCAE9014AA6162851B819E65FF840409F18CE343598E15E33542EE91C61A52CEC0EEB2BE95D58937D3`
SSDEEP | `1536:SBdGLaGo1x/N6c8DDj3Kc4GDUHlesJMwT:1mh1xsj3KYDUF7JMw`
IMP | `6E7A1544BDBD368372174644C38392C4`
PESHA1 | `7E072852CABD2EBF5112693677606A901D72E696`
PE256 | `59D52E9872F7E9C3D4D10A2034EDED03354C75E71B2FDF4F048FB5E2FCC90972`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`DllCanUnloadNow` | 1 (0x1) | Exported Function | 0x1000e680 | 0x0000e680
`DllGetClassObject` | 2 (0x2) | Exported Function | 0x10006d30 | 0x00006d30
`DllRegisterServer` | 3 (0x3) | Exported Function | 0x1000e6a0 | 0x0000e6a0
`DllUnregisterServer` | 4 (0x4) | Exported Function | 0x1000e810 | 0x0000e810
`DoMsCtfMonitor` | 5 (0x5) | Exported Function | 0x100052f0 | 0x000052f0
`InitLocalMsCtfMonitor` | 6 (0x6) | Exported Function | 0x1000eb80 | 0x0000eb80
`UninitLocalMsCtfMonitor` | 7 (0x7) | Exported Function | 0x1000ec50 | 0x0000ec50


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsCtfMonitor.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/bdfe8b537ec8066192807427f239c9231fb46598b24c6a88650482c8f002a9f3/detection/


## Possible Misuse

*The following table contains possible examples of `MsCtfMonitor.dll` being misused. While `MsCtfMonitor.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `1D56BAB28793E3AB96E390F09F02425E52E28FFC` \| MsCtfMonitor.dll \| Amavaldo injector             \| Win32/Spy.Amavaldo.U trojan            \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `\| `B761D9216C00F5E2871DE16AE157DE13C6283B5D` \| MsCtfMonitor     \| Amavaldo banking trojan       \| Win32/Spy.Amavaldo.N trojan            \|` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [amavaldo](https://github.com/eset/malware-ioc/blob/master/amavaldo/README.adoc) | `- `%LocalAppData%\%RAND%\MsCtfMonitor[.dll]`` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


