
# qprocess.exe 

* File Path: `C:\Windows\system32\qprocess.exe`
* Description: Query Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `179E779B7BB0ED05A420C34D51DB7E4B`
SHA1 | `70BFD877E1736F23F4153423343C89A4693455C0`
SHA256 | `017E9E2914E74A951DA7FCB4E281C2BE2A1C246EE2942E6D540D612F675586D9`
SHA384 | `3D01C7B30ABEA885CB62B75952AE0B6680E7EF9707A0FB0F742C018BB10857D3060257C745E9A8962028A26EB6E0180D`
SHA512 | `DCADA2AB2AF08A9652017504931A09184C01443E2788FB3A7916122FF4A701A164C98DCBC5562C1888CA30783FF04EBDA5601B9958433AD47D19C6B911798A4B`
SSDEEP | `384:UNbL5jXhznOMC2BoH3S4tXHZeCGl5c3kbaEF55rLutDPgsKviTV5p0gdc9YXBFoJ:wbVN7FC2Z4neV5HhBqDv7zp0ooTVQ`

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


