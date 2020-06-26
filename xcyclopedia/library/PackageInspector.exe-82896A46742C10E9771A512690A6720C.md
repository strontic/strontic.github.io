---
title: PackageInspector.exe | PackageInspector allows creation of a catalog containing all executable files laid down by an installer
---

# PackageInspector.exe 

* File Path: `C:\Windows\system32\PackageInspector.exe`
* Description: PackageInspector allows creation of a catalog containing all executable files laid down by an installer
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `82896A46742C10E9771A512690A6720C`
SHA1 | `D44069F02E2B25694D4330CA7EE7EF08E4C88E0F`
SHA256 | `8ACBA9A79F2D3565DD4056DDDAFD4D0AB425E6A88A46F03645492FABE4CF6716`
SHA384 | `DDE2DD9D460A9B87E5B484296C0B7F42E1196AE11CC07466807602AE2BB6B0E2C7AE3AA10AFC87EC709137368A385F80`
SHA512 | `4A9F1FAA3E410F839E93ADAD0A4361A794657775DB539293FDAFFD3D852F03EF1259BEB1E6D84F0CF60BE03B182561E1EF62F3C3DFB5F26A20B88A6A758D70C8`
SSDEEP | `1536:barAFc3oN7s5PPE46TS+BtvrzSaRhE+b30hNj5x9irmgO0Y5+l4XTeT2KJg8Tt6s:2AFc3oN7sBPE4dyvfSa4y8+l4q3i8hL`

## Runtime Data

### Usage (stdout):
```Batchfile
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

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: PACKAGEINSPECTOR.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 1.00 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.





MIT License. Copyright (c) 2020 Strontic.


