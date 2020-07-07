---
title: verclsid.exe | Extension CLSID Verification Host
---

# verclsid.exe 

* File Path: `C:\windows\SysWOW64\verclsid.exe`
* Description: Extension CLSID Verification Host
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `A8D94E0B69D09A4C93B87EDEC8ECEBB9`
SHA1 | `C19679F11320A41D2558058CE0458311699C57DF`
SHA256 | `2294FED3A1625476EBC1AFC219793FA9ED4CE56AE036926B79776CBAC1EC2B30`
SHA384 | `C493EF3FCEB32AC38FA0F3BB9D919BDCB3C5347159717B07B2A5177334C031DBA08C28CCECF0C1F6EDC7F47FBDDD4131`
SHA512 | `180FE1AEFA24E49D2E1BCBBD8B422DCF87B23DAF58DE51E5AC2E3278F207C46DDD65048FE2FFFF26261C18CB5CCEE3334D8E840AFDC1D6AF5B35761588AEFE39`
SSDEEP | `96:KRf9UHJpooq5JXNKncxjEx9NvDWPTE2Fb+uDpVbvJOoO19u0yDJdMx2bKveL5vEj:KR1UJmhXQolTV1DxOoO1kVqOsWkNWx`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: The file C:\windows\SysWOW64\verclsid.exe is not digitally signed. You cannot run this script on the current system. For more information about running scripts and setting execution policy, see about_Execution_Policies at http://go.microsoft.com/fwlink/?LinkID=135170
* Serial: ``
* Thumbprint: ``
* Issuer: 
* Subject: 

## File Metadata

* Original Filename: verclsid.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 6.3.9600.17415 (winblue_r4.141028-1500)
* Product Version: 6.3.9600.17415
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.


## Possible Misuse

*The following table contains possible examples of `verclsid.exe` being misused. While `verclsid.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `title: Malware Shellcode in Verclsid Target Process` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `description: Detects a process access to verclsid.exe that injects shellcode from a Microsoft Office application / VBA macro` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_malware_verclsid_shellcode.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_access/sysmon_malware_verclsid_shellcode.yml) | `        TargetImage: '*\verclsid.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `Name: Verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `  - Command: verclsid.exe /S /C {CLSID}` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `  - Path: C:\Windows\System32\verclsid.exe` | 
[LOLBAS](https://github.com/LOLBAS-Project/LOLBAS) | [Verclsid.yml](https://github.com/LOLBAS-Project/LOLBAS/blob/master/yml/OSBinaries/Verclsid.yml) | `  - Path: C:\Windows\SysWOW64\verclsid.exe` | 



MIT License. Copyright (c) 2020 Strontic.


