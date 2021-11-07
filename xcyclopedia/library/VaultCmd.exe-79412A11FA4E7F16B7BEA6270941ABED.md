---
title: VaultCmd.exe | Vault cmdline Program
excerpt: What is VaultCmd.exe?
---

# VaultCmd.exe 

* File Path: `C:\windows\system32\VaultCmd.exe`
* Description: Vault cmdline Program

## Hashes

Type | Hash
-- | --
MD5 | `79412A11FA4E7F16B7BEA6270941ABED`
SHA1 | `F87ECC5312DDCA32EF03A96C44AAAC18E0867289`
SHA256 | `15667792199CC764A62E3E61F5380B08298A107B12C7C3D8109D8EDBBC11CC7B`
SHA384 | `FC43EF1579823E3977166EF74A292C00FE18613CAC1361370240AE8387611C59B3130889281A733911E45832AF5A6D41`
SHA512 | `E932B2E45C516D10A853962BB8A3C74BB0B17EBD35A9E6F24C1D5D6FBA693980D0288476AA209290F910D34225D1A76040D07E83B06BEC8C18CBC256973928E1`
SSDEEP | `384:Ani4neX2foNUVScJ46Mv/gXGcWcYQhQLAwAvDj7LSTARyyoImeLrqJFFBVWFFW:AzeX2QN8SqQIgca3AvDj7LxLOJPBM`

## Signature

* Status: The file C:\windows\system32\VaultCmd.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: VAULTCMD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `VaultCmd.exe` being misused. While `VaultCmd.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #4: Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Windows Credentials] [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #5: Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Web Credentials] [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #4: Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Windows Credentials] [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #5: Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Web Credentials] [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | - [Atomic Test #4 - Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Windows Credentials]](#atomic-test-4---enumerate-credentials-from-windows-credential-manager-using-vaultcmdexe-windows-credentials) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | - [Atomic Test #5 - Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Web Credentials]](#atomic-test-5---enumerate-credentials-from-windows-credential-manager-using-vaultcmdexe-web-credentials) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | ## Atomic Test #4 - Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Windows Credentials] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | This module will enumerate credentials stored in Windows Credentials vault of Windows Credential Manager using builtin utility vaultcmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | vaultcmd /listcreds:"Windows Credentials" /all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | ## Atomic Test #5 - Enumerate credentials from Windows Credential Manager using vaultcmd.exe [Web Credentials] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | This module will enumerate credentials stored in Web Credentials vault of Windows Credential Manager using builtin utility vaultcmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1555.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1555/T1555.md) | vaultcmd /listcreds:"Web Credentials" /all | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020-2021 Strontic.


