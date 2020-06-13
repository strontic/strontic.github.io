
# driverquery.exe 

* File Path: `C:\WINDOWS\system32\driverquery.exe`
* Description: Queries the drivers on a system
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9A90C33B8663A96394675C95B9BF540C`
SHA1 | `0DA4CBE5244EE5451FAF0F6EC7A1A58F76E7B332`
SHA256 | `0D0B565F8AEB0ED951320B790AB5EE120AC485C1F502757C5E3F9C337A83BE57`
SHA384 | `2DCE053322AEAF95B353DF3FADAC444E2DA979C1D12C79C280EBC7EE057EA9D15271937CC5638B0E3CB71498FB6E5615`
SHA512 | `65584B8809ADE5D7B08ECF294EC7FBBBA5EDC148D0774C3602A051B7542F674E0045A162915C4ABFAB1C29362842276C9EFB4CB4BE8D2FCB2B06B4718071195F`
SSDEEP | `1536:AKPAuORd6xM2ndgV27MsiKO7J+5SJZW1c8VdI9T+tkNvGI/xKYTLb:Z4J27P1OfWG8VmF+kp/x1D`

## Runtime Data

### Usage (stdout):
```Batchfile

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
```Batchfile
ERROR: Invalid argument/option - '-help'.
Type "DRIVERQUERY /?" for usage.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: drvqry.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# driverquery

Enables an administrator to display a list of installed device drivers and their properties. If used without parameters, **driverquery** runs on the local computer.

## Syntax

```
driverquery [/s <system> [/u [<domain>\]<username> [/p <password>]]] [/fo {table | list | csv}] [/nh] [/v | /si]
```

### Parameters

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

### Examples

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

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


