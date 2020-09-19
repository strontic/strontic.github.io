---
title: MsMpEng.exe | Antimalware Service Executable
---

# MsMpEng.exe 

* File Path: `C:\ProgramData\Microsoft\Windows Defender\Platform\4.18.2001.10-0\MsMpEng.exe`
* Description: Antimalware Service Executable

## Hashes

Type | Hash
-- | --
MD5 | `F6B04D08ECC4B9FF446CAB52EC622618`
SHA1 | `4F40E568E2C63C6AAF4D28157BAFA5C0C1694AB9`
SHA256 | `55CB6465F4038330E4705440CC5623D79805BBD1D33DB0CFF8B016EB2AC20D3F`
SHA384 | `90A57AE690195ED8F561866B97271EDD533C1E346B8160AB4971FF07D301F7FB36E9E9C5B2F8EDCC0936A0864A0B1AF5`
SHA512 | `68027A7D211BCBF01DA3E62A1467652DA6AE8A67406438034F2CB5BAF9CCB6B3204F69A3EE381B3ABCBE9B399E7CE97FABAA58FCA82CC571CE28539673F37482`
SSDEEP | `1536:/w22jtIgAVwgLJnT6BnnDm1CnE/+i3V3KTeqGeKDmVpWUBwDPs:IHJHglnTQDm1mEr3V3KTeq3KDmVpzwDU`

## Signature

* Status: Signature verified.
* Serial: `3300000216CA389B93E0C73695000000000216`
* Thumbprint: `7D827CF26BD7A3AFA75051801568E35191389BF5`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MsMpEng.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 4.18.2001.10 (WinBuild.160101.0800)
* Product Version: 4.18.2001.10
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Microsoft\Windows Defender\platform\4.18.2003.8-0\MsMpEng.exe](MsMpEng.exe-331A9DAB79909E3012F0FBD1BA870757.md) | 82

## Possible Misuse

*The following table contains possible examples of `MsMpEng.exe` being misused. While `MsMpEng.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- '*MsMpEng.exe*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_msmpeng_crash.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_msmpeng_crash.yml) | `- MsMpEng.exe can crash when C:\ is full` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_plugx_susp_exe_locations.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_plugx_susp_exe_locations.yml) | `Image: '*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_proc_wrong_parent.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_proc_wrong_parent.yml) | `- '*\Windows Defender\\*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_svchost.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_svchost.yml) | `- '*\MsMpEng.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) |       $s1 = "MsMpEng.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


