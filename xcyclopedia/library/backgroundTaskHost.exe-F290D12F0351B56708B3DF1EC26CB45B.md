---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\Windows\SysWOW64\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `F290D12F0351B56708B3DF1EC26CB45B`
SHA1 | `8992D17CBE7275F69B8CABEE0EE6BCFBDD1B3596`
SHA256 | `CD2BF90FE5CD57DC49AF50950C8CE3CFC6433CCE7B68FB20DFD78E30A865B134`
SHA384 | `2AB41422D0E4942EE8227472D42B7E0A3F6BDA9929B240DAF6EE9835A0D7E2115CF7D096B001E1C1BB20CD5F8D1A7FBF`
SHA512 | `918C3D82CA9E8386EF0BCAD06B5238DF9DC6E5F9C3B58EEFC0A10E90F1A3EEE613503281E31567FD498AFF439AE850CCACC6F0DD5EF23273FBA3AFBC5641EB13`
SSDEEP | `384:oLapnnorHWBWqGWhr6wDDBRJLrUJAl3qQBYJ:kknOHWbJr6wD1PLIuS`
IMP | `B01956F70C2FC1C81D9AF197F35D4D75`
PESHA1 | `F2B4B70338939B44D86BC5D578C54DDE3BAF7D6C`
PE256 | `979EF31565289D7672F368247B466854F8A89F7432C51DE5F6DCADC69D9BE100`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\backgroundTaskHost.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: backgroundTaskHost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.546 (WinBuild.160101.0800)
* Product Version: 10.0.19041.546
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/cd2bf90fe5cd57dc49af50950c8ce3cfc6433cce7b68fb20dfd78e30a865b134/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll](6bea57fb-8dfb-4177-9ae8-42e8b3529933_RuntimeDeviceInstall.dll-513E16B14C2E8DE6AEA439153A9733FD.md) | 35
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-ABA7E7513886979AF8A3B68A1F4E591D.md) | 29
[C:\Windows\system32\LocationFrameworkPS.dll](LocationFrameworkPS.dll-FBF3B3CCC037AD1D9FC36C28D0E29A25.md) | 27
[C:\Windows\system32\migwiz\migres.dll](migres.dll-E937B164DC2D2A03490AC3EB9D5875B2.md) | 35
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-09C06B0224F439DF8666CF7B411B7B1C.md) | 38
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-5D20EF28D0B222CA57F47524F2D3E8C0.md) | 35
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-BD3FC089F0D20F1D9172EA5CD41B2CA8.md) | 35
[C:\Windows\system32\ScriptRunner.exe](ScriptRunner.exe-C64357854C5214AC178B78EF1A17042F.md) | 32
[C:\Windows\system32\WerEnc.dll](WerEnc.dll-57896D83DAD20250B3878747AB6115F6.md) | 38
[C:\Windows\SystemApps\MicrosoftWindows.UndockedDevKit_cw5n1h2txyewy\UndockedDevKit.exe](UndockedDevKit.exe-C1FD0D396683E3F59646E4CEC2A55A85.md) | 43
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 57
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-6F3C9485F8F97AC04C8E43EF4463A68C.md) | 33
[C:\Windows\SysWOW64\WerEnc.dll](WerEnc.dll-F4C2183256B20B62EBD7C9397F0C5D85.md) | 33

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


