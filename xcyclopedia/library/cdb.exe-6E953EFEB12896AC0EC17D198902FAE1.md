---
title: cdb.exe | Symbolic Debugger for Windows
excerpt: What is cdb.exe?
---

# cdb.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe`
* Description: Symbolic Debugger for Windows

## Hashes

Type | Hash
-- | --
MD5 | `6E953EFEB12896AC0EC17D198902FAE1`
SHA1 | `8FAF07B823ECE7885A4AFA7834364B8D931C0976`
SHA256 | `F63FE4CB27BB604707AB4E5A96BBF74D9940A278F488740DC72F6788B2CD422E`
SHA384 | `D8F0784655359F9777408731AE8C7ACB27F62A2630FB779D68C03CB6114F292111BCE11C52B3A23066313C42B4CE928F`
SHA512 | `2DA8C6FD8DD34E5673BB8AA266E2F45DF5DE5D71A14534720B33A495B1CAD34C196859F9FF02D7758D722035F954156ED6B9EA0A79523E084811C013C3849040`
SSDEEP | `3072:IW+k5FnbMomoWATua+Ah7aBvOu6eIgJ0xi+RB7M:IWoWvgJ0x1f7M`
IMP | `016D37B1E2EF9A623D81C30DB609F838`
PESHA1 | `3D1385F5614C5C71A707035FAED442AF1FEE0911`
PE256 | `A60BAD5A4E4138A303E58DED15ECDA10E7ED522F24538E80D9B14D53F203A71F`

## Runtime Data

