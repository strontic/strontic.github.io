---
title: DeviceCensus.exe | Device Census
---

# DeviceCensus.exe 

* File Path: `C:\WINDOWS\system32\DeviceCensus.exe`
* Description: Device Census

## Hashes

Type | Hash
-- | --
MD5 | `AC7BD0E738FDE12FB29DA98D88C903EA`
SHA1 | `83DCF09996467B8C9ED3DB56172E9DBC5D86A0C8`
SHA256 | `42D05239F096FB64197CD00BACCE0C0B390D9889BD108638BA792DE35BC2562E`
SHA384 | `5DECB50AA5DE13EE19BED441130256B300C34F4DD1D1B478F673E66383C28C9120307616A9D1C053DD41C6AA320D42C6`
SHA512 | `0BA268A9F52ABC3B28E6533AAE505A722DC79B13BBC690919DB03ACE9F9B2D82C5D3444A9BE9E14CC1003FCE63E437147BB1CC01FB1CA17CE8612B4DD3724010`
SSDEEP | `384:/9FRwpU6F4NF1s0bFOaog3N4UA7Oy1All2RtzVrMFWYG4i6XiWbgW7/zD1IDBRJ3:/3qp1ssuvWRCll0zrMF7G4i6XfnI1P3`

## Runtime Data

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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
[C:\program files (x86)\Common Files\Microsoft Shared\ink\TabTip32.exe](TabTip32.exe-DCB3378628CC715C93B9D53DF1857029.md) | 27
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 30
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-26FC7C7BDB99AB9B3EACB4BD513F6642.md) | 85
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-8159944C79034D2BCABF73D461A7E643.md) | 97
[C:\Windows\system32\dllhost.exe](dllhost.exe-C6723950D1A8CD49D93C8D082B175D41.md) | 30
[C:\Windows\system32\NDKPing.exe](NDKPing.exe-5FC26E00B9012CC0188F65BB999174E9.md) | 27
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-EA059E3BA7E07347BDE08EF016E09D50.md) | 30
[C:\Windows\system32\prproc.exe](prproc.exe-912400A90CA88E80ABC6CB8F30C1BB41.md) | 30
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-100E032F234550530487627EC8FACAA8.md) | 33
[C:\WINDOWS\system32\ResetEngine.exe](ResetEngine.exe-5A802B773089A709FC7E731368C4E328.md) | 25
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 29
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


