---
title: openfiles.exe | Displays the current open files list
---

# openfiles.exe 

* File Path: `C:\Windows\SysWOW64\openfiles.exe`
* Description: Displays the current open files list
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `50BD10A4C573E609A401114488299D3D`
SHA1 | `7240332D975AAF2F26726730CA18113FE37B5563`
SHA256 | `8C8EAD6B2FFF2BECE455B6B43BE47DDD177B5803F1CE9D0AB7CF5F23AEFC3221`
SHA384 | `6FA1B656C2C268AE158463DC87FA40F49A796311DE131F535545C6A45F1151885E305F3D38FFD4A80133283C74C3D02F`
SHA512 | `E44F4C4A23FD6C57B155ED4D531EC83453A64D78D1FD03979F2D7C501156C620D598005B60E8DCBB5A42AD090BA6FB908ADBBAAD09B97A230A63FB663BB5AC90`
SSDEEP | `1536:vORfIKvHBDNrNIwv9DVSc+c3YWaq9xddR/:HKvHBDXIs1VSc+cZaq9xzR/`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile
ERROR: The target system must be running a 32 bit OS.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: opnfiles.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## openfiles



Enables an administrator to query, display, or disconnect files and directories that have been opened on a system. Also enables or disables the system Maintain Objects List global flag.

This topic includes information about the following commands:
-   [openfiles /disconnect](#BKMK_disconnect)
-   [openfiles /query](#BKMK_query)
-   [openfiles /local](#BKMK_local)

### <a name=BKMK_disconnect></a>openfiles /disconnect

Enables an administrator to disconnect files and folders that have been opened remotely through a shared folder.

#### Syntax

```
openfiles /disconnect [/s <System> [/u [<Domain>\]<UserName> [/p [<Password>]]]] {[/id <OpenFileID>] | [/a <AccessedBy>] | [/o {read | write | read/write}]} [/op <OpenFile>]
```

##### Parameters

|            Parameter             |                                                                                                                                 Description                                                                                                                                  |
|----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|           /s \<System>           | Specifies the remote system to connect to (by name or IP address). Do not use backslashes. If you do not use the **/s** option, the command is executed on the local computer by default. This parameter applies to all files and folders that are specified in the command. |
|    /u [\<Domain>\]<UserName>     |                                                          Executes the command by using the permissions of the specified user account. If you do not use the **/u** option, system permissions are used by default.                                                           |
|         /p [\<Password>]         |                                               Specifies the password of the user account that is specified in the **/u** option. If you do not use the **/p** option, a password prompt appears when the command is executed.                                                |
|        /id \<OpenFileID>         |                                       Disconnects open files by the specified file ID. The wildcard character (**&#42;**) can be used with this parameter.</br>Note: You can use the **openfiles /query** command to find the file ID.                                       |
|         /a \<AccessedBy>         |                                                Disconnects all open files associated with the user name that is specified in the *AccessedBy* parameter. The wildcard character (**&#42;**) can be used with this parameter.                                                 |
| /o {read \| write \| read/write} |                                               Disconnects all open files with the specified open mode value. Valid values are Read, Write, or Read/Write. The wildcard character (**&#42;**) can be used with this parameter.                                                |
|         /op \<OpenFile>          |                                                           Disconnects all open file connections that are created by a specific open file name. The wildcard character (**&#42;**) can be used with this parameter.                                                           |
|                /?                |                                                                                                                     Displays help at the command prompt.                                                                                                                     |

#### Examples

To disconnect all open files with the file ID 26843578, type:
```
openfiles /disconnect /id 26843578
```
To disconnect all open files and directories accessed by the user hiropln, type:
```
openfiles /disconnect /a hiropln
```
To disconnect all open files and directories with read/write mode, type:
```
openfiles /disconnect /o read/write
```
To disconnect the directory with the Open File name C:\TestShare\, regardless of who is accessing it, type:
```
openfiles /disconnect /a * /op c:\testshare\
```
To disconnect all open files on the remote computer srvmain that are being accessed by the user hiropln, regardless of their ID, type:
```
openfiles /disconnect /s srvmain /u maindom\hiropln /id *
```

### <a name=BKMK_query></a>openfiles /query

Queries and displays all open files.

#### Syntax

```
openfiles /query [/s <System> [/u [<Domain>\]<UserName> [/p [<Password>]]]] [/fo {TABLE | LIST | CSV}] [/nh] [/v]
```

##### Parameters

|          Parameter           |                                                                                                                                 Description                                                                                                                                  |
|------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|         /s \<System>         | Specifies the remote system to connect to (by name or IP address). Do not use backslashes. If you do not use the **/s** option, the command is executed on the local computer by default. This parameter applies to all files and folders that are specified in the command. |
|  /u [\<Domain>\]<UserName>   |                                                          Executes the command by using the permissions of the specified user account. If you do not use the **/u** option, system permissions are used by default.                                                           |
|       /p [\<Password>]       |                                               Specifies the password of the user account that is specified in the **/u** option. If you do not use the **/p** option, a password prompt appears when the command is executed.                                                |
| [/fo {TABLE \| LIST \| CSV}] |                             Displays the output in the specified format. Valid values for *Format* are:</br>TABLE:  Displays output in a table.</br>LIST: Displays output in a list.</br>CSV: Displays output in Comma Separated Values format.                              |
|             /nh              |                                                                                Suppresses column header in the output. Valid only when the **/fo** parameter is set to **TABLE** or **CSV**.                                                                                 |
|              /v              |                                                                                                       Specifies that detailed information be displayed in the output.                                                                                                        |
|              /?              |                                                                                                                     Displays help at the command prompt.                                                                                                                     |

#### Examples

To query and display all open files, type:
```
openfiles /query
```
To query and display all open files in table format without headers, type:
```
openfiles /query /fo table /nh
```
To query and display all open files in list format with detailed information, type:
```
openfiles /query /fo list /v
```
To query and display all open files on the remote system srvmain by using the credentials for the user hiropln on the maindom domain, type:
```
openfiles /query /s srvmain /u maindom\hiropln /p p@ssW23
```

> [!NOTE]
> In this example, the password is supplied on the command line. To prevent displaying the password, leave out the **/p** option. You will be prompted for the password, which will not be echoed to the screen.

### <a name=BKMK_local></a>openfiles /local

Enables or disables the system Maintain Objects List global flag. If used without parameters, **openfiles /local** displays the current status of the Maintain Objects List global flag.

#### Syntax

```
openfiles /local [on | off]
```

##### Parameters

|Parameter|Description|
|---------|-----------|
|[on \| off]|Enables or disables the system Maintain Objects List global flag, which tracks local file handles.|
|/?|Displays help at the command prompt.|

#### Remarks

-   Enabling the Maintain Objects List global flag may slow down your system.
-   Changes made by using the **on** or **off** option do not take effect until you restart the system.

#### Examples

To check the current status of the Maintain Objects List global flag, type:
```
openfiles /local
```
By default, the Maintain Objects List global flag is disabled, and the following output is displayed:
```
INFO: The system global flag 'maintain objects list' is currently disabled.
```
To enable the Maintain Objects List global flag, type:
```
openfiles /local on
```
The following message is displayed when the global flag is enabled:
```
SUCCESS: The system global flag 'maintain objects list' is enabled.
         This will take effect after the system is restarted.
```
To disable the Maintain Objects List global flag, type:
```
openfiles /local off
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


