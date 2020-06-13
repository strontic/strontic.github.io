
# taskkill.exe 

* File Path: `C:\WINDOWS\SysWOW64\taskkill.exe`
* Description: Terminates Processes
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `07D18817187E87CFC6AB2A4670061AE0`
SHA1 | `BFF1DF5D96A56DB65B6BBBFE7C2527A45E7B882E`
SHA256 | `89D9BDF537EC43228448187779299AC347449361E067B0AD453BB54AD7EDB37E`
SHA384 | `8F47DB9BDC42D6B660DFE4787974A7DCA38C14B4B590FF9E7594818443E4E93179C493AD1FEB4172DBB74E927BE9B2D3`
SHA512 | `48394012123B5E7E4A1FCBB379452BA19455D6BA45F09FAB55D092F640B75A74E26DA3D4682B6C3C1C464E34B6A55A587DD7C1BB981EFA40CAA83E3E69269FD2`
SSDEEP | `1536:hJYuUaWAT4+lHVOmp+04tjrGLusCaGDmc5hv2ivP0i03gmXYqc6xVMFG17p9B:hzTHY2SjdtaGDmc5hv2i30iKgX6xiFG5`

## Runtime Data

### Usage (stdout):
```Batchfile

TASKKILL [/S system [/U username [/P [password]]]]
         { [/FI filter] [/PID processid | /IM imagename] } [/T] [/F]

Description:
    This tool is used to terminate tasks by process id (PID) or image name.

Parameter List:
    /S    system           Specifies the remote system to connect to.

    /U    [domain\]user    Specifies the user context under which the
                           command should execute.

    /P    [password]       Specifies the password for the given user
                           context. Prompts for input if omitted.

    /FI   filter           Applies a filter to select a set of tasks.
                           Allows "*" to be used. ex. imagename eq acme*

    /PID  processid        Specifies the PID of the process to be terminated.
                           Use TaskList to get the PID.

    /IM   imagename        Specifies the image name of the process
                           to be terminated. Wildcard '*' can be used
                           to specify all tasks or image names.

    /T                     Terminates the specified process and any
                           child processes which were started by it.

    /F                     Specifies to forcefully terminate the process(es).

    /?                     Displays this help message.

Filters:
    Filter Name   Valid Operators           Valid Value(s)
    -----------   ---------------           -------------------------
    STATUS        eq, ne                    RUNNING |
                                            NOT RESPONDING | UNKNOWN
    IMAGENAME     eq, ne                    Image name
    PID           eq, ne, gt, lt, ge, le    PID value
    SESSION       eq, ne, gt, lt, ge, le    Session number.
    CPUTIME       eq, ne, gt, lt, ge, le    CPU time in the format
                                            of hh:mm:ss.
                                            hh - hours,
                                            mm - minutes, ss - seconds
    MEMUSAGE      eq, ne, gt, lt, ge, le    Memory usage in KB
    USERNAME      eq, ne                    User name in [domain\]user
                                            format
    MODULES       eq, ne                    DLL name
    SERVICES      eq, ne                    Service name
    WINDOWTITLE   eq, ne                    Window title

    NOTE
    ----
    1) Wildcard '*' for /IM switch is accepted only when a filter is applied.
    2) Termination of remote processes will always be done forcefully (/F).
    3) "WINDOWTITLE" and "STATUS" filters are not considered when a remote
       machine is specified.

Examples:
    TASKKILL /IM notepad.exe
    TASKKILL /PID 1230 /PID 1241 /PID 1253 /T
    TASKKILL /F /IM cmd.exe /T 
    TASKKILL /F /FI "PID ge 1000" /FI "WINDOWTITLE ne untitle*"
    TASKKILL /F /FI "USERNAME eq NT AUTHORITY\SYSTEM" /IM notepad.exe
    TASKKILL /S system /U domain\username /FI "USERNAME ne NT*" /IM *
    TASKKILL /S system /U username /P password /FI "IMAGENAME eq note*"

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "TASKKILL /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: taskkill.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---
# taskkill

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Ends one or more tasks or processes. Processes can be ended by process ID or image name. **taskkill** replaces the **kill** tool.

For examples of how to use this command, see [Examples](#examples).

## Syntax

```
taskkill [/s <computer> [/u [<Domain>\]<UserName> [/p [<Password>]]]] {[/fi <Filter>] [...] [/pid <ProcessID> | /im <ImageName>]} [/f] [/t]
```

### Parameters

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

#### Filter names, operators, and values

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

## Remarks
* The WINDOWTITLE and STATUS filters are not supported when a remote system is specified.
* The wildcard character (**\\**<em>) is accepted for the **/im</em>* option only when a filter is applied.
* Termination of remote processes is always carried out forcefully, regardless of whether the **/f** option is specified.
* Supplying a computer name to the hostname filter causes a shutdown and all processes are stopped.
* You can use **tasklist** to determine the process ID (PID) for the process to be terminated.

## Examples

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

## Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


