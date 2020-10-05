---
title: extensibility.dll | Extensibility.dll
excerpt: What is extensibility.dll?
---

# extensibility.dll 

* File Path: `C:\Program Files (x86)\Common Files\Microsoft Shared\MSEnv\PublicAssemblies\extensibility.dll`
* Description: Extensibility.dll

## Hashes

Type | Hash
-- | --
MD5 | `F8D11C60B70ACD2EC9154EE676F615BA`
SHA1 | `A869FC75F44438D9207511DC73BAE976F558BA6E`
SHA256 | `B342088C8A4403092703BF40062041265E12EDD204AFF4F6532226478A65CBB2`
SHA384 | `62E0CA2A8D04EBE87006C3AC1E0F7EF192DDE31B189EEE0DD5EEEDB004AB5A29B991EAB22AC4BA157792AD951DFA9DCD`
SHA512 | `C4C324E22FF7570C6D9A6FCD5EA3BFC4917A404110B3E202BE847355C57C189096FEB5C37C0A36C541F4A9D9E80BB1F1BC5DB3F4146E515BA34468C5547BA907`
SSDEEP | `48:6H73BCKHGta7+hUGC9tkfY66hd+IvC+GbzActhIZWi9fOTAS5WPxC:oB0tphUGCPj663xvObzAcLEWjHWP`
IMP | `DAE02F32A21E03CE65412F6E56942DAA`
PESHA1 | `710078BDFF21E82C0803B811278832CC9C9BF5F5`
PE256 | `777A9F08E71DF2419663107132472EB1230B6B7E9FAC4A8BE1E0497D92E53C05`


## Signature

* Status: The file C:\Program Files (x86)\Common Files\Microsoft Shared\MSEnv\PublicAssemblies\extensibility.dll is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: Extensibility.dll
* Product Name: Microsoft Visual Studio .NET
* Company Name: Microsoft Corporation
* File Version: 7.00.9466
* Product Version: 7.00.9466
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/b342088c8a4403092703bf40062041265e12edd204aff4f6532226478a65cbb2/detection/

## Possible Misuse

*The following table contains possible examples of `extensibility.dll` being misused. While `extensibility.dll` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [win_susp_direct_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_susp_direct_asep_reg_keys_modification.yml) | `description: Detects direct modification of autostart extensibility point (ASEP) in registry using reg.exe.` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_asep_reg_keys_modification.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/registry_event/sysmon_asep_reg_keys_modification.yml) | `description: Detects modification of autostart extensibility point (ASEP) in registry` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


