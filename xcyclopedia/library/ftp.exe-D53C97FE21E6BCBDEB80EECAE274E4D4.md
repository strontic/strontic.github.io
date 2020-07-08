---
title: ftp.exe | File Transfer Program
---

# ftp.exe 

* File Path: `C:\windows\system32\ftp.exe`
* Description: File Transfer Program

## Hashes

Type | Hash
-- | --
MD5 | `D53C97FE21E6BCBDEB80EECAE274E4D4`
SHA1 | `01A84CB1733048520C6E8E099C07F748DAB52648`
SHA256 | `D7FB0E7E7E6C653E0DB554433DFA6AAD8BE33B99431DD0A31E25943D0EFB91F0`
SHA384 | `367DFB74FD0EF20BDD9E1AE0C8D67349C08977B99BF64658A428CDFF981677FF62C1003F285ACB6E6F69FC835C3AE3F1`
SHA512 | `3B52296964D3FEEF5605F36B3D601660C9BE01FEBEED9DE8ECE5D70932C3E985995144A30F6B853C6EC69EC2A2B59D65634B207C255BFA59D81B2226567BB824`
SSDEEP | `1536:SL9q/bXmnLhUc+4p5obG48INnRDwCvGiLMYnw:SL9dZ+8pmnR0nv+w`

## Runtime Data

### Usage (stderr):
```Batchfile

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
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ftp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `ftp.exe` being misused. While `ftp.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Name: Ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `    Usecase: Spawn new process using ftp.exe. Ftp.exe runs cmd /C YourCommand` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `    Usecase: Spawn new process using ftp.exe. Ftp.exe downloads the binary.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `  - Path: C:\Windows\System32\ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `  - Path: C:\Windows\SysWOW64\ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | ` - IOC: cmd /c as child process of ftp.exe` | 

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## ftp

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

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

- [Additional FTP guidance](https://docs.microsoft.com/previous-versions/orphan-topics/ws.10/cc756013(v=ws.10))

- [IP version 6](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2003/cc738636(v=ws.10))

- [IPv6 applications](https://docs.microsoft.com/previous-versions/windows/it-pro/windows-server-2003/cc782509(v=ws.10))

---



MIT License. Copyright (c) 2020 Strontic.


