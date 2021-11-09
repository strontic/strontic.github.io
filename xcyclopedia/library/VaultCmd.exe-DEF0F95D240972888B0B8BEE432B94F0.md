---
title: VaultCmd.exe | Vault cmdline Program
excerpt: What is VaultCmd.exe?
---

# VaultCmd.exe 

* File Path: `C:\WINDOWS\system32\VaultCmd.exe`
* Description: Vault cmdline Program

## Hashes

Type | Hash
-- | --
MD5 | `DEF0F95D240972888B0B8BEE432B94F0`
SHA1 | `3AF147508A86F482E33C19541048765232FD5E07`
SHA256 | `C3C92A650456D0034CFF5D514572EB282F419BF739652E04C3428797D0E2C84E`
SHA384 | `5AA6A8D142E22BBE915DAB655AC3DF23DEDE48CCEAF535A7790CB38C7E7DD22F3EE40FA6BF5CE847264AAF8070A22FBE`
SHA512 | `EBF9D9E2EF946B764C20AC607EA2185E5BA01057726C69EAAFA0DC7783685BC62A8777817DB3F389219590B8E42DC875BB0E94D9BFFCDEC7A2113CEFB81E7EA5`
SSDEEP | `768:5wxsoqfjMlO/GYpmoSmwdH825jvXXPQBY:ksoZlOOYi7nvXXPQBY`
IMP | `423E299DF33B8039596FF81AE53C9CA4`
PESHA1 | `10791CB220A14DE1AD25C661FFDE33A07364D594`
PE256 | `A5288F9AFA72842A3BB84857628180BD8E8345B79F5CD57F9396B5E6930DAA14`

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

### Child Processes:
RdpSa.exe

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\VaultCmd.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VAULTCMD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/c3c92a650456d0034cff5d514572eb282f419bf739652e04c3428797d0e2c84e/detection


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


