
# quser.exe 

* File Path: `C:\WINDOWS\system32\quser.exe`
* Description: Query User Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3147F9B0C7089DD698778246E835C494`
SHA1 | `8040C04017E6B1AF0B704E632FA1FB4655D5EEF1`
SHA256 | `6EE15E5B1311D501FBDAA15C9D1197BA2F99745EA5ABB3E724D598EE53D48A6E`
SHA384 | `D800081202047346984F1BD904F87FACA2BB30BCCFF487500112BE4A21943667AB75A90BC878F9A51CBBAF823E88D42B`
SHA512 | `EEE3AB3655EB56E1FFD6EF9FAA86CA2DC2355D3466D94ABCA5B147DC46DBBCE994CFB911E0133564CDC50EAE49B5BB225570D089D0A641D5F3C972B9164CB553`
SSDEEP | `768:XdcgSIZE45pVrLSoYMmWyDwK895aPJ+dP:N9SgVrqy5aAdP`

## Runtime Data

### Usage (stdout):
```Batchfile
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Display information about users logged on to the system.

QUERY USER [username | sessionname | sessionid] [/SERVER:servername]

  username            Identifies the username.
  sessionname         Identifies the session named sessionname.
  sessionid           Identifies the session with ID sessionid.
  /SERVER:servername  The server to be queried (default is current).


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: quser.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# quser

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information about user sessions on a Remote Desktop Session Host (rd Session Host) server.  

> [!NOTE]  
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.  

## Remarks  
This command is the same as the **query user** command.  

## Additional References  
[query user](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/query-user.md)  
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)  
[Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)  

---


MIT License. Copyright (c) 2020 Strontic.


