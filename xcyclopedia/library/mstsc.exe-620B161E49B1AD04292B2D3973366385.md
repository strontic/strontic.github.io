---
title: mstsc.exe | Remote Desktop Connection
excerpt: What is mstsc.exe?
---

# mstsc.exe 

* File Path: `C:\Windows\system32\mstsc.exe`
* Description: Remote Desktop Connection

## Screenshot

![mstsc.exe](screenshots/mstsc.exe-15E40532CB76DB15B94901B8F22F7CDD-1.png)
![mstsc.exe](screenshots/mstsc.exe-15E40532CB76DB15B94901B8F22F7CDD-2.png)
![mstsc.exe](screenshots/mstsc.exe-15E40532CB76DB15B94901B8F22F7CDD-4.png)

## Hashes

Type | Hash
-- | --
MD5 | `620B161E49B1AD04292B2D3973366385`
SHA1 | `3B3A80B78D15AA647E520BE71EAD454805049A11`
SHA256 | `CF7882E388852EB0D62C4B5B40832947D18DAFCA4D2503BB30C4C8AE53A65647`
SHA384 | `D46AC8D1B0268EDBB187855ECE0F399A99DED6703BD1916497DC96FA310FC7E1B2FA23603FC8CAF45740180514C231D0`
SHA512 | `49E27AB2A2767587CC3B04D624619CDACF79A09248F678EDFB6A87C4F03EC29ED9A8AEA8E5A66F2FA4106C20FB6F30B419BC6BD23A9635A76435B9F64B5DFC9A`
SSDEEP | `98304:wqZ5q1jVV5SZ5ptRnFMn4Y2Z8jnwgI7bv3F8esVNxOWM9Mg:wqZ5q1jVV5SZ5ptRnFMn4Y2Z8jnwgI7D`
IMP | `43D4C98DB4E05AF16115818C6E500A33`
PESHA1 | `D8655DB63971B0A9E15C73BAB24240E3F429A0F0`
PE256 | `FC6C857EE6379B8B923FC840C6E1005506A98B6DEDBB3C777D8DCC6740CA2221`

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
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/cf7882e388852eb0d62c4b5b40832947d18dafca4d2503bb30c4c8ae53a65647/detection/


## Possible Misuse

*The following table contains possible examples of `mstsc.exe` being misused. While `mstsc.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_tsclient_filewrite_startup.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_tsclient_filewrite_startup.yml) | `Image: '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_rdp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/network_connection/sysmon_susp_rdp.yml) | `- '*\mstsc.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rdp_hijack_shadowing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rdp_hijack_shadowing.yml) | `title: MSTSC Shadowing` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_rdp_hijack_shadowing.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_rdp_hijack_shadowing.yml) | `description: Detects RDP session hijacking by using MSTSC shadowing` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | mstsc /v:$Server | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | $p=Tasklist /svc /fi "IMAGENAME eq mstsc.exe" /fo csv \| convertfrom-csv | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "srv\\newclient\\lib\\win32\\obj\\i386\\mstsc.pdb" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a2 = "taskkill /f /im mstsc.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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
or
```
mstsc /v:computer1 /f
```
To assign width/height, type:

```
mstsc /v:computer1 /w:1920 /h:1080
```
To open a file called *filename.rdp* for editing, type:

```
mstsc /edit filename.rdp
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


