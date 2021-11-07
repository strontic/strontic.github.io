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
MD5 | `5F69F4F8683151A59C5A11265B4A3C96`
SHA1 | `95AE738AB6B2CC92D88E3DEBBAACDD924BC27F5E`
SHA256 | `EDC1B6A3E4FDE216A323329E35F4192B0F49BC68285EE67036DEFF9E94C4E33A`
SHA384 | `4FD25542E14EF99158C31B3278F7E209EE09327980393C7555F6386E0EE7D27D0C23D941E0F1E9BA77FC6D1AF0EFCBA6`
SHA512 | `33FD26E122685C5D9E49930CF4C64237D157443EA43DD82423187C6B71E19539BC3C9582D567736BAC3D8D27B604F32514F85EEFA8E8A5E5B26B9F402B23BEBF`
SSDEEP | `768:fs4TjbWSCdB16t4D+GJmiPioMNFzXn7Bv:fTjb7yPioWFzXn7Bv`
IMP | `692BBD94F45AD2DFEFD2A3DA11FCCE0F`
PESHA1 | `8AD190CA516BE4D2011FAB4CCA027EF3C7A9556E`
PE256 | `1FAB228260D00955882172B836AA658E48A7A27D1506F3B1B4448A3C95B05490`

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

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\VaultCmd.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VAULTCMD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/edc1b6a3e4fde216a323329e35f4192b0f49bc68285ee67036deff9e94c4e33a/detection


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


