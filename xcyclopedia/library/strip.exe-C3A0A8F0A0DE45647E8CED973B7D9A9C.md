---
title: strip.exe | 
---

# strip.exe 

* File Path: `C:\Program Files\PeaZip\res\upx\strip.exe`

## Hashes

Type | Hash
-- | --
MD5 | `C3A0A8F0A0DE45647E8CED973B7D9A9C`
SHA1 | `0F94B5919A355D2CFD65441EB2C6CFA922560A80`
SHA256 | `B4EBE301E77A5B6A40E71776B921EFDB639BDC9011D2EF5A137DE9FA6F57E51E`
SHA384 | `76F1C083909DEA31F8466C73140F86BE2BD54CA09FE9F43F605997D77CF042EFEE1082D55C43EE1CE59807258F488193`
SHA512 | `1E4B0EE443C6EA9842F20FADA828658E419273FD2BE44A0F6F782E218BC60826C1E0FD23765E73C062AF23C28C05F16BA840742C6E2E983BB8476D7A8CC139AA`
SSDEEP | `3072:yRpDGWktD8mKjlry9BJj40p9EeenSKg8Qn9axvJPoBEI3ravQ:sdaKpGX9x9CnSKgzGNoe/`

## Runtime Data

### Usage (stdout):
```Batchfile
Usage: C:\Program Files\PeaZip\res\upx\strip.exe [-vVsSpgxX] [-I bfdname] [-O bfdname] [-F bfdname] [-R section]
       [--input-target=bfdname] [--output-target=bfdname] [--target=bfdname]
       [--strip-all] [--strip-debug] [--strip-unneeded] [--discard-all]
       [--discard-locals] [--keep-symbol symbol] [-K symbol]
       [--strip-symbol symbol] [-N symbol] [--remove-section=section]
       [-o file] [--preserve-dates] [--verbose] [--version] [--help] file...
C:\Program Files\PeaZip\res\upx\strip.exe: supported targets: pe-i386 pei-i386 srec symbolsrec tekhex binary ihex
Report bugs to bug-gnu-utils@gnu.org

```

### Usage (stderr):
```Batchfile
C:\Program Files\PeaZip\res\upx\strip.exe: invalid option -- h
Usage: C:\Program Files\PeaZip\res\upx\strip.exe [-vVsSpgxX] [-I bfdname] [-O bfdname] [-F bfdname] [-R section]
       [--input-target=bfdname] [--output-target=bfdname] [--target=bfdname]
       [--strip-all] [--strip-debug] [--strip-unneeded] [--discard-all]
       [--discard-locals] [--keep-symbol symbol] [-K symbol]
       [--strip-symbol symbol] [-N symbol] [--remove-section=section]
       [-o file] [--preserve-dates] [--verbose] [--version] [--help] file...
C:\Program Files\PeaZip\res\upx\strip.exe: supported targets: pe-i386 pei-i386 srec symbolsrec tekhex binary ihex

```

## Signature

* Status: The file C:\Program Files\PeaZip\res\upx\strip.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 


## Possible Misuse

*The following table contains possible examples of `strip.exe` being misused. While `strip.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_backdoor_ssh_python.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_backdoor_ssh_python.yar) | 		$s0 = "command= raw_input(\"Enter command: \").strip('n')" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_empire.yar) | 		$s1 = "script += \" -\" + str(option) + \" \\\"\" + str(values['Value'].strip(\"\\\"\")) + \"\\\"\"" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


