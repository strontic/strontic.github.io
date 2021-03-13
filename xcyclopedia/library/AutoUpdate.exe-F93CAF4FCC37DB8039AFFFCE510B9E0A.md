---
title: AutoUpdate.exe | Glary Utilities AutoUpdate
excerpt: What is AutoUpdate.exe?
---

# AutoUpdate.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\AutoUpdate.exe`
* Description: Glary Utilities AutoUpdate

## Hashes

Type | Hash
-- | --
MD5 | `F93CAF4FCC37DB8039AFFFCE510B9E0A`
SHA1 | `E58EC4AD53BD851A036DBFC1255A4AE4B97322DA`
SHA256 | `3390274DCCA766F8E1ADA6663C1D8F38EE57B3E7026DD7680A9647F7CEAE0CEF`
SHA384 | `CCCBC0EA250AABB6343A720623D3155CF414B29A3D77CAA6CD26AEA04060C3E43EF4AB39E7315FC908A2473897438B23`
SHA512 | `313B2C1224491E8FD4CBB8AA2613B41561D1BE58C605B813BA7CB588E778750D406983A228EE95AF2E70E6636839EC008C6D36E97D76EEB13F9FBA40E778831F`
SSDEEP | `12288:KBhvKRuGiIGrm+Su8DzIr+EuK4LXJcgaSB:Yi0GiIL+SPEuK4LXybSB`
IMP | `4F4128965F8B5571E99DA347BF457FF4`
PESHA1 | `A9C737822F0C582A66E23163801F0980C1226190`
PE256 | `FAE88C5F49C9123EC3FE73E083579C2BFF2653FF0D2350A3879C0427D6A004F3`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Glary Utilities 5\AutoUpdate.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `0F05AE21CDC17B9F3CF09D7BFC659BA3`
* Thumbprint: `362EBB303E088105BDCC07D94E6B7875D30C0D06`
* Issuer: CN=DigiCert Assured ID Code Signing CA-1, OU=www.digicert.com, O=DigiCert Inc, C=US
* Subject: CN=Glarysoft LTD, O=Glarysoft LTD, S=Beijing, C=CN

## File Metadata

* Original Filename: 
* Product Name: Glary Utilities
* Company Name: Glarysoft Ltd
* File Version: 5, 0, 0, 10
* Product Version: 5.0.0.1
* Language: Chinese (Simplified, China)
* Legal Copyright: Copyright (c) 2003-2020 Glarysoft Ltd
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/3390274dcca766f8e1ada6663c1d8f38ee57b3e7026dd7680a9647f7ceae0cef/detection/

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\program files (x86)\Glary Utilities 5\AutoUpdate.exe](AutoUpdate.exe-8048161409846C49D68B61AB91551B3C.md) | 96
[C:\Program Files (x86)\Glary Utilities 5\AutoUpdate.exe](AutoUpdate.exe-9EBC727B6DB81A87605E024E23D35326.md) | 96

## Possible Misuse

*The following table contains possible examples of `AutoUpdate.exe` being misused. While `AutoUpdate.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s0 = "<input type=\"checkbox\" name=\"autoUpdate\" value=\"AutoUpdate\" on" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | $s1 = "onblur=\"document.shell.autoUpdate.checked= this.oldValue;" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020-2021 Strontic.


