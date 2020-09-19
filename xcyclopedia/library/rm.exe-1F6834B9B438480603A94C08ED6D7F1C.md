---
title: rm.exe | 
---

# rm.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\rm.exe`

## Hashes

Type | Hash
-- | --
MD5 | `1F6834B9B438480603A94C08ED6D7F1C`
SHA1 | `1CDC5F0D578DC0BCAEE9962B810D22874A60DC5F`
SHA256 | `3B92192599CA78CC28216F31DC742D131C7D1B25AA05DFFFED4EDD47B985E8FD`
SHA384 | `A71A0FB40726AB3DEEFDDDEAE2B52D62C99BC84604A43FB624D9FBB380F699ED5D51E4CAEDBD243D1B886BA0DB7EB7A3`
SHA512 | `33733F03F2999FD2BCEDF714F6B7A87810809AE5AA461AEBDA34C9EDBCD046C3EB0831598E1A8E64AEF15951DD493706BFA3757C61337997CE7EDC08967B730B`
SSDEEP | `1536:oZNo44qisRl0K9oIgaSSvrWNfWQaFmjWUfX:+y4drRl0KWIgaSWrvQaFmj5`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/rm [OPTION]... [FILE]...
Remove (unlink) the FILE(s).

  -f, --force           ignore nonexistent files and arguments, never prompt
  -i                    prompt before every removal
  -I                    prompt once before removing more than three files, or
                          when removing recursively; less intrusive than -i,
                          while still giving protection against most mistakes
      --interactive[=WHEN]  prompt according to WHEN: never, once (-I), or
                          always (-i); without WHEN, prompt always
      --one-file-system  when removing a hierarchy recursively, skip any
                          directory that is on a file system different from
                          that of the corresponding command line argument
      --no-preserve-root  do not treat '/' specially
      --preserve-root[=all]  do not remove '/' (default);
                              with 'all', reject any command line argument
                              on a separate device from its parent
  -r, -R, --recursive   remove directories and their contents recursively
  -d, --dir             remove empty directories
  -v, --verbose         explain what is being done
      --help     display this help and exit
      --version  output version information and exit

By default, rm does not remove directories.  Use the --recursive (-r or -R)
option to remove each listed directory, too, along with all of its contents.

To remove a file whose name starts with a '-', for example '-foo',
use one of these commands:
  /usr/bin/rm -- -foo

  /usr/bin/rm ./-foo

Note that if you use rm to remove a file, it might be possible to recover
some of its contents, given sufficient expertise and/or time.  For greater
assurance that the contents are truly unrecoverable, consider using shred.

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/rm>
or available locally via: info '(coreutils) rm invocation'

```

### Usage (stderr):
```cmhg
rm: unknown option -- h
Try '/usr/bin/rm ./-help' to remove the file '-help'.
Try '/usr/bin/rm --help' for more information.

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


