---
title: dispdiag.exe | Display Diagnostics
---

# dispdiag.exe 

* File Path: `C:\WINDOWS\system32\dispdiag.exe`
* Description: Display Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `4131B785B0EC3C5A7F71FA80D113972C`
SHA1 | `0D56DD7A2270A6956C96AD29E2AC65B69B441CED`
SHA256 | `FBC924D365F233C0D5D634004F77BEFBD688C3CD137559CE8C998E8251D5DACA`
SHA384 | `3AD55109CF7A58B886E92DA68F053381DBBF8ED177926EB76226869C3ACCD1DCE08C6391FC0931887F60396F51291F1E`
SHA512 | `53FA476266CCE83E04C867034075FB53208309143E7EC290FD962C04541E7D19627881A4CF06D82CE73282D1A9615FD8465371F5B7D0B9908A51D581090DA626`
SSDEEP | `3072:J03bMUGJg/SrM6AXsxoDee217IMqKUiqf:qbMUGJgKmsxvRJIMqKUiq`

## Runtime Data

### Usage (stdout):
```cmhg
Logs display information to a file in the current directory.

Usage: dispdiag [-testacpi] [-d] [-delay <seconds>] [-brightnesslogging] [-out <FilePath>]
	-testacpi            runs hotkey diagnostics test
	-d                   generates a dmp file as well with additional data.
	-delay               delays the collection of data by specified time in seconds.
	-out <FilePath>      path where the dispdiag file should be saved, including filename. This must be the last parameter
	-DumpIdDiag          force Indirect DIsplay framework to dump diag info via WPP
	-brightnesslogging              toggle verbose brightness logging.
	-ccddatabaselogging <on|off>    toggle Ccd database access logging.
	-dxgautologger <on|off>         toggle DxgDiagnostics autologger. Requires admin and a reboot.
	-DodFullscreenupdates <on|off>  toggle if all active display only drivers should process each present
	                                as full screen dirty.
	-Msg <Message to log>           Inserts the specified message into the diagnostic buffers
Output:
	Name of the saved file.

```

## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## dispdiag

Logs display information to a file.

### Syntax

```
dispdiag [-testacpi] [-d] [-delay <seconds>] [-out <filepath>]
```

##### Parameters

| Parameter | Description |
| --------- | ----------- |
| - testacpi | Runs hotkey diagnostics test. Displays the key name, code and scan code for any key pressed during the test. |
| -d | Generates a dump file with test results. |
| -delay `<seconds>` | Delays the collection of data by specified time in *seconds*. |
| -out `<filepath>`  | Specifies path and filename to save collected data. This must be the last parameter. |
| -? | Displays available command parameters and provides help for using them. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


