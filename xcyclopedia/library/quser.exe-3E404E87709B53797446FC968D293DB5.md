
# quser.exe 

* File Path: `C:\Windows\system32\quser.exe`
* Description: Query User Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3E404E87709B53797446FC968D293DB5`
SHA1 | `6C652A9A42A0CCEFB10E2478A19D8FF7AF4EFD1D`
SHA256 | `67D4FF2489B1C4E78928CA9AC9C1A79782A30BB976DC1AE49AC667CD5AC344A8`
SHA384 | `ED850B75E566BA8FC96B36DE5399082AB260860D4F9919362BF049301036C1616497D5BB579AE93016EA026CF7D16C1A`
SHA512 | `E38E1887190D88B27E8D8D2BD50B64E6EE1A5AF656AB9E761C5174176A7E9488BB5858891288F2C629940B4A989128D9558BACF1A0E7B154797E70BCBAB6832D`
SSDEEP | `384:y945Lr624gG8FKP8Xpiw7ASNTpti9rbJTEE55VzU/E4YnwjqX5yszGur/FWqPWSY:m4ZrB4gd8Pcow9pubJXPUMMmyqWqbI`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: quser.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
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


