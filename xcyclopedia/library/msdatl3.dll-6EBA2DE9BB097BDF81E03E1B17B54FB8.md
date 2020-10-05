---
title: msdatl3.dll | OLE DB Implementation Support Routines
excerpt: What is msdatl3.dll?
---

# msdatl3.dll 

* File Path: `C:\Program Files\Common Files\System\Ole DB\msdatl3.dll`
* Description: OLE DB Implementation Support Routines

## Hashes

Type | Hash
-- | --
MD5 | `6EBA2DE9BB097BDF81E03E1B17B54FB8`
SHA1 | `323F41B6B8EE19193D9E518E18D8087509A69C91`
SHA256 | `3757DA45FDF887B48C28284844F280C96D0C51D40A66213DE5001A8B571A2DFB`
SHA384 | `6B3485AAB189178ADD443C73D9034D34124BFC710099B84343526200416E8D22293E0C7B20A794975AEBEBC546EEA5B2`
SHA512 | `A5E29C3FF6ACC630A8964A586EDCF35CA0BBC62FA4D9451B9DC885DB1BB00F3A803553406A38A134B1A8653B5695DD4BE79A6518567380246C8562DBE51B837A`
SSDEEP | `3072:Zi/QhtPjMiqUyqEBzJclbVbfoiJV5f5LHHFE:NDjMdFJcv`
IMP | `150C026D59899221BDD1D565DA5F91BC`
PESHA1 | `17AE6BE10CF32D02582BBFAD9F5277F6B8F59258`
PE256 | `8314A307057ED858FBDBCB52EF132F77B38CC3A5C444D39C9665FA1E0C0A34DF`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual int __cdecl CHeapDispenser::CompareResource(void * __ptr64,void * __ptr64) __ptr64` | 179 | Exported Function
`public: virtual int __cdecl CHeapDispenser::HashKey(void * __ptr64,unsigned long,int * __ptr64) __ptr64` | 299 | Exported Function
`public: virtual int __cdecl CSlotListLong::FInit(unsigned __int64,class ISlotList * __ptr64 * __ptr64,class IHashTbl * __ptr64 * __ptr64,unsigned __int64) __ptr64` | 217 | Exported Function
`public: virtual __cdecl IBookmarkObj::~IBookmarkObj(void) __ptr64` | 86 | Exported Function
`public: virtual __cdecl IHashTbl::~IHashTbl(void) __ptr64` | 87 | Exported Function
`public: virtual __cdecl ISlotList::~ISlotList(void) __ptr64` | 88 | Exported Function
`public: virtual long __cdecl CClassFactory::LockServer(int) __ptr64` | 319 | Exported Function
`public: virtual long __cdecl CClassFactory::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 333 | Exported Function
`public: virtual long __cdecl CEnumConnectionPoints::Clone(struct IEnumConnectionPoints * __ptr64 * __ptr64) __ptr64` | 174 | Exported Function
`public: virtual int __cdecl CSlotListShort::FInit(unsigned __int64,class ISlotList * __ptr64 * __ptr64,class IHashTbl * __ptr64 * __ptr64,unsigned __int64) __ptr64` | 218 | Exported Function
`public: virtual int __cdecl CUtlProps2::ConflictsWithCurrent(unsigned long,unsigned long,struct tagVARIANT const & __ptr64) __ptr64` | 182 | Exported Function
`public: virtual int __cdecl CUtlProps2::FIsValidColId(struct tagDBPROP * __ptr64) __ptr64` | 224 | Exported Function
`public: virtual __cdecl CUtlPropsFastLookup2::~CUtlPropsFastLookup2(void) __ptr64` | 84 | Exported Function
`public: virtual __cdecl CBaseObj::~CBaseObj(void) __ptr64` | 66 | Exported Function
`public: virtual __cdecl CBaseObjBoko::~CBaseObjBoko(void) __ptr64` | 67 | Exported Function
`public: virtual __cdecl CBaseObjZombie::~CBaseObjZombie(void) __ptr64` | 68 | Exported Function
`public: unsigned short __cdecl CUtlProps2::GetExpectedVarType(unsigned long,unsigned long) __ptr64` | 249 | Exported Function
`public: unsigned short __cdecl CWString::operator[](int)const __ptr64` | 123 | Exported Function
`public: unsigned short const * __ptr64 __cdecl CUtlProps2::GetValString(unsigned long,unsigned long) __ptr64` | 297 | Exported Function
`public: virtual __cdecl CSlotListShort::~CSlotListShort(void) __ptr64` | 81 | Exported Function
`public: virtual __cdecl CUtlPropInfo::~CUtlPropInfo(void) __ptr64` | 82 | Exported Function
`public: virtual __cdecl CUtlProps2::~CUtlProps2(void) __ptr64` | 83 | Exported Function
`public: virtual __cdecl CHashTbl::~CHashTbl(void) __ptr64` | 76 | Exported Function
`public: virtual __cdecl CHashTblAggr::~CHashTblAggr(void) __ptr64` | 77 | Exported Function
`public: virtual __cdecl CSlotListLong::~CSlotListLong(void) __ptr64` | 80 | Exported Function
`public: virtual long __cdecl CEnumConnectionPoints::Next(unsigned long,struct IConnectionPoint * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 324 | Exported Function
`public: virtual long __cdecl CHeapDispenser::ResetResource(void * __ptr64) __ptr64` | 365 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::Advise(struct IUnknown * __ptr64,unsigned long * __ptr64) __ptr64` | 161 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::EnumConnections(struct IEnumConnections * __ptr64 * __ptr64) __ptr64` | 209 | Exported Function
`public: virtual long __cdecl CHeapDispenser::DestroyResource(void * __ptr64) __ptr64` | 201 | Exported Function
`public: virtual long __cdecl CHeapDispenser::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 337 | Exported Function
`public: virtual long __cdecl CHeapDispenser::RateRes(void * __ptr64,unsigned long,void * __ptr64,int * __ptr64) __ptr64` | 340 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::Unadvise(unsigned long) __ptr64` | 416 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPointContainer::EnumConnectionPoints(struct IEnumConnectionPoints * __ptr64 * __ptr64) __ptr64` | 208 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPointContainer::FindConnectionPoint(struct _GUID const & __ptr64,struct IConnectionPoint * __ptr64 * __ptr64) __ptr64` | 226 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::GetConnectionInterface(struct _GUID * __ptr64) __ptr64` | 243 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::GetConnectionPointContainer(struct IConnectionPointContainer * __ptr64 * __ptr64) __ptr64` | 244 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPoint::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 338 | Exported Function
`public: virtual long __cdecl CHeapDispenser::CreateResource(void * __ptr64,unsigned long,void * __ptr64,void * __ptr64 * __ptr64,int * __ptr64) __ptr64` | 193 | Exported Function
`public: virtual long __cdecl CEnumConnections::Clone(struct IEnumConnections * __ptr64 * __ptr64) __ptr64` | 175 | Exported Function
`public: virtual long __cdecl CEnumConnections::Next(unsigned long,struct tagCONNECTDATA * __ptr64,unsigned long * __ptr64) __ptr64` | 325 | Exported Function
`public: virtual long __cdecl CEnumConnections::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 336 | Exported Function
`public: virtual long __cdecl CEnumConnectionPoints::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 335 | Exported Function
`public: virtual long __cdecl CEnumConnectionPoints::Reset(void) __ptr64` | 360 | Exported Function
`public: virtual long __cdecl CEnumConnectionPoints::Skip(unsigned long) __ptr64` | 413 | Exported Function
`public: virtual long __cdecl CHashTbl::InsertFindBmk(int,unsigned __int64,unsigned __int64,unsigned char * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 302 | Exported Function
`public: virtual long __cdecl CHashTblAggr::DeleteBmk(unsigned __int64) __ptr64` | 198 | Exported Function
`public: virtual long __cdecl CHashTblAggr::InsertFindBmk(int,unsigned __int64,unsigned __int64,unsigned char * __ptr64,unsigned __int64 * __ptr64) __ptr64` | 303 | Exported Function
`public: virtual long __cdecl CEnumConnections::Reset(void) __ptr64` | 361 | Exported Function
`public: virtual long __cdecl CEnumConnections::Skip(unsigned long) __ptr64` | 414 | Exported Function
`public: virtual long __cdecl CHashTbl::DeleteBmk(unsigned __int64) __ptr64` | 197 | Exported Function
`public: unsigned short * __ptr64 __cdecl CWString::GetBufferSetLength(int) __ptr64` | 241 | Exported Function
`public: long __cdecl CUtlProps2::GetPropertiesArgChk(unsigned long,struct tagDBPROPIDSET const * __ptr64 const,unsigned long * __ptr64,struct tagDBPROPSET * __ptr64 * __ptr64) __ptr64` | 276 | Exported Function
`public: long __cdecl CUtlProps2::GetPropValue(struct _GUID const * __ptr64,unsigned long,struct tagVARIANT * __ptr64) __ptr64` | 273 | Exported Function
`public: long __cdecl CUtlProps2::GetValLong(unsigned long,unsigned long)const __ptr64` | 294 | Exported Function
`public: long __cdecl CUtlProps2::FillDefaultValues(unsigned long) __ptr64` | 225 | Exported Function
`public: long __cdecl CUtlProps2::GetProperties(unsigned long,struct tagDBPROPIDSET const * __ptr64 const,unsigned long * __ptr64,struct tagDBPROPSET * __ptr64 * __ptr64) __ptr64` | 274 | Exported Function
`public: long __cdecl CUtlProps2::GetProperties(unsigned long,struct tagDBPROPIDSET const * __ptr64 const,unsigned long * __ptr64,struct tagDBPROPSET * __ptr64 * __ptr64,struct _GUID const * __ptr64) __ptr64` | 275 | Exported Function
`public: short __cdecl CUtlProps2::GetValBool(unsigned long,unsigned long)const __ptr64` | 292 | Exported Function
`public: short __cdecl CUtlProps2::GetValShort(unsigned long,unsigned long)const __ptr64` | 296 | Exported Function
`public: short __cdecl CUtlProps2::OkToPersistSensitiveAuthInfo(void) __ptr64` | 332 | Exported Function
`public: long __cdecl CUtlProps2::SetProperties(unsigned long,struct tagDBPROPSET const * __ptr64 const,int) __ptr64` | 393 | Exported Function
`public: long __cdecl CUtlProps2::SetPropValue(struct _GUID const * __ptr64,unsigned long,struct tagVARIANT * __ptr64) __ptr64` | 392 | Exported Function
`public: long __cdecl CUtlProps2::SetVariant(unsigned long,unsigned long,struct tagVARIANT * __ptr64) __ptr64` | 411 | Exported Function
`public: long __cdecl CUtlProps2::CopyUPropVal(unsigned long,struct tagUPROPVAL * __ptr64,class CColumnIds * __ptr64) __ptr64` | 190 | Exported Function
`public: long __cdecl CGenericPooler::GetResource(void * __ptr64 * __ptr64,struct IGPHolder * __ptr64,struct IGPDispenser * __ptr64,void * __ptr64 * __ptr64,void * __ptr64) __ptr64` | 282 | Exported Function
`public: long __cdecl CRowsetConnectionPoint::DoNotify(enum DBREASONENUM,enum DBEVENTPHASEENUM,enum ENOTIFICATIONTYPE,struct IRowset * __ptr64,union tagNOTIFYARGS * __ptr64) __ptr64` | 203 | Exported Function
`public: long __cdecl CRowsetConnectionPointContainer::DoFcNotify(unsigned long,enum DBREASONENUM,enum DBEVENTPHASEENUM,struct IRowset * __ptr64,unsigned __int64,unsigned __int64,unsigned __int64 * __ptr64 const) __ptr64` | 202 | Exported Function
`public: long __cdecl CExtBuffer::ReplaceInExtBuffer(unsigned __int64,unsigned __int64,void const * __ptr64,unsigned __int64) __ptr64` | 357 | Exported Function
`public: long __cdecl CExtBuffer::WriteIntoExtBuffer(void const * __ptr64,unsigned __int64) __ptr64` | 417 | Exported Function
`public: long __cdecl CExtBuffer::WriteWCharToExtBuffer(unsigned short,unsigned __int64) __ptr64` | 418 | Exported Function
`public: long __cdecl CUtlPropInfo::FInit(void) __ptr64` | 219 | Exported Function
`public: long __cdecl CUtlPropInfo::GetPropertyInfo(unsigned long,struct tagDBPROPIDSET const * __ptr64 const,unsigned long * __ptr64,struct tagDBPROPINFOSET * __ptr64 * __ptr64,unsigned short * __ptr64 * __ptr64) __ptr64` | 277 | Exported Function
`public: long __cdecl CUtlProps2::ConvertRowsetIIDtoDBPROPSET(struct _GUID const * __ptr64,struct tagDBPROPSET * __ptr64) __ptr64` | 183 | Exported Function
`public: long __cdecl CRowsetConnectionPointContainer::DoRcNotify(unsigned long,enum DBREASONENUM,enum DBEVENTPHASEENUM,struct IRowset * __ptr64,unsigned __int64,unsigned __int64 * __ptr64 const) __ptr64` | 204 | Exported Function
`public: long __cdecl CRowsetConnectionPointContainer::DoRscNotify(unsigned long,enum DBREASONENUM,enum DBEVENTPHASEENUM,struct IRowset * __ptr64) __ptr64` | 205 | Exported Function
`public: long __cdecl CRowsetConnectionPointContainer::Init(void) __ptr64` | 300 | Exported Function
`public: static long __cdecl CUtlProps2::SetPropertiesArgChk(unsigned long,struct tagDBPROPSET const * __ptr64 const)` | 394 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetPropID(unsigned long,unsigned long) __ptr64` | 270 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetPropOption(unsigned long,unsigned long) __ptr64` | 271 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetPropStatus(struct tagUPROPVAL * __ptr64) __ptr64` | 272 | Exported Function
`public: unsigned long __cdecl CEnum::Release(void) __ptr64` | 344 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetInternalFlags(unsigned long,unsigned long) __ptr64` | 256 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetInternalStatus(unsigned long,unsigned long) __ptr64` | 257 | Exported Function
`public: unsigned short * __ptr64 __cdecl CBaseObj::GetBaseObjectTypeName(void) __ptr64` | 237 | Exported Function
`public: unsigned short * __ptr64 __cdecl CExtBuffer::GetNameFromOffset(unsigned __int64) __ptr64` | 264 | Exported Function
`public: unsigned short * __ptr64 __cdecl CWString::GetBuffer(int) __ptr64` | 240 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetStatus(unsigned long,unsigned long) __ptr64` | 285 | Exported Function
`public: unsigned long __cdecl CUtlProps2::GetUPropSetCount(void) __ptr64` | 289 | Exported Function
`public: unsigned long __cdecl CWString::NumElements(unsigned short * __ptr64 const)const __ptr64` | 330 | Exported Function
`public: unsigned long __cdecl CEnum::AddRef(void) __ptr64` | 153 | Exported Function
`public: struct IUnknown * __ptr64 __cdecl CBaseObj::GetOuterUnknown(void) __ptr64` | 269 | Exported Function
`public: struct tagCONNECTDATA * __ptr64 __cdecl CConnectData::GetCd(void) __ptr64` | 242 | Exported Function
`public: struct tagVARIANT * __ptr64 __cdecl CUtlProps2::GetVariant(unsigned long,unsigned long) __ptr64` | 298 | Exported Function
`public: static unsigned long __cdecl CHashTbl::CbHashTblSize(unsigned long)` | 168 | Exported Function
`public: struct _GUID const * __ptr64 __cdecl CUtlProps2::GetGuid(unsigned long) __ptr64` | 250 | Exported Function
`public: struct IGPHolder * __ptr64 __cdecl CGenericPooler::GetHeapHolder(void) __ptr64` | 252 | Exported Function
`public: unsigned __int64 __cdecl CExtBuffer::GetItemSize(void)const __ptr64` | 261 | Exported Function
`public: unsigned char * __ptr64 __cdecl CExtBuffer::AllocItems(unsigned __int64) __ptr64` | 164 | Exported Function
`public: unsigned long * __ptr64 __cdecl CUtlProps2::GetPropsInErrorPtr(void) __ptr64` | 279 | Exported Function
`public: unsigned __int64 __cdecl CExtBuffer::GetDWORDOfExtBuffer(unsigned __int64) __ptr64` | 248 | Exported Function
`public: unsigned __int64 __cdecl CExtBuffer::GetItemCount(void)const __ptr64` | 258 | Exported Function
`public: unsigned __int64 __cdecl CExtBuffer::GetItemMax(void)const __ptr64` | 259 | Exported Function
`public: virtual long __cdecl CRowsetConnectionPointContainer::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 339 | Exported Function
`public: void __cdecl CUtlProps2::ClearPropSupported(unsigned long,unsigned long) __ptr64` | 171 | Exported Function
`public: void __cdecl CUtlProps2::CopyAvailUPropSets(unsigned long * __ptr64,struct tagUPROPSET const * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 184 | Exported Function
`public: void __cdecl CUtlProps2::CopyPropsInError(class CUtlProps2 * __ptr64) __ptr64` | 187 | Exported Function
`public: void __cdecl CUtlProps2::AddInternalFlags(unsigned long,unsigned long,unsigned long) __ptr64` | 151 | Exported Function
`public: void __cdecl CUtlProps2::ClearPropertyInError(void) __ptr64` | 172 | Exported Function
`public: void __cdecl CUtlProps2::ClearPropsSupported(void) __ptr64` | 173 | Exported Function
`public: void __cdecl CUtlProps2::RemoveInternalFlags(unsigned long,unsigned long,unsigned long) __ptr64` | 355 | Exported Function
`public: void __cdecl CUtlProps2::RestoreInternalFlags(unsigned long,unsigned long) __ptr64` | 368 | Exported Function
`public: void __cdecl CUtlProps2::RestoreInternalStatus(unsigned long,unsigned long) __ptr64` | 369 | Exported Function
`public: void __cdecl CUtlProps2::CopyPropsInError(unsigned long * __ptr64) __ptr64` | 186 | Exported Function
`public: void __cdecl CUtlProps2::CopyUPropInfo(unsigned long,struct tagUPROPINFO * __ptr64 * __ptr64) __ptr64` | 188 | Exported Function
`public: void __cdecl CUtlProps2::CopyUPropSetsSupported(unsigned long * __ptr64) __ptr64` | 189 | Exported Function
`public: void __cdecl CUtlProps2::``default constructor closure'(void) __ptr64` | 148 | Exported Function
`public: void __cdecl CExtBuffer::DeleteWithCompactFromExtBuffer(unsigned __int64) __ptr64` | 200 | Exported Function
`public: void __cdecl CExtBuffer::Free(void) __ptr64` | 231 | Exported Function
`public: void __cdecl CExtBuffer::GetItemOfExtBuffer(unsigned __int64,void * __ptr64) __ptr64` | 260 | Exported Function
`public: void __cdecl CConnectData::ForgetReason(enum DBREASONENUM) __ptr64` | 229 | Exported Function
`public: void __cdecl CExtBuffer::CompactExtBuffer(void) __ptr64` | 176 | Exported Function
`public: void __cdecl CExtBuffer::DeleteFromExtBuffer(unsigned __int64) __ptr64` | 199 | Exported Function
`public: void __cdecl CGenericPooler::FInitializeGPStructures(void) __ptr64` | 222 | Exported Function
`public: void __cdecl CGenericPooler::ReleaseHolders(void) __ptr64` | 351 | Exported Function
`public: void __cdecl CGenericPooler::ReleaseResource(void * __ptr64,struct IGPHolder * __ptr64,struct IGPDispenser * __ptr64,void * __ptr64) __ptr64` | 352 | Exported Function
`public: void __cdecl CExtBuffer::GetLastItemHandle(unsigned __int64 & __ptr64) __ptr64` | 262 | Exported Function
`public: void __cdecl CExtBuffer::SetItemCount(unsigned __int64) __ptr64` | 384 | Exported Function
`public: void __cdecl CExtBuffer::Transfer(class CExtBuffer * __ptr64) __ptr64` | 415 | Exported Function
`public: void __cdecl CUtlProps2::SaveInternalFlags(unsigned long,unsigned long) __ptr64` | 375 | Exported Function
`public: void __cdecl CWString::ClearError(void) __ptr64` | 169 | Exported Function
`public: void __cdecl CWString::ConcatInPlace(int,unsigned short const * __ptr64) __ptr64` | 181 | Exported Function
`public: void __cdecl CWString::Empty(void) __ptr64` | 207 | Exported Function
`public: void __cdecl CUtlProps2::SetValLongLong(unsigned long,unsigned long,__int64) __ptr64` | 408 | Exported Function
`public: void __cdecl CUtlProps2::SetValShort(unsigned long,unsigned long,short) __ptr64` | 409 | Exported Function
`public: void __cdecl CUtlPropsFastLookup2::``default constructor closure'(void) __ptr64` | 149 | Exported Function
`public: void __cdecl CWString::SetAt(int,unsigned short) __ptr64` | 379 | Exported Function
`public: void __cdecl CWString::SetError(void) __ptr64` | 382 | Exported Function
`void __cdecl FreeDBIDs(struct tagDBID * __ptr64)` | 232 | Exported Function
`public: void __cdecl CWString::FreeExtra(void) __ptr64` | 233 | Exported Function
`public: void __cdecl CWString::ReleaseBuffer(int) __ptr64` | 350 | Exported Function
`public: void __cdecl CWString::ReplaceAt(int,int,unsigned short const * __ptr64,int) __ptr64` | 356 | Exported Function
`public: void __cdecl CUtlProps2::SetValLong(unsigned long,unsigned long,long) __ptr64` | 407 | Exported Function
`public: void __cdecl CUtlProps2::SetPropertyStatus(unsigned long,struct tagDBPROPSET const * __ptr64 const) __ptr64` | 397 | Exported Function
`public: void __cdecl CUtlProps2::SetPropOption(unsigned long,unsigned long,unsigned long) __ptr64` | 389 | Exported Function
`public: void __cdecl CUtlProps2::SetPropRequired(unsigned long,unsigned long,short) __ptr64` | 390 | Exported Function
`public: void __cdecl CUtlProps2::SaveInternalStatus(unsigned long,unsigned long) __ptr64` | 376 | Exported Function
`public: void __cdecl CUtlProps2::SetInternalStatus(unsigned long,unsigned long,unsigned long) __ptr64` | 383 | Exported Function
`public: void __cdecl CUtlProps2::SetPropertyInError(unsigned long,unsigned long) __ptr64` | 396 | Exported Function
`public: void __cdecl CUtlProps2::SetValBool(unsigned long,unsigned long,short) __ptr64` | 404 | Exported Function
`public: void __cdecl CUtlProps2::SetValByRef(unsigned long,unsigned long,void * __ptr64) __ptr64` | 405 | Exported Function
`public: void __cdecl CUtlProps2::SetValEmpty(unsigned long,unsigned long) __ptr64` | 406 | Exported Function
`public: void __cdecl CUtlProps2::SetPropSupported(unsigned long,unsigned long) __ptr64` | 391 | Exported Function
`public: void __cdecl CUtlProps2::SetStatus(unsigned long,unsigned long,unsigned long) __ptr64` | 401 | Exported Function
`public: void __cdecl CUtlProps2::SetUPropSetCount(unsigned long) __ptr64` | 403 | Exported Function
`public: void __cdecl CConnectData::ForgetEvent(enum DBREASONENUM,enum DBEVENTPHASEENUM) __ptr64` | 227 | Exported Function
`public: virtual long __cdecl CUtlPropsFastLookup2::FInit(class CUtlPropsFastLookup2 * __ptr64) __ptr64` | 221 | Exported Function
`public: virtual struct tagRowBuff * __ptr64 __cdecl CSlotListLong::GetRowBuff(unsigned __int64) __ptr64` | 283 | Exported Function
`public: virtual struct tagRowBuff * __ptr64 __cdecl CSlotListShort::GetRowBuff(unsigned __int64) __ptr64` | 284 | Exported Function
`public: virtual long __cdecl CUtlProps2::SetCombinedPassThrough(struct tagDBPROPSET const * __ptr64,unsigned long) __ptr64` | 381 | Exported Function
`public: virtual long __cdecl CUtlProps2::SetPassThrough(struct tagDBPROPSET const * __ptr64) __ptr64` | 385 | Exported Function
`public: virtual long __cdecl CUtlProps2::SetValString(unsigned long,unsigned long,unsigned short const * __ptr64) __ptr64` | 410 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListShort::CountOfBusySlots(void) __ptr64` | 192 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListShort::ReleaseSlots(unsigned __int64,unsigned __int64) __ptr64` | 354 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListShort::SLSlotCapacity(void) __ptr64` | 372 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListLong::CountOfBusySlots(void) __ptr64` | 191 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListLong::ReleaseSlots(unsigned __int64,unsigned __int64) __ptr64` | 353 | Exported Function
`public: virtual unsigned __int64 __cdecl CSlotListLong::SLSlotCapacity(void) __ptr64` | 371 | Exported Function
`public: virtual long __cdecl CUtlProps2::SecureSetValue(unsigned long,unsigned long,struct tagVARIANT * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 378 | Exported Function
`public: virtual long __cdecl CSlotListLong::NoBusySlots(void) __ptr64` | 328 | Exported Function
`public: virtual long __cdecl CSlotListShort::GetNextSlots(unsigned __int64,unsigned __int64,unsigned __int64 * __ptr64) __ptr64` | 266 | Exported Function
`public: virtual long __cdecl CSlotListShort::IsValidSlot(unsigned __int64) __ptr64` | 314 | Exported Function
`public: virtual long __cdecl CSlotListLong::GetNextSlots(unsigned __int64,unsigned __int64,unsigned __int64 * __ptr64) __ptr64` | 265 | Exported Function
`public: virtual long __cdecl CSlotListLong::IsValidSlot(unsigned __int64) __ptr64` | 313 | Exported Function
`public: virtual long __cdecl CSlotListLong::NextBusySlot(unsigned __int64 * __ptr64) __ptr64` | 326 | Exported Function
`public: virtual long __cdecl CUtlProps2::GetIndexofPropIdinPropSet(unsigned long,unsigned long,unsigned long * __ptr64) __ptr64` | 253 | Exported Function
`public: virtual long __cdecl CUtlProps2::GetIndexofPropSet(struct _GUID const * __ptr64,unsigned long * __ptr64) __ptr64` | 255 | Exported Function
`public: virtual long __cdecl CUtlProps2::SecureGetValue(unsigned long,unsigned long,struct tagVARIANT * __ptr64,struct tagVARIANT * __ptr64) __ptr64` | 377 | Exported Function
`public: virtual long __cdecl CSlotListShort::NextBusySlot(unsigned __int64 * __ptr64) __ptr64` | 327 | Exported Function
`public: virtual long __cdecl CSlotListShort::NoBusySlots(void) __ptr64` | 329 | Exported Function
`public: virtual long __cdecl CUtlProps2::FInit(class CUtlProps2 * __ptr64) __ptr64` | 220 | Exported Function
`public: virtual unsigned long __cdecl CClassFactory::AddRef(void) __ptr64` | 152 | Exported Function
`public: void * __ptr64 __cdecl CExtBuffer::GetPtrOfExtBuffer(void) __ptr64` | 280 | Exported Function
`public: void * __ptr64 __cdecl CUtlProps2::GetValByRef(unsigned long,unsigned long)const __ptr64` | 293 | Exported Function
`public: void __cdecl CBaseObjBoko::GetTimestamp(unsigned long * __ptr64) __ptr64` | 286 | Exported Function
`public: virtual void __cdecl CSlotListShort::RecordInternalUse(void) __ptr64` | 342 | Exported Function
`public: virtual void __cdecl CSlotListShort::ResetBusySlotIteration(void) __ptr64` | 364 | Exported Function
`public: void * __ptr64 __cdecl CExtBuffer::GetPtrOfExtBuffer(unsigned __int64) __ptr64` | 281 | Exported Function
`public: void __cdecl CBitArray::ResetAllSlots(void) __ptr64` | 362 | Exported Function
`public: void __cdecl CBitArray::ResetSlot(unsigned __int64) __ptr64` | 366 | Exported Function
`public: void __cdecl CBitArray::ResetSlots(unsigned __int64,unsigned __int64) __ptr64` | 367 | Exported Function
`public: void __cdecl CBaseObjBoko::MakeZombies(void) __ptr64` | 320 | Exported Function
`public: void __cdecl CBaseObjZombie::GetBokoTimestamp(void) __ptr64` | 239 | Exported Function
`public: void __cdecl CBaseObjZombie::SetBoko(class CBaseObjBoko * __ptr64) __ptr64` | 380 | Exported Function
`public: virtual void __cdecl CSlotListLong::ResetBusySlotIteration(void) __ptr64` | 363 | Exported Function
`public: virtual unsigned long __cdecl CEnumConnections::AddRef(void) __ptr64` | 155 | Exported Function
`public: virtual unsigned long __cdecl CEnumConnections::Release(void) __ptr64` | 346 | Exported Function
`public: virtual unsigned long __cdecl CHeapDispenser::AddRef(void) __ptr64` | 156 | Exported Function
`public: virtual unsigned long __cdecl CClassFactory::Release(void) __ptr64` | 343 | Exported Function
`public: virtual unsigned long __cdecl CEnumConnectionPoints::AddRef(void) __ptr64` | 154 | Exported Function
`public: virtual unsigned long __cdecl CEnumConnectionPoints::Release(void) __ptr64` | 345 | Exported Function
`public: virtual unsigned long __cdecl CRowsetConnectionPointContainer::AddRef(void) __ptr64` | 158 | Exported Function
`public: virtual unsigned long __cdecl CRowsetConnectionPointContainer::Release(void) __ptr64` | 349 | Exported Function
`public: virtual void __cdecl CSlotListLong::RecordInternalUse(void) __ptr64` | 341 | Exported Function
`public: virtual unsigned long __cdecl CHeapDispenser::Release(void) __ptr64` | 347 | Exported Function
`public: virtual unsigned long __cdecl CRowsetConnectionPoint::AddRef(void) __ptr64` | 157 | Exported Function
`public: virtual unsigned long __cdecl CRowsetConnectionPoint::Release(void) __ptr64` | 348 | Exported Function
`public: long __cdecl CExtBuffer::InsertIntoExtBuffer(void * __ptr64,unsigned __int64 & __ptr64) __ptr64` | 304 | Exported Function
`public: __cdecl CEnum::~CEnum(void) __ptr64` | 72 | Exported Function
`public: __cdecl CEnumConnectionPoints::CEnumConnectionPoints(class CEnumConnectionPoints const & __ptr64) __ptr64` | 23 | Exported Function
`public: __cdecl CEnumConnectionPoints::CEnumConnectionPoints(struct IUnknown * __ptr64,unsigned long,struct IConnectionPoint * __ptr64 * __ptr64) __ptr64` | 24 | Exported Function
`public: __cdecl CConnectData::CConnectData(void) __ptr64` | 21 | Exported Function
`public: __cdecl CConnectData::~CConnectData(void) __ptr64` | 71 | Exported Function
`public: __cdecl CEnum::CEnum(struct IUnknown * __ptr64,unsigned long,void * __ptr64 * __ptr64,struct _GUID,unsigned __int64,unsigned long,enum CENUMTYPE) __ptr64` | 22 | Exported Function
`public: __cdecl CEnumConnections::~CEnumConnections(void) __ptr64` | 74 | Exported Function
`public: __cdecl CExtBuffer::CExtBuffer(void) __ptr64` | 27 | Exported Function
`public: __cdecl CExtBuffer::~CExtBuffer(void) __ptr64` | 75 | Exported Function
`public: __cdecl CEnumConnectionPoints::~CEnumConnectionPoints(void) __ptr64` | 73 | Exported Function
`public: __cdecl CEnumConnections::CEnumConnections(class CEnumConnections const & __ptr64) __ptr64` | 25 | Exported Function
`public: __cdecl CEnumConnections::CEnumConnections(struct IUnknown * __ptr64,struct tagCONNECTDATA * __ptr64,unsigned long) __ptr64` | 26 | Exported Function
`public: __cdecl CClassFactory::~CClassFactory(void) __ptr64` | 70 | Exported Function
`protected: void __cdecl CWString::AssignCopy(int,unsigned short const * __ptr64) __ptr64` | 166 | Exported Function
`protected: void __cdecl CWString::ConcatCopy(int,unsigned short const * __ptr64,int,unsigned short const * __ptr64) __ptr64` | 180 | Exported Function
`protected: void __cdecl CWString::Init(void) __ptr64` | 301 | Exported Function
`protected: void __cdecl CUtlPropInfo::SetUPropSetCount(unsigned long) __ptr64` | 402 | Exported Function
`protected: void __cdecl CWString::AllocBuffer(int) __ptr64` | 162 | Exported Function
`protected: void __cdecl CWString::AllocCopy(class CWString & __ptr64,int,int,int)const __ptr64` | 163 | Exported Function
`public: __cdecl CBitArray::~CBitArray(void) __ptr64` | 69 | Exported Function
`public: __cdecl CClassFactory::CClassFactory(class CClassFactory const & __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl CClassFactory::CClassFactory(long * __ptr64,long * __ptr64) __ptr64` | 20 | Exported Function
`public: __cdecl CBaseObjBoko::CBaseObjBoko(enum EBaseObjectType,long * __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl CBaseObjZombie::CBaseObjZombie(enum EBaseObjectType,long * __ptr64) __ptr64` | 16 | Exported Function
`public: __cdecl CBitArray::CBitArray(void) __ptr64` | 17 | Exported Function
`public: __cdecl CGenericPooler::CGenericPooler(class CGenericPooler && __ptr64) __ptr64` | 28 | Exported Function
`public: __cdecl CSlotListLong::CSlotListLong(void) __ptr64` | 43 | Exported Function
`public: __cdecl CSlotListShort::CSlotListShort(class CSlotListShort const & __ptr64) __ptr64` | 44 | Exported Function
`public: __cdecl CSlotListShort::CSlotListShort(void) __ptr64` | 45 | Exported Function
`public: __cdecl CRowsetConnectionPointContainer::CRowsetConnectionPointContainer(struct IUnknown * __ptr64) __ptr64` | 41 | Exported Function
`public: __cdecl CRowsetConnectionPointContainer::~CRowsetConnectionPointContainer(void) __ptr64` | 79 | Exported Function
`public: __cdecl CSlotListLong::CSlotListLong(class CSlotListLong const & __ptr64) __ptr64` | 42 | Exported Function
`public: __cdecl CUtlProps2::CUtlProps2(unsigned long) __ptr64` | 49 | Exported Function
`public: __cdecl CUtlPropsFastLookup2::CUtlPropsFastLookup2(class CUtlPropsFastLookup2 && __ptr64) __ptr64` | 50 | Exported Function
`public: __cdecl CUtlPropsFastLookup2::CUtlPropsFastLookup2(class CUtlPropsFastLookup2 const & __ptr64) __ptr64` | 51 | Exported Function
`public: __cdecl CUtlPropInfo::CUtlPropInfo(class CUtlPropInfo const & __ptr64) __ptr64` | 46 | Exported Function
`public: __cdecl CUtlPropInfo::CUtlPropInfo(void) __ptr64` | 47 | Exported Function
`public: __cdecl CUtlProps2::CUtlProps2(class CUtlProps2 const & __ptr64) __ptr64` | 48 | Exported Function
`public: __cdecl CRowsetConnectionPointContainer::CRowsetConnectionPointContainer(class CRowsetConnectionPointContainer const & __ptr64) __ptr64` | 40 | Exported Function
`public: __cdecl CHashTbl::CHashTbl(void) __ptr64` | 32 | Exported Function
`public: __cdecl CHashTblAggr::CHashTblAggr(class CHashTblAggr const & __ptr64) __ptr64` | 33 | Exported Function
`public: __cdecl CHashTblAggr::CHashTblAggr(void) __ptr64` | 34 | Exported Function
`public: __cdecl CGenericPooler::CGenericPooler(class CGenericPooler const & __ptr64) __ptr64` | 29 | Exported Function
`public: __cdecl CGenericPooler::CGenericPooler(void) __ptr64` | 30 | Exported Function
`public: __cdecl CHashTbl::CHashTbl(class CHashTbl const & __ptr64) __ptr64` | 31 | Exported Function
`public: __cdecl CRowsetConnectionPoint::CRowsetConnectionPoint(class CRowsetConnectionPoint const & __ptr64) __ptr64` | 38 | Exported Function
`public: __cdecl CRowsetConnectionPoint::CRowsetConnectionPoint(struct IUnknown * __ptr64,struct _GUID const * __ptr64,unsigned long) __ptr64` | 39 | Exported Function
`public: __cdecl CRowsetConnectionPoint::~CRowsetConnectionPoint(void) __ptr64` | 78 | Exported Function
`public: __cdecl CHeapDispenser::CHeapDispenser(class CHeapDispenser && __ptr64) __ptr64` | 35 | Exported Function
`public: __cdecl CHeapDispenser::CHeapDispenser(class CHeapDispenser const & __ptr64) __ptr64` | 36 | Exported Function
`public: __cdecl CHeapDispenser::CHeapDispenser(void) __ptr64` | 37 | Exported Function
`protected: virtual unsigned long __cdecl CUtlPropsFastLookup2::GetUPropValIndex(unsigned long,unsigned long) __ptr64` | 291 | Exported Function
`const IBookmarkObj::``vftable'` | 145 | Exported Function
`const IHashTbl::``vftable'` | 146 | Exported Function
`const ISlotList::``vftable'` | 147 | Exported Function
`const CUtlPropInfo::``vftable'` | 142 | Exported Function
`const CUtlProps2::``vftable'` | 143 | Exported Function
`const CUtlPropsFastLookup2::``vftable'` | 144 | Exported Function
`long __cdecl CopyDBIDs(struct tagDBID * __ptr64,struct tagDBID const * __ptr64)` | 185 | Exported Function
`long __cdecl CreateVLHeap(struct IVLHeap * __ptr64 * __ptr64)` | 194 | Exported Function
`long __cdecl LoadResourceDLL(unsigned short * __ptr64,unsigned short * __ptr64,void * __ptr64,void * __ptr64 * __ptr64)` | 317 | Exported Function
`DllMain` | 12 | Exported Function
`int __cdecl OLEDBGetCharTypeW(unsigned long,unsigned short,unsigned short * __ptr64)` | 331 | Exported Function
`long __cdecl CompareDBIDs(struct tagDBID const * __ptr64,struct tagDBID const * __ptr64)` | 178 | Exported Function
`const CSlotListShort::``vftable'` | 141 | Exported Function
`const CClassFactory::``vftable'` | 132 | Exported Function
`const CEnumConnectionPoints::``vftable'` | 133 | Exported Function
`const CEnumConnections::``vftable'` | 134 | Exported Function
`const CBaseObj::``vftable'` | 129 | Exported Function
`const CBaseObjBoko::``vftable'` | 130 | Exported Function
`const CBaseObjZombie::``vftable'` | 131 | Exported Function
`const CRowsetConnectionPoint::``vftable'` | 138 | Exported Function
`const CRowsetConnectionPointContainer::``vftable'` | 139 | Exported Function
`const CSlotListLong::``vftable'` | 140 | Exported Function
`const CHashTbl::``vftable'` | 135 | Exported Function
`const CHashTblAggr::``vftable'` | 136 | Exported Function
`const CHeapDispenser::``vftable'` | 137 | Exported Function
`private: __cdecl CClassFactory::CClassFactory(void) __ptr64` | 18 | Exported Function
`private: void __cdecl CUtlProps2::RetrieveColumnIdProps(struct tagDBPROP * __ptr64,struct tagUPROPVAL * __ptr64,unsigned long * __ptr64) __ptr64` | 370 | Exported Function
`protected: __cdecl CBaseObj::CBaseObj(enum EBaseObjectType,long * __ptr64) __ptr64` | 13 | Exported Function
`protected: __cdecl CBaseObj::CBaseObj(enum EBaseObjectType,struct IUnknown * __ptr64,long * __ptr64,bool) __ptr64` | 14 | Exported Function
`private: void __cdecl CSlotListShort::DecoupleSlot(struct tagSLOT * __ptr64) __ptr64` | 196 | Exported Function
`private: void __cdecl CUtlProps2::ClearMemberVars(void) __ptr64` | 170 | Exported Function
`private: void __cdecl CUtlProps2::FreeMemory(void) __ptr64` | 234 | Exported Function
`protected: unsigned long __cdecl CUtlPropInfo::GetUPropSetCount(void) __ptr64` | 288 | Exported Function
`protected: virtual long __cdecl CUtlPropsFastLookup2::GetIndexofPropIdinPropSet(unsigned long,unsigned long,unsigned long * __ptr64) __ptr64` | 254 | Exported Function
`protected: virtual unsigned long __cdecl CUtlProps2::GetUPropValIndex(unsigned long,unsigned long) __ptr64` | 290 | Exported Function
`protected: long __cdecl CBaseObj::FInit(void) __ptr64` | 210 | Exported Function
`protected: static int __cdecl CWString::SafeStrlen(unsigned short const * __ptr64)` | 374 | Exported Function
`protected: static void __cdecl CWString::SafeDelete(unsigned short * __ptr64)` | 373 | Exported Function
`private: void __cdecl CSlotListShort::AddSlotToList(struct tagSLOT * __ptr64) __ptr64` | 159 | Exported Function
`private: static unsigned long __cdecl CHashTbl::AdjustRange(unsigned long)` | 160 | Exported Function
`private: static unsigned long const * const CUtlProps2::sm_rgPropStatusFromInternStatus` | 426 | Exported Function
`private: struct IUnknown * __ptr64 __cdecl CEnum::GetNthUnknown(unsigned long) __ptr64` | 268 | Exported Function
`private: long __cdecl CUtlPropInfo::GetPropertySetIndex(struct _GUID const * __ptr64) __ptr64` | 278 | Exported Function
`private: long __cdecl CUtlPropInfo::GetUPropInfoPtr(unsigned long,unsigned long,struct tagUPROPINFO * __ptr64 * __ptr64) __ptr64` | 287 | Exported Function
`private: long __cdecl CUtlProps2::SetProperty(unsigned long,unsigned long,struct tagDBPROP * __ptr64) __ptr64` | 395 | Exported Function
`private: void * __ptr64 __cdecl CEnum::GetNthElement(unsigned long) __ptr64` | 267 | Exported Function
`private: void __cdecl CRowsetConnectionPoint::ForgetEvent(enum DBREASONENUM,enum DBEVENTPHASEENUM) __ptr64` | 228 | Exported Function
`private: void __cdecl CRowsetConnectionPoint::SetReasons(void) __ptr64` | 398 | Exported Function
`private: unsigned long __cdecl CUtlPropInfo::CalcDescripBuffers(unsigned long,struct tagDBPROPINFOSET * __ptr64) __ptr64` | 167 | Exported Function
`private: unsigned long __cdecl CUtlProps2::GetCountofColids(struct tagUPROP * __ptr64) __ptr64` | 245 | Exported Function
`private: unsigned long __cdecl CUtlProps2::GetCountofWritablePropsInPropSet(unsigned long) __ptr64` | 246 | Exported Function
`public: __cdecl CUtlPropsFastLookup2::CUtlPropsFastLookup2(unsigned long) __ptr64` | 52 | Exported Function
`public: int __cdecl CExtBuffer::FInit(class CExtBuffer * __ptr64) __ptr64` | 212 | Exported Function
`public: int __cdecl CExtBuffer::FInit(unsigned __int64,unsigned __int64) __ptr64` | 213 | Exported Function
`public: int __cdecl CExtBuffer::FInit(unsigned __int64,void * __ptr64,unsigned __int64,unsigned __int64) __ptr64` | 214 | Exported Function
`public: int __cdecl CBitArray::fGetCopyOf(class CBitArray * __ptr64) __ptr64` | 421 | Exported Function
`public: int __cdecl CConnectData::fOkToFire(enum DBREASONENUM,enum DBEVENTPHASEENUM) __ptr64` | 423 | Exported Function
`public: int __cdecl CConnectData::Reset(void) __ptr64` | 358 | Exported Function
`public: int __cdecl CRowsetConnectionPoint::fInit(void) __ptr64` | 422 | Exported Function
`public: int __cdecl CRowsetConnectionPoint::fReasonNeeded(enum DBREASONENUM,enum DBEVENTPHASEENUM) __ptr64` | 424 | Exported Function
`public: int __cdecl CRowsetConnectionPointContainer::fReasonNeeded(unsigned long,enum DBREASONENUM,enum DBEVENTPHASEENUM) __ptr64` | 425 | Exported Function
`public: int __cdecl CHashTbl::FInit(unsigned short,class CSlotListShort * __ptr64,class IBookmarkObj * __ptr64) __ptr64` | 215 | Exported Function
`public: int __cdecl CHashTblAggr::AddHashTbl(class CSlotListShort * __ptr64) __ptr64` | 150 | Exported Function
`public: int __cdecl CHashTblAggr::FInit(class CHashTbl * __ptr64) __ptr64` | 216 | Exported Function
`public: int __cdecl CBaseObjZombie::ZombieMustUnprepare(void) __ptr64` | 420 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(unsigned short) __ptr64` | 116 | Exported Function
`public: class IBookmarkObj & __ptr64 __cdecl IBookmarkObj::operator=(class IBookmarkObj const & __ptr64) __ptr64` | 120 | Exported Function
`public: class IHashTbl & __ptr64 __cdecl IHashTbl::operator=(class IHashTbl const & __ptr64) __ptr64` | 121 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(class CWString const & __ptr64) __ptr64` | 114 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(unsigned char const * __ptr64) __ptr64` | 118 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(unsigned short const * __ptr64) __ptr64` | 119 | Exported Function
`public: int __cdecl CBaseObjBoko::IsZombie(unsigned long) __ptr64` | 315 | Exported Function
`public: int __cdecl CBaseObjBoko::ZombieMustUnprepare(void) __ptr64` | 419 | Exported Function
`public: int __cdecl CBaseObjZombie::IsZombie(void) __ptr64` | 316 | Exported Function
`public: class ISlotList & __ptr64 __cdecl ISlotList::operator=(class ISlotList const & __ptr64) __ptr64` | 122 | Exported Function
`public: enum EBaseObjectType __cdecl CBaseObj::GetBaseObjectType(void) __ptr64` | 236 | Exported Function
`public: int __cdecl CBaseObj::GetBidID(void) __ptr64` | 238 | Exported Function
`public: int __cdecl CUtlProps2::FIsDefaultValue(unsigned long,unsigned long,struct tagVARIANT * __ptr64) __ptr64` | 223 | Exported Function
`public: long __cdecl CBitArray::SetSlots(unsigned __int64,unsigned __int64) __ptr64` | 400 | Exported Function
`public: long __cdecl CEnum::Next(unsigned long,void * __ptr64 * __ptr64,unsigned long * __ptr64) __ptr64` | 323 | Exported Function
`public: long __cdecl CEnum::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64,struct IUnknown * __ptr64) __ptr64` | 334 | Exported Function
`public: long __cdecl CBitArray::FInit(unsigned __int64) __ptr64` | 211 | Exported Function
`public: long __cdecl CBitArray::IsSlotSet(unsigned __int64) __ptr64` | 311 | Exported Function
`public: long __cdecl CBitArray::SetSlot(unsigned __int64) __ptr64` | 399 | Exported Function
`public: long __cdecl CEnumConnectionPoints::SetPos(unsigned long) __ptr64` | 387 | Exported Function
`public: long __cdecl CEnumConnections::SetPos(unsigned long) __ptr64` | 388 | Exported Function
`public: long __cdecl CExtBuffer::DWORDIntoExtBuffer(unsigned __int64) __ptr64` | 195 | Exported Function
`public: long __cdecl CEnum::Reset(void) __ptr64` | 359 | Exported Function
`public: long __cdecl CEnum::SetPos(unsigned long) __ptr64` | 386 | Exported Function
`public: long __cdecl CEnum::Skip(unsigned long) __ptr64` | 412 | Exported Function
`public: long __cdecl CBitArray::ArrayEmpty(void) __ptr64` | 165 | Exported Function
`public: int __cdecl CUtlProps2::IsRequiredTrue(unsigned long,unsigned long) __ptr64` | 309 | Exported Function
`public: int __cdecl CUtlProps2::IsSetIfCan(unsigned long,unsigned long) __ptr64` | 310 | Exported Function
`public: int __cdecl CUtlProps2::IsTrue(unsigned long,unsigned long) __ptr64` | 312 | Exported Function
`public: int __cdecl CUtlProps2::IsEmpty(unsigned long,unsigned long) __ptr64` | 305 | Exported Function
`public: int __cdecl CUtlProps2::IsPropSet(struct _GUID const * __ptr64,unsigned long) __ptr64` | 307 | Exported Function
`public: int __cdecl CUtlProps2::IsRequiredFalse(unsigned long,unsigned long) __ptr64` | 308 | Exported Function
`public: int __cdecl CWString::GetLength(void)const __ptr64` | 263 | Exported Function
`public: int __cdecl CWString::IsEmpty(void)const __ptr64` | 306 | Exported Function
`public: int __cdecl CWString::LoadStringW(void * __ptr64,unsigned int) __ptr64` | 318 | Exported Function
`public: int __cdecl CWString::Compare(unsigned short const * __ptr64)const __ptr64` | 177 | Exported Function
`public: int __cdecl CWString::FoundError(void)const __ptr64` | 230 | Exported Function
`public: int __cdecl CWString::GetAllocLength(void)const __ptr64` | 235 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(char) __ptr64` | 115 | Exported Function
`public: class CBaseObj & __ptr64 __cdecl CBaseObj::operator=(class CBaseObj const & __ptr64) __ptr64` | 89 | Exported Function
`public: class CBaseObjBoko & __ptr64 __cdecl CBaseObjBoko::operator=(class CBaseObjBoko const & __ptr64) __ptr64` | 90 | Exported Function
`public: class CBaseObjZombie & __ptr64 __cdecl CBaseObjZombie::operator=(class CBaseObjZombie const & __ptr64) __ptr64` | 91 | Exported Function
`public: __cdecl ISlotList::ISlotList(class ISlotList const & __ptr64) __ptr64` | 64 | Exported Function
`public: __cdecl ISlotList::ISlotList(void) __ptr64` | 65 | Exported Function
`public: __int64 __cdecl CUtlProps2::GetValLongLong(unsigned long,unsigned long)const __ptr64` | 295 | Exported Function
`public: class CConnectData & __ptr64 __cdecl CConnectData::operator=(class CConnectData const & __ptr64) __ptr64` | 95 | Exported Function
`public: class CCriticalSection * __ptr64 * __ptr64 __cdecl CBaseObj::GetCriticalSection(void) __ptr64` | 247 | Exported Function
`public: class CEnum & __ptr64 __cdecl CEnum::operator=(class CEnum const & __ptr64) __ptr64` | 96 | Exported Function
`public: class CBitArray & __ptr64 __cdecl CBitArray::operator=(class CBitArray const & __ptr64) __ptr64` | 92 | Exported Function
`public: class CClassFactory & __ptr64 __cdecl CClassFactory::operator=(class CClassFactory const & __ptr64) __ptr64` | 93 | Exported Function
`public: class CConnectData & __ptr64 __cdecl CConnectData::operator=(class CConnectData && __ptr64) __ptr64` | 94 | Exported Function
`public: __cdecl IHashTbl::IHashTbl(void) __ptr64` | 63 | Exported Function
`public: __cdecl CWString::CWString(unsigned short const * __ptr64) __ptr64` | 57 | Exported Function
`public: __cdecl CWString::CWString(unsigned short const * __ptr64,int) __ptr64` | 58 | Exported Function
`public: __cdecl CWString::CWString(unsigned short,int) __ptr64` | 54 | Exported Function
`public: __cdecl CWString::CWString(char const * __ptr64) __ptr64` | 55 | Exported Function
`public: __cdecl CWString::CWString(class CWString const & __ptr64) __ptr64` | 53 | Exported Function
`public: __cdecl CWString::CWString(unsigned char const * __ptr64) __ptr64` | 56 | Exported Function
`public: __cdecl IBookmarkObj::IBookmarkObj(class IBookmarkObj const & __ptr64) __ptr64` | 60 | Exported Function
`public: __cdecl IBookmarkObj::IBookmarkObj(void) __ptr64` | 61 | Exported Function
`public: __cdecl IHashTbl::IHashTbl(class IHashTbl const & __ptr64) __ptr64` | 62 | Exported Function
`public: __cdecl CWString::CWString(void) __ptr64` | 59 | Exported Function
`public: __cdecl CWString::operator unsigned short const * __ptr64(void)const __ptr64` | 124 | Exported Function
`public: __cdecl CWString::~CWString(void) __ptr64` | 85 | Exported Function
`public: class CEnumConnectionPoints & __ptr64 __cdecl CEnumConnectionPoints::operator=(class CEnumConnectionPoints const & __ptr64) __ptr64` | 97 | Exported Function
`public: class CUtlPropsFastLookup2 & __ptr64 __cdecl CUtlPropsFastLookup2::operator=(class CUtlPropsFastLookup2 const & __ptr64) __ptr64` | 113 | Exported Function
`public: class CWString __cdecl CWString::ElementAt(unsigned short * __ptr64 const,int)const __ptr64` | 206 | Exported Function
`public: class CWString __cdecl CWString::Mid(int)const __ptr64` | 321 | Exported Function
`public: class CUtlPropInfo & __ptr64 __cdecl CUtlPropInfo::operator=(class CUtlPropInfo const & __ptr64) __ptr64` | 110 | Exported Function
`public: class CUtlProps2 & __ptr64 __cdecl CUtlProps2::operator=(class CUtlProps2 const & __ptr64) __ptr64` | 111 | Exported Function
`public: class CUtlPropsFastLookup2 & __ptr64 __cdecl CUtlPropsFastLookup2::operator=(class CUtlPropsFastLookup2 && __ptr64) __ptr64` | 112 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator+=(unsigned short const * __ptr64) __ptr64` | 128 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator+=(unsigned short) __ptr64` | 127 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator=(char const * __ptr64) __ptr64` | 117 | Exported Function
`public: class CWString __cdecl CWString::Mid(int,int)const __ptr64` | 322 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator+=(char) __ptr64` | 126 | Exported Function
`public: class CWString const & __ptr64 __cdecl CWString::operator+=(class CWString const & __ptr64) __ptr64` | 125 | Exported Function
`public: class CSlotListShort & __ptr64 __cdecl CSlotListShort::operator=(class CSlotListShort const & __ptr64) __ptr64` | 109 | Exported Function
`public: class CGenericPooler & __ptr64 __cdecl CGenericPooler::operator=(class CGenericPooler const & __ptr64) __ptr64` | 101 | Exported Function
`public: class CHashTbl & __ptr64 __cdecl CHashTbl::operator=(class CHashTbl const & __ptr64) __ptr64` | 102 | Exported Function
`public: class CHashTblAggr & __ptr64 __cdecl CHashTblAggr::operator=(class CHashTblAggr const & __ptr64) __ptr64` | 103 | Exported Function
`public: class CEnumConnections & __ptr64 __cdecl CEnumConnections::operator=(class CEnumConnections const & __ptr64) __ptr64` | 98 | Exported Function
`public: class CExtBuffer & __ptr64 __cdecl CExtBuffer::operator=(class CExtBuffer const & __ptr64) __ptr64` | 99 | Exported Function
`public: class CGenericPooler & __ptr64 __cdecl CGenericPooler::operator=(class CGenericPooler && __ptr64) __ptr64` | 100 | Exported Function
`public: class CRowsetConnectionPoint & __ptr64 __cdecl CRowsetConnectionPoint::operator=(class CRowsetConnectionPoint const & __ptr64) __ptr64` | 106 | Exported Function
`public: class CRowsetConnectionPointContainer & __ptr64 __cdecl CRowsetConnectionPointContainer::operator=(class CRowsetConnectionPointContainer const & __ptr64) __ptr64` | 107 | Exported Function
`public: class CSlotListLong & __ptr64 __cdecl CSlotListLong::operator=(class CSlotListLong const & __ptr64) __ptr64` | 108 | Exported Function
`public: class CHeapDispenser & __ptr64 __cdecl CHeapDispenser::operator=(class CHeapDispenser && __ptr64) __ptr64` | 104 | Exported Function
`public: class CHeapDispenser & __ptr64 __cdecl CHeapDispenser::operator=(class CHeapDispenser const & __ptr64) __ptr64` | 105 | Exported Function
`public: class CHeapDispenser * __ptr64 __cdecl CGenericPooler::GetHeapDispenser(void) __ptr64` | 251 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: msdatl3.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: Language Neutral
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/3757da45fdf887b48c28284844f280c96d0c51d40a66213de5001a8b571a2dfb/detection/




MIT License. Copyright (c) 2020 Strontic.


