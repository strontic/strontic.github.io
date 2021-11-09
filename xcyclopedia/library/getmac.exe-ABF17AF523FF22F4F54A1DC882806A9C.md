---
title: getmac.exe | Displays NIC MAC information
excerpt: What is getmac.exe?
---

# getmac.exe 

* File Path: `C:\WINDOWS\system32\getmac.exe`
* Description: Displays NIC MAC information

## Hashes

Type | Hash
-- | --
MD5 | `ABF17AF523FF22F4F54A1DC882806A9C`
SHA1 | `DBB90021970DFC9B1EA8E04316724E6879E6FA0D`
SHA256 | `92473977A002C5A70B652DAB2BD5E7099940E35F03AE0249935E5667916D149D`
SHA384 | `F1772393EC11C26B6FAD6CF6F957E829059D1195D79CAA670E4F0CB4BCDF79BBEFF6839096FB04E7CAD973BED680C4AC`
SHA512 | `CC1E06D5B4BC97C699B8DE30CED5A5896D5B112177954BA210B94F74077406A1F6A7911FD5DA8C06D273B2E587D549673F753F33CFF056231645E6C7844C358E`
SSDEEP | `1536:Kv1a76XN0nZeFBcvv/YxwiEVbLFJoUD0dQlY6zw0bH7FZAaNs5:IU7ALFAji2tJoI0Ck0bHRZAa6`
IMP | `09D98CEBD60FAD97D0A14690BDB89C42`
PESHA1 | `A4CC75AA43760F3256794E10C84FCFB59824CC91`
PE256 | `D9518CD7A22F22ED12C0B1F076E876F6C1394068B669203535E03F1067199C91`

## Runtime Data

### Usage (stdout):
```cmhg

GETMAC [/S system [/U username [/P [password]]]] [/FO format] [/NH] [/V]

Description:
    This tool enables an administrator to display the MAC address
    for network adapters on a system.

Parameter List: 
    /S     system            Specifies the remote system to connect to.

    /U     [domain\]user     Specifies the user context under 
                             which the command should execute.

    /P     [password]        Specifies the password for the given
                             user context. Prompts for input if omitted.

    /FO    format            Specifies the format in which the output
                             is to be displayed.
                             Valid values: "TABLE", "LIST", "CSV".

    /NH                      Specifies that the "Column Header" should
                             not be displayed in the output.
                             Valid only for TABLE and CSV formats.

    /V                       Specifies that verbose output is displayed.

    /?                       Displays this help message.

Examples: 
    GETMAC /? 
    GETMAC /FO csv 
    GETMAC /S system /NH /V
    GETMAC /S system /U user
    GETMAC /S system /U domain\user /P password /FO list /V
    GETMAC /S system /U domain\user /P password /FO table /NH

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "GETMAC /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\system32\getmac.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GetMac.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/92473977a002c5a70b652dab2bd5e7099940e35f03ae0249935e5667916d149d/detection



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## getmac

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Returns the media access control (MAC) address and list of network protocols associated with each address for all network cards in each computer, either locally or across a network. This command is particularly useful either when you want to enter the MAC address into a network analyzer, or when you need to know what protocols are currently in use on each network adapter on a computer.

### Syntax

```
getmac[.exe][/s <computer> [/u <domain\<user> [/p <password>]]][/fo {table | list | csv}][/nh][/v]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /s `<computer>` | Specifies the name or IP address of a remote computer (do not use backslashes). The default is the local computer. |
| /u `<domain>\<user>` | Runs the command with the account permissions of the user specified by *user* or *domain\user*. The default is the permissions of the current logged on user on the computer issuing the command. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. |
| /fo {table \| list \| csv} | Specifies the format to use for the query output. Valid values are **table**, **list**, and **csv**. The default format for output is **table**. |
| /nh | Suppresses column header in output. Valid when the **/fo** parameter is set to **table** or **csv**. |
| /v | Specifies that the output display verbose information. |
| /? | Displays help at the command prompt. |

#### Examples

The following examples show how you can use the **getmac** command:

```
getmac /fo table /nh /v
```

```
getmac /s srvmain
```

```
getmac /s srvmain /u maindom\hiropln
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23 /fo list /v
```

```
getmac /s srvmain /u maindom\hiropln /p p@ssW23 /fo table /nh
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


