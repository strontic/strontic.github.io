---
title: LogonUI.exe | Windows Logon User Interface Host
excerpt: What is LogonUI.exe?
---

# LogonUI.exe 

* File Path: `C:\WINDOWS\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `067FEF16147556C78D5FE950AE199449`
SHA1 | `E41031F3D03D017F6F14967713B28E54B5CD3E31`
SHA256 | `4A224037F9832D0BBFF2D61289F4F9030B72EBD42DA90FB343CA94978BFD0459`
SHA384 | `E6BE2F07E088FD3B72F1CDB245DA514616E1031AF3D301BDE8E9CFADCD4F88850C94C53001015B6AB556617026D99C0C`
SHA512 | `6D0992166323E60D57FA7297879AE4F0324225AF3355D5456F0D33525FE853843D6591ED11AB7F46BD6DCD43A1C98D606A522E16BAB5BF52AD84CFD662500E22`
SSDEEP | `192:SRG+XVk/z9Fk5yDIShvMDiRB3maaTZe0slqW7UW:Szy/5O5ANvMOHZ8ZeRkW7UW`
IMP | `0EF1A1FBF5FA5B3737A8D19C60F416A9`
PESHA1 | `165C18CC3B3E369B1159D9B2466484BB76BAD938`
PE256 | `5DF12DDEB0E63B24C993566E64365BCEA00FC6893ED0FF64456F42DC088FE70B`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\system32\LogonUI.exe |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.120 (WinBuild.160101.0800)
* Product Version: 10.0.22000.120
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/4a224037f9832d0bbff2d61289f4f9030b72ebd42da90fb343ca94978bfd0459/detection


## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | $s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