### Usage (stdout):
```cmhg
cdb: Invalid switch 'h'
cdb version 10.0.19041.1
usage: cdb [options]

Options:

  <command-line> command to run under the debugger
  -? displays command line help text
  -- equivalent to -G -g -o -p -1 -d -pd
  -2 creates a separate console window for debuggee
  -a<DllName> adds a default extension DLL
  -bonc request break in after session started
  -c "<command>" executes the given debugger command at the first debugger
                 prompt
  -cf <file> specifies a script file to be processed at the first debugger
             prompt
  -cfr <file> specifies a script file to be processed at the beginning of a
              session (including after .restart)
  -cimp uses implicit create command line from a process server
  -clines <#> number of lines of output history retrieved by a remote client
  -d sends all debugger output to kernel debugger via DbgPrint
     input is requested from the kernel debugger via DbgPrompt
     -d cannot be used with debugger remoting
     -d can only be used when the kernel debugger is enabled
  -ddefer sends all debugger output to kernel debugger via DbgPrint
          input is requested from the kernel debugger via DbgPrompt unless
          there are remote clients that can provide input
          -ddefer can only be used when the kernel debugger is enabled
          -ddefer should be used with -server
  -ee <name> set default expression evaluator
             <name> can be MASM or C++
  -failinc causes incomplete symbol and module loads to fail
  -g ignores initial breakpoint in debuggee
  -G ignores final breakpoint at process termination
  -hd specifies that the debug heap should not be used for created processes. 
      This only works on Windows XP and later
  -i <ImagePath> specifies the location of the executables that generated the
                 fault (see _NT_EXECUTABLE_IMAGE_PATH)
  -iae install as AeDebug debugger
  -iaec <Command> install as AeDebug debugger with given command tail
  -isd sets the CREATE_IGNORE_SYSTEM_DEFAULT flag in STARTUPINFO.dwFlags
       during CreateProcess
  -iu install dbgeng URL protocols
  -kqm turns on kd quiet mode (equivalent to KDQUIET)
  -lines requests that line number information be used if present
  -loga <logfile> appends to a log file
  -logau <logfile> appends to an Unicode log file
  -logo <logfile> opens a new log file
  -logou <logfile> opens a new Unicode log file
  -myob ignores version mismatches in DBGHELP.DLL
  -n enables verbose output from symbol handler
  -netsym:yes|no allow or disallow loading symbols from a network path
  -noinh disables handle inheritance for created processes
  -noio disables all I/O
  -noshell disables the .shell (!!) command
  -nosqm disables SQM data collection/upload.
  -o debugs all processes launched by debuggee
  -openPrivateDumpByHandle <HANDLE> 
    specifies the handle of a crash dump file to debug
  -p <pid> specifies the decimal process ID to attach to
  -pb specifies that the debugger should not break in at attach
  -pd specifies that the debugger should automatically detach
  -pe specifies that any attach should be to an existing debug port
  -pn <name> specifies the name of the process to attach to
  -pr specifies that the debugger should resume on attach
  -psn <name> specifies the process to attach to by service name
  -premote <transport>:server=<name>,<params> 
    specifies the process server to connect to
    transport arguments are given as with remoting
  -pt <#> specifies the interrupt timeout
  -pv specifies that any attach should be noninvasive
  -pvr specifies that any attach should be noninvasive and nonsuspending
  -QR \\<machine> queries for remote servers
  -r <BreakErrorLevel> specifies the (0-3) error level to break on (see
                       SetErrorLevel)
  -remote <transport>:server=<name>,<params> 
    lets you connect to a debugger session started with -server
    must be the first argument if present
      transport: tcp | npipe | ssl | spipe | 1394 | com
      name: machine name on which the debug server was created
      params: parameters the debugger server was created with
        for tcp use:  port=<socket port #>
        for npipe use:  pipe=<name of pipe>
        for 1394 use:  channel=<channel #>
        for com use:  port=<COM port>,baud=<baud rate>,
                      channel=<channel #>
        for ssl and spipe see the documentation
      example: ... -remote npipe:server=yourmachine,pipe=foobar
  -robp allows breakpoints to be set in read-only memory
  -s disables lazy symbol loading
  -sdce pops up dialogs for critical errors
  -server <transport>:<params> 
    creates a debugger session other people can connect to
    must be the first argument if present
      transport: tcp | npipe | ssl | spipe | 1394 | com
      params: connection parameterization
        for tcp use:  port=<socket port #>
        for npipe use:  pipe=<name of pipe>
        for 1394 use:  channel=<channel #>
        for com use:  port=<COM port>,baud=<baud rate>,
                      channel=<channel #>
        for ssl and spipe see the documentation
      example: ... -server npipe:pipe=foobar
  -ses enables strict symbol loading
  -sflags <flags> sets symbol flags from a numeric argument
  -sicv ignores the CV record when symbol loading
  -sins ignores the symbol path environment variables
  -snc converts :: to __ in symbol names
  -snul disables automatic symbol loading for unqualified names
  -srcpath <SourcePath> specifies the source search path
  -sup enables full public symbol searches
  -t <PrintErrorLevel> specifies the (0-3) error level to display (see
                       SetErrorLevel)
  -v enables verbose output from debugger
  -version shows the build version
  -vf enables default ApplicationVerifier settings
  -vf:<opts> enables given ApplicationVerifier settings
  -w specifies to debug 16 bit applications in a separate VDM
  -wake <pid> wakes up a sleeping debugger and exits
  -x sets second-chance break on AV exceptions
  -x{e|d|n|i} <event> sets the break status for the specified event
  -y <SymbolsPath> specifies the symbol search path (see _NT_SYMBOL_PATH)
  -z <CrashDmpFile> specifies the name of a crash dump file to debug
  -zd <CrashDmpFile> specifies the name of a crash dump file to debugand
                     deletes that crash dump after the debugger has finished
                     using it
  -zp <CrashPageFile> specifies the name of a page.dmp file to use with a
                      crash dump
  -plmPackage <PlmPackageFullName> 
    specifies the UWP package to be started. Needs '-plmApp' or '-plmPackage'
    option, but not both.
  -plmApp <PlmApplicationName> 
    specifies the UWP application to be started. Needs '-plmPackage' option. 
  -plmBgTaskId <PlmBackgroundTaskId> 
    specifies the UWP background task to be activated. Needs '-plmPackage'
    option. 

Environment Variables:

    _NT_SYMBOL_PATH=[Drive:][Path]
        Specify symbol image path.

    _NT_ALT_SYMBOL_PATH=[Drive:][Path]
        Specify an alternate symbol image path.

    _NT_DEBUGGER_EXTENSION_PATH=[Drive:][Path]
        Specify a path which should be searched first for extensions dlls

    _NT_EXECUTABLE_IMAGE_PATH=[Drive:][Path]
        Specify executable image path.

    _NT_SOURCE_PATH=[Drive:][Path]
        Specify source file path.

    _NT_DEBUG_LOG_FILE_OPEN=filename
        If specified, all output will be written to this file from offset 0.

    _NT_DEBUG_LOG_FILE_APPEND=filename
        If specified, all output will be APPENDed to this file.

    _NT_DEBUG_HISTORY_SIZE=size
        Specifies the size of a server's output history in kilobytes

Control Keys:

     <Ctrl-B><Enter> Quit debugger
     <Ctrl-C>        Break into Target
     <Ctrl-F><Enter> Force a break into debuggee (same as Ctrl-C)
     <Ctrl-\><Enter> Debug Current debugger
     <Ctrl-V><Enter> Toggle Verbose mode
     <Ctrl-W><Enter> Print version information

```

