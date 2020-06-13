
# netsh.exe 

* File Path: `C:\Windows\SysWOW64\netsh.exe`
* Description: Network Command Shell
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C3542EE1B9198274179B797C9B2A4633`
SHA1 | `312578BD25DF2BF1AA93D55E1F8A3B4C8517F5C3`
SHA256 | `00B424FCE60E8C3ABB5BC05E2E1C4D86F14B07DB48D08660A5A7BB25FC9E3C23`
SHA384 | `7846E29C04ED86C2E1CC6E36B32EA7ADC10CF0AFB888675BE4A59EC58080E0D4DBA8A6E406BE39D1ECB1FB8B7BEB5558`
SHA512 | `56A8331CE370ABB55E60771BB5236105709E70D46E648D901B97F53E4DD6E83DAB4CF6CC73133B32A7909DF81A011C24C5895011174C345351C5F7BB23A7126F`
SSDEEP | `768:5MfVsa/qhZ4nlWDvrKlFhDjbb/hjZiL5IgmEc:C7/aS4Dv2jhDn5ZG5IgmEc`

## Runtime Data

### Usage (stdout):
```Batchfile

Usage: C:\Windows\SysWOW64\netsh.exe [-a AliasFile] [-c Context] [-r RemoteMachine] [-u [DomainName\]UserName] [-p Password | *]
             [Command | -f ScriptFile]

The following commands are available:

Commands in this context:
?              - Displays a list of commands.
add            - Adds a configuration entry to a list of entries.
advfirewall    - Changes to the `netsh advfirewall' context.
branchcache    - Changes to the `netsh branchcache' context.
bridge         - Changes to the `netsh bridge' context.
delete         - Deletes a configuration entry from a list of entries.
dhcpclient     - Changes to the `netsh dhcpclient' context.
dnsclient      - Changes to the `netsh dnsclient' context.
dump           - Displays a configuration script.
exec           - Runs a script file.
firewall       - Changes to the `netsh firewall' context.
help           - Displays a list of commands.
http           - Changes to the `netsh http' context.
interface      - Changes to the `netsh interface' context.
ipsec          - Changes to the `netsh ipsec' context.
ipsecdosprotection - Changes to the `netsh ipsecdosprotection' context.
lan            - Changes to the `netsh lan' context.
namespace      - Changes to the `netsh namespace' context.
netio          - Changes to the `netsh netio' context.
ras            - Changes to the `netsh ras' context.
rpc            - Changes to the `netsh rpc' context.
set            - Updates configuration settings.
show           - Displays information.
wfp            - Changes to the `netsh wfp' context.
winhttp        - Changes to the `netsh winhttp' context.
winsock        - Changes to the `netsh winsock' context.

The following sub-contexts are available:
 advfirewall branchcache bridge dhcpclient dnsclient firewall http interface ipsec ipsecdosprotection lan namespace netio ras rpc wfp winhttp winsock

To view help for a command, type the command, followed by a space, and then
 type ?.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `33000000BCE120FDD27CC8EE930000000000BC`
* Thumbprint: `E85459B23C232DB3CB94C7A56D47678F58E8E51E`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netsh.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# netsh

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2016

The Network Shell command-line scripting utility that allows you to, either locally or remotely, display or modify the network configuration of a currently running computer. You can start this utility at the command prompt or in Windows PowerShell.

## Syntax

```
netsh [-a <Aliasfile>][-c <Context>][-r <Remotecomputer>][-u [<domainname>\<username>][-p <Password> | [{<NetshCommand> | -f <scriptfile>}]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| -a `<Aliasfile>` | Specifies that you are returned to the netsh prompt after running Aliasfile and the name of the text file that contains one or more netsh commands. |
| -c `<Context>` | Specifies that netsh enters the specified netsh context and the netsh context to enter. |
| -r `<Remotecomputer>` | Specifies the remote computer to configure.<p>**Important:** If you use this parameter, you must make sure the Remote Registry service is running on the remote computer. If it isn't running, Windows displays a â€œNetwork Path Not Foundâ€ error message. |
| -u `<domainname>\<username>` | Specifies the domain and user account name to use while running the netsh command under a user account. If you omit the domain, the local domain is used by default. |
| -p `<Password>` | Specifies the password for the user account specified by the `-u <username>` parameter. |
| `<NetshCommand>` | Specifies the netsh command to run. |
| -f `<scriptfile>` | Exits the netsh command after running the specified script file. |
| /? | Displays help at the command prompt. |

#### Remarks

- If you specify **-r** followed by another command, netsh runs the command on the remote computer and then returns to the Cmd.exe command prompt. If you specify **-r** without another command, netsh opens in remote mode. The process is similar to using **set machine** at the Netsh command prompt. When you use **-r**, you set the target computer for the current instance of netsh only. After you exit and reenter netsh, the target computer is reset as the local computer. You can run netsh commands on a remote computer by specifying a computer name stored in WINS, a UNC name, an Internet name to be resolved by the DNS server, or an IP address.

- If your string value contains spaces between characters, you must enclose the string value in quotation marks. For example, `-r "contoso remote device"`

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


