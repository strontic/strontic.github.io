---
title: KernelDumpDecrypt.exe | Windows Kernel Dump File Decryptor
excerpt: What is KernelDumpDecrypt.exe?
---

# KernelDumpDecrypt.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\KernelDumpDecrypt.exe`
* Description: Windows Kernel Dump File Decryptor

## Hashes

Type | Hash
-- | --
MD5 | `8990D55CD7DBA7B9A0FE25B448D2FBBF`
SHA1 | `FF12864C1F6943F97CAE31F3CDA98EDEEEC24920`
SHA256 | `7B422910859C6D7C46F309CE857904B06FBE867E77C552786D23376804E73806`
SHA384 | `2DC947E64F437824DB9E1086A804812A756E2A83ABB0668490E5FE14822F95D7AC2F50CC45624243815251E9228D9872`
SHA512 | `785D35A9F934261E8150056F6F177CE74F8B176221397C7EE4169B443C213420C0EAE47F5271D1B6A0F29A120F31B1AEDA8871CA9CA312C8462AB8C520D2D653`
SSDEEP | `384:52815cuxAUXQTEWaWc1IvNK/Yadeh2iaWoXWorywwGyzTzIwS+klTxXH:ko53QvPc1IvsAYe/Unryw8vdO3`
IMP | `1E442598CB7E6DB7CAAD1C1E6392857C`
PESHA1 | `007172FF9059F93B0D6F362270EBD6AA9A31B485`
PE256 | `7E75E8284C0EBD5AF4BB0FB3392C8BF4849BD0DDCC0EBFD1AF1765E447DD2E1D`

## Runtime Data

### Usage (stdout):
```cmhg
Usage: KernelDumpDecrypt [args] <input.dmp> <output.dmp>
Where args is a sequence of the following:
	/user             - Use user certificate store/key store.
	/machine          - Use machine certificate store/key store.
	/keystore <name>  - Name of the key store provider.
	/keyname <name>   - Name of the key to lookup in the KSP.
	/keyfile <path>   - Path to the file containing a raw private key
	                    or a full key pair (starts with 'RSA2' magic).
	/enumproviders    - List key store providers.
	/enumkeys         - List keys in the key store.

If no key parameters are specified, the tool looks up the certificate
matching the thumbprint contained in the encrypted dump file.
If only the keyname is specified, the key will be retrieved from the
default key store for the current user.

Examples:

KernelDumpDecrypt memory.dmp memory_decr.dmp
	Decrypts memory.dmp using the private key obtained from the
	current user's certificate store. Writes memory_decr.dmp.

KernelDumpDecrypt /machine memory.dmp memory_decr.dmp
	Decrypts the dump using a key obtained from the local
	machine's certificate store.

KernelDumpDecrypt  /user /keyname "My app key" memory.dmp memory_decr.dmp
	Decrypts the dump using named key in the
	user store of the default key storage provider


Exit status: SUCCEEDED: 00000000: The operation completed successfully.


```

### Loaded Modules:

Path |
-- |
C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\KernelDumpDecrypt.exe |
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

