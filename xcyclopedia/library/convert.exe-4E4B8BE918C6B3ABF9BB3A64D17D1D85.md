---
title: convert.exe | File System Conversion Utility
excerpt: What is convert.exe?
---

# convert.exe 

* File Path: `C:\WINDOWS\SysWOW64\convert.exe`
* Description: File System Conversion Utility

## Hashes

Type | Hash
-- | --
MD5 | `4E4B8BE918C6B3ABF9BB3A64D17D1D85`
SHA1 | `0BE2C266890B0B35FA9CED15B8AB5ABBDB695C61`
SHA256 | `51AE3C6225A8C1C6F25D20C6D44FF6D8E727A537BB1B52251034D6D4F7EC009C`
SHA384 | `63CBF7F952DA9FF4EF49F2E34F467AC2CC683B08A90A118D802458593C1679C0D88223BFBC900518228311F61564747B`
SHA512 | `231C7F897C879FF44615FA7FD95481CC84B2D97E6109394DF4730960042C65AA560D96CF1B014AF7FD88042A08AFEBD7E4CF487730C4AC9FD7CB862DF399D247`
SSDEEP | `192:3HtxRpRiYBiGDXeQ+pEdvTp/QZofvRABGZlCeNhYzuY7ahLX/qK7M7Tc/OAYgihF:FxHp+adppGG1JtUK7wTa/eNDWJqWf`
IMP | `4075BD8C3D5493A1502E6D9BCBD30110`
PESHA1 | `F3B5A1888E2ABE0BDB5A02322E46463F46A063A7`
PE256 | `FD51AFAF37CFE4B986487F1494F3B8AFEDB224065B40F12902FC000CABA1EF3F`

## Runtime Data

### Usage (stdout):
```cmhg
Converts a FAT volume to NTFS.

CONVERT volume /FS:NTFS [/V] [/CvtArea:filename] [/NoSecurity] [/X]


  volume      Specifies the drive letter (followed by a colon),
              mount point, or volume name.
  /FS:NTFS    Specifies that the volume will be converted to NTFS.
  /V          Specifies that Convert will be run in verbose mode.
  /CvtArea:filename
              Specifies a contiguous file in the root directory
              that will be the place holder for NTFS system files.
  /NoSecurity Specifies that the security settings on the converted
              files and directories allow access by all users.
  /X          Forces the volume to dismount first if necessary.
              All open handles to the volume will not be valid.

```

### Usage (stderr):
```cmhg
Invalid drive specification.

```

### Loaded Modules:

Path |
-- |
C:\WINDOWS\SYSTEM32\ntdll.dll |
C:\WINDOWS\System32\wow64.dll |
C:\WINDOWS\System32\wow64base.dll |
C:\WINDOWS\System32\wow64con.dll |
C:\WINDOWS\System32\wow64win.dll |
C:\WINDOWS\SysWOW64\convert.exe |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: CONVERT.EXE
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/51ae3c6225a8c1c6f25d20c6d44ff6d8e727a537bb1b52251034d6d4f7ec009c/detection


## Possible Misuse

*The following table contains possible examples of `convert.exe` being misused. While `convert.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [apt_silence_eda.yml](https://github.com/Neo23x0/sigma/blob/master/rules/apt/apt_silence_eda.yml) | `- '[Convert]::ToString($SYNOptions, 16)'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/deprecated/powershell_suspicious_invocation_specific.yml) | `- '[Convert]::FromBase64String'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific_in_contextinfo.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_suspicious_invocation_specific_in_contextinfo.yml) | `- '[Convert]::FromBase64String'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_powerview_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_powerview_malicious_commandlets.yml) | `- Convert-NameToSid`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_powerview_malicious_commandlets.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_powerview_malicious_commandlets.yml) | `- Convert-ADName`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_suspicious_invocation_specific_in_scripblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_suspicious_invocation_specific_in_scripblocktext.yml) | `- '[Convert]::FromBase64String'`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | $EncodedCommand =[Convert]::ToBase64String($Bytes) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1027.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1027/T1027.md) | powershell.exe -Command "IEX ([Text.Encoding]::UNICODE.GetString([Convert]::FromBase64String((gp #{registry_key_storage} #{registry_entry_storage}).#{registry_entry_storage})))" | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1059.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1059.001/T1059.001.md) | iex ([Text.Encoding]::ASCII.GetString([Convert]::FromBase64String((gp 'HKCU:\Software\Classes\AtomicRedTeam').ART))) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1098.001.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1098.001/T1098.001.md) | $keyValue = [System.Convert]::ToBase64String($cert.GetRawCertData()) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1218.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1218.009/T1218.009.md) | $Content = [System.Convert]::FromBase64String($key) | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $x1 = "Request.Item[System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(\"[password]\"))];" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $x2 = "eval(arguments,System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $s1 = "<%@ Page Language=\"Jscript\" validateRequest=\"false\"%><%try{eval(System.Text.Encoding.UTF8.GetString(Convert.FromBase64String" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $s2 = "{return System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $a1 = "function DEC(d){return System.Text.Encoding.UTF8.GetString(Convert.FromBase64String(d));}" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_aus_parl_compromise.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_aus_parl_compromise.yar) | $a2 = "function ENC(d){return Convert.ToBase64String(System.Text.Encoding.UTF8.GetBytes(d));}" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp.yar) | $x2 = "convert an XML file generated by the BLATSTING sniffer module into a pcap capture file." fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_eqgrp_apr17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_eqgrp_apr17.yar) | $s6 = "* Failed to convert destination address into sockaddr_storage values" fullword wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hafnium.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hafnium.yar) | $s2 = "System.Text.Encoding.Default.GetString(Convert.FromBase64String(StrTr(Request.Headers.Get" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_muddywater.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_muddywater.yar) | /* iex([System.Text.Encoding]::Unicode.GetString([System.Convert]::FromBase64String( */ | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig.yar) | $s2 = "$fdn=[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String('" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_oilrig_oct17.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_oilrig_oct17.yar) | $s3 = "$DATA = [System.Convert]::FromBase64String([IO.File]::ReadAllText('%Base%'));[io.file]::WriteAllBytes(" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_op_wocao.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_op_wocao.yar) | $encfile = "New-Object IO.Compression.DeflateStream([IO.MemoryStream][Convert]::FromBase64String($encfile)" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_project_sauron_extras.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_project_sauron_extras.yar) | $s2 = "Convert mode: Read log from file and convert to text" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_tophat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_tophat.yar) | $s1 = "= New-Object IO.MemoryStream(,[Convert]::FromBase64String(\"" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_turla_neuron.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_turla_neuron.yar) | $ = "Convert.FromBase64String(temp[1])" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_unc2447_sombrat.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_unc2447_sombrat.yar) | $x1 = "powershell.exe -c \"[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String([IO.File]::" ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [expl_proxyshell.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/expl_proxyshell.yar) | $s01 = ".LoadXml(System.Text.Encoding.UTF8.GetString(System.Convert.FromBase64String(Request[" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
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
[signature-base](https://github.com/Neo23x0/signature-base) | [webshell_xsl_transform.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/webshell_xsl_transform.yar) | $x2 = ".LoadXml(System.Text.Encoding.UTF8.GetString(System.Convert.FromBase64String(" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)

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



MIT License. Copyright (c) 2020-2021 Strontic.


