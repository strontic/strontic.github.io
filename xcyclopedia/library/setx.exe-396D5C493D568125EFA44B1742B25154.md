
# setx.exe 

* File Path: `C:\Windows\SysWOW64\setx.exe`
* Description: Setx - Sets environment variables
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `396D5C493D568125EFA44B1742B25154`
SHA1 | `415D0A2C114E2262A4B02605EDDA8F439811367B`
SHA256 | `F6C20EDD98B353E84E85A0C4D55B5F0F2A9DFA3C4F8C41624A92C1D908573195`
SHA384 | `FCA56141B947252EA4A9D4BBF96118EE279D342B85655E14A33ADD85714AF327804B027F57306092061FA8B45A5000EF`
SHA512 | `14511451764046AAB92E02BAACF285D268655CBAA957D07EBD390757F53E2B967658C102CB83DC6996D2AEEE4047B435BEFEDB55271CF81C15A36FBE0DBD2D80`
SSDEEP | `768:wmvkCl57szTADhftyEwdF4bzbIeIh3qwg9FEGbROBDP5DPLkOquoaHNjs:ZvkCltcS1yh+t03sbEoOqPaHNY`

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
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setx.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# setx

Creates or modifies environment variables in the user or system environment, without requiring programming or scripting. The **Setx** command also retrieves the values of registry keys and writes them to text files.



## Syntax

```
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] <Variable> <Value> [/m]
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] [<Variable>] /k <Path> [/m]
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] /f <FileName> {[<Variable>] {/a <X>,<Y> | /r <X>,<Y> <String>} [/m] | /x} [/d <Delimiters>]
```

### Parameters

|         Parameter          |                                                                                                                                              Description                                                                                                                                              |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|       /s \<Computer>       |                                                                                  Specifies the name or IP address of a remote computer. Do not use backslashes. The default value is the name of the local computer.                                                                                  |
| /u [\<Domain>\]<User name> |                                                                                           Runs the script with the credentials of the specified user account. The default value is the system permissions.                                                                                            |
|      /p [\<Password>]      |                                                                                                         Specifies the password of the user account that is specified in the **/u** parameter.                                                                                                         |
|        \<Variable>         |                                                                                                                 Specifies the name of the environment variable that you want to set.                                                                                                                  |
|          \<Value>          |                                                                                                                Specifies the value to which you want to set the environment variable.                                                                                                                 |
|         /k \<Path>         | Specifies that the variable is set based on information from a registry key. The p*ath* uses the following syntax:</br>`\\<HIVE>\<KEY>\...\<Value>`</br>For example, you might specify the following path:</br>`HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName` |
|      /f \<File name>       |                                                                                                                               Specifies the file that you want to use.                                                                                                                                |
|        /a \<X>,<Y>         |                                                                                                                    Specifies absolute coordinates and offset as search parameters.                                                                                                                    |
|   /r \<X>,<Y> <String>   |                                                                                                            Specifies relative coordinates and offset from **String** as search parameters.                                                                                                            |
|             /m             |                                                                                                Specifies to set the variable in the system environment. The default setting is the local environment.                                                                                                 |
|             /x             |                                                                                                       Displays file coordinates, ignoring the **/a**, **/r**, and **/d** command-line options.                                                                                                        |
|      /d \<Delimiters>      |                    Specifies delimiters such as **,** or **\\** to be used in addition to the four built-in delimiters â€” SPACE, TAB, ENTER, and LINEFEED. Valid delimiters include any ASCII character. The maximum number of delimiters is 15, including built-in delimiters.                    |
|             /?             |                                                                                                                                 Displays help at the command prompt.                                                                                                                                  |

## Remarks

-   The **Setx** command is similar to the UNIX utility SETENV.
-   **Setx** provides the only command-line or programmatic way to directly and permanently set system environment values. System environment variables are manually configurable through **Control Panel** or through a registry editor. The **set** command, which is internal to the command interpreter (Cmd.exe), sets user environment variables for the current console window only.
-   You can use the **setx** command to set values for user and system environment variables from one of three sources (modes): Command Line Mode, Registry Mode, or File Mode.
-   **Setx** writes variables to the master environment in the registry. Variables set with **setx** variables are available in future command windows only, not in the current command window.
-   **HKEY_CURRENT_USER** and **HKEY_LOCAL_MACHINE** are the only supported hives. REG_DWORD, REG_EXPAND_SZ, REG_SZ, and REG_MULTI_SZ are the valid **RegKey** data types.
-   When you gain access to **REG_MULTI_SZ** values in the registry, only the first item is extracted and used.
-   You cannot use the **setx** command to remove values that have been added to the local or system environments. You can use **set** with a variable name and no value to remove a corresponding value from the local environment.
-   REG_DWORD registry values are extracted and used in hexadecimal mode.
-   File mode supports the parsing of carriage return and line feed (CRLF) text files only.

## Examples

To set the MACHINE environment variable in the local environment to the value Brand1, type:
```
setx MACHINE Brand1
```
To set the MACHINE environment variable in the system environment to the value Brand1 Computer, type:
```
setx MACHINE Brand1 Computer /m
```
To set the MYPATH environment variable in the local environment to use the search path defined in the PATH environment variable, type:
```
setx MYPATH %PATH%
```
To set the MYPATH environment variable in the local environment to use the search path defined in the PATH environment variable after replacing **~** with **%**, type:
```
setx MYPATH ~PATH~ 
```
To set the MACHINE environment variable in the local environment to Brand1 on a remote computer named Computer1, type:
```
setx /s computer1 /u maindom\hiropln /p p@ssW23 MACHINE Brand1
```
To set the MYPATH environment variable in the local environment to use the search path defined in the PATH environment variable on a remote computer named Computer1, type:
```
setx /s computer1 /u maindom\hiropln /p p@ssW23 MYPATH %PATH%
```
To set the TZONE environment variable in the local environment to the value found in the **HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName** registry key, type:
```
setx TZONE /k HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName 
```
To set the TZONE environment variable in the local environment of a remote computer named Computer1 to the value found in the **HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName** registry key, type:
```
setx /s computer1 /u maindom\hiropln /p p@ssW23 TZONE /k HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName 
```
To set the BUILD environment variable in the system environment to the value found in the **HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber** registry key, type:
```
setx BUILD /k HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber /m
```
To set the BUILD environment variable in the system environment of a remote computer named Computer1 to the value found in the **HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber** registry key, type:
```
setx /s computer1 /u maindom\hiropln /p p@ssW23  BUILD /k HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber /m
```
To display the contents of a file named Ipconfig.out, along with the contents' corresponding coordinates, type:
```
setx /f ipconfig.out /x
```
To set the IPADDR environment variable in the local environment to the value found at the coordinate 5,11 in the file Ipconfig.out, type:
```
setx IPADDR /f ipconfig.out /a 5,11
```
To set the OCTET1 environment variable in the local environment to the value found at the coordinate 5,3 in the file Ipconfig.out with delimiters **#$\*.**, type:
```
setx OCTET1 /f ipconfig.out /a 5,3 /d #$*. 
```
To set the IPGATEWAY environment variable in the local environment to the value found at the coordinate 0,7 with respect to the coordinate of Gateway in the file Ipconfig.out, type:
```
setx IPGATEWAY /f ipconfig.out /r 0,7 Gateway 
```
To display the contents of a file named Ipconfig.out â€” along with the contents' corresponding coordinates â€” on a computer named Computer1, type:
```
setx /s computer1 /u maindom\hiropln /p p@ssW23 /f ipconfig.out /x 
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


