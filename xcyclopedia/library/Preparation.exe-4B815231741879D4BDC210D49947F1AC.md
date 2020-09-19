---
title: Preparation.exe | Microsoft Visual Studio 2015
---

# Preparation.exe 

* File Path: `C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\wdexpress_full\Preparation.exe`
* Description: Microsoft Visual Studio 2015

## Hashes

Type | Hash
-- | --
MD5 | `4B815231741879D4BDC210D49947F1AC`
SHA1 | `2881C0C707E29C7268CDD3F9D81A6E53C63C1D80`
SHA256 | `9107BB3C06902071F3BB94E6D9986A57D8BED01EF3074A9FCF11CAE66952CBE5`
SHA384 | `C70D92386CE2AC7C34BED3317A1E6FCE2F68E814BFB9779DA6CC2B7AB23FDA7532830203883999F8CD00BFE67F8763C9`
SHA512 | `67DC63BB84F48CE0B70BC8BBEFFA737C82BF7C183AD7937F8172BE53ED307B9A043DECE483BD9020C79A2E32F8A0A57DDC94FEB61EDA4EE5774865C0CBAD5F69`
SSDEEP | `3072:/3PpKOd0dAeJopCjW+C1dvI8YOOYI0UmpKpu0PaT57qap:sdAeJQCg7Amjgadlp`

## Signature

* Status: Signature verified.
* Serial: `330000010A2C79AED7797BA6AC00010000010A`
* Thumbprint: `3BDA323E552DB1FDE5F4FBEE75D6D5B2B187EEDC`
* Issuer: CN=Microsoft Code Signing PCA, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, OU=MOPR, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Preparation.exe
* Product Name: Microsoft Visual Studio Preparation
* Company Name: Microsoft Corporation
* File Version: 14.0.23107.0 built by: D14REL
* Product Version: 14.0.23107.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\patch_KB3110221\Preparation.exe](Preparation.exe-6103F3E05186AA3A496E7521C59F2E30.md) | 80
[C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\vsupdate_KB3022398\Preparation.exe](Preparation.exe-A911C2DC24898DFD47B45467E4A9F092.md) | 85

## Possible Misuse

*The following table contains possible examples of `Preparation.exe` being misused. While `Preparation.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `title: Privilege Escalation Preparation` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `description: Detects suspicious shell commands indicating the information gathering phase as preparation for the Privilege Escalation.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `- https://patrick-bareiss.com/detect-privilege-escalation-preparation-in-linux-with-sigma/` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tap_driver_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_tap_driver_installation.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunnelling techniques` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tap_installer_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_tap_installer_execution.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunneling techniques` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


