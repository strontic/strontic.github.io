---
title: expr.exe | 
---

# expr.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\expr.exe`

## Hashes

Type | Hash
-- | --
MD5 | `491AB80E0A8FE0BEA1F3B2D815F7856C`
SHA1 | `E92FFF47284616B42F16C5A0812611C5868845F8`
SHA256 | `656A666EB436E73AF8EAE6BA4D789749A1237BE50BDED0DCF423152E8300FDA2`
SHA384 | `548DF5812572DD39A187A7C0A823F740A45879BF289035D2522E38AF7201AB8F562C8C4F16A93DA04386CC79A0E47729`
SHA512 | `3BA5D1894628F7D08664462350D08990CB393E8E50B5725C5A78E32504549C5C58C9CCDE3D32D16FC71329ACD9755C29E5858B7172987A3A0205C499DDF41D11`
SSDEEP | `3072:9ryBotf9xN5thg+EFcTCaSW2HiLw/FmK/:xyCgkAHiLw/FmK/`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/expr EXPRESSION
  or:  /usr/bin/expr OPTION

      --help     display this help and exit
      --version  output version information and exit

Print the value of EXPRESSION to standard output.  A blank line below
separates increasing precedence groups.  EXPRESSION may be:

  ARG1 | ARG2       ARG1 if it is neither null nor 0, otherwise ARG2

  ARG1 & ARG2       ARG1 if neither argument is null or 0, otherwise 0

  ARG1 < ARG2       ARG1 is less than ARG2
  ARG1 <= ARG2      ARG1 is less than or equal to ARG2
  ARG1 = ARG2       ARG1 is equal to ARG2
  ARG1 != ARG2      ARG1 is unequal to ARG2
  ARG1 >= ARG2      ARG1 is greater than or equal to ARG2
  ARG1 > ARG2       ARG1 is greater than ARG2

  ARG1 + ARG2       arithmetic sum of ARG1 and ARG2
  ARG1 - ARG2       arithmetic difference of ARG1 and ARG2

  ARG1 * ARG2       arithmetic product of ARG1 and ARG2
  ARG1 / ARG2       arithmetic quotient of ARG1 divided by ARG2
  ARG1 % ARG2       arithmetic remainder of ARG1 divided by ARG2

  STRING : REGEXP   anchored pattern match of REGEXP in STRING

  match STRING REGEXP        same as STRING : REGEXP
  substr STRING POS LENGTH   substring of STRING, POS counted from 1
  index STRING CHARS         index in STRING where any CHARS is found, or 0
  length STRING              length of STRING
  + TOKEN                    interpret TOKEN as a string, even if it is a
                               keyword like 'match' or an operator like '/'

  ( EXPRESSION )             value of EXPRESSION

Beware that many operators need to be escaped or quoted for shells.
Comparisons are arithmetic if both ARGs are numbers, else lexicographical.
Pattern matches return the string matched between \( and \) or null; if
\( and \) are not used, they return the number of characters matched or 0.

Exit status is 0 if EXPRESSION is neither null nor 0, 1 if EXPRESSION is null
or 0, 2 if EXPRESSION is syntactically invalid, and 3 if an error occurred.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/expr>
or available locally via: info '(coreutils) expr invocation'

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\expr.exe |
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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\expr.exe](expr.exe-491AB80E0A8FE0BEA1F3B2D815F7856C.md) | 100




MIT License. Copyright (c) 2020 Strontic.


