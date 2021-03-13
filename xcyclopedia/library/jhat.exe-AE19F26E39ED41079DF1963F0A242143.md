---
title: jhat.exe | OpenJDK Platform binary
excerpt: What is jhat.exe?
---

# jhat.exe 

* File Path: `C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jhat.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `AE19F26E39ED41079DF1963F0A242143`
SHA1 | `1EA3A2E34E572B8BF223171BB860DD19049EEC2C`
SHA256 | `9E82D79D8AB8B97FFA4FAC7AC66791CEEDD495F2C5C7EAE29853292DF1DD6A7B`
SHA384 | `43C2D2745472646293358D8D47897765D4B5A66504D61925EA07B3A8A4319F76B6FE0154614C2D855645E0DC5672AD41`
SHA512 | `E4C7E05A585A91E83CEF18F34268A2B2838C0A08B4DBD636592646F6D74BBA21DB73769EC04C3496EFD221FBC679423A9769C17765AD50B397FF49E35A27EE44`
SSDEEP | `384:GpsI5BnBqrmSHhV8MWeeo4Sz0K6jS5hzHDgf2hv:Gpsyn5S/8MbeomKgaHUf2hv`

## Runtime Data

### Usage (stdout):
```cmhg
Reading from --help...

```

### Usage (stderr):
```cmhg
Usage:  jhat [-stack <bool>] [-refs <bool>] [-port <port>] [-baseline <file>] [-debug <int>] [-version] [-h|-help] <file>

	-J<flag>          Pass <flag> directly to the runtime system. For
			  example, -J-mx512m to use a maximum heap size of 512MB
	-stack false:     Turn off tracking object allocation call stack.
	-refs false:      Turn off tracking of references to objects
	-port <port>:     Set the port for the HTTP server.  Defaults to 7000
	-exclude <file>:  Specify a file that lists data members that should
			  be excluded from the reachableFrom query.
	-baseline <file>: Specify a baseline object dump.  Objects in
			  both heap dumps with the same ID and same class will
			  be marked as not being "new".
	-debug <int>:     Set debug level.
			    0:  No debug output
			    1:  Debug hprof file parsing
			    2:  Debug hprof file parsing, no server
	-version          Report version number
	-h|-help          Print this help and exit
	<file>            The file to read

For a dump file that contains multiple heap dumps,
you may specify which dump in the file
by appending "#<number>" to the file name, i.e. "foo.hprof#3".

All boolean options default to "true"

```

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Amazon Corretto\jdk1.8.0_265\bin\jhat.exe |
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

* Original Filename: jhat.exe
* Product Name: OpenJDK Platform 8
* Company Name: Amazon.com Inc.
* File Version: 8.0.2650.1
* Product Version: 8.0.2650.1
* Language: Language Neutral
* Legal Copyright: Copyright  2020


## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files\Amazon Corretto\jdk1.8.0_265\bin\javac.exe](javac.exe-E1A9361E0F13035D3450B2E5BF9F565A.md) | 43




MIT License. Copyright (c) 2020-2021 Strontic.


