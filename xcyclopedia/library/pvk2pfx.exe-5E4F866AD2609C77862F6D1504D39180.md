---
title: pvk2pfx.exe | PVK/SPC to PFX file converter
excerpt: What is pvk2pfx.exe?
---

# pvk2pfx.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\pvk2pfx.exe`
* Description: PVK/SPC to PFX file converter

## Hashes

Type | Hash
-- | --
MD5 | `5E4F866AD2609C77862F6D1504D39180`
SHA1 | `B3B1962AD521595E14DC40E4EAE43D6E93971713`
SHA256 | `518A17B39FFE3C205D9FDD68A3A1E27C14177708A85551F58042FA4EC915BA15`
SHA384 | `DDDAF269B257542A3A892314BAC41C6AC0D1C489866360C5D765257ABDF172B99B76E140CD25C1A6686246C6CF77D7AD`
SHA512 | `C7B0820205FB73D05BA94191A8F9C82C8CB1B7861CA0CA4F005F966D4401B3CFDDF70B550C83BCEB77588F5A613740F79D33608AD41DDA80F4FCA8437EF78183`
SSDEEP | `384:9YWI5dnWO6vbhe0NQQd/hqWKvlH19d9g7riWLkWkKOXciwGynTTzIwS+klTxi:OXJXEe0NQM5BK91/Wr/qKOf8vdO`
IMP | `CBED8978BD13D078156B76651A089815`
PESHA1 | `D386471110F00D262042C375D56E5725CAF9A943`
PE256 | `5ECBA5C40960EE367C4A9C30905AC641B8EB1A72008056C759815691C68629EA`

## Runtime Data

### Usage (stderr):
```cmhg

Usage:
    pvk2pfx -pvk <pvk-file> [-pi <pvk-pswd>] -spc <spc-file>
           [-pfx <pfx-file> [-po <pfx-pswd>] [-f]]

        -pvk <pvk-file>  - input PVK file name.
        -spc <spc-file>  - input SPC file name.
        -pfx <pfx-file>  - output PFX file name.
        -pi <pvk-pswd>   - PVK password.
        -po <pfx-pswd>   - PFX password; same as -pi if not given.
        -f               - force overwrite existing PFX file.

        if -pfx option is not given, an export wizard will pop up. in
        this case, options -po and -f are ignored.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\pvk2pfx.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pvk2pfx.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/518a17b39ffe3c205d9fdd68a3a1e27c14177708a85551f58042fa4ec915ba15/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\Smart Tag\SmartTagInstall.exe](SmartTagInstall.exe-632AB2DBE46DE1E9BB0FB7B54B3BB05C.md) | 29
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\arm64\pvk2pfx.exe](pvk2pfx.exe-C0002840F47F992AFA351FD697491929.md) | 29
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x64\pvk2pfx.exe](pvk2pfx.exe-6E300F27AA19FCD62D309F6622107B68.md) | 30
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\convertstore.exe](convertstore.exe-47A94D2F58F4C4E6D08A74B0FEDC89A5.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\KernelDumpDecrypt.exe](KernelDumpDecrypt.exe-8990D55CD7DBA7B9A0FE25B448D2FBBF.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-core-handle-l1-1-0.dll](api-ms-win-core-handle-l1-1-0.dll-1CF1915F2BEBBFD01C1AD340C8438AA7.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-crt-math-l1-1-0.dll](api-ms-win-crt-math-l1-1-0.dll-E798070D2F259C51EDD04FAFFD39477D.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-crt-runtime-l1-1-0.dll](api-ms-win-crt-runtime-l1-1-0.dll-F90FE8F6F46C7ED429F3E802DEE23469.md) | 35
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-core-console-l1-2-0.dll](api-ms-win-core-console-l1-2-0.dll-C72A9CA97ED04384C43D71B6C2819A78.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-core-libraryloader-l1-1-0.dll](api-ms-win-core-libraryloader-l1-1-0.dll-2791E9E5FB104A377C5C4C16B27F2612.md) | 36
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-crt-runtime-l1-1-0.dll](api-ms-win-crt-runtime-l1-1-0.dll-AA4ECF393C106E9687B7BB8AB91BB431.md) | 41
[C:\Windows\system32\downlevel\api-ms-win-core-errorhandling-l1-1-0.dll](api-ms-win-core-errorhandling-l1-1-0.dll-C70BC6950514139DE25A7BF78D01CBF5.md) | 30
[C:\Windows\system32\downlevel\api-ms-win-core-localization-l1-2-0.dll](api-ms-win-core-localization-l1-2-0.dll-464DF4108FD3C92B67953ADFD272D093.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-core-registry-l1-1-0.dll](api-ms-win-core-registry-l1-1-0.dll-EE67ECCFF1EC5527BCBAE3859A60576A.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-core-timezone-l1-1-0.dll](api-ms-win-core-timezone-l1-1-0.dll-83E18EE6246907BA1DE2715692C113C7.md) | 33
[C:\Windows\system32\downlevel\api-ms-win-crt-environment-l1-1-0.dll](api-ms-win-crt-environment-l1-1-0.dll-9653409A06CF90AEAE4491EE6A66125C.md) | 30
[C:\Windows\system32\downlevel\api-ms-win-shcore-stream-l1-1-0.dll](api-ms-win-shcore-stream-l1-1-0.dll-A7345C9A04290DD9793F75E58282CA31.md) | 32
[C:\Windows\system32\kd.dll](kd.dll-8B1596C15C53EE3CD3C9B3CB17518195.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-delayload-l1-1-0.dll](api-ms-win-core-delayload-l1-1-0.dll-E4A997A788A2E02BCE3068EEDC524C7B.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-fibers-l1-1-1.dll](api-ms-win-core-fibers-l1-1-1.dll-C49938B5D4A709984C8FA33BF2C18046.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-processenvironment-l1-1-0.dll](api-ms-win-core-processenvironment-l1-1-0.dll-26E6B45BE5422947F9B5E6DB9355F676.md) | 30
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-realtime-l1-1-0.dll](api-ms-win-core-realtime-l1-1-0.dll-581779B9812E301268CD3F8FCD26E897.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-version-l1-1-0.dll](api-ms-win-core-version-l1-1-0.dll-60C3AA0275AB401269FCC5343CD24942.md) | 30
[C:\Windows\SysWOW64\downlevel\api-ms-win-crt-filesystem-l1-1-0.dll](api-ms-win-crt-filesystem-l1-1-0.dll-1931D2B08A0AE1BF619D68794E24209E.md) | 38
[C:\Windows\SysWOW64\downlevel\api-ms-win-crt-stdio-l1-1-0.dll](api-ms-win-crt-stdio-l1-1-0.dll-7B122ADB73C3EEBAC63D6567EC011C10.md) | 33
[C:\Windows\SysWOW64\fltLib.dll](fltLib.dll-BFE513C7E3E16B332ED75DDF44607C79.md) | 33
[C:\Windows\SysWOW64\IME\IMETC\IMTCTRLN.DLL](IMTCTRLN.DLL-09C0A650FE3B78EB0ACE5C626FDE511A.md) | 27




MIT License. Copyright (c) 2020 Strontic.


