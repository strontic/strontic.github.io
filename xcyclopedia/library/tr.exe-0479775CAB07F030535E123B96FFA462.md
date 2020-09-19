---
title: tr.exe | 
---

# tr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\tr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `0479775CAB07F030535E123B96FFA462`
SHA1 | `539AABD59AD7FF469B81A28B2EDE0A866B82ECB1`
SHA256 | `B2207BD1F58D2B25CCE47165DA93989C7828A3600E524F5E67A7CAE26D100C30`
SHA384 | `2C01EBCC4627C9EE17BB914A636B5813CF6F5025B94BA3573A0F31A89A1A3B779BE3EAD4FD9046CE7D5A9BCC3336BA3E`
SHA512 | `D2D888C6CC37A7EDC01CB48BB844015F0FE4FF9ED4AAC55C4BBACF4127C8630E6FF0EDF24F7E9DA49729BD6BD01F1B26DE6E56CC25E7CCC42BC249CB8124587F`
SSDEEP | `768:s7PW/5lsw6E6gakYVCv8nBaUhsabYViqbo7qcccccccccccccccccccccccccccU:KWhlsBgXYi8BHhNXdO6W6cYoteuUf`

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


