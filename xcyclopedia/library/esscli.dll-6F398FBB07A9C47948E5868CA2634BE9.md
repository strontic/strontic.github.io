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

Function Name | Ordinal | Type
-- | -- | --
`public: static int __stdcall CQueryAnalyser::CompareRequestedToProvided(class CClassInfoArray &,class CClassInfoArray &)` | 83 | Exported Function
`public: static int __stdcall CEvalTree::Compare(class CEvalNode *,class CEvalNode *)` | 81 | Exported Function
`public: static long __stdcall CEvalTree::BuildFromToken(class CContextMetaData *,class CImplicationList &,struct QL_LEVEL_1_TOKEN &,class CEvalNode * *)` | 68 | Exported Function
`public: static long __stdcall CEvalTree::Combine(class CEvalNode *,class CEvalNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 78 | Exported Function
`public: static long __stdcall CEvalTree::BuildTwoPropFromToken(class CContextMetaData *,class CImplicationList &,struct QL_LEVEL_1_TOKEN &,class CEvalNode * *)` | 69 | Exported Function
`public: static bool __stdcall CEvalNode::IsInvalid(class CEvalNode *)` | 124 | Exported Function
`public: static bool __stdcall CEvalNode::IsAllFalse(class CEvalNode *)` | 120 | Exported Function
`public: static bool __stdcall CEvalNode::IsNoop(class CEvalNode *,int)` | 128 | Exported Function
`public: static int __stdcall CEvalNode::GetType(class CEvalNode *)` | 117 | Exported Function
`public: static class CEvalNode * __stdcall CEvalNode::CloneNode(class CEvalNode const *)` | 77 | Exported Function
`public: static long __stdcall CEvalTree::CreateFromConjunction(class CContextMetaData *,class CImplicationList &,class CConjunction *,class CEvalNode * *)` | 87 | Exported Function
`public: static long __stdcall CQueryAnalyser::GetNecessaryQueryForClass(struct QL_LEVEL_1_RPN_EXPRESSION *,struct IWbemClassObject *,class CWStringArray &,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 111 | Exported Function
`public: static long __stdcall CQueryAnalyser::GetLimitingQueryForInstanceClass(struct QL_LEVEL_1_RPN_EXPRESSION *,struct CClassInformation &,unsigned short * &)` | 110 | Exported Function
`public: static long __stdcall CQueryAnalyser::GetNecessaryQueryForProperty(struct QL_LEVEL_1_RPN_EXPRESSION *,class CPropertyName &,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 112 | Exported Function
`public: static long __stdcall CQueryAnalyser::SimplifyQueryForChild(struct QL_LEVEL_1_RPN_EXPRESSION *,unsigned short const *,struct IWbemClassObject *,class CContextMetaData *,struct QL_LEVEL_1_RPN_EXPRESSION * &)` | 160 | Exported Function
`public: static long __stdcall CQueryAnalyser::GetPossibleInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION *,class CClassInfoArray * &)` | 115 | Exported Function
`public: static long __stdcall CEvalTree::IsMergeAdvisable(class CEvalNode *,class CEvalNode *,class CImplicationList &)` | 127 | Exported Function
`public: static long __stdcall CEvalTree::Evaluate(class CObjectInfo &,class CEvalNode *,class CSortedArray &)` | 96 | Exported Function
`public: static long __stdcall CEvalTree::Project(class CContextMetaData *,class CImplicationList &,class CEvalNode *,class CProjectionFilter *,enum EProjectionType,bool,class CEvalNode * *)` | 145 | Exported Function
`public: static long __stdcall CQueryAnalyser::GetDefiniteInstanceClasses(struct QL_LEVEL_1_RPN_EXPRESSION *,class CClassInfoArray * &)` | 107 | Exported Function
`public: static long __stdcall CQueryAnalyser::CanPointToClass(struct IWbemClassObject *,unsigned short const *,unsigned short const *,class CContextMetaData *)` | 70 | Exported Function
`public: long __thiscall CEvalTree::CombineWith(class CEvalTree &,class CContextMetaData *,int,long)` | 80 | Exported Function
`public: long __thiscall CEvalTree::ApplyPredicate(class CLeafPredicate *)` | 67 | Exported Function
`public: long __thiscall CEvalTree::CreateFromDNF(class CContextMetaData *,class CImplicationList &,class CDNFExpression *,class CEvalNode * *)` | 88 | Exported Function
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,unsigned short const *,int,struct QL_LEVEL_1_TOKEN *,long,long)` | 90 | Exported Function
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,struct QL_LEVEL_1_RPN_EXPRESSION *,long,long)` | 89 | Exported Function
`public: int __thiscall CSortedArray::Add(unsigned long)` | 55 | Exported Function
`public: int __thiscall CClassInfoArray::IsLimited(void)` | 126 | Exported Function
`public: int __thiscall CSortedArray::Compare(class CSortedArray &)` | 82 | Exported Function
`public: long __thiscall CContextMetaData::GetClass(unsigned short const *,struct _IWmiObject * *)` | 104 | Exported Function
`public: int __thiscall CSortedArray::Size(void)const ` | 162 | Exported Function
`public: long __thiscall CEvalTree::CreateFromQuery(class CContextMetaData *,unsigned short const *,long,long)` | 91 | Exported Function
`public: long __thiscall CSortedArray::AddDataFrom(class CSortedArray const &)` | 57 | Exported Function
`public: long __thiscall CObjectInfo::GetLength(void)` | 109 | Exported Function
`public: long __thiscall CSortedArray::AddDataFrom(unsigned long const *,unsigned int)` | 58 | Exported Function
`public: long __thiscall CSortedArray::CopyDataFrom(unsigned long const *,unsigned int)` | 85 | Exported Function
`public: long __thiscall CSortedArray::CopyDataFrom(class CSortedArray const &)` | 84 | Exported Function
`public: long __thiscall CEvalTree::Evaluate(struct IWbemObjectAccess *,class CSortedArray &)` | 95 | Exported Function
`public: long __thiscall CEvalTree::CreateProjection(class CEvalTree &,class CContextMetaData *,class CProjectionFilter *,enum EProjectionType,bool)` | 92 | Exported Function
`public: long __thiscall CEvalTree::Optimize(class CContextMetaData *)` | 140 | Exported Function
`public: long __thiscall CEvalTree::UtilizeGuarantee(class CEvalTree &,class CContextMetaData *)` | 164 | Exported Function
`public: long __thiscall CEvalTree::RemoveIndex(int)` | 152 | Exported Function
`public: void __thiscall CEvalTree::operator=(class CEvalTree const &)` | 38 | Exported Function
`public: void __thiscall CClassInfoArray::SetLimited(int)` | 156 | Exported Function
`public: void __thiscall CEvalTree::Rebase(unsigned long)` | 147 | Exported Function
`public: void __thiscall CObjectInfo::SetObjectAt(long,struct _IWmiObject *)` | 157 | Exported Function
`public: void __thiscall CObjectInfo::Clear(void)` | 73 | Exported Function
`public: void * __thiscall CReuseMemoryManager::Allocate(void)` | 61 | Exported Function
`public: virtual unsigned long __stdcall CMetaData::Release(void)` | 149 | Exported Function
`public: void * __thiscall CTempMemoryManager::Allocate(unsigned int)` | 62 | Exported Function
`public: void __thiscall CClassInfoArray::RemoveClass(int)` | 151 | Exported Function
`public: void __thiscall CClassInfoArray::Clear(void)` | 71 | Exported Function
`public: void __thiscall CReuseMemoryManager::Clear(void)` | 74 | Exported Function
`public: void __thiscall CSortedArray::SetSize(int)` | 159 | Exported Function
`public: void __thiscall CSortedArray::Rebase(unsigned long)` | 148 | Exported Function
`public: void __thiscall CStandardMetaData::Clear(void)` | 75 | Exported Function
`public: void __thiscall CTempMemoryManager::Free(void *,unsigned int)` | 99 | Exported Function
`public: void __thiscall CTempMemoryManager::Clear(void)` | 76 | Exported Function
`public: void __thiscall CSortedArray::``default constructor closure'(void)` | 54 | Exported Function
`public: void __thiscall CReuseMemoryManager::Free(void *)` | 98 | Exported Function
`public: void __thiscall CSortedArray::Empty(void)` | 94 | Exported Function
`public: void __thiscall CSortedArray::operator=(class CSortedArray const &)` | 45 | Exported Function
`public: void __thiscall CSortedArray::Insert(unsigned long)` | 119 | Exported Function
`public: unsigned long * __thiscall CSortedArray::GetArrayPtr(void)` | 101 | Exported Function
`public: unsigned int __thiscall CSortedArray::Find(unsigned long)` | 97 | Exported Function
`public: unsigned long * __thiscall CSortedArray::UnbindPtr(void)` | 163 | Exported Function
`public: virtual __thiscall CEvalNode::~CEvalNode(void)` | 25 | Exported Function
`public: unsigned long __thiscall CSortedArray::GetAt(int)` | 102 | Exported Function
`public: struct _IWmiObject * __thiscall CObjectInfo::GetObjectAt(long)` | 114 | Exported Function
`public: static void __stdcall CEvalNode::PrintOffset(struct _iobuf *,int)` | 144 | Exported Function
`public: struct CClassInformation & __thiscall CClassInformation::operator=(struct CClassInformation const &)` | 36 | Exported Function
`public: unsigned int __thiscall CSortedArray::CopyTo(unsigned long *,unsigned int)` | 86 | Exported Function
`public: struct CClassInformation * __thiscall CClassInfoArray::GetClass(int)` | 103 | Exported Function
`public: virtual __thiscall CMetaData::~CMetaData(void)` | 27 | Exported Function
`public: virtual long __stdcall CMetaData::QueryInterface(struct _GUID const &,void * *)` | 146 | Exported Function
`public: virtual long __stdcall CMetaData::GetClass(unsigned short const *,struct IWbemContext *,struct IWbemClassObject * *)` | 105 | Exported Function
`public: virtual long __thiscall CEvalNode::Optimize(class CContextMetaData *,class CEvalNode * *)` | 139 | Exported Function
`public: virtual unsigned long __stdcall CMetaData::AddRef(void)` | 60 | Exported Function
`public: virtual long __thiscall CStandardMetaData::GetClass(unsigned short const *,struct IWbemContext *,struct _IWmiObject * *)` | 106 | Exported Function
`public: virtual bool __thiscall CEvalNode::IsAllFalse(void)` | 121 | Exported Function
`public: virtual __thiscall CStandardMetaData::~CStandardMetaData(void)` | 32 | Exported Function
`public: virtual bool __thiscall CEvalNode::IsInvalid(void)` | 125 | Exported Function
`public: virtual bool __thiscall CPropertyProjectionFilter::IsInSet(class CEvalNode *)` | 123 | Exported Function
`public: virtual bool __thiscall CEvalNode::IsNoop(int)` | 129 | Exported Function
`public: int __thiscall CClassInfoArray::GetNumClasses(void)` | 113 | Exported Function
`protected: static long __stdcall CQueryAnalyser::OrPossibleClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 142 | Exported Function
`protected: static long __stdcall CQueryAnalyser::OrDefiniteClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 141 | Exported Function
`protected: static long __stdcall CQueryAnalyser::OrQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 143 | Exported Function
`protected: unsigned int __thiscall CTempMemoryManager::RoundUp(unsigned int)` | 153 | Exported Function
`protected: static void __stdcall CQueryAnalyser::AppendQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 66 | Exported Function
`protected: static long __stdcall CQueryAnalyser::GetPropertiesThatMustDiffer(struct QL_LEVEL_1_RPN_EXPRESSION *,struct CClassInformation &,class CWStringArray &)` | 116 | Exported Function
`protected: static long __stdcall CQueryAnalyser::GetInstanceClasses(struct QL_LEVEL_1_TOKEN &,class CClassInfoArray &)` | 108 | Exported Function
`protected: static long __stdcall CQueryAnalyser::NegateDefiniteClassArray(class CClassInfoArray *,class CClassInfoArray *)` | 136 | Exported Function
`protected: static long __stdcall CQueryAnalyser::NegateQueryExpression(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 138 | Exported Function
`protected: static long __stdcall CQueryAnalyser::NegatePossibleClassArray(class CClassInfoArray *,class CClassInfoArray *)` | 137 | Exported Function
`public: __thiscall CClassInfoArray::CClassInfoArray(void)` | 1 | Exported Function
`public: __thiscall CEvalNode::CEvalNode(class CEvalNode const &)` | 5 | Exported Function
`public: __thiscall CContextMetaData::~CContextMetaData(void)` | 24 | Exported Function
`public: __thiscall CEvalNode::CEvalNode(void)` | 6 | Exported Function
`public: __thiscall CEvalTree::CEvalTree(void)` | 8 | Exported Function
`public: __thiscall CEvalTree::CEvalTree(class CEvalTree const &)` | 7 | Exported Function
`public: __thiscall CClassInformation::CClassInformation(struct CClassInformation const &)` | 2 | Exported Function
`public: __thiscall CClassInfoArray::~CClassInfoArray(void)` | 22 | Exported Function
`public: __thiscall CClassInformation::CClassInformation(void)` | 3 | Exported Function
`public: __thiscall CContextMetaData::CContextMetaData(class CMetaData *,struct IWbemContext *)` | 4 | Exported Function
`public: __thiscall CClassInformation::~CClassInformation(void)` | 23 | Exported Function
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
`protected: static long __stdcall CEvalTree::InnerCombine(class CEvalNode *,class CEvalNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 118 | Exported Function
`protected: static long __stdcall CEvalTree::CombineLeafWithBranch(class CValueNode *,class CBranchingNode *,int,class CContextMetaData *,class CImplicationList &,bool,bool,class CEvalNode * *)` | 79 | Exported Function
`protected: static long __stdcall CQueryAnalyser::AndDefiniteClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 63 | Exported Function
`protected: static long __stdcall CQueryAnalyser::AndQueryExpressions(struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *,struct QL_LEVEL_1_RPN_EXPRESSION *)` | 65 | Exported Function
`protected: static long __stdcall CQueryAnalyser::AndPossibleClassArrays(class CClassInfoArray *,class CClassInfoArray *,class CClassInfoArray *)` | 64 | Exported Function
`protected: static int __stdcall CQueryAnalyser::IsTokenAboutClass(struct QL_LEVEL_1_TOKEN &,struct IWbemClassObject *,class CWStringArray &)` | 131 | Exported Function
`protected: static int __stdcall CQueryAnalyser::IsPropertyInClass(class CPropertyName &,struct IWbemClassObject *,class CWStringArray &)` | 130 | Exported Function
`protected: static int __stdcall CQueryAnalyser::IsTokenAboutProperty(struct QL_LEVEL_1_TOKEN &,class CPropertyName &)` | 132 | Exported Function
`protected: static int __stdcall CQueryAnalyser::ValidateSQLDateTime(unsigned short const *)` | 165 | Exported Function
`protected: static int __stdcall CQueryAnalyser::SimplifyTokenForChild(struct QL_LEVEL_1_TOKEN &,unsigned short const *,struct IWbemClassObject *,class CContextMetaData *)` | 161 | Exported Function
`public: bool __thiscall CObjectInfo::SetLength(long)` | 155 | Exported Function
`public: bool __thiscall CEvalTree::SetBool(int)` | 154 | Exported Function
`public: bool __thiscall CPropertyProjectionFilter::AddProperty(class CPropertyName const &)` | 59 | Exported Function
`public: bool __thiscall CTimeKeeper::DecorateObject(struct _IWmiObject *)` | 93 | Exported Function
`public: bool __thiscall CSortedArray::Remove(unsigned long)` | 150 | Exported Function
`public: bool __thiscall CClassInfoArray::SetOne(unsigned short const *,int)` | 158 | Exported Function
`public: bool __thiscall CClassInfoArray::operator=(class CClassInfoArray &)` | 35 | Exported Function
`public: bool __thiscall CEvalTree::Clear(void)` | 72 | Exported Function
`public: bool __thiscall CEvalTree::IsValid(void)` | 135 | Exported Function
`public: bool __thiscall CEvalTree::IsFalse(void)` | 122 | Exported Function
`public: class CContextMetaData & __thiscall CContextMetaData::operator=(class CContextMetaData const &)` | 37 | Exported Function
`public: class CStandardMetaData & __thiscall CStandardMetaData::operator=(class CStandardMetaData const &)` | 46 | Exported Function
`public: class CReuseMemoryManager & __thiscall CReuseMemoryManager::operator=(class CReuseMemoryManager const &)` | 44 | Exported Function
`public: class CTempMemoryManager & __thiscall CTempMemoryManager::operator=(class CTempMemoryManager const &)` | 47 | Exported Function
`public: class CTimeKeeper & __thiscall CTimeKeeper::operator=(class CTimeKeeper const &)` | 49 | Exported Function
`public: class CTimeKeeper & __thiscall CTimeKeeper::operator=(class CTimeKeeper &&)` | 48 | Exported Function
`public: class CObjectInfo & __thiscall CObjectInfo::operator=(class CObjectInfo const &)` | 40 | Exported Function
`public: class CMetaData & __thiscall CMetaData::operator=(class CMetaData const &)` | 39 | Exported Function
`public: class CPropertyProjectionFilter & __thiscall CPropertyProjectionFilter::operator=(class CPropertyProjectionFilter const &)` | 41 | Exported Function
`public: class CQueryAnalyser & __thiscall CQueryAnalyser::operator=(class CQueryAnalyser const &)` | 43 | Exported Function
`public: class CQueryAnalyser & __thiscall CQueryAnalyser::operator=(class CQueryAnalyser &&)` | 42 | Exported Function
`public: __thiscall CPropertyProjectionFilter::CPropertyProjectionFilter(void)` | 13 | Exported Function
`public: __thiscall CPropertyProjectionFilter::CPropertyProjectionFilter(class CPropertyProjectionFilter const &)` | 12 | Exported Function
`public: __thiscall CPropertyProjectionFilter::~CPropertyProjectionFilter(void)` | 29 | Exported Function
`public: __thiscall CReuseMemoryManager::~CReuseMemoryManager(void)` | 30 | Exported Function
`public: __thiscall CReuseMemoryManager::CReuseMemoryManager(unsigned int,unsigned int)` | 14 | Exported Function
`public: __thiscall CMetaData::CMetaData(class CMetaData const &)` | 9 | Exported Function
`public: __thiscall CEvalTree::~CEvalTree(void)` | 26 | Exported Function
`public: __thiscall CMetaData::CMetaData(void)` | 10 | Exported Function
`public: __thiscall CObjectInfo::~CObjectInfo(void)` | 28 | Exported Function
`public: __thiscall CObjectInfo::CObjectInfo(void)` | 11 | Exported Function
`public: __thiscall CSortedArray::CSortedArray(class CSortedArray &)` | 15 | Exported Function
`public: __thiscall CTempMemoryManager::~CTempMemoryManager(void)` | 33 | Exported Function
`public: __thiscall CTempMemoryManager::CTempMemoryManager(void)` | 20 | Exported Function
`public: __thiscall CTimeKeeper::CTimeKeeper(void)` | 21 | Exported Function
`public: bool __thiscall CClassInfoArray::AddClass(struct CClassInformation *)` | 56 | Exported Function
`public: __thiscall CTimeKeeper::~CTimeKeeper(void)` | 34 | Exported Function
`public: __thiscall CSortedArray::CSortedArray(unsigned int,unsigned long *)` | 17 | Exported Function
`public: __thiscall CSortedArray::CSortedArray(int,int)` | 16 | Exported Function
`public: __thiscall CSortedArray::~CSortedArray(void)` | 31 | Exported Function
`public: __thiscall CStandardMetaData::CStandardMetaData(struct IWbemServices *)` | 19 | Exported Function
`public: __thiscall CStandardMetaData::CStandardMetaData(class CStandardMetaData const &)` | 18 | Exported Function


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


