---
title: cut.exe | 
excerpt: What is cut.exe?
---

# cut.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\cut.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C78A9AB4BF79B7E0FE7F27761F69AB0B`
SHA1 | `59940489A8E0EA62E271D76C8087865DE6F259A3`
SHA256 | `091993CF0BDD63187EC4E65FCEA85EC4FE7C637586DD3D987708E4690658EFEF`
SHA384 | `C2D314AA69E1B18A75A23BF985323B1C2D907F12F91EBE1AF084A56158D5A55F9D38B44A30EADBFBA1DAD06299F6C2C3`
SHA512 | `ED522B60346F47C5D39AFA7219F001AA6C3C4C1EA509E012C8E39BC5C43C68C6DCF96ACF91B40FE97011A2CE09FB34F0FF4B593BFB1C76885EEBFC1DA0903AAB`
SSDEEP | `768:5OrkN6AdaFl7Ew6NLersNi4NiqbowieAva+WtdFbr4DGZUf2hq:5OrVW67EwOqzfWtdFbrdUfT`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/cut OPTION... [FILE]...
Print selected parts of lines from each FILE to standard output.

With no FILE, or when FILE is -, read standard input.

Mandatory arguments to long options are mandatory for short options too.
  -b, --bytes=LIST        select only these bytes
  -c, --characters=LIST   select only these characters
  -d, --delimiter=DELIM   use DELIM instead of TAB for field delimiter
  -f, --fields=LIST       select only these fields;  also print any line
                            that contains no delimiter character, unless
                            the -s option is specified
  -n                      (ignored)
      --complement        complement the set of selected bytes, characters
                            or fields
  -s, --only-delimited    do not print lines not containing delimiters
      --output-delimiter=STRING  use STRING as the output delimiter
                            the default is to use the input delimiter
  -z, --zero-terminated    line delimiter is NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

Use one, and only one of -b, -c or -f.  Each LIST is made up of one
range, or many ranges separated by commas.  Selected input is written
in the same order that it is read, and is written exactly once.
Each range is one of:

  N     N'th byte, character or field, counted from 1
  N-    from N'th byte, character or field, to end of line
  N-M   from N'th to M'th (included) byte, character or field
  -M    from first to M'th (included) byte, character or field

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/cut>
or available locally via: info '(coreutils) cut invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/cut: you must specify a list of bytes, characters, or fields
Try '/usr/bin/cut --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\cut.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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






MIT License. Copyright (c) 2020-2021 Strontic.


