---
title: tsdiscon.exe | Session Disconnection Utility
excerpt: What is tsdiscon.exe?
---

# tsdiscon.exe 

* File Path: `C:\windows\system32\tsdiscon.exe`
* Description: Session Disconnection Utility

## Hashes

Type | Hash
-- | --
MD5 | `8B4E256F72C64974F37AB30328EDDBEB`
SHA1 | `38CB862090949683DE434EB0C8AB826D1E3ABC3B`
SHA256 | `DF20AE70BA1D8DA2FD3A5C6A0CB2A2F9FC0CA9C343512B3C276D3599F7D59A9E`
SHA384 | `0F0AF33354E4E06CE6CA7A949516B2DCD85D4A58397851C815B207C4807843C4E1A2B58D78AAA8DE345353AF9B7F78BF`
SHA512 | `82E199D7B0808D2B3F3171DE70BE19470875CBF735D4D70B1F85BF16446C9DE7551030F38C4A14EC2BF924C5553346E807349B83E74ADA76C1DF2872CBDD454C`
SSDEEP | `384:GmDJPtyFgu/5shmgtzGs7LKRvEc55lJvoxrnIvM2PRvbI9oQeeOLwWMnWW:Gm1P0//aYKJ4jdoxrroCZOL4`

## Signature

* Status: The file C:\windows\system32\tsdiscon.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tsdiscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\windows\system32\logoff.exe](logoff.exe-B8D1105A898B94F01EAFCE98E9C6F9D0.md) | 35


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tsdiscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Disconnects a session from a Remote Desktop Session Host server. If you don't specify a session ID or session name, this command disconnects the current session.

> [!IMPORTANT]
> You must have **Full Control access** permission or **Disconnect special access** permission to disconnect another user from a session.

> [!NOTE]
> To find out what's new in the latest version, see [What's New in Remote Desktop Services in Windows Server](/previous-versions/windows/it-pro/windows-server-2012-r2-and-2012/dn283323(v=ws.11)).

### Syntax

```
tsdiscon [<sessionID> | <sessionname>] [/server:<servername>] [/v]
```

#### Parameters

| Parameter | Description |
|--|--|
| `<sessionID>` | Specifies the ID of the session to disconnect. |
| `<sessionname>` | Specifies the name of the session to disconnect. |
| /server:`<servername>` | Specifies the terminal server that contains the session that you want to disconnect. Otherwise, the current Remote Desktop Session Host server is used. This parameter is required only if you run the **tsdiscon** command from a remote server. |
| /v | Displays information about the actions being performed. |
| /? | Displays help at the command prompt. |

##### Remarks

- Any applications running when you disconnected the session are automatically running when you reconnect to that session with no loss of data. You can use the [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md) to end the running applications of the disconnected session, but this may result in loss of data at the session.

- The console session can't be disconnected.

### Examples

To disconnect the current session, type:

```
tsdiscon
```

To disconnect *Session 10*, type:

```
tsdiscon 10
```

To disconnect the session named *TERM04*, type:

```
tsdiscon TERM04
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

- [reset session command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/reset-session.md)

---



MIT License. Copyright (c) 2020 Strontic.


