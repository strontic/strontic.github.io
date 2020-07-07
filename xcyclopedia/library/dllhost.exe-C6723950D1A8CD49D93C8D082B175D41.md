---
title: dllhost.exe | COM Surrogate
---

# dllhost.exe 

* File Path: `C:\Windows\system32\dllhost.exe`
* Description: COM Surrogate
* Comments: 

## Hashes

Type | Hash
-- | --
MD5 | `C6723950D1A8CD49D93C8D082B175D41`
SHA1 | `45E05A31CBAE71818816EC86AA6152F6D8C22E8C`
SHA256 | `FFBFD4EA38939327584779F31F46CC8A8AFA0AD03A783A35D1C166C335E7B910`
SHA384 | `4189FB4C78239045790FF7D036AC4C24153FA2D73EB3CBA043FE31E60184188D13AF26F8A6981F2836B278DE26A7CBD7`
SHA512 | `EC559A2A244731CEAF10E39F7A2958FDB3500C95F9F196C644DA2CBB47135A50BCB8ACEAC559B11C9F23E085EB5EC9471A4B60E47D9470E5DAAAE1BB9D5A91C0`
SSDEEP | `384:Z7JRXcksOlcUcZlHWg5WiD1IDBRJJAZhKtklxt:Z7JR7WUcZlDdI1Pe`

## Runtime Data

### Usage (stdout):
```Batchfile

```

### Usage (stderr):
```Batchfile

```

### Child Processes:


## Signature

* Status: Signature verified.
* Serial: `330000023241FB59996DCC4DFF000000000232`
* Thumbprint: `FF82BC38E1DA5E596DF374C53E3617F7EDA36B06`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: dllhost.exe
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.

## File Similarity (ssdeep match)

File | Score
-- | --
[C:\Windows\system32\backgroundTaskHost.exe](backgroundTaskHost.exe-9B19B73580F7813DAD7C7C4671D004E5.md) | 38
[C:\Windows\system32\DeviceCensus.exe](DeviceCensus.exe-8159944C79034D2BCABF73D461A7E643.md) | 33
[C:\WINDOWS\system32\DeviceCensus.exe](DeviceCensus.exe-AC7BD0E738FDE12FB29DA98D88C903EA.md) | 30
[C:\Windows\system32\dllhst3g.exe](dllhst3g.exe-E4208ACA399EC8C0AD48B05960F7FA9D.md) | 41
[C:\Windows\system32\NDKPing.exe](NDKPing.exe-5FC26E00B9012CC0188F65BB999174E9.md) | 43
[C:\Windows\system32\oobe\FirstLogonAnim.exe](FirstLogonAnim.exe-EA059E3BA7E07347BDE08EF016E09D50.md) | 36
[C:\Windows\system32\prproc.exe](prproc.exe-912400A90CA88E80ABC6CB8F30C1BB41.md) | 40
[C:\Windows\system32\ResetEngine.exe](ResetEngine.exe-100E032F234550530487627EC8FACAA8.md) | 33
[C:\WINDOWS\system32\ResetEngine.exe](ResetEngine.exe-5A802B773089A709FC7E731368C4E328.md) | 35
[C:\WINDOWS\system32\ScriptRunner.exe](ScriptRunner.exe-C024FF9A88E26EEB26A1A942260489BC.md) | 36
[C:\Windows\system32\SlideToShutDown.exe](SlideToShutDown.exe-FD18CDC89BFD664E85644B460C37D85B.md) | 40
[C:\Windows\system32\wuauclt.exe](wuauclt.exe-7582BF723A39B56BCCEF2C170E330BD7.md) | 32
[C:\Windows\SysWOW64\backgroundTaskHost.exe](backgroundTaskHost.exe-8B50BFD5811304543479B20D0A281C56.md) | 35
[C:\Windows\SysWOW64\CameraSettingsUIHost.exe](CameraSettingsUIHost.exe-AB2C7BC86F9E1BB245E43C81A01A7380.md) | 27
[C:\Windows\SysWOW64\dllhost.exe](dllhost.exe-BE467A8F33CDEB0538E98CF10101E9E0.md) | 44

## Possible Misuse

*The following table contains possible examples of `dllhost.exe` being misused. While `dllhost.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_creation_system_file.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_creation_system_file.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [sysmon_susp_adsi_cache_usage.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/file_event/sysmon_susp_adsi_cache_usage.yml) | `            - 'C:\windows\system32\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_cmstp_com_object_access.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_cmstp_com_object_access.yml) | `        ParentCommandLine\|contains: '\DllHost.exe '` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)
[sigma](https://github.com/Neo23x0/sigma) | [win_system_exe_anomaly.yml](https://github.com/Neo23x0/sigma/blob/master/rules/windows/process_creation/win_system_exe_anomaly.yml) | `            - '*\dllhost.exe'` | [DRL 1.0](https://github.com/Neo23x0/sigma/blob/master/LICENSE.Detection.Rules.md)



MIT License. Copyright (c) 2020 Strontic.


