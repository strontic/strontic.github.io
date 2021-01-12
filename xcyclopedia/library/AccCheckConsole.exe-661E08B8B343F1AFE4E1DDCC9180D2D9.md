---
title: AccCheckConsole.exe |  
excerpt: What is AccCheckConsole.exe?
---

# AccCheckConsole.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\AccChecker\AccCheckConsole.exe`
* Description:  

## Hashes

Type | Hash
-- | --
MD5 | `661E08B8B343F1AFE4E1DDCC9180D2D9`
SHA1 | `EF237756BE56DB310996B9F16FA6D15DBF31A9CE`
SHA256 | `9EC5D88096C84D9BF533433D38DAA31EE61E34BD8FE9C5ED7ECD60FDDEFB6792`
SHA384 | `69B38CEDF7FD7D4DCEAE20FF270647531767C7129E77A713D081700C72444095BF7033D0F091D46B89B113A70180E14C`
SHA512 | `7A9E368FC172910092846AEB06127EE3003786449591FFC492DBA6A7D48369075BE30B5114393AE43925EDDC382EF3B5D9898B2C4674C867ACC6FEA48463EFEC`
SSDEEP | `384:aLwCj6aYZS0reG41oCvYf6kQFTFemhjITi3K+dwJ0gM+KyW2VQwWqwGyeVZalxYI:0BkC5hnjHK+dwJ0qKKVQA65gA`
IMP | `n/a`
PESHA1 | `44B637B4DBE16D74CFB8CC25E4315EB57FD845D4`
PE256 | `963022C2F151959D3B86C2D1CFAC2160E6CF97D2B1FF7C13C89CF4DF4BBA5376`

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
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\AccChecker\AccCheckConsole.exe |
C:\Windows\System32\KERNEL32.dll |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\MSCOREE.DLL |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-D5777B6C068E726AF25C21FB0F9608BF.md) | 80
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-4B0134C4D55EE109CE2AF245A295DA69.md) | 75
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\AccChecker\AccCheckConsole.exe](AccCheckConsole.exe-7FD40FEAFC038D02E510142B20F4AC8F.md) | 82




MIT License. Copyright (c) 2020 Strontic.


