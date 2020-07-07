---
title: setx.exe | Setx - Sets environment variables
---

# setx.exe 

* File Path: `C:\windows\SysWOW64\setx.exe`
* Description: Setx - Sets environment variables
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `6343A4BB2F54CC5950DAE2280E199486`
SHA1 | `A61B9CBB008A8A5FBEB527500C0F79DFDFA5FC8E`
SHA256 | `8835A72592F8A7DA8FFC8D058410D0175CB1905B018906F22B922DC1180C4027`
SHA384 | `DE09789A24464B8487CA5D5E585360910162BFB64A0117B4D5B30DB830B1D2266EE5624CBE8984B33B6CB99957B206AC`
SHA512 | `5916E82CE2375D341F6AB060859CC813140D0CF6092A73AD8B99F0327B83B1E22832B2F4AEAD2D45486842889F2F9D86DE59473AC07FCBA14F22B47C8348704E`
SSDEEP | `768:RmF6RDl+n8wnP9CV/ata5gvUEYemJ/PTntsNPqAluuD6K9MbEYyxKodNoailP:MF6AtaYUEQ1UPqOuuDHvood+ail`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\setx.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: setx.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## setx

Creates or modifies environment variables in the user or system environment, without requiring programming or scripting. The **Setx** command also retrieves the values of registry keys and writes them to text files.



### Syntax

```
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] <Variable> <Value> [/m]
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] [<Variable>] /k <Path> [/m]
setx [/s <Computer> [/u [<Domain>\]<User name> [/p [<Password>]]]] /f <FileName> {[<Variable>] {/a <X>,<Y> | /r <X>,<Y> <String>} [/m] | /x} [/d <Delimiters>]
```

#### Parameters

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

### Remarks

-   The **Setx** command is similar to the UNIX utility SETENV.
-   **Setx** provides the only command-line or programmatic way to directly and permanently set system environment values. System environment variables are manually configurable through **Control Panel** or through a registry editor. The **set** command, which is internal to the command interpreter (Cmd.exe), sets user environment variables for the current console window only.
-   You can use the **setx** command to set values for user and system environment variables from one of three sources (modes): Command Line Mode, Registry Mode, or File Mode.
-   **Setx** writes variables to the master environment in the registry. Variables set with **setx** variables are available in future command windows only, not in the current command window.
-   **HKEY_CURRENT_USER** and **HKEY_LOCAL_MACHINE** are the only supported hives. REG_DWORD, REG_EXPAND_SZ, REG_SZ, and REG_MULTI_SZ are the valid **RegKey** data types.
-   When you gain access to **REG_MULTI_SZ** values in the registry, only the first item is extracted and used.
-   You cannot use the **setx** command to remove values that have been added to the local or system environments. You can use **set** with a variable name and no value to remove a corresponding value from the local environment.
-   REG_DWORD registry values are extracted and used in hexadecimal mode.
-   File mode supports the parsing of carriage return and line feed (CRLF) text files only.

### Examples

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

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


