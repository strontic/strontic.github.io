---
title: rdpclip.exe | RDP Clipboard Monitor
---

# rdpclip.exe 

* File Path: `C:\windows\system32\rdpclip.exe`
* Description: RDP Clipboard Monitor

## Hashes

Type | Hash
-- | --
MD5 | `B66E3F36EDD5E0AC620C8FD08C55C0E1`
SHA1 | `99C5CF01C2D9A7B72B9BB13C9756366EE57D4FED`
SHA256 | `B66D93926841E798F5AE1EF97158E74D79263745C81501BF342AA9D0672419D8`
SHA384 | `2E25710B480AF7862B19DC7105B958D3B57276A307CDA3F45B1C0D8427AF6DD2E3BD66E73C83E0E078DA6CA0A6771281`
SHA512 | `BBEE6B6EF73D838F1E112DE0DDA9FE85727CFB82F3015DBB47B81834B1A9EB6762D659F21B5F11E78BD87D0B1AF6CF487032C324CED9B8275CD3D213DDB0FAA3`
SSDEEP | `6144:YQHSTM6D0HjEX2T//5t6xYqd6FFpjRRpB/ZOJWPkY3FHqzE:RSMDEXGX5U/dkFptx/ZOJIkYN`

## Signature

* Status: The file C:\windows\system32\rdpclip.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: rdpclip.exe.mui
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.16384 (winblue_rtm.130821-1623)
* Product Version: 6.3.9600.16384
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `rdpclip.exe` being misused. While `rdpclip.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_termserv_proc_spawn.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_termserv_proc_spawn.yml) | `Image: '*\rdpclip.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


