---
title: TFTP.EXE | Trivial File Transfer Protocol App
---

# TFTP.EXE 

* File Path: `C:\Windows\system32\TFTP.EXE`
* Description: Trivial File Transfer Protocol App

## Hashes

Type | Hash
-- | --
MD5 | `F42A40D7DBC19BE5763F460E40819B90`
SHA1 | `257D9415260EDE38200AAA43BA2A9D9B97DC6754`
SHA256 | `FAFFA0EF7432859CC49FB39FD448C47735F1887B84EE87014330EBBE3BE05FBC`
SHA384 | `C47823646B2511427578C8C20FAB6B8F00BEA5F95C02E6F8A2A2A2F162B1BD2EDA9DF5E7DFC1DD7916F8E1C3906F0705`
SHA512 | `20FB0032F9DDE474488B136B8AC512761DDEBCEC22382E1A8E0530ECE4FA03035FB0B79FD99CCD1B6EC7BC98BA5AB4EC02572D7C9BAD967D5F543DCB58ED5B06`
SSDEEP | `768:LCBu/DB8PbDz0mVMRlpTrmOjTtCCzprfu:mBuV8wmORlpPmOjTHJfu`

## Runtime Data

### Usage (stderr):
```cmhg

Transfers files to and from a remote computer running the TFTP service.

TFTP [-i] host [GET | PUT] source [destination]

  -i              Specifies binary image transfer mode (also called
                  octet). In binary image mode the file is moved
                  literally, byte by byte. Use this mode when
                  transferring binary files.
  host            Specifies the local or remote host.
  GET             Transfers the file destination on the remote host to
                  the file source on the local host.
  PUT             Transfers the file source on the local host to
                  the file destination on the remote host.
  source          Specifies the file to transfer.
  destination     Specifies where to transfer the file.


```

## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: tftp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---
## tftp

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Transfers files to and from a remote computer, typically a computer running UNIX, that is running the Trivial File Transfer Protocol (tftp) service or daemon. tftp is typically used by embedded devices or systems that retrieve firmware, configuration information, or a system image during the boot process from a tftp server.

### Syntax
```
tftp [-i] [<Host>] [{get | put}] <Source> [<Destination>]
```

##### Parameters
|Parameter|Description|
|-------|--------|
|-i|Specifies binary image transfer mode (also called octet mode). In binary image mode, the file is transferred in one-byte units. Use this mode when transferring binary files. If **-i** is omitted, the file is transferred in ASCII mode. This is the default transfer mode. This mode converts the end-of-line (EOL) characters to an appropriate format for the specified computer. Use this mode when transferring text files. If a file transfer is successful, the data transfer rate is displayed.|
|\<Host\>|Specifies the local or remote computer.|
|put|Transfers the file *Source* on the local computer to the file *Destination* on the remote computer. Because the tftp protocol does not support user authentication, the user must be logged onto the remote computer, and the files must be writable on the remote computer.|
|get|Transfers the file *Destination* on the remote computer to the file *Source* on the local computer.|
|\<Source\>|Specifies the file to transfer.|
|\<Destination\>|Specifies where to transfer the file.|

### Remarks
-   You can install the tftp client using the add Features Wizard.
-   The tftp protocol does not support any authentication or encryption mechanism, and as such can introduce a security risk when present. Installing the tftp client is not recommended for systems connected to the Internet.
-   The tftp client is optional software, and marked as deprecated on Windows Vista and later versions of the Windows operating system. A tftp server service is no longer provided by Microsoft for security reasons.

### Examples
Copy the file **boot.img** from the remote computer **Host1**.
```
tftp  -i Host1 get boot.img
```

### Additional References
- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


