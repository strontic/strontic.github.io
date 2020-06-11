
# eventcreate.exe 

* File Path: `C:\Windows\system32\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `1EDA7FDF4B09E1582A7DAC5FEFFE0894`
SHA1 | `9F442376B6ED94DA2DCB47F1B851153488D0B909`
SHA256 | `AD90D99135B3E443F3DEEA5B40199CE5B83CCB0964FD9AC3F11B9224766ED7BA`
SHA384 | `A18DAA92750CE6469B345A7E40C70D450240335D3E612F1F6D7541E88CB24D04EDF902057AE685E34BFE1BE54F50981A`
SHA415 | `31F345ADEF864E8DB02439CE8191DE06EA924FAD6F3CA040593A9F6275D40D8E758B320C3DC2542A5E5B6C5F911F4A0E0E8AD5B7BE65604872D54BC755BB86D4`
SSDEEP | `768:9I2semKXr+5bjQNAWDnm8pKNtO3VcItPTxlCXHYQNt0y3SJXaT1oA:W2bnrFnpFTP6HYQN6oS5aBoA`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "EVENTCREATE /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: evcreate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


