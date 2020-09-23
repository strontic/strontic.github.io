---
title: PackageInspector.exe | PackageInspector allows creation of a catalog containing all executable files laid down by an installer
excerpt: What is PackageInspector.exe?
---

# PackageInspector.exe 

* File Path: `C:\Windows\system32\PackageInspector.exe`
* Description: PackageInspector allows creation of a catalog containing all executable files laid down by an installer

## Hashes

Type | Hash
-- | --
MD5 | `A128A0B6961768391516E71DB936E4E4`
SHA1 | `148CC949EDD24D9227736C75A831DF2BE746A7C5`
SHA256 | `ADF1880A66C7FFAB61F60DBB27145A0DCCBC7B7726AC750896FF2B7E79A31064`
SHA384 | `2AA127F0872B36C818D38D2BFBDB436C53D56C8C7946FB5AA00F59FEA0104520BA61763D3987B9A288DEB6F62B06D4FF`
SHA512 | `B60C0A5779D8A9FE69E124DA62EF8647940DF2BB916C5E644178290A1387040C5C017E33A4388A9677958253E2FD6A5E2132A77D322CBB3D3F3AB80FCD3A2502`
SSDEEP | `1536:fjzMGv33k2Ty2QepOaVc+wnZYeOfhAt6mhdFA+K7gAwS+EwAPJP9HUcn:fMI3U4Q7l+GZYe8AAm7y+K7gI+EwAPJb`
IMP | `4E095ADEBA5B01D1D9BE8EA1CB75A8BA`
PESHA1 | `9CAAD71DAF7467E5752757D15AA261695CCE2E85`
PE256 | `8C508A38F06B3EEF4A2A665C60A855DC11D3B1B36C8AF2CCFD90714F3F4A01C4`

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
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\system32\PackageInspector.exe |


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PACKAGEINSPECTOR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 1.00 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/adf1880a66c7ffab61f60dbb27145a0dccbc7b7726ac750896ff2b7e79a31064/detection/





MIT License. Copyright (c) 2020 Strontic.


