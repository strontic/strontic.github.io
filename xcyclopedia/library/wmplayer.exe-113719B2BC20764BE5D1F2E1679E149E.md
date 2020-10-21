---
title: wmplayer.exe | Windows Media Player
excerpt: What is wmplayer.exe?
---

# wmplayer.exe 

* File Path: `C:\Program Files\Windows Media Player\wmplayer.exe`
* Description: Windows Media Player

## Hashes

Type | Hash
-- | --
MD5 | `113719B2BC20764BE5D1F2E1679E149E`
SHA1 | `E4CA0DCEA9A75B78CE11DD1CB05BDB32508ED278`
SHA256 | `B3958D6FAD71FA64227F2B41F57DBF9BAB434746BA0D249E226408199C218F48`
SHA384 | `C18D3630A024D6CD0892AF8CB1AD63D9A44385C09766A30DF3C9D9F9B78C7981B65F683CAA27841897AE5207D8AAB2E8`
SHA512 | `C7FA2906D3EF4A80F130D40D4C9F257F789126CCACB15FB09BF02C78856336E53A136590E6508590F327B4B90E2DFA02563E6EA582FA47B90127992900105B8B`
SSDEEP | `3072:DAziiNohYkQr0jeLwJr95rJolNAzyP+msVK0Zh:DPYQqLwhHrWsOP+5VT`
IMP | `33E3BA3C576D003915CF7E8CEC099D86`
PESHA1 | `80801622A250316607C59D889B87C570BDCC3800`
PE256 | `A9D9EF640DD10DE6C842257FA589632C2757B0C9FA55F14D2FB339A4176FB229`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\Windows Media Player\wmplayer.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\System32\cryptsp.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\System32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\ole32.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\System32\powrprof.dll |
C:\Windows\System32\profapi.dll |
C:\Windows\SYSTEM32\PROPSYS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\shcore.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\shlwapi.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\system32\uxtheme.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\System32\windows.storage.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: wmplayer.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 12.0.17763.1 (WinBuild.160101.0800)
* Product Version: 12.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/b3958d6fad71fa64227f2b41f57dbf9bab434746ba0d249e226408199c218f48/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-4ACC57344531EEAC412463137996B8C1.md) | 61
[C:\Program Files (x86)\Windows Media Player\wmpconfig.exe](wmpconfig.exe-E173D6822FF7ACBBA5ADD79705D8DEB1.md) | 61
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-6AA4614C7ADE4C07F2F6E362D08DCF5A.md) | 93
[C:\Program Files (x86)\Windows Media Player\wmplayer.exe](wmplayer.exe-EEB987151A57294A024B8FBE323E8E94.md) | 93
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-1BA5B0F52DCD29859D8D3C5DB0F59410.md) | 65
[C:\Program Files (x86)\Windows Media Player\wmpshare.exe](wmpshare.exe-AA5933CE16373F146EC28DA42A0700B7.md) | 63
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-29E52BFB44C74B2E3730F79D04082692.md) | 61
[C:\Program Files\Windows Media Player\wmpconfig.exe](wmpconfig.exe-5607F957C0A4FF1B26F7D1A5F7D66814.md) | 61
[C:\Program Files\Windows Media Player\wmplayer.exe](wmplayer.exe-D86F92A0D66CD72733ECA3BE2B1A412C.md) | 83
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-275462C97656943B9F1A11F1701861FA.md) | 63
[C:\Program Files\Windows Media Player\wmpshare.exe](wmpshare.exe-5E1E371446C859EB714A2C53BF9FAEC6.md) | 66

## Possible Misuse

*The following table contains possible examples of `wmplayer.exe` being misused. While `wmplayer.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `Image\|endswith: '\wmplayer.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


