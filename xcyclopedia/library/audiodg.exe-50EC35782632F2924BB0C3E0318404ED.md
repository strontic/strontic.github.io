---
title: audiodg.exe | Windows Audio Device Graph Isolation 
excerpt: What is audiodg.exe?
---

# audiodg.exe 

* File Path: `C:\Windows\system32\audiodg.exe`
* Description: Windows Audio Device Graph Isolation 

## Hashes

Type | Hash
-- | --
MD5 | `50EC35782632F2924BB0C3E0318404ED`
SHA1 | `F1FFCCED9AC272CD57DADD91FF91FC95A3198C98`
SHA256 | `6DFD3FF11824E58D4ABE0946D4BB0DDC06C7C5275BA743738B2B03E11FF6E55F`
SHA384 | `47FF53C9623B761B239459919B637CB5E48A77FDC75654FCD472BBBB70914974755132E70D59EFFF1948D4F6285319DE`
SHA512 | `ABFF83156582BE759484E31B2CD7E7199D4DFD246B209E2F0942EC08190068C5224F36C4CDE534056AA285180D1C275962C286624AC48E0269CEF4BC15EAE2E4`
SSDEEP | `12288:e+R8p4PptSXiRtfP68HJMbBLccXNSRLKmHYZbxw+j:e+RzPptS2HiLccQLdYlfj`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\audiodg.exe |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\cfgmgr32.dll |
C:\Windows\System32\combase.dll |
C:\Windows\system32\DEVOBJ.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\system32\MMDevAPI.DLL |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\OLEAUT32.dll |
C:\Windows\system32\PROPSYS.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: audioadg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\audiodg.exe](audiodg.exe-30CE6C6D6DAD15411223A127C0405BE4.md) | 93

## Possible Misuse

*The following table contains possible examples of `audiodg.exe` being misused. While `audiodg.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `- '*\audiodg.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020-2021 Strontic.


