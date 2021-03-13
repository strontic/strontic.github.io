---
title: nslookup.exe | nslookup
excerpt: What is nslookup.exe?
---

# nslookup.exe 

* File Path: `C:\Windows\system32\nslookup.exe`
* Description: nslookup

## Hashes

Type | Hash
-- | --
MD5 | `AD20D425C3012EE191535AD65E56DEBB`
SHA1 | `9A3BE34E8316EBB945A4D5818A4066C91FE98C95`
SHA256 | `54DAF167F8DBE7FE0F23B37A600BD8D9D16B756D3B83F0804B5037CBBE895EB6`
SHA384 | `3389C98384E113765999B5F313078BBF667BACC75C51A64AC80C11B23C428C2DBAE394EA350356CC6F37CAC7F98C6C0A`
SHA512 | `FC6C0C4CD72803F411F3E9BC30940B2C18C3EA3C5D692AEF7301EC13763D3EDFF341F341E0E2DDFD3A89FD1230FF7F0BB4196E9C548CE550216A79A73E14C25C`
SSDEEP | `768:3xx2FQe580dMI0GA4/YQFRWsWlYviTs3lvW22Mn1tZRyNXVkjheTFRYnM0qLdYG6:wazQFSI1j/cFRy9ydF9+5lK2hJLxf`
IMP | `F9A02896E71DF610AF20835CEAEF5BE9`
PESHA1 | `957A8337DBB7F3378EAE64EB17EED2842C6A08FF`
PE256 | `5ADB10A6860293DF7CFA3B66F22AF056DCFFF4818E28F273925539470489D1CA`

## Runtime Data

### Usage (stdout):
```cmhg
Default Server:  ip-172-31-0-2.us-east-2.compute.internal
Address:  172.31.0.2

> 
```

### Usage (stderr):
```cmhg
Usage:
   nslookup [-opt ...]             # interactive mode using default server
   nslookup [-opt ...] - server    # interactive mode using 'server'
   nslookup [-opt ...] host        # just look up 'host' using default server
   nslookup [-opt ...] host server # just look up 'host' using 'server'

```

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\nslookup.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\dhcpcsvc.DLL |
C:\Windows\SYSTEM32\dhcpcsvc6.DLL |
C:\Windows\system32\DNSAPI.dll |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\IMM32.DLL |
C:\Windows\SYSTEM32\IPHLPAPI.DLL |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\system32\MSWSOCK.dll |
C:\Windows\System32\NSI.dll |
C:\Windows\system32\nslookup.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\user32.dll |
C:\Windows\System32\win32u.dll |
C:\Windows\SYSTEM32\WINNSI.DLL |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: nslookup.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/54daf167f8dbe7fe0f23b37a600bd8d9d16b756d3b83f0804b5037cbbe895eb6/detection/


## Possible Misuse

*The following table contains possible examples of `nslookup.exe` being misused. While `nslookup.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_eda.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_eda.yml) | `- '$Command \| nslookup 2>&1 \| Out-String'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_chafer_mar18.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_chafer_mar18.yml) | `CommandLine: '*\nslookup.exe -q=TXT*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dnscat2_powershell_implementation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dnscat2_powershell_implementation.yml) | `description: The PowerShell implementation of DNSCat2 calls nslookup to craft queries. Counting nslookup processes spawned by PowerShell will show hundreds or thousands of instances if PS DNSCat2 is active locally.`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dnscat2_powershell_implementation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dnscat2_powershell_implementation.yml) | `Image\|endswith: '*\nslookup.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dnscat2_powershell_implementation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dnscat2_powershell_implementation.yml) | `CommandLine\|endswith: '*\nslookup.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_dnscat2_powershell_implementation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_dnscat2_powershell_implementation.yml) | `- Other powershell scripts that call nslookup.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_multiple_suspicious_cli.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_multiple_suspicious_cli.yml) | `- nslookup.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `- '*\nslookup.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_commands_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_commands_recon_activity.yml) | `- nslookup`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_execution_path_webserver.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_execution_path_webserver.yml) | `- Tools that include ping or nslookup command invocations`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #8: Remote System Discovery - nslookup [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #8: Remote System Discovery - nslookup [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | - [Atomic Test #8 - Remote System Discovery - nslookup](#atomic-test-8---remote-system-discovery---nslookup) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | ## Atomic Test #8 - Remote System Discovery - nslookup | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Powershell script that runs nslookup on cmd.exe against the local /24 network of the first network adaptor listed in ipconfig. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, powershell will identify the ip range (via ipconfig) and perform a for loop and execute nslookup against that IP range. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | foreach ($ip in 1..255 \| % { "$firstOctet.$secondOctet.$thirdOctet.$_" } ) {cmd.exe /c nslookup $ip} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_laudanum_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_laudanum_webshells.yar) | $s1 = "command = \"nslookup -type=\" & qtype & \" \" & query " fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $ = "nslookup" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [ce485320-41a4-42e8-a510-f5a8fe96a644.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/ce485320-41a4-42e8-a510-f5a8fe96a644.yml) | `(nslookup -querytype=mx #{target.org.domain}. \| Select-String -pattern 'mail' \| Out-String).Trim()`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [fa4ed735-7006-4451-a578-b516f80e559f.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/fa4ed735-7006-4451-a578-b516f80e559f.yml) | `name: Reverse nslookup IP`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [fa4ed735-7006-4451-a578-b516f80e559f.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/discovery/fa4ed735-7006-4451-a578-b516f80e559f.yml) | `nslookup #{remote.host.ip}`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## nslookup

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays information that you can use to diagnose Domain Name System (DNS) infrastructure. Before using this tool, you should be familiar with how DNS works. The nslookup command-line tool is available only if you have installed the TCP/IP protocol.

The nslookup command-line tool has two modes: interactive and noninteractive.

If you need to look up only a single piece of data, we recommend using the non-interactive mode. For the first parameter, type the name or IP address of the computer that you want to look up. For the second parameter, type the name or IP address of a DNS name server. If you omit the second argument, **nslookup** uses the default DNS name server.

If you need to look up more than one piece of data, you can use interactive mode. Type a hyphen (-) for the first parameter and the name or IP address of a DNS name server for the second parameter. If you omit both parameters, the tool uses the default DNS name server. While using the interactive mode, you can:

- Interrupt interactive commands at any time, by pressing CTRL+B.

- Exit, by typing **exit**.

- Treat a built-in command as a computer name, by preceding it with the escape character (\). An unrecognized command is interpreted as a computer name.

### Syntax

```
nslookup [exit | finger | help | ls | lserver | root | server | set | view] [options]
```

#### Parameters

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

#### Remarks

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

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


