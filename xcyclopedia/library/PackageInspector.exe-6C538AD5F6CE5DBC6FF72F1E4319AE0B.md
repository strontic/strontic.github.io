---
title: PackageInspector.exe | PackageInspector allows creation of a catalog containing all executable files laid down by an installer
excerpt: What is PackageInspector.exe?
---

# PackageInspector.exe 

* File Path: `C:\WINDOWS\system32\PackageInspector.exe`
* Description: PackageInspector allows creation of a catalog containing all executable files laid down by an installer

## Hashes

Type | Hash
-- | --
MD5 | `6C538AD5F6CE5DBC6FF72F1E4319AE0B`
SHA1 | `ABE69F49D08E465FDF9CEB538935E3011D1E13A1`
SHA256 | `F32F1FC2245E6AD6B6A316C8E68AEA73EB354C5C8542D45DE36162FCD397B0A2`
SHA384 | `1CA13F0D7E374880E1CB602FC8013A3685D37263931B8D63B83C8B74451A6C9867960FD09AB675F25AA8B4A3A32379CB`
SHA512 | `8FFC3CD5919D435769CEC8E7786AF80FC570691CDA08598D2F0D19A18EF7E233F51DEF6A563614B862F8D2DA4B12F4685D21151CAE53FF29AEA36B82FFFD37B1`
SSDEEP | `1536:3C9Kmf+unWC79Mo3i3rZB20GFnSODukGX9q+K73FgHV5TlbJaLn:3CbnWC7Ib7GgO9Gw+K71gHV5Tlw`
IMP | `BE9CC8974980428AD11BEA059AD1E4B2`
PESHA1 | `7D0F3A6C54903037DA71B8058384BF1233213018`
PE256 | `6EE070FB026814FF0EFD7C722CDF1481F87AA226A9AD515F5C68832CBD6D9C71`

## Runtime Data

### Usage (stdout):
```cmhg
Usage:
PackageInspector.exe <command> <DriveLetter or Path> [options]
PackageInspector.exe start <DriveLetter>: [-path <pathToInstaller>]
PackageInspector.exe stop <DriveLetter>: -out cdf|cat|list [-cdfPath <outputCdfPath>] [-name <nameOfCat>] [-resdir <directoryForCat>] [-ph true | false] [-en <encoding type>] [-ca1 <CATATTR1>] [-ca2 <CATATTR2>] [-listPath <pathToOutputList.txt>]
PackageInspector.exe scan <PathToScan> -out cdf|cat|list [-cdfPath <outputCdfPath>] [-name <nameOfCat>] [-resdir <directoryForCat>] [-ph true | false] [-en <encoding type>] [-ca1 <CATATTR1>] [-ca2 <CATATTR2>] [-listPath <pathToOutputList.txt>]

Valid Commands : 
	start   	--	Specifies that a user will start a scan
	stop    	--	Specifies that a scan is complete and one of the supported outputs it to be produced
	scan    	--	Specifies that PackageInspector is to directly scan the given path rather than monitor created files.  Takes same options as stop

Start Options : 
	path    	--	File path to the package being inspected

Stop/Scan Options : 
	out     	--	Specifies what the tool should output from the scan (CAT, CDF, or List)
	cdfPath 	--	Specifies the full path for output of CDF including filename
	name    	--	Specifies the name of the catalog to produce
	resdir  	--	Specifies the result directory of the catalog
	ph      	--	Specifies whether page hashes should be included in the catalog
	en      	--	Specifies the encoding type of the catalog
	ca1     	--	Specifies CATATTR1 in the CDF or CAT
	ca2     	--	Specifies CATATTR2 in the CDF or CAT
	listPath	--	Specifies location to output list of files laid down by installer (for -out list)

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\system32\PackageInspector.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PACKAGEINSPECTOR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 1.00 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/f32f1fc2245e6ad6b6a316c8e68aea73eb354c5c8542d45de36162fcd397b0a2/detection





MIT License. Copyright (c) 2020-2021 Strontic.


