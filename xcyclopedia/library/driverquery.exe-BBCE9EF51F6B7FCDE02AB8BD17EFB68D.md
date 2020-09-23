---
title: driverquery.exe | Queries the drivers on a system
excerpt: What is driverquery.exe?
---

# driverquery.exe 

* File Path: `C:\windows\SysWOW64\driverquery.exe`
* Description: Queries the drivers on a system

## Hashes

Type | Hash
-- | --
MD5 | `BBCE9EF51F6B7FCDE02AB8BD17EFB68D`
SHA1 | `9DD4E6E0A130168FC597F7D787CECD4CE5E6C045`
SHA256 | `A07C4D3B4970E4041201B62DAA296EBE8EEAE6A940B40C0A545EB6215D13EACE`
SHA384 | `29A1B6B21AF3969FBF56A5D050AA0DEDB9FF5E2FEE7280E482B4E2C859681EA38D6CA58C7EFE5C9E4123CD1B1BCEC19F`
SHA512 | `DD2CDE48BB01EFB7EEB3AFF3066C548D22D8A077FFA693BFF836966E5E4B791E4973040DF582D409143D6373D23944ACA0889897E5F315A92EE3A2DAED799C73`
SSDEEP | `1536:LWJR/QDvPbFXOQzSrnjKEV47Rn0v4yB/s5YAmnq6FCUmTLxZwyM:NDvPbFXOQzSrnjKPR5y1sPN1LxqJ`

## Signature

* Status: The file C:\windows\SysWOW64\driverquery.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: drvqry.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## driverquery

Enables an administrator to display a list of installed device drivers and their properties. If used without parameters, **driverquery** runs on the local computer.

### Syntax

```
driverquery [/s <system> [/u [<domain>\]<username> [/p <password>]]] [/fo {table | list | csv}] [/nh] [/v | /si]
```

#### Parameters

| Parameter | Description |
| --------- |------------ |
| /s `<system>` | Specifies the name or IP address of a remote computer. Do not use backslashes. The default is the local computer. |
| /u `[<domain>]<username>` | Runs the command with the credentials of the user account as specified by *user* or *domain\user*. By default, */s* uses the credentials of the user who is currently logged on to the computer that is issuing the command. **/u** can't be used unless **/s** is specified. |
| /p `<password>` | Specifies the password of the user account that is specified in the **/u** parameter. **/p** cannot be used unless **/u** is specified. |
| /fo table | Formats the output as a table. This is the default. |
| /fo list | Formats the output as a list. |
| /fo csv | Formats the output with comma-separated values. |
| /nh | Omits the header row from the displayed driver information. Not valid if the **/fo** parameter is set to **list**. |
| /v | Displays verbose output. **/v** is not valid for signed drivers. |
| /si | Provides information about signed drivers. |
| /? | Displays help at the command prompt. |

#### Examples

To display a list of installed device drivers on the local computer, type:

```
driverquery
```

To display the output in a comma-separated values (CSV) format, type:

```
driverquery /fo csv
```

To hide the header row in the output, type:

```
driverquery /nh
```

To use the **driverquery** command on a remote server named *server1* using your current credentials on the local computer, type:

```
driverquery /s server1
```

To use the **driverquery** command on a remote server named *server1* using the credentials for *user1* on the domain *maindom*, type:

```
driverquery /s server1 /u maindom\user1 /p p@ssw3d
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


