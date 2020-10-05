---
title: SignalRClient.dll | Microsoft SignalR C++ Client (v140)
excerpt: What is SignalRClient.dll?
---

# SignalRClient.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\SignalRClient.dll`
* Description: Microsoft SignalR C++ Client (v140)

## Hashes

Type | Hash
-- | --
MD5 | `1F5CD830F285610227E716668A888A61`
SHA1 | `8C03F2237D037011EFF33E41A86E4B7DC3FB5BC4`
SHA256 | `2C3F8D9E9D16ED06A14C2D1561853F06C8ECDD429B5CC774EEDDBD37CE776F7E`
SHA384 | `DE37AE05039D296A23C0A592DA92BC714CC3DCFCB3DAE204B5A0E15A7B67DFFC7D57808B6E8CFB3E82CED64BE85C6903`
SHA512 | `BBE2407224CC4B668CFD78B96B2AC7988AC9F827C15F4E4A7CBA02ED5935D8C15A8763F37AC723FA30E7DC5BCF6F0F0E7A24416715B74D2AED1A474E86F8F134`
SSDEEP | `6144:sDdtfQnNq9Xk0KdhjjDHwqCfqaiF1ynDb+w988ISVBIX:sDYIgDgZie5TJVqX`
IMP | `14B003FC996B213CDDAAA27D1E7A2BBB`
PESHA1 | `D688F388AC0EDC64E90A076E0A530C3D316F9A3A`
PE256 | `1A097830155623F371DC0ECC2C4B650ABFC70BF11E6A0EFB70B3E7B23729BEA7`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: void __cdecl signalr::connection::set_disconnected(class std::function<void __cdecl(void)> const &)` | 31 | Exported Function
`public: void __cdecl signalr::connection::set_client_config(class signalr::signalr_client_config const &)` | 27 | Exported Function
`public: void __cdecl signalr::connection::set_message_received(class std::function<void __cdecl(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)> const &)` | 35 | Exported Function
`public: void __cdecl signalr::connection::set_reconnecting(class std::function<void __cdecl(void)> const &)` | 39 | Exported Function
`public: void __cdecl signalr::connection::set_reconnected(class std::function<void __cdecl(void)> const &)` | 37 | Exported Function
`public: struct signalr::connection_settings __cdecl signalr::signalr_client_config::get_connection_settings(void)const ` | 14 | Exported Function
`public: class web::http::http_headers __cdecl signalr::signalr_client_config::get_http_headers(void)const ` | 20 | Exported Function
`public: class web::http::client::http_client_config __cdecl signalr::signalr_client_config::get_http_client_config(void)const ` | 19 | Exported Function
`public: class web::websockets::client::websocket_client_config __cdecl signalr::signalr_client_config::get_websocket_client_config(void)const ` | 22 | Exported Function
`public: enum signalr::connection_state __cdecl signalr::hub_connection::get_connection_state(void)const ` | 16 | Exported Function
`public: enum signalr::connection_state __cdecl signalr::connection::get_connection_state(void)const ` | 15 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_http_client_config(class web::http::client::http_client_config const &)` | 33 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_credentials(class web::credentials const &)` | 30 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_http_headers(class web::http::http_headers const &)` | 34 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_websocket_client_config(class web::websockets::client::websocket_client_config const &)` | 41 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_proxy(class web::web_proxy const &)` | 36 | Exported Function
`public: void __cdecl signalr::signalr_client_config::set_connection_settings(struct signalr::connection_settings const &)` | 29 | Exported Function
`public: void __cdecl signalr::hub_connection::set_disconnected(class std::function<void __cdecl(void)> const &)` | 32 | Exported Function
`public: void __cdecl signalr::hub_connection::set_client_config(class signalr::signalr_client_config const &)` | 28 | Exported Function
`public: void __cdecl signalr::hub_connection::set_reconnected(class std::function<void __cdecl(void)> const &)` | 38 | Exported Function
`public: void __cdecl signalr::hub_proxy::on(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::function<void __cdecl(class web::json::value const &)> const &)` | 25 | Exported Function
`public: void __cdecl signalr::hub_connection::set_reconnecting(class std::function<void __cdecl(void)> const &)` | 40 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl signalr::hub_proxy::get_hub_name(void)const ` | 21 | Exported Function
`public: __thiscall signalr::hub_proxy::hub_proxy(class signalr::hub_proxy const &)` | 4 | Exported Function
`public: __thiscall signalr::hub_proxy::hub_proxy(class signalr::hub_proxy const &&)` | 3 | Exported Function
`public: __thiscall signalr::hub_proxy::hub_proxy(void)` | 5 | Exported Function
`public: class Concurrency::task<void> __cdecl signalr::connection::send(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 26 | Exported Function
`public: __thiscall signalr::hub_proxy::~hub_proxy(void)` | 8 | Exported Function
`public: __thiscall signalr::hub_connection::~hub_connection(void)` | 7 | Exported Function
`private: class Concurrency::task<void> __cdecl signalr::hub_proxy::invoke_void(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class web::json::value const &,class std::function<void __cdecl(class web::json::value const &)> const &)` | 24 | Exported Function
`private: class Concurrency::task<class web::json::value> __cdecl signalr::hub_proxy::invoke_json(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class web::json::value const &,class std::function<void __cdecl(class web::json::value const &)> const &)` | 23 | Exported Function
`public: __thiscall signalr::connection::connection(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,enum signalr::trace_level,class std::shared_ptr<class signalr::log_writer>)` | 1 | Exported Function
`public: __thiscall signalr::hub_connection::hub_connection(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,enum signalr::trace_level,class std::shared_ptr<class signalr::log_writer>,bool,class std::shared_ptr<class signalr::connection_progress>)` | 2 | Exported Function
`public: __thiscall signalr::connection::~connection(void)` | 6 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl signalr::connection::get_connection_id(void)const ` | 12 | Exported Function
`public: class signalr::hub_proxy __cdecl signalr::hub_connection::create_hub_proxy(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 11 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl signalr::connection::get_connection_token(void)const ` | 17 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl signalr::hub_connection::get_connection_token(void)const ` | 18 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl signalr::hub_connection::get_connection_id(void)const ` | 13 | Exported Function
`public: class signalr::hub_proxy & __cdecl signalr::hub_proxy::operator=(class signalr::hub_proxy const &)` | 10 | Exported Function
`public: class Concurrency::task<void> __cdecl signalr::connection::stop(void)` | 44 | Exported Function
`public: class Concurrency::task<void> __cdecl signalr::connection::start(void)` | 42 | Exported Function
`public: class Concurrency::task<void> __cdecl signalr::hub_connection::start(void)` | 43 | Exported Function
`public: class signalr::hub_proxy & __cdecl signalr::hub_proxy::operator=(class signalr::hub_proxy const &&)` | 9 | Exported Function
`public: class Concurrency::task<void> __cdecl signalr::hub_connection::stop(void)` | 45 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CF6D2CC57CAA65A6D80000000002CF`
* Thumbprint: `1A221B3B4FEF088B17BA6704FD088DF192D9E0EF`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: signalrclient.dll
* Product Name: SignalR C++ Client (v140)
* Company Name: Microsoft Corporation
* File Version: 1.0.0.0
* Product Version: 1.0.0-alpha1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation.  All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/2c3f8d9e9d16ed06a14c2d1561853f06c8ecdd429b5cc774eeddbd37ce776f7e/detection/




MIT License. Copyright (c) 2020 Strontic.


