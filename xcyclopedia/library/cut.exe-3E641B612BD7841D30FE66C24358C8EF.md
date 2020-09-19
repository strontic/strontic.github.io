---
title: cut.exe | 
---

# cut.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\cut.exe`

## Hashes

Type | Hash
-- | --
MD5 | `3E641B612BD7841D30FE66C24358C8EF`
SHA1 | `1D753A61825D445A1A39C969BEF971EC52056621`
SHA256 | `9FC143261CE763BF634608707C17B4FEE10F082372D4B327FD034EBD44A5C450`
SHA384 | `20B90FB502E85E4F82797CEAC1A4DE8F1037E7F9D41BD84732262D48765DD795056C6F86EF6F3A3C8CD06CD5554C212F`
SHA512 | `15E5BDE15203FC5FAD5E010EB0AA619ED004336078801A70C55AC619CBB9676C5CECC6CC879D9EA4BC59BC1946AC6A4C8C660C5D170881D2CC256EEC48E8257D`
SSDEEP | `768:OISscCK/26NsWQkN1ex18uQvViqbo//ccccccccccccccccccccccccccccccccv:Pc/u6Nsm/exuAWkrFb4iUfw`

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





MIT License. Copyright (c) 2020 Strontic.


