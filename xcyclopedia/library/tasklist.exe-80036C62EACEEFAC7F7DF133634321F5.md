
# tasklist.exe 
* File Path: `C:\WINDOWS\system32\tasklist.exe`
* Description: Lists the current running tasks
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `80036C62EACEEFAC7F7DF133634321F5`
SHA1 | `7736E178321ABBD3C53103C7ABF0C93D0E189554`
SHA256 | `9F60240830FAF4DE590360561A6E249F5D0C41FF8AFBB9498BBE5C1A80ABD02C`
SHA384 | `37FCB36727B975D98D2060F5AF7C5A8664FED1E8FF63024F45DDC488B658E241967BB91140CE2702C9041454236DEA50`
SHA415 | `294D54A96AB528C0BE6ED6F526E50157EBFB986CF7D71C208DB91A1A9E8C9ECBF3EF5C81187487BD185138621E8AD98814E8F286623519B85BB2A7E5105184C1`
SSDEEP | `3072:KuW1S+3PxZ2rrCRjbgnvQHMRgPgBxaZt:K91SQf26RjboIHMR+geZ`

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


