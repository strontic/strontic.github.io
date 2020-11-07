---
title: wbemsvc.dll | WMI
excerpt: What is wbemsvc.dll?
---

# wbemsvc.dll 

* File Path: `C:\Windows\SysWOW64\wbem\wbemsvc.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `1C2F40870081182396F968B17790A547`
SHA1 | `A16D197EB144FD2073D5E4E0EF0BE6A1D6D83585`
SHA256 | `B99485A42D85B81D7D626AC76F2545B979524D07D1073CB745C213156E1043D4`
SHA384 | `F9C4DEC218EA4E4DD7EED42EF92BA81169F23516A59724E5178ED5830685E373910E862A6C4637E8E77FB76910800206`
SHA512 | `43CB93E7503934537F9DA7DCF63CCDF8DF609786DB107C3B36F4C9AD0C32A58201BD88FD2715AC1DC43DFF057ACBDDC70EB4605680AE2230949B3BB4582B0DFF`
SSDEEP | `768:g2lOcBxz/J4S+4JoNCZpMjyhrVG+oq4K96Z9drkxb:g8J4t6JhrIFqf96Z9dox`
IMP | `BACB56FFFD9CDFA7320267145FAD5E2D`
PESHA1 | `69DDB14632238994D1FC0A4B3908AC9AD5DB64E9`
PE256 | `975B67DFED8D516318892C436C54188FCB7B93643FEE82FC6D7819050E308108`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wbemsvc.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/b99485a42d85b81d7d626ac76f2545b979524d07d1073cb745c213156e1043d4/detection/


## Possible Misuse

*The following table contains possible examples of `wbemsvc.dll` being misused. While `wbemsvc.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemsvc.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wbemsvc.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


