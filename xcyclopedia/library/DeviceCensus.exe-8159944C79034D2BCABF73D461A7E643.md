---
title: DeviceCensus.exe | Device Census
excerpt: What is DeviceCensus.exe?
---

# DeviceCensus.exe 

* File Path: `C:\Windows\system32\DeviceCensus.exe`
* Description: Device Census

## Hashes

Type | Hash
-- | --
MD5 | `8159944C79034D2BCABF73D461A7E643`
SHA1 | `9E488437B2233E5AD9ABD3151EC28EA51EB64C2D`
SHA256 | `DBEA7473D5E7B3B4948081DACC6E35327D5A588F4FD0A2D68184BFFD10439296`
SHA384 | `46DBFAF363BC335B3BB688DFAA324F234C86B4A38BFFF986A5822262E905965676D77263A3E7A870FA5B33D238DC94D9`
SHA512 | `49CA6F6357EB41241900F1997759ECCEB3EE0B3905118060F07109FFC2E09D3CB69A7DD2ABE77635DD5D2C41484AD2E889EAAC5882E989E494CCA97ACF7E2440`
SSDEEP | `384:/ZFRwpU6F4NF1s0bFOaog3N4UA7Oy1All2RtzVrMFWYG4i6XiWbgW7/zD1IDBRJ6:/Dqp1ssuvWRCll0zrMF7G4i6XfnI1PyR`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DeviceCensus.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1035 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1035
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Common Files\Microsoft Shared\ink\TabTip32.exe](TabTip32.exe-DCB3378628CC715C93B9D53DF1857029.md) | 25
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 30
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-26FC7C7BDB99AB9B3EACB4BD513F6642.md) | 83
[C:\WINDOWS\system32\DeviceCensus.exe](DeviceCensus.exe-AC7BD0E738FDE12FB29DA98D88C903EA.md) | 97
[C:\Windows\system32\dllhost.exe](dllhost.exe-C6723950D1A8CD49D93C8D082B175D41.md) | 33
[C:\Windows\system32\NDKPing.exe](NDKPing.exe-5FC26E00B9012CC0188F65BB999174E9.md) | 27
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-EA059E3BA7E07347BDE08EF016E09D50.md) | 30
[C:\Windows\system32\prproc.exe](prproc.exe-912400A90CA88E80ABC6CB8F30C1BB41.md) | 30
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-100E032F234550530487627EC8FACAA8.md) | 33
[C:\WINDOWS\system32\ResetEngine.exe](ResetEngine.exe-5A802B773089A709FC7E731368C4E328.md) | 25
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 25
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-FD18CDC89BFD664E85644B460C37D85B.md) | 27
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-7582BF723A39B56BCCEF2C170E330BD7.md) | 27
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 29
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-AB2C7BC86F9E1BB245E43C81A01A7380.md) | 27
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-BE467A8F33CDEB0538E98CF10101E9E0.md) | 25

## Possible Misuse

*The following table contains possible examples of `DeviceCensus.exe` being misused. While `DeviceCensus.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_wmi_module_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_wmi_module_load.yml) | `- '\DeviceCensus.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


