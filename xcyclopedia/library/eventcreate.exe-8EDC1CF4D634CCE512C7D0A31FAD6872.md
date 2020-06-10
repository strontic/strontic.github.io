
# eventcreate.exe 
* File Path: `C:\WINDOWS\SysWOW64\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `8EDC1CF4D634CCE512C7D0A31FAD6872`
SHA1 | `EA9BA59C3CDB8DBCFC4B2EF13304EA702CCEE245`
SHA256 | `AFCB15B1F200134DB8E7537E3D535A292C9C87418F13D84D02B9B98F40AC3BCE`
SHA384 | `7A7248E8DB487FF9CC0E5BA50B2CFAADDA6488DA4847AF28C4DF901EB9F03E238A7DA544416835214D8EC946BC043891`
SHA415 | `76C1F570904FF87B362FB680B3ECB4D583BEB47618C3863F2D742FFB054640A9F6F88A678ECF19FD16016993A788535A833344484779D8B5939C20767FF23108`
SSDEEP | `768:R6YgjPJ6d/bcLQxwHMHQd87DJiBH6hXED4pYFnxlJOoa+o6m:R6YgjPJ8geXwd87DJiJ6ku+xlJva+o6`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: evcreate.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


