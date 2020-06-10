
# doskey.exe 
* File Path: `C:\Windows\SysWOW64\doskey.exe`
* Description: Keyboard History Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `9280692881E517D6D52D0F8962907A8F`
SHA1 | `E3749E4132A93F277EA918668C9B1CAD7B27B6D5`
SHA256 | `618D1A19D8DED46AAD536216AFDD5E5FC9787807435BB63FA130AB712B268D0C`
SHA384 | `E0BDCEA4D399696969AE6F138EB51B1CAF86B768397CA4C0A25FB2CF8D27336D5E94774C72A9797D5BE9B95EBC31F141`
SHA415 | `CB390E6D446A204DC9B509BB09507DF4DF337EB38EF3E77BADCD7C7DA987742E83F9148FCFA90FD72FDCA9E15AC10727707F229D2D07C4107B3CAE8D3DAB3EB0`
SSDEEP | `384:FA/c2bZzWIkkkPIIxBmQTsHvXG6lBsWvWXiWz/q:y/VJWIkkkPIIxBmQ0sWc`

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
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: DOSKEY.EXE.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


