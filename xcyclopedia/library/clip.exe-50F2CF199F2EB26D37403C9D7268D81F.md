---
title: clip.exe | Clip - copies the data into clipboard
excerpt: What is clip.exe?
---

# clip.exe 

* File Path: `C:\Windows\system32\clip.exe`
* Description: Clip - copies the data into clipboard

## Hashes

Type | Hash
-- | --
MD5 | `50F2CF199F2EB26D37403C9D7268D81F`
SHA1 | `1DEAA1CDDCC528D30749DCA3CC410EBFE9ADE6C8`
SHA256 | `5AD606BCBBBDB95DDA19C955E4129B436295CAC249E2370FEE3D0285D387CF55`
SHA384 | `C42EF2CE3E5BBF6C4BF5262DD7CAFBB2085A9E39A1AD08F556507AF9DD3C7781A76334D83898AC748C41624D7205BCD4`
SHA512 | `594F89523886B2451222067D196F1A62CAC9EF784B633DF638DDDC0F0E53042FF94C4D0C69751BD352DE3A9D502C5E38115E7CAE32C5772310D2FA3C4906AE2C`
SSDEEP | `768:RKq1nys0lSb7jg4jY5yi+i359SMY1yGiaLefVv0r0x+gNcgs:RKq1BNLdi3scGiaLef+Ixfcg`
IMP | `D4F9D4B3E58F3C49F0B3042F0B20C802`
PESHA1 | `C7CD388D1908DD1812B7F3104D529FF8313838F5`
PE256 | `3D992025F26A7D8A1BB3E2AB15982D2D4E4169DD1CE924666776BFB3DB26A8F8`

## Runtime Data

### Usage (stdout):
```cmhg

CLIP

Description:
    Redirects output of command line tools to the Windows clipboard.
    This text output can then be pasted into other programs.

Parameter List:
    /?                  Displays this help message.

Examples:
    DIR | CLIP          Places a copy of the current directory
                        listing into the Windows clipboard.

    CLIP < README.TXT   Places a copy of the text from readme.txt
                        on to the Windows clipboard.

```

### Usage (stderr):
```cmhg
ERROR: Invalid argument/option - '--help'.
Type "CLIP /?" for usage.

```

### Loaded Modules:

Path |
-- |
C:\Windows\system32\clip.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/74
* VirusTotal Link: https://www.virustotal.com/gui/file/5ad606bcbbbdb95dda19c955e4129b436295cac249e2370fee3d0285d387cf55/detection


## Possible Misuse

*The following table contains possible examples of `clip.exe` being misused. While `clip.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_clip_services.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_clip_services_security.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_use_clip_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_use_clip_services.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_use_clip_services_security.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/builtin/win_invoke_obfuscation_via_use_clip_services_security.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_clip.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_use_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_module/powershell_invoke_obfuscation_via_use_clip.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_clip_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_clip_in_scriptblocktext.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [powershell_invoke_obfuscation_via_use_clip_in_scriptblocktext.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/powershell/powershell_script/powershell_invoke_obfuscation_via_use_clip_in_scriptblocktext.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [process_creation_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/process_creation_clip.yml) | `OriginalFileName: clip.exe`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_clip.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_invoke_obfuscation_via_use_clip.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_invoke_obfuscation_via_use_clip.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_clip+_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_clip+_services.yml) | `description: Detects Obfuscated use of Clip.exe to execute PowerShell`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [driver_load_invoke_obfuscation_via_use_clip_services.yml](https://github.com/Neo23x0/sigma/blob/master/rules-unsupported/driver_load_invoke_obfuscation_via_use_clip_services.yml) | `description: Detects Obfuscated Powershell via use Clip.exe in Scripts`{:.highlight .language-yaml} | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)

## Additional Info*

**The information below is copied from [MicrosoftDocs](https://github.com/MicrosoftDocs/windowsserverdocs), which is maintained by [Microsoft](https://opensource.microsoft.com/codeofconduct/). Available under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.*

---

## clip

Redirects the command output from the command line to the Windows clipboard. You can use this command to copy data directly into any application that can receive text from the Clipboard. You can also paste this text output into other programs.

### Syntax

```
<command> | clip
clip < <filename>
```

#### Parameters

| Parameter | Description |
| --------- | ----------- |
| `<command>` | Specifies a command whose output you want to send to the Windows clipboard. |
| `<filename>` | Specifies a file whose contents you want to send to the Windows clipboard. |
| /? | Displays help at the command prompt. |

### Examples

To copy the current directory listing to the Windows clipboard, type:

```
dir | clip
```

To copy the output of a program called *generic.awk* to the Windows clipboard, type:

```
awk -f generic.awk input.txt | clip
```

To copy the contents of a file called *readme.txt* to the Windows clipboard, type:

```
clip < readme.txt
```

### Additional References

- [Command-Line Syntax Key](https://github.com/MicrosoftDocs/windowsserverdocs/tree/master/WindowsServerDocs/administration/windows-commands/command-line-syntax-key.md)

---



MIT License. Copyright (c) 2020-2021 Strontic.


