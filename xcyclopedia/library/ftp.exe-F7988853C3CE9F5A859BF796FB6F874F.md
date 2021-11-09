---
title: ftp.exe | File Transfer Program
excerpt: What is ftp.exe?
---

# ftp.exe 

* File Path: `C:\WINDOWS\SysWOW64\ftp.exe`
* Description: File Transfer Program

## Hashes

Type | Hash
-- | --
MD5 | `F7988853C3CE9F5A859BF796FB6F874F`
SHA1 | `B4CC545149E7ED406DC7EA281F767F814856E6DA`
SHA256 | `0EC78EA01CFA65E9F86410CEC82121113A0CD46B02E7ACE78A108C417444ACE6`
SHA384 | `4650D6A31C570FB6DA5CF56477B5BC72A386D62388DB1CD97919F815A91A9560DB7837F7472536C3E565B4C10F5B0FBF`
SHA512 | `F99B7554DC2523849728B3112900F2298EDA4E6F9EDD3D88D3FF73ABEF99CE83CE38B06E6A39D535577F91520A2E9DDBED4D97AEABB684B2CB89772404DF90B9`
SSDEEP | `1536:z8vesx7rwjQ9X57Wx7MEmIOU2hUMk71JawTujqoSyGEK:zwu1OtWfaBn`
IMP | `E31C220ED6451BFB3057109EF4AB4A4C`
PESHA1 | `1030655F7580E677E745862621C68E52766EA62F`
PE256 | `261EBC675A29010EA15DF8EF7975BE14CB26A46549FFCF0FD66144169270E480`

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
conhost.exe

### Open Handles:

Path | Type
-- | --
(RW-)   C:\Windows | File
(RW-)   C:\Windows\SysWOW64 | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000001.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\Sessions\2\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64cpu.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\ftp.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ftp.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/0ec78ea01cfa65e9f86410cec82121113a0cd46b02e7ace78a108c417444ace6/detection


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


