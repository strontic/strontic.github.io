---
title: wbemprox.dll | WMI
excerpt: What is wbemprox.dll?
---

# wbemprox.dll 

* File Path: `C:\Windows\system32\wbem\wbemprox.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `FE86E9EC7B04145E65A59BB60DFE2E38`
SHA1 | `24C4120BCD40DFFBAD7EB697A77F52FE5C30475C`
SHA256 | `5C7ECD69B82D395BC8F064DB723594B0F572BE743ECAA44CD4988A43498845E1`
SHA384 | `54C88E0877195C8C9668C184A5635D32735E19A7AFFA617F0E93316A4462E728CD75F5E2CA1D471A49733BA64CB64021`
SHA512 | `F1337D61250C0A03E0BD8666D3E4C531947670FD77168ECF3CBDB4D5672A4D32DA8816B149B9973AB54D044CDCF36943E06128EB0C629655416666F8F5608E47`
SSDEEP | `768:MTzV7M8rCzr5U3rJrBHPXxUACiEzjVdrAmB5PUQZCl:MZCzr5qr3vXxwjHrFGQZCl`
IMP | `31BB95F0D989FF6272550F8EC7E6F48C`
PESHA1 | `46BE18D02EFADA6E2F926AE4B4C307765628F960`
PE256 | `D7FC3DBDB7D0C58FB2234117D7BFB3D5E2DFB2B4A1C2586F2C017825086096C9`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wbemprox.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/5c7ecd69b82d395bc8f064db723594b0f572be743ecaa44cd4988a43498845e1/detection/


## Possible Misuse

*The following table contains possible examples of `wbemprox.dll` being misused. While `wbemprox.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_winword_wmidll_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_susp_winword_wmidll_load.yml) | `- '*\wbemprox.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\wbemprox.dll'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


