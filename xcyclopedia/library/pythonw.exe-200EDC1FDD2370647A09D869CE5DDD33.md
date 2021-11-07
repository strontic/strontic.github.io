---
title: pythonw.exe | Python
excerpt: What is pythonw.exe?
---

# pythonw.exe 

* File Path: `C:\Program Files\Inkscape\bin\pythonw.exe`
* Description: Python

## Screenshot

![pythonw.exe](screenshots/pythonw.exe-42FAD025D3A6ACC48AFED0D4FABA2C06-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `200EDC1FDD2370647A09D869CE5DDD33`
SHA1 | `35E3C9A914873291795A5EF67A2C60E7144C626E`
SHA256 | `D3C2FF52C22D7F2ABD3DBEE644311DEE3F1F2C44C6A3EEAE2D6477EBA1FAE067`
SHA384 | `DFE1937A3B51B578DFC43D8A4A1C40D5D32FD98CD6842FCB970506D4B7FB0AAEAE0F9FE577763DD5D23146D75421AED0`
SHA512 | `0210D31D8321ACBE102E201EC0846054B9CAC0F525461C499590ECB7405DD12CCC93A3EA412EBD5928CE1D0B2EDD752F849090889E2D1587C3C13FF538CC14C4`
SSDEEP | `1536:DTJHAIxHHWMpdPa5wiE21M8kJIGFvb1Cwz/k3s10I:JnwMpdCq/IM8uIGfJ/k3sK`
IMP | `1C979FEC02F87AADB9118FA823EE00EE`
PESHA1 | `FFA6F8D6FAFE3644553D5018101ADB44C5259309`
PE256 | `00C194658B7DF605B2D8C3E2AA46280898A320A21E9823DC4E7AA295E75DC486`

## Runtime Data

### Usage (stdout):
```cmhg
usage: C:\Program Files\Inkscape\bin\pythonw.exe [option] ... [-c cmd | -m mod | file | -] [arg] ...
Options and arguments (and corresponding environment variables):
-b     : issue warnings about str(bytes_instance), str(bytearray_instance)
         and comparing bytes/bytearray with str. (-bb: issue errors)
-B     : don't write .pyc files on import; also PYTHONDONTWRITEBYTECODE=x
-c cmd : program passed in as string (terminates option list)
-d     : debug output from parser; also PYTHONDEBUG=x
-E     : ignore PYTHON* environment variables (such as PYTHONPATH)
-h     : print this help message and exit (also --help)
-i     : inspect interactively after running script; forces a prompt even
         if stdin does not appear to be a terminal; also PYTHONINSPECT=x
-I     : isolate Python from the user's environment (implies -E and -s)
-m mod : run library module as a script (terminates option list)
-O     : remove assert and __debug__-dependent statements; add .opt-1 before
         .pyc extension; also PYTHONOPTIMIZE=x
-OO    : do -O changes and also discard docstrings; add .opt-2 before
         .pyc extension
-q     : don't print version and copyright messages on interactive startup
-s     : don't add user site directory to sys.path; also PYTHONNOUSERSITE
-S     : don't imply 'import site' on initialization
-u     : force the stdout and stderr streams to be unbuffered;
         this option has no effect on stdin; also PYTHONUNBUFFERED=x
-v     : verbose (trace import statements); also PYTHONVERBOSE=x
         can be supplied multiple times to increase verbosity
-V     : print the Python version number and exit (also --version)
         when given twice, print more information about the build
-W arg : warning control; arg is action:message:category:module:lineno
         also PYTHONWARNINGS=arg
-x     : skip first line of source, allowing use of non-Unix forms of #!cmd
-X opt : set implementation-specific option. The following options are available:

         -X faulthandler: enable faulthandler
         -X showrefcount: output the total reference count and number of used
             memory blocks when the program finishes or after each statement in the
             interactive interpreter. This only works on debug builds
         -X tracemalloc: start tracing Python memory allocations using the
             tracemalloc module. By default, only the most recent frame is stored in a
             traceback of a trace. Use -X tracemalloc=NFRAME to start tracing with a
             traceback limit of NFRAME frames
         -X showalloccount: output the total count of allocated objects for each
             type when the program finishes. This only works when Python was built with
             COUNT_ALLOCS defined
         -X importtime: show how long each import takes. It shows module name,
             cumulative time (including nested imports) and self time (excluding
             nested imports). Note that its output may be broken in multi-threaded
             application. Typical usage is python3 -X importtime -c 'import asyncio'
         -X dev: enable CPythons development mode, introducing additional runtime
             checks which are too expensive to be enabled by default. Effect of the
             developer mode:
                * Add default warning filter, as -W default
                * Install debug hooks on memory allocators: see the PyMem_SetupDebugHooks() C function
                * Enable the faulthandler module to dump the Python traceback on a crash
                * Enable asyncio debug mode
                * Set the dev_mode attribute of sys.flags to True
                * io.IOBase destructor logs close() exceptions
         -X utf8: enable UTF-8 mode for operating system interfaces, overriding the default
             locale-aware mode. -X utf8=0 explicitly disables UTF-8 mode (even when it would
             otherwise activate automatically)
         -X pycache_prefix=PATH: enable writing .pyc files to a parallel tree rooted at the
             given directory instead of to the code tree

--check-hash-based-pycs always|default|never:
    control how Python invalidates hash-based .pyc files
file   : program read from script file
-      : program read from stdin (default; interactive mode if a tty)
arg ...: arguments passed to program in sys.argv[1:]

Other environment variables:
PYTHONSTARTUP: file executed on interactive startup (no default)
PYTHONPATH   : ';'-separated list of directories prefixed to the
               default module search path.  The result is sys.path.
PYTHONHOME   : alternate <prefix> directory (or <prefix>;<exec_prefix>).
               The default module search path uses <prefix>/lib/pythonX.X.
PYTHONCASEOK : ignore case in 'import' statements (Windows).
PYTHONUTF8: if set to 1, enable the UTF-8 mode.
PYTHONIOENCODING: Encoding[:errors] used for stdin/stdout/stderr.
PYTHONFAULTHANDLER: dump the Python traceback on fatal errors.
PYTHONHASHSEED: if this variable is set to 'random', a random value is used
   to seed the hashes of str and bytes objects.  It can also be set to an
   integer in the range [0,4294967295] to get hash values with a
   predictable seed.
PYTHONMALLOC: set the Python memory allocators and/or install debug hooks
   on Python memory allocators. Use PYTHONMALLOC=debug to install debug
   hooks.
PYTHONCOERCECLOCALE: if this variable is set to 0, it disables the locale
   coercion behavior. Use PYTHONCOERCECLOCALE=warn to request display of
   locale coercion and locale compatibility warnings on stderr.
PYTHONBREAKPOINT: if this variable is set to 0, it disables the default
   debugger. It can be set to the callable of your debugger of choice.
PYTHONDEVMODE: enable the development mode.
PYTHONPYCACHEPREFIX: root directory for bytecode cache (pyc) files.

```

### Usage (stderr):
```cmhg
C:\Program Files\Inkscape\bin\pythonw.exe: can't open file 'C:\temp\strontic-xcyclopedia\notepad.exe': [Errno 13] Permission denied

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Inkscape\bin\libpython3.8.dll |
C:\Program Files\Inkscape\bin\pythonw.exe |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\sechost.dll |
C:\Windows\System32\USER32.dll |


## Signature

* Status: The file C:\Program Files\Inkscape\bin\pythonw.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: pythonw.exe
* Product Name: Python
* Company Name: Python Software Foundation
* File Version: 3.8.5
* Product Version: 3.8.5
* Language: Language Neutral
* Legal Copyright: Copyright  2001-2016 Python Software Foundation. Copyright  2000 BeOpen.com. Copyright  1995-2001 CNRI. Copyright  1991-1995 SMC.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/69
* VirusTotal Link: https://www.virustotal.com/gui/file/d3c2ff52c22d7f2abd3dbee644311dee3f1f2c44c6a3eeae2d6477eba1fae067/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Python310-32\Lib\venv\scripts\nt\pythonw.exe](pythonw.exe-4120303CF8654D6C7C02877CB49513C8.md) | 32
[C:\Program Files (x86)\Python310-32\pythonw.exe](pythonw.exe-B51D3765D11963CCA572DF6AE0C5E332.md) | 79
[C:\program files (x86)\Python38-32\pythonw.exe](pythonw.exe-22A73968F535CD1042A5AA301C2A537B.md) | 79
[C:\program files\Inkscape\bin\pythonw.exe](pythonw.exe-9E945D60BBB4991F4E436E7351F3D5C6.md) | 86
[C:\Program Files\Python310\Lib\venv\scripts\nt\pythonw.exe](pythonw.exe-75513C9847FDFFDDE9323C4CB464E04E.md) | 40
[C:\Program Files\Python310\pythonw.exe](pythonw.exe-9A4CC0D8E7007F7EF20CA585324E0739.md) | 77
[C:\Program Files\Python38\pythonw.exe](pythonw.exe-B37D95BFD4A51E2847F3EB6A2F8A427E.md) | 79




MIT License. Copyright (c) 2020-2021 Strontic.


