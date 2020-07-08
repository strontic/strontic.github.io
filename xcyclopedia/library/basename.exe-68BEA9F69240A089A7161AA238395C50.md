---
title: basename.exe | 
---

# basename.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\basename.exe`

## Hashes

Type | Hash
-- | --
MD5 | `68BEA9F69240A089A7161AA238395C50`
SHA1 | `D6D5BC0EB419AA1F6AAABC321A574B0993D3180D`
SHA256 | `513553D11D392D1B4E17E6BD0E3854922F5E361DD219FF0BF313F8699184A0E9`
SHA384 | `D093A2AC3CBECDAC725A615D4391655BFDE45CA82E01A32DE34F338841DCC8A82E370FB475E3413D8A4D89959E9B8E85`
SHA512 | `3509D90DAAD12FE366C631CF44BFB1731DC635EF7012645FBEBD6CA00115B493649975160371A7CC3E0B36108976A39787A76F0C23AF4879C3A0AE71AD4C44C9`
SSDEEP | `768:EYmR8IDsOkVCYrRJdLxgmViqboTHcccccccccccccccccccccccccccccccccBNl:EfZDsqYr1lWFFXhUfh`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: /usr/bin/basename NAME [SUFFIX]
  or:  /usr/bin/basename OPTION... NAME...
Print NAME with any leading directory components removed.
If specified, also remove a trailing SUFFIX.

Mandatory arguments to long options are mandatory for short options too.
  -a, --multiple       support multiple arguments and treat each as a NAME
  -s, --suffix=SUFFIX  remove a trailing SUFFIX; implies -a
  -z, --zero           end each output line with NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

Examples:
  /usr/bin/basename /usr/bin/sort          -> "sort"
  /usr/bin/basename include/stdio.h .h     -> "stdio"
  /usr/bin/basename -s .h include/stdio.h  -> "stdio"
  /usr/bin/basename -a any/str1 any/str2   -> "str1" followed by "str2"

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/basename>
or available locally via: info '(coreutils) basename invocation'

```

### Usage (stderr):
```Batchfile
basename: unknown option -- h
Try '/usr/bin/basename --help' for more information.

```

## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\basename.exe](basename.exe-68BEA9F69240A089A7161AA238395C50.md) | 100

## Possible Misuse

*The following table contains possible examples of `basename.exe` being misused. While `basename.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1556.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1556.002/T1556.002.md) | $passwordFilterName = (Copy-Item "#{input_dll}" -Destination "C:\Windows\System32" -PassThru).basename | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)



MIT License. Copyright (c) 2020 Strontic.


