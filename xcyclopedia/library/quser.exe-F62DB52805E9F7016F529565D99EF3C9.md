
# quser.exe 

* File Path: `C:\Windows\SysWOW64\quser.exe`
* Description: Query User Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `F62DB52805E9F7016F529565D99EF3C9`
SHA1 | `C842F013741901BCC4E15EDF2FFCA5E262D8C01B`
SHA256 | `EAE530A0D5CD045A90BBE6E12839AEC0383486CCDAAC07102D50250F381A2309`
SHA384 | `230F599CE7A04A4600AA4AF9881709A523A206EAE7F94308E879D955A66DFCF01750325433EC8B2CD0BA33D678EA6BFF`
SHA512 | `3B199C0F4766323BB4D11BB9A510B0B132F5129A0EF25811E4DF9544792D5622255F74C8FD515F9170C54EBF8E629CB29E0A8CB513AAD6C6968749601BE6001A`
SSDEEP | `384:Hu4v05f4EIE9aXi/aoqaEXR63o8RzgGDETULPWS3FWnSHLY:vM5f40x/m6VTLbISHLY`

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

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

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


