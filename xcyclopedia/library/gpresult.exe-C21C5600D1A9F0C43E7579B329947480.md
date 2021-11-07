---
title: gpresult.exe | Query Group Policy RSOP Data
excerpt: What is gpresult.exe?
---

# gpresult.exe 

* File Path: `C:\WINDOWS\system32\gpresult.exe`
* Description: Query Group Policy RSOP Data

## Hashes

Type | Hash
-- | --
MD5 | `C21C5600D1A9F0C43E7579B329947480`
SHA1 | `F9BAFCE7386ACC27E6EF492357D9D57EEE7874F5`
SHA256 | `88795DD89E4F3D7BDF4011846CFC863031D9217D7AB996A8ED8C488A1C73009F`
SHA384 | `F5AAFA9D9268D5FAFAB24F608FE3F37DD502BFE36E9305E9E3DC516A58545C52C8B65C9DCEA3BB772C3F7A670E1ED727`
SHA512 | `B544D2B9BC525974E3B951687228F5D6A2BEB8F391FCD9FFF3B32D2EE44EC4A8456C3FBC7C93B5F1CAA80B9E76E19E63EF12D8C7B0E7802AAD5A8635D7C1D52C`
SSDEEP | `6144:IqHAmk7jtxdElaoR3Ls10c8T4sJHJeAFVUQkM:IqZkX4aa3L+0c8T4e/VqM`

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

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gprslt.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `gpresult.exe` being misused. While `gpresult.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[stockpile](https://github.com/mitre/stockpile) | [5c4dd985-89e3-4590-9b57-71fed66ff4e2.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/5c4dd985-89e3-4590-9b57-71fed66ff4e2.yml) | `gpresult /R`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## gpresult

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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

- On ARM64 versions of Windows, only the `gpresult` in SysWow64 works with the `/h` parameter.

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



MIT License. Copyright (c) 2020-2021 Strontic.


