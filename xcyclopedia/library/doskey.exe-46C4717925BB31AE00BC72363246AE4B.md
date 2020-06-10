
# doskey.exe 
* File Path: `C:\WINDOWS\system32\doskey.exe`
* Description: Keyboard History Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `46C4717925BB31AE00BC72363246AE4B`
SHA1 | `3050E292AF60839DF1136AD394AD9C359FFC5C9F`
SHA256 | `4EC657B1F81E765637D6337E8F18159418921068DDFFAFD4D103E2F4C36C557D`
SHA384 | `473C5686F5FB554D6A0D3C0659376413880D526DC2E833ADA22863B3C4FAAAEEF35D2D2F1799961EF88AC5E400C26438`
SHA415 | `57F9E3582C1447AB72EAA8166C356929772D1C71D6F738D0FC6C9F09F321F8B82BA55CB404B330BE8CA14B883C483F5517925791B9EB712AE04D5BACABA69878`
SSDEEP | `384:JvozV3t9ZT7ziTnMk12gwv04hWgtzctzmK/PYjMBdnWpiW:JvozzrT7ziTnMo2gY0KWCgtugBdW`

## Runtime Data
### Usage (stdout):
```Batchfile
Edits command lines, recalls Windows commands, and creates macros.

DOSKEY [/REINSTALL] [/LISTSIZE=size] [/MACROS[:ALL | :exename]]
  [/HISTORY] [/INSERT | /OVERSTRIKE] [/EXENAME=exename] [/MACROFILE=filename]
  [macroname=[text]]

  /REINSTALL          Installs a new copy of Doskey.
  /LISTSIZE=size      Sets size of command history buffer.
  /MACROS             Displays all Doskey macros.
  /MACROS:ALL         Displays all Doskey macros for all executables which have
                      Doskey macros.
  /MACROS:exename     Displays all Doskey macros for the given executable.
  /HISTORY            Displays all commands stored in memory.
  /INSERT             Specifies that new text you type is inserted in old text.
  /OVERSTRIKE         Specifies that new text overwrites old text.
  /EXENAME=exename    Specifies the executable.
  /MACROFILE=filename Specifies a file of macros to install.
  macroname           Specifies a name for a macro you create.
  text                Specifies commands you want to record.

UP and DOWN ARROWS recall commands; ESC clears command line; F7 displays
command history; ALT+F7 clears command history; F8 searches command
history; F9 selects a command by number; ALT+F10 clears macro definitions.

The following are some special codes in Doskey macro definitions:
$T     Command separator.  Allows multiple commands in a macro.
$1-$9  Batch parameters.  Equivalent to %1-%9 in batch programs.
$*     Symbol replaced by everything following macro name on command line.

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: 330000023241FB59996DCC4DFF000000000232
* Thumbprint: FF82BC38E1DA5E596DF374C53E3617F7EDA36B06
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DOSKEY.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


