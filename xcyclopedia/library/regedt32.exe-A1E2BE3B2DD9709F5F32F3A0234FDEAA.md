---
title: regedt32.exe | Registry Editor Utility
excerpt: What is regedt32.exe?
---

# regedt32.exe 

* File Path: `C:\WINDOWS\system32\regedt32.exe`
* Description: Registry Editor Utility

## Hashes

Type | Hash
-- | --
MD5 | `A1E2BE3B2DD9709F5F32F3A0234FDEAA`
SHA1 | `36C1791CE932959D9EA1EC5DC1921EDF257AC87C`
SHA256 | `23D040CCEF1F44F724D052AC8BDBA3714746739B055F954B27BDABEE6F735A81`
SHA384 | `B4D3E63D937BF638FFE4FD6C1A66DC35A1BA6C412101910A032DE1A0A5592B4915CE1AFEEA20BEF22B71BE1EEDD04883`
SHA512 | `396ACD9912498B412D5CC46CC1BAD6853C6FD5A02B9CB778C89B18B2C138748E18AE00E7EC9FFFCF7C064D8A0AFB4129A0B50ADE9F4C6AE4BF2AACAD6D55593E`
SSDEEP | `192:QSwiKZdNjkllUBmHctRaO0REqOeUE81Br6XvUkWExW:4TdullSm8TaO02eUbiMkWExW`
IMP | `A3060EC916831020104FAE5BC9414975`
PESHA1 | `0E3EA187A2027FFF5482FC2483AC8F329DD161BC`
PE256 | `CE32AF0877FC13D4476C6BCE8EB821B27D254E0CAE4223071232C46CE8230869`

## Runtime Data

### Child Processes:
regedit.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcp_win.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\regedt32.exe |
C:\WINDOWS\System32\SHELL32.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\System32\USER32.dll |
C:\WINDOWS\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: regedt32.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/23d040ccef1f44f724d052ac8bdba3714746739b055f954b27bdabee6f735a81/detection


## Possible Misuse

*The following table contains possible examples of `regedt32.exe` being misused. While `regedt32.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_grizzlybear_uscert.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_grizzlybear_uscert.yar) | $a3 = "regedt32.exe" wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


