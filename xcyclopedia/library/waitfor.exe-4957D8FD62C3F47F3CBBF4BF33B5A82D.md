
# waitfor.exe 

* File Path: `C:\WINDOWS\SysWOW64\waitfor.exe`
* Description: waitfor - wait/send a signal over a network
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `4957D8FD62C3F47F3CBBF4BF33B5A82D`
SHA1 | `34D19F22C89ACFAAEAFD3A828E119FF18B715FA7`
SHA256 | `DAAA464B6DB46DBD0B81329F563993736A8F92C590716AA2C65DC5593D8F9034`
SHA384 | `7B2B0C5CFE3451A84238C68CEBF5E1F0BECD9C0A3618E867A8926F9F222446B1AC9EC786648FB552206545A7C8BCFA70`
SHA415 | `41FFDFED2B435C871F6E71AC8F01F40B0B064DAD9E8EF30B6717A46255A26A72BDFAB08AA93F1ED456C75C21DD66F49CB90AEB03EEA1AEAA531F3B79D3BB15AE`
SSDEEP | `768:fIHaIW5dWEwe+LofdLadiVfp4wQhHuawisNxLApk+e:fIHaIWFeLiFadidzQhOaw1xQk`

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

* Original Filename: waitfor.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


