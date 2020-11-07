---
title: backgroundTaskHost.exe | Background Task Host
excerpt: What is backgroundTaskHost.exe?
---

# backgroundTaskHost.exe 

* File Path: `C:\Windows\system32\backgroundTaskHost.exe`
* Description: Background Task Host

## Hashes

Type | Hash
-- | --
MD5 | `DA7063B17DBB8BBB3015351016868006`
SHA1 | `C6E63C7AAE9C4E07E15C1717872C0C73F3D4FB09`
SHA256 | `20330D3CA71D58F4AEB432676CB6A3D5B97005954E45132FB083E90782EFDD50`
SHA384 | `EAB5CEFD65A29D80B5CB330DD2F6B22AD678A10984FF13F20ADCD3187DEAA1C6114CC5BA8A78534FC40620C66214853C`
SHA512 | `16A8E5AAD8900CB2DA6D2E06258563EFF56B4022092A750C16DA50496EC490D1B761D630135CDF313C0EF96D6F30CCE09DF9EBCA0DE96E854F2F901B34FD9D1F`
SSDEEP | `384:s5daovOa6xo3rHy7WqGWl8hDBRJykqQ3klGs6mJJc9:semHbHypmh1PJGDc9`
IMP | `D2ACF1CBC4A6DB14A34C687B9362D66B`
PESHA1 | `47F5FDA44A6E0307FC3B9BBA945BA4F113B19811`
PE256 | `FF3236DB2671E3E544CB5E38638D678AE771E2BB75B9673F75F5D89D2120DA16`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\system32\backgroundTaskHost.exe |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\System32\clbcatq.dll |
C:\Windows\System32\combase.dll |
C:\Windows\SYSTEM32\kernel.appcore.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\twinapi.appcore.dll |
C:\Windows\System32\ucrtbase.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/20330d3ca71d58f4aeb432676cb6a3d5b97005954e45132fb083e90782efdd50/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 49

## Possible Misuse

*The following table contains possible examples of `backgroundTaskHost.exe` being misused. While `backgroundTaskHost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_azure_browser_sso.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_abusing_azure_browser_sso.yml) | `- BackgroundTaskHost.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


