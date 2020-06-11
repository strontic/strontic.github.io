
# eventcreate.exe 

* File Path: `C:\Windows\SysWOW64\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `8792D807006C5FBC5B9B9B3E8393823E`
SHA1 | `3C2DE87D328D68BEEA122C1CD24444785B075753`
SHA256 | `066F8E55D0C082287CC7460499301B8A88D6210FBFF965646AA1CEB44DE4199A`
SHA384 | `9A52AA4004204BD2AA9D24B9AC6A601AAAAD4FB3E106B6E3F8638C0D4299A9A9E4E5D2556B2E082A98F749A9FE9AAD0B`
SHA415 | `EC545F9EFB8DFE8AFFF3441BADF3AE3ED2CA65F390D7B79408D6A3F4BEDE81544898CA587EAF224920EAF2B760CEA38306E05CED0F58D980A25C7D67590D6CB6`
SSDEEP | `768:tYg9NYCkzlv6W+WmIpylh6RyTqsx7LU7S8dapAA:tYg9vkZJSkw+67L6S8apAA`

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


