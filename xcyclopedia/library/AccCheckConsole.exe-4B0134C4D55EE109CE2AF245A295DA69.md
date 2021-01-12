---
title: AccCheckConsole.exe |  
excerpt: What is AccCheckConsole.exe?
---

# AccCheckConsole.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\AccChecker\AccCheckConsole.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `4B0134C4D55EE109CE2AF245A295DA69`
SHA1 | `C0F29AEBBA4194BE223BAE74CB7A62E5A19694E1`
SHA256 | `60FFBECB6301A6EA0CC380D558DBA4CA07E8360A3A838EA317061B6BE6DA6F4F`
SHA384 | `832D2026F3888171175AA1404CB221B4CB1A0C233096128EA095DB81ADF05E8E6661911FF6776EEDFE49C8E6EB33B6BF`
SHA512 | `E545646DC265D253FE3FE114526B4A91F603BF629643E64CCE1AC18141A9C591BB8A8B2477A0B53D2802D07D5319284B67BF3CD1BB327FAE6133092D8A8CBF8D`
SSDEEP | `384:j6XLwCj6aYZScLeG41oCvYf6kQFTFemhjITi3K+dwJMgMuiXW2VQwWng4JeRlF6:ypkC5hnjHK+dwJMqivVQpz`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `F2C1ED684583ADE3691B81A988DB357C3A837721`
PE256 | `52A1DEC3DA7965CDD0A10779B2ED60D79096CDB0AB7312EEF899F97432676B86`

## Runtime Data

### Usage (stdout):
```cmhg
[Information] Command line argument
	Text: -help

The syntax of this command is:

	AccCheckConsole [options] (-hwnd <hwnd> | -process <name>) [<dlls>]

	Options:
		-hwnd <hwnd>          Validates the given hwnd. Can be hex or dec.
		-window <title>       Validates the window with the title given.
		-process <name>       Validates the main window of the process with that name.
		-list                 Lists all the verification routines available.
		-enable <name>        Runs the given routine. Can be specified more than once
		-disable <name>       Runs all but the given routine.  Can be specified more than once
		-log (info|warn|err)  The lowest event rating that will be logged.
		-logfile <file>       Outputs the log to file. Can be used multiple times.
		-suppress <file>      Uses the XML file <file> to suppress errors.
		-quiet                No logging to stdout.
		-help                 Quick Help.

	Error codes returned from AccCheckConsole when using "echo %errorlevel%"
		0 - No errors and no warnings.
		1 - Usages statement was requested.
		2 - Errors and no warnings.
		3 - Errors and warnings.
		4 - No errors but Warnings.
		5 - Invalid command line.

Examples:

1) Run all verifications on a window with a specified name.
	AccCheckConsole -window "Untitled - Notepad"

2) Run a subset of the verifications against an HWND, specifying a suppression file.
	AccCheckConsole -hwnd 0x00382f00 -enable CheckTabbing -enable CheckName -suppress suppress.xml

3) Run all verifications from a new verification DLL.
	AccCheckConsole -window "Untitled - Notepad" VerificationRoutine1.dll


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\AccChecker\AccCheckConsole.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002B7E8E007A82AEF13150000000002B7`
* Thumbprint: `5A68625F1A516670A744F7EF919500A479D32A5B`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows Kits Publisher, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: AccCheckConsole.exe
* Product Name: Microsoft (R) Windows (R) Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright: Copyright (c) Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-D5777B6C068E726AF25C21FB0F9608BF.md) | 83
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-661E08B8B343F1AFE4E1DDCC9180D2D9.md) | 75
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-7FD40FEAFC038D02E510142B20F4AC8F.md) | 77
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm64\agestore.exe](agestore.exe-794ECE80B607AD6A630D876BA29EADD8.md) | 29




MIT License. Copyright (c) 2020 Strontic.


