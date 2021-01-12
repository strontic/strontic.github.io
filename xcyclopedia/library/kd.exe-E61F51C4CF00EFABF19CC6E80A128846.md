---
title: kd.exe | Windows Kernel Debugger
excerpt: What is kd.exe?
---

# kd.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kd.exe`
* Description: Windows Kernel Debugger

## Hashes

Type | Hash
-- | --
MD5 | `E61F51C4CF00EFABF19CC6E80A128846`
SHA1 | `3FA35574F770704A0C4BE2FFCE290B49AEBCC76D`
SHA256 | `BD240F684F9E6D1BF03A88C75FA9C6D84BF84F823A9F0E6EBB7DA14B46748B16`
SHA384 | `0B039736A01D9605F5D41E7A1BDDD41CCF728A1DC99EB8D23587714F6FFBE20DB0A041DA3EC5D1BFB950932D7BE391F3`
SHA512 | `44742540622CAF25462EF990E0098F0C2589F21E8162A969C8C9D06DD8022121CE729D1BB58E4D7AF520AA8A4A49AD252CAC7ABCD50BC5B8452238A1DB923F7D`
SSDEEP | `3072:JO+DfFnbMwmoWATuajmhHmcLslY+20xcKM+8ForOvex:JO5slY+20xceGC`
IMP | `35AC0844A3992124484E6597B292EA5D`
PESHA1 | `AE345C63B49EF181A6B26C351C3EBD80B5B580FA`
PE256 | `CDA05CD498D2BC403D26C394A393264B4DBA74ECC7F22FD251B01911A1E472D7`

## Runtime Data

### Usage (stdout):
```cmhg
kd: Invalid switch 'h'
kd version 10.0.19041.1
usage: kd [options]

Options:

  -? displays command line help text
  -a<DllName> adds a default extension DLL
  -b break into kernel when connection is established
  -bonc request break in after session started
  -c "<command>" executes the given debugger command at the first debugger
                 prompt
  -cf <file> specifies a script file to be processed at the first debugger
             prompt
  -cfr <file> specifies a script file to be processed at the beginning of a
              session (including after .restart)
  -clines <#> number of lines of output history retrieved by a remote client
  -d breaks into kernel on first module load
  -ee <name> set default expression evaluator
             <name> can be MASM or C++
  -failinc causes incomplete symbol and module loads to fail
  -i <ImagePath> specifies the location of the executables that generated the
                 fault (see _NT_EXECUTABLE_IMAGE_PATH)
  -iu install dbgeng URL protocols
  -k <options> tells the debugger how to connect to the target
               net:port=n,key=w.x.y.z[,target=name] connects over the network
                    n: network port number, must match port assigned to target
                    w.x.y.z: key assigned to target machine
                    name: optional VM host machine name, used if debugging VMs
               usb:targetname=name connects over USB
                    name: USB target name assigned to target machine
               1394:channel=chan connects over 1394
                    chan: 1394 channel number, must match channel used at boot
               com:modem connects through a modem
               com:port=id,baud=rate connects through a COM port
                   id: com port name, of the form com2 or \\.\com12
                   rate: valid baudrate value, such as 57600
  -kl tells the debugger to connect to the local machine
  -kqm turns on kd quiet mode (equivalent to KDQUIET)
  -kx <options> tells the debugger to connect to an eXDI driver
  -lines requests that line number information be used if present
  -loga <logfile> appends to a log file
  -logau <logfile> appends to an Unicode log file
  -logo <logfile> opens a new log file
  -logou <logfile> opens a new Unicode log file
  -m serial port is a modem, watch for carrier detect
  -myob ignores version mismatches in DBGHELP.DLL
  -n enables verbose output from symbol handler
  -noio disables all I/O
  -noshell disables the .shell (!!) command
  -nosqm disables SQM data collection/upload.
  -QR \\<machine> queries for remote servers
  -r display registers
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
  -s disables lazy symbol loading
  -sdce pops up dialogs for critical errors
  -secure disallows operations dangerous for the host
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
  -t Enable KD transport related output (CTRL+D output) by default.
  -v enables verbose output from debugger
  -version shows the build version
  -wake <pid> wakes up a sleeping debugger and exits
  -x same as -b, except uses an initial command of eb NtGlobalFlag 9;g
  -y <SymbolsPath> specifies the symbol search path (see _NT_SYMBOL_PATH)
  -z <CrashDmpFile> specifies the name of a crash dump file to debug
  -zd <CrashDmpFile> specifies the name of a crash dump file to debugand
                     deletes that crash dump after the debugger has finished
                     using it
  -zp <CrashPageFile> specifies the name of a page.dmp file to use with a
                      crash dump

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
    _NT_DEBUG_BUS=1394
        Specifies the type of BUS the kernel debugger will use to communicate with the target

    _NT_DEBUG_1394_CHANNEL=number
        Specifies the channel to be used over the 1394 bus

    _NT_DEBUG_PORT=com[1|2|...]
        Specify which com port to use. (Default = com1)

    _NT_DEBUG_BAUD_RATE=baud rate
        Specify the baud rate used by debugging serial port. (Default = 19200)

    _NT_DEBUG_CACHE_SIZE=x
        If specified, gives the number of bytes cached on debugger side
        of kernel debugger serial connection (default is 102400).

    KDQUIET=anything
        If defined, disables obnoxious warning message displayed when user
        presses Ctrl-C


Control Keys:

     <Ctrl-A><Enter> Toggle BaudRate
     <Ctrl-B><Enter> Quit debugger
     <Ctrl-C>        Break into Target
     <Ctrl-D><Enter> Display debugger debugging information
     <Ctrl-F><Enter> Force a break into the kernel (same as Ctrl-C)
     <Ctrl-K><Enter> Toggle Initial Breakpoint
     <Ctrl-\><Enter> Debug Current debugger
     <Ctrl-R><Enter> Resynchronize target and host
     <Ctrl-V><Enter> Toggle Verbose mode
     <Ctrl-W><Enter> Print version information

```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\kd.exe |
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

* Original Filename: kd.exe
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
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\cdb.exe](cdb.exe-5017F8EFBE98513AEB75EAC57C1EA351.md) | 33
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\kd.exe](kd.exe-F6B9E69A6C0563D9338B4B73EBAAC34C.md) | 49
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntkd.exe](ntkd.exe-F468EEBF04739821C2B5C322754FA720.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Debuggers\arm\ntsd.exe](ntsd.exe-629EA12D527237B9CD945AC44C2DE80D.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\cdb.exe](cdb.exe-6E953EFEB12896AC0EC17D198902FAE1.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntkd.exe](ntkd.exe-BCABCBB87A2D6CF497D3FBF60BDD2543.md) | 46
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\ntsd.exe](ntsd.exe-329FBD3549A7D0FB1BF3A250ED8BDFB7.md) | 46




MIT License. Copyright (c) 2020 Strontic.


