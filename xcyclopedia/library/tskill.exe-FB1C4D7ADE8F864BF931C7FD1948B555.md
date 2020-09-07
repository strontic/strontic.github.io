---
title: tskill.exe | Remote Desktop Services End Process Utility
---

# tskill.exe 

* File Path: `C:\Windows\SysWOW64\tskill.exe`
* Description: Remote Desktop Services End Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `FB1C4D7ADE8F864BF931C7FD1948B555`
SHA1 | `BC76AA8F095D7FFF72C69D1D704849E1E71B6B50`
SHA256 | `B2FA07A9A1634079F537A5A81AF8D2C658B0F19483EEACA014C22111DB426EEC`
SHA384 | `55A9A1D4E45B49508C21727914B0F28AD3522CEC37743302BB5314F785A81C3106B39FB4638D3C865067A69762F0A16F`
SHA512 | `B30ABAF0BB04FB0931D031E134BC17C85CBF3A3682AA1144D46438991DF2231496AA9E9AE7DE8BFEE54C7DF126373C13437B4754F30E3D100746C2642D11859A`
SSDEEP | `384:nfC/dOQejY9qXIVb/Y0LhakXr3owymfj/IkC56W4kQWk5ff:nKVOQe81/R3M5dk`

## Runtime Data

### Usage (stderr):
```Batchfile
Invalid parameter(s)
Ends a process.

TSKILL processid | processname [/SERVER:servername] [/ID:sessionid | /A] [/V]

  processid           Process ID for the process to be terminated.
  processname         Process name to be terminated.
  /SERVER:servername  Server containing processID (default is current).
                         /ID or /A must be specified when using processname
                         and /SERVER
  /ID:sessionid       End process running under the specified session.
  /A                  End process running under ALL sessions.
  /V                  Display information about actions being performed.


```

## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tskill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends a process running in a session on a Remote Desktop Session Host server.


> [!NOTE]
> To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](/previous-versions/orphan-topics/ws.11/hh831527(v=ws.11)) in the Windows Server TechNet Library.

### Syntax
```
tskill {<ProcessID> | <ProcessName>} [/server:<ServerName>] [/id:<SessionID> | /a] [/v]
```

#### Parameters

|Parameter|Description|
|-------|--------|
|\<ProcessID>|Specifies the ID of the process that you want to end.|
|\<ProcessName>|Specifies the name of the process that you want to end. This parameter can include wildcard characters.|
|/server:\<ServerName>|Specifies the terminal server that contains the process that you want to end. If **/server** is not specified, the current RD Session Host server is used.|
|/id:\<SessionID>|Ends the process that is running in the specified session.|
|/a|Ends the process that is running in all sessions.|
|/v|Displays information about the actions being performed.|
|/?|Displays help at the command prompt.|

### Remarks
- You can use **tskill** to end only those processes that belong to you, unless you are an administrator. Administrators have full access to all **tskill** functions and can end processes that are running in other user sessions.
- When all processes that are running in a session end, the session also ends.
- if you use the *ProcessName* and the **/server:**<em>ServerName</em> parameters, you must also specify either the **/id:**<em>SessionID</em> or the **/a** parameter.

### Examples
- To end process 6543, type:
  ```
  tskill 6543
  ```
- To end the process explorer running on session 5, type:
  ```
  tskill explorer /id:5
  ```
  ## Additional References
  - [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)
  [Remote Desktop Services (Terminal Services) Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/remote-desktop-services-terminal-services-command-reference.md)

---



MIT License. Copyright (c) 2020 Strontic.


