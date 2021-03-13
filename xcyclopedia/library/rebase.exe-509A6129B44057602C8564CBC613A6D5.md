---
title: rebase.exe | 
excerpt: What is rebase.exe?
---

# rebase.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\rebase.exe`

## Hashes

Type | Hash
-- | --
MD5 | `509A6129B44057602C8564CBC613A6D5`
SHA1 | `8B52B3453F583CBCD01C86102703C5D3A3A7E974`
SHA256 | `43CEA8E89B681AA19114C3558DCF58270E179DA88E7D9DD1690651815CB9BB78`
SHA384 | `6453BEAE15646160D012649ECCED79482D01F2B7D92DA53F4362D01A2A07D32A42E63E49B525F018F574FB88C8C74CFD`
SHA512 | `C6409A73D9E2205EE998FFCBE66CAEEA76915E990C78E8CB91F182C5571B7B6C6D558A8597DDFBD45BD2A80A19ACDF7D5AC2B369654ED08A86698179F1FAB5D6`
SSDEEP | `24576:vM1ooGYlsMnB/RtTjgqbWqNZG1HHHHHHHlbfHHHpHHHkrkznb5:vM16YlsMnB/PjgqbWugbXznb5`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: rebase [OPTIONS] [FILE]...
Rebase PE files, usually DLLs, to a specified address or address range.

  -4, --32                Only rebase 32 bit DLLs.
  -8, --64                Only rebase 64 bit DLLs.  This is the default.
  -b, --base=BASEADDRESS  Specifies the base address at which to start rebasing.
  -s, --database          Utilize the rebase database to find unused memory
                          slots to rebase the files on the command line to.
                          (Implies -d).
                          If -b is given, too, the database gets recreated.
  -O, --oblivious         Do not change any files already in the database
                          and do not record any changes to the database.
                          (Implies -s).
  -i, --info              Rather then rebasing, just print the current base
                          address and size of the files.  With -s, use the
                          database.  The files are ordered by base address.
                          A '*' at the end of the line is printed if a
                          collisions with an adjacent file is detected.

  One of the options -b, -s or -i is mandatory.  If no rebase database exists
  yet, -b is required together with -s.

  -d, --down              Treat the BaseAddress as upper ceiling and rebase
                          files top-down from there.  Without this option the
                          files are rebased from BaseAddress bottom-up.
                          With the -s option, this option is implicitly set.
  -n, --no-dynamicbase    Remove PE dynamicbase flag from rebased DLLs, if set.
  -o, --offset=OFFSET     Specify an additional offset between adjacent DLLs
                          when rebasing.  Default is no offset.
  -t, --touch             Use this option to make sure the file's modification
                          time is bumped if it has been successfully rebased.
                          Usually rebase does not change the file's time.
  -T, --filelist=FILE     Also rebase the files specified in FILE.  The format
                          of FILE is one DLL per line.
  -q, --quiet             Be quiet about non-critical issues.
  -v, --verbose           Print some debug output.
  -V, --version           Print version info and exit.
  -h, --help, --usage     This help.

```

### Usage (stderr):
```cmhg
help: skipped because not rebaseable

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
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\rebase.exe](rebase.exe-9D64CD9BC0B1BB328E9B97F4D26F4231.md) | 97




MIT License. Copyright (c) 2020-2021 Strontic.


