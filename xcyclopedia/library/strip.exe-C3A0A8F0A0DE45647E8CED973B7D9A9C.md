---
title: strip.exe | 
excerpt: What is strip.exe?
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
PESHA1 | `4205FEEC0677F8DF1950D9BCDA01D716433879B4`
PE256 | `534CDEE60CF6316698B6D8C0F4F411AC2A48493389DB50CF6C4F40F85A0C3FD1`

## Runtime Data

### Usage (stdout):
```cmhg
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
```cmhg
C:\Program Files\PeaZip\res\upx\strip.exe: invalid option -- h
Usage: C:\Program Files\PeaZip\res\upx\strip.exe [-vVsSpgxX] [-I bfdname] [-O bfdname] [-F bfdname] [-R section]
       [--input-target=bfdname] [--output-target=bfdname] [--target=bfdname]
       [--strip-all] [--strip-debug] [--strip-unneeded] [--discard-all]
       [--discard-locals] [--keep-symbol symbol] [-K symbol]
       [--strip-symbol symbol] [-N symbol] [--remove-section=section]
       [-o file] [--preserve-dates] [--verbose] [--version] [--help] file...
C:\Program Files\PeaZip\res\upx\strip.exe: supported targets: pe-i386 pei-i386 srec symbolsrec tekhex binary ihex

```

### Loaded Modules:

Path |
-- |
C:\Program Files\PeaZip\res\upx\strip.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 1/69
* VirusTotal Link: https://www.virustotal.com/gui/file/b4ebe301e77a5b6a40e71776b921efdb639bdc9011d2ef5a137de9fa6f57e51e/detection/


## Possible Misuse

*The following table contains possible examples of `strip.exe` being misused. While `strip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1098.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1098/T1098.md) | $account = $member.Name -replace ".+\\\","" # strip computername\ | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_backdoor_ssh_python.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_backdoor_ssh_python.yar) | $s0 = "command= raw_input(\"Enter command: \").strip('n')" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_fireeye_redteam_tools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_fireeye_redteam_tools.yar) | $ign1 = "--strip-comments" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_empire.yar) | $s1 = "script += \" -\" + str(option) + \" \\\"\" + str(values['Value'].strip(\"\\\"\")) + \"\\\"\"" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


