---
title: taskkill.exe | Terminates Processes
---

# taskkill.exe 

* File Path: `C:\windows\system32\taskkill.exe`
* Description: Terminates Processes
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0BDA7EC0A57799EF56854017F57E9F9B`
SHA1 | `38B1DF4EF753FF67B2EA5069B1B18841F58AA02F`
SHA256 | `864D801AEC0B788EB0880A4DE45B202796273867CF08DAF247B672A25704035B`
SHA384 | `62DD9F819DD80EFBF1C78BFB5D7571500B53241666900D6D847F100348EC00EFC0EF84BAAF1571CC0275B092D953F563`
SHA512 | `7A7C167C08F5121EC179F06DABCEAF8662F54F858CD369AE1BEDEE76DC55151ED02E666EB3ACDC1CBD29849E9E3A1EA50CE69E2C71CEE8BD7B05C6761365363B`
SSDEEP | `3072:EH3ZD80M/Xp6hy2XCquuYZeH5ToM+J/8tDu2xQ:8I0MB1eHlt0ktDu`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\system32\taskkill.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: taskkill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `taskkill.exe` being misused. While `taskkill.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `            - cmd.exe /c taskkill /im cmd.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `            - taskkill.exe` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Rundll32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Rundll32.yml) | `  - Command: rundll32.exe javascript:"\..\mshtml,RunHTMLApplication ";document.write();h=new%20ActiveXObject("WScript.Shell").run("calc.exe",0,true);try{h.Send();b=h.ResponseText;eval(b);}catch(e){new%20ActiveXObject("WScript.Shell").Run("cmd /c taskkill /f /im rundll32.exe",0,true);}` | 
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | taskkill /f /im calculator.exe >nul 2>nul | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1489.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1489/T1489.md) | taskkill.exe /f /im #{process_name} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.002/T1574.002.md) | taskkill /F /IM #{process_name} >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## taskkill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends one or more tasks or processes. Processes can be ended by process ID or image name. **taskkill** replaces the **kill** tool.

For examples of how to use this command, see [Examples](#examples).

### Syntax

```
taskkill [/s <computer> [/u [<Domain>\]<UserName> [/p [<Password>]]]] {[/fi <Filter>] [...] [/pid <ProcessID> | /im <ImageName>]} [/f] [/t]
```

#### Parameters

|         Parameter         |                                                                                                                                        Description                                                                                                                                        |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|      /s \<computer>       |                                                                                    Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer.                                                                                     |
| /u \<Domain>\\\<UserName> | Runs the command with the account permissions of the user who is specified by *UserName* or *Domain*\\*UserName*. **/u** can be specified only if **/s** is specified. The default is the permissions of the user who is currently logged on to the computer that is issuing the command. |
|      /p \<Password>       |                                                                                                   Specifies the password of the user account that is specified in the **/u** parameter.                                                                                                   |
|       /fi \<Filter>       |          Applies a filter to select a set of tasks. You can use more than one filter or use the wildcard character (**\\**\*) to specify all tasks or image names. See the following [table for valid filter names](#filter-names-operators-and-values), operators, and values.           |
|     /pid \<ProcessID>     |                                                                                                                 Specifies the process ID of the process to be terminated.                                                                                                                 |
|     /im \<ImageName>      |                                                                                Specifies the image name of the process to be terminated. Use the wildcard character (**\\**\*) to specify all image names.                                                                                |
|            /f             |                                                                    Specifies that processes be forcefully terminated. This parameter is ignored for remote processes; all remote processes are forcefully terminated.                                                                     |
|            /t             |                                                                                                          Terminates the specified process and any child processes started by it.                                                                                                          |

##### Filter names, operators, and values

| Filter Name |    Valid Operators     |                                                                Valid Value(s)                                                                |
|-------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|   STATUS    |         eq, ne         |                                                 RUNNING &#124; NOT RESPONDING &#124; UNKNOWN                                                 |
|  IMAGENAME  |         eq, ne         |                                                                  Image name                                                                  |
|     PID     | eq, ne, gt, lt, ge, le |                                                                  PID value                                                                   |
|   SESSION   | eq, ne, gt, lt, ge, le |                                                                Session number                                                                |
|   CPUtime   | eq, ne, gt, lt, ge, le | CPU time in the format <em>HH</em>**:**<em>MM</em>**:**<em>SS</em>, where *MM* and *SS* are between 0 and 59 and *HH* is any unsigned number |
|  MEMUSAGE   | eq, ne, gt, lt, ge, le |                                                              Memory usage in KB                                                              |
|  USERNAME   |         eq, ne         |                                               Any valid user name (*User* or *Domain*\\*User*)                                               |
|  SERVICES   |         eq, ne         |                                                                 Service name                                                                 |
| WINDOWTITLE |         eq, ne         |                                                                 Window title                                                                 |
|   MODULES   |         eq, ne         |                                                                   DLL name                                                                   |

### Remarks
* The WINDOWTITLE and STATUS filters are not supported when a remote system is specified.
* The wildcard character (**\\**<em>) is accepted for the **/im</em>* option only when a filter is applied.
* Termination of remote processes is always carried out forcefully, regardless of whether the **/f** option is specified.
* Supplying a computer name to the hostname filter causes a shutdown and all processes are stopped.
* You can use **tasklist** to determine the process ID (PID) for the process to be terminated.

### Examples

To end the processes with process IDs 1230, 1241, and 1253, type:

```
taskkill /pid 1230 /pid 1241 /pid 1253
```

To forcefully end the process Notepad.exe if it was started by the system, type:

```
taskkill /f /fi USERNAME eq NT AUTHORITY\SYSTEM /im notepad.exe
```

To end all processes on the remote computer Srvmain with an image name beginning with note, while using the credentials for the user account Hiropln, type:

```
taskkill /s srvmain /u maindom\hiropln /p p@ssW23 /fi IMAGENAME eq note* /im *
```

To end the process with the process ID 2134 and any child processes that it started, but only if those processes were started by the Administrator account, type:

```
taskkill /pid 2134 /t /fi username eq administrator
```

To end all processes that have a process ID greater than or equal to 1000, regardless of their image names, type:

```
taskkill /f /fi PID ge 1000 /im *
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


