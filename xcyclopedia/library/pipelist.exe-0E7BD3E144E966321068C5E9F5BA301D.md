---
title: pipelist.exe | Lists open named pipes
excerpt: What is pipelist.exe?
---

# pipelist.exe 

* File Path: `C:\SysinternalsSuite\pipelist.exe`
* Description: Lists open named pipes

## Hashes

Type | Hash
-- | --
MD5 | `0E7BD3E144E966321068C5E9F5BA301D`
SHA1 | `00919FEAAFECB87369D0605D3ECB9FBE69B41507`
SHA256 | `2156D7D3158EA589E8187C5CB82442EE6C37EE982BC0D728EDC8A50A2A1C4281`
SHA384 | `5F28F37509DC93186A23A9C401D293691241062F0D45B70A1848961F9E78B9D55048F8F1D73F3449AF991E646B3700D1`
SHA512 | `0AB6BB567E2B02460C724AB3CD83FC94F27CA0E268417BBD3A96F37F8B237C8DCFB62ACEDB2081E21EE216168933AC49C0FE502077FDB9FD6ED68C1088A05180`
SSDEEP | `6144:Yxhmgd8B4mPalFmZUYQXw/uc1Jiq0MPiU44tzElX:YSgM4mPafmiYQ6t1L18X`
IMP | `750C5946C0A20EE752F648B16312BE3A`
PESHA1 | `217DD3EA40D3DA05094C0DC6E1EF4274EA66929C`
PE256 | `DC5233CDA94B669C665F55B833A8F1DF17061484A91C19C58637042B2620A5F6`

## Runtime Data

### Usage (stdout):
```cmhg

PipeList v1.02 - Lists open named pipes
Copyright (C) 2005-2016 Mark Russinovich
Sysinternals - www.sysinternals.com

Pipe Name                                    Instances       Max Instances
---------                                    ---------       -------------
InitShutdown                                      3               -1      
lsass                                             4               -1      
ntsvcs                                            3               -1      
scerpc                                            3               -1      
Winsock2\CatalogChangeListener-298-0              1                1      
Winsock2\CatalogChangeListener-34c-0              1                1      
epmapper                                          3               -1      
Winsock2\CatalogChangeListener-258-0              1                1      
LSM_API_service                                   3               -1      
Winsock2\CatalogChangeListener-308-0              1                1      
eventlog                                          3               -1      
Winsock2\CatalogChangeListener-428-0              1                1      
TermSrv_API_service                               3               -1      
Ctx_WinStation_API_service                        3               -1      
wkssvc                                            4               -1      
atsvc                                             3               -1      
spoolss                                           3               -1      
SessEnvPublicRpc                                  3               -1      
Winsock2\CatalogChangeListener-618-0              1                1      
Winsock2\CatalogChangeListener-3c8-0              1                1      
Winsock2\CatalogChangeListener-438-0              1                1      
trkwks                                            3               -1      
srvsvc                                            4               -1      
Winsock2\CatalogChangeListener-868-0              1                1      
Winsock2\CatalogChangeListener-284-0              1                1      
TSVCPIPE-24ab4aa6-7fe0-4229-9ebe-a6792d481794          7               -1      
PIPE_EVENTROOT\CIMV2SCM EVENT PROVIDER            1               -1      
PowerShellISEPipeName_1_66bbfac3-9929-4d37-87c5-3455013cdf68          1               -1      
PSHost.132455098211545351.676.DefaultAppDomain.powershell_ise          1                1      
efsrpc                                            3               -1      

```

### Loaded Modules:

Path |
-- |
C:\SysinternalsSuite\pipelist.exe |
C:\Windows\SYSTEM32\ntdll.dll |
C:\Windows\System32\wow64.dll |
C:\Windows\System32\wow64cpu.dll |
C:\Windows\System32\wow64win.dll |


## Signature

* Status: Signature verified.
* Serial: `3300000187721772155940C709000000000187`
* Thumbprint: `2485A7AFA98E178CB8F30C9838346B514AEA4769`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: pipelist.exe
* Product Name: Sysinternals PipeList
* Company Name: Sysinternals - www.sysinternals.com
* File Version: 1.02
* Product Version: 1.02
* Language: English (United States)
* Legal Copyright: Copyright (C) 2005-2016 Mark Russinovich
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/2156d7d3158ea589e8187c5cb82442ee6c37ee982bc0d728edc8a50a2a1c4281/detection/


## Possible Misuse

*The following table contains possible examples of `pipelist.exe` being misused. While `pipelist.exe` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | description = "Detects NirSoft PipeList" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | $s1 = "PipeList" ascii fullword | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | and not filename contains "pipelist.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [yara_mixed_ext_vars.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/yara_mixed_ext_vars.yar) | and not filename contains "PipeList.exe" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


