---
title: eventcreate.exe | Event Create - Creates a custom event in an event log
excerpt: What is eventcreate.exe?
---

# eventcreate.exe 

* File Path: `C:\WINDOWS\SysWOW64\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log

## Hashes

Type | Hash
-- | --
MD5 | `D339A09EE543F1D70DADA26AA75967D7`
SHA1 | `F0D744DC5A604F766EF9D05B9157EDA808F4ACA6`
SHA256 | `B91C6B90C4F28CBB848A5D0C9D65AD0D5274956AB8A15D259EDC71CF259672AD`
SHA384 | `1774B55663B5C72EAE36121638EDA5CC7275F813CD8E2DB994E03556885A873A0FD04B8D792AB83B5A7880C747467F6A`
SHA512 | `7B4DDC1D099F98CF266979ADA865EB2FE0B68D72E95552D32ED54A9D644439D42653280C565B44F86B304B0945DA090298843678749EC0C0519A3AAD0F08FCB0`
SSDEEP | `768:aYgaOTDz2rjgAB7tW0bi6ZVrXGDlX3dWLolKqoaC2oQiB:aYgaOTDAVSmR0lAolKLaC2oQ`
IMP | `9AA2B0AB7DC35FBB1ED0455F25254D9F`
PESHA1 | `C17FFA959AD4096C6FBE5526CBD1F92F7854E6E8`
PE256 | `F2636CF55A5C71F6F7DED3218A0B7272479E3B8AF3E2D3A756C956052B4A39FE`

## Runtime Data

### Usage (stdout):
```cmhg

EVENTCREATE [/S system [/U username [/P [password]]]] /ID eventid
            [/L logname] [/SO srcname] /T type /D description

Description:
    This command line tool enables an administrator to create
    a custom event ID and message in a specified event log.

Parameter List:
    /S    system           Specifies the remote system to connect to.

    /U    [domain\]user    Specifies the user context under which
                           the command should execute.

    /P    [password]       Specifies the password for the given
                           user context. Prompts for input if omitted.

    /L    logname          Specifies the event log to create
                           an event in.

    /T    type             Specifies the type of event to create.
                           Valid types: SUCCESS, ERROR, WARNING, INFORMATION.

    /SO   source           Specifies the source to use for the
                           event (if not specified, source will default
                           to 'eventcreate'). A valid source can be any
                           string and should represent the application
                           or component that is generating the event.

    /ID   id               Specifies the event ID for the event. A
                           valid custom message ID is in the range
                           of 1 - 1000.

    /D    description      Specifies the description text for the new event.

    /?                     Displays this help message.


Examples:
    EVENTCREATE /T ERROR /ID 1000
        /L APPLICATION /D "My custom error event for the application log"

    EVENTCREATE /T ERROR /ID 999 /L APPLICATION
        /SO WinWord /D "Winword event 999 happened due to low diskspace"

    EVENTCREATE /S system /T ERROR /ID 100
        /L APPLICATION /D "Custom job failed to install"

    EVENTCREATE /S system /U user /P password /ID 1 /T ERROR
        /L APPLICATION /D "User access failed due to invalid user credentials"

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "EVENTCREATE /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\eventcreate.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: evcreate.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/b91c6b90c4f28cbb848a5d0c9d65ad0d5274956ab8a15d259edc71cf259672ad/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## eventcreate

Enables an administrator to create a custom event in a specified event log.

> [!IMPORTANT]
> Custom events can't be written to the security log.

### Syntax

```
eventcreate [/s <computer> [/u <domain\user> [/p <password>]] {[/l {APPLICATION|SYSTEM}]|[/so <srcname>]} /t {ERROR|WARNING|INFORMATION|SUCCESSAUDIT|FAILUREAUDIT} /id <eventID> /d <description>
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain\user>` | Runs the command with the account permissions of the user specified by `<user>` or `<domain\user>`. The default is the permissions of the current logged on user on the computer issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /l `{APPLICATION | SYSTEM}` | Specifies the name of the event log where the event will be created. The valid log names are **APPLICATION** or **SYSTEM**. |
| /so `<srcname>` | Specifies the source to use for the event. A valid source can be any string and should represent the application or component that is generating the event. |
| /t `{ERROR | WARNING | INFORMATION | SUCCESSAUDIT | FAILUREAUDIT}` | Specifies the type of event to create. The valid types are **ERROR**, **WARNING**, **INFORMATION**, **SUCCESSAUDIT**, and **FAILUREAUDIT**. |
| /id `<eventID>` | Specifies the event ID for the event. A valid ID is any number from 1 to 1000. |
| /d `<description>` | Specifies the description to use for the newly created event. |
| /? | Displays help at the command prompt. |

#### Examples

The following examples show how you can use the **eventcreate** command:

```
eventcreate /t ERROR /id 100 /l application /d "Create event in application log"
eventcreate /t INFORMATION /id 1000 /d "Create event in WinMgmt source"
eventcreate /t ERROR /id 201 /so winword /l application /d "New src Winword in application log"
eventcreate /s server /t ERROR /id 100 /l application /d "Remote machine without user credentials"
eventcreate /s server /u user /p password /id 100 /t ERROR /l application /d "Remote machine with user credentials"
eventcreate /s server1 /s server2 /u user /p password /id 100 /t ERROR /d "Creating events on Multiple remote machines"
eventcreate /s server /u user /id 100 /t WARNING /d "Remote machine with partial user credentials"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


