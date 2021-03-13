---
title: getmac.exe | Displays NIC MAC information
excerpt: What is getmac.exe?
---

# getmac.exe 

* File Path: `C:\Windows\system32\getmac.exe`
* Description: Displays NIC MAC information

## Hashes

Type | Hash
-- | --
MD5 | `AFF4CB80DA66CF74426CA8089FCD0BB6`
SHA1 | `BBF3F30E24B97D6B7C8FD6417672B797DF596627`
SHA256 | `31A48B157DB2CED030516B0F41604EF7BB51149FBA3FAFD1926347F92B9CA5E2`
SHA384 | `4E391E22E05F758136B42D96F77CB520EBD47665522F2E4F0BE20DB6C619F30F7A5858330F9F6953FF874ED29C4ECA65`
SHA512 | `D1F654DBAF4FD3A2E4ACD3457F40C757574B1D6527A2469A41B06999D09132E02644B017426C8922E3ECD11C7ADAF19284E76D2B4DD8BE4FC65E3FD6B4183A20`
SSDEEP | `1536:BjEOQ0AcBjnfgqI84EvJsyU810TSdCpYaz4bxTkEaGCUasmN:BjREcBTg7qJNL+TSdHbxpTCUaX`
IMP | `8E550FD6D80E97018F9097BB725420C8`
PESHA1 | `71F07792C4B2790AC534EA7D49150EA88793ED4B`
PE256 | `D53B41677226C59748B8B1724ECF08871BC899232CF70A119DBD9A79AD947E39`

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
C:\Windows\system32\getmac.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: GetMac.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/31a48b157db2ced030516b0f41604ef7bb51149fba3fafd1926347f92b9ca5e2/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## getmac

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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
| /fo {table | list | csv} | Specifies the format to use for the query output. Valid values are **table**, **list**, and **csv**. The default format for output is **table**. |
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


