
# taskkill.exe 

* File Path: `C:\WINDOWS\system32\taskkill.exe`
* Description: Terminates Processes
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `3BBEE3AC757CA54F33710DF8FB9D47A7`
SHA1 | `DF3A0F49F9310B401FA5C2FE35C086DFA3018DBA`
SHA256 | `D9E29313D2127FF1983A050D84626765D01682EDB2C1C5D5F209DDA20C3EAB87`
SHA384 | `1846AB297C13298CBC4E6BF62A79BBC9D160A23AC313BFC801430CEE3A535EA62D6E20A04E2F18A1A26388FE92098671`
SHA415 | `8CD25388832D081A57831C767F5869122A7571E962641AB97DFE5F3E9090490BF68498AC0DAF8DDE06E0A5259C6D0151027BD18678E74B99E07778B319D9BA82`
SSDEEP | `1536:e39Rc5hnL7uU6PQUHJKpf7JaClxf7iL/DM5C0U4o+weE7XxXDs:e39ROhnL7upCNlxjiL7M5C0GeE7XxA`

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
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
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

MIT License. Copyright (c) 2020 Strontic.


