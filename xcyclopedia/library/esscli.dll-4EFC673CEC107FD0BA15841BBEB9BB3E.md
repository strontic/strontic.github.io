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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CEvalNode::``vftable'` | 50 (0x32) | Exported Function | 0x0000000180052318 | 0x00052318
`public: static bool __cdecl CEvalNode::IsInvalid(class CEvalNode * __ptr64)` | 124 (0x7c) | Exported Function | 0x0000000180013a10 | 0x00013a10
`public: static bool __cdecl CEvalNode::IsNoop(class CEvalNode * __ptr64,int)` | 128 (0x80) | Exported Function | 0x000000018003d000 | 0x0003d000
`public: static class CEvalNode * __ptr64 __cdecl CEvalNode::CloneNode(class CEvalNode const * __ptr64)` | 77 (0x4d) | Exported Function | 0x0000000180013100 | 0x00013100
`public: static int __cdecl CEvalNode::GetType(class CEvalNode * __ptr64)` | 117 (0x75) | Exported Function | 0x000000018000cd90 | 0x0000cd90
`public: static int __cdecl CEvalTree::Compare(class CEvalNode * __ptr64,class CEvalNode * __ptr64)` | 81 (0x51) | Exported Function | 0x000000018000cd20 | 0x0000cd20
`public: static int __cdecl CQueryAnalyser::CompareRequestedToProvided(class CClassInfoArray & __ptr64,class CClassInfoArray & __ptr64)` | 83 (0x53) | Exported Function | 0x0000000180010c80 | 0x00010c80
`public: static long __cdecl CEvalTree::BuildFromToken(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,struct QL_LEVEL_1_TOKEN & __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 68 (0x44) | Exported Function | 0x000000018000b570 | 0x0000b570
`public: static long __cdecl CEvalTree::BuildTwoPropFromToken(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,struct QL_LEVEL_1_TOKEN & __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 69 (0x45) | Exported Function | 0x0000000180033840 | 0x00033840
`public: static long __cdecl CEvalTree::Combine(class CEvalNode * __ptr64,class CEvalNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 78 (0x4e) | Exported Function | 0x00000001800085c0 | 0x000085c0
`public: static long __cdecl CEvalTree::CreateFromConjunction(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CConjunction * __ptr64,class CEvalNode * __ptr64 * __ptr64)` | 87 (0x57) | Exported Function | 0x000000018000b230 | 0x0000b230
`public: static long __cdecl CEvalTree::Evaluate(class CObjectInfo & __ptr64,class CEvalNode * __ptr64,class CSortedArray & __ptr64)` | 96 (0x60) | Exported Function | 0x000000018003a0d0 | 0x0003a0d0
`public: static long __cdecl CEvalTree::IsMergeAdvisable(class CEvalNode * __ptr64,class CEvalNode * __ptr64,class CImplicationList & __ptr64)` | 127 (0x7f) | Exported Function | 0x000000018000d6c0 | 0x0000d6c0
`public: static long __cdecl CEvalTree::Project(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CEvalNode * __ptr64,class CProjectionFilter * __ptr64,enum EProjectionType,bool,class CEvalNode * __ptr64 * __ptr64)` | 145 (0x91) | Exported Function | 0x000000018003df60 | 0x0003df60
`public: static long __cdecl CQueryAnalyser::CanPointToClass(struct IWbemClassObject * __ptr64,unsigned short const * __ptr64,unsigned short const * __ptr64,class CContextMetaData * __ptr64)` | 70 (0x46) | Exported Function | 0x0000000180011dd0 | 0x00011dd0
`public: static long __cdecl CQueryAnalyser::GetDefiniteInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CClassInfoArray * __ptr64 & __ptr64)` | 107 (0x6b) | Exported Function | 0x0000000180002530 | 0x00002530
`public: static long __cdecl CQueryAnalyser::GetLimitingQueryForInstanceClass(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct CClassInformation & __ptr64,unsigned short * __ptr64 & __ptr64)` | 110 (0x6e) | Exported Function | 0x00000001800422a0 | 0x000422a0
`public: static long __cdecl CQueryAnalyser::GetNecessaryQueryForClass(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 111 (0x6f) | Exported Function | 0x0000000180002d50 | 0x00002d50
`public: static bool __cdecl CEvalNode::IsAllFalse(class CEvalNode * __ptr64)` | 120 (0x78) | Exported Function | 0x0000000180012c60 | 0x00012c60
`public: static long __cdecl CQueryAnalyser::GetNecessaryQueryForProperty(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CPropertyName & __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 112 (0x70) | Exported Function | 0x0000000180043200 | 0x00043200
`public: long __cdecl CSortedArray::CopyDataFrom(unsigned __int64 const * __ptr64,unsigned int) __ptr64` | 85 (0x55) | Exported Function | 0x00000001800387a0 | 0x000387a0
`public: long __cdecl CSortedArray::AddDataFrom(unsigned __int64 const * __ptr64,unsigned int) __ptr64` | 58 (0x3a) | Exported Function | 0x0000000180033200 | 0x00033200
`public: int __cdecl CSortedArray::Add(unsigned __int64) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180032fd0 | 0x00032fd0
`public: int __cdecl CSortedArray::Compare(class CSortedArray & __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180038660 | 0x00038660
`public: int __cdecl CSortedArray::Size(void)const __ptr64` | 162 (0xa2) | Exported Function | 0x000000018003ff70 | 0x0003ff70
`public: long __cdecl CContextMetaData::GetClass(unsigned short const * __ptr64,struct _IWmiObject * __ptr64 * __ptr64) __ptr64` | 104 (0x68) | Exported Function | 0x000000018000a660 | 0x0000a660
`public: long __cdecl CEvalTree::ApplyPredicate(class CLeafPredicate * __ptr64) __ptr64` | 67 (0x43) | Exported Function | 0x00000001800337b0 | 0x000337b0
`public: long __cdecl CEvalTree::CombineWith(class CEvalTree & __ptr64,class CContextMetaData * __ptr64,int,long) __ptr64` | 80 (0x50) | Exported Function | 0x00000001800057a0 | 0x000057a0
`public: long __cdecl CEvalTree::CreateFromDNF(class CContextMetaData * __ptr64,class CImplicationList & __ptr64,class CDNFExpression * __ptr64,class CEvalNode * __ptr64 * __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x000000018000b0e0 | 0x0000b0e0
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,long,long) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180038a40 | 0x00038a40
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,unsigned short const * __ptr64,int,struct QL_LEVEL_1_TOKEN * __ptr64,long,long) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180009290 | 0x00009290
`public: long __cdecl CEvalTree::CreateFromQuery(class CContextMetaData * __ptr64,unsigned short const * __ptr64,long,long) __ptr64` | 91 (0x5b) | Exported Function | 0x0000000180005390 | 0x00005390
`public: long __cdecl CEvalTree::CreateProjection(class CEvalTree & __ptr64,class CContextMetaData * __ptr64,class CProjectionFilter * __ptr64,enum EProjectionType,bool) __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180038a80 | 0x00038a80
`public: long __cdecl CEvalTree::Evaluate(struct IWbemObjectAccess * __ptr64,class CSortedArray & __ptr64) __ptr64` | 95 (0x5f) | Exported Function | 0x0000000180039fb0 | 0x00039fb0
`public: long __cdecl CEvalTree::Optimize(class CContextMetaData * __ptr64) __ptr64` | 140 (0x8c) | Exported Function | 0x00000001800042e0 | 0x000042e0
`public: long __cdecl CEvalTree::RemoveIndex(int) __ptr64` | 152 (0x98) | Exported Function | 0x0000000180012450 | 0x00012450
`public: long __cdecl CEvalTree::UtilizeGuarantee(class CEvalTree & __ptr64,class CContextMetaData * __ptr64) __ptr64` | 164 (0xa4) | Exported Function | 0x0000000180004150 | 0x00004150
`public: long __cdecl CObjectInfo::GetLength(void) __ptr64` | 109 (0x6d) | Exported Function | 0x0000000180010d90 | 0x00010d90
`public: long __cdecl CSortedArray::AddDataFrom(class CSortedArray const & __ptr64) __ptr64` | 57 (0x39) | Exported Function | 0x0000000180032ff0 | 0x00032ff0
`public: long __cdecl CSortedArray::CopyDataFrom(class CSortedArray const & __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180038770 | 0x00038770
`public: static long __cdecl CQueryAnalyser::GetPossibleInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,class CClassInfoArray * __ptr64 & __ptr64)` | 115 (0x73) | Exported Function | 0x0000000180002110 | 0x00002110
`public: static long __cdecl CQueryAnalyser::SimplifyQueryForChild(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,class CContextMetaData * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64)` | 160 (0xa0) | Exported Function | 0x0000000180003360 | 0x00003360
`public: static void __cdecl CEvalNode::PrintOffset(struct _iobuf * __ptr64,int)` | 144 (0x90) | Exported Function | 0x000000018003d740 | 0x0003d740
`public: void * __ptr64 __cdecl CTempMemoryManager::Allocate(unsigned __int64) __ptr64` | 62 (0x3e) | Exported Function | 0x0000000180010280 | 0x00010280
`public: void __cdecl CClassInfoArray::Clear(void) __ptr64` | 71 (0x47) | Exported Function | 0x0000000180001780 | 0x00001780
`public: void __cdecl CClassInfoArray::RemoveClass(int) __ptr64` | 151 (0x97) | Exported Function | 0x00000001800444f0 | 0x000444f0
`public: void __cdecl CClassInfoArray::SetLimited(int) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180044550 | 0x00044550
`public: void __cdecl CEvalTree::operator=(class CEvalTree const & __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180031ed0 | 0x00031ed0
`public: void __cdecl CEvalTree::Rebase(unsigned __int64) __ptr64` | 147 (0x93) | Exported Function | 0x000000018003e380 | 0x0003e380
`public: void __cdecl CObjectInfo::Clear(void) __ptr64` | 73 (0x49) | Exported Function | 0x0000000180034a40 | 0x00034a40
`public: void __cdecl CObjectInfo::SetObjectAt(long,struct _IWmiObject * __ptr64) __ptr64` | 157 (0x9d) | Exported Function | 0x000000018003ea00 | 0x0003ea00
`public: void __cdecl CReuseMemoryManager::Clear(void) __ptr64` | 74 (0x4a) | Exported Function | 0x000000018002b420 | 0x0002b420
`public: void __cdecl CReuseMemoryManager::Free(void * __ptr64) __ptr64` | 98 (0x62) | Exported Function | 0x000000018002b7f0 | 0x0002b7f0
`public: void __cdecl CSortedArray::``default constructor closure'(void) __ptr64` | 54 (0x36) | Exported Function | 0x00000001800323d0 | 0x000323d0
`public: void __cdecl CSortedArray::Empty(void) __ptr64` | 94 (0x5e) | Exported Function | 0x0000000180038cf0 | 0x00038cf0
`public: void __cdecl CSortedArray::Insert(unsigned __int64) __ptr64` | 119 (0x77) | Exported Function | 0x000000018003b620 | 0x0003b620
`public: void __cdecl CSortedArray::operator=(class CSortedArray const & __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180032200 | 0x00032200
`public: void __cdecl CSortedArray::Rebase(unsigned __int64) __ptr64` | 148 (0x94) | Exported Function | 0x000000018003e3b0 | 0x0003e3b0
`public: void __cdecl CSortedArray::SetSize(int) __ptr64` | 159 (0x9f) | Exported Function | 0x000000018003f740 | 0x0003f740
`public: void __cdecl CStandardMetaData::Clear(void) __ptr64` | 75 (0x4b) | Exported Function | 0x000000018002aaa0 | 0x0002aaa0
`public: void * __ptr64 __cdecl CReuseMemoryManager::Allocate(void) __ptr64` | 61 (0x3d) | Exported Function | 0x000000018002b380 | 0x0002b380
`public: virtual unsigned long __cdecl CMetaData::Release(void) __ptr64` | 149 (0x95) | Exported Function | 0x000000018000f360 | 0x0000f360
`public: virtual unsigned long __cdecl CMetaData::AddRef(void) __ptr64` | 60 (0x3c) | Exported Function | 0x000000018000fac0 | 0x0000fac0
`public: virtual long __cdecl CStandardMetaData::GetClass(unsigned short const * __ptr64,struct IWbemContext * __ptr64,struct _IWmiObject * __ptr64 * __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x0000000180011cc0 | 0x00011cc0
`public: struct _IWmiObject * __ptr64 __cdecl CObjectInfo::GetObjectAt(long) __ptr64` | 114 (0x72) | Exported Function | 0x000000018003af80 | 0x0003af80
`public: struct CClassInformation & __ptr64 __cdecl CClassInformation::operator=(struct CClassInformation const & __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180042030 | 0x00042030
`public: struct CClassInformation * __ptr64 __cdecl CClassInfoArray::GetClass(int) __ptr64` | 103 (0x67) | Exported Function | 0x0000000180010710 | 0x00010710
`public: unsigned __int64 * __ptr64 __cdecl CSortedArray::GetArrayPtr(void) __ptr64` | 101 (0x65) | Exported Function | 0x000000018003ac40 | 0x0003ac40
`public: unsigned __int64 * __ptr64 __cdecl CSortedArray::UnbindPtr(void) __ptr64` | 163 (0xa3) | Exported Function | 0x00000001800412a0 | 0x000412a0
`public: unsigned __int64 __cdecl CSortedArray::GetAt(int) __ptr64` | 102 (0x66) | Exported Function | 0x000000018003ac60 | 0x0003ac60
`public: unsigned int __cdecl CSortedArray::CopyTo(unsigned __int64 * __ptr64,unsigned int) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180038880 | 0x00038880
`public: unsigned int __cdecl CSortedArray::Find(unsigned __int64) __ptr64` | 97 (0x61) | Exported Function | 0x000000018003ab20 | 0x0003ab20
`public: int __cdecl CClassInfoArray::IsLimited(void) __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180010d90 | 0x00010d90
`public: virtual __cdecl CEvalNode::~CEvalNode(void) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180031cb0 | 0x00031cb0
`public: virtual __cdecl CStandardMetaData::~CStandardMetaData(void) __ptr64` | 32 (0x20) | Exported Function | 0x000000018002a920 | 0x0002a920
`public: virtual bool __cdecl CEvalNode::IsAllFalse(void) __ptr64` | 121 (0x79) | Exported Function | 0x000000018000fee0 | 0x0000fee0
`public: virtual bool __cdecl CEvalNode::IsInvalid(void) __ptr64` | 125 (0x7d) | Exported Function | 0x000000018000fee0 | 0x0000fee0
`public: virtual bool __cdecl CEvalNode::IsNoop(int) __ptr64` | 129 (0x81) | Exported Function | 0x000000018000fee0 | 0x0000fee0
`public: virtual bool __cdecl CPropertyProjectionFilter::IsInSet(class CEvalNode * __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x000000018003ceb0 | 0x0003ceb0
`public: virtual long __cdecl CEvalNode::Optimize(class CContextMetaData * __ptr64,class CEvalNode * __ptr64 * __ptr64) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018000ff50 | 0x0000ff50
`public: virtual long __cdecl CMetaData::GetClass(unsigned short const * __ptr64,struct IWbemContext * __ptr64,struct IWbemClassObject * __ptr64 * __ptr64) __ptr64` | 105 (0x69) | Exported Function | 0x000000018000ee40 | 0x0000ee40
`public: virtual long __cdecl CMetaData::QueryInterface(struct _GUID const & __ptr64,void * __ptr64 * __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x000000018002aae0 | 0x0002aae0
`public: virtual __cdecl CMetaData::~CMetaData(void) __ptr64` | 27 (0x1b) | Exported Function | 0x000000018000cbc0 | 0x0000cbc0
`public: void __cdecl CTempMemoryManager::Clear(void) __ptr64` | 76 (0x4c) | Exported Function | 0x0000000180010bc0 | 0x00010bc0
`public: int __cdecl CClassInfoArray::GetNumClasses(void) __ptr64` | 113 (0x71) | Exported Function | 0x000000018000fef0 | 0x0000fef0
`public: class CTimeKeeper & __ptr64 __cdecl CTimeKeeper::operator=(class CTimeKeeper && __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x0000000180042060 | 0x00042060
`protected: static long __cdecl CQueryAnalyser::GetPropertiesThatMustDiffer(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct CClassInformation & __ptr64,class CWStringArray & __ptr64)` | 116 (0x74) | Exported Function | 0x0000000180043620 | 0x00043620
`protected: static long __cdecl CQueryAnalyser::NegateDefiniteClassArray(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 136 (0x88) | Exported Function | 0x0000000180044130 | 0x00044130
`protected: static long __cdecl CQueryAnalyser::NegatePossibleClassArray(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 137 (0x89) | Exported Function | 0x0000000180044160 | 0x00044160
`protected: static long __cdecl CQueryAnalyser::NegateQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 138 (0x8a) | Exported Function | 0x0000000180044180 | 0x00044180
`protected: static long __cdecl CQueryAnalyser::OrDefiniteClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 141 (0x8d) | Exported Function | 0x0000000180044220 | 0x00044220
`protected: static long __cdecl CQueryAnalyser::OrPossibleClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 142 (0x8e) | Exported Function | 0x00000001800014e0 | 0x000014e0
`protected: static long __cdecl CQueryAnalyser::OrQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 143 (0x8f) | Exported Function | 0x0000000180001240 | 0x00001240
`protected: static void __cdecl CQueryAnalyser::AppendQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 66 (0x42) | Exported Function | 0x00000001800013b0 | 0x000013b0
`protected: unsigned __int64 __cdecl CTempMemoryManager::RoundUp(unsigned __int64) __ptr64` | 153 (0x99) | Exported Function | 0x00000001800104c0 | 0x000104c0
`public: __cdecl CClassInfoArray::CClassInfoArray(void) __ptr64` | 1 (0x1) | Exported Function | 0x0000000180003c70 | 0x00003c70
`public: __cdecl CClassInfoArray::~CClassInfoArray(void) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180001820 | 0x00001820
`public: __cdecl CClassInformation::CClassInformation(struct CClassInformation const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x0000000180001670 | 0x00001670
`public: __cdecl CClassInformation::CClassInformation(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180041c70 | 0x00041c70
`public: __cdecl CClassInformation::~CClassInformation(void) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180041f00 | 0x00041f00
`public: __cdecl CContextMetaData::CContextMetaData(class CMetaData * __ptr64,struct IWbemContext * __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x000000018000eed0 | 0x0000eed0
`public: __cdecl CContextMetaData::~CContextMetaData(void) __ptr64` | 24 (0x18) | Exported Function | 0x000000018000f050 | 0x0000f050
`public: __cdecl CEvalNode::CEvalNode(class CEvalNode const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x00000001800304d0 | 0x000304d0
`protected: static long __cdecl CQueryAnalyser::GetInstanceClasses(struct QL_LEVEL_1_TOKEN & __ptr64,class CClassInfoArray & __ptr64)` | 108 (0x6c) | Exported Function | 0x0000000180001ab0 | 0x00001ab0
`public: __cdecl CEvalNode::CEvalNode(void) __ptr64` | 6 (0x6) | Exported Function | 0x00000001800304d0 | 0x000304d0
`protected: static long __cdecl CQueryAnalyser::AndQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64,struct QL_LEVEL_1_RPN_EXPRESSION * __ptr64)` | 65 (0x41) | Exported Function | 0x00000001800012f0 | 0x000012f0
`protected: static long __cdecl CQueryAnalyser::AndDefiniteClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 63 (0x3f) | Exported Function | 0x00000001800421e0 | 0x000421e0
`const CMetaData::``vftable'` | 51 (0x33) | Exported Function | 0x0000000180052620 | 0x00052620
`const CPropertyProjectionFilter::``vftable'` | 52 (0x34) | Exported Function | 0x0000000180055628 | 0x00055628
`const CStandardMetaData::``vftable'` | 53 (0x35) | Exported Function | 0x00000001800525f0 | 0x000525f0
`DllCanUnloadNow` | 166 (0xa6) | Exported Function | 0x000000018000f190 | 0x0000f190
`DllGetClassObject` | 167 (0xa7) | Exported Function | 0x000000018000f210 | 0x0000f210
`DllRegisterServer` | 168 (0xa8) | Exported Function | 0x0000000180050070 | 0x00050070
`DllUnregisterServer` | 169 (0xa9) | Exported Function | 0x0000000180050240 | 0x00050240
`GetAccessMask` | 100 (0x64) | Exported Function | 0x000000018004e910 | 0x0004e910
`IsUserAdministrator` | 133 (0x85) | Exported Function | 0x000000018004ed30 | 0x0004ed30
`IsUserInGroup` | 134 (0x86) | Exported Function | 0x000000018004ed60 | 0x0004ed60
`protected: static int __cdecl CQueryAnalyser::IsPropertyInClass(class CPropertyName & __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64)` | 130 (0x82) | Exported Function | 0x0000000180043f50 | 0x00043f50
`protected: static int __cdecl CQueryAnalyser::IsTokenAboutClass(struct QL_LEVEL_1_TOKEN & __ptr64,struct IWbemClassObject * __ptr64,class CWStringArray & __ptr64)` | 131 (0x83) | Exported Function | 0x0000000180044000 | 0x00044000
`protected: static int __cdecl CQueryAnalyser::IsTokenAboutProperty(struct QL_LEVEL_1_TOKEN & __ptr64,class CPropertyName & __ptr64)` | 132 (0x84) | Exported Function | 0x0000000180044060 | 0x00044060
`protected: static int __cdecl CQueryAnalyser::SimplifyTokenForChild(struct QL_LEVEL_1_TOKEN & __ptr64,unsigned short const * __ptr64,struct IWbemClassObject * __ptr64,class CContextMetaData * __ptr64)` | 161 (0xa1) | Exported Function | 0x00000001800038f0 | 0x000038f0
`protected: static int __cdecl CQueryAnalyser::ValidateSQLDateTime(unsigned short const * __ptr64)` | 165 (0xa5) | Exported Function | 0x0000000180044560 | 0x00044560
`protected: static long __cdecl CEvalTree::CombineLeafWithBranch(class CValueNode * __ptr64,class CBranchingNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 79 (0x4f) | Exported Function | 0x0000000180038090 | 0x00038090
`protected: static long __cdecl CEvalTree::InnerCombine(class CEvalNode * __ptr64,class CEvalNode * __ptr64,int,class CContextMetaData * __ptr64,class CImplicationList & __ptr64,bool,bool,class CEvalNode * __ptr64 * __ptr64)` | 118 (0x76) | Exported Function | 0x00000001800089c0 | 0x000089c0
`protected: static long __cdecl CQueryAnalyser::AndPossibleClassArrays(class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64,class CClassInfoArray * __ptr64)` | 64 (0x40) | Exported Function | 0x0000000180042210 | 0x00042210
`public: __cdecl CEvalTree::CEvalTree(class CEvalTree const & __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x00000001800304f0 | 0x000304f0
`public: __cdecl CEvalTree::CEvalTree(void) __ptr64` | 8 (0x8) | Exported Function | 0x00000001800146f0 | 0x000146f0
`public: __cdecl CEvalTree::~CEvalTree(void) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180014690 | 0x00014690
`public: bool __cdecl CEvalTree::Clear(void) __ptr64` | 72 (0x48) | Exported Function | 0x00000001800349a0 | 0x000349a0
`public: bool __cdecl CEvalTree::IsFalse(void) __ptr64` | 122 (0x7a) | Exported Function | 0x000000018003cea0 | 0x0003cea0
`public: bool __cdecl CEvalTree::IsValid(void) __ptr64` | 135 (0x87) | Exported Function | 0x000000018003d080 | 0x0003d080
`public: bool __cdecl CEvalTree::SetBool(int) __ptr64` | 154 (0x9a) | Exported Function | 0x000000018003e5b0 | 0x0003e5b0
`public: bool __cdecl CObjectInfo::SetLength(long) __ptr64` | 155 (0x9b) | Exported Function | 0x0000000180014250 | 0x00014250
`public: bool __cdecl CPropertyProjectionFilter::AddProperty(class CPropertyName const & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x00000001800333e0 | 0x000333e0
`public: bool __cdecl CSortedArray::Remove(unsigned __int64) __ptr64` | 150 (0x96) | Exported Function | 0x000000018003e450 | 0x0003e450
`public: bool __cdecl CTimeKeeper::DecorateObject(struct _IWmiObject * __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x000000018004ef10 | 0x0004ef10
`public: class CContextMetaData & __ptr64 __cdecl CContextMetaData::operator=(class CContextMetaData const & __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x000000018002a9b0 | 0x0002a9b0
`public: class CMetaData & __ptr64 __cdecl CMetaData::operator=(class CMetaData const & __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x000000018002a9d0 | 0x0002a9d0
`public: class CObjectInfo & __ptr64 __cdecl CObjectInfo::operator=(class CObjectInfo const & __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x000000018002a9b0 | 0x0002a9b0
`public: class CPropertyProjectionFilter & __ptr64 __cdecl CPropertyProjectionFilter::operator=(class CPropertyProjectionFilter const & __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x00000001800321e0 | 0x000321e0
`public: class CQueryAnalyser & __ptr64 __cdecl CQueryAnalyser::operator=(class CQueryAnalyser && __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180042050 | 0x00042050
`public: class CQueryAnalyser & __ptr64 __cdecl CQueryAnalyser::operator=(class CQueryAnalyser const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180042050 | 0x00042050
`public: class CReuseMemoryManager & __ptr64 __cdecl CReuseMemoryManager::operator=(class CReuseMemoryManager const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x000000018002b210 | 0x0002b210
`public: class CStandardMetaData & __ptr64 __cdecl CStandardMetaData::operator=(class CStandardMetaData const & __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x000000018002a9f0 | 0x0002a9f0
`public: class CTempMemoryManager & __ptr64 __cdecl CTempMemoryManager::operator=(class CTempMemoryManager const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018002b250 | 0x0002b250
`public: bool __cdecl CClassInfoArray::SetOne(unsigned short const * __ptr64,int) __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180001c00 | 0x00001c00
`public: bool __cdecl CClassInfoArray::operator=(class CClassInfoArray & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x0000000180041f50 | 0x00041f50
`public: bool __cdecl CClassInfoArray::AddClass(struct CClassInformation * __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x0000000180001940 | 0x00001940
`public: __cdecl CTimeKeeper::~CTimeKeeper(void) __ptr64` | 34 (0x22) | Exported Function | 0x0000000180010e90 | 0x00010e90
`public: __cdecl CMetaData::CMetaData(class CMetaData const & __ptr64) __ptr64` | 9 (0x9) | Exported Function | 0x000000018002a870 | 0x0002a870
`public: __cdecl CMetaData::CMetaData(void) __ptr64` | 10 (0xa) | Exported Function | 0x000000018000a8b0 | 0x0000a8b0
`public: __cdecl CObjectInfo::CObjectInfo(void) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800308a0 | 0x000308a0
`public: __cdecl CObjectInfo::~CObjectInfo(void) __ptr64` | 28 (0x1c) | Exported Function | 0x0000000180005320 | 0x00005320
`public: __cdecl CPropertyProjectionFilter::CPropertyProjectionFilter(class CPropertyProjectionFilter const & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x00000001800309e0 | 0x000309e0
`public: __cdecl CPropertyProjectionFilter::CPropertyProjectionFilter(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180030a00 | 0x00030a00
`public: __cdecl CPropertyProjectionFilter::~CPropertyProjectionFilter(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180031d40 | 0x00031d40
`public: __cdecl CReuseMemoryManager::CReuseMemoryManager(unsigned __int64,unsigned __int64) __ptr64` | 14 (0xe) | Exported Function | 0x000000018002af50 | 0x0002af50
`public: class CTimeKeeper & __ptr64 __cdecl CTimeKeeper::operator=(class CTimeKeeper const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x00000001800420a0 | 0x000420a0
`public: __cdecl CReuseMemoryManager::~CReuseMemoryManager(void) __ptr64` | 30 (0x1e) | Exported Function | 0x000000018002b190 | 0x0002b190
`public: __cdecl CSortedArray::CSortedArray(int,int) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180030b60 | 0x00030b60
`public: __cdecl CSortedArray::CSortedArray(unsigned int,unsigned __int64 * __ptr64) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180030bb0 | 0x00030bb0
`public: __cdecl CSortedArray::~CSortedArray(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180031dc0 | 0x00031dc0
`public: __cdecl CStandardMetaData::CStandardMetaData(class CStandardMetaData const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x000000018002a890 | 0x0002a890
`public: __cdecl CStandardMetaData::CStandardMetaData(struct IWbemServices * __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x000000018000a960 | 0x0000a960
`public: __cdecl CTempMemoryManager::CTempMemoryManager(void) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180010aa0 | 0x00010aa0
`public: __cdecl CTempMemoryManager::~CTempMemoryManager(void) __ptr64` | 33 (0x21) | Exported Function | 0x0000000180010b40 | 0x00010b40
`public: __cdecl CTimeKeeper::CTimeKeeper(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180010d50 | 0x00010d50
`public: __cdecl CSortedArray::CSortedArray(class CSortedArray & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180030b10 | 0x00030b10
`public: void __cdecl CTempMemoryManager::Free(void * __ptr64,unsigned __int64) __ptr64` | 99 (0x63) | Exported Function | 0x0000000180044b50 | 0x00044b50


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


