---
title: cdrecord.exe | 
---

# cdrecord.exe 

* File Path: `C:\program files\InfraRecorder\cdrtools\cdrecord.exe`

## Hashes

Type | Hash
-- | --
MD5 | `BADAE4CD656C8FE7E5F7B06C2DB926EF`
SHA1 | `AEBEDE6E62626FFB0F0D95C827A68C00AAC55AE6`
SHA256 | `7F1133CE207CF067F7604FD8AC8D8B092D714EA0C7000838E59DB7C9E050BEED`
SHA384 | `C636818F436F836111D9BC25D93A6CBB11F37C331BDAE3137B3A4E7CEC1C5521B2C7DC5AAF469C25F0271E483DCAD8ED`
SHA512 | `9259E9D3FC39B3149B308A013FF522166D3307D17C40BAC41A115D09343E9D7B6452B6DE2A14C9A90A498D5902E226E7D5363F95CDFE22170CC82D589A1CF1B3`
SSDEEP | `6144:Bx1xaWxsMqjptDOZCV7I404SHwMWG8QMWVUbV/gt/PIiiiiiT1fG/ay0x9n:BZrxsrzDOZCV7I4D+Jc/g5/Rxh`

## Runtime Data

### Usage (stdout):
```Batchfile
Cdrecord-ProDVD-ProBD-Clone 2.01.01a61 (i686-pc-cygwin) Copyright (C) 1995-2009 Jrg Schilling

```

### Usage (stderr):
```Batchfile
Usage: /cygdrive/c/program files/InfraRecorder/cdrtools/cdrecord [options] track1...trackn
Options:
	-version	print version information and exit
	dev=target	SCSI target to use as CD/DVD/BD-Recorder
	gracetime=#	set the grace time before starting to write to #.
	timeout=#	set the default SCSI command timeout to #.
	debug=#,-d	Set to # or increment misc debug level
	kdebug=#,kd=#	do Kernel debugging
	-verbose,-v	increment general verbose level by one
	-Verbose,-V	increment SCSI command transport verbose level by one
	-silent,-s	do not print status of failed SCSI commands
	driver=name	user supplied driver name, use with extreme care
	driveropts=opt	a comma separated list of driver specific options
	-setdropts	set driver specific options and exit
	-checkdrive	check if a driver for the drive is present
	-prcap		print drive capabilities for MMC compliant drives
	-inq		do an inquiry for the drive and exit
	-scanbus	scan the SCSI bus and exit
	-reset		reset the SCSI bus with the cdrecorder (if possible)
	-abort		send an abort sequence to the drive (may help if hung)
	-overburn	allow to write more than the official size of a medium
	-ignsize	ignore the known size of a medium (may cause problems)
	-useinfo	use *.inf files to overwrite audio options.
	speed=#		set speed of drive
	blank=type	blank a CD-RW disc (see blank=help)
	-format		format a CD-RW/DVD-RW/DVD+RW disc
	fs=#		Set fifo size to # (0 to disable, default is 4 MB)
	ts=#		set maximum transfer size for a single SCSI command
	-load		load the disk and exit (works only with tray loader)
	-lock		load and lock the disk and exit (works only with tray loader)
	-eject		eject the disk after doing the work
	-dummy		do everything with laser turned off
	-minfo		retrieve and print media information/status
	-media-info	retrieve and print media information/status
	-msinfo		retrieve multi-session info for mkisofs >= 1.10
	-toc		retrieve and print TOC/PMA data
	-atip		retrieve and print ATIP data
	-multi		generate a TOC that allows multi session
			In this case default track type is CD-ROM XA mode 2 form 1 - 2048 bytes
	-fix		fixate a corrupt or unfixated disk (generate a TOC)
	-nofix		do not fixate disk after writing tracks
	-waiti		wait until input is available before opening SCSI
	-immed		Try to use the SCSI IMMED flag with certain long lasting commands
	-force		force to continue on some errors to allow blanking bad disks
	-tao		Write disk in TAO mode. This option will be replaced in the future.
	-dao		Write disk in SAO mode. This option will be replaced in the future.
	-sao		Write disk in SAO mode. This option will be replaced in the future.
	-raw		Write disk in RAW mode. This option will be replaced in the future.
	-raw96r		Write disk in RAW/RAW96R mode. This option will be replaced in the future.
	-raw96p		Write disk in RAW/RAW96P mode. This option will be replaced in the future.
	-raw16		Write disk in RAW/RAW16 mode. This option will be replaced in the future.
	-clone		Write disk in clone write mode.
	tsize=#		Length of valid data in next track
	padsize=#	Amount of padding for next track
	pregap=#	Amount of pre-gap sectors before next track
	defpregap=#	Amount of pre-gap sectors for all but track #1
	mcn=text	Set the media catalog number for this CD to 'text'
	isrc=text	Set the ISRC number for the next track to 'text'
	index=list	Set the index list for the next track to 'list'
	-text		Write CD-Text from information from *.inf or *.cue files
	textfile=name	Set the file with CD-Text data to 'name'
	cuefile=name	Set the file with CDRWIN CUE data to 'name'
	-audio		Subsequent tracks are CD-DA audio tracks
	-data		Subsequent tracks are CD-ROM data mode 1 - 2048 bytes (default)
	-mode2		Subsequent tracks are CD-ROM data mode 2 - 2336 bytes
	-xa		Subsequent tracks are CD-ROM XA mode 2 form 1 - 2048 bytes
	-xa1		Subsequent tracks are CD-ROM XA mode 2 form 1 - 2056 bytes
	-xa2		Subsequent tracks are CD-ROM XA mode 2 form 2 - 2324 bytes
	-xamix		Subsequent tracks are CD-ROM XA mode 2 form 1/2 - 2332 bytes
	-cdi		Subsequent tracks are CDI tracks
	-isosize	Use iso9660 file system size for next data track
	-preemp		Audio tracks are mastered with 50/15 s preemphasis
	-nopreemp	Audio tracks are mastered with no preemphasis (default)
	-copy		Audio tracks have unlimited copy permission
	-nocopy		Audio tracks may only be copied once for personal use (default)
	-scms		Audio tracks will not have any copy permission at all
	-pad		Pad data tracks with 15 zeroed sectors
			Pad audio tracks to a multiple of 2352 bytes
	-nopad		Do not pad data tracks (default)
	-shorttrack	Subsequent tracks may be non Red Book < 4 seconds if in SAO or RAW mode
	-noshorttrack	Subsequent tracks must be >= 4 seconds
	-swab		Audio data source is byte-swapped (little-endian/Intel)
The type of the first track is used for the toc type.
Currently only form 1 tracks are supported.

```

### Loaded Modules:

Path |
-- |
C:\program files\InfraRecorder\cdrtools\cdrecord.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
[C:\program files\InfraRecorder\cdrtools\cdda2wav.exe](cdda2wav.exe-081F6F52F4254F500A8BB168C5A43CC8.md) | 29
[C:\program files\InfraRecorder\cdrtools\readcd.exe](readcd.exe-5A6E919190ADE849A55BEDEDD7E63774.md) | 35




MIT License. Copyright (c) 2020 Strontic.


