---
title: prnqctl.vbs | 
excerpt: What is prnqctl.vbs?
---

# prnqctl.vbs 

* File Path: `C:\Windows\system32\Printing_Admin_Scripts\en-US\prnqctl.vbs`

## Hashes

Type | Hash
-- | --
MD5 | `11895A0FF5707A85D5C7C43C4AB73B18`
SHA1 | `5FC0EADB2D1AA2415C90287538E12CEC58795EDC`
SHA256 | `C3443DA4D9C08229E0A40019174FAFE4D00F158F670328E55E1CB1650EE42623`
SHA384 | `99BBE36A34C6879CAF3381F442CFA8102B3F0FA10AD77A5395795C18553A3C1BDB3D32DF8DD96E48C7E02266C550497E`
SHA512 | `4030A9A043EB7B0E8EB351E07E13D9083BF9AD00F7F11320BA225390CA198AA077F630AF1940F162B834D952DC38F0026B1495A7FFDD7F5E370202C4123B7503`
SSDEEP | `768:ciYFirBOZAZdXe6buhoBANo8zTDn/g1qSakLaO:BKirBJZdXbbu6YDvSaLO`
PESHA1 | `5FC0EADB2D1AA2415C90287538E12CEC58795EDC`
PE256 | `C3443DA4D9C08229E0A40019174FAFE4D00F158F670328E55E1CB1650EE42623`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: prnqctl [-zmex?] [-s server][-p printer][-u user name][-w password]

Arguments:
-e     - print test page
-m     - resume the printer
-p     - printer name
-s     - server name
-u     - user name
-w     - password
-x     - purge the printer (cancel all jobs)
-z     - pause the printer
-?     - display command usage

Examples:
prnqctl -e -s server -p printer
prnqctl -m -p printer
prnqctl -x -p printer

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
* VirusTotal Link: https://www.virustotal.com/gui/file/c3443da4d9c08229e0a40019174fafe4d00f158f670328e55e1cb1650ee42623/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\Printing_Admin_Scripts\en-US\prnport.vbs](prnport.vbs-6D0114E9FBAE0DD8081C9A0D8F67D69F.md) | 43
[C:\Windows\system32\Printing_Admin_Scripts\en-US\pubprn.vbs](pubprn.vbs-C09F6C90E1DD04184030416D3C469206.md) | 65
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnport.vbs](prnport.vbs-96198EB7E50C0B72BBD5C1553DEB5915.md) | 40
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\prnqctl.vbs](prnqctl.vbs-3174AA250852ED50AC058E83A06482D0.md) | 65
[C:\Windows\SysWOW64\Printing_Admin_Scripts\en-US\pubprn.vbs](pubprn.vbs-D960FA3DAF18F891E2FF7F81C1AF1ADC.md) | 35


## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## prnqctl

> Applies to: Windows Server (Semi-Annual Channel), Windows Server 2019, Windows Server 2016, Windows Server 2012 R2, Windows Server 2012

Prints a test page, pauses or resumes a printer, and clears a printer queue. This command is a Visual Basic script located in the `%WINdir%\System32\printing_Admin_Scripts\<language>` directory. To use this command at a command prompt, type **cscript** followed by the full path to the prnqctl file, or change directories to the appropriate folder. For example: `cscript %WINdir%\System32\printing_Admin_Scripts\en-US\prnqctl`.

### Syntax

```
cscript Prnqctl {-z | -m | -e | -x | -?} [-s <Servername>] [-p <Printername>] [-u <Username>] [-w <password>]
```

#### Parameters

| Parameter | Description |
|--|--|
| -z | Pauses printing on the printer specified by the **-p** parameter. |
| -m | Resumes printing on the printer specified by the **-p** parameter. |
| -e | Prints a test page on the printer specified by the **-p** parameter. |
| -x | Cancels all print jobs on the printer specified by the **-p** parameter. |
| -s `<Servername>` | Specifies the name of the remote computer that hosts the printer that you want to manage. If you don't specify a computer, the local computer is used. |
| -p `<Printername>` | Required. Specifies the name of the printer that you want to manage. |
| -u `<Username>` -w `<password>` | Specifies an account with permissions to connect to the computer that hosts the printer that you want to manage. All members of the target computer's local Administrators group have these permissions, but the permissions can also be granted to other users. If you don't specify an account, you must be logged on under an account with these permissions for the command to work. |
| /? | Displays help at the command prompt. |

##### Remarks

- If the information that you supply contains spaces, use quotation marks around the text (for example, "Computer Name").

#### Examples

To print a test page on the Laserprinter1 printer shared by the \\Server1 computer, type:

```
cscript prnqctl -e -s Server1 -p Laserprinter1
```

To pause printing on the Laserprinter1 printer on the local computer, type:

```
cscript prnqctl -z -p Laserprinter1
```

To cancel all print jobs on the Laserprinter1 printer on the local computer, type:

```
cscript prnqctl -x -p Laserprinter1
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

- [Print Command Reference](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/print-command-reference.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


