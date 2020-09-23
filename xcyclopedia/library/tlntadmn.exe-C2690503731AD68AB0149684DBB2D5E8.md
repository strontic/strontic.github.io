---
title: tlntadmn.exe | 
excerpt: What is tlntadmn.exe?
---

# tlntadmn.exe 

* File Path: `C:\windows\system32\tlntadmn.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C2690503731AD68AB0149684DBB2D5E8`
SHA1 | `68D92CA650F14C821ACB8AEDF48FD321F2A45840`
SHA256 | `C71B3DBE6543D6755A15F6D31EFBAA590742C6C856D27BC3A257D540A0674E7E`
SHA384 | `F1E7C5A627D106CB75F12A0565D9D7DAE3E2DF67B4ED0D7A58E83A6138EA8829F969C985EF92BCB12B242604BA27E41E`
SHA512 | `9306689E8262D1860E8B693EFC943FE46D26D0623E1905B78EC7A6D97184D45008BE134128C4FFDF0F8EAA24B89EAA3DDBE43013A5E49B0CDD152D31AAE82102`
SSDEEP | `768:C/j1yRTXpMQ/6rbRpBwtx+PeqT+R9mUqekpva2lkCI8kMjjf4BSx8VgfxO69uGUr:Cj1y/eYxiecoEpXlVxJPf4so0uGK`

## Signature

* Status: The file C:\windows\system32\tlntadmn.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tnadmin.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tlntadmn

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Administers a local or remote computer that is running the telnet Server Service.

### Syntax
```
tlntadmn [<computerName>] [-u <UserName>] [-p <Password>] [{start | stop | pause | continue}] [-s {<SessionID> | all}] [-k {<SessionID> | all}] [-m {<SessionID> | all}  <Message>] [config [dom = <Domain>] [ctrlakeymap = {yes | no}] [timeout = <hh>:<mm>:<ss>] [timeoutactive = {yes | no}] [maxfail = <attempts>] [maxconn = <Connections>] [port = <Number>] [sec {+ | -}NTLM {+ | -}passwd] [mode = {console | stream}]] [-?]
```
##### Parameters

|                   Parameter                    |                                                                                                                                                       Description                                                                                                                                                        |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                \<computerName>                 |                                                                                                                    Specifies the name of the server to connect to. The default is the local computer.                                                                                                                    |
|         -u \<UserName> -p \<Password>          |                                                Specifies administrative credentials for a remote server that you want to administer. This parameter is required if you want to administer a remote server to which you are not logged on with administrative credentials.                                                |
|                     start                      |                                                                                                                                            starts the telnet Server Service.                                                                                                                                             |
|                      stop                      |                                                                                                                                             Stops the telnet Server Service                                                                                                                                              |
|                     pause                      |                                                                                                                          pauses the telnet Server Service. No new connections will be accepted.                                                                                                                          |
|                    continue                    |                                                                                                                                            Resumes the telnet Server Service.                                                                                                                                            |
|          -s {\<SessionID> &#124; all}          |                                                                                                                                             Displays active telnet sessions.                                                                                                                                             |
|          -k {\<SessionID> &#124; all}          |                                                                                                        Ends telnet sessions. type the Session ID to end a specific session, or type all to end all the sessions.                                                                                                         |
|    -m {\<SessionID> &#124; all}  <Message>     |                                                   Sends a message to one or more sessions. type the session ID to send a message to a specific session, or type all to send a message to all sessions. type the message that you want to send between quotation marks.                                                   |
|             config dom = \<Domain>             |                                                                                                                                      Configures the default domain for the server.                                                                                                                                       |
|      config ctrlakeymap = {yes &#124; no}      |                                                                                     Specifies if you want the telnet server to interpret CTRL+A as ALT. type **yes** to map the shortcut key, or type **no** to prevent the mapping.                                                                                     |
|       config timeout = \<hh>:\<mm>:\<ss>       |                                                                                                                                 Sets the time-out period in hours, minutes, and seconds.                                                                                                                                 |
|     config timeoutactive = {yes &#124; no      |                                                                                                                                            Enables the idle session timeout.                                                                                                                                             |
|          config maxfail = \<attempts>          |                                                                                                                          Sets the maximum number of failed logon attempts before disconnecting.                                                                                                                          |
|        config maxconn = \<Connections>         |                                                                                                                                         Sets the maximum number of connections.                                                                                                                                          |
|            config port = <\Number>             |                                                                                                                    Sets the telnet port. You must specify the port with an integer smaller than 1024.                                                                                                                    |
| config sec {+ &#124; -}NTLM {+ &#124; -}passwd | Specifies whether you want to use NTLM, a password, or both to authenticate logon attempts. To use a particular type of authentication, type a plus sign (**+**) before that type of authentication. To prevent using a particular type of authentication, type a minus sign (**-**) before that type of authentication. |
|     config mode = {console &#124; stream}      |                                                                                                                                             Specifies the mode of operation.                                                                                                                                             |
|                       -?                       |                                                                                                                                           Displays help at the command prompt.                                                                                                                                           |

### Remarks
-   To display the server settings, type **tlntadmn** without any parameters.
-   To use the **tlntadmn** command, you must log on to the local computer with administrative credentials. To administer a remote computer, you must also provide administrative credentials for the remote computer. You can do so by logging on to the local computer with an account that has administrative credentials for both the local computer and the remote computer. If you cannot use this method, you can use the **-u** and **-p** parameters to provide administrative credentials for the remote computer.

### Examples
Configure the idle session timeout to 30 minutes.
```
tlntadmn config timeout=0:30:0
```
Display active telnet sessions.
```
tlntadmn -s
```

### Additional References
-   [telnet Operations Guide](/previous-versions/windows/it-pro/windows-server-2008-R2-and-2008/cc753164(v=ws.10))
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


