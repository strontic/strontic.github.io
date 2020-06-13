
# qprocess.exe 

* File Path: `C:\WINDOWS\system32\qprocess.exe`
* Description: Query Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `B9512ABDF1F4982292DC60D11EDA20DF`
SHA1 | `5F28B8A7DF02B0F5E8B39BD1D3978F615B0CD3F6`
SHA256 | `C325DF5932FB17D7909B633D11AAC31BE603BC210DBE3173AFC237C22D206703`
SHA384 | `48B53A63A918337F5F9CF5BC83DDA283023F35D1D5868334A661144B39DFC7B6C1BB6653CF5B9FD5264374C1FD9CBA54`
SHA512 | `1FA36B64371BAD345BAC5D5CB72752202717149AEBE409CA8C065C83D55D66FEAEBA1A95549DB1A7ADB043012593B2537D3778FCC691C42038991F02A312BE8B`
SSDEEP | `768:48igjPq3JqPcvSphuU1EK8sB8HU/DY/y:hGZipYcBBMy`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: qprocess.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


