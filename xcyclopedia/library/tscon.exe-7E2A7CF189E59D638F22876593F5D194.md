﻿---
title: tscon.exe | Session Connection Utility
excerpt: What is tscon.exe?
---

# tscon.exe 

* File Path: `C:\Windows\SysWOW64\tscon.exe`
* Description: Session Connection Utility

## Hashes

Type | Hash
-- | --
MD5 | `7E2A7CF189E59D638F22876593F5D194`
SHA1 | `0B407F6EE053903F0E76FB4E4A2404F4DA60C4A3`
SHA256 | `B0837A65F983BF6C8D06E695AD60977F141066F1C8CB84753E75F96B9FAEE66C`
SHA384 | `891E1A5FE872EAE25AB90DB88231CD5253315D3B4EED7D5248D867B476356EAD0B455C01BD208F7D0BA589B286BA2BEB`
SHA512 | `C4AB2BEAFC90BF97A83F662E3CE1D09E41C8E59FC469E7F43019196599BA0B56D56B04E72D5C198AC007ADD65C7518C40F0854536BB5C39E73533A08E3761CEF`
SSDEEP | `384:0oai19OcbTqUcw/kWm9lSteKotZV5uY4x27v7WjigW7dT:0K9OczX/upVG2btD`
IMP | `A56882D0079E92DB91AA4874A2D331B8`
PESHA1 | `206F9C4A690F43964B6F44A05D26341F53FCB60A`
PE256 | `720688F69AA8EB3B1BEC81775CE2ECC1F39C28B5B357E3CAE622316A0087597B`

## Runtime Data

### Usage (stdout):
```cmhg
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

### Usage (stderr):
```cmhg
Invalid parameter(s)
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/b0837a65f983bf6c8d06e695ad60977f141066f1c8cb84753e75f96b9faee66c/detection/


## Possible Misuse

*The following table contains possible examples of `tscon.exe` being misused. While `tscon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `title: Suspicious TSCON Start`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `description: Detects a tscon.exe start as LOCAL SYSTEM`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `Image\|endswith: '\tscon.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `title: Suspicious RDP Redirect Using TSCON`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `description: Detects a suspicious RDP session redirect using tscon.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | Adversaries may perform RDP session hijacking which involves stealing a legitimate user's remote session. Typically, a user is notified when someone else is trying to steal their session. With System permissions and using Terminal Services Console, `c:\windows\system32\tscon.exe [session number to be stolen]`, an adversary can hijack a session without the need for credentials or prompts to the user.(Citation: RDP Hijacking Korznikov) This can be done remotely or locally and with active or disconnected sessions.(Citation: RDP Hijacking Medium) It can also lead to [Remote System Discovery](https://attack.mitre.org/techniques/T1018) and Privilege Escalation by stealing a Domain Admin or higher privileged account session. All of this can be done by using native Windows commands, but it has also been added as a feature in red teaming tools.(Citation: Kali Redsnarf)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | sc.exe create sesshijack binpath= "cmd.exe /k tscon #{Session_ID} /dest:#{Destination_ID}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tscon

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Connects to another session on a Remote Desktop Session Host server.

> [!IMPORTANT]
> You must have **Full Control access** permission or **Connect special access** permission to connect to another session.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
tscon {<sessionID> | <sessionname>} [/dest:<sessionname>] [/password:<pw> | /password:*] [/v]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<sessionID>` | Specifies the ID of the session to which you want to connect. If you use the optional `/dest:<sessionname>` parameter, you can also specify the name of the current session. |
| `<sessionname>` | Specifies the name of the session to which you want to connect. |
| /dest:`<sessionname>` | Specifies the name of the current session. This session will disconnect when you connect to the new session. You can also use this parameter to connect the session of another user to a different session. |
| /password:`<pw>` | Specifies the password of the user who owns the session to which you want to connect. This password is required when the connecting user does not own the session. |
| /password:`*` | Prompts for the password of the user who owns the session to which you want to connect. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- This command fails if you don't specify a password in the **/password** parameter, and the target session belongs to a user other than the current one.

- You can't connect to the console session.

### Examples

To connect to *Session 12* on the current Remote Desktop Services Session Host server, and to disconnect the current session, type:

```
tscon 12
```

To connect to *Session 23* on the current Remote Desktop Services Session Host server using the password *mypass*, and to disconnect the current session, type:

```
tscon 23 /password:mypass
```

To connect the session named *TERM03* to the session named *TERM05*, and then to disconnect session *TERM05*, type:

```
tscon TERM03 /v /dest:TERM05
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


