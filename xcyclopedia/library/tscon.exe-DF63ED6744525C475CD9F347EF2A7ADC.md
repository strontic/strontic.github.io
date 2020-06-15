
# tscon.exe 

* File Path: `C:\WINDOWS\system32\tscon.exe`
* Description: Session Connection Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `DF63ED6744525C475CD9F347EF2A7ADC`
SHA1 | `026E0FE254F4976B05539434CB0B979F466C1039`
SHA256 | `EC0E8104CEC80F4503FC1776F03B20D124A83AB3268968F3F1DE54FAC443F0B0`
SHA384 | `876840C4DECAAEF7906C95CF4780B73AF988784CC7522C7EE37567910A7AE7D5E675CA4C7AC478C317804C92CF653F88`
SHA512 | `68069EEAA3EF1BDC351D1E5040B0E89446563B9B179376F6C387B450F5973160E909108DC6DA2A8B6B5C504556CFCDF36A3FDEFD133959F2F78632AA4822E0B5`
SSDEEP | `384:Ex4GaOjrQ0Vd5mIbhzELz58xYK8+JVbCODeub+xfQHc5ycZs3bWjsgW:oXAcd4UhaeYK82lCqezxZW3H`

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
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


