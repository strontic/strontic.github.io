---
title: SENDTO.DLL | SendTo9 RPC Proxy/Stub DLL
excerpt: What is SENDTO.DLL?
---

# SENDTO.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\SENDTO.DLL`
* Description: SendTo9 RPC Proxy/Stub DLL

## Hashes

Type | Hash
-- | --
MD5 | `6D4E9BD8423CDFACED2C4C75D207FB79`
SHA1 | `5975B5B08E858B86920F22E0D450299F9B6D7C20`
SHA256 | `4EB94CF508D7A8003D627EFFEF27539456F7C7E388CD812316691E4EEC666AA0`
SHA384 | `7E407A9E21518218B8CFB38EECCC305A035930A8C891A4619FE95E3560980A30790FA931DD6CA218C2FBE78CBCBF251F`
SHA512 | `D8B3B9E9B469F80F175396CFADCD95A2ECCE069216370F47887B8A6DA842157844003D739B868AE8750D045B2DA5EA50212461822D30DA77337F2CFAFEB28D8B`
SSDEEP | `384:JIueBNJLWLEK/hTy/cIbPrzf3TqDI7WjDGW61wvYlOgPcbHRN7qOlOgF+:4N9DKpTyE+P3W2MbI`
IMP | `774D7043C8B9D59B8982A489036BF7F4`
PESHA1 | `39BEC7AACF247B4C6A4A61FD4ACD7D88661FE54D`
PE256 | `FFCF2F5D7E71AF527FE0F35BF97008E76BA3AEE1E408A6C1D1FD303E875B0356`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`DllCanUnloadNow` | 1 | Exported Function
`DllGetClassObject` | 2 | Exported Function
`DllRegisterServer` | 3 | Exported Function
`DllUnregisterServer` | 4 | Exported Function
`GetProxyDllInfo` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: SendTo9.Dll
* Product Name: Microsoft Outlook
* Company Name: Microsoft Corporation
* File Version: 16.0.12325.20144
* Product Version: 16.0.12325.20144
* Language: Language Neutral
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/4eb94cf508d7a8003d627effef27539456f7c7e388cd812316691e4eec666aa0/detection/

## Possible Misuse

*The following table contains possible examples of `SENDTO.DLL` being misused. While `SENDTO.DLL` is **not** inherently malicious, its legitimate functionality can by abused for malicious purposes.*

Source | Source File | Example | License
-- | -- | -- | --
[malware-ioc](https://github.com/eset/malware-ioc) | [sshdoor.yar](https://github.com/eset/malware-ioc/blob/master/sshdoor/sshdoor.yar) | `$i3 = "sendto"` | [© ESET 2014-2018](https://github.com/eset/malware-ioc/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_hkdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_hkdoor.yar) | pe.imports("ws2_32.dll", "sendto") | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)
[signature-base](https://github.com/Neo23x0/signature-base) | [apt_triton_mal_sshdoor.yar](https://github.com/Neo23x0/signature-base/blob/master/yara/apt_triton_mal_sshdoor.yar) | $crait_i3 = "sendto" | [CC BY-NC 4.0](https://github.com/Neo23x0/signature-base/blob/master/LICENSE)



MIT License. Copyright (c) 2020 Strontic.


