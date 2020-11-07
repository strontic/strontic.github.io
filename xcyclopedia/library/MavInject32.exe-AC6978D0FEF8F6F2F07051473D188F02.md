---
title: MavInject32.exe | mavinject32
excerpt: What is MavInject32.exe?
---

# MavInject32.exe 

* File Path: `C:\Program Files\Common Files\microsoft shared\ClickToRun\MavInject32.exe`
* Description: mavinject32

## Hashes

Type | Hash
-- | --
MD5 | `AC6978D0FEF8F6F2F07051473D188F02`
SHA1 | `E50DA923C96E44B0D7987EB1E6A7940A05B511B4`
SHA256 | `84D4C479221646130ED559A78FB278996FBC060CF87DEBF6E8BD2C270A7D70F2`
SHA384 | `C4551D6545A47627944E5CE804089706F25A54CA7219886C1004DC24DA6AACE892897C32E4F8BA2D587CDB44790F8832`
SHA512 | `95147A5FF79642E007D718D095CFEFB424F7BD40DCE15F4810F27AE1D52C21F329F9649FBA9E654E3215747CB1FA6F8534F0A0D42C68BD75374530AD059D6AB9`
SSDEEP | `6144:tWhzr8SfxL/2Dc33C+U4tLsUL6mmt0fSoD78uLwsehNjRMX:tAwSfxL/2Dc3jDLLmt0LDQewsAjRE`
IMP | `EAD69853B7CB1B3BD5E661D99B54CF07`
PESHA1 | `FBAF7F111EE06FDBB8CD9A2FC75A3C3757F760B6`
PE256 | `ACBCBE6476FB0C72C94B13FD470968BBE07100FC314E4DC7A421AB3FF6569004`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files\Common Files\microsoft shared\ClickToRun\MavInject32.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `330000014096A9EE7056FECC07000100000140`
* Thumbprint: `98ED99A67886D020C564923B7DF25E9AC019DF26`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mavinject32.exe
* Product Name: Microsoft Application Virtualization (App-V)
* Company Name: Microsoft Corporation
* File Version: 5.0.10348.0
* Product Version: 5.0.10348.0
* Language: English (United States)
* Legal Copyright: Copyright  2014 Microsoft Corporation
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/84d4c479221646130ed559a78fb278996fbc060cf87debf6e8bd2c270a7d70f2/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVDllSurrogate32.exe](AppVDllSurrogate32.exe-BB87D970CD29CC07A84A92E637ADD9A2.md) | 35
[C:\Program Files (x86)\Microsoft Office\root\Client\AppVLP.exe](AppVLP.exe-F8CF92A63D69595CE0E6ECB9265EA7F7.md) | 33
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-49338D141DD60CA212D85F60521FB1DF.md) | 32
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-644673C741AB152A3E8904A5B4080489.md) | 29
[C:\WINDOWS\SysWOW64\mavinject.exe](mavinject.exe-8FE5871DE2870F39CFA317FA5C28988D.md) | 32
[C:\Windows\SysWOW64\mavinject.exe](mavinject.exe-B8B01B6A24B8A2BA242D96DB63298120.md) | 27

## Possible Misuse

*The following table contains possible examples of `MavInject32.exe` being misused. While `MavInject32.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_mavinject_proc_inj.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mavinject_proc_inj.yml) | `description: Detects process injection using the signed Windows tool Mavinject32.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


