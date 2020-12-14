---
title: convert.exe | File System Conversion Utility
excerpt: What is convert.exe?
---

# convert.exe 

* File Path: `C:\windows\SysWOW64\convert.exe`
* Description: File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `7C67469A8B9A0748A063BF5616AE4582`
SHA1 | `0B15CC3E2BD988C28ACB858DAFAD0788D3F65B48`
SHA256 | `74F4956142E6867378635C2E2E52A6A312C21FFD20253B95E6183C76872787E8`
SHA384 | `45CA0F5511EE83E1817E40287BFE72DFFA6741BB78C71FD67AE97D964E20201F55D7A62DDBE6D662617DB0EF84003FFB`
SHA512 | `753F7581398DCA10110FAAAC785DC85DF345E38C7E55F4F2042DA068CD39BD7FCF44C1ACB2E8649004F1A3B51E07E484358EFA4CF138EA66B5D9BAD12F85974F`
SSDEEP | `384:Z3Mj+lNoV5xeC5ip8/kGFfXdYQp5MaBCNbW0qWi:Zi+3oV5A2iYkElbowCZ`

## Signature

* Status: The file C:\windows\SysWOW64\convert.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: CONVERT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.



## Possible Misuse

*The following table contains possible examples of `convert.exe` being misused. While `convert.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_eda.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_eda.yml) | `- '[Convert]::ToString($SYNOptions, 16)'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_suspicious_invocation_specific.yml) | `- '* -nop -w hidden -c * [Convert]::FromBase64String*'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | $EncodedCommand =[Convert]::ToBase64String($Bytes) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | powershell.exe -Command "IEX ([Text.Encoding]::UNICODE.GetString([Convert]::FromBase64String((gp #{registry_key_storage} #{registry_entry_storage}).#{registry_entry_storage})))" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | iex ([Text.Encoding]::ASCII.GetString([Convert]::FromBase64String((gp 'HKCU:\Software\Classes\AtomicRedTeam').ART))) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | $Content = [System.Convert]::FromBase64String($key) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $x1 = "Request.Item[System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(\"[password]\"))];" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $x2 = "eval(arguments,System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $s1 = "<%@ Page Language=\"Jscript\" validateRequest=\"false\"%><%try{eval(System.Text.Encoding.UTF8.GetString(Convert.FromBase64String" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $s2 = "{return System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $a1 = "function DEC(d){return System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(d));}" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $a2 = "function ENC(d){return Convert.ToBase64String(System.Text.Encoding.UTF8.GetBytes(d));}" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x2 = "convert an XML file generated by the BLATSTING sniffer module into a pcap capture file." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s6 = "* Failed to convert destination address into sockaddr_storage values" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_muddywater.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_muddywater.yar) | /* iex([System.Text.Encoding]::Unicode.GetString([System.Convert]::FromBase64String( */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s2 = "$fdn=[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String('" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $s3 = "$DATA = [System.Convert]::FromBase64String([IO.File]::ReadAllText('%Base%'));[io.file]::WriteAllBytes(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | $encfile = "New-Object IO.Compression.DeflateStream([IO.MemoryStream][Convert]::FromBase64String($encfile)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s2 = "Convert mode: Read log from file and convert to text" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tophat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tophat.yar) | $s1 = "= New-Object IO.MemoryStream(,[Convert]::FromBase64String(\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_neuron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_neuron.yar) | $ = "Convert.FromBase64String(temp[1])" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_cn_webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_cn_webshells.yar) | $s2 = "$sCmd = \"convert \".$sFile.\" -flip -quality 80 \".$sFileOut;" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s1 = "$Base64Decoded = [Convert]::FromBase64String($Cpassword)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_empire.yar) | $s2 = "$NTLM_challenge_base64 = [System.Convert]::ToBase64String($HTTP_NTLM_bytes)" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_invoke_thehash.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_invoke_thehash.yar) | $s3 = "$NTLM_hash_bytes = $NTLM_hash_bytes.Split(\"-\") \| ForEach-Object{[Char][System.Convert]::ToInt16($_,16)}" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_metasploit_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_metasploit_payloads.yar) | $s10 = "= [System.Convert]::FromBase64String(\"/" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_metasploit_payloads.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_metasploit_payloads.yar) | $s5 = "= [System.Convert]::FromBase64String(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_empire.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_empire.yar) | $s3 = "[Byte[]]$DllBytes = [Byte[]][Convert]::FromBase64String($DllBytes32)" fullword ascii  | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_susp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_susp.yar) | $p3 = "[System.Convert]::FromBase64String(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s3 = "if ($Env:PROCESSOR_ARCHITECTURE -eq $([Text.Encoding]::Unicode.GetString([Convert]::FromBase64String('QQBNAEQANgA0AA==')))) {" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s5 = "-eq $([Text.Encoding]::Unicode.GetString([Convert]::FromBase64String('MAAxADQAQwA='))))"  ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [gen_powershell_toolkit.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/gen_powershell_toolkit.yar) | $s1 = "if($MyConString -like $([Text.Encoding]::Unicode.GetString([Convert]::" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "WSocketResolveHost: Cannot convert host address '%s'" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-hacktools.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-hacktools.yar) | $s2 = "System.Convert.FromBase64String(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## convert

Converts a disk from one disk type to another.

### Syntax

```
convert basic
convert dynamic
convert gpt
convert mbr
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| [convert basic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-basic.md) | Converts an empty dynamic disk into a basic disk. |
| [convert dynamic command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-dynamic.md) | Converts a basic disk into a dynamic disk. |
| [convert gpt command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-gpt.md) | Converts an empty basic disk with the master boot record (MBR) partition style into a basic disk with the GUID partition table (GPT) partition style. |
| [convert mbr command](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/convert-mbr.md) | Converts an empty basic disk with the GUID Partition Table (GPT) partition style into a basic disk with the master boot record (MBR) partition style. |

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020 Strontic.


