---
title: prnmngr.vbs | 
excerpt: What is prnmngr.vbs?
---

# prnmngr.vbs 

* File Path: `C:\Windows\system32\Printing_Admin_Scripts\en-US\prnmngr.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `F758133F96C716B563E726C531DDA13D`
SHA1 | `E7F50ECFABB17B7F98DE8F80A83F0628328EBC05`
SHA256 | `3E1252E1D3173801E2AC9BD715CD97E69F9684398963F185BEEBE007EFF5D45D`
SHA384 | `14D48DD5E6AFFBBD1C00B50F664DD3B59EAC7AB66823C6614D4152A768B8D7A2E52A48D3775907C24F4B3486801CD923`
SHA512 | `DE727DF0350E9ECD874ED1B7FB528EA8EDBDA1D3E560B5F8F213481B16593351B1F134BB5218282E76D4DC605ADB72BCA18C20423E1EDBA11E11E88599009D66`
SSDEEP | `1536:e63LRV0ubIGkikGkFjGkikGkKEt0eEKU+kCKGWGPrbrbTDDpOAWGPrbrbTDDpDFC:pVJDxSo`
PESHA1 | `E7F50ECFABB17B7F98DE8F80A83F0628328EBC05`
PE256 | `3E1252E1D3173801E2AC9BD715CD97E69F9684398963F185BEEBE007EFF5D45D`

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

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/3e1252e1d3173801e2ac9bd715cd97e69f9684398963f185beebe007eff5d45d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prncnfg.vbs](prncnfg.vbs-CD24C6399311AE49BCF218EB908EE9D4.md) | 71
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prncnfg.vbs](prncnfg.vbs-BFC68573988A820811549CC55C94768C.md) | 72
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnmngr.vbs](prnmngr.vbs-65FC1A4445EA44AA1DCA130BE37CEDD1.md) | 99


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


