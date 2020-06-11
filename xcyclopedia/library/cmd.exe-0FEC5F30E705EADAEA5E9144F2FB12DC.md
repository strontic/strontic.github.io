
# cmd.exe 

* File Path: `C:\Windows\SysWOW64\cmd.exe`
* Description: Windows Command Processor
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `0FEC5F30E705EADAEA5E9144F2FB12DC`
SHA1 | `A4D7B99EB716919BB47448E135D489A1100BA70C`
SHA256 | `614CA7B627533E22AA3E5C3594605DC6FE6F000B0CC2B845ECE47CA60673EC7F`
SHA384 | `71B8FA64B5256640E9CCE73A1B76FFBBBDF3FF4CD2772805145001A046AD0236EAF1AF7706A806BFFF4EA0B49206B8EC`
SHA415 | `39252E20797E13653E09142239BF31751193DAAE410107D6493E5BACE5F3688F3CF6CEE46986EA793FA7171805A61D6343CB3040EA4DDECDEC8507FB726A6A4B`
SSDEEP | `6144:6WrN5vc/THHkVaGrns6QSK7p6UAVmqa3XAmx:6GAT/GzeSKgUAVmqanA`

## Runtime Data

### Usage (stdout):
```Batchfile
Starts a new instance of the Windows command interpreter

CMD [/A | /U] [/Q] [/D] [/E:ON | /E:OFF] [/F:ON | /F:OFF] [/V:ON | /V:OFF]
    [[/S] [/C | /K] string]

/C      Carries out the command specified by string and then terminates
/K      Carries out the command specified by string but remains
/S      Modifies the treatment of string after /C or /K (see below)
/Q      Turns echo off
/D      Disable execution of AutoRun commands from registry (see below)
/A      Causes the output of internal commands to a pipe or file to be ANSI
/U      Causes the output of internal commands to a pipe or file to be
        Unicode
/T:fg   Sets the foreground/background colors (see COLOR /? for more info)
/E:ON   Enable command extensions (see below)
/E:OFF  Disable command extensions (see below)
/F:ON   Enable file and directory name completion characters (see below)
/F:OFF  Disable file and directory name completion characters (see below)
/V:ON   Enable delayed environment variable expansion using ! as the
        delimiter. For example, /V:ON would allow !var! to expand the
        variable var at execution time.  The var syntax expands variables
        at input time, which is quite a different thing when inside of a FOR
        loop.
/V:OFF  Disable delayed environment expansion.

Note that multiple commands separated by the command separator '&&'
are accepted for string if surrounded by quotes.  Also, for compatibility
reasons, /X is the same as /E:ON, /Y is the same as /E:OFF and /R is the
same as /C.  Any other switches are ignored.

If /C or /K is specified, then the remainder of the command line after
the switch is processed as a command line, where the following logic is
used to process quote (") characters:

    1.  If all of the following conditions are met, then quote characters
        on the command line are preserved:

        - no /S switch
        - exactly two quote characters
        - no special characters between the two quote characters,
          where special is one of: &<>()@^|
        - there are one or more whitespace characters between the
          two quote characters
        - the string between the two quote characters is the name
          of an executable file.

    2.  Otherwise, old behavior is to see if the first character is
        a quote character and if so, strip the leading character and
        remove the last quote character on the command line, preserving
        any text after the last quote character.

If /D was NOT specified on the command line, then when CMD.EXE starts, it
looks for the following REG_SZ/REG_EXPAND_SZ registry variables, and if
either or both are present, they are executed first.

    HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\AutoRun

        and/or

    HKEY_CURRENT_USER\Software\Microsoft\Command Processor\AutoRun

Command Extensions are enabled by default.  You may also disable
extensions for a particular invocation by using the /E:OFF switch.  You
can enable or disable extensions for all invocations of CMD.EXE on a
machine and/or user logon session by setting either or both of the
following REG_DWORD values in the registry using REGEDIT.EXE:

    HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\EnableExtensions

        and/or

    HKEY_CURRENT_USER\Software\Microsoft\Command Processor\EnableExtensions

to either 0x1 or 0x0.  The user specific setting takes precedence over
the machine setting.  The command line switches take precedence over the
registry settings.

In a batch file, the SETLOCAL ENABLEEXTENSIONS or DISABLEEXTENSIONS arguments
takes precedence over the /E:ON or /E:OFF switch. See SETLOCAL /? for details.

The command extensions involve changes and/or additions to the following
commands:

    DEL or ERASE
    COLOR
    CD or CHDIR
    MD or MKDIR
    PROMPT
    PUSHD
    POPD
    SET
    SETLOCAL
    ENDLOCAL
    IF
    FOR
    CALL
    SHIFT
    GOTO
    START (also includes changes to external command invocation)
    ASSOC
    FTYPE

To get specific details, type commandname /? to view the specifics.

Delayed environment variable expansion is NOT enabled by default.  You
can enable or disable delayed environment variable expansion for a
particular invocation of CMD.EXE with the /V:ON or /V:OFF switch.  You
can enable or disable delayed expansion for all invocations of CMD.EXE on a
machine and/or user logon session by setting either or both of the
following REG_DWORD values in the registry using REGEDIT.EXE:

    HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\DelayedExpansion

        and/or

    HKEY_CURRENT_USER\Software\Microsoft\Command Processor\DelayedExpansion

to either 0x1 or 0x0.  The user specific setting takes precedence over
the machine setting.  The command line switches take precedence over the
registry settings.

In a batch file the SETLOCAL ENABLEDELAYEDEXPANSION or DISABLEDELAYEDEXPANSION
arguments takes precedence over the /V:ON or /V:OFF switch. See SETLOCAL /?
for details.

If delayed environment variable expansion is enabled, then the exclamation
character can be used to substitute the value of an environment variable
at execution time.

You can enable or disable file name completion for a particular
invocation of CMD.EXE with the /F:ON or /F:OFF switch.  You can enable
or disable completion for all invocations of CMD.EXE on a machine and/or
user logon session by setting either or both of the following REG_DWORD
values in the registry using REGEDIT.EXE:

    HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\CompletionChar
    HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\PathCompletionChar

        and/or

    HKEY_CURRENT_USER\Software\Microsoft\Command Processor\CompletionChar
    HKEY_CURRENT_USER\Software\Microsoft\Command Processor\PathCompletionChar

with the hex value of a control character to use for a particular
function (e.g.  0x4 is Ctrl-D and 0x6 is Ctrl-F).  The user specific
settings take precedence over the machine settings.  The command line
switches take precedence over the registry settings.

If completion is enabled with the /F:ON switch, the two control
characters used are Ctrl-D for directory name completion and Ctrl-F for
file name completion.  To disable a particular completion character in
the registry, use the value for space (0x20) as it is not a valid
control character.

Completion is invoked when you type either of the two control
characters.  The completion function takes the path string to the left
of the cursor appends a wild card character to it if none is already
present and builds up a list of paths that match.  It then displays the
first matching path.  If no paths match, it just beeps and leaves the
display alone.  Thereafter, repeated pressing of the same control
character will cycle through the list of matching paths.  Pressing the
Shift key with the control character will move through the list
backwards.  If you edit the line in any way and press the control
character again, the saved list of matching paths is discarded and a new
one generated.  The same occurs if you switch between file and directory
name completion.  The only difference between the two control characters
is the file completion character matches both file and directory names,
while the directory completion character only matches directory names.
If file completion is used on any of the built in directory commands
(CD, MD or RD) then directory completion is assumed.

The completion code deals correctly with file names that contain spaces
or other special characters by placing quotes around the matching path.
Also, if you back up, then invoke completion from within a line, the
text to the right of the cursor at the point completion was invoked is
discarded.

The special characters that require quotes are:
     <space>
     &()[]{}^=;!'+,`~

```

### Usage (stderr):
```Batchfile

```

### Child Processes:
conhost.exe

## Signature

* Status: Signature verified.
* Serial: 33000000BCE120FDD27CC8EE930000000000BC
* Thumbprint: E85459B23C232DB3CB94C7A56D47678F58E8E51E
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Cmd.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.14393.0 (rs1_release.160715-1616)
* Product Version: 10.0.14393.0
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

MIT License. Copyright (c) 2020 Strontic.


