---
title: clip.exe | Clip - copies the data into clipboard
excerpt: What is clip.exe?
---

# clip.exe 

* File Path: `C:\WINDOWS\system32\clip.exe`
* Description: Clip - copies the data into clipboard

## Hashes

Type | Hash
-- | --
MD5 | `CAD14CC1A8FDF9F53241B82C93350E2F`
SHA1 | `94953576F41AAB3C9A7828FC29A604216894889A`
SHA256 | `DB10C74D475A4B8D31A726F7E09248B3C7CC71992548C1E724B936F9E75A9694`
SHA384 | `3A4680D7D66CA55CEC087815E586B3527B9BB03889389A6D3E4E18378A243E96502930DB05E0B8A4B3407D19B078A545`
SHA512 | `6168A97274F42568ECAED06023E415D97321EFD4AB78BDC470E185BF708C05B5A863242CC0EC84E7D703751466D0BAB0AF058840616D1FB6789516270DCFE477`
SSDEEP | `1536:qu1aSB7rXd8/awU4QnFFMFmkiAPeDsGFefEGIxjX:F8S5Xd8/awU4QnFFMFmki+eDFxD`
IMP | `FFEDF33A1AF6412E26F1F659C12D5FF7`
PESHA1 | `D0AA7D7399FAFDE3EC1BA558BBDF0C0812956903`
PE256 | `B9A7430F1CC999FE8C0C0397C0E9D39FB90AC214D379C70BC4019E24E19F3916`

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
C:\WINDOWS\system32\clip.exe |
C:\WINDOWS\System32\KERNEL32.DLL |
C:\WINDOWS\System32\KERNELBASE.dll |
C:\WINDOWS\SYSTEM32\ntdll.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002ED2C45E4C145CF48440000000002ED`
* Thumbprint: `312860D2047EB81F8F58C29FF19ECDB4C634CF6A`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: clip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.22000.1 (WinBuild.160101.0800)
* Product Version: 10.0.22000.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/73
* VirusTotal Link: https://www.virustotal.com/gui/file/db10c74d475a4b8d31a726f7e09248b3c7cc71992548c1e724b936f9e75a9694/detection


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


