---
title: AccCheckConsole.exe |  
excerpt: What is AccCheckConsole.exe?
---

# AccCheckConsole.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\AccChecker\AccCheckConsole.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `7FD40FEAFC038D02E510142B20F4AC8F`
SHA1 | `18F3AE31D33B30A5FC49C048080BEBB2B355159F`
SHA256 | `B7AEB85CE2B87D3DBB46D6BF86DD304E13C96AE6DB98059BDCD94AFA0EBE2809`
SHA384 | `9C564E272821E0EC516F374364F0B7FD23136FF26817AF0A62AEF4389721CEB1327D99ED6CED29BF8A2EC79DBCDCE77D`
SHA512 | `65A3611E05DA5654CD0BC796CF6659E8FD0B8C83D269CA229007FE215FEAE3A7FA4571AC358433B74C486139F9701C247C18F6A4CE764E66E2915CC8636B6B59`
SSDEEP | `384:hLwCj6aYZScLeG41oCvYf6kQFTFemhjITi3K+dwJwgMDoVW2VQwWUwGytZalxb7v:7pkC5hnjHK+dwJwHotVQC3v`
IMP | `F34D5F2D4577ED6D9CEEC516C1F5A744`
PESHA1 | `BF97B26844B4D3193BAEA926DD5B99C6D1BF190E`
PE256 | `BCCB9991113DAB6DF65C84B4540589E5CEE107369F8CBEEBABE3B6057AE78C7F`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\AccChecker\AccCheckConsole.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-D5777B6C068E726AF25C21FB0F9608BF.md) | 77
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-4B0134C4D55EE109CE2AF245A295DA69.md) | 77
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-661E08B8B343F1AFE4E1DDCC9180D2D9.md) | 82




MIT License. Copyright (c) 2020-2021 Strontic.


