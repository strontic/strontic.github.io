---
title: mip_core.dll | MIP SDK
excerpt: What is mip_core.dll?
---

# mip_core.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\mip_core.dll`
* Description: MIP SDK

## Hashes

Type | Hash
-- | --
MD5 | `9A1EEE8C14A8DD6891195C3193DC82EF`
SHA1 | `B2D1A88B50F2F1FA17B8A3EB7125281E815BF4F9`
SHA256 | `F04AC4097E4587D410F287C2040636DB18A44645A10D6A33341BA5C41AAB6481`
SHA384 | `F67422A51A82931D9458F80877B7537132F6A31685C0F58ECC19D6F567B2192E764C82B171BBE2617F56DFE5134C4182`
SHA512 | `B8F5CCCE84C170BD910D56DFAE224492F02CB3229D23A22915CCACB0F36172AE3F697F110F1F0F7831499D5C624F2DAE0F05431F57E68A69C07866F25CAD46AF`
SSDEEP | `12288:VFukC14IaTNcB8JmiXd124FggEeN1dEGhOhUdbOm5dgKGdn8q3doGO3yzwDvCx:VEkC14IaTNcB8JmiXd124FkVqOhUdbOR`
IMP | `302303C81601618496168D1C08B4D84F`
PESHA1 | `FC4A5C784939861F2DC74EFFB7FC0E84CDD78E82`
PE256 | `264E891664690649D03BAFE6E0BC82E51CB023758AE5819F09D6B11DDB8AFCB6`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`QueueTask` | 17 | Exported Function
`SendHttpRequest` | 18 | Exported Function
`HasCustomTaskHandler` | 16 | Exported Function
`public: static class std::shared_ptr<class mip::HttpClient> __cdecl mip::HttpClient::Create(void)` | 1 | Exported Function
`void __cdecl mip::logger::SetIsInitialized(void)` | 12 | Exported Function
`void __cdecl mip::SetAriaHttpDelegate(class std::shared_ptr<class mip::HttpDelegate> const &)` | 10 | Exported Function
`void __cdecl mip::SetAriaTaskDispatcherDelegate(class std::shared_ptr<class mip::TaskDispatcherDelegate> const &)` | 11 | Exported Function
`void __cdecl mip::logger::SetLoggerDelegateInstance(class std::shared_ptr<class mip::LoggerDelegate> const &)` | 13 | Exported Function
`void __cdecl mip::SendHttp(bool,class std::shared_ptr<class mip::HttpDelegate> const &,class std::shared_ptr<class mip::HttpRequest> const &,class std::shared_ptr<void> const &,class std::function<void __cdecl(class std::shared_ptr<class mip::HttpOperation> const &)> const &)` | 9 | Exported Function
`CancelTask` | 15 | Exported Function
`class mip::LoggerDelegate & __cdecl mip::logger::GetLoggerDelegateInstance(void)` | 7 | Exported Function
`bool __cdecl mip::logger::IsInitialized(void)` | 8 | Exported Function
`CancelHttpOperation` | 14 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl mip::GetAuthToken(class std::shared_ptr<class mip::AuthDelegate> const &,class mip::Identity const &,class mip::AuthDelegate::OAuth2Challenge const &)` | 5 | Exported Function
`class std::shared_ptr<class mip::HttpRequestBase> __cdecl mip::CreateHttpRequest(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum mip::HttpRequestType,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 2 | Exported Function
`class std::unique_ptr<class mip::Uri,struct std::default_delete<class mip::Uri> > __cdecl mip::CreateUri(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 4 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl mip::GetHeaderValueFromHttpResponse(class mip::HttpResponse const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 6 | Exported Function
`class std::shared_ptr<class mip::HttpRequestBase> __cdecl mip::CreateHttpRequest(class mip::HttpRequestBase const &)` | 3 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: 
* Product Name: MIP SDK
* Company Name: Microsoft Corporation
* File Version: 1.2.183
* Product Version: 1.2.183
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/f04ac4097e4587d410f287c2040636db18a44645a10d6a33341ba5c41aab6481/detection/




MIT License. Copyright (c) 2020 Strontic.


