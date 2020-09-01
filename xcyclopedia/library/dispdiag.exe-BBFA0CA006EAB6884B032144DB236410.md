---
title: dispdiag.exe | Display Diagnostics
---

# dispdiag.exe 

* File Path: `C:\Windows\system32\dispdiag.exe`
* Description: Display Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `BBFA0CA006EAB6884B032144DB236410`
SHA1 | `272ED6EC0EA0954447FBB1A2BFD5E030FCB8491B`
SHA256 | `0B5E810C20FC5E8906AA993BB09EA021982C95A8244C2D56518EA16D22F16362`
SHA384 | `AEF77386BDB4D5F535148CAC9CA82EB1839A9DC14DB3A45281D836B16ADCBF3A0C03FCFEB790EE1217613145FAF29FDE`
SHA512 | `093B3279097D4676061BB2519F8BA85526E9F9FE0E5A20466FCDD2139074A23B7992B68081405A95C8065C0E1369548CDA669B47DF6DC76B296E8E6CDE7FBD6E`
SSDEEP | `3072:Hnhcq7iLbXtm9x5X32170rSPQRnzix1qm:BcAiLex5mJcSGnzix1`

## Runtime Data

### Usage (stdout):
```Batchfile
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

### Loaded Modules:

Path |
-- |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000001C422B2F79B793DACB20000000001C4`
* Thumbprint: `AE9C1AE54763822EEC42474983D8B635116C8452`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
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


