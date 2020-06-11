
# dispdiag.exe 

* File Path: `C:\Windows\system32\dispdiag.exe`
* Description: Display Diagnostics
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `2E0521ED2631272D90D5887A7109C20C`
SHA1 | `D7396AD887AEB2DA1D5D1045741CBCFD684098AD`
SHA256 | `2FAFF3700BF080D64D0997994C533B57816751E70893A158AF6C7B47D9FD9301`
SHA384 | `A3235624D967DF832805EFA3FEA07553C343EF710D8B88DA004CC15E5B301F8CDC2A60F55F1525CBBE9489913298F9EC`
SHA415 | `CA3BC7605B220BA691F064F69AF5C794F44C3529EDED9700A905D2BA7BDC1336EAB975A68DAC5EB222D760234C73042A563B3703739132B5F60504A28D002FCA`
SSDEEP | `1536:f+DGiHD+sItZuxWsB81yl/uJkgqQlgzn3/bCZxcd060I+qCIIpX78hWF26Z:fhsBLl/a8z3/bSxcdSINBIpX7iWf`

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
	                                as full screen dirty.Output:
	Name of the saved file.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dispdiag.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


