﻿---
title: ftp.exe | File Transfer Program
excerpt: What is ftp.exe?
---

# ftp.exe 

* File Path: `C:\WINDOWS\SysWOW64\ftp.exe`
* Description: File Transfer Program

## Hashes

Type | Hash
-- | --
MD5 | `8149085604E1B1D9C7872E619F5B0D52`
SHA1 | `B6DAB50D22BF997B37B25CD6C2EB95BC6332A455`
SHA256 | `A0A27B65B1359B659568ED59637F36F216377A7F2066D15DB5BE7024EB48863D`
SHA384 | `0F3D48CCC3B743C930C475B107B7D81658C09E70722557B33F565C19166060171FB977E38065078E416A76342A34539B`
SHA512 | `56F9B929F5D891112D3BFC9AA83279890FA15B8E36BD8EE2464D44EDC8C7895636262927B128E60C0427A37AFD7C8CD2839FB144956CA684B5DDDF4A03893E8C`
SSDEEP | `768:h0E/x9/S+KW2626a6tWZa2ZeNmrhRf3qjmVeD6f2/Dd7/BaB5BW3iI:SIrMKWZxZeNmEJtDdUB5Ep`

## Runtime Data

### Usage (stdout):
```cmhg
Unknown host help.
ftp> 
```

### Usage (stderr):
```cmhg

Transfers files to and from a computer running an FTP server service
(sometimes called a daemon). Ftp can be used interactively.

FTP [-v] [-d] [-i] [-n] [-g] [-s:filename] [-a] [-A] [-x:sendbuffer] [-r:recvbuffer] [-b:asyncbuffers] [-w:windowsize] [host]

  -v              Suppresses display of remote server responses.
  -n              Suppresses auto-login upon initial connection.
  -i              Turns off interactive prompting during multiple file
                  transfers.
  -d              Enables debugging.
  -g              Disables filename globbing (see GLOB command).
  -s:filename     Specifies a text file containing FTP commands; the
                  commands will automatically run after FTP starts.
  -a              Use any local interface when binding data connection.
  -A              login as anonymous.
  -x:send sockbuf Overrides the default SO_SNDBUF size of 8192.
  -r:recv sockbuf Overrides the default SO_RCVBUF size of 8192.
  -b:async count  Overrides the default async count of 3
  -w:windowsize   Overrides the default transfer buffer size of 65535.
  host            Specifies the host name or IP address of the remote
                  host to connect to.

Notes:
  - mget and mput commands take y/n/q for yes/no/quit.
  - Use Control-C to abort commands.

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

* Original Filename: ftp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `ftp.exe` being misused. While `ftp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ftp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ftp.yml) | `title: Suspicious ftp.exe `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ftp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ftp.yml) | `description: Detects renamed ftp.exe, ftp.exe script execution and child processes ran by ftp.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ftp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ftp.yml) | `Image\|endswith: 'ftp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ftp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ftp.yml) | `OriginalFileName\|contains: 'ftp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_ftp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_ftp.yml) | `ParentImage\|endswith: 'ftp.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Name: Ftp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Usecase: Spawn new process using ftp.exe. Ftp.exe runs cmd /C YourCommand`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Usecase: Spawn new process using ftp.exe. Ftp.exe downloads the binary.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Path: C:\Windows\System32\ftp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Path: C:\Windows\SysWOW64\ftp.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- IOC: cmd /c as child process of ftp.exe`{:.highlight .language-yaml} | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ftp

>Applies to: Windows Server 2022, Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Transfers files to and from a computer running a File Transfer Protocol (ftp) server service. This command can be used interactively or in batch mode by processing ASCII text files.

### Syntax

```
ftp [-v] [-d] [-i] [-n] [-g] [-s:<filename>] [-a] [-A] [-x:<sendbuffer>] [-r:<recvbuffer>] [-b:<asyncbuffers>][-w:<windowssize>][<host>] [-?]
```

#### Parameters

| Parameter | Description |
| ----------| ----------- |
| -v | Suppresses display of remote server responses. |
| -d | Enables debugging, displaying all commands passed between the FTP client and FTP server. |
| -i | Disables interactive prompting during multiple file transfers. |
| -n | Suppresses auto-login upon initial connection. |
| -g | Disables file name globbing.  **Glob** permits the use of the asterisk (*) and question mark (?) as wildcard characters in local file and path names. |
| -s:`<filename>` | Specifies a text file that contains **ftp** commands. These commands run automatically after **ftp** starts. This parameter allows no spaces. Use this parameter instead of redirection (`<`). **Note:** In Windows 8 and  Windows Server 2012  or later operating systems, the text file must be written in UTF-8. |
| -a | Specifies that any local interface can be used when binding the ftp data connection. |
| -A | Logs onto the ftp server as anonymous. |
| -x:`<sendbuffer> `| Overrides the default SO_SNDBUF size of 8192. |
| -r:`<recvbuffer>` | Overrides the default SO_RCVBUF size of 8192. |
| -b:`<asyncbuffers>` | Overrides the default async buffer count of 3. |
| -w:`<windowssize>` | Specifies the size of the transfer buffer. The default window size is 4096 bytes. |
| `<host>` | Specifies the computer name, IP address, or IPv6 address of the ftp server to which to connect. The host name or address, if specified, must be the last parameter on the line. |
| -? | Displays help at the command prompt. |

##### Remarks

- The **ftp** command-line parameters are case-sensitive.

- This command is available only if the **Internet Protocol (TCP/IP)** protocol is installed as a component in the properties of a network adapter in Network Connections.

- The **ftp** command can be used interactively. After it is started, **ftp** creates a sub-environment in which you can use **ftp** commands. You can return to the command prompt by typing the **quit** command. When the **ftp** sub-environment is running, it is indicated by the `ftp >` command prompt. For more information, see the **ftp** commands.

- The **ftp** command supports the use of IPv6 when the IPv6 protocol is installed.

#### Examples

To log on to the ftp server named `ftp.example.microsoft.com`, type:

```
ftp ftp.example.microsoft.com
```

To log on to the ftp server named `ftp.example.microsoft.com` and run the **ftp** commands contained in a file named *resync.txt*, type:

```
ftp -s:resync.txt ftp.example.microsoft.com
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Additional FTP guidance](/previous-versions/orphan-topics/ws.10/cc756013(v=ws.10))

- [IP version 6](/previous-versions/windows/it-pro/windows-server-2003/cc738636(v=ws.10))

- [IPv6 applications](/previous-versions/windows/it-pro/windows-server-2003/cc782509(v=ws.10))

---



MIT License. Copyright (c) 2020-2021 Strontic.


