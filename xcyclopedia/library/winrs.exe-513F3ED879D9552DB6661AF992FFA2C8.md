﻿---
title: winrs.exe | winrs
excerpt: What is winrs.exe?
---

# winrs.exe 

* File Path: `C:\WINDOWS\system32\winrs.exe`
* Description: winrs

## Hashes

Type | Hash
-- | --
MD5 | `513F3ED879D9552DB6661AF992FFA2C8`
SHA1 | `A074788FD13B12EE7281B90A5B0AF72A572F073B`
SHA256 | `700ACD72EBC15130B66048B7E7D3282A17A8ABA24092D871620955883A1160A6`
SHA384 | `943BD99942ABCFCD2277CDE3400E26A8675640D652C5439E1055BC51E713843A271B7243DAD854EE0F0C707773FEB133`
SHA512 | `30DDA0CD2AB5FDE674265FB2E676821EAE10BF24603EAE2C72B8186C6A21665B1EDC95338A262246CFF6F6E2DCA2A58C1D9DF4B4AB4B39DDD98ABB73267071A5`
SSDEEP | `768:OoP5b7LATPN2avUphn9VXvN2XChn4OwGwBO8DIDp+z9ecMmkSx+Bz6lqrzit:b3gPN2acphn9yXCa5OBDpk4mk5it`

## Runtime Data

### Usage (stdout):
```cmhg

USAGE
=====
(ALL UPPER-CASE = value that must be supplied by user.)

winrs [-/SWITCH[:VALUE]] COMMAND

COMMAND - Any string that can be executed as a command in the cmd.exe shell.

SWITCHES
========
(All switches accept both short form or long form. For example both -r and 
-remote are valid.)

-r[emote]:ENDPOINT      - The target endpoint using a NetBIOS name or the standard connection URL: [TRANSPORT://]TARGET[:PORT]. If not specified 
-r:localhost is used.

-un[encrypted]          - Specify that the messages to the remote shell will not be encrypted. This is useful for troubleshooting, or when the network traffic is already encrypted using ipsec, or when physical security is enforced. By default the messages are encrypted using Kerberos or NTLM keys. This switch is ignored when HTTPS transport is selected. 

-u[sername]:USERNAME    - Specify username on command line. If not specified the tool will use Negotiate authentication or prompt for the name. 
If -username is specified, -password must be as well.

-p[assword]:PASSWORD    - Specify password on command line. If -password is not specified but -username is the tool will prompt for the password. If -password is specified, -user must be specified as well.

-t[imeout]:SECONDS      - This option is deprecated. 

-d[irectory]:PATH       - Specifies starting directory for remote shell. If not specified the remote shell will start in the user's home directory defined by the environment variable %USERPROFILE%.

-env[ironment]:STRING=VALUE   - Specifies a single environment variable to be set when shell starts, which allows changing default environment for shell. Multiple occurrences of this switch must be used to specify multiple environment variables.

-noe[cho]               - Specifies that echo should be disabled. This may be necessary to ensure that user's answers to remote prompts are not displayed locally. By default echo is "on".

-nop[rofile]            - Specifies that the user's profile should not be loaded. By default the server will attempt to load the user profile. If the remote user is not a local administrator on the target system then this option will be required (the default will result in error).

-a[llow]d[elegate]      - Specifies that the user's credentials can be used to access a remote share, for example, found on a different machine than the target endpoint.

-comp[ression]          - Turn on compression.  Older installations on remote machines may not support compression so it is off by default.

-[use]ssl               - Use an SSL connection when using a remote endpoint.  Specifying this instead of the transport "https:" will use the default WinRM default port. 

-?                      - Help

To terminate the remote command the user can type Ctrl-C or Ctrl-Break, which will be sent to the remote shell. The second Ctrl-C will force termination of winrs.exe.

To manage active remote shells or WinRS configuration, use the WinRM tool.  The URI alias to manage active shells is shell/cmd.  The URI alias for WinRS configuration is winrm/config/winrs.  Example usage can be found in the WinRM tool by typing "WinRM -?".

Examples:
winrs -r:https://myserver.com command
winrs -r:myserver.com -usessl command
winrs -r:myserver command
winrs -r:http://127.0.0.1 command
winrs -r:http://169.51.2.101:80 -unencrypted command
winrs -r:https://[::FFFF:129.144.52.38] command
winrs -r:http://[1080:0:0:0:8:800:200C:417A]:80 command
winrs -r:https://myserver.com -t:600 -u:administrator -p:$%fgh7 ipconfig
winrs -r:myserver -env:PATH=^%PATH^%;c:\tools -env:TEMP=d:\temp config.cmd
winrs -r:myserver netdom join myserver /domain:testdomain /userd:johns /passwordd:$%fgh789
winrs -r:myserver -ad -u:administrator -p:$%fgh7 dir \\anotherserver\share

```

