---
title: LogonUI.exe | Windows Logon User Interface Host
excerpt: What is LogonUI.exe?
---

# LogonUI.exe 

* File Path: `C:\Windows\system32\LogonUI.exe`
* Description: Windows Logon User Interface Host

## Hashes

Type | Hash
-- | --
MD5 | `893144FE49AA16124B5BD3034E79BBC6`
SHA1 | `FBF39A288FC46CBF0620CFD297395A8FB4FBCDAD`
SHA256 | `CF01E46C146699F6C0E3DD447043F59BC9438DBBCB9563AF6C60EBC6D82727F2`
SHA384 | `AD04C11ECD7D65D4C50FDCFF26BBA66F60D0F929C624FC85A706456C142036EBB4E3E40AD75EE9CA407E614EEE741517`
SHA512 | `C921EE3786717AC1F9E1981E35494F33D26D153AFB335C52219830261F84155383D5AC9FF0EA1D7F3F6913B28C878CE6B5EA350F60ED9A9BF1AC006596FD4C68`
SSDEEP | `192:yecuhBM44rbhVsO3XKtK3NyeiKQ2pxeILJJQYSlid3slZiU4ltWIUW:HVhq4Ih6U3NRXpxLLJGYWi2ZcnWIUW`
IMP | `B9B0B64B08B38276711093CA94348D39`
PESHA1 | `7C621A783BF7A358486DAC4DF3DEFD1185E56D26`
PE256 | `7A2DB86800DDCE2F818724012C945E54834BA2C8D9644F43372FED150A5EA592`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\LogonUI.exe |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: logonui.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/cf01e46c146699f6c0e3dd447043f59bc9438dbbcb9563af6c60ebc6d82727f2/detection/


## Possible Misuse

*The following table contains possible examples of `LogonUI.exe` being misused. While `LogonUI.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_seaduke_unit42.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_seaduke_unit42.yar) | $s2 = "LogonUI.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


