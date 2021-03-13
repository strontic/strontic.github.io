---
title: prncnfg.vbs | 
excerpt: What is prncnfg.vbs?
---

# prncnfg.vbs 

* File Path: `C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prncnfg.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `BFC68573988A820811549CC55C94768C`
SHA1 | `E03C0CD9AEA19D7F1BBA7F4F6ED30594FD39A3B4`
SHA256 | `5491E67ADAA0A642003969AC19D64D8FA79D03374B62C218C6ACD5C2703ECD6D`
SHA384 | `9C315F9A1D27E20F5B6354B29B2BAC26A3F286AB705378E9BA5E65CE9231ED4337A75AFE68FA46C1F01130BE4C21DDDB`
SHA512 | `593C458FA34BAB1FB33278293E796DE2A75F2D39D8C2268D8C9C3FC46327887E5C44832F7D03BD3C3D6B0858B4895257A8B3D4246D6EF56A00D1DECDEF374EB7`
SSDEEP | `1536:19Je4Mi3mI2hb7KZ18C2NGkikGkFjGkikGkKEt0eEKU+kCKGWGPrbrbTDDpOAWGC:heBQaFqR`
PESHA1 | `E03C0CD9AEA19D7F1BBA7F4F6ED30594FD39A3B4`
PE256 | `5491E67ADAA0A642003969AC19D64D8FA79D03374B62C218C6ACD5C2703ECD6D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prncnfg [-gtx?] [-s server][-p printer][-z new printer name]
               [-u user name][-w password][-r port name][-l location]
               [-m comment][-h share name][-f sep file][-y datatype]
               [-st start time][-ut until time][-i default priority]
               [-o priority][<+|->shared][<+|->direct][<+|->hidden]
               [<+|->published][<+|->rawonly][<+|->queued][<+|->enablebidi]
               [<+|->keepprintedjobs][<+|->workoffline][<+|->enabledevq]
               [<+|->docompletefirst]
Arguments:
-f     - separator file name
-g     - get configuration
-h     - share name
-i     - default priority
-l     - location string
-m     - comment string
-o     - priority
-p     - printer name
-r     - port name
-s     - server name
-st    - start time
-t     - set configuration
-u     - user name
-ut    - until time
-w     - password
-x     - change printer name
-y     - data type string
-z     - new printer name

