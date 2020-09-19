---
title: cdda2wav.exe | 
---

# cdda2wav.exe 

* File Path: `C:\program files\InfraRecorder\cdrtools\cdda2wav.exe`

## Hashes

Type | Hash
-- | --
MD5 | `081F6F52F4254F500A8BB168C5A43CC8`
SHA1 | `61FC44CCDAF425B6D11BBA0460BBF084EF1DFE87`
SHA256 | `E28AA3A998FB8D104DC5B053282EF0A3EE007D2791027870D1153F4AFC28C8D7`
SHA384 | `DC147DAB3057D1EC1EE674762B7E9D08CA3C77DF7995AAEB3244B98401F00F082AADE6EAEC4CECBDDF8C548CBEB84E24`
SHA512 | `8D9BF0C8CFA1518FD59F96081D5DD72288AB6139516EB7A50A285115E59FA58734494EA4906C375A2BB591F11EA5E73A9F7C0E7FA794CFA7060E1DC25BCE8DB9`
SSDEEP | `6144:qHCnri5/0OIkorrR90YsqB8eSN8QMWVUbmstwW:ZnaH290YsqBaGwW`

## Runtime Data

### Usage (stderr):
```cmhg
usage: cdda2wav [OPTIONS ...] [trackfilenames ...]
OPTIONS:
        [-c chans] [-s] [-m] [-b bits] [-r rate] [-a divider] [-S speed] [-x]
        [-t track[+endtrack]] [-i index] [-o offset] [-d duration] [-F] [-G]
        [-q] [-w] [-v vopts] [-R] [-P overlap] [-B] [-T] [-C input-endianess]
        [-e] [-n sectors] [-N] [-J] [-L cddbp-mode] [-H] [-g] [-l buffers] [-D cd-device]
        [-I interface] [-K sound-device] [-O audiotype] [-E output-endianess]
        [-A auxdevice] [-paranoia] [-cddbp-server=name] [-cddbp-port=port] [-version]
  (-D) dev=device		set the cdrom or scsi device (as Bus,Id,Lun).
       ts=#			set maximum transfer size for a single SCSI command
  (-A) auxdevice=device		set the aux device (typically /dev/cdrom).
  (-K) sound-device=device	set the sound device to use for -e (typically /dev/dsp).
       out-fd=descriptor	set the file descriptor for general output to descriptor.
       audio-fd=descriptor	set the file descriptor for '-' audio output.
  (-I) interface=interface	specify the interface for cdrom access.
        (generic_scsi or cooked_ioctl).
  (-c) channels=channels	set 1 for mono, 2 or s for stereo (s: channels swapped).
  (-s) -stereo			select stereo recording.
  (-m) -mono			select mono recording.
  (-x) -max			select maximum quality (stereo/16-bit/44.1 KHz).
  (-b) bits=bits		set bits per sample per channel (8, 12 or 16 bits).
  (-r) rate=rate		set rate in samples per second. -R gives all rates
  (-a) divider=divider		set rate to 44100Hz / divider. -R gives all rates
  (-R) -dump-rates		dump a table with all available sample rates
  (-S) speed=speedfactor	set the cdrom drive to a given speed during reading
  (-P) set-overlap=sectors	set amount of overlap sampling (default is 0)
  (-n) sectors-per-request=secs	read 'sectors' sectors per request.
  (-l) buffers-in-ring=buffers	use a ring buffer with 'buffers' elements.
  (-t) track=track[+end track]	select start track (option. end track).
  (-i) index=index		select start index.
  (-o) offset=offset		start at 'offset' sectors behind start track/index.
        one sector equivalents 1/75 second.
       start-sector=sector	set absolute start sector.
  (-O) output-format=audiotype	set to wav, au (sun), cdr (raw), aiff or aifc format.
  (-C) cdrom-endianess=endian	set little, big or guess input sample endianess.
  (-E) output-endianess=endian	set little or big output sample endianess.
  (-d) duration=seconds		set recording time in seconds or 0 for whole track.
  (-w) -wait			wait for audio signal, then start recording.
  (-F) -find-extremes		find extrem amplitudes in samples.
  (-G) -find-mono		find if input samples are mono.
  (-T) -deemphasize		undo pre-emphasis in input samples.
  (-e) -echo			echo audio data to sound device (see -K) SOUND_DEV.
  (-v) verbose-level=optlist	controls verbosity (for a list use -vhelp).
  (-N) -no-write		do not create audio sample files.
  (-J) -info-only		give disc information only.
  (-L) cddb=cddbpmode		do cddbp title lookups.
        resolve multiple entries according to cddbpmode: 0=interactive, 1=first entry
  (-H) -no-infofile		no info file generation.
       -no-fork			do not fork for better buffering.
  (-g) -gui			generate special output suitable for gui frontends.
  (-Q) -silent-scsi		do not print status of erreneous scsi-commands.
       -scanbus			scan the SCSI bus and exit
  (-M) -md5			calculate MD-5 checksum for audio data.
  (-q) -quiet			quiet operation, no screen output.
  (-p) playback-realtime=perc	play (echo) audio pitched at perc percent (50%-200%).
  (-V) -verbose-scsi		each option increases verbosity for SCSI commands.
  (-h) -help			show this help screen.
  (-B) -alltracks, -bulk	record each track into a separate file.
       -paranoia		use the lib paranoia for reading.
       -paraopts=opts		set options for lib paranoia (see -paraopts=help).
       -cddbp-server=servername	set the cddbp server to use for title lookups.
       -cddbp-port=portnumber	set the cddbp port to use for title lookups.
       -interactive		select interactive mode (used by gstreamer plugin).
       -version			print version information.

Please note: some short options will be phased out soon (disappear)!

parameters: (optional) one or more file names or - for standard output.
Version 2.01.01a61_cygwin32_nt_1.5.25-0.156-4-2-_i686_i686
defaults	stereo, 16 bit, 44100.00 Hz, track 1, no offset, one track,
          type: wav 'audio', don't wait for signal, not quiet,
          use: 'generic_scsi', device: 'yourSCSI_Bus,yourSCSI_ID,yourSCSI_LUN', aux: ''

```

### Loaded Modules:

Path |
-- |
C:\program files\InfraRecorder\cdrtools\cdda2wav.exe |
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
[C:\program files\InfraRecorder\cdrtools\cdrecord.exe](cdrecord.exe-BADAE4CD656C8FE7E5F7B06C2DB926EF.md) | 29
[C:\program files\InfraRecorder\cdrtools\readcd.exe](readcd.exe-5A6E919190ADE849A55BEDEDD7E63774.md) | 29




MIT License. Copyright (c) 2020 Strontic.


