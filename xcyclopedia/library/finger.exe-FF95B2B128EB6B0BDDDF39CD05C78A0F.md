
# finger.exe 

* File Path: `C:\Windows\system32\finger.exe`
* Description: TCPIP Finger Command
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FF95B2B128EB6B0BDDDF39CD05C78A0F`
SHA1 | `EA35E56DD787C90E4BAD3DAE3DFD621E6188575C`
SHA256 | `DF1AE05C349A5C4E9D3187D0D85BD6172FB131BD5B826A1FFC947DB9A09F3DCF`
SHA384 | `037AC29CFF65182A3B83F056C01546BFC4A2E3CF2EB2CAECD05A481CA5CEFBB1BBB42A45F5DA3DB7EEFA6B0C782F7FB0`
SHA512 | `0D0B205294C9A79F58C83A870CE32E4EAAB020B3B0726559C01FD6EC16B5D41629C3B2F621570D4ED0320BB7129613A48FFA01F2B8EE959D3530FA4C8EDB9F97`
SSDEEP | `192:EwdcloBqMc+SDPhpT+qcXxmYFrurHF6h+YGkEYou3OD8r1oyW20W:Ewdcl6qM2tJKxmyru8eu3+0W20W`

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
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: finger.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# finger

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about users on a specified remote computer (typically a computer running UNIX) that is running the finger service or daemon. The remote computer specifies the format and output of the user information display. Used without parameters, **finger** displays help.

> [!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network Connections.

## Syntax

```
finger [-l] [<user>] [@<host>] [...]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| -l | Displays user information in long list format. |
| `<user>` | Specifies the user about which you want information. If you omit the *user* parameter, this command displays information about all users on the specified computer. |
| `@<host>` | Specifies the remote computer running the finger service where you are looking for user information. You can specify a computer name or IP address. |
| /? | Displays help at the command prompt. |

#### Remarks

- You must prefix **finger** parameters with a hyphen (-) rather than a slash (/).

- Multiple `user@host` parameters can be specified.

### Examples

To display information for *user1* on the computer *users.microsoft.com*, type:

```
finger user1@users.microsoft.com
```

To display information for *all users* on the computer *users.microsoft.com*, type:

```
finger @users.microsoft.com
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


