---
title: sendmail.dll | Send Mail
excerpt: What is sendmail.dll?
---

# sendmail.dll 

* File Path: `C:\Windows\system32\sendmail.dll`
* Description: Send Mail

## Hashes

Type | Hash
-- | --
MD5 | `660AC3CA4189335223A85A462061DDEE`
SHA1 | `4D7E073FDA14E263A84CA09CCA1CAEBD1EA1AD60`
SHA256 | `AC33DD9E2F2323F5BF67443C78B6220D4AD606C913A5E0118FF05453EA99F00B`
SHA384 | `15FA1C05292DFB6D6E91A15557E15F7B64A9BE25CFF902F8C444A9A3BBBE9AAB90C9ADA28E7B05406DA442504F89B8EA`
SHA512 | `C84F11B37CBAC1540027ABCA8FAD195F4747FD61E459E21FE619B1F2A1EB3E51A8B07978BA4E9A877BDA72DCF21E587E937BE639C4956056D87BB47C18DA8084`
SSDEEP | `1536:XXa2toEUYB7s/Hd58mkbi5aOoSMtGD7FB2nPVBBPTKVHyfXX2OLN:ZGwBeHEmkbi5QtokTNfpx`
IMP | `9A2286798F785EE11497FA3D113D6CBE`
PESHA1 | `000645D864E8B937E43235B4EC78B03E4E8269FB`
PE256 | `CE5CDCC26459433DFA4BFDF2B636C9C5E39A0093352930F3B0AA412B68B2612C`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllGetClassObject` | 2 | Exported Function
`DllCanUnloadNow` | 1 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SENDMAIL.DLL.MUI
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/ac33dd9e2f2323f5bf67443c78b6220d4ad606c913a5e0118ff05453ea99f00b/detection/


## Possible Misuse

*The following table contains possible examples of `sendmail.dll` being misused. While `sendmail.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'sendmail -osendmail;chmod +x sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'wget http*; chmod +x /tmp/sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 700 fp sendmail pt'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 700 sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- 'chmod 0700 sendmail'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [lnx_apt_equationgroup_lnx.yml](https://github.com/Neo23x0/sigma/blob/master/rules/linux/lnx_apt_equationgroup_lnx.yml) | `- '/usr/bin/wget http*sendmail;chmod +x sendmail;'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | rule sendmail { | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [thor-webshells.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/thor-webshells.yar) | description = "Webshells Auto-generated - file sendmail.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


