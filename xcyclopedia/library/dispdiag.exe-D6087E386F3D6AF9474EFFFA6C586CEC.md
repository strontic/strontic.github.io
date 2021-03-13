---
title: dispdiag.exe | Display Diagnostics
excerpt: What is dispdiag.exe?
---

# dispdiag.exe 

* File Path: `C:\Windows\system32\dispdiag.exe`
* Description: Display Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `D6087E386F3D6AF9474EFFFA6C586CEC`
SHA1 | `FAF1350A70457B82F5826FDB7B42A5B61252C41D`
SHA256 | `89808FECDA2B63D1A16C42748C4905324983F66AA20EAA704F39F251CCCE7B7A`
SHA384 | `65EFA232F7207134644610146FF508C938880BC199657303B5305A9B0FA2B2C0C7EE2760E8474AFB11F67A9E57107B04`
SHA512 | `8F966A8AEBA3D7EB615815CE94FC57BC6F68B05F723802A86BABB6B0DBA4767F50EA8B8C646C4A16566C58CB97A1D034700A35A1AB25362361CA378A06D349BC`
SSDEEP | `3072:/ZMS3Ww0Zx6o6s/W/MCv6KuGzSSOE219p+IjPiy1yk:ROw0ZQoPK9YfptjPiy1y`
IMP | `9ACE3E42278A3D9F47810466AD00D927`
PESHA1 | `5DDE05DFCBD4873ED8BFBBDD8CFE566E99794487`
PE256 | `A156B6983F0D2D3B23DEB8314A3AF26BB0292603363AAF137B015DDDAE26FBBC`

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

### Loaded Modules:

Path |
-- |
C:\Windows\system32\dispdiag.exe |
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

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/89808fecda2b63d1a16c42748c4905324983f66aa20eaa704f39f251ccce7b7a/detection



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



MIT License. Copyright (c) 2020-2021 Strontic.


