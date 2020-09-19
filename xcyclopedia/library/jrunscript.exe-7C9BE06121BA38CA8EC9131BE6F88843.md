---
title: jrunscript.exe | OpenJDK Platform binary
---

# jrunscript.exe 

* File Path: `C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jrunscript.exe`
* Description: OpenJDK Platform binary

## Hashes

Type | Hash
-- | --
MD5 | `7C9BE06121BA38CA8EC9131BE6F88843`
SHA1 | `AB85427A424F37930A688EA2B71659A8B7023413`
SHA256 | `04950849D042BB55C5E76D5659EFD53AB7F6B2A3A6F1A701118A3ED89C4A9B6B`
SHA384 | `03EB1CA8C549870DABF168EB29330BEC867F9F4FCF6EC392F14CBE8C5184F81F60D76C586B114CA26063338A415C0DF6`
SHA512 | `1B8972D5CDE1464BD685D849D7A0167416CB1FECA55C0F9CA93FD1A553F18DB36AD008F90A4704B6EC236259D4EFCD6AE39ED18E1D40BCC2005D3B1A2763DEAD`
SSDEEP | `384:wb9bCPq99YBbFv8p45A0QK6jSpUTDgf2hEc:0uPJFQ45SKg8UTUf2hJ`

## Runtime Data

### Usage (stderr):
```cmhg
Usage: jrunscript [options] [arguments...]

where [options] include:
  -classpath <path>    Specify where to find user class files 
  -cp <path>           Specify where to find user class files 
  -D<name>=<value>     Set a system property 
  -J<flag>             Pass <flag> directly to the runtime system 
  -l <language>        Use specified scripting language 
  -e <script>          Evaluate given script 
  -encoding <encoding> Specify character encoding used by script files 
  -f <script file>     Evaluate given script file 
  -f -                 Interactive mode, read script from standard input 
                       If this is used, this should be the last -f option 
  -? -h --help -help   Print this help message and exit 
  -q                   List all scripting engines available and exit 
  
If [arguments..] are present and if no -e or -f option is used, then first
argument is script file and the rest of the arguments, if any, are passed
as script arguments. If [arguments..] and -e or -f option is used, then all
[arguments..] are passed as script arguments. If [arguments..], -e, -f are
missing, then interactive mode is used.

```

### Loaded Modules:

Path |
-- |
C:\program files\Amazon Corretto\jdk11.0.8_10\bin\jrunscript.exe |
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

* Original Filename: jrunscript.exe
* Product Name: OpenJDK Platform 11
* Company Name: Amazon.com Inc.
* File Version: 11.0.8
* Product Version: 11.0.8
* Language: Language Neutral
* Legal Copyright: Copyright  2020

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files\AdoptOpenJDK\jdk-11.0.8.10-hotspot\bin\jrunscript.exe](jrunscript.exe-B8C457CC6E8878FC4E78DF87FE69A04F.md) | 47
[C:\program files\AdoptOpenJDK\jre-11.0.8.10-hotspot\bin\jrunscript.exe](jrunscript.exe-7C4A5CAEF06DF2591580E764C20610EB.md) | 50




MIT License. Copyright (c) 2020 Strontic.


