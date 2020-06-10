
# doskey.exe 
* File Path: `C:\Windows\system32\doskey.exe`
* Description: Keyboard History Utility
* Comments: 

## Hashes
Type | Hash
-- | --
MD5 | `56BC572C8305144F4C498ABB7E8160A2`
SHA1 | `15E1995CEAC131956607103DB274DE7745AFCAB3`
SHA256 | `DBF2E1E11FD57DD0FBB2ACCB08778E6D838F272B3D5E814260044F0B0866B5A1`
SHA384 | `136F44DC02EF332B8D24F94CCC477F8892F000844B38303C142F1E28AD6D020D5C1EDBBC7D2517DCAFCA8C7983C537FF`
SHA415 | `F9A09DD562580E5440D2A084E1712B97AF804C72DA1B0700AE00BE4DBDBA97BF3012F3706CE2A23D2D6AB2EF8C3069A3D7491A76C032082D5D850BD50954E6BF`
SSDEEP | `384:fvRMoahJprnSidDNEUfXUQp5+5mMV+JUy+t7mPWXiWz:fvRMpfpbSCNPXTIR17m8`

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


