
# waitfor.exe 

* File Path: `C:\WINDOWS\system32\waitfor.exe`
* Description: waitfor - wait/send a signal over a network
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `E6F52AF752157757EA5B0B1F1C997314`
SHA1 | `B1F46293696764C26BFB2F6BD172FA2FBDD95740`
SHA256 | `4C2F9EFA10013D1E95810973DC5A47795C0B62AF923165E4CC232399A89E5767`
SHA384 | `680A6BB4769E40C5AB3D70BC801877F466B4271207239D94FCC25828117B6FBD3237F7C5EDE5C1813174D8F48154320A`
SHA415 | `76CB0ECDC1A867A3785C8A9FFEF74154E3ECA3E86D65A70205CCAFB16ECD85342AC9F50E4DC4564FE3DE4514161DCC90987D6832C7B32522BDAF59F387987809`
SSDEEP | `768:Yf98nv2Ciy9wn0bgdr5g+L3Rcy95XX6GgHKePKx6nUM8:Uoevjn6lHKVx6N8`

## Runtime Data

### Usage (stdout):
```Batchfile

WaitFor has two ways of working: 

Syntax 1: to send a signal
    WAITFOR [/S system [/U user [/P [password]]]] /SI signal

Syntax 2: to wait for a signal
    WAITFOR [/T timeout] signal 

Description:
    This tool sends, or waits for, a signal on a system. When /S is not
    specified, the signal will be broadcasted to all the systems in a
    domain. If /S is specified, then the signal will be sent only
    to the specified system.

Parameter List:
    /S     system         Specifies remote system to send signal to.

    /U     [domain\]user  Specifies the user context under which
                          the command should execute.

    /P     [password]     Specifies the password for the given user context.

    /SI                   Sends the signal across the net to waiting machines

    /T     timeout        Number of seconds to wait for signal. Valid range
                          is 1 - 99999. Default is to wait forever for signal.

    signal                The name of the signal to wait for or to send.

    /?                    Displays this help message.

    NOTE: A system can wait for multiple unique signal names.
    The signal name cannot exceed 225 characters and cannot
    contain characters other than a-z, A-Z, 0-9 and ASCII 
    characters in the range 128-255.

Examples:
    WAITFOR /?
    WAITFOR SetupReady 
    WAITFOR CopyDone /T 100 
    WAITFOR /SI SetupReady 
    WAITFOR /S system  /U user /P password /SI CopyDone

```

### Usage (stderr):
```Batchfile
ERROR: The signal cannot contain characters other than a-z, A-Z, 0-9 
and ASCII characters in the range 128-255.

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: waitfor.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


