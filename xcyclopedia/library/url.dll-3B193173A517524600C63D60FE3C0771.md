---
title: url.dll | Internet Shortcut Shell Extension DLL
excerpt: What is url.dll?
---

# url.dll 

* File Path: `C:\Windows\system32\url.dll`
* Description: Internet Shortcut Shell Extension DLL

## Hashes

Type | Hash
-- | --
MD5 | `3B193173A517524600C63D60FE3C0771`
SHA1 | `AFDBF106E79AF8EC45A1F0533AF86019E59F9614`
SHA256 | `36BB3D6893068FF80CF83772447849F8D2DF551280C9EE532E793518E5CF62B5`
SHA384 | `C09B3D1C92BC6F8044644CE7F03BB4E725F9D079E25F94A8938F197ED5441C07A9C654EEE4327020BFCC2BBA72C9BED5`
SHA512 | `70EA1602EB29BEFE4E7CE7273AF800E259D6DCFC2289DE6C8B97C86C0BA65E5DC29F9A6C07DBA681D242C0957FB5B1245B41F771E28F4011994772C44C0574B7`
SSDEEP | `6144:VdYMMHMMMyMMMZMMMVcRMebzDq0DKF/2Ar++X:MMMHMMMyMMMZMMMVcR9bzOco2ArZX`
IMP | `A7D49AFEFA1AB6D3734E92164F1530F5`
PESHA1 | `7E7F56978A45B54A4DD12263216276D07002BB2B`
PE256 | `760FAE51BC14FA8807736811851DC0D5C93A21399DA2C83F82144282997876A0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`AddMIMEFileTypesPS` | 102 | Exported Function
`TranslateURLW` | 116 | Exported Function
`TranslateURLA` | 115 | Exported Function
`TelnetProtocolHandlerA` | 114 | Exported Function
`TelnetProtocolHandler` | 113 | Exported Function
`OpenURLA` | 112 | Exported Function
`OpenURL` | 111 | Exported Function
`URLAssociationDialogA` | 117 | Exported Function
`MIMEAssociationDialogW` | 108 | Exported Function
`MailToProtocolHandlerA` | 110 | Exported Function
`MailToProtocolHandler` | 109 | Exported Function
`InetIsOffline` | 106 | Exported Function
`FileProtocolHandlerA` | 105 | Exported Function
`FileProtocolHandler` | 104 | Exported Function
`AutodialHookCallback` | 103 | Exported Function
`MIMEAssociationDialogA` | 107 | Exported Function
`URLAssociationDialogW` | 118 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: URL.DLL
* Product Name: Internet Explorer
* Company Name: Microsoft Corporation
* File Version: 11.00.19041.1 (WinBuild.160101.0800)
* Product Version: 11.00.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/36bb3d6893068ff80cf83772447849f8d2df551280c9ee532e793518e5cf62b5/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\url.dll](url.dll-4EA55A213FF5CC019E388673D0E1B9AB.md) | 96

## Possible Misuse

*The following table contains possible examples of `url.dll` being misused. While `url.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '*\rundll32.exe* url.dll,*OpenURL *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '*\rundll32.exe* url.dll,*OpenURLA *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '*\rundll32.exe* url.dll,*FileProtocolHandler *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '* url.dll,*OpenURL *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '* url.dll,*OpenURLA *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rundll32_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rundll32_activity.yml) | `- '* url.dll,*FileProtocolHandler *'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `Name: Url.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,OpenURL "C:\test\calc.hta"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,OpenURL "C:\test\calc.url"` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,OpenURL file://^C^:^/^W^i^n^d^o^w^s^/^s^y^s^t^e^m^3^2^/^c^a^l^c^.^e^x^e` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,FileProtocolHandler calc.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,FileProtocolHandler file://^C^:^/^W^i^n^d^o^w^s^/^s^y^s^t^e^m^3^2^/^c^a^l^c^.^e^x^e` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Command: rundll32.exe url.dll,FileProtocolHandler file:///C:/test/test.hta` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Path: c:\windows\system32\url.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Path: c:\windows\syswow64\url.dll` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Url.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Url.yml) | `- Link: https://windows10dll.nirsoft.net/url_dll.html` | 



MIT License. Copyright (c) 2020 Strontic.


