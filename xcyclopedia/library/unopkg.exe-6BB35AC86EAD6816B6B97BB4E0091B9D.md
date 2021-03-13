---
title: unopkg.exe | 
excerpt: What is unopkg.exe?
---

# unopkg.exe 

* File Path: `C:\program files\LibreOffice\program\unopkg.exe`

## Hashes

Type | Hash
-- | --
MD5 | `6BB35AC86EAD6816B6B97BB4E0091B9D`
SHA1 | `84806C9D7F5630B8CBFACC0E5C72A59534999F25`
SHA256 | `9EBE98AF179E3399ED296334B8350754D40D1C3C21923592AEC2122F93C7B06A`
SHA384 | `4378A28B8215BCE68E9D874654D29765B027C079C0E8CD7D13337422EAE866113EAF508FFB1B205062CF132002EDA243`
SHA512 | `4BAB52B532C222972D52AB60F24C2CB24C4BE48B1BAB19EE0A12B522A4D46178D3FA0E0442E309E822399E8625E84A8148169F3DB3DC40CCE927061CABEFCBC7`
SSDEEP | `3072:5cGmpcSSwi3ofraMcSC/Ka2O7Rvv4TOEuOL:5cGmpcSSwMofuQq7RY6m`

## Runtime Data

### Usage (stdout):
```cmhg

using: unopkg add <options> extension-path...
       unopkg validate <options> extension-identifier...
       unopkg remove <options> extension-identifier...
       unopkg list <options> extension-identifier...
       unopkg reinstall <options>
       unopkg gui
       unopkg -V
       unopkg -h

sub-commands:
 add                     add extension
 validate                checks the prerequisites of an installed extension and
                         registers it if possible
 remove                  remove extensions by identifier
 reinstall               expert feature: reinstall all deployed extensions
 list                    list information about deployed extensions
 gui                     raise Extension Manager Graphical User Interface (GUI)

options:
 -h, --help              this help
 -V, --version           version information
 -v, --verbose           verbose output
 -f, --force             force overwriting existing extensions
 -s, --suppress-license  prevents showing the license
 --log-file <file>       custom log file; default: <cache-dir>/log.txt
 --shared                expert feature: operate on shared installation
                                         deployment context;
                                         run only when no concurrent Office
                                         process(es) are running!
 --bundled               expert feature: operate on bundled extensions. Only
                                         works with list, validate, reinstall;
 --deployment-context    expert feature: explicit deployment context
     <context>

To learn more about the Extension Manager and extensions, see:
http://wiki.openoffice.org/wiki/Documentation/DevGuide/Extensions/Extensions


```

### Usage (stderr):
```cmhg
ERROR: Unknown sub-command: '-help'. Use unopkg --help (short -h) to print all options.


```

### Loaded Modules:

Path |
-- |
C:\program files\LibreOffice\program\unopkg.exe |
C:\Windows\System32\GDI32.dll |
C:\Windows\System32\gdi32full.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcp_win.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\SHELL32.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\System32\USER32.dll |
C:\Windows\System32\win32u.dll |


## Signature

* Status: Signature verified.
* Serial: `049F5EBAA6B29CF6C79003917374242E`
* Thumbprint: `059BD34C72E8BE4FB19A80877268097C87F7D487`
* Issuer: CN=Certum Code Signing CA SHA2, OU=Certum Certification Authority, O=Unizeto Technologies S.A., C=PL
* Subject: E=info@documentfoundation.org, C=DE, S=Berlin, L=Berlin, OU=LibreOffice Build Team, O=The Document Foundation, CN=The Document Foundation

## File Metadata

* Original Filename: unopkg.exe
* Product Name: LibreOffice
* Company Name: The Document Foundation
* File Version: 7.0.0.3
* Product Version: 7.0.0.3
* Language: English (United States)
* Legal Copyright: Copyright  2000-2020 by LibreOffice contributors. All rights reserved.


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\LibreOffice\program\soffice.exe](soffice.exe-F1ACF6DB37A26E2EA498DBDCFDCF8F73.md) | 83




MIT License. Copyright (c) 2020-2021 Strontic.


