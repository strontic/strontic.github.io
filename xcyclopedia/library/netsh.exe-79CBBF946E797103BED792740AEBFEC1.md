
# netsh.exe 

* File Path: `C:\WINDOWS\system32\netsh.exe`
* Description: Network Command Shell
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `79CBBF946E797103BED792740AEBFEC1`
SHA1 | `E7A3B17F625283E3064D91A988D0B1694BA3E9B8`
SHA256 | `90F0822D26680C8FFD703A080C876F87695580747A3704C169E39E1A8802EA38`
SHA384 | `44C68D901D7ACC6DA54FE3AF8F06346C1A70FE9E0430B94F8F4D51AB205D47CE84E3C06BCF69898C08A9D55E1A3180E7`
SHA512 | `2898E00BB5796C3EA17828BC65ED05090F0F52CE0324AB67FCF6DBC8C5B45799BD1E7A6B6BDEE36ECBD54C96F41DE7CEB0C5DAA884B63D8CEA3763FE61076937`
SSDEEP | `1536:WHbGVLn6iQTaFs9DueVzrUXKsFxgpeb5A99s:ObGV7nQTAkieVzoXXFxgp22k`

## Runtime Data

### Usage (stdout):
```Batchfile

Usage: C:\WINDOWS\system32\netsh.exe [-a AliasFile] [-c Context] [-r RemoteMachine] [-u [DomainName\]UserName] [-p Password | *]
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
lan            - Changes to the `netsh lan' context.
mbn            - Changes to the `netsh mbn' context.
namespace      - Changes to the `netsh namespace' context.
netio          - Changes to the `netsh netio' context.
p2p            - Changes to the `netsh p2p' context.
ras            - Changes to the `netsh ras' context.
rpc            - Changes to the `netsh rpc' context.
set            - Updates configuration settings.
show           - Displays information.
trace          - Changes to the `netsh trace' context.
wcn            - Changes to the `netsh wcn' context.
wfp            - Changes to the `netsh wfp' context.
winhttp        - Changes to the `netsh winhttp' context.
winsock        - Changes to the `netsh winsock' context.
wlan           - Changes to the `netsh wlan' context.

The following sub-contexts are available:
 advfirewall branchcache bridge dhcpclient dnsclient firewall http interface ipsec lan mbn namespace netio p2p ras rpc trace wcn wfp winhttp winsock wlan

To view help for a command, type the command, followed by a space, and then
 type ?.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: netsh.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.




## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

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


