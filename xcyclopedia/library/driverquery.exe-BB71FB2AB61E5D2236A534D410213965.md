---
title: driverquery.exe | Queries the drivers on a system
excerpt: What is driverquery.exe?
---

# driverquery.exe 

* File Path: `C:\WINDOWS\system32\driverquery.exe`
* Description: Queries the drivers on a system

## Hashes

Type | Hash
-- | --
MD5 | `BB71FB2AB61E5D2236A534D410213965`
SHA1 | `A2EA75B35D49D2E02144B6B4DD182859217F4F37`
SHA256 | `31C7953EFDA0F9F4853FE345EDBC0E402B609F3A781A09A164C3E74B15D5A799`
SHA384 | `3BA3B733BE3997FE8751B8B03839A32FEA668E26F5EFDA2AB4E9B8F7D2683136E9C2B327B71754E5D8CBF1EDB86BC1A1`
SHA512 | `5D989E212D132D796AF8877A2AA2FB5CAE3142ACF7C925E98248F56BCB51E4EF120379AA0FB4EA6FD8FF6E2DDAAC184BF350102328227C55039C7BA85F0D60F0`
SSDEEP | `1536:62dVWlt/oyjyXFZgxCVXtkqFJLEHOlOyGSJR7JuDPZExICx/iVa:60GWsxCV9TLh75ulEGCx/Ga`
IMP | `033B70299A7F2D13D2CCD201F2FD5461`
PESHA1 | `FFA6559F615F1D703E06E360C11F57BEC7EC16FD`
PE256 | `B67AB37962233DFDE2102BDEB74D26F286EAD5EB0836E3F28FCB160779C4ED6E`

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
C:\WINDOWS\system32\driverquery.exe |
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

* Original Filename: drvqry.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/31c7953efda0f9f4853fe345edbc0e402b609f3a781a09a164c3e74b15d5a799/detection



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


