---
title: Csi.dll | Microsoft Office Document Cache
excerpt: What is Csi.dll?
---

# Csi.dll 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\vfs\ProgramFilesCommonX64\Microsoft Shared\OFFICE16\Csi.dll`
* Description: Microsoft Office Document Cache

## Hashes

Type | Hash
-- | --
MD5 | `1592DB3DBBB0AF5B3B39CDAECBF4F02C`
SHA1 | `9259BD89D056E6D3586DAA289497BC7E5F9A016D`
SHA256 | `914F70A50949E494CEAE550D871DD982D2F04111C7464E64AB37E7E64F710308`
SHA384 | `CA7E4EA2008235157E39160179A1FC82B89A7B32B68925F57DF8B52B3F1D5B6A4EFFE763401912C8D660C70862F2A70A`
SHA512 | `38FA71B58DD9EBC7D7ACEF4FEF4DFE930276D67919905096387E5C88F0B0A5B0DE02170CF3CE9F5D08AD8D3A4F7FD81B1C6E1C105C0E8B005FD3D7F2B7BE444B`
SSDEEP | `98304:tWWnBFoEmaPu2b1xp5csVVKiUEeuVQdinmfiGGm0IJBKm:tbw2Zx0sVV3UEnGiSDL`
IMP | `F7CC830437BC386548CCBA1A47850417`
PESHA1 | `1A94EB0342CD647A418C6737D0D9A8C4CDF4CB9C`
PE256 | `F3FA19AE04F42967E28059BF5A704B0A37A977BFC8322B8C6B406C3BC82524CB`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`void __cdecl Csi::CreateCellStorageOverHttp(wchar_t const * __ptr64,struct CsiCell::ICellStorage * __ptr64 * __ptr64,struct _GUID const & __ptr64,struct Csi::IWebServiceSubRequestUserManager * __ptr64,struct Csi::IWebServiceRequest * __ptr64,wchar_t const * __ptr64,bool)` | 56 | Exported Function
`void __cdecl Csi::CreateCellStorageRequest(class Csi::CCellStorageRequestProcessor * __ptr64,struct CsiCell::IDataElementWriteStream * __ptr64,struct CsiCell::ICellStorageRequest * __ptr64 * __ptr64)` | 57 | Exported Function
`void __cdecl Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IFileProxy * __ptr64,struct Csi::IChangeCountNotify * __ptr64,bool,bool,bool,struct CsiCell::ICellStorageCollection * __ptr64 * __ptr64)` | 55 | Exported Function
`void __cdecl Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IByteStorage * __ptr64,struct Csi::IChangeCountNotify * __ptr64,bool,bool,struct CsiCell::ICellStorageCollection * __ptr64 * __ptr64)` | 53 | Exported Function
`void __cdecl Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IFileProxy * __ptr64,struct Csi::IChangeCountNotify * __ptr64,bool,bool,bool,struct CsiCell::ICellStorage * __ptr64 * __ptr64)` | 54 | Exported Function
`void __cdecl Csi::CreateKnowledge(struct Csi::IKnowledge * __ptr64 * __ptr64)` | 68 | Exported Function
`void __cdecl Csi::CreateNewStorageIndexScaffold(class Csi::CStorageIndexScaffold * __ptr64 * __ptr64)` | 74 | Exported Function
`void __cdecl Csi::CreateGenericFda(struct Csi::IFileDataAdapter * __ptr64 * __ptr64)` | 66 | Exported Function
`void __cdecl Csi::CreateCsiDllPropertySet(struct Csi::ICsiDllPropertySet * __ptr64 * __ptr64)` | 58 | Exported Function
`void __cdecl Csi::CreateDataElementPackage(class Csi::CDataElementPackage * __ptr64 * __ptr64)` | 59 | Exported Function
`void __cdecl Csi::CreateCellStorageOnLocalFileSystem(struct Csi::IByteStorage * __ptr64,struct Csi::IChangeCountNotify * __ptr64,bool,bool,struct CsiCell::ICellStorage * __ptr64 * __ptr64)` | 52 | Exported Function
`void __cdecl Csi::CopyFileToFileBranchImpl(struct Csi::IFileProxy * __ptr64,struct Csi::IByteStorage * __ptr64,struct Csi::IStorageLock * __ptr64,struct _GUID const & __ptr64,struct Csi::IFileBranch * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64)` | 44 | Exported Function
`void __cdecl Csi::CopyFileToStream(struct Csi::IFileProxy * __ptr64,struct IStream * __ptr64)` | 45 | Exported Function
`void __cdecl Csi::CopyFileToFileBranch(struct Csi::IFileProxy * __ptr64,struct _GUID const & __ptr64,struct Csi::IFileBranch * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64)` | 43 | Exported Function
`void __cdecl Csi::CopyFileBranchToStream(struct Csi::IFileBranch * __ptr64,struct _GUID const & __ptr64,struct Csi::ISequentialWriteStream * __ptr64,unsigned __int64,struct MsoCF::ExtendedGUID const & __ptr64)` | 41 | Exported Function
`void __cdecl Csi::CopyFileBranchToTempFile(wchar_t const * __ptr64,wchar_t const * __ptr64,struct Csi::IFileBranch * __ptr64)` | 42 | Exported Function
`void __cdecl Csi::CreateCellBinaryRequestProxy(struct CsiCell::ICellStorageBinary * __ptr64,struct CsiCell::ICellStorage * __ptr64 * __ptr64)` | 50 | Exported Function
`void __cdecl Csi::CreateCellManifestScaffold(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,class Csi::CCellManifestScaffold * __ptr64 * __ptr64)` | 51 | Exported Function
`void __cdecl Csi::CopyTempFileToFileBranch(struct Csi::IFileBranch * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 48 | Exported Function
`void __cdecl Csi::CopyStreamToFile(struct IStream * __ptr64,struct Csi::IFileProxy * __ptr64)` | 46 | Exported Function
`void __cdecl Csi::CopyStreamToFileBranch(struct Csi::IReadStream * __ptr64,struct _GUID const & __ptr64,struct Csi::IFileBranch * __ptr64,unsigned __int64,struct MsoCF::ExtendedGUID const & __ptr64,bool)` | 47 | Exported Function
`void __cdecl Csi::CreateNoChangeCellStorage(struct CsiCell::ICellStorage * __ptr64 * __ptr64)` | 75 | Exported Function
`void __cdecl Csi::EnableServerReachabilityAutoDiscovery(void)` | 103 | Exported Function
`void __cdecl Csi::EndEnsureCsiUninitialized(int)` | 104 | Exported Function
`void __cdecl Csi::DeserializeKnowledge(class Csi::CStreamObjectParser & __ptr64,struct Csi::IKnowledge * __ptr64 * __ptr64)` | 102 | Exported Function
`void __cdecl Csi::CsiAtomFromMsoCfAtom(class MsoCF::IAtom * __ptr64,struct Csi::ICsiAtom * __ptr64 * __ptr64)` | 96 | Exported Function
`void __cdecl Csi::CsiClientWriteToLog(unsigned int,enum Csi::CsiLoggingLevel,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 98 | Exported Function
`void __cdecl Csi::EnsureCellKnowledge(struct Csi::IKnowledge * __ptr64,struct CsiCell::ICellKnowledge * __ptr64 * __ptr64)` | 108 | Exported Function
`void __cdecl Csi::EnsureCsiUninitialized(int)` | 109 | Exported Function
`void __cdecl Csi::EndShutdownOfficeFileCache2(void)` | 107 | Exported Function
`void __cdecl Csi::EndFinishCsiClientDll(bool)` | 105 | Exported Function
`void __cdecl Csi::EndFinishCsiClientLib(void)` | 106 | Exported Function
`void __cdecl Csi::CreateTemporaryFile(struct Csi::IFileProxy * __ptr64 * __ptr64,wchar_t const * __ptr64)` | 92 | Exported Function
`void __cdecl Csi::CreateReadStreamOnByteStorage(struct Csi::IByteStorage * __ptr64,bool,struct Csi::FileChunkReference64 const & __ptr64,struct Csi::IStorageLock * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 83 | Exported Function
`void __cdecl Csi::CreateRevisionManifestScaffold(struct MsoCF::ExtendedGUID const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,class Csi::CRevisionManifestScaffold * __ptr64 * __ptr64)` | 84 | Exported Function
`void __cdecl Csi::CreateOfficeFileCacheUrl(struct Csi::IOfficeFileCache2 * __ptr64,struct Csi::IOfficeFileCacheUrl * __ptr64 * __ptr64)` | 78 | Exported Function
`void __cdecl Csi::CreateObjectDataBlob(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,unsigned __int64,class MsoCF::IAtom * __ptr64,struct Csi::IReadStream * __ptr64,unsigned __int64,struct CsiCell::IObjectDataBlob * __ptr64 * __ptr64)` | 76 | Exported Function
`void __cdecl Csi::CreateObjectGroupScaffold(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,class Csi::CObjectGroupScaffold * __ptr64 * __ptr64)` | 77 | Exported Function
`void __cdecl Csi::CreateStorageIndexScaffold(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,class Csi::CStorageIndexScaffold * __ptr64 * __ptr64)` | 90 | Exported Function
`void __cdecl Csi::CreateStorageManifestScaffold(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64,class Csi::CStorageManifestScaffold * __ptr64 * __ptr64)` | 91 | Exported Function
`void __cdecl Csi::CreateServerPropertySetForUpload(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,struct MsoCF::IPropertySet * __ptr64 * __ptr64)` | 88 | Exported Function
`void __cdecl Csi::CreateServerAccessOnWebService(wchar_t const * __ptr64,struct Csi::IServerAccess * __ptr64 * __ptr64,wchar_t const * __ptr64)` | 85 | Exported Function
`void __cdecl Csi::CreateServerAccessOverHttp(wchar_t const * __ptr64,struct Csi::IServerAccess * __ptr64 * __ptr64,struct _GUID const & __ptr64,wchar_t const * __ptr64)` | 86 | Exported Function
`void __cdecl Csi::CopyFileBranchToFileImpl(struct Csi::IFileBranch * __ptr64,struct Csi::IByteStorage * __ptr64,struct _GUID const & __ptr64,struct Csi::IFileProxy * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64)` | 40 | Exported Function
`unsigned long __cdecl Csi::GetCsiCapabilities(class MsoCF::String<struct MsoCF::WzTraits>,unsigned long)` | 149 | Exported Function
`unsigned short __cdecl Csi::Configuration::GetUnsignedInteger16(enum Csi::Configuration::ConfigurationId)` | 226 | Exported Function
`unsigned int __cdecl Csi::RandomNumber(unsigned int,unsigned int,bool)` | 290 | Exported Function
`unsigned char __cdecl Csi::Configuration::GetUnsignedInteger8(enum Csi::Configuration::ConfigurationId)` | 229 | Exported Function
`unsigned int __cdecl Csi::Configuration::GetUnsignedInteger32(enum Csi::Configuration::ConfigurationId)` | 227 | Exported Function
`void __cdecl Csi::AppendStringToNameOfFilename(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64)` | 19 | Exported Function
`void __cdecl Csi::BeginEnsureCsiUninitialized(int)` | 25 | Exported Function
`void __cdecl Csi::AddSerialNumber(struct CsiCell::ICellKnowledge * __ptr64,struct CsiCell::SerialNumber const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64)` | 17 | Exported Function
`unsigned short __cdecl Csi::GetCobaltRequestVersion(void)` | 141 | Exported Function
`unsigned short __cdecl Csi::GetCobaltResponseVersion(void)` | 142 | Exported Function
`unsigned __int64 __cdecl Csi::MapSubRequestToCellStorageRequest(class Csi::CSubRequest * __ptr64,struct CsiCell::ICellStorageRequest * __ptr64)` | 286 | Exported Function
`public: void __cdecl Csi::CStorageManifestScaffold::AddRootContextAndCellID(struct CsiCell::RootContextAndCellID const & __ptr64) __ptr64` | 15 | Exported Function
`public: void __cdecl Csi::CStorageManifestScaffold::SetSchemaID(struct _GUID const & __ptr64) __ptr64` | 317 | Exported Function
`public: void __cdecl Csi::CStorageIndexScaffold::AddStorageManifestMapping(struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64) __ptr64` | 18 | Exported Function
`public: void __cdecl Csi::CStorageIndexScaffold::AddCellToCellManifestMapping(struct CsiCell::ContextAndCellID const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64) __ptr64` | 10 | Exported Function
`public: void __cdecl Csi::CStorageIndexScaffold::AddRevisionToRevisionManifestMapping(struct MsoCF::ExtendedGUID const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::SerialNumber const & __ptr64) __ptr64` | 14 | Exported Function
`struct MsoCF::IError * __ptr64 __cdecl Csi::Errors::UseIError(class MsoCF::CErrorException const & __ptr64)` | 339 | Exported Function
`unsigned __int64 __cdecl Csi::Configuration::GetUnsignedInteger64(enum Csi::Configuration::ConfigurationId)` | 228 | Exported Function
`struct Csi::MapPathsResult __cdecl Csi::FMapPaths(wchar_t * __ptr64,int,wchar_t * __ptr64,int,wchar_t const * __ptr64,bool,bool,bool)` | 124 | Exported Function
`short __cdecl Csi::Configuration::GetSignedInteger16(enum Csi::Configuration::ConfigurationId)` | 214 | Exported Function
`signed char __cdecl Csi::Configuration::GetSignedInteger8(enum Csi::Configuration::ConfigurationId)` | 217 | Exported Function
`void __cdecl Csi::BeginFinishCsiClientDll(bool)` | 26 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned short)` | 306 | Exported Function
`void __cdecl Csi::ConvertStorageService(struct _GUID const & __ptr64,struct _GUID const & __ptr64,struct IUnknown * __ptr64,struct _GUID const & __ptr64,struct _GUID const & __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 34 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned int)` | 308 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned __int64)` | 311 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,unsigned char)` | 304 | Exported Function
`void __cdecl Csi::ConvertTagToString(unsigned long,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64)` | 38 | Exported Function
`void __cdecl Csi::CopyFileBranchToFile(struct Csi::IFileBranch * __ptr64,struct _GUID const & __ptr64,struct Csi::IFileProxy * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64)` | 39 | Exported Function
`void __cdecl Csi::ConvertStream(struct Csi::ISizeableWriteStream * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 37 | Exported Function
`void __cdecl Csi::ConvertStream(struct Csi::IFixedWriteStream * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 35 | Exported Function
`void __cdecl Csi::ConvertStream(struct Csi::IReadStream * __ptr64,struct _GUID const & __ptr64,void * __ptr64 * __ptr64)` | 36 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,struct IUnknown * __ptr64)` | 309 | Exported Function
`void __cdecl Csi::Configuration::Reset(enum Csi::Configuration::ConfigurationId)` | 298 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,__int64)` | 310 | Exported Function
`void __cdecl Csi::CellStorageXML::WriteRequestResponse(struct Csi::CellStorageXML::AWriteSite * __ptr64,class MsoCF::String<struct MsoCF::WzTraits>,bool,bool,class MsoCF::CMap<class Csi::CSubRequest * __ptr64,unsigned __int64> const & __ptr64,struct CsiCell::IDataElementPackage * __ptr64,struct CsiCell::IDataElementPackage * __ptr64)` | 346 | Exported Function
`void __cdecl Csi::BeginFinishCsiClientLib(void)` | 27 | Exported Function
`void __cdecl Csi::BeginShutdownOfficeFileCache2(void)` | 28 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,short)` | 305 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,signed char)` | 303 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,int)` | 307 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,bool)` | 312 | Exported Function
`void __cdecl Csi::Configuration::Set(enum Csi::Configuration::ConfigurationId,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64)` | 302 | Exported Function
`void __cdecl Csi::FinishCsiClientDll(bool)` | 130 | Exported Function
`void __cdecl Csi::GetWriteStreamOnComStream(struct IStream * __ptr64,struct Csi::FileChunkReference64 const & __ptr64,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 233 | Exported Function
`void __cdecl Csi::GetWriteStreamOnComStream(struct IStream * __ptr64,unsigned int,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 234 | Exported Function
`void __cdecl Csi::GetTemporaryFolder(struct Csi::IFolderProxy * __ptr64 * __ptr64)` | 224 | Exported Function
`void __cdecl Csi::GetSizeableWriteStreamOnMemory(struct Csi::ISizeableWriteStream * __ptr64 * __ptr64,unsigned char const * __ptr64,unsigned int,unsigned int,bool,bool)` | 221 | Exported Function
`void __cdecl Csi::GetSizeableWriteStreamWithUnk(struct Csi::ISizeableWriteStream * __ptr64,struct IUnknown * __ptr64,struct Csi::ISizeableWriteStream * __ptr64 * __ptr64)` | 222 | Exported Function
`void __cdecl Csi::GetWriteStreamOnMemory(struct Csi::IFixedWriteStream * __ptr64 * __ptr64,unsigned char const * __ptr64,unsigned int,bool,bool)` | 238 | Exported Function
`void __cdecl Csi::GetWriteStreamOnStreamOffset(struct Csi::IFixedWriteStream * __ptr64,unsigned __int64,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 239 | Exported Function
`void __cdecl Csi::GetWriteStreamOnMemory(struct Csi::IFixedWriteStream * __ptr64 * __ptr64,struct Csi::IReadStream * __ptr64)` | 237 | Exported Function
`void __cdecl Csi::GetWriteStreamOnExistingAlloc(unsigned char * __ptr64,unsigned int,struct Csi::IFixedWriteStream * __ptr64 * __ptr64,struct IUnknown * __ptr64)` | 235 | Exported Function
`void __cdecl Csi::GetWriteStreamOnLockBytes(struct ILockBytes * __ptr64,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 236 | Exported Function
`void __cdecl Csi::GetSizeableWriteStreamOnMemory(struct Csi::ISizeableWriteStream * __ptr64 * __ptr64,struct Csi::IReadStream * __ptr64,unsigned int,bool,bool)` | 220 | Exported Function
`void __cdecl Csi::GetSequentialWriteStreamOnComStream(struct ISequentialStream * __ptr64,struct Csi::ISequentialWriteStream * __ptr64 * __ptr64)` | 208 | Exported Function
`void __cdecl Csi::GetSequentialWriteStreamOnComStream(struct IStream * __ptr64,struct Csi::ISequentialWriteStream * __ptr64 * __ptr64,unsigned __int64)` | 209 | Exported Function
`void __cdecl Csi::GetSequentialReadStreamOnStream(struct Csi::IReadStream * __ptr64,struct Csi::ISequentialReadStream * __ptr64 * __ptr64,unsigned __int64)` | 207 | Exported Function
`void __cdecl Csi::GetSequentialReadStreamOnSequentialComStream(struct ISequentialStream * __ptr64,struct Csi::ISequentialReadStream * __ptr64 * __ptr64)` | 205 | Exported Function
`void __cdecl Csi::GetSequentialReadStreamOnSimple(struct Csi::ISequentialReadStreamSimple * __ptr64,struct Csi::ISequentialReadStream * __ptr64 * __ptr64)` | 206 | Exported Function
`void __cdecl Csi::GetSizeableWriteStreamOnComStream(struct IStream * __ptr64,struct Csi::ISizeableWriteStream * __ptr64 * __ptr64)` | 218 | Exported Function
`void __cdecl Csi::GetSizeableWriteStreamOnLockBytes(struct ILockBytes * __ptr64,struct Csi::ISizeableWriteStream * __ptr64 * __ptr64)` | 219 | Exported Function
`void __cdecl Csi::GetSequentialWriteStreamOnStream(struct Csi::ISizeableWriteStream * __ptr64,struct Csi::ISequentialWriteStream * __ptr64 * __ptr64,unsigned __int64)` | 212 | Exported Function
`void __cdecl Csi::GetSequentialWriteStreamOnSimple(struct Csi::ISequentialWriteStreamSimple * __ptr64,struct Csi::ISequentialWriteStream * __ptr64 * __ptr64)` | 210 | Exported Function
`void __cdecl Csi::GetSequentialWriteStreamOnStream(struct Csi::IFixedWriteStream * __ptr64,struct Csi::ISequentialWriteStream * __ptr64 * __ptr64,unsigned __int64)` | 211 | Exported Function
`void __cdecl Csi::GetWriteStreamOnStreamSubset(struct Csi::IFixedWriteStream * __ptr64,struct Csi::FileChunkReference64 const & __ptr64,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 240 | Exported Function
`void __cdecl Csi::Sync::TryCancelRequest(struct MsoCF::Async::IAsyncResult * __ptr64,unsigned long)` | 327 | Exported Function
`void __cdecl Csi::Sync::WaitIfWaiting(struct MsoCF::Async::IAsyncResult * __ptr64,void * __ptr64)` | 343 | Exported Function
`void __cdecl Csi::StartCsiLogging(void)` | 322 | Exported Function
`void __cdecl Csi::StartCsiClientDll(enum Csi::CsiApplicationEnum,wchar_t const * __ptr64,bool)` | 320 | Exported Function
`void __cdecl Csi::StartCsiClientLib(enum Csi::CsiApplicationEnum)` | 321 | Exported Function
`void __cdecl Csi::WriteToLog_Impl(unsigned long,unsigned int,enum Csi::CsiLoggingLevel,struct _GUID const & __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 347 | Exported Function
`wchar_t const * __ptr64 __cdecl Csi::GetUsernameFromServerLockOwner(wchar_t const * __ptr64)` | 230 | Exported Function
`void __cdecl Csi::UninitCsiDavCache(void)` | 332 | Exported Function
`void __cdecl Csi::TEMPORARY_CopyStateSignatureToMemory(struct Csi::IReadStream * __ptr64,unsigned char * __ptr64,unsigned long)` | 325 | Exported Function
`void __cdecl Csi::TestApi_CreateStreamOnFileBranch(struct Csi::IFileBranch * __ptr64,enum Csi::FilePartitionType,enum Csi::FileBranchType,bool,struct IStream * __ptr64 * __ptr64,bool,bool)` | 326 | Exported Function
`void __cdecl Csi::ShutdownOfficeFileCache2(void)` | 318 | Exported Function
`void __cdecl Csi::LoadKnowledgeFromProperty(struct MsoCF::IPropertySet * __ptr64,unsigned int,struct Csi::IKnowledge * __ptr64 * __ptr64)` | 284 | Exported Function
`void __cdecl Csi::MapCellStorageResponseToSubRequest(struct CsiCell::ICellStorageResponse * __ptr64,unsigned __int64,class Csi::CSubRequest * __ptr64)` | 285 | Exported Function
`void __cdecl Csi::InitCsiDavCache(void)` | 247 | Exported Function
`void __cdecl Csi::GetWriteStreamWithUnk(struct Csi::IFixedWriteStream * __ptr64,struct IUnknown * __ptr64,struct Csi::IFixedWriteStream * __ptr64 * __ptr64)` | 241 | Exported Function
`void __cdecl Csi::GrooveSetURLReachable(wchar_t const * __ptr64,unsigned long)` | 242 | Exported Function
`void __cdecl Csi::SaveKnowledgeToProperty(struct Csi::IKnowledge * __ptr64,struct MsoCF::IPropertySet * __ptr64,unsigned int)` | 300 | Exported Function
`void __cdecl Csi::SerializeDataElementPackage(struct CsiCell::IDataElementPackage * __ptr64,struct Csi::ISequentialWriteStream * __ptr64,unsigned short,bool)` | 301 | Exported Function
`void __cdecl Csi::RegisterPrefetchFileProvider(class Mso::TCntPtr<struct Csi::ISupportPrefetchFile> const & __ptr64)` | 297 | Exported Function
`void __cdecl Csi::OnUserCredentialChange(wchar_t const * __ptr64)` | 288 | Exported Function
`void __cdecl Csi::PickupCreds(void)` | 289 | Exported Function
`void __cdecl Csi::GetSequentialReadStreamOnComStream(struct IStream * __ptr64,struct Csi::ISequentialReadStream * __ptr64 * __ptr64,unsigned __int64)` | 204 | Exported Function
`void __cdecl Csi::GetEnumServerTargetIDTestOnly(struct Csi::IOfficeFileCache2 const * __ptr64,struct Csi::IEnumServerTargetIDTestOnly * __ptr64 * __ptr64)` | 160 | Exported Function
`void __cdecl Csi::GetErrorReadStream(struct MsoCF::IError * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 162 | Exported Function
`void __cdecl Csi::GetEmptyReadStream(struct Csi::IReadStream * __ptr64 * __ptr64)` | 159 | Exported Function
`void __cdecl Csi::GetCsiErrorFromDavError(struct Csi::ICsiError * __ptr64 * __ptr64,struct Csi::ICsiDavError * __ptr64,bool)` | 151 | Exported Function
`void __cdecl Csi::GetCsiErrorFromDavError(struct MsoCF::IError * __ptr64 * __ptr64,struct Csi::ICsiDavError * __ptr64,bool)` | 152 | Exported Function
`void __cdecl Csi::GetFileProxyFromPath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFileProxy * __ptr64 * __ptr64,bool,bool * __ptr64,bool)` | 167 | Exported Function
`void __cdecl Csi::GetFileProxyFromRelativeOrAbsolutePath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy * __ptr64,struct Csi::IFileProxy * __ptr64 * __ptr64)` | 168 | Exported Function
`void __cdecl Csi::GetFilePropertiesFromFileStoreFile(struct Csi::IFileStoreFile * __ptr64,struct Csi::IFileProperties_DEPRECATE * __ptr64 * __ptr64)` | 166 | Exported Function
`void __cdecl Csi::GetErrorSizeableWriteStream(struct MsoCF::IError * __ptr64,struct Csi::ISizeableWriteStream * __ptr64 * __ptr64)` | 163 | Exported Function
`void __cdecl Csi::GetFileOrFolderProxyFromPathAndLeaf(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFileProxy * __ptr64 * __ptr64)` | 165 | Exported Function
`void __cdecl Csi::GetCsiDavClient(struct IMsoUrl * __ptr64,struct Csi::ICsiDavClient * __ptr64 * __ptr64)` | 150 | Exported Function
`void __cdecl Csi::GetCellStorageMultiRoundTrip(struct CsiCell::ICellStorage * __ptr64,struct CsiCell::IMultiRoundTripSuspend * __ptr64,struct CsiCell::ICellStorage * __ptr64 * __ptr64)` | 139 | Exported Function
`void __cdecl Csi::GetComStreamOnLockBytes(struct ILockBytes * __ptr64,struct IStream * __ptr64 * __ptr64,unsigned __int64,struct IUnknown * __ptr64)` | 143 | Exported Function
`void __cdecl Csi::GetAggregatedReadStream(class Ofc::TCntPtrList<struct Csi::IReadStream> const & __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 135 | Exported Function
`void __cdecl Csi::FinishCsiClientLib(void)` | 131 | Exported Function
`void __cdecl Csi::FinishCsiLogging(void)` | 132 | Exported Function
`void __cdecl Csi::GetComStreamOnSizeableWriteStream(struct Csi::ISizeableWriteStream * __ptr64,struct IStream * __ptr64 * __ptr64,unsigned __int64)` | 147 | Exported Function
`void __cdecl Csi::GetComStreamOnWriteStream(struct Csi::IFixedWriteStream * __ptr64,struct IStream * __ptr64 * __ptr64,unsigned __int64,struct IUnknown * __ptr64)` | 148 | Exported Function
`void __cdecl Csi::GetComStreamOnSequentialWriteStream(struct Csi::ISequentialWriteStream * __ptr64,struct IStream * __ptr64 * __ptr64)` | 146 | Exported Function
`void __cdecl Csi::GetComStreamOnReadStream(struct Csi::IReadStream * __ptr64,struct IStream * __ptr64 * __ptr64,unsigned __int64,struct IUnknown * __ptr64)` | 144 | Exported Function
`void __cdecl Csi::GetComStreamOnSequentialReadStream(struct Csi::ISequentialReadStream * __ptr64,struct IStream * __ptr64 * __ptr64)` | 145 | Exported Function
`void __cdecl Csi::GetFolderProxyFromPath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy * __ptr64 * __ptr64,bool,bool * __ptr64,bool)` | 169 | Exported Function
`void __cdecl Csi::GetReadStreamOnLockBytes(struct ILockBytes * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 195 | Exported Function
`void __cdecl Csi::GetReadStreamOnMemory(struct Csi::IReadStream * __ptr64 * __ptr64,struct Csi::IReadStream * __ptr64)` | 196 | Exported Function
`void __cdecl Csi::GetReadStreamOnExistingAlloc(unsigned char const * __ptr64,unsigned int,struct Csi::IReadStream * __ptr64 * __ptr64,struct IUnknown * __ptr64)` | 194 | Exported Function
`void __cdecl Csi::GetReadStreamOnComStream(struct IStream * __ptr64,struct Csi::FileChunkReference64 const & __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64,unsigned int,bool)` | 192 | Exported Function
`void __cdecl Csi::GetReadStreamOnComStream(struct IStream * __ptr64,unsigned int,struct Csi::IReadStream * __ptr64 * __ptr64,unsigned int,bool)` | 193 | Exported Function
`void __cdecl Csi::GetReadStreamOnStreamSubset(struct Csi::IReadStream * __ptr64,struct Csi::FileChunkReference64 const & __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 200 | Exported Function
`void __cdecl Csi::GetReadStreamWithUnk(struct Csi::IReadStream * __ptr64,struct IUnknown * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 201 | Exported Function
`void __cdecl Csi::GetReadStreamOnStreamOffset(struct Csi::IReadStream * __ptr64,unsigned __int64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 199 | Exported Function
`void __cdecl Csi::GetReadStreamOnMemory(struct Csi::IReadStream * __ptr64 * __ptr64,unsigned char const * __ptr64,unsigned int)` | 197 | Exported Function
`void __cdecl Csi::GetReadStreamOnSequentialStream(struct Csi::ISequentialReadStream * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64,unsigned __int64)` | 198 | Exported Function
`void __cdecl Csi::GetReadStreamOnAtom(class MsoCF::IAtom * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64)` | 191 | Exported Function
`void __cdecl Csi::GetLockBytesOnStream(struct Csi::IFixedWriteStream * __ptr64,struct ILockBytes * __ptr64 * __ptr64)` | 177 | Exported Function
`void __cdecl Csi::GetLockBytesOnStream(struct Csi::IReadStream * __ptr64,struct ILockBytes * __ptr64 * __ptr64)` | 178 | Exported Function
`void __cdecl Csi::GetIWorkingCopyUtils(struct Csi::IWorkingCopyUtils * __ptr64 * __ptr64)` | 175 | Exported Function
`void __cdecl Csi::GetFolderProxyFromRegistryPath(struct _msoreg const * __ptr64,struct Csi::IFolderProxy * __ptr64 * __ptr64,class MsoCF::String<struct MsoCF::WzTraits>,bool,bool,bool * __ptr64)` | 170 | Exported Function
`void __cdecl Csi::GetFolderProxyFromRelativeOrAbsolutePath(class MsoCF::String<struct MsoCF::WzTraits>,struct Csi::IFolderProxy * __ptr64,struct Csi::IFolderProxy * __ptr64 * __ptr64)` | 171 | Exported Function
`void __cdecl Csi::GetOfficeFileCacheFolder(struct Csi::IFolderProxy * __ptr64 * __ptr64)` | 186 | Exported Function
`void __cdecl Csi::GetPlaceholderReadStream(struct Csi::IReadStream * __ptr64 * __ptr64)` | 188 | Exported Function
`void __cdecl Csi::GetOfficeFileCache2(struct Csi::IOfficeFileCache2 * __ptr64 * __ptr64)` | 185 | Exported Function
`void __cdecl Csi::GetLockBytesOnStream(struct Csi::ISizeableWriteStream * __ptr64,struct ILockBytes * __ptr64 * __ptr64)` | 179 | Exported Function
`void __cdecl Csi::GetNextBufferSize(unsigned int,unsigned __int64,unsigned int & __ptr64)` | 180 | Exported Function
`public: void __cdecl Csi::CRevisionWriteObject2::GetData(struct Csi::ISizeableWriteStream * __ptr64 * __ptr64,unsigned char) __ptr64` | 153 | Exported Function
`class Csi::CsiErrorCode __cdecl Csi::Errors::GetErrorCodeFromCsiError(struct MsoCF::IError * __ptr64)` | 161 | Exported Function
`class Mso::LegacyFuture<class Mso::TCntPtr<struct MsoCF::IError> > __cdecl Csi::DeleteLocalDocumentAsync(struct Mso::UserStorage::IFile & __ptr64)` | 100 | Exported Function
`bool __cdecl FEnsureUNCPath(wchar_t const * __ptr64 const)` | 116 | Exported Function
`bool __cdecl FEnsureCsiCompatibleProtocol(wchar_t const * __ptr64 const)` | 113 | Exported Function
`bool __cdecl FEnsureDirectUrlToFile(wchar_t const * __ptr64 const)` | 115 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IDocumentRepository> __cdecl DocumentRevisionGraph::CreateDocumentRepository(class Disco::IFileSystem * __ptr64,class Mso::TCntPtr<class Storage::ISettings> && __ptr64)` | 64 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IDocumentRepository> __cdecl DocumentRevisionGraph::CreateDocumentRepository(enum DocumentRevisionGraph::StorageMode,class Mso::TCntPtr<class Storage::ISettings> && __ptr64)` | 65 | Exported Function
`class Mso::TCntPtr<struct Csi::IDocumentFactory> __cdecl Csi::GetDocumentFactory(void)` | 155 | Exported Function
`class Mso::LegacyFuture<class Mso::TCntPtr<struct MsoCF::IError> > __cdecl Csi::DeleteServerDocumentAsync(struct IMsoUrl const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64)` | 101 | Exported Function
`class Mso::TCntPtr<class Storage::ISettings> __cdecl DocumentRevisionGraph::CreateSettings(void)` | 89 | Exported Function
`bool __cdecl Csi::TryEnsureOfficeSyncProcessInitialized(void)` | 329 | Exported Function
`bool __cdecl Csi::IsFileCacheProhibited(class MsoCF::String<struct MsoCF::WzTraits>)` | 263 | Exported Function
`bool __cdecl Csi::IsFileOneNoteExtension(class MsoCF::String<struct MsoCF::WzTraits>)` | 265 | Exported Function
`bool __cdecl Csi::IsBranchEmpty(struct Csi::IFileBranch * __ptr64)` | 251 | Exported Function
`bool __cdecl Csi::IsApplicationCacheAware(wchar_t const * __ptr64,int * __ptr64 const)` | 248 | Exported Function
`bool __cdecl Csi::IsAssociatedApplicationCacheAware(class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64)` | 249 | Exported Function
`bool __cdecl Csi::Sync::IsWaiting(struct MsoCF::Async::IAsyncResult * __ptr64)` | 283 | Exported Function
`bool __cdecl Csi::TryDiscardFile(struct _GUID const & __ptr64)` | 328 | Exported Function
`bool __cdecl Csi::Sync::IsSyncing(struct MsoCF::Async::IAsyncResult * __ptr64)` | 279 | Exported Function
`bool __cdecl Csi::IsLongTermCachingDisabled(void)` | 270 | Exported Function
`bool __cdecl Csi::IsMetroFileExtension(wchar_t const * __ptr64)` | 271 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IReadStream> __cdecl DocumentRevisionGraph::TryUnwrapIReadStreamFromIBS(struct IByteStream & __ptr64)` | 330 | Exported Function
`enum Csi::CsiApplicationEnum __cdecl Csi::GetApplicationAssociatedToExtension(wchar_t const * __ptr64)` | 136 | Exported Function
`enum Csi::EnumFileExistsResult __cdecl Csi::ValidateSubcache_ForGroove(struct _GUID const & __ptr64,void * __ptr64,int & __ptr64,void (__cdecl*)(void * __ptr64,unsigned int,wchar_t const * __ptr64) noexcept)` | 341 | Exported Function
`EndEnsureCsiUninitializedEx` | 349 | Exported Function
`class std::unique_ptr<class Csi::IServerCountMapUpdater,struct std::default_delete<class Csi::IServerCountMapUpdater> > __cdecl Csi::CreateServerCountMapUpdater(void)` | 87 | Exported Function
`class std::vector<struct std::pair<class Csi::CsiErrorCode,enum Csi::ReadOnlyReason>,class std::allocator<struct std::pair<class Csi::CsiErrorCode,enum Csi::ReadOnlyReason> > > const & __ptr64 __cdecl Csi::GetErrorToReadOnlyReasonMappings(void)` | 164 | Exported Function
`FIsAsyncOpenSkyDriveProFile` | 350 | Exported Function
`HrCreateEditorsTableXmlManager` | 351 | Exported Function
`enum Csi::ReadOnlyReason __cdecl Csi::GetReadOnlyReasonFromError(struct MsoCF::IError const * __ptr64)` | 190 | Exported Function
`enum Csi::FileSyncStatus __cdecl Csi::Sync::WaitForSyncIteration(struct MsoCF::Async::IAsyncResult * __ptr64,unsigned int,void * __ptr64)` | 342 | Exported Function
`enum Csi::OfficeFileCacheStartResult __cdecl Csi::StartOfficeFileCache2(struct Csi::StartOfficeFileCacheArgs2 * __ptr64,struct Csi::IOfficeFileCache2 * __ptr64 * __ptr64,struct MsoCF::IError * __ptr64 * __ptr64)` | 323 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl Csi::ExtractWopiSrcFromWopiUrl(wchar_t const * __ptr64)` | 111 | Exported Function
`class Mso::TCntPtr<struct IUnknown> __cdecl Csi::Configuration::GetUnknown(enum Csi::Configuration::ConfigurationId)` | 225 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __cdecl ZipArchiveOnDictionary::CreateReadOnlyArchive(struct DocumentRevisionGraph::IImmutableDictionary & __ptr64)` | 82 | Exported Function
`class Mso::TCntPtr<struct IByteStream> __cdecl DocumentRevisionGraph::WrapIWriteStreamInIBS(struct DocumentRevisionGraph::IWriteStream & __ptr64)` | 345 | Exported Function
`class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __cdecl DocumentRevisionGraph::TryUnwrapIWriteStreamFromIBS(struct IByteStream & __ptr64)` | 331 | Exported Function
`class Mso::TCntPtr<struct IByteStream> __cdecl DocumentRevisionGraph::WrapIReadStreamInIBS(struct DocumentRevisionGraph::IReadStream & __ptr64)` | 344 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl Csi::Configuration::GetString(enum Csi::Configuration::ConfigurationId)` | 223 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __cdecl Csi::ConstructWopiUrl(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 33 | Exported Function
`class std::array<unsigned char,16> const __cdecl DocumentRevisionGraph::HashStringToDocumentId(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64)` | 245 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __cdecl ZipArchiveOnDictionary::CreateWriteArchive(struct DocumentRevisionGraph::IImmutableDictionaryBuilder & __ptr64,class Mso::Functor<class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __cdecl(void)>)` | 93 | Exported Function
`class Mso::TCntPtr<struct IZipArchive> __cdecl ZipArchiveOnDictionary::CreateWriteArchiveWithLookupDictionary(struct DocumentRevisionGraph::IImmutableDictionaryBuilder & __ptr64,struct DocumentRevisionGraph::IImmutableDictionary & __ptr64,class Mso::Functor<class Mso::TCntPtr<struct DocumentRevisionGraph::IWriteStream> __cdecl(void)>)` | 94 | Exported Function
`bool __cdecl Csi::GetServerInfoByFileUrl(struct IMsoUrl const * __ptr64,struct Csi::CsiServerInfo * __ptr64)` | 213 | Exported Function
`bool __cdecl Csi::Errors::IsCsiError(struct MsoCF::IError const * __ptr64,class Csi::CsiErrorCode)` | 256 | Exported Function
`bool __cdecl Csi::Errors::IsDependentRequestNotExecutedError(struct MsoCF::IError * __ptr64)` | 257 | Exported Function
`bool __cdecl Csi::Errors::IsCsiError(struct MsoCF::IError * __ptr64)` | 255 | Exported Function
`bool __cdecl Csi::Errors::IsCacheVersionError(struct MsoCF::IError * __ptr64)` | 253 | Exported Function
`bool __cdecl Csi::Errors::IsCoherencyError(struct MsoCF::IError * __ptr64)` | 254 | Exported Function
`bool __cdecl Csi::Errors::IsFallbackToLocalWorkingCopyOnOpenError(struct MsoCF::IError * __ptr64)` | 262 | Exported Function
`bool __cdecl Csi::Errors::IsFFMColdMismatchHRESULTError(struct MsoCF::IError * __ptr64)` | 258 | Exported Function
`bool __cdecl Csi::Errors::IsFallbackToHttpError(struct MsoCF::IError * __ptr64)` | 261 | Exported Function
`bool __cdecl Csi::Errors::IsFallBackOfflineError(struct MsoCF::IError * __ptr64)` | 259 | Exported Function
`bool __cdecl Csi::Errors::IsFallbackToDavError(struct MsoCF::IError * __ptr64)` | 260 | Exported Function
`bool __cdecl Csi::Errors::IsCacheCorruptionError(struct MsoCF::IError * __ptr64)` | 252 | Exported Function
`bool __cdecl Csi::AreEqualStreams(struct Csi::IReadStream * __ptr64,struct Csi::IReadStream * __ptr64)` | 22 | Exported Function
`bool __cdecl Csi::AreStreamAndAtomEqual(struct Csi::IReadStream * __ptr64,class MsoCF::IAtom * __ptr64)` | 23 | Exported Function
`bool __cdecl Csi::AreEqualSequentialStreams(struct Csi::ISequentialReadStream * __ptr64,struct Csi::ISequentialReadStream * __ptr64,unsigned int)` | 21 | Exported Function
`__int64 __cdecl Csi::Configuration::GetSignedInteger64(enum Csi::Configuration::ConfigurationId)` | 216 | Exported Function
`BeginEnsureCsiUninitializedEx` | 348 | Exported Function
`bool __cdecl Csi::Errors::AreEqualError(struct MsoCF::IError * __ptr64,struct MsoCF::IError * __ptr64)` | 20 | Exported Function
`bool __cdecl Csi::Errors::IsBaseDownloadError(struct MsoCF::IError const * __ptr64)` | 250 | Exported Function
`bool __cdecl Csi::CsiClientIsLoggingTraceTagSet(unsigned int)` | 97 | Exported Function
`bool __cdecl Csi::CanUseTransactedStream(wchar_t const * __ptr64,enum Csi::SyncBackedType,enum Csi::FileLocationType,bool)` | 30 | Exported Function
`bool __cdecl Csi::Configuration::GetBoolean(enum Csi::Configuration::ConfigurationId)` | 137 | Exported Function
`bool __cdecl Csi::Errors::IsFileCorruptionError(struct MsoCF::IError * __ptr64)` | 264 | Exported Function
`bool __cdecl Csi::FIsFileInCache(struct IMsoUrl const * __ptr64,struct Csi::CacheFileParams * __ptr64)` | 122 | Exported Function
`bool __cdecl Csi::FIsSpecializedKnowledgeEqual(struct Csi::ISpecializedKnowledge * __ptr64,struct Csi::ISpecializedKnowledge * __ptr64)` | 123 | Exported Function
`bool __cdecl Csi::FIsCurrentApplicationCoauthEnabled(void)` | 121 | Exported Function
`bool __cdecl Csi::FGetCsiFileFromPath2(wchar_t const * __ptr64,struct Csi::IOfficeFileCacheFile2 * __ptr64 * __ptr64,bool,bool * __ptr64,enum Csi::FileOpenState,struct Csi::CsiServerInfo const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64)` | 118 | Exported Function
`bool __cdecl Csi::FGetStreamOutermostSubsetOf(struct Csi::IReadStream * __ptr64,struct Csi::IReadStream * __ptr64 * __ptr64,struct Csi::FileChunkReference64 * __ptr64,bool * __ptr64)` | 120 | Exported Function
`bool __cdecl Csi::FTryDeserializeDataElementPackage(class Csi::CStreamObjectParser & __ptr64,struct CsiCell::IDataElementPackage * __ptr64 * __ptr64,class Csi::CSerialNumberMapper * __ptr64,struct CsiCell::IDataElementCallbacks * __ptr64)` | 128 | Exported Function
`bool __cdecl Csi::FTryDeserializeDataElementPackage(struct Csi::ISequentialReadStream * __ptr64,struct CsiCell::IDataElementPackage * __ptr64 * __ptr64,class Csi::CSerialNumberMapper * __ptr64,struct CsiCell::IDataElementCallbacks * __ptr64)` | 129 | Exported Function
`bool __cdecl Csi::FSyncLocalWorkingFileTime(wchar_t const * __ptr64)` | 127 | Exported Function
`bool __cdecl Csi::FOfficeFileCacheFolderValid(void)` | 125 | Exported Function
`bool __cdecl Csi::FPathInExplicitSubcache(wchar_t const * __ptr64)` | 126 | Exported Function
`bool __cdecl Csi::FGetCellKnowledge(struct Csi::IKnowledge * __ptr64,struct CsiCell::ICellKnowledge * __ptr64 * __ptr64)` | 117 | Exported Function
`bool __cdecl Csi::Errors::IsRecoverableEditorsTableSyncError(struct MsoCF::IError * __ptr64)` | 272 | Exported Function
`bool __cdecl Csi::Errors::IsRecoverableError(struct MsoCF::IError * __ptr64)` | 273 | Exported Function
`bool __cdecl Csi::Errors::IsInAppDownloadAuthenticationError(struct MsoCF::IError * __ptr64)` | 268 | Exported Function
`bool __cdecl Csi::Errors::IsFileOpenForEditTakenError(struct MsoCF::IError const * __ptr64)` | 266 | Exported Function
`bool __cdecl Csi::Errors::IsGetDocMetaInfoNotSupportedError(struct MsoCF::IError * __ptr64)` | 267 | Exported Function
`bool __cdecl Csi::Errors::IsUnresolvedUploadError(struct MsoCF::IError * __ptr64)` | 282 | Exported Function
`bool __cdecl Csi::FCobaltDisabled(void)` | 112 | Exported Function
`bool __cdecl Csi::Errors::IsServerOnlyAsyncOpenDownloadFailure(struct MsoCF::IError * __ptr64)` | 278 | Exported Function
`bool __cdecl Csi::Errors::IsRetryImmediatelyError(struct MsoCF::IError * __ptr64)` | 275 | Exported Function
`bool __cdecl Csi::Errors::IsRetryRaceConditionError(struct MsoCF::IError * __ptr64)` | 276 | Exported Function
`int __cdecl Csi::Configuration::GetSignedInteger32(enum Csi::Configuration::ConfigurationId)` | 215 | Exported Function
`public: virtual __cdecl Csi::CCellStorageRequestProcessor::~CCellStorageRequestProcessor(void) __ptr64` | 5 | Exported Function
`public: virtual __cdecl Csi::DocumentState::Listener::~Listener(void) __ptr64` | 7 | Exported Function
`public: unsigned int __cdecl Csi::CRevisionBuilder2::CountOfObjects(void) __ptr64` | 49 | Exported Function
`public: struct MsoCF::ExtendedGUID const & __ptr64 __cdecl Csi::CRevisionWriteObject2::GetObjectID(void) __ptr64` | 183 | Exported Function
`public: unsigned __int64 __cdecl Csi::CRevisionBuilder2::SizeOfObjectDataInBytes(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char) __ptr64` | 319 | Exported Function
`public: virtual struct _GUID __cdecl Csi::DocumentState::BroadcasterRegistration::RegisterListenerForDocument(wchar_t const * __ptr64,struct Csi::DocumentState::IListener * __ptr64) __ptr64` | 296 | Exported Function
`public: virtual void __cdecl Csi::DocumentState::BroadcasterRegistration::UnregisterDocumentListener(struct _GUID const & __ptr64) __ptr64` | 334 | Exported Function
`public: virtual bool __cdecl Csi::DocumentState::Listener::IsRegistered(void) __ptr64` | 274 | Exported Function
`public: virtual bool __cdecl Csi::DocumentState::BroadcasterRegistration::RegisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener * __ptr64) __ptr64` | 293 | Exported Function
`public: virtual bool __cdecl Csi::DocumentState::BroadcasterRegistration::RegisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener * __ptr64) __ptr64` | 295 | Exported Function
`public: static void __cdecl Csi::DocumentState::QueryFactory::CreateQueryDocument(wchar_t const * __ptr64,struct Csi::DocumentState::IQueryDocument * __ptr64 * __ptr64)` | 81 | Exported Function
`public: static void __cdecl Csi::DocumentState::Broadcaster::UnregisterDocumentListener(struct _GUID const & __ptr64)` | 333 | Exported Function
`public: static void __cdecl Csi::DocumentState::Broadcaster::UnregisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener * __ptr64)` | 335 | Exported Function
`public: static void __cdecl Csi::DocumentState::Broadcaster::RegisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener * __ptr64)` | 294 | Exported Function
`public: static void __cdecl Csi::CRevisionBuilder2::CreateInstance(struct CsiCell::ICellStorageLocal * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64,struct CsiCell::IRevision * __ptr64,bool,struct MsoCF::ExtendedGUID const & __ptr64,class Csi::CRevisionBuilder2 * __ptr64 * __ptr64)` | 67 | Exported Function
`public: static void __cdecl Csi::DocumentState::Broadcaster::RegisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener * __ptr64)` | 292 | Exported Function
`public: static void __cdecl Csi::DocumentState::QueryFactory::CreateQueryAllDocumentsNeedingAttention(struct Csi::DocumentState::IQuery * __ptr64 * __ptr64)` | 79 | Exported Function
`public: static void __cdecl Csi::DocumentState::QueryFactory::CreateQueryAllDocumentsWithErrors(struct Csi::DocumentState::IQuery * __ptr64 * __ptr64)` | 80 | Exported Function
`public: static void __cdecl Csi::DocumentState::Listener::SetRegistrationOverride_ForTesting(class Csi::DocumentState::BroadcasterRegistration * __ptr64)` | 315 | Exported Function
`public: static void __cdecl Csi::DocumentState::Broadcaster::UnregisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener * __ptr64)` | 337 | Exported Function
`public: static void __cdecl Csi::DocumentState::Listener::ResetRegistrationOverride_ForTesting(void)` | 299 | Exported Function
`public: virtual void __cdecl Csi::DocumentState::BroadcasterRegistration::UnregisterListenerForAllCachedFiles(struct Csi::DocumentState::IListener * __ptr64) __ptr64` | 336 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetRevisionID(struct MsoCF::ExtendedGUID * __ptr64) __ptr64` | 202 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetRootObject(struct MsoCF::ExtendedGUID const & __ptr64,struct MsoCF::ExtendedGUID * __ptr64) __ptr64` | 203 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetPartitions(struct MsoCF::ExtendedGUID const & __ptr64,class MsoCF::CArrayInBuffer<unsigned char> & __ptr64) __ptr64` | 187 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetObjectData(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char,struct Csi::IReadStream * __ptr64 * __ptr64) __ptr64` | 182 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetObjectReferences(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char,class MsoCF::CArrayInBuffer<struct MsoCF::ExtendedGUID> * __ptr64,class MsoCF::CArrayInBuffer<struct CsiCell::ContextAndCellID> * __ptr64) __ptr64` | 184 | Exported Function
`public: void __cdecl Csi::CRevisionManifestScaffold::AddRootObjectDeclaration(struct MsoCF::ExtendedGUID const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 16 | Exported Function
`public: void __cdecl Csi::CRevisionWriteObject2::FinishWrite(void) __ptr64` | 133 | Exported Function
`public: void __cdecl Csi::CRevisionManifestScaffold::AddObjectGroup(struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 12 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::GetWriteObject(struct MsoCF::ExtendedGUID const & __ptr64,class Csi::CRevisionWriteObject2 * __ptr64 * __ptr64,bool) __ptr64` | 232 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::SetRootObject(struct MsoCF::ExtendedGUID const & __ptr64,struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 316 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::EnumObjectIDs(struct CsiCell::IEnumObjectIDs * __ptr64 * __ptr64) __ptr64` | 110 | Exported Function
`public: void __cdecl Csi::CCellStorageSyncer::Sync(void) __ptr64` | 324 | Exported Function
`public: void __cdecl Csi::CDataElementPackage::AddDataElement(struct CsiCell::IDataElement * __ptr64) __ptr64` | 11 | Exported Function
`public: void __cdecl Csi::CCellStorageSyncer::Attach(struct CsiCell::ICellStorage * __ptr64,struct CsiCell::ICellStorage * __ptr64) __ptr64` | 24 | Exported Function
`public: virtual void __cdecl Csi::DocumentState::BroadcasterRegistration::UnregisterListenerForAllCachedFilesWithSyncStatusChanges(struct Csi::DocumentState::IListener * __ptr64) __ptr64` | 338 | Exported Function
`public: void __cdecl Csi::CCellManifestScaffold::SetCurrentRevision(struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 313 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::Commit(bool,bool * __ptr64,struct CsiCell::IRevision * __ptr64 * __ptr64) __ptr64` | 32 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::CreateWriteObject(class Csi::CRevisionWriteObject2 * __ptr64 * __ptr64,bool,struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 95 | Exported Function
`public: void __cdecl Csi::CRevisionBuilder2::Abort(void) __ptr64` | 8 | Exported Function
`public: void __cdecl Csi::CObjectGroupScaffold::AddObjectPartition(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char,enum CsiCell::ObjectChangeFrequency,struct MsoCF::ExtendedGUID const * __ptr64,unsigned int,struct CsiCell::ContextAndCellID const * __ptr64,unsigned int,struct Csi::IReadStream * __ptr64,struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 13 | Exported Function
`public: void __cdecl Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::Add(enum Csi::RevertToServerVersionBeforeFirstSaveDisabledReason) __ptr64` | 9 | Exported Function
`public: static struct _GUID const __cdecl Csi::DocumentState::Broadcaster::RegisterDocumentListener(wchar_t const * __ptr64,struct Csi::DocumentState::IListener * __ptr64)` | 291 | Exported Function
`public: __cdecl Csi::CCellStorageSyncer::~CCellStorageSyncer(void) __ptr64` | 6 | Exported Function
`public: __cdecl Csi::DocumentState::Listener::Listener(unsigned long,bool,class Mso::TCntPtr<class Csi::DocumentState::BroadcasterRegistration>) __ptr64` | 4 | Exported Function
`public: __cdecl Csi::CCellStorageSyncer::CCellStorageSyncer(void) __ptr64` | 2 | Exported Function
`protected: virtual void __cdecl Csi::CCellStorageRequestProcessor::SetLoggingContext(struct Csi::ILoggingContext * __ptr64) __ptr64` | 314 | Exported Function
`public: __cdecl Csi::CCellStorageRequestProcessor::CCellStorageRequestProcessor(void) __ptr64` | 1 | Exported Function
`public: bool __cdecl Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::Get(enum Csi::RevertToServerVersionBeforeFirstSaveDisabledReason) __ptr64` | 134 | Exported Function
`public: bool __cdecl Csi::CRevertToSerVerBeforeFirstSaveDisableReasons::IsRevertToSerVerBeforeFirstSaveDisabled(void)const __ptr64` | 277 | Exported Function
`public: bool __cdecl Csi::CLoggingSettings::IsTraceTagEnabled(unsigned int) __ptr64` | 281 | Exported Function
`public: bool __cdecl Csi::CLoggingSettings::IsLoggingLevelEnabled(enum Csi::CsiLoggingLevel) __ptr64` | 269 | Exported Function
`public: bool __cdecl Csi::CLoggingSettings::IsTraceEnabledAtLevel(unsigned int,enum Csi::CsiLoggingLevel) __ptr64` | 280 | Exported Function
`protected: __cdecl EditorInformation::EditorInformation(void) __ptr64` | 3 | Exported Function
`long __cdecl Csi::GetBroadcastSoap(struct Csi::BroadcastVersion,struct Csi::IBroadcastSoap * __ptr64 * __ptr64)` | 138 | Exported Function
`long __cdecl Csi::GetChangesSinceToken(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,int & __ptr64,int & __ptr64,int & __ptr64,wchar_t const * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveItemDescriptor> * __ptr64 * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64)` | 140 | Exported Function
`long __cdecl Csi::CsiHrMakeVersionRequest(struct Csi::ISoapWebService * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,enum VersionsSoapOp,class VersionsContext * __ptr64 * __ptr64,struct IAsyncSoapCallback * __ptr64)` | 99 | Exported Function
`int __cdecl Csi::FEnsureCsiInitialized(enum Csi::CsiApplicationEnum,bool,struct MsoCF::IError * __ptr64 * __ptr64,struct Csi::StartOfficeFileCacheArgs2 * __ptr64,wchar_t const * __ptr64)` | 114 | Exported Function
`long __cdecl Csi::BroadcastGetHostInfo(wchar_t const * __ptr64,wchar_t * __ptr64,struct Csi::BroadcastVersion * __ptr64,int,struct Csi::BroadcastVersion * __ptr64,wchar_t * __ptr64,int)` | 29 | Exported Function
`long __cdecl Csi::GetWebAccountInfo(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveLibraryDescriptor> * __ptr64 * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,struct Mso::Authentication::IOfficeIdentity * __ptr64)` | 231 | Exported Function
`long __cdecl Csi::HrDavUploadNewFile(wchar_t const * __ptr64,struct IStream * __ptr64,bool)` | 246 | Exported Function
`long __cdecl Csi::GetProductInfo(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,bool & __ptr64,bool & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wcha` | 189 | Exported Function
`long __cdecl Csi::GetItemInfo(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CIPtr<struct Csi::ISkyDriveLibraryDescriptor,struct Csi::ISkyDriveLibraryDescriptor> * __ptr64)` | 176 | Exported Function
`long __cdecl Csi::GetNotebooks(wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,wchar_t const * __ptr64,enum Csi::ISkyDriveNotebookDescriptor::QueryFilter,bool,bool & __ptr64,bool & __ptr64,bool & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveNotebookDescriptor> * __ptr64 * __ptr64,struct Csi::T_ISkyDriveList<struct Csi::ISkyDriveNotebookDescriptor> * __ptr64 * __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<struct MsoCF::WzTraits>,class MsoCF::CBuffer<wchar_t> > & __ptr64,class MsoCF::CWzInBuffer_T<class MsoCF::String<stru` | 181 | Exported Function
`public: bool __cdecl Csi::CRevisionBuilder2::FGetObjectData(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char,struct Csi::IReadStream * __ptr64 * __ptr64) __ptr64` | 119 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::GetDocument(struct Mso::UserStorage::IFile const & __ptr64)` | 154 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::GetDocumentFromUri(wchar_t const * __ptr64)` | 156 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::CreateNewDocumentAtServerUri(struct IMsoUrl const & __ptr64,wchar_t const * __ptr64,enum Csi::FileLocation)` | 73 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::CreateDocumentForSaveAs(struct Mso::UserStorage::IFile const & __ptr64)` | 60 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::CreateNewDocument(struct Mso::UserStorage::IFolder const & __ptr64,wchar_t const * __ptr64)` | 69 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiBrowse> __cdecl Csi::WopiBrowseFactory::GetIWopiBrowseForTestEnvironment(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::unique_ptr<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > >,struct std::default_delete<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > > >)` | 173 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiFileClient> __cdecl Csi::WopiFileClientFactory::GetIWopiFileClient(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class Mso::TCntPtr<class Mso::Async::IDispatchQueue> const & __ptr64)` | 174 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IWopiBrowse> __cdecl Csi::WopiBrowseFactory::GetIWopiBrowse(class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64,class std::unique_ptr<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > >,struct std::default_delete<class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > > >)` | 172 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::GetDocumentFromUriAndResourceID(wchar_t const * __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64)` | 157 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::GetDocumentFromUriAndVersion(wchar_t const * __ptr64,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const & __ptr64)` | 158 | Exported Function
`public: static class Mso::TCntPtr<struct Csi::IDocument> __cdecl Csi::DocumentFactory::CreateDocumentForSaveAs(struct IMsoUrl const & __ptr64)` | 61 | Exported Function
`public: class MsoCF::CArrayInBuffer<struct MsoCF::ExtendedGUID> & __ptr64 __cdecl Csi::CRevisionWriteObject2::ObjectReferences(unsigned char) __ptr64` | 287 | Exported Function
`public: static class Csi::CLoggingSettings * __ptr64 __cdecl Csi::CLoggingSettings::UseSingleton(void)` | 340 | Exported Function
`public: class MsoCF::CArrayInBuffer<struct CsiCell::ContextAndCellID> & __ptr64 __cdecl Csi::CRevisionWriteObject2::CellReferences(unsigned char) __ptr64` | 31 | Exported Function
`public: bool __cdecl Csi::CRevisionBuilder2::HasObject(struct MsoCF::ExtendedGUID const & __ptr64) __ptr64` | 243 | Exported Function
`public: bool __cdecl Csi::CRevisionBuilder2::HasReferences(struct MsoCF::ExtendedGUID const & __ptr64,unsigned char,bool * __ptr64,bool * __ptr64) __ptr64` | 244 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __cdecl Csi::DocumentFactory::CreateNewDocumentAsync(struct Mso::OfficeServicesManager::IConnectedService const & __ptr64,wchar_t const * __ptr64,enum Csi::FileLocation)` | 70 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __cdecl Csi::DocumentFactory::CreateNewDocumentAsync(struct Mso::UserStorage::IFolder const & __ptr64,wchar_t const * __ptr64)` | 71 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __cdecl Csi::DocumentFactory::CreateNewDocumentAsync(struct IMsoUrl const & __ptr64,wchar_t const * __ptr64,enum Csi::FileLocation)` | 72 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __cdecl Csi::DocumentFactory::CreateDocumentForSaveAsAsync(struct IMsoUrl const & __ptr64,enum Csi::FileLocation)` | 63 | Exported Function
`public: static class Mso::LegacyFuture<struct Csi::DocumentFactoryResult> __cdecl Csi::DocumentFactory::CreateDocumentForSaveAsAsync(struct Mso::UserStorage::IFile const & __ptr64)` | 62 | Exported Function


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
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/914f70a50949e494ceae550d871dd982d2f04111c7464e64ab37e7e64f710308/detection/




MIT License. Copyright (c) 2020 Strontic.