* Original Filename: KernelDumpDecrypt.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/76
* VirusTotal Link: https://www.virustotal.com/gui/file/7b422910859c6d7c46f309ce857904b06fbe867e77c552786d23376804e73806/detection

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX86\Microsoft Shared\Smart Tag\SmartTagInstall.exe](SmartTagInstall.exe-632AB2DBE46DE1E9BB0FB7B54B3BB05C.md) | 30
[C:\Program Files (x86)\Windows Kits\10\bin\10.0.19041.0\x86\pvk2pfx.exe](pvk2pfx.exe-5E4F866AD2609C77862F6D1504D39180.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Debuggers\x86\convertstore.exe](convertstore.exe-47A94D2F58F4C4E6D08A74B0FEDC89A5.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-core-handle-l1-1-0.dll](api-ms-win-core-handle-l1-1-0.dll-1CF1915F2BEBBFD01C1AD340C8438AA7.md) | 38
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-crt-math-l1-1-0.dll](api-ms-win-crt-math-l1-1-0.dll-E798070D2F259C51EDD04FAFFD39477D.md) | 33
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\arm\api-ms-win-crt-runtime-l1-1-0.dll](api-ms-win-crt-runtime-l1-1-0.dll-F90FE8F6F46C7ED429F3E802DEE23469.md) | 32
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-core-console-l1-2-0.dll](api-ms-win-core-console-l1-2-0.dll-C72A9CA97ED04384C43D71B6C2819A78.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-core-libraryloader-l1-1-0.dll](api-ms-win-core-libraryloader-l1-1-0.dll-2791E9E5FB104A377C5C4C16B27F2612.md) | 40
[C:\Program Files (x86)\Windows Kits\10\Redist\10.0.19041.0\ucrt\DLLs\x86\api-ms-win-crt-runtime-l1-1-0.dll](api-ms-win-crt-runtime-l1-1-0.dll-AA4ECF393C106E9687B7BB8AB91BB431.md) | 43
[C:\Windows\system32\downlevel\api-ms-win-core-errorhandling-l1-1-0.dll](api-ms-win-core-errorhandling-l1-1-0.dll-C70BC6950514139DE25A7BF78D01CBF5.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-core-localization-l1-2-0.dll](api-ms-win-core-localization-l1-2-0.dll-464DF4108FD3C92B67953ADFD272D093.md) | 29
[C:\Windows\system32\downlevel\api-ms-win-core-registry-l1-1-0.dll](api-ms-win-core-registry-l1-1-0.dll-EE67ECCFF1EC5527BCBAE3859A60576A.md) | 32
[C:\Windows\system32\downlevel\api-ms-win-core-timezone-l1-1-0.dll](api-ms-win-core-timezone-l1-1-0.dll-83E18EE6246907BA1DE2715692C113C7.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-crt-environment-l1-1-0.dll](api-ms-win-crt-environment-l1-1-0.dll-9653409A06CF90AEAE4491EE6A66125C.md) | 35
[C:\Windows\system32\downlevel\api-ms-win-shcore-stream-l1-1-0.dll](api-ms-win-shcore-stream-l1-1-0.dll-A7345C9A04290DD9793F75E58282CA31.md) | 35
[C:\Windows\system32\kd.dll](kd.dll-8B1596C15C53EE3CD3C9B3CB17518195.md) | 36
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-delayload-l1-1-0.dll](api-ms-win-core-delayload-l1-1-0.dll-E4A997A788A2E02BCE3068EEDC524C7B.md) | 33
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-fibers-l1-1-1.dll](api-ms-win-core-fibers-l1-1-1.dll-C49938B5D4A709984C8FA33BF2C18046.md) | 38
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-processenvironment-l1-1-0.dll](api-ms-win-core-processenvironment-l1-1-0.dll-26E6B45BE5422947F9B5E6DB9355F676.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-realtime-l1-1-0.dll](api-ms-win-core-realtime-l1-1-0.dll-581779B9812E301268CD3F8FCD26E897.md) | 33
[C:\Windows\SysWOW64\downlevel\api-ms-win-core-version-l1-1-0.dll](api-ms-win-core-version-l1-1-0.dll-60C3AA0275AB401269FCC5343CD24942.md) | 32
[C:\Windows\SysWOW64\downlevel\api-ms-win-crt-filesystem-l1-1-0.dll](api-ms-win-crt-filesystem-l1-1-0.dll-1931D2B08A0AE1BF619D68794E24209E.md) | 33
[C:\Windows\SysWOW64\downlevel\api-ms-win-crt-stdio-l1-1-0.dll](api-ms-win-crt-stdio-l1-1-0.dll-7B122ADB73C3EEBAC63D6567EC011C10.md) | 35
[C:\Windows\SysWOW64\fltLib.dll](fltLib.dll-BFE513C7E3E16B332ED75DDF44607C79.md) | 32
[C:\Windows\SysWOW64\IME\IMETC\IMTCTRLN.DLL](IMTCTRLN.DLL-09C0A650FE3B78EB0ACE5C626FDE511A.md) | 32




MIT License. Copyright (c) 2020-2021 Strontic.


