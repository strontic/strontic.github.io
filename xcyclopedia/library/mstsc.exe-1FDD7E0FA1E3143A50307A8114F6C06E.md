---
title: mstsc.exe | Remote Desktop Connection
---

# mstsc.exe 

* File Path: `C:\Windows\system32\mstsc.exe`
* Description: Remote Desktop Connection
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1FDD7E0FA1E3143A50307A8114F6C06E`
SHA1 | `C73032EEA47A4B63C6E8C388030847EFC31F71DB`
SHA256 | `A31EEA63100D2EC1DB5AE73A94120ED95E75421265679C4F72FADE9B9156DA90`
SHA384 | `209B9DE98881D61CE88C5D50D0A27E221F28E525A30E6550600D22D6D4C4372A58EDB2BE65FB849AA4FA243CF2A55150`
SHA512 | `B8B45354B66915117F19FB7287A28EB9464D1D3D6459512E9B30F046037669E235788ABE11098D25EAE5653761A954B7A6EE8388883CE2515482882D696836A6`
SSDEEP | `24576:ZPZQFGYMTqa44V0ek4rBadHiQl1tF2QZjQQgyKrF4fr8eeRQ+yf2EaAoxgMbZaj/:vQFGYMTqa44V0eDVadHioz2QZjQQgXFt`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mstsc.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `mstsc.exe` being misused. While `mstsc.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_tsclient_filewrite_startup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_tsclient_filewrite_startup.yml) | `        Image: '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_susp_rdp.yml) | `            - '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rdp_hijack_shadowing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rdp_hijack_shadowing.yml) | `title: MSTSC Shadowing` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rdp_hijack_shadowing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rdp_hijack_shadowing.yml) | `description: Detects RDP session hijacking by using MSTSC shadowing` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_susp_rdp.yml) | `            - '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_tsclient_filewrite_startup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/sysmon/sysmon_tsclient_filewrite_startup.yml) | `        Image: '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## mstsc

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Creates connections to Remote Desktop Session Host servers or other remote computers, edits an existing Remote Desktop Connection (.rdp) configuration file, and migrates legacy connection files that were created with Client Connection Manager to new .rdp connection files.

### Syntax

```
mstsc.exe [<connectionfile>] [/v:<server>[:<port>]] [/admin] [/f] [/w:<width> /h:<height>] [/public] [/span]
mstsc.exe /edit <connectionfile>
mstsc.exe /migrate
```

#### Parameters

| Parameter | Description |
| --------- | ------------|
| `<connectionfile>` | Specifies the name of an .rdp file for the connection. |
| /v:`<server>[:<port>]` | Specifies the remote computer and, optionally, the port number to which you want to connect. |
| /admin | Connects you to a session for administering the server. |
| /f | Starts Remote Desktop Connection in full-screen mode. |
| /w:`<width>` | Specifies the width of the Remote Desktop window. |
| /h:`<height>` | Specifies the height of the Remote Desktop window. |
| /public | Runs Remote Desktop in public mode. In public mode, passwords and bitmaps aren't cached. |
| /span | Matches the Remote Desktop width and height with the local virtual desktop, spanning across multiple monitors if necessary. |
| /edit `<connectionfile>` | Opens the specified .rdp file for editing. |
| /migrate | Migrates legacy connection files that were created with Client Connection Manager to new .rdp connection files. |
| /? | Displays help at the command prompt. |

##### Remarks

- Default.rdp is stored for each user as a hidden file in the user's **Documents** folder.

- User created .rdp files are saved by default in the user's **Documents** folder, but can be saved anywhere.

- To span across monitors, the monitors must use the same resolution and must be aligned horizontally (that is, side-by-side). There is currently no support for spanning multiple monitors vertically on the client system.

#### Examples

To connect to a session in full-screen mode, type:

```
mstsc /f
```

To open a file called *filename.rdp* for editing, type:

```
mstsc /edit filename.rdp
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


