
# Defrag.exe 
* File Path: `C:\Windows\system32\Defrag.exe`
* Description: Disk Defragmenter Module
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `BCBD8C0BFD620A4761C8ACDF96D9CDAE`
SHA1 | `608A8D6663A114825E800F84A053D74B901C0754`
SHA256 | `9FEC67B7E7C6FB7009C5D16387B1B34C017EA0BBE7543C63A2E197B1F369F127`
SHA384 | `5F508C96D54DBB97478F5375A31279BCDB972EAA727295B429F61008BDCD1862CFD156E429678B2A6998A9FB9ED5985D`
SHA415 | `5CAF2D20CE205E197CF58A63AB93F6EEC9D9FAA5267E25438FDA5C324243FB71E24F6B0D35C918FE4CE849517BA437323E8C251C23C237F178EA6EC079485DBC`
SSDEEP | `3072:BRzXzWWCZawAPFeFtyab4C6c5Q3eSjlR+8qxLijgJyfFOG83Yj34YFnw6OC2c9cB:/XRCMPuk3lRGOUZGKc4YFnwjCpW`

## Runtime Data
### Usage (stdout):
```Batchfile
Microsoft Drive Optimizer
Copyright (c) 2013 Microsoft Corp.

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

	/D	Perform traditional defrag (this is the default).

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
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Defrag.EXE.MUI
* Product Name: Windows Drive Optimizer
* Company Name: Microsoft Corp.
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  2013 Microsoft Corp.


