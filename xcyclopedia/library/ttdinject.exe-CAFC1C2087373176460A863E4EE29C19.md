---
title: ttdinject.exe | Time Traver Debugger Application Launcher
excerpt: What is ttdinject.exe?
---

# ttdinject.exe 

* File Path: `C:\WINDOWS\SysWOW64\ttdinject.exe`
* Description: Time Traver Debugger Application Launcher

## Hashes

Type | Hash
-- | --
MD5 | `CAFC1C2087373176460A863E4EE29C19`
SHA1 | `853C080B9E0C6342E50866F39C0BB18B1E01784B`
SHA256 | `3572ADA17A4E88324A3295338CD9BF02BC9C76D881AB020576FF759733146DFA`
SHA384 | `C14FE796330923062C1393AD84D0F4721AF1162ACF79CE6A9622C1152601A95696F35A2825851D3D588B98FCF32AD1DD`
SHA512 | `BC01F401640F44C134B8158A4044E8EE3ACFC806AC42C06DA7D06148178474927F8B751C39D816FE7433E6605DA34C8C8BCBD146DCA092CBEF66BD673878800B`
SSDEEP | `3072:P7+nuZC491nBweMVewi0FOPU5I2ze3DgOTgZoX+NV597Io0aeg:PB84Rwi0F2UDvOw2YPfAg`

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: TTDInject.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ttdinject.exe` being misused. While `ttdinject.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Name: Ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: TTDInject.exe /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /Launch "C:/Windows/System32/calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `Description: Execute calc using ttdinject.exe. Requires administrator privileges. A log file will be created in tmp.run. The log file can be changed, but the length (7) has to be updated.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Command: ttdinject.exe /ClientScenario TTDRecorder /ddload 0 /ClientParams "7 tmp.run 0 0 0 0 0 0 0 0 0 0" /launch "C:/Windows/System32/calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\System32\ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- Path: C:\Windows\Syswow64\ttdinject.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Parent child relationship. Ttdinject.exe parent for executed command`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ttdinject.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ttdinject.yml) | `- IOC: Multiple queries made to the IFEO registry key of an untrusted executable (Ex. "HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\payload.exe") from the ttdinject.exe process`{:.highlight .language-yaml} | 



MIT License. Copyright (c) 2020-2021 Strontic.


