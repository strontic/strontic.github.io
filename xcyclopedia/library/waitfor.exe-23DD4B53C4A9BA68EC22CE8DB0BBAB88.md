
# waitfor.exe 

* File Path: `C:\Windows\system32\waitfor.exe`
* Description: waitfor - wait/send a signal over a network
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `23DD4B53C4A9BA68EC22CE8DB0BBAB88`
SHA1 | `D1D8CE3F66770A1D2A736CE78D7103DB4D31D006`
SHA256 | `963A39D3A7194A7BBEEDCB36DC32C5E809D2B78872161B94E157D0A57C67DEB0`
SHA384 | `2828786B525094CBE7535220968392F163B8984044A041F307AB54CA48FEFD17DD27A1F7EB953443F4E6197A51C2A277`
SHA415 | `1F1AB4D965C67487A100F5EDBF75147BCF40C0E84162703A84E41F566814749A7A987D535A11D12876A0984B51A5E34F56C52D7737C4F6714C94D12360DEE29A`
SSDEEP | `768:UC5ElL/4bn7XFdGY1M/4HrO3V5xH9YBSdNUQTHKoOCIx02onG:UnV/4bN+/rpyQdNFHKTxXonG`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: waitfor.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


