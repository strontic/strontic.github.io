---
title: prndrvr.vbs | 
excerpt: What is prndrvr.vbs?
---

# prndrvr.vbs 

* File Path: `C:\Windows\system32\Printing_Admin_Scripts\en-US\prndrvr.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `B8B837D76A848A135BBCCE619585B312`
SHA1 | `6D7BF95D31AD0FF82888A0CD5FB861BEC54750B4`
SHA256 | `874C672CD5A9291529F461BF0A28B933D1D5D076073D1D88ABC3E249423B2156`
SHA384 | `DC518AA97038489BFEEEB1F6B1107ED3BA291E8C623D3CE24616C997C91916AFDB54A7565233EE822586ACE98EB5416D`
SHA512 | `9682062A589B8C9C6737288158B7A1F05EB9DC375CEC9AA802F9965A11FF2AE981E335F39259D90F3423069A53871FD91456041E1F735D5147C00472B9A121C2`
SSDEEP | `1536:VYbdy4c+n2cLKxLJi/rCsSRaCYuGgseNDmXYugjAezgMEZVXbbu6VuoDySWXPjs:VYbdHznXmxLJIrCsS4CYuGgseNyXYuge`
PESHA1 | `6D7BF95D31AD0FF82888A0CD5FB861BEC54750B4`
PE256 | `874C672CD5A9291529F461BF0A28B933D1D5D076073D1D88ABC3E249423B2156`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prndrvr [-adlx?] [-m model][-v version][-e environment][-s server]
               [-u user name][-w password][-h path][-i inf file]
Arguments:
-a     - add the specified driver
-d     - delete the specified driver
-e     - environment  "Windows {NT x86 | X64 | IA64}"
-h     - driver file path
-i     - fully qualified inf file name
-l     - list all drivers
-m     - driver model name
-s     - server name
-u     - user name
-v     - version
-w     - password
-x     - delete all drivers that are not in use
-?     - display command usage

Examples:
prndrvr -a -m "driver" -v 3 -e "Windows NT x86"
prndrvr -d -m "driver" -v 3 -e "Windows x64"
prndrvr -a -m "driver" -v 3 -e "Windows IA64" -i c:\temp\drv\drv.inf -h c:\temp\drv
prndrvr -l -s server
prndrvr -x -s server
Remarks:
The inf file name must be fully qualified. If the inf name is not specified, the script uses
one of the inbox printer inf files in the inf subdirectory of the Windows directory.
If the driver path is not specified, the script searches for driver files in the driver.cab file.

The -x option deletes all additional printer drivers (drivers installed for use on clients running
alternate versions of Windows), even if the primary driver is in use. If the fax component is installed,
this option deletes any additional fax drivers. The primary fax driver is also deleted if it is not
in use (i.e. if there is no queue using it). If the primary fax driver is deleted, the only way to
re-enable fax is to reinstall the fax component.

```

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\cscript.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/874c672cd5a9291529f461bf0a28b933d1d5d076073d1d88abc3e249423b2156/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prndrvr.vbs](prndrvr.vbs-E1187FCA414B43779D91B7545FEBBA03.md) | 97


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prndrvr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Adds, deletes, and lists printer drivers. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prndrvr file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prndrvr`.

Used without parameters, **prndrvr** displays command-line help.

### Syntax

```
cscript prndrvr {-a | -d | -l | -x | -?} [-m <model>] [-v {0|1|2|3}] [-e <environment>] [-s <Servername>] [-u <Username>] [-w <password>] [-h <path>] [-i <inf file>]
```

#### Parameters

| Parameter | Description |
|--|--|
| -a | Installs a driver. |
| -d | Deletes a driver. |
| -l | Lists all printer drivers installed on the server specified by the **-s** parameter. If you don't specify a server, Windows lists the printer drivers installed on the local computer. |
| -x | Deletes all printer drivers and additional printer drivers not in use by a logical printer on the server specified by the **-s** parameter. If you don't specify a server to remove from the list, Windows deletes all unused printer drivers on the local computer. |
| -m `<model_name>` | Specifies (by name) the driver you want to install. Drivers are often named for the model of printer they support. See the printer documentation for more information. |
| `-v {0|1|2|3}` | Specifies the version of the driver you want to install. See the description of the **-e**parameter for information on which versions are available for which environment. If you don't specify a version, the version of the driver appropriate for the version of Windows running on the computer where you are installing the driver is installed. |
| -e `<environment>` | Specifies the environment for the driver you want to install. If you don't specify an environment, the environment of the computer where you are installing the driver is used. The supported environment parameters are: **Windows NT x86**, **Windows x64** or **Windows IA64**. |
| -s `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| -h `<path>` | Specifies the path to the driver file. If you don't specify a path, the path to the location where Windows was installed is used. |
| -i `<filename.inf>` | Specifies the complete path and file name for the driver you want to install. If you don't specify a file name, the script uses one of the inbox printer .inf files in the inf subdirectory of the Windows directory.<p>if the driver path is not specified, the script searches for driver files in the driver.cab file. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

- The **-x** parameter deletes all additional printer drivers (drivers installed for use on clients running alternate versions of Windows), even if the primary driver is in use. If the fax component is installed, this option also deletes fax drivers. The primary fax driver is deleted if it is not in use (that is, if there is no queue using it). If the primary fax driver is deleted, the only way to re-enable fax is to reinstall the fax component.

#### Examples

To list all drivers on the local \\printServer1 server, type:

```
cscript prndrvr -l -s
```

To add a version 3 Windows x64 printer driver for the Laser printer model 1 model of printer using the c:\temp\Laserprinter1.inf driver information file for a driver stored in the c:\temp folder, type:

```
cscript prndrvr -a -m Laser printer model 1 -v 3 -e Windows x64 -i c:\temp\Laserprinter1.inf -h c:\temp
```

To delete a version 3 Windows x64 printer driver for Laser printer model 1, type:

```
cscript prndrvr -a -m Laser printer model 1 -v 3 -e Windows x64
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


