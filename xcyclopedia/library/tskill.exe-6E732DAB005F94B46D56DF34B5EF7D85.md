
# tskill.exe 

* File Path: `C:\WINDOWS\system32\tskill.exe`
* Description: Remote Desktop Services End Process Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6E732DAB005F94B46D56DF34B5EF7D85`
SHA1 | `B86C1D15DD8812DAFE45584289D44DFDF8168CD8`
SHA256 | `1B92303B2B2D13F02F45F7164BC0B73EE39FB6CEE6C61296904BD7F7C87E4685`
SHA384 | `9A8FD7AB844CCC8895149107718FA8242346CE16D240292C60E53A1DA026D25338AA241CC3ED25A19CC19854F69C4601`
SHA512 | `DD096D8B69749202F1CCB5145D346BDC27A8FBC8D48B5C1281404BE5CB59F563AE7EDF21350265CE2571383E10BC674F883FE414099CA71C1D13A581FDB8880E`
SSDEEP | `384:deUPfdE901EeMrjS/JI8lEgz5ZhJK8bg1Kl4uwkU2i4xxC5xCInHWqSUZpyCyW42:deUoyQrjSBI8zJJK8bcKZwPNmxC5xCsp`

## Runtime Data

### Usage (stdout):
```Batchfile

```

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

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tskill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends a process running in a session on a Remote Desktop Session Host server.


> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

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


