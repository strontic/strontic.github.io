---
title: csfcommunicationhistory.dll | 
excerpt: What is csfcommunicationhistory.dll?
---

# csfcommunicationhistory.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\csfcommunicationhistory.dll`

## Hashes

Type | Hash
-- | --
MD5 | `704758DFAEC6611CBFD857D8B3521EB2`
SHA1 | `17B92B9E791EE9D0105295831C8BFD4754239E55`
SHA256 | `819F4D6B1E3015A5D865757F3E8FA009E05360064E3D5881F44DBA9432288748`
SHA384 | `B4ADE1D6EE722B2855472CF2B8148E7FFA22C18E5E9C4FE4FF7255E05CF9DC610FE260433DD041FC119894757A50C8C7`
SHA512 | `CC97329AE3D8BFCB6D54C49152BDD8F6068B2D8CFCA5C282E668FC759A7F8AF7F62420AD53452CDC9D88C402AEFF984B95B3CE9E9BB265AFE0977B22B9B08127`
SSDEEP | `24576:Ov3Rms1bxLV/4uzLbuTbHM17LYrbHQsljO6cn/wr/ojAKqQbeUO8rBFNn:OX1bPg2bgbHMEuluQbeB8rBFNn`
IMP | `08D451C44F7E15F6019C5BA026A8777D`
PESHA1 | `398E91D3184D07523835FEF2270F1FB770B6A6B6`
PE256 | `DA11039E9EBA9A2512C7E60E51B8C79DC9CE8D4529AFCFB900D939342E5194EE`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: virtual __int64 __thiscall csf::ChatRoomHistoryDBManager::getLastInsertRowId(void)` | 209 | Exported Function
`public: virtual __thiscall csf::ChatRoomHistoryDBManager::~ChatRoomHistoryDBManager(void)` | 52 | Exported Function
`public: virtual __thiscall csf::ChatRoomHistoryManager::~ChatRoomHistoryManager(void)` | 54 | Exported Function
`public: static class std::shared_ptr<class csf::HistoryManager> __cdecl csf::HistoryManager::getFileSystemInstance(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 187 | Exported Function
`public: static class std::shared_ptr<class csf::HistoryManager> __cdecl csf::HistoryManager::getInMemoryInstance(void)` | 200 | Exported Function
`public: unsigned int __thiscall csf::ChatRoomFilterUnreadMessages::count(void)const ` | 133 | Exported Function
`public: virtual __thiscall csf::FileSystemHistoryManager::~FileSystemHistoryManager(void)` | 61 | Exported Function
`public: virtual bool __thiscall csf::ChatRoomHistoryDBManager::execParameterlessResultlessStatement(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 148 | Exported Function
`public: virtual bool __thiscall csf::ChatRoomHistoryDBManager::execStatement(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class csf::DBParamSet>)` | 150 | Exported Function
`public: virtual bool __thiscall csf::ChatRoomHistoryDBManager::isOpened(void)` | 278 | Exported Function
`public: virtual __thiscall csf::HistoryManager::~HistoryManager(void)` | 64 | Exported Function
`public: virtual __thiscall csf::InMemoryHistoryManager::~InMemoryHistoryManager(void)` | 67 | Exported Function
`public: virtual __thiscall csf::SQLiteCommand::~SQLiteCommand(void)` | 68 | Exported Function
`public: int __thiscall csf::ChatRoomHistoryManager::deleteEvents(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >)` | 139 | Exported Function
`public: int __thiscall csf::ChatRoomHistoryMessage::getType(void)` | 250 | Exported Function
`public: int __thiscall csf::HistoryLabel::getBGColor(void)` | 162 | Exported Function
`public: enum csf::HistoryPhoneType __thiscall csf::HistoryParticipant::getPhoneType(void)` | 233 | Exported Function
`public: enum csf::HistoryProtocolType __thiscall csf::HistoryItem::getProtocolType(void)` | 237 | Exported Function
`public: int __thiscall csf::ChatRoomHistoryManager::addEvents(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >,bool,bool)` | 117 | Exported Function
`public: int __thiscall csf::HistoryLabel::getFGColor(void)` | 185 | Exported Function
`public: int __thiscall csf::HistoryManager::updateOrCreateFilterViewTime(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,bool)` | 413 | Exported Function
`public: int __thiscall csf::HistoryMessage::getType(void)` | 251 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl csf::ChatRoomHistoryManager::getChatRoomHistoryFileName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 168 | Exported Function
`public: int __thiscall csf::HistoryManager::addChatRoomEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >,bool,bool)` | 114 | Exported Function
`public: int __thiscall csf::HistoryManager::addChatRoomFilterMatch(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,__int64,bool)` | 115 | Exported Function
`public: int __thiscall csf::HistoryManager::deleteMatchesForFilter(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 142 | Exported Function
`public: virtual void __thiscall csf::FileSystemHistoryManager::initialize(void)` | 268 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::deleteEvents(class std::vector<__int64,class std::allocator<__int64> > &)` | 140 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::markEventsRead(class std::vector<__int64,class std::allocator<__int64> > &)` | 284 | Exported Function
`public: virtual void __thiscall csf::ChatRoomHistoryDBManager::endTransaction(void)` | 145 | Exported Function
`public: virtual void __thiscall csf::ChatRoomHistoryDBManager::rollbackTransaction(void)` | 331 | Exported Function
`public: virtual void __thiscall csf::ChatRoomHistoryDBManager::uninitialize(void)` | 406 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::markEventsUnread(class std::vector<__int64,class std::allocator<__int64> > &)` | 285 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::setMaxCallEvents(int)` | 377 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::setMaxImEvents(int)` | 378 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::setMaxVoicemailEvents(int)` | 379 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::purgeDeletedCallEvents(void)` | 303 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::purgeEvents(class std::vector<__int64,class std::allocator<__int64> > &,bool)` | 304 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::purgeOldImEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 306 | Exported Function
`public: virtual class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > > __thiscall csf::HistoryManager::getRecentChatEvents(void)` | 241 | Exported Function
`public: virtual class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > > __thiscall csf::HistoryManager::getVoicemailEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 258 | Exported Function
`public: virtual int __thiscall csf::ChatRoomHistoryDBManager::getNumberOfRowsModified(void)` | 226 | Exported Function
`public: virtual class std::shared_ptr<class csf::DBResultSet> __thiscall csf::ChatRoomHistoryDBManager::execStatement(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class csf::DBParamSet>,bool)` | 149 | Exported Function
`public: virtual class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > > __thiscall csf::HistoryManager::getCallEvents(void)` | 164 | Exported Function
`public: virtual class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > > __thiscall csf::HistoryManager::getImEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 199 | Exported Function
`public: virtual int __thiscall csf::ChatRoomHistoryDBManager::initialize(void)` | 266 | Exported Function
`public: virtual int __thiscall csf::HistoryManager::getDeletedImEventsCount(void)` | 179 | Exported Function
`public: virtual int __thiscall csf::HistoryManager::getUnreadCallEventsCount(void)` | 254 | Exported Function
`public: virtual void __thiscall csf::ChatRoomHistoryDBManager::beginTransaction(void)` | 128 | Exported Function
`public: virtual int __thiscall csf::HistoryManager::getAllCallEventsCount(void)` | 160 | Exported Function
`public: virtual int __thiscall csf::HistoryManager::getAllImEventsCount(void)` | 161 | Exported Function
`public: virtual int __thiscall csf::HistoryManager::getDeletedCallEventsCount(void)` | 177 | Exported Function
`public: enum csf::HistoryMediaType __thiscall csf::HistoryItem::getMediaType(void)` | 216 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getPreferredPhoneNumber(void)` | 236 | Exported Function
`public: class std::shared_ptr<class csf::ChatRoomHistoryItem> __thiscall csf::ChatRoomHistoryManager::getMessageItem(__int64)` | 220 | Exported Function
`public: class std::shared_ptr<class csf::ChatRoomHistoryManager> __thiscall csf::HistoryManager::getOrCreateChatRoomHistoryManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 231 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::GetName(void)` | 107 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::GetNumber(void)` | 108 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getPhotoUri(void)` | 234 | Exported Function
`public: class std::shared_ptr<class csf::ChatRoomHistoryMessage> __thiscall csf::ChatRoomHistoryItem::getMessage(void)` | 217 | Exported Function
`public: class std::shared_ptr<class csf::HistoryLabel> __thiscall csf::HistoryMessage::getLabel(void)` | 207 | Exported Function
`public: class std::shared_ptr<class csf::HistoryManager const > __thiscall std::enable_shared_from_this<class csf::HistoryManager>::shared_from_this(void)const ` | 404 | Exported Function
`public: class std::shared_ptr<class csf::HistoryManager> __thiscall std::enable_shared_from_this<class csf::HistoryManager>::shared_from_this(void)` | 403 | Exported Function
`public: class std::shared_ptr<class csf::HistoryItem> __thiscall csf::HistoryManager::getEventById(__int64)` | 184 | Exported Function
`public: class std::shared_ptr<class csf::HistoryItem> __thiscall csf::HistoryManager::getRecentChatHistoryItemByRemoteParticipant(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 242 | Exported Function
`public: class std::shared_ptr<class csf::HistoryLabel> __thiscall csf::ChatRoomHistoryMessage::getLabel(void)` | 206 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryMessage::getSender(void)` | 249 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getAccount(void)` | 159 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getBusinessPhone(void)` | 163 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryLabel::getMarking(void)` | 214 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryLabel::getSelector(void)` | 247 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryMessage::getPayload(void)` | 232 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getDefaultPhone(void)` | 176 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getJid(void)` | 204 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getLineID(void)` | 211 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getMobilePhone(void)` | 225 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getDisplayName(void)` | 181 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getHomePhone(void)` | 191 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryParticipant::getHuntGroup(void)` | 192 | Exported Function
`public: class std::vector<__int64,class std::allocator<__int64> > __thiscall csf::HistoryManager::getOldestCallEventsId(int)` | 227 | Exported Function
`public: class std::vector<__int64,class std::allocator<__int64> > __thiscall csf::HistoryManager::getOldestImEventsId(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 228 | Exported Function
`public: class std::weak_ptr<class csf::HistoryManager const > __thiscall std::enable_shared_from_this<class csf::HistoryManager>::weak_from_this(void)const ` | 420 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryParticipant>,class std::allocator<class std::shared_ptr<class csf::HistoryParticipant> > > > __thiscall csf::HistoryItem::getRemoteParticipants(void)` | 243 | Exported Function
`public: class std::vector<__int64,class std::allocator<__int64> > __thiscall csf::HistoryManager::getDeletedCallEventsId(void)` | 178 | Exported Function
`public: class std::vector<__int64,class std::allocator<__int64> > __thiscall csf::HistoryManager::getDeletedImEventsId(void)` | 180 | Exported Function
`public: class std::weak_ptr<class csf::HistoryManager> __thiscall std::enable_shared_from_this<class csf::HistoryManager>::weak_from_this(void)` | 419 | Exported Function
`public: enum csf::HistoryManagerOpenResultEnum::HistoryManagerOpenResult __thiscall csf::ChatRoomHistoryDBManager::getOpenDbResult(void)` | 230 | Exported Function
`public: enum csf::HistoryManagerOpenResultEnum::HistoryManagerOpenResult __thiscall csf::ChatRoomHistoryManager::getInitialiseResult(void)` | 201 | Exported Function
`public: enum csf::HistoryMediaType __thiscall csf::ChatRoomHistoryItem::getMediaType(void)` | 215 | Exported Function
`public: enum csf::HistoryCallType __thiscall csf::HistoryItem::getCallType(void)` | 165 | Exported Function
`public: enum csf::HistoryContactResolved __thiscall csf::HistoryParticipant::getContactResolved(void)` | 169 | Exported Function
`public: enum csf::HistoryContactType __thiscall csf::HistoryParticipant::getContactType(void)` | 170 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::ChatRoomHistoryManager::getImEvents(__int64,int,bool)` | 198 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::ChatRoomHistoryManager::getMessages(class std::vector<__int64,class std::allocator<__int64> > &)` | 221 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::ChatRoomHistoryManager::getMessagesContaining(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,__int64,unsigned int)` | 222 | Exported Function
`public: class std::shared_ptr<class csf::HistoryMessage> __thiscall csf::HistoryItem::getMessage(void)` | 218 | Exported Function
`public: class std::shared_ptr<class csf::HistoryParticipant> __thiscall csf::HistoryItem::getLocalParticipant(void)` | 213 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomFilterUnreadMessages>,class std::allocator<class std::shared_ptr<class csf::ChatRoomFilterUnreadMessages> > > > __thiscall csf::HistoryManager::getFiltersUnreadMessagesCount(void)` | 190 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::ChatRoomHistoryManager::getMessagesNewerThan(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,unsigned int)` | 223 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::getQuickSearchMatchesFromRooms(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64,__int64,unsigned int)` | 238 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::getQuickSearchMatchesFromRoomsNewerThan(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64,unsigned int)` | 239 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::getQuickSearchMatchesFromRoomsOlderThan(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64,unsigned int)` | 240 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::ChatRoomHistoryManager::getMessagesOlderThan(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,unsigned int)` | 224 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::getChatRoomEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,int,bool)` | 166 | Exported Function
`public: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::getChatRoomFilterMatches(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 167 | Exported Function
`public: void __thiscall csf::HistoryManager::requestRoomUnreadMessagesCount(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 330 | Exported Function
`public: void __thiscall csf::HistoryManager::setDatabaseKey(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 343 | Exported Function
`public: void __thiscall csf::HistoryManager::setHistoryUserId(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 355 | Exported Function
`public: void __thiscall csf::HistoryManager::removeRemoteParticipantByNumber(__int64,char const *)` | 326 | Exported Function
`public: void __thiscall csf::HistoryManager::requestLastConsistentDateForRoom(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 328 | Exported Function
`public: void __thiscall csf::HistoryManager::requestRoomLastMessageDate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 329 | Exported Function
`public: void __thiscall csf::HistoryManager::uninitialize(void)` | 407 | Exported Function
`public: void __thiscall csf::HistoryManager::updateRemoteParticipant(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 415 | Exported Function
`public: void __thiscall csf::HistoryManager::updateRemoteParticipantByNumber(__int64,class std::shared_ptr<class csf::HistoryParticipant>,char const *)` | 416 | Exported Function
`public: void __thiscall csf::HistoryManager::updateRemoteParticipantByUid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::shared_ptr<class csf::HistoryParticipant>)` | 417 | Exported Function
`public: void __thiscall csf::HistoryManager::updateEvent(class std::shared_ptr<class csf::HistoryItem>)` | 409 | Exported Function
`public: void __thiscall csf::HistoryManager::updateLocalLineID(unsigned int)` | 410 | Exported Function
`public: void __thiscall csf::HistoryManager::updateLocalParticipant(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 411 | Exported Function
`public: void __thiscall csf::HistoryManager::addLocalParticipant(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 120 | Exported Function
`public: void __thiscall csf::HistoryManager::addRemoteParticipant(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 125 | Exported Function
`public: void __thiscall csf::HistoryManager::calculateAndNofityFilterLastMessageDate(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 129 | Exported Function
`public: void __thiscall csf::HistoryLabel::setSelector(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 396 | Exported Function
`public: void __thiscall csf::HistoryManager::addEvent(class std::shared_ptr<class csf::HistoryItem>,bool)` | 116 | Exported Function
`public: void __thiscall csf::HistoryManager::addEvents(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > >)` | 118 | Exported Function
`public: void __thiscall csf::HistoryManager::calculateAndNotifyFilterUnreadMessagesCount(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 130 | Exported Function
`public: void __thiscall csf::HistoryManager::queryConversationMessagesFromLocalHistory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<class std::shared_ptr<struct csf::SenderUidMessagesQuery>,class std::allocator<class std::shared_ptr<struct csf::SenderUidMessagesQuery> > > >)` | 310 | Exported Function
`public: void __thiscall csf::HistoryManager::removeLocalParticipant(__int64)` | 319 | Exported Function
`public: void __thiscall csf::HistoryManager::removeRemoteParticipant(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 325 | Exported Function
`public: void __thiscall csf::HistoryManager::deleteChatRoomEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >)` | 137 | Exported Function
`public: void __thiscall csf::HistoryManager::deleteRoom(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 143 | Exported Function
`public: void __thiscall csf::HistoryManager::queryConversationMessageFromLocalHistory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 308 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setJid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 370 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setLineID(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 374 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setMobilePhone(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 384 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setHomePhone(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 356 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setHuntGroup(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 357 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setId(__int64)` | 362 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setNameFromConversation(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 385 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setPreferredPhoneNumber(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 391 | Exported Function
`public: void __thiscall csf::Listenable<class csf::HistoryEventListener>::addListener(class std::shared_ptr<class csf::HistoryEventListener>)` | 119 | Exported Function
`public: void __thiscall csf::Listenable<class csf::HistoryEventListener>::removeListener(class std::shared_ptr<class csf::HistoryEventListener>)` | 318 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setNumberFromConversation(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 386 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setPhoneType(enum csf::HistoryPhoneType)` | 388 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setPhotoUri(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 389 | Exported Function
`public: void __thiscall csf::HistoryMessage::setLabel(class std::shared_ptr<class csf::HistoryLabel>)` | 372 | Exported Function
`public: void __thiscall csf::HistoryMessage::setPayload(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 387 | Exported Function
`public: void __thiscall csf::HistoryMessage::setSender(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 398 | Exported Function
`public: void __thiscall csf::HistoryMessage::setDate(__int64)` | 347 | Exported Function
`public: void __thiscall csf::HistoryMessage::setId(__int64)` | 361 | Exported Function
`public: void __thiscall csf::HistoryMessage::setItem(__int64)` | 369 | Exported Function
`public: void __thiscall csf::HistoryMessage::setType(int)` | 400 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setContactType(enum csf::HistoryContactType)` | 340 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setDefaultPhone(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 349 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setDisplayName(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 350 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setAccount(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 335 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setBusinessPhone(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 337 | Exported Function
`public: void __thiscall csf::HistoryParticipant::setContactResolved(enum csf::HistoryContactResolved)` | 339 | Exported Function
`public: void __thiscall csf::HistoryLabel::setMarking(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 376 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::notifyLastConsistentDate(void)` | 296 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::notifyLastMessageDate(void)` | 297 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::notifyUnreadMessageCount(void)` | 301 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::initialize(void)` | 267 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::notifyChatRoomMessageQueryResult(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class csf::ChatRoomHistoryMessage>)` | 289 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::notifyChatRoomMessagesQueryResult(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >)` | 290 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::queryConversationMessageFromLocalHistory(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 307 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setItem(__int64)` | 368 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setLabel(class std::shared_ptr<class csf::HistoryLabel>)` | 371 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setPlainText(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 390 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryManager::queryConversationMessagesFromLocalHistory(class std::shared_ptr<class std::vector<class std::shared_ptr<struct csf::SenderUidMessagesQuery>,class std::allocator<class std::shared_ptr<struct csf::SenderUidMessagesQuery> > > >)` | 309 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setDate(__int64)` | 345 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setId(__int64)` | 359 | Exported Function
`public: void __thiscall csf::ChatRoomFilterUnreadMessages::setFilterId(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 353 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setConversationVisible(bool)` | 341 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setDate(__int64)` | 344 | Exported Function
`public: virtual void __thiscall csf::HistoryManager::undeleteEvents(class std::vector<__int64,class std::allocator<__int64> > &)` | 405 | Exported Function
`public: virtual void __thiscall csf::InMemoryHistoryManager::initialize(void)` | 269 | Exported Function
`public: void __thiscall csf::ChatRoomFilterUnreadMessages::setCount(unsigned int)` | 342 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setHistoryConsistencyMessage(bool)` | 354 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setMediaType(enum csf::HistoryMediaType)` | 380 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setMessage(class std::shared_ptr<class csf::ChatRoomHistoryMessage>)` | 382 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setUid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 401 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setId(__int64)` | 358 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setIsDeleted(bool)` | 364 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryItem::setIsRead(bool)` | 366 | Exported Function
`public: void __thiscall csf::HistoryItem::setIsRead(bool)` | 367 | Exported Function
`public: void __thiscall csf::HistoryItem::setLocalParticipant(class std::shared_ptr<class csf::HistoryParticipant>)` | 375 | Exported Function
`public: void __thiscall csf::HistoryItem::setMediaType(enum csf::HistoryMediaType)` | 381 | Exported Function
`public: void __thiscall csf::HistoryItem::setId(__int64)` | 360 | Exported Function
`public: void __thiscall csf::HistoryItem::setIsConf(bool)` | 363 | Exported Function
`public: void __thiscall csf::HistoryItem::setIsDeleted(bool)` | 365 | Exported Function
`public: void __thiscall csf::HistoryItem::setMessage(class std::shared_ptr<class csf::HistoryMessage>)` | 383 | Exported Function
`public: void __thiscall csf::HistoryLabel::setBGColor(int)` | 336 | Exported Function
`public: void __thiscall csf::HistoryLabel::setFGColor(int)` | 352 | Exported Function
`public: void __thiscall csf::HistoryLabel::setLabelID(__int64)` | 373 | Exported Function
`public: void __thiscall csf::HistoryItem::setProtocolType(enum csf::HistoryProtocolType)` | 392 | Exported Function
`public: void __thiscall csf::HistoryItem::setRemoteParticipants(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryParticipant>,class std::allocator<class std::shared_ptr<class csf::HistoryParticipant> > > >)` | 393 | Exported Function
`public: void __thiscall csf::HistoryItem::setUid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 402 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setType(int)` | 399 | Exported Function
`public: void __thiscall csf::DBColumn::getValue(__int64 &)const ` | 257 | Exported Function
`public: void __thiscall csf::DBColumn::getValue(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > &)const ` | 256 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setRichText(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 394 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setRoomJid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 395 | Exported Function
`public: void __thiscall csf::ChatRoomHistoryMessage::setSender(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 397 | Exported Function
`public: void __thiscall csf::DBColumn::getValue(int &)const ` | 255 | Exported Function
`public: void __thiscall csf::HistoryItem::setCallType(enum csf::HistoryCallType)` | 338 | Exported Function
`public: void __thiscall csf::HistoryItem::setDate(__int64)` | 346 | Exported Function
`public: void __thiscall csf::HistoryItem::setDuration(__int64)` | 351 | Exported Function
`public: void __thiscall csf::FileSystemHistoryManager::setDbFilePath(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 348 | Exported Function
`public: void __thiscall csf::HistoryItem::addRemoteParticipant(class std::shared_ptr<class csf::HistoryParticipant>)` | 124 | Exported Function
`public: void __thiscall csf::HistoryItem::removeRemoteParticipant(class std::shared_ptr<class csf::HistoryParticipant>)` | 324 | Exported Function
`protected: virtual class csf::SecureString __thiscall csf::FileSystemHistoryManager::getEncryptKeyForSQLite(void)` | 183 | Exported Function
`protected: void __thiscall csf::ChatRoomHistoryManager::notifyMesssageAdded(class std::shared_ptr<class csf::ChatRoomHistoryItem>)` | 299 | Exported Function
`protected: void __thiscall csf::ChatRoomHistoryManager::notifyMesssageAddedForSearch(void)` | 300 | Exported Function
`protected: class std::shared_ptr<class csf::HistoryMessage> __thiscall csf::HistoryManager::findMessage(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 157 | Exported Function
`protected: int __thiscall csf::Listenable<class csf::HistoryEventListener>::countOfListeners(void)const ` | 134 | Exported Function
`protected: unsigned int __thiscall csf::ChatRoomHistoryManager::queryUnreadMessageCount(void)` | 314 | Exported Function
`protected: void __thiscall csf::ChatRoomHistoryManager::saveLastConsistentDate(void)` | 334 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryManager::getOldestMessageTimeInUTC(void)` | 229 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryMessage::getDate(void)` | 172 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryMessage::getId(void)` | 194 | Exported Function
`protected: void __thiscall csf::HistoryManager::updateMessage(int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 412 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryItem::getDate(void)` | 171 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryItem::getId(void)` | 193 | Exported Function
`protected: __thiscall csf::HistoryManager::HistoryManager(void)` | 39 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::HistoryManager>::enable_shared_from_this<class csf::HistoryManager>(class std::enable_shared_from_this<class csf::HistoryManager> const &)` | 2 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::HistoryManager>::enable_shared_from_this<class csf::HistoryManager>(void)` | 3 | Exported Function
`protected: __int64 __thiscall csf::ChatRoomHistoryManager::queryDBCreationTimeInUTC(void)` | 311 | Exported Function
`protected: __int64 __thiscall csf::ChatRoomHistoryManager::queryLastDateConsistency(void)` | 312 | Exported Function
`protected: __int64 __thiscall csf::ChatRoomHistoryManager::queryLastMessageDate(void)` | 313 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::HistoryManager>::~enable_shared_from_this<class csf::HistoryManager>(void)` | 50 | Exported Function
`protected: class std::enable_shared_from_this<class csf::HistoryManager> & __thiscall std::enable_shared_from_this<class csf::HistoryManager>::operator=(class std::enable_shared_from_this<class csf::HistoryManager> const &)` | 69 | Exported Function
`protected: class std::set<class std::weak_ptr<class csf::HistoryEventListener>,struct std::owner_less<class std::weak_ptr<class csf::HistoryEventListener> >,class std::allocator<class std::weak_ptr<class csf::HistoryEventListener> > > __thiscall csf::Listenable<class csf::HistoryEventListener>::getListeners(void)const ` | 212 | Exported Function
`protected: class std::shared_ptr<class csf::ChatRoomHistoryMessage> __thiscall csf::ChatRoomHistoryManager::findMessage(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 156 | Exported Function
`protected: bool __thiscall csf::ChatRoomHistoryManager::saveChatRoomHistoryItem(class std::shared_ptr<class csf::ChatRoomHistoryItem>)` | 332 | Exported Function
`protected: bool __thiscall csf::ChatRoomHistoryManager::saveChatRoomHistoryMessage(class std::shared_ptr<class csf::ChatRoomHistoryMessage>,__int64)` | 333 | Exported Function
`protected: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryManager::extractSearchTerms(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 152 | Exported Function
`public: __thiscall csf::ChatRoomHistoryDBManager::ChatRoomHistoryDBManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 8 | Exported Function
`public: __thiscall csf::ChatRoomHistoryItem::ChatRoomHistoryItem(class csf::ChatRoomHistoryItem const &)` | 9 | Exported Function
`public: __thiscall csf::ChatRoomHistoryItem::ChatRoomHistoryItem(void)` | 10 | Exported Function
`public: __thiscall csf::ChatRoomFilterUnreadMessages::ChatRoomFilterUnreadMessages(void)` | 6 | Exported Function
`public: __thiscall csf::ChatRoomFilterUnreadMessages::~ChatRoomFilterUnreadMessages(void)` | 51 | Exported Function
`public: __thiscall csf::ChatRoomHistoryDBManager::ChatRoomHistoryDBManager(class csf::ChatRoomHistoryDBManager const &)` | 7 | Exported Function
`public: __thiscall csf::ChatRoomHistoryItem::~ChatRoomHistoryItem(void)` | 53 | Exported Function
`public: __thiscall csf::ChatRoomHistoryMessage::~ChatRoomHistoryMessage(void)` | 55 | Exported Function
`public: __thiscall csf::DBColumn::DBColumn(class csf::DBColumn &&)` | 14 | Exported Function
`public: __thiscall csf::DBColumn::DBColumn(class csf::DBColumn const &)` | 15 | Exported Function
`public: __thiscall csf::ChatRoomHistoryManager::ChatRoomHistoryManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::set<class std::weak_ptr<class csf::HistoryEventListener>,struct std::owner_less<class std::weak_ptr<class csf::HistoryEventListener> >,class std::allocator<class std::weak_ptr<class csf::HistoryEventListener> > >,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,bool)` | 11 | Exported Function
`public: __thiscall csf::ChatRoomHistoryMessage::ChatRoomHistoryMessage(class csf::ChatRoomHistoryMessage const &)` | 12 | Exported Function
`public: __thiscall csf::ChatRoomHistoryMessage::ChatRoomHistoryMessage(void)` | 13 | Exported Function
`public: __int64 __thiscall csf::HistoryItem::getId(void)` | 195 | Exported Function
`public: __int64 __thiscall csf::HistoryLabel::getLabelID(void)` | 208 | Exported Function
`public: __int64 __thiscall csf::HistoryManager::getLastMessageDateForItem(class std::shared_ptr<class csf::HistoryItem>)` | 210 | Exported Function
`public: __int64 __thiscall csf::ChatRoomHistoryMessage::getItem(void)` | 202 | Exported Function
`public: __int64 __thiscall csf::HistoryItem::getDate(void)` | 173 | Exported Function
`public: __int64 __thiscall csf::HistoryItem::getDuration(void)` | 182 | Exported Function
`public: __int64 __thiscall csf::HistoryManager::getRoomFirstMessageTimeInUTC(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 245 | Exported Function
`public: __int64 __thiscall csf::HistoryParticipant::getId(void)` | 197 | Exported Function
`public: __thiscall csf::ChatRoomFilterUnreadMessages::ChatRoomFilterUnreadMessages(class csf::ChatRoomFilterUnreadMessages &&)` | 4 | Exported Function
`public: __thiscall csf::ChatRoomFilterUnreadMessages::ChatRoomFilterUnreadMessages(class csf::ChatRoomFilterUnreadMessages const &)` | 5 | Exported Function
`public: __int64 __thiscall csf::HistoryMessage::getDate(void)` | 174 | Exported Function
`public: __int64 __thiscall csf::HistoryMessage::getId(void)` | 196 | Exported Function
`public: __int64 __thiscall csf::HistoryMessage::getItem(void)` | 203 | Exported Function
`private: void __thiscall csf::HistoryManager::removeRemoteParticipantInternal(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 327 | Exported Function
`private: bool __thiscall csf::HistoryManager::filterViewExists(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 155 | Exported Function
`private: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryManager::getFileNameFromJid(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 186 | Exported Function
`private: class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > > __thiscall csf::HistoryManager::fitNumberOfResults(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::ChatRoomHistoryItem>,class std::allocator<class std::shared_ptr<class csf::ChatRoomHistoryItem> > > >,unsigned int)` | 158 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::rekeyDatabase(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &)` | 315 | Exported Function
`private: bool __thiscall csf::HistoryManager::attachDatabase(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 127 | Exported Function
`private: bool __thiscall csf::HistoryManager::detachDatabase(void)` | 144 | Exported Function
`private: class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::HistoryManager::getJidsForCleanup(int)` | 205 | Exported Function
`private: static class std::shared_ptr<class csf::HistoryManager> csf::HistoryManager::fileInstance` | 153 | Exported Function
`private: static class std::shared_ptr<class csf::HistoryManager> csf::HistoryManager::inMemoryInstance` | 265 | Exported Function
`private: unsigned int __thiscall csf::HistoryManager::getFilterUnreadMessagesCount(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 189 | Exported Function
`private: static class csf::Mutex csf::FileSystemHistoryManager::monitor` | 286 | Exported Function
`private: static class csf::Mutex csf::HistoryManager::monitor` | 287 | Exported Function
`private: static class csf::Mutex csf::InMemoryHistoryManager::monitor` | 288 | Exported Function
`const csf::HistoryEventListener::``vftable'` | 102 | Exported Function
`const csf::HistoryManager::``vftable'` | 103 | Exported Function
`const csf::InMemoryHistoryManager::``vftable'` | 104 | Exported Function
`const csf::ChatRoomHistoryDBManager::``vftable'` | 99 | Exported Function
`const csf::ChatRoomHistoryManager::``vftable'` | 100 | Exported Function
`const csf::FileSystemHistoryManager::``vftable'` | 101 | Exported Function
`const csf::SQLiteCommand::``vftable'` | 105 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::exportDatabase(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class csf::SecureString const &)` | 151 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::isColumnAlreadyInTable(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 270 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::isDatabaseOpen(void)` | 272 | Exported Function
`private: __int64 __thiscall csf::HistoryManager::getFilterMatchLastMessageTimeStamp(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 188 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::checkTableExists(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 131 | Exported Function
`private: bool __thiscall csf::ChatRoomHistoryDBManager::createNewDatabase(void)` | 136 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyEventUpdated(class std::shared_ptr<class csf::HistoryItem>)` | 292 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyFilterLastMessageDateChanged(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64)` | 294 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyFilterUnreadCountChanged(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,unsigned int)` | 295 | Exported Function
`private: void __thiscall csf::HistoryManager::loadParticipantForItemVector(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > >)` | 283 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyEventAdded(class std::shared_ptr<class csf::HistoryItem>)` | 291 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyEventsPurged(class std::vector<__int64,class std::allocator<__int64> >,bool)` | 293 | Exported Function
`private: void __thiscall csf::HistoryManager::notifyLocalNumberUpdated(void)` | 298 | Exported Function
`private: void __thiscall csf::HistoryManager::removeOldCallEvents(int)` | 321 | Exported Function
`private: void __thiscall csf::HistoryManager::removeOldImEvents(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int,bool)` | 322 | Exported Function
`private: void __thiscall csf::HistoryManager::removeOldImEvents(int)` | 323 | Exported Function
`private: void __thiscall csf::HistoryManager::purgeEventsInternal(class std::vector<__int64,class std::allocator<__int64> > &,bool)` | 305 | Exported Function
`private: void __thiscall csf::HistoryManager::removeChatRoomHistoryManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 316 | Exported Function
`private: void __thiscall csf::HistoryManager::removeLocalParticipantInternal(__int64)` | 320 | Exported Function
`private: void __thiscall csf::ChatRoomHistoryDBManager::createIMLabelIfNotExists(void)` | 135 | Exported Function
`private: void __thiscall csf::ChatRoomHistoryDBManager::deleteCurrentDatabaseAndCreateNew(void)` | 138 | Exported Function
`private: void __thiscall csf::HistoryManager::addLocalParticipantInternal(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 121 | Exported Function
`private: void __thiscall csf::ChatRoomHistoryDBManager::addNewColumnIfNotExists(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 123 | Exported Function
`private: void __thiscall csf::ChatRoomHistoryDBManager::closeDatabaseConnection(void)` | 132 | Exported Function
`private: void __thiscall csf::ChatRoomHistoryDBManager::CreateFtsVTable(bool)` | 106 | Exported Function
`private: void __thiscall csf::HistoryManager::addMessageInternal(class std::shared_ptr<class csf::HistoryMessage>)` | 122 | Exported Function
`private: void __thiscall csf::HistoryManager::loadDatesForItemVector(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > >)` | 280 | Exported Function
`private: void __thiscall csf::HistoryManager::loadMessage(class std::shared_ptr<class csf::HistoryItem>)` | 281 | Exported Function
`private: void __thiscall csf::HistoryManager::loadMessageForItemVector(class std::shared_ptr<class std::vector<class std::shared_ptr<class csf::HistoryItem>,class std::allocator<class std::shared_ptr<class csf::HistoryItem> > > >)` | 282 | Exported Function
`private: void __thiscall csf::HistoryManager::addRemoteParticipantInternal(__int64,class std::shared_ptr<class csf::HistoryParticipant>)` | 126 | Exported Function
`private: void __thiscall csf::HistoryManager::ensureFilterViewExist(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 146 | Exported Function
`private: void __thiscall csf::HistoryManager::getMessageIdsFromFilterMatch(class std::vector<__int64,class std::allocator<__int64> > &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 219 | Exported Function
`public: class csf::ChatRoomHistoryMessage & __thiscall csf::ChatRoomHistoryMessage::operator=(class csf::ChatRoomHistoryMessage const &)` | 74 | Exported Function
`public: class csf::DBColumn & __thiscall csf::DBColumn::operator=(class csf::DBColumn &&)` | 75 | Exported Function
`public: class csf::DBColumn & __thiscall csf::DBColumn::operator=(class csf::DBColumn const &)` | 76 | Exported Function
`public: class csf::ChatRoomFilterUnreadMessages & __thiscall csf::ChatRoomFilterUnreadMessages::operator=(class csf::ChatRoomFilterUnreadMessages const &)` | 71 | Exported Function
`public: class csf::ChatRoomHistoryDBManager & __thiscall csf::ChatRoomHistoryDBManager::operator=(class csf::ChatRoomHistoryDBManager const &)` | 72 | Exported Function
`public: class csf::ChatRoomHistoryItem & __thiscall csf::ChatRoomHistoryItem::operator=(class csf::ChatRoomHistoryItem const &)` | 73 | Exported Function
`public: class csf::DBParam & __thiscall csf::DBParam::operator=(class csf::DBParam &&)` | 77 | Exported Function
`public: class csf::DBResultSet & __thiscall csf::DBResultSet::operator=(class csf::DBResultSet &&)` | 81 | Exported Function
`public: class csf::DBResultSet & __thiscall csf::DBResultSet::operator=(class csf::DBResultSet const &)` | 82 | Exported Function
`public: class csf::DBRow & __thiscall csf::DBRow::operator=(class csf::DBRow &&)` | 83 | Exported Function
`public: class csf::DBParam & __thiscall csf::DBParam::operator=(class csf::DBParam const &)` | 78 | Exported Function
`public: class csf::DBParamSet & __thiscall csf::DBParamSet::operator=(class csf::DBParamSet &&)` | 79 | Exported Function
`public: class csf::DBParamSet & __thiscall csf::DBParamSet::operator=(class csf::DBParamSet const &)` | 80 | Exported Function
`public: bool __thiscall csf::DBColumn::isString(void)const ` | 279 | Exported Function
`public: bool __thiscall csf::HistoryItem::IsConf(void)` | 109 | Exported Function
`public: bool __thiscall csf::HistoryItem::IsDeleted(void)` | 111 | Exported Function
`public: bool __thiscall csf::DBColumn::isInt32(void)const ` | 275 | Exported Function
`public: bool __thiscall csf::DBColumn::isInt64(void)const ` | 276 | Exported Function
`public: bool __thiscall csf::DBColumn::isNull(void)const ` | 277 | Exported Function
`public: bool __thiscall csf::HistoryItem::IsRead(void)` | 113 | Exported Function
`public: bool __thiscall csf::HistoryManager::haveMessagesOlderThan(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64)` | 264 | Exported Function
`public: bool __thiscall csf::HistoryManager::updateOrCreateRoomLastViewTime(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64)` | 414 | Exported Function
`public: class csf::ChatRoomFilterUnreadMessages & __thiscall csf::ChatRoomFilterUnreadMessages::operator=(class csf::ChatRoomFilterUnreadMessages &&)` | 70 | Exported Function
`public: bool __thiscall csf::HistoryManager::deleteFilterMatchesByRoom(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 141 | Exported Function
`public: bool __thiscall csf::HistoryManager::haveMessagesInTimeRange(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64,__int64)` | 262 | Exported Function
`public: bool __thiscall csf::HistoryManager::haveMessagesNewerThan(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,__int64)` | 263 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryItem::getUid(void)` | 252 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryManager::escapeSQLSpecialCharacters(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 147 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryManager::prepareSearchTerm(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 302 | Exported Function
`public: class csf::SQLiteErrorCodes & __thiscall csf::SQLiteErrorCodes::operator=(class csf::SQLiteErrorCodes const &)` | 97 | Exported Function
`public: class csf::SQLiteStatement & __thiscall csf::SQLiteStatement::operator=(class csf::SQLiteStatement const &)` | 98 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomFilterUnreadMessages::filterId(void)const ` | 154 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryManager::removeInterpunctualCharacters(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 317 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryMessage::getSender(void)` | 248 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::FileSystemHistoryManager::getDbFilePath(void)` | 175 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::HistoryItem::getUid(void)` | 253 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryMessage::getPlainText(void)` | 235 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryMessage::getRichText(void)` | 244 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::ChatRoomHistoryMessage::getRoomJid(void)` | 246 | Exported Function
`public: class csf::HistoryItem & __thiscall csf::HistoryItem::operator=(class csf::HistoryItem &&)` | 87 | Exported Function
`public: class csf::HistoryItem & __thiscall csf::HistoryItem::operator=(class csf::HistoryItem const &)` | 88 | Exported Function
`public: class csf::HistoryLabel & __thiscall csf::HistoryLabel::operator=(class csf::HistoryLabel &&)` | 89 | Exported Function
`public: class csf::DBRow & __thiscall csf::DBRow::operator=(class csf::DBRow const &)` | 84 | Exported Function
`public: class csf::HistoryEventListener & __thiscall csf::HistoryEventListener::operator=(class csf::HistoryEventListener &&)` | 85 | Exported Function
`public: class csf::HistoryEventListener & __thiscall csf::HistoryEventListener::operator=(class csf::HistoryEventListener const &)` | 86 | Exported Function
`public: class csf::HistoryLabel & __thiscall csf::HistoryLabel::operator=(class csf::HistoryLabel const &)` | 90 | Exported Function
`public: class csf::HistoryParticipant & __thiscall csf::HistoryParticipant::operator=(class csf::HistoryParticipant const &)` | 94 | Exported Function
`public: class csf::SQLiteCommand & __thiscall csf::SQLiteCommand::operator=(class csf::SQLiteCommand const &)` | 95 | Exported Function
`public: class csf::SQLiteErrorCodes & __thiscall csf::SQLiteErrorCodes::operator=(class csf::SQLiteErrorCodes &&)` | 96 | Exported Function
`public: class csf::HistoryMessage & __thiscall csf::HistoryMessage::operator=(class csf::HistoryMessage &&)` | 91 | Exported Function
`public: class csf::HistoryMessage & __thiscall csf::HistoryMessage::operator=(class csf::HistoryMessage const &)` | 92 | Exported Function
`public: class csf::HistoryParticipant & __thiscall csf::HistoryParticipant::operator=(class csf::HistoryParticipant &&)` | 93 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::updateRoomLastViewTime(__int64,bool)` | 418 | Exported Function
`public: __thiscall csf::DBRow::DBRow(void)` | 28 | Exported Function
`public: __thiscall csf::DBRow::~DBRow(void)` | 60 | Exported Function
`public: __thiscall csf::FileSystemHistoryManager::FileSystemHistoryManager(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 29 | Exported Function
`public: __thiscall csf::DBResultSet::~DBResultSet(void)` | 59 | Exported Function
`public: __thiscall csf::DBRow::DBRow(class csf::DBRow &&)` | 26 | Exported Function
`public: __thiscall csf::DBRow::DBRow(class csf::DBRow const &)` | 27 | Exported Function
`public: __thiscall csf::HistoryEventListener::HistoryEventListener(class csf::HistoryEventListener &&)` | 30 | Exported Function
`public: __thiscall csf::HistoryItem::HistoryItem(class csf::HistoryItem const &)` | 34 | Exported Function
`public: __thiscall csf::HistoryItem::HistoryItem(void)` | 35 | Exported Function
`public: __thiscall csf::HistoryItem::~HistoryItem(void)` | 62 | Exported Function
`public: __thiscall csf::HistoryEventListener::HistoryEventListener(class csf::HistoryEventListener const &)` | 31 | Exported Function
`public: __thiscall csf::HistoryEventListener::HistoryEventListener(void)` | 32 | Exported Function
`public: __thiscall csf::HistoryItem::HistoryItem(class csf::HistoryItem &&)` | 33 | Exported Function
`public: __thiscall csf::DBParam::DBParam(class csf::DBParam const &)` | 18 | Exported Function
`public: __thiscall csf::DBParam::DBParam(void)` | 19 | Exported Function
`public: __thiscall csf::DBParam::~DBParam(void)` | 57 | Exported Function
`public: __thiscall csf::DBColumn::DBColumn(void)` | 16 | Exported Function
`public: __thiscall csf::DBColumn::~DBColumn(void)` | 56 | Exported Function
`public: __thiscall csf::DBParam::DBParam(class csf::DBParam &&)` | 17 | Exported Function
`public: __thiscall csf::DBParamSet::DBParamSet(class csf::DBParamSet &&)` | 20 | Exported Function
`public: __thiscall csf::DBResultSet::DBResultSet(class csf::DBResultSet &&)` | 23 | Exported Function
`public: __thiscall csf::DBResultSet::DBResultSet(class csf::DBResultSet const &)` | 24 | Exported Function
`public: __thiscall csf::DBResultSet::DBResultSet(void)` | 25 | Exported Function
`public: __thiscall csf::DBParamSet::DBParamSet(class csf::DBParamSet const &)` | 21 | Exported Function
`public: __thiscall csf::DBParamSet::DBParamSet(void)` | 22 | Exported Function
`public: __thiscall csf::DBParamSet::~DBParamSet(void)` | 58 | Exported Function
`public: __thiscall csf::SQLiteStatement::SQLiteStatement(class csf::SQLiteStatement const &)` | 48 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryItem::isConversationVisible(void)const ` | 271 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryItem::IsDeleted(void)` | 110 | Exported Function
`public: __thiscall csf::Listenable<class csf::HistoryEventListener>::Listenable<class csf::HistoryEventListener>(void)` | 1 | Exported Function
`public: __thiscall csf::Listenable<class csf::HistoryEventListener>::~Listenable<class csf::HistoryEventListener>(void)` | 49 | Exported Function
`public: __thiscall csf::SQLiteCommand::SQLiteCommand(class csf::SQLiteCommand const &)` | 47 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryItem::isHistoryConsistencyMessage(void)const ` | 273 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::hasMessagesOlderThan(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64)` | 261 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::isInitialized(void)` | 274 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::updateChatRoomHistoryMessage(class std::shared_ptr<class csf::ChatRoomHistoryMessage>,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 408 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryItem::IsRead(void)` | 112 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::hasMessagesInTimeRange(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64,__int64)` | 259 | Exported Function
`public: bool __thiscall csf::ChatRoomHistoryManager::hasMessagesNewerThan(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,__int64)` | 260 | Exported Function
`public: __thiscall csf::HistoryLabel::~HistoryLabel(void)` | 63 | Exported Function
`public: __thiscall csf::HistoryMessage::HistoryMessage(class csf::HistoryMessage &&)` | 40 | Exported Function
`public: __thiscall csf::HistoryMessage::HistoryMessage(class csf::HistoryMessage const &)` | 41 | Exported Function
`public: __thiscall csf::HistoryLabel::HistoryLabel(class csf::HistoryLabel &&)` | 36 | Exported Function
`public: __thiscall csf::HistoryLabel::HistoryLabel(class csf::HistoryLabel const &)` | 37 | Exported Function
`public: __thiscall csf::HistoryLabel::HistoryLabel(void)` | 38 | Exported Function
`public: __thiscall csf::HistoryMessage::HistoryMessage(void)` | 42 | Exported Function
`public: __thiscall csf::HistoryParticipant::HistoryParticipant(void)` | 45 | Exported Function
`public: __thiscall csf::HistoryParticipant::~HistoryParticipant(void)` | 66 | Exported Function
`public: __thiscall csf::InMemoryHistoryManager::InMemoryHistoryManager(void)` | 46 | Exported Function
`public: __thiscall csf::HistoryMessage::~HistoryMessage(void)` | 65 | Exported Function
`public: __thiscall csf::HistoryParticipant::HistoryParticipant(class csf::HistoryParticipant &&)` | 43 | Exported Function
`public: __thiscall csf::HistoryParticipant::HistoryParticipant(class csf::HistoryParticipant const &)` | 44 | Exported Function


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

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/819f4d6b1e3015a5d865757f3e8fa009e05360064e3d5881f44dba9432288748/detection/




MIT License. Copyright (c) 2020 Strontic.


