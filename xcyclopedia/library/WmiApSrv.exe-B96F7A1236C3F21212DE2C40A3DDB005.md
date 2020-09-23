---
title: WmiApSrv.exe | WMI Performance Reverse Adapter
excerpt: What is WmiApSrv.exe?
---

# WmiApSrv.exe 

* File Path: `C:\windows\system32\wbem\WmiApSrv.exe`
* Description: WMI Performance Reverse Adapter

## Hashes

Type | Hash
-- | --
MD5 | `B96F7A1236C3F21212DE2C40A3DDB005`
SHA1 | `170ECEA5CE21520266275140B0C5608CA05491FC`
SHA256 | `5A29EBB6DA036E303611EB1304192655021405BB05452FD37886DDE604FF0D9D`
SHA384 | `EAEA2B3F5D3971A91E24C5E8E21EE4E3FA39C368125B2A3B9658B213029A196B2A0F721E5ACEE1D05DBC2282889242B7`
SHA512 | `4591856C73168EF833FC661BD31ED719BE0074BFBB71B153ECD301A413F4B98BF31DF8E5A8924FD55D1ABF46AEF79B3BFD992073588BDB1C19975433CBFA993A`
SSDEEP | `3072:xM/2ye7sSZqVYjX4Y+U9ov/W3tiopJuHb/tnTiTuTVLxtBtiXorbZU2oPY:dqVYjX4Y+ygu3tioHete2vBc4rFnoP`

## Signature

* Status: The file C:\windows\system32\wbem\WmiApSrv.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: WmiApSrv.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `WmiApSrv.exe` being misused. While `WmiApSrv.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\WmiAPsrv.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


