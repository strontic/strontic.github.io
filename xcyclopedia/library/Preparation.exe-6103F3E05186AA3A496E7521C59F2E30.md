﻿---
title: Preparation.exe | Microsoft Visual Studio 2015
excerpt: What is Preparation.exe?
---

# Preparation.exe 

* File Path: `C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\patch_KB3110221\Preparation.exe`
* Description: Microsoft Visual Studio 2015

## Hashes

Type | Hash
-- | --
MD5 | `6103F3E05186AA3A496E7521C59F2E30`
SHA1 | `504D877BF18A9EA7E18D968EA7A305ED9E322C16`
SHA256 | `FE5E41220930AC6DB6C7413A1F62835A5C5EFF9EEFB2083F813AA91270A63CA5`
SHA384 | `5F32C761CC70F9D2EB6CF04E0BE0201B34781AA995F914258DA3BF0DD74B5038DCE2560BE100AB3FD403628ADF91C7B3`
SHA512 | `58BAF260BAB9D740063099BA2A72797F262522850096C00E38E63F3C95B72A540FE9338F84385EAB101059DF19B1C54FB1278E62EBC1DFE4F48DD19140209EE1`
SSDEEP | `3072:h3PpcWd0dAeJopCjW+C1dvI8YOOYI0UmpKpmV2aT5qTEoN:EdAeJQCg7AmbEadEN`

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
* File Version: 14.0.24730.2 built by: D14VSULDR
* Product Version: 14.0.24730.2
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\vsupdate_KB3022398\Preparation.exe](Preparation.exe-A911C2DC24898DFD47B45467E4A9F092.md) | 80
[C:\ProgramData\Package Cache\00000000-0000-0000-0000-000000000000\packages\wdexpress_full\Preparation.exe](Preparation.exe-4B815231741879D4BDC210D49947F1AC.md) | 80

## Possible Misuse

*The following table contains possible examples of `Preparation.exe` being misused. While `Preparation.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `title: Privilege Escalation Preparation`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `description: Detects suspicious shell commands indicating the information gathering phase as preparation for the Privilege Escalation.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_shell_priv_esc_prep.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_shell_priv_esc_prep.yml) | `- https://patrick-bareiss.com/detect-privilege-escalation-preparation-in-linux-with-sigma/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_security_tap_driver_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_security_tap_driver_installation.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunnelling techniques`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tap_driver_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_tap_driver_installation.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunnelling techniques`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_tap_installer_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_tap_installer_execution.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunneling techniques`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_tap_driver_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_tap_driver_installation.yml) | `description: Well-known TAP software installation. Possible preparation for data exfiltration using tunnelling techniques`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.006.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.006/T1574.006.md) | <blockquote>Adversaries may execute their own malicious payloads by hijacking environment variables the dynamic linker uses to load shared libraries. During the execution preparation phase of a program, the dynamic linker loads specified absolute paths of shared libraries from environment variables and files, such as <code>LD_PRELOAD</code> on Linux or <code>DYLD_INSERT_LIBRARIES</code> on macOS. Libraries specified in environment variables are loaded first, taking precedence over system libraries with the same function name.(Citation: Man LD.SO)(Citation: TLDP Shared Libraries)(Citation: Apple Doco Archive Dynamic Libraries) These variables are often used by developers to debug binaries without needing to recompile, deconflict mapped symbols, and implement custom functions without changing the original library.(Citation: Baeldung LD_PRELOAD) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