-?     - display command usage
Examples:
prncnfg -g -s server -p printer
prncnfg -x -s server -p printer -z "new printer"
prncnfg -t -p printer -l "Building A/Floor 100/Office 1" -m "Color Printer"
prncnfg -t -p printer -h "Share" +shared -direct
prncnfg -t -p printer +rawonly +keepprintedjobs
prncnfg -t -p printer -st 2300 -ut 0215 -o 1 -i 5

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
* VirusTotal Link: https://www.virustotal.com/gui/file/5491e67adaa0a642003969ac19d64d8fa79d03374b62c218c6acd5c2703ecd6d/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prncnfg.vbs](prncnfg.vbs-CD24C6399311AE49BCF218EB908EE9D4.md) | 99
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnmngr.vbs](prnmngr.vbs-F758133F96C716B563E726C531DDA13D.md) | 72
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnmngr.vbs](prnmngr.vbs-65FC1A4445EA44AA1DCA130BE37CEDD1.md) | 71


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prncnfg

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Configures or displays configuration information about a printer. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prncnfg file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prncnfg`.

### Syntax

```
cscript prncnfg {-g | -t | -x | -?} [-S <Servername>] [-P <Printername>] [-z <newprintername>] [-u <Username>] [-w <password>] [-r <portname>] [-l <location>] [-h <sharename>] [-m <comment>] [-f <separatorfilename>] [-y <datatype>] [-st <starttime>] [-ut <untiltime>] [-i <defaultpriority>] [-o <priority>] [<+|->shared] [<+|->direct] [<+|->hidden] [<+|->published] [<+|->rawonly] [<+|->queued] [<+|->enablebidi] [<+|->keepprintedjobs] [<+|->workoffline] [<+|->enabledevq] [<+|->docompletefirst]
```

#### Parameters

| Parameter | Description |
|--|--|
| -g | Displays configuration information about a printer. |
| -t | Configures a printer. |
| -x | Renames a printer. |
| -S `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -P `<Printername>` | Specifies the name of the printer that you want to manage. Required. |
| -z `<newprintername>` | Specifies the new printer name. Requires the **-x** and **-P** parameters. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| -r `<portname>` | Specifies the port where the printer is connected. If this is a parallel or a serial port, then use the ID of the port (for example, LPT1 or COM1). If this is a TCP/IP port, use the port name that was specified when the port was added. |
| -l `<location>` | Specifies the printer location, such as **Copyroom**. If the location contains spaces, use quotation marks around the text, such as **"Copy Room"**.|
| -h `<sharename>` | Specifies the printer's share name. |
| -m `<comment>` | Specifies the printer's comment string. |
| -f `<separatorfilename>` | Specifies a file that contains the text that appears on the separator page. |
| -y `<datatype>` | Specifies the data types that the printer can accept. |
| -st `<starttime>` | Configures the printer for limited availability. Specifies the time of day the printer is available. If you send a document to a printer when it is unavailable, the document is held (spooled) until the printer becomes available. You must specify time as a 24-hour clock. For example, to specify 11:00 P.M., type **2300**. |
| -ut `<endtime>` | Configures the printer for limited availability. Specifies the time of day the printer is no longer available. If you send a document to a printer when it is unavailable, the document is held (spooled) until the printer becomes available. You must specify time as a 24-hour clock. For example, to specify 11:00 P.M., type **2300**. |
| -o `<priority>` | Specifies a priority that the spooler uses to route print jobs into the print queue. A print queue with a higher priority receives all its jobs before any queue with a lower priority. |
| -i `<defaultpriority>` | Specifies the default priority assigned to each print job. |
| `{+|-}`shared | Specifies whether this printer is shared on the network. |
| `{+|-}`direct | Specifies whether the document should be sent directly to the printer without being spooled. |
| `{+|-}`published | Specifies whether this printer should be published in active directory. If you publish the printer, other users can search for it based on its location and capabilities (such as color printing and stapling). |
| `{+|-}`hidden | Reserved function. |
| `{+|-}`rawonly | Specifies whether only raw data print jobs can be spooled in this queue. |
| `{+|-}`}queued | Specifies that the printer should not begin to print until after the last page of the document is spooled. The printing program is unavailable until the document has finished printing. However, using this parameter ensures that the whole document is available to the printer. |
| `{+|-}`keepprintedjobs | Specifies whether the spooler should retain documents after they are printed. Enabling this option allows a user to resubmit a document to the printer from the print queue instead of from the printing program. |
| `{+|-}`workoffline | Specifies whether a user is able to send print jobs to the print queue if the computer is not connected to the network. |
| `{+|-}`enabledevq | Specifies whether print jobs that don't match the printer setup (for example, PostScript files spooled to non-PostScript printers) should be held in the queue rather than being printed. |
| `{+|-}`docompletefirst | Specifies whether the spooler should send print jobs with a lower priority that have completed spooling before sending print jobs with a higher priority that have not completed spooling. If this option is enabled and no documents have completed spooling, the spooler will send larger documents before smaller ones. You should enable this option if you want to maximize printer efficiency at the cost of job priority. If this option is disabled, the spooler always sends higher priority jobs to their respective queues first. |
| `{+|-}`enablebidi | Specifies whether the printer sends status information to the spooler. |
| /? | Displays help at the command prompt. |

#### Examples

To display configuration information for the printer named *colorprinter_2* with a print queue hosted by the remote computer named *HRServer*, type:

```
cscript prncnfg -g -S HRServer -P colorprinter_2
```

To configure a printer named *colorprinter_2* so that the spooler in the remote computer named *HRServer* keeps print jobs after they have been printed, type:

```
cscript prncnfg -t -S HRServer -P colorprinter_2 +keepprintedjobs
```

To change the name of a printer on the remote computer named *HRServer* from *colorprinter_2* to *colorprinter 3*, type:

```
cscript prncnfg -x -S HRServer -P colorprinter_2 -z "colorprinter 3"
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


