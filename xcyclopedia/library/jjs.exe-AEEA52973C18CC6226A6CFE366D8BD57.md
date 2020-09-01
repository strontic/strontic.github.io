---
title: jjs.exe | OpenJDK Platform binary
---

# jjs.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jjs.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `AEEA52973C18CC6226A6CFE366D8BD57`
SHA1 | `8B3212DF2AC51195248DF79869DFA221474E4894`
SHA256 | `537E9EAE010ED2EE0BAAF7140E43A57EC4E2C6430658065E185752D7242D23B3`
SHA384 | `D007B379764FC60A8E6184677EB2BC22F85C4680CDCA7973063BD0CC5120C9643228C9C66E7A8BE573EF118C0A8BBE3F`
SHA512 | `267E6FA9516CCD01F73D472B36BB60FB262EC206FE57C00DE83ED515A45746B15EEBDBBE983A3A889E1E6590EDA24667A9D4CF8A2DB2EB57B414F52EA800F1CB`
SSDEEP | `384:nb9bCPqn7KaX7nBbFcpA5APaK6jSLpGDgf2hT:JuPeLxFAA5vKgQ4Uf2hT`

## Runtime Data

### Usage (stderr):
```Batchfile
jjs [<options>] <files> [-- <arguments>]
	-D (-Dname=value. Set a system property. This option can be repeated.)

	--add-modules (--add-modules modules. Specify the root user java modules.)

	-cp, -classpath (-cp path. Specify where to find user class files.)

	-doe, -dump-on-error (Dump a stack trace on errors.)
		param: [true|false]   default: false

	-fv, -fullversion (Print full version info of Nashorn.)
		param: [true|false]   default: false

	-fx (Launch script as an fx application.)
		param: [true|false]   default: false

	-h, --help (Print this help message.)
		param: [true|false]   default: false

	--language (Specify ECMAScript language version.)
		param: [es5|es6]   default: es5

	--module-path (--module-path path. Specify where to find user java modules.)

	--no-deprecation-warning (Do not show nashorn deprecation warning.)
		param: [true|false]   default: false

	-ot, --optimistic-types (Use optimistic type assumptions with deoptimizing recompilation. 
	                        This makes the compiler try, for any program symbol whose type cannot 
	                        be proven at compile time, to type it as narrow and primitive as 
	                        possible. If the runtime encounters an error because symbol type 
	                        is too narrow, a wider method will be generated until steady stage 
	                        is reached. While this produces as optimal Java Bytecode as possible, 
	                        erroneous type guesses will lead to longer warmup. Optimistic typing 
	                        is currently enabled by default, but can be disabled for faster 
	                        startup performance.)
		param: [true|false]   default: true

	-scripting (Enable scripting features.)
		param: [true|false]   default: false

	-strict (Run scripts in strict mode.)
		param: [true|false]   default: false

	-t, -timezone (Set timezone for script execution.)
		param: <timezone>   default: America/New_York

	-v, -version (Print version info of Nashorn.)
		param: [true|false]   default: false


```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jjs.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jjs.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jjs.exe](jjs.exe-769519D4B82D6F7FF7C779C74BCA82CF.md) | 60
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jjs.exe](jjs.exe-4BBAAAD09CA86598C402F02D56D521A7.md) | 61




MIT License. Copyright (c) 2020 Strontic.


