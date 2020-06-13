
# HOSTNAME.EXE 

* File Path: `C:\WINDOWS\system32\HOSTNAME.EXE`
* Description: Hostname APP
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `612DBA11F1DFAD1998609A647B740B34`
SHA1 | `C37511680B331D7CC1CC0DC32235CD233C7E5F0D`
SHA256 | `F88F37BFEFFC80D563B87AD6DE0F65D52D5760882013ABA5ECBE9FAD08D36777`
SHA384 | `60E56301C0010924AB98B00FE5C48B9A73FA29470949AEF638D2D0804C022D274A6DA6BA84DF1CE12E352BC270AEBAF6`
SHA512 | `C6077C31577FDB2011F4D2E7C1BCBB3983F2AE47D6BD7FA281E965E8C52DEDF27F712087F8F2ED77E50FB6AD9EB3C6AD2B03C453E1B6781C257025B35FF22D63`
SSDEEP | `192:0xyxH6lzKFc8rRYU861ds0ePdGXgoXabtwl4tWE6W:wyUuFTFP8cigAbtZWE6W`

## Runtime Data

### Usage (stdout):
```Batchfile

Prints the name of the current host.

hostname


```

### Usage (stderr):
```Batchfile
sethostname: Use the Network Control Panel Applet to set hostname.
hostname -s is not supported.

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: hostname.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Additional Info

*Source: [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs) by [Microsoft](https://opensource.microsoft.com/codeofconduct/), available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license. Some links modified.*

---

# hostname

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Displays the host name portion of the full computer name of the computer.

>[!IMPORTANT]
> This command is available only if the Internet Protocol (TCP/IP) protocol is installed as a component in the properties of a network adapter in Network.

## Syntax

```
hostname
```

### Parameters
| Parameter | Description |
| ------- | -------- |
| /? | Displays help at the command prompt. |

### Examples

To display the name of the computer, type:

```
hostname
```

## Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---


MIT License. Copyright (c) 2020 Strontic.


