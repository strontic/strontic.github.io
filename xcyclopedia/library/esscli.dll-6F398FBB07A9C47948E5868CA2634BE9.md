---
title: esscli.dll | WMI
excerpt: What is esscli.dll?
---

# esscli.dll 

* File Path: `C:\Windows\SysWOW64\wbem\esscli.dll`
* Description: WMI

## Hashes

Type | Hash
-- | --
MD5 | `6F398FBB07A9C47948E5868CA2634BE9`
SHA1 | `4E905B67220CB845C9CED882F1E8CD9048B6BE29`
SHA256 | `4D6934CEBDCF785EF1CB036B45AE3F470D2340DB469DD7A3A1DB01E86DB85927`
SHA384 | `9B4DBA89EFC23A1E177079DF79AA9BB9EFF8E616C27EBFC70DD23013888BFE0161A43E7C7898B900E08DA1B8BE05A64D`
SHA512 | `D6B2D7FD1EB9538F450DD920FE019F0E856D6406EB101BD5A8271D6F72F3E2651B3E80477D69C3591311A359721C00EA787396AF1A22DFDAB5A77E9CA4F3771B`
SSDEEP | `6144:YRdyGucKJcCokWPH9tEN+7E35vmOSgywg/DhHR3dcFb6TNVcVay:QyLQCokWP0oXOSgHe1RyFbMcVay`
IMP | `D9FA14142925A2C0E2CE68535FDA0D9E`
PESHA1 | `9C1EF46EA61C9AD324AA292C6F8B18894FD041BC`
PE256 | `B267A5E43686E25C05C7A5CB97E723DAF9096251C8C3DDF5970B013AF2820ABE`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const CEvalNode::``vftable'` | 50 (0x32) | Exported Function | 0x100010cc | 0x000010cc
`public: static bool __stdcall CEvalNode::IsInvalid(class CEvalNode *)` | 124 (0x7c) | Exported Function | 0x10036f50 | 0x00036f50
`public: static bool __stdcall CEvalNode::IsNoop(class CEvalNode *,int)` | 128 (0x80) | Exported Function | 0x10036f80 | 0x00036f80
`public: static class CEvalNode * __stdcall CEvalNode::CloneNode(class CEvalNode const *)` | 77 (0x4d) | Exported Function | 0x10031860 | 0x00031860
`public: static int __stdcall CEvalNode::GetType(class CEvalNode *)` | 117 (0x75) | Exported Function | 0x100059a0 | 0x000059a0
`public: static int __stdcall CEvalTree::Compare(class CEvalNode *,class CEvalNode *)` | 81 (0x51) | Exported Function | 0x10005ce0 | 0x00005ce0
`public: static int __stdcall CQueryAnalyser::CompareRequestedToProvided(class CClassInfoArray &,class CClassInfoArray &)` | 83 (0x53) | Exported Function | 0x10013540 | 0x00013540
`public: static long __stdcall CEvalTree::BuildFromToken(class CContextMetaData *,class CImplicationList &,struct QL_LEVEL_1_TOKEN &,class CEvalNode * *)` | 68 (0x44) | Exported Function | 0x100068e0 | 0x000068e0
`public: static long __stdcall CEvalTree::BuildTwoPropFromToken(class CContextMetaData *,class CImplicationList &,struct QL_LEVEL_1_TOKEN &,class CEvalNode * *)` | 69 (0x45) | Exported Function | 0x100303b0 | 0x000303b0
`public: static long __stdcall CEvalTree::Combine(class CEvalNode *,class CEvalNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 78 (0x4e) | Exported Function | 0x1000ac70 | 0x0000ac70
`public: static long __stdcall CEvalTree::CreateFromConjunction(class CContextMetaData *,class CImplicationList &,class CConjunction *,class CEvalNode * *)` | 87 (0x57) | Exported Function | 0x100065f0 | 0x000065f0
`public: static long __stdcall CEvalTree::Evaluate(class CObjectInfo &,class CEvalNode *,class CSortedArray &)` | 96 (0x60) | Exported Function | 0x10035300 | 0x00035300
`public: static long __stdcall CEvalTree::IsMergeAdvisable(class CEvalNode *,class CEvalNode *,class CImplicationList &)` | 127 (0x7f) | Exported Function | 0x10005930 | 0x00005930
`public: static long __stdcall CEvalTree::Project(class CContextMetaData *,class CImplicationList &,class CEvalNode *,class CProjectionFilter *,enum EProjectionType,bool,class CEvalNode * *)` | 145 (0x91) | Exported Function | 0x100381a0 | 0x000381a0
`public: static long __stdcall CQueryAnalyser::CanPointToClass(struct IWbemClassObject *,unsigned short const *,unsigned short const *,class CContextMetaData *)` | 70 (0x46) | Exported Function | 0x10014240 | 0x00014240
`public: static long __stdcall CQueryAnalyser::GetDefiniteInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION *,class CClassInfoArray * &)` | 107 (0x6b) | Exported Function | 0x1000fae0 | 0x0000fae0
`public: static long __stdcall CQueryAnalyser::GetLimitingQueryForInstanceClass(struct QL_LEVEL_1_RPN_EXPRESSION *,struct CClassInformation &,unsigned short * &)` | 110 (0x6e) | Exported Function | 0x1003bc00 | 0x0003bc00
`public: static long __stdcall CQueryAnalyser::GetNecessaryQueryForClass(struct QL_LEVEL_1_RPN_EXPRESSION *,struct IWbemClassObject *,class CWStringArray &,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 111 (0x6f) | Exported Function | 0x1000e060 | 0x0000e060
`public: static bool __stdcall CEvalNode::IsAllFalse(class CEvalNode *)` | 120 (0x78) | Exported Function | 0x10036e00 | 0x00036e00
`public: static long __stdcall CQueryAnalyser::GetNecessaryQueryForProperty(struct QL_LEVEL_1_RPN_EXPRESSION *,class CPropertyName &,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 112 (0x70) | Exported Function | 0x1003c630 | 0x0003c630
`public: long __thiscall CSortedArray::CopyDataFrom(unsigned long const *,unsigned int)` | 85 (0x55) | Exported Function | 0x10034200 | 0x00034200
`public: long __thiscall CSortedArray::AddDataFrom(unsigned long const *,unsigned int)` | 58 (0x3a) | Exported Function | 0x1002fcf0 | 0x0002fcf0
`public: int __thiscall CSortedArray::Add(unsigned long)` | 55 (0x37) | Exported Function | 0x1002fb20 | 0x0002fb20
`public: int __thiscall CSortedArray::Compare(class CSortedArray &)` | 82 (0x52) | Exported Function | 0x10034130 | 0x00034130
`public: int __thiscall CSortedArray::Size(void)const ` | 162 (0xa2) | Exported Function | 0x1003a0d0 | 0x0003a0d0
`public: long __thiscall CContextMetaData::GetClass(unsigned short const *,struct _IWmiObject * *)` | 104 (0x68) | Exported Function | 0x1000aa80 | 0x0000aa80
`public: long __thiscall CEvalTree::ApplyPredicate(class CLeafPredicate *)` | 67 (0x43) | Exported Function | 0x100302b0 | 0x000302b0
`public: long __thiscall CEvalTree::CombineWith(class CEvalTree &,class CContextMetaData *,int,long)` | 80 (0x50) | Exported Function | 0x100075d0 | 0x000075d0
`public: long __thiscall CEvalTree::CreateFromDNF(class CContextMetaData *,class CImplicationList &,class CDNFExpression *,class CEvalNode * *)` | 88 (0x58) | Exported Function | 0x10006520 | 0x00006520
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,struct QL_LEVEL_1_RPN_EXPRESSION *,long,long)` | 89 (0x59) | Exported Function | 0x10034340 | 0x00034340
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,unsigned short const *,int,struct QL_LEVEL_1_TOKEN *,long,long)` | 90 (0x5a) | Exported Function | 0x1000be20 | 0x0000be20
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,unsigned short const *,long,long)` | 91 (0x5b) | Exported Function | 0x1000f210 | 0x0000f210
`public: long __thiscall CEvalTree::CreateProjection(class CEvalTree &,class CContextMetaData *,class CProjectionFilter *,enum EProjectionType,bool)` | 92 (0x5c) | Exported Function | 0x10034370 | 0x00034370
`public: long __thiscall CEvalTree::Evaluate(struct IWbemObjectAccess *,class CSortedArray &)` | 95 (0x5f) | Exported Function | 0x10035250 | 0x00035250
`public: long __thiscall CEvalTree::Optimize(class CContextMetaData *)` | 140 (0x8c) | Exported Function | 0x10010320 | 0x00010320
`public: long __thiscall CEvalTree::RemoveIndex(int)` | 152 (0x98) | Exported Function | 0x100385a0 | 0x000385a0
`public: long __thiscall CEvalTree::UtilizeGuarantee(class CEvalTree &,class CContextMetaData *)` | 164 (0xa4) | Exported Function | 0x1000f720 | 0x0000f720
`public: long __thiscall CObjectInfo::GetLength(void)` | 109 (0x6d) | Exported Function | 0x10013720 | 0x00013720
`public: long __thiscall CSortedArray::AddDataFrom(class CSortedArray const &)` | 57 (0x39) | Exported Function | 0x1002fb40 | 0x0002fb40
`public: long __thiscall CSortedArray::CopyDataFrom(class CSortedArray const &)` | 84 (0x54) | Exported Function | 0x100341d0 | 0x000341d0
`public: static long __stdcall CQueryAnalyser::GetPossibleInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION *,class CClassInfoArray * &)` | 115 (0x73) | Exported Function | 0x10010c00 | 0x00010c00
`public: static long __stdcall CQueryAnalyser::SimplifyQueryForChild(struct QL_LEVEL_1_RPN_EXPRESSION *,unsigned short const *,struct IWbemClassObject *,class CContextMetaData *,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 160 (0xa0) | Exported Function | 0x1000e730 | 0x0000e730
`public: static void __stdcall CEvalNode::PrintOffset(struct _iobuf *,int)` | 144 (0x90) | Exported Function | 0x10037a70 | 0x00037a70
`public: void * __thiscall CTempMemoryManager::Allocate(unsigned int)` | 62 (0x3e) | Exported Function | 0x10012ba0 | 0x00012ba0
`public: void __thiscall CClassInfoArray::Clear(void)` | 71 (0x47) | Exported Function | 0x10013430 | 0x00013430
`public: void __thiscall CClassInfoArray::RemoveClass(int)` | 151 (0x97) | Exported Function | 0x1003d2c0 | 0x0003d2c0
`public: void __thiscall CClassInfoArray::SetLimited(int)` | 156 (0x9c) | Exported Function | 0x1003d2e0 | 0x0003d2e0
`public: void __thiscall CEvalTree::operator=(class CEvalTree const &)` | 38 (0x26) | Exported Function | 0x1002e960 | 0x0002e960
`public: void __thiscall CEvalTree::Rebase(unsigned long)` | 147 (0x93) | Exported Function | 0x10038470 | 0x00038470
`public: void __thiscall CObjectInfo::Clear(void)` | 73 (0x49) | Exported Function | 0x100310f0 | 0x000310f0
`public: void __thiscall CObjectInfo::SetObjectAt(long,struct _IWmiObject *)` | 157 (0x9d) | Exported Function | 0x10038b80 | 0x00038b80
`public: void __thiscall CReuseMemoryManager::Clear(void)` | 74 (0x4a) | Exported Function | 0x10029ec0 | 0x00029ec0
`public: void __thiscall CReuseMemoryManager::Free(void *)` | 98 (0x62) | Exported Function | 0x1002a160 | 0x0002a160
`public: void __thiscall CSortedArray::``default constructor closure'(void)` | 54 (0x36) | Exported Function | 0x1002eeb0 | 0x0002eeb0
`public: void __thiscall CSortedArray::Empty(void)` | 94 (0x5e) | Exported Function | 0x10034560 | 0x00034560
`public: void __thiscall CSortedArray::Insert(unsigned long)` | 119 (0x77) | Exported Function | 0x10035e50 | 0x00035e50
`public: void __thiscall CSortedArray::operator=(class CSortedArray const &)` | 45 (0x2d) | Exported Function | 0x1002eb80 | 0x0002eb80
`public: void __thiscall CSortedArray::Rebase(unsigned long)` | 148 (0x94) | Exported Function | 0x100384a0 | 0x000384a0
`public: void __thiscall CSortedArray::SetSize(int)` | 159 (0x9f) | Exported Function | 0x10039a70 | 0x00039a70
`public: void __thiscall CStandardMetaData::Clear(void)` | 75 (0x4b) | Exported Function | 0x10029820 | 0x00029820
`public: void * __thiscall CReuseMemoryManager::Allocate(void)` | 61 (0x3d) | Exported Function | 0x10029e60 | 0x00029e60
`public: virtual unsigned long __stdcall CMetaData::Release(void)` | 149 (0x95) | Exported Function | 0x1000d5d0 | 0x0000d5d0
`public: virtual unsigned long __stdcall CMetaData::AddRef(void)` | 60 (0x3c) | Exported Function | 0x1000d990 | 0x0000d990
`public: virtual long __thiscall CStandardMetaData::GetClass(unsigned short const *,struct IWbemContext *,struct _IWmiObject * *)` | 106 (0x6a) | Exported Function | 0x10013980 | 0x00013980
`public: struct _IWmiObject * __thiscall CObjectInfo::GetObjectAt(long)` | 114 (0x72) | Exported Function | 0x10035e30 | 0x00035e30
`public: struct CClassInformation & __thiscall CClassInformation::operator=(struct CClassInformation const &)` | 36 (0x24) | Exported Function | 0x1003ba40 | 0x0003ba40
`public: struct CClassInformation * __thiscall CClassInfoArray::GetClass(int)` | 103 (0x67) | Exported Function | 0x10013410 | 0x00013410
`public: unsigned int __thiscall CSortedArray::CopyTo(unsigned long *,unsigned int)` | 86 (0x56) | Exported Function | 0x10034290 | 0x00034290
`public: unsigned int __thiscall CSortedArray::Find(unsigned long)` | 97 (0x61) | Exported Function | 0x10035a80 | 0x00035a80
`public: unsigned long * __thiscall CSortedArray::GetArrayPtr(void)` | 101 (0x65) | Exported Function | 0x10035b90 | 0x00035b90
`public: unsigned long * __thiscall CSortedArray::UnbindPtr(void)` | 163 (0xa3) | Exported Function | 0x1003aae0 | 0x0003aae0
`public: unsigned long __thiscall CSortedArray::GetAt(int)` | 102 (0x66) | Exported Function | 0x10035ba0 | 0x00035ba0
`public: int __thiscall CClassInfoArray::IsLimited(void)` | 126 (0x7e) | Exported Function | 0x10013720 | 0x00013720
`public: virtual __thiscall CEvalNode::~CEvalNode(void)` | 25 (0x19) | Exported Function | 0x1002e500 | 0x0002e500
`public: virtual __thiscall CStandardMetaData::~CStandardMetaData(void)` | 32 (0x20) | Exported Function | 0x10029680 | 0x00029680
`public: virtual bool __thiscall CEvalNode::IsAllFalse(void)` | 121 (0x79) | Exported Function | 0x10036e30 | 0x00036e30
`public: virtual bool __thiscall CEvalNode::IsInvalid(void)` | 125 (0x7d) | Exported Function | 0x1000b790 | 0x0000b790
`public: virtual bool __thiscall CEvalNode::IsNoop(int)` | 129 (0x81) | Exported Function | 0x10036fc0 | 0x00036fc0
`public: virtual bool __thiscall CPropertyProjectionFilter::IsInSet(class CEvalNode *)` | 123 (0x7b) | Exported Function | 0x10036e70 | 0x00036e70
`public: virtual long __stdcall CMetaData::GetClass(unsigned short const *,struct IWbemContext *,struct IWbemClassObject * *)` | 105 (0x69) | Exported Function | 0x10011940 | 0x00011940
`public: virtual long __stdcall CMetaData::QueryInterface(struct _GUID const &,void * *)` | 146 (0x92) | Exported Function | 0x10029850 | 0x00029850
`public: virtual long __thiscall CEvalNode::Optimize(class CContextMetaData *,class CEvalNode * *)` | 139 (0x8b) | Exported Function | 0x10012ad0 | 0x00012ad0
`public: virtual __thiscall CMetaData::~CMetaData(void)` | 27 (0x1b) | Exported Function | 0x10010020 | 0x00010020
`public: void __thiscall CTempMemoryManager::Clear(void)` | 76 (0x4c) | Exported Function | 0x100134f0 | 0x000134f0
`public: int __thiscall CClassInfoArray::GetNumClasses(void)` | 113 (0x71) | Exported Function | 0x10012e00 | 0x00012e00
`public: class CTimeKeeper & __thiscall CTimeKeeper::operator=(class CTimeKeeper &&)` | 48 (0x30) | Exported Function | 0x1003ba70 | 0x0003ba70
`protected: static long __stdcall CQueryAnalyser::GetPropertiesThatMustDiffer(struct QL_LEVEL_1_RPN_EXPRESSION *,struct CClassInformation &,class CWStringArray &)` | 116 (0x74) | Exported Function | 0x1003c9d0 | 0x0003c9d0
`protected: static long __stdcall CQueryAnalyser::NegateDefiniteClassArray(class CClassInfoArray *,class CClassInfoArray *)` | 136 (0x88) | Exported Function | 0x1003cf90 | 0x0003cf90
`protected: static long __stdcall CQueryAnalyser::NegatePossibleClassArray(class CClassInfoArray *,class CClassInfoArray *)` | 137 (0x89) | Exported Function | 0x1003cfc0 | 0x0003cfc0
`protected: static long __stdcall CQueryAnalyser::NegateQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 138 (0x8a) | Exported Function | 0x1003cfe0 | 0x0003cfe0
`protected: static long __stdcall CQueryAnalyser::OrDefiniteClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 141 (0x8d) | Exported Function | 0x1003d050 | 0x0003d050
`protected: static long __stdcall CQueryAnalyser::OrPossibleClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 142 (0x8e) | Exported Function | 0x10011540 | 0x00011540
`protected: static long __stdcall CQueryAnalyser::OrQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 143 (0x8f) | Exported Function | 0x10010a80 | 0x00010a80
`protected: static void __stdcall CQueryAnalyser::AppendQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 66 (0x42) | Exported Function | 0x1003bb50 | 0x0003bb50
`protected: unsigned int __thiscall CTempMemoryManager::RoundUp(unsigned int)` | 153 (0x99) | Exported Function | 0x10012d40 | 0x00012d40
`public: __thiscall CClassInfoArray::CClassInfoArray(void)` | 1 (0x1) | Exported Function | 0x10011120 | 0x00011120
`public: __thiscall CClassInfoArray::~CClassInfoArray(void)` | 22 (0x16) | Exported Function | 0x10012770 | 0x00012770
`public: __thiscall CClassInformation::CClassInformation(struct CClassInformation const &)` | 2 (0x2) | Exported Function | 0x100114f0 | 0x000114f0
`public: __thiscall CClassInformation::CClassInformation(void)` | 3 (0x3) | Exported Function | 0x1003b750 | 0x0003b750
`public: __thiscall CClassInformation::~CClassInformation(void)` | 23 (0x17) | Exported Function | 0x1003b950 | 0x0003b950
`public: __thiscall CContextMetaData::CContextMetaData(class CMetaData *,struct IWbemContext *)` | 4 (0x4) | Exported Function | 0x1000f5c0 | 0x0000f5c0
`public: __thiscall CContextMetaData::~CContextMetaData(void)` | 24 (0x18) | Exported Function | 0x1000d3d0 | 0x0000d3d0
`public: __thiscall CEvalNode::CEvalNode(class CEvalNode const &)` | 5 (0x5) | Exported Function | 0x1002d180 | 0x0002d180
`protected: static long __stdcall CQueryAnalyser::GetInstanceClasses(struct QL_LEVEL_1_TOKEN &,class CClassInfoArray &)` | 108 (0x6c) | Exported Function | 0x100111d0 | 0x000111d0
`public: __thiscall CEvalNode::CEvalNode(void)` | 6 (0x6) | Exported Function | 0x1002d190 | 0x0002d190
`protected: static long __stdcall CQueryAnalyser::AndQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 65 (0x41) | Exported Function | 0x10010990 | 0x00010990
`protected: static long __stdcall CQueryAnalyser::AndDefiniteClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 63 (0x3f) | Exported Function | 0x1003baf0 | 0x0003baf0
`const CMetaData::``vftable'` | 51 (0x33) | Exported Function | 0x10001238 | 0x00001238
`const CPropertyProjectionFilter::``vftable'` | 52 (0x34) | Exported Function | 0x10002aec | 0x00002aec
`const CStandardMetaData::``vftable'` | 53 (0x35) | Exported Function | 0x10001250 | 0x00001250
`DllCanUnloadNow` | 166 (0xa6) | Exported Function | 0x100120b0 | 0x000120b0
`DllGetClassObject` | 167 (0xa7) | Exported Function | 0x10012150 | 0x00012150
`DllRegisterServer` | 168 (0xa8) | Exported Function | 0x10046ac0 | 0x00046ac0
`DllUnregisterServer` | 169 (0xa9) | Exported Function | 0x10046c20 | 0x00046c20
`GetAccessMask` | 100 (0x64) | Exported Function | 0x10045900 | 0x00045900
`IsUserAdministrator` | 133 (0x85) | Exported Function | 0x10045be0 | 0x00045be0
`IsUserInGroup` | 134 (0x86) | Exported Function | 0x10045c10 | 0x00045c10
`protected: static int __stdcall CQueryAnalyser::IsPropertyInClass(class CPropertyName &,struct IWbemClassObject *,class CWStringArray &)` | 130 (0x82) | Exported Function | 0x1003ce50 | 0x0003ce50
`protected: static int __stdcall CQueryAnalyser::IsTokenAboutClass(struct QL_LEVEL_1_TOKEN &,struct IWbemClassObject *,class CWStringArray &)` | 131 (0x83) | Exported Function | 0x1003ceb0 | 0x0003ceb0
`protected: static int __stdcall CQueryAnalyser::IsTokenAboutProperty(struct QL_LEVEL_1_TOKEN &,class CPropertyName &)` | 132 (0x84) | Exported Function | 0x1003cf00 | 0x0003cf00
`protected: static int __stdcall CQueryAnalyser::SimplifyTokenForChild(struct QL_LEVEL_1_TOKEN &,unsigned short const *,struct IWbemClassObject *,class CContextMetaData *)` | 161 (0xa1) | Exported Function | 0x1000ed20 | 0x0000ed20
`protected: static int __stdcall CQueryAnalyser::ValidateSQLDateTime(unsigned short const *)` | 165 (0xa5) | Exported Function | 0x1003d390 | 0x0003d390
`protected: static long __stdcall CEvalTree::CombineLeafWithBranch(class CValueNode *,class CBranchingNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 79 (0x4f) | Exported Function | 0x10033c60 | 0x00033c60
`protected: static long __stdcall CEvalTree::InnerCombine(class CEvalNode *,class CEvalNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 118 (0x76) | Exported Function | 0x1000b0d0 | 0x0000b0d0
`protected: static long __stdcall CQueryAnalyser::AndPossibleClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 64 (0x40) | Exported Function | 0x1003bb20 | 0x0003bb20
`public: __thiscall CEvalTree::CEvalTree(class CEvalTree const &)` | 7 (0x7) | Exported Function | 0x1002d1a0 | 0x0002d1a0
`public: __thiscall CEvalTree::CEvalTree(void)` | 8 (0x8) | Exported Function | 0x1000f540 | 0x0000f540
`public: __thiscall CEvalTree::~CEvalTree(void)` | 26 (0x1a) | Exported Function | 0x1002e510 | 0x0002e510
`public: bool __thiscall CEvalTree::Clear(void)` | 72 (0x48) | Exported Function | 0x10031080 | 0x00031080
`public: bool __thiscall CEvalTree::IsFalse(void)` | 122 (0x7a) | Exported Function | 0x10036e60 | 0x00036e60
`public: bool __thiscall CEvalTree::IsValid(void)` | 135 (0x87) | Exported Function | 0x10037020 | 0x00037020
`public: bool __thiscall CEvalTree::SetBool(int)` | 154 (0x9a) | Exported Function | 0x100386c0 | 0x000386c0
`public: bool __thiscall CObjectInfo::SetLength(long)` | 155 (0x9b) | Exported Function | 0x100387f0 | 0x000387f0
`public: bool __thiscall CPropertyProjectionFilter::AddProperty(class CPropertyName const &)` | 59 (0x3b) | Exported Function | 0x1002fe40 | 0x0002fe40
`public: bool __thiscall CSortedArray::Remove(unsigned long)` | 150 (0x96) | Exported Function | 0x10038510 | 0x00038510
`public: bool __thiscall CTimeKeeper::DecorateObject(struct _IWmiObject *)` | 93 (0x5d) | Exported Function | 0x10045d80 | 0x00045d80
`public: class CContextMetaData & __thiscall CContextMetaData::operator=(class CContextMetaData const &)` | 37 (0x25) | Exported Function | 0x10029730 | 0x00029730
`public: class CMetaData & __thiscall CMetaData::operator=(class CMetaData const &)` | 39 (0x27) | Exported Function | 0x10029750 | 0x00029750
`public: class CObjectInfo & __thiscall CObjectInfo::operator=(class CObjectInfo const &)` | 40 (0x28) | Exported Function | 0x10029730 | 0x00029730
`public: class CPropertyProjectionFilter & __thiscall CPropertyProjectionFilter::operator=(class CPropertyProjectionFilter const &)` | 41 (0x29) | Exported Function | 0x10029750 | 0x00029750
`public: class CQueryAnalyser & __thiscall CQueryAnalyser::operator=(class CQueryAnalyser &&)` | 42 (0x2a) | Exported Function | 0x1003ba60 | 0x0003ba60
`public: class CQueryAnalyser & __thiscall CQueryAnalyser::operator=(class CQueryAnalyser const &)` | 43 (0x2b) | Exported Function | 0x1003ba60 | 0x0003ba60
`public: class CReuseMemoryManager & __thiscall CReuseMemoryManager::operator=(class CReuseMemoryManager const &)` | 44 (0x2c) | Exported Function | 0x10029df0 | 0x00029df0
`public: class CStandardMetaData & __thiscall CStandardMetaData::operator=(class CStandardMetaData const &)` | 46 (0x2e) | Exported Function | 0x10029770 | 0x00029770
`public: class CTempMemoryManager & __thiscall CTempMemoryManager::operator=(class CTempMemoryManager const &)` | 47 (0x2f) | Exported Function | 0x10029e10 | 0x00029e10
`public: bool __thiscall CClassInfoArray::SetOne(unsigned short const *,int)` | 158 (0x9e) | Exported Function | 0x1003d300 | 0x0003d300
`public: bool __thiscall CClassInfoArray::operator=(class CClassInfoArray &)` | 35 (0x23) | Exported Function | 0x1003b9b0 | 0x0003b9b0
`public: bool __thiscall CClassInfoArray::AddClass(struct CClassInformation *)` | 56 (0x38) | Exported Function | 0x1003bad0 | 0x0003bad0
`public: __thiscall CTimeKeeper::~CTimeKeeper(void)` | 34 (0x22) | Exported Function | 0x10013770 | 0x00013770
`public: __thiscall CMetaData::CMetaData(class CMetaData const &)` | 9 (0x9) | Exported Function | 0x100295a0 | 0x000295a0
`public: __thiscall CMetaData::CMetaData(void)` | 10 (0xa) | Exported Function | 0x1000d3b0 | 0x0000d3b0
`public: __thiscall CObjectInfo::CObjectInfo(void)` | 11 (0xb) | Exported Function | 0x1002d3c0 | 0x0002d3c0
`public: __thiscall CObjectInfo::~CObjectInfo(void)` | 28 (0x1c) | Exported Function | 0x1000f4c0 | 0x0000f4c0
`public: __thiscall CPropertyProjectionFilter::CPropertyProjectionFilter(class CPropertyProjectionFilter const &)` | 12 (0xc) | Exported Function | 0x1002d4b0 | 0x0002d4b0
`public: __thiscall CPropertyProjectionFilter::CPropertyProjectionFilter(void)` | 13 (0xd) | Exported Function | 0x1002d4d0 | 0x0002d4d0
`public: __thiscall CPropertyProjectionFilter::~CPropertyProjectionFilter(void)` | 29 (0x1d) | Exported Function | 0x1002e740 | 0x0002e740
`public: __thiscall CReuseMemoryManager::CReuseMemoryManager(unsigned int,unsigned int)` | 14 (0xe) | Exported Function | 0x10029b40 | 0x00029b40
`public: class CTimeKeeper & __thiscall CTimeKeeper::operator=(class CTimeKeeper const &)` | 49 (0x31) | Exported Function | 0x1003bab0 | 0x0003bab0
`public: __thiscall CReuseMemoryManager::~CReuseMemoryManager(void)` | 30 (0x1e) | Exported Function | 0x10029d80 | 0x00029d80
`public: __thiscall CSortedArray::CSortedArray(int,int)` | 16 (0x10) | Exported Function | 0x1002d5b0 | 0x0002d5b0
`public: __thiscall CSortedArray::CSortedArray(unsigned int,unsigned long *)` | 17 (0x11) | Exported Function | 0x1002d5e0 | 0x0002d5e0
`public: __thiscall CSortedArray::~CSortedArray(void)` | 31 (0x1f) | Exported Function | 0x1002e820 | 0x0002e820
`public: __thiscall CStandardMetaData::CStandardMetaData(class CStandardMetaData const &)` | 18 (0x12) | Exported Function | 0x100295c0 | 0x000295c0
`public: __thiscall CStandardMetaData::CStandardMetaData(struct IWbemServices *)` | 19 (0x13) | Exported Function | 0x1000d4b0 | 0x0000d4b0
`public: __thiscall CTempMemoryManager::CTempMemoryManager(void)` | 20 (0x14) | Exported Function | 0x100133a0 | 0x000133a0
`public: __thiscall CTempMemoryManager::~CTempMemoryManager(void)` | 33 (0x21) | Exported Function | 0x10013470 | 0x00013470
`public: __thiscall CTimeKeeper::CTimeKeeper(void)` | 21 (0x15) | Exported Function | 0x10013600 | 0x00013600
`public: __thiscall CSortedArray::CSortedArray(class CSortedArray &)` | 15 (0xf) | Exported Function | 0x1002d580 | 0x0002d580
`public: void __thiscall CTempMemoryManager::Free(void *,unsigned int)` | 99 (0x63) | Exported Function | 0x1003d6a0 | 0x0003d6a0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/66
* VirusTotal Link: https://www.virustotal.com/gui/file/4d6934cebdcf785ef1cb036b45ae3f470d2340db469dd7a3a1db01e86db85927/detection/





MIT License. Copyright (c) 2020 Strontic.


