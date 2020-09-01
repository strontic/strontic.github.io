---
title: quickassist.exe | Quick Assist
---

# quickassist.exe 

* File Path: `C:\WINDOWS\system32\quickassist.exe`
* Description: Quick Assist

## Screenshot

![quickassist.exe](screenshots/quickassist.exe-39AB5ED601B0C39DCE3B7D269847C944-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `D042F2290489AD0715C077941E9AB742`
SHA1 | `EEBE5A0D4341A85D8A60628C7E99FC91E33FDC71`
SHA256 | `C58A2F432B756B9E7044892573658B18ED978C711E2BA960D9BD0F4350602D44`
SHA384 | `869FBA6E6772DDD936882CA00AF37409356A19E0B3F2FFF23D5A10F6D9E3CD0EDD621F48204F3CE6607FD9B7449B1F4F`
SHA512 | `8F30778C46F7B879217FE1B9AB03594C9ACFD918342B3F83D0E0F0514681458C8CAD15F0C43DFF52F638905F2938EB122C88A4712847FEF8C0A9012D234BC969`
SSDEEP | `12288:8GTc62pXTXZy7tjPghe8HPOgCzsUdLeANsDvH:TIt9Zyt7fLIU0GS`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\advapi32.dll |
C:\Windows\system32\ATL.DLL |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\CRYPT32.dll |
C:\Windows\system32\d2d1.dll |
C:\Windows\system32\d3d11.dll |
C:\Windows\system32\dcomp.dll |
C:\Windows\system32\dxgi.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\quickassist.exe |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\system32\SAS.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\shell32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\UxTheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\WinSxS\amd64_microsoft.windows.gdiplus_6595b64144ccf1df_1.1.19041.450_none_fae7a009761b0b44\gdiplus.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: QuickAssist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `quickassist.exe` being misused. While `quickassist.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) |       $s1 = "QuickAssist.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_middle_east_talosreport.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_middle_east_talosreport.yar) |       $s4 = "name=\"QuickAssist\" " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


