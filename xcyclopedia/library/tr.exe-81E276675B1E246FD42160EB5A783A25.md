---
title: tr.exe | 
excerpt: What is tr.exe?
---

# tr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\tr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `81E276675B1E246FD42160EB5A783A25`
SHA1 | `CB1C235F00DEB94722433E695C75783556B0FF35`
SHA256 | `5FFB2662FF1A176A8FD8FCAAF7D67ADC580E9996F7DCF8EF5696C3C7CFBF4A78`
SHA384 | `C26F96C3712991B9DEC0AFCBC3A691D2815BB3E5858F745B876208CC9A77C7E4DC57AC34AA06DFC73A3C0BA4D62C8550`
SHA512 | `DBA416513F537A2D513F09EC79F5142BA51CE5E2B5E0D325DDE5E8DCD392500BABECC861D6E6FD742BE3B672463A8C63FC2864AA24D0BB7B37FA5D4B604C56E5`
SSDEEP | `768:LpaxcdH/fA13Yqt9WF2/IcWPFQsimJK9NMaUhsabrNiqbockhmWy1roKQDGFUf2/:LpEcBf6D9WFc8CX9GHhNFCmWaroKJUf`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/tr [OPTION]... SET1 [SET2]
Translate, squeeze, and/or delete characters from standard input,
writing to standard output.

  -c, -C, --complement    use the complement of SET1
  -d, --delete            delete characters in SET1, do not translate
  -s, --squeeze-repeats   replace each sequence of a repeated character
                            that is listed in the last specified SET,
                            with a single occurrence of that character
  -t, --truncate-set1     first truncate SET1 to length of SET2
      --help     display this help and exit
      --version  output version information and exit

SETs are specified as strings of characters.  Most represent themselves.
Interpreted sequences are:

  \NNN            character with octal value NNN (1 to 3 octal digits)
  \\              backslash
  \a              audible BEL
  \b              backspace
  \f              form feed
  \n              new line
  \r              return
  \t              horizontal tab
  \v              vertical tab
  CHAR1-CHAR2     all characters from CHAR1 to CHAR2 in ascending order
  [CHAR*]         in SET2, copies of CHAR until length of SET1
  [CHAR*REPEAT]   REPEAT copies of CHAR, REPEAT octal if starting with 0
  [:alnum:]       all letters and digits
  [:alpha:]       all letters
  [:blank:]       all horizontal whitespace
  [:cntrl:]       all control characters
  [:digit:]       all digits
  [:graph:]       all printable characters, not including space
  [:lower:]       all lower case letters
  [:print:]       all printable characters, including space
  [:punct:]       all punctuation characters
  [:space:]       all horizontal or vertical whitespace
  [:upper:]       all upper case letters
  [:xdigit:]      all hexadecimal digits
  [=CHAR=]        all characters which are equivalent to CHAR

Translation occurs if -d is not given and both SET1 and SET2 appear.
-t may be used only when translating.  SET2 is extended to length of
SET1 by repeating its last character as necessary.  Excess characters
of SET2 are ignored.  Only [:lower:] and [:upper:] are guaranteed to
expand in ascending order; used in SET2 while translating, they may
only be used in pairs to specify case conversion.  -s uses the last
specified SET, and occurs after translation or deletion.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/tr>
or available locally via: info '(coreutils) tr invocation'

```

### Usage (stderr):
```cmhg
/usr/bin/tr: missing operand after 'help'
Two strings must be given when translating.
Try '/usr/bin/tr --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\tr.exe |
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






MIT License. Copyright (c) 2020 Strontic.


