---
title: rm.exe | 
excerpt: What is rm.exe?
---

# rm.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\rm.exe`

## Hashes

Type | Hash
-- | --
MD5 | `F8D439C840174EDAD57E00BD828A00E2`
SHA1 | `3C6C43EE97675F755A534DC8E9B129A00BFA0BF3`
SHA256 | `942D66730E4E1D1AEE1BA736F79303EB9C9A4DC21ED029E03CB468CCB432B1AC`
SHA384 | `D301E68003B28B4FC8CF8C8E97E066E75456C219524C87F5B925F290717B1667585AC73084A11AF889F65DFF970B5E5B`
SHA512 | `A9D76DDDB447B0D7A28348278E3FAC0631FAC28BB333F85349FD08F67A57A1B0D3FDB21D0727A2699735CA82D897A5C749AA0F427E1BBD48A9B22FB3480A235C`
SSDEEP | `1536:rWI/2YX6r2iyvWRVyf2GJEX9KW76FmIy2Uf:r/HXHiyvWDyfRJEXJ76FmIy`

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

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\rm.exe |
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


