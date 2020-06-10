
# eventcreate.exe 
* File Path: `C:\WINDOWS\system32\eventcreate.exe`
* Description: Event Create - Creates a custom event in an event log
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `BC294542C30FA80E43A939D5271A7B56`
SHA1 | `DF426EBCCC3CCD516BCC769031A2471C8A8581EC`
SHA256 | `CC68C3D269C62282A4FDAF1EA4FAA18AEBC4A03D7E27C7C898EB726B9B5F9CB4`
SHA384 | `66B3672642BE1AC67F68564CFE4EC82CEB3EFC806D54FA11D6FC7BD75BF255E899499BBC8EB0F46408C22878092C902B`
SHA415 | `B08AE7F9038C1A0696758578ADFA46092C9212E111A2C8727EFED784FA57F4A66A7E52D2C1F37CB4AFC5D3821569203BDE64DA9344AD9B357C1056C5FF1851D8`
SSDEEP | `768:sUYyXdVm3yGC48gBTtvw394azPXfiZYQhYukkcZslaOoa2/ylg6:s2iP7sPmYQwslava1g6`

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

* Original Filename: evcreate.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


