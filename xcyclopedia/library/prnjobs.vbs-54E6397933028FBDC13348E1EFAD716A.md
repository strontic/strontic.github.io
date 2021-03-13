---
title: prnjobs.vbs | 
excerpt: What is prnjobs.vbs?
---

# prnjobs.vbs 

* File Path: `C:\Windows\system32\Printing_Admin_Scripts\en-US\prnjobs.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `54E6397933028FBDC13348E1EFAD716A`
SHA1 | `263840502AFF415ADDFCFE768CC7345C46C16AB4`
SHA256 | `AE0D0032FEDEC77A9EB95149DF622BA25C8EE2E21A43BAC6981F11C013D93381`
SHA384 | `C190DC40A3EFF4BF0D812DB4E71CA9C15CB897B58C0686204CA8525039012353E42B66DB5AED605DD6DDF8B90DC2EF84`
SHA512 | `EF4B6A2E77651F6DBEF2CA4689167117ACF380BB4683A56694AC1B85812CB3603861B6AC3943BE507B59FD9663FA25687E076B1C5DC8ACC51050003141D50FE0`
SSDEEP | `1536:+o125FjaXGxbMN75ro6BHB1ZiXbbu6ABDaSj:L6QHeSj`
PESHA1 | `263840502AFF415ADDFCFE768CC7345C46C16AB4`
PE256 | `AE0D0032FEDEC77A9EB95149DF622BA25C8EE2E21A43BAC6981F11C013D93381`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prnjobs [-zmxl?] [-s server][-p printer][-j jobid][-u user name][-w password]

Arguments:
-j     - job id
-l     - list all jobs
-m     - resume the job
-p     - printer name
-s     - server name
-u     - user name
-w     - password
-x     - cancel the job
-z     - pause the job
-?     - display command usage

Examples:
prnjobs -z -p printer -j jobid
prnjobs -l -p printer
prnjobs -l

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
* VirusTotal Link: https://www.virustotal.com/gui/file/ae0d0032fedec77a9eb95149df622ba25c8ee2e21a43bac6981f11c013d93381/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnjobs.vbs](prnjobs.vbs-16EF15265C4D06DAAA4F0BEA9AC9F11B.md) | 85


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prnjobs

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Pauses, resumes, cancels, and lists print jobs. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prnjobs file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prnjobs.vbs`.

### Syntax

```
cscript prnjobs {-z | -m | -x | -l | -?} [-s <Servername>] [-p <Printername>] [-j <JobID>] [-u <Username>] [-w <password>]
```

#### Parameters

| Parameter | Description |
|--|--|
| -z | Pauses the print job specified by the **-j** parameter. |
| -m | Resumes the print job specified by the **-j** parameter. |
| -x | Cancels the print job specified by the **-j** parameter. |
| -l | Lists all the print jobs in a print queue. |
| -s `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -p `<Printername>` | Required. Specifies the name of the printer that you want to manage. |
| -j `<JobID>` | Specifies (by ID number) the print job you want to cancel. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

#### Examples

To pause a print job with a job ID of 27 sent to the remote computer named HRServer for printing on the printer named colorprinter, type:

```
cscript prnjobs.vbs -z -s HRServer -p colorprinter -j 27
```

To list all current print jobs in the queue for the local printer named colorprinter_2, type:

```
cscript prnjobs.vbs -l -p colorprinter_2
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


