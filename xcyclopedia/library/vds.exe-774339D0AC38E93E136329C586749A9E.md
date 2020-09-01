---
title: vds.exe | Virtual Disk Service
---

# vds.exe 

* File Path: `C:\WINDOWS\system32\vds.exe`
* Description: Virtual Disk Service

## Hashes

Type | Hash
-- | --
MD5 | `774339D0AC38E93E136329C586749A9E`
SHA1 | `67F641569896762F61511DC916FCE797779328DE`
SHA256 | `DFB0F5C163B45F769BE1F0DBF51254B67BFE191E37B049628A659381B445983A`
SHA384 | `ACB37992FFA6E452A9A09C59A87143368FA273A7D5EAB451BD45FFD9D098F3E9A4AB92C7850284B971C4A1E05143662A`
SHA512 | `DB9B014B65A041DEA4A3943132F548C1A4B66E361121A26B7F5048A5BC3C4E1E0C1EDE6305EAFD489504863832EDE43F39DDEB228C4605014F871069289F227E`
SSDEEP | `6144:FaoyIxrIf9Qoyuy/Nr7YXCHUAKK4uUxjENrCUy04wRGE2hMEzmZ1G:gvOeytcC/14uUx4rh12hpWG`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\VaultCmd.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: vds.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `vds.exe` being misused. While `vds.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_raw_disk_access_using_illegitimate_tools.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_raw_disk_access_using_illegitimate_tools.yml) | `            - '\vds.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


