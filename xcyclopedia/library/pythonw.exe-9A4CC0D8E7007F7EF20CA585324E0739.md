---
title: pythonw.exe | Python
excerpt: What is pythonw.exe?
---

# pythonw.exe 

* File Path: `C:\Program Files\Python310\pythonw.exe`
* Description: Python

## Screenshot

![pythonw.exe](screenshots/pythonw.exe-42FAD025D3A6ACC48AFED0D4FABA2C06-1.png)

## Hashes

Type | Hash
-- | --
MD5 | `9A4CC0D8E7007F7EF20CA585324E0739`
SHA1 | `F3E5A2E477CAC4BAB85940A2158EED78F2D74441`
SHA256 | `040D121A3179F49CD3F33F4BC998BC8F78B7F560BFD93F279224D69E76A06E92`
SHA384 | `501E93D71B16991399C53E1724692C7D5A3D5E18EFD260B0992BEC50E1FAD9ECB221BA199F57329E0461D04DF17570C1`
SHA512 | `54636A48141804112F5B4F2FC70CB7C959A041E5743AEEDB5184091B51DAA1D1A03F0016E8299C0D56D924C6C8AE585E4FC864021081FFDF1E6F3EAB11DD43B3`
SSDEEP | `1536:9M/AhIxHHWMpdPa5wiE21M8kJIGFvb1Cwn/ZDs5yf:9M4SwMpdCq/IM8uIGfV/ZDso`
IMP | `5B30998B2EC74C8918984E16A74E5411`
PESHA1 | `D2701E90AA71A442C5081969568C8E20387C9F00`
PE256 | `6D7E93FDDABC340E64D64E36B1E80013BD78457C42703848180F2B38B628195C`

## Runtime Data

### Usage (stdout):
```cmhg
usage: C:\Program Files\Python310\pythonw.exe [option] ... [-c cmd | -m mod | file | -] [arg] ...
Options and arguments (and corresponding environment variables):
-b     : issue warnings about str(bytes_instance), str(bytearray_instance)
         and comparing bytes/bytearray with str. (-bb: issue errors)
-B     : don't write .pyc files on import; also PYTHONDONTWRITEBYTECODE=x
-c cmd : program passed in as string (terminates option list)
-d     : turn on parser debugging output (for experts only, only works on
         debug builds); also PYTHONDEBUG=x
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
         -X importtime: show how long each import takes. It shows module name,
             cumulative time (including nested imports) and self time (excluding
             nested imports). Note that its output may be broken in multi-threaded
             application. Typical usage is python3 -X importtime -c 'import asyncio'
         -X dev: enable CPython's "development mode", introducing additional runtime
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
         -X warn_default_encoding: enable opt-in EncodingWarning for 'encoding=None'

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
               The default module search path uses <prefix>\python{major}{minor}.
PYTHONPLATLIBDIR : override sys.platlibdir.
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
PYTHONWARNDEFAULTENCODING: enable opt-in EncodingWarning for 'encoding=None'.

```

### Usage (stderr):
```cmhg
UnicodeDecodeError: 'utf-8' codec can't decode byte 0xbe in position 0: invalid start byte

```

### Loaded Modules:

Path |
-- |
C:\Program Files\Python310\python310.dll |
C:\Program Files\Python310\pythonw.exe |
C:\Program Files\Python310\VCRUNTIME140.dll |
C:\Windows\System32\ADVAPI32.dll |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\System32\msvcrt.dll |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\RPCRT4.dll |
C:\Windows\System32\ucrtbase.dll |
C:\Windows\SYSTEM32\VERSION.dll |
C:\Windows\System32\WS2_32.dll |


## Signature

* Status: Signature verified.
* Serial: `033ED5EDA065D1B8C91DFCF92A6C9BD8`
* Thumbprint: `C91DCECB3A92A17B063059200B20F5CE251B5A95`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Python Software Foundation, O=Python Software Foundation, L=Wolfeboro, S=New Hampshire, C=US

## File Metadata

* Original Filename: pythonw.exe
* Product Name: Python
* Company Name: Python Software Foundation
* File Version: 3.10.0
* Product Version: 3.10.0
* Language: Language Neutral
* Legal Copyright: Copyright  2001-2021 Python Software Foundation. Copyright  2000 BeOpen.com. Copyright  1995-2001 CNRI. Copyright  1991-1995 SMC.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/040d121a3179f49cd3f33f4bc998bc8f78b7f560bfd93f279224d69e76a06e92/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Python310-32\Lib\venv\scripts\nt\pythonw.exe](pythonw.exe-4120303CF8654D6C7C02877CB49513C8.md) | 33
[C:\Program Files (x86)\Python310-32\pythonw.exe](pythonw.exe-B51D3765D11963CCA572DF6AE0C5E332.md) | 88
[C:\program files (x86)\Python38-32\pythonw.exe](pythonw.exe-22A73968F535CD1042A5AA301C2A537B.md) | 77
[C:\Program Files\Inkscape\bin\pythonw.exe](pythonw.exe-200EDC1FDD2370647A09D869CE5DDD33.md) | 77
[C:\program files\Inkscape\bin\pythonw.exe](pythonw.exe-9E945D60BBB4991F4E436E7351F3D5C6.md) | 77
[C:\Program Files\Python310\Lib\venv\scripts\nt\pythonw.exe](pythonw.exe-75513C9847FDFFDDE9323C4CB464E04E.md) | 44
[C:\Program Files\Python38\pythonw.exe](pythonw.exe-B37D95BFD4A51E2847F3EB6A2F8A427E.md) | 75




MIT License. Copyright (c) 2020-2021 Strontic.


