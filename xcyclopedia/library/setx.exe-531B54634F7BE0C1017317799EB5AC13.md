
# setx.exe 

* File Path: `C:\WINDOWS\system32\setx.exe`
* Description: Setx - Sets environment variables
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `531B54634F7BE0C1017317799EB5AC13`
SHA1 | `84C42394C7A9D43E0269152199A212FEC8A18398`
SHA256 | `4A59AF81F7D99A53DAEE587BDAF77D97314E5592E2348B414282054E4913266A`
SHA384 | `ACBBFE5955239CA01C495F0BD69F686366C3C48E5C618EA3C8057AF87843C86B3DB74883AE1D1D9371A42E4F9D0C34DB`
SHA415 | `4AB883DB84DB89964F126F4593428D888ADE869CBEFDE370C490BA258084EFEF7A77AF0D57926B49B5E0D74D291408A22C5160512BC06C206932CF9013D84B95`
SSDEEP | `1536:YoDIvXk5MeicnNUl1Cyrm/ENjrqHjNa1t3r:afbTBCqjr6jNa1tb`

## Runtime Data

### Usage (stdout):
```Batchfile

SetX has three ways of working: 

Syntax 1:
    SETX [/S system [/U [domain\]user [/P [password]]]] var value [/M]

Syntax 2:
    SETX [/S system [/U [domain\]user [/P [password]]]] var /K regpath [/M]

Syntax 3:
    SETX [/S system [/U [domain\]user [/P [password]]]]
         /F file {var {/A x,y | /R x,y string}[/M] | /X} [/D delimiters]

Description:
    Creates or modifies environment variables in the user or system
    environment. Can set variables based on arguments, regkeys or
    file input.

Parameter List:
    /S     system          Specifies the remote system to connect to.

    /U     [domain\]user   Specifies the user context under which
                           the command should execute.

    /P     [password]      Specifies the password for the given
                           user context. Prompts for input if omitted.

    var                    Specifies the environment variable to set.

    value                  Specifies a value to be assigned to the 
                           environment variable.

    /K     regpath         Specifies that the variable is set based
                           on information from a registry key.
                           Path should be specified in the format of
                           hive\key\...\value. For example,
                           HKEY_LOCAL_MACHINE\System\CurrentControlSet\
                           Control\TimeZoneInformation\StandardName.

    /F     file            Specifies the filename of the text file
                           to use.

    /A     x,y             Specifies absolute file coordinates
                           (line X, item Y) as parameters to search 
                           within the file.

    /R     x,y string      Specifies relative file coordinates with
                           respect to "string" as the search parameters.

    /M                     Specifies that the variable should be set in
                           the system wide (HKEY_LOCAL_MACHINE)
                           environment. The default is to set the
                           variable under the HKEY_CURRENT_USER 
                           environment.

    /X                     Displays file contents with x,y coordinates.

    /D     delimiters      Specifies additional delimiters such as ","
                           or "\". The built-in delimiters are space,
                           tab, carriage return, and linefeed. Any 
                           ASCII character can be used as an additional
                           delimiter. The maximum number of delimiters,
                           including the built-in delimiters, is 15.

    /?                     Displays this help message.

NOTE: 1) SETX writes variables to the master environment in the registry.

      2) On a local system, variables created or modified by this tool
         will be available in future command windows but not in the
         current CMD.exe command window.

      3) On a remote system, variables created or modified by this tool
         will be available at the next logon session.

      4) The valid Registry Key data types are REG_DWORD, REG_EXPAND_SZ,
         REG_SZ, REG_MULTI_SZ.

      5) Supported hives:  HKEY_LOCAL_MACHINE (HKLM),
         HKEY_CURRENT_USER (HKCU).

      6) Delimiters are case sensitive.

      7) REG_DWORD values are extracted from the registry in decimal 
         format.

Examples:
    SETX MACHINE COMPAQ 
    SETX MACHINE "COMPAQ COMPUTER" /M
    SETX MYPATH "%PATH%"
    SETX MYPATH ~PATH~
    SETX /S system /U user /P password  MACHINE COMPAQ 
    SETX /S system /U user /P password MYPATH ^%PATH^% 
    SETX TZONE /K HKEY_LOCAL_MACHINE\System\CurrentControlSet\
         Control\TimeZoneInformation\StandardName
    SETX BUILD /K "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows
         NT\CurrentVersion\CurrentBuildNumber" /M
    SETX /S system /U user /P password TZONE /K HKEY_LOCAL_MACHINE\
         System\CurrentControlSet\Control\TimeZoneInformation\
         StandardName
    SETX /S system /U user /P password  BUILD /K 
         "HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\
         CurrentVersion\CurrentBuildNumber" /M
    SETX /F ipconfig.out /X 
    SETX IPADDR /F ipconfig.out /A 5,11 
    SETX OCTET1 /F ipconfig.out /A 5,3 /D "#$*." 
    SETX IPGATEWAY /F ipconfig.out /R 0,7 Gateway
    SETX /S system /U user /P password  /F c:\ipconfig.out /X

```

### Usage (stderr):
```Batchfile
ERROR: Invalid syntax.
Type "SETX /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setx.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


