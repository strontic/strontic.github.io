---
title: MsMpEng.exe | Antimalware Service Executable
excerpt: What is MsMpEng.exe?
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2006.10-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `7E6A1F2089954CAC26D5C6FA6D83B8B2`
SHA1 | `05AB603053EFC9EBA363FB4C320974C37E49DA15`
SHA256 | `A601DF49E5E6B2A5477A2516260FC01DBEF186D7FD1C458C2BC57F7342E5BB9F`
SHA384 | `A592ABC76FCA241515A2E81112733C1E8ED42DD6FC83B02CA00840416AA55412F2A85C4D8732A1EBFC36059802F7BE02`
SHA512 | `72E39AD6DD91BAE17510CF15A8D0ED19B0A274AF232CC50C42E32A1DA3BF501EC081755AF80C1E69498AAD89024F34E661AB9CDE4B57E4CFD70B10F05003522E`
SSDEEP | `3072:3JxCU1lTwUlA1mpKvCXKTeigfhaEqGMMdZkZ:ZhZwnOKKyqaEq64`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2006.10-0\MsMpEng.exe |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `330000024A0E8AFDF15C662D2B00000000024A`
* Thumbprint: `96384A7F5F1C438F32E2454697DC6D312A74517B`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2006.10 (WinBuild.160101.0800)
* Product Version: 4.18.2006.10
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `MsMpEng.exe` being misused. While `MsMpEng.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- '*MsMpEng.exe*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- MsMpEng.exe can crash when C:\ is full`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\Windows Defender\\*\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `- '*\MsMpEng.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $s1 = "MsMpEng.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [1258b063-27d6-489b-a677-4807faacf868.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/1258b063-27d6-489b-a677-4807faacf868.yml) | `"msmpeng",`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