### Child Processes:
conhost.exe help.exe

### Open Handles:

Path | Type
-- | --
(R-D)   C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\sym\wntdll.pdb\3CCC2398F623C3D0915D0E0ADC5714A71\wntdll.pdb | File
(R-D)   C:\Windows\System32\en-US\crypt32.dll.mui | File
(R-D)   C:\Windows\System32\en-US\mswsock.dll.mui | File
(RW-)   C:\Users\user | File
(RW-)   C:\Windows | File
(RWD)   C:\Windows\SysWOW64\ntdll.dll | File
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{6AF0698E-D558-4F6E-9B3C-3716689AF493}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*{DDF571F2-BE98-426D-8288-1A9A39C3FDA2}.2.ver0x0000000000000002.db | Section
\BaseNamedObjects\C:\*ProgramData\*Microsoft\*Windows\*Caches\*cversions.2 | Section
\BaseNamedObjects\F932B6C7-3A20-46A0-B8A0-8894AA421973 | Section
\BaseNamedObjects\NLS_CodePage_1252_3_2_0_0 | Section
\BaseNamedObjects\NLS_CodePage_437_3_2_0_0 | Section
\Sessions\1\BaseNamedObjects\UrlZonesSM_user | Section
\Sessions\1\BaseNamedObjects\windows_shell_global_counters | Section
\Sessions\1\BaseNamedObjects\windows_webcache_counters_{9B6AB5B3-91BC-4097-835C-EA2DEC95E9CC}_S-1-5-21-2047949552-857980807-821054962-504 | Section


### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe |
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

* Original Filename: CDB.Exe
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
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\cdb.exe](cdb.exe-5017F8EFBE98513AEB75EAC57C1EA351.md) | 44
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\kd.exe](kd.exe-F6B9E69A6C0563D9338B4B73EBAAC34C.md) | 41
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntkd.exe](ntkd.exe-F468EEBF04739821C2B5C322754FA720.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntsd.exe](ntsd.exe-629EA12D527237B9CD945AC44C2DE80D.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kd.exe](kd.exe-E61F51C4CF00EFABF19CC6E80A128846.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntkd.exe](ntkd.exe-BCABCBB87A2D6CF497D3FBF60BDD2543.md) | 43
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntsd.exe](ntsd.exe-329FBD3549A7D0FB1BF3A250ED8BDFB7.md) | 50

## Possible Misuse

*The following table contains possible examples of `cdb.exe` being misused. While `cdb.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `description: Launch 64-bit shellcode from a debugger script file using cdb.exe.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_cdb.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_cdb.yml) | `Image\|endswith: '\cdb.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Name: Cdb.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Command: cdb.exe -cf x64_calc.wds -o notepad.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `Description: Launch 64-bit shellcode from the x64_calc.wds file using cdb.exe.` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\cdb.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Cdb.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OtherMSBinaries/Cdb.yml) | `- Path: C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe` | 



MIT License. Copyright (c) 2020 Strontic.


