---
title: jjs.exe | OpenJDK Platform binary
excerpt: What is jjs.exe?
---

# jjs.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `50283CF0315C0D9CB58A0C666D5CEFF7`
SHA1 | `745CFA70FC6061204177AF24970A676C2A782567`
SHA256 | `09EEA7184228DEA857294B205E0E096E682AD3D17316FF8EB7332AB51D9BD5D6`
SHA384 | `534D269CE43B47C3BE8D0A53AB0606A50FC16B0C48FDE8AF2ADF2E7616D39634C5A56A98FA1B164985C7F2B652C90E2D`
SHA512 | `2092218FB933ABDC41A37D69AE3912A7ED1176202BD12E101C6A58E274D51EF456FE24793E5BF6B39430A43C62260B217702F4170317EAB242FAE0479B4F0EEA`
SSDEEP | `384:Gpsu5BnqqGmSHhV8dKeeF4Sz8K6jSXayDgf2hv:GpsAnTS/8dXeF+KgaUf2hv`

## Runtime Data

### Usage (stderr):
```cmhg
jjs [<options>] <files> [-- <arguments>]
	-D (-Dname=value. Set a system property. This option can be repeated.)

	-cp, -classpath (-cp path. Specify where to find user class files.)

	-doe, -dump-on-error (Dump a stack trace on errors.)
		param: [true|false]   default: false

	-fv, -fullversion (Print full version info of Nashorn.)
		param: [true|false]   default: false

	-fx (Launch script as an fx application.)
		param: [true|false]   default: false

	-h, -help (Print help for command line flags.)
		param: [true|false]   default: false

	--language (Specify ECMAScript language version.)
		param: [es5|es6]   default: es5

	-ot, --optimistic-types (Use optimistic type assumptions with deoptimizing recompilation. 
	                        This makes the compiler try, for any program symbol whose type cannot 
	                        be proven at compile time, to type it as narrow and primitive as 
	                        possible. If the runtime encounters an error because symbol type 
	                        is too narrow, a wider method will be generated until steady stage 
	                        is reached. While this produces as optimal Java Bytecode as possible, 
	                        erroneous type guesses will lead to longer warmup. Optimistic typing 
	                        is currently disabled by default, but can be enabled for significantly 
	                        better peak performance.)
		param: [true|false]   default: false

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
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `2F83C35B5136353D68CE9EB669FD1B0B`
* Thumbprint: `4BAD227329ADEF18F215B6475FB7948E1629B505`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Amazon.com Services LLC, OU=Software Services, O=Amazon.com Services LLC, L=Seattle, S=Washington, C=US

## File Metadata

* Original Filename: jjs.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe](jdeps.exe-3391DEEABD10D7DF3EC9A1EA35F11ADA.md) | 69
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-EF545E6EFCC0E8BA4089FE7DC1DFDE90.md) | 86
[C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe](jjs.exe-F1EAC51F83F1299AD8072546BD948015.md) | 88
[C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 77




MIT License. Copyright (c) 2020 Strontic.