### Usage (stderr):
```cmhg
Winrs.exe: Unrecognized switch "/h"
Use "winrs -?" to obtain the usage information
```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: winrs.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `winrs.exe` being misused. While `winrs.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_logon_explicit_credentials.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_logon_explicit_credentials.yml) | `- '\winrs.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## winrs

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Windows remote Management allows you to manage and execute programs remotely.
### Syntax
```
winrs [/<parameter>[:<value>]] <command>
```
##### Parameters

|           Parameter            |                                                                                                                                                                                    Description                                                                                                                                                                                     |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|      /remote:\<endpoint>       |                                                                                          Specifies the target endpoint using a NetBIOS name or the standard connection:<p>-   \<url\>: [\<transport>://]\<target>[:\<port>]<p>if not specified, **/r:localhost** is used.                                                                                          |
|          /unencrypted          | Specifies that the messages to the remote shell will not be encrypted. This is useful for troubleshooting or when the network traffic is already encrypted using **ipsec**, or when physical security is enforced.<p>By default, the messages are encrypted using Kerberos or NTLM keys.<p>This command-line option is ignored when HTTPS transport is selected. |
|     /username:\<username>      |                                                                                Specifies username on command line.<p>if not specified, the tool will use Negotiate authentication or prompt for the name.<p>if **/username** is specified, **/password** must also be specified.                                                                                 |
|     /password:\<password>      |                                                                           Specifies password on command line.<p>if **/password** is not specified but **/username** is, the tool will prompt for the password.<p>if **/password** is specified, **/username** must also be specified.                                                                            |
|      /timeout:\<seconds>       |                                                                                                                                                                             This option is deprecated.                                                                                                                                                                             |
|       /directory:\<path>       |                                                                                            Specifies starting directory for remote shell.<p>if not specified, the remote shell will start in the user's home directory defined by the environment variable **%USERPROFILE%**.                                                                                             |
| /environment:\<string>=\<value\> |                                                                          Specifies a single environment variable to be set when shell starts, which allows changing default environment for shell.<p>Multiple occurrences of this switch must be used to specify multiple environment variables.                                                                          |
|            /noecho             |                                                                                                    Specifies that echo should be disabled. This may be necessary to ensure that user's answers to remote prompts are not displayed locally.<p>By default echo is on.                                                                                                    |
|           /noprofile           |                                              Specifies that the user's profile should not be loaded.<p>By default, the server will attempt to load the user profile.<p>if the remote user is not a local administrator on the target system, then this option will be required (the default will result in error).                                               |
|         /allowdelegate         |                                                                                                                  Specifies that the user's credentials can be used to access a remote share, for example, found on a different machine than the target endpoint.                                                                                                                   |
|          /compression          |                                                                           Turn on compression.  Older installations on remote machines may not support compression so it is off by default.<p>Default setting is off, since older installations on remote machines may not support compression.                                                                           |
|            /usessl             |                                                                                                               Use an SSL connection when using a remote endpoint.  Specifying this instead of the transport **https:** will use the default **WinRM** default port.                                                                                                                |
|               /?               |                                                                                                                                                                        Displays help at the command prompt.                                                                                                                                                                        |

### Remarks
-   All command-line options accept either short form or long form. For example both **/r** and **/remote** are valid.
-   To terminate the **/remote** command, the user can type **Ctrl-C** or **Ctrl-break**, which will be sent to the remote shell. The second **Ctrl-C** will force termination of **winrs.exe**.
-   To manage active remote shells or winrs configuration, use the WinRM tool.  The URI alias to manage active shells is **shell/cmd**.  The URI alias for winrs configuration is **winrm/config/winrs**.

### Examples
```
winrs /r:https://contoso.com command
```
```
winrs /r:contoso.com /usessl command
```
```
winrs /r:myserver command
```
```
winrs /r:http://127.0.0.1 command
```
```
winrs /r:http://169.51.2.101:80 /unencrypted command
```
```
winrs /r:https://[::FFFF:129.144.52.38] command
```
```
winrs /r:http://[1080:0:0:0:8:800:200C:417A]:80 command
```
```
winrs /r:https://contoso.com /t:600 /u:administrator /p:$%fgh7 ipconfig
```
```
winrs /r:myserver /env:path=^%path^%;c:\tools /env:TEMP=d:\temp config.cmd
```
```
winrs /r:myserver netdom join myserver /domain:testdomain /userd:johns /passwordd:$%fgh789
```
```
winrs /r:myserver /ad /u:administrator /p:$%fgh7 dir \\anotherserver\share
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)


---



MIT License. Copyright (c) 2020-2021 Strontic.


