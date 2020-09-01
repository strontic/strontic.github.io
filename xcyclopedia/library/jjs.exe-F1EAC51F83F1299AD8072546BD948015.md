---
title: jjs.exe | OpenJDK Platform binary
---

# jjs.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `F1EAC51F83F1299AD8072546BD948015`
SHA1 | `92718A070102CD79A64BDCD24FBCEF9BAC8DEDC9`
SHA256 | `1786A2775B43F92C12AFC15E9650BA75838351E89EE9717C70936B94EBCE6831`
SHA384 | `E900C5D3A0B30CE95937E970EAD73CA90F3D1126C11E3534D9F25AFDD9AA0FBEB64DC6679AD247B1873273E1B9469F46`
SHA512 | `C426997C661368C8A3532B6660C9BBEC7B693A17D659C8BD0F9CF985032DD939F37E4669CF387E5E393984549460B34DC742D1160462332EEFB62EE1824F4097`
SSDEEP | `384:GpsJ5BnqqGmSHhV8dKeeF4Sz8K6jS7qDgf2hLe:Gps5nTS/8dXeF+KgAqUf2hLe`

## Runtime Data

### Usage (stderr):
```Batchfile
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
C:\program files (x86)\Amazon Corretto\jre8\bin\jjs.exe |
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
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jdeps.exe](jdeps.exe-3391DEEABD10D7DF3EC9A1EA35F11ADA.md) | 71
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jjs.exe](jjs.exe-50283CF0315C0D9CB58A0C666D5CEFF7.md) | 88
[C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\jre\bin\jjs.exe](jjs.exe-EF545E6EFCC0E8BA4089FE7DC1DFDE90.md) | 86
[C:\program files (x86)\Amazon Corretto\jre8\bin\ktab.exe](ktab.exe-AB2485516E63BA82335DA60828829563.md) | 72




MIT License. Copyright (c) 2020 Strontic.


