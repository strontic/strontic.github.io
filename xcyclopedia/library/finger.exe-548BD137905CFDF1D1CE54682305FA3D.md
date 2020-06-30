---
title: finger.exe | TCPIP Finger Command
---

# finger.exe 

* File Path: `C:\WINDOWS\SysWOW64\finger.exe`
* Description: TCPIP Finger Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `548BD137905CFDF1D1CE54682305FA3D`
SHA1 | `3616ED0E330CC8843CBA246C5E3FCCAE2E988B2E`
SHA256 | `6761440DE752EC2FDBBD367486F4B077A912AC4EEFC26C05052D7E36DC6FFA1B`
SHA384 | `AE5FAE4F3712C718EC1B5505A0747C4A86688228541F15EA517F0CBE45E5A6D6B73BEECC493675D19E1932B508814813`
SHA512 | `A2701FF4E71C68327C83DC09A2022CC0A4C1B2C5AD0867A959753CD4D3DAE8E7609DDB936E7C86985A43AA5547456A39C6067F29FAF4E399EE96525EFCA2FB4B`
SSDEEP | `192:cfE/7RoJqMujnHDQ2jgDmXPmXp6MvE1jJ6wWwWU0W:NTRoJcjn82jjXuXRqjJ1pWU0W`

## Runtime Data

### Usage (stdout):
```Batchfile

[default-pc]

```

### Usage (stderr):
```Batchfile

Displays information about a user on a specified system running the
Finger service. Output varies based on the remote system.

FINGER [-l] [user]@host [...]

  -l        Displays information in long list format.
  user      Specifies the user you want information about. Omit the user
            parameter to display information about all users on the
            specifed host.
  @host     Specifies the server on the remote system whose users you
            want information about.


```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\finger.exe](finger.exe-12F4A450805172B74227AB0D3F7AF151.md) | 52


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## finger

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about users on a specified remote computer (typically a computer running UNIX) that is running the finger service or daemon. The remote computer specifies the format and output of the user information display. Used without parameters, **finger** displays help.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

### Syntax

```
finger [-l] [<user>] [@<host>] [...]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| -l | Displays user information in long list format. |
| `<user>` | Specifies the user about which you want information. If you omit the *user* parameter, this command displays information about all users on the specified computer. |
| `@<host>` | Specifies the remote computer running the finger service where you are looking for user information. You can specify a computer name or IP address. |
| /? | Displays help at the command prompt. |

##### Remarks

- You must prefix **finger** parameters with a hyphen (-) rather than a slash (/).

- Multiple `user@host` parameters can be specified.

#### Examples

To display information for *user1* on the computer *users.microsoft.com*, type:

```
finger user1@users.microsoft.com
```

To display information for *all users* on the computer *users.microsoft.com*, type:

```
finger @users.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


