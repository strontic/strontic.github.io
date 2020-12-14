---
title: test.exe | 
excerpt: What is test.exe?
---

# test.exe 

* File Path: `C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\test.exe`

## Hashes

Type | Hash
-- | --
MD5 | `5B62936D2C8C72BFE2BA70C84DF77CEA`
SHA1 | `1687F84B834716303A6D79C0ADFE56AE2165DCE4`
SHA256 | `3549DE02F9F4A6369B309FABE22340D82CD4A2EF376E34A81D8FFF3B311C5528`
SHA384 | `628FD5E0F26DE4922485740916F1CA9E04471C4BDCA6D201F4DB52F2BE5C1177A8B41DF9A6EB2AD2AD9E4552F6724DF5`
SHA512 | `6AD5D93AEB468B4AA9AF267F7D9AB06646C2BE250E23D01712C3908D7F55066277A4AF4C01EDCEE65C7EAEDCA2DE96CC1F012AE468CB8E4BF2F2FEBFD39D5BEE`
SSDEEP | `1536:Y2/+iDj1N2zG/+YCWnbgjcx2BTIi9jfWWwFIS8Uf:lNj1t/+YlbriI6/wFI`

## Runtime Data

### Loaded Modules:

Path |
-- |
C:\Users\user\AppData\Local\GitHubDesktop\app-2.5.4\resources\app\git\usr\bin\test.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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



## Possible Misuse

*The following table contains possible examples of `test.exe` being misused. While `test.exe` is **not** inherently malicious, its legitimate functionality can be abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_apt_winnti_mal_hk_jan20.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_apt_winnti_mal_hk_jan20.yml) | `ParentImage\|endswith: '\Test.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[atomic-red-team](https://github.com/redcanaryco/atomic-red-team) | [T1574.009.md](https://github.com/redcanaryco/atomic-red-team/blob/master/atomics/T1574.009/T1574.009.md) | In this case, if an executable program.exe in C:\ exists, C:\program.exe will be executed instead of test.exe in C:\Program Files\subfolder\test.exe. | [MIT License. © 2018 Red Canary](https://github.com/redcanaryco/atomic-red-team/blob/master/LICENSE.txt)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_apt3_bemstour.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_apt3_bemstour.yar) | $cmdline_4 = "hello.exe  \"C:\\WINDOWS\\DEBUG\\test.exe\"" ascii wide | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_waterbear.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_waterbear.yar) | $s2 = "name=\"test.exe\"/>" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s1 = "test.exe" fullword ascii | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


