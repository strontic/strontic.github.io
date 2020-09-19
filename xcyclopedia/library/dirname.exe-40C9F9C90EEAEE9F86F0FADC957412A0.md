---
title: dirname.exe | 
---

# dirname.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\dirname.exe`

## Hashes

Type | Hash
-- | --
MD5 | `40C9F9C90EEAEE9F86F0FADC957412A0`
SHA1 | `08DD52160770882EBF685E42D0C05582088B4FC4`
SHA256 | `AAF461CF4CF8E7E6578D12F79575AD8BC138CB4C1CD72CE42E5B1E275853CAE5`
SHA384 | `1DAEEF0460142941ED1F0B2A08B7BA5B116A29D333D8F27F2DA14E9F9F6845AD659F84687EF163211A503BFB6448BF81`
SHA512 | `47C2F022CCB895F8F1FE70388946A13972C241C3D594379A33D7DF45B328FBF20E698027A134B40B7EB9C7DBC26DD9D808F7C58C48B4DE0D299BE0F41C5A4216`
SSDEEP | `768:dsr6TsPUXAPkLZENfoViqboPycccccccccccccccccccccccccccccccpMZQgW2S:dseTsYAPzqnWEFXmUf`

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
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s3 = "echo      \"<input name='p' type='text' size='27' value='\".dirname(_FILE_).\"" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s0 = "else {$act = \"f\"; $d = dirname($mkfile); if (substr($d,-1) != DIRECTORY_SEPA" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


