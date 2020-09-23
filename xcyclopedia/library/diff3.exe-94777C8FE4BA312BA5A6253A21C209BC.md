---
title: diff3.exe | 
excerpt: What is diff3.exe?
---

# diff3.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\diff3.exe`

## Hashes

Type | Hash
-- | --
MD5 | `94777C8FE4BA312BA5A6253A21C209BC`
SHA1 | `B67526C54F6BA9AB21B7AA6459971AFB05A60119`
SHA256 | `1E2BA7753B3B7F03B2171DC12FEFDBFA582B3762B60779DC942BCFE13F3A6A01`
SHA384 | `25FD9855F63B162FBA4B1EEA9BE8D1A93448CF1760513F9E6C0A0C9830CE211C54E3ED7869CA74CF4033F0B2A74BBCC3`
SHA512 | `0F7595AB2F469CF399D419AF403493F928403BC93F482219DF50F78FFC2763D281226640A1C5B7B553BDFDA76F749E4857A545F588CB059B5F1D106B83751909`
SSDEEP | `1536:aNdqmdQ4DpweNAJedQzJsRscfUj0RB2WQgFuC4Uf:aP5dWeCY5ScMoRxQgFuC`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/diff3 [OPTION]... MYFILE OLDFILE YOURFILE
Compare three files line by line.

Mandatory arguments to long options are mandatory for short options too.
  -A, --show-all              output all changes, bracketing conflicts

  -e, --ed                    output ed script incorporating changes
                                from OLDFILE to YOURFILE into MYFILE
  -E, --show-overlap          like -e, but bracket conflicts
  -3, --easy-only             like -e, but incorporate only nonoverlapping changes
  -x, --overlap-only          like -e, but incorporate only overlapping changes
  -X                          like -x, but bracket conflicts
  -i                          append 'w' and 'q' commands to ed scripts

  -m, --merge                 output actual merged file, according to
                                -A if no other options are given

  -a, --text                  treat all files as text
      --strip-trailing-cr     strip trailing carriage return on input
  -T, --initial-tab           make tabs line up by prepending a tab
      --diff-program=PROGRAM  use PROGRAM to compare files
  -L, --label=LABEL           use LABEL instead of file name
                                (can be repeated up to three times)

      --help                  display this help and exit
  -v, --version               output version information and exit

The default output format is a somewhat human-readable representation of
the changes.

The -e, -E, -x, -X (and corresponding long) options cause an ed script
to be output instead of the default.

Finally, the -m (--merge) option causes diff3 to do the merge internally
and output the actual merged file.  For unusual input, this is more
robust than using ed.

If a FILE is '-', read standard input.
Exit status is 0 if successful, 1 if conflicts, 2 if trouble.

Report bugs to: bug-diffutils@gnu.org
GNU diffutils home page: <http://www.gnu.org/software/diffutils/>
General help using GNU software: <https://www.gnu.org/gethelp/>

```

### Usage (stderr):
```cmhg
/usr/bin/diff3: missing operand after 'help'
/usr/bin/diff3: Try '/usr/bin/diff3 --help' for more information.

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
[C:\Users\WDAGUtilityAccount\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\diff3.exe](diff3.exe-176C85055DC8F75969956CC0FB7109B7.md) | 96




MIT License. Copyright (c) 2020 Strontic.


