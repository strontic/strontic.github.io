---
title: gpresult.exe | Query Group Policy RSOP Data
excerpt: What is gpresult.exe?
---

# gpresult.exe 

* File Path: `C:\WINDOWS\SysWOW64\gpresult.exe`
* Description: Query Group Policy RSOP Data

## Hashes

Type | Hash
-- | --
MD5 | `4B3389505013792F5240E8A1F65F5B53`
SHA1 | `CA81910B56560E47398D978B97F8997E731CB6FA`
SHA256 | `1A3B87C401395223DF6645D1F2E1EA40C6CAF2DBD474CC5F7EB7D38E8571B7FC`
SHA384 | `14E4651DAD69CF3AAB410C911816B7C149D0B7AF5E4A1B600E6BEFEC6EDBDAC98786FE991D4211ECA19C41B61C8C2C0D`
SHA512 | `90F53BD238A4CFEDA20C32121FB03B048EDEF2155DB489C433A4679921B77C5A8FF91F02C813B93B1DAACA746EA12F6B1CEBA36C246396005AD914EF2DF13FC0`
SSDEEP | `3072:Bm+r+Zvkm56rYXLrXOHRzFOGbPDeS5ND8ntQ8cd0vtulcZsfgMhWwoMec5cyA:Bml62yHRMGHV8MJlcoh+Mj/A`
IMP | `322014C1AB0A6DC11B69439769785755`
PESHA1 | `78234FDB73ABCF773D2DEE20020B15CBFD96B144`
PE256 | `74B4406CB97A29B447679B974151737D88222EF765882B1F927CFA0C76837579`

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
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\gpresult.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: gprslt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/1a3b87c401395223df6645d1f2e1ea40c6caf2dbd474cc5f7eb7d38e8571b7fc/detection


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


