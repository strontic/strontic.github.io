---
title: readcd.exe | 
---

# readcd.exe 

* File Path: `C:\Program Files\InfraRecorder\cdrtools\readcd.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5A6E919190ADE849A55BEDEDD7E63774`
SHA1 | `E40CA9E275F62DE1119B813584D43E4F69989A4F`
SHA256 | `1A39CAC63CA32EB4B1F7B538E31BB979F2696AC71676F8D57347A16A519BBF58`
SHA384 | `1E83ACBBBE8EF63AE2334EF2C8045A9684C9011F645ECD578C43CE82B93AEA66060FB34CDF06318CB14A3163778EBAC3`
SHA512 | `5E821A21C7B0686F139EADEA03E595ABFCF505ABC2C851E6033786635E5B0D643FB81815D2859C636FE38533E8F51B1F357FA264B5B7A942DB1B120CFA7680D1`
SSDEEP | `6144:flABjsKB+FSXGE3JEQXhlF8QMWVUbTI+VMu/gt/6ryI:ZcXxJzxfu/gUrT`

### Usage (stderr):
```Batchfile
/cygdrive/c/Program Files/InfraRecorder/cdrtools/readcd: Target 'help' is not a Number.
Usage:	readcd [options]
options:
	-version	print version information and exit
	dev=target	SCSI target to use
	f=filename	Name of file to read/write
	sectors=range	Range of sectors to read/write
	speed=#		set speed of drive (MMC only)
	ts=#		set maximum transfer size for a single SCSI command
	-w		Switch to write mode
	-c2scan		Do a C2 error scan
	-cxscan		Do a C1/C2/CU scan (only available on a few drives)
	-pi8scan	Do a DVD pisum8 scan (only available on a few drives)
	-pifscan	Do a DVD pif scan (only available on a few drives)
	-plot		Print data suitable for gnuplot
	-fulltoc	Retrieve the full TOC
	-clone		Retrieve the full TOC and all data
	-edc-corr	Try to do user level Reed Solomon repair (experimental)
	timeout=#	set the default SCSI command timeout to #.
	debug=#,-d	Set to # or increment misc debug level
	kdebug=#,kd=#	do Kernel debugging
	-quiet,-q	be more quiet in error retry mode
	-verbose,-v	increment general verbose level by one
	-Verbose,-V	increment SCSI command transport verbose level by one
	-silent,-s	do not print status of failed SCSI commands
	-scanbus	scan the SCSI bus and exit
	-noerror	do not abort on error
	-nocorr		do not apply error correction in drive
	-notrunc	do not truncate outputfile in read mode
	retries=#	set retry count (default is 128)
	-overhead	meter SCSI command overhead times
	meshpoints=#	print read-speed at # locations
	-factor		try to use speed factor with meshpoints=# if possible

sectors=0-0 will read nothing, sectors=0-1 will read one sector starting from 0

```

## Signature

* Status: Signature verified.
* Serial: `00B1F4A9019F0E490A34743EF8FEB1A228`
* Thumbprint: `7C65C5FB8A87242D467A7F1BF4571AD02C037069`
* Issuer: CN=UTN-USERFirst-Object, OU=http://www.usertrust.com, O=The USERTRUST Network, L=Salt Lake City, S=UT, C=US
* Subject: CN=Christian Kindahl, O=Christian Kindahl, STREET=Lotta Svrdsgatan 4 A, L=Gteborg, S=Vstra Gtaland, PostalCode=41504, C=SE

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\InfraRecorder\cdrtools\cdda2wav.exe](cdda2wav.exe-081F6F52F4254F500A8BB168C5A43CC8.md) | 29
[C:\Program Files\InfraRecorder\cdrtools\cdrecord.exe](cdrecord.exe-BADAE4CD656C8FE7E5F7B06C2DB926EF.md) | 35




MIT License. Copyright (c) 2020 Strontic.


