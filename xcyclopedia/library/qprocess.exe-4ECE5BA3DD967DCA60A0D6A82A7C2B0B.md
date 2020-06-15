
# qprocess.exe 

* File Path: `C:\Windows\SysWOW64\qprocess.exe`
* Description: Query Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4ECE5BA3DD967DCA60A0D6A82A7C2B0B`
SHA1 | `DF1E31D88E72B5F9EC9E2642227033FF81534F9D`
SHA256 | `D5B92AB0654819674BADD553DF707A8E861D35D2565914EA8514D42B20C5B485`
SHA384 | `CC87FD2B9FDC8FB8F7FC7F57902798E786CD0830C038A4DE82FC336DA3FFA44414A5D216804536719B85241DCCB592AD`
SHA512 | `DBA05BE188DDC454376856414CA25D3BCECF7D88A6FFEA4546AB1F28F6F72A2020F309258D6A3A77CD02A04482B220394E57D3BC52A44B08A522245D2570EF19`
SSDEEP | `384:n09tT0SlB9wOVRT+qFrp+B6acXtQ+2wFLR2dUbBWLgE+2Wzb/:4T0KBpo+rbAu`

## Runtime Data

### Usage (stdout):
```Batchfile
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Displays information about processes.

QUERY PROCESS [* | processid | username | sessionname | /ID:nn | programname]
  [/SERVER:servername]

  *                  Display all visible processes.
  processid          Display process specified by processid.
  username           Display all processes belonging to username.
  sessionname        Display all processes running at sessionname.
  /ID:nn             Display all processes running at session nn.
  programname        Display all processes associated with programname.
  /SERVER:servername The Remote Desktop Session Host server to be queried.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qprocess.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# qprocess

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about processes that are running on a Remote Desktop Session Host (RD Session Host) server.

> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

## Remarks
This command is the same as the **query process** command.

## Additional References
[query process](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-process.md)
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
[Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---


MIT License. Copyright (c) 2020 Strontic.


