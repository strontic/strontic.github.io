---
title: gpresult.exe | Query Group Policy RSOP Data
excerpt: What is gpresult.exe?
---

# gpresult.exe 

* File Path: `C:\Windows\SysWOW64\gpresult.exe`
* Description: Query Group Policy RSOP Data

## Hashes

Type | Hash
-- | --
MD5 | `4CE46E3DEDF809788CA8438AD491559F`
SHA1 | `E2DEA8C3294544614BDFACD7B77B100B0F4497C8`
SHA256 | `3286F3271943104E023E36323F0ABBB114C2C59E3A95D64951B1AAFE964272A0`
SHA384 | `434787D367F2E94475DCEA8C7637F04D225B03505F07A0759380FA0320EC6DB9E600E6E3F9CD58E916F73E220D85D59E`
SHA512 | `835227D54F1BC7222C9575DAB48061A85E8547BD4F4D4986240F08B3EE65B3D6CF577BB537460908545D0E9D8E5E3767AD6B99A1BDDA08DCD823AD1694818FA8`
SSDEEP | `3072:uQ+sOKvkZ05VarRlyE19HmHmPbVrA/ZbaZ48FfIiPe0mc3CPbuw7MWktI:hBbValME19HmHmPbmRbb8JIirmcyPb9K`
IMP | `01C94545980BD083D50BD5F70C211D99`
PESHA1 | `2CCAC1027CED739CAACA9F5FC1FC82734ACED8AE`
PE256 | `F95F2903F49B5AE1E31220ED7995241F8D14E7B3FCA479719434C3C3739A8632`

## Runtime Data

### Usage (stdout):
```cmhg

GPRESULT [/S system [/U username [/P [password]]]] [/SCOPE scope]
           [/USER targetusername] [/R | /V | /Z] [(/X | /H) <filename> [/F]]

Description:
    This command line tool displays the Resultant Set of Policy (RSoP)
    information for a target user and computer.

Parameter List:
    /S        system           Specifies the remote system to connect to.

    /U        [domain\]user    Specifies the user context under which the
                               command should run.
                               Can not be used with /X, /H.

    /P        [password]       Specifies the password for the given user
                               context. Prompts for input if omitted.
                               Cannot be used with /X, /H.

    /SCOPE    scope            Specifies whether the user or the
                               computer settings need to be displayed.
                               Valid values: "USER", "COMPUTER".

    /USER     [domain\]user    Specifies the user name for which the
                               RSoP data is to be displayed.

    /X        <filename>       Saves the report in XML format at the
                               location and with the file name specified
                               by the <filename> parameter. (valid in Windows
                               Vista SP1 and later and Windows Server 2008 and later)

    /H        <filename>       Saves the report in HTML format at the
                               location and with the file name specified by
                               the <filename> parameter. (valid in Windows
                               at least Vista SP1 and at least Windows Server 2008)

    /F                         Forces Gpresult to overwrite the file name
                               specified in the /X or /H command.

    /R                         Displays RSoP summary data.

    /V                         Specifies that verbose information should
                               be displayed. Verbose information provides
                               additional detailed settings that have
                               been applied with a precedence of 1.

    /Z                         Specifies that the super-verbose
                               information should be displayed. Super-
                               verbose information provides additional
                               detailed settings that have been applied
                               with a precedence of 1 and higher. This
                               allows you to see if a setting was set in
                               multiple places. See the Group Policy
                               online help topic for more information.

    /?                         Displays this help message.


Examples:
    GPRESULT /R
    GPRESULT /H GPReport.html
    GPRESULT /USER targetusername /V
    GPRESULT /S system /USER targetusername /SCOPE COMPUTER /Z
    GPRESULT /S system /U username /P password /SCOPE USER /V

```

### Usage (stderr):
```cmhg
ERROR: Invalid syntax. Value expected for '/h'.
Type "GPRESULT /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\gpresult.exe |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gprslt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3286f3271943104e023e36323f0abbb114c2c59e3a95d64951b1aafe964272a0/detection/



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## gpresult

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the Resultant Set of Policy (RSoP) information for a remote user and computer. To use RSoP reporting for remotely targeted computers through the firewall, you must have firewall rules that enable inbound network traffic on the ports.

### Syntax

```
gpresult [/s <system> [/u <username> [/p [<password>]]]] [/user [<targetdomain>\]<targetuser>] [/scope {user | computer}] {/r | /v | /z | [/x | /h] <filename> [/f] | /?}
```

> [!NOTE]
> Except when using **/?**, you must include an output option, **/r**, **/v**, **/z**, **/x**, or **/h**.

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /s `<system>` | Specifies the name or IP address of a remote computer. Don't use backslashes. The default is the local computer. |
| /u `<username>` | Uses the credentials of the specified user to run the command. The default user is the user who is logged on to the computer that issues the command. |
| /p `[<password>]` | Specifies the password of the user account that is provided in the **/u** parameter. If **/p** is omitted, **gpresult** prompts for the password. The **/p** parameter can't be used with **/x** or **/h**. |
| /user `[<targetdomain>\]<targetuser>]` | Specifies the remote user whose RSoP data is to be displayed. |
| /scope `{user | computer}` | Displays RSoP data for either the user or the computer. If **/scope** is omitted, **gpresult** displays RSoP data for both the user and the computer. |
| `[/x | /h] <filename>` | Saves the report in either XML (**/x**) or HTML (**/h**) format at the location and with the file name that is specified by the *filename* parameter. Can't be used with **/u**, **/p**, **/r**, **/v**, or **/z**. |
| /f | Forces **gpresult** to overwrite the file name that is specified in the **/x** or **/h** option. |
| /r | Displays RSoP summary data. |
| /v | Displays verbose policy information. This includes detailed settings that were applied with a precedence of 1. |
| /z | Displays all available information about Group Policy. This includes detailed settings that were applied with a precedence of 1 and higher. |
| /? | Displays help at the command prompt. |

##### Remarks

- Group Policy is the primary administrative tool for defining and controlling how programs, network resources, and the operating system operate for users and computers in an organization. In an active directory environment, Group Policy is applied to users or computers based on their membership in sites, domains, or organizational units.

- Because you can apply overlapping policy settings to any computer or user, the Group Policy feature generates a resulting set of policy settings when the user logs on. The **gpresult** command displays the resulting set of policy settings that were enforced on the computer for the specified user when the user logged on.

- Because **/v** and **/z** produce a lot of information, it's useful to redirect output to a text file (for example, `gpresult/z >policy.txt`).

#### Examples

To retrieve RSoP data for only the remote user, *maindom\hiropln* with the password *p@ssW23*, who's on the computer *srvmain*, type:

```
gpresult /s srvmain /u maindom\hiropln /p p@ssW23 /user targetusername /scope user /r
```

To save all available information about Group Policy to a file named, *policy.txt*, for only the remote user *maindom\hiropln* with the password *p@ssW23*, on the computer *srvmain*, type:

```
gpresult /s srvmain /u maindom\hiropln /p p@ssW23 /user targetusername /z > policy.txt
```

To display RSoP data for the logged on user, *maindom\hiropln* with the password *p@ssW23*, for the computer *srvmain*, type:

```
gpresult /s srvmain /u maindom\hiropln /p p@ssW23 /r
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


