---
title: pyw.exe | Python
excerpt: What is pyw.exe?
---

# pyw.exe 

* File Path: `C:\Windows\pyw.exe`
* Description: Python

## Hashes

Type | Hash
-- | --
MD5 | `82526CE8444D6C0BD8EF8E331E5F73D6`
SHA1 | `13FD7710347F11E01BAC4C1033C5D8EFE770238A`
SHA256 | `00EE8AC047DA54994B169CC5C6C0F9C1FADE2B169AE002AE59AABEA3F1D7FF19`
SHA384 | `F628AC4A672A8002A5B1A146E2399B1F09F0040C35C21293A1395027B851B3868EBAF39BA21E3A52CDA72F6410C470EF`
SHA512 | `F4AEDB1A606E734B9917369BD3B2645E3BDCBCA7AAA615DB8B0BABB23612957ECFD483D1C380FDC51D7281240B06C3BB80E338093A3445623B1575958F1F2EC0`
SSDEEP | `12288:3fFkVE5OglEyM/UB7v14t677Vut+XG1ykwM+hGxsKBg:v5tlLM8Bx4tSVuUXG4fM+hGng`
IMP | `978742095DBF8D30B4557E295495F574`
PESHA1 | `B66339A3EB5B74B0CC165A2BC2EA101CD5049203`
PE256 | `E2BD9F6226EE41FF6CA8C66445BA4CFBF5080C65D37E0675BCD8E19EE7CBB715`

## Runtime Data

### Usage (stdout):
```cmhg
Python Launcher for Windows Version 3.10.150.1013

usage:
C:\Windows\pyw.exe [launcher-args] [python-args] [script [script-args]]

Launcher arguments:

-2     : Launch the latest Python 2.x version
-3     : Launch the latest Python 3.x version
-X.Y   : Launch the specified Python version
     The above all default to 64 bit if a matching 64 bit python is present.
-X.Y-32: Launch the specified 32bit Python version
-X-32  : Launch the latest 32bit Python X version
-X.Y-64: Launch the specified 64bit Python version
-X-64  : Launch the latest 64bit Python X version
-0  --list       : List the available pythons
-0p --list-paths : List with paths

 If no script is specified the specified interpreter is opened.
If an exact version is not given, using the latest version can be overridden by
any of the following, (in priority order):
 An active virtual environment
 A shebang line in the script (if present)
 With -2 or -3 flag a matching PY_PYTHON2 or PY_PYTHON3 Environment variable
 A PY_PYTHON Environment variable
 From [defaults] in py.ini in your %LOCALAPPDATA%\py.ini
 From [defaults] in py.ini beside py.exe (use `where py` to locate)

The following help text is from Python:

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
C:\Program Files\Python310\pythonw.exe: can't open file 'C:\\Users\\user\\help': [Errno 2] No such file or directory

```

### Loaded Modules:

Path |
-- |
C:\Windows\pyw.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `033ED5EDA065D1B8C91DFCF92A6C9BD8`
* Thumbprint: `C91DCECB3A92A17B063059200B20F5CE251B5A95`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Python Software Foundation, O=Python Software Foundation, L=Wolfeboro, S=New Hampshire, C=US

## File Metadata

* Original Filename: py.exe
* Product Name: Python
* Company Name: Python Software Foundation
* File Version: 3.10.0
* Product Version: 3.10.0
* Language: Language Neutral
* Legal Copyright: Copyright  2001-2021 Python Software Foundation. Copyright  2000 BeOpen.com. Copyright  1995-2001 CNRI. Copyright  1991-1995 SMC.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/00ee8ac047da54994b169cc5c6c0f9c1fade2b169ae002ae59aabea3f1d7ff19/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\py.exe](py.exe-058FBBDE5562FB56DAC231BA820AE9D5.md) | 75
[C:\Windows\py.exe](py.exe-25C3B6466E2AA4696B0FA9B94A11AE6C.md) | 57
[C:\Windows\pyw.exe](pyw.exe-6EE19289DAA2870459BB8155510B4769.md) | 61




MIT License. Copyright (c) 2020-2021 Strontic.


