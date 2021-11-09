---
title: dispdiag.exe | Display Diagnostics
excerpt: What is dispdiag.exe?
---

# dispdiag.exe 

* File Path: `C:\WINDOWS\system32\dispdiag.exe`
* Description: Display Diagnostics

## Hashes

Type | Hash
-- | --
MD5 | `497E1A824D96B2BF39352DFC65CA664A`
SHA1 | `33D56C644A300DC7B09F398D69010591EF3541AB`
SHA256 | `9CE5DB462B01BAAF505A5405B9A77797DEAAF6BA435AACDDEF4322C39DA61736`
SHA384 | `90263C42EA1BC32FEFFFE229FB71D6C0588CA7C0B292FB311C3B21975F40BFB100EF518DD8C245CE11D799BD20C8BBE5`
SHA512 | `27EA2D34FFC6EB21F9A8673067A4506AA8AD2C960BC58A6597D05AB3C74FDBB1512B87D69B6587AAA79CF2E7BC3C81E810CBB373F7B7A833F6A61BF1E4A6537B`
SSDEEP | `3072:+Dc5HPVrTXJZPIsrpzn3xUAKJPLIYEo2187sVaMe1ph6pN:+IHtrTXJZwsrpj3xUAKJPWuA4h1ph6`
IMP | `5BA7D44CCB1EF9DE85EEE8889019345E`
PESHA1 | `77673B41B91A1FB1F3BCC72E9BEDFCF62916CA60`
PE256 | `7A85A47064F6123E8A77949D1FEA98DEFE72DD8AC053BAD8A9F395BA6BD1638E`

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
C:\WINDOWS\system32\dispdiag.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/9ce5db462b01baaf505a5405b9a77797deaaf6ba435aacddef4322c39da61736/detection



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


