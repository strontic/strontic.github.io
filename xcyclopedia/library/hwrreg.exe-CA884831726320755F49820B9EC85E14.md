
# hwrreg.exe 

* File Path: `C:\Windows\system32\hwrreg.exe`
* Description: Microsoft Custom Dictionary Registration Tool
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `CA884831726320755F49820B9EC85E14`
SHA1 | `7130337984874649218F953EFAC809A98E50EE93`
SHA256 | `1179269C2FE5D784374F92138BC0EC960BEDE5833F32655BC8AFEE1A4A980E3D`
SHA384 | `ABF4E920A5A097A9EF4D68D839BCF6ADDA8EE564BE64151DB2CF9213EAACD691BA9A6003B83FA33047A8B4371C4B7301`
SHA415 | `6A3BE37B55B4AD58648F0FA991CBC06A10C3B2BDC740481562B5CD03D4BD2734588E541E55BB198BCF0904B106C363B224000491387112539A8564654C7184B7`
SSDEEP | `3072:9chRQFLQSXRKC9TPN/cVRZl31qbydPlJReBrYWQgbmpQJ5GtCmY2lZmVC:rRRh1uLZLcydPlJReSr45J5G1Y`

## Runtime Data

### Usage (stdout):
```Batchfile
USAGE:
  hwrreg [-check]
         [-lang <locale>]
         [-scope {all|me}]
         [-noprompt] 
         <dictfile.hwrdict>

-check          Verify dictionary file and show its registration information
-lang <locale>  Assign this language to the installed dictionary.
                Locale is of the form <language>-<REGION> using ISO codes
-scope {all|me} Install for all users on this machine or just for me
-noprompt       Don't prompt for confirmation

Example:
hwrreg -lang en-US myrsrc1.hwrdict
  installs myrsrc1.hwrdict with language 'English (US)' and default scope 'me'


Usage: hwrreg [-lang <localename>]
              [-scope {all|me}]
              [-type <type>]
              -list | -remove

-lang <locale>  List or remove dictionaries registered for this language.
                Locale is of the form <language>-<REGION> using ISO codes
-scope {all|me} List or remove dictionaries installed for all users
                or or just dictionaries installed for me (default)
-type <type>    List or remove dictionaries registered with this type
-list           List all installed dictionaries matching the other options
-remove         Prompts for removal of any dictionary  matching other options
 
Examples:
hwrreg -list -lang en-US -type PRIMARY-DICTIONARY
  lists dictionaries installed for me with this language and type
hwrreg -remove -lang en-US -type PRIMARY-DICTIONARY
  removes dictionaries installed for me with this language and type


```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 3300000266BD1580EFA75CD6D3000000000266
* Thumbprint: A4341B9FD50FB9964283220A36A1EF6F6FAA7840
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: HWRReg.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


