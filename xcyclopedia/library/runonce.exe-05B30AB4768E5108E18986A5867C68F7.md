---
title: runonce.exe | Run Once Wrapper
excerpt: What is runonce.exe?
---

# runonce.exe 

* File Path: `C:\Windows\system32\runonce.exe`
* Description: Run Once Wrapper

## Hashes

Type | Hash
-- | --
MD5 | `05B30AB4768E5108E18986A5867C68F7`
SHA1 | `9A10295C54450788722A8C97BDCA5857D8666CF6`
SHA256 | `E4AFEF687BCEFB9A581299FB35946C869C6D0E000966E688589A48907C352432`
SHA384 | `6A92BE80EA3C41057B29760D7B2FE18C024A7A9CF7A698A47D520920FA98F0A778640766A522F90A85DB111752A8D04E`
SHA512 | `D49CB830DA90DFC873FFB105C58599098F6E67B97B8DD159F668C2968864E3DDB340CC3DA4AF3E087529AB4DC85ACF7D1130518C201330D0245D7AD987065A41`
SSDEEP | `1536:ooX4KqGA17ukVmCgnTAX0ZgdZK7lonRm9NVcqDoZq+Sh:ooZOVkCgnTAysk9N+cCq+C`
IMP | `EC2020E2A17AC9DD377F6A8CA39994C4`
PESHA1 | `BE53B5FC19DB84C9F8AAFBB346C8FB5C29D57E88`
PE256 | `E876276A94326DA85FB139D6BECA07BECD791C6F6A333799531CC08645D22C6C`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CoreMessaging.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\system32\dwmapi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\MSASN1.dll |
C:\Windows\System32\MSCTF.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\runonce.exe |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.common-controls_6595b64144ccf1df_6.0.17763.1518_none_de6e2bd0534e2567\COMCTL32.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: RUNONCE.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/e4afef687bcefb9a581299fb35946c869c6d0e000966e688589a48907c352432/detection/


## Possible Misuse

*The following table contains possible examples of `runonce.exe` being misused. While `runonce.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_remote_thread.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_suspicious_remote_thread.yml) | `- '\runonce.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `Name: Runonce.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Command: Runonce.exe /AlternateShellStartup` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\System32\runonce.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Runonce.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Runonce.yml) | `- Path: C:\Windows\SysWOW64\runonce.exe` | 



MIT License. Copyright (c) 2020 Strontic.


