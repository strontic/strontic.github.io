
# doskey.exe 

* File Path: `C:\WINDOWS\SysWOW64\doskey.exe`
* Description: Keyboard History Utility
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `9B3BD6541888943BAF634BD68425AE2C`
SHA1 | `557619B41D36C4A7288536C79054B8800A14F163`
SHA256 | `38AE625F758F29C77B225A152D970F6472896CD9763A958AD5101C9C08682803`
SHA384 | `48D4474D476938314D1553623FC4AA652C3183FA098367A801D66DFE97D7B2780F8227CDC01C37E0C7329373C04856B8`
SHA415 | `697170A3EA437EAE0A840182013C14A594B3C3F167745E943F7BD3EA4102FD079B2AA80C6D6A2ED779F1FFA98D799A0D770E45BCA5CB8F875913ADDBA3BE8808`
SSDEEP | `192:SggeWYfxnntxPYYtPg+pplkhazuApmg2Y8PqFDDUkSVltSWRRkHWpiWDwvN:TlnntxPTlgZAKAog2DPqCDMHWpiWDI`

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

* Original Filename: DOSKEY.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.18362.1 (WinBuild.160101.0800)
* Product Version: 10.0.18362.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


