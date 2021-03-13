---
title: driverquery.exe | Queries the drivers on a system
excerpt: What is driverquery.exe?
---

# driverquery.exe 

* File Path: `C:\Windows\SysWOW64\driverquery.exe`
* Description: Queries the drivers on a system

## Hashes

Type | Hash
-- | --
MD5 | `D14D75148EB7FCCD8D8849F9BFDC4E89`
SHA1 | `2BC4B5F66769C9A7361D86EB3B8B2A82A285E65C`
SHA256 | `42EC0718E29088EA73BBAC9C96EAF02807BA556A392FA8C830AE9B425B7E0CC0`
SHA384 | `D9308CE4907507C330C3A3975073361C24AE8FCA7FA2009619C5EC3614C12EAC53C22AD85AFC7CFF90C94DBE68E6B62F`
SHA512 | `AF16C83D1468AAABCD10A3A4BB13BC753D30770F6496526E561674D36DB0B974A678C7E35A10153059FB26BEB1FBF257F08B5D5744FEAC7E54297E7A711468E2`
SSDEEP | `1536:LSJUbCDS01QaavBCGWFxND02cCncUIfP0N5yIKxfm8:/bCF1QaD/DncdUZ1Kxe`
IMP | `C118304E7D2CAFD7F39FDA694BE5CE60`
PESHA1 | `516F7F8F94692A7D2EBF8EC4B11FF2B68C476672`
PE256 | `08910C8DB9E4C230452404BEA0651678C0C80AE6C6151FFBF8B6D9D296A7F536`

## Runtime Data

### Usage (stdout):
```cmhg

DRIVERQUERY [/S system [/U username [/P [password]]]]
              [/FO format] [/NH] [/SI] [/V] 
Description:
    Enables an administrator to display a list of 
    installed device drivers.

Parameter List:
      /S     system           Specifies the remote system to connect to.

      /U     [domain\]user    Specifies the user context 
                              under which the command should execute.

      /P     [password]       Specify the password for the given 
                              user context.

      /FO    format           Specifies the type of output to display.
                              Valid values to be passed with the
                              switch are "TABLE", "LIST", "CSV".

      /NH                     Specifies that the "Column Header" 
                              should not be displayed. Valid for  
                              "TABLE" and "CSV" format only.

      /SI                     Provides information about signed drivers.

      /V                      Displays verbose output. Not valid 
                              for signed drivers.

      /?                      Displays this help message.

Examples:
    DRIVERQUERY
    DRIVERQUERY /FO CSV /SI
    DRIVERQUERY /NH
    DRIVERQUERY /S ipaddress /U user /V 
    DRIVERQUERY /S system /U domain\user /P password /FO LIST

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "DRIVERQUERY /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\driverquery.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: drvqry.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/42ec0718e29088ea73bbac9c96eaf02807ba556a392fa8c830ae9b425b7e0cc0/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


