---
title: dnsutils.dll | 
excerpt: What is dnsutils.dll?
---

# dnsutils.dll 

* File Path: `C:\Program Files (x86)\Cisco Systems\Cisco Jabber\dnsutils.dll`

## Hashes

Type | Hash
-- | --
MD5 | `33BD9697DADE4D5F7C6F32D406270E94`
SHA1 | `3A7066F65A091D9493F9A307092B5D8894B218F4`
SHA256 | `5241C99361F17228F3B244807C94A583BEE79F5F119F8F943B9C1A3C34FC1410`
SHA384 | `28A3AB136458CA4F3D76C97031A09CA07ADFC61470157F1740B9612311318F8F79BB5E4C6457D931848729D60EAE3999`
SHA512 | `6515C668EEBA24D2853BD94B100BA6A60239647FB4C9619B594E4EB3876FD3C79BD73E999382D464F5D778F4AF130E9536B2D40EC3E0374EF3C981199B52A1EE`
SSDEEP | `3072:TxJ8UvD3GXl+aOu+0ti/2NnFlEEKFS8baTzFfGh/:TfFrg+BZEObaTzK`
IMP | `3484969A19C304B9B8049249F387413E`
PESHA1 | `162BDA0E64936EFB289767456CDDC859E78B1A9F`
PE256 | `ED781770271C285BE82D62707759465B2217E1703BDC8F8534C56A537A6EB9AD`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: class std::weak_ptr<class csf::dns::DnsQueryResolverImpl const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::weak_from_this(void)const ` | 159 | Exported Function
`public: class std::weak_ptr<class csf::dns::DnsQuery> __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::weak_from_this(void)` | 156 | Exported Function
`public: enum csf::dns::DnsQueryType __thiscall csf::dns::DnsQuery::getType(void)const ` | 138 | Exported Function
`public: class std::weak_ptr<class csf::dns::DnsQueryResolverImpl> __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::weak_from_this(void)` | 158 | Exported Function
`public: class std::weak_ptr<class csf::dns::DnsQuery const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::weak_from_this(void)const ` | 157 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQueryResolverImpl> __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::shared_from_this(void)` | 153 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQueryResolverImpl const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::shared_from_this(void)const ` | 154 | Exported Function
`public: class std::vector<class std::shared_ptr<class csf::dns::DnsQuery>,class std::allocator<class std::shared_ptr<class csf::dns::DnsQuery> > > __thiscall csf::dns::DnsRequest::getDnsQueries(void)const ` | 118 | Exported Function
`public: class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > __thiscall csf::dns::DnsQuery::getRequests(void)const ` | 132 | Exported Function
`public: enum csf::dns::DnsQueryType __thiscall csf::dns::QueryResponse::getType(void)const ` | 139 | Exported Function
`public: static class std::shared_ptr<class csf::dns::DnsQuery> __cdecl csf::dns::DnsQuery::createDnsQuery(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,enum csf::dns::DnsQueryType)` | 95 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const __cdecl csf::dns::DnsUtils::getCustomNameServerAddress(void)` | 117 | Exported Function
`public: static class std::shared_ptr<class csf::dns::DnsResponse> __cdecl csf::dns::DnsUtils::excuteDnsQueriesInParallel(class std::shared_ptr<class csf::dns::DnsRequest>,int)` | 100 | Exported Function
`public: static class std::shared_ptr<class csf::dns::DnsRequest> __cdecl csf::dns::DnsRequest::createDnsRequest(class std::vector<class std::shared_ptr<class csf::dns::DnsQuery>,class std::allocator<class std::shared_ptr<class csf::dns::DnsQuery> > >)` | 97 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const __cdecl csf::dns::DnsUtils::convertIpV6ToArpaEntry(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 94 | Exported Function
`public: int __thiscall csf::dns::ARecord::getTtl(void)const ` | 137 | Exported Function
`public: int __thiscall csf::dns::AAAARecord::getTtl(void)const ` | 136 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const __cdecl csf::dns::DnsUtils::convertIpV4ToArpaEntry(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >)` | 93 | Exported Function
`public: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const __cdecl csf::dns::DnsUtils::convertIpToArpaEntry(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 92 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQuery> __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::shared_from_this(void)` | 151 | Exported Function
`public: class csf::dns::SOARecord & __thiscall csf::dns::SOARecord::operator=(class csf::dns::SOARecord const &)` | 71 | Exported Function
`public: class csf::dns::ServiceResourceRecord & __thiscall csf::dns::ServiceResourceRecord::operator=(class csf::dns::ServiceResourceRecord const &)` | 72 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::AAAARecord::getIP6Address(void)const ` | 125 | Exported Function
`public: class csf::dns::TXTRecord const & __thiscall csf::dns::TXTRecord::operator=(class csf::dns::TXTRecord const &)` | 73 | Exported Function
`public: class csf::dns::QueryResponse & __thiscall csf::dns::QueryResponse::operator=(class csf::dns::QueryResponse const &)` | 70 | Exported Function
`public: class csf::dns::DnsUtilsScopedSetCustomServerAddress & __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::operator=(class csf::dns::DnsUtilsScopedSetCustomServerAddress const &)` | 67 | Exported Function
`public: class csf::dns::DnsUtilsInterface & __thiscall csf::dns::DnsUtilsInterface::operator=(class csf::dns::DnsUtilsInterface const &)` | 66 | Exported Function
`public: class csf::dns::QueryResponse & __thiscall csf::dns::QueryResponse::operator=(class csf::dns::QueryResponse &&)` | 69 | Exported Function
`public: class csf::dns::PointerRecord & __thiscall csf::dns::PointerRecord::operator=(class csf::dns::PointerRecord const &)` | 68 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::AAAARecord::getName(void)const ` | 127 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::SOARecord::getPrimaryNameServer(void)const ` | 130 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::SOARecord::getHostName(void)const ` | 123 | Exported Function
`public: class std::shared_ptr<class csf::dns::DnsQuery const > __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::shared_from_this(void)const ` | 152 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const __thiscall csf::dns::TXTRecord::getText(void)const ` | 134 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::ServiceResourceRecord::getTarget(void)const ` | 133 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::ARecord::getName(void)const ` | 128 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::ARecord::getIP4Address(void)const ` | 124 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::PointerRecord::getIpArpaEntry(void)const ` | 126 | Exported Function
`public: class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __thiscall csf::dns::PointerRecord::getHostName(void)const ` | 122 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executeAAAARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::AAAARecord,class std::allocator<class csf::dns::AAAARecord> > &)` | 103 | Exported Function
`public: virtual class std::vector<class std::shared_ptr<class csf::dns::QueryResponse>,class std::allocator<class std::shared_ptr<class csf::dns::QueryResponse> > > __thiscall csf::dns::DnsResponse::getDnsResponsesOfType(enum csf::dns::DnsQueryType)const ` | 120 | Exported Function
`public: virtual class std::vector<class std::shared_ptr<class csf::dns::QueryResponse>,class std::allocator<class std::shared_ptr<class csf::dns::QueryResponse> > > __thiscall csf::dns::DnsResponse::getDnsResponsesForRequest(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::dns::DnsQueryType)const ` | 119 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executeAAAARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::AAAARecord,class std::allocator<class csf::dns::AAAARecord> > &)` | 104 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsResponse::getDnsResultCodeForRequest(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::dns::DnsQueryType)const ` | 121 | Exported Function
`public: virtual class std::shared_ptr<class csf::dns::DnsResponse> __thiscall csf::dns::DnsUtilsImpl::excuteDnsQueriesInParallel(class std::shared_ptr<class csf::dns::DnsRequest>,int)` | 101 | Exported Function
`public: virtual class std::shared_ptr<class csf::dns::DnsQuery> __thiscall csf::dns::DnsUtilsImpl::createDnsQuery(class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &,enum csf::dns::DnsQueryType)` | 96 | Exported Function
`public: virtual bool __thiscall csf::dns::DnsResponse::isTimeouted(void)const ` | 141 | Exported Function
`public: virtual class std::shared_ptr<class csf::dns::DnsResponse> __thiscall csf::dns::DnsQueryResolverImpl::executeDnsQueriesInParallel(class std::shared_ptr<class csf::dns::DnsRequest>,int)` | 107 | Exported Function
`public: virtual class std::shared_ptr<class csf::dns::DnsRequest> __thiscall csf::dns::DnsUtilsImpl::createDnsRequest(class std::vector<class std::shared_ptr<class csf::dns::DnsQuery>,class std::allocator<class std::shared_ptr<class csf::dns::DnsQuery> > >)` | 98 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executeARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::ARecord,class std::allocator<class csf::dns::ARecord> > &)` | 106 | Exported Function
`public: void __thiscall csf::dns::DnsQuery::cancel(void)` | 91 | Exported Function
`public: void __thiscall csf::dns::DnsQuery::addListener(class std::shared_ptr<class csf::dns::DnsQueryListener>)` | 89 | Exported Function
`public: void __thiscall csf::dns::ServiceResourceRecordSorter::sortRecords(void)` | 155 | Exported Function
`public: void __thiscall csf::dns::DnsQuery::execute(void)` | 102 | Exported Function
`public: virtual void __thiscall csf::dns::DnsQueryResolverImpl::onDnsQueryResultReceived(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::dns::DnsQueryType,enum csf::dns::DnsQueryResult::Result,class std::vector<class std::shared_ptr<class csf::dns::QueryResponse>,class std::allocator<class std::shared_ptr<class csf::dns::QueryResponse> > > const &)` | 143 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executeSOARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::SOARecord,class std::allocator<class csf::dns::SOARecord> > &)` | 111 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executePtrRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::PointerRecord,class std::allocator<class csf::dns::PointerRecord> > &)` | 109 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executeTXTRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::TXTRecord,class std::allocator<class csf::dns::TXTRecord> > &)` | 115 | Exported Function
`public: virtual enum csf::dns::DnsQueryResult::Result __thiscall csf::dns::DnsUtilsImpl::executeSRVRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 113 | Exported Function
`public: virtual __thiscall csf::dns::DnsUtilsInterface::~DnsUtilsInterface(void)` | 48 | Exported Function
`public: static void __cdecl csf::dns::DnsUtils::setCustomNameServerAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 148 | Exported Function
`public: static int __cdecl csf::dns::DnsUtils::GetIpAddressFamily(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 87 | Exported Function
`public: struct csf::dns::DnsQueryResult & __thiscall csf::dns::DnsQueryResult::operator=(struct csf::dns::DnsQueryResult &&)` | 62 | Exported Function
`public: static void __cdecl csf::dns::DnsUtils::setDNSServerIpAddressesFunc(class std::function<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > __cdecl(void)>)` | 149 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executeTXTRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::TXTRecord,class std::allocator<class csf::dns::TXTRecord> > &)` | 114 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executePtrRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::PointerRecord,class std::allocator<class csf::dns::PointerRecord> > &)` | 108 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executeARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::ARecord,class std::allocator<class csf::dns::ARecord> > &)` | 105 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executeSRVRecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 112 | Exported Function
`public: static enum csf::dns::DnsQueryResult::Result __cdecl csf::dns::DnsUtils::executeSOARecordQuery(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::vector<class csf::dns::SOARecord,class std::allocator<class csf::dns::SOARecord> > &)` | 110 | Exported Function
`public: struct csf::dns::DnsQueryResult & __thiscall csf::dns::DnsQueryResult::operator=(struct csf::dns::DnsQueryResult const &)` | 63 | Exported Function
`public: virtual __thiscall csf::dns::DnsQueryResolverImpl::~DnsQueryResolverImpl(void)` | 44 | Exported Function
`public: virtual __thiscall csf::dns::DnsQueryResolver::~DnsQueryResolver(void)` | 43 | Exported Function
`public: virtual __thiscall csf::dns::DnsUtilsImpl::~DnsUtilsImpl(void)` | 47 | Exported Function
`public: virtual __thiscall csf::dns::DnsResponse::~DnsResponse(void)` | 46 | Exported Function
`public: virtual __thiscall csf::dns::DnsQueryListener::~DnsQueryListener(void)` | 42 | Exported Function
`public: unsigned int __thiscall csf::dns::ServiceResourceRecord::getPort(void)const ` | 129 | Exported Function
`public: unsigned int __thiscall csf::dns::DnsQuery::numOfDnsQueries(void)const ` | 142 | Exported Function
`public: unsigned int __thiscall csf::dns::ServiceResourceRecord::getWeight(void)const ` | 140 | Exported Function
`public: unsigned int __thiscall csf::dns::ServiceResourceRecord::getPriority(void)const ` | 131 | Exported Function
`public: class csf::dns::DnsUtilsImpl & __thiscall csf::dns::DnsUtilsImpl::operator=(class csf::dns::DnsUtilsImpl const &)` | 65 | Exported Function
`protected: __thiscall csf::dns::DnsResponse::DnsResponse(void)` | 17 | Exported Function
`private: void __thiscall csf::dns::ServiceResourceRecordSorter::randomlySortResourceRecordVectorByWeight(class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 147 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::enable_shared_from_this<class csf::dns::DnsQuery>(class std::enable_shared_from_this<class csf::dns::DnsQuery> const &)` | 1 | Exported Function
`protected: __thiscall csf::dns::QueryResponse::QueryResponse(enum csf::dns::DnsQueryType)` | 27 | Exported Function
`private: void __thiscall csf::dns::ServiceResourceRecordSorter::randomizeWithinPriority(void)` | 146 | Exported Function
`private: void __thiscall csf::dns::DnsResponse::setTimeouted(bool)` | 150 | Exported Function
`private: void __thiscall csf::dns::DnsResponse::addQueryResponse(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,enum csf::dns::DnsQueryType,enum csf::dns::DnsQueryResult::Result,class std::vector<class std::shared_ptr<class csf::dns::QueryResponse>,class std::allocator<class std::shared_ptr<class csf::dns::QueryResponse> > > const &)` | 90 | Exported Function
`private: void __thiscall csf::dns::ServiceResourceRecordSorter::randomizeByWeight(class std::_Vector_iterator<class std::_Vector_val<struct std::_Simple_types<class csf::dns::ServiceResourceRecord> > >,class std::_Vector_iterator<class std::_Vector_val<struct std::_Simple_types<class csf::dns::ServiceResourceRecord> > >)` | 145 | Exported Function
`private: void __thiscall csf::dns::ServiceResourceRecordSorter::extractZeroWeightRecordsFromCurrentPriorityVector(class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &,class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 116 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::enable_shared_from_this<class csf::dns::DnsQuery>(void)` | 2 | Exported Function
`public: __thiscall csf::dns::AAAARecord::AAAARecord(class csf::dns::AAAARecord const &)` | 5 | Exported Function
`protected: class std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl> & __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::operator=(class std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl> const &)` | 56 | Exported Function
`public: __thiscall csf::dns::AAAARecord::~AAAARecord(void)` | 39 | Exported Function
`public: __thiscall csf::dns::AAAARecord::AAAARecord(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 6 | Exported Function
`protected: class std::enable_shared_from_this<class csf::dns::DnsQuery> & __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::operator=(class std::enable_shared_from_this<class csf::dns::DnsQuery> const &)` | 55 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>(class std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl> const &)` | 3 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQuery>::~enable_shared_from_this<class csf::dns::DnsQuery>(void)` | 37 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::~enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>(void)` | 38 | Exported Function
`protected: __thiscall std::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>::enable_shared_from_this<class csf::dns::DnsQueryResolverImpl>(void)` | 4 | Exported Function
`private: void __thiscall csf::dns::DnsQuery::onQueryRunnerCompleted(class std::shared_ptr<class csf::dns::DnsQueryRunner>)` | 144 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::dns::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,enum csf::dns::DnsQueryResult::Result const &)` | 76 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::dns::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::dns::TXTRecord const &)` | 75 | Exported Function
`const csf::dns::DnsQueryResolver::``vftable'` | 82 | Exported Function
`const csf::dns::DnsQueryListener::``vftable'` | 81 | Exported Function
`class std::basic_ostream<char,struct std::char_traits<char> > & __cdecl csf::dns::operator<<(class std::basic_ostream<char,struct std::char_traits<char> > &,class csf::dns::ServiceResourceRecord const &)` | 74 | Exported Function
`bool __cdecl csf::dns::operator<(class csf::dns::ServiceResourceRecord const &,class csf::dns::ServiceResourceRecord const &)` | 79 | Exported Function
`bool __cdecl csf::dns::operator!=(class csf::dns::ServiceResourceRecord const &,class csf::dns::ServiceResourceRecord const &)` | 78 | Exported Function
`bool __cdecl csf::dns::operator>(class csf::dns::ServiceResourceRecord const &,class csf::dns::ServiceResourceRecord const &)` | 80 | Exported Function
`bool __cdecl csf::dns::operator==(class csf::dns::ServiceResourceRecord const &,class csf::dns::ServiceResourceRecord const &)` | 77 | Exported Function
`const csf::dns::DnsQueryResolverImpl::``vftable'` | 83 | Exported Function
`private: int __thiscall csf::dns::ServiceResourceRecordSorter::getTotalWeightWithinPriority(class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 135 | Exported Function
`private: __thiscall csf::dns::DnsRequest::DnsRequest(class std::vector<class std::shared_ptr<class csf::dns::DnsQuery>,class std::allocator<class std::shared_ptr<class csf::dns::DnsQuery> > >)` | 16 | Exported Function
`private: static class std::shared_ptr<class csf::ThreadPool> csf::dns::DnsQuery::_threadPool` | 88 | Exported Function
`private: static class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > csf::dns::DnsUtils::customNameServerAddress` | 99 | Exported Function
`private: __thiscall csf::dns::DnsQueryResolverImpl::DnsQueryResolverImpl(void)` | 15 | Exported Function
`const csf::dns::DnsUtilsImpl::``vftable'` | 85 | Exported Function
`const csf::dns::DnsResponse::``vftable'` | 84 | Exported Function
`private: __thiscall csf::dns::DnsQuery::DnsQuery(enum csf::dns::DnsQueryType,class std::vector<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> >,class std::allocator<class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > > > const &)` | 9 | Exported Function
`const csf::dns::DnsUtilsInterface::``vftable'` | 86 | Exported Function
`public: __thiscall csf::dns::ARecord::ARecord(class csf::dns::ARecord const &)` | 7 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::~ServiceResourceRecordSorter(void)` | 53 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::ServiceResourceRecordSorter(class std::vector<class csf::dns::ServiceResourceRecord,class std::allocator<class csf::dns::ServiceResourceRecord> > &)` | 33 | Exported Function
`public: __thiscall csf::dns::SOARecord::SOARecord(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 29 | Exported Function
`public: __thiscall csf::dns::SOARecord::SOARecord(class csf::dns::SOARecord const &)` | 28 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::ServiceResourceRecordSorter(class csf::dns::ServiceResourceRecordSorter const &)` | 34 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecord::ServiceResourceRecord(unsigned int,unsigned int,unsigned int,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 31 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecord::ServiceResourceRecord(class csf::dns::ServiceResourceRecord const &)` | 30 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecordSorter::ServiceResourceRecordSorter(class csf::dns::ServiceResourceRecordSorter &&)` | 32 | Exported Function
`public: __thiscall csf::dns::ServiceResourceRecord::~ServiceResourceRecord(void)` | 52 | Exported Function
`public: __thiscall csf::dns::SOARecord::~SOARecord(void)` | 51 | Exported Function
`public: class csf::dns::DnsQueryResolver & __thiscall csf::dns::DnsQueryResolver::operator=(class csf::dns::DnsQueryResolver &&)` | 60 | Exported Function
`public: class csf::dns::DnsQueryListener & __thiscall csf::dns::DnsQueryListener::operator=(class csf::dns::DnsQueryListener const &)` | 59 | Exported Function
`public: class csf::dns::DnsUtilsImpl & __thiscall csf::dns::DnsUtilsImpl::operator=(class csf::dns::DnsUtilsImpl &&)` | 64 | Exported Function
`public: class csf::dns::DnsQueryResolver & __thiscall csf::dns::DnsQueryResolver::operator=(class csf::dns::DnsQueryResolver const &)` | 61 | Exported Function
`public: class csf::dns::ARecord & __thiscall csf::dns::ARecord::operator=(class csf::dns::ARecord const &)` | 58 | Exported Function
`public: __thiscall csf::dns::TXTRecord::TXTRecord(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 36 | Exported Function
`public: __thiscall csf::dns::TXTRecord::TXTRecord(class csf::dns::TXTRecord const &)` | 35 | Exported Function
`public: class csf::dns::AAAARecord & __thiscall csf::dns::AAAARecord::operator=(class csf::dns::AAAARecord const &)` | 57 | Exported Function
`public: __thiscall csf::dns::TXTRecord::~TXTRecord(void)` | 54 | Exported Function
`public: __thiscall csf::dns::PointerRecord::~PointerRecord(void)` | 50 | Exported Function
`public: __thiscall csf::dns::DnsQueryResolver::DnsQueryResolver(class csf::dns::DnsQueryResolver const &)` | 13 | Exported Function
`public: __thiscall csf::dns::DnsQueryResolver::DnsQueryResolver(class csf::dns::DnsQueryResolver &&)` | 12 | Exported Function
`public: __thiscall csf::dns::DnsRequest::~DnsRequest(void)` | 45 | Exported Function
`public: __thiscall csf::dns::DnsQueryResolver::DnsQueryResolver(void)` | 14 | Exported Function
`public: __thiscall csf::dns::DnsQueryListener::DnsQueryListener(void)` | 11 | Exported Function
`public: __thiscall csf::dns::ARecord::~ARecord(void)` | 40 | Exported Function
`public: __thiscall csf::dns::ARecord::ARecord(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,int)` | 8 | Exported Function
`public: __thiscall csf::dns::DnsQueryListener::DnsQueryListener(class csf::dns::DnsQueryListener const &)` | 10 | Exported Function
`public: __thiscall csf::dns::DnsQuery::~DnsQuery(void)` | 41 | Exported Function
`public: __thiscall csf::dns::DnsUtilsImpl::DnsUtilsImpl(class csf::dns::DnsUtilsImpl &&)` | 18 | Exported Function
`public: __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::~DnsUtilsScopedSetCustomServerAddress(void)` | 49 | Exported Function
`public: __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::DnsUtilsScopedSetCustomServerAddress(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 24 | Exported Function
`public: __thiscall csf::dns::PointerRecord::PointerRecord(class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &,class std::basic_string<char,struct std::char_traits<char>,class std::allocator<char> > const &)` | 26 | Exported Function
`public: __thiscall csf::dns::PointerRecord::PointerRecord(class csf::dns::PointerRecord const &)` | 25 | Exported Function
`public: __thiscall csf::dns::DnsUtilsScopedSetCustomServerAddress::DnsUtilsScopedSetCustomServerAddress(class csf::dns::DnsUtilsScopedSetCustomServerAddress const &)` | 23 | Exported Function
`public: __thiscall csf::dns::DnsUtilsImpl::DnsUtilsImpl(void)` | 20 | Exported Function
`public: __thiscall csf::dns::DnsUtilsImpl::DnsUtilsImpl(class csf::dns::DnsUtilsImpl const &)` | 19 | Exported Function
`public: __thiscall csf::dns::DnsUtilsInterface::DnsUtilsInterface(void)` | 22 | Exported Function
`public: __thiscall csf::dns::DnsUtilsInterface::DnsUtilsInterface(class csf::dns::DnsUtilsInterface const &)` | 21 | Exported Function


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
* VirusTotal Link: https://www.virustotal.com/gui/file/5241c99361f17228f3b244807c94a583bee79f5f119f8f943b9c1a3c34fc1410/detection/




MIT License. Copyright (c) 2020 Strontic.


