---
title: tscon.exe | Session Connection Utility
---

# tscon.exe 

* File Path: `C:\windows\system32\tscon.exe`
* Description: Session Connection Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `074538506BFAE9C0087C246AB3C59218`
SHA1 | `A8DBB83381DD40A76CFD4F0B5A21C42991597408`
SHA256 | `9A47AAFC2C4104733BD3C6D7F8458D1F7669496DF2C0EABC2C8D0BE75FEEB129`
SHA384 | `F1CEA9343C1FB687001BB9E70E65AA916D659AEA82DD4719E385E09F0E3BD332B65325C10C8097B5EFA54F2540BB0895`
SHA512 | `41BDB2DA92F0F2F3BAB90EE619588772E9741FB61C31F348D7967AAF4EA39173104713AFD2BE11151812736F211A064A5EBB3439EBDF3B89C93AF1CCBEC1FF62`
SSDEEP | `384:DkDdlQS/hFkOcDz6N4s7vyOCE155bjSkF9cyF9x2M/sD2VcobeeO5zWjPgW:Dolv/TrAmVzV9WO9cod/uAO5s`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\tscon.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tscon.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `tscon.exe` being misused. While `tscon.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `title: Suspicious TSCON Start` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `description: Detects a tscon.exe start as LOCAL SYSTEM` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_localsystem.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_localsystem.yml) | `        Image: '*\tscon.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `title: Suspicious RDP Redirect Using TSCON` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_tscon_rdp_redirect.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_tscon_rdp_redirect.yml) | `description: Detects a suspicious RDP session redirect using tscon.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.001/T1021.001.md) | sc.exe create sesshijack binpath= "cmd.exe /k tscon #{Session_ID} /dest:#{Destination_ID}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tscon

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Connects to another session on a Remote Desktop Session Host server.



> [!NOTE]
> In Windows Server 2008 R2, Terminal Services was renamed Remote Desktop Services. To find out what's new in the latest version, see [What s New in Remote Desktop Services in Windows Server 2012](https://technet.microsoft.com/library/hh831527) in the Windows Server TechNet Library.

### Syntax
```
tscon {<SessionID> | <SessionName>} [/dest:<SessionName>] [/password:<pw> | /password:*] [/v]
```
#### Parameters

|Parameter|Description|
|-------|--------|
|\<SessionID>|Specifies the ID of the session to which you want to connect. If you use the optional **/dest:**<*SessionName*> parameter, this is the ID of the session to which you want to connect.|
|\<SessionName>|Specifies the name of the session to which you want to connect.|
|/dest:\<SessionName>|Specifies the name of the current session. This session will disconnect when you connect to the new session.|
|/password:\<pw>|Specifies the password of the user who owns the session to which you want to connect. This password is required when the connecting user does not own the session.|
|/password:*|prompts for the password of the user who owns the session to which you want to connect.|
|/v|Displays information about the actions being performed.|
|/?|Displays help at the command prompt.|

### Remarks
-   You must have Full Control access permission or Connect special access permission to connect to another session.
-   The **/dest:**<*SessionName*> parameter allows you to connect the session of another user to a different session.
-   if you do not specify a password in the <*Password*> parameter, and the target session belongs to a user other than the current one, **tscon** fails.
-   You cannot connect to the console session.

### Examples
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


