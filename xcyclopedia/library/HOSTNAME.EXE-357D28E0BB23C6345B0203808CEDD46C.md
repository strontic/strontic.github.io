
# HOSTNAME.EXE 

* File Path: `C:\WINDOWS\SysWOW64\HOSTNAME.EXE`
* Description: Hostname APP
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `357D28E0BB23C6345B0203808CEDD46C`
SHA1 | `DCA4E6271334C660D585850E9CB5B538BB44EEAC`
SHA256 | `76BFA38D580C3B2982C4F78DF7C7CCBCC6A9383753E34F9968727BAC7B53B6B2`
SHA384 | `58D5E90E45953F77A257F1FFC97F907832AF53727F4FC3D7C00D89CA9E01E0B1C6CF5E761464F152C126DEEBD229E117`
SHA512 | `58E71C6F433BF798B767C383EDDDA019D734427F1D502CBB8B6550423BBF459048C8B43320372254883701C2810B527D2FE95CB42361CF5B902FD2087B915B16`
SSDEEP | `192:C4Mgw00PF5REIuoZj1m1ZWWgbXabxwubWE6WwY0:Tdw0gFnEIue1m1gWVbx3WE6W5`

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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


