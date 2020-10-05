---
title: provthrd.dll | WMI Provider Thread & Log Library
excerpt: What is provthrd.dll?
---

# provthrd.dll 

* File Path: `C:\Windows\system32\provthrd.dll`
* Description: WMI Provider Thread & Log Library

## Hashes

Type | Hash
-- | --
MD5 | `FB444274833D6E97D35F34C9ECA52AD0`
SHA1 | `9691FBFE47245911077F45C389CCC9CF0070402A`
SHA256 | `6995774C4F464F6A5077EE33957920F539038C8ACD501BB404C4AD1A8F78667E`
SHA384 | `FD59BE18799BA42DA81E9DA450C747F7547BBBECEDAEF2E4D9FDF0A64D5B47685F9C7A124879D7D5FFD795933F454338`
SHA512 | `0F5E7D75738C0864281E9D2903F2F11A9BB4C1AC0A74CDD28A33FD5C625F7BCE94EB0DD85FD218C1323EFDE305ECD8452B1EE605539FAA2FC1201469B5E0CCDD`
SSDEEP | `6144:lDojENwUN5yaGsHVn/y5DdJM6fCJ+rei1W4ckPHmbWZ:lDLVn/i9AkPWW`
IMP | `664F98A16E717D758A9217E003BC7587`
PESHA1 | `0C0103EF707FBF2CD8249D1B46CD01DCE8019BCE`
PE256 | `FC40C3EEFF5877D3251082C83B7C1F2AFA97FF02F6F8D7937DEA2033E8F01034`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned char * __ptr64 __cdecl ProvOpaque::GetValue(void)const __ptr64` | 758 | Exported Function
`public: unsigned char * __ptr64 __cdecl ProvOctetStringType::GetValue(void)const __ptr64` | 757 | Exported Function
`public: unsigned char * __ptr64 __cdecl ProvOctetString::GetValue(void)const __ptr64` | 756 | Exported Function
`public: unsigned char * __ptr64 __cdecl ProvOpaqueType::GetValue(void)const __ptr64` | 759 | Exported Function
`public: unsigned long * __ptr64 __cdecl ProvObjectIdentifierType::GetValue(void)const __ptr64` | 755 | Exported Function
`public: unsigned long * __ptr64 __cdecl ProvObjectIdentifier::GetValue(void)const __ptr64` | 754 | Exported Function
`public: unsigned long & __ptr64 __cdecl ProvObjectIdentifier::operator[](unsigned long)const __ptr64` | 392 | Exported Function
`public: union ProvLexiconValue * __ptr64 __cdecl ProvLexicon::GetValue(void) __ptr64` | 752 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::OctWCharToDecInteger(unsigned short)` | 815 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::OctCharToDecInteger(char)` | 814 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::HexWCharToDecInteger(unsigned short)` | 774 | Exported Function
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToDecWChar(unsigned char)` | 608 | Exported Function
`public: static void __cdecl ProvDebugLog::Closedown(void)` | 531 | Exported Function
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToOctWChar(unsigned char)` | 612 | Exported Function
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToHexWChar(unsigned char)` | 610 | Exported Function
`public: unsigned long __cdecl ProvDebugLog::GetLevel(void) __ptr64` | 678 | Exported Function
`public: unsigned long __cdecl ProvCounterType::GetValue(void)const __ptr64` | 741 | Exported Function
`public: unsigned long __cdecl ProvCounter::GetValue(void)const __ptr64` | 740 | Exported Function
`public: unsigned long __cdecl ProvGauge::GetValue(void)const __ptr64` | 746 | Exported Function
`public: unsigned long __cdecl ProvIpAddressType::GetValue(void)const __ptr64` | 751 | Exported Function
`public: unsigned long __cdecl ProvIpAddress::GetValue(void)const __ptr64` | 750 | Exported Function
`public: unsigned long __cdecl ProvGaugeType::GetValue(void)const __ptr64` | 747 | Exported Function
`public: unsigned long __cdecl ProvCounter64::GetLowValue(void)const __ptr64` | 680 | Exported Function
`public: unsigned long __cdecl Disjunctions::GetDisjunctionCount(void) __ptr64` | 666 | Exported Function
`public: unsigned long __cdecl Disjunctions::GetConjunctionCount(void) __ptr64` | 661 | Exported Function
`public: unsigned long __cdecl Conjunctions::GetRangeCount(void) __ptr64` | 706 | Exported Function
`public: unsigned long __cdecl PartitionSet::GetKeyIndex(void) __ptr64` | 675 | Exported Function
`public: unsigned long __cdecl ProvCounter64::GetHighValue(void)const __ptr64` | 668 | Exported Function
`public: unsigned long __cdecl ProvBitStringType::GetValue(unsigned short * __ptr64 * __ptr64 & __ptr64)const __ptr64` | 738 | Exported Function
`public: unsigned long __cdecl PartitionSet::GetPartitionCount(void) __ptr64` | 689 | Exported Function
`public: long __cdecl WmiValueNode::ComparePropertyName(class WmiValueNode & __ptr64) __ptr64` | 534 | Exported Function
`public: long __cdecl WmiSignedIntegerRangeNode::UpperBound(void) __ptr64` | 952 | Exported Function
`public: long __cdecl WmiSignedIntegerRangeNode::LowerBound(void) __ptr64` | 807 | Exported Function
`public: static char __cdecl ProvAnalyser::DecIntegerToDecChar(unsigned char)` | 607 | Exported Function
`public: static class ProvDebugLog * __ptr64 __cdecl ProvDebugLog::GetProvDebugLog(char)` | 693 | Exported Function
`public: static char __cdecl ProvAnalyser::DecIntegerToOctChar(unsigned char)` | 611 | Exported Function
`public: static char __cdecl ProvAnalyser::DecIntegerToHexChar(unsigned char)` | 609 | Exported Function
`public: long __cdecl WmiSignedIntegerNode::GetValue(void) __ptr64` | 764 | Exported Function
`public: long __cdecl ProvInteger::GetValue(void)const __ptr64` | 748 | Exported Function
`public: int __cdecl WmiUnsignedIntegerNode::LexicographicallyBefore(unsigned long & __ptr64) __ptr64` | 806 | Exported Function
`public: int __cdecl WmiUnsignedIntegerNode::LexicographicallyAfter(unsigned long & __ptr64) __ptr64` | 803 | Exported Function
`public: long __cdecl ProvIntegerType::GetValue(void)const __ptr64` | 749 | Exported Function
`public: long __cdecl WmiRangeNode::ComparePropertyName(class WmiRangeNode & __ptr64) __ptr64` | 533 | Exported Function
`public: long __cdecl ProvNegativeRangeType::GetUpperBound(void) __ptr64` | 736 | Exported Function
`public: long __cdecl ProvNegativeRangeType::GetLowerBound(void) __ptr64` | 681 | Exported Function
`public: static int __cdecl ProvDebugLog::Startup(void)` | 925 | Exported Function
`public: static int __cdecl ProvAnalyser::IsWhitespace(unsigned short)` | 799 | Exported Function
`public: static int __cdecl ProvAnalyser::IsOctal(unsigned short)` | 792 | Exported Function
`public: static long ProvDebugLog::s_ReferenceCount` | 964 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::HexCharToDecInteger(char)` | 773 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::DecWCharToDecInteger(unsigned short)` | 613 | Exported Function
`public: static unsigned long __cdecl ProvAnalyser::DecCharToDecInteger(char)` | 606 | Exported Function
`public: static int __cdecl ProvAnalyser::IsLeadingDecimal(unsigned short)` | 790 | Exported Function
`public: static int __cdecl ProvAnalyser::IsAlpha(unsigned short)` | 785 | Exported Function
`public: static class ProvDebugLog * ProvDebugLog::s_aLogs` | 965 | Exported Function
`public: static class ProvDebugLog * __ptr64 __ptr64 ProvDebugLog::s_ProvDebugLog` | 963 | Exported Function
`public: static int __cdecl ProvAnalyser::IsAlphaNumeric(unsigned short)` | 786 | Exported Function
`public: static int __cdecl ProvAnalyser::IsHex(unsigned short)` | 789 | Exported Function
`public: static int __cdecl ProvAnalyser::IsEof(unsigned short)` | 788 | Exported Function
`public: static int __cdecl ProvAnalyser::IsDecimal(unsigned short)` | 787 | Exported Function
`public: virtual __cdecl ProvEventObject::~ProvEventObject(void) __ptr64` | 241 | Exported Function
`public: virtual __cdecl ProvEnumeratedType::~ProvEnumeratedType(void) __ptr64` | 240 | Exported Function
`public: virtual __cdecl ProvDisplayStringType::~ProvDisplayStringType(void) __ptr64` | 239 | Exported Function
`public: virtual __cdecl ProvFixedLengthDisplayStringType::~ProvFixedLengthDisplayStringType(void) __ptr64` | 242 | Exported Function
`public: virtual __cdecl ProvFixedLengthPhysAddressType::~ProvFixedLengthPhysAddressType(void) __ptr64` | 245 | Exported Function
`public: virtual __cdecl ProvFixedLengthOpaqueType::~ProvFixedLengthOpaqueType(void) __ptr64` | 244 | Exported Function
`public: virtual __cdecl ProvFixedLengthOctetStringType::~ProvFixedLengthOctetStringType(void) __ptr64` | 243 | Exported Function
`public: virtual __cdecl ProvDateTimeType::~ProvDateTimeType(void) __ptr64` | 238 | Exported Function
`public: virtual __cdecl ProvBitStringType::~ProvBitStringType(void) __ptr64` | 233 | Exported Function
`public: virtual __cdecl ProvAnalyser::~ProvAnalyser(void) __ptr64` | 232 | Exported Function
`public: virtual __cdecl ProvAnalyser::operator void * __ptr64(void) __ptr64` | 393 | Exported Function
`public: virtual __cdecl ProvCounter64::~ProvCounter64(void) __ptr64` | 234 | Exported Function
`public: virtual __cdecl ProvCounterType::~ProvCounterType(void) __ptr64` | 237 | Exported Function
`public: virtual __cdecl ProvCounter::~ProvCounter(void) __ptr64` | 236 | Exported Function
`public: virtual __cdecl ProvCounter64Type::~ProvCounter64Type(void) __ptr64` | 235 | Exported Function
`public: virtual __cdecl ProvNegativeRangeType::~ProvNegativeRangeType(void) __ptr64` | 256 | Exported Function
`public: virtual __cdecl ProvMacAddressType::~ProvMacAddressType(void) __ptr64` | 255 | Exported Function
`public: virtual __cdecl ProvIpAddressType::~ProvIpAddressType(void) __ptr64` | 253 | Exported Function
`public: virtual __cdecl ProvNetworkAddressType::~ProvNetworkAddressType(void) __ptr64` | 257 | Exported Function
`public: virtual __cdecl ProvObjectIdentifier::~ProvObjectIdentifier(void) __ptr64` | 261 | Exported Function
`public: virtual __cdecl ProvNullType::~ProvNullType(void) __ptr64` | 259 | Exported Function
`public: virtual __cdecl ProvNull::~ProvNull(void) __ptr64` | 258 | Exported Function
`public: virtual __cdecl ProvIpAddress::~ProvIpAddress(void) __ptr64` | 252 | Exported Function
`public: virtual __cdecl ProvGaugeType::~ProvGaugeType(void) __ptr64` | 248 | Exported Function
`public: virtual __cdecl ProvGauge::~ProvGauge(void) __ptr64` | 247 | Exported Function
`public: virtual __cdecl ProvFixedType::~ProvFixedType(void) __ptr64` | 246 | Exported Function
`public: virtual __cdecl ProvInstanceType::operator void * __ptr64(void) __ptr64` | 394 | Exported Function
`public: virtual __cdecl ProvIntegerType::~ProvIntegerType(void) __ptr64` | 251 | Exported Function
`public: virtual __cdecl ProvInteger::~ProvInteger(void) __ptr64` | 250 | Exported Function
`public: virtual __cdecl ProvInstanceType::~ProvInstanceType(void) __ptr64` | 249 | Exported Function
`public: unsigned long __cdecl ProvTimeTicksType::GetValue(void)const __ptr64` | 762 | Exported Function
`public: unsigned long __cdecl ProvTimeTicks::GetValue(void)const __ptr64` | 761 | Exported Function
`public: unsigned long __cdecl ProvPositiveRangeType::GetUpperBound(void) __ptr64` | 737 | Exported Function
`public: unsigned long __cdecl ProvUInteger32::GetValue(void)const __ptr64` | 763 | Exported Function
`public: unsigned long __cdecl WmiUnsignedIntegerNode::GetValue(void) __ptr64` | 766 | Exported Function
`public: unsigned long __cdecl WmiTreeNode::GetType(void) __ptr64` | 735 | Exported Function
`public: unsigned long __cdecl WmiRangeNode::GetIndex(void) __ptr64` | 669 | Exported Function
`public: unsigned long __cdecl ProvPositiveRangeType::GetLowerBound(void) __ptr64` | 682 | Exported Function
`public: unsigned long __cdecl ProvObjectIdentifierType::GetValueLength(void)const __ptr64` | 768 | Exported Function
`public: unsigned long __cdecl ProvObjectIdentifier::GetValueLength(void)const __ptr64` | 767 | Exported Function
`public: unsigned long __cdecl ProvNetworkAddressType::GetValue(void)const __ptr64` | 753 | Exported Function
`public: unsigned long __cdecl ProvOctetString::GetValueLength(void)const __ptr64` | 769 | Exported Function
`public: unsigned long __cdecl ProvOpaqueType::GetValueLength(void)const __ptr64` | 772 | Exported Function
`public: unsigned long __cdecl ProvOpaque::GetValueLength(void)const __ptr64` | 771 | Exported Function
`public: unsigned long __cdecl ProvOctetStringType::GetValueLength(void)const __ptr64` | 770 | Exported Function
`public: unsigned short * __ptr64 __cdecl WmiStringNode::GetValue(void) __ptr64` | 765 | Exported Function
`public: unsigned short * __ptr64 __cdecl WmiRangeNode::GetPropertyName(void) __ptr64` | 691 | Exported Function
`public: unsigned short * __ptr64 __cdecl ProvRowStatusType::GetValue(void)const __ptr64` | 760 | Exported Function
`public: unsigned short * __ptr64 __cdecl WmiStringRangeNode::LowerBound(void) __ptr64` | 808 | Exported Function
`public: virtual __cdecl PartitionSet::~PartitionSet(void) __ptr64` | 231 | Exported Function
`public: unsigned short * __ptr64 __cdecl WmiValueNode::GetPropertyName(void) __ptr64` | 692 | Exported Function
`public: unsigned short * __ptr64 __cdecl WmiStringRangeNode::UpperBound(void) __ptr64` | 953 | Exported Function
`public: unsigned short * __ptr64 __cdecl ProvFixedLengthDisplayStringType::GetValue(void)const __ptr64` | 745 | Exported Function
`public: unsigned long __cdecl WmiValueNode::GetIndex(void) __ptr64` | 670 | Exported Function
`public: unsigned long __cdecl WmiUnsignedIntegerRangeNode::UpperBound(void) __ptr64` | 954 | Exported Function
`public: unsigned long __cdecl WmiUnsignedIntegerRangeNode::LowerBound(void) __ptr64` | 809 | Exported Function
`public: unsigned short * __ptr64 __cdecl CBString::GetString(void) __ptr64` | 710 | Exported Function
`public: unsigned short * __ptr64 __cdecl ProvEnumeratedType::GetValue(void)const __ptr64` | 744 | Exported Function
`public: unsigned short * __ptr64 __cdecl ProvDisplayStringType::GetValue(void)const __ptr64` | 743 | Exported Function
`public: unsigned short * __ptr64 __cdecl ProvDateTimeType::GetValue(void)const __ptr64` | 742 | Exported Function
`public: int __cdecl WmiStringNode::LexicographicallyBefore(unsigned short * __ptr64 & __ptr64) __ptr64` | 805 | Exported Function
`public: class WmiOperatorLikeNode & __ptr64 __cdecl WmiOperatorLikeNode::operator=(class WmiOperatorLikeNode const & __ptr64) __ptr64` | 366 | Exported Function
`public: class WmiOperatorLessNode & __ptr64 __cdecl WmiOperatorLessNode::operator=(class WmiOperatorLessNode const & __ptr64) __ptr64` | 365 | Exported Function
`public: class WmiOperatorIsANode & __ptr64 __cdecl WmiOperatorIsANode::operator=(class WmiOperatorIsANode const & __ptr64) __ptr64` | 364 | Exported Function
`public: class WmiOperatorNode & __ptr64 __cdecl WmiOperatorNode::operator=(class WmiOperatorNode const & __ptr64) __ptr64` | 367 | Exported Function
`public: class WmiOperatorNotLikeNode & __ptr64 __cdecl WmiOperatorNotLikeNode::operator=(class WmiOperatorNotLikeNode const & __ptr64) __ptr64` | 370 | Exported Function
`public: class WmiOperatorNotIsANode & __ptr64 __cdecl WmiOperatorNotIsANode::operator=(class WmiOperatorNotIsANode const & __ptr64) __ptr64` | 369 | Exported Function
`public: class WmiOperatorNotEqualNode & __ptr64 __cdecl WmiOperatorNotEqualNode::operator=(class WmiOperatorNotEqualNode const & __ptr64) __ptr64` | 368 | Exported Function
`public: class WmiOperatorGreaterNode & __ptr64 __cdecl WmiOperatorGreaterNode::operator=(class WmiOperatorGreaterNode const & __ptr64) __ptr64` | 363 | Exported Function
`public: class WmiNullNode & __ptr64 __cdecl WmiNullNode::operator=(class WmiNullNode const & __ptr64) __ptr64` | 358 | Exported Function
`public: class WmiNullNode & __ptr64 __cdecl WmiNullNode::operator=(class WmiNullNode && __ptr64) __ptr64` | 357 | Exported Function
`public: class WmiNotNode & __ptr64 __cdecl WmiNotNode::operator=(class WmiNotNode const & __ptr64) __ptr64` | 356 | Exported Function
`public: class WmiNullRangeNode & __ptr64 __cdecl WmiNullRangeNode::operator=(class WmiNullRangeNode const & __ptr64) __ptr64` | 359 | Exported Function
`public: class WmiOperatorEqualOrLessNode & __ptr64 __cdecl WmiOperatorEqualOrLessNode::operator=(class WmiOperatorEqualOrLessNode const & __ptr64) __ptr64` | 362 | Exported Function
`public: class WmiOperatorEqualOrGreaterNode & __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::operator=(class WmiOperatorEqualOrGreaterNode const & __ptr64) __ptr64` | 361 | Exported Function
`public: class WmiOperatorEqualNode & __ptr64 __cdecl WmiOperatorEqualNode::operator=(class WmiOperatorEqualNode const & __ptr64) __ptr64` | 360 | Exported Function
`public: class WmiTreeNode & __ptr64 __cdecl WmiTreeNode::operator=(class WmiTreeNode const & __ptr64) __ptr64` | 379 | Exported Function
`public: class WmiStringRangeNode & __ptr64 __cdecl WmiStringRangeNode::operator=(class WmiStringRangeNode const & __ptr64) __ptr64` | 378 | Exported Function
`public: class WmiStringNode & __ptr64 __cdecl WmiStringNode::operator=(class WmiStringNode const & __ptr64) __ptr64` | 377 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetLeft(void) __ptr64` | 676 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetLeft(class WmiTreeNode * __ptr64) __ptr64` | 897 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetRight(void) __ptr64` | 707 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetParent(void) __ptr64` | 686 | Exported Function
`public: class WmiSignedIntegerRangeNode & __ptr64 __cdecl WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode const & __ptr64) __ptr64` | 376 | Exported Function
`public: class WmiRangeNode * __ptr64 __cdecl Conjunctions::GetRange(unsigned long) __ptr64` | 694 | Exported Function
`public: class WmiRangeNode & __ptr64 __cdecl WmiRangeNode::operator=(class WmiRangeNode const & __ptr64) __ptr64` | 372 | Exported Function
`public: class WmiOrNode & __ptr64 __cdecl WmiOrNode::operator=(class WmiOrNode const & __ptr64) __ptr64` | 371 | Exported Function
`public: class WmiRangeNode * __ptr64 __cdecl PartitionSet::GetRange(void) __ptr64` | 695 | Exported Function
`public: class WmiSignedIntegerRangeNode & __ptr64 __cdecl WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode && __ptr64) __ptr64` | 375 | Exported Function
`public: class WmiSignedIntegerNode & __ptr64 __cdecl WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode const & __ptr64) __ptr64` | 374 | Exported Function
`public: class WmiSignedIntegerNode & __ptr64 __cdecl WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode && __ptr64) __ptr64` | 373 | Exported Function
`public: class ProvOSIAddressType & __ptr64 __cdecl ProvOSIAddressType::operator=(class ProvOSIAddressType const & __ptr64) __ptr64` | 338 | Exported Function
`public: class ProvOpaqueType & __ptr64 __cdecl ProvOpaqueType::operator=(class ProvOpaqueType const & __ptr64) __ptr64` | 344 | Exported Function
`public: class ProvOctetStringType & __ptr64 __cdecl ProvOctetStringType::operator=(class ProvOctetStringType const & __ptr64) __ptr64` | 342 | Exported Function
`public: class ProvPhysAddressType & __ptr64 __cdecl ProvPhysAddressType::operator=(class ProvPhysAddressType const & __ptr64) __ptr64` | 345 | Exported Function
`public: class ProvRowStatusType & __ptr64 __cdecl ProvRowStatusType::operator=(class ProvRowStatusType const & __ptr64) __ptr64` | 348 | Exported Function
`public: class ProvPositiveRangeType & __ptr64 __cdecl ProvPositiveRangeType::operator=(class ProvPositiveRangeType const & __ptr64) __ptr64` | 346 | Exported Function
`public: class ProvPositiveRangedType & __ptr64 __cdecl ProvPositiveRangedType::operator=(class ProvPositiveRangedType const & __ptr64) __ptr64` | 347 | Exported Function
`public: class ProvObjectIdentifierType & __ptr64 __cdecl ProvObjectIdentifierType::operator=(class ProvObjectIdentifierType const & __ptr64) __ptr64` | 340 | Exported Function
`public: class ProvNegativeRangeType & __ptr64 __cdecl ProvNegativeRangeType::operator=(class ProvNegativeRangeType const & __ptr64) __ptr64` | 334 | Exported Function
`public: class ProvMacAddressType & __ptr64 __cdecl ProvMacAddressType::operator=(class ProvMacAddressType const & __ptr64) __ptr64` | 333 | Exported Function
`public: class ProvLexicon * __ptr64 __cdecl ProvAnalyser::Get(int,int,int) __ptr64` | 655 | Exported Function
`public: class ProvNetworkAddressType & __ptr64 __cdecl ProvNetworkAddressType::operator=(class ProvNetworkAddressType const & __ptr64) __ptr64` | 335 | Exported Function
`public: class ProvObjectIdentifier __cdecl ProvObjectIdentifier::operator+(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 396 | Exported Function
`public: class ProvObjectIdentifier * __ptr64 __cdecl ProvObjectIdentifier::Cut(class ProvObjectIdentifier & __ptr64)const __ptr64` | 603 | Exported Function
`public: class ProvNullType & __ptr64 __cdecl ProvNullType::operator=(class ProvNullType const & __ptr64) __ptr64` | 337 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvOpaque::operator=(class ProvOpaque const & __ptr64) __ptr64` | 343 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvOctetString::operator=(class ProvOctetString const & __ptr64) __ptr64` | 341 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvObjectIdentifier::operator=(class ProvObjectIdentifier const & __ptr64) __ptr64` | 339 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvTimeTicks::operator=(class ProvTimeTicks const & __ptr64) __ptr64` | 349 | Exported Function
`public: class WmiAndNode & __ptr64 __cdecl WmiAndNode::operator=(class WmiAndNode const & __ptr64) __ptr64` | 355 | Exported Function
`public: class QueryPreprocessor & __ptr64 __cdecl QueryPreprocessor::operator=(class QueryPreprocessor const & __ptr64) __ptr64` | 354 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvUInteger32::operator=(class ProvUInteger32 const & __ptr64) __ptr64` | 352 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvNull::operator=(class ProvNull const & __ptr64) __ptr64` | 336 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvCounter64::operator=(class ProvCounter64 const & __ptr64) __ptr64` | 310 | Exported Function
`public: class ProvUDPAddressType & __ptr64 __cdecl ProvUDPAddressType::operator=(class ProvUDPAddressType const & __ptr64) __ptr64` | 351 | Exported Function
`public: class ProvTimeTicksType & __ptr64 __cdecl ProvTimeTicksType::operator=(class ProvTimeTicksType const & __ptr64) __ptr64` | 350 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvCounter::operator=(class ProvCounter const & __ptr64) __ptr64` | 312 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvIpAddress::operator=(class ProvIpAddress const & __ptr64) __ptr64` | 330 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvInteger::operator=(class ProvInteger const & __ptr64) __ptr64` | 328 | Exported Function
`public: class ProvValue & __ptr64 __cdecl ProvGauge::operator=(class ProvGauge const & __ptr64) __ptr64` | 325 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator==(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 387 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator<=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 398 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator<(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 397 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator>(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 399 | Exported Function
`public: int __cdecl ProvObjectIdentifier::Suffix(unsigned long,class ProvObjectIdentifier & __ptr64)const __ptr64` | 926 | Exported Function
`public: int __cdecl ProvObjectIdentifier::Prefix(unsigned long,class ProvObjectIdentifier & __ptr64)const __ptr64` | 839 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator>=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 400 | Exported Function
`public: int __cdecl ProvObjectIdentifier::operator!=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 390 | Exported Function
`public: int __cdecl ProvInstanceType::operator!=(class ProvInstanceType const & __ptr64)const __ptr64` | 389 | Exported Function
`public: int __cdecl ProvGauge::Equivalent(class ProvGauge const & __ptr64)const __ptr64` | 624 | Exported Function
`public: int __cdecl ProvDebugLog::GetLogging(void) __ptr64` | 679 | Exported Function
`public: int __cdecl ProvInstanceType::operator==(class ProvInstanceType const & __ptr64)const __ptr64` | 386 | Exported Function
`public: int __cdecl ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const & __ptr64,unsigned long)const __ptr64` | 637 | Exported Function
`public: int __cdecl ProvIpAddress::Equivalent(class ProvIpAddress const & __ptr64)const __ptr64` | 630 | Exported Function
`public: int __cdecl ProvInteger::Equivalent(class ProvInteger const & __ptr64)const __ptr64` | 627 | Exported Function
`public: int __cdecl WmiRangeNode::InfiniteLowerBound(void) __ptr64` | 775 | Exported Function
`public: int __cdecl WmiRangeNode::ClosedUpperBound(void) __ptr64` | 530 | Exported Function
`public: int __cdecl WmiRangeNode::ClosedLowerBound(void) __ptr64` | 529 | Exported Function
`public: int __cdecl WmiRangeNode::InfiniteUpperBound(void) __ptr64` | 776 | Exported Function
`public: int __cdecl WmiStringNode::LexicographicallyAfter(unsigned short * __ptr64 & __ptr64) __ptr64` | 802 | Exported Function
`public: int __cdecl WmiSignedIntegerNode::LexicographicallyBefore(long & __ptr64) __ptr64` | 804 | Exported Function
`public: int __cdecl WmiSignedIntegerNode::LexicographicallyAfter(long & __ptr64) __ptr64` | 801 | Exported Function
`public: int __cdecl ProvValue::operator==(class ProvValue const & __ptr64)const __ptr64` | 388 | Exported Function
`public: int __cdecl ProvPositiveRangedType::Check(unsigned long const & __ptr64) __ptr64` | 527 | Exported Function
`public: int __cdecl ProvOpaque::Equivalent(class ProvOpaque const & __ptr64)const __ptr64` | 643 | Exported Function
`public: int __cdecl ProvOctetString::Equivalent(class ProvOctetString const & __ptr64)const __ptr64` | 640 | Exported Function
`public: int __cdecl ProvPositiveRangedType::IsValid(void) __ptr64` | 798 | Exported Function
`public: int __cdecl ProvValue::operator!=(class ProvValue const & __ptr64)const __ptr64` | 391 | Exported Function
`public: int __cdecl ProvUInteger32::Equivalent(class ProvUInteger32 const & __ptr64)const __ptr64` | 649 | Exported Function
`public: int __cdecl ProvTimeTicks::Equivalent(class ProvTimeTicks const & __ptr64)const __ptr64` | 646 | Exported Function
`public: enum ProvLexicon::LexiconToken __cdecl ProvLexicon::GetToken(void) __ptr64` | 734 | Exported Function
`public: class WmiValueNode & __ptr64 __cdecl WmiValueNode::operator=(class WmiValueNode const & __ptr64) __ptr64` | 385 | Exported Function
`public: class WmiUnsignedIntegerRangeNode & __ptr64 __cdecl WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode const & __ptr64) __ptr64` | 384 | Exported Function
`public: enum ProvRowStatusType::ProvRowStatusEnum __cdecl ProvRowStatusType::GetRowStatus(void)const __ptr64` | 709 | Exported Function
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::Query(unsigned short * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64) __ptr64` | 869 | Exported Function
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::PreProcess(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64,class WmiTreeNode * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,class PartitionSet * __ptr64 & __ptr64) __ptr64` | 838 | Exported Function
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::PreProcess(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 837 | Exported Function
`public: class WmiUnsignedIntegerRangeNode & __ptr64 __cdecl WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode && __ptr64) __ptr64` | 383 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNodeIterator::GetIterator(void) __ptr64` | 674 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetRight(class WmiTreeNode * __ptr64) __ptr64` | 905 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetParent(class WmiTreeNode * __ptr64) __ptr64` | 901 | Exported Function
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNodeIterator::SetIterator(class WmiTreeNode * __ptr64) __ptr64` | 895 | Exported Function
`public: class WmiUnsignedIntegerNode & __ptr64 __cdecl WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode const & __ptr64) __ptr64` | 382 | Exported Function
`public: class WmiUnsignedIntegerNode & __ptr64 __cdecl WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode && __ptr64) __ptr64` | 381 | Exported Function
`public: class WmiTreeNodeIterator & __ptr64 __cdecl WmiTreeNodeIterator::operator=(class WmiTreeNodeIterator const & __ptr64) __ptr64` | 380 | Exported Function
`public: enum WmiValueNode::WmiValueFunction __cdecl WmiValueNode::GetPropertyFunction(void) __ptr64` | 690 | Exported Function
`public: enum WmiValueNode::WmiValueFunction __cdecl WmiValueNode::GetConstantFunction(void) __ptr64` | 662 | Exported Function
`public: enum WmiTriState __cdecl WmiUnsignedIntegerRangeNode::GetOverlappingRange(class WmiUnsignedIntegerRangeNode & __ptr64,class WmiUnsignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 685 | Exported Function
`public: int __cdecl PartitionSet::Leaf(void) __ptr64` | 800 | Exported Function
`public: int __cdecl ProvCounter::Equivalent(class ProvCounter const & __ptr64)const __ptr64` | 621 | Exported Function
`public: int __cdecl ProvCounter64::Equivalent(class ProvCounter64 const & __ptr64)const __ptr64` | 618 | Exported Function
`public: int __cdecl PartitionSet::Root(void) __ptr64` | 891 | Exported Function
`public: enum WmiTriState __cdecl WmiUnsignedIntegerRangeNode::GetIntersectingRange(class WmiUnsignedIntegerRangeNode & __ptr64,class WmiUnsignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 673 | Exported Function
`public: enum WmiTriState __cdecl PartitionSet::Initialize(unsigned long) __ptr64` | 780 | Exported Function
`public: enum WmiTriState __cdecl Disjunctions::Initialize(void) __ptr64` | 779 | Exported Function
`public: enum WmiTriState __cdecl Conjunctions::Initialize(void) __ptr64` | 778 | Exported Function
`public: enum WmiTriState __cdecl WmiSignedIntegerRangeNode::GetIntersectingRange(class WmiSignedIntegerRangeNode & __ptr64,class WmiSignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 671 | Exported Function
`public: enum WmiTriState __cdecl WmiStringRangeNode::GetOverlappingRange(class WmiStringRangeNode & __ptr64,class WmiStringRangeNode * __ptr64 & __ptr64) __ptr64` | 684 | Exported Function
`public: enum WmiTriState __cdecl WmiStringRangeNode::GetIntersectingRange(class WmiStringRangeNode & __ptr64,class WmiStringRangeNode * __ptr64 & __ptr64) __ptr64` | 672 | Exported Function
`public: enum WmiTriState __cdecl WmiSignedIntegerRangeNode::GetOverlappingRange(class WmiSignedIntegerRangeNode & __ptr64,class WmiSignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 683 | Exported Function
`public: virtual void __cdecl WmiSignedIntegerRangeNode::Print(void) __ptr64` | 856 | Exported Function
`public: virtual void __cdecl WmiSignedIntegerNode::Print(void) __ptr64` | 855 | Exported Function
`public: virtual void __cdecl WmiOrNode::Print(void) __ptr64` | 854 | Exported Function
`public: virtual void __cdecl WmiStringNode::Print(void) __ptr64` | 857 | Exported Function
`public: virtual void __cdecl WmiUnsignedIntegerNode::Print(void) __ptr64` | 860 | Exported Function
`public: virtual void __cdecl WmiTreeNode::Print(void) __ptr64` | 859 | Exported Function
`public: virtual void __cdecl WmiStringRangeNode::Print(void) __ptr64` | 858 | Exported Function
`public: virtual void __cdecl WmiOperatorNotLikeNode::Print(void) __ptr64` | 853 | Exported Function
`public: virtual void __cdecl WmiOperatorIsANode::Print(void) __ptr64` | 848 | Exported Function
`public: virtual void __cdecl WmiOperatorGreaterNode::Print(void) __ptr64` | 847 | Exported Function
`public: virtual void __cdecl WmiOperatorEqualOrLessNode::Print(void) __ptr64` | 846 | Exported Function
`public: virtual void __cdecl WmiOperatorLessNode::Print(void) __ptr64` | 849 | Exported Function
`public: virtual void __cdecl WmiOperatorNotIsANode::Print(void) __ptr64` | 852 | Exported Function
`public: virtual void __cdecl WmiOperatorNotEqualNode::Print(void) __ptr64` | 851 | Exported Function
`public: virtual void __cdecl WmiOperatorLikeNode::Print(void) __ptr64` | 850 | Exported Function
`public: void __cdecl PartitionSet::SetPartition(unsigned long,class PartitionSet * __ptr64) __ptr64` | 902 | Exported Function
`public: void __cdecl PartitionSet::SetKeyIndex(unsigned long) __ptr64` | 896 | Exported Function
`public: void __cdecl Conjunctions::SetRange(unsigned long,class WmiRangeNode * __ptr64) __ptr64` | 903 | Exported Function
`public: void __cdecl PartitionSet::SetRange(class WmiRangeNode * __ptr64) __ptr64` | 904 | Exported Function
`public: void __cdecl ProvAnalyser::Set(unsigned short const * __ptr64) __ptr64` | 892 | Exported Function
`public: void __cdecl ProvAnalyser::PutBack(class ProvLexicon const * __ptr64) __ptr64` | 868 | Exported Function
`public: void __cdecl ProvAnalyser::``default constructor closure'(void) __ptr64` | 499 | Exported Function
`public: void * __ptr64 __cdecl WmiTreeNode::SetData(void * __ptr64) __ptr64` | 894 | Exported Function
`public: void * __ptr64 __cdecl ProvIpAddress::operator()(void)const __ptr64` | 401 | Exported Function
`public: void * __ptr64 __cdecl ProvEventObject::GetHandle(void) __ptr64` | 667 | Exported Function
`public: virtual void __cdecl WmiUnsignedIntegerRangeNode::Print(void) __ptr64` | 861 | Exported Function
`public: void * __ptr64 __cdecl ProvObjectIdentifier::operator()(void)const __ptr64` | 402 | Exported Function
`public: void * __ptr64 __cdecl WmiTreeNode::GetData(void) __ptr64` | 663 | Exported Function
`public: void * __ptr64 __cdecl ProvOpaque::operator()(void)const __ptr64` | 404 | Exported Function
`public: void * __ptr64 __cdecl ProvOctetString::operator()(void)const __ptr64` | 403 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvIpAddressType::GetStringValue(void)const __ptr64` | 721 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvIntegerType::GetStringValue(void)const __ptr64` | 720 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvGaugeType::GetStringValue(void)const __ptr64` | 719 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvMacAddressType::GetStringValue(void)const __ptr64` | 722 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvObjectIdentifierType::GetStringValue(void)const __ptr64` | 726 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvNullType::GetStringValue(void)const __ptr64` | 724 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvNetworkAddressType::GetStringValue(void)const __ptr64` | 723 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvFixedLengthPhysAddressType::GetStringValue(void)const __ptr64` | 718 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvCounterType::GetStringValue(void)const __ptr64` | 713 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvCounter64Type::GetStringValue(void)const __ptr64` | 712 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvBitStringType::GetStringValue(void)const __ptr64` | 711 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvDateTimeType::GetStringValue(void)const __ptr64` | 714 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvFixedLengthDisplayStringType::GetStringValue(void)const __ptr64` | 717 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvEnumeratedType::GetStringValue(void)const __ptr64` | 716 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvDisplayStringType::GetStringValue(void)const __ptr64` | 715 | Exported Function
`public: virtual void __cdecl WmiNotNode::Print(void) __ptr64` | 841 | Exported Function
`public: virtual void __cdecl WmiAndNode::Print(void) __ptr64` | 840 | Exported Function
`public: virtual void __cdecl ProvEventObject::Process(void) __ptr64` | 863 | Exported Function
`public: virtual void __cdecl WmiNullNode::Print(void) __ptr64` | 842 | Exported Function
`public: virtual void __cdecl WmiOperatorEqualOrGreaterNode::Print(void) __ptr64` | 845 | Exported Function
`public: virtual void __cdecl WmiOperatorEqualNode::Print(void) __ptr64` | 844 | Exported Function
`public: virtual void __cdecl WmiNullRangeNode::Print(void) __ptr64` | 843 | Exported Function
`public: virtual void __cdecl ProvEventObject::Complete(void) __ptr64` | 535 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvOSIAddressType::GetStringValue(void)const __ptr64` | 725 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvOpaqueType::GetStringValue(void)const __ptr64` | 728 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvOctetStringType::GetStringValue(void)const __ptr64` | 727 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvPhysAddressType::GetStringValue(void)const __ptr64` | 729 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvUDPAddressType::GetStringValue(void)const __ptr64` | 732 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvTimeTicksType::GetStringValue(void)const __ptr64` | 731 | Exported Function
`public: virtual unsigned short * __ptr64 __cdecl ProvRowStatusType::GetStringValue(void)const __ptr64` | 730 | Exported Function
`public: void __cdecl WmiOperatorEqualOrGreaterNode::``default constructor closure'(void) __ptr64` | 512 | Exported Function
`public: void __cdecl WmiOperatorEqualNode::``default constructor closure'(void) __ptr64` | 511 | Exported Function
`public: void __cdecl WmiNotNode::``default constructor closure'(void) __ptr64` | 510 | Exported Function
`public: void __cdecl WmiOperatorEqualOrLessNode::``default constructor closure'(void) __ptr64` | 513 | Exported Function
`public: void __cdecl WmiOperatorLessNode::``default constructor closure'(void) __ptr64` | 516 | Exported Function
`public: void __cdecl WmiOperatorIsANode::``default constructor closure'(void) __ptr64` | 515 | Exported Function
`public: void __cdecl WmiOperatorGreaterNode::``default constructor closure'(void) __ptr64` | 514 | Exported Function
`public: void __cdecl WmiAndNode::``default constructor closure'(void) __ptr64` | 509 | Exported Function
`public: void __cdecl ProvPositiveRangedType::SetStatus(int const & __ptr64) __ptr64` | 907 | Exported Function
`public: void __cdecl ProvPositiveRangedType::``default constructor closure'(void) __ptr64` | 508 | Exported Function
`public: void __cdecl ProvPhysAddressType::``default constructor closure'(void) __ptr64` | 507 | Exported Function
`public: void __cdecl ProvPositiveRangeType::SetLowerBound(unsigned long const & __ptr64) __ptr64` | 899 | Exported Function
`public: void __cdecl ProvUInteger32::SetValue(unsigned long) __ptr64` | 921 | Exported Function
`public: void __cdecl ProvTimeTicks::SetValue(unsigned long) __ptr64` | 920 | Exported Function
`public: void __cdecl ProvPositiveRangeType::SetUpperBound(unsigned long const & __ptr64) __ptr64` | 911 | Exported Function
`public: void __cdecl WmiTreeNode::SetType(unsigned long) __ptr64` | 909 | Exported Function
`public: void __cdecl WmiTreeNode::GetRight(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 708 | Exported Function
`public: void __cdecl WmiTreeNode::GetParent(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 687 | Exported Function
`unsigned int __cdecl HashKey<unsigned short * __ptr64>(unsigned short * __ptr64)` | 2 | Exported Function
`unsigned short * __ptr64 __cdecl UnicodeStringDuplicate(unsigned short const * __ptr64)` | 950 | Exported Function
`unsigned short * __ptr64 __cdecl UnicodeStringAppend(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 949 | Exported Function
`unsigned short * __ptr64 __cdecl DbcsToUnicodeString(char const * __ptr64)` | 605 | Exported Function
`public: void __cdecl WmiTreeNode::GetLeft(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 677 | Exported Function
`public: void __cdecl WmiOperatorNotIsANode::``default constructor closure'(void) __ptr64` | 519 | Exported Function
`public: void __cdecl WmiOperatorNotEqualNode::``default constructor closure'(void) __ptr64` | 518 | Exported Function
`public: void __cdecl WmiOperatorLikeNode::``default constructor closure'(void) __ptr64` | 517 | Exported Function
`public: void __cdecl WmiOperatorNotLikeNode::``default constructor closure'(void) __ptr64` | 520 | Exported Function
`public: void __cdecl WmiTreeNode::GetData(void * __ptr64 * __ptr64) __ptr64` | 664 | Exported Function
`public: void __cdecl WmiTreeNode::``default constructor closure'(void) __ptr64` | 522 | Exported Function
`public: void __cdecl WmiOrNode::``default constructor closure'(void) __ptr64` | 521 | Exported Function
`public: void __cdecl ProvDisplayStringType::``default constructor closure'(void) __ptr64` | 500 | Exported Function
`public: void __cdecl ProvDebugLog::WriteW(unsigned short const * __ptr64,...) __ptr64` | 962 | Exported Function
`public: void __cdecl ProvDebugLog::WriteFileAndLineW(unsigned short const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 961 | Exported Function
`public: void __cdecl ProvEventObject::``default constructor closure'(void) __ptr64` | 501 | Exported Function
`public: void __cdecl ProvGauge::SetValue(unsigned long) __ptr64` | 914 | Exported Function
`public: void __cdecl ProvEventObject::Set(void) __ptr64` | 893 | Exported Function
`public: void __cdecl ProvEventObject::Clear(void) __ptr64` | 528 | Exported Function
`public: void __cdecl ProvDebugLog::WriteFileAndLineA(char const * __ptr64,unsigned long,char const * __ptr64,...) __ptr64` | 960 | Exported Function
`public: void __cdecl ProvCounter::SetValue(unsigned long) __ptr64` | 913 | Exported Function
`public: void __cdecl ProvCounter64Type::GetValue(unsigned long & __ptr64,unsigned long & __ptr64)const __ptr64` | 739 | Exported Function
`public: void __cdecl ProvCounter64::SetValue(unsigned long,unsigned long) __ptr64` | 912 | Exported Function
`public: void __cdecl ProvDebugLog::Write(unsigned short const * __ptr64,...) __ptr64` | 956 | Exported Function
`public: void __cdecl ProvDebugLog::WriteFileAndLine(unsigned short const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 959 | Exported Function
`public: void __cdecl ProvDebugLog::WriteFileAndLine(char const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 958 | Exported Function
`public: void __cdecl ProvDebugLog::WriteA(char const * __ptr64,...) __ptr64` | 957 | Exported Function
`public: void __cdecl ProvObjectIdentifier::SetValue(unsigned long const * __ptr64,unsigned long) __ptr64` | 917 | Exported Function
`public: void __cdecl ProvNegativeRangeType::SetUpperBound(long const & __ptr64) __ptr64` | 910 | Exported Function
`public: void __cdecl ProvNegativeRangeType::SetLowerBound(long const & __ptr64) __ptr64` | 898 | Exported Function
`public: void __cdecl ProvOctetString::SetValue(unsigned char const * __ptr64,unsigned long) __ptr64` | 918 | Exported Function
`public: void __cdecl ProvOpaqueType::``default constructor closure'(void) __ptr64` | 506 | Exported Function
`public: void __cdecl ProvOpaque::SetValue(unsigned char const * __ptr64,unsigned long) __ptr64` | 919 | Exported Function
`public: void __cdecl ProvOctetStringType::``default constructor closure'(void) __ptr64` | 505 | Exported Function
`public: void __cdecl ProvLexicon::SetToken(enum ProvLexicon::LexiconToken) __ptr64` | 908 | Exported Function
`public: void __cdecl ProvInstanceType::SetNull(int) __ptr64` | 900 | Exported Function
`public: void __cdecl ProvInstanceType::``default constructor closure'(void) __ptr64` | 503 | Exported Function
`public: void __cdecl ProvGaugeType::``default constructor closure'(void) __ptr64` | 502 | Exported Function
`public: void __cdecl ProvInstanceType::SetStatus(int) __ptr64` | 906 | Exported Function
`public: void __cdecl ProvIpAddress::SetValue(unsigned long) __ptr64` | 916 | Exported Function
`public: void __cdecl ProvIntegerType::``default constructor closure'(void) __ptr64` | 504 | Exported Function
`public: void __cdecl ProvInteger::SetValue(long) __ptr64` | 915 | Exported Function
`public: virtual int __cdecl ProvNullType::IsProvV2CType(void)const __ptr64` | 796 | Exported Function
`public: virtual __cdecl WmiUnsignedIntegerNode::~WmiUnsignedIntegerNode(void) __ptr64` | 300 | Exported Function
`public: virtual __cdecl WmiTreeNodeIterator::~WmiTreeNodeIterator(void) __ptr64` | 299 | Exported Function
`public: virtual __cdecl WmiTreeNode::~WmiTreeNode(void) __ptr64` | 298 | Exported Function
`public: virtual __cdecl WmiUnsignedIntegerRangeNode::~WmiUnsignedIntegerRangeNode(void) __ptr64` | 301 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvCounter64Type::Copy(void)const __ptr64` | 539 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvBitStringType::Copy(void)const __ptr64` | 537 | Exported Function
`public: virtual __cdecl WmiValueNode::~WmiValueNode(void) __ptr64` | 302 | Exported Function
`public: virtual __cdecl WmiStringRangeNode::~WmiStringRangeNode(void) __ptr64` | 297 | Exported Function
`public: virtual __cdecl WmiOrNode::~WmiOrNode(void) __ptr64` | 292 | Exported Function
`public: virtual __cdecl WmiOperatorNotLikeNode::~WmiOperatorNotLikeNode(void) __ptr64` | 291 | Exported Function
`public: virtual __cdecl WmiOperatorNotIsANode::~WmiOperatorNotIsANode(void) __ptr64` | 290 | Exported Function
`public: virtual __cdecl WmiRangeNode::~WmiRangeNode(void) __ptr64` | 293 | Exported Function
`public: virtual __cdecl WmiStringNode::~WmiStringNode(void) __ptr64` | 296 | Exported Function
`public: virtual __cdecl WmiSignedIntegerRangeNode::~WmiSignedIntegerRangeNode(void) __ptr64` | 295 | Exported Function
`public: virtual __cdecl WmiSignedIntegerNode::~WmiSignedIntegerNode(void) __ptr64` | 294 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvIpAddressType::Copy(void)const __ptr64` | 554 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvIntegerType::Copy(void)const __ptr64` | 552 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvGaugeType::Copy(void)const __ptr64` | 550 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvMacAddressType::Copy(void)const __ptr64` | 555 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvObjectIdentifierType::Copy(void)const __ptr64` | 562 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvNullType::Copy(void)const __ptr64` | 559 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvNetworkAddressType::Copy(void)const __ptr64` | 557 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthPhysAddressType::Copy(void)const __ptr64` | 548 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvDisplayStringType::Copy(void)const __ptr64` | 543 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvDateTimeType::Copy(void)const __ptr64` | 542 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvCounterType::Copy(void)const __ptr64` | 541 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvEnumeratedType::Copy(void)const __ptr64` | 544 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthOpaqueType::Copy(void)const __ptr64` | 547 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthOctetStringType::Copy(void)const __ptr64` | 546 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthDisplayStringType::Copy(void)const __ptr64` | 545 | Exported Function
`public: virtual __cdecl ProvRowStatusType::~ProvRowStatusType(void) __ptr64` | 270 | Exported Function
`public: virtual __cdecl ProvPositiveRangeType::~ProvPositiveRangeType(void) __ptr64` | 268 | Exported Function
`public: virtual __cdecl ProvPositiveRangedType::~ProvPositiveRangedType(void) __ptr64` | 269 | Exported Function
`public: virtual __cdecl ProvTimeTicks::~ProvTimeTicks(void) __ptr64` | 271 | Exported Function
`public: virtual __cdecl ProvUInteger32::~ProvUInteger32(void) __ptr64` | 274 | Exported Function
`public: virtual __cdecl ProvUDPAddressType::~ProvUDPAddressType(void) __ptr64` | 273 | Exported Function
`public: virtual __cdecl ProvTimeTicksType::~ProvTimeTicksType(void) __ptr64` | 272 | Exported Function
`public: virtual __cdecl ProvPositiveRangedType::operator void * __ptr64(void) __ptr64` | 395 | Exported Function
`public: virtual __cdecl ProvOctetStringType::~ProvOctetStringType(void) __ptr64` | 264 | Exported Function
`public: virtual __cdecl ProvOctetString::~ProvOctetString(void) __ptr64` | 263 | Exported Function
`public: virtual __cdecl ProvObjectIdentifierType::~ProvObjectIdentifierType(void) __ptr64` | 262 | Exported Function
`public: virtual __cdecl ProvOpaque::~ProvOpaque(void) __ptr64` | 265 | Exported Function
`public: virtual __cdecl ProvPhysAddressType::~ProvPhysAddressType(void) __ptr64` | 267 | Exported Function
`public: virtual __cdecl ProvOSIAddressType::~ProvOSIAddressType(void) __ptr64` | 260 | Exported Function
`public: virtual __cdecl ProvOpaqueType::~ProvOpaqueType(void) __ptr64` | 266 | Exported Function
`public: virtual __cdecl WmiOperatorIsANode::~WmiOperatorIsANode(void) __ptr64` | 285 | Exported Function
`public: virtual __cdecl WmiOperatorGreaterNode::~WmiOperatorGreaterNode(void) __ptr64` | 284 | Exported Function
`public: virtual __cdecl WmiOperatorEqualOrLessNode::~WmiOperatorEqualOrLessNode(void) __ptr64` | 283 | Exported Function
`public: virtual __cdecl WmiOperatorLessNode::~WmiOperatorLessNode(void) __ptr64` | 286 | Exported Function
`public: virtual __cdecl WmiOperatorNotEqualNode::~WmiOperatorNotEqualNode(void) __ptr64` | 289 | Exported Function
`public: virtual __cdecl WmiOperatorNode::~WmiOperatorNode(void) __ptr64` | 288 | Exported Function
`public: virtual __cdecl WmiOperatorLikeNode::~WmiOperatorLikeNode(void) __ptr64` | 287 | Exported Function
`public: virtual __cdecl WmiOperatorEqualOrGreaterNode::~WmiOperatorEqualOrGreaterNode(void) __ptr64` | 282 | Exported Function
`public: virtual __cdecl WmiAndNode::~WmiAndNode(void) __ptr64` | 277 | Exported Function
`public: virtual __cdecl QueryPreprocessor::~QueryPreprocessor(void) __ptr64` | 276 | Exported Function
`public: virtual __cdecl ProvValue::~ProvValue(void) __ptr64` | 275 | Exported Function
`public: virtual __cdecl WmiNotNode::~WmiNotNode(void) __ptr64` | 278 | Exported Function
`public: virtual __cdecl WmiOperatorEqualNode::~WmiOperatorEqualNode(void) __ptr64` | 281 | Exported Function
`public: virtual __cdecl WmiNullRangeNode::~WmiNullRangeNode(void) __ptr64` | 280 | Exported Function
`public: virtual __cdecl WmiNullNode::~WmiNullNode(void) __ptr64` | 279 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorLikeNode::Copy(void) __ptr64` | 584 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorLessNode::Copy(void) __ptr64` | 583 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorIsANode::Copy(void) __ptr64` | 582 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotEqualNode::Copy(void) __ptr64` | 585 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOrNode::Copy(void) __ptr64` | 588 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotLikeNode::Copy(void) __ptr64` | 587 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotIsANode::Copy(void) __ptr64` | 586 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorGreaterNode::Copy(void) __ptr64` | 581 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNullNode::Copy(void) __ptr64` | 576 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNotNode::Copy(void) __ptr64` | 575 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiAndNode::Copy(void) __ptr64` | 574 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNullRangeNode::Copy(void) __ptr64` | 577 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualOrLessNode::Copy(void) __ptr64` | 580 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::Copy(void) __ptr64` | 579 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualNode::Copy(void) __ptr64` | 578 | Exported Function
`public: virtual int __cdecl ProvEventObject::Wait(void) __ptr64` | 955 | Exported Function
`public: virtual int __cdecl ProvCounter64Type::IsProvV1Type(void)const __ptr64` | 793 | Exported Function
`public: virtual class WmiTreeNodeIterator * __ptr64 __cdecl WmiTreeNodeIterator::Copy(void) __ptr64` | 594 | Exported Function
`public: virtual int __cdecl ProvInstanceType::IsNull(void)const __ptr64` | 791 | Exported Function
`public: virtual int __cdecl ProvInstanceType::IsValid(void)const __ptr64` | 797 | Exported Function
`public: virtual int __cdecl ProvInstanceType::IsProvV2CType(void)const __ptr64` | 795 | Exported Function
`public: virtual int __cdecl ProvInstanceType::IsProvV1Type(void)const __ptr64` | 794 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiUnsignedIntegerRangeNode::Copy(void) __ptr64` | 596 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiStringNode::Copy(void) __ptr64` | 591 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiSignedIntegerRangeNode::Copy(void) __ptr64` | 590 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiSignedIntegerNode::Copy(void) __ptr64` | 589 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiStringRangeNode::Copy(void) __ptr64` | 592 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiUnsignedIntegerNode::Copy(void) __ptr64` | 595 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::CopyNode(void) __ptr64` | 597 | Exported Function
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::Copy(void) __ptr64` | 593 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvCounter::Copy(void)const __ptr64` | 540 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvCounter64::Copy(void)const __ptr64` | 538 | Exported Function
`public: virtual class ProvPositiveRangeType * __ptr64 __cdecl ProvPositiveRangeType::Copy(void) __ptr64` | 568 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvGauge::Copy(void)const __ptr64` | 549 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvNull::Copy(void)const __ptr64` | 558 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvIpAddress::Copy(void)const __ptr64` | 553 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvInteger::Copy(void)const __ptr64` | 551 | Exported Function
`public: virtual class ProvNegativeRangeType * __ptr64 __cdecl ProvNegativeRangeType::Copy(void) __ptr64` | 556 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOSIAddressType::Copy(void)const __ptr64` | 560 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOpaqueType::Copy(void)const __ptr64` | 566 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOctetStringType::Copy(void)const __ptr64` | 564 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvPhysAddressType::Copy(void)const __ptr64` | 567 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvUDPAddressType::Copy(void)const __ptr64` | 572 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvTimeTicksType::Copy(void)const __ptr64` | 571 | Exported Function
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvRowStatusType::Copy(void)const __ptr64` | 569 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorLessNode::GetRange(void) __ptr64` | 701 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorIsANode::GetRange(void) __ptr64` | 700 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorGreaterNode::GetRange(void) __ptr64` | 699 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorLikeNode::GetRange(void) __ptr64` | 702 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotLikeNode::GetRange(void) __ptr64` | 705 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotIsANode::GetRange(void) __ptr64` | 704 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotEqualNode::GetRange(void) __ptr64` | 703 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualOrLessNode::GetRange(void) __ptr64` | 698 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvOpaque::Copy(void)const __ptr64` | 565 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvOctetString::Copy(void)const __ptr64` | 563 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvObjectIdentifier::Copy(void)const __ptr64` | 561 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvTimeTicks::Copy(void)const __ptr64` | 570 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::GetRange(void) __ptr64` | 697 | Exported Function
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualNode::GetRange(void) __ptr64` | 696 | Exported Function
`public: virtual class ProvValue * __ptr64 __cdecl ProvUInteger32::Copy(void)const __ptr64` | 573 | Exported Function
`public: class ProvLexicon & __ptr64 __cdecl ProvLexicon::operator=(class ProvLexicon const & __ptr64) __ptr64` | 332 | Exported Function
`protected: int __cdecl ProvPhysAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 833 | Exported Function
`protected: int __cdecl ProvOSIAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 829 | Exported Function
`protected: int __cdecl ProvOpaqueType::Parse(unsigned short const * __ptr64) __ptr64` | 832 | Exported Function
`protected: int __cdecl ProvPositiveRangedType::Parse(unsigned short const * __ptr64) __ptr64` | 834 | Exported Function
`protected: int __cdecl ProvTimeTicksType::Parse(unsigned short const * __ptr64) __ptr64` | 835 | Exported Function
`protected: int __cdecl ProvPositiveRangedType::RecursiveDef(void) __ptr64` | 875 | Exported Function
`protected: int __cdecl ProvPositiveRangedType::RangeDef(void) __ptr64` | 871 | Exported Function
`protected: int __cdecl ProvOctetStringType::Parse(unsigned short const * __ptr64) __ptr64` | 831 | Exported Function
`protected: int __cdecl ProvIpAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 826 | Exported Function
`protected: int __cdecl ProvIntegerType::Parse(unsigned short const * __ptr64) __ptr64` | 825 | Exported Function
`protected: int __cdecl ProvGaugeType::Parse(unsigned short const * __ptr64) __ptr64` | 824 | Exported Function
`protected: int __cdecl ProvMacAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 827 | Exported Function
`protected: int __cdecl ProvObjectIdentifierType::Parse(unsigned short const * __ptr64) __ptr64` | 830 | Exported Function
`protected: int __cdecl ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 635 | Exported Function
`protected: int __cdecl ProvNetworkAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 828 | Exported Function
`protected: virtual int __cdecl ProvCounter::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 620 | Exported Function
`protected: virtual int __cdecl ProvCounter64Type::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 619 | Exported Function
`protected: virtual int __cdecl ProvCounter64::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 617 | Exported Function
`protected: virtual int __cdecl ProvCounterType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 622 | Exported Function
`protected: virtual int __cdecl ProvInteger::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 626 | Exported Function
`protected: virtual int __cdecl ProvGaugeType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 625 | Exported Function
`protected: virtual int __cdecl ProvGauge::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 623 | Exported Function
`protected: virtual int __cdecl ProvAnalyser::Analyse(class ProvLexicon * __ptr64,unsigned long & __ptr64,unsigned short,unsigned short const * __ptr64,unsigned long & __ptr64,int,int,int) __ptr64` | 525 | Exported Function
`protected: int __cdecl QueryPreprocessor::RecursiveEvaluate(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64 * __ptr64,int & __ptr64) __ptr64` | 877 | Exported Function
`protected: int __cdecl QueryPreprocessor::Evaluate(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION & __ptr64,class WmiTreeNode * __ptr64 * __ptr64) __ptr64` | 650 | Exported Function
`protected: int __cdecl ProvUDPAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 836 | Exported Function
`protected: virtual class ProvLexicon * __ptr64 __cdecl ProvAnalyser::CreateLexicon(void) __ptr64` | 601 | Exported Function
`protected: virtual enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::InvariantEvaluate(void * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 784 | Exported Function
`protected: virtual class WmiTreeNode * __ptr64 __cdecl QueryPreprocessor::AllocTypeNode(void * __ptr64,unsigned short * __ptr64,struct tagVARIANT & __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,class WmiTreeNode * __ptr64) __ptr64` | 524 | Exported Function
`protected: virtual class WmiRangeNode * __ptr64 __cdecl QueryPreprocessor::AllocInfiniteRangeNode(void * __ptr64,unsigned short * __ptr64) __ptr64` | 523 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::ConvertToRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 536 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RemoveNonOverlappingRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 886 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RemoveInvariants(void * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 885 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreateDisjunctionContainer(void * __ptr64,class WmiTreeNode * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,class Disjunctions * __ptr64 & __ptr64) __ptr64` | 599 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateAndExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 651 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreatePartitionSet(class Disjunctions * __ptr64,class PartitionSet * __ptr64 & __ptr64) __ptr64` | 602 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreateDisjunctions(void * __ptr64,class WmiTreeNode * __ptr64,class Disjunctions * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long & __ptr64) __ptr64` | 600 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveRemoveNonOverlappingRanges(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 882 | Exported Function
`protected: class ProvLexicon * __ptr64 __cdecl ProvPositiveRangedType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 813 | Exported Function
`protected: class ProvLexicon * __ptr64 __cdecl ProvPositiveRangedType::Get(void) __ptr64` | 659 | Exported Function
`protected: __cdecl ProvValue::ProvValue(void) __ptr64` | 166 | Exported Function
`protected: enum ProvObjectIdentifier::Comparison __cdecl ProvObjectIdentifier::Compare(class ProvObjectIdentifier const & __ptr64,class ProvObjectIdentifier const & __ptr64)const __ptr64` | 532 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveRemoveInvariants(void * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 881 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveDisjunctiveNormalForm(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 876 | Exported Function
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::DisjunctiveNormalForm(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 614 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::Sort(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 922 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RemoveOverlaps(unsigned long * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,class WmiRangeNode * __ptr64 * __ptr64) __ptr64` | 887 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveSortConditionals(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 884 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::SortConditionals(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 923 | Exported Function
`protected: int __cdecl ProvFixedLengthPhysAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 823 | Exported Function
`protected: int __cdecl ProvCounterType::Parse(unsigned short const * __ptr64) __ptr64` | 820 | Exported Function
`protected: int __cdecl ProvCounter64Type::Parse(unsigned short const * __ptr64) __ptr64` | 819 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveSort(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 883 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateOrExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 654 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateNotExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 653 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 652 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::InsertNode(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 783 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursivePartitionSet(class Disjunctions * __ptr64,class PartitionSet * __ptr64 & __ptr64,unsigned long,unsigned long * __ptr64,unsigned long) __ptr64` | 879 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveInsertNode(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 878 | Exported Function
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveConvertToRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 872 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorIsAExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 938 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorGreaterExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 937 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualOrLessExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 936 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorLessExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 939 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotIsAExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 942 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 941 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorLikeExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 940 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualOrGreaterExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 935 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNonIntersectingRange(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 930 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformIntersectingRange(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 929 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformAndTrueEvaluation(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 928 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotAndExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 931 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 934 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotNotExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 933 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 932 | Exported Function
`public: __cdecl Disjunctions::Disjunctions(unsigned long,unsigned long) __ptr64` | 7 | Exported Function
`public: __cdecl Conjunctions::~Conjunctions(void) __ptr64` | 229 | Exported Function
`public: __cdecl Conjunctions::Conjunctions(unsigned long) __ptr64` | 6 | Exported Function
`public: __cdecl Disjunctions::~Disjunctions(void) __ptr64` | 230 | Exported Function
`public: __cdecl ProvAnalyser::ProvAnalyser(class ProvAnalyser const & __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl PartitionSet::PartitionSet(void) __ptr64` | 9 | Exported Function
`public: __cdecl PartitionSet::PartitionSet(class PartitionSet const & __ptr64) __ptr64` | 8 | Exported Function
`public: __cdecl CBString::~CBString(void) __ptr64` | 228 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformOperatorToRange(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 945 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOrExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 944 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotLikeExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 943 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformOrFalseEvaluation(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 946 | Exported Function
`public: __cdecl CBString::CBString(void) __ptr64` | 5 | Exported Function
`public: __cdecl CBString::CBString(unsigned short const * __ptr64) __ptr64` | 4 | Exported Function
`public: __cdecl CBString::CBString(int) __ptr64` | 3 | Exported Function
`protected: virtual int __cdecl ProvOpaque::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 642 | Exported Function
`protected: virtual int __cdecl ProvOctetStringType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 641 | Exported Function
`protected: virtual int __cdecl ProvOctetString::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 639 | Exported Function
`protected: virtual int __cdecl ProvOpaqueType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 644 | Exported Function
`protected: virtual int __cdecl ProvUInteger32::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 648 | Exported Function
`protected: virtual int __cdecl ProvTimeTicksType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 647 | Exported Function
`protected: virtual int __cdecl ProvTimeTicks::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 645 | Exported Function
`protected: virtual int __cdecl ProvObjectIdentifierType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 638 | Exported Function
`protected: virtual int __cdecl ProvIpAddressType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 631 | Exported Function
`protected: virtual int __cdecl ProvIpAddress::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 629 | Exported Function
`protected: virtual int __cdecl ProvIntegerType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 628 | Exported Function
`protected: virtual int __cdecl ProvNetworkAddressType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 632 | Exported Function
`protected: virtual int __cdecl ProvObjectIdentifier::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 636 | Exported Function
`protected: virtual int __cdecl ProvNullType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 634 | Exported Function
`protected: virtual int __cdecl ProvNull::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 633 | Exported Function
`protected: void __cdecl QueryPreprocessor::PrintTree(class WmiTreeNode * __ptr64) __ptr64` | 862 | Exported Function
`protected: void __cdecl QueryPreprocessor::CountDisjunctions(class WmiTreeNode * __ptr64,unsigned long & __ptr64) __ptr64` | 598 | Exported Function
`protected: void __cdecl ProvPositiveRangedType::PushBack(void) __ptr64` | 867 | Exported Function
`protected: void __cdecl QueryPreprocessor::QuickSort(class WmiRangeNode * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long) __ptr64` | 870 | Exported Function
`protected: void __cdecl QueryPreprocessor::TransformAndOrExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 927 | Exported Function
`protected: void __cdecl QueryPreprocessor::SortRanges(unsigned long,unsigned long * __ptr64,class WmiRangeNode * __ptr64 * __ptr64) __ptr64` | 924 | Exported Function
`protected: void __cdecl QueryPreprocessor::RecursiveQuickSort(class WmiRangeNode * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long,unsigned long) __ptr64` | 880 | Exported Function
`protected: virtual void __cdecl ProvOctetString::UnReplicate(unsigned char * __ptr64) __ptr64` | 948 | Exported Function
`protected: virtual unsigned long * __ptr64 __cdecl ProvObjectIdentifier::Replicate(unsigned long const * __ptr64,unsigned long,unsigned long const * __ptr64,unsigned long)const __ptr64` | 888 | Exported Function
`protected: virtual unsigned long * __ptr64 __cdecl ProvObjectIdentifier::Replicate(unsigned long const * __ptr64,unsigned long)const __ptr64` | 889 | Exported Function
`protected: virtual unsigned char * __ptr64 __cdecl ProvOctetString::Replicate(unsigned char const * __ptr64,unsigned long) __ptr64` | 890 | Exported Function
`protected: virtual void __cdecl ProvAnalyser::Initialise(void) __ptr64` | 777 | Exported Function
`protected: virtual void __cdecl ProvOctetString::Initialize(unsigned char const * __ptr64,unsigned long) __ptr64` | 782 | Exported Function
`protected: virtual void __cdecl ProvObjectIdentifier::UnReplicate(unsigned long * __ptr64) __ptr64` | 947 | Exported Function
`protected: virtual void __cdecl ProvObjectIdentifier::Initialize(unsigned long const * __ptr64,unsigned long) __ptr64` | 781 | Exported Function
`protected: __cdecl ProvInstanceType::ProvInstanceType(int,int) __ptr64` | 74 | Exported Function
`const ProvMacAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 444 | Exported Function
`const ProvMacAddressType::``vftable'{for ``ProvInstanceType'}` | 443 | Exported Function
`const ProvMacAddressType::``vftable'` | 442 | Exported Function
`const ProvNegativeRangeType::``vftable'` | 445 | Exported Function
`const ProvNullType::``vftable'` | 448 | Exported Function
`const ProvNull::``vftable'` | 447 | Exported Function
`const ProvNetworkAddressType::``vftable'` | 446 | Exported Function
`const ProvIpAddressType::``vftable'` | 441 | Exported Function
`const ProvInstanceType::``vftable'` | 436 | Exported Function
`const ProvGaugeType::``vftable'{for ``ProvPositiveRangedType'}` | 435 | Exported Function
`const ProvGaugeType::``vftable'{for ``ProvInstanceType'}` | 434 | Exported Function
`const ProvInteger::``vftable'` | 437 | Exported Function
`const ProvIpAddress::``vftable'` | 440 | Exported Function
`const ProvIntegerType::``vftable'{for ``ProvNegativeRangedType'}` | 439 | Exported Function
`const ProvIntegerType::``vftable'{for ``ProvInstanceType'}` | 438 | Exported Function
`const ProvPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 459 | Exported Function
`const ProvOSIAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 450 | Exported Function
`const ProvOSIAddressType::``vftable'{for ``ProvInstanceType'}` | 449 | Exported Function
`const ProvPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 460 | Exported Function
`const ProvRowStatusType::``vftable'{for ``ProvInstanceType'}` | 463 | Exported Function
`const ProvPositiveRangeType::``vftable'` | 461 | Exported Function
`const ProvPositiveRangedType::``vftable'` | 462 | Exported Function
`const ProvOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 458 | Exported Function
`const ProvOctetString::``vftable'` | 453 | Exported Function
`const ProvObjectIdentifierType::``vftable'` | 452 | Exported Function
`const ProvObjectIdentifier::``vftable'` | 451 | Exported Function
`const ProvOctetStringType::``vftable'{for ``ProvInstanceType'}` | 454 | Exported Function
`const ProvOpaqueType::``vftable'{for ``ProvInstanceType'}` | 457 | Exported Function
`const ProvOpaque::``vftable'` | 456 | Exported Function
`const ProvOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 455 | Exported Function
`const ProvDateTimeType::``vftable'{for ``ProvPositiveRangedType'}` | 414 | Exported Function
`const ProvDateTimeType::``vftable'{for ``ProvInstanceType'}` | 413 | Exported Function
`const ProvCounterType::``vftable'` | 412 | Exported Function
`const ProvDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 415 | Exported Function
`const ProvEnumeratedType::``vftable'{for ``ProvNegativeRangedType'}` | 418 | Exported Function
`const ProvEnumeratedType::``vftable'{for ``ProvInstanceType'}` | 417 | Exported Function
`const ProvDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 416 | Exported Function
`const ProvCounter::``vftable'` | 411 | Exported Function
`const ProvAnalyser::``vftable'` | 406 | Exported Function
`const PartitionSet::``vftable'` | 405 | Exported Function
`char * __ptr64 __cdecl UnicodeToDbcsString(unsigned short const * __ptr64)` | 951 | Exported Function
`const ProvBitStringType::``vftable'{for ``ProvInstanceType'}` | 407 | Exported Function
`const ProvCounter64Type::``vftable'` | 410 | Exported Function
`const ProvCounter64::``vftable'` | 409 | Exported Function
`const ProvBitStringType::``vftable'{for ``ProvPositiveRangedType'}` | 408 | Exported Function
`const ProvFixedLengthPhysAddressType::``vftable'` | 429 | Exported Function
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 428 | Exported Function
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvInstanceType'}` | 427 | Exported Function
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 430 | Exported Function
`const ProvGauge::``vftable'` | 433 | Exported Function
`const ProvFixedType::``vftable'` | 432 | Exported Function
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 431 | Exported Function
`const ProvFixedLengthOpaqueType::``vftable'` | 426 | Exported Function
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 421 | Exported Function
`const ProvFixedLengthDisplayStringType::``vftable'` | 420 | Exported Function
`const ProvEventObject::``vftable'` | 419 | Exported Function
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 422 | Exported Function
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 425 | Exported Function
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvInstanceType'}` | 424 | Exported Function
`const ProvFixedLengthOctetStringType::``vftable'` | 423 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvDateTimeType::Get(void) __ptr64` | 657 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvBitStringType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 810 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvBitStringType::Get(void) __ptr64` | 656 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvDateTimeType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 811 | Exported Function
`private: class ProvValue & __ptr64 __cdecl ProvValue::operator=(class ProvValue const & __ptr64) __ptr64` | 353 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvEnumeratedType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 812 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvEnumeratedType::Get(void) __ptr64` | 658 | Exported Function
`private: class ProvLexicon * __ptr64 __cdecl ProvAnalyser::GetToken(int,int,int) __ptr64` | 733 | Exported Function
`const WmiUnsignedIntegerNode::``vftable'` | 496 | Exported Function
`const WmiTreeNodeIterator::``vftable'` | 495 | Exported Function
`const WmiTreeNode::``vftable'` | 494 | Exported Function
`const WmiUnsignedIntegerRangeNode::``vftable'` | 497 | Exported Function
`private: __cdecl ProvValue::ProvValue(class ProvValue const & __ptr64) __ptr64` | 165 | Exported Function
`int __cdecl CompareElements<unsigned short * __ptr64,unsigned short * __ptr64>(unsigned short * __ptr64 const * __ptr64,unsigned short * __ptr64 const * __ptr64)` | 1 | Exported Function
`const WmiValueNode::``vftable'` | 498 | Exported Function
`private: void __cdecl ProvDateTimeType::PushBack(void) __ptr64` | 865 | Exported Function
`private: void __cdecl ProvDateTimeType::Encode(unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64) __ptr64` | 615 | Exported Function
`private: void __cdecl ProvBitStringType::PushBack(void) __ptr64` | 864 | Exported Function
`private: void __cdecl ProvEnumeratedType::PushBack(void) __ptr64` | 866 | Exported Function
`protected: __cdecl ProvInstanceType::ProvInstanceType(class ProvInstanceType const & __ptr64) __ptr64` | 73 | Exported Function
`private: void __cdecl ProvOctetString::OverWrite(unsigned char const * __ptr64) __ptr64` | 817 | Exported Function
`private: void __cdecl ProvObjectIdentifier::OverWrite(unsigned long const * __ptr64) __ptr64` | 816 | Exported Function
`private: int __cdecl ProvEnumeratedType::RecursiveDef(void) __ptr64` | 874 | Exported Function
`private: int __cdecl ProvBitStringType::RecursiveDef(void) __ptr64` | 873 | Exported Function
`private: int __cdecl ProvBitStringType::Parse(unsigned short const * __ptr64) __ptr64` | 818 | Exported Function
`private: int __cdecl ProvBitStringType::BitStringDef(void) __ptr64` | 526 | Exported Function
`private: int __cdecl ProvDateTimeType::DateTimeDef(void) __ptr64` | 604 | Exported Function
`private: int __cdecl ProvEnumeratedType::Parse(unsigned short const * __ptr64) __ptr64` | 822 | Exported Function
`private: int __cdecl ProvEnumeratedType::EnumerationDef(void) __ptr64` | 616 | Exported Function
`private: int __cdecl ProvDateTimeType::Parse(unsigned short const * __ptr64) __ptr64` | 821 | Exported Function
`const WmiNotNode::``vftable'` | 474 | Exported Function
`const WmiAndNode::``vftable'` | 473 | Exported Function
`const QueryPreprocessor::``vftable'` | 472 | Exported Function
`const WmiNullNode::``vftable'` | 475 | Exported Function
`const WmiOperatorEqualOrGreaterNode::``vftable'` | 478 | Exported Function
`const WmiOperatorEqualNode::``vftable'` | 477 | Exported Function
`const WmiNullRangeNode::``vftable'` | 476 | Exported Function
`const ProvValue::``vftable'` | 471 | Exported Function
`const ProvTimeTicksType::``vftable'` | 466 | Exported Function
`const ProvTimeTicks::``vftable'` | 465 | Exported Function
`const ProvRowStatusType::``vftable'{for ``ProvNegativeRangedType'}` | 464 | Exported Function
`const ProvUDPAddressType::``vftable'` | 467 | Exported Function
`const ProvUInteger32::``vftable'` | 470 | Exported Function
`const ProvUDPAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 469 | Exported Function
`const ProvUDPAddressType::``vftable'{for ``ProvInstanceType'}` | 468 | Exported Function
`const WmiRangeNode::``vftable'` | 489 | Exported Function
`const WmiOrNode::``vftable'` | 488 | Exported Function
`const WmiOperatorNotLikeNode::``vftable'` | 487 | Exported Function
`const WmiSignedIntegerNode::``vftable'` | 490 | Exported Function
`const WmiStringRangeNode::``vftable'` | 493 | Exported Function
`const WmiStringNode::``vftable'` | 492 | Exported Function
`const WmiSignedIntegerRangeNode::``vftable'` | 491 | Exported Function
`const WmiOperatorNotIsANode::``vftable'` | 486 | Exported Function
`const WmiOperatorIsANode::``vftable'` | 481 | Exported Function
`const WmiOperatorGreaterNode::``vftable'` | 480 | Exported Function
`const WmiOperatorEqualOrLessNode::``vftable'` | 479 | Exported Function
`const WmiOperatorLessNode::``vftable'` | 482 | Exported Function
`const WmiOperatorNotEqualNode::``vftable'` | 485 | Exported Function
`const WmiOperatorNode::``vftable'` | 484 | Exported Function
`const WmiOperatorLikeNode::``vftable'` | 483 | Exported Function
`public: __cdecl WmiNullNode::WmiNullNode(unsigned short * __ptr64,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 175 | Exported Function
`public: __cdecl WmiNullNode::WmiNullNode(class WmiNullNode const & __ptr64) __ptr64` | 174 | Exported Function
`public: __cdecl WmiNullNode::WmiNullNode(class WmiNullNode && __ptr64) __ptr64` | 173 | Exported Function
`public: __cdecl WmiNullRangeNode::WmiNullRangeNode(class WmiNullRangeNode const & __ptr64) __ptr64` | 176 | Exported Function
`public: __cdecl WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 179 | Exported Function
`public: __cdecl WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiOperatorEqualNode const & __ptr64) __ptr64` | 178 | Exported Function
`public: __cdecl WmiNullRangeNode::WmiNullRangeNode(unsigned short * __ptr64,unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 177 | Exported Function
`public: __cdecl WmiNotNode::WmiNotNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 172 | Exported Function
`public: __cdecl QueryPreprocessor::QueryPreprocessor(class QueryPreprocessor const & __ptr64) __ptr64` | 167 | Exported Function
`public: __cdecl ProvUInteger32::ProvUInteger32(long) __ptr64` | 164 | Exported Function
`public: __cdecl ProvUInteger32::ProvUInteger32(class ProvUInteger32 const & __ptr64) __ptr64` | 163 | Exported Function
`public: __cdecl QueryPreprocessor::QueryPreprocessor(void) __ptr64` | 168 | Exported Function
`public: __cdecl WmiNotNode::WmiNotNode(class WmiNotNode const & __ptr64) __ptr64` | 171 | Exported Function
`public: __cdecl WmiAndNode::WmiAndNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 170 | Exported Function
`public: __cdecl WmiAndNode::WmiAndNode(class WmiAndNode const & __ptr64) __ptr64` | 169 | Exported Function
`public: __cdecl WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiOperatorLikeNode const & __ptr64) __ptr64` | 190 | Exported Function
`public: __cdecl WmiOperatorLessNode::WmiOperatorLessNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 189 | Exported Function
`public: __cdecl WmiOperatorLessNode::WmiOperatorLessNode(class WmiOperatorLessNode const & __ptr64) __ptr64` | 188 | Exported Function
`public: __cdecl WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 191 | Exported Function
`public: __cdecl WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiOperatorNotEqualNode const & __ptr64) __ptr64` | 194 | Exported Function
`public: __cdecl WmiOperatorNode::WmiOperatorNode(unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 193 | Exported Function
`public: __cdecl WmiOperatorNode::WmiOperatorNode(class WmiOperatorNode const & __ptr64) __ptr64` | 192 | Exported Function
`public: __cdecl WmiOperatorIsANode::WmiOperatorIsANode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 187 | Exported Function
`public: __cdecl WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiOperatorEqualOrLessNode const & __ptr64) __ptr64` | 182 | Exported Function
`public: __cdecl WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 181 | Exported Function
`public: __cdecl WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiOperatorEqualOrGreaterNode const & __ptr64) __ptr64` | 180 | Exported Function
`public: __cdecl WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 183 | Exported Function
`public: __cdecl WmiOperatorIsANode::WmiOperatorIsANode(class WmiOperatorIsANode const & __ptr64) __ptr64` | 186 | Exported Function
`public: __cdecl WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 185 | Exported Function
`public: __cdecl WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiOperatorGreaterNode const & __ptr64) __ptr64` | 184 | Exported Function
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(unsigned long,long) __ptr64` | 141 | Exported Function
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(class ProvPositiveRangeType const & __ptr64) __ptr64` | 140 | Exported Function
`public: __cdecl ProvPositiveRangedType::ProvPositiveRangedType(unsigned short const * __ptr64) __ptr64` | 144 | Exported Function
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(void) __ptr64` | 142 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(enum ProvRowStatusType::ProvRowStatusEnum const & __ptr64) __ptr64` | 148 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(class ProvRowStatusType const & __ptr64) __ptr64` | 146 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(class ProvInteger const & __ptr64) __ptr64` | 147 | Exported Function
`public: __cdecl ProvPositiveRangedType::ProvPositiveRangedType(class ProvPositiveRangedType const & __ptr64) __ptr64` | 143 | Exported Function
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 136 | Exported Function
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(void) __ptr64` | 112 | Exported Function
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(unsigned short const * __ptr64) __ptr64` | 111 | Exported Function
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(class ProvPhysAddressType const & __ptr64) __ptr64` | 135 | Exported Function
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 138 | Exported Function
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned short const * __ptr64) __ptr64` | 139 | Exported Function
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 137 | Exported Function
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(class ProvOctetString const & __ptr64) __ptr64` | 159 | Exported Function
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(void) __ptr64` | 157 | Exported Function
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(unsigned short const * __ptr64) __ptr64` | 156 | Exported Function
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(class ProvUDPAddressType const & __ptr64) __ptr64` | 158 | Exported Function
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(void) __ptr64` | 162 | Exported Function
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(unsigned short const * __ptr64) __ptr64` | 161 | Exported Function
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(unsigned char const * __ptr64) __ptr64` | 160 | Exported Function
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(unsigned long) __ptr64` | 155 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(void) __ptr64` | 150 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(unsigned short const * __ptr64) __ptr64` | 149 | Exported Function
`public: __cdecl ProvRowStatusType::ProvRowStatusType(long const & __ptr64) __ptr64` | 145 | Exported Function
`public: __cdecl ProvTimeTicks::ProvTimeTicks(class ProvTimeTicks const & __ptr64) __ptr64` | 151 | Exported Function
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicksType const & __ptr64) __ptr64` | 153 | Exported Function
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicks const & __ptr64) __ptr64` | 154 | Exported Function
`public: __cdecl ProvTimeTicks::ProvTimeTicks(unsigned long) __ptr64` | 152 | Exported Function
`public: class PartitionSet * __ptr64 __cdecl PartitionSet::GetPartition(unsigned long) __ptr64` | 688 | Exported Function
`public: class PartitionSet & __ptr64 __cdecl PartitionSet::operator=(class PartitionSet const & __ptr64) __ptr64` | 307 | Exported Function
`public: class Disjunctions & __ptr64 __cdecl Disjunctions::operator=(class Disjunctions const & __ptr64) __ptr64` | 306 | Exported Function
`public: class ProvAnalyser & __ptr64 __cdecl ProvAnalyser::operator=(class ProvAnalyser const & __ptr64) __ptr64` | 308 | Exported Function
`public: class ProvCounterType & __ptr64 __cdecl ProvCounterType::operator=(class ProvCounterType const & __ptr64) __ptr64` | 313 | Exported Function
`public: class ProvCounter64Type & __ptr64 __cdecl ProvCounter64Type::operator=(class ProvCounter64Type const & __ptr64) __ptr64` | 311 | Exported Function
`public: class ProvBitStringType & __ptr64 __cdecl ProvBitStringType::operator=(class ProvBitStringType const & __ptr64) __ptr64` | 309 | Exported Function
`public: class Conjunctions * __ptr64 __cdecl Disjunctions::GetDisjunction(unsigned long) __ptr64` | 665 | Exported Function
`public: __cdecl WmiValueNode::WmiValueNode(unsigned long,unsigned short * __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 227 | Exported Function
`public: __cdecl WmiValueNode::WmiValueNode(class WmiValueNode const & __ptr64) __ptr64` | 226 | Exported Function
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,unsigned long,unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 225 | Exported Function
`public: char * __ptr64 __cdecl ProvObjectIdentifier::GetAllocatedString(void)const __ptr64` | 660 | Exported Function
`public: class Conjunctions & __ptr64 __cdecl Conjunctions::operator=(class Conjunctions const & __ptr64) __ptr64` | 305 | Exported Function
`public: class CBString const & __ptr64 __cdecl CBString::operator=(unsigned short const * __ptr64) __ptr64` | 304 | Exported Function
`public: class CBString & __ptr64 __cdecl CBString::operator=(class CBString const & __ptr64) __ptr64` | 303 | Exported Function
`public: class ProvFixedType & __ptr64 __cdecl ProvFixedType::operator=(class ProvFixedType const & __ptr64) __ptr64` | 324 | Exported Function
`public: class ProvFixedLengthPhysAddressType & __ptr64 __cdecl ProvFixedLengthPhysAddressType::operator=(class ProvFixedLengthPhysAddressType const & __ptr64) __ptr64` | 323 | Exported Function
`public: class ProvFixedLengthOpaqueType & __ptr64 __cdecl ProvFixedLengthOpaqueType::operator=(class ProvFixedLengthOpaqueType const & __ptr64) __ptr64` | 322 | Exported Function
`public: class ProvGaugeType & __ptr64 __cdecl ProvGaugeType::operator=(class ProvGaugeType const & __ptr64) __ptr64` | 326 | Exported Function
`public: class ProvIpAddressType & __ptr64 __cdecl ProvIpAddressType::operator=(class ProvIpAddressType const & __ptr64) __ptr64` | 331 | Exported Function
`public: class ProvIntegerType & __ptr64 __cdecl ProvIntegerType::operator=(class ProvIntegerType const & __ptr64) __ptr64` | 329 | Exported Function
`public: class ProvInstanceType & __ptr64 __cdecl ProvInstanceType::operator=(class ProvInstanceType const & __ptr64) __ptr64` | 327 | Exported Function
`public: class ProvFixedLengthOctetStringType & __ptr64 __cdecl ProvFixedLengthOctetStringType::operator=(class ProvFixedLengthOctetStringType const & __ptr64) __ptr64` | 321 | Exported Function
`public: class ProvDebugLog & __ptr64 __cdecl ProvDebugLog::operator=(class ProvDebugLog const & __ptr64) __ptr64` | 316 | Exported Function
`public: class ProvDebugLog & __ptr64 __cdecl ProvDebugLog::operator=(class ProvDebugLog && __ptr64) __ptr64` | 315 | Exported Function
`public: class ProvDateTimeType & __ptr64 __cdecl ProvDateTimeType::operator=(class ProvDateTimeType const & __ptr64) __ptr64` | 314 | Exported Function
`public: class ProvDisplayStringType & __ptr64 __cdecl ProvDisplayStringType::operator=(class ProvDisplayStringType const & __ptr64) __ptr64` | 317 | Exported Function
`public: class ProvFixedLengthDisplayStringType & __ptr64 __cdecl ProvFixedLengthDisplayStringType::operator=(class ProvFixedLengthDisplayStringType const & __ptr64) __ptr64` | 320 | Exported Function
`public: class ProvEventObject & __ptr64 __cdecl ProvEventObject::operator=(class ProvEventObject const & __ptr64) __ptr64` | 319 | Exported Function
`public: class ProvEnumeratedType & __ptr64 __cdecl ProvEnumeratedType::operator=(class ProvEnumeratedType const & __ptr64) __ptr64` | 318 | Exported Function
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode const & __ptr64) __ptr64` | 205 | Exported Function
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode && __ptr64) __ptr64` | 204 | Exported Function
`public: __cdecl WmiRangeNode::WmiRangeNode(unsigned long,unsigned short * __ptr64,unsigned long,int,int,int,int,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 203 | Exported Function
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(unsigned short * __ptr64,long,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 206 | Exported Function
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,long,long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 209 | Exported Function
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode const & __ptr64) __ptr64` | 208 | Exported Function
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode && __ptr64) __ptr64` | 207 | Exported Function
`public: __cdecl WmiRangeNode::WmiRangeNode(class WmiRangeNode const & __ptr64) __ptr64` | 202 | Exported Function
`public: __cdecl WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 197 | Exported Function
`public: __cdecl WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiOperatorNotIsANode const & __ptr64) __ptr64` | 196 | Exported Function
`public: __cdecl WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 195 | Exported Function
`public: __cdecl WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiOperatorNotLikeNode const & __ptr64) __ptr64` | 198 | Exported Function
`public: __cdecl WmiOrNode::WmiOrNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 201 | Exported Function
`public: __cdecl WmiOrNode::WmiOrNode(class WmiOrNode const & __ptr64) __ptr64` | 200 | Exported Function
`public: __cdecl WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 199 | Exported Function
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode && __ptr64) __ptr64` | 220 | Exported Function
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator const & __ptr64) __ptr64` | 217 | Exported Function
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator * __ptr64) __ptr64` | 218 | Exported Function
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode const & __ptr64) __ptr64` | 221 | Exported Function
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode const & __ptr64) __ptr64` | 224 | Exported Function
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode && __ptr64) __ptr64` | 223 | Exported Function
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(unsigned short * __ptr64,unsigned long,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 222 | Exported Function
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNode * __ptr64) __ptr64` | 219 | Exported Function
`public: __cdecl WmiStringRangeNode::WmiStringRangeNode(class WmiStringRangeNode const & __ptr64) __ptr64` | 212 | Exported Function
`public: __cdecl WmiStringNode::WmiStringNode(unsigned short * __ptr64,unsigned short * __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 211 | Exported Function
`public: __cdecl WmiStringNode::WmiStringNode(class WmiStringNode const & __ptr64) __ptr64` | 210 | Exported Function
`public: __cdecl WmiStringRangeNode::WmiStringRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,unsigned short * __ptr64,unsigned short * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 213 | Exported Function
`public: __cdecl WmiTreeNode::WmiTreeNode(unsigned long,void * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 215 | Exported Function
`public: __cdecl WmiTreeNode::WmiTreeNode(class WmiTreeNode const & __ptr64) __ptr64` | 214 | Exported Function
`public: __cdecl WmiTreeNode::WmiTreeNode(class WmiTreeNode * __ptr64) __ptr64` | 216 | Exported Function
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(unsigned char const * __ptr64,unsigned long) __ptr64` | 110 | Exported Function
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64) __ptr64` | 50 | Exported Function
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(class ProvFixedLengthOctetStringType const & __ptr64) __ptr64` | 54 | Exported Function
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 48 | Exported Function
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 51 | Exported Function
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(class ProvFixedLengthOpaqueType const & __ptr64) __ptr64` | 59 | Exported Function
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 53 | Exported Function
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,unsigned char const * __ptr64) __ptr64` | 52 | Exported Function
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 47 | Exported Function
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 40 | Exported Function
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,long const & __ptr64) __ptr64` | 42 | Exported Function
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,class ProvInteger const & __ptr64) __ptr64` | 43 | Exported Function
`public: __cdecl ProvEventObject::ProvEventObject(class ProvEventObject const & __ptr64) __ptr64` | 44 | Exported Function
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64) __ptr64` | 46 | Exported Function
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(class ProvFixedLengthDisplayStringType const & __ptr64) __ptr64` | 49 | Exported Function
`public: __cdecl ProvEventObject::ProvEventObject(unsigned short const * __ptr64) __ptr64` | 45 | Exported Function
`public: __cdecl ProvGauge::ProvGauge(class ProvGauge const & __ptr64) __ptr64` | 66 | Exported Function
`public: __cdecl ProvFixedType::ProvFixedType(unsigned long) __ptr64` | 65 | Exported Function
`public: __cdecl ProvFixedType::ProvFixedType(class ProvFixedType const & __ptr64) __ptr64` | 64 | Exported Function
`public: __cdecl ProvGauge::ProvGauge(long) __ptr64` | 67 | Exported Function
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned long,unsigned short const * __ptr64) __ptr64` | 70 | Exported Function
`public: __cdecl ProvGaugeType::ProvGaugeType(class ProvGaugeType const & __ptr64) __ptr64` | 68 | Exported Function
`public: __cdecl ProvGaugeType::ProvGaugeType(class ProvGauge const & __ptr64,unsigned short const * __ptr64) __ptr64` | 69 | Exported Function
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 62 | Exported Function
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,unsigned char const * __ptr64,unsigned long) __ptr64` | 57 | Exported Function
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,class ProvOpaque const & __ptr64) __ptr64` | 56 | Exported Function
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64) __ptr64` | 55 | Exported Function
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 58 | Exported Function
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 61 | Exported Function
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64) __ptr64` | 60 | Exported Function
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(class ProvFixedLengthPhysAddressType const & __ptr64) __ptr64` | 63 | Exported Function
`public: __cdecl ProvCounter64Type::ProvCounter64Type(unsigned short const * __ptr64) __ptr64` | 21 | Exported Function
`public: __cdecl ProvCounter64Type::ProvCounter64Type(unsigned long,unsigned long) __ptr64` | 20 | Exported Function
`public: __cdecl ProvCounter64Type::ProvCounter64Type(class ProvCounter64Type const & __ptr64) __ptr64` | 18 | Exported Function
`public: __cdecl ProvCounter64Type::ProvCounter64Type(void) __ptr64` | 22 | Exported Function
`public: __cdecl ProvCounterType::ProvCounterType(class ProvCounter const & __ptr64) __ptr64` | 26 | Exported Function
`public: __cdecl ProvCounter::ProvCounter(unsigned long) __ptr64` | 24 | Exported Function
`public: __cdecl ProvCounter::ProvCounter(class ProvCounter const & __ptr64) __ptr64` | 23 | Exported Function
`public: __cdecl ProvCounter64Type::ProvCounter64Type(class ProvCounter64 const & __ptr64) __ptr64` | 19 | Exported Function
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64) __ptr64` | 13 | Exported Function
`public: __cdecl ProvBitStringType::ProvBitStringType(class ProvBitStringType const & __ptr64) __ptr64` | 12 | Exported Function
`public: __cdecl ProvAnalyser::ProvAnalyser(unsigned short const * __ptr64) __ptr64` | 11 | Exported Function
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 14 | Exported Function
`public: __cdecl ProvCounter64::ProvCounter64(unsigned long,unsigned long) __ptr64` | 17 | Exported Function
`public: __cdecl ProvCounter64::ProvCounter64(class ProvCounter64 const & __ptr64) __ptr64` | 16 | Exported Function
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64,unsigned long const & __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 36 | Exported Function
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(class ProvDisplayStringType const & __ptr64) __ptr64` | 35 | Exported Function
`public: __cdecl ProvDebugLog::ProvDebugLog(char) __ptr64` | 34 | Exported Function
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(unsigned short const * __ptr64) __ptr64` | 38 | Exported Function
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64) __ptr64` | 41 | Exported Function
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(class ProvEnumeratedType const & __ptr64) __ptr64` | 39 | Exported Function
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 37 | Exported Function
`public: __cdecl ProvDateTimeType::ProvDateTimeType(void) __ptr64` | 33 | Exported Function
`public: __cdecl ProvCounterType::ProvCounterType(unsigned short const * __ptr64) __ptr64` | 28 | Exported Function
`public: __cdecl ProvCounterType::ProvCounterType(unsigned long) __ptr64` | 27 | Exported Function
`public: __cdecl ProvCounterType::ProvCounterType(class ProvCounterType const & __ptr64) __ptr64` | 25 | Exported Function
`public: __cdecl ProvCounterType::ProvCounterType(void) __ptr64` | 29 | Exported Function
`public: __cdecl ProvDateTimeType::ProvDateTimeType(unsigned short const * __ptr64) __ptr64` | 32 | Exported Function
`public: __cdecl ProvDateTimeType::ProvDateTimeType(class ProvOctetString const & __ptr64) __ptr64` | 31 | Exported Function
`public: __cdecl ProvDateTimeType::ProvDateTimeType(class ProvDateTimeType const & __ptr64) __ptr64` | 30 | Exported Function
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifierType const & __ptr64) __ptr64` | 116 | Exported Function
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifier const & __ptr64) __ptr64` | 117 | Exported Function
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(unsigned long const * __ptr64,unsigned long) __ptr64` | 115 | Exported Function
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned long const * __ptr64,unsigned long) __ptr64` | 119 | Exported Function
`public: __cdecl ProvOctetString::ProvOctetString(class ProvOctetString const & __ptr64) __ptr64` | 121 | Exported Function
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(void) __ptr64` | 120 | Exported Function
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned short const * __ptr64) __ptr64` | 118 | Exported Function
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(class ProvObjectIdentifier const & __ptr64) __ptr64` | 113 | Exported Function
`public: __cdecl ProvNull::ProvNull(void) __ptr64` | 104 | Exported Function
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(void) __ptr64` | 103 | Exported Function
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(unsigned short const * __ptr64) __ptr64` | 102 | Exported Function
`public: __cdecl ProvNullType::ProvNullType(class ProvNull const & __ptr64) __ptr64` | 106 | Exported Function
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(char const * __ptr64) __ptr64` | 114 | Exported Function
`public: __cdecl ProvNullType::ProvNullType(void) __ptr64` | 107 | Exported Function
`public: __cdecl ProvNullType::ProvNullType(class ProvNullType const & __ptr64) __ptr64` | 105 | Exported Function
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 132 | Exported Function
`public: __cdecl ProvOpaqueType::ProvOpaqueType(class ProvOpaqueType const & __ptr64) __ptr64` | 130 | Exported Function
`public: __cdecl ProvOpaqueType::ProvOpaqueType(class ProvOpaque const & __ptr64,unsigned short const * __ptr64) __ptr64` | 131 | Exported Function
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned short const * __ptr64) __ptr64` | 134 | Exported Function
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(class ProvOSIAddressType const & __ptr64) __ptr64` | 108 | Exported Function
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(class ProvOctetString const & __ptr64) __ptr64` | 109 | Exported Function
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 133 | Exported Function
`public: __cdecl ProvOpaque::ProvOpaque(unsigned char const * __ptr64,unsigned long) __ptr64` | 129 | Exported Function
`public: __cdecl ProvOctetStringType::ProvOctetStringType(class ProvOctetStringType const & __ptr64) __ptr64` | 123 | Exported Function
`public: __cdecl ProvOctetStringType::ProvOctetStringType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 124 | Exported Function
`public: __cdecl ProvOctetString::ProvOctetString(unsigned char const * __ptr64,unsigned long) __ptr64` | 122 | Exported Function
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 125 | Exported Function
`public: __cdecl ProvOpaque::ProvOpaque(class ProvOpaque const & __ptr64) __ptr64` | 128 | Exported Function
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 126 | Exported Function
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned short const * __ptr64) __ptr64` | 127 | Exported Function
`public: __cdecl ProvIpAddress::ProvIpAddress(class ProvIpAddress const & __ptr64) __ptr64` | 82 | Exported Function
`public: __cdecl ProvIpAddress::ProvIpAddress(char const * __ptr64) __ptr64` | 84 | Exported Function
`public: __cdecl ProvIntegerType::ProvIntegerType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 80 | Exported Function
`public: __cdecl ProvIpAddress::ProvIpAddress(unsigned long) __ptr64` | 83 | Exported Function
`public: __cdecl ProvIpAddressType::ProvIpAddressType(unsigned long) __ptr64` | 87 | Exported Function
`public: __cdecl ProvIpAddressType::ProvIpAddressType(class ProvIpAddressType const & __ptr64) __ptr64` | 85 | Exported Function
`public: __cdecl ProvIpAddressType::ProvIpAddressType(class ProvIpAddress const & __ptr64) __ptr64` | 86 | Exported Function
`public: __cdecl ProvIntegerType::ProvIntegerType(unsigned short const * __ptr64) __ptr64` | 81 | Exported Function
`public: __cdecl ProvInteger::ProvInteger(class ProvInteger const & __ptr64) __ptr64` | 75 | Exported Function
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 71 | Exported Function
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned short const * __ptr64) __ptr64` | 72 | Exported Function
`public: __cdecl ProvInteger::ProvInteger(long) __ptr64` | 76 | Exported Function
`public: __cdecl ProvIntegerType::ProvIntegerType(long,unsigned short const * __ptr64) __ptr64` | 79 | Exported Function
`public: __cdecl ProvIntegerType::ProvIntegerType(class ProvIntegerType const & __ptr64) __ptr64` | 77 | Exported Function
`public: __cdecl ProvIntegerType::ProvIntegerType(class ProvInteger const & __ptr64,unsigned short const * __ptr64) __ptr64` | 78 | Exported Function
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(long,long) __ptr64` | 97 | Exported Function
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(class ProvNegativeRangeType const & __ptr64) __ptr64` | 96 | Exported Function
`public: __cdecl ProvMacAddressType::ProvMacAddressType(void) __ptr64` | 95 | Exported Function
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(void) __ptr64` | 98 | Exported Function
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(unsigned long) __ptr64` | 101 | Exported Function
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(class ProvNetworkAddressType const & __ptr64) __ptr64` | 99 | Exported Function
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(class ProvIpAddress const & __ptr64) __ptr64` | 100 | Exported Function
`public: __cdecl ProvMacAddressType::ProvMacAddressType(unsigned short const * __ptr64) __ptr64` | 94 | Exported Function
`public: __cdecl ProvLexicon::ProvLexicon(void) __ptr64` | 90 | Exported Function
`public: __cdecl ProvIpAddressType::ProvIpAddressType(void) __ptr64` | 89 | Exported Function
`public: __cdecl ProvIpAddressType::ProvIpAddressType(unsigned short const * __ptr64) __ptr64` | 88 | Exported Function
`public: __cdecl ProvLexicon::~ProvLexicon(void) __ptr64` | 254 | Exported Function
`public: __cdecl ProvMacAddressType::ProvMacAddressType(unsigned char const * __ptr64) __ptr64` | 93 | Exported Function
`public: __cdecl ProvMacAddressType::ProvMacAddressType(class ProvOctetString const & __ptr64) __ptr64` | 92 | Exported Function
`public: __cdecl ProvMacAddressType::ProvMacAddressType(class ProvMacAddressType const & __ptr64) __ptr64` | 91 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `330000026551AE1BBD005CBFBD000000000265`
* Thumbprint: `E168609353F30FF2373157B4EB8CD519D07A2BFF`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: provthrd.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/70
* VirusTotal Link: https://www.virustotal.com/gui/file/6995774c4f464f6a5077ee33957920f539038c8acd501bb404c4ad1a8f78667e/detection/





MIT License. Copyright (c) 2020 Strontic.


