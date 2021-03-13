---
title: prnmngr.vbs | 
excerpt: What is prnmngr.vbs?
---

# prnmngr.vbs 

* File Path: `C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnmngr.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `65FC1A4445EA44AA1DCA130BE37CEDD1`
SHA1 | `C10B48120727BDC3B8155F21B5813E7EA0C6416E`
SHA256 | `D6B5C6BEB1F0242D0A8E224D23ACADC56D503FC4B0552022856E77FF1E84C5D1`
SHA384 | `46419EE6D4953B543660CE864EC64C36867FCC96812972849D98645108D488AB90022C8645560DA0A4A0EB9E8DAEBD73`
SHA512 | `C0C0740A7B1DB9D795D5DF1E8C9EAC78DB2D20ECCFE679D113CD240A2A7F9E0535190C320CC28EFA461119DE8517DC2EB2F95BDC91F5CD0C6D118E6129457B06`
SSDEEP | `1536:e63LRV0ubIGkikGkFjGkikGkKEt0eEKU+kCKGWGPrbrbTDDpOAWGPrbrbTDDpDFk:pVJAtg`
PESHA1 | `C10B48120727BDC3B8155F21B5813E7EA0C6416E`
PE256 | `D6B5C6BEB1F0242D0A8E224D23ACADC56D503FC4B0552022856E77FF1E84C5D1`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prnmngr [-adxgtl?][c] [-s server][-p printer][-m driver model]
               [-r port][-u user name][-w password]
Arguments:
-a     - add local printer
-ac    - add printer connection
-d     - delete printer
-g     - get the default printer
-l     - list printers
-m     - driver model
-p     - printer name
-r     - port name
-s     - server name
-t     - set the default printer
-u     - user name
-w     - password
-x     - delete all printers
-xc    - delete all printer connections
-xo    - delete all local printers
-?     - display command usage

Examples:
prnmngr -a -p "printer" -m "driver" -r "lpt1:"
prnmngr -d -p "printer" -s server
prnmngr -ac -p "\\server\printer"
prnmngr -d -p "\\server\printer"
prnmngr -x -s server
prnmngr -xo
prnmngr -l -s server
prnmngr -g
prnmngr -t -p "\\server\printer"

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

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/d6b5c6beb1f0242d0a8e224d23acadc56d503fc4b0552022856e77ff1e84c5d1/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prncnfg.vbs](prncnfg.vbs-CD24C6399311AE49BCF218EB908EE9D4.md) | 71
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnmngr.vbs](prnmngr.vbs-F758133F96C716B563E726C531DDA13D.md) | 99
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prncnfg.vbs](prncnfg.vbs-BFC68573988A820811549CC55C94768C.md) | 71


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prnmngr

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Adds, deletes, and lists printers or printer connections, in addition to setting and displaying the default printer. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prnmngr file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prnmngr`.

### Syntax

```
cscript prnmngr {-a | -d | -x | -g | -t | -l | -?}[c] [-s <Servername>] [-p <Printername>] [-m <printermodel>] [-r <portname>] [-u <Username>]
[-w <password>]
```

#### Parameters

| Parameter | Description |
|--|--|
| -a | Adds a local printer connection. |
| -d | Deletes a printer connection. |
| -x | Deletes all printers from the server specified by the **-s** parameter. If you don't specify a server, Windows deletes all printers on the local computer. |
| -g | Displays the default printer. |
| -t | Sets the default printer to the printer specified by the **-p** parameter. |
| -l | Lists all printers installed on the server specified by the **-s** parameter. If you don't specify a server, Windows lists the printers installed on the local computer. |
| c | Specifies that the parameter applies to printer connections. Can be used with the **-a** and **-x** parameters. |
| -s `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -p `<Printername>` | Specifies the name of the printer that you want to manage. |
| -m `<Modelname>` | Specifies (by name) the driver you want to install. Drivers are often named for the model of printer they support. See the printer documentation for more information. |
| -r `<portname>` | Specifies the port where the printer is connected. If this is a parallel or a serial port, use the ID of the port (for example, LPT1: or COM1:). If this is a TCP/IP port, use the port name that was specified when the port was added. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

#### Examples

To add a printer named colorprinter_2 that is connected to LPT1 on the local computer and requires a printer driver called color printer Driver1, type:

```
cscript prnmngr -a -p colorprinter_2 -m "color printer Driver1" -r lpt1:
```

To delete the printer named colorprinter_2 from the remote computer named HRServer, type:

```
cscript prnmngr -d -s HRServer -p colorprinter_2
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


