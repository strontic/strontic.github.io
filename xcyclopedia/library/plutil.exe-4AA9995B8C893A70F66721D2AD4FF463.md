---
title: plutil.exe | defaults
excerpt: What is plutil.exe?
---

# plutil.exe 

* File Path: `C:\program files\Common Files\Apple\Apple Application Support\plutil.exe`
* Description: defaults

## Hashes

Type | Hash
-- | --
MD5 | `4AA9995B8C893A70F66721D2AD4FF463`
SHA1 | `736C74E434D9195C968514221A31FF31071D5911`
SHA256 | `FF86B0A8122E2EBBB6436B8092F16FC4ACB7EB559BC2A0C655A39B629E16AE0C`
SHA384 | `4C2ED7C0329D855B43A2A55F132A3E953FE5845A7C55C7F313713D12531693E6800482070E6D3A043CE2D42DE19D9050`
SHA512 | `F0B9F2375A80E53982B02CC5DD8F31CAA91062D6CB17F33C16BE468346659B9A7E9E42307A08E6FC49D3A2829D383861185AFFEF1C6048A48F564ECC6260DE7A`
SSDEEP | `768:uCRDw7VSo2xvDMtAZ+qGr7Z+dsNtChZxyosvjDppW533hY6D:JBk29q/ChZxMjtpW533hY6D`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
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
2020-08-30 15:04:28.396 plutil.exe[2392:1b0] Windows edition

```

### Loaded Modules:

Path |
-- |
C:\program files\Common Files\Apple\Apple Application Support\plutil.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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






MIT License. Copyright (c) 2020-2021 Strontic.


