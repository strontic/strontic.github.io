---
title: esscli.dll | WMI
excerpt: What is esscli.dll?
---

# esscli.dll 

* File Path: `C:\Windows\system32\wbem\esscli.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `4EFC673CEC107FD0BA15841BBEB9BB3E`
SHA1 | `A881EBE3FE7EAAE8C8F563CF810E3BFD7172DAD2`
SHA256 | `03A6932CD4BF117EA26D3B8D0F8F466500B4137271F5B69CB9F048D7315D815F`
SHA384 | `879D4675392FC2B240D6ADE2BF350A2AAA9A20B9880952E983677B1902870C52578A2F5F066A5EC311DF8E878DB55F7E`
SHA512 | `51720D324CBB9F1FF7B5DEA690D615E9F1477BA43F69646F7C4B3F47E4F10026A96E2662037A55AF2DC0C7C76695BA40284FD93186CB81F5CA15921C0577DB3B`
SSDEEP | `6144:A7JEf/CsDW3JsAw4b/AsiUbqltqS1QpZarOcaRkOfGEW9+cgB:AeS6CzrASbqltdCpEceEcgB`
IMP | `CCFF9BAEF6BDB74D324275BC99F55AB1`
PESHA1 | `10090C4D4EF5233F4D44DF78B911363A431A7927`
PE256 | `7E1EB766B058165F8099AE42F481ABE26467BC3C916818C8E0A9EFFE73E127FA`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static int __cdecl CQueryAnalyser::CompareRequestedToProvided(class CClassInfoArray & __ptr64,class CClassInfoArray & __ptr64)` | 83 | Exported Function
`public: static int __cdecl CEvalTree::Compare(class CEvalNode * __ptr64,class CEvalNode * __ptr64)` | 81 | Exported Function
`public: static long __cdecl CEvalTree::BuildFromToken(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,struct QL_LEVEL_1_TOKEN & __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 68 | Exported Function
`public: static long __cdecl CEvalTree::Combine(class CEvalNode * __ptr64,class CEvalNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 78 | Exported Function
`public: static long __cdecl CEvalTree::BuildTwoPropFromToken(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,struct QL_LEVEL_1_TOKEN & __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 69 | Exported Function
`public: static bool __cdecl CEvalNode::IsInvalid(class CEvalNode * __ptr64)` | 124 | Exported Function
`public: static bool __cdecl CEvalNode::IsAllFalse(class CEvalNode * __ptr64)` | 120 | Exported Function
`public: static bool __cdecl CEvalNode::IsNoop(class CEvalNode * __ptr64,int)` | 128 | Exported Function
`public: static int __cdecl CEvalNode::GetType(class CEvalNode * __ptr64)` | 117 | Exported Function
`public: static class CEvalNode * __ptr64 __cdecl CEvalNode::CloneNode(class CEvalNode const * __ptr64)` | 77 | Exported Function
`public: static long __cdecl CEvalTree::CreateFromConjunction(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CConjunction * __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 87 | Exported Function
`public: static long __cdecl CQueryAnalyser::GetNecessaryQueryForClass(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 111 | Exported Function
`public: static long __cdecl CQueryAnalyser::GetLimitingQueryForInstanceClass(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct CClassInformation & __ptr64,unsigned short * __ptr64 & __ptr64)` | 110 | Exported Function
`public: static long __cdecl CQueryAnalyser::GetNecessaryQueryForProperty(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CPropertyName & __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 112 | Exported Function
`public: static long __cdecl CQueryAnalyser::SimplifyQueryForChild(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,class CContextMetaData * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 160 | Exported Function
`public: static long __cdecl CQueryAnalyser::GetPossibleInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CClassInfoArray * __ptr64 & __ptr64)` | 115 | Exported Function
`public: static long __cdecl CEvalTree::IsMergeAdvisable(class CEvalNode * __ptr64,class CEvalNode * __ptr64,class CImplicationList & __ptr64)` | 127 | Exported Function
`public: static long __cdecl CEvalTree::Evaluate(class CObjectInfo & __ptr64,class CEvalNode * __ptr64,class CSortedArray & __ptr64)` | 96 | Exported Function
`public: static long __cdecl CEvalTree::Project(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CEvalNode * __ptr64,class CProjectionFilter * __ptr64,enum EProjectionType,bool,class CEvalNode * __ptr64 * __ptr64)` | 145 | Exported Function
`public: static long __cdecl CQueryAnalyser::GetDefiniteInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CClassInfoArray * __ptr64 & __ptr64)` | 107 | Exported Function
`public: static long __cdecl CQueryAnalyser::CanPointToClass(struct IWbemClassObject * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,class CContextMetaData * __ptr64)` | 70 | Exported Function
`public: long __cdecl CEvalTree::CombineWith(class CEvalTree & __ptr64,class CContextMetaData * __ptr64,int,long) __ptr64` | 80 | Exported Function
`public: long __cdecl CEvalTree::ApplyPredicate(class CLeafPredicate * __ptr64) __ptr64` | 67 | Exported Function
`public: long __cdecl CEvalTree::CreateFromDNF(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CDNFExpression * __ptr64,class CEvalNode * __ptr64 * __ptr64) __ptr64` | 88 | Exported Function
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,unsigned short const * __ptr64,int,struct QL_LEVEL_1_TOKEN * __ptr64,long,long) __ptr64` | 90 | Exported Function
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,long,long) __ptr64` | 89 | Exported Function
`public: int __cdecl CSortedArray::Add(unsigned __int64) __ptr64` | 55 | Exported Function
`public: int __cdecl CClassInfoArray::IsLimited(void) __ptr64` | 126 | Exported Function
`public: int __cdecl CSortedArray::Compare(class CSortedArray & __ptr64) __ptr64` | 82 | Exported Function
`public: long __cdecl CContextMetaData::GetClass(unsigned short const * __ptr64,struct _IWmiObject * __ptr64 * __ptr64) __ptr64` | 104 | Exported Function
`public: int __cdecl CSortedArray::Size(void)const __ptr64` | 162 | Exported Function
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,unsigned short const * __ptr64,long,long) __ptr64` | 91 | Exported Function
`public: long __cdecl CSortedArray::AddDataFrom(class CSortedArray const & __ptr64) __ptr64` | 57 | Exported Function
`public: long __cdecl CObjectInfo::GetLength(void) __ptr64` | 109 | Exported Function
`public: long __cdecl CSortedArray::AddDataFrom(unsigned __int64 const * __ptr64,unsigned int) __ptr64` | 58 | Exported Function
`public: long __cdecl CSortedArray::CopyDataFrom(unsigned __int64 const * __ptr64,unsigned int) __ptr64` | 85 | Exported Function
`public: long __cdecl CSortedArray::CopyDataFrom(class CSortedArray const & __ptr64) __ptr64` | 84 | Exported Function
`public: long __cdecl CEvalTree::Evaluate(struct IWbemObjectAccess * __ptr64,class CSortedArray & __ptr64) __ptr64` | 95 | Exported Function
`public: long __cdecl CEvalTree::CreateProjection(class CEvalTree & __ptr64,class CContextMetaData * __ptr64,class CProjectionFilter * __ptr64,enum EProjectionType,bool) __ptr64` | 92 | Exported Function
`public: long __cdecl CEvalTree::Optimize(class CContextMetaData * __ptr64) __ptr64` | 140 | Exported Function
`public: long __cdecl CEvalTree::UtilizeGuarantee(class CEvalTree & __ptr64,class CContextMetaData * __ptr64) __ptr64` | 164 | Exported Function
`public: long __cdecl CEvalTree::RemoveIndex(int) __ptr64` | 152 | Exported Function
`public: void __cdecl CEvalTree::operator=(class CEvalTree const & __ptr64) __ptr64` | 38 | Exported Function
`public: void __cdecl CClassInfoArray::SetLimited(int) __ptr64` | 156 | Exported Function
`public: void __cdecl CEvalTree::Rebase(unsigned __int64) __ptr64` | 147 | Exported Function
`public: void __cdecl CObjectInfo::SetObjectAt(long,struct _IWmiObject * __ptr64) __ptr64` | 157 | Exported Function
`public: void __cdecl CObjectInfo::Clear(void) __ptr64` | 73 | Exported Function
`public: void * __ptr64 __cdecl CReuseMemoryManager::Allocate(void) __ptr64` | 61 | Exported Function
`public: virtual unsigned long __cdecl CMetaData::Release(void) __ptr64` | 149 | Exported Function
`public: void * __ptr64 __cdecl CTempMemoryManager::Allocate(unsigned __int64) __ptr64` | 62 | Exported Function
`public: void __cdecl CClassInfoArray::RemoveClass(int) __ptr64` | 151 | Exported Function
`public: void __cdecl CClassInfoArray::Clear(void) __ptr64` | 71 | Exported Function
`public: void __cdecl CReuseMemoryManager::Clear(void) __ptr64` | 74 | Exported Function
`public: void __cdecl CSortedArray::SetSize(int) __ptr64` | 159 | Exported Function
`public: void __cdecl CSortedArray::Rebase(unsigned __int64) __ptr64` | 148 | Exported Function
`public: void __cdecl CStandardMetaData::Clear(void) __ptr64` | 75 | Exported Function
`public: void __cdecl CTempMemoryManager::Free(void * __ptr64,unsigned __int64) __ptr64` | 99 | Exported Function
`public: void __cdecl CTempMemoryManager::Clear(void) __ptr64` | 76 | Exported Function
`public: void __cdecl CSortedArray::``default constructor closure'(void) __ptr64` | 54 | Exported Function
`public: void __cdecl CReuseMemoryManager::Free(void * __ptr64) __ptr64` | 98 | Exported Function
`public: void __cdecl CSortedArray::Empty(void) __ptr64` | 94 | Exported Function
`public: void __cdecl CSortedArray::operator=(class CSortedArray const & __ptr64) __ptr64` | 45 | Exported Function
`public: void __cdecl CSortedArray::Insert(unsigned __int64) __ptr64` | 119 | Exported Function
`public: unsigned __int64 __cdecl CSortedArray::GetAt(int) __ptr64` | 102 | Exported Function
`public: unsigned __int64 * __ptr64 __cdecl CSortedArray::UnbindPtr(void) __ptr64` | 163 | Exported Function
`public: unsigned int __cdecl CSortedArray::CopyTo(unsigned __int64 * __ptr64,unsigned int) __ptr64` | 86 | Exported Function
`public: virtual __cdecl CEvalNode::~CEvalNode(void) __ptr64` | 25 | Exported Function
`public: unsigned int __cdecl CSortedArray::Find(unsigned __int64) __ptr64` | 97 | Exported Function
`public: struct _IWmiObject * __ptr64 __cdecl CObjectInfo::GetObjectAt(long) __ptr64` | 114 | Exported Function
`public: static void __cdecl CEvalNode::PrintOffset(struct _iobuf * __ptr64,int)` | 144 | Exported Function
`public: struct CClassInformation & __ptr64 __cdecl CClassInformation::operator=(struct CClassInformation const & __ptr64) __ptr64` | 36 | Exported Function
`public: unsigned __int64 * __ptr64 __cdecl CSortedArray::GetArrayPtr(void) __ptr64` | 101 | Exported Function
`public: struct CClassInformation * __ptr64 __cdecl CClassInfoArray::GetClass(int) __ptr64` | 103 | Exported Function
`public: virtual __cdecl CMetaData::~CMetaData(void) __ptr64` | 27 | Exported Function
`public: virtual long __cdecl CMetaData::GetClass(unsigned short const * __ptr64,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 105 | Exported Function
`public: virtual long __cdecl CEvalNode::Optimize(class CContextMetaData * __ptr64,class CEvalNode * __ptr64 * __ptr64) __ptr64` | 139 | Exported Function
`public: virtual long __cdecl CMetaData::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 146 | Exported Function
`public: virtual unsigned long __cdecl CMetaData::AddRef(void) __ptr64` | 60 | Exported Function
`public: virtual long __cdecl CStandardMetaData::GetClass(unsigned short const * __ptr64,struct IWbemContext * __ptr64,struct _IWmiObject * __ptr64 * __ptr64) __ptr64` | 106 | Exported Function
`public: virtual bool __cdecl CEvalNode::IsAllFalse(void) __ptr64` | 121 | Exported Function
`public: virtual __cdecl CStandardMetaData::~CStandardMetaData(void) __ptr64` | 32 | Exported Function
`public: virtual bool __cdecl CEvalNode::IsInvalid(void) __ptr64` | 125 | Exported Function
`public: virtual bool __cdecl CPropertyProjectionFilter::IsInSet(class CEvalNode * __ptr64) __ptr64` | 123 | Exported Function
`public: virtual bool __cdecl CEvalNode::IsNoop(int) __ptr64` | 129 | Exported Function
`public: int __cdecl CClassInfoArray::GetNumClasses(void) __ptr64` | 113 | Exported Function
`protected: static long __cdecl CQueryAnalyser::OrPossibleClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 142 | Exported Function
`protected: static long __cdecl CQueryAnalyser::OrDefiniteClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 141 | Exported Function
`protected: static long __cdecl CQueryAnalyser::OrQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 143 | Exported Function
`protected: unsigned __int64 __cdecl CTempMemoryManager::RoundUp(unsigned __int64) __ptr64` | 153 | Exported Function
`protected: static void __cdecl CQueryAnalyser::AppendQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 66 | Exported Function
`protected: static long __cdecl CQueryAnalyser::GetPropertiesThatMustDiffer(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct CClassInformation & __ptr64,class CWStringArray & __ptr64)` | 116 | Exported Function
`protected: static long __cdecl CQueryAnalyser::GetInstanceClasses(struct QL_LEVEL_1_TOKEN & __ptr64,class CClassInfoArray & __ptr64)` | 108 | Exported Function
`protected: static long __cdecl CQueryAnalyser::NegateDefiniteClassArray(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 136 | Exported Function
`protected: static long __cdecl CQueryAnalyser::NegateQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 138 | Exported Function
`protected: static long __cdecl CQueryAnalyser::NegatePossibleClassArray(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 137 | Exported Function
`public: __cdecl CClassInfoArray::CClassInfoArray(void) __ptr64` | 1 | Exported Function
`public: __cdecl CEvalNode::CEvalNode(class CEvalNode const & __ptr64) __ptr64` | 5 | Exported Function
`public: __cdecl CContextMetaData::~CContextMetaData(void) __ptr64` | 24 | Exported Function
`public: __cdecl CEvalNode::CEvalNode(void) __ptr64` | 6 | Exported Function
`public: __cdecl CEvalTree::CEvalTree(void) __ptr64` | 8 | Exported Function
`public: __cdecl CEvalTree::CEvalTree(class CEvalTree const & __ptr64) __ptr64` | 7 | Exported Function
`public: __cdecl CClassInformation::CClassInformation(struct CClassInformation const & __ptr64) __ptr64` | 2 | Exported Function
`public: __cdecl CClassInfoArray::~CClassInfoArray(void) __ptr64` | 22 | Exported Function
`public: __cdecl CClassInformation::CClassInformation(void) __ptr64` | 3 | Exported Function
`public: __cdecl CContextMetaData::CContextMetaData(class CMetaData * __ptr64,struct IWbemContext * __ptr64) __ptr64` | 4 | Exported Function
`public: __cdecl CClassInformation::~CClassInformation(void) __ptr64` | 23 | Exported Function
`DllRegisterServer` | 168 | Exported Function
`DllGetClassObject` | 167 | Exported Function
`DllUnregisterServer` | 169 | Exported Function
`IsUserAdministrator` | 133 | Exported Function
`GetAccessMask` | 100 | Exported Function
`const CMetaData::``vftable'` | 51 | Exported Function
`const CEvalNode::``vftable'` | 50 | Exported Function
`const CPropertyProjectionFilter::``vftable'` | 52 | Exported Function
`DllCanUnloadNow` | 166 | Exported Function
`const CStandardMetaData::``vftable'` | 53 | Exported Function
`IsUserInGroup` | 134 | Exported Function
`protected: static long __cdecl CEvalTree::InnerCombine(class CEvalNode * __ptr64,class CEvalNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 118 | Exported Function
`protected: static long __cdecl CEvalTree::CombineLeafWithBranch(class CValueNode * __ptr64,class CBranchingNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 79 | Exported Function
`protected: static long __cdecl CQueryAnalyser::AndDefiniteClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 63 | Exported Function
`protected: static long __cdecl CQueryAnalyser::AndQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 65 | Exported Function
`protected: static long __cdecl CQueryAnalyser::AndPossibleClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 64 | Exported Function
`protected: static int __cdecl CQueryAnalyser::IsTokenAboutClass(struct QL_LEVEL_1_TOKEN & __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64)` | 131 | Exported Function
`protected: static int __cdecl CQueryAnalyser::IsPropertyInClass(class CPropertyName & __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64)` | 130 | Exported Function
`protected: static int __cdecl CQueryAnalyser::IsTokenAboutProperty(struct QL_LEVEL_1_TOKEN & __ptr64,class CPropertyName & __ptr64)` | 132 | Exported Function
`protected: static int __cdecl CQueryAnalyser::ValidateSQLDateTime(unsigned short const * __ptr64)` | 165 | Exported Function
`protected: static int __cdecl CQueryAnalyser::SimplifyTokenForChild(struct QL_LEVEL_1_TOKEN & __ptr64,unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,class CContextMetaData * __ptr64)` | 161 | Exported Function
`public: bool __cdecl CObjectInfo::SetLength(long) __ptr64` | 155 | Exported Function
`public: bool __cdecl CEvalTree::SetBool(int) __ptr64` | 154 | Exported Function
`public: bool __cdecl CPropertyProjectionFilter::AddProperty(class CPropertyName const & __ptr64) __ptr64` | 59 | Exported Function
`public: bool __cdecl CTimeKeeper::DecorateObject(struct _IWmiObject * __ptr64) __ptr64` | 93 | Exported Function
`public: bool __cdecl CSortedArray::Remove(unsigned __int64) __ptr64` | 150 | Exported Function
`public: bool __cdecl CClassInfoArray::SetOne(unsigned short const * __ptr64,int) __ptr64` | 158 | Exported Function
`public: bool __cdecl CClassInfoArray::operator=(class CClassInfoArray & __ptr64) __ptr64` | 35 | Exported Function
`public: bool __cdecl CEvalTree::Clear(void) __ptr64` | 72 | Exported Function
`public: bool __cdecl CEvalTree::IsValid(void) __ptr64` | 135 | Exported Function
`public: bool __cdecl CEvalTree::IsFalse(void) __ptr64` | 122 | Exported Function
`public: class CContextMetaData & __ptr64 __cdecl CContextMetaData::operator=(class CContextMetaData const & __ptr64) __ptr64` | 37 | Exported Function
`public: class CStandardMetaData & __ptr64 __cdecl CStandardMetaData::operator=(class CStandardMetaData const & __ptr64) __ptr64` | 46 | Exported Function
`public: class CReuseMemoryManager & __ptr64 __cdecl CReuseMemoryManager::operator=(class CReuseMemoryManager const & __ptr64) __ptr64` | 44 | Exported Function
`public: class CTempMemoryManager & __ptr64 __cdecl CTempMemoryManager::operator=(class CTempMemoryManager const & __ptr64) __ptr64` | 47 | Exported Function
`public: class CTimeKeeper & __ptr64 __cdecl CTimeKeeper::operator=(class CTimeKeeper const & __ptr64) __ptr64` | 49 | Exported Function
`public: class CTimeKeeper & __ptr64 __cdecl CTimeKeeper::operator=(class CTimeKeeper && __ptr64) __ptr64` | 48 | Exported Function
`public: class CObjectInfo & __ptr64 __cdecl CObjectInfo::operator=(class CObjectInfo const & __ptr64) __ptr64` | 40 | Exported Function
`public: class CMetaData & __ptr64 __cdecl CMetaData::operator=(class CMetaData const & __ptr64) __ptr64` | 39 | Exported Function
`public: class CPropertyProjectionFilter & __ptr64 __cdecl CPropertyProjectionFilter::operator=(class CPropertyProjectionFilter const & __ptr64) __ptr64` | 41 | Exported Function
`public: class CQueryAnalyser & __ptr64 __cdecl CQueryAnalyser::operator=(class CQueryAnalyser const & __ptr64) __ptr64` | 43 | Exported Function
`public: class CQueryAnalyser & __ptr64 __cdecl CQueryAnalyser::operator=(class CQueryAnalyser && __ptr64) __ptr64` | 42 | Exported Function
`public: __cdecl CPropertyProjectionFilter::CPropertyProjectionFilter(void) __ptr64` | 13 | Exported Function
`public: __cdecl CPropertyProjectionFilter::CPropertyProjectionFilter(class CPropertyProjectionFilter const & __ptr64) __ptr64` | 12 | Exported Function
`public: __cdecl CPropertyProjectionFilter::~CPropertyProjectionFilter(void) __ptr64` | 29 | Exported Function
`public: __cdecl CReuseMemoryManager::~CReuseMemoryManager(void) __ptr64` | 30 | Exported Function
`public: __cdecl CReuseMemoryManager::CReuseMemoryManager(unsigned __int64,unsigned __int64) __ptr64` | 14 | Exported Function
`public: __cdecl CMetaData::CMetaData(class CMetaData const & __ptr64) __ptr64` | 9 | Exported Function
`public: __cdecl CEvalTree::~CEvalTree(void) __ptr64` | 26 | Exported Function
`public: __cdecl CMetaData::CMetaData(void) __ptr64` | 10 | Exported Function
`public: __cdecl CObjectInfo::~CObjectInfo(void) __ptr64` | 28 | Exported Function
`public: __cdecl CObjectInfo::CObjectInfo(void) __ptr64` | 11 | Exported Function
`public: __cdecl CSortedArray::CSortedArray(class CSortedArray & __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl CTempMemoryManager::~CTempMemoryManager(void) __ptr64` | 33 | Exported Function
`public: __cdecl CTempMemoryManager::CTempMemoryManager(void) __ptr64` | 20 | Exported Function
`public: __cdecl CTimeKeeper::CTimeKeeper(void) __ptr64` | 21 | Exported Function
`public: bool __cdecl CClassInfoArray::AddClass(struct CClassInformation * __ptr64) __ptr64` | 56 | Exported Function
`public: __cdecl CTimeKeeper::~CTimeKeeper(void) __ptr64` | 34 | Exported Function
`public: __cdecl CSortedArray::CSortedArray(unsigned int,unsigned __int64 * __ptr64) __ptr64` | 17 | Exported Function
`public: __cdecl CSortedArray::CSortedArray(int,int) __ptr64` | 16 | Exported Function
`public: __cdecl CSortedArray::~CSortedArray(void) __ptr64` | 31 | Exported Function
`public: __cdecl CStandardMetaData::CStandardMetaData(struct IWbemServices * __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl CStandardMetaData::CStandardMetaData(class CStandardMetaData const & __ptr64) __ptr64` | 18 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: esscli.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/67
* VirusTotal Link: https://www.virustotal.com/gui/file/03a6932cd4bf117ea26d3b8d0f8f466500b4137271f5b69cb9f048d7315d815f/detection/





MIT License. Copyright (c) 2020 Strontic.


