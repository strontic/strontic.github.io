---
title: finger.exe | TCPIP Finger Command
---

# finger.exe 

* File Path: `C:\windows\SysWOW64\finger.exe`
* Description: TCPIP Finger Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `12F4A450805172B74227AB0D3F7AF151`
SHA1 | `2EC3DDA4BB72FC136774F84A1FE15B1CCE047C9F`
SHA256 | `621F2CC798234A31B17B90CFC91B6E6F9A3A249E37EA9C235AB83E39FA4C7E63`
SHA384 | `83DE091890CE4A0A327616CC1B52E3BE755F13F79B18C54DEDBC691AFBB816B12204370AB3D0E1371798DA92D86688A7`
SHA512 | `384B922062077EED7983E751180C61F34716CF94777AF9C4C6EE7B4B3559DDCAADE662060D0B8C9A34F85201B1099410F3C1E8405CBAE9CD87ED022A6D07DECB`
SSDEEP | `192:W9W/jd6t+vAJLcH9CXDYqTgDmXfmXp6MvERjJ6wWAW60WjTFf:9bLvAJY9C0qTDX+XROjJ15W60Wj`

## Runtime Data

### Usage (stdout):
```Batchfile

[Strontic5]

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
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\WINDOWS\SysWOW64\finger.exe](finger.exe-548BD137905CFDF1D1CE54682305FA3D.md) | 52


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


