---
title: tskill.exe | Remote Desktop Services End Process Utility
---

# tskill.exe 

* File Path: `C:\windows\system32\tskill.exe`
* Description: Remote Desktop Services End Process Utility

## Hashes

Type | Hash
-- | --
MD5 | `81E8B19A3D44C4F2B0BFB615182E03B2`
SHA1 | `971C2301CE910B3C8D3E70F21477DEB74ADAB1A2`
SHA256 | `A5FAE2450541751F488984A6DDA11CC3324EC3A98E063B9662DD535597778B58`
SHA384 | `044B6F0348BAB5912084BF79CF4DEEF01A5B9A1EAEFE09C005068732F66CCB8750046B0A2D564EFCD4BFC7754458A771`
SHA512 | `11CA774F46500DFA68FF0507B51563B245DD3B4B06DD726CB93207D08C2873E493F3B1A94F52190B72472A04CD22633ECAC320590EF6530AC056D4ECCAB18003`
SSDEEP | `384:pqrjAOrQUVkEqbkSY7jovpDEe55fArF6R4b302rZ6D5zRCleOSSW4pQW:mnr72Jbkde9sF6R4YLVOSI`

### Loaded Modules:

Path |
-- |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\tskill.exe |


## Signature

* Status: The file C:\windows\system32\tskill.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tskill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


