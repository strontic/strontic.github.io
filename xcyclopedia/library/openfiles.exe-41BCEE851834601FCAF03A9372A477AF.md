---
title: openfiles.exe | Displays the current open files list
---

# openfiles.exe 

* File Path: `C:\Windows\SysWOW64\openfiles.exe`
* Description: Displays the current open files list

## Hashes

Type | Hash
-- | --
MD5 | `41BCEE851834601FCAF03A9372A477AF`
SHA1 | `D96A322CBACD7E4DD78500BBED2A84DC51A6AB8B`
SHA256 | `AE663F66615F66A4F5970FFF2EBC7B50142BB5FA809B472D942B50887DAF9F0F`
SHA384 | `4BB66ACAB0016BC010A8E9D5FBE82903CEED662EB6BF73F8C2BDC21B9DCBB513F5300B0F34A55F795DFDC80D73EF899D`
SHA512 | `151938F70B2848C10004B07CD9E860B8739A7E4B07F25B95E60D5EA083C869ADA2BAAD2AE616E5CFAE27E3704C265A342D39F60A7B5755D228D420D8FD495129`
SSDEEP | `1536:FORf+E6e0Obn96ysWUux88cs3+tamCxdqc:W6e0O9X7Uum8clamCxQ`

## Runtime Data

### Usage (stderr):
```Batchfile
ERROR: The target system must be running a 32 bit OS.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: opnfiles.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## openfiles

Enables an administrator to query, display, or disconnect files and directories that have been opened on a system. This command also enables or disables the system **Maintain Objects List** global flag.

### openfiles /disconnect

Enables an administrator to disconnect files and folders that have been opened remotely through a shared folder.

#### Syntax

```
openfiles /disconnect [/s <system> [/u [<domain>\]<username> [/p [<password>]]]] {[/id <openfileID>] | [/a <accessedby>] | [/o {read | write | read/write}]} [/op <openfile>]
```

##### Parameters

| Parameter | Description |
|--|--|
| /s `<system>` | Specifies the remote system to connect to (by name or IP address). Don't use backslashes. If you don't use the **/s** option, the command is run on the local computer by default. This parameter applies to all files and folders that are specified in the command. |
| /u `[<domain>\]<username>` | Runs the command using the permissions of the specified user account. If you don't use the **/u** option, system permissions are used by default. |
| /p `[<password>]` | Specifies the password of the user account that is specified in the **/u** option. If you don't use the **/p** option, a password prompt appears when the command is run. |
| /id `<openfileID>` | Disconnects open files by the specified file ID. You can use the wildcard character (**&#42;**) with this parameter.<p>Note: You can use the **openfiles /query** command to find the file ID. |
| /a `<accessedby>` | Disconnects all open files associated with the user name specified in the *accessedby* parameter. You can use the wildcard character (**&#42;**) with this parameter. |
| /o `{read | write | read/write}` | Disconnects all open files with the specified open mode value. Valid values are **Read**, **Write**, or **Read/Write**. You can use the wildcard character (**&#42;**) with this parameter. |
| /op `<openfile>` | Disconnects all open file connections that are created by a specific open file name. You can use the wildcard character (**&#42;**) with this parameter. |
| /? | Displays help at the command prompt. |

#### Examples

To disconnect all open files with the *file ID 26843578*, type:

```
openfiles /disconnect /id 26843578
```

To disconnect all open files and directories accessed by the user *hiropln*, type:

```
openfiles /disconnect /a hiropln
```

To disconnect all open files and directories with *read/write mode*, type:

```
openfiles /disconnect /o read/write
```

To disconnect the directory with the open file name *C:\testshare\*, regardless of who is accessing it, type:

```
openfiles /disconnect /a * /op c:\testshare\
```

To disconnect all open files on the remote computer *srvmain* that are being accessed by the user *hiropln*, regardless of their ID, type:

```
openfiles /disconnect /s srvmain /u maindom\hiropln /id *
```

### openfiles /query

Queries and displays all open files.

#### Syntax

```
openfiles /query [/s <system> [/u [<domain>\]<username> [/p [<password>]]]] [/fo {TABLE | LIST | CSV}] [/nh] [/v]
```

##### Parameters


| Parameter | Description |
|--|--|
| /s `<system>` | Specifies the remote system to connect to (by name or IP address). Don't use backslashes. If you don't use the **/s** option, the command is run on the local computer by default. This parameter applies to all files and folders that are specified in the command. |
| /u `[<domain>\]<username>` | Runs the command using the permissions of the specified user account. If you don't use the **/u** option, system permissions are used by default. |
| /p `[<password>]` | Specifies the password of the user account that is specified in the **/u** option. If you don't use the **/p** option, a password prompt appears when the command is run. |
| [/fo `{TABLE | LIST | CSV}`] | Displays the output in the specified format. Valid values include:<ul><li>**TABLE** - Displays output in a table.</li><li>**LIST** - Displays output in a list.</li><li>**CSV** - Displays output in Comma Separated Values (CSV) format.</li></ul> |
| /nh | Suppresses column headers in the output. Valid only when the **/fo** parameter is set to **TABLE** or **CSV**. |
| /v | Specifies that detailed (verbose) information be displayed in the output. |
| /? | Displays help at the command prompt. |

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

To query and display all open files on the remote system *srvmain* by using the credentials for the user *hiropln* on the *maindom* domain, type:

```
openfiles /query /s srvmain /u maindom\hiropln /p p@ssW23
```

> [!NOTE]
> In this example, the password is supplied on the command line. To prevent displaying the password, leave out the **/p** option. You'll be prompted for the password, which won't be echoed to the screen.

### openfiles /local

Enables or disables the system **Maintain Objects List** global flag. If used without parameters, **openfiles /local** displays the current status of the **Maintain Objects List** global flag.

> [!NOTE]
> Changes made by using the **on** or **off** option don't take effect until you restart the system. Enabling the **Maintain Objects List** global flag might slow down your system.

#### Syntax

```
openfiles /local [on | off]
```

##### Parameters

| Parameter | Description |
|--|--|
| `[on | off]` | Enables or disables the system **Maintain Objects List** global flag, which tracks local file handles. |
| /? | Displays help at the command prompt. |

#### Examples

To check the current status of the **Maintain Objects List** global flag, type:

```
openfiles /local
```

By default, the **Maintain Objects List** global flag is disabled, and the following message appears, `INFO: The system global flag 'maintain objects list' is currently disabled.`

To enable the **Maintain Objects List** global flag, type:

```
openfiles /local on
```

The following message appears when the global flag is enabled, `SUCCESS: The system global flag 'maintain objects list' is enabled. This will take effect after the system is restarted.`

To disable the **Maintain Objects List** global flag, type:

```
openfiles /local off
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


