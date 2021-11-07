---
title: VaultCmd.exe | Vault cmdline Program
excerpt: What is VaultCmd.exe?
---

# VaultCmd.exe 

* File Path: `C:\Windows\system32\VaultCmd.exe`
* Description: Vault cmdline Program

## Hashes

Type | Hash
-- | --
MD5 | `306E548A802A8FFCD6D5360CD13D6612`
SHA1 | `69DC9047C73056C061EBE259F16985C9EABA166C`
SHA256 | `52BE7172716ABBC00F6190D27C24FAC24E6A871E4E6BFEA608E50D254737FC59`
SHA384 | `81A5B73D87BC54DB8FA650D2E96DC551371C4F5E5A2989751214C3D67494F8906112764DA0F4E032A08076D2536BA5D4`
SHA512 | `8B309B01B8FEA58823178B587332A72B1C62F6EA15D0814041B4510622C2A790B3CA995AFC04DD0F38713C430A0983F03CB57DFADC377394E19B2CD48745424D`
SSDEEP | `384:6HP+BIhjOAVnyluGSkhJrefbHjcN5GMuetruHIp7bYjAVkBNWYFW:EP7XVnyQGS08fbDcLGPeKo8jAqBZ`

## Runtime Data

### Usage (stdout):
```cmhg
Creates, displays and deletes stored credentials.
Following commands are supported.Use VaultCmd /<command> /? for further help 
VaultCmd /list
VaultCmd /listschema
VaultCmd /listcreds
VaultCmd /addcreds
VaultCmd /deletecreds
VaultCmd /listproperties
VaultCmd /sync

```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VAULTCMD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


