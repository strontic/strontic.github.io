
# HOSTNAME.EXE 

* File Path: `C:\Windows\SysWOW64\HOSTNAME.EXE`
* Description: Hostname APP
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `FE94C0F04071B788C7DF4EA0FBF3BD7E`
SHA1 | `57999E8595EBCEAF65698461DE02E259B19844C0`
SHA256 | `5AF3F93786332B1038792E7FD34C0FF75D3F9420DF4B723207C59146233D67BF`
SHA384 | `132D326BEE45AA4D79154B8F42A90103A50CA9A410656D2D8C7B4AC5702C1B1C81419E820DAA126E37EB749315586FEE`
SHA512 | `AEE29FC629918A055FC0BBAC87872FDDF44C1EF088391F757FFF5F7FD15827FA0C4FA2BE508781C14BC7C00128ACD7DB4E2D17F84A27078F1B62AF28FF80BCF7`
SSDEEP | `192:gpTHig8HMuXWM+T5N7g7vWngc1XHNXSpbjW26Wid:cigYMuXWb37g7On7NXoHW26W`

## Runtime Data

### Usage (stdout):
```Batchfile

Prints the name of the current host.

hostname


```

### Usage (stderr):
```Batchfile
sethostname: Use the Network Control Panel Applet to set hostname.
hostname -s is not supported.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001733031072665B8B9B3000000000173`
* Thumbprint: `14590DC5C3AAF238FCFD7785B4B93F4071402C34`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

# hostname

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the host name portion of the full computer name of the computer.

>[!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network.

## Syntax

```
hostname
```

### Parameters
| Parameter | Description |
| ------- | -------- |
| /? | Displays help at the command prompt. |

### Examples

To display the name of the computer, type:

```
hostname
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


