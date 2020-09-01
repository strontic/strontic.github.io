---
title: AutoUpdate.exe | Glary Utilities AutoUpdate
---

# AutoUpdate.exe 

* File Path: `C:\program files (x86)\Glary Utilities 5\AutoUpdate.exe`
* Description: Glary Utilities AutoUpdate

## Hashes

Type | Hash
-- | --
MD5 | `8048161409846C49D68B61AB91551B3C`
SHA1 | `DC910088C0884A1F7EBAFB8615464EE75A033756`
SHA256 | `A01D37CE9D6940ECBE0C95344E8C69B017A6EFF7B65CE0F175D89E7A783C7BBF`
SHA384 | `7E6011C3D9D25206E45909A278BC7C3B88BA68F9671C95254D725EE9856EB8C70EC8B8C0C20D61195E2933746276C537`
SHA512 | `CD144D7E5810CDE436853F31EE6F6F964867EFC899A49FCEF22EE2C7322F131C3962CC260220132A3E552D50F49AD20162DA21607C551452C432F53A63898A30`
SSDEEP | `12288:xBhvKRuGiIGrm+Su8DzIr+EuK4LXJcgaBA:xi0GiIL+SPEuK4LXybBA`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\program files (x86)\Glary Utilities 5\AutoUpdate.exe |
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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Glary Utilities 5\AutoUpdate.exe](AutoUpdate.exe-9EBC727B6DB81A87605E024E23D35326.md) | 93

## Possible Misuse

*The following table contains possible examples of `AutoUpdate.exe` being misused. While `AutoUpdate.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s0 = "<input type=\"checkbox\" name=\"autoUpdate\" value=\"AutoUpdate\" on" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s1 = "onblur=\"document.shell.autoUpdate.checked= this.oldValue;" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


