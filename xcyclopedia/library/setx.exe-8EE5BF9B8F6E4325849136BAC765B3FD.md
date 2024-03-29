﻿---
title: setx.exe | Setx - Sets environment variables
excerpt: What is setx.exe?
---

# setx.exe 

* File Path: `C:\WINDOWS\system32\setx.exe`
* Description: Setx - Sets environment variables

## Hashes

Type | Hash
-- | --
MD5 | `8EE5BF9B8F6E4325849136BAC765B3FD`
SHA1 | `C0C4AEC6C2A48A857C7900110448973238CAD96E`
SHA256 | `18C8E1F5907DEFCF4881F6A60DFA8A053AEFF78EE4CAD97F88D17B060503F10F`
SHA384 | `BBBC4D770BD77D9A7C6EFCA7A2E4B5C30799B65209E414D7AAEE0DCEC0D89CFD80D56182F7FB4C48C900331BF1ED4ED3`
SHA512 | `DD1FF5329383E19EC7999E566E9910A0974EF951B279F3CB55F160CFE922870A825A6E9EFDCF5E80594394224D21A3354D3B4B67FA812AA35DE7F73987FBDBA1`
SSDEEP | `1536:LTPRFlQv3VSRkfTNJGvA5l1uXR+TVtX/b5qm3Z/EdZVAHeVa1vxl:LDRzRk7NIvA5l1uB+TVh/tqoyZVEeVaN`
IMP | `D4D91C020E7B54B5EFCEEAE2FD69B971`
PESHA1 | `0C61ACD42187CEB1A253C21FA6A8FC3FB92B6950`
PE256 | `8B5390D744F2E4A146079035A0C2EA041EE90CD0CB8BAA020AE9C8FE8595D221`

## Runtime Data

### Usage (stdout):
```cmhg

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
```cmhg
ERROR: Invalid syntax.
Type "SETX /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\setx.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: setx.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/18c8e1f5907defcf4881f6a60dfa8a053aeff78ee4cad97f88d17b060503f10f/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## setx

Creates or modifies environment variables in the user or system environment, without requiring programming or scripting. The **Setx** command also retrieves the values of registry keys and writes them to text files.

> [!NOTE]
> This command provides the only command-line or programmatic way to directly and permanently set system environment values. System environment variables are manually configurable through **Control Panel** or through a registry editor. The **set** command, which is internal to the command interpreter (Cmd.exe), sets user environment variables for the current console window only.

### Syntax

```
setx [/s <computer> [/u [<domain>\]<user name> [/p [<password>]]]] <variable> <value> [/m]
setx [/s <computer> [/u [<domain>\]<user name> [/p [<password>]]]] <variable>] /k <path> [/m]
setx [/s <computer> [/u [<domain>\]<user name> [/p [<password>]]]] /f <filename> {[<variable>] {/a <X>,<Y> | /r <X>,<Y> <String>} [/m] | /x} [/d <delimiters>]
```

#### Parameters

| Parameter | Description |
|--|--|
| /s `<computer>` | Specifies the name or IP address of a remote computer. Do not use backslashes. The default value is the name of the local computer. |
| /u `[<domain>\]<user name>` | Runs the script with the credentials of the specified user account. The default value is the system permissions. |
| /p [`<password>`]| Specifies the password of the user account that is specified in the **/u** parameter. |
| `<variable>` | Specifies the name of the environment variable that you want to set. |
| `<value>` | Specifies the value to which you want to set the environment variable. |
| /k `<path>` | Specifies that the variable is set based on information from a registry key. The *path* uses the following syntax: `\\<HIVE>\<KEY>\...\<Value>`. For example, you might specify the following path: `HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName` |
| /f `<filename>` | Specifies the file that you want to use. |
| /a `<X>,<Y>` | Specifies absolute coordinates and offset as search parameters. |
| /r `<X>,<Y> <String>` | Specifies relative coordinates and offset from **String** as search parameters. |
| /m | Specifies to set the variable in the system environment. The default setting is the local environment. |
| /x | Displays file coordinates, ignoring the **/a**, **/r**, and **/d** command-line options. |
| /d `<delimiters>` | Specifies delimiters such as **,** or **\\** to be used in addition to the four built-in delimiters â€” SPACE, TAB, ENTER, and LINEFEED. Valid delimiters include any ASCII character. The maximum number of delimiters is 15, including built-in delimiters. |
| /? | Displays help at the command prompt. |

##### Remarks

- This command is similar to the UNIX utility SETENV.

