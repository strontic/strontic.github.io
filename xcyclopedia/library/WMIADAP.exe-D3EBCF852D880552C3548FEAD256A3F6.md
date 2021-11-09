---
title: WMIADAP.exe | WMI Reverse Performance Adapter Maintenance Utility
excerpt: What is WMIADAP.exe?
---

# WMIADAP.exe 

* File Path: `C:\WINDOWS\system32\wbem\WMIADAP.exe`
* Description: WMI Reverse Performance Adapter Maintenance Utility

## Hashes

Type | Hash
-- | --
MD5 | `D3EBCF852D880552C3548FEAD256A3F6`
SHA1 | `C7BEC96032E61A9E28AB2B9CEB7EC238ABE5FAD0`
SHA256 | `E908196299C6E527E9450DEBF87308107A0D8AA8EB9F904EA2CBC21C753B0A2F`
SHA384 | `19A45D76B27969D70E8015530087EDC0EFEBC7852FDBC572DC9B46B21BB1603558216B40365E1C6C514A3915B3DBEC39`
SHA512 | `A12C9E6B4DE2D6D0FCA0CCC0C73026D7809E7669777F28888EB0B4791B0A3B948C422F74E99E26C5CAEE29D92B74CA0513850C101E6D5272B5E8AE93279851C6`
SSDEEP | `3072:n+C/QOG/+PYo1mr3KTwVaWwFgm0hQZob0o+IL/s6C2A32uPze:n+C/QOmo1mrAw8WwFgm0aZE0o5s6C2AT`
IMP | `B32AC086F6F46562D0C3EDBAE67A344B`
PESHA1 | `C71ADA0A73C56D146AE900CCB58244F23D08A256`
PE256 | `B4FACB092FA32A4A0DDE0EF5D40993284418B55C7DDDEE576813E3302BEDB7E1`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\combase.dll |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\System32\msvcrt.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\ucrtbase.dll |
C:\WINDOWS\system32\wbem\WMIADAP.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmicookr.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/e908196299c6e527e9450debf87308107a0d8aa8eb9f904ea2cbc21c753b0a2f/detection


## Possible Misuse

*The following table contains possible examples of `WMIADAP.exe` being misused. While `WMIADAP.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\windows\system32\wbem\WMIADAP.exe'  # https://github.com/SigmaHQ/sigma/issues/1871`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


