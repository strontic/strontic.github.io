
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
SHA512 | `294D54A96AB528C0BE6ED6F526E50157EBFB986CF7D71C208DB91A1A9E8C9ECBF3EF5C81187487BD185138621E8AD98814E8F286623519B85BB2A7E5105184C1`
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
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
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


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# tasklist

Displays a list of currently running processes on the local computer or on a remote computer. **Tasklist** replaces the **tlist** tool.



## Syntax

```
tasklist [/s <Computer> [/u [<Domain>\]<UserName> [/p <Password>]]] [{/m <Module> | /svc | /v}] [/fo {table | list | csv}] [/nh] [/fi <Filter> [/fi <Filter> [ ... ]]]
```

### Parameters

|          Parameter           |                                                                                                                                            Description                                                                                                                                             |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|        /s \<Computer>        |                                                                                         Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer.                                                                                         |
| /u [\<Domain>\\\]\<UserName> | Runs the command with the account permissions of the user who is specified by *UserName* or *Domain*\*UserName<em>. \*\*/u</em>\* can be specified only if **/s** is specified. The default is the permissions of the user who is currently logged on to the computer that is issuing the command. |
|        /p \<Password>        |                                                                                                       Specifies the password of the user account that is specified in the **/u** parameter.                                                                                                        |
|         /m \<Module>         |                                                               Lists all tasks with DLL modules loaded that match the given pattern name. If the module name is not specified, this option displays all modules loaded by each task.                                                                |
|             /svc             |                                                                                    Lists all the service information for each process without truncation. Valid when the **/fo** parameter is set to **table**.                                                                                    |
|              /v              |                                                                                 Displays verbose task information in the output. For complete verbose output without truncation, use **/v** and **/svc** together.                                                                                 |
|  /fo {table \| list \| csv}  |                                                                             Specifies the format to use for the output. Valid values are **table**, **list**, and **csv**. The default format for output is **table**.                                                                             |
|             /nh              |                                                                                             Suppresses column headers in the output. Valid when the **/fo** parameter is set to **table** or **csv**.                                                                                              |
|        /fi \<Filter>         |                                                                          Specifies the types of processes to include in or exclude from the query. See the following table for valid filter names, operators, and values.                                                                          |
|              /?              |                                                                                                                                Displays help at the command prompt.                                                                                                                                |

### Filter names, operators, and values

| Filter Name |    Valid Operators     |                                                                 Valid Values                                                                 |
|-------------|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
|   STATUS    |         eq, ne         |                                                                   RUNNING                                                                    |
|  IMAGENAME  |         eq, ne         |                                                                  Image name                                                                  |
|     PID     | eq, ne, gt, lt, ge, le |                                                                  PID value                                                                   |
|   SESSION   | eq, ne, gt, lt, ge, le |                                                                Session number                                                                |
| SESSIONNAME |         eq, ne         |                                                                 Session name                                                                 |
|   CPUTIME   | eq, ne, gt, lt, ge, le | CPU time in the format <em>HH</em>**:**<em>MM</em>**:**<em>SS</em>, where *MM* and *SS* are between 0 and 59 and *HH* is any unsigned number |
|  MEMUSAGE   | eq, ne, gt, lt, ge, le |                                                              Memory usage in KB                                                              |
|  USERNAME   |         eq, ne         |                                                             Any valid user name                                                              |
|  SERVICES   |         eq, ne         |                                                                 Service name                                                                 |
| WINDOWTITLE |         eq, ne         |                                                                 Window title                                                                 |
|   MODULES   |         eq, ne         |                                                                   DLL name                                                                   |

## Remarks

The WINDOWTITLE and STATUS filters are not supported when a remote system is specified.

## <a name="BKMK_examples"></a>Examples

To list all tasks with a process ID greater than 1000, and display them in CSV format, type:
```
tasklist /v /fi "PID gt 1000" /fo csv
```
To list the system processes that are currently running, type:
```
tasklist /fi "USERNAME ne NT AUTHORITY\SYSTEM" /fi "STATUS eq running"
```
To list detailed information for all processes that are currently running, type:
```
tasklist /v /fi "STATUS eq running"
```
To list all the service information for processes on the remote computer "Srvmain" that have a DLL name beginning with "ntdll," type:
```
tasklist /s srvmain /svc /fi "MODULES eq ntdll*"
```
To list the processes on the remote computer "Srvmain," using the credentials of your currently logged-on user account, type:
```
tasklist /s srvmain 
```
To list the processes on the remote computer "Srvmain," using the credentials of the user account Hiropln, type:
```
tasklist /s srvmain /u maindom\hiropln /p p@ssW23
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


