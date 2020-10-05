---
title: libcxypmp.dll | 
excerpt: What is libcxypmp.dll?
---

# libcxypmp.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\libcxypmp.dll`

## Hashes

Type | Hash
-- | --
MD5 | `C0A0EAC0AC9A5E3D2C8537323DCBBA7C`
SHA1 | `0A14F9DB255A0438515266D96A63529EBACF866B`
SHA256 | `BCDEA44573E19E48AF284371CFC88A38FD7243F891A3C617C5E0CE54468F0ED7`
SHA384 | `4953AA45B7E252E8428B0749D875616F22B145188541D18CBC797F31A171CAA1A1E66A4F9312CD1CFB7A83C13B3C3F86`
SHA512 | `CA9F0B21CBC92DDB9550E0035990C022A26D6FA1358F686AE5FB9F027533DED1A2C42AAF58FB187E85AC221509C82B633F010BF0DB5D8814A298276804ACA150`
SSDEEP | `12288:ao4ztAqTyWXxCbU+pr0/0PRzgaCXlBPhBLrkgDO6Q0hfg52gLSmY3CTgaF7apHvn:aoaAquSos/BBLrkgrfkp7OmfLTTU4Y`
IMP | `BFBEEFAF8229B881BB3690367988824C`
PESHA1 | `AEF7D478F9E805E46424014A9464493B86B38A4F`
PE256 | `13E7FDD49346B35887D8805D6F02D9B328A8DB8528C80AF0749B63AF03538A32`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static void __cdecl RefPtr<class Pmp::ConnectionManager>::swap(class RefPtr<class Pmp::ConnectionManager> &,class RefPtr<class Pmp::ConnectionManager> &)` | 73 | Exported Function
`public: struct _PmeConnectionManager * __thiscall RefPtr<class Pmp::ConnectionManager>::c_handle(void)const ` | 22 | Exported Function
`public: static void __cdecl Pmp::ConnectionManager::destroy(void)` | 30 | Exported Function
`public: static void __cdecl Pmp::ConnectionManager::onTURNConfigured(void *,int,int,char const *,int,int)` | 62 | Exported Function
`public: struct _PmeConnectionManager * __thiscall RefPtr<class Pmp::ConnectionManager>::ref_c_handle(void)const ` | 64 | Exported Function
`public: virtual int __thiscall Pmp::ConnectionManager::next_allocation_id(void)` | 60 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::allocate_ports(int,int,int,int,class RefPtr<class Pme::ConnectionListener>)` | 18 | Exported Function
`public: struct Pmp::TURNServer __thiscall Pmp::ConnectionManager::get_active_TURNserver(void)const ` | 37 | Exported Function
`public: virtual __thiscall Pmp::ConnectionManager::~ConnectionManager(void)` | 6 | Exported Function
`public: int __thiscall Pmp::ConnectionManager::get_turn_servers(class std::vector<struct Pmp::TURNServer,class std::allocator<struct Pmp::TURNServer> > &)` | 40 | Exported Function
`public: int __thiscall Pmp::ConnectionManager::ice_AllocateInstance(void *,bool,void (__cdecl*)(void *,int,bool))` | 50 | Exported Function
`public: class RefPtr<class Pmp::ConnectionManager> & __thiscall RefPtr<class Pmp::ConnectionManager>::reset(class Pmp::ConnectionManager *)` | 65 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall Pmp::ConnectionManager::get_active_TURNserver_fqdn(void)const ` | 38 | Exported Function
`public: int __thiscall RefPtr<class Pmp::ConnectionManager>::get_refcount(void)const ` | 39 | Exported Function
`public: static class RefPtr<class Pmp::ConnectionManager> __cdecl RefPtr<class Pmp::ConnectionManager>::from_objectbase(class ObjectBase *)` | 35 | Exported Function
`public: static class RefPtr<class Pmp::ConnectionManager> __cdecl RefPtr<class Pmp::ConnectionManager>::from_objectbase_new(class ObjectBase *)` | 36 | Exported Function
`public: static class RefPtr<class Pmp::ConnectionManager> __cdecl Pmp::ConnectionManager::create(void)` | 28 | Exported Function
`public: static class RefPtr<class Pmp::ConnectionManager> __cdecl RefPtr<class Pmp::ConnectionManager>::from_handle(struct _PmeConnectionManager *)` | 34 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::bind_conn_to_remote(int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,bool)` | 21 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::ice_Restart(int)` | 58 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::onTurnAllocated(int,int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool,int)` | 63 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::ice_Free(int)` | 51 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::ice_GetConclusion(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,int &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,int &,int &,bool &)` | 53 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::send_data(int,void const *,unsigned int)` | 66 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::set_tos(int,int,int)` | 71 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::startStunTrace(void *,class std::vector<struct Pmp::Cluster,class std::allocator<struct Pmp::Cluster> >,int,int,enum Pmp::CONNECTION_TRANSPORT,bool,void (__cdecl*)(void *,char const *,enum Pmp::TURNTransport,int,unsigned int))` | 72 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::set_ipv6(bool)` | 69 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::set_local_ip(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 70 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::free_ports(int)` | 33 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::send_data(int,class RefPtr<class Pme::Buffer>)` | 67 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::cancel_allocation(int)` | 23 | Exported Function
`public: virtual void __thiscall Pmp::ConnectionManager::free_one_port(int,int)` | 32 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::``vbase destructor'(void)` | 16 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::deallocate_one_turn_port(int,int)` | 29 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::enable_rtcpmux(int,bool)` | 31 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::allocate_ports_with_protocol(int,int,int,int,class RefPtr<class Pme::ConnectionListener>,enum Pmp::CONNECTION_TRANSPORT)` | 19 | Exported Function
`public: void __thiscall Pmp::ConnectionManager::configure(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 25 | Exported Function
`public: __thiscall RefPtr<class Pmp::ConnectionManager>::RefPtr<class Pmp::ConnectionManager>(class RefPtr<class Pmp::ConnectionManager> const &)` | 1 | Exported Function
`public: __thiscall RefPtr<class Pmp::ConnectionManager>::RefPtr<class Pmp::ConnectionManager>(void)` | 3 | Exported Function
`public: __thiscall Pmp::ConnectionManager::ConnectionManager(void)` | 4 | Exported Function
`public: __thiscall RefPtr<class Pmp::ConnectionManager>::RefPtr<class Pmp::ConnectionManager>(class Pmp::ConnectionManager *)` | 2 | Exported Function
`public: __thiscall RefPtr<class Pmp::ConnectionManager>::~RefPtr<class Pmp::ConnectionManager>(void)` | 5 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::configure_turn(void *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned int,unsigned int,enum Pmp::TURNTransport,void (__cdecl*)(void *,int,int))` | 26 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::configure_turn(void *,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<struct Pmp::TURNServer,class std::allocator<struct Pmp::TURNServer> > const &,unsigned int,unsigned int,void (__cdecl*)(void *,int,int))` | 27 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::allocate_turn_ports_with_protocol(void *,class std::vector<struct Pmp::TurnAllocation,class std::allocator<struct Pmp::TurnAllocation> > const &,void (__cdecl*)(void *,int))` | 20 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::cancel_turn(void)` | 24 | Exported Function
`const Pmp::ConnectionManager::``vftable'{for ``Pme::ConnectionManager'}` | 13 | Exported Function
`private: static void __cdecl Pmp::ConnectionManager::onServerTraced(void *,char const *,int,int,int,unsigned int)` | 61 | Exported Function
`const Pmp::ConnectionManager::``vbtable'` | 15 | Exported Function
`const Pmp::ConnectionManager::``vftable'{for ``ObjectBase'}` | 14 | Exported Function
`private: void __thiscall Pmp::ConnectionManager::abort_TURN_configure(void)const ` | 17 | Exported Function
`protected: static struct _GMutex * Pmp::ConnectionManager::global_mutex` | 43 | Exported Function
`protected: static unsigned int Pmp::ConnectionManager::global_instance_use_count` | 42 | Exported Function
`private: void __thiscall Pmp::ConnectionManager::set_active_TURNserver(struct Pmp::TURNServer const &)` | 68 | Exported Function
`protected: static class RefPtr<class Pmp::ConnectionManager> Pmp::ConnectionManager::global_instance` | 41 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddingLocalMedialinesCompleted(int)` | 48 | Exported Function
`public: bool __thiscall RefPtr<class Pmp::ConnectionManager>::is_null(void)const ` | 59 | Exported Function
`public: bool __thiscall RefPtr<class Pmp::ConnectionManager>::operator<(class RefPtr<class Pmp::ConnectionManager> const &)const ` | 12 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_RemoveRemoteMedialine(int,int)` | 57 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::testbandwidth(void *,unsigned short,unsigned short,unsigned short,unsigned short,void (__cdecl*)(void *,unsigned short))` | 74 | Exported Function
`public: bool __thiscall RefPtr<class Pmp::ConnectionManager>::operator==(class RefPtr<class Pmp::ConnectionManager> const &)const ` | 9 | Exported Function
`public: class RefPtr<class Pmp::ConnectionManager> & __thiscall RefPtr<class Pmp::ConnectionManager>::operator=(class Pmp::ConnectionManager *)` | 8 | Exported Function
`public: class RefPtr<class Pmp::ConnectionManager> & __thiscall RefPtr<class Pmp::ConnectionManager>::operator=(class RefPtr<class Pmp::ConnectionManager> const &)` | 7 | Exported Function
`public: class Pmp::ConnectionManager & __thiscall RefPtr<class Pmp::ConnectionManager>::operator*(void)const ` | 11 | Exported Function
`public: class Pmp::ConnectionManager * __thiscall RefPtr<class Pmp::ConnectionManager>::operator->(void)const ` | 10 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddLocalMedialineAttributes(int,int,bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,bool,enum Pmp::ICE_TRANSPORT)` | 45 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddRemoteMedialine(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 46 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddingRemoteMedialinesCompleted(int)` | 49 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddLocalMedialine(int,int,bool,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,bool,enum Pmp::ICE_TRANSPORT)` | 44 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_AddRemoteMedialineAttribute(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 47 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_GetRemoteUfragPasswd(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 55 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_RemoveLocalMedialine(int,int)` | 56 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_GetConcludedCandidates(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)` | 52 | Exported Function
`public: bool __thiscall Pmp::ConnectionManager::ice_GetLocalCandidates(int,int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > &)` | 54 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `59C5C9F46EA82C4C743981566B64BD6C`
* Thumbprint: `475DAEE5A6CC149389EFDE176DEA526C627D203A`
* Issuer: CN=Symantec Class 3 SHA256 Code Signing CA - G2, OU=Symantec Trust Network, O=Symantec Corporation, C=US
* Subject: CN=Cisco Systems Inc., O=Cisco Systems Inc., L=San Jose, S=California, C=US

## File Metadata

* Original Filename: 
* Product Name: 
* Company Name: 
* File Version: 
* Product Version: 
* Language: 
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/68
* VirusTotal Link: https://www.virustotal.com/gui/file/bcdea44573e19e48af284371cfc88a38fd7243f891a3c617c5e0ce54468f0ed7/detection/




MIT License. Copyright (c) 2020 Strontic.


