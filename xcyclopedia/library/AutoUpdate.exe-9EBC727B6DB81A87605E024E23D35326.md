---
title: AutoUpdate.exe | Glary Utilities AutoUpdate
---

# AutoUpdate.exe 

* File Path: `C:\Program Files (x86)\Glary Utilities 5\AutoUpdate.exe`
* Description: Glary Utilities AutoUpdate

## Hashes

Type | Hash
-- | --
MD5 | `9EBC727B6DB81A87605E024E23D35326`
SHA1 | `515E4746D7E13531BA163B1171B280CFA65DF31F`
SHA256 | `DFA43FC9B59B4E3E64A0FF43F64713DF42A1C6762F061E4522A1BEED68128D80`
SHA384 | `0CC2027F0C2F848B7E830D7A332513AE740FFE95FA4C7719804E432E2E73B55F8C65251DC03FBC1443FDD84489DBA254`
SHA512 | `691ED64F581DFC1C0A0CED7037ADEF71EBB3C4176229B600FA329E58A8A765017802A76D19CF7DDA9FAB8862CDBE57160AE46FF41F12BE0A4B12B9D7081F5BDE`
SSDEEP | `12288:QBhvKRuGiIGrm+Su8DzIr+EuK4LXJcgaSu:ui0GiIL+SPEuK4LXybSu`

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


## Possible Misuse

*The following table contains possible examples of `AutoUpdate.exe` being misused. While `AutoUpdate.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s0 = "<input type=\"checkbox\" name=\"autoUpdate\" value=\"AutoUpdate\" on" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | 		$s1 = "onblur=\"document.shell.autoUpdate.checked= this.oldValue;" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


