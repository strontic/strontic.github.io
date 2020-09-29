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

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`char * __ptr64 __cdecl UnicodeToDbcsString(unsigned short const * __ptr64)` | 951 (0x3b7) | Exported Function | 0x000000018001bf00 | 0x0001bf00
`public: static unsigned long __cdecl ProvAnalyser::OctCharToDecInteger(char)` | 814 (0x32e) | Exported Function | 0x0000000180019360 | 0x00019360
`public: static unsigned long __cdecl ProvAnalyser::OctWCharToDecInteger(unsigned short)` | 815 (0x32f) | Exported Function | 0x0000000180019370 | 0x00019370
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToDecWChar(unsigned char)` | 608 (0x260) | Exported Function | 0x0000000180015710 | 0x00015710
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToHexWChar(unsigned char)` | 610 (0x262) | Exported Function | 0x0000000180015750 | 0x00015750
`public: static unsigned short __cdecl ProvAnalyser::DecIntegerToOctWChar(unsigned char)` | 612 (0x264) | Exported Function | 0x00000001800157a0 | 0x000157a0
`public: static void __cdecl ProvDebugLog::Closedown(void)` | 531 (0x213) | Exported Function | 0x000000018000a500 | 0x0000a500
`public: union ProvLexiconValue * __ptr64 __cdecl ProvLexicon::GetValue(void) __ptr64` | 752 (0x2f0) | Exported Function | 0x0000000180018bc0 | 0x00018bc0
`public: unsigned char * __ptr64 __cdecl ProvOctetString::GetValue(void)const __ptr64` | 756 (0x2f4) | Exported Function | 0x0000000180005110 | 0x00005110
`public: unsigned char * __ptr64 __cdecl ProvOctetStringType::GetValue(void)const __ptr64` | 757 (0x2f5) | Exported Function | 0x0000000180018be0 | 0x00018be0
`public: unsigned char * __ptr64 __cdecl ProvOpaque::GetValue(void)const __ptr64` | 758 (0x2f6) | Exported Function | 0x0000000180018bf0 | 0x00018bf0
`public: unsigned char * __ptr64 __cdecl ProvOpaqueType::GetValue(void)const __ptr64` | 759 (0x2f7) | Exported Function | 0x0000000180018c00 | 0x00018c00
`public: unsigned long & __ptr64 __cdecl ProvObjectIdentifier::operator[](unsigned long)const __ptr64` | 392 (0x188) | Exported Function | 0x000000018001c6a0 | 0x0001c6a0
`public: static unsigned long __cdecl ProvAnalyser::HexWCharToDecInteger(unsigned short)` | 774 (0x306) | Exported Function | 0x0000000180018cb0 | 0x00018cb0
`public: unsigned long * __ptr64 __cdecl ProvObjectIdentifier::GetValue(void)const __ptr64` | 754 (0x2f2) | Exported Function | 0x000000018001d380 | 0x0001d380
`public: unsigned long __cdecl Conjunctions::GetRangeCount(void) __ptr64` | 706 (0x2c2) | Exported Function | 0x0000000180021c80 | 0x00021c80
`public: unsigned long __cdecl Disjunctions::GetConjunctionCount(void) __ptr64` | 661 (0x295) | Exported Function | 0x0000000180021c80 | 0x00021c80
`public: unsigned long __cdecl Disjunctions::GetDisjunctionCount(void) __ptr64` | 666 (0x29a) | Exported Function | 0x0000000180021cc0 | 0x00021cc0
`public: unsigned long __cdecl PartitionSet::GetKeyIndex(void) __ptr64` | 675 (0x2a3) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl PartitionSet::GetPartitionCount(void) __ptr64` | 689 (0x2b1) | Exported Function | 0x0000000180005100 | 0x00005100
`public: unsigned long __cdecl ProvBitStringType::GetValue(unsigned short * __ptr64 * __ptr64 & __ptr64)const __ptr64` | 738 (0x2e2) | Exported Function | 0x0000000180018710 | 0x00018710
`public: unsigned long __cdecl ProvCounter64::GetHighValue(void)const __ptr64` | 668 (0x29c) | Exported Function | 0x0000000180018700 | 0x00018700
`public: unsigned long __cdecl ProvCounter64::GetLowValue(void)const __ptr64` | 680 (0x2a8) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl ProvCounter::GetValue(void)const __ptr64` | 740 (0x2e4) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl ProvCounterType::GetValue(void)const __ptr64` | 741 (0x2e5) | Exported Function | 0x0000000180005100 | 0x00005100
`public: unsigned long __cdecl ProvDebugLog::GetLevel(void) __ptr64` | 678 (0x2a6) | Exported Function | 0x000000018000a510 | 0x0000a510
`public: unsigned long __cdecl ProvGauge::GetValue(void)const __ptr64` | 746 (0x2ea) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long * __ptr64 __cdecl ProvObjectIdentifierType::GetValue(void)const __ptr64` | 755 (0x2f3) | Exported Function | 0x0000000180018bd0 | 0x00018bd0
`public: unsigned long __cdecl ProvGaugeType::GetValue(void)const __ptr64` | 747 (0x2eb) | Exported Function | 0x0000000180016730 | 0x00016730
`public: static unsigned long __cdecl ProvAnalyser::HexCharToDecInteger(char)` | 773 (0x305) | Exported Function | 0x0000000180018c70 | 0x00018c70
`public: static unsigned long __cdecl ProvAnalyser::DecCharToDecInteger(char)` | 606 (0x25e) | Exported Function | 0x00000001800156d0 | 0x000156d0
`public: int __cdecl WmiUnsignedIntegerNode::LexicographicallyBefore(unsigned long & __ptr64) __ptr64` | 806 (0x326) | Exported Function | 0x00000001800261a0 | 0x000261a0
`public: long __cdecl ProvInteger::GetValue(void)const __ptr64` | 748 (0x2ec) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: long __cdecl ProvIntegerType::GetValue(void)const __ptr64` | 749 (0x2ed) | Exported Function | 0x0000000180016730 | 0x00016730
`public: long __cdecl ProvNegativeRangeType::GetLowerBound(void) __ptr64` | 681 (0x2a9) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: long __cdecl ProvNegativeRangeType::GetUpperBound(void) __ptr64` | 736 (0x2e0) | Exported Function | 0x0000000180018700 | 0x00018700
`public: long __cdecl WmiRangeNode::ComparePropertyName(class WmiRangeNode & __ptr64) __ptr64` | 533 (0x215) | Exported Function | 0x0000000180020c20 | 0x00020c20
`public: long __cdecl WmiSignedIntegerNode::GetValue(void) __ptr64` | 764 (0x2fc) | Exported Function | 0x00000001800051d0 | 0x000051d0
`public: long __cdecl WmiSignedIntegerRangeNode::LowerBound(void) __ptr64` | 807 (0x327) | Exported Function | 0x00000001800261c0 | 0x000261c0
`public: long __cdecl WmiSignedIntegerRangeNode::UpperBound(void) __ptr64` | 952 (0x3b8) | Exported Function | 0x0000000180028550 | 0x00028550
`public: long __cdecl WmiValueNode::ComparePropertyName(class WmiValueNode & __ptr64) __ptr64` | 534 (0x216) | Exported Function | 0x0000000180020c20 | 0x00020c20
`public: static char __cdecl ProvAnalyser::DecIntegerToDecChar(unsigned char)` | 607 (0x25f) | Exported Function | 0x00000001800156f0 | 0x000156f0
`public: static char __cdecl ProvAnalyser::DecIntegerToHexChar(unsigned char)` | 609 (0x261) | Exported Function | 0x0000000180015730 | 0x00015730
`public: static unsigned long __cdecl ProvAnalyser::DecWCharToDecInteger(unsigned short)` | 613 (0x265) | Exported Function | 0x00000001800157c0 | 0x000157c0
`public: static char __cdecl ProvAnalyser::DecIntegerToOctChar(unsigned char)` | 611 (0x263) | Exported Function | 0x0000000180015780 | 0x00015780
`public: static class ProvDebugLog * __ptr64 __ptr64 ProvDebugLog::s_ProvDebugLog` | 963 (0x3c3) | Exported Function | 0x000000018004b000 | 0x0004b000
`public: static class ProvDebugLog * ProvDebugLog::s_aLogs` | 965 (0x3c5) | Exported Function | 0x000000018004c100 | 0x0004c100
`public: static int __cdecl ProvAnalyser::IsAlpha(unsigned short)` | 785 (0x311) | Exported Function | 0x0000000180018d70 | 0x00018d70
`public: static int __cdecl ProvAnalyser::IsAlphaNumeric(unsigned short)` | 786 (0x312) | Exported Function | 0x0000000180018d90 | 0x00018d90
`public: static int __cdecl ProvAnalyser::IsDecimal(unsigned short)` | 787 (0x313) | Exported Function | 0x0000000180018dd0 | 0x00018dd0
`public: static int __cdecl ProvAnalyser::IsEof(unsigned short)` | 788 (0x314) | Exported Function | 0x0000000180018df0 | 0x00018df0
`public: static int __cdecl ProvAnalyser::IsHex(unsigned short)` | 789 (0x315) | Exported Function | 0x0000000180018e00 | 0x00018e00
`public: static int __cdecl ProvAnalyser::IsLeadingDecimal(unsigned short)` | 790 (0x316) | Exported Function | 0x0000000180018e20 | 0x00018e20
`public: static int __cdecl ProvAnalyser::IsOctal(unsigned short)` | 792 (0x318) | Exported Function | 0x0000000180018e60 | 0x00018e60
`public: static int __cdecl ProvAnalyser::IsWhitespace(unsigned short)` | 799 (0x31f) | Exported Function | 0x0000000180018e90 | 0x00018e90
`public: static int __cdecl ProvDebugLog::Startup(void)` | 925 (0x39d) | Exported Function | 0x000000018000a570 | 0x0000a570
`public: static long ProvDebugLog::s_ReferenceCount` | 964 (0x3c4) | Exported Function | 0x000000018004c784 | 0x0004c784
`public: static class ProvDebugLog * __ptr64 __cdecl ProvDebugLog::GetProvDebugLog(char)` | 693 (0x2b5) | Exported Function | 0x000000018000a550 | 0x0000a550
`public: int __cdecl WmiUnsignedIntegerNode::LexicographicallyAfter(unsigned long & __ptr64) __ptr64` | 803 (0x323) | Exported Function | 0x0000000180026050 | 0x00026050
`public: unsigned long __cdecl ProvIpAddress::GetValue(void)const __ptr64` | 750 (0x2ee) | Exported Function | 0x0000000180018700 | 0x00018700
`public: unsigned long __cdecl ProvNetworkAddressType::GetValue(void)const __ptr64` | 753 (0x2f1) | Exported Function | 0x0000000180018bb0 | 0x00018bb0
`public: virtual __cdecl ProvAnalyser::~ProvAnalyser(void) __ptr64` | 232 (0xe8) | Exported Function | 0x00000001800107f0 | 0x000107f0
`public: virtual __cdecl ProvBitStringType::~ProvBitStringType(void) __ptr64` | 233 (0xe9) | Exported Function | 0x0000000180010830 | 0x00010830
`public: virtual __cdecl ProvCounter64::~ProvCounter64(void) __ptr64` | 234 (0xea) | Exported Function | 0x00000001800109f0 | 0x000109f0
`public: virtual __cdecl ProvCounter64Type::~ProvCounter64Type(void) __ptr64` | 235 (0xeb) | Exported Function | 0x0000000180010a30 | 0x00010a30
`public: virtual __cdecl ProvCounter::~ProvCounter(void) __ptr64` | 236 (0xec) | Exported Function | 0x0000000180010a70 | 0x00010a70
`public: virtual __cdecl ProvCounterType::~ProvCounterType(void) __ptr64` | 237 (0xed) | Exported Function | 0x0000000180010ab0 | 0x00010ab0
`public: virtual __cdecl ProvDateTimeType::~ProvDateTimeType(void) __ptr64` | 238 (0xee) | Exported Function | 0x0000000180010b30 | 0x00010b30
`public: virtual __cdecl ProvDisplayStringType::~ProvDisplayStringType(void) __ptr64` | 239 (0xef) | Exported Function | 0x0000000180010bc0 | 0x00010bc0
`public: virtual __cdecl ProvEnumeratedType::~ProvEnumeratedType(void) __ptr64` | 240 (0xf0) | Exported Function | 0x0000000180010c10 | 0x00010c10
`public: virtual __cdecl ProvEventObject::~ProvEventObject(void) __ptr64` | 241 (0xf1) | Exported Function | 0x000000018000ae20 | 0x0000ae20
`public: virtual __cdecl ProvFixedLengthDisplayStringType::~ProvFixedLengthDisplayStringType(void) __ptr64` | 242 (0xf2) | Exported Function | 0x0000000180010dd0 | 0x00010dd0
`public: virtual __cdecl ProvFixedLengthOctetStringType::~ProvFixedLengthOctetStringType(void) __ptr64` | 243 (0xf3) | Exported Function | 0x0000000180010e20 | 0x00010e20
`public: virtual __cdecl ProvAnalyser::operator void * __ptr64(void) __ptr64` | 393 (0x189) | Exported Function | 0x00000001800124d0 | 0x000124d0
`public: virtual __cdecl ProvFixedLengthOpaqueType::~ProvFixedLengthOpaqueType(void) __ptr64` | 244 (0xf4) | Exported Function | 0x0000000180010ea0 | 0x00010ea0
`public: virtual __cdecl ProvFixedType::~ProvFixedType(void) __ptr64` | 246 (0xf6) | Exported Function | 0x0000000180010f70 | 0x00010f70
`public: virtual __cdecl ProvGauge::~ProvGauge(void) __ptr64` | 247 (0xf7) | Exported Function | 0x0000000180010f90 | 0x00010f90
`public: virtual __cdecl ProvGaugeType::~ProvGaugeType(void) __ptr64` | 248 (0xf8) | Exported Function | 0x0000000180010fd0 | 0x00010fd0
`public: virtual __cdecl ProvInstanceType::operator void * __ptr64(void) __ptr64` | 394 (0x18a) | Exported Function | 0x00000001800124f0 | 0x000124f0
`public: virtual __cdecl ProvInstanceType::~ProvInstanceType(void) __ptr64` | 249 (0xf9) | Exported Function | 0x0000000180011080 | 0x00011080
`public: virtual __cdecl ProvInteger::~ProvInteger(void) __ptr64` | 250 (0xfa) | Exported Function | 0x00000001800110a0 | 0x000110a0
`public: virtual __cdecl ProvIntegerType::~ProvIntegerType(void) __ptr64` | 251 (0xfb) | Exported Function | 0x00000001800110e0 | 0x000110e0
`public: virtual __cdecl ProvIpAddress::~ProvIpAddress(void) __ptr64` | 252 (0xfc) | Exported Function | 0x0000000180011190 | 0x00011190
`public: virtual __cdecl ProvIpAddressType::~ProvIpAddressType(void) __ptr64` | 253 (0xfd) | Exported Function | 0x00000001800111d0 | 0x000111d0
`public: virtual __cdecl ProvMacAddressType::~ProvMacAddressType(void) __ptr64` | 255 (0xff) | Exported Function | 0x0000000180011290 | 0x00011290
`public: virtual __cdecl ProvNegativeRangeType::~ProvNegativeRangeType(void) __ptr64` | 256 (0x100) | Exported Function | 0x00000001800112e0 | 0x000112e0
`public: virtual __cdecl ProvNetworkAddressType::~ProvNetworkAddressType(void) __ptr64` | 257 (0x101) | Exported Function | 0x00000001800113d0 | 0x000113d0
`public: virtual __cdecl ProvFixedLengthPhysAddressType::~ProvFixedLengthPhysAddressType(void) __ptr64` | 245 (0xf5) | Exported Function | 0x0000000180010f20 | 0x00010f20
`public: unsigned long __cdecl ProvIpAddressType::GetValue(void)const __ptr64` | 751 (0x2ef) | Exported Function | 0x0000000180018bb0 | 0x00018bb0
`public: virtual __cdecl PartitionSet::~PartitionSet(void) __ptr64` | 231 (0xe7) | Exported Function | 0x000000018001ef40 | 0x0001ef40
`public: unsigned short * __ptr64 __cdecl WmiStringRangeNode::UpperBound(void) __ptr64` | 953 (0x3b9) | Exported Function | 0x00000001800051c0 | 0x000051c0
`public: unsigned long __cdecl ProvObjectIdentifier::GetValueLength(void)const __ptr64` | 767 (0x2ff) | Exported Function | 0x000000018001d390 | 0x0001d390
`public: unsigned long __cdecl ProvObjectIdentifierType::GetValueLength(void)const __ptr64` | 768 (0x300) | Exported Function | 0x0000000180018c20 | 0x00018c20
`public: unsigned long __cdecl ProvOctetString::GetValueLength(void)const __ptr64` | 769 (0x301) | Exported Function | 0x0000000180005100 | 0x00005100
`public: unsigned long __cdecl ProvOctetStringType::GetValueLength(void)const __ptr64` | 770 (0x302) | Exported Function | 0x0000000180018c30 | 0x00018c30
`public: unsigned long __cdecl ProvOpaque::GetValueLength(void)const __ptr64` | 771 (0x303) | Exported Function | 0x0000000180018c40 | 0x00018c40
`public: unsigned long __cdecl ProvOpaqueType::GetValueLength(void)const __ptr64` | 772 (0x304) | Exported Function | 0x0000000180018c50 | 0x00018c50
`public: unsigned long __cdecl ProvPositiveRangeType::GetLowerBound(void) __ptr64` | 682 (0x2aa) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl ProvPositiveRangeType::GetUpperBound(void) __ptr64` | 737 (0x2e1) | Exported Function | 0x0000000180018700 | 0x00018700
`public: unsigned long __cdecl ProvTimeTicks::GetValue(void)const __ptr64` | 761 (0x2f9) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl ProvTimeTicksType::GetValue(void)const __ptr64` | 762 (0x2fa) | Exported Function | 0x0000000180005100 | 0x00005100
`public: unsigned long __cdecl ProvUInteger32::GetValue(void)const __ptr64` | 763 (0x2fb) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl WmiRangeNode::GetIndex(void) __ptr64` | 669 (0x29d) | Exported Function | 0x0000000180021cd0 | 0x00021cd0
`public: unsigned short * __ptr64 __cdecl WmiValueNode::GetPropertyName(void) __ptr64` | 692 (0x2b4) | Exported Function | 0x00000001800051f0 | 0x000051f0
`public: unsigned long __cdecl WmiTreeNode::GetType(void) __ptr64` | 735 (0x2df) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: unsigned long __cdecl WmiUnsignedIntegerRangeNode::LowerBound(void) __ptr64` | 809 (0x329) | Exported Function | 0x00000001800261c0 | 0x000261c0
`public: unsigned long __cdecl WmiUnsignedIntegerRangeNode::UpperBound(void) __ptr64` | 954 (0x3ba) | Exported Function | 0x0000000180028550 | 0x00028550
`public: unsigned long __cdecl WmiValueNode::GetIndex(void) __ptr64` | 670 (0x29e) | Exported Function | 0x0000000180021cd0 | 0x00021cd0
`public: unsigned short * __ptr64 __cdecl CBString::GetString(void) __ptr64` | 710 (0x2c6) | Exported Function | 0x00000001800167a0 | 0x000167a0
`public: unsigned short * __ptr64 __cdecl ProvDateTimeType::GetValue(void)const __ptr64` | 742 (0x2e6) | Exported Function | 0x0000000180018940 | 0x00018940
`public: unsigned short * __ptr64 __cdecl ProvDisplayStringType::GetValue(void)const __ptr64` | 743 (0x2e7) | Exported Function | 0x0000000180018b20 | 0x00018b20
`public: unsigned short * __ptr64 __cdecl ProvEnumeratedType::GetValue(void)const __ptr64` | 744 (0x2e8) | Exported Function | 0x0000000180016a10 | 0x00016a10
`public: unsigned short * __ptr64 __cdecl ProvFixedLengthDisplayStringType::GetValue(void)const __ptr64` | 745 (0x2e9) | Exported Function | 0x0000000180016ac0 | 0x00016ac0
`public: unsigned short * __ptr64 __cdecl ProvRowStatusType::GetValue(void)const __ptr64` | 760 (0x2f8) | Exported Function | 0x0000000180017fc0 | 0x00017fc0
`public: unsigned short * __ptr64 __cdecl WmiRangeNode::GetPropertyName(void) __ptr64` | 691 (0x2b3) | Exported Function | 0x00000001800051f0 | 0x000051f0
`public: unsigned short * __ptr64 __cdecl WmiStringNode::GetValue(void) __ptr64` | 765 (0x2fd) | Exported Function | 0x0000000180025c50 | 0x00025c50
`public: unsigned short * __ptr64 __cdecl WmiStringRangeNode::LowerBound(void) __ptr64` | 808 (0x328) | Exported Function | 0x00000001800050c0 | 0x000050c0
`public: unsigned long __cdecl WmiUnsignedIntegerNode::GetValue(void) __ptr64` | 766 (0x2fe) | Exported Function | 0x00000001800051d0 | 0x000051d0
`public: int __cdecl WmiStringNode::LexicographicallyBefore(unsigned short * __ptr64 & __ptr64) __ptr64` | 805 (0x325) | Exported Function | 0x0000000180026090 | 0x00026090
`public: int __cdecl WmiStringNode::LexicographicallyAfter(unsigned short * __ptr64 & __ptr64) __ptr64` | 802 (0x322) | Exported Function | 0x0000000180025f90 | 0x00025f90
`public: int __cdecl WmiSignedIntegerNode::LexicographicallyBefore(long & __ptr64) __ptr64` | 804 (0x324) | Exported Function | 0x0000000180026070 | 0x00026070
`public: class WmiNullNode & __ptr64 __cdecl WmiNullNode::operator=(class WmiNullNode && __ptr64) __ptr64` | 357 (0x165) | Exported Function | 0x000000018001f8c0 | 0x0001f8c0
`public: class WmiNullNode & __ptr64 __cdecl WmiNullNode::operator=(class WmiNullNode const & __ptr64) __ptr64` | 358 (0x166) | Exported Function | 0x000000018001f8c0 | 0x0001f8c0
`public: class WmiNullRangeNode & __ptr64 __cdecl WmiNullRangeNode::operator=(class WmiNullRangeNode const & __ptr64) __ptr64` | 359 (0x167) | Exported Function | 0x000000018001f910 | 0x0001f910
`public: class WmiOperatorEqualNode & __ptr64 __cdecl WmiOperatorEqualNode::operator=(class WmiOperatorEqualNode const & __ptr64) __ptr64` | 360 (0x168) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorEqualOrGreaterNode & __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::operator=(class WmiOperatorEqualOrGreaterNode const & __ptr64) __ptr64` | 361 (0x169) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorEqualOrLessNode & __ptr64 __cdecl WmiOperatorEqualOrLessNode::operator=(class WmiOperatorEqualOrLessNode const & __ptr64) __ptr64` | 362 (0x16a) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorGreaterNode & __ptr64 __cdecl WmiOperatorGreaterNode::operator=(class WmiOperatorGreaterNode const & __ptr64) __ptr64` | 363 (0x16b) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorIsANode & __ptr64 __cdecl WmiOperatorIsANode::operator=(class WmiOperatorIsANode const & __ptr64) __ptr64` | 364 (0x16c) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorLessNode & __ptr64 __cdecl WmiOperatorLessNode::operator=(class WmiOperatorLessNode const & __ptr64) __ptr64` | 365 (0x16d) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorLikeNode & __ptr64 __cdecl WmiOperatorLikeNode::operator=(class WmiOperatorLikeNode const & __ptr64) __ptr64` | 366 (0x16e) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorNode & __ptr64 __cdecl WmiOperatorNode::operator=(class WmiOperatorNode const & __ptr64) __ptr64` | 367 (0x16f) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorNotEqualNode & __ptr64 __cdecl WmiOperatorNotEqualNode::operator=(class WmiOperatorNotEqualNode const & __ptr64) __ptr64` | 368 (0x170) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiNotNode & __ptr64 __cdecl WmiNotNode::operator=(class WmiNotNode const & __ptr64) __ptr64` | 356 (0x164) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOperatorNotIsANode & __ptr64 __cdecl WmiOperatorNotIsANode::operator=(class WmiOperatorNotIsANode const & __ptr64) __ptr64` | 369 (0x171) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiOrNode & __ptr64 __cdecl WmiOrNode::operator=(class WmiOrNode const & __ptr64) __ptr64` | 371 (0x173) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiRangeNode & __ptr64 __cdecl WmiRangeNode::operator=(class WmiRangeNode const & __ptr64) __ptr64` | 372 (0x174) | Exported Function | 0x000000018001f910 | 0x0001f910
`public: class WmiRangeNode * __ptr64 __cdecl Conjunctions::GetRange(unsigned long) __ptr64` | 694 (0x2b6) | Exported Function | 0x0000000180025280 | 0x00025280
`public: class WmiRangeNode * __ptr64 __cdecl PartitionSet::GetRange(void) __ptr64` | 695 (0x2b7) | Exported Function | 0x0000000180005110 | 0x00005110
`public: class WmiSignedIntegerNode & __ptr64 __cdecl WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode && __ptr64) __ptr64` | 373 (0x175) | Exported Function | 0x000000018001f970 | 0x0001f970
`public: class WmiSignedIntegerNode & __ptr64 __cdecl WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode const & __ptr64) __ptr64` | 374 (0x176) | Exported Function | 0x000000018001f970 | 0x0001f970
`public: class WmiSignedIntegerRangeNode & __ptr64 __cdecl WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode && __ptr64) __ptr64` | 375 (0x177) | Exported Function | 0x000000018001f9d0 | 0x0001f9d0
`public: class WmiSignedIntegerRangeNode & __ptr64 __cdecl WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode const & __ptr64) __ptr64` | 376 (0x178) | Exported Function | 0x000000018001f9d0 | 0x0001f9d0
`public: class WmiStringNode & __ptr64 __cdecl WmiStringNode::operator=(class WmiStringNode const & __ptr64) __ptr64` | 377 (0x179) | Exported Function | 0x000000018001fa40 | 0x0001fa40
`public: class WmiStringRangeNode & __ptr64 __cdecl WmiStringRangeNode::operator=(class WmiStringRangeNode const & __ptr64) __ptr64` | 378 (0x17a) | Exported Function | 0x000000018001faa0 | 0x0001faa0
`public: class WmiTreeNode & __ptr64 __cdecl WmiTreeNode::operator=(class WmiTreeNode const & __ptr64) __ptr64` | 379 (0x17b) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetLeft(void) __ptr64` | 676 (0x2a4) | Exported Function | 0x00000001800232c0 | 0x000232c0
`public: class WmiOperatorNotLikeNode & __ptr64 __cdecl WmiOperatorNotLikeNode::operator=(class WmiOperatorNotLikeNode const & __ptr64) __ptr64` | 370 (0x172) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetParent(void) __ptr64` | 686 (0x2ae) | Exported Function | 0x0000000180025260 | 0x00025260
`public: class WmiAndNode & __ptr64 __cdecl WmiAndNode::operator=(class WmiAndNode const & __ptr64) __ptr64` | 355 (0x163) | Exported Function | 0x000000018001f880 | 0x0001f880
`public: class ProvValue & __ptr64 __cdecl ProvUInteger32::operator=(class ProvUInteger32 const & __ptr64) __ptr64` | 352 (0x160) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvMacAddressType & __ptr64 __cdecl ProvMacAddressType::operator=(class ProvMacAddressType const & __ptr64) __ptr64` | 333 (0x14d) | Exported Function | 0x0000000180011de0 | 0x00011de0
`public: class ProvNegativeRangeType & __ptr64 __cdecl ProvNegativeRangeType::operator=(class ProvNegativeRangeType const & __ptr64) __ptr64` | 334 (0x14e) | Exported Function | 0x0000000180011f00 | 0x00011f00
`public: class ProvNetworkAddressType & __ptr64 __cdecl ProvNetworkAddressType::operator=(class ProvNetworkAddressType const & __ptr64) __ptr64` | 335 (0x14f) | Exported Function | 0x0000000180011f50 | 0x00011f50
`public: class ProvNullType & __ptr64 __cdecl ProvNullType::operator=(class ProvNullType const & __ptr64) __ptr64` | 337 (0x151) | Exported Function | 0x0000000180011f00 | 0x00011f00
`public: class ProvObjectIdentifier * __ptr64 __cdecl ProvObjectIdentifier::Cut(class ProvObjectIdentifier & __ptr64)const __ptr64` | 603 (0x25b) | Exported Function | 0x000000018001cda0 | 0x0001cda0
`public: class ProvObjectIdentifier __cdecl ProvObjectIdentifier::operator+(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 396 (0x18c) | Exported Function | 0x000000018001c6d0 | 0x0001c6d0
`public: class ProvObjectIdentifierType & __ptr64 __cdecl ProvObjectIdentifierType::operator=(class ProvObjectIdentifierType const & __ptr64) __ptr64` | 340 (0x154) | Exported Function | 0x0000000180012000 | 0x00012000
`public: class ProvOctetStringType & __ptr64 __cdecl ProvOctetStringType::operator=(class ProvOctetStringType const & __ptr64) __ptr64` | 342 (0x156) | Exported Function | 0x0000000180012080 | 0x00012080
`public: class ProvOpaqueType & __ptr64 __cdecl ProvOpaqueType::operator=(class ProvOpaqueType const & __ptr64) __ptr64` | 344 (0x158) | Exported Function | 0x0000000180012150 | 0x00012150
`public: class ProvOSIAddressType & __ptr64 __cdecl ProvOSIAddressType::operator=(class ProvOSIAddressType const & __ptr64) __ptr64` | 338 (0x152) | Exported Function | 0x0000000180011ce0 | 0x00011ce0
`public: class ProvPhysAddressType & __ptr64 __cdecl ProvPhysAddressType::operator=(class ProvPhysAddressType const & __ptr64) __ptr64` | 345 (0x159) | Exported Function | 0x0000000180011ce0 | 0x00011ce0
`public: class ProvPositiveRangedType & __ptr64 __cdecl ProvPositiveRangedType::operator=(class ProvPositiveRangedType const & __ptr64) __ptr64` | 347 (0x15b) | Exported Function | 0x00000001800121e0 | 0x000121e0
`public: class QueryPreprocessor & __ptr64 __cdecl QueryPreprocessor::operator=(class QueryPreprocessor const & __ptr64) __ptr64` | 354 (0x162) | Exported Function | 0x0000000180011fb0 | 0x00011fb0
`public: class ProvPositiveRangeType & __ptr64 __cdecl ProvPositiveRangeType::operator=(class ProvPositiveRangeType const & __ptr64) __ptr64` | 346 (0x15a) | Exported Function | 0x0000000180011f00 | 0x00011f00
`public: class ProvTimeTicksType & __ptr64 __cdecl ProvTimeTicksType::operator=(class ProvTimeTicksType const & __ptr64) __ptr64` | 350 (0x15e) | Exported Function | 0x0000000180011c50 | 0x00011c50
`public: class ProvUDPAddressType & __ptr64 __cdecl ProvUDPAddressType::operator=(class ProvUDPAddressType const & __ptr64) __ptr64` | 351 (0x15f) | Exported Function | 0x0000000180011de0 | 0x00011de0
`public: class ProvValue & __ptr64 __cdecl ProvCounter64::operator=(class ProvCounter64 const & __ptr64) __ptr64` | 310 (0x136) | Exported Function | 0x0000000180011be0 | 0x00011be0
`public: class ProvValue & __ptr64 __cdecl ProvCounter::operator=(class ProvCounter const & __ptr64) __ptr64` | 312 (0x138) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvValue & __ptr64 __cdecl ProvGauge::operator=(class ProvGauge const & __ptr64) __ptr64` | 325 (0x145) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvValue & __ptr64 __cdecl ProvInteger::operator=(class ProvInteger const & __ptr64) __ptr64` | 328 (0x148) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvValue & __ptr64 __cdecl ProvIpAddress::operator=(class ProvIpAddress const & __ptr64) __ptr64` | 330 (0x14a) | Exported Function | 0x0000000180011f20 | 0x00011f20
`public: class ProvValue & __ptr64 __cdecl ProvNull::operator=(class ProvNull const & __ptr64) __ptr64` | 336 (0x150) | Exported Function | 0x0000000180011fb0 | 0x00011fb0
`public: class ProvValue & __ptr64 __cdecl ProvObjectIdentifier::operator=(class ProvObjectIdentifier const & __ptr64) __ptr64` | 339 (0x153) | Exported Function | 0x0000000180011fc0 | 0x00011fc0
`public: class ProvValue & __ptr64 __cdecl ProvOctetString::operator=(class ProvOctetString const & __ptr64) __ptr64` | 341 (0x155) | Exported Function | 0x0000000180012040 | 0x00012040
`public: class ProvValue & __ptr64 __cdecl ProvOpaque::operator=(class ProvOpaque const & __ptr64) __ptr64` | 343 (0x157) | Exported Function | 0x0000000180012110 | 0x00012110
`public: class ProvValue & __ptr64 __cdecl ProvTimeTicks::operator=(class ProvTimeTicks const & __ptr64) __ptr64` | 349 (0x15d) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvRowStatusType & __ptr64 __cdecl ProvRowStatusType::operator=(class ProvRowStatusType const & __ptr64) __ptr64` | 348 (0x15c) | Exported Function | 0x0000000180012240 | 0x00012240
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::GetRight(void) __ptr64` | 707 (0x2c3) | Exported Function | 0x0000000180025c30 | 0x00025c30
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetLeft(class WmiTreeNode * __ptr64) __ptr64` | 897 (0x381) | Exported Function | 0x0000000180026fe0 | 0x00026fe0
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetParent(class WmiTreeNode * __ptr64) __ptr64` | 901 (0x385) | Exported Function | 0x0000000180026ff0 | 0x00026ff0
`public: int __cdecl ProvInstanceType::operator!=(class ProvInstanceType const & __ptr64)const __ptr64` | 389 (0x185) | Exported Function | 0x00000001800122a0 | 0x000122a0
`public: int __cdecl ProvInstanceType::operator==(class ProvInstanceType const & __ptr64)const __ptr64` | 386 (0x182) | Exported Function | 0x0000000180012260 | 0x00012260
`public: int __cdecl ProvInteger::Equivalent(class ProvInteger const & __ptr64)const __ptr64` | 627 (0x273) | Exported Function | 0x0000000180015b50 | 0x00015b50
`public: int __cdecl ProvIpAddress::Equivalent(class ProvIpAddress const & __ptr64)const __ptr64` | 630 (0x276) | Exported Function | 0x0000000180015c80 | 0x00015c80
`public: int __cdecl ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const & __ptr64,unsigned long)const __ptr64` | 637 (0x27d) | Exported Function | 0x000000018001d0c0 | 0x0001d0c0
`public: int __cdecl ProvObjectIdentifier::operator!=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 390 (0x186) | Exported Function | 0x00000001800122d0 | 0x000122d0
`public: int __cdecl ProvObjectIdentifier::operator<(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 397 (0x18d) | Exported Function | 0x0000000180012530 | 0x00012530
`public: int __cdecl ProvObjectIdentifier::operator<=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 398 (0x18e) | Exported Function | 0x0000000180012560 | 0x00012560
`public: int __cdecl ProvObjectIdentifier::operator==(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 387 (0x183) | Exported Function | 0x0000000180012280 | 0x00012280
`public: int __cdecl ProvObjectIdentifier::operator>(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 399 (0x18f) | Exported Function | 0x0000000180012590 | 0x00012590
`public: int __cdecl ProvObjectIdentifier::operator>=(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 400 (0x190) | Exported Function | 0x00000001800125c0 | 0x000125c0
`public: int __cdecl ProvObjectIdentifier::Prefix(unsigned long,class ProvObjectIdentifier & __ptr64)const __ptr64` | 839 (0x347) | Exported Function | 0x000000018001b340 | 0x0001b340
`public: int __cdecl ProvGauge::Equivalent(class ProvGauge const & __ptr64)const __ptr64` | 624 (0x270) | Exported Function | 0x0000000180015b50 | 0x00015b50
`public: int __cdecl ProvObjectIdentifier::Suffix(unsigned long,class ProvObjectIdentifier & __ptr64)const __ptr64` | 926 (0x39e) | Exported Function | 0x000000018001bd20 | 0x0001bd20
`public: int __cdecl ProvOpaque::Equivalent(class ProvOpaque const & __ptr64)const __ptr64` | 643 (0x283) | Exported Function | 0x0000000180015ec0 | 0x00015ec0
`public: int __cdecl ProvPositiveRangedType::Check(unsigned long const & __ptr64) __ptr64` | 527 (0x20f) | Exported Function | 0x00000001800148a0 | 0x000148a0
`public: int __cdecl ProvPositiveRangedType::IsValid(void) __ptr64` | 798 (0x31e) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: int __cdecl ProvTimeTicks::Equivalent(class ProvTimeTicks const & __ptr64)const __ptr64` | 646 (0x286) | Exported Function | 0x0000000180015b50 | 0x00015b50
`public: int __cdecl ProvUInteger32::Equivalent(class ProvUInteger32 const & __ptr64)const __ptr64` | 649 (0x289) | Exported Function | 0x0000000180015b50 | 0x00015b50
`public: int __cdecl ProvValue::operator!=(class ProvValue const & __ptr64)const __ptr64` | 391 (0x187) | Exported Function | 0x00000001800122a0 | 0x000122a0
`public: int __cdecl ProvValue::operator==(class ProvValue const & __ptr64)const __ptr64` | 388 (0x184) | Exported Function | 0x0000000180012260 | 0x00012260
`public: int __cdecl WmiRangeNode::ClosedLowerBound(void) __ptr64` | 529 (0x211) | Exported Function | 0x00000001800051e0 | 0x000051e0
`public: int __cdecl WmiRangeNode::ClosedUpperBound(void) __ptr64` | 530 (0x212) | Exported Function | 0x00000001800051d0 | 0x000051d0
`public: int __cdecl WmiRangeNode::InfiniteLowerBound(void) __ptr64` | 775 (0x307) | Exported Function | 0x00000001800050d0 | 0x000050d0
`public: int __cdecl WmiRangeNode::InfiniteUpperBound(void) __ptr64` | 776 (0x308) | Exported Function | 0x0000000180005120 | 0x00005120
`public: int __cdecl WmiSignedIntegerNode::LexicographicallyAfter(long & __ptr64) __ptr64` | 801 (0x321) | Exported Function | 0x0000000180025f70 | 0x00025f70
`public: int __cdecl ProvOctetString::Equivalent(class ProvOctetString const & __ptr64)const __ptr64` | 640 (0x280) | Exported Function | 0x000000018001d1a0 | 0x0001d1a0
`public: int __cdecl ProvDebugLog::GetLogging(void) __ptr64` | 679 (0x2a7) | Exported Function | 0x000000018000a520 | 0x0000a520
`public: int __cdecl ProvCounter::Equivalent(class ProvCounter const & __ptr64)const __ptr64` | 621 (0x26d) | Exported Function | 0x0000000180015b50 | 0x00015b50
`public: int __cdecl ProvCounter64::Equivalent(class ProvCounter64 const & __ptr64)const __ptr64` | 618 (0x26a) | Exported Function | 0x0000000180015a90 | 0x00015a90
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::SetRight(class WmiTreeNode * __ptr64) __ptr64` | 905 (0x389) | Exported Function | 0x00000001800270a0 | 0x000270a0
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNodeIterator::GetIterator(void) __ptr64` | 674 (0x2a2) | Exported Function | 0x000000018000ae80 | 0x0000ae80
`public: class WmiTreeNode * __ptr64 __cdecl WmiTreeNodeIterator::SetIterator(class WmiTreeNode * __ptr64) __ptr64` | 895 (0x37f) | Exported Function | 0x0000000180026fd0 | 0x00026fd0
`public: class WmiTreeNodeIterator & __ptr64 __cdecl WmiTreeNodeIterator::operator=(class WmiTreeNodeIterator const & __ptr64) __ptr64` | 380 (0x17c) | Exported Function | 0x000000018000a430 | 0x0000a430
`public: class WmiUnsignedIntegerNode & __ptr64 __cdecl WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode && __ptr64) __ptr64` | 381 (0x17d) | Exported Function | 0x000000018001f970 | 0x0001f970
`public: class WmiUnsignedIntegerNode & __ptr64 __cdecl WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode const & __ptr64) __ptr64` | 382 (0x17e) | Exported Function | 0x000000018001f970 | 0x0001f970
`public: class WmiUnsignedIntegerRangeNode & __ptr64 __cdecl WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode && __ptr64) __ptr64` | 383 (0x17f) | Exported Function | 0x000000018001f9d0 | 0x0001f9d0
`public: class WmiUnsignedIntegerRangeNode & __ptr64 __cdecl WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode const & __ptr64) __ptr64` | 384 (0x180) | Exported Function | 0x000000018001f9d0 | 0x0001f9d0
`public: class WmiValueNode & __ptr64 __cdecl WmiValueNode::operator=(class WmiValueNode const & __ptr64) __ptr64` | 385 (0x181) | Exported Function | 0x000000018001f8c0 | 0x0001f8c0
`public: enum ProvLexicon::LexiconToken __cdecl ProvLexicon::GetToken(void) __ptr64` | 734 (0x2de) | Exported Function | 0x0000000180018700 | 0x00018700
`public: enum ProvRowStatusType::ProvRowStatusEnum __cdecl ProvRowStatusType::GetRowStatus(void)const __ptr64` | 709 (0x2c5) | Exported Function | 0x0000000180016730 | 0x00016730
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::PreProcess(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 837 (0x345) | Exported Function | 0x0000000180002820 | 0x00002820
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::PreProcess(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64,class WmiTreeNode * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,class PartitionSet * __ptr64 & __ptr64) __ptr64` | 838 (0x346) | Exported Function | 0x0000000180002220 | 0x00002220
`public: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::Query(unsigned short * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION * __ptr64 & __ptr64) __ptr64` | 869 (0x365) | Exported Function | 0x0000000180001420 | 0x00001420
`public: enum WmiTriState __cdecl Conjunctions::Initialize(void) __ptr64` | 778 (0x30a) | Exported Function | 0x0000000180025c60 | 0x00025c60
`public: enum WmiTriState __cdecl Disjunctions::Initialize(void) __ptr64` | 779 (0x30b) | Exported Function | 0x0000000180025cd0 | 0x00025cd0
`public: enum WmiTriState __cdecl PartitionSet::Initialize(unsigned long) __ptr64` | 780 (0x30c) | Exported Function | 0x0000000180025db0 | 0x00025db0
`public: enum WmiTriState __cdecl WmiSignedIntegerRangeNode::GetIntersectingRange(class WmiSignedIntegerRangeNode & __ptr64,class WmiSignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 671 (0x29f) | Exported Function | 0x0000000180021ce0 | 0x00021ce0
`public: enum WmiTriState __cdecl WmiSignedIntegerRangeNode::GetOverlappingRange(class WmiSignedIntegerRangeNode & __ptr64,class WmiSignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 683 (0x2ab) | Exported Function | 0x00000001800232e0 | 0x000232e0
`public: enum WmiTriState __cdecl WmiStringRangeNode::GetIntersectingRange(class WmiStringRangeNode & __ptr64,class WmiStringRangeNode * __ptr64 & __ptr64) __ptr64` | 672 (0x2a0) | Exported Function | 0x0000000180022400 | 0x00022400
`public: enum WmiTriState __cdecl WmiStringRangeNode::GetOverlappingRange(class WmiStringRangeNode & __ptr64,class WmiStringRangeNode * __ptr64 & __ptr64) __ptr64` | 684 (0x2ac) | Exported Function | 0x0000000180023d70 | 0x00023d70
`public: enum WmiTriState __cdecl WmiUnsignedIntegerRangeNode::GetIntersectingRange(class WmiUnsignedIntegerRangeNode & __ptr64,class WmiUnsignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 673 (0x2a1) | Exported Function | 0x0000000180022ba0 | 0x00022ba0
`public: enum WmiTriState __cdecl WmiUnsignedIntegerRangeNode::GetOverlappingRange(class WmiUnsignedIntegerRangeNode & __ptr64,class WmiUnsignedIntegerRangeNode * __ptr64 & __ptr64) __ptr64` | 685 (0x2ad) | Exported Function | 0x00000001800247d0 | 0x000247d0
`public: enum WmiValueNode::WmiValueFunction __cdecl WmiValueNode::GetConstantFunction(void) __ptr64` | 662 (0x296) | Exported Function | 0x0000000180005120 | 0x00005120
`public: enum WmiValueNode::WmiValueFunction __cdecl WmiValueNode::GetPropertyFunction(void) __ptr64` | 690 (0x2b2) | Exported Function | 0x00000001800050d0 | 0x000050d0
`public: int __cdecl PartitionSet::Leaf(void) __ptr64` | 800 (0x320) | Exported Function | 0x0000000180025f50 | 0x00025f50
`public: int __cdecl PartitionSet::Root(void) __ptr64` | 891 (0x37b) | Exported Function | 0x0000000180026fa0 | 0x00026fa0
`public: virtual __cdecl ProvNull::~ProvNull(void) __ptr64` | 258 (0x102) | Exported Function | 0x0000000180011450 | 0x00011450
`public: virtual __cdecl ProvNullType::~ProvNullType(void) __ptr64` | 259 (0x103) | Exported Function | 0x0000000180011490 | 0x00011490
`public: virtual __cdecl ProvObjectIdentifier::~ProvObjectIdentifier(void) __ptr64` | 261 (0x105) | Exported Function | 0x000000018001c5f0 | 0x0001c5f0
`public: virtual __cdecl ProvObjectIdentifierType::~ProvObjectIdentifierType(void) __ptr64` | 262 (0x106) | Exported Function | 0x0000000180011560 | 0x00011560
`public: virtual void __cdecl WmiOperatorGreaterNode::Print(void) __ptr64` | 847 (0x34f) | Exported Function | 0x0000000180026510 | 0x00026510
`public: virtual void __cdecl WmiOperatorIsANode::Print(void) __ptr64` | 848 (0x350) | Exported Function | 0x0000000180026570 | 0x00026570
`public: virtual void __cdecl WmiOperatorLessNode::Print(void) __ptr64` | 849 (0x351) | Exported Function | 0x00000001800265d0 | 0x000265d0
`public: virtual void __cdecl WmiOperatorLikeNode::Print(void) __ptr64` | 850 (0x352) | Exported Function | 0x0000000180026630 | 0x00026630
`public: virtual void __cdecl WmiOperatorNotEqualNode::Print(void) __ptr64` | 851 (0x353) | Exported Function | 0x0000000180026690 | 0x00026690
`public: virtual void __cdecl WmiOperatorNotIsANode::Print(void) __ptr64` | 852 (0x354) | Exported Function | 0x00000001800266f0 | 0x000266f0
`public: virtual void __cdecl WmiOperatorNotLikeNode::Print(void) __ptr64` | 853 (0x355) | Exported Function | 0x0000000180026750 | 0x00026750
`public: virtual void __cdecl WmiOrNode::Print(void) __ptr64` | 854 (0x356) | Exported Function | 0x00000001800267b0 | 0x000267b0
`public: virtual void __cdecl WmiSignedIntegerNode::Print(void) __ptr64` | 855 (0x357) | Exported Function | 0x00000001800268d0 | 0x000268d0
`public: virtual void __cdecl WmiSignedIntegerRangeNode::Print(void) __ptr64` | 856 (0x358) | Exported Function | 0x0000000180026920 | 0x00026920
`public: virtual void __cdecl WmiStringNode::Print(void) __ptr64` | 857 (0x359) | Exported Function | 0x0000000180026a00 | 0x00026a00
`public: virtual void __cdecl WmiStringRangeNode::Print(void) __ptr64` | 858 (0x35a) | Exported Function | 0x0000000180026a50 | 0x00026a50
`public: virtual void __cdecl WmiOperatorEqualOrLessNode::Print(void) __ptr64` | 846 (0x34e) | Exported Function | 0x00000001800264b0 | 0x000264b0
`public: virtual void __cdecl WmiTreeNode::Print(void) __ptr64` | 859 (0x35b) | Exported Function | 0x0000000180005240 | 0x00005240
`public: virtual void __cdecl WmiUnsignedIntegerRangeNode::Print(void) __ptr64` | 861 (0x35d) | Exported Function | 0x0000000180026b70 | 0x00026b70
`public: void * __ptr64 __cdecl ProvEventObject::GetHandle(void) __ptr64` | 667 (0x29b) | Exported Function | 0x000000018000ae80 | 0x0000ae80
`public: void * __ptr64 __cdecl ProvIpAddress::operator()(void)const __ptr64` | 401 (0x191) | Exported Function | 0x0000000180012510 | 0x00012510
`public: void * __ptr64 __cdecl ProvObjectIdentifier::operator()(void)const __ptr64` | 402 (0x192) | Exported Function | 0x0000000180012510 | 0x00012510
`public: void * __ptr64 __cdecl ProvOctetString::operator()(void)const __ptr64` | 403 (0x193) | Exported Function | 0x0000000180012510 | 0x00012510
`public: void * __ptr64 __cdecl ProvOpaque::operator()(void)const __ptr64` | 404 (0x194) | Exported Function | 0x00000001800126b0 | 0x000126b0
`public: void * __ptr64 __cdecl WmiTreeNode::GetData(void) __ptr64` | 663 (0x297) | Exported Function | 0x0000000180005110 | 0x00005110
`public: void * __ptr64 __cdecl WmiTreeNode::SetData(void * __ptr64) __ptr64` | 894 (0x37e) | Exported Function | 0x0000000180026fc0 | 0x00026fc0
`public: void __cdecl Conjunctions::SetRange(unsigned long,class WmiRangeNode * __ptr64) __ptr64` | 903 (0x387) | Exported Function | 0x0000000180027020 | 0x00027020
`public: void __cdecl PartitionSet::SetKeyIndex(unsigned long) __ptr64` | 896 (0x380) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl PartitionSet::SetPartition(unsigned long,class PartitionSet * __ptr64) __ptr64` | 902 (0x386) | Exported Function | 0x0000000180027000 | 0x00027000
`public: void __cdecl PartitionSet::SetRange(class WmiRangeNode * __ptr64) __ptr64` | 904 (0x388) | Exported Function | 0x0000000180027090 | 0x00027090
`public: virtual void __cdecl WmiUnsignedIntegerNode::Print(void) __ptr64` | 860 (0x35c) | Exported Function | 0x0000000180026b20 | 0x00026b20
`public: void __cdecl ProvAnalyser::``default constructor closure'(void) __ptr64` | 499 (0x1f3) | Exported Function | 0x0000000180014070 | 0x00014070
`public: virtual void __cdecl WmiOperatorEqualOrGreaterNode::Print(void) __ptr64` | 845 (0x34d) | Exported Function | 0x0000000180026450 | 0x00026450
`public: virtual void __cdecl WmiNullRangeNode::Print(void) __ptr64` | 843 (0x34b) | Exported Function | 0x00000001800263a0 | 0x000263a0
`public: virtual unsigned short * __ptr64 __cdecl ProvCounter64Type::GetStringValue(void)const __ptr64` | 712 (0x2c8) | Exported Function | 0x00000001800167c0 | 0x000167c0
`public: virtual unsigned short * __ptr64 __cdecl ProvCounterType::GetStringValue(void)const __ptr64` | 713 (0x2c9) | Exported Function | 0x00000001800168a0 | 0x000168a0
`public: virtual unsigned short * __ptr64 __cdecl ProvDateTimeType::GetStringValue(void)const __ptr64` | 714 (0x2ca) | Exported Function | 0x0000000180016970 | 0x00016970
`public: virtual unsigned short * __ptr64 __cdecl ProvDisplayStringType::GetStringValue(void)const __ptr64` | 715 (0x2cb) | Exported Function | 0x0000000180016980 | 0x00016980
`public: virtual unsigned short * __ptr64 __cdecl ProvEnumeratedType::GetStringValue(void)const __ptr64` | 716 (0x2cc) | Exported Function | 0x0000000180016a10 | 0x00016a10
`public: virtual unsigned short * __ptr64 __cdecl ProvFixedLengthDisplayStringType::GetStringValue(void)const __ptr64` | 717 (0x2cd) | Exported Function | 0x0000000180016ac0 | 0x00016ac0
`public: virtual unsigned short * __ptr64 __cdecl ProvFixedLengthPhysAddressType::GetStringValue(void)const __ptr64` | 718 (0x2ce) | Exported Function | 0x0000000180016b40 | 0x00016b40
`public: virtual unsigned short * __ptr64 __cdecl ProvGaugeType::GetStringValue(void)const __ptr64` | 719 (0x2cf) | Exported Function | 0x0000000180016d60 | 0x00016d60
`public: virtual unsigned short * __ptr64 __cdecl ProvIntegerType::GetStringValue(void)const __ptr64` | 720 (0x2d0) | Exported Function | 0x0000000180016e40 | 0x00016e40
`public: virtual unsigned short * __ptr64 __cdecl ProvIpAddressType::GetStringValue(void)const __ptr64` | 721 (0x2d1) | Exported Function | 0x0000000180016f20 | 0x00016f20
`public: virtual unsigned short * __ptr64 __cdecl ProvMacAddressType::GetStringValue(void)const __ptr64` | 722 (0x2d2) | Exported Function | 0x0000000180017320 | 0x00017320
`public: virtual unsigned short * __ptr64 __cdecl ProvNetworkAddressType::GetStringValue(void)const __ptr64` | 723 (0x2d3) | Exported Function | 0x0000000180016f20 | 0x00016f20
`public: virtual void __cdecl WmiOperatorEqualNode::Print(void) __ptr64` | 844 (0x34c) | Exported Function | 0x00000001800263f0 | 0x000263f0
`public: virtual unsigned short * __ptr64 __cdecl ProvNullType::GetStringValue(void)const __ptr64` | 724 (0x2d4) | Exported Function | 0x0000000180017460 | 0x00017460
`public: virtual unsigned short * __ptr64 __cdecl ProvOctetStringType::GetStringValue(void)const __ptr64` | 727 (0x2d7) | Exported Function | 0x0000000180017a30 | 0x00017a30
`public: virtual unsigned short * __ptr64 __cdecl ProvOpaqueType::GetStringValue(void)const __ptr64` | 728 (0x2d8) | Exported Function | 0x0000000180017b80 | 0x00017b80
`public: virtual unsigned short * __ptr64 __cdecl ProvOSIAddressType::GetStringValue(void)const __ptr64` | 725 (0x2d5) | Exported Function | 0x0000000180017490 | 0x00017490
`public: virtual unsigned short * __ptr64 __cdecl ProvPhysAddressType::GetStringValue(void)const __ptr64` | 729 (0x2d9) | Exported Function | 0x0000000180017da0 | 0x00017da0
`public: virtual unsigned short * __ptr64 __cdecl ProvRowStatusType::GetStringValue(void)const __ptr64` | 730 (0x2da) | Exported Function | 0x0000000180017fc0 | 0x00017fc0
`public: virtual unsigned short * __ptr64 __cdecl ProvTimeTicksType::GetStringValue(void)const __ptr64` | 731 (0x2db) | Exported Function | 0x00000001800168a0 | 0x000168a0
`public: virtual unsigned short * __ptr64 __cdecl ProvUDPAddressType::GetStringValue(void)const __ptr64` | 732 (0x2dc) | Exported Function | 0x0000000180017fd0 | 0x00017fd0
`public: virtual void __cdecl ProvEventObject::Complete(void) __ptr64` | 535 (0x217) | Exported Function | 0x0000000180005240 | 0x00005240
`public: virtual void __cdecl ProvEventObject::Process(void) __ptr64` | 863 (0x35f) | Exported Function | 0x0000000180005240 | 0x00005240
`public: virtual void __cdecl WmiAndNode::Print(void) __ptr64` | 840 (0x348) | Exported Function | 0x00000001800261d0 | 0x000261d0
`public: virtual void __cdecl WmiNotNode::Print(void) __ptr64` | 841 (0x349) | Exported Function | 0x00000001800262f0 | 0x000262f0
`public: virtual void __cdecl WmiNullNode::Print(void) __ptr64` | 842 (0x34a) | Exported Function | 0x00000001800263a0 | 0x000263a0
`public: virtual unsigned short * __ptr64 __cdecl ProvObjectIdentifierType::GetStringValue(void)const __ptr64` | 726 (0x2d6) | Exported Function | 0x0000000180017780 | 0x00017780
`public: void __cdecl ProvAnalyser::PutBack(class ProvLexicon const * __ptr64) __ptr64` | 868 (0x364) | Exported Function | 0x000000018001b430 | 0x0001b430
`public: void __cdecl ProvAnalyser::Set(unsigned short const * __ptr64) __ptr64` | 892 (0x37c) | Exported Function | 0x000000018001bae0 | 0x0001bae0
`public: void __cdecl ProvCounter64::SetValue(unsigned long,unsigned long) __ptr64` | 912 (0x390) | Exported Function | 0x000000018001d700 | 0x0001d700
`public: void __cdecl ProvPositiveRangedType::SetStatus(int const & __ptr64) __ptr64` | 907 (0x38b) | Exported Function | 0x000000018001bb80 | 0x0001bb80
`public: void __cdecl ProvPositiveRangeType::SetLowerBound(unsigned long const & __ptr64) __ptr64` | 899 (0x383) | Exported Function | 0x000000018001bb80 | 0x0001bb80
`public: void __cdecl ProvPositiveRangeType::SetUpperBound(unsigned long const & __ptr64) __ptr64` | 911 (0x38f) | Exported Function | 0x000000018001bbb0 | 0x0001bbb0
`public: void __cdecl ProvTimeTicks::SetValue(unsigned long) __ptr64` | 920 (0x398) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl ProvUInteger32::SetValue(unsigned long) __ptr64` | 921 (0x399) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl WmiAndNode::``default constructor closure'(void) __ptr64` | 509 (0x1fd) | Exported Function | 0x0000000180020870 | 0x00020870
`public: void __cdecl WmiNotNode::``default constructor closure'(void) __ptr64` | 510 (0x1fe) | Exported Function | 0x0000000180020890 | 0x00020890
`public: void __cdecl WmiOperatorEqualNode::``default constructor closure'(void) __ptr64` | 511 (0x1ff) | Exported Function | 0x00000001800208a0 | 0x000208a0
`public: void __cdecl WmiOperatorEqualOrGreaterNode::``default constructor closure'(void) __ptr64` | 512 (0x200) | Exported Function | 0x00000001800208b0 | 0x000208b0
`public: void __cdecl WmiOperatorEqualOrLessNode::``default constructor closure'(void) __ptr64` | 513 (0x201) | Exported Function | 0x00000001800208c0 | 0x000208c0
`public: void __cdecl WmiOperatorGreaterNode::``default constructor closure'(void) __ptr64` | 514 (0x202) | Exported Function | 0x00000001800208d0 | 0x000208d0
`public: void __cdecl WmiOperatorIsANode::``default constructor closure'(void) __ptr64` | 515 (0x203) | Exported Function | 0x00000001800208e0 | 0x000208e0
`public: void __cdecl ProvPositiveRangedType::``default constructor closure'(void) __ptr64` | 508 (0x1fc) | Exported Function | 0x0000000180014100 | 0x00014100
`public: void __cdecl WmiOperatorLessNode::``default constructor closure'(void) __ptr64` | 516 (0x204) | Exported Function | 0x00000001800208f0 | 0x000208f0
`public: void __cdecl WmiOperatorNotEqualNode::``default constructor closure'(void) __ptr64` | 518 (0x206) | Exported Function | 0x0000000180020910 | 0x00020910
`public: void __cdecl WmiOperatorNotIsANode::``default constructor closure'(void) __ptr64` | 519 (0x207) | Exported Function | 0x0000000180020920 | 0x00020920
`public: void __cdecl WmiOperatorNotLikeNode::``default constructor closure'(void) __ptr64` | 520 (0x208) | Exported Function | 0x0000000180020930 | 0x00020930
`public: void __cdecl WmiOrNode::``default constructor closure'(void) __ptr64` | 521 (0x209) | Exported Function | 0x0000000180020940 | 0x00020940
`public: void __cdecl WmiTreeNode::``default constructor closure'(void) __ptr64` | 522 (0x20a) | Exported Function | 0x0000000180020960 | 0x00020960
`public: void __cdecl WmiTreeNode::GetData(void * __ptr64 * __ptr64) __ptr64` | 664 (0x298) | Exported Function | 0x0000000180021c90 | 0x00021c90
`public: void __cdecl WmiTreeNode::GetLeft(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 677 (0x2a5) | Exported Function | 0x00000001800232d0 | 0x000232d0
`public: void __cdecl WmiTreeNode::GetParent(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 687 (0x2af) | Exported Function | 0x0000000180025270 | 0x00025270
`public: void __cdecl WmiTreeNode::GetRight(class WmiTreeNode * __ptr64 * __ptr64 & __ptr64) __ptr64` | 708 (0x2c4) | Exported Function | 0x0000000180025c40 | 0x00025c40
`public: void __cdecl WmiTreeNode::SetType(unsigned long) __ptr64` | 909 (0x38d) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`unsigned int __cdecl HashKey<unsigned short * __ptr64>(unsigned short * __ptr64)` | 2 (0x2) | Exported Function | 0x000000018000af10 | 0x0000af10
`unsigned short * __ptr64 __cdecl DbcsToUnicodeString(char const * __ptr64)` | 605 (0x25d) | Exported Function | 0x0000000180015620 | 0x00015620
`public: void __cdecl WmiOperatorLikeNode::``default constructor closure'(void) __ptr64` | 517 (0x205) | Exported Function | 0x0000000180020900 | 0x00020900
`public: void __cdecl ProvPhysAddressType::``default constructor closure'(void) __ptr64` | 507 (0x1fb) | Exported Function | 0x00000001800140f0 | 0x000140f0
`public: void __cdecl ProvOpaqueType::``default constructor closure'(void) __ptr64` | 506 (0x1fa) | Exported Function | 0x00000001800140e0 | 0x000140e0
`public: void __cdecl ProvOpaque::SetValue(unsigned char const * __ptr64,unsigned long) __ptr64` | 919 (0x397) | Exported Function | 0x000000018001bbc0 | 0x0001bbc0
`public: void __cdecl ProvCounter64Type::GetValue(unsigned long & __ptr64,unsigned long & __ptr64)const __ptr64` | 739 (0x2e3) | Exported Function | 0x0000000180018920 | 0x00018920
`public: void __cdecl ProvCounter::SetValue(unsigned long) __ptr64` | 913 (0x391) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl ProvDebugLog::Write(unsigned short const * __ptr64,...) __ptr64` | 956 (0x3bc) | Exported Function | 0x000000018000a7f0 | 0x0000a7f0
`public: void __cdecl ProvDebugLog::WriteA(char const * __ptr64,...) __ptr64` | 957 (0x3bd) | Exported Function | 0x000000018000a8e0 | 0x0000a8e0
`public: void __cdecl ProvDebugLog::WriteFileAndLine(char const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 958 (0x3be) | Exported Function | 0x000000018000a980 | 0x0000a980
`public: void __cdecl ProvDebugLog::WriteFileAndLine(unsigned short const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 959 (0x3bf) | Exported Function | 0x000000018000aaa0 | 0x0000aaa0
`public: void __cdecl ProvDebugLog::WriteFileAndLineA(char const * __ptr64,unsigned long,char const * __ptr64,...) __ptr64` | 960 (0x3c0) | Exported Function | 0x000000018000abc0 | 0x0000abc0
`public: void __cdecl ProvDebugLog::WriteFileAndLineW(unsigned short const * __ptr64,unsigned long,unsigned short const * __ptr64,...) __ptr64` | 961 (0x3c1) | Exported Function | 0x000000018000aca0 | 0x0000aca0
`public: void __cdecl ProvDebugLog::WriteW(unsigned short const * __ptr64,...) __ptr64` | 962 (0x3c2) | Exported Function | 0x000000018000a7f0 | 0x0000a7f0
`public: void __cdecl ProvDisplayStringType::``default constructor closure'(void) __ptr64` | 500 (0x1f4) | Exported Function | 0x0000000180014080 | 0x00014080
`public: void __cdecl ProvEventObject::``default constructor closure'(void) __ptr64` | 501 (0x1f5) | Exported Function | 0x000000018000a4f0 | 0x0000a4f0
`public: void __cdecl ProvEventObject::Clear(void) __ptr64` | 528 (0x210) | Exported Function | 0x000000018000ae60 | 0x0000ae60
`public: void __cdecl ProvEventObject::Set(void) __ptr64` | 893 (0x37d) | Exported Function | 0x000000018000ae90 | 0x0000ae90
`public: void __cdecl ProvGauge::SetValue(unsigned long) __ptr64` | 914 (0x392) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl ProvGaugeType::``default constructor closure'(void) __ptr64` | 502 (0x1f6) | Exported Function | 0x0000000180014090 | 0x00014090
`public: void __cdecl ProvInstanceType::``default constructor closure'(void) __ptr64` | 503 (0x1f7) | Exported Function | 0x00000001800140a0 | 0x000140a0
`public: void __cdecl ProvInstanceType::SetNull(int) __ptr64` | 900 (0x384) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl ProvInstanceType::SetStatus(int) __ptr64` | 906 (0x38a) | Exported Function | 0x000000018001bba0 | 0x0001bba0
`public: void __cdecl ProvInteger::SetValue(long) __ptr64` | 915 (0x393) | Exported Function | 0x000000018001bb90 | 0x0001bb90
`public: void __cdecl ProvIntegerType::``default constructor closure'(void) __ptr64` | 504 (0x1f8) | Exported Function | 0x00000001800140c0 | 0x000140c0
`public: void __cdecl ProvIpAddress::SetValue(unsigned long) __ptr64` | 916 (0x394) | Exported Function | 0x000000018001d710 | 0x0001d710
`public: void __cdecl ProvLexicon::SetToken(enum ProvLexicon::LexiconToken) __ptr64` | 908 (0x38c) | Exported Function | 0x000000018001bba0 | 0x0001bba0
`public: void __cdecl ProvNegativeRangeType::SetLowerBound(long const & __ptr64) __ptr64` | 898 (0x382) | Exported Function | 0x000000018001bb80 | 0x0001bb80
`public: void __cdecl ProvNegativeRangeType::SetUpperBound(long const & __ptr64) __ptr64` | 910 (0x38e) | Exported Function | 0x000000018001bbb0 | 0x0001bbb0
`public: void __cdecl ProvObjectIdentifier::SetValue(unsigned long const * __ptr64,unsigned long) __ptr64` | 917 (0x395) | Exported Function | 0x000000018001d730 | 0x0001d730
`public: void __cdecl ProvOctetString::SetValue(unsigned char const * __ptr64,unsigned long) __ptr64` | 918 (0x396) | Exported Function | 0x000000018001d7e0 | 0x0001d7e0
`public: void __cdecl ProvOctetStringType::``default constructor closure'(void) __ptr64` | 505 (0x1f9) | Exported Function | 0x00000001800140d0 | 0x000140d0
`public: virtual unsigned short * __ptr64 __cdecl ProvBitStringType::GetStringValue(void)const __ptr64` | 711 (0x2c7) | Exported Function | 0x00000001800167b0 | 0x000167b0
`public: class ProvLexicon * __ptr64 __cdecl ProvAnalyser::Get(int,int,int) __ptr64` | 655 (0x28f) | Exported Function | 0x0000000180015f70 | 0x00015f70
`public: virtual int __cdecl ProvNullType::IsProvV2CType(void)const __ptr64` | 796 (0x31c) | Exported Function | 0x0000000180014660 | 0x00014660
`public: virtual int __cdecl ProvInstanceType::IsProvV2CType(void)const __ptr64` | 795 (0x31b) | Exported Function | 0x0000000180018e80 | 0x00018e80
`public: virtual __cdecl WmiOperatorNotLikeNode::~WmiOperatorNotLikeNode(void) __ptr64` | 291 (0x123) | Exported Function | 0x000000018001f600 | 0x0001f600
`public: virtual __cdecl WmiOrNode::~WmiOrNode(void) __ptr64` | 292 (0x124) | Exported Function | 0x000000018001f680 | 0x0001f680
`public: virtual __cdecl WmiRangeNode::~WmiRangeNode(void) __ptr64` | 293 (0x125) | Exported Function | 0x000000018001f700 | 0x0001f700
`public: virtual __cdecl WmiSignedIntegerNode::~WmiSignedIntegerNode(void) __ptr64` | 294 (0x126) | Exported Function | 0x000000018001f0d0 | 0x0001f0d0
`public: virtual __cdecl WmiSignedIntegerRangeNode::~WmiSignedIntegerRangeNode(void) __ptr64` | 295 (0x127) | Exported Function | 0x000000018001f760 | 0x0001f760
`public: virtual __cdecl WmiStringNode::~WmiStringNode(void) __ptr64` | 296 (0x128) | Exported Function | 0x0000000180003610 | 0x00003610
`public: virtual __cdecl WmiStringRangeNode::~WmiStringRangeNode(void) __ptr64` | 297 (0x129) | Exported Function | 0x0000000180003280 | 0x00003280
`public: virtual __cdecl WmiTreeNode::~WmiTreeNode(void) __ptr64` | 298 (0x12a) | Exported Function | 0x000000018001f790 | 0x0001f790
`public: virtual __cdecl WmiTreeNodeIterator::~WmiTreeNodeIterator(void) __ptr64` | 299 (0x12b) | Exported Function | 0x000000018001f7b0 | 0x0001f7b0
`public: virtual __cdecl WmiUnsignedIntegerNode::~WmiUnsignedIntegerNode(void) __ptr64` | 300 (0x12c) | Exported Function | 0x0000000180002d50 | 0x00002d50
`public: virtual __cdecl WmiUnsignedIntegerRangeNode::~WmiUnsignedIntegerRangeNode(void) __ptr64` | 301 (0x12d) | Exported Function | 0x0000000180002e80 | 0x00002e80
`public: virtual __cdecl WmiValueNode::~WmiValueNode(void) __ptr64` | 302 (0x12e) | Exported Function | 0x000000018001f7d0 | 0x0001f7d0
`public: virtual __cdecl WmiOperatorNotIsANode::~WmiOperatorNotIsANode(void) __ptr64` | 290 (0x122) | Exported Function | 0x000000018001f580 | 0x0001f580
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvBitStringType::Copy(void)const __ptr64` | 537 (0x219) | Exported Function | 0x0000000180014980 | 0x00014980
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvCounterType::Copy(void)const __ptr64` | 541 (0x21d) | Exported Function | 0x0000000180014a60 | 0x00014a60
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvDateTimeType::Copy(void)const __ptr64` | 542 (0x21e) | Exported Function | 0x0000000180014ab0 | 0x00014ab0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvDisplayStringType::Copy(void)const __ptr64` | 543 (0x21f) | Exported Function | 0x0000000180014b00 | 0x00014b00
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvEnumeratedType::Copy(void)const __ptr64` | 544 (0x220) | Exported Function | 0x0000000180014b50 | 0x00014b50
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthDisplayStringType::Copy(void)const __ptr64` | 545 (0x221) | Exported Function | 0x0000000180014ba0 | 0x00014ba0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthOctetStringType::Copy(void)const __ptr64` | 546 (0x222) | Exported Function | 0x0000000180014bf0 | 0x00014bf0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthOpaqueType::Copy(void)const __ptr64` | 547 (0x223) | Exported Function | 0x0000000180014c40 | 0x00014c40
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvFixedLengthPhysAddressType::Copy(void)const __ptr64` | 548 (0x224) | Exported Function | 0x0000000180014c90 | 0x00014c90
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvGaugeType::Copy(void)const __ptr64` | 550 (0x226) | Exported Function | 0x0000000180014ce0 | 0x00014ce0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvIntegerType::Copy(void)const __ptr64` | 552 (0x228) | Exported Function | 0x0000000180014d30 | 0x00014d30
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvIpAddressType::Copy(void)const __ptr64` | 554 (0x22a) | Exported Function | 0x0000000180014d80 | 0x00014d80
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvMacAddressType::Copy(void)const __ptr64` | 555 (0x22b) | Exported Function | 0x0000000180014dd0 | 0x00014dd0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvCounter64Type::Copy(void)const __ptr64` | 539 (0x21b) | Exported Function | 0x00000001800149d0 | 0x000149d0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvNetworkAddressType::Copy(void)const __ptr64` | 557 (0x22d) | Exported Function | 0x0000000180014e80 | 0x00014e80
`public: virtual __cdecl WmiOperatorNotEqualNode::~WmiOperatorNotEqualNode(void) __ptr64` | 289 (0x121) | Exported Function | 0x000000018001f500 | 0x0001f500
`public: virtual __cdecl WmiOperatorLikeNode::~WmiOperatorLikeNode(void) __ptr64` | 287 (0x11f) | Exported Function | 0x000000018001f440 | 0x0001f440
`public: virtual __cdecl ProvOctetString::~ProvOctetString(void) __ptr64` | 263 (0x107) | Exported Function | 0x000000018001c640 | 0x0001c640
`public: virtual __cdecl ProvOctetStringType::~ProvOctetStringType(void) __ptr64` | 264 (0x108) | Exported Function | 0x00000001800115c0 | 0x000115c0
`public: virtual __cdecl ProvOpaque::~ProvOpaque(void) __ptr64` | 265 (0x109) | Exported Function | 0x0000000180011660 | 0x00011660
`public: virtual __cdecl ProvOpaqueType::~ProvOpaqueType(void) __ptr64` | 266 (0x10a) | Exported Function | 0x00000001800116c0 | 0x000116c0
`public: virtual __cdecl ProvOSIAddressType::~ProvOSIAddressType(void) __ptr64` | 260 (0x104) | Exported Function | 0x0000000180011510 | 0x00011510
`public: virtual __cdecl ProvPhysAddressType::~ProvPhysAddressType(void) __ptr64` | 267 (0x10b) | Exported Function | 0x0000000180011760 | 0x00011760
`public: virtual __cdecl ProvPositiveRangedType::operator void * __ptr64(void) __ptr64` | 395 (0x18b) | Exported Function | 0x0000000180012510 | 0x00012510
`public: virtual __cdecl ProvPositiveRangedType::~ProvPositiveRangedType(void) __ptr64` | 269 (0x10d) | Exported Function | 0x00000001800117d0 | 0x000117d0
`public: virtual __cdecl ProvPositiveRangeType::~ProvPositiveRangeType(void) __ptr64` | 268 (0x10c) | Exported Function | 0x00000001800117b0 | 0x000117b0
`public: virtual __cdecl ProvRowStatusType::~ProvRowStatusType(void) __ptr64` | 270 (0x10e) | Exported Function | 0x00000001800118b0 | 0x000118b0
`public: virtual __cdecl ProvTimeTicks::~ProvTimeTicks(void) __ptr64` | 271 (0x10f) | Exported Function | 0x0000000180011900 | 0x00011900
`public: virtual __cdecl ProvTimeTicksType::~ProvTimeTicksType(void) __ptr64` | 272 (0x110) | Exported Function | 0x0000000180011940 | 0x00011940
`public: virtual __cdecl WmiOperatorNode::~WmiOperatorNode(void) __ptr64` | 288 (0x120) | Exported Function | 0x000000018001f4c0 | 0x0001f4c0
`public: virtual __cdecl ProvUDPAddressType::~ProvUDPAddressType(void) __ptr64` | 273 (0x111) | Exported Function | 0x00000001800119c0 | 0x000119c0
`public: virtual __cdecl ProvValue::~ProvValue(void) __ptr64` | 275 (0x113) | Exported Function | 0x0000000180011a50 | 0x00011a50
`public: virtual __cdecl QueryPreprocessor::~QueryPreprocessor(void) __ptr64` | 276 (0x114) | Exported Function | 0x0000000180005220 | 0x00005220
`public: virtual __cdecl WmiAndNode::~WmiAndNode(void) __ptr64` | 277 (0x115) | Exported Function | 0x000000018001eff0 | 0x0001eff0
`public: virtual __cdecl WmiNotNode::~WmiNotNode(void) __ptr64` | 278 (0x116) | Exported Function | 0x000000018001f070 | 0x0001f070
`public: virtual __cdecl WmiNullNode::~WmiNullNode(void) __ptr64` | 279 (0x117) | Exported Function | 0x000000018001f0d0 | 0x0001f0d0
`public: virtual __cdecl WmiNullRangeNode::~WmiNullRangeNode(void) __ptr64` | 280 (0x118) | Exported Function | 0x000000018001f100 | 0x0001f100
`public: virtual __cdecl WmiOperatorEqualNode::~WmiOperatorEqualNode(void) __ptr64` | 281 (0x119) | Exported Function | 0x000000018001f140 | 0x0001f140
`public: virtual __cdecl WmiOperatorEqualOrGreaterNode::~WmiOperatorEqualOrGreaterNode(void) __ptr64` | 282 (0x11a) | Exported Function | 0x000000018001f1c0 | 0x0001f1c0
`public: virtual __cdecl WmiOperatorEqualOrLessNode::~WmiOperatorEqualOrLessNode(void) __ptr64` | 283 (0x11b) | Exported Function | 0x000000018001f240 | 0x0001f240
`public: virtual __cdecl WmiOperatorGreaterNode::~WmiOperatorGreaterNode(void) __ptr64` | 284 (0x11c) | Exported Function | 0x000000018001f2c0 | 0x0001f2c0
`public: virtual __cdecl WmiOperatorIsANode::~WmiOperatorIsANode(void) __ptr64` | 285 (0x11d) | Exported Function | 0x000000018001f340 | 0x0001f340
`public: virtual __cdecl WmiOperatorLessNode::~WmiOperatorLessNode(void) __ptr64` | 286 (0x11e) | Exported Function | 0x000000018001f3c0 | 0x0001f3c0
`public: virtual __cdecl ProvUInteger32::~ProvUInteger32(void) __ptr64` | 274 (0x112) | Exported Function | 0x0000000180011a10 | 0x00011a10
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvNullType::Copy(void)const __ptr64` | 559 (0x22f) | Exported Function | 0x0000000180014f30 | 0x00014f30
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvObjectIdentifierType::Copy(void)const __ptr64` | 562 (0x232) | Exported Function | 0x0000000180014fd0 | 0x00014fd0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOctetStringType::Copy(void)const __ptr64` | 564 (0x234) | Exported Function | 0x0000000180015020 | 0x00015020
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNullNode::Copy(void) __ptr64` | 576 (0x240) | Exported Function | 0x0000000180020ed0 | 0x00020ed0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNullRangeNode::Copy(void) __ptr64` | 577 (0x241) | Exported Function | 0x0000000180020f40 | 0x00020f40
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualNode::Copy(void) __ptr64` | 578 (0x242) | Exported Function | 0x0000000180003710 | 0x00003710
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::Copy(void) __ptr64` | 579 (0x243) | Exported Function | 0x0000000180020fa0 | 0x00020fa0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorEqualOrLessNode::Copy(void) __ptr64` | 580 (0x244) | Exported Function | 0x0000000180021050 | 0x00021050
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorGreaterNode::Copy(void) __ptr64` | 581 (0x245) | Exported Function | 0x0000000180021100 | 0x00021100
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorIsANode::Copy(void) __ptr64` | 582 (0x246) | Exported Function | 0x00000001800211b0 | 0x000211b0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorLessNode::Copy(void) __ptr64` | 583 (0x247) | Exported Function | 0x0000000180021260 | 0x00021260
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorLikeNode::Copy(void) __ptr64` | 584 (0x248) | Exported Function | 0x0000000180021310 | 0x00021310
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotEqualNode::Copy(void) __ptr64` | 585 (0x249) | Exported Function | 0x00000001800213c0 | 0x000213c0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotIsANode::Copy(void) __ptr64` | 586 (0x24a) | Exported Function | 0x0000000180021470 | 0x00021470
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOperatorNotLikeNode::Copy(void) __ptr64` | 587 (0x24b) | Exported Function | 0x0000000180021520 | 0x00021520
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiNotNode::Copy(void) __ptr64` | 575 (0x23f) | Exported Function | 0x0000000180020e20 | 0x00020e20
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiOrNode::Copy(void) __ptr64` | 588 (0x24c) | Exported Function | 0x00000001800215d0 | 0x000215d0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiSignedIntegerRangeNode::Copy(void) __ptr64` | 590 (0x24e) | Exported Function | 0x0000000180021760 | 0x00021760
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiStringNode::Copy(void) __ptr64` | 591 (0x24f) | Exported Function | 0x0000000180003400 | 0x00003400
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiStringRangeNode::Copy(void) __ptr64` | 592 (0x250) | Exported Function | 0x0000000180003dc0 | 0x00003dc0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::Copy(void) __ptr64` | 593 (0x251) | Exported Function | 0x0000000180028560 | 0x00028560
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiTreeNode::CopyNode(void) __ptr64` | 597 (0x255) | Exported Function | 0x0000000180028630 | 0x00028630
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiUnsignedIntegerNode::Copy(void) __ptr64` | 595 (0x253) | Exported Function | 0x0000000180002bd0 | 0x00002bd0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiUnsignedIntegerRangeNode::Copy(void) __ptr64` | 596 (0x254) | Exported Function | 0x0000000180002ff0 | 0x00002ff0
`public: virtual class WmiTreeNodeIterator * __ptr64 __cdecl WmiTreeNodeIterator::Copy(void) __ptr64` | 594 (0x252) | Exported Function | 0x00000001800217f0 | 0x000217f0
`public: virtual int __cdecl ProvCounter64Type::IsProvV1Type(void)const __ptr64` | 793 (0x319) | Exported Function | 0x0000000180014660 | 0x00014660
`public: virtual int __cdecl ProvEventObject::Wait(void) __ptr64` | 955 (0x3bb) | Exported Function | 0x000000018000aeb0 | 0x0000aeb0
`public: virtual int __cdecl ProvInstanceType::IsNull(void)const __ptr64` | 791 (0x317) | Exported Function | 0x00000001800162b0 | 0x000162b0
`public: virtual int __cdecl ProvInstanceType::IsProvV1Type(void)const __ptr64` | 794 (0x31a) | Exported Function | 0x0000000180018e80 | 0x00018e80
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiSignedIntegerNode::Copy(void) __ptr64` | 589 (0x24d) | Exported Function | 0x00000001800216f0 | 0x000216f0
`public: virtual class WmiTreeNode * __ptr64 __cdecl WmiAndNode::Copy(void) __ptr64` | 574 (0x23e) | Exported Function | 0x0000000180003300 | 0x00003300
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotLikeNode::GetRange(void) __ptr64` | 705 (0x2c1) | Exported Function | 0x0000000180025910 | 0x00025910
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotIsANode::GetRange(void) __ptr64` | 704 (0x2c0) | Exported Function | 0x0000000180025910 | 0x00025910
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOpaqueType::Copy(void)const __ptr64` | 566 (0x236) | Exported Function | 0x00000001800150d0 | 0x000150d0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvOSIAddressType::Copy(void)const __ptr64` | 560 (0x230) | Exported Function | 0x0000000180014f80 | 0x00014f80
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvPhysAddressType::Copy(void)const __ptr64` | 567 (0x237) | Exported Function | 0x0000000180015120 | 0x00015120
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvRowStatusType::Copy(void)const __ptr64` | 569 (0x239) | Exported Function | 0x00000001800151d0 | 0x000151d0
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvTimeTicksType::Copy(void)const __ptr64` | 571 (0x23b) | Exported Function | 0x0000000180015220 | 0x00015220
`public: virtual class ProvInstanceType * __ptr64 __cdecl ProvUDPAddressType::Copy(void)const __ptr64` | 572 (0x23c) | Exported Function | 0x0000000180015270 | 0x00015270
`public: virtual class ProvNegativeRangeType * __ptr64 __cdecl ProvNegativeRangeType::Copy(void) __ptr64` | 556 (0x22c) | Exported Function | 0x0000000180014e20 | 0x00014e20
`public: virtual class ProvPositiveRangeType * __ptr64 __cdecl ProvPositiveRangeType::Copy(void) __ptr64` | 568 (0x238) | Exported Function | 0x0000000180015170 | 0x00015170
`public: virtual class ProvValue * __ptr64 __cdecl ProvCounter64::Copy(void)const __ptr64` | 538 (0x21a) | Exported Function | 0x000000018001c9b0 | 0x0001c9b0
`public: virtual class ProvValue * __ptr64 __cdecl ProvCounter::Copy(void)const __ptr64` | 540 (0x21c) | Exported Function | 0x000000018001ca30 | 0x0001ca30
`public: virtual class ProvValue * __ptr64 __cdecl ProvGauge::Copy(void)const __ptr64` | 549 (0x225) | Exported Function | 0x000000018001caa0 | 0x0001caa0
`public: virtual class ProvValue * __ptr64 __cdecl ProvInteger::Copy(void)const __ptr64` | 551 (0x227) | Exported Function | 0x000000018001cb10 | 0x0001cb10
`public: virtual class ProvValue * __ptr64 __cdecl ProvIpAddress::Copy(void)const __ptr64` | 553 (0x229) | Exported Function | 0x000000018001cb80 | 0x0001cb80
`public: virtual class ProvValue * __ptr64 __cdecl ProvNull::Copy(void)const __ptr64` | 558 (0x22e) | Exported Function | 0x0000000180014ed0 | 0x00014ed0
`public: virtual class ProvValue * __ptr64 __cdecl ProvObjectIdentifier::Copy(void)const __ptr64` | 561 (0x231) | Exported Function | 0x000000018001cc00 | 0x0001cc00
`public: virtual class ProvValue * __ptr64 __cdecl ProvOctetString::Copy(void)const __ptr64` | 563 (0x233) | Exported Function | 0x000000018001cc60 | 0x0001cc60
`public: virtual class ProvValue * __ptr64 __cdecl ProvOpaque::Copy(void)const __ptr64` | 565 (0x235) | Exported Function | 0x0000000180015070 | 0x00015070
`public: virtual class ProvValue * __ptr64 __cdecl ProvTimeTicks::Copy(void)const __ptr64` | 570 (0x23a) | Exported Function | 0x000000018001ccc0 | 0x0001ccc0
`public: virtual class ProvValue * __ptr64 __cdecl ProvUInteger32::Copy(void)const __ptr64` | 573 (0x23d) | Exported Function | 0x000000018001cd30 | 0x0001cd30
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualNode::GetRange(void) __ptr64` | 696 (0x2b8) | Exported Function | 0x00000001800037e0 | 0x000037e0
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualOrGreaterNode::GetRange(void) __ptr64` | 697 (0x2b9) | Exported Function | 0x00000001800252a0 | 0x000252a0
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorEqualOrLessNode::GetRange(void) __ptr64` | 698 (0x2ba) | Exported Function | 0x00000001800254d0 | 0x000254d0
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorGreaterNode::GetRange(void) __ptr64` | 699 (0x2bb) | Exported Function | 0x00000001800256f0 | 0x000256f0
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorIsANode::GetRange(void) __ptr64` | 700 (0x2bc) | Exported Function | 0x0000000180025910 | 0x00025910
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorLessNode::GetRange(void) __ptr64` | 701 (0x2bd) | Exported Function | 0x0000000180025a10 | 0x00025a10
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorLikeNode::GetRange(void) __ptr64` | 702 (0x2be) | Exported Function | 0x0000000180025910 | 0x00025910
`public: virtual class WmiRangeNode * __ptr64 __cdecl WmiOperatorNotEqualNode::GetRange(void) __ptr64` | 703 (0x2bf) | Exported Function | 0x0000000180014660 | 0x00014660
`public: virtual int __cdecl ProvInstanceType::IsValid(void)const __ptr64` | 797 (0x31d) | Exported Function | 0x0000000180018700 | 0x00018700
`unsigned short * __ptr64 __cdecl UnicodeStringAppend(unsigned short const * __ptr64,unsigned short const * __ptr64)` | 949 (0x3b5) | Exported Function | 0x000000018001bda0 | 0x0001bda0
`public: class ProvLexicon & __ptr64 __cdecl ProvLexicon::operator=(class ProvLexicon const & __ptr64) __ptr64` | 332 (0x14c) | Exported Function | 0x0000000180011f90 | 0x00011f90
`public: class ProvIntegerType & __ptr64 __cdecl ProvIntegerType::operator=(class ProvIntegerType const & __ptr64) __ptr64` | 329 (0x149) | Exported Function | 0x0000000180011e80 | 0x00011e80
`protected: int __cdecl ProvIntegerType::Parse(unsigned short const * __ptr64) __ptr64` | 825 (0x339) | Exported Function | 0x0000000180019ad0 | 0x00019ad0
`protected: int __cdecl ProvIpAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 826 (0x33a) | Exported Function | 0x0000000180019b90 | 0x00019b90
`protected: int __cdecl ProvMacAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 827 (0x33b) | Exported Function | 0x0000000180019f50 | 0x00019f50
`protected: int __cdecl ProvNetworkAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 828 (0x33c) | Exported Function | 0x000000018001a080 | 0x0001a080
`protected: int __cdecl ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const & __ptr64)const __ptr64` | 635 (0x27b) | Exported Function | 0x000000018001cff0 | 0x0001cff0
`protected: int __cdecl ProvObjectIdentifierType::Parse(unsigned short const * __ptr64) __ptr64` | 830 (0x33e) | Exported Function | 0x000000018001a6c0 | 0x0001a6c0
`protected: int __cdecl ProvOctetStringType::Parse(unsigned short const * __ptr64) __ptr64` | 831 (0x33f) | Exported Function | 0x000000018001a8c0 | 0x0001a8c0
`protected: int __cdecl ProvOpaqueType::Parse(unsigned short const * __ptr64) __ptr64` | 832 (0x340) | Exported Function | 0x000000018001aab0 | 0x0001aab0
`protected: int __cdecl ProvOSIAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 829 (0x33d) | Exported Function | 0x000000018001a460 | 0x0001a460
`protected: int __cdecl ProvPhysAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 833 (0x341) | Exported Function | 0x000000018001aca0 | 0x0001aca0
`protected: int __cdecl ProvPositiveRangedType::Parse(unsigned short const * __ptr64) __ptr64` | 834 (0x342) | Exported Function | 0x000000018001ae60 | 0x0001ae60
`protected: int __cdecl ProvPositiveRangedType::RangeDef(void) __ptr64` | 871 (0x367) | Exported Function | 0x000000018001b570 | 0x0001b570
`protected: int __cdecl ProvGaugeType::Parse(unsigned short const * __ptr64) __ptr64` | 824 (0x338) | Exported Function | 0x0000000180019a10 | 0x00019a10
`protected: int __cdecl ProvPositiveRangedType::RecursiveDef(void) __ptr64` | 875 (0x36b) | Exported Function | 0x000000018001b9b0 | 0x0001b9b0
`protected: int __cdecl ProvUDPAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 836 (0x344) | Exported Function | 0x000000018001aeb0 | 0x0001aeb0
`protected: int __cdecl QueryPreprocessor::Evaluate(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION & __ptr64,class WmiTreeNode * __ptr64 * __ptr64) __ptr64` | 650 (0x28a) | Exported Function | 0x0000000180021a90 | 0x00021a90
`protected: int __cdecl QueryPreprocessor::RecursiveEvaluate(void * __ptr64,struct SQL_LEVEL_1_RPN_EXPRESSION & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64 * __ptr64,int & __ptr64) __ptr64` | 877 (0x36d) | Exported Function | 0x00000001800039e0 | 0x000039e0
`protected: virtual class ProvLexicon * __ptr64 __cdecl ProvAnalyser::CreateLexicon(void) __ptr64` | 601 (0x259) | Exported Function | 0x00000001800152c0 | 0x000152c0
`protected: virtual class WmiRangeNode * __ptr64 __cdecl QueryPreprocessor::AllocInfiniteRangeNode(void * __ptr64,unsigned short * __ptr64) __ptr64` | 523 (0x20b) | Exported Function | 0x0000000180014660 | 0x00014660
`protected: virtual class WmiTreeNode * __ptr64 __cdecl QueryPreprocessor::AllocTypeNode(void * __ptr64,unsigned short * __ptr64,struct tagVARIANT & __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,class WmiTreeNode * __ptr64) __ptr64` | 524 (0x20c) | Exported Function | 0x00000001800209d0 | 0x000209d0
`protected: virtual enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::InvariantEvaluate(void * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 784 (0x310) | Exported Function | 0x0000000180025f40 | 0x00025f40
`protected: virtual int __cdecl ProvAnalyser::Analyse(class ProvLexicon * __ptr64,unsigned long & __ptr64,unsigned short,unsigned short const * __ptr64,unsigned long & __ptr64,int,int,int) __ptr64` | 525 (0x20d) | Exported Function | 0x0000000180014660 | 0x00014660
`protected: virtual int __cdecl ProvCounter64::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 617 (0x269) | Exported Function | 0x000000018001ce60 | 0x0001ce60
`protected: virtual int __cdecl ProvCounter64Type::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 619 (0x26b) | Exported Function | 0x0000000180015ac0 | 0x00015ac0
`protected: virtual int __cdecl ProvCounter::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 620 (0x26c) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`protected: virtual int __cdecl ProvCounterType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 622 (0x26e) | Exported Function | 0x0000000180015b70 | 0x00015b70
`protected: int __cdecl ProvTimeTicksType::Parse(unsigned short const * __ptr64) __ptr64` | 835 (0x343) | Exported Function | 0x0000000180019720 | 0x00019720
`protected: virtual int __cdecl ProvGauge::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 623 (0x26f) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`protected: int __cdecl ProvFixedLengthPhysAddressType::Parse(unsigned short const * __ptr64) __ptr64` | 823 (0x337) | Exported Function | 0x0000000180019850 | 0x00019850
`protected: int __cdecl ProvCounter64Type::Parse(unsigned short const * __ptr64) __ptr64` | 819 (0x333) | Exported Function | 0x00000001800193d0 | 0x000193d0
`protected: class ProvLexicon * __ptr64 __cdecl ProvPositiveRangedType::Get(void) __ptr64` | 659 (0x293) | Exported Function | 0x0000000180016160 | 0x00016160
`protected: class ProvLexicon * __ptr64 __cdecl ProvPositiveRangedType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 813 (0x32d) | Exported Function | 0x00000001800190d0 | 0x000190d0
`protected: enum ProvObjectIdentifier::Comparison __cdecl ProvObjectIdentifier::Compare(class ProvObjectIdentifier const & __ptr64,class ProvObjectIdentifier const & __ptr64)const __ptr64` | 532 (0x214) | Exported Function | 0x000000018001c940 | 0x0001c940
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::DisjunctiveNormalForm(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 614 (0x266) | Exported Function | 0x0000000180021a50 | 0x00021a50
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveDisjunctiveNormalForm(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 876 (0x36c) | Exported Function | 0x0000000180003fb0 | 0x00003fb0
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveRemoveInvariants(void * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 881 (0x371) | Exported Function | 0x0000000180004390 | 0x00004390
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RecursiveRemoveNonOverlappingRanges(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 882 (0x372) | Exported Function | 0x0000000180004240 | 0x00004240
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RemoveInvariants(void * __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 885 (0x375) | Exported Function | 0x0000000180026ea0 | 0x00026ea0
`protected: enum QueryPreprocessor::QuadState __cdecl QueryPreprocessor::RemoveNonOverlappingRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 886 (0x376) | Exported Function | 0x0000000180026f20 | 0x00026f20
`protected: enum WmiTriState __cdecl QueryPreprocessor::ConvertToRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 536 (0x218) | Exported Function | 0x0000000180020e10 | 0x00020e10
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreateDisjunctionContainer(void * __ptr64,class WmiTreeNode * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,class Disjunctions * __ptr64 & __ptr64) __ptr64` | 599 (0x257) | Exported Function | 0x00000001800218b0 | 0x000218b0
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreateDisjunctions(void * __ptr64,class WmiTreeNode * __ptr64,class Disjunctions * __ptr64,unsigned long,unsigned short * __ptr64 * __ptr64,unsigned long & __ptr64) __ptr64` | 600 (0x258) | Exported Function | 0x00000001800040a0 | 0x000040a0
`protected: int __cdecl ProvCounterType::Parse(unsigned short const * __ptr64) __ptr64` | 820 (0x334) | Exported Function | 0x0000000180019720 | 0x00019720
`protected: enum WmiTriState __cdecl QueryPreprocessor::CreatePartitionSet(class Disjunctions * __ptr64,class PartitionSet * __ptr64 & __ptr64) __ptr64` | 602 (0x25a) | Exported Function | 0x0000000180004580 | 0x00004580
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 652 (0x28c) | Exported Function | 0x0000000180021b60 | 0x00021b60
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateNotExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 653 (0x28d) | Exported Function | 0x0000000180021b90 | 0x00021b90
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateOrExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 654 (0x28e) | Exported Function | 0x0000000180014660 | 0x00014660
`protected: enum WmiTriState __cdecl QueryPreprocessor::InsertNode(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 783 (0x30f) | Exported Function | 0x0000000180025e80 | 0x00025e80
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveConvertToRanges(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 872 (0x368) | Exported Function | 0x0000000180004480 | 0x00004480
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveInsertNode(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 878 (0x36e) | Exported Function | 0x0000000180002ed0 | 0x00002ed0
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursivePartitionSet(class Disjunctions * __ptr64,class PartitionSet * __ptr64 & __ptr64,unsigned long,unsigned long * __ptr64,unsigned long) __ptr64` | 879 (0x36f) | Exported Function | 0x0000000180004720 | 0x00004720
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveSort(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 883 (0x373) | Exported Function | 0x0000000180026e10 | 0x00026e10
`protected: enum WmiTriState __cdecl QueryPreprocessor::RecursiveSortConditionals(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 884 (0x374) | Exported Function | 0x0000000180002900 | 0x00002900
`protected: enum WmiTriState __cdecl QueryPreprocessor::RemoveOverlaps(unsigned long * __ptr64,unsigned long,unsigned long * __ptr64,unsigned long * __ptr64,class WmiRangeNode * __ptr64 * __ptr64) __ptr64` | 887 (0x377) | Exported Function | 0x0000000180004db0 | 0x00004db0
`protected: enum WmiTriState __cdecl QueryPreprocessor::Sort(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 922 (0x39a) | Exported Function | 0x00000001800270b0 | 0x000270b0
`protected: enum WmiTriState __cdecl QueryPreprocessor::SortConditionals(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 923 (0x39b) | Exported Function | 0x00000001800270c0 | 0x000270c0
`protected: enum WmiTriState __cdecl QueryPreprocessor::EvaluateAndExpression(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 651 (0x28b) | Exported Function | 0x0000000180021b00 | 0x00021b00
`protected: __cdecl ProvValue::ProvValue(void) __ptr64` | 166 (0xa6) | Exported Function | 0x0000000180010510 | 0x00010510
`protected: virtual int __cdecl ProvGaugeType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 625 (0x271) | Exported Function | 0x0000000180015bf0 | 0x00015bf0
`protected: virtual int __cdecl ProvIntegerType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 628 (0x274) | Exported Function | 0x0000000180015bf0 | 0x00015bf0
`protected: void __cdecl QueryPreprocessor::TransformIntersectingRange(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 929 (0x3a1) | Exported Function | 0x0000000180027490 | 0x00027490
`protected: void __cdecl QueryPreprocessor::TransformNonIntersectingRange(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 930 (0x3a2) | Exported Function | 0x0000000180005240 | 0x00005240
`protected: void __cdecl QueryPreprocessor::TransformNotAndExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 931 (0x3a3) | Exported Function | 0x00000001800274e0 | 0x000274e0
`protected: void __cdecl QueryPreprocessor::TransformNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 932 (0x3a4) | Exported Function | 0x0000000180027750 | 0x00027750
`protected: void __cdecl QueryPreprocessor::TransformNotNotExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 933 (0x3a5) | Exported Function | 0x00000001800279b0 | 0x000279b0
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 934 (0x3a6) | Exported Function | 0x0000000180027a60 | 0x00027a60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualOrGreaterExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 935 (0x3a7) | Exported Function | 0x0000000180027b60 | 0x00027b60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorEqualOrLessExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 936 (0x3a8) | Exported Function | 0x0000000180027c60 | 0x00027c60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorGreaterExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 937 (0x3a9) | Exported Function | 0x0000000180027b60 | 0x00027b60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorIsAExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 938 (0x3aa) | Exported Function | 0x0000000180027d60 | 0x00027d60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorLessExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 939 (0x3ab) | Exported Function | 0x0000000180027c60 | 0x00027c60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorLikeExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 940 (0x3ac) | Exported Function | 0x0000000180027e60 | 0x00027e60
`protected: void __cdecl QueryPreprocessor::TransformAndTrueEvaluation(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 928 (0x3a0) | Exported Function | 0x0000000180027410 | 0x00027410
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotEqualExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 941 (0x3ad) | Exported Function | 0x0000000180027f60 | 0x00027f60
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotLikeExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 943 (0x3af) | Exported Function | 0x0000000180028160 | 0x00028160
`protected: void __cdecl QueryPreprocessor::TransformNotOrExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 944 (0x3b0) | Exported Function | 0x0000000180028260 | 0x00028260
`protected: void __cdecl QueryPreprocessor::TransformOperatorToRange(class WmiTreeNode * __ptr64 & __ptr64) __ptr64` | 945 (0x3b1) | Exported Function | 0x00000001800284d0 | 0x000284d0
`protected: void __cdecl QueryPreprocessor::TransformOrFalseEvaluation(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 946 (0x3b2) | Exported Function | 0x0000000180027410 | 0x00027410
`public: __cdecl CBString::CBString(int) __ptr64` | 3 (0x3) | Exported Function | 0x000000018000b140 | 0x0000b140
`public: __cdecl CBString::CBString(unsigned short const * __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x000000018000b170 | 0x0000b170
`public: __cdecl CBString::CBString(void) __ptr64` | 5 (0x5) | Exported Function | 0x000000018000b1a0 | 0x0000b1a0
`public: __cdecl CBString::~CBString(void) __ptr64` | 228 (0xe4) | Exported Function | 0x0000000180010780 | 0x00010780
`public: __cdecl Conjunctions::Conjunctions(unsigned long) __ptr64` | 6 (0x6) | Exported Function | 0x000000018001d990 | 0x0001d990
`public: __cdecl Conjunctions::~Conjunctions(void) __ptr64` | 229 (0xe5) | Exported Function | 0x000000018001ee30 | 0x0001ee30
`public: __cdecl Disjunctions::Disjunctions(unsigned long,unsigned long) __ptr64` | 7 (0x7) | Exported Function | 0x000000018001d9b0 | 0x0001d9b0
`public: __cdecl Disjunctions::~Disjunctions(void) __ptr64` | 230 (0xe6) | Exported Function | 0x000000018001eeb0 | 0x0001eeb0
`protected: void __cdecl QueryPreprocessor::TransformNotOperatorNotIsAExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 942 (0x3ae) | Exported Function | 0x0000000180028060 | 0x00028060
`protected: virtual int __cdecl ProvInteger::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 626 (0x272) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`protected: void __cdecl QueryPreprocessor::TransformAndOrExpression(class WmiTreeNode * __ptr64 & __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 927 (0x39f) | Exported Function | 0x0000000180027190 | 0x00027190
`protected: void __cdecl QueryPreprocessor::RecursiveQuickSort(class WmiRangeNode * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long,unsigned long) __ptr64` | 880 (0x370) | Exported Function | 0x0000000180026cf0 | 0x00026cf0
`protected: virtual int __cdecl ProvIpAddress::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 629 (0x275) | Exported Function | 0x000000018001cf70 | 0x0001cf70
`protected: virtual int __cdecl ProvIpAddressType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 631 (0x277) | Exported Function | 0x0000000180015cb0 | 0x00015cb0
`protected: virtual int __cdecl ProvNetworkAddressType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 632 (0x278) | Exported Function | 0x0000000180015cb0 | 0x00015cb0
`protected: virtual int __cdecl ProvNull::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 633 (0x279) | Exported Function | 0x0000000180015d30 | 0x00015d30
`protected: virtual int __cdecl ProvNullType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 634 (0x27a) | Exported Function | 0x0000000180015d30 | 0x00015d30
`protected: virtual int __cdecl ProvObjectIdentifier::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 636 (0x27c) | Exported Function | 0x000000018001d040 | 0x0001d040
`protected: virtual int __cdecl ProvObjectIdentifierType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 638 (0x27e) | Exported Function | 0x0000000180015da0 | 0x00015da0
`protected: virtual int __cdecl ProvOctetString::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 639 (0x27f) | Exported Function | 0x000000018001d120 | 0x0001d120
`protected: virtual int __cdecl ProvOctetStringType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 641 (0x281) | Exported Function | 0x0000000180015e30 | 0x00015e30
`protected: virtual int __cdecl ProvOpaque::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 642 (0x282) | Exported Function | 0x000000018001d1f0 | 0x0001d1f0
`protected: virtual int __cdecl ProvOpaqueType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 644 (0x284) | Exported Function | 0x0000000180015ee0 | 0x00015ee0
`protected: virtual int __cdecl ProvTimeTicks::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 645 (0x285) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`protected: void __cdecl QueryPreprocessor::SortRanges(unsigned long,unsigned long * __ptr64,class WmiRangeNode * __ptr64 * __ptr64) __ptr64` | 924 (0x39c) | Exported Function | 0x0000000180027160 | 0x00027160
`protected: virtual int __cdecl ProvTimeTicksType::Equivalent(class ProvInstanceType const & __ptr64)const __ptr64` | 647 (0x287) | Exported Function | 0x0000000180015b70 | 0x00015b70
`protected: virtual unsigned char * __ptr64 __cdecl ProvOctetString::Replicate(unsigned char const * __ptr64,unsigned long) __ptr64` | 890 (0x37a) | Exported Function | 0x000000018001d6a0 | 0x0001d6a0
`protected: virtual unsigned long * __ptr64 __cdecl ProvObjectIdentifier::Replicate(unsigned long const * __ptr64,unsigned long)const __ptr64` | 889 (0x379) | Exported Function | 0x000000018001d620 | 0x0001d620
`protected: virtual unsigned long * __ptr64 __cdecl ProvObjectIdentifier::Replicate(unsigned long const * __ptr64,unsigned long,unsigned long const * __ptr64,unsigned long)const __ptr64` | 888 (0x378) | Exported Function | 0x000000018001d500 | 0x0001d500
`protected: virtual void __cdecl ProvAnalyser::Initialise(void) __ptr64` | 777 (0x309) | Exported Function | 0x0000000180005240 | 0x00005240
`protected: virtual void __cdecl ProvObjectIdentifier::Initialize(unsigned long const * __ptr64,unsigned long) __ptr64` | 781 (0x30d) | Exported Function | 0x000000018001d3a0 | 0x0001d3a0
`protected: virtual void __cdecl ProvObjectIdentifier::UnReplicate(unsigned long * __ptr64) __ptr64` | 947 (0x3b3) | Exported Function | 0x000000018001d850 | 0x0001d850
`protected: virtual void __cdecl ProvOctetString::Initialize(unsigned char const * __ptr64,unsigned long) __ptr64` | 782 (0x30e) | Exported Function | 0x000000018001d450 | 0x0001d450
`protected: virtual void __cdecl ProvOctetString::UnReplicate(unsigned char * __ptr64) __ptr64` | 948 (0x3b4) | Exported Function | 0x000000018001d8a0 | 0x0001d8a0
`protected: void __cdecl ProvPositiveRangedType::PushBack(void) __ptr64` | 867 (0x363) | Exported Function | 0x000000018001b420 | 0x0001b420
`protected: void __cdecl QueryPreprocessor::CountDisjunctions(class WmiTreeNode * __ptr64,unsigned long & __ptr64) __ptr64` | 598 (0x256) | Exported Function | 0x0000000180021850 | 0x00021850
`protected: void __cdecl QueryPreprocessor::PrintTree(class WmiTreeNode * __ptr64) __ptr64` | 862 (0x35e) | Exported Function | 0x0000000180026c50 | 0x00026c50
`protected: void __cdecl QueryPreprocessor::QuickSort(class WmiRangeNode * __ptr64 * __ptr64,unsigned long * __ptr64,unsigned long) __ptr64` | 870 (0x366) | Exported Function | 0x0000000180026cc0 | 0x00026cc0
`protected: virtual int __cdecl ProvUInteger32::Equivalent(class ProvValue const & __ptr64)const __ptr64` | 648 (0x288) | Exported Function | 0x000000018001cef0 | 0x0001cef0
`protected: __cdecl ProvInstanceType::ProvInstanceType(int,int) __ptr64` | 74 (0x4a) | Exported Function | 0x000000018000d9a0 | 0x0000d9a0
`protected: __cdecl ProvInstanceType::ProvInstanceType(class ProvInstanceType const & __ptr64) __ptr64` | 73 (0x49) | Exported Function | 0x000000018000d970 | 0x0000d970
`private: void __cdecl ProvOctetString::OverWrite(unsigned char const * __ptr64) __ptr64` | 817 (0x331) | Exported Function | 0x000000018001d4d0 | 0x0001d4d0
`const ProvGaugeType::``vftable'{for ``ProvPositiveRangedType'}` | 435 (0x1b3) | Exported Function | 0x000000018002ad20 | 0x0002ad20
`const ProvInstanceType::``vftable'` | 436 (0x1b4) | Exported Function | 0x000000018002a208 | 0x0002a208
`const ProvInteger::``vftable'` | 437 (0x1b5) | Exported Function | 0x000000018002af50 | 0x0002af50
`const ProvIntegerType::``vftable'{for ``ProvInstanceType'}` | 438 (0x1b6) | Exported Function | 0x000000018002ada0 | 0x0002ada0
`const ProvIntegerType::``vftable'{for ``ProvNegativeRangedType'}` | 439 (0x1b7) | Exported Function | 0x000000018002ad88 | 0x0002ad88
`const ProvIpAddress::``vftable'` | 440 (0x1b8) | Exported Function | 0x000000018002aeb0 | 0x0002aeb0
`const ProvIpAddressType::``vftable'` | 441 (0x1b9) | Exported Function | 0x000000018002abe0 | 0x0002abe0
`const ProvMacAddressType::``vftable'` | 442 (0x1ba) | Exported Function | 0x000000018002a908 | 0x0002a908
`const ProvMacAddressType::``vftable'{for ``ProvInstanceType'}` | 443 (0x1bb) | Exported Function | 0x000000018002a930 | 0x0002a930
`const ProvMacAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 444 (0x1bc) | Exported Function | 0x000000018002a918 | 0x0002a918
`const ProvNegativeRangeType::``vftable'` | 445 (0x1bd) | Exported Function | 0x000000018002a280 | 0x0002a280
`const ProvNetworkAddressType::``vftable'` | 446 (0x1be) | Exported Function | 0x000000018002ab90 | 0x0002ab90
`const ProvGaugeType::``vftable'{for ``ProvInstanceType'}` | 434 (0x1b2) | Exported Function | 0x000000018002ad38 | 0x0002ad38
`const ProvNull::``vftable'` | 447 (0x1bf) | Exported Function | 0x000000018002af70 | 0x0002af70
`const ProvObjectIdentifier::``vftable'` | 451 (0x1c3) | Exported Function | 0x000000018002af90 | 0x0002af90
`const ProvObjectIdentifierType::``vftable'` | 452 (0x1c4) | Exported Function | 0x000000018002ab40 | 0x0002ab40
`const ProvOctetString::``vftable'` | 453 (0x1c5) | Exported Function | 0x000000018002afd0 | 0x0002afd0
`const ProvOctetStringType::``vftable'{for ``ProvInstanceType'}` | 454 (0x1c6) | Exported Function | 0x000000018002aa10 | 0x0002aa10
`const ProvOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 455 (0x1c7) | Exported Function | 0x000000018002a9f8 | 0x0002a9f8
`const ProvOpaque::``vftable'` | 456 (0x1c8) | Exported Function | 0x000000018002aed0 | 0x0002aed0
`const ProvOpaqueType::``vftable'{for ``ProvInstanceType'}` | 457 (0x1c9) | Exported Function | 0x000000018002aaf0 | 0x0002aaf0
`const ProvOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 458 (0x1ca) | Exported Function | 0x000000018002aad8 | 0x0002aad8
`const ProvOSIAddressType::``vftable'{for ``ProvInstanceType'}` | 449 (0x1c1) | Exported Function | 0x000000018002a558 | 0x0002a558
`const ProvOSIAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 450 (0x1c2) | Exported Function | 0x000000018002a540 | 0x0002a540
`const ProvPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 459 (0x1cb) | Exported Function | 0x000000018002a8b8 | 0x0002a8b8
`const ProvPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 460 (0x1cc) | Exported Function | 0x000000018002a8a0 | 0x0002a8a0
`const ProvNullType::``vftable'` | 448 (0x1c0) | Exported Function | 0x000000018002adf0 | 0x0002adf0
`const ProvPositiveRangedType::``vftable'` | 462 (0x1ce) | Exported Function | 0x000000018002ae40 | 0x0002ae40
`const ProvGauge::``vftable'` | 433 (0x1b1) | Exported Function | 0x000000018002af30 | 0x0002af30
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 431 (0x1af) | Exported Function | 0x000000018002a838 | 0x0002a838
`const PartitionSet::``vftable'` | 405 (0x195) | Exported Function | 0x000000018002a1a8 | 0x0002a1a8
`const ProvAnalyser::``vftable'` | 406 (0x196) | Exported Function | 0x000000018002a298 | 0x0002a298
`const ProvBitStringType::``vftable'{for ``ProvInstanceType'}` | 407 (0x197) | Exported Function | 0x000000018002a628 | 0x0002a628
`const ProvBitStringType::``vftable'{for ``ProvPositiveRangedType'}` | 408 (0x198) | Exported Function | 0x000000018002a610 | 0x0002a610
`const ProvCounter64::``vftable'` | 409 (0x199) | Exported Function | 0x000000018002ae70 | 0x0002ae70
`const ProvCounter64Type::``vftable'` | 410 (0x19a) | Exported Function | 0x000000018002ac30 | 0x0002ac30
`const ProvCounter::``vftable'` | 411 (0x19b) | Exported Function | 0x000000018002af10 | 0x0002af10
`const ProvCounterType::``vftable'` | 412 (0x19c) | Exported Function | 0x000000018002ac80 | 0x0002ac80
`const ProvDateTimeType::``vftable'{for ``ProvInstanceType'}` | 413 (0x19d) | Exported Function | 0x000000018002a5c0 | 0x0002a5c0
`const ProvDateTimeType::``vftable'{for ``ProvPositiveRangedType'}` | 414 (0x19e) | Exported Function | 0x000000018002a5a8 | 0x0002a5a8
`const ProvDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 415 (0x19f) | Exported Function | 0x000000018002a7d8 | 0x0002a7d8
`const ProvDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 416 (0x1a0) | Exported Function | 0x000000018002a7c0 | 0x0002a7c0
`const ProvFixedType::``vftable'` | 432 (0x1b0) | Exported Function | 0x000000018002a258 | 0x0002a258
`const ProvEnumeratedType::``vftable'{for ``ProvInstanceType'}` | 417 (0x1a1) | Exported Function | 0x000000018002a6f8 | 0x0002a6f8
`const ProvEventObject::``vftable'` | 419 (0x1a3) | Exported Function | 0x000000018002a440 | 0x0002a440
`const ProvFixedLengthDisplayStringType::``vftable'` | 420 (0x1a4) | Exported Function | 0x000000018002a748 | 0x0002a748
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 421 (0x1a5) | Exported Function | 0x000000018002a770 | 0x0002a770
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 422 (0x1a6) | Exported Function | 0x000000018002a758 | 0x0002a758
`const ProvFixedLengthOctetStringType::``vftable'` | 423 (0x1a7) | Exported Function | 0x000000018002a980 | 0x0002a980
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvInstanceType'}` | 424 (0x1a8) | Exported Function | 0x000000018002a9a8 | 0x0002a9a8
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 425 (0x1a9) | Exported Function | 0x000000018002a990 | 0x0002a990
`const ProvFixedLengthOpaqueType::``vftable'` | 426 (0x1aa) | Exported Function | 0x000000018002aa60 | 0x0002aa60
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvInstanceType'}` | 427 (0x1ab) | Exported Function | 0x000000018002aa88 | 0x0002aa88
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 428 (0x1ac) | Exported Function | 0x000000018002aa70 | 0x0002aa70
`const ProvFixedLengthPhysAddressType::``vftable'` | 429 (0x1ad) | Exported Function | 0x000000018002a828 | 0x0002a828
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 430 (0x1ae) | Exported Function | 0x000000018002a850 | 0x0002a850
`const ProvEnumeratedType::``vftable'{for ``ProvNegativeRangedType'}` | 418 (0x1a2) | Exported Function | 0x000000018002a6e0 | 0x0002a6e0
`const ProvPositiveRangeType::``vftable'` | 461 (0x1cd) | Exported Function | 0x000000018002a268 | 0x0002a268
`const ProvRowStatusType::``vftable'{for ``ProvInstanceType'}` | 463 (0x1cf) | Exported Function | 0x000000018002a690 | 0x0002a690
`const ProvRowStatusType::``vftable'{for ``ProvNegativeRangedType'}` | 464 (0x1d0) | Exported Function | 0x000000018002a678 | 0x0002a678
`const WmiUnsignedIntegerNode::``vftable'` | 496 (0x1f0) | Exported Function | 0x000000018002a008 | 0x0002a008
`const WmiUnsignedIntegerRangeNode::``vftable'` | 497 (0x1f1) | Exported Function | 0x000000018002a030 | 0x0002a030
`const WmiValueNode::``vftable'` | 498 (0x1f2) | Exported Function | 0x000000018002a158 | 0x0002a158
`int __cdecl CompareElements<unsigned short * __ptr64,unsigned short * __ptr64>(unsigned short * __ptr64 const * __ptr64,unsigned short * __ptr64 const * __ptr64)` | 1 (0x1) | Exported Function | 0x000000018000aee0 | 0x0000aee0
`private: __cdecl ProvValue::ProvValue(class ProvValue const & __ptr64) __ptr64` | 165 (0xa5) | Exported Function | 0x0000000180010510 | 0x00010510
`private: class ProvLexicon * __ptr64 __cdecl ProvAnalyser::GetToken(int,int,int) __ptr64` | 733 (0x2dd) | Exported Function | 0x00000001800180f0 | 0x000180f0
`private: class ProvLexicon * __ptr64 __cdecl ProvBitStringType::Get(void) __ptr64` | 656 (0x290) | Exported Function | 0x0000000180015fc0 | 0x00015fc0
`private: class ProvLexicon * __ptr64 __cdecl ProvBitStringType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 810 (0x32a) | Exported Function | 0x0000000180019010 | 0x00019010
`private: class ProvLexicon * __ptr64 __cdecl ProvDateTimeType::Get(void) __ptr64` | 657 (0x291) | Exported Function | 0x0000000180016030 | 0x00016030
`private: class ProvLexicon * __ptr64 __cdecl ProvDateTimeType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 811 (0x32b) | Exported Function | 0x0000000180019050 | 0x00019050
`private: class ProvLexicon * __ptr64 __cdecl ProvEnumeratedType::Get(void) __ptr64` | 658 (0x292) | Exported Function | 0x00000001800160a0 | 0x000160a0
`private: class ProvLexicon * __ptr64 __cdecl ProvEnumeratedType::Match(enum ProvLexicon::LexiconToken) __ptr64` | 812 (0x32c) | Exported Function | 0x0000000180019090 | 0x00019090
`const WmiTreeNodeIterator::``vftable'` | 495 (0x1ef) | Exported Function | 0x000000018002a2e8 | 0x0002a2e8
`private: class ProvValue & __ptr64 __cdecl ProvValue::operator=(class ProvValue const & __ptr64) __ptr64` | 353 (0x161) | Exported Function | 0x0000000180011fb0 | 0x00011fb0
`private: int __cdecl ProvBitStringType::Parse(unsigned short const * __ptr64) __ptr64` | 818 (0x332) | Exported Function | 0x0000000180019380 | 0x00019380
`private: int __cdecl ProvBitStringType::RecursiveDef(void) __ptr64` | 873 (0x369) | Exported Function | 0x000000018001b850 | 0x0001b850
`private: int __cdecl ProvDateTimeType::DateTimeDef(void) __ptr64` | 604 (0x25c) | Exported Function | 0x0000000180015320 | 0x00015320
`private: int __cdecl ProvDateTimeType::Parse(unsigned short const * __ptr64) __ptr64` | 821 (0x335) | Exported Function | 0x00000001800197d0 | 0x000197d0
`private: int __cdecl ProvEnumeratedType::EnumerationDef(void) __ptr64` | 616 (0x268) | Exported Function | 0x0000000180015940 | 0x00015940
`private: int __cdecl ProvEnumeratedType::Parse(unsigned short const * __ptr64) __ptr64` | 822 (0x336) | Exported Function | 0x0000000180019800 | 0x00019800
`private: int __cdecl ProvEnumeratedType::RecursiveDef(void) __ptr64` | 874 (0x36a) | Exported Function | 0x000000018001b8c0 | 0x0001b8c0
`private: void __cdecl ProvBitStringType::PushBack(void) __ptr64` | 864 (0x360) | Exported Function | 0x000000018001b3c0 | 0x0001b3c0
`private: void __cdecl ProvDateTimeType::Encode(unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64,unsigned long const & __ptr64) __ptr64` | 615 (0x267) | Exported Function | 0x00000001800157f0 | 0x000157f0
`private: void __cdecl ProvDateTimeType::PushBack(void) __ptr64` | 865 (0x361) | Exported Function | 0x000000018001b3e0 | 0x0001b3e0
`private: void __cdecl ProvEnumeratedType::PushBack(void) __ptr64` | 866 (0x362) | Exported Function | 0x000000018001b400 | 0x0001b400
`private: void __cdecl ProvObjectIdentifier::OverWrite(unsigned long const * __ptr64) __ptr64` | 816 (0x330) | Exported Function | 0x000000018001d4a0 | 0x0001d4a0
`private: int __cdecl ProvBitStringType::BitStringDef(void) __ptr64` | 526 (0x20e) | Exported Function | 0x0000000180014670 | 0x00014670
`const WmiTreeNode::``vftable'` | 494 (0x1ee) | Exported Function | 0x000000018002a058 | 0x0002a058
`const WmiStringRangeNode::``vftable'` | 493 (0x1ed) | Exported Function | 0x000000018002a0a8 | 0x0002a0a8
`const WmiStringNode::``vftable'` | 492 (0x1ec) | Exported Function | 0x000000018002a180 | 0x0002a180
`const ProvTimeTicks::``vftable'` | 465 (0x1d1) | Exported Function | 0x000000018002aef0 | 0x0002aef0
`const ProvTimeTicksType::``vftable'` | 466 (0x1d2) | Exported Function | 0x000000018002acd0 | 0x0002acd0
`const ProvUDPAddressType::``vftable'` | 467 (0x1d3) | Exported Function | 0x000000018002a4c8 | 0x0002a4c8
`const ProvUDPAddressType::``vftable'{for ``ProvInstanceType'}` | 468 (0x1d4) | Exported Function | 0x000000018002a4f0 | 0x0002a4f0
`const ProvUDPAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 469 (0x1d5) | Exported Function | 0x000000018002a4d8 | 0x0002a4d8
`const ProvUInteger32::``vftable'` | 470 (0x1d6) | Exported Function | 0x000000018002ae90 | 0x0002ae90
`const ProvValue::``vftable'` | 471 (0x1d7) | Exported Function | 0x000000018002a2c8 | 0x0002a2c8
`const QueryPreprocessor::``vftable'` | 472 (0x1d8) | Exported Function | 0x000000018002a1b8 | 0x0002a1b8
`const WmiAndNode::``vftable'` | 473 (0x1d9) | Exported Function | 0x000000018002a0d0 | 0x0002a0d0
`const WmiNotNode::``vftable'` | 474 (0x1da) | Exported Function | 0x000000018002b258 | 0x0002b258
`const WmiNullNode::``vftable'` | 475 (0x1db) | Exported Function | 0x000000018002b058 | 0x0002b058
`const WmiNullRangeNode::``vftable'` | 476 (0x1dc) | Exported Function | 0x000000018002b008 | 0x0002b008
`const WmiOperatorEqualNode::``vftable'` | 477 (0x1dd) | Exported Function | 0x000000018002a128 | 0x0002a128
`const WmiOperatorEqualOrGreaterNode::``vftable'` | 478 (0x1de) | Exported Function | 0x000000018002b1f8 | 0x0002b1f8
`const WmiOperatorEqualOrLessNode::``vftable'` | 479 (0x1df) | Exported Function | 0x000000018002b1c8 | 0x0002b1c8
`const WmiOperatorGreaterNode::``vftable'` | 480 (0x1e0) | Exported Function | 0x000000018002b198 | 0x0002b198
`const WmiOperatorIsANode::``vftable'` | 481 (0x1e1) | Exported Function | 0x000000018002b0d8 | 0x0002b0d8
`const WmiOperatorLessNode::``vftable'` | 482 (0x1e2) | Exported Function | 0x000000018002b168 | 0x0002b168
`const WmiOperatorLikeNode::``vftable'` | 483 (0x1e3) | Exported Function | 0x000000018002b138 | 0x0002b138
`const WmiOperatorNode::``vftable'` | 484 (0x1e4) | Exported Function | 0x000000018002a0f8 | 0x0002a0f8
`const WmiOperatorNotEqualNode::``vftable'` | 485 (0x1e5) | Exported Function | 0x000000018002b228 | 0x0002b228
`const WmiOperatorNotIsANode::``vftable'` | 486 (0x1e6) | Exported Function | 0x000000018002b0a8 | 0x0002b0a8
`const WmiOperatorNotLikeNode::``vftable'` | 487 (0x1e7) | Exported Function | 0x000000018002b108 | 0x0002b108
`const WmiOrNode::``vftable'` | 488 (0x1e8) | Exported Function | 0x000000018002b280 | 0x0002b280
`const WmiRangeNode::``vftable'` | 489 (0x1e9) | Exported Function | 0x000000018002a080 | 0x0002a080
`const WmiSignedIntegerNode::``vftable'` | 490 (0x1ea) | Exported Function | 0x000000018002b080 | 0x0002b080
`const WmiSignedIntegerRangeNode::``vftable'` | 491 (0x1eb) | Exported Function | 0x000000018002b030 | 0x0002b030
`public: __cdecl PartitionSet::PartitionSet(class PartitionSet const & __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x000000018001d9d0 | 0x0001d9d0
`public: __cdecl PartitionSet::PartitionSet(void) __ptr64` | 9 (0x9) | Exported Function | 0x000000018001da10 | 0x0001da10
`public: __cdecl ProvAnalyser::ProvAnalyser(class ProvAnalyser const & __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x000000018000b1b0 | 0x0000b1b0
`public: __cdecl ProvAnalyser::ProvAnalyser(unsigned short const * __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x000000018000b1e0 | 0x0000b1e0
`public: __cdecl ProvUInteger32::ProvUInteger32(long) __ptr64` | 164 (0xa4) | Exported Function | 0x00000001800104c0 | 0x000104c0
`public: __cdecl QueryPreprocessor::QueryPreprocessor(class QueryPreprocessor const & __ptr64) __ptr64` | 167 (0xa7) | Exported Function | 0x0000000180005200 | 0x00005200
`public: __cdecl QueryPreprocessor::QueryPreprocessor(void) __ptr64` | 168 (0xa8) | Exported Function | 0x0000000180005200 | 0x00005200
`public: __cdecl WmiAndNode::WmiAndNode(class WmiAndNode const & __ptr64) __ptr64` | 169 (0xa9) | Exported Function | 0x000000018001da40 | 0x0001da40
`public: __cdecl WmiAndNode::WmiAndNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 170 (0xaa) | Exported Function | 0x000000018001dab0 | 0x0001dab0
`public: __cdecl WmiNotNode::WmiNotNode(class WmiNotNode const & __ptr64) __ptr64` | 171 (0xab) | Exported Function | 0x000000018001db10 | 0x0001db10
`public: __cdecl WmiNotNode::WmiNotNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 172 (0xac) | Exported Function | 0x000000018001db80 | 0x0001db80
`public: __cdecl WmiNullNode::WmiNullNode(class WmiNullNode && __ptr64) __ptr64` | 173 (0xad) | Exported Function | 0x000000018001dbe0 | 0x0001dbe0
`public: __cdecl WmiNullNode::WmiNullNode(class WmiNullNode const & __ptr64) __ptr64` | 174 (0xae) | Exported Function | 0x000000018001dbe0 | 0x0001dbe0
`public: __cdecl WmiNullNode::WmiNullNode(unsigned short * __ptr64,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 175 (0xaf) | Exported Function | 0x000000018001dc30 | 0x0001dc30
`public: __cdecl WmiNullRangeNode::WmiNullRangeNode(class WmiNullRangeNode const & __ptr64) __ptr64` | 176 (0xb0) | Exported Function | 0x000000018001dc90 | 0x0001dc90
`public: __cdecl WmiNullRangeNode::WmiNullRangeNode(unsigned short * __ptr64,unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 177 (0xb1) | Exported Function | 0x000000018001dce0 | 0x0001dce0
`public: __cdecl ProvUInteger32::ProvUInteger32(class ProvUInteger32 const & __ptr64) __ptr64` | 163 (0xa3) | Exported Function | 0x000000018001c5a0 | 0x0001c5a0
`public: __cdecl WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiOperatorEqualNode const & __ptr64) __ptr64` | 178 (0xb2) | Exported Function | 0x000000018001dd60 | 0x0001dd60
`public: __cdecl WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiOperatorEqualOrGreaterNode const & __ptr64) __ptr64` | 180 (0xb4) | Exported Function | 0x000000018001de30 | 0x0001de30
`public: __cdecl WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 181 (0xb5) | Exported Function | 0x000000018001deb0 | 0x0001deb0
`public: __cdecl WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiOperatorEqualOrLessNode const & __ptr64) __ptr64` | 182 (0xb6) | Exported Function | 0x000000018001df00 | 0x0001df00
`public: __cdecl WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 183 (0xb7) | Exported Function | 0x000000018001df80 | 0x0001df80
`public: __cdecl WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiOperatorGreaterNode const & __ptr64) __ptr64` | 184 (0xb8) | Exported Function | 0x000000018001dfd0 | 0x0001dfd0
`public: __cdecl WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 185 (0xb9) | Exported Function | 0x000000018001e050 | 0x0001e050
`public: __cdecl WmiOperatorIsANode::WmiOperatorIsANode(class WmiOperatorIsANode const & __ptr64) __ptr64` | 186 (0xba) | Exported Function | 0x000000018001e0a0 | 0x0001e0a0
`public: __cdecl WmiOperatorIsANode::WmiOperatorIsANode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 187 (0xbb) | Exported Function | 0x000000018001e120 | 0x0001e120
`public: __cdecl WmiOperatorLessNode::WmiOperatorLessNode(class WmiOperatorLessNode const & __ptr64) __ptr64` | 188 (0xbc) | Exported Function | 0x000000018001e170 | 0x0001e170
`public: __cdecl WmiOperatorLessNode::WmiOperatorLessNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 189 (0xbd) | Exported Function | 0x000000018001e1f0 | 0x0001e1f0
`public: __cdecl WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiOperatorLikeNode const & __ptr64) __ptr64` | 190 (0xbe) | Exported Function | 0x000000018001e240 | 0x0001e240
`public: __cdecl WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 191 (0xbf) | Exported Function | 0x000000018001e2c0 | 0x0001e2c0
`public: __cdecl WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 179 (0xb3) | Exported Function | 0x000000018001dde0 | 0x0001dde0
`public: __cdecl WmiOperatorNode::WmiOperatorNode(class WmiOperatorNode const & __ptr64) __ptr64` | 192 (0xc0) | Exported Function | 0x000000018001e310 | 0x0001e310
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(void) __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180010450 | 0x00010450
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(unsigned char const * __ptr64) __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180010350 | 0x00010350
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(void) __ptr64` | 112 (0x70) | Exported Function | 0x000000018000ec60 | 0x0000ec60
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 136 (0x88) | Exported Function | 0x000000018000f910 | 0x0000f910
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(class ProvPhysAddressType const & __ptr64) __ptr64` | 135 (0x87) | Exported Function | 0x000000018000f8c0 | 0x0000f8c0
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 137 (0x89) | Exported Function | 0x000000018000f960 | 0x0000f960
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned short const * __ptr64) __ptr64` | 139 (0x8b) | Exported Function | 0x000000018000fa30 | 0x0000fa30
`public: __cdecl ProvPhysAddressType::ProvPhysAddressType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 138 (0x8a) | Exported Function | 0x000000018000f9b0 | 0x0000f9b0
`public: __cdecl ProvPositiveRangedType::ProvPositiveRangedType(class ProvPositiveRangedType const & __ptr64) __ptr64` | 143 (0x8f) | Exported Function | 0x000000018000fb00 | 0x0000fb00
`public: __cdecl ProvPositiveRangedType::ProvPositiveRangedType(unsigned short const * __ptr64) __ptr64` | 144 (0x90) | Exported Function | 0x000000018000fc40 | 0x0000fc40
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(class ProvPositiveRangeType const & __ptr64) __ptr64` | 140 (0x8c) | Exported Function | 0x000000018000fa90 | 0x0000fa90
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(unsigned long,long) __ptr64` | 141 (0x8d) | Exported Function | 0x000000018000fac0 | 0x0000fac0
`public: __cdecl ProvPositiveRangeType::ProvPositiveRangeType(void) __ptr64` | 142 (0x8e) | Exported Function | 0x000000018000fae0 | 0x0000fae0
`public: __cdecl ProvRowStatusType::ProvRowStatusType(class ProvInteger const & __ptr64) __ptr64` | 147 (0x93) | Exported Function | 0x000000018000fdd0 | 0x0000fdd0
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(unsigned short const * __ptr64) __ptr64` | 161 (0xa1) | Exported Function | 0x00000001800103c0 | 0x000103c0
`public: __cdecl ProvRowStatusType::ProvRowStatusType(class ProvRowStatusType const & __ptr64) __ptr64` | 146 (0x92) | Exported Function | 0x000000018000fd80 | 0x0000fd80
`public: __cdecl ProvRowStatusType::ProvRowStatusType(long const & __ptr64) __ptr64` | 145 (0x91) | Exported Function | 0x000000018000fd20 | 0x0000fd20
`public: __cdecl ProvRowStatusType::ProvRowStatusType(unsigned short const * __ptr64) __ptr64` | 149 (0x95) | Exported Function | 0x000000018000fe90 | 0x0000fe90
`public: __cdecl ProvRowStatusType::ProvRowStatusType(void) __ptr64` | 150 (0x96) | Exported Function | 0x000000018000fef0 | 0x0000fef0
`public: __cdecl ProvTimeTicks::ProvTimeTicks(class ProvTimeTicks const & __ptr64) __ptr64` | 151 (0x97) | Exported Function | 0x000000018001c550 | 0x0001c550
`public: __cdecl ProvTimeTicks::ProvTimeTicks(unsigned long) __ptr64` | 152 (0x98) | Exported Function | 0x000000018000ff50 | 0x0000ff50
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicks const & __ptr64) __ptr64` | 154 (0x9a) | Exported Function | 0x0000000180010030 | 0x00010030
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicksType const & __ptr64) __ptr64` | 153 (0x99) | Exported Function | 0x000000018000ffa0 | 0x0000ffa0
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(unsigned long) __ptr64` | 155 (0x9b) | Exported Function | 0x00000001800100c0 | 0x000100c0
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(unsigned short const * __ptr64) __ptr64` | 156 (0x9c) | Exported Function | 0x0000000180010150 | 0x00010150
`public: __cdecl ProvTimeTicksType::ProvTimeTicksType(void) __ptr64` | 157 (0x9d) | Exported Function | 0x00000001800101f0 | 0x000101f0
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(class ProvOctetString const & __ptr64) __ptr64` | 159 (0x9f) | Exported Function | 0x00000001800102e0 | 0x000102e0
`public: __cdecl ProvUDPAddressType::ProvUDPAddressType(class ProvUDPAddressType const & __ptr64) __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180010280 | 0x00010280
`public: __cdecl ProvRowStatusType::ProvRowStatusType(enum ProvRowStatusType::ProvRowStatusEnum const & __ptr64) __ptr64` | 148 (0x94) | Exported Function | 0x000000018000fe30 | 0x0000fe30
`public: __cdecl WmiOperatorNode::WmiOperatorNode(unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 193 (0xc1) | Exported Function | 0x000000018001e380 | 0x0001e380
`public: __cdecl WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiOperatorNotEqualNode const & __ptr64) __ptr64` | 194 (0xc2) | Exported Function | 0x000000018001e3e0 | 0x0001e3e0
`public: __cdecl WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 195 (0xc3) | Exported Function | 0x000000018001e460 | 0x0001e460
`public: __cdecl WmiValueNode::WmiValueNode(unsigned long,unsigned short * __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 227 (0xe3) | Exported Function | 0x000000018001ed40 | 0x0001ed40
`public: char * __ptr64 __cdecl ProvObjectIdentifier::GetAllocatedString(void)const __ptr64` | 660 (0x294) | Exported Function | 0x000000018001d270 | 0x0001d270
`public: class CBString & __ptr64 __cdecl CBString::operator=(class CBString const & __ptr64) __ptr64` | 303 (0x12f) | Exported Function | 0x0000000180011a70 | 0x00011a70
`public: class CBString const & __ptr64 __cdecl CBString::operator=(unsigned short const * __ptr64) __ptr64` | 304 (0x130) | Exported Function | 0x0000000180011a90 | 0x00011a90
`public: class Conjunctions & __ptr64 __cdecl Conjunctions::operator=(class Conjunctions const & __ptr64) __ptr64` | 305 (0x131) | Exported Function | 0x000000018001f830 | 0x0001f830
`public: class Conjunctions * __ptr64 __cdecl Disjunctions::GetDisjunction(unsigned long) __ptr64` | 665 (0x299) | Exported Function | 0x0000000180021ca0 | 0x00021ca0
`public: class Disjunctions & __ptr64 __cdecl Disjunctions::operator=(class Disjunctions const & __ptr64) __ptr64` | 306 (0x132) | Exported Function | 0x000000018001f830 | 0x0001f830
`public: class PartitionSet & __ptr64 __cdecl PartitionSet::operator=(class PartitionSet const & __ptr64) __ptr64` | 307 (0x133) | Exported Function | 0x000000018001f850 | 0x0001f850
`public: class PartitionSet * __ptr64 __cdecl PartitionSet::GetPartition(unsigned long) __ptr64` | 688 (0x2b0) | Exported Function | 0x00000001800050a0 | 0x000050a0
`public: class ProvAnalyser & __ptr64 __cdecl ProvAnalyser::operator=(class ProvAnalyser const & __ptr64) __ptr64` | 308 (0x134) | Exported Function | 0x0000000180011ae0 | 0x00011ae0
`public: class ProvBitStringType & __ptr64 __cdecl ProvBitStringType::operator=(class ProvBitStringType const & __ptr64) __ptr64` | 309 (0x135) | Exported Function | 0x0000000180011b00 | 0x00011b00
`public: class ProvCounter64Type & __ptr64 __cdecl ProvCounter64Type::operator=(class ProvCounter64Type const & __ptr64) __ptr64` | 311 (0x137) | Exported Function | 0x0000000180011c00 | 0x00011c00
`public: __cdecl WmiValueNode::WmiValueNode(class WmiValueNode const & __ptr64) __ptr64` | 226 (0xe2) | Exported Function | 0x000000018001ecc0 | 0x0001ecc0
`public: class ProvCounterType & __ptr64 __cdecl ProvCounterType::operator=(class ProvCounterType const & __ptr64) __ptr64` | 313 (0x139) | Exported Function | 0x0000000180011c50 | 0x00011c50
`public: class ProvDebugLog & __ptr64 __cdecl ProvDebugLog::operator=(class ProvDebugLog && __ptr64) __ptr64` | 315 (0x13b) | Exported Function | 0x000000018000a420 | 0x0000a420
`public: class ProvDebugLog & __ptr64 __cdecl ProvDebugLog::operator=(class ProvDebugLog const & __ptr64) __ptr64` | 316 (0x13c) | Exported Function | 0x000000018000a420 | 0x0000a420
`public: class ProvDisplayStringType & __ptr64 __cdecl ProvDisplayStringType::operator=(class ProvDisplayStringType const & __ptr64) __ptr64` | 317 (0x13d) | Exported Function | 0x0000000180011ce0 | 0x00011ce0
`public: class ProvEnumeratedType & __ptr64 __cdecl ProvEnumeratedType::operator=(class ProvEnumeratedType const & __ptr64) __ptr64` | 318 (0x13e) | Exported Function | 0x0000000180011d00 | 0x00011d00
`public: class ProvEventObject & __ptr64 __cdecl ProvEventObject::operator=(class ProvEventObject const & __ptr64) __ptr64` | 319 (0x13f) | Exported Function | 0x000000018000a430 | 0x0000a430
`public: class ProvFixedLengthDisplayStringType & __ptr64 __cdecl ProvFixedLengthDisplayStringType::operator=(class ProvFixedLengthDisplayStringType const & __ptr64) __ptr64` | 320 (0x140) | Exported Function | 0x0000000180011de0 | 0x00011de0
`public: class ProvFixedLengthOctetStringType & __ptr64 __cdecl ProvFixedLengthOctetStringType::operator=(class ProvFixedLengthOctetStringType const & __ptr64) __ptr64` | 321 (0x141) | Exported Function | 0x0000000180011e00 | 0x00011e00
`public: class ProvFixedLengthOpaqueType & __ptr64 __cdecl ProvFixedLengthOpaqueType::operator=(class ProvFixedLengthOpaqueType const & __ptr64) __ptr64` | 322 (0x142) | Exported Function | 0x0000000180011e40 | 0x00011e40
`public: class ProvFixedLengthPhysAddressType & __ptr64 __cdecl ProvFixedLengthPhysAddressType::operator=(class ProvFixedLengthPhysAddressType const & __ptr64) __ptr64` | 323 (0x143) | Exported Function | 0x0000000180011de0 | 0x00011de0
`public: class ProvFixedType & __ptr64 __cdecl ProvFixedType::operator=(class ProvFixedType const & __ptr64) __ptr64` | 324 (0x144) | Exported Function | 0x0000000180011c30 | 0x00011c30
`public: class ProvGaugeType & __ptr64 __cdecl ProvGaugeType::operator=(class ProvGaugeType const & __ptr64) __ptr64` | 326 (0x146) | Exported Function | 0x0000000180011e80 | 0x00011e80
`public: class ProvInstanceType & __ptr64 __cdecl ProvInstanceType::operator=(class ProvInstanceType const & __ptr64) __ptr64` | 327 (0x147) | Exported Function | 0x0000000180011f00 | 0x00011f00
`public: class ProvDateTimeType & __ptr64 __cdecl ProvDateTimeType::operator=(class ProvDateTimeType const & __ptr64) __ptr64` | 314 (0x13a) | Exported Function | 0x0000000180011c70 | 0x00011c70
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,unsigned long,unsigned long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 225 (0xe1) | Exported Function | 0x0000000180002da0 | 0x00002da0
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode const & __ptr64) __ptr64` | 224 (0xe0) | Exported Function | 0x000000018001ec60 | 0x0001ec60
`public: __cdecl WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode && __ptr64) __ptr64` | 223 (0xdf) | Exported Function | 0x000000018001ec60 | 0x0001ec60
`public: __cdecl WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiOperatorNotIsANode const & __ptr64) __ptr64` | 196 (0xc4) | Exported Function | 0x000000018001e4b0 | 0x0001e4b0
`public: __cdecl WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 197 (0xc5) | Exported Function | 0x000000018001e530 | 0x0001e530
`public: __cdecl WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiOperatorNotLikeNode const & __ptr64) __ptr64` | 198 (0xc6) | Exported Function | 0x000000018001e580 | 0x0001e580
`public: __cdecl WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 199 (0xc7) | Exported Function | 0x000000018001e600 | 0x0001e600
`public: __cdecl WmiOrNode::WmiOrNode(class WmiOrNode const & __ptr64) __ptr64` | 200 (0xc8) | Exported Function | 0x000000018001e650 | 0x0001e650
`public: __cdecl WmiOrNode::WmiOrNode(class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 201 (0xc9) | Exported Function | 0x000000018001e6c0 | 0x0001e6c0
`public: __cdecl WmiRangeNode::WmiRangeNode(class WmiRangeNode const & __ptr64) __ptr64` | 202 (0xca) | Exported Function | 0x000000018001e720 | 0x0001e720
`public: __cdecl WmiRangeNode::WmiRangeNode(unsigned long,unsigned short * __ptr64,unsigned long,int,int,int,int,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 203 (0xcb) | Exported Function | 0x000000018001e7b0 | 0x0001e7b0
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode && __ptr64) __ptr64` | 204 (0xcc) | Exported Function | 0x000000018001e890 | 0x0001e890
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode const & __ptr64) __ptr64` | 205 (0xcd) | Exported Function | 0x000000018001e890 | 0x0001e890
`public: __cdecl WmiSignedIntegerNode::WmiSignedIntegerNode(unsigned short * __ptr64,long,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 206 (0xce) | Exported Function | 0x000000018001e8f0 | 0x0001e8f0
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode && __ptr64) __ptr64` | 207 (0xcf) | Exported Function | 0x000000018001e970 | 0x0001e970
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode const & __ptr64) __ptr64` | 208 (0xd0) | Exported Function | 0x000000018001e970 | 0x0001e970
`public: __cdecl WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,long,long,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 209 (0xd1) | Exported Function | 0x000000018001e9d0 | 0x0001e9d0
`public: __cdecl WmiStringNode::WmiStringNode(class WmiStringNode const & __ptr64) __ptr64` | 210 (0xd2) | Exported Function | 0x000000018001ea70 | 0x0001ea70
`public: __cdecl WmiStringNode::WmiStringNode(unsigned short * __ptr64,unsigned short * __ptr64,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 211 (0xd3) | Exported Function | 0x0000000180003510 | 0x00003510
`public: __cdecl WmiStringRangeNode::WmiStringRangeNode(class WmiStringRangeNode const & __ptr64) __ptr64` | 212 (0xd4) | Exported Function | 0x000000018001ead0 | 0x0001ead0
`public: __cdecl WmiStringRangeNode::WmiStringRangeNode(unsigned short * __ptr64,unsigned long,int,int,int,int,unsigned short * __ptr64,unsigned short * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 213 (0xd5) | Exported Function | 0x0000000180003190 | 0x00003190
`public: __cdecl WmiTreeNode::WmiTreeNode(class WmiTreeNode * __ptr64) __ptr64` | 216 (0xd8) | Exported Function | 0x000000018001eb30 | 0x0001eb30
`public: __cdecl WmiTreeNode::WmiTreeNode(class WmiTreeNode const & __ptr64) __ptr64` | 214 (0xd6) | Exported Function | 0x000000018001eb30 | 0x0001eb30
`public: __cdecl WmiTreeNode::WmiTreeNode(unsigned long,void * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64,class WmiTreeNode * __ptr64) __ptr64` | 215 (0xd7) | Exported Function | 0x000000018001eb70 | 0x0001eb70
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNode * __ptr64) __ptr64` | 219 (0xdb) | Exported Function | 0x000000018001ebe0 | 0x0001ebe0
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator * __ptr64) __ptr64` | 218 (0xda) | Exported Function | 0x000000018001ebc0 | 0x0001ebc0
`public: __cdecl WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator const & __ptr64) __ptr64` | 217 (0xd9) | Exported Function | 0x000000018001ebc0 | 0x0001ebc0
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode && __ptr64) __ptr64` | 220 (0xdc) | Exported Function | 0x000000018001ec00 | 0x0001ec00
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode const & __ptr64) __ptr64` | 221 (0xdd) | Exported Function | 0x000000018001ec00 | 0x0001ec00
`public: __cdecl WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(unsigned short * __ptr64,unsigned long,unsigned long,class WmiTreeNode * __ptr64) __ptr64` | 222 (0xde) | Exported Function | 0x0000000180002ca0 | 0x00002ca0
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(unsigned short const * __ptr64) __ptr64` | 111 (0x6f) | Exported Function | 0x000000018000ebe0 | 0x0000ebe0
`public: class ProvIpAddressType & __ptr64 __cdecl ProvIpAddressType::operator=(class ProvIpAddressType const & __ptr64) __ptr64` | 331 (0x14b) | Exported Function | 0x0000000180011f50 | 0x00011f50
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(unsigned char const * __ptr64,unsigned long) __ptr64` | 110 (0x6e) | Exported Function | 0x000000018000eb60 | 0x0000eb60
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(class ProvOctetString const & __ptr64) __ptr64` | 109 (0x6d) | Exported Function | 0x000000018000eae0 | 0x0000eae0
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,long const & __ptr64) __ptr64` | 42 (0x2a) | Exported Function | 0x000000018000c780 | 0x0000c780
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 40 (0x28) | Exported Function | 0x000000018000c4d0 | 0x0000c4d0
`public: __cdecl ProvEventObject::ProvEventObject(class ProvEventObject const & __ptr64) __ptr64` | 44 (0x2c) | Exported Function | 0x000000018000a400 | 0x0000a400
`public: __cdecl ProvEventObject::ProvEventObject(unsigned short const * __ptr64) __ptr64` | 45 (0x2d) | Exported Function | 0x000000018000adc0 | 0x0000adc0
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(class ProvFixedLengthDisplayStringType const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x000000018000cb10 | 0x0000cb10
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x000000018000c9a0 | 0x0000c9a0
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x000000018000ca00 | 0x0000ca00
`public: __cdecl ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x000000018000ca60 | 0x0000ca60
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(class ProvFixedLengthOctetStringType const & __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x000000018000ce40 | 0x0000ce40
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x000000018000cb70 | 0x0000cb70
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x000000018000cc10 | 0x0000cc10
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,unsigned char const * __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x000000018000ccc0 | 0x0000ccc0
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64,class ProvInteger const & __ptr64) __ptr64` | 43 (0x2b) | Exported Function | 0x000000018000c890 | 0x0000c890
`public: __cdecl ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x000000018000cd70 | 0x0000cd70
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x000000018000cef0 | 0x0000cef0
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,class ProvOpaque const & __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x000000018000cf90 | 0x0000cf90
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,unsigned char const * __ptr64,unsigned long) __ptr64` | 57 (0x39) | Exported Function | 0x000000018000d040 | 0x0000d040
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x000000018000d100 | 0x0000d100
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(class ProvFixedLengthPhysAddressType const & __ptr64) __ptr64` | 63 (0x3f) | Exported Function | 0x000000018000d3d0 | 0x0000d3d0
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x000000018000d280 | 0x0000d280
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x000000018000d2f0 | 0x0000d2f0
`public: __cdecl ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const & __ptr64,unsigned short const * __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x000000018000d350 | 0x0000d350
`public: __cdecl ProvFixedType::ProvFixedType(class ProvFixedType const & __ptr64) __ptr64` | 64 (0x40) | Exported Function | 0x000000018000d430 | 0x0000d430
`public: __cdecl ProvFixedType::ProvFixedType(unsigned long) __ptr64` | 65 (0x41) | Exported Function | 0x000000018000d450 | 0x0000d450
`public: __cdecl ProvGauge::ProvGauge(class ProvGauge const & __ptr64) __ptr64` | 66 (0x42) | Exported Function | 0x000000018001c0b0 | 0x0001c0b0
`public: __cdecl ProvGauge::ProvGauge(long) __ptr64` | 67 (0x43) | Exported Function | 0x000000018000d470 | 0x0000d470
`public: __cdecl ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(class ProvFixedLengthOpaqueType const & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x000000018000d1d0 | 0x0000d1d0
`public: __cdecl ProvGaugeType::ProvGaugeType(class ProvGauge const & __ptr64,unsigned short const * __ptr64) __ptr64` | 69 (0x45) | Exported Function | 0x000000018000d5a0 | 0x0000d5a0
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(unsigned short const * __ptr64) __ptr64` | 41 (0x29) | Exported Function | 0x000000018000c6a0 | 0x0000c6a0
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 37 (0x25) | Exported Function | 0x000000018000c210 | 0x0000c210
`public: __cdecl ProvBitStringType::ProvBitStringType(class ProvBitStringType const & __ptr64) __ptr64` | 12 (0xc) | Exported Function | 0x000000018000b280 | 0x0000b280
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64) __ptr64` | 13 (0xd) | Exported Function | 0x000000018000b420 | 0x0000b420
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64,class ProvOctetString const & __ptr64) __ptr64` | 14 (0xe) | Exported Function | 0x000000018000b500 | 0x0000b500
`public: __cdecl ProvBitStringType::ProvBitStringType(unsigned short const * __ptr64,unsigned short const * __ptr64 * __ptr64,unsigned long const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x000000018000b680 | 0x0000b680
`public: __cdecl ProvCounter64::ProvCounter64(class ProvCounter64 const & __ptr64) __ptr64` | 16 (0x10) | Exported Function | 0x000000018001c010 | 0x0001c010
`public: __cdecl ProvCounter64::ProvCounter64(unsigned long,unsigned long) __ptr64` | 17 (0x11) | Exported Function | 0x000000018000b9b0 | 0x0000b9b0
`public: __cdecl ProvCounter64Type::ProvCounter64Type(class ProvCounter64 const & __ptr64) __ptr64` | 19 (0x13) | Exported Function | 0x000000018000ba60 | 0x0000ba60
`public: __cdecl ProvCounter64Type::ProvCounter64Type(class ProvCounter64Type const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x000000018000ba00 | 0x0000ba00
`public: __cdecl ProvCounter64Type::ProvCounter64Type(unsigned long,unsigned long) __ptr64` | 20 (0x14) | Exported Function | 0x000000018000bac0 | 0x0000bac0
`public: __cdecl ProvCounter64Type::ProvCounter64Type(unsigned short const * __ptr64) __ptr64` | 21 (0x15) | Exported Function | 0x000000018000bb20 | 0x0000bb20
`public: __cdecl ProvCounter64Type::ProvCounter64Type(void) __ptr64` | 22 (0x16) | Exported Function | 0x000000018000bb80 | 0x0000bb80
`public: __cdecl ProvCounter::ProvCounter(class ProvCounter const & __ptr64) __ptr64` | 23 (0x17) | Exported Function | 0x000000018001c060 | 0x0001c060
`public: __cdecl ProvEnumeratedType::ProvEnumeratedType(class ProvEnumeratedType const & __ptr64) __ptr64` | 39 (0x27) | Exported Function | 0x000000018000c330 | 0x0000c330
`public: __cdecl ProvCounter::ProvCounter(unsigned long) __ptr64` | 24 (0x18) | Exported Function | 0x000000018000bbe0 | 0x0000bbe0
`public: __cdecl ProvCounterType::ProvCounterType(class ProvCounterType const & __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x000000018000bc30 | 0x0000bc30
`public: __cdecl ProvCounterType::ProvCounterType(unsigned long) __ptr64` | 27 (0x1b) | Exported Function | 0x000000018000bd50 | 0x0000bd50
`public: __cdecl ProvCounterType::ProvCounterType(unsigned short const * __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x000000018000bde0 | 0x0000bde0
`public: __cdecl ProvCounterType::ProvCounterType(void) __ptr64` | 29 (0x1d) | Exported Function | 0x000000018000be80 | 0x0000be80
`public: __cdecl ProvDateTimeType::ProvDateTimeType(class ProvDateTimeType const & __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x000000018000bf10 | 0x0000bf10
`public: __cdecl ProvDateTimeType::ProvDateTimeType(class ProvOctetString const & __ptr64) __ptr64` | 31 (0x1f) | Exported Function | 0x000000018000bf90 | 0x0000bf90
`public: __cdecl ProvDateTimeType::ProvDateTimeType(unsigned short const * __ptr64) __ptr64` | 32 (0x20) | Exported Function | 0x000000018000c030 | 0x0000c030
`public: __cdecl ProvDateTimeType::ProvDateTimeType(void) __ptr64` | 33 (0x21) | Exported Function | 0x000000018000c0f0 | 0x0000c0f0
`public: __cdecl ProvDebugLog::ProvDebugLog(char) __ptr64` | 34 (0x22) | Exported Function | 0x000000018000a3f0 | 0x0000a3f0
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(class ProvDisplayStringType const & __ptr64) __ptr64` | 35 (0x23) | Exported Function | 0x000000018000c170 | 0x0000c170
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 36 (0x24) | Exported Function | 0x000000018000c1c0 | 0x0000c1c0
`public: __cdecl ProvDisplayStringType::ProvDisplayStringType(unsigned short const * __ptr64) __ptr64` | 38 (0x26) | Exported Function | 0x000000018000c2d0 | 0x0000c2d0
`public: __cdecl ProvCounterType::ProvCounterType(class ProvCounter const & __ptr64) __ptr64` | 26 (0x1a) | Exported Function | 0x000000018000bcc0 | 0x0000bcc0
`public: __cdecl ProvGaugeType::ProvGaugeType(class ProvGaugeType const & __ptr64) __ptr64` | 68 (0x44) | Exported Function | 0x000000018000d4c0 | 0x0000d4c0
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned long,unsigned short const * __ptr64) __ptr64` | 70 (0x46) | Exported Function | 0x000000018000d6a0 | 0x0000d6a0
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned short const * __ptr64) __ptr64` | 72 (0x48) | Exported Function | 0x000000018000d8a0 | 0x0000d8a0
`public: __cdecl ProvNull::ProvNull(void) __ptr64` | 104 (0x68) | Exported Function | 0x000000018000e930 | 0x0000e930
`public: __cdecl ProvNullType::ProvNullType(class ProvNull const & __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x000000018000e970 | 0x0000e970
`public: __cdecl ProvNullType::ProvNullType(class ProvNullType const & __ptr64) __ptr64` | 105 (0x69) | Exported Function | 0x000000018000e970 | 0x0000e970
`public: __cdecl ProvNullType::ProvNullType(void) __ptr64` | 107 (0x6b) | Exported Function | 0x000000018000ea00 | 0x0000ea00
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(char const * __ptr64) __ptr64` | 114 (0x72) | Exported Function | 0x000000018001c340 | 0x0001c340
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(class ProvObjectIdentifier const & __ptr64) __ptr64` | 113 (0x71) | Exported Function | 0x000000018001c2d0 | 0x0001c2d0
`public: __cdecl ProvObjectIdentifier::ProvObjectIdentifier(unsigned long const * __ptr64,unsigned long) __ptr64` | 115 (0x73) | Exported Function | 0x000000018001c430 | 0x0001c430
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifier const & __ptr64) __ptr64` | 117 (0x75) | Exported Function | 0x000000018000ed20 | 0x0000ed20
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifierType const & __ptr64) __ptr64` | 116 (0x74) | Exported Function | 0x000000018000ecb0 | 0x0000ecb0
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned long const * __ptr64,unsigned long) __ptr64` | 119 (0x77) | Exported Function | 0x000000018000ee20 | 0x0000ee20
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned short const * __ptr64) __ptr64` | 118 (0x76) | Exported Function | 0x000000018000ed90 | 0x0000ed90
`public: __cdecl ProvObjectIdentifierType::ProvObjectIdentifierType(void) __ptr64` | 120 (0x78) | Exported Function | 0x000000018000ee90 | 0x0000ee90
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(void) __ptr64` | 103 (0x67) | Exported Function | 0x000000018000e8a0 | 0x0000e8a0
`public: __cdecl ProvOctetString::ProvOctetString(class ProvOctetString const & __ptr64) __ptr64` | 121 (0x79) | Exported Function | 0x000000018001c4a0 | 0x0001c4a0
`public: __cdecl ProvOctetStringType::ProvOctetStringType(class ProvOctetString const & __ptr64,unsigned short const * __ptr64) __ptr64` | 124 (0x7c) | Exported Function | 0x000000018000efc0 | 0x0000efc0
`public: __cdecl ProvOctetStringType::ProvOctetStringType(class ProvOctetStringType const & __ptr64) __ptr64` | 123 (0x7b) | Exported Function | 0x000000018000ef00 | 0x0000ef00
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 125 (0x7d) | Exported Function | 0x000000018000f0a0 | 0x0000f0a0
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned short const * __ptr64) __ptr64` | 127 (0x7f) | Exported Function | 0x000000018000f290 | 0x0000f290
`public: __cdecl ProvOctetStringType::ProvOctetStringType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 126 (0x7e) | Exported Function | 0x000000018000f190 | 0x0000f190
`public: __cdecl ProvOpaque::ProvOpaque(class ProvOpaque const & __ptr64) __ptr64` | 128 (0x80) | Exported Function | 0x000000018000f340 | 0x0000f340
`public: __cdecl ProvOpaque::ProvOpaque(unsigned char const * __ptr64,unsigned long) __ptr64` | 129 (0x81) | Exported Function | 0x000000018000f3e0 | 0x0000f3e0
`public: __cdecl ProvOpaqueType::ProvOpaqueType(class ProvOpaque const & __ptr64,unsigned short const * __ptr64) __ptr64` | 131 (0x83) | Exported Function | 0x000000018000f540 | 0x0000f540
`public: __cdecl ProvOpaqueType::ProvOpaqueType(class ProvOpaqueType const & __ptr64) __ptr64` | 130 (0x82) | Exported Function | 0x000000018000f480 | 0x0000f480
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned char const * __ptr64,unsigned long,unsigned short const * __ptr64) __ptr64` | 132 (0x84) | Exported Function | 0x000000018000f620 | 0x0000f620
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned short const * __ptr64) __ptr64` | 134 (0x86) | Exported Function | 0x000000018000f810 | 0x0000f810
`public: __cdecl ProvOpaqueType::ProvOpaqueType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 133 (0x85) | Exported Function | 0x000000018000f710 | 0x0000f710
`public: __cdecl ProvOctetString::ProvOctetString(unsigned char const * __ptr64,unsigned long) __ptr64` | 122 (0x7a) | Exported Function | 0x000000018001c500 | 0x0001c500
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(unsigned short const * __ptr64) __ptr64` | 102 (0x66) | Exported Function | 0x000000018000e800 | 0x0000e800
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(unsigned long) __ptr64` | 101 (0x65) | Exported Function | 0x000000018000e770 | 0x0000e770
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(class ProvNetworkAddressType const & __ptr64) __ptr64` | 99 (0x63) | Exported Function | 0x000000018000e690 | 0x0000e690
`public: __cdecl ProvGaugeType::ProvGaugeType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 71 (0x47) | Exported Function | 0x000000018000d790 | 0x0000d790
`public: __cdecl ProvInteger::ProvInteger(class ProvInteger const & __ptr64) __ptr64` | 75 (0x4b) | Exported Function | 0x000000018001c100 | 0x0001c100
`public: __cdecl ProvInteger::ProvInteger(long) __ptr64` | 76 (0x4c) | Exported Function | 0x000000018000d9c0 | 0x0000d9c0
`public: __cdecl ProvIntegerType::ProvIntegerType(class ProvInteger const & __ptr64,unsigned short const * __ptr64) __ptr64` | 78 (0x4e) | Exported Function | 0x000000018000daf0 | 0x0000daf0
`public: __cdecl ProvIntegerType::ProvIntegerType(class ProvIntegerType const & __ptr64) __ptr64` | 77 (0x4d) | Exported Function | 0x000000018000da10 | 0x0000da10
`public: __cdecl ProvIntegerType::ProvIntegerType(long,unsigned short const * __ptr64) __ptr64` | 79 (0x4f) | Exported Function | 0x000000018000dbd0 | 0x0000dbd0
`public: __cdecl ProvIntegerType::ProvIntegerType(unsigned short const * __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x000000018000ddd0 | 0x0000ddd0
`public: __cdecl ProvIntegerType::ProvIntegerType(unsigned short const * __ptr64,unsigned short const * __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x000000018000dcc0 | 0x0000dcc0
`public: __cdecl ProvIpAddress::ProvIpAddress(char const * __ptr64) __ptr64` | 84 (0x54) | Exported Function | 0x000000018001c1b0 | 0x0001c1b0
`public: __cdecl ProvIpAddress::ProvIpAddress(class ProvIpAddress const & __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x000000018001c150 | 0x0001c150
`public: __cdecl ProvIpAddress::ProvIpAddress(unsigned long) __ptr64` | 83 (0x53) | Exported Function | 0x000000018000dea0 | 0x0000dea0
`public: __cdecl ProvIpAddressType::ProvIpAddressType(class ProvIpAddress const & __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x000000018000df60 | 0x0000df60
`public: __cdecl ProvIpAddressType::ProvIpAddressType(class ProvIpAddressType const & __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x000000018000def0 | 0x0000def0
`public: __cdecl ProvIpAddressType::ProvIpAddressType(unsigned long) __ptr64` | 87 (0x57) | Exported Function | 0x000000018000dfd0 | 0x0000dfd0
`public: __cdecl ProvIpAddressType::ProvIpAddressType(unsigned short const * __ptr64) __ptr64` | 88 (0x58) | Exported Function | 0x000000018000e060 | 0x0000e060
`public: __cdecl ProvIpAddressType::ProvIpAddressType(void) __ptr64` | 89 (0x59) | Exported Function | 0x000000018000e100 | 0x0000e100
`public: __cdecl ProvLexicon::ProvLexicon(void) __ptr64` | 90 (0x5a) | Exported Function | 0x000000018000e190 | 0x0000e190
`public: __cdecl ProvLexicon::~ProvLexicon(void) __ptr64` | 254 (0xfe) | Exported Function | 0x0000000180011250 | 0x00011250
`public: __cdecl ProvMacAddressType::ProvMacAddressType(class ProvMacAddressType const & __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x000000018000e1b0 | 0x0000e1b0
`public: __cdecl ProvMacAddressType::ProvMacAddressType(class ProvOctetString const & __ptr64) __ptr64` | 92 (0x5c) | Exported Function | 0x000000018000e210 | 0x0000e210
`public: __cdecl ProvMacAddressType::ProvMacAddressType(unsigned char const * __ptr64) __ptr64` | 93 (0x5d) | Exported Function | 0x000000018000e280 | 0x0000e280
`public: __cdecl ProvMacAddressType::ProvMacAddressType(unsigned short const * __ptr64) __ptr64` | 94 (0x5e) | Exported Function | 0x000000018000e2f0 | 0x0000e2f0
`public: __cdecl ProvMacAddressType::ProvMacAddressType(void) __ptr64` | 95 (0x5f) | Exported Function | 0x000000018000e380 | 0x0000e380
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(class ProvNegativeRangeType const & __ptr64) __ptr64` | 96 (0x60) | Exported Function | 0x000000018000e3f0 | 0x0000e3f0
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(long,long) __ptr64` | 97 (0x61) | Exported Function | 0x000000018000e420 | 0x0000e420
`public: __cdecl ProvNegativeRangeType::ProvNegativeRangeType(void) __ptr64` | 98 (0x62) | Exported Function | 0x000000018000e440 | 0x0000e440
`public: __cdecl ProvNetworkAddressType::ProvNetworkAddressType(class ProvIpAddress const & __ptr64) __ptr64` | 100 (0x64) | Exported Function | 0x000000018000e700 | 0x0000e700
`public: __cdecl ProvOSIAddressType::ProvOSIAddressType(class ProvOSIAddressType const & __ptr64) __ptr64` | 108 (0x6c) | Exported Function | 0x000000018000ea90 | 0x0000ea90
`unsigned short * __ptr64 __cdecl UnicodeStringDuplicate(unsigned short const * __ptr64)` | 950 (0x3b6) | Exported Function | 0x000000018001be80 | 0x0001be80


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


