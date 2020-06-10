
# Defrag.exe 
* File Path: `C:\WINDOWS\system32\Defrag.exe`
* Description: Disk Defragmenter Module
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `15EFD404D3065B560876BBE567CE981A`
SHA1 | `DAF77FBBA1671CDFD23C76B3D7E05859D695DCDE`
SHA256 | `2630901B1B24EDE6AA117163BB738B90921D3D67F5AEB233CAC0715A836BACE3`
SHA384 | `36FB405C2FF40F14D54CC0957A75E73EB04329DFEBA1FB8062CF29D003FF3985279D22FA2D2D57C047234132F537C1DF`
SHA415 | `3B556CE7E80FB3E054A289BC35593240DB41915B8C28E0D8EB09417553640338273CB2AABA7B17603FA48034A90828912FE7FF8C3A359FAF9B59277F30625A7D`
SSDEEP | `3072:UtzyHzVHRADkbo0pwIuUEb4C6c5Q3eSjlR+8qxLijgJyfFOG83Yj34YFnw6OC2cs:UcTFRWKT3lRGOUZGKc4YFnwjCpW`

## Runtime Data
### Usage (stdout):
```Batchfile
Microsoft Drive Optimizer
Copyright (c) Microsoft Corp.

Please specify a volume to perform the operation on. (0x89000007)

Description:

	Optimizes and defragments files on local volumes to
	improve system performance.

Syntax:

	defrag <volumes> | /C | /E <volumes> [<task(s)>] [/H] [/M [n] | [/U] [/V]] [/I n]

	Where <task(s)> is omitted (traditional defrag), or as follows:
		/A | [/D] [/K] [/L] | /O | /X

	Or, to track an operation already in progress on a volume:
	defrag <volume> /T

Parameters:

	Value	Description
	/A	Perform analysis on the specified volumes.
	/C	Perform the operation on all volumes.
	/D	Perform traditional defrag (this is the default).  On a tiered volume
		though, traditional defrag is performed only on the Capacity tier.
	/E	Perform the operation on all volumes except those specified.
	/G	Optimize the storage tiers on the specified volumes.
	/H	Run the operation at normal priority (default is low).
	/I n	Tier optimization would run for at most n seconds on each volume.
	/K	Perform slab consolidation on the specified volumes.
	/L	Perform retrim on the specified volumes.
	/M [n]	Run the operation on each volume in parallel in the background.
		At most n threads optimize the storage tiers in parallel.
	/O	Perform the proper optimization for each media type.
	/T	Track an operation already in progress on the specified volume.
	/U	Print the progress of the operation on the screen.
	/V	Print verbose output containing the fragmentation statistics.
	/X	Perform free space consolidation on the specified volumes.

Examples:

	defrag C: /U /V
	defrag C: D: /M
	defrag C:\mountpoint /A /U
	defrag /C /H /V

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Defrag.EXE.MUI
* Product Name: Windows Drive Optimizer
* Company Name: Microsoft Corp.
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corp.


