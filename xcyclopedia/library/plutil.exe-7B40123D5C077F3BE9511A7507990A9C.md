---
title: plutil.exe | defaults
---

# plutil.exe 

* File Path: `C:\program files (x86)\Common Files\Apple\Apple Application Support\plutil.exe`
* Description: defaults

## Hashes

Type | Hash
-- | --
MD5 | `7B40123D5C077F3BE9511A7507990A9C`
SHA1 | `B4765265AC87613D47F6770F18E72B50339C852B`
SHA256 | `976208DE5D14BA36ADB47EC127754264280227F7F345778BD9AA7560C9B65713`
SHA384 | `B10F5C98CC7EBC2C0C1D886AEF7B8E2248F1B45D868126AF1417F54F5FDDBC8A725703DD1669CECFACBB52154360D1B1`
SHA512 | `7725021D70044AC769DAEFF202B2C99BE4F6D7B26CA100746F19C794106B5C61E35F02EEF9C1742BDD3EBAB10313324895ECA6B77DE1DCD7392A93439546CF12`
SSDEEP | `384:QFuVJDjKmI17JmGtEREl8uVujyabwuWPoHYqnYPLgWadDM8JN77hh5qC:QFTmI17j/ujyabNwoHLpWCDv3hnqC`

## Runtime Data

### Usage (stdout):
```Batchfile
plutil.exe: [command_option] [other_options] file...
The file '-' means stdin
Command options are (-lint is the default):
 -help		show this message and exit
 -lint		check the property list files for syntax errors
 -convert fmt	rewrite property list files in format
		fmt is one of: xml1 binary1 json
 -p             print property list in a human-readable fashion without attempting to convert the actual data
                (not for machine parsing! this 'format' is not stable) 
There are some additional optional arguments:
 -s		be silent on success
 -o path	specify alternate file path name for result;
		the -o option is used with -convert, and is only
		useful with one file argument (last file overwrites);
		the path '-' means stdout
 -e extension	specify alternate extension for converted files
 -r		if writing JSON, output in human-readable form
 --		specifies that all further arguments are file names

```

### Usage (stderr):
```Batchfile
unrecognized option: --help
plutil.exe: [command_option] [other_options] file...
The file '-' means stdin
Command options are (-lint is the default):
 -help		show this message and exit
 -lint		check the property list files for syntax errors
 -convert fmt	rewrite property list files in format
		fmt is one of: xml1 binary1 json
 -p             print property list in a human-readable fashion without attempting to convert the actual data
                (not for machine parsing! this 'format' is not stable) 
There are some additional optional arguments:
 -s		be silent on success
 -o path	specify alternate file path name for result;
		the -o option is used with -convert, and is only
		useful with one file argument (last file overwrites);
		the path '-' means stdout
 -e extension	specify alternate extension for converted files
 -r		if writing JSON, output in human-readable form
 --		specifies that all further arguments are file names
2020-08-30 17:47:30.365 plutil.exe[8064:2788] Windows edition

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Common Files\Apple\Apple Application Support\plutil.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `4EF16586A2FF12D69C556EC4C91BAEE1`
* Thumbprint: `634A0D892E72161714861C178015AFE9C1832E14`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Apple Inc., O=Apple Inc., L=Cupertino, S=California, C=US

## File Metadata

* Original Filename: plutil.exe
* Product Name: plutil
* Company Name: Apple Inc.
* File Version: 1,950,522,0
* Product Version: 1,950,522,0
* Language: English (United States)
* Legal Copyright: Copyright (C) 2007-2011, Apple Inc.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Common Files\Apple\Apple Application Support\distnoted.exe](distnoted.exe-899CED92AB6A8B024568572CB2748126.md) | 38
[C:\program files (x86)\Common Files\Apple\Apple Application Support\VersionCheckMe.exe](VersionCheckMe.exe-A7AB1130391C0261B6AEEFBDC4EAEF5E.md) | 38
[C:\program files\Common Files\Apple\Apple Application Support\VersionCheckMe.exe](VersionCheckMe.exe-220A1A86EC8E4B9159C075BC8B55B998.md) | 35




MIT License. Copyright (c) 2020 Strontic.


