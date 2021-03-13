---
title: mp3gain.exe | mp3 volume normalizer
excerpt: What is mp3gain.exe?
---

# mp3gain.exe 

* File Path: `C:\Program Files (x86)\MusicBee\mp3gain.exe`
* Description: mp3 volume normalizer

## Hashes

Type | Hash
-- | --
MD5 | `1047510FB6C40F4E88F5E922785835E5`
SHA1 | `F606F8EFBE8551695D61E2E6D7B0D79EBD1C651C`
SHA256 | `679805127DB2A5E9390409EE1B7380AC1BEF5955ED146F22408A91B4F2739C7E`
SHA384 | `EE41740BE534D51A6558C392ADDD34A86C6BA692D392CB7198AFB84F09B4F1EB7932CA174572E788567F0F683522B984`
SHA512 | `79556B3F5BCFEFB7D8BFF9080B45AF7CD30DCE407D9CF817D961884339455A735B6374EEFB1D913C43A37F3294272F138ED468807E0930A8739F3237A09B7398`
SSDEEP | `3072:HoszI/9Hh6uSeL9blOPQuAkyMt5TXT4SC/EyiO+60weV17CHC:pI/v6uSgCBC/Eyc`
IMP | `46819273B0680EA7DD46FCB2627AD998`
PESHA1 | `2C8B7C6F65080459F9FC4DFB43C4E7774FC0A9E1`
PE256 | `0B37782E72BB1411AFD0B80AD40470F98D77B9BC970002749F5A97659037C70E`

## Runtime Data

### Usage (stdout):
```cmhg
C:\temp\strontic-xcyclopedia\notepad.exe
Can't open C:\temp\strontic-xcyclopedia\notepad.exe for reading

```

### Usage (stderr):
```cmhg
C:\Program Files (x86)\MusicBee\mp3gain.exe version 1.5.2
copyright(c) 2001-2009 by Glen Sawyer
uses mpglib, which can be found at http://www.mpg123.de
Usage: C:\Program Files (x86)\MusicBee\mp3gain.exe [options] <infile> [<infile 2> ...]
options:
	/v - show version number
	/g <i>  - apply gain i without doing any analysis
	/l 0 <i> - apply gain i to channel 0 (left channel)
	          without doing any analysis (ONLY works for STEREO files,
	          not Joint Stereo)
	/l 1 <i> - apply gain i to channel 1 (right channel)
	/e - skip Album analysis, even if multiple files listed
	/r - apply Track gain automatically (all files set to equal loudness)
	/k - automatically lower Track/Album gain to not clip audio
	/a - apply Album gain automatically (files are all from the same
	              album: a single gain change is applied to all files, so
	              their loudness relative to each other remains unchanged,
	              but the average album loudness is normalized)
	/m <i> - modify suggested MP3 gain by integer i
	/d <n> - modify suggested dB gain by floating-point n
	/c - ignore clipping warning when applying gain
	/o - output is a database-friendly tab-delimited list
	/t - writes modified data to temp file, then deletes original
	     instead of modifying bytes in original file
	/q - Quiet mode: no status messages
	/p - Preserve original file timestamp
	/x - Only find max. amplitude of file
	/f - Assume input file is an MPEG 2 Layer III file
	     (i.e. don't check for mis-named Layer I or Layer II files)
	/? or /h - show this message
	/s c - only check stored tag info (no other processing)
	/s d - delete stored tag info (no other processing)
	/s s - skip (ignore) stored tag info (do not read or write tags)
	/s r - force re-calculation (do not read tag info)
	/s i - use ID3v2 tag for MP3 gain info
	/s a - use APE tag for MP3 gain info (default)
	/u - undo changes made (based on stored tag info)
	/w - "wrap" gain change if gain+change > 255 or gain+change < 0
	      (use "/? wrap" switch for a complete explanation)
If you specify /r and /a, only the second one will work
If you do not specify /c, the program will stop and ask before
     applying gain change to a file that might clip

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\MusicBee\mp3gain.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: The file C:\Program Files (x86)\MusicBee\mp3gain.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: mp3gain.exe
* Product Name: mp3gain
* Company Name: 
* File Version: 1, 5, 0, 2
* Product Version: 1, 5, 0, 2
* Language: English (United States)
* Legal Copyright: Copyright  2001-2009 Glen Sawyer
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/679805127db2a5e9390409ee1b7380ac1bef5955ed146f22408a91b4f2739c7e/detection/





MIT License. Copyright (c) 2020-2021 Strontic.


