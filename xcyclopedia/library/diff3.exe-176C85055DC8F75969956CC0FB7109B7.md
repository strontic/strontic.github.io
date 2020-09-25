---
title: diff3.exe | 
excerpt: What is diff3.exe?
---

# diff3.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\diff3.exe`

## Hashes

Type | Hash
-- | --
MD5 | `176C85055DC8F75969956CC0FB7109B7`
SHA1 | `35851C32F44DADB0D7B309598D8E80181E6A3804`
SHA256 | `3E14BC154E1862A2F0D34C99D53EB2483DCC3EACF483A78D2B050A675C74B9D2`
SHA384 | `9F19A8CFF489D73AD35A3DB215A3D87AE22525BE397203FB05B90A634C1333CAB348E92F6240206AE4164CF772A06BD1`
SHA512 | `9566F33D4011B4C85B650169E8E4A5E9B29C565C8649C7249BD73D4ADEB3DE74A515DB63E7BE5FB5AE8D79F9CB4B7004FB67D05449933CC403A8991A980AEF7E`
SSDEEP | `1536:fNdqmdQ4DpweNAJedQzJsRscfUj0RB2WQgFuCSUfl:fP5dWeCY5ScMoRxQgFuCb`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\diff3.exe |
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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\diff3.exe](diff3.exe-94777C8FE4BA312BA5A6253A21C209BC.md) | 96




MIT License. Copyright (c) 2020 Strontic.


