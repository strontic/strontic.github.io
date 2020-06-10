
# tasklist.exe 
* File Path: `C:\WINDOWS\SysWOW64\tasklist.exe`
* Description: Lists the current running tasks
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `F8D74B8779B1C59977779109410C8F4F`
SHA1 | `9F9DC9C75A230923526432FA848C7C4F12780928`
SHA256 | `E25A51D329B8355D6A297E10E26F572496B6030C827BCF12B736FD3A5096B20C`
SHA384 | `9844246E4729AF921AEE3CA900DE20C4722BF531D56B020F5F74B9216B246750EE4A81A964104408D9DC3E9A5457CD76`
SHA415 | `D7E3216C3CAA15DA6E10D5C98603D2F02EDD092D63E036D931AEA1E877E808B3969ECCACE674840B536462435D777468B2FEE3D7E0B76C0E9F5DBF64C50B2D83`
SSDEEP | `1536:2AkP/O24q2blpd+o2kK/yJ/GPcHch9tQlTNoIvCd1VtY2WxD3xJFW1hS:t2qRp0Hr0/GPcHcbilNoaCTWxDxJU`

## Runtime Data
### Usage (stdout):
```Batchfile

TASKLIST [/S system [/U username [/P [password]]]]
         [/M [module] | /SVC | /V] [/FI filter] [/FO format] [/NH]

Description:
    This tool displays a list of currently running processes on
    either a local or remote machine.

Parameter List:
   /S     system           Specifies the remote system to connect to.

   /U     [domain\]user    Specifies the user context under which
                           the command should execute.

   /P     [password]       Specifies the password for the given
                           user context. Prompts for input if omitted.

   /M     [module]         Lists all tasks currently using the given
                           exe/dll name. If the module name is not
                           specified all loaded modules are displayed.

   /SVC                    Displays services hosted in each process.

   /APPS                   Displays Store Apps and their associated processes.

   /V                      Displays verbose task information.

   /FI    filter           Displays a set of tasks that match a
                           given criteria specified by the filter.

   /FO    format           Specifies the output format.
                           Valid values: "TABLE", "LIST", "CSV".

   /NH                     Specifies that the "Column Header" should
                           not be displayed in the output.
                           Valid only for "TABLE" and "CSV" formats.

   /?                      Displays this help message.

Filters:
    Filter Name     Valid Operators           Valid Value(s)
    -----------     ---------------           --------------------------
    STATUS          eq, ne                    RUNNING | SUSPENDED
                                              NOT RESPONDING | UNKNOWN
    IMAGENAME       eq, ne                    Image name
    PID             eq, ne, gt, lt, ge, le    PID value
    SESSION         eq, ne, gt, lt, ge, le    Session number
    SESSIONNAME     eq, ne                    Session name
    CPUTIME         eq, ne, gt, lt, ge, le    CPU time in the format
                                              of hh:mm:ss.
                                              hh - hours,
                                              mm - minutes, ss - seconds
    MEMUSAGE        eq, ne, gt, lt, ge, le    Memory usage in KB
    USERNAME        eq, ne                    User name in [domain\]user
                                              format
    SERVICES        eq, ne                    Service name
    WINDOWTITLE     eq, ne                    Window title
    MODULES         eq, ne                    DLL name

NOTE: "WINDOWTITLE" and "STATUS" filters are not supported when querying
      a remote machine.

Examples:
    TASKLIST
    TASKLIST /M
    TASKLIST /V /FO CSV
    TASKLIST /SVC /FO LIST
    TASKLIST /APPS /FI "STATUS eq RUNNING"
    TASKLIST /M wbem*
    TASKLIST /S system /FO LIST
    TASKLIST /S system /U domain\username /FO CSV /NH
    TASKLIST /S system /U username /P password /FO TABLE /NH
    TASKLIST /FI "USERNAME ne NT AUTHORITY\SYSTEM" /FI "STATUS eq running"

```

### Usage (stderr):
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "TASKLIST /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tasklist.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


