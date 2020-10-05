---
title: ulib.dll | File Utilities Support DLL
excerpt: What is ulib.dll?
---

# ulib.dll 

* File Path: `C:\Windows\SysWOW64\ulib.dll`
* Description: File Utilities Support DLL

## Hashes

Type | Hash
-- | --
MD5 | `7127419B5A2BAD800E5B03051A7AB976`
SHA1 | `0F0811BA150BF1ACE78A8D0DDF1756A6C99D34E5`
SHA256 | `8CE6869F6756383ADB8922087C97028CA206CABADAC2B87912135C4EC2B458F5`
SHA384 | `13BAA1B1E7D00FC348E5A05AB57D6B7B17351378379688FD0D1637CEB1E878111ACC03A7D8ED4A37F740ACC2536FF22C`
SHA512 | `B0FE0DBB37C82682B8ED2530EAB3A97B2A7FAC48AD937BC8789B9EF58FC25E575D79A74CF8C30411366F48DCD0063397D4BA37DF8556C109EE0EC21537BEE2D7`
SSDEEP | `3072:TjXYquM6EoncIwVNXxWdpHXBowX/QmhpupM:TjXYquM6EqcIwVbWdpHXxv1`
IMP | `A2D2D148511C20DA7ACC289291BB7CBE`
PESHA1 | `DFC78AF311EC29180815A8A8FB266157EF2E6E27`
PE256 | `76A9BD1D6CB13B482184E372DC26C8405A3E6549669DC4EF1BAA38330EFF3EF0`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char __thiscall TIMEINFO_ARGUMENT::Initialize(char *)` | 233 | Exported Function
`public: unsigned char __thiscall WSTRING::Initialize(char const *,unsigned long)` | 235 | Exported Function
`public: unsigned char __thiscall WSTRING::Initialize(class WSTRING const *,unsigned long,unsigned long)` | 237 | Exported Function
`public: unsigned char __thiscall TIMEINFO::QueryTime(class WSTRING *)const ` | 341 | Exported Function
`public: unsigned char __thiscall TIMEINFO::operator<(class TIMEINFO)const ` | 96 | Exported Function
`public: unsigned char __thiscall TIMEINFO::operator>(class TIMEINFO)const ` | 99 | Exported Function
`public: unsigned char __thiscall TIMEINFO::QueryDate(class WSTRING *)const ` | 303 | Exported Function
`public: unsigned char __thiscall WSTRING::operator!=(class WSTRING const &)const ` | 95 | Exported Function
`public: unsigned char __thiscall WSTRING::operator<(class WSTRING const &)const ` | 97 | Exported Function
`public: unsigned char __thiscall WSTRING::operator<=(class WSTRING const &)const ` | 98 | Exported Function
`public: unsigned char __thiscall WSTRING::InsertString(unsigned long,class WSTRING const *,unsigned long,unsigned long)` | 241 | Exported Function
`public: unsigned char __thiscall WSTRING::Initialize(long)` | 234 | Exported Function
`public: unsigned char __thiscall WSTRING::Initialize(unsigned short const *,unsigned long)` | 236 | Exported Function
`public: unsigned char __thiscall WSTRING::Initialize(void)` | 238 | Exported Function
`public: unsigned char __thiscall TIMEINFO::Initialize(void)` | 231 | Exported Function
`public: unsigned char __thiscall STRING_ARGUMENT::Initialize(char *)` | 227 | Exported Function
`public: unsigned char __thiscall STRING_ARRAY::Initialize(unsigned long,unsigned long,unsigned long)` | 228 | Exported Function
`public: unsigned char __thiscall SVILOGFILES::DeleteOldest(void)` | 145 | Exported Function
`public: unsigned char __thiscall STREAM_MESSAGE::Initialize(class STREAM *,class STREAM *,class STREAM *)` | 226 | Exported Function
`public: unsigned char __thiscall STREAM::ReadMbLine(char *,unsigned long,unsigned long *,unsigned char,unsigned long)` | 349 | Exported Function
`public: unsigned char __thiscall STREAM::ReadWLine(unsigned short *,unsigned long,unsigned long *,unsigned char,unsigned long)` | 350 | Exported Function
`public: unsigned char __thiscall STREAM::WriteByte(unsigned char)` | 456 | Exported Function
`public: unsigned char __thiscall TIMEINFO::ConvertToLocal(void)` | 132 | Exported Function
`public: unsigned char __thiscall TIMEINFO::ConvertToUTC(void)` | 133 | Exported Function
`public: unsigned char __thiscall TIMEINFO::Initialize(struct _FILETIME *)` | 230 | Exported Function
`public: unsigned char __thiscall SVILOGFILES::ShiftLogs(unsigned short const *)` | 407 | Exported Function
`public: unsigned char __thiscall SVILOGFILES::GetHandleNewLogFile(void * *)` | 180 | Exported Function
`public: unsigned char __thiscall SVILOGFILES::Initialize(unsigned short const *,unsigned short const *,unsigned short const *,unsigned long)` | 229 | Exported Function
`public: unsigned char __thiscall SVILOGFILES::NewLogFileName(class WSTRING *)` | 276 | Exported Function
`public: unsigned long __thiscall WSTRING::Strrchr(unsigned short,unsigned long)const ` | 436 | Exported Function
`public: unsigned long __thiscall WSTRING::Strspn(class WSTRING const *,unsigned long)const ` | 437 | Exported Function
`public: unsigned long __thiscall WSTRING::Strstr(class WSTRING const *)const ` | 439 | Exported Function
`public: unsigned long __thiscall WSTRING::Strcspn(class WSTRING const *,unsigned long)const ` | 428 | Exported Function
`public: unsigned long __thiscall WSTRING::QueryByteCount(void)const ` | 295 | Exported Function
`public: unsigned long __thiscall WSTRING::QueryChCount(void)const ` | 298 | Exported Function
`public: unsigned long __thiscall WSTRING::Strchr(unsigned short,unsigned long)const ` | 419 | Exported Function
`public: unsigned short __thiscall WSTRING::QueryChAt(unsigned long)const ` | 296 | Exported Function
`public: unsigned short __thiscall WSTRING::SetChAt(unsigned short,unsigned long)` | 381 | Exported Function
`public: unsigned short const * __thiscall WSTRING::GetWSTR(void)const ` | 189 | Exported Function
`public: unsigned short * __thiscall WSTRING::QueryWSTR(unsigned long,unsigned long,unsigned short *,unsigned long,unsigned char)const ` | 345 | Exported Function
`public: unsigned long __thiscall WSTRING::SyncLength(void)` | 442 | Exported Function
`public: unsigned long __thiscall WSTRING::Truncate(unsigned long)` | 445 | Exported Function
`public: unsigned short * __thiscall WSTRING::GetWSTRNonConst(void)` | 190 | Exported Function
`public: unsigned long __thiscall SCREEN::QueryCodePage(void)` | 300 | Exported Function
`public: unsigned char __thiscall WSTRING::Replace(unsigned long,unsigned long,class WSTRING const *,unsigned long,unsigned long)` | 354 | Exported Function
`public: unsigned char __thiscall WSTRING::ReplaceWithChars(unsigned long,unsigned long,unsigned short,unsigned long)` | 356 | Exported Function
`public: unsigned char __thiscall WSTRING::Split(class ARRAY *,class WSTRING const *,unsigned char)const ` | 412 | Exported Function
`public: unsigned char __thiscall WSTRING::QueryNumber(long *,unsigned long,unsigned long)const ` | 326 | Exported Function
`public: unsigned char __thiscall WSTRING::operator==(class WSTRING const &)const ` | 94 | Exported Function
`public: unsigned char __thiscall WSTRING::operator>(class WSTRING const &)const ` | 100 | Exported Function
`public: unsigned char __thiscall WSTRING::operator>=(class WSTRING const &)const ` | 101 | Exported Function
`public: unsigned long __thiscall BSTRING::QueryChCount(void)const ` | 297 | Exported Function
`public: unsigned long __thiscall BSTRING::Strchr(char,unsigned long)const ` | 418 | Exported Function
`public: unsigned long __thiscall OBJECT::QueryClassId(void)const ` | 299 | Exported Function
`public: unsigned long __thiscall BSTRING::NextChar(unsigned long)` | 277 | Exported Function
`public: unsigned char __thiscall WSTRING::Strcat(class WSTRING const *)` | 417 | Exported Function
`public: unsigned char __thiscall WSTRING::Strcat(unsigned short const *)` | 416 | Exported Function
`public: unsigned long __thiscall BITVECTOR::SetSize(unsigned long,enum BIT)` | 402 | Exported Function
`public: unsigned char __thiscall STREAM::ReadLine(class WSTRING *,unsigned char)` | 348 | Exported Function
`public: unsigned char __thiscall MESSAGE::DumpDataToLog(void *,unsigned long)` | 159 | Exported Function
`public: unsigned char __thiscall MESSAGE::Initialize(void)` | 215 | Exported Function
`public: unsigned char __thiscall MESSAGE::IsLoggingEnabled(void)` | 251 | Exported Function
`public: unsigned char __thiscall MESSAGE::DisplayMsg(unsigned long,enum MESSAGE_TYPE,unsigned long)` | 154 | Exported Function
`public: unsigned char __thiscall MEM_BLOCK_MGR::Free(void *)` | 174 | Exported Function
`public: unsigned char __thiscall MEM_BLOCK_MGR::Initialize(unsigned long,unsigned long)` | 214 | Exported Function
`public: unsigned char __thiscall MESSAGE::DisplayMsg(unsigned long)` | 153 | Exported Function
`public: unsigned char __thiscall MESSAGE::QueryPackedLog(class HMEM *,unsigned long *)` | 327 | Exported Function
`public: unsigned char __thiscall MESSAGE::SetLogOnly(unsigned char)` | 392 | Exported Function
`public: unsigned char __thiscall MULTIPLE_PATH_ARGUMENT::Initialize(char *,unsigned char,unsigned char)` | 216 | Exported Function
`public: unsigned char __thiscall MESSAGE::QueryNextLoggedMessage(class FSTRING *)` | 325 | Exported Function
`public: unsigned char __thiscall MESSAGE::LogMessage(class WSTRING const *)` | 263 | Exported Function
`public: unsigned char __thiscall MESSAGE::LogMsg(unsigned long)` | 265 | Exported Function
`public: unsigned char __thiscall MESSAGE::LogOnly(void)` | 266 | Exported Function
`public: unsigned char __thiscall MEM_ALLOCATOR::Initialize(unsigned __int64,unsigned long)` | 213 | Exported Function
`public: unsigned char __thiscall KEYBOARD::EnableLineMode(void)` | 161 | Exported Function
`public: unsigned char __thiscall KEYBOARD::Flush(void)` | 173 | Exported Function
`public: unsigned char __thiscall KEYBOARD::Initialize(unsigned char,unsigned char)` | 209 | Exported Function
`public: unsigned char __thiscall KEYBOARD::DisableLineMode(void)` | 147 | Exported Function
`public: unsigned char __thiscall FSNODE::WorkOnReparsePoint(unsigned char)` | 455 | Exported Function
`public: unsigned char __thiscall HMEM::Initialize(void)` | 208 | Exported Function
`public: unsigned char __thiscall HMEM::Resize(unsigned long,unsigned long)` | 363 | Exported Function
`public: unsigned char __thiscall MACHINE::Initialize(void)` | 212 | Exported Function
`public: unsigned char __thiscall MACHINE::IsFMR(void)` | 245 | Exported Function
`public: unsigned char __thiscall MACHINE::IsPCAT(void)` | 252 | Exported Function
`public: unsigned char __thiscall LONG_ARGUMENT::Initialize(char *)` | 211 | Exported Function
`public: unsigned char __thiscall KEYBOARD::IsKeyAvailable(unsigned char *)const ` | 249 | Exported Function
`public: unsigned char __thiscall LIST::Initialize(void)` | 210 | Exported Function
`public: unsigned char __thiscall LIST::Insert(class OBJECT *,class ITERATOR *)` | 240 | Exported Function
`public: unsigned char __thiscall PROGRAM::Initialize(unsigned long,unsigned long,unsigned long)` | 222 | Exported Function
`public: unsigned char __thiscall REST_OF_LINE_ARGUMENT::Initialize(void)` | 223 | Exported Function
`public: unsigned char __thiscall SCREEN::ChangeScreenSize(unsigned short,unsigned short,unsigned char *)` | 120 | Exported Function
`public: unsigned char __thiscall PRINT_STREAM::Initialize(class PATH const *)` | 221 | Exported Function
`public: unsigned char __thiscall PATH::SetName(class WSTRING const *)` | 394 | Exported Function
`public: unsigned char __thiscall PATH::TruncateBase(void)` | 446 | Exported Function
`public: unsigned char __thiscall PATH_ARGUMENT::Initialize(char *,unsigned char)` | 220 | Exported Function
`public: unsigned char __thiscall SCREEN::SetCodePage(unsigned long)` | 383 | Exported Function
`public: unsigned char __thiscall SCREEN::SetOutputCodePage(unsigned long)` | 399 | Exported Function
`public: unsigned char __thiscall SORTED_LIST::Initialize(unsigned char)` | 225 | Exported Function
`public: unsigned char __thiscall SCREEN::MoveCursorTo(unsigned short,unsigned short)` | 272 | Exported Function
`public: unsigned char __thiscall SCREEN::EraseScreen(void)` | 164 | Exported Function
`public: unsigned char __thiscall SCREEN::EraseScreenAndResetAttribute(void)` | 165 | Exported Function
`public: unsigned char __thiscall SCREEN::Initialize(void)` | 224 | Exported Function
`public: unsigned char __thiscall PATH::SetDevice(class WSTRING const *)` | 386 | Exported Function
`public: unsigned char __thiscall PATH::AppendString(class WSTRING const *)` | 116 | Exported Function
`public: unsigned char __thiscall PATH::EndsWithDelimiter(void)const ` | 163 | Exported Function
`public: unsigned char __thiscall PATH::HasWildCard(void)const ` | 192 | Exported Function
`public: unsigned char __thiscall PATH::AppendDelimiter(void)` | 115 | Exported Function
`public: unsigned char __thiscall OBJECT::IsSameClass(class OBJECT const *)const ` | 253 | Exported Function
`public: unsigned char __thiscall OBJECT::IsSameObject(class OBJECT const *)const ` | 254 | Exported Function
`public: unsigned char __thiscall PATH::AppendBase(class WSTRING const *,unsigned char)` | 114 | Exported Function
`public: unsigned char __thiscall PATH::IsGuidVolName(void)` | 246 | Exported Function
`public: unsigned char __thiscall PATH::ModifyName(class WSTRING const *)` | 271 | Exported Function
`public: unsigned char __thiscall PATH::PathWasTooBig(void)` | 280 | Exported Function
`public: unsigned char __thiscall PATH::IsDrive(void)const ` | 243 | Exported Function
`public: unsigned char __thiscall PATH::Initialize(class PATH const *,unsigned char)` | 218 | Exported Function
`public: unsigned char __thiscall PATH::Initialize(class WSTRING const *,unsigned char)` | 219 | Exported Function
`public: unsigned char __thiscall PATH::Initialize(unsigned short const *,unsigned char)` | 217 | Exported Function
`public: virtual unsigned long __thiscall LIST::QueryMemberCount(void)const ` | 320 | Exported Function
`public: virtual unsigned long __thiscall SORTED_LIST::QueryMemberCount(void)const ` | 321 | Exported Function
`public: virtual void * __thiscall CONT_MEM::Acquire(unsigned long,unsigned long)` | 109 | Exported Function
`public: virtual unsigned long __thiscall ARRAY::QueryMemberCount(void)const ` | 319 | Exported Function
`public: virtual unsigned char __thiscall STREAM_MESSAGE::Set(unsigned long,enum MESSAGE_TYPE,unsigned long)` | 373 | Exported Function
`public: virtual unsigned char __thiscall STRING_ARRAY::Sort(unsigned char)` | 411 | Exported Function
`public: virtual unsigned long __cdecl MESSAGE::SelectResponse(unsigned long,...)` | 371 | Exported Function
`public: virtual void __thiscall PROGRAM::Fatal(void)const ` | 168 | Exported Function
`public: virtual void __thiscall PROGRAM::Usage(void)const ` | 451 | Exported Function
`public: virtual void __thiscall PROGRAM::ValidateVersion(unsigned long,unsigned long)const ` | 453 | Exported Function
`public: virtual void __thiscall OBJECT::DebugDump(unsigned char)const ` | 137 | Exported Function
`public: virtual void * __thiscall HMEM::Acquire(unsigned long,unsigned long)` | 110 | Exported Function
`public: virtual void __cdecl PROGRAM::Fatal(unsigned long,unsigned long,char *,...)const ` | 167 | Exported Function
`public: virtual void __thiscall KEYBOARD::DoNotRestoreConsoleMode(void)` | 156 | Exported Function
`public: virtual unsigned char __thiscall STREAM_MESSAGE::IsYesResponse(unsigned char)` | 260 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::IsKeyPressed(unsigned long,unsigned long)` | 250 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::IsSuppressedMessage(unsigned char)` | 256 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::IsYesResponse(unsigned char)` | 259 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::IsInSetup(void)` | 248 | Exported Function
`public: virtual unsigned char __thiscall FSTRING::Resize(unsigned long)` | 362 | Exported Function
`public: virtual unsigned char __thiscall LIST::Put(class OBJECT *)` | 283 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::IsInAutoChk(void)` | 247 | Exported Function
`public: virtual unsigned char __thiscall SEQUENTIAL_CONTAINER::DeleteAllMembers(void)` | 140 | Exported Function
`public: virtual unsigned char __thiscall SORTED_LIST::DeleteAllMembers(void)` | 141 | Exported Function
`public: virtual unsigned char __thiscall SORTED_LIST::Put(class OBJECT *)` | 284 | Exported Function
`public: virtual unsigned char __thiscall PROGRAM::DisplayMessage(unsigned long,enum MESSAGE_TYPE)const ` | 150 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::QueryStringInput(class WSTRING *)` | 339 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::SetDotsOnly(unsigned char)` | 387 | Exported Function
`public: virtual unsigned char __thiscall MESSAGE::WaitForUserSignal(void)` | 454 | Exported Function
`public: void __thiscall MESSAGE::Unlock(void)` | 449 | Exported Function
`public: void __thiscall PATH::TrimTrailingDelimeters(void)` | 444 | Exported Function
`public: void __thiscall PATH::TruncateDelimiter(void)` | 447 | Exported Function
`public: void __thiscall MESSAGE::SetLoggingEnabled(unsigned char)` | 393 | Exported Function
`public: void __thiscall BSTRING::DeleteChAt(unsigned long,unsigned long)` | 142 | Exported Function
`public: void __thiscall MESSAGE::Lock(void)` | 261 | Exported Function
`public: void __thiscall MESSAGE::ResetLoggingIterator(void)` | 359 | Exported Function
`TrackMsgId` | 467 | Exported Function
`UlibRealloc` | 468 | Exported Function
`void * __stdcall FindFirstFileW(class PATH const *,struct _WIN32_FIND_DATAW *)` | 171 | Exported Function
`public: void __thiscall WSTRING::DeleteChAt(unsigned long,unsigned long)` | 143 | Exported Function
`public: void __thiscall PATH::TruncateNameAtColon(void)` | 448 | Exported Function
`public: void __thiscall SCREEN::QueryScreenSize(unsigned short *,unsigned short *,unsigned short *,unsigned short *)const ` | 335 | Exported Function
`public: void __thiscall TIMEINFO::Initialize(class TIMEINFO const *)` | 232 | Exported Function
`public: void __thiscall BITVECTOR::SetBit(unsigned long,unsigned long)` | 379 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutMultipleSwitch(char const *)` | 287 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutMultipleSwitch(class WSTRING const *)` | 288 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutSeparators(char const *)` | 289 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutMultiCharSwitch(unsigned short const *)` | 286 | Exported Function
`public: void * __thiscall MEM_ALLOCATOR::Allocate(unsigned long)` | 112 | Exported Function
`public: void * __thiscall MEM_BLOCK_MGR::Alloc(void)` | 111 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutMultiCharSwitch(char const *)` | 285 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::SetNoSpcBetweenDstAndSwitch(unsigned char)` | 395 | Exported Function
`public: void __thiscall BITVECTOR::Initialize(unsigned long *,unsigned long)` | 196 | Exported Function
`public: void __thiscall BITVECTOR::ResetBit(unsigned long,unsigned long)` | 357 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::SetCaseSensitive(unsigned char)` | 380 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutSwitches(char const *)` | 293 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::PutSwitches(class WSTRING const *)` | 294 | Exported Function
`public: void __thiscall ARGUMENT_LEXEMIZER::SetAllowSwitchGlomming(unsigned char)` | 374 | Exported Function
`public: virtual unsigned char __thiscall FSTRING::NewBuf(unsigned long)` | 275 | Exported Function
`public: virtual __thiscall OBJECT::~OBJECT(void)` | 72 | Exported Function
`public: virtual __thiscall PATH::~PATH(void)` | 73 | Exported Function
`public: virtual __thiscall PATH_ARGUMENT::~PATH_ARGUMENT(void)` | 74 | Exported Function
`public: virtual __thiscall MULTIPLE_PATH_ARGUMENT::~MULTIPLE_PATH_ARGUMENT(void)` | 71 | Exported Function
`public: virtual __thiscall MEM_BLOCK_MGR::~MEM_BLOCK_MGR(void)` | 68 | Exported Function
`public: virtual __thiscall MESSAGE::~MESSAGE(void)` | 69 | Exported Function
`public: virtual __thiscall MESSAGE_ID_COUNT::~MESSAGE_ID_COUNT(void)` | 70 | Exported Function
`public: virtual __thiscall STACK::~STACK(void)` | 79 | Exported Function
`public: virtual __thiscall STREAM_MESSAGE::~STREAM_MESSAGE(void)` | 80 | Exported Function
`public: virtual __thiscall STRING_ARGUMENT::~STRING_ARGUMENT(void)` | 81 | Exported Function
`public: virtual __thiscall SORTED_LIST::~SORTED_LIST(void)` | 78 | Exported Function
`public: virtual __thiscall PRINT_STREAM::~PRINT_STREAM(void)` | 75 | Exported Function
`public: virtual __thiscall PROGRAM::~PROGRAM(void)` | 76 | Exported Function
`public: virtual __thiscall SCREEN::~SCREEN(void)` | 77 | Exported Function
`public: virtual __thiscall MEM_ALLOCATOR::~MEM_ALLOCATOR(void)` | 67 | Exported Function
`public: virtual __thiscall BSTRING::~BSTRING(void)` | 57 | Exported Function
`public: virtual __thiscall BYTE_STREAM::~BYTE_STREAM(void)` | 58 | Exported Function
`public: virtual __thiscall CHKDSK_MESSAGE::~CHKDSK_MESSAGE(void)` | 59 | Exported Function
`public: virtual __thiscall BITVECTOR::~BITVECTOR(void)` | 56 | Exported Function
`public: virtual __thiscall ARGUMENT_LEXEMIZER::~ARGUMENT_LEXEMIZER(void)` | 53 | Exported Function
`public: virtual __thiscall ARRAY::~ARRAY(void)` | 54 | Exported Function
`public: virtual __thiscall BDSTRING::~BDSTRING(void)` | 55 | Exported Function
`public: virtual __thiscall HMEM::~HMEM(void)` | 64 | Exported Function
`public: virtual __thiscall ITERATOR::~ITERATOR(void)` | 65 | Exported Function
`public: virtual __thiscall LIST::~LIST(void)` | 66 | Exported Function
`public: virtual __thiscall FSTRING::~FSTRING(void)` | 63 | Exported Function
`public: virtual __thiscall COMM_DEVICE::~COMM_DEVICE(void)` | 60 | Exported Function
`public: virtual __thiscall DSTRING::~DSTRING(void)` | 61 | Exported Function
`public: virtual __thiscall FSN_FILTER::~FSN_FILTER(void)` | 62 | Exported Function
`public: virtual unsigned char __thiscall ARRAY::Put(class OBJECT *)` | 282 | Exported Function
`public: virtual unsigned char __thiscall ARRAY::Sort(int (__cdecl*)(void *,void *))` | 410 | Exported Function
`public: virtual unsigned char __thiscall ARRAY::Sort(unsigned char)` | 409 | Exported Function
`public: virtual unsigned char __thiscall ARRAY::DeleteAllMembers(void)` | 139 | Exported Function
`public: virtual unsigned char __cdecl FSTRING::SPrintf(unsigned short const *,...)` | 366 | Exported Function
`public: virtual unsigned char __cdecl FSTRING::SPrintfAppend(unsigned short const *,...)` | 368 | Exported Function
`public: virtual unsigned char __cdecl PROGRAM::DisplayMessage(unsigned long,enum MESSAGE_TYPE,char *,...)const ` | 149 | Exported Function
`public: virtual unsigned char __thiscall CHKDSK_MESSAGE::SqmExport(unsigned char (__cdecl*)(void *,unsigned long,unsigned char,char *,...),void *)` | 413 | Exported Function
`public: virtual unsigned char __thiscall DSTRING::NewBuf(unsigned long)` | 274 | Exported Function
`public: virtual unsigned char __thiscall DSTRING::Resize(unsigned long)` | 361 | Exported Function
`public: virtual unsigned char __thiscall CHKDSK_MESSAGE::Set(unsigned long,enum MESSAGE_TYPE,unsigned long)` | 372 | Exported Function
`public: virtual unsigned char __thiscall BDSTRING::NewBuf(unsigned long)` | 273 | Exported Function
`public: virtual unsigned char __thiscall BDSTRING::Resize(unsigned long)` | 360 | Exported Function
`public: virtual unsigned char __thiscall CHKDSK_MESSAGE::IsYesResponse(unsigned char)` | 258 | Exported Function
`public: virtual unsigned char __cdecl DSTRING::SPrintfAppend(unsigned short const *,...)` | 367 | Exported Function
`public: virtual class ITERATOR * __thiscall SORTED_LIST::QueryIterator(void)const ` | 316 | Exported Function
`public: virtual class OBJECT * __thiscall ARRAY::GetAt(unsigned long)const ` | 176 | Exported Function
`public: virtual class OBJECT * __thiscall ARRAY::Remove(class ITERATOR *)` | 351 | Exported Function
`public: virtual class ITERATOR * __thiscall LIST::QueryIterator(void)const ` | 315 | Exported Function
`public: virtual __thiscall TIMEINFO_ARGUMENT::~TIMEINFO_ARGUMENT(void)` | 82 | Exported Function
`public: virtual __thiscall WSTRING::~WSTRING(void)` | 83 | Exported Function
`public: virtual class ITERATOR * __thiscall ARRAY::QueryIterator(void)const ` | 314 | Exported Function
`public: virtual class STREAM * __thiscall PROGRAM::GetStandardOutput(void)` | 188 | Exported Function
`public: virtual long __thiscall OBJECT::Compare(class OBJECT const *)const ` | 124 | Exported Function
`public: virtual unsigned char __cdecl DSTRING::SPrintf(unsigned short const *,...)` | 365 | Exported Function
`public: virtual class STREAM * __thiscall PROGRAM::GetStandardInput(void)` | 187 | Exported Function
`public: virtual class OBJECT * __thiscall ARRAY::RemoveAt(unsigned long)` | 352 | Exported Function
`public: virtual class OBJECT * __thiscall ITERATOR::FindNext(class OBJECT const *)` | 172 | Exported Function
`public: virtual class STREAM * __thiscall PROGRAM::GetStandardError(void)` | 186 | Exported Function
`public: __thiscall STRING_ARGUMENT::STRING_ARGUMENT(void)` | 45 | Exported Function
`public: __thiscall STRING_ARRAY::STRING_ARRAY(void)` | 46 | Exported Function
`public: __thiscall TIMEINFO::TIMEINFO(void)` | 47 | Exported Function
`public: __thiscall STREAM_MESSAGE::STREAM_MESSAGE(void)` | 44 | Exported Function
`public: __thiscall SCREEN::SCREEN(void)` | 41 | Exported Function
`public: __thiscall SORTED_LIST::SORTED_LIST(void)` | 42 | Exported Function
`public: __thiscall STACK::STACK(void)` | 43 | Exported Function
`public: char * __thiscall WSTRING::QuerySTR(unsigned long,unsigned long,char *,unsigned long,unsigned char)const ` | 334 | Exported Function
`public: char const * __thiscall OBJECT::DebugGetClassName(void)const ` | 138 | Exported Function
`public: class ARRAY * __thiscall FSN_DIRECTORY::QueryFsnodeArray(class FSN_FILTER *)const ` | 309 | Exported Function
`public: char * __thiscall BSTRING::QuerySTR(unsigned long,unsigned long,char *,unsigned long,unsigned char)const ` | 333 | Exported Function
`public: __thiscall TIMEINFO_ARGUMENT::TIMEINFO_ARGUMENT(void)` | 48 | Exported Function
`public: __thiscall WSTRING::WSTRING(class WSTRING &&)` | 50 | Exported Function
`public: __thiscall WSTRING::WSTRING(class WSTRING const &)` | 51 | Exported Function
`public: __thiscall REST_OF_LINE_ARGUMENT::REST_OF_LINE_ARGUMENT(void)` | 40 | Exported Function
`public: __thiscall MACHINE::MACHINE(void)` | 28 | Exported Function
`public: __thiscall MEM_ALLOCATOR::MEM_ALLOCATOR(void)` | 29 | Exported Function
`public: __thiscall MEM_BLOCK_MGR::MEM_BLOCK_MGR(void)` | 30 | Exported Function
`public: __thiscall LONG_ARGUMENT::LONG_ARGUMENT(void)` | 27 | Exported Function
`public: __thiscall ITERATOR::ITERATOR(class ITERATOR const &)` | 24 | Exported Function
`public: __thiscall KEYBOARD::KEYBOARD(void)` | 25 | Exported Function
`public: __thiscall LIST::LIST(void)` | 26 | Exported Function
`public: __thiscall PATH::PATH(void)` | 36 | Exported Function
`public: __thiscall PATH_ARGUMENT::PATH_ARGUMENT(void)` | 37 | Exported Function
`public: __thiscall PRINT_STREAM::PRINT_STREAM(void)` | 38 | Exported Function
`public: __thiscall OBJECT::OBJECT(class OBJECT const &)` | 35 | Exported Function
`public: __thiscall MESSAGE::MESSAGE(void)` | 31 | Exported Function
`public: __thiscall MESSAGE_ID_COUNT::MESSAGE_ID_COUNT(void)` | 32 | Exported Function
`public: __thiscall MULTIPLE_PATH_ARGUMENT::MULTIPLE_PATH_ARGUMENT(void)` | 33 | Exported Function
`public: class WSTRING & __thiscall WSTRING::operator=(class WSTRING const &)` | 93 | Exported Function
`public: class WSTRING * __thiscall ARGUMENT::GetLexeme(void)` | 181 | Exported Function
`public: class WSTRING * __thiscall ARGUMENT::GetPattern(void)` | 185 | Exported Function
`public: class WSTRING & __thiscall WSTRING::operator=(class WSTRING &&)` | 92 | Exported Function
`public: class PATH * __thiscall PATH::QueryMountPointPath(void)` | 322 | Exported Function
`public: class PATH * __thiscall PATH::QueryPath(void)const ` | 328 | Exported Function
`public: class PATH * __thiscall PATH::QueryWCExpansion(class PATH *)` | 344 | Exported Function
`public: class WSTRING * __thiscall PATH::QueryGuidString(class WSTRING *,unsigned char *,class WSTRING *)` | 312 | Exported Function
`public: class WSTRING * __thiscall PATH::QueryRoot(void)` | 332 | Exported Function
`public: class WSTRING * __thiscall WSTRING::QueryString(unsigned long,unsigned long)const ` | 338 | Exported Function
`public: class WSTRING * __thiscall PATH::QueryFullPathString(void)const ` | 311 | Exported Function
`public: class WSTRING * __thiscall ARGUMENT_LEXEMIZER::GetLexemeAt(unsigned long)` | 182 | Exported Function
`public: class WSTRING * __thiscall ARGUMENT_LEXEMIZER::QueryInvalidArgument(void)` | 313 | Exported Function
`public: class WSTRING * __thiscall FSTRING::Initialize(unsigned short *,unsigned long)` | 207 | Exported Function
`public: class PATH * __thiscall PATH::QueryFullPath(void)const ` | 310 | Exported Function
`public: class CLASS_DESCRIPTOR const * __thiscall OBJECT::GetClassDescriptor(void)const ` | 177 | Exported Function
`public: class DSTRING & __thiscall DSTRING::operator=(class DSTRING const &)` | 87 | Exported Function
`public: class FILE_STREAM * __thiscall FSN_FILE::QueryStream(enum STREAMACCESS,unsigned long)` | 337 | Exported Function
`public: class BSTRING & __thiscall BSTRING::operator=(class BSTRING const &)` | 86 | Exported Function
`public: class ARRAY * __thiscall PATH::QueryComponentArray(class ARRAY *)const ` | 301 | Exported Function
`public: class BDSTRING & __thiscall BDSTRING::operator=(class BDSTRING const &)` | 84 | Exported Function
`public: class BSTRING & __thiscall BSTRING::operator=(class BSTRING &&)` | 85 | Exported Function
`public: class ITERATOR & __thiscall ITERATOR::operator=(class ITERATOR const &)` | 90 | Exported Function
`public: class OBJECT & __thiscall OBJECT::operator=(class OBJECT const &)` | 91 | Exported Function
`public: class OBJECT * __thiscall ARRAY::OrderedSearch(class OBJECT *,void * *)` | 279 | Exported Function
`public: class FSTRING & __thiscall FSTRING::operator=(class FSTRING const &)` | 89 | Exported Function
`public: class FSN_DIRECTORY * __thiscall FSN_DIRECTORY::CreateDirectoryPath(class PATH const *)const ` | 136 | Exported Function
`public: class FSNODE * __thiscall FSN_DIRECTORY::GetNext(void * *,unsigned long *)` | 183 | Exported Function
`public: class FSTRING & __thiscall FSTRING::operator=(class FSTRING &&)` | 88 | Exported Function
`public: __thiscall HMEM::HMEM(void)` | 22 | Exported Function
`private: static unsigned char WSTRING::_UseConsoleConversionsPrev` | 460 | Exported Function
`private: unsigned char __thiscall BYTE_STREAM::FillAndReadByte(unsigned char *)` | 170 | Exported Function
`private: unsigned char __thiscall DSTRING::SPrintfWorker(unsigned short const *,char *)` | 369 | Exported Function
`private: static unsigned char WSTRING::_UseConsoleConversions` | 459 | Exported Function
`private: static unsigned char __stdcall WSTRING::ConvertUnicodeToOemN(char *,unsigned long,unsigned long *,unsigned short *,unsigned long)` | 134 | Exported Function
`private: static unsigned char WSTRING::_UseAnsiConversions` | 457 | Exported Function
`private: static unsigned char WSTRING::_UseAnsiConversionsPrev` | 458 | Exported Function
`protected: __thiscall ITERATOR::ITERATOR(void)` | 23 | Exported Function
`protected: __thiscall OBJECT::OBJECT(void)` | 34 | Exported Function
`protected: __thiscall PROGRAM::PROGRAM(void)` | 39 | Exported Function
`protected: __thiscall BSTRING::BSTRING(void)` | 7 | Exported Function
`private: unsigned long __thiscall BITVECTOR::ComputeCountSet(void)const ` | 125 | Exported Function
`private: void __thiscall BDSTRING::Construct(void)` | 126 | Exported Function
`private: void __thiscall DSTRING::Construct(void)` | 128 | Exported Function
`private: static unsigned char __stdcall WSTRING::ConvertOemToUnicodeN(unsigned short *,unsigned long,unsigned long *,char *,unsigned long)` | 131 | Exported Function
`const ITERATOR::``vftable'` | 106 | Exported Function
`const OBJECT::``vftable'` | 107 | Exported Function
`const WSTRING::``vftable'` | 108 | Exported Function
`const FSTRING::``vftable'` | 105 | Exported Function
`const BDSTRING::``vftable'` | 102 | Exported Function
`const BSTRING::``vftable'` | 103 | Exported Function
`const DSTRING::``vftable'` | 104 | Exported Function
`Get_Standard_Output_Stream` | 465 | Exported Function
`MachinePlatform` | 466 | Exported Function
`private: static int __stdcall WSTRING::CheckSpace(unsigned short *)` | 122 | Exported Function
`Get_Standard_Input_Stream` | 464 | Exported Function
`DebugPrintfReal` | 461 | Exported Function
`Export` | 462 | Exported Function
`Get_Standard_Error_Stream` | 463 | Exported Function
`public: __thiscall CLASS_DESCRIPTOR::CLASS_DESCRIPTOR(void)` | 12 | Exported Function
`public: __thiscall COMM_DEVICE::COMM_DEVICE(void)` | 13 | Exported Function
`public: __thiscall CONT_MEM::CONT_MEM(void)` | 14 | Exported Function
`public: __thiscall CHKDSK_MESSAGE::CHKDSK_MESSAGE(void)` | 11 | Exported Function
`public: __thiscall BSTRING::BSTRING(class BSTRING &&)` | 8 | Exported Function
`public: __thiscall BSTRING::BSTRING(class BSTRING const &)` | 9 | Exported Function
`public: __thiscall BYTE_STREAM::BYTE_STREAM(void)` | 10 | Exported Function
`public: __thiscall FSTRING::FSTRING(class FSTRING &&)` | 19 | Exported Function
`public: __thiscall FSTRING::FSTRING(class FSTRING const &)` | 20 | Exported Function
`public: __thiscall FSTRING::FSTRING(void)` | 21 | Exported Function
`public: __thiscall FSN_FILTER::FSN_FILTER(void)` | 18 | Exported Function
`public: __thiscall DSTRING::DSTRING(class DSTRING const &)` | 15 | Exported Function
`public: __thiscall DSTRING::DSTRING(void)` | 16 | Exported Function
`public: __thiscall FLAG_ARGUMENT::FLAG_ARGUMENT(void)` | 17 | Exported Function
`public: __thiscall BITVECTOR::BITVECTOR(void)` | 6 | Exported Function
`protected: void __thiscall OBJECT::SetClassDescriptor(class CLASS_DESCRIPTOR const *)` | 382 | Exported Function
`protected: void __thiscall WSTRING::Construct(void)` | 130 | Exported Function
`protected: void __thiscall WSTRING::PutString(unsigned short *)` | 291 | Exported Function
`protected: void __thiscall OBJECT::Construct(void)` | 129 | Exported Function
`protected: __thiscall WSTRING::WSTRING(void)` | 49 | Exported Function
`protected: void __thiscall BSTRING::Construct(void)` | 127 | Exported Function
`protected: void __thiscall BSTRING::PutString(char *,unsigned long)` | 290 | Exported Function
`public: __thiscall ARRAY::ARRAY(void)` | 3 | Exported Function
`public: __thiscall BDSTRING::BDSTRING(class BDSTRING const &)` | 4 | Exported Function
`public: __thiscall BDSTRING::BDSTRING(void)` | 5 | Exported Function
`public: __thiscall ARGUMENT_LEXEMIZER::ARGUMENT_LEXEMIZER(void)` | 2 | Exported Function
`protected: void __thiscall WSTRING::PutString(unsigned short *,unsigned long)` | 292 | Exported Function
`public: __thiscall ADMINFILEPRIVS::ADMINFILEPRIVS(void)` | 1 | Exported Function
`public: __thiscall ADMINFILEPRIVS::~ADMINFILEPRIVS(void)` | 52 | Exported Function
`public: unsigned char __thiscall BITVECTOR::Initialize(unsigned long,enum BIT,unsigned long *)` | 195 | Exported Function
`public: unsigned char __thiscall BITVECTOR::QueryResetBit(unsigned long,unsigned long)const ` | 329 | Exported Function
`public: unsigned char __thiscall BITVECTOR::QuerySetBit(unsigned long,unsigned long)const ` | 336 | Exported Function
`public: unsigned char __thiscall ARRAY::OrderedInsert(class OBJECT *,void * *)` | 278 | Exported Function
`public: unsigned char __thiscall ARGUMENT_LEXEMIZER::QueryMultiCharSwitch(class WSTRING *)` | 323 | Exported Function
`public: unsigned char __thiscall ARRAY::Initialize(unsigned long,unsigned long)` | 194 | Exported Function
`public: unsigned char __thiscall ARRAY::Insert(class OBJECT *,unsigned long)` | 239 | Exported Function
`public: unsigned char __thiscall CHKDSK_MESSAGE::Initialize(class STREAM *,class STREAM *,class STREAM *)` | 200 | Exported Function
`public: unsigned char __thiscall CLASS_DESCRIPTOR::Initialize(char const *)` | 201 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::CommitState(void)` | 123 | Exported Function
`public: unsigned char __thiscall BYTE_STREAM::Initialize(class STREAM *,unsigned long)` | 199 | Exported Function
`public: unsigned char __thiscall BSTRING::Initialize(char const *,unsigned long)` | 197 | Exported Function
`public: unsigned char __thiscall BSTRING::Initialize(void)` | 198 | Exported Function
`public: unsigned char __thiscall BSTRING::ReplaceWithChars(unsigned long,unsigned long,char,unsigned long)` | 355 | Exported Function
`public: unsigned char __thiscall ARGUMENT_LEXEMIZER::PrepareToParse(class WSTRING *)` | 281 | Exported Function
`public: static void __stdcall WSTRING::SetConsoleConversions(void)` | 384 | Exported Function
`public: static void __stdcall WSTRING::SetOemConversions(void)` | 398 | Exported Function
`public: unsigned char __cdecl MESSAGE::Display(char const *,...)` | 148 | Exported Function
`public: static void __stdcall WSTRING::SetAnsiConversions(void)` | 375 | Exported Function
`public: static void __stdcall SYSTEM::DisplaySystemError(unsigned long,int)` | 155 | Exported Function
`public: static void __stdcall SYSTEM::FreeLibraryHandle(void *)` | 175 | Exported Function
`public: static void __stdcall WSTRING::ResetConversions(void)` | 358 | Exported Function
`public: unsigned char __thiscall ARGUMENT::IsValueSet(void)` | 257 | Exported Function
`public: unsigned char __thiscall ARGUMENT_LEXEMIZER::DoParsing(class ARRAY *)` | 157 | Exported Function
`public: unsigned char __thiscall ARGUMENT_LEXEMIZER::Initialize(class ARRAY *)` | 193 | Exported Function
`public: unsigned char __cdecl MESSAGE::LogMsg(unsigned long,char const *,...)` | 264 | Exported Function
`public: unsigned char __cdecl MESSAGE::DisplayMsg(unsigned long,char const *,...)` | 151 | Exported Function
`public: unsigned char __cdecl MESSAGE::DisplayMsg(unsigned long,enum MESSAGE_TYPE,unsigned long,char const *,...)` | 152 | Exported Function
`public: unsigned char __cdecl MESSAGE::Log(char const *,...)` | 262 | Exported Function
`public: unsigned char __thiscall FSN_DIRECTORY::Traverse(void *,class FSN_FILTER *,class PATH *,unsigned char (__stdcall*)(void *,class FSNODE *,class PATH *))const ` | 443 | Exported Function
`public: unsigned char __thiscall FSN_FILE::Copy(class PATH *,enum _COPY_ERROR *,unsigned long,unsigned long (__stdcall*)(union _LARGE_INTEGER,union _LARGE_INTEGER,union _LARGE_INTEGER,union _LARGE_INTEGER,unsigned long,unsigned long,void *,void *,void *),void *,int *)const ` | 135 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::DoesNodeMatch(class FSNODE *)` | 158 | Exported Function
`public: unsigned char __thiscall FSN_DIRECTORY::IsEmpty(void)const ` | 244 | Exported Function
`public: unsigned char __thiscall FLAG_ARGUMENT::Initialize(char *)` | 204 | Exported Function
`public: unsigned char __thiscall FLAG_ARGUMENT::Initialize(class WSTRING *)` | 205 | Exported Function
`public: unsigned char __thiscall FSN_DIRECTORY::DeleteDirectory(void)` | 144 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::SetTimeInfo(class TIMEINFO const *,enum FSN_TIME,unsigned short)` | 404 | Exported Function
`public: unsigned char __thiscall FSNODE::SetAttributes(unsigned long,unsigned long *)` | 376 | Exported Function
`public: unsigned char __thiscall FSNODE::UseAlternateName(void)` | 452 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::SetFileName(class WSTRING const *)` | 390 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::Initialize(void)` | 206 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::SetAttributes(unsigned long,unsigned long,unsigned long)` | 377 | Exported Function
`public: unsigned char __thiscall FSN_FILTER::SetFileName(char const *)` | 389 | Exported Function
`public: unsigned char __thiscall FILE_STREAM::ReadAt(unsigned char *,unsigned long,__int64,enum SEEKORIGIN,unsigned long *)` | 347 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetDtrControl(enum DTR_CONTROL)` | 388 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetIdsr(unsigned char)` | 391 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetOcts(unsigned char)` | 396 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetDataBits(unsigned long)` | 385 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::Initialize(class PATH const *,unsigned char *)` | 202 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::QueryTimeOut(void)const ` | 342 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetBaudRate(unsigned long)` | 378 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetTimeOut(unsigned char)` | 405 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetXon(unsigned char)` | 406 | Exported Function
`public: unsigned char __thiscall CONT_MEM::Initialize(void *,unsigned long)` | 203 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetStopBits(enum STOPBITS)` | 403 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetOdsr(unsigned char)` | 397 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetParity(enum PARITY)` | 400 | Exported Function
`public: unsigned char __thiscall COMM_DEVICE::SetRtsControl(enum RTS_CONTROL)` | 401 | Exported Function
`public: static void __stdcall SQMEXPORT::SqmExportOnError(unsigned long,unsigned long,unsigned char,unsigned char,unsigned __int64,struct _GUID)` | 415 | Exported Function
`public: static class FSN_FILE * __stdcall SYSTEM::MakeFile(class PATH const *)` | 268 | Exported Function
`public: static class FSN_FILE * __stdcall SYSTEM::MakeTemporaryFile(class WSTRING const *,class PATH const *)` | 270 | Exported Function
`public: static class FSN_FILE * __stdcall SYSTEM::QueryFile(class PATH const *,unsigned char,unsigned char *)` | 307 | Exported Function
`public: static class FSN_DIRECTORY * __stdcall SYSTEM::QueryDirectory(class PATH const *,unsigned char)` | 304 | Exported Function
`public: static char * __stdcall MBSTR::Strstr(char *,char *)` | 438 | Exported Function
`public: static class FILE_STREAM * __stdcall FILE_STREAM::Cast(class OBJECT const *)` | 117 | Exported Function
`public: static class FSN_DIRECTORY * __stdcall SYSTEM::MakeDirectory(class PATH const *,class PATH const *,enum _COPY_ERROR *,unsigned long (__stdcall*)(union _LARGE_INTEGER,union _LARGE_INTEGER,union _LARGE_INTEGER,union _LARGE_INTEGER,unsigned long,unsigned long,void *,void *,void *),void *,int *,unsigned long)` | 267 | Exported Function
`public: static class SCREEN * __stdcall SCREEN::Cast(class OBJECT const *)` | 119 | Exported Function
`public: static class WSTRING * __stdcall SYSTEM::QueryEnvironmentVariable(class WSTRING const *)` | 306 | Exported Function
`public: static class WSTRING * __stdcall SYSTEM::QueryVolumeLabel(class PATH *,struct _VOL_SERIAL_NUMBER *)` | 343 | Exported Function
`public: static class PATH * __stdcall SYSTEM::SearchPathW(class WSTRING *,class WSTRING *)` | 370 | Exported Function
`public: static class KEYBOARD * __stdcall KEYBOARD::Cast(class OBJECT const *)` | 118 | Exported Function
`public: static class OBJECT * __stdcall ARRAY::GetCompareArgument(void *)` | 178 | Exported Function
`public: static class PATH * __stdcall SYSTEM::QuerySystemDirectory(void)` | 340 | Exported Function
`public: static char * __stdcall MBSTR::CharNextW(char *)` | 121 | Exported Function
`public: enum PATH_ANALYZE_CODE __thiscall PATH::AnalyzePath(class WSTRING *,class PATH *,class WSTRING *)` | 113 | Exported Function
`public: int * __thiscall KEYBOARD::GetPFlagBreak(void)const ` | 184 | Exported Function
`public: long __thiscall ADMINFILEPRIVS::EnablePrivileges(void)` | 162 | Exported Function
`public: class WSTRING * __thiscall WSTRING::Strupr(void)` | 441 | Exported Function
`public: class WSTRING * __thiscall WSTRING::Strlwr(unsigned long,unsigned long)` | 434 | Exported Function
`public: class WSTRING * __thiscall WSTRING::Strlwr(void)` | 435 | Exported Function
`public: class WSTRING * __thiscall WSTRING::Strupr(unsigned long,unsigned long)` | 440 | Exported Function
`public: long __thiscall WSTRING::Stricmp(class WSTRING const *)const ` | 430 | Exported Function
`public: long __thiscall WSTRING::Stricmp(class WSTRING const *,unsigned long)const ` | 431 | Exported Function
`public: long __thiscall WSTRING::Stricmp(class WSTRING const *,unsigned long,unsigned long,unsigned long,unsigned long)const ` | 432 | Exported Function
`public: long __thiscall WSTRING::Strcmp(class WSTRING const *,unsigned long,unsigned long,unsigned long,unsigned long)const ` | 422 | Exported Function
`public: long __thiscall ADMINFILEPRIVS::RestorePrivileges(void)` | 364 | Exported Function
`public: long __thiscall WSTRING::Strcmp(class WSTRING const *)const ` | 420 | Exported Function
`public: long __thiscall WSTRING::Strcmp(class WSTRING const *,unsigned long)const ` | 421 | Exported Function
`public: static unsigned char __stdcall SQMEXPORT::UploadSqmFromFile(void *)` | 450 | Exported Function
`public: static unsigned char __stdcall SYSTEM::GetFileSecurityBackup(class PATH const *,unsigned long,struct _SECURITY_ATTRIBUTES *,unsigned long *)` | 179 | Exported Function
`public: static unsigned char __stdcall SYSTEM::IsCorrectVersion(void)` | 242 | Exported Function
`public: static unsigned char __stdcall KEYBOARD::GotABreak(void)` | 191 | Exported Function
`public: static unsigned char __stdcall BASE_SYSTEM::QueryResourceStringV(class WSTRING *,unsigned long,char const *,char *)` | 331 | Exported Function
`public: static unsigned char __stdcall KEYBOARD::DisableBreakHandling(void)` | 146 | Exported Function
`public: static unsigned char __stdcall KEYBOARD::EnableBreakHandling(void)` | 160 | Exported Function
`public: static unsigned char __stdcall SYSTEM::RemoveNode(class FSNODE * *,unsigned char)` | 353 | Exported Function
`public: static unsigned short * __stdcall WSTRING::SkipWhite(unsigned short *)` | 408 | Exported Function
`public: static void __stdcall PROGRAM::ExitProgram(unsigned long)` | 166 | Exported Function
`public: static unsigned char __stdcall SYSTEM::QueryWindowsErrorMessage(unsigned long,class WSTRING *)` | 346 | Exported Function
`public: static unsigned char __stdcall SYSTEM::IsStorageDaxCapable(class WSTRING const *,unsigned char *)` | 255 | Exported Function
`public: static unsigned char __stdcall SYSTEM::QueryCurrentDosDriveName(class WSTRING *)` | 302 | Exported Function
`public: static unsigned char __stdcall SYSTEM::QueryLocalTimeFromUTime(class TIMEINFO const *,class TIMEINFO *)` | 318 | Exported Function
`public: static unsigned char __cdecl SQMEXPORT::SqmExport(void *,unsigned long,unsigned char,char *,...)` | 414 | Exported Function
`public: static int __stdcall MBSTR::Strcmpis(char *,char *)` | 424 | Exported Function
`public: static int __stdcall MBSTR::Strcmps(char *,char *)` | 426 | Exported Function
`public: static int __stdcall MBSTR::Stricmp(char *,char *)` | 429 | Exported Function
`public: static int (__stdcall*__stdcall SYSTEM::QueryNextLibraryEntryPoint(void *,class WSTRING const *))(void)` | 324 | Exported Function
`public: static enum DRIVE_TYPE __stdcall SYSTEM::QueryDriveType(class WSTRING const *)` | 305 | Exported Function
`public: static enum FILE_TYPE __stdcall SYSTEM::QueryFileType(class WSTRING const *)` | 308 | Exported Function
`public: static int (__stdcall*__stdcall SYSTEM::QueryLibraryEntryPoint(class WSTRING const *,class WSTRING const *,void * *))(void)` | 317 | Exported Function
`public: static unsigned __int64 __stdcall MESSAGE::MakeFileToken(char const *)` | 269 | Exported Function
`public: static unsigned char __cdecl BASE_SYSTEM::QueryResourceString(class WSTRING *,unsigned long,char const *,...)` | 330 | Exported Function
`public: static unsigned char __cdecl SQMEXPORT::FileExport(void *,unsigned long,unsigned char,char *,...)` | 169 | Exported Function
`public: static int __stdcall WSTRING::Stricmp(unsigned short *,unsigned short *)` | 433 | Exported Function
`public: static int __stdcall WSTRING::Strcmp(unsigned short *,unsigned short *)` | 423 | Exported Function
`public: static int __stdcall WSTRING::Strcmpis(unsigned short *,unsigned short *)` | 425 | Exported Function
`public: static int __stdcall WSTRING::Strcmps(unsigned short *,unsigned short *)` | 427 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: ulib.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 1/72
* VirusTotal Link: https://www.virustotal.com/gui/file/8ce6869f6756383adb8922087c97028ca206cabadac2b87912135c4ec2b458f5/detection/





MIT License. Copyright (c) 2020 Strontic.


