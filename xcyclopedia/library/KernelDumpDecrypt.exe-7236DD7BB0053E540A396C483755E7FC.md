---
title: KernelDumpDecrypt.exe | Windows Kernel Dump File Decryptor
excerpt: What is KernelDumpDecrypt.exe?
---

# KernelDumpDecrypt.exe 

* File Path: `C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\KernelDumpDecrypt.exe`
* Description: Windows Kernel Dump File Decryptor

## Hashes

Type | Hash
-- | --
MD5 | `7236DD7BB0053E540A396C483755E7FC`
SHA1 | `8B80C883F0B16C4F5FABE30971303A7B240711F3`
SHA256 | `A629705EBC2205EE0C565E397E93814A46BA40A35E981FBC8B8F0EBF8D8E2E95`
SHA384 | `76E9F094144EEE54506B065CFE9849224A0ACE1C1F138ECFD3AEFD02008F2F2D16BA96CAF95E59B92CF0E886C91BC6AB`
SHA512 | `B05D970C87654E10954D498046636A0BCE97884A547ECC18BD2FF7A5BA424CE6D4DB3E011B82AB4356DCF23F748B0E52DDDD23D7956CC90CEFB5AC6259C6D3E1`
SSDEEP | `384:LtSsmphK0Wvpv81zpqv2f0x8FYaHeaq/SWoXWEYwGyAlITvb:Jjcwe1F1yCeFcOov`
IMP | `4831C665BDBFB7166F68E6FB09509318`
PESHA1 | `B2BFDDBC2767DE31FE60CEBDF5DDA8E2898652CC`
PE256 | `8B169AE37C89B2C0E61B2AEC836896071AE8F2D3B62A5D48ACAE727B6E0B4031`

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
C:\Program Files (x86)\Windows Kits\10\Debuggers\x64\KernelDumpDecrypt.exe |
C:\Windows\System32\KERNEL32.DLL |
C:\Windows\System32\KERNELBASE.dll |
C:\Windows\SYSTEM32\ntdll.dll |


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/75
* VirusTotal Link: https://www.virustotal.com/gui/file/a629705ebc2205ee0c565e397e93814a46ba40a35e981fbc8b8f0ebf8d8e2e95/detection





MIT License. Copyright (c) 2020-2021 Strontic.


