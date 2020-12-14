---
title: ftp.exe | File Transfer Program
excerpt: What is ftp.exe?
---

# ftp.exe 

* File Path: `C:\Windows\SysWOW64\ftp.exe`
* Description: File Transfer Program

## Hashes

Type | Hash
-- | --
MD5 | `F0707986208091066AFD2AB0A73D1693`
SHA1 | `3F79C30934FB96FAABE9DF828592F41280D394F2`
SHA256 | `BE279F10D7FF4C18D69724EF0EB04C91D8A34AAC0DB610E638B000991DFB8B02`
SHA384 | `580CCCCD3F91EDE1DFB91471C83C28018017E0680812CF19443C027DE2AD501DF24E726171909F4B23BDD24C9849020B`
SHA512 | `5D442EEB2E69B8CE6EFD8EB4302E4DC3E7B6EC0326C9F35965E299B130AAF8927769CB6BEB9B0B8D670D84B06824B0311EEFD8B0EACA9C56F1804E9592B874AF`
SSDEEP | `768:q9TSteOAJzRjbEm1kvWZhCwZeNyQbsVoSVzBHIeoG5BIFYB2BC4pOU5:qViejSWZYwZeNyqb0B7DIFxBC415`
IMP | `F76AC455BB3971C0CB2A43FDCD1FF525`
PESHA1 | `AF0B7487E479E952A6D7519DC6886E944E0F691F`
PE256 | `9E05810F224ECEBA50D8E128C7F2F54318342E3C79AC73CFFFA0B122AB90BBCB`

## Runtime Data

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
csrss.exe wininit.exe conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |
C:\Windows\SysWOW64\ftp.exe |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ftp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/be279f10d7ff4c18d69724ef0eb04c91d8a34aac0db610e638b000991dfb8b02/detection/


## Possible Misuse

*The following table contains possible examples of `ftp.exe` being misused. While `ftp.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Name: Ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Usecase: Spawn new process using ftp.exe. Ftp.exe runs cmd /C YourCommand` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `Usecase: Spawn new process using ftp.exe. Ftp.exe downloads the binary.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Path: C:\Windows\System32\ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Path: C:\Windows\SysWOW64\ftp.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- IOC: cmd /c as child process of ftp.exe` | 

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

- [Additional FTP guidance](/previous-versions/orphan-topics/ws.10/cc756013(v=ws.10))

- [IP version 6](/previous-versions/windows/it-pro/windows-server-2003/cc738636(v=ws.10))

- [IPv6 applications](/previous-versions/windows/it-pro/windows-server-2003/cc782509(v=ws.10))

---



MIT License. Copyright (c) 2020 Strontic.


