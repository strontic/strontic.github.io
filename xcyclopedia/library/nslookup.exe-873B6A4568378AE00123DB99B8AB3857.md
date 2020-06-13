
# nslookup.exe 

* File Path: `C:\WINDOWS\system32\nslookup.exe`
* Description: nslookup
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `873B6A4568378AE00123DB99B8AB3857`
SHA1 | `784821A41DFE25E66DF7672D28B97F1BB4138E6B`
SHA256 | `7FF4539922EADCFF60675FC1A07FDECA8DECB2E1FAFF4A9478E5FAE51C71D505`
SHA384 | `78D4FBE607725F5332E134F2FC2DF2FD5B79C227CE1C9A40A077346067946671C1C15BE0B9B0FF51F2E8465171668313`
SHA512 | `BBE6F86E90D28BB177A6A8BFC579598A41E73D02778EAE59DD41014FD24B14B0D0A53D6587A806EA4F46AEAAB0F8081C033C85D4E731E8858BD70F59C5991C74`
SSDEEP | `1536:WOdNjLmD53XAWeW6Mhydn4tO4oOlkvzxz:WktLS5gWt0B444ocwz`

## Runtime Data

### Usage (stdout):
```Batchfile
Server:  UnKnown
Address:  1.1.1.1

Name:    help.


```

### Usage (stderr):
```Batchfile
Usage:
   nslookup [-opt ...]             # interactive mode using default server
   nslookup [-opt ...] - server    # interactive mode using 'server'
   nslookup [-opt ...] host        # just look up 'host' using default server
   nslookup [-opt ...] host server # just look up 'host' using 'server'

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

* Original Filename: nslookup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# nslookup

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information that you can use to diagnose Domain Name System (DNS) infrastructure. Before using this tool, you should be familiar with how DNS works. The nslookup command-line tool is available only if you have installed the TCP/IP protocol.

The nslookup command-line tool has two modes: interactive and noninteractive.

If you need to look up only a single piece of data, we recommend using the non-interactive mode. For the first parameter, type the name or IP address of the computer that you want to look up. For the second parameter, type the name or IP address of a DNS name server. If you omit the second argument, **nslookup** uses the default DNS name server.

If you need to look up more than one piece of data, you can use interactive mode. Type a hyphen (-) for the first parameter and the name or IP address of a DNS name server for the second parameter. If you omit both parameters, the tool uses the default DNS name server. While using the interactive mode, you can:

- Interrupt interactive commands at any time, by pressing CTRL+B.

- Exit, by typing **exit**.

- Treat a built-in command as a computer name, by preceding it with the escape character (\). An unrecognized command is interpreted as a computer name.

## Syntax

```
nslookup [exit | finger | help | ls | lserver | root | server | set | view] [options]
```

### Parameters

| Parameter | Description |
| --------- | ----------- |
| [nslookup exit](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-exit-command.md) | Exits the nslookup command-line tool. |
| [nslookup finger](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-finger-command.md) | Connects with the finger server on the current computer. |
| [nslookup help](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-help.md) | Displays a short summary of subcommands. |
| [nslookup ls](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-ls.md) | Lists information for a DNS domain. |
| [nslookup lserver](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-lserver.md) | Changes the default server to the specified DNS domain. |
| [nslookup root](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-root.md) | Changes the default server to the server for the root of the DNS domain name space. |
| [nslookup server](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-server.md) | Changes the default server to the specified DNS domain. |
| [nslookup set](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set.md) | Changes configuration settings that affect how lookups function. |
| [nslookup set all](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-all.md) | Prints the current values of the configuration settings. |
| [nslookup set class](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-class.md) | Changes the query class. The class specifies the protocol group of the information. |
| [nslookup set d2](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-d2.md) | Turns exhaustive Debugging mode on or off. All fields of every packet are printed. |
| [nslookup set debug](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-debug.md) | Turns Debugging mode on or off. |
| [nslookup set domain](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-domain.md) | Changes the default DNS domain name to the name specified. |
| [nslookup set port](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-port.md) | Changes the default TCP/UDP DNS name server port to the value specified. |
| [nslookup set querytype](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-querytype.md) | Changes the resource record type for the query. |
| [nslookup set recurse](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-recurse.md) | Tells the DNS name server to query other servers if it doesn't have the information. |
| [nslookup set retry](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-retry.md) | Sets the number of retries. |
| [nslookup set root](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-root.md) | Changes the name of the root server used for queries. |
| [nslookup set search](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-search.md) | Appends the DNS domain names in the DNS domain search list to the request until an answer is received. This applies when the set and the lookup request contain at least one period, but do not end with a trailing period. |
| [nslookup set srchlist](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-srchlist.md) | Changes the default DNS domain name and search list. |
| [nslookup set timeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-timeout.md) | Changes the initial number of seconds to wait for a reply to a request. |
| [nslookup set type](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-type.md) | Changes the resource record type for the query. |
| [nslookup set vc](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-vc.md) | Specifies to use or not use a virtual circuit when sending requests to the server. |
| [nslookup view](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-view.md) | Sorts and lists the output of the previous **ls** subcommand or commands. |

### Remarks

- If *computerTofind* is an IP address and the query is for an **A** or **PTR** resource record type, the name of the computer is returned.

- If *computerTofind* is a name and doesn't have a trailing period, the default DNS domain name is appended to the name. This behavior depends on the state of the following **set** subcommands: **domain**, **srchlist**, **defname**, and **search**.

- If you type a hyphen (-) instead of *computerTofind*, the command prompt changes to **nslookup** interactive mode.

- If the lookup request fails, the command-line tool provides an error message, including:

  | Error message | Description |
  | ------------- | ----------- |
  | timed out |The server didn't respond to a request after a certain amount of time and a certain number of retries. You can set the time-out period with the [nslookup set timeout](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-timeout.md) command. You can set the number of retries with the [nslookup set retry](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-retry.md) command. |
  | No response from server | No DNS name server is running on the server computer. |
  | No records | The DNS name server doesn't have resource records of the current query type for the computer, although the computer name is valid. The query type is specified with the [nslookup set querytype](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/nslookup-set-querytype.md) command. |
  | Nonexistent domain | The computer or DNS domain name doesn't exist. |
  | Connection refused or Network is unreachable | The connection to the DNS name server or finger server could not be made. This error commonly occurs with the **ls** and **finger** requests. |
  | Server failure | The DNS name server found an internal inconsistency in its database and could not return a valid answer. |
  | Refused | The DNS name server refused to service the request. |
  | format error | The DNS name server found that the request packet was not in the proper format. It may indicate an error in **nslookup**. |

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


