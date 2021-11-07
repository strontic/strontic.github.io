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
MD5 | `54324BEC9270523FAB7FAB47CE70CDD7`
SHA1 | `24253D3D4D588D2232B4EC9418484A38A9B5C4F6`
SHA256 | `62CF87143D183E704AF6C6EB1A73EDA8D9F36497A71BFDD812F232CF01B553D6`
SHA384 | `5F0DC04DC0A7A71674DA14485E261A4E53F2D3BE04B84C458CF0411C6C1A792552CFFDE61CAB188A5A0D8D8DCAD060F2`
SHA512 | `F9B7803D6C6D15099CF7B80528354903F7E7DB345CD90FBBC1F59627EB0D8624197419CE019A01FB632FCB2A1E3EFDF6924218AC3C1CA6A1BBEC607043EF26FE`
SSDEEP | `384:cHcdzKY0S74r7ukS7cSTxJULCpkfnZ51OQ8HGaBOvxfbzYSXFsBeWiFW:LUG7sakS7cgyLCKZ50D8ZUSXFsBi`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: VAULTCMD.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


