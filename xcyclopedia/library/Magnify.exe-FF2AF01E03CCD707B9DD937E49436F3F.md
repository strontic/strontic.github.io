---
title: Magnify.exe | Microsoft Screen Magnifier
excerpt: What is Magnify.exe?
---

# Magnify.exe 

* File Path: `C:\Windows\SysWOW64\Magnify.exe`
* Description: Microsoft Screen Magnifier

## Hashes

Type | Hash
-- | --
MD5 | `FF2AF01E03CCD707B9DD937E49436F3F`
SHA1 | `9BC4A22DC2E8931C21B931875A16EC8A94F5F5B0`
SHA256 | `33FCD1363966AB6478FE5B1061FA5A401BB8BF5C0996A837E1B08FF892393EF1`
SHA384 | `D274C665D44B43D8FFCCD3EAA5EC08E9AB4F0032F71ED08E051E8C715BD163AC142915B679F2A9DE4E14030474A74EE4`
SHA512 | `450AA663C3BF7A772E7C5FCFD6E7748BD7ECBDEAD23873E57E1B38927B446EFB792CA5FE27CDD910F646E222C96A3A66800B870319D95D6DDFF3FA760DC4ED88`
SSDEEP | `12288:6jeZBV2/droHDy3hAgNEFTt8XOykpyklYx:rZB8/drojy3hAgNYTzykpykix`
IMP | `5A38C436F6513FD9B5358A509D9AE21A`
PESHA1 | `1DBA70A0BF6041D7872994E9F03D48CE0E45684C`
PE256 | `07D0CE6DBBDF9C913ADA2D5CE0D74CCD69AA43CF9BD8327A41D4FFBF702625B0`

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ScreenMagnifier.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/33fcd1363966ab6478fe5b1061fa5a401bb8bf5c0996a837e1b08ff892393ef1/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Magnify.exe](Magnify.exe-1B8EFE43AE616AEC6D19AFFC54183FA5.md) | 43

## Possible Misuse

*The following table contains possible examples of `Magnify.exe` being misused. While `Magnify.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stickykey_like_backdoor.yml) | `- 'Magnify.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_install_reg_debugger_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_install_reg_debugger_backdoor.yml) | `- 'magnify.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [registry_event_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/registry_event_stickykey_like_backdoor.yml) | `- '\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\Magnify.exe\Debugger'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | * Magnifier: <code>C:\Windows\System32\Magnify.exe</code> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| parent_list \| Comma separated list of system binaries to which you want to attach each #{attached_process}. Default: "osk.exe" \| String \| osk.exe, sethc.exe, utilman.exe, magnify.exe, narrator.exe, DisplaySwitch.exe, atbroker.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | description = "Abnormal magnify.exe (Magnifier) - typical strings not found in file" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | $winxp = "Software\\Microsoft\\Magnify" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor_inverse_matches.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor_inverse_matches.yar) | filename =="magnify.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


