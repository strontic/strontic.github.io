---
title: tscon.exe | Session Connection Utility
excerpt: What is tscon.exe?
---

# tscon.exe 

* File Path: `C:\Windows\system32\tscon.exe`
* Description: Session Connection Utility

## Hashes

Type | Hash
-- | --
MD5 | `C016EB73D00753336161B7397DE4AA96`
SHA1 | `93C08CF77F7C5C8CCBE83499F3C0E01895404A40`
SHA256 | `BDC8ADA1C5F994A656A8B79BDB7A9F9935B5E49172FCD744B46CF78ED706D47B`
SHA384 | `4E8A84ADE5659FA21234015A45E0E6316D848D5834E678BDD8F6475106194BB356C4D9181A101757EF89FA2169FC04A5`
SHA512 | `A84908B06DD0202540B31D6A06413AE766437A598FE2CC4AF5815A749FE7DFFECCA27862D9395C4DC4F4F42FD9103B5FD62884ADEBB856C812C9379D2ABA782D`
SSDEEP | `384:MX122/6vmRvN4Cst5Qe9E/55nk4W6NNIdW/K+Q9f5hFHyIyrUIhzWjegW:MlzKFR/IZ5HqdCYx7IhB`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `tscon.exe` being misused. While `tscon.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `title: Suspicious TSCON Start` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `description: Detects a tscon.exe start as LOCAL SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `Image: '*\tscon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `title: Suspicious RDP Redirect Using TSCON` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `description: Detects a suspicious RDP session redirect using tscon.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | Adversaries may perform RDP session hijacking which involves stealing a legitimate user's remote session. Typically, a user is notified when someone else is trying to steal their session. With System permissions and using Terminal Services Console, `c:\windows\system32\tscon.exe [session number to be stolen]`, an adversary can hijack a session without the need for credentials or prompts to the user.(Citation: RDP Hijacking Korznikov) This can be done remotely or locally and with active or disconnected sessions.(Citation: RDP Hijacking Medium) It can also lead to [Remote System Discovery](https://attack.mitre.org/techniques/T1018) and Privilege Escalation by stealing a Domain Admin or higher privileged account session. All of this can be done by using native Windows commands, but it has also been added as a feature in red teaming tools.(Citation: Kali Redsnarf)</blockquote> | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | sc.exe create sesshijack binpath= "cmd.exe /k tscon #{Session_ID} /dest:#{Destination_ID}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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



MIT License. Copyright (c) 2020 Strontic.