- You can use this command to set values for user and system environment variables from one of three sources (modes): Command Line Mode, Registry Mode, or File Mode.

- This command writes variables to the master environment in the registry. Variables set with **setx** variables are available in future command windows only, not in the current command window.

- **HKEY_CURRENT_USER** and **HKEY_LOCAL_MACHINE** are the only supported hives. REG_DWORD, REG_EXPAND_SZ, REG_SZ, and REG_MULTI_SZ are the valid **RegKey** data types.

- If you gain access to **REG_MULTI_SZ** values in the registry, only the first item is extracted and used.

- You can't use this command to remove values added to the local or system environments. You can use this command with a variable name and no value to remove a corresponding value from the local environment.

- REG_DWORD registry values are extracted and used in hexadecimal mode.

- File mode supports the parsing of carriage return and line feed (CRLF) text files only.

- Running this command on an existing variable removes any variable references and uses expanded values.

  For instance, if the variable %PATH% has a reference to %JAVADIR%, and %PATH% is manipulated using **setx**, %JAVADIR% is expanded and its value is assigned directly to the target variable %PATH%. This means that future updates to %JAVADIR% **will not** be reflected in the %PATH% variable.

- Be aware there's a limit of 1024 characters when assigning contents to a variable using **setx**.

  This means that the content is cropped if you go over 1024 characters, and that the cropped text is what's applied to the target variable. If this cropped text is applied to an existing variable, it can result in loss of data previously held by the target variable.

### Examples

To set the *MACHINE* environment variable in the local environment to the value *Brand1*, type:

```
setx MACHINE Brand1
```

To set the *MACHINE* environment variable in the system environment to the value *Brand1 Computer*, type:

```
setx MACHINE Brand1 Computer /m
```

To set the *MYPATH* environment variable in the local environment to use the search path defined in the *PATH* environment variable, type:

```
setx MYPATH %PATH%
```

To set the *MYPATH* environment variable in the local environment to use the search path defined in the *PATH* environment variable after replacing **~** with **%**, type:

```
setx MYPATH ~PATH~
```

To set the *MACHINE* environment variable in the local environment to *Brand1* on a remote computer named *computer1*, type:

```
setx /s computer1 /u maindom\hiropln /p p@ssW23 MACHINE Brand1
```

To set the *MYPATH* environment variable in the local environment to use the search path defined in the *PATH* environment variable on a remote computer named *computer1*, type:

```
setx /s computer1 /u maindom\hiropln /p p@ssW23 MYPATH %PATH%
```

To set the *TZONE* environment variable in the local environment to the value found in the **HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName** registry key, type:

```
setx TZONE /k HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName
```

To set the *TZONE* environment variable in the local environment of a remote computer named *computer1* to the value found in the **HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName** registry key, type:

```
setx /s computer1 /u maindom\hiropln /p p@ssW23 TZONE /k HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\TimeZoneInformation\StandardName
```

To set the *BUILD* environment variable in the system environment to the value found in the **HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber** registry key, type:

```
setx BUILD /k HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber /m
```

To set the BUILD environment variable in the system environment of a remote computer named Computer1 to the value found in the **HKEY_LOCAL_MACHINE\Software\Microsoft\WindowsNT\CurrentVersion\CurrentBuildNumber** registry key, type:

```
setx /s computer1 /u maindom\hiropln /p p@ssW23  BUILD /k HKEY_LOCAL_MACHINE\Software\Microsoft\Windows NT\CurrentVersion\CurrentBuildNumber /m
```

To display the contents of a file named *Ipconfig.out*, along with the contents' corresponding coordinates, type:

```
setx /f ipconfig.out /x
```

To set the *IPADDR* environment variable in the local environment to the value found at the coordinate *5,11* in the *Ipconfig.out* file, type:

```
setx IPADDR /f ipconfig.out /a 5,11
```

To set the *OCTET1* environment variable in the local environment to the value found at the coordinate *5,3* in the *Ipconfig.out* file with delimiters **#$*.**, type:

```
setx OCTET1 /f ipconfig.out /a 5,3 /d #$*.
```

To set the *IPGATEWAY* environment variable in the local environment to the value found at the coordinate *0,7* with respect to the coordinate of *Gateway* in the *Ipconfig.out* file, type:

```
setx IPGATEWAY /f ipconfig.out /r 0,7 Gateway
```

To display the contents of the *Ipconfig.out* file, along with the contents' corresponding coordinates, on a computer named *computer1*, type:

```
setx /s computer1 /u maindom\hiropln /p p@ssW23 /f ipconfig.out /x
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


