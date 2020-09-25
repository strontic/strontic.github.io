---
title: dirname.exe | 
excerpt: What is dirname.exe?
---

# dirname.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\dirname.exe`

## Hashes

Type | Hash
-- | --
MD5 | `165A8B75C6AA8A5E1616D2BE8C8B607A`
SHA1 | `D4E5D476B26FBF9C141B012920896BD122543020`
SHA256 | `603EFAEF46CF52BE4932948FD34260D14DA6762A9CB8485D78639367E327AAAE`
SHA384 | `A66C01EB90541ADFCC9DDB5E49FA6688ED3CD63A08A5A810F289E006582ADDA1069F4FDF0610B8478C5687193121CF84`
SHA512 | `16AFF02C4C8238F032F56927E210AC057433017EB83B450AD13796CF83F61C099D2F667760F5558EA73EB5D964B463E470C8471BDDC07AE4685C5D7763BFC861`
SSDEEP | `768:f2WWPiM2nVszjC9BncDNiqbowd1WeFM6DGeUf2hBM:f2WWh2nuXCwTWeFMQUfSM`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: /usr/bin/dirname [OPTION] NAME...
Output each NAME with its last non-slash component and trailing slashes
removed; if NAME contains no /'s, output '.' (meaning the current directory).

  -z, --zero     end each output line with NUL, not newline
      --help     display this help and exit
      --version  output version information and exit

Examples:
  /usr/bin/dirname /usr/bin/          -> "/usr"
  /usr/bin/dirname dir1/str dir2/str  -> "dir1" followed by "dir2"
  /usr/bin/dirname stdio.h            -> "."

GNU coreutils online help: <https://www.gnu.org/software/coreutils/>
Report any translation bugs to <https://translationproject.org/team/>
Full documentation <https://www.gnu.org/software/coreutils/dirname>
or available locally via: info '(coreutils) dirname invocation'

```

### Usage (stderr):
```cmhg
dirname: unknown option -- h
Try '/usr/bin/dirname --help' for more information.

```

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\dirname.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `045D8F14A82147641722D4FAFC66BC80`
* Thumbprint: `FB713A60A7FA79DFC03CB301CA05D4E8C1BDD431`
* Issuer: CN=DigiCert SHA2 Assured ID Code Signing CA, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN="GitHub, Inc.", O="GitHub, Inc.", L=San Francisco, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 



## Possible Misuse

*The following table contains possible examples of `dirname.exe` being misused. While `dirname.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s3 = "echo      \"<input name='p' type='text' size='27' value='\".dirname(_FILE_).\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "else {$act = \"f\"; $d = dirname($mkfile); if (substr($d,-1) != DIRECTORY_SEPA" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


