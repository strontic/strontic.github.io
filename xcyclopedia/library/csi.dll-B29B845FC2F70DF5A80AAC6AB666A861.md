---
title: csi.dll | Microsoft Office Document Cache
excerpt: What is csi.dll?
---

# csi.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\csi.dll`
* Description: Microsoft Office Document Cache

## Hashes

Type | Hash
-- | --
MD5 | `B29B845FC2F70DF5A80AAC6AB666A861`
SHA1 | `90D6F2406938AFDE13859D2E1D474F9D2389197F`
SHA256 | `529307EC18B82F7FA6D86F0E246888A0D93378C6F6896E280A0354547A1B9C57`
SHA384 | `D5C96047625E5ABBFAF6A4396810299097EADA9EFB8C6BF55FB749F3B77227257843227EFF0F61F0B4BDFAC144919A38`
SHA512 | `2F98A7CE265DB87327220448D2D4B7355110852AB5EF2D3A431FDA93E11AE44BA7814DBAA35049066E6AD6CBBC40E70A6D620F72BDEA66810F824ABEABFD6B86`
SSDEEP | `98304:IT/rMR6XRGzXkhbqpWPBZq0D7FxgmyRnmBA86ZAFWejVusEU0m1/tsKr5HccI7eW:6TMoXnbqsPBnPUmORKFWejVu4XpVc3Si`
IMP | `3CCF879FB5FD888C8C3CE6F5D7448D70`
PESHA1 | `D015BC0F47EB5F6490AAB45D36B10DDD7B11BA79`
PE256 | `FE7B987A5D569C4439984FD3F156EAC99FA4B49B4F3951ACAEA7425B5148C380`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`void __stdcall Csi::CreateCellStorageOverHttp(wchar_t const *,struct CsiCell::ICellStorage * *,struct _GUID const &,struct Csi::IWebServiceSubRequestUserManager *,struct Csi::IWebServiceRequest *,wchar_t const *,bool)` | 55 | Exported Function
`void __stdcall Csi::CreateCellStorageRequest(class Csi::CCellStorageRequestProcessor *,struct CsiCell::IDataElementWriteStream *,struct CsiCell::ICellStorageRequest * *)` | 56 | Exported Function
`void __stdcall Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IFileProxy *,struct Csi::IChangeCountNotify *,bool,bool,bool,struct CsiCell::ICellStorageCollection * *)` | 54 | Exported Function
`void __stdcall Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IByteStorage *,struct Csi::IChangeCountNotify *,bool,bool,struct CsiCell::ICellStorageCollection * *)` | 52 | Exported Function
`void __stdcall Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IFileProxy *,struct Csi::IChangeCountNotify *,bool,bool,bool,struct CsiCell::ICellStorage * *)` | 53 | Exported Function
`void __stdcall Csi::CreateKnowledge(struct Csi::IKnowledge * *)` | 67 | Exported Function
`void __stdcall Csi::CreateNewStorageIndexScaffold(class Csi::CStorageIndexScaffold * *)` | 73 | Exported Function
`void __stdcall Csi::CreateGenericFda(struct Csi::IFileDataAdapter * *)` | 65 | Exported Function
`void __stdcall Csi::CreateCsiDllPropertySet(struct Csi::ICsiDllPropertySet * *)` | 57 | Exported Function
`void __stdcall Csi::CreateDataElementPackage(class Csi::CDataElementPackage * *)` | 58 | Exported Function
`void __stdcall Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IByteStorage *,struct Csi::IChangeCountNotify *,bool,bool,struct CsiCell::ICellStorage * *)` | 51 | Exported Function
`void __stdcall Csi::CopyFileToFileBranchImpl(struct Csi::IFileProxy *,struct Csi::IByteStorage *,struct Csi::IStorageLock *,struct _GUID const &,struct Csi::IFileBranch *,struct MsoCF::ExtendedGUID const &)` | 43 | Exported Function
`void __stdcall Csi::CopyFileToStream(struct Csi::IFileProxy *,struct IStream *)` | 44 | Exported Function
`void __stdcall Csi::CopyFileToFileBranch(struct Csi::IFileProxy *,struct _GUID const &,struct Csi::IFileBranch *,struct MsoCF::ExtendedGUID const &)` | 42 | Exported Function
`void __stdcall Csi::CopyFileBranchToStream(struct Csi::IFileBranch *,struct _GUID const &,struct Csi::ISequentialWriteStream *,unsigned __int64,struct MsoCF::ExtendedGUID const &)` | 40 | Exported Function
`void __stdcall Csi::CopyFileBranchToTempFile(wchar_t const *,wchar_t const *,struct Csi::IFileBranch *)` | 41 | Exported Function
`void __stdcall Csi::CreateCellBinaryRequestProxy(struct CsiCell::ICellStorageBinary *,struct CsiCell::ICellStorage * *)` | 49 | Exported Function
`void __stdcall Csi::CreateCellManifestScaffold(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,class Csi::CCellManifestScaffold * *)` | 50 | Exported Function
`void __stdcall Csi::CopyTempFileToFileBranch(struct Csi::IFileBranch *,wchar_t const *,wchar_t const *)` | 47 | Exported Function
`void __stdcall Csi::CopyStreamToFile(struct IStream *,struct Csi::IFileProxy *)` | 45 | Exported Function
`void __stdcall Csi::CopyStreamToFileBranch(struct Csi::IReadStream *,struct _GUID const &,struct Csi::IFileBranch *,unsigned __int64,struct MsoCF::ExtendedGUID const &,bool)` | 46 | Exported Function
`void __stdcall Csi::CreateNoChangeCellStorage(struct CsiCell::ICellStorage * *)` | 74 | Exported Function
`void __stdcall Csi::EnableServerReachabilityAutoDiscovery(void)` | 102 | Exported Function
`void __stdcall Csi::EndEnsureCsiUninitialized(int)` | 103 | Exported Function
`void __stdcall Csi::DeserializeKnowledge(class Csi::CStreamObjectParser &,struct Csi::IKnowledge * *)` | 101 | Exported Function
`void __stdcall Csi::CsiAtomFromMsoCfAtom(class MsoCF::IAtom *,struct Csi::ICsiAtom * *)` | 95 | Exported Function
`void __stdcall Csi::CsiClientWriteToLog(unsigned int,enum Csi::CsiLoggingLevel,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 97 | Exported Function
`void __stdcall Csi::EnsureCellKnowledge(struct Csi::IKnowledge *,struct CsiCell::ICellKnowledge * *)` | 107 | Exported Function
`void __stdcall Csi::EnsureCsiUninitialized(int)` | 108 | Exported Function
`void __stdcall Csi::EndShutdownOfficeFileCache2(void)` | 106 | Exported Function
`void __stdcall Csi::EndFinishCsiClientDll(bool)` | 104 | Exported Function
`void __stdcall Csi::EndFinishCsiClientLib(void)` | 105 | Exported Function
`void __stdcall Csi::CreateTemporaryFile(struct Csi::IFileProxy * *,wchar_t const *)` | 91 | Exported Function
`void __stdcall Csi::CreateReadStreamOnByteStorage(struct Csi::IByteStorage *,bool,struct Csi::FileChunkReference64 const &,struct Csi::IStorageLock *,struct Csi::IReadStream * *)` | 82 | Exported Function
`void __stdcall Csi::CreateRevisionManifestScaffold(struct MsoCF::ExtendedGUID const &,struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,class Csi::CRevisionManifestScaffold * *)` | 83 | Exported Function
`void __stdcall Csi::CreateOfficeFileCacheUrl(struct Csi::IOfficeFileCache2 *,struct Csi::IOfficeFileCacheUrl * *)` | 77 | Exported Function
`void __stdcall Csi::CreateObjectDataBlob(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,unsigned __int64,class MsoCF::IAtom *,struct Csi::IReadStream *,unsigned __int64,struct CsiCell::IObjectDataBlob * *)` | 75 | Exported Function
`void __stdcall Csi::CreateObjectGroupScaffold(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,class Csi::CObjectGroupScaffold * *)` | 76 | Exported Function
`void __stdcall Csi::CreateStorageIndexScaffold(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,class Csi::CStorageIndexScaffold * *)` | 89 | Exported Function
`void __stdcall Csi::CreateStorageManifestScaffold(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &,class Csi::CStorageManifestScaffold * *)` | 90 | Exported Function
`void __stdcall Csi::CreateServerPropertySetForUpload(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,struct MsoCF::IPropertySet * *)` | 87 | Exported Function
`void __stdcall Csi::CreateServerAccessOnWebService(wchar_t const *,struct Csi::IServerAccess * *,wchar_t const *)` | 84 | Exported Function
`void __stdcall Csi::CreateServerAccessOverHttp(wchar_t const *,struct Csi::IServerAccess * *,struct _GUID const &,wchar_t const *)` | 85 | Exported Function
`void __stdcall Csi::CopyFileBranchToFileImpl(struct Csi::IFileBranch *,struct Csi::IByteStorage *,struct _GUID const &,struct Csi::IFileProxy *,struct MsoCF::ExtendedGUID const &)` | 39 | Exported Function
`unsigned int __stdcall Csi::RandomNumber(unsigned int,unsigned int,bool)` | 290 | Exported Function
`unsigned long __stdcall Csi::GetCsiCapabilities(class MsoCF::String<struct MsoCF::WzTraits>,unsigned long)` | 149 | Exported Function
`unsigned int __stdcall Csi::MapSubRequestToCellStorageRequest(class Csi::CSubRequest *,struct CsiCell::ICellStorageRequest *)` | 286 | Exported Function
`unsigned char __stdcall Csi::Configuration::GetUnsignedInteger8(enum Csi::Configuration::ConfigurationId)` | 229 | Exported Function
`unsigned int __stdcall Csi::Configuration::GetUnsignedInteger32(enum Csi::Configuration::ConfigurationId)` | 227 | Exported Function
`void __stdcall Csi::AddSerialNumber(struct CsiCell::ICellKnowledge *,struct CsiCell::SerialNumber const &,struct MsoCF::ExtendedGUID const &)` | 17 | Exported Function
`void __stdcall Csi::AppendStringToNameOfFilename(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &)` | 19 | Exported Function
`unsigned short __stdcall Csi::GetCobaltResponseVersion(void)` | 142 | Exported Function
`unsigned short __stdcall Csi::Configuration::GetUnsignedInteger16(enum Csi::Configuration::ConfigurationId)` | 226 | Exported Function
`unsigned short __stdcall Csi::GetCobaltRequestVersion(void)` | 141 | Exported Function
`unsigned __int64 __stdcall Csi::Configuration::GetUnsignedInteger64(enum Csi::Configuration::ConfigurationId)` | 228 | Exported Function
`public: void __thiscall Csi::CStorageIndexScaffold::AddStorageManifestMapping(struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &)` | 18 | Exported Function
`public: void __thiscall Csi::CStorageManifestScaffold::AddRootContextAndCellID(struct CsiCell::RootContextAndCellID const &)` | 15 | Exported Function
`public: void __thiscall Csi::CStorageIndexScaffold::AddRevisionToRevisionManifestMapping(struct MsoCF::ExtendedGUID const &,struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &)` | 14 | Exported Function
`public: void __thiscall Csi::CRevisionManifestScaffold::AddRootObjectDeclaration(struct MsoCF::ExtendedGUID const &,struct MsoCF::ExtendedGUID const &)` | 16 | Exported Function
`public: void __thiscall Csi::CStorageIndexScaffold::AddCellToCellManifestMapping(struct CsiCell::ContextAndCellID const &,struct MsoCF::ExtendedGUID const &,struct CsiCell::SerialNumber const &)` | 10 | Exported Function
`struct Csi::MapPathsResult __stdcall Csi::FMapPaths(wchar_t *,int,wchar_t *,int,wchar_t const *,bool,bool,bool)` | 123 | Exported Function
`struct MsoCF::IError * __stdcall Csi::Errors::UseIError(class MsoCF::CErrorException const &)` | 339 | Exported Function
`signed char __stdcall Csi::Configuration::GetSignedInteger8(enum Csi::Configuration::ConfigurationId)` | 217 | Exported Function
`public: void __thiscall Csi::CStorageManifestScaffold::SetSchemaID(struct _GUID const &)` | 317 | Exported Function
`short __stdcall Csi::Configuration::GetSignedInteger16(enum Csi::Configuration::ConfigurationId)` | 214 | Exported Function
`void __stdcall Csi::BeginEnsureCsiUninitialized(int)` | 25 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned int)` | 308 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned short)` | 306 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned char)` | 304 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,struct IUnknown *)` | 309 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned __int64)` | 311 | Exported Function
`void __stdcall Csi::ConvertStream(struct Csi::ISizeableWriteStream *,struct _GUID const &,void * *)` | 37 | Exported Function
`void __stdcall Csi::CopyFileBranchToFile(struct Csi::IFileBranch *,struct _GUID const &,struct Csi::IFileProxy *,struct MsoCF::ExtendedGUID const &)` | 38 | Exported Function
`void __stdcall Csi::ConvertStream(struct Csi::IReadStream *,struct _GUID const &,void * *)` | 36 | Exported Function
`void __stdcall Csi::ConvertStorageService(struct _GUID const &,struct _GUID const &,struct IUnknown *,struct _GUID const &,struct _GUID const &,struct _GUID const &,void * *)` | 34 | Exported Function
`void __stdcall Csi::ConvertStream(struct Csi::IFixedWriteStream *,struct _GUID const &,void * *)` | 35 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,signed char)` | 303 | Exported Function
`void __stdcall Csi::CellStorageXML::WriteRequestResponse(struct Csi::CellStorageXML::AWriteSite *,class MsoCF::String<struct MsoCF::WzTraits>,bool,bool,class MsoCF::CMap<class Csi::CSubRequest *,unsigned int> const &,struct CsiCell::IDataElementPackage *,struct CsiCell::IDataElementPackage *)` | 346 | Exported Function
`void __stdcall Csi::Configuration::Reset(enum Csi::Configuration::ConfigurationId)` | 298 | Exported Function
`void __stdcall Csi::BeginShutdownOfficeFileCache2(void)` | 28 | Exported Function
`void __stdcall Csi::BeginFinishCsiClientDll(bool)` | 26 | Exported Function
`void __stdcall Csi::BeginFinishCsiClientLib(void)` | 27 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,int)` | 307 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,short)` | 305 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 302 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,__int64)` | 310 | Exported Function
`void __stdcall Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,bool)` | 312 | Exported Function
`void __stdcall Csi::FinishCsiClientDll(bool)` | 130 | Exported Function
`void __stdcall Csi::GetWriteStreamOnComStream(struct IStream *,struct Csi::FileChunkReference64 const &,struct Csi::IFixedWriteStream * *)` | 233 | Exported Function
`void __stdcall Csi::GetWriteStreamOnComStream(struct IStream *,unsigned int,struct Csi::IFixedWriteStream * *)` | 234 | Exported Function
`void __stdcall Csi::GetTemporaryFolder(struct Csi::IFolderProxy * *)` | 224 | Exported Function
`void __stdcall Csi::GetSizeableWriteStreamOnMemory(struct Csi::ISizeableWriteStream * *,unsigned char const *,unsigned int,unsigned int,bool,bool)` | 221 | Exported Function
`void __stdcall Csi::GetSizeableWriteStreamWithUnk(struct Csi::ISizeableWriteStream *,struct IUnknown *,struct Csi::ISizeableWriteStream * *)` | 222 | Exported Function
`void __stdcall Csi::GetWriteStreamOnMemory(struct Csi::IFixedWriteStream * *,unsigned char const *,unsigned int,bool,bool)` | 238 | Exported Function
`void __stdcall Csi::GetWriteStreamOnStreamOffset(struct Csi::IFixedWriteStream *,unsigned __int64,struct Csi::IFixedWriteStream * *)` | 239 | Exported Function
`void __stdcall Csi::GetWriteStreamOnMemory(struct Csi::IFixedWriteStream * *,struct Csi::IReadStream *)` | 237 | Exported Function
`void __stdcall Csi::GetWriteStreamOnExistingAlloc(unsigned char *,unsigned int,struct Csi::IFixedWriteStream * *,struct IUnknown *)` | 235 | Exported Function
`void __stdcall Csi::GetWriteStreamOnLockBytes(struct ILockBytes *,struct Csi::IFixedWriteStream * *)` | 236 | Exported Function
`void __stdcall Csi::GetSizeableWriteStreamOnMemory(struct Csi::ISizeableWriteStream * *,struct Csi::IReadStream *,unsigned int,bool,bool)` | 220 | Exported Function
`void __stdcall Csi::GetSequentialWriteStreamOnComStream(struct ISequentialStream *,struct Csi::ISequentialWriteStream * *)` | 208 | Exported Function
`void __stdcall Csi::GetSequentialWriteStreamOnComStream(struct IStream *,struct Csi::ISequentialWriteStream * *,unsigned __int64)` | 209 | Exported Function
`void __stdcall Csi::GetSequentialReadStreamOnStream(struct Csi::IReadStream *,struct Csi::ISequentialReadStream * *,unsigned __int64)` | 207 | Exported Function
`void __stdcall Csi::GetSequentialReadStreamOnSequentialComStream(struct ISequentialStream *,struct Csi::ISequentialReadStream * *)` | 205 | Exported Function
`void __stdcall Csi::GetSequentialReadStreamOnSimple(struct Csi::ISequentialReadStreamSimple *,struct Csi::ISequentialReadStream * *)` | 206 | Exported Function
`void __stdcall Csi::GetSizeableWriteStreamOnComStream(struct IStream *,struct Csi::ISizeableWriteStream * *)` | 218 | Exported Function
`void __stdcall Csi::GetSizeableWriteStreamOnLockBytes(struct ILockBytes *,struct Csi::ISizeableWriteStream * *)` | 219 | Exported Function
`void __stdcall Csi::GetSequentialWriteStreamOnStream(struct Csi::ISizeableWriteStream *,struct Csi::ISequentialWriteStream * *,unsigned __int64)` | 212 | Exported Function
`void __stdcall Csi::GetSequentialWriteStreamOnSimple(struct Csi::ISequentialWriteStreamSimple *,struct Csi::ISequentialWriteStream * *)` | 210 | Exported Function
`void __stdcall Csi::GetSequentialWriteStreamOnStream(struct Csi::IFixedWriteStream *,struct Csi::ISequentialWriteStream * *,unsigned __int64)` | 211 | Exported Function
`void __stdcall Csi::GetWriteStreamOnStreamSubset(struct Csi::IFixedWriteStream *,struct Csi::FileChunkReference64 const &,struct Csi::IFixedWriteStream * *)` | 240 | Exported Function
`void __stdcall Csi::Sync::TryCancelRequest(struct MsoCF::Async::IAsyncResult *,unsigned long)` | 327 | Exported Function
`void __stdcall Csi::Sync::WaitIfWaiting(struct MsoCF::Async::IAsyncResult *,void *)` | 343 | Exported Function
`void __stdcall Csi::StartCsiLogging(void)` | 322 | Exported Function
`void __stdcall Csi::StartCsiClientDll(enum Csi::CsiApplicationEnum,wchar_t const *,bool)` | 320 | Exported Function
`void __stdcall Csi::StartCsiClientLib(enum Csi::CsiApplicationEnum)` | 321 | Exported Function
`void __stdcall Csi::WriteToLog_Impl(unsigned long,unsigned int,enum Csi::CsiLoggingLevel,struct _GUID const &,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 347 | Exported Function
`wchar_t const * __stdcall Csi::GetUsernameFromServerLockOwner(wchar_t const *)` | 230 | Exported Function
`void __stdcall Csi::UninitCsiDavCache(void)` | 332 | Exported Function
`void __stdcall Csi::TEMPORARY_CopyStateSignatureToMemory(struct Csi::IReadStream *,unsigned char *,unsigned long)` | 325 | Exported Function
`void __stdcall Csi::TestApi_CreateStreamOnFileBranch(struct Csi::IFileBranch *,enum Csi::FilePartitionType,enum Csi::FileBranchType,bool,struct IStream * *,bool,bool)` | 326 | Exported Function
`void __stdcall Csi::ShutdownOfficeFileCache2(void)` | 318 | Exported Function
`void __stdcall Csi::LoadKnowledgeFromProperty(struct MsoCF::IPropertySet *,unsigned int,struct Csi::IKnowledge * *)` | 284 | Exported Function
`void __stdcall Csi::MapCellStorageResponseToSubRequest(struct CsiCell::ICellStorageResponse *,unsigned int,class Csi::CSubRequest *)` | 285 | Exported Function
`void __stdcall Csi::InitCsiDavCache(void)` | 247 | Exported Function
`void __stdcall Csi::GetWriteStreamWithUnk(struct Csi::IFixedWriteStream *,struct IUnknown *,struct Csi::IFixedWriteStream * *)` | 241 | Exported Function
`void __stdcall Csi::GrooveSetURLReachable(wchar_t const *,unsigned long)` | 242 | Exported Function
`void __stdcall Csi::SaveKnowledgeToProperty(struct Csi::IKnowledge *,struct MsoCF::IPropertySet *,unsigned int)` | 300 | Exported Function
`void __stdcall Csi::SerializeDataElementPackage(struct CsiCell::IDataElementPackage *,struct Csi::ISequentialWriteStream *,unsigned short,bool)` | 301 | Exported Function
`void __stdcall Csi::RegisterPrefetchFileProvider(class Mso::TCntPtr<struct Csi::ISupportPrefetchFile> const &)` | 297 | Exported Function
`void __stdcall Csi::OnUserCredentialChange(wchar_t const *)` | 288 | Exported Function
`void __stdcall Csi::PickupCreds(void)` | 289 | Exported Function
`void __stdcall Csi::GetSequentialReadStreamOnComStream(struct IStream *,struct Csi::ISequentialReadStream * *,unsigned __int64)` | 204 | Exported Function
`void __stdcall Csi::GetEnumServerTargetIDTestOnly(struct Csi::IOfficeFileCache2 const *,struct Csi::IEnumServerTargetIDTestOnly * *)` | 160 | Exported Function
`void __stdcall Csi::GetErrorReadStream(struct MsoCF::IError *,struct Csi::IReadStream * *)` | 162 | Exported Function
`void __stdcall Csi::GetEmptyReadStream(struct Csi::IReadStream * *)` | 159 | Exported Function
`void __stdcall Csi::GetCsiErrorFromDavError(struct Csi::ICsiError * *,struct Csi::ICsiDavError *,bool)` | 151 | Exported Function
`void __stdcall Csi::GetCsiErrorFromDavError(struct MsoCF::IError * *,struct Csi::ICsiDavError *,bool)` | 152 | Exported Function
`void __stdcall Csi::GetFileProxyFromPath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFileProxy * *,bool,bool *,bool)` | 167 | Exported Function
`void __stdcall Csi::GetFileProxyFromRelativeOrAbsolutePath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy *,struct Csi::IFileProxy * *)` | 168 | Exported Function
`void __stdcall Csi::GetFilePropertiesFromFileStoreFile(struct Csi::IFileStoreFile *,struct Csi::IFileProperties_DEPRECATE * *)` | 166 | Exported Function
`void __stdcall Csi::GetErrorSizeableWriteStream(struct MsoCF::IError *,struct Csi::ISizeableWriteStream * *)` | 163 | Exported Function
`void __stdcall Csi::GetFileOrFolderProxyFromPathAndLeaf(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFileProxy * *)` | 165 | Exported Function
`void __stdcall Csi::GetCsiDavClient(struct IMsoUrl *,struct Csi::ICsiDavClient * *)` | 150 | Exported Function
`void __stdcall Csi::GetCellStorageMultiRoundTrip(struct CsiCell::ICellStorage *,struct CsiCell::IMultiRoundTripSuspend *,struct CsiCell::ICellStorage * *)` | 139 | Exported Function
`void __stdcall Csi::GetComStreamOnLockBytes(struct ILockBytes *,struct IStream * *,unsigned __int64,struct IUnknown *)` | 143 | Exported Function
`void __stdcall Csi::GetAggregatedReadStream(class Ofc::TCntPtrList<struct Csi::IReadStream> const &,struct Csi::IReadStream * *)` | 135 | Exported Function
`void __stdcall Csi::FinishCsiClientLib(void)` | 131 | Exported Function
`void __stdcall Csi::FinishCsiLogging(void)` | 132 | Exported Function
`void __stdcall Csi::GetComStreamOnSizeableWriteStream(struct Csi::ISizeableWriteStream *,struct IStream * *,unsigned __int64)` | 147 | Exported Function
`void __stdcall Csi::GetComStreamOnWriteStream(struct Csi::IFixedWriteStream *,struct IStream * *,unsigned __int64,struct IUnknown *)` | 148 | Exported Function
`void __stdcall Csi::GetComStreamOnSequentialWriteStream(struct Csi::ISequentialWriteStream *,struct IStream * *)` | 146 | Exported Function
`void __stdcall Csi::GetComStreamOnReadStream(struct Csi::IReadStream *,struct IStream * *,unsigned __int64,struct IUnknown *)` | 144 | Exported Function
`void __stdcall Csi::GetComStreamOnSequentialReadStream(struct Csi::ISequentialReadStream *,struct IStream * *)` | 145 | Exported Function
`void __stdcall Csi::GetFolderProxyFromPath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy * *,bool,bool *,bool)` | 169 | Exported Function
`void __stdcall Csi::GetReadStreamOnLockBytes(struct ILockBytes *,struct Csi::IReadStream * *)` | 195 | Exported Function
`void __stdcall Csi::GetReadStreamOnMemory(struct Csi::IReadStream * *,struct Csi::IReadStream *)` | 196 | Exported Function
`void __stdcall Csi::GetReadStreamOnExistingAlloc(unsigned char const *,unsigned int,struct Csi::IReadStream * *,struct IUnknown *)` | 194 | Exported Function
`void __stdcall Csi::GetReadStreamOnComStream(struct IStream *,struct Csi::FileChunkReference64 const &,struct Csi::IReadStream * *,unsigned int,bool)` | 192 | Exported Function
`void __stdcall Csi::GetReadStreamOnComStream(struct IStream *,unsigned int,struct Csi::IReadStream * *,unsigned int,bool)` | 193 | Exported Function
`void __stdcall Csi::GetReadStreamOnStreamSubset(struct Csi::IReadStream *,struct Csi::FileChunkReference64 const &,struct Csi::IReadStream * *)` | 200 | Exported Function
`void __stdcall Csi::GetReadStreamWithUnk(struct Csi::IReadStream *,struct IUnknown *,struct Csi::IReadStream * *)` | 201 | Exported Function
`void __stdcall Csi::GetReadStreamOnStreamOffset(struct Csi::IReadStream *,unsigned __int64,struct Csi::IReadStream * *)` | 199 | Exported Function
`void __stdcall Csi::GetReadStreamOnMemory(struct Csi::IReadStream * *,unsigned char const *,unsigned int)` | 197 | Exported Function
`void __stdcall Csi::GetReadStreamOnSequentialStream(struct Csi::ISequentialReadStream *,struct Csi::IReadStream * *,unsigned __int64)` | 198 | Exported Function
`void __stdcall Csi::GetReadStreamOnAtom(class MsoCF::IAtom *,struct Csi::IReadStream * *)` | 191 | Exported Function
`void __stdcall Csi::GetLockBytesOnStream(struct Csi::IFixedWriteStream *,struct ILockBytes * *)` | 177 | Exported Function
`void __stdcall Csi::GetLockBytesOnStream(struct Csi::IReadStream *,struct ILockBytes * *)` | 178 | Exported Function
`void __stdcall Csi::GetIWorkingCopyUtils(struct Csi::IWorkingCopyUtils * *)` | 175 | Exported Function
`void __stdcall Csi::GetFolderProxyFromRegistryPath(struct _msoreg const *,struct Csi::IFolderProxy * *,class MsoCF::String<struct MsoCF::WzTraits>,bool,bool,bool *)` | 170 | Exported Function
`void __stdcall Csi::GetFolderProxyFromRelativeOrAbsolutePath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy *,struct Csi::IFolderProxy * *)` | 171 | Exported Function
`void __stdcall Csi::GetOfficeFileCacheFolder(struct Csi::IFolderProxy * *)` | 186 | Exported Function
`void __stdcall Csi::GetPlaceholderReadStream(struct Csi::IReadStream * *)` | 188 | Exported Function
`void __stdcall Csi::GetOfficeFileCache2(struct Csi::IOfficeFileCache2 * *)` | 185 | Exported Function
`void __stdcall Csi::GetLockBytesOnStream(struct Csi::ISizeableWriteStream *,struct ILockBytes * *)` | 179 | Exported Function
`void __stdcall Csi::GetNextBufferSize(unsigned int,unsigned __int64,unsigned int &)` | 180 | Exported Function
`public: void __thiscall Csi::CRevisionManifestScaffold::AddObjectGroup(struct MsoCF::ExtendedGUID const &)` | 12 | Exported Function
`bool __stdcall FEnsureDirectUrlToFile(wchar_t const * const)` | 114 | Exported Function
`bool __stdcall FEnsureUNCPath(wchar_t const * const)` | 115 | Exported Function
`bool __stdcall FEnsureCsiCompatibleProtocol(wchar_t const * const)` | 112 | Exported Function
`bool __stdcall Csi::TryDiscardFile(struct _GUID const &)` | 328 | Exported Function
`bool __stdcall Csi::TryEnsureOfficeSyncProcessInitialized(void)` | 329 | Exported Function
`class Mso::LegacyFuture<class Mso::TCntPtr<struct MsoCF::IError> > __stdcall Csi::DeleteServerDocumentAsync(struct IMsoUrl const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 100 | Exported Function
`class Mso::TCntPtr<class Storage::ISettings> __stdcall DocumentRevisionGraph::CreateSettings(void)` | 88 | Exported Function
`class Mso::LegacyFuture<class Mso::TCntPtr<struct MsoCF::IError> > __stdcall Csi::DeleteLocalDocumentAsync(struct Mso::UserStorage::IFile &)` | 99 | Exported Function
`bool __stdcall FTryDeserializeDataElementPackage(class Csi::CStreamObjectParser &,struct CsiCell::IDataElementWriteStream *,class Csi::CSerialNumberMapper *,struct CsiCell::IDataElementCallbacks *)` | 127 | Exported Function
`class Csi::CsiErrorCode __stdcall Csi::Errors::GetErrorCodeFromCsiError(struct MsoCF::IError *)` | 161 | Exported Function
`bool __stdcall Csi::Sync::IsWaiting(struct MsoCF::Async::IAsyncResult *)` | 283 | Exported Function
`bool __stdcall Csi::IsAssociatedApplicationCacheAware(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &)` | 249 | Exported Function
`bool __stdcall Csi::IsBranchEmpty(struct Csi::IFileBranch *)` | 251 | Exported Function
`bool __stdcall Csi::IsApplicationCacheAware(wchar_t const *,int * const)` | 248 | Exported Function
`bool __stdcall Csi::FTryDeserializeDataElementPackage(struct Csi::ISequentialReadStream *,struct CsiCell::IDataElementPackage * *,class Csi::CSerialNumberMapper *,struct CsiCell::IDataElementCallbacks *)` | 129 | Exported Function
`bool __stdcall Csi::GetServerInfoByFileUrl(struct IMsoUrl const *,struct Csi::CsiServerInfo *)` | 213 | Exported Function
`bool __stdcall Csi::IsMetroFileExtension(wchar_t const *)` | 271 | Exported Function
`bool __stdcall Csi::Sync::IsSyncing(struct MsoCF::Async::IAsyncResult *)` | 279 | Exported Function
`bool __stdcall Csi::IsLongTermCachingDisabled(void)` | 270 | Exported Function
`bool __stdcall Csi::IsFileCacheProhibited(class MsoCF::String<struct MsoCF::WzTraits>)` | 263 | Exported Function
`bool __stdcall Csi::IsFileOneNoteExtension(class MsoCF::String<struct MsoCF::WzTraits>)` | 265 | Exported Function
`class Mso::TCntPtr<struct Csi::IDocumentFactory> __stdcall Csi::GetDocumentFactory(void)` | 155 | Exported Function
`class std::unique_ptr<class Csi::IServerCountMapUpdater,struct std::default_delete<class Csi::IServerCountMapUpdater> > __stdcall Csi::CreateServerCountMapUpdater(void)` | 86 | Exported Function
`class std::vector<struct std::pair<class Csi::CsiErrorCode,enum Csi::ReadOnlyReason>,class std::allocator<struct std::pair<class Csi::CsiErrorCode,enum Csi::ReadOnlyReason> > > const & __stdcall Csi::GetErrorToReadOnlyReasonMappings(void)` | 164 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall Csi::ExtractWopiSrcFromWopiUrl(wchar_t const *)` | 110 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall Csi::Configuration::GetString(enum Csi::Configuration::ConfigurationId)` | 223 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall Csi::ConstructWopiUrl(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 33 | Exported Function
`enum Csi::FileSyncStatus __stdcall Csi::Sync::WaitForSyncIteration(struct MsoCF::Async::IAsyncResult *,unsigned int,void *)` | 342 | Exported Function
`enum Csi::OfficeFileCacheStartResult __stdcall Csi::StartOfficeFileCache2(struct Csi::StartOfficeFileCacheArgs2 *,struct Csi::IOfficeFileCache2 * *,struct MsoCF::IError * *)` | 323 | Exported Function
`enum Csi::EnumFileExistsResult __stdcall Csi::ValidateSubcache_ForGroove(struct _GUID const &,void *,int &,void (__stdcall*)(void *,unsigned int,wchar_t const *) noexcept)` | 341 | Exported Function
`EndEnsureCsiUninitializedEx` | 349 | Exported Function
`enum Csi::CsiApplicationEnum __stdcall Csi::GetApplicationAssociatedToExtension(wchar_t const *)` | 136 | Exported Function
`class std::array<unsigned char,16> const __stdcall DocumentRevisionGraph::HashStringToDocumentId(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 245 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __stdcall DocumentRevisionGraph::TryUnwrapIWriteStreamFromIBS(struct IByteStream &)` | 331 | Exported Function
`class Mso::TCntPtr<struct IByteStream> __stdcall DocumentRevisionGraph::WrapIReadStreamInIBS(struct DocumentRevisionGraph::IReadStream &)` | 344 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IReadStream> __stdcall DocumentRevisionGraph::TryUnwrapIReadStreamFromIBS(struct IByteStream &)` | 330 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IDocumentRepository> __stdcall DocumentRevisionGraph::CreateDocumentRepository(class Disco::IFileSystem *,class Mso::TCntPtr<class Storage::ISettings> &&)` | 63 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IDocumentRepository> __stdcall DocumentRevisionGraph::CreateDocumentRepository(enum DocumentRevisionGraph::StorageMode,class Mso::TCntPtr<class Storage::ISettings> &&)` | 64 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __stdcall ZipArchiveOnDictionary::CreateWriteArchive(struct DocumentRevisionGraph::IImmutableDictionaryBuilder &,class Mso::Functor<class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __stdcall(void)>)` | 92 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __stdcall ZipArchiveOnDictionary::CreateWriteArchiveWithLookupDictionary(struct DocumentRevisionGraph::IImmutableDictionaryBuilder &,struct DocumentRevisionGraph::IImmutableDictionary &,class Mso::Functor<class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __stdcall(void)>)` | 93 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __stdcall ZipArchiveOnDictionary::CreateReadOnlyArchive(struct DocumentRevisionGraph::IImmutableDictionary &)` | 81 | Exported Function
`class Mso::TCntPtr<struct IByteStream> __stdcall DocumentRevisionGraph::WrapIWriteStreamInIBS(struct DocumentRevisionGraph::IWriteStream &)` | 345 | Exported Function
`class Mso::TCntPtr<struct IUnknown> __stdcall Csi::Configuration::GetUnknown(enum Csi::Configuration::ConfigurationId)` | 225 | Exported Function
`bool __stdcall Csi::FTryDeserializeDataElementPackage(class Csi::CStreamObjectParser &,struct CsiCell::IDataElementPackage * *,class Csi::CSerialNumberMapper *,struct CsiCell::IDataElementCallbacks *)` | 128 | Exported Function
`bool __stdcall Csi::Errors::IsCoherencyError(struct MsoCF::IError *)` | 254 | Exported Function
`bool __stdcall Csi::Errors::IsCsiError(struct MsoCF::IError *)` | 255 | Exported Function
`bool __stdcall Csi::Errors::IsCacheVersionError(struct MsoCF::IError *)` | 253 | Exported Function
`bool __stdcall Csi::Errors::IsBaseDownloadError(struct MsoCF::IError const *)` | 250 | Exported Function
`bool __stdcall Csi::Errors::IsCacheCorruptionError(struct MsoCF::IError *)` | 252 | Exported Function
`bool __stdcall Csi::Errors::IsFallbackToDavError(struct MsoCF::IError *)` | 260 | Exported Function
`bool __stdcall Csi::Errors::IsFallbackToHttpError(struct MsoCF::IError *)` | 261 | Exported Function
`bool __stdcall Csi::Errors::IsFallBackOfflineError(struct MsoCF::IError *)` | 259 | Exported Function
`bool __stdcall Csi::Errors::IsCsiError(struct MsoCF::IError const *,class Csi::CsiErrorCode)` | 256 | Exported Function
`bool __stdcall Csi::Errors::IsDependentRequestNotExecutedError(struct MsoCF::IError *)` | 257 | Exported Function
`bool __stdcall Csi::Errors::AreEqualError(struct MsoCF::IError *,struct MsoCF::IError *)` | 20 | Exported Function
`BeginEnsureCsiUninitializedEx` | 348 | Exported Function
`bool __stdcall Csi::AreEqualSequentialStreams(struct Csi::ISequentialReadStream *,struct Csi::ISequentialReadStream *,unsigned int)` | 21 | Exported Function
`_HrCreateEditorsTableXmlManager@4` | 351 | Exported Function
`__int64 __stdcall Csi::Configuration::GetSignedInteger64(enum Csi::Configuration::ConfigurationId)` | 216 | Exported Function
`_FIsAsyncOpenSkyDriveProFile@4` | 350 | Exported Function
`bool __stdcall Csi::Configuration::GetBoolean(enum Csi::Configuration::ConfigurationId)` | 137 | Exported Function
`bool __stdcall Csi::CsiClientIsLoggingTraceTagSet(unsigned int)` | 96 | Exported Function
`bool __stdcall Csi::CanUseTransactedStream(wchar_t const *,enum Csi::SyncBackedType,enum Csi::FileLocationType,bool)` | 30 | Exported Function
`bool __stdcall Csi::AreEqualStreams(struct Csi::IReadStream *,struct Csi::IReadStream *)` | 22 | Exported Function
`bool __stdcall Csi::AreStreamAndAtomEqual(struct Csi::IReadStream *,class MsoCF::IAtom *)` | 23 | Exported Function
`bool __stdcall Csi::Errors::IsFallbackToLocalWorkingCopyOnOpenError(struct MsoCF::IError *)` | 262 | Exported Function
`bool __stdcall Csi::FGetStreamOutermostSubsetOf(struct Csi::IReadStream *,struct Csi::IReadStream * *,struct Csi::FileChunkReference64 *,bool *)` | 119 | Exported Function
`bool __stdcall Csi::FIsCurrentApplicationCoauthEnabled(void)` | 120 | Exported Function
`bool __stdcall Csi::FGetCsiFileFromPath2(wchar_t const *,struct Csi::IOfficeFileCacheFile2 * *,bool,bool *,enum Csi::FileOpenState,struct Csi::CsiServerInfo const *,wchar_t const *,wchar_t const *)` | 117 | Exported Function
`bool __stdcall Csi::FCobaltDisabled(void)` | 111 | Exported Function
`bool __stdcall Csi::FGetCellKnowledge(struct Csi::IKnowledge *,struct CsiCell::ICellKnowledge * *)` | 116 | Exported Function
`bool __stdcall Csi::FPathInExplicitSubcache(wchar_t const *)` | 125 | Exported Function
`bool __stdcall Csi::FSyncLocalWorkingFileTime(wchar_t const *)` | 126 | Exported Function
`bool __stdcall Csi::FOfficeFileCacheFolderValid(void)` | 124 | Exported Function
`bool __stdcall Csi::FIsFileInCache(struct IMsoUrl const *,struct Csi::CacheFileParams *)` | 121 | Exported Function
`bool __stdcall Csi::FIsSpecializedKnowledgeEqual(struct Csi::ISpecializedKnowledge *,struct Csi::ISpecializedKnowledge *)` | 122 | Exported Function
`bool __stdcall Csi::Errors::IsUnresolvedUploadError(struct MsoCF::IError *)` | 282 | Exported Function
`bool __stdcall Csi::Errors::IsGetDocMetaInfoNotSupportedError(struct MsoCF::IError *)` | 267 | Exported Function
`bool __stdcall Csi::Errors::IsInAppDownloadAuthenticationError(struct MsoCF::IError *)` | 268 | Exported Function
`bool __stdcall Csi::Errors::IsFileOpenForEditTakenError(struct MsoCF::IError const *)` | 266 | Exported Function
`bool __stdcall Csi::Errors::IsFFMColdMismatchHRESULTError(struct MsoCF::IError *)` | 258 | Exported Function
`bool __stdcall Csi::Errors::IsFileCorruptionError(struct MsoCF::IError *)` | 264 | Exported Function
`bool __stdcall Csi::Errors::IsRetryRaceConditionError(struct MsoCF::IError *)` | 276 | Exported Function
`bool __stdcall Csi::Errors::IsServerOnlyAsyncOpenDownloadFailure(struct MsoCF::IError *)` | 278 | Exported Function
`bool __stdcall Csi::Errors::IsRetryImmediatelyError(struct MsoCF::IError *)` | 275 | Exported Function
`bool __stdcall Csi::Errors::IsRecoverableEditorsTableSyncError(struct MsoCF::IError *)` | 272 | Exported Function
`bool __stdcall Csi::Errors::IsRecoverableError(struct MsoCF::IError *)` | 273 | Exported Function
`enum Csi::ReadOnlyReason __stdcall Csi::GetReadOnlyReasonFromError(struct MsoCF::IError const *)` | 190 | Exported Function
`public: unsigned int __stdcall Csi::CRevisionBuilder2::CountOfObjects(void)` | 48 | Exported Function
`public: virtual __thiscall Csi::CCellStorageRequestProcessor::~CCellStorageRequestProcessor(void)` | 5 | Exported Function
`public: unsigned __int64 __stdcall Csi::CRevisionBuilder2::SizeOfObjectDataInBytes(struct MsoCF::ExtendedGUID const &,unsigned char)` | 319 | Exported Function
`public: static void __stdcall Csi::DocumentState::QueryFactory::CreateQueryDocument(wchar_t const *,struct Csi::DocumentState::IQueryDocument * *)` | 80 | Exported Function
`public: struct MsoCF::ExtendedGUID const & __stdcall Csi::CRevisionWriteObject2::GetObjectID(void)` | 183 | Exported Function
`public: virtual bool __thiscall Csi::DocumentState::Listener::IsRegistered(void)` | 274 | Exported Function
`public: virtual struct _GUID __thiscall Csi::DocumentState::BroadcasterRegistration::RegisterListenerForDocument(wchar_t const *,struct Csi::DocumentState::IListener *)` | 296 | Exported Function
`public: virtual bool __thiscall Csi::DocumentState::BroadcasterRegistration::RegisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener *)` | 295 | Exported Function
`public: virtual __thiscall Csi::DocumentState::Listener::~Listener(void)` | 7 | Exported Function
`public: virtual bool __thiscall Csi::DocumentState::BroadcasterRegistration::RegisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener *)` | 293 | Exported Function
`public: static void __stdcall Csi::DocumentState::QueryFactory::CreateQueryAllDocumentsWithErrors(struct Csi::DocumentState::IQuery * *)` | 79 | Exported Function
`public: static void __stdcall Csi::DocumentState::Broadcaster::RegisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener *)` | 294 | Exported Function
`public: static void __stdcall Csi::DocumentState::Broadcaster::UnregisterDocumentListener(struct _GUID const &)` | 333 | Exported Function
`public: static void __stdcall Csi::DocumentState::Broadcaster::RegisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener *)` | 292 | Exported Function
`public: static struct _GUID const __stdcall Csi::DocumentState::Broadcaster::RegisterDocumentListener(wchar_t const *,struct Csi::DocumentState::IListener *)` | 291 | Exported Function
`public: static void __stdcall Csi::CRevisionBuilder2::CreateInstance(struct CsiCell::ICellStorageLocal *,struct MsoCF::ExtendedGUID const &,struct CsiCell::IRevision *,bool,struct MsoCF::ExtendedGUID const &,class Csi::CRevisionBuilder2 * *)` | 66 | Exported Function
`public: static void __stdcall Csi::DocumentState::Listener::SetRegistrationOverride_ForTesting(class Csi::DocumentState::BroadcasterRegistration *)` | 315 | Exported Function
`public: static void __stdcall Csi::DocumentState::QueryFactory::CreateQueryAllDocumentsNeedingAttention(struct Csi::DocumentState::IQuery * *)` | 78 | Exported Function
`public: static void __stdcall Csi::DocumentState::Listener::ResetRegistrationOverride_ForTesting(void)` | 299 | Exported Function
`public: static void __stdcall Csi::DocumentState::Broadcaster::UnregisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener *)` | 335 | Exported Function
`public: static void __stdcall Csi::DocumentState::Broadcaster::UnregisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener *)` | 337 | Exported Function
`public: virtual void __thiscall Csi::DocumentState::BroadcasterRegistration::UnregisterDocumentListener(struct _GUID const &)` | 334 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetWriteObject(struct MsoCF::ExtendedGUID const &,class Csi::CRevisionWriteObject2 * *,bool)` | 232 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::SetRootObject(struct MsoCF::ExtendedGUID const &,struct MsoCF::ExtendedGUID const &)` | 316 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetRootObject(struct MsoCF::ExtendedGUID const &,struct MsoCF::ExtendedGUID *)` | 203 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetPartitions(struct MsoCF::ExtendedGUID const &,class MsoCF::CArrayInBuffer<unsigned char> &)` | 187 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetRevisionID(struct MsoCF::ExtendedGUID *)` | 202 | Exported Function
`public: void __thiscall Csi::CDataElementPackage::AddDataElement(struct CsiCell::IDataElement *)` | 11 | Exported Function
`public: void __thiscall Csi::CObjectGroupScaffold::AddObjectPartition(struct MsoCF::ExtendedGUID const &,unsigned char,enum CsiCell::ObjectChangeFrequency,struct MsoCF::ExtendedGUID const *,unsigned int,struct CsiCell::ContextAndCellID const *,unsigned int,struct Csi::IReadStream *,struct MsoCF::ExtendedGUID const &)` | 13 | Exported Function
`public: void __thiscall Csi::CCellManifestScaffold::SetCurrentRevision(struct MsoCF::ExtendedGUID const &)` | 313 | Exported Function
`public: void __stdcall Csi::CRevisionWriteObject2::FinishWrite(void)` | 133 | Exported Function
`public: void __stdcall Csi::CRevisionWriteObject2::GetData(struct Csi::ISizeableWriteStream * *,unsigned char)` | 153 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetObjectReferences(struct MsoCF::ExtendedGUID const &,unsigned char,class MsoCF::CArrayInBuffer<struct MsoCF::ExtendedGUID> *,class MsoCF::CArrayInBuffer<struct CsiCell::ContextAndCellID> *)` | 184 | Exported Function
`public: void __stdcall Csi::CCellStorageSyncer::Sync(void)` | 324 | Exported Function
`public: void __stdcall Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::Add(enum Csi::RevertToServerVersionBeforeFirstSaveDisabledReason)` | 9 | Exported Function
`public: void __stdcall Csi::CCellStorageSyncer::Attach(struct CsiCell::ICellStorage *,struct CsiCell::ICellStorage *)` | 24 | Exported Function
`public: virtual void __thiscall Csi::DocumentState::BroadcasterRegistration::UnregisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener *)` | 336 | Exported Function
`public: virtual void __thiscall Csi::DocumentState::BroadcasterRegistration::UnregisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener *)` | 338 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::EnumObjectIDs(struct CsiCell::IEnumObjectIDs * *)` | 109 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::GetObjectData(struct MsoCF::ExtendedGUID const &,unsigned char,struct Csi::IReadStream * *)` | 182 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::CreateWriteObject(class Csi::CRevisionWriteObject2 * *,bool,struct MsoCF::ExtendedGUID const &)` | 94 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::Abort(void)` | 8 | Exported Function
`public: void __stdcall Csi::CRevisionBuilder2::Commit(bool,bool *,struct CsiCell::IRevision * *)` | 32 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiFileClient> __stdcall Csi::WopiFileClientFactory::GetIWopiFileClient(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class Mso::TCntPtr<class Mso::Async::IDispatchQueue> const &)` | 174 | Exported Function
`public: __thiscall Csi::CCellStorageSyncer::CCellStorageSyncer(void)` | 2 | Exported Function
`public: __thiscall Csi::CCellStorageSyncer::~CCellStorageSyncer(void)` | 6 | Exported Function
`public: __thiscall Csi::CCellStorageRequestProcessor::CCellStorageRequestProcessor(void)` | 1 | Exported Function
`protected: __thiscall EditorInformation::EditorInformation(void)` | 3 | Exported Function
`protected: virtual void __thiscall Csi::CCellStorageRequestProcessor::SetLoggingContext(struct Csi::ILoggingContext *)` | 314 | Exported Function
`public: bool __stdcall Csi::CRevisionBuilder2::FGetObjectData(struct MsoCF::ExtendedGUID const &,unsigned char,struct Csi::IReadStream * *)` | 118 | Exported Function
`public: bool __stdcall Csi::CRevisionBuilder2::HasObject(struct MsoCF::ExtendedGUID const &)` | 243 | Exported Function
`public: bool __stdcall Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::IsRevertToSerVerBeforeFirstSaveDisabled(void)const ` | 277 | Exported Function
`public: __thiscall Csi::DocumentState::Listener::Listener(unsigned long,bool,class Mso::TCntPtr<class Csi::DocumentState::BroadcasterRegistration>)` | 4 | Exported Function
`public: bool __stdcall Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::Get(enum Csi::RevertToServerVersionBeforeFirstSaveDisabledReason)` | 134 | Exported Function
`long __stdcall Csi::HrDavUploadNewFile(wchar_t const *,struct IStream *,bool)` | 246 | Exported Function
`long __stdcall Csi::CsiHrMakeVersionRequest(struct Csi::ISoapWebService *,wchar_t const *,wchar_t const *,enum VersionsSoapOp,class VersionsContext * *,struct IAsyncSoapCallback *)` | 98 | Exported Function
`long __stdcall Csi::GetBroadcastSoap(struct Csi::BroadcastVersion,struct Csi::IBroadcastSoap * *)` | 138 | Exported Function
`long __stdcall Csi::BroadcastGetHostInfo(wchar_t const *,wchar_t *,struct Csi::BroadcastVersion *,int,struct Csi::BroadcastVersion *,wchar_t *,int)` | 29 | Exported Function
`int __stdcall Csi::Configuration::GetSignedInteger32(enum Csi::Configuration::ConfigurationId)` | 215 | Exported Function
`int __stdcall Csi::FEnsureCsiInitialized(enum Csi::CsiApplicationEnum,bool,struct MsoCF::IError * *,struct Csi::StartOfficeFileCacheArgs2 *,wchar_t const *)` | 113 | Exported Function
`long __stdcall Csi::GetProductInfo(wchar_t const *,wchar_t const *,wchar_t const *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,bool &,bool &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::C` | 189 | Exported Function
`long __stdcall Csi::GetWebAccountInfo(wchar_t const *,wchar_t const *,wchar_t const *,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveLibraryDescriptor> * *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,struct Mso::Authentication::IOfficeIdentity *)` | 231 | Exported Function
`long __stdcall Csi::GetNotebooks(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,enum Csi::ISkyDriveNotebookDescriptor::QueryFilter,bool,bool &,bool &,bool &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveNotebookDescriptor> * *,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveNotebookDescriptor> * *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class std::vector<class std::basic_string<wchar_t,struct std::char_trait` | 181 | Exported Function
`long __stdcall Csi::GetChangesSinceToken(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,int &,int &,int &,wchar_t const *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveItemDescriptor> * *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &)` | 140 | Exported Function
`long __stdcall Csi::GetItemInfo(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > &,class MsoCF::CIPtr<struct Csi::ISkyDriveLibraryDescriptor,struct Csi::ISkyDriveLibraryDescriptor> *)` | 176 | Exported Function
`public: bool __stdcall Csi::CRevisionBuilder2::HasReferences(struct MsoCF::ExtendedGUID const &,unsigned char,bool *,bool *)` | 244 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::CreateNewDocumentAtServerUri(struct IMsoUrl const &,wchar_t const *,enum Csi::FileLocation)` | 72 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::GetDocument(struct Mso::UserStorage::IFile const &)` | 154 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::CreateNewDocument(struct Mso::UserStorage::IFolder const &,wchar_t const *)` | 68 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::CreateDocumentForSaveAs(struct IMsoUrl const &)` | 60 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::CreateDocumentForSaveAs(struct Mso::UserStorage::IFile const &)` | 59 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiBrowse> __stdcall Csi::WopiBrowseFactory::GetIWopiBrowse(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::unique_ptr<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > >,struct std::default_delete<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > > >)` | 172 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiBrowse> __stdcall Csi::WopiBrowseFactory::GetIWopiBrowseForTestEnvironment(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &,class std::unique_ptr<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > >,struct std::default_delete<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > > >)` | 173 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::GetDocumentFromUriAndVersion(wchar_t const *,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 158 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::GetDocumentFromUri(wchar_t const *)` | 156 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __stdcall Csi::DocumentFactory::GetDocumentFromUriAndResourceID(wchar_t const *,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 157 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __stdcall Csi::DocumentFactory::CreateNewDocumentAsync(struct Mso::UserStorage::IFolder const &,wchar_t const *)` | 70 | Exported Function
`public: class MsoCF::CArrayInBuffer<struct CsiCell::ContextAndCellID> & __stdcall Csi::CRevisionWriteObject2::CellReferences(unsigned char)` | 31 | Exported Function
`public: class MsoCF::CArrayInBuffer<struct MsoCF::ExtendedGUID> & __stdcall Csi::CRevisionWriteObject2::ObjectReferences(unsigned char)` | 287 | Exported Function
`public: bool __thiscall Csi::CLoggingSettings::IsTraceTagEnabled(unsigned int)` | 281 | Exported Function
`public: bool __thiscall Csi::CLoggingSettings::IsLoggingLevelEnabled(enum Csi::CsiLoggingLevel)` | 269 | Exported Function
`public: bool __thiscall Csi::CLoggingSettings::IsTraceEnabledAtLevel(unsigned int,enum Csi::CsiLoggingLevel)` | 280 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __stdcall Csi::DocumentFactory::CreateNewDocumentAsync(struct IMsoUrl const &,wchar_t const *,enum Csi::FileLocation)` | 71 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __stdcall Csi::DocumentFactory::CreateNewDocumentAsync(struct Mso::OfficeServicesManager::IConnectedService const &,wchar_t const *,enum Csi::FileLocation)` | 69 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __stdcall Csi::DocumentFactory::CreateDocumentForSaveAsAsync(struct Mso::UserStorage::IFile const &)` | 61 | Exported Function
`public: static class Csi::CLoggingSettings * __stdcall Csi::CLoggingSettings::UseSingleton(void)` | 340 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __stdcall Csi::DocumentFactory::CreateDocumentForSaveAsAsync(struct IMsoUrl const &,enum Csi::FileLocation)` | 62 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: Csi.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20470
* Product Version: 16.0.12527.20470
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: Unknown
* VirusTotal Link: n/a




MIT License. Copyright (c) 2020 Strontic.


