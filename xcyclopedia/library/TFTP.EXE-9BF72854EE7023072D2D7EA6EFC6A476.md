---
title: TFTP.EXE | Trivial File Transfer Protocol App
---

# TFTP.EXE 

* File Path: `C:\windows\system32\TFTP.EXE`
* Description: Trivial File Transfer Protocol App

## Hashes

Type | Hash
-- | --
MD5 | `9BF72854EE7023072D2D7EA6EFC6A476`
SHA1 | `786F6E826DF8328B7D696E03EFD0BF242D994E18`
SHA256 | `11B755FFC5D2C622844EDB2528A46AD43CB61872BACB0F14B4D1631689EBFB8E`
SHA384 | `C6100F922C7B33354EC49961309DE3858448D152E37EDFD0C5B7A361188B8DC8A12BBD2EE5AB302DA2CFB6B179846424`
SHA512 | `F7EE5719F4A94287C3D64FF4B7B7B17D70B8AF2F5CB9EA82207E7F8F0C099AFF9237922616603548698AF86C3DA323FC698FB60AA14162167DB74AD2954BFE01`
SSDEEP | `384:xhDp0DZKITPyQk7Ex+WQGxjQS9Q/o6csdSo2lGlUQsmNCD1P2Q0284PWcBjW:xht0DVPzUoxnjxQ/o6cs8luNdNCD1P2O`

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\test.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: The file C:\windows\system32\TFTP.EXE is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: tftp.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
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


