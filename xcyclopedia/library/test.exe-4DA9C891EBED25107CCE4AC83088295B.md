---
title: test.exe | 
---

# test.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\test.exe`

## Hashes

Type | Hash
-- | --
MD5 | `4DA9C891EBED25107CCE4AC83088295B`
SHA1 | `28DBAED0DC141EF25368C3AF81DC798B304D6E88`
SHA256 | `4DDD8BFA98C39A68EA1ADD45E1A4B0C19C16E37C8F47CB00BA3883FC442EC5C1`
SHA384 | `BA5609E7E350B66BC43102884F2B5318B29359AA1204DA82B3FF58A6AEC56EAD783D1892C2A545C32C7D1C726DFF2E7D`
SHA512 | `A78F3ED40E7D13EFDA6091977B8DCA9CAB5C549697FA80EFBBF8510B15F5039ACE6399C5B055B851FAF93EA00B3F8CE12884AAEAEF34DA4C34C8FB5DF5E14A39`
SSDEEP | `1536:ZOfFlFIbsFehzGwEr+C4GeFHxlcwRNQvYR3vUckpKWl9AbI02RBTIvHWcWJFj8ld:ZOfF7I4FczGwE+t4YR3sckpKWl9AbIb4`

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

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.3\resources\app\git\usr\bin\test.exe](test.exe-4DA9C891EBED25107CCE4AC83088295B.md) | 100

## Possible Misuse

*The following table contains possible examples of `test.exe` being misused. While `test.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `        ParentImage\|endswith: '\Test.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.009/T1574.009.md) | In this case, if an executable program.exe in C:\ exists, C:\program.exe will be executed instead of test.exe in C:\Program Files\subfolder\test.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt3_bemstour.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt3_bemstour.yar) | $cmdline_4 = "hello.exe  \"C:\\WINDOWS\\DEBUG\\test.exe\"" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_waterbear.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_waterbear.yar) |       $s2 = "name=\"test.exe\"/>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | 		$s1 = "test.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


