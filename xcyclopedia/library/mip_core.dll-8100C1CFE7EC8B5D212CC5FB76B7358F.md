---
title: mip_core.dll | MIP SDK Core Library
excerpt: What is mip_core.dll?
---

# mip_core.dll 

* File Path: `C:\Program Files (x86)\Microsoft\Edge\Application\85.0.564.68\mip_core.dll`
* Description: MIP SDK Core Library

## Hashes

Type | Hash
-- | --
MD5 | `8100C1CFE7EC8B5D212CC5FB76B7358F`
SHA1 | `8D4EC68BDF08582553A3D9433534491BD6BF1402`
SHA256 | `CE735A1308512B796086F3451AC803146E25170E1DDDE8821CB938D2E2DF13D4`
SHA384 | `51CB891DB5CD55844AADF16386852DF89572FD66667B7D60965EEC3C0A5CEEA9103E4DAEACC4DBF194284AE5FE316D9A`
SHA512 | `F3E57A462A88F05BD11132C06A433330EE4A5D334140D8370DAC20961DC76F5EBB4C281DCF0D2ED99BC47E95DFF926B83D86F1CEB989B5E10E0C057A1397FFF7`
SSDEEP | `49152:EGtlqKCTXw1mVCAHd1WGz1fzGnPtTKw3Dc0jw5ReyBetP3O2yIU6ih3nuEUJpsNH:QnVJwdefG+NuEUJpU`
IMP | `3217B5574C7747537337420723A703E0`
PESHA1 | `6A170479A7B8FD5C79A5CE04933F68FC3220D5EA`
PE256 | `A50B1F8E789F97EE196B6FB0C9C6A38C7E4438C27568BC90F0B324ACC22640EC`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`MIP_CC_ProtectionDescriptor_GetReferrerSize` | 87 | Exported Function
`MIP_CC_ProtectionDescriptor_GetTemplateId` | 88 | Exported Function
`MIP_CC_ReleaseDictionary` | 89 | Exported Function
`MIP_CC_ProtectionDescriptor_GetOwnerSize` | 84 | Exported Function
`MIP_CC_ProtectionDescriptor_GetProtectionType` | 85 | Exported Function
`MIP_CC_ProtectionDescriptor_GetReferrer` | 86 | Exported Function
`MIP_CC_ReleaseHttpDelegate` | 90 | Exported Function
`MIP_CC_ReleaseStringList` | 94 | Exported Function
`MIP_CC_ReleaseTaskDispatcherDelegate` | 95 | Exported Function
`MIP_CC_ReleaseTelemetryConfiguration` | 96 | Exported Function
`MIP_CC_ReleaseLoggerDelegate` | 91 | Exported Function
`MIP_CC_ReleaseMipContext` | 92 | Exported Function
`MIP_CC_ReleaseProtectionDescriptor` | 93 | Exported Function
`MIP_CC_ProtectionDescriptor_GetOwner` | 83 | Exported Function
`MIP_CC_ProtectionDescriptor_DoesContentExpire` | 73 | Exported Function
`MIP_CC_ProtectionDescriptor_GetContentId` | 74 | Exported Function
`MIP_CC_ProtectionDescriptor_GetContentValidUntil` | 75 | Exported Function
`MIP_CC_ExecuteDispatchedTask` | 70 | Exported Function
`MIP_CC_NotifyHttpDelegateResponse` | 71 | Exported Function
`MIP_CC_ProtectionDescriptor_DoesAllowOfflineAccess` | 72 | Exported Function
`MIP_CC_ProtectionDescriptor_GetDescription` | 76 | Exported Function
`MIP_CC_ProtectionDescriptor_GetLabelId` | 80 | Exported Function
`MIP_CC_ProtectionDescriptor_GetName` | 81 | Exported Function
`MIP_CC_ProtectionDescriptor_GetNameSize` | 82 | Exported Function
`MIP_CC_ProtectionDescriptor_GetDescriptionSize` | 77 | Exported Function
`MIP_CC_ProtectionDescriptor_GetDoubleKeyUrl` | 78 | Exported Function
`MIP_CC_ProtectionDescriptor_GetDoubleKeyUrlSize` | 79 | Exported Function
`public: static class std::vector<unsigned char,class std::allocator<unsigned char> > const & __ptr64 __cdecl mipns::HttpClientCert::GetMsftCert(void)` | 48 | Exported Function
`unsigned __int64 __cdecl mipns::GetHashSize(enum mipns::CryptoHashAlgorithm)` | 45 | Exported Function
`void __cdecl mipns::ApplyGlobalTelemetryCustomSettings(class std::map<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const ,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > const & __ptr64)` | 1 | Exported Function
`public: static class std::shared_ptr<class mipns::MipContext> __cdecl mipns::MipContext::Create(struct mipns::ApplicationInfo const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::LogLevel,bool,class std::shared_ptr<class mipns::LoggerDelegate> const & __ptr64,class std::shared_ptr<struct mipns::TelemetryConfiguration> const & __ptr64)` | 5 | Exported Function
`public: static class std::shared_ptr<class mipns::MipContext> __cdecl mipns::MipContext::CreateWithCustomFeatureSettings(struct mipns::ApplicationInfo const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::LogLevel,bool,class std::shared_ptr<class mipns::LoggerDelegate> const & __ptr64,class std::shared_ptr<struct mipns::TelemetryConfiguration> const & __ptr64,class std::map<enum mipns::FlightingFeature,bool,struct std::less<enum mipns::FlightingFeature>,class std::allocator<struct std::pair<enum mipns::FlightingFeature const ,bool> > > const & __ptr64)` | 39 | Exported Function
`public: static class std::unique_ptr<class mipns::SymmetricCryptoWriter,struct std::default_delete<class mipns::SymmetricCryptoWriter> > __cdecl mipns::SymmetricCryptoWriter::CreateSymmetricCryptoWriter(unsigned char const * __ptr64,int,enum mipns::CryptoAlgorithm)` | 33 | Exported Function
`void __cdecl mipns::ApplyGlobalTelemetryMaskingFilter(class std::map<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > >,struct std::less<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > >,class std::allocator<struct std::pair<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const ,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > > > > const & __ptr64)` | 2 | Exported Function
`void __cdecl mipns::SetOneDSHttpDelegate(class std::shared_ptr<class mipns::HttpDelegate> const & __ptr64)` | 55 | Exported Function
`void __cdecl mipns::SetOneDSIsTls12Enforced(bool)` | 56 | Exported Function
`void __cdecl mipns::SetOneDSTaskDispatcherDelegate(class std::shared_ptr<class mipns::TaskDispatcherDelegate> const & __ptr64)` | 57 | Exported Function
`void __cdecl mipns::GenerateHash(enum mipns::CryptoHashAlgorithm,unsigned char const * __ptr64,unsigned int,unsigned char * __ptr64,unsigned int & __ptr64)` | 44 | Exported Function
`void __cdecl mipns::logger::SetLoggerDelegateInstance(class std::shared_ptr<class mipns::LoggerDelegate> const & __ptr64)` | 54 | Exported Function
`void __cdecl mipns::logger::SetLogLevel(enum mipns::LogLevel)` | 53 | Exported Function
`public: static class std::shared_ptr<class mipns::HttpClient> __cdecl mipns::HttpClient::Create(void)` | 4 | Exported Function
`MIP_CC_TelemetryConfiguration_SetHostName` | 100 | Exported Function
`MIP_CC_TelemetryConfiguration_SetHttpDelegate` | 101 | Exported Function
`MIP_CC_TelemetryConfiguration_SetIsFastShutdownEnabled` | 102 | Exported Function
`MIP_CC_StringList_GetStrings` | 97 | Exported Function
`MIP_CC_TelemetryConfiguration_AddMaskedProperty` | 98 | Exported Function
`MIP_CC_TelemetryConfiguration_SetCustomSettings` | 99 | Exported Function
`MIP_CC_TelemetryConfiguration_SetIsLocalCachingEnabled` | 103 | Exported Function
`MIP_CC_TelemetryConfiguration_SetLibraryName` | 107 | Exported Function
`MIP_CC_TelemetryConfiguration_SetTaskDispatcherDelegate` | 108 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64 __cdecl mipns::HttpClientCert::GetMsftCertPEM(void)` | 50 | Exported Function
`MIP_CC_TelemetryConfiguration_SetIsNetworkDetectionEnabled` | 104 | Exported Function
`MIP_CC_TelemetryConfiguration_SetIsTelemetryOptedOut` | 105 | Exported Function
`MIP_CC_TelemetryConfiguration_SetIsTraceLoggingEnabled` | 106 | Exported Function
`class std::shared_ptr<class mipns::HttpRequestBase> __cdecl mipns::CreateHttpRequest(class mipns::HttpRequestBase const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 25 | Exported Function
`class std::shared_ptr<class mipns::HttpRequestBase> __cdecl mipns::CreateHttpRequest(enum mipns::TransportLayerSecurityMinimumVersion,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::HttpRequestType,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 26 | Exported Function
`class std::shared_ptr<class mipns::LoggerDelegate> __cdecl mipns::logger::CreateDefaultLoggerDelegate(void)` | 12 | Exported Function
`class std::shared_ptr<class mipns::EventProperty> __cdecl mipns::CreateEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::Pii)` | 20 | Exported Function
`class std::shared_ptr<class mipns::EventProperty> __cdecl mipns::CreateEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,double,enum mipns::Pii)` | 21 | Exported Function
`class std::shared_ptr<class mipns::HttpDirector> __cdecl mipns::CreateHttpDirector(class std::shared_ptr<class mipns::MipContext> const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class mipns::Identity const & __ptr64,class std::shared_ptr<class mipns::HttpDelegate> const & __ptr64,class std::shared_ptr<class mipns::HttpProvider> const & __ptr64,class std::shared_ptr<class mipns::TelemetryContext> const & __ptr64)` | 24 | Exported Function
`class std::shared_ptr<class mipns::RequestTransformer> __cdecl mipns::CreateAuthRequestTransformer(class std::shared_ptr<class mipns::MipContext> const & __ptr64,class mipns::Identity const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::shared_ptr<class mipns::AuthDelegate> const & __ptr64,class std::shared_ptr<class mipns::AuthChallengeProvider> const & __ptr64,class std::shared_ptr<class mipns::HttpProvider> const & __ptr64)` | 8 | Exported Function
`class std::shared_ptr<class mipns::Stream> __cdecl mipns::CreateStreamFromStdStream(class std::shared_ptr<class std::basic_istream<char,struct std::char_traits<char> > > const & __ptr64)` | 31 | Exported Function
`class std::shared_ptr<class mipns::Stream> __cdecl mipns::CreateStreamFromStdStream(class std::shared_ptr<class std::basic_ostream<char,struct std::char_traits<char> > > const & __ptr64)` | 32 | Exported Function
`class std::shared_ptr<class mipns::TelemetryContext> __cdecl mipns::CreateTelemetryContext(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::shared_ptr<class mipns::TelemetryContext> const & __ptr64)` | 34 | Exported Function
`class std::shared_ptr<class mipns::RequestTransformer> __cdecl mipns::CreateRedirectRequestTransformer(class std::shared_ptr<class mipns::MipContext> const & __ptr64,class mipns::Identity const & __ptr64,class std::shared_ptr<class mipns::RedirectProvider> const & __ptr64,class std::shared_ptr<class mipns::HttpProvider> const & __ptr64)` | 28 | Exported Function
`class std::shared_ptr<class mipns::Stream> __cdecl mipns::CreateStreamFromBuffer(unsigned char * __ptr64,__int64)` | 29 | Exported Function
`class std::shared_ptr<class mipns::Stream> __cdecl mipns::CreateStreamFromStdStream(class std::shared_ptr<class std::basic_iostream<char,struct std::char_traits<char> > > const & __ptr64)` | 30 | Exported Function
`class std::shared_ptr<class mipns::EventProperty> __cdecl mipns::CreateEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,bool)` | 23 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl mipns::GenerateAESKey(void)` | 42 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl mipns::GetSanitizedUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 52 | Exported Function
`class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64 __cdecl mipns::GetMsftCertPEM(void)` | 51 | Exported Function
`__int64 __cdecl mipns::bufferprotector::DecryptBuffer(enum mipns::CipherMode,class mipns::CryptoKey const & __ptr64,__int64,unsigned char const * __ptr64,__int64,unsigned char * __ptr64,__int64,bool)` | 40 | Exported Function
`__int64 __cdecl mipns::bufferprotector::EncryptBuffer(enum mipns::CipherMode,class mipns::CryptoKey const & __ptr64,__int64,unsigned char const * __ptr64,__int64,unsigned char * __ptr64,__int64,bool)` | 41 | Exported Function
`class mipns::LoggerDelegate & __ptr64 __cdecl mipns::logger::GetLoggerDelegateInstance(void)` | 47 | Exported Function
`class std::shared_ptr<class mipns::AsymmetricCryptoProvider> __cdecl mipns::CreateAsymmetricCryptoProvider(enum mipns::CryptoAlgorithm,class std::vector<unsigned char,class std::allocator<unsigned char> > const & __ptr64,unsigned int)` | 6 | Exported Function
`class std::shared_ptr<class mipns::Event> __cdecl mipns::CreateTelemetryEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::EventLevel,enum mipns::EventPipeline)` | 35 | Exported Function
`class std::shared_ptr<class mipns::EventProperty> __cdecl mipns::CreateAuditOnlyEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 7 | Exported Function
`class std::shared_ptr<class mipns::EventProperty> __cdecl mipns::CreateEventProperty(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,__int64,enum mipns::Pii)` | 22 | Exported Function
`class std::shared_ptr<class mipns::CryptoProvider> __cdecl mipns::CreateCryptoProvider(enum mipns::CipherMode,class mipns::CryptoKey const & __ptr64)` | 11 | Exported Function
`class std::shared_ptr<class mipns::Domain> __cdecl mipns::CreateDomainFromEmail(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 14 | Exported Function
`class std::shared_ptr<class mipns::Domain> __cdecl mipns::CreateDomainFromUrl(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 15 | Exported Function
`MIP_CC_CreateLoggerDelegate` | 60 | Exported Function
`MIP_CC_CreateMipContext` | 61 | Exported Function
`MIP_CC_CreateMipContextWithCustomFeatureSettings` | 62 | Exported Function
`enum mipns::LogLevel __cdecl mipns::logger::GetLogLevel(void)` | 46 | Exported Function
`MIP_CC_CreateDictionary` | 58 | Exported Function
`MIP_CC_CreateHttpDelegate` | 59 | Exported Function
`MIP_CC_CreateProtectionDescriptorFromTemplate` | 63 | Exported Function
`MIP_CC_CreateTaskDispatcherDelegate` | 67 | Exported Function
`MIP_CC_CreateTelemetryConfiguration` | 68 | Exported Function
`MIP_CC_Dictionary_GetEntries` | 69 | Exported Function
`MIP_CC_CreateProtectionDescriptorFromUserRights` | 64 | Exported Function
`MIP_CC_CreateProtectionDescriptorFromUserRoles` | 65 | Exported Function
`MIP_CC_CreateStringList` | 66 | Exported Function
`class std::vector<unsigned char,class std::allocator<unsigned char> > const & __ptr64 __cdecl mipns::GetMsftCert(void)` | 49 | Exported Function
`class std::shared_ptr<class mipns::TelemetrySchemaValidator> __cdecl mipns::CreateTelemetrySchemaValidator(bool)` | 37 | Exported Function
`class std::unique_ptr<class mipns::AutoEvent,struct std::default_delete<class mipns::AutoEvent> > __cdecl mipns::CreateAutoEvent(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,enum mipns::EventLevel,enum mipns::EventPipeline,class std::shared_ptr<class mipns::TelemetryContext> const & __ptr64,class std::shared_ptr<class mipns::TelemetryManager> const & __ptr64)` | 9 | Exported Function
`class std::unique_ptr<class mipns::AutoEvent,struct std::default_delete<class mipns::AutoEvent> > __cdecl mipns::CreateAutoEvent(class std::shared_ptr<class mipns::Event> const & __ptr64,class std::shared_ptr<class mipns::TelemetryContext> const & __ptr64,class std::shared_ptr<class mipns::TelemetryManager> const & __ptr64)` | 10 | Exported Function
`class std::shared_ptr<class mipns::TelemetryDelegate> __cdecl mipns::CreateDefaultTelemetryDelegate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,struct mipns::TelemetryConfiguration const & __ptr64)` | 13 | Exported Function
`class std::shared_ptr<class mipns::TelemetryDelegate> __cdecl mipns::CreateEmptyTelemetryDelegate(void)` | 16 | Exported Function
`class std::shared_ptr<class mipns::TelemetryManager> __cdecl mipns::CreateTelemetryManager(class std::shared_ptr<class mipns::TelemetryDelegate> const & __ptr64,enum mipns::EventLevel,struct mipns::TelemetryConfiguration const & __ptr64)` | 36 | Exported Function
`class std::unique_ptr<class mipns::PersistentStore,struct std::default_delete<class mipns::PersistentStore> > __cdecl mipns::CreatePersistentStore(class std::shared_ptr<class mipns::MipContext> const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const & __ptr64,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const & __ptr64,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class ` | 27 | Exported Function
`class std::vector<class std::shared_ptr<class mipns::EventProperty>,class std::allocator<class std::shared_ptr<class mipns::EventProperty> > > __cdecl mipns::CreateEventFailureProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,int,class std::exception_ptr const & __ptr64)` | 19 | Exported Function
`class std::vector<unsigned char,class std::allocator<unsigned char> > __cdecl mipns::CrackBlock(unsigned char const * __ptr64,unsigned int,unsigned int,unsigned char const * __ptr64,unsigned int,unsigned char const * __ptr64,unsigned int,enum mipns::RSAPadding,enum mipns::CryptoHashAlgorithm)` | 3 | Exported Function
`class std::vector<unsigned char,class std::allocator<unsigned char> > __cdecl mipns::GenerateAESKeyAsBytes(unsigned int)` | 43 | Exported Function
`class std::unique_ptr<class mipns::Uri,struct std::default_delete<class mipns::Uri> > __cdecl mipns::CreateUri(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64)` | 38 | Exported Function
`class std::vector<class std::shared_ptr<class mipns::EventProperty>,class std::allocator<class std::shared_ptr<class mipns::EventProperty> > > __cdecl mipns::CreateEventFailureProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,int)` | 17 | Exported Function
`class std::vector<class std::shared_ptr<class mipns::EventProperty>,class std::allocator<class std::shared_ptr<class mipns::EventProperty> > > __cdecl mipns::CreateEventFailureProperties(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const & __ptr64,int,class mipns::Error const & __ptr64)` | 18 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000001519E8D8F4071A30E41000000000151`
* Thumbprint: `62009AAABDAE749FD47D19150958329BF6FF4B34`
* Issuer: CN=Microsoft Code Signing PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: mip_core.dll
* Product Name: MIP SDK
* Company Name: Microsoft Corporation
* File Version: 1.6.103
* Product Version: 1.6.103
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/ce735a1308512b796086f3451ac803146e25170e1ddde8821cb938d2e2df13d4/detection/




MIT License. Copyright (c) 2020 Strontic.


