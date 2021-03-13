---
title: jjs.exe | OpenJDK Platform binary
excerpt: What is jjs.exe?
---

# jjs.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `EF545E6EFCC0E8BA4089FE7DC1DFDE90`
SHA1 | `29204A2F600129D27EABAD167982209144CBF838`
SHA256 | `8423993ACB5F7979AB8956DF7907F4EC3990C6BD0B70AAFA30981953EF401D61`
SHA384 | `DD6E13D9CE97270029F8F0354FD5DEF6A7B52E08FB04A7D775B992CC42969065965E833A040B11F4CE197A772CF2C32A`
SHA512 | `368BB0400380381A236DDF3EF15F51C31DB78F18DDA56D8879F59E96CA856D5DA72302819F3D8B8435619C22A2EED2B88E29BE9AA6F33A277A9F03FBC298288B`
SSDEEP | `384:Gpsr5BnqqGmSHhV8dKeeF4Sz8K6jSObDgf2hIdt:Gps7nTS/8dXeF+KgZUf2hIdt`

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
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe |
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe](jdeps.exe-3391DEEABD10D7DF3EC9A1EA35F11ADA.md) | 68
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe](jjs.exe-50283CF0315C0D9CB58A0C666D5CEFF7.md) | 86
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jps.exe](jps.exe-5AFACE3595288F9EF62F39721DEEC88C.md) | 75
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jstat.exe](jstat.exe-667252B3D687876CE357538652F3779E.md) | 72
[C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe](jjs.exe-F1EAC51F83F1299AD8072546BD948015.md) | 86
[C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 71




MIT License. Copyright (c) 2020-2021 Strontic.


