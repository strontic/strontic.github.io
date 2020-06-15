
# tscon.exe 

* File Path: `C:\Windows\SysWOW64\tscon.exe`
* Description: Session Connection Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C6EA34C2D9A6D7541E7E4C0DCA380795`
SHA1 | `6E140FEFE34B732220E05FCDF38718D936E649AA`
SHA256 | `71B4BC48247FBBA8E3D442E8043B93DAEB1C75C46E35072B832A84828671AC19`
SHA384 | `6C2DC304226BCDB4373A2BC878CF1482E4CB9DC23F3512572BD691F84154200F15B2CDC1D44F8DCE362FC078705D70D1`
SHA512 | `3E3E6E74D6F8DBA367F8AE48925C260FDAB33A0D1F3A2D487DDFC0F511C0543A8A2B79364558DD9F7729092581F270A2007549434211F5970BD86114560F3CF3`
SSDEEP | `384:4vrzYf9G/TQ9qrfb/qXsBakXjAJyc4E8TTWjegW2X:4fY1G/06/M6xThMX`

## Runtime Data

### Usage (stdout):
```Batchfile
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Attaches a user session to a remote desktop session.

TSCON {sessionid | sessionname} [/DEST:sessionname]
        [/PASSWORD:pw | /PASSWORD:*] [/V]

  sessionid          The ID of the session.
  sessionname        The name of the session.
  /DEST:sessionname  Connect the session to destination sessionname.
  /PASSWORD:pw       Password of user owning identified session.
  /V                 Displays information about the actions performed.


```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
# tscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Connects to another session on a Remote Desktop Session Host server.  

  

> [!NOTE]  
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.  

## Syntax  
```  
tscon {<SessionID> | <SessionName>} [/dest:<SessionName>] [/password:<pw> | /password:*] [/v]  
```  
### Parameters  

|Parameter|Description|  
|-------|--------|  
|\<SessionID>|Specifies the ID of the session to which you want to connect. If you use the optional **/dest:**<*SessionName*> parameter, this is the ID of the session to which you want to connect.|  
|\<SessionName>|Specifies the name of the session to which you want to connect.|  
|/dest:\<SessionName>|Specifies the name of the current session. This session will disconnect when you connect to the new session.|  
|/password:\<pw>|Specifies the password of the user who owns the session to which you want to connect. This password is required when the connecting user does not own the session.|  
|/password:*|prompts for the password of the user who owns the session to which you want to connect.|  
|/v|Displays information about the actions being performed.|  
|/?|Displays help at the command prompt.|  

## Remarks  
-   You must have Full Control access permission or Connect special access permission to connect to another session.  
-   The **/dest:**<*SessionName*> parameter allows you to connect the session of another user to a different session.  
-   if you do not specify a password in the <*Password*> parameter, and the target session belongs to a user other than the current one, **tscon** fails.  
-   You cannot connect to the console session.  

## Examples  
- To connect to session 12 on the current rd Session Host server and disconnect the current session, type:  
  ```  
  tscon 12  
  ```  
- To connect to session 23 on the current rd Session Host server, by using the password mypass, and disconnect the current session, type:  
  ```  
  tscon 23 /password:mypass  
  ```  
- To connect the session named TERM03 to the session named TERM05, and then disconnect session TERM05, if it is connected, type:  
  ```  
  tscon TERM03 /v /dest:TERM05  
  ```  
  ## Additional References  
  - [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)  
  [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)  

---


MIT License. Copyright (c) 2020 Strontic.


