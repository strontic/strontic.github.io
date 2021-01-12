---
title: symchk.exe | Symbol Checker
excerpt: What is symchk.exe?
---

# symchk.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\symchk.exe`
* Description: Symbol Checker

## Hashes

Type | Hash
-- | --
MD5 | `727D672CDAA552D32CED03E0FEC83ABF`
SHA1 | `328781A60C82BA5396B939097C19DD5D26307F41`
SHA256 | `D5436169513098F45E53E9B67FCD9BCE47E6FFD40EF208272C34787BDA901F58`
SHA384 | `974D618E57D258F5511B2A3505C142472A2DAE864378B5106B43237966367ACB3F03341A83FF97E626D7225067F63002`
SHA512 | `719AB350CDCE9BE04FED2634AA17CE2A8346E2F9F361D2BB5AE0CD76FA86FC799B7996A9B4A8AD421856D03988E1F7F5BFB11CEE57419C93BBD4C188E83E451C`
SSDEEP | `768:PaOWfB1oeniNFEzjmZGkkgiS0FTmjVqUBnJfHIt/erxsm8X3YZLXFqH1KuX:PahC0mZGkhCqhHIt53WXFqH1n`
IMP | `6B2BED98B1905067E31143851D959636`
PESHA1 | `8E96204BD2B5819E1C2F52468BF1180E00368E53`
PE256 | `617B285B7913A52EECDD1ECE42D2440AB52A4551CEB2423F41399BDF8FE4678B`

## Runtime Data

### Usage (stdout):
```cmhg

symchk [/r] [/q] [Input options] <Filename> [/s <SymbolPath>] [options]

<Filename>      Name of the file or directory that contains the executables
                to perform symbol checking on.

/s <SymbolPath> Semi-colon separated list of symbol paths.  Symbol server
                paths are allowed.  To retrieve symbols to a downstream
                store, use "SRV*<downstream store>*<symbol server>" for
                the symbol path.  See the debugger documentation for more
                details.

/r              Perform recursive operations on the <Filename> specified.  The
                wildcard * can be used in filenames.

/q              Turn off all output options by default. Only output turned on
                with a output flag (see below) will be printed

--------------------------------------------------------------------------------
* Input options (choose only one):
/if <Filename>       Input is a file name.  Wildcards can be used to specify
                     the file name. Default if nothing is specified.
/id <DumpFile>       Input is a dump file.
/ih <HotFix>         Input is a self-extracting Hotfix cab.
/ie <ExeName>        Input is an application name that is currently running.
                     If the provided ExeName is '*', all currently running
                     processes will be checked.
/im <ManifestList>   Input is a manifest previously created using the /om <file>
                     option.
/ip <ProcessId>      Input is a process id. If the provided ProcessID is '*',
                     all currently running processes will be checked.
/it <TextFileList>   Input is a list of files, one per line, inside of a text
                     file.

--------------------------------------------------------------------------------
* Action options (choose only one):
/av  For each binary, Verify symbols exist and match.  Default.

--------------------------------------------------------------------------------
* Symbol checking options:
/cc  when symbol checking a hotfix cab, don't look for symbols inside the cab.
     By default, symchk will look for symbols in the cab as well as in the
     provided symbol path.
/cn  When symbol checking a running process, don't suspend that process.  User
     must ensure the process doesn't exit before symbol checking finishes.
/cs  Skip verifying that there is CodeView data. Symchk will verify that there
     IS codeview data by default.

- Symbol checking options for DBG information (choose one):
/ds  If image was built so that there is information that belongs in a DBG
     file, then this option verifies that the DBG information is stripped
     from the image and that the image points to a DBG file. Default.
/de  If image was built so that there is information that belongs in a DBG
     file, then this option verifies that the DBG information is STILL in the
     image and that the image does not point to a DBG file.
/dn  Verify that the image does not point to a DBG file and that DBG
     information is not in the image.

- Symbol checking options for PDB files:
/pa  Allow both public and private PDBs.  Default.
/pf  Verify that PDB files contain full source information.
/ps  Verify that PDB files are stripped and do not contain full source
     (private) information.
/pt  Verify that PDB files are stripped, but do have type information.  Some
     PDB files may be stripped but have type information added back in.

--------------------------------------------------------------------------------
* Symbol checking exclude options:
/ea <Filename>  Don't perform symbol checking for the binaries listed in the
                file specified.  <Filename> is a text file that contains the
                name of each binary, one per line.
/ee <Filename>  Perform symbol checking and report files that pass or are
                ignored, but don't report errors for binaries listed in the
                file specified.  <Filename> is a text file that contains the
                name of each binary, one per line.

--------------------------------------------------------------------------------
* Symbol path options:
/s[eprsu]  <SymbolPath>  Use <SymbolPath> as the search path.

   NOTE: If the '/s' option is not used, SymChk defaults to using the value
         in %_NT_SYMBOL_PATH%. If %_NT_SYMBOL_PATH% is not defined, then SymChk
         will default to:
           SRV*%SYSTEMROOT%\SYMBOLS*https://msdl.microsoft.com/download/symbols

* Modifiers (choose all that apply):
   e - check each path individually instead of checking all paths at once.
   p - force checking for private symbols.  Public symbols will be treated as
       not matching. (Implies the 'e' and 'u' modifiers.)
   r - Expand all non-symbol server elements in the specified path in order to do
       a deep search of the path. NOTE: This option may produce matches that will
       not occur inside the debugger since it modifies the symbol path specified.
   s - force checking for public (split) symbols. Private symbols will be
       treated as not matching. (Implies the 'e' and 'u' modifiers.)
   u - force updating of downstream stores. If the symbol path includes a
       downstream store, always re-check the server for the symbol. Only
       stores that are checked against will be updated.
   NOTE: The 's' and 'p' options are mutually exclusive. Only the last one
         present will be used.

--------------------------------------------------------------------------------
* Output options (choose all that apply):
/ob       Give the full path for binaries in the output messages for symbol
          checking.
/oc[x[a]] <Directory>    Create a flat symbols tree in <Directory> which
          contains all matching symbols. If 'x' is also used, copy the matching
          binaries into <Directory> as well. If 'a' is also present, the binary
          will always be copied to the flat symbol tree even if symbol checking
          failed.
/od       List all details.  Same as /oe /op /oi
/oe       List individual errors.  Errors will be sent to the output by default.
          This option is only needed when using /q
/oi       List each file that is ignored.
/op       List each file that passes.
/os       Give the full path for symbols in the output messages for symbol
          checking.
/ot       Send totals to the output.  Totals are sent to the output by default.
          This option is only needed when using /q
/ov       Print version information for checked binaries as well.

- Extended output options:
/ol <File>     In addition to the messages sent to standard out, write a
               file that contains a comma separated list of all the
               binaries and their symbols that pass symbol checking.
/om <Manifest> Print out a manifest file for later use with the '/im' option.
/v             Turn on verbose output mode.
--------------------------------------------------------------------------------
* Module filtering options when checking processes or dump files (choose one):
 /fm <Module>  Filter results to only include the named module.

--------------------------------------------------------------------------------
* Misc options
 /port     Old usage to new usage quick porting table
--------------------------------------------------------------------------------



```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\symchk.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SYMCHK.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\symchk.exe](symchk.exe-DF8295AEE5CCD3C96F293FCE780E4DFC.md) | 35




MIT License. Copyright (c) 2020 Strontic.


