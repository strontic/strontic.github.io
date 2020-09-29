---
title: provthrd.dll | WMI Provider Thread & Log Library
excerpt: What is provthrd.dll?
---

# provthrd.dll 

* File Path: `C:\Windows\SysWOW64\provthrd.dll`
* Description: WMI Provider Thread & Log Library

## Hashes

Type | Hash
-- | --
MD5 | `6C72B449A0DE38B4EC62A8163AE30BC6`
SHA1 | `D6283A293CA08BB7C64809798F3A7273F78B4A3D`
SHA256 | `DDA77140A10DC7F5C8CE543943ADB77FE9E65D3C02FBD345E6E9CB221CA7EDC5`
SHA384 | `B12A37E92A22B58E5BA52C82659940E19FBEA9A9F058ADEF955F95FFE19605519D108F275313D34A84E05F7F52A15377`
SHA512 | `5A4DBFAB62E242EF85A771A31169BA97FBF87DEFEFCF131B65F30FFC08BD605B0AB2D4E2A57CCD799D0CB7AF6F7EB3E52C309B5B503B40CC1AA7EDD1587D6539`
SSDEEP | `3072:yWCwT0Mju6LIDysjfBy8L01Kg2AQrvDFackoRfuqeNEgSQVq6xWbG2VYSQwUVAhW:yfTY1UDVNKD2DHk6kJd2oA`
IMP | `05FB7F62D29DC7B357EC1621C442764B`
PESHA1 | `F6B392CC35B29FF147E69DFE79B9BE8C9988F5F3`
PE256 | `EE4DCDBBCA28BDCD5B097DECF722F4BCB7CBE010F391173018C29565918B1BEB`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`char * __stdcall UnicodeToDbcsString(unsigned short const *)` | 951 (0x3b7) | Exported Function | 0x1001c9d0 | 0x0001c9d0
`public: static unsigned long __stdcall ProvAnalyser::OctCharToDecInteger(char)` | 814 (0x32e) | Exported Function | 0x1001a680 | 0x0001a680
`public: static unsigned long __stdcall ProvAnalyser::OctWCharToDecInteger(unsigned short)` | 815 (0x32f) | Exported Function | 0x1001a6a0 | 0x0001a6a0
`public: static unsigned short __stdcall ProvAnalyser::DecIntegerToDecWChar(unsigned char)` | 608 (0x260) | Exported Function | 0x100178d0 | 0x000178d0
`public: static unsigned short __stdcall ProvAnalyser::DecIntegerToHexWChar(unsigned char)` | 610 (0x262) | Exported Function | 0x10017930 | 0x00017930
`public: static unsigned short __stdcall ProvAnalyser::DecIntegerToOctWChar(unsigned char)` | 612 (0x264) | Exported Function | 0x10017990 | 0x00017990
`public: static void __stdcall ProvDebugLog::Closedown(void)` | 531 (0x213) | Exported Function | 0x1000f170 | 0x0000f170
`public: union ProvLexiconValue * __thiscall ProvLexicon::GetValue(void)` | 752 (0x2f0) | Exported Function | 0x1001a0b0 | 0x0001a0b0
`public: unsigned char * __thiscall ProvOctetString::GetValue(void)const ` | 756 (0x2f4) | Exported Function | 0x100092a0 | 0x000092a0
`public: unsigned char * __thiscall ProvOctetStringType::GetValue(void)const ` | 757 (0x2f5) | Exported Function | 0x1001a0d0 | 0x0001a0d0
`public: unsigned char * __thiscall ProvOpaque::GetValue(void)const ` | 758 (0x2f6) | Exported Function | 0x1001a0e0 | 0x0001a0e0
`public: unsigned char * __thiscall ProvOpaqueType::GetValue(void)const ` | 759 (0x2f7) | Exported Function | 0x1001a0f0 | 0x0001a0f0
`public: unsigned long & __thiscall ProvObjectIdentifier::operator[](unsigned long)const ` | 392 (0x188) | Exported Function | 0x1001cff0 | 0x0001cff0
`public: static unsigned long __stdcall ProvAnalyser::HexWCharToDecInteger(unsigned short)` | 774 (0x306) | Exported Function | 0x1001a180 | 0x0001a180
`public: unsigned long * __thiscall ProvObjectIdentifier::GetValue(void)const ` | 754 (0x2f2) | Exported Function | 0x1001d9c0 | 0x0001d9c0
`public: unsigned long __thiscall Conjunctions::GetRangeCount(void)` | 706 (0x2c2) | Exported Function | 0x100184e0 | 0x000184e0
`public: unsigned long __thiscall Disjunctions::GetConjunctionCount(void)` | 661 (0x295) | Exported Function | 0x100184e0 | 0x000184e0
`public: unsigned long __thiscall Disjunctions::GetDisjunctionCount(void)` | 666 (0x29a) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall PartitionSet::GetKeyIndex(void)` | 675 (0x2a3) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall PartitionSet::GetPartitionCount(void)` | 689 (0x2b1) | Exported Function | 0x10009290 | 0x00009290
`public: unsigned long __thiscall ProvBitStringType::GetValue(unsigned short * * &)const ` | 738 (0x2e2) | Exported Function | 0x10019ce0 | 0x00019ce0
`public: unsigned long __thiscall ProvCounter64::GetHighValue(void)const ` | 668 (0x29c) | Exported Function | 0x100092a0 | 0x000092a0
`public: unsigned long __thiscall ProvCounter64::GetLowValue(void)const ` | 680 (0x2a8) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall ProvCounter::GetValue(void)const ` | 740 (0x2e4) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall ProvCounterType::GetValue(void)const ` | 741 (0x2e5) | Exported Function | 0x10019eb0 | 0x00019eb0
`public: unsigned long __thiscall ProvDebugLog::GetLevel(void)` | 678 (0x2a6) | Exported Function | 0x1000f180 | 0x0000f180
`public: unsigned long __thiscall ProvGauge::GetValue(void)const ` | 746 (0x2ea) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long * __thiscall ProvObjectIdentifierType::GetValue(void)const ` | 755 (0x2f3) | Exported Function | 0x1001a0c0 | 0x0001a0c0
`public: unsigned long __thiscall ProvGaugeType::GetValue(void)const ` | 747 (0x2eb) | Exported Function | 0x10018490 | 0x00018490
`public: static unsigned long __stdcall ProvAnalyser::HexCharToDecInteger(char)` | 773 (0x305) | Exported Function | 0x1001a140 | 0x0001a140
`public: static unsigned long __stdcall ProvAnalyser::DecCharToDecInteger(char)` | 606 (0x25e) | Exported Function | 0x10017880 | 0x00017880
`public: int __thiscall WmiUnsignedIntegerNode::LexicographicallyBefore(unsigned long &)` | 806 (0x326) | Exported Function | 0x100246c0 | 0x000246c0
`public: long __thiscall ProvInteger::GetValue(void)const ` | 748 (0x2ec) | Exported Function | 0x1000f850 | 0x0000f850
`public: long __thiscall ProvIntegerType::GetValue(void)const ` | 749 (0x2ed) | Exported Function | 0x10018490 | 0x00018490
`public: long __thiscall ProvNegativeRangeType::GetLowerBound(void)` | 681 (0x2a9) | Exported Function | 0x1000f850 | 0x0000f850
`public: long __thiscall ProvNegativeRangeType::GetUpperBound(void)` | 736 (0x2e0) | Exported Function | 0x100092a0 | 0x000092a0
`public: long __thiscall WmiRangeNode::ComparePropertyName(class WmiRangeNode &)` | 533 (0x215) | Exported Function | 0x10020cf0 | 0x00020cf0
`public: long __thiscall WmiSignedIntegerNode::GetValue(void)` | 764 (0x2fc) | Exported Function | 0x10009310 | 0x00009310
`public: long __thiscall WmiSignedIntegerRangeNode::LowerBound(void)` | 807 (0x327) | Exported Function | 0x10009270 | 0x00009270
`public: long __thiscall WmiSignedIntegerRangeNode::UpperBound(void)` | 952 (0x3b8) | Exported Function | 0x100092f0 | 0x000092f0
`public: long __thiscall WmiValueNode::ComparePropertyName(class WmiValueNode &)` | 534 (0x216) | Exported Function | 0x10020cf0 | 0x00020cf0
`public: static char __stdcall ProvAnalyser::DecIntegerToDecChar(unsigned char)` | 607 (0x25f) | Exported Function | 0x100178b0 | 0x000178b0
`public: static char __stdcall ProvAnalyser::DecIntegerToHexChar(unsigned char)` | 609 (0x261) | Exported Function | 0x10017900 | 0x00017900
`public: static unsigned long __stdcall ProvAnalyser::DecWCharToDecInteger(unsigned short)` | 613 (0x265) | Exported Function | 0x100179c0 | 0x000179c0
`public: static char __stdcall ProvAnalyser::DecIntegerToOctChar(unsigned char)` | 611 (0x263) | Exported Function | 0x10017970 | 0x00017970
`public: static class ProvDebugLog * ProvDebugLog::s_aLogs` | 965 (0x3c5) | Exported Function | 0x10036d9c | 0x00036d9c
`public: static class ProvDebugLog * ProvDebugLog::s_ProvDebugLog` | 963 (0x3c3) | Exported Function | 0x10036000 | 0x00036000
`public: static int __stdcall ProvAnalyser::IsAlpha(unsigned short)` | 785 (0x311) | Exported Function | 0x1001a220 | 0x0001a220
`public: static int __stdcall ProvAnalyser::IsAlphaNumeric(unsigned short)` | 786 (0x312) | Exported Function | 0x1001a240 | 0x0001a240
`public: static int __stdcall ProvAnalyser::IsDecimal(unsigned short)` | 787 (0x313) | Exported Function | 0x1001a270 | 0x0001a270
`public: static int __stdcall ProvAnalyser::IsEof(unsigned short)` | 788 (0x314) | Exported Function | 0x1001a290 | 0x0001a290
`public: static int __stdcall ProvAnalyser::IsHex(unsigned short)` | 789 (0x315) | Exported Function | 0x1001a2b0 | 0x0001a2b0
`public: static int __stdcall ProvAnalyser::IsLeadingDecimal(unsigned short)` | 790 (0x316) | Exported Function | 0x1001a2d0 | 0x0001a2d0
`public: static int __stdcall ProvAnalyser::IsOctal(unsigned short)` | 792 (0x318) | Exported Function | 0x1001a300 | 0x0001a300
`public: static int __stdcall ProvAnalyser::IsWhitespace(unsigned short)` | 799 (0x31f) | Exported Function | 0x1001a340 | 0x0001a340
`public: static int __stdcall ProvDebugLog::Startup(void)` | 925 (0x39d) | Exported Function | 0x1000f1e0 | 0x0000f1e0
`public: static long ProvDebugLog::s_ReferenceCount` | 964 (0x3c4) | Exported Function | 0x10037108 | 0x00037108
`public: static class ProvDebugLog * __stdcall ProvDebugLog::GetProvDebugLog(char)` | 693 (0x2b5) | Exported Function | 0x1000f1b0 | 0x0000f1b0
`public: int __thiscall WmiUnsignedIntegerNode::LexicographicallyAfter(unsigned long &)` | 803 (0x323) | Exported Function | 0x10024570 | 0x00024570
`public: unsigned long __thiscall ProvIpAddress::GetValue(void)const ` | 750 (0x2ee) | Exported Function | 0x100092a0 | 0x000092a0
`public: unsigned long __thiscall ProvNetworkAddressType::GetValue(void)const ` | 753 (0x2f1) | Exported Function | 0x1001a0a0 | 0x0001a0a0
`public: virtual __thiscall ProvAnalyser::~ProvAnalyser(void)` | 232 (0xe8) | Exported Function | 0x100136a0 | 0x000136a0
`public: virtual __thiscall ProvBitStringType::~ProvBitStringType(void)` | 233 (0xe9) | Exported Function | 0x100136f0 | 0x000136f0
`public: virtual __thiscall ProvCounter64::~ProvCounter64(void)` | 234 (0xea) | Exported Function | 0x10013800 | 0x00013800
`public: virtual __thiscall ProvCounter64Type::~ProvCounter64Type(void)` | 235 (0xeb) | Exported Function | 0x10013850 | 0x00013850
`public: virtual __thiscall ProvCounter::~ProvCounter(void)` | 236 (0xec) | Exported Function | 0x100138a0 | 0x000138a0
`public: virtual __thiscall ProvCounterType::~ProvCounterType(void)` | 237 (0xed) | Exported Function | 0x100138f0 | 0x000138f0
`public: virtual __thiscall ProvDateTimeType::~ProvDateTimeType(void)` | 238 (0xee) | Exported Function | 0x10013960 | 0x00013960
`public: virtual __thiscall ProvDisplayStringType::~ProvDisplayStringType(void)` | 239 (0xef) | Exported Function | 0x100139e0 | 0x000139e0
`public: virtual __thiscall ProvEnumeratedType::~ProvEnumeratedType(void)` | 240 (0xf0) | Exported Function | 0x10013a30 | 0x00013a30
`public: virtual __thiscall ProvEventObject::~ProvEventObject(void)` | 241 (0xf1) | Exported Function | 0x1000f7f0 | 0x0000f7f0
`public: virtual __thiscall ProvFixedLengthDisplayStringType::~ProvFixedLengthDisplayStringType(void)` | 242 (0xf2) | Exported Function | 0x10013b40 | 0x00013b40
`public: virtual __thiscall ProvFixedLengthOctetStringType::~ProvFixedLengthOctetStringType(void)` | 243 (0xf3) | Exported Function | 0x10013ba0 | 0x00013ba0
`public: virtual __thiscall ProvAnalyser::operator void *(void)` | 393 (0x189) | Exported Function | 0x10014ea0 | 0x00014ea0
`public: virtual __thiscall ProvFixedLengthOpaqueType::~ProvFixedLengthOpaqueType(void)` | 244 (0xf4) | Exported Function | 0x10013c10 | 0x00013c10
`public: virtual __thiscall ProvFixedType::~ProvFixedType(void)` | 246 (0xf6) | Exported Function | 0x10013ce0 | 0x00013ce0
`public: virtual __thiscall ProvGauge::~ProvGauge(void)` | 247 (0xf7) | Exported Function | 0x10013cf0 | 0x00013cf0
`public: virtual __thiscall ProvGaugeType::~ProvGaugeType(void)` | 248 (0xf8) | Exported Function | 0x10013d40 | 0x00013d40
`public: virtual __thiscall ProvInstanceType::operator void *(void)` | 394 (0x18a) | Exported Function | 0x10014eb0 | 0x00014eb0
`public: virtual __thiscall ProvInstanceType::~ProvInstanceType(void)` | 249 (0xf9) | Exported Function | 0x10013dc0 | 0x00013dc0
`public: virtual __thiscall ProvInteger::~ProvInteger(void)` | 250 (0xfa) | Exported Function | 0x10013dd0 | 0x00013dd0
`public: virtual __thiscall ProvIntegerType::~ProvIntegerType(void)` | 251 (0xfb) | Exported Function | 0x10013e20 | 0x00013e20
`public: virtual __thiscall ProvIpAddress::~ProvIpAddress(void)` | 252 (0xfc) | Exported Function | 0x10013ea0 | 0x00013ea0
`public: virtual __thiscall ProvIpAddressType::~ProvIpAddressType(void)` | 253 (0xfd) | Exported Function | 0x10013ef0 | 0x00013ef0
`public: virtual __thiscall ProvMacAddressType::~ProvMacAddressType(void)` | 255 (0xff) | Exported Function | 0x10013fb0 | 0x00013fb0
`public: virtual __thiscall ProvNegativeRangeType::~ProvNegativeRangeType(void)` | 256 (0x100) | Exported Function | 0x10014010 | 0x00014010
`public: virtual __thiscall ProvNetworkAddressType::~ProvNetworkAddressType(void)` | 257 (0x101) | Exported Function | 0x100140c0 | 0x000140c0
`public: virtual __thiscall ProvFixedLengthPhysAddressType::~ProvFixedLengthPhysAddressType(void)` | 245 (0xf5) | Exported Function | 0x10013c80 | 0x00013c80
`public: unsigned long __thiscall ProvIpAddressType::GetValue(void)const ` | 751 (0x2ef) | Exported Function | 0x1001a0a0 | 0x0001a0a0
`public: virtual __thiscall PartitionSet::~PartitionSet(void)` | 231 (0xe7) | Exported Function | 0x1001f1a0 | 0x0001f1a0
`public: unsigned short * __thiscall WmiStringRangeNode::UpperBound(void)` | 953 (0x3b9) | Exported Function | 0x100092f0 | 0x000092f0
`public: unsigned long __thiscall ProvObjectIdentifier::GetValueLength(void)const ` | 767 (0x2ff) | Exported Function | 0x1001d9d0 | 0x0001d9d0
`public: unsigned long __thiscall ProvObjectIdentifierType::GetValueLength(void)const ` | 768 (0x300) | Exported Function | 0x1001a100 | 0x0001a100
`public: unsigned long __thiscall ProvOctetString::GetValueLength(void)const ` | 769 (0x301) | Exported Function | 0x10009290 | 0x00009290
`public: unsigned long __thiscall ProvOctetStringType::GetValueLength(void)const ` | 770 (0x302) | Exported Function | 0x1001a110 | 0x0001a110
`public: unsigned long __thiscall ProvOpaque::GetValueLength(void)const ` | 771 (0x303) | Exported Function | 0x1001a120 | 0x0001a120
`public: unsigned long __thiscall ProvOpaqueType::GetValueLength(void)const ` | 772 (0x304) | Exported Function | 0x1001a130 | 0x0001a130
`public: unsigned long __thiscall ProvPositiveRangeType::GetLowerBound(void)` | 682 (0x2aa) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall ProvPositiveRangeType::GetUpperBound(void)` | 737 (0x2e1) | Exported Function | 0x100092a0 | 0x000092a0
`public: unsigned long __thiscall ProvTimeTicks::GetValue(void)const ` | 761 (0x2f9) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall ProvTimeTicksType::GetValue(void)const ` | 762 (0x2fa) | Exported Function | 0x10019eb0 | 0x00019eb0
`public: unsigned long __thiscall ProvUInteger32::GetValue(void)const ` | 763 (0x2fb) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall WmiRangeNode::GetIndex(void)` | 669 (0x29d) | Exported Function | 0x10021b50 | 0x00021b50
`public: unsigned short * __thiscall WmiValueNode::GetPropertyName(void)` | 692 (0x2b4) | Exported Function | 0x10009340 | 0x00009340
`public: unsigned long __thiscall WmiTreeNode::GetType(void)` | 735 (0x2df) | Exported Function | 0x1000f850 | 0x0000f850
`public: unsigned long __thiscall WmiUnsignedIntegerRangeNode::LowerBound(void)` | 809 (0x329) | Exported Function | 0x10009270 | 0x00009270
`public: unsigned long __thiscall WmiUnsignedIntegerRangeNode::UpperBound(void)` | 954 (0x3ba) | Exported Function | 0x100092f0 | 0x000092f0
`public: unsigned long __thiscall WmiValueNode::GetIndex(void)` | 670 (0x29e) | Exported Function | 0x10021b50 | 0x00021b50
`public: unsigned short * __thiscall CBString::GetString(void)` | 710 (0x2c6) | Exported Function | 0x100184e0 | 0x000184e0
`public: unsigned short * __thiscall ProvDateTimeType::GetValue(void)const ` | 742 (0x2e6) | Exported Function | 0x10019ec0 | 0x00019ec0
`public: unsigned short * __thiscall ProvDisplayStringType::GetValue(void)const ` | 743 (0x2e7) | Exported Function | 0x1001a040 | 0x0001a040
`public: unsigned short * __thiscall ProvEnumeratedType::GetValue(void)const ` | 744 (0x2e8) | Exported Function | 0x100186d0 | 0x000186d0
`public: unsigned short * __thiscall ProvFixedLengthDisplayStringType::GetValue(void)const ` | 745 (0x2e9) | Exported Function | 0x10018750 | 0x00018750
`public: unsigned short * __thiscall ProvRowStatusType::GetValue(void)const ` | 760 (0x2f8) | Exported Function | 0x10019630 | 0x00019630
`public: unsigned short * __thiscall WmiRangeNode::GetPropertyName(void)` | 691 (0x2b3) | Exported Function | 0x10009340 | 0x00009340
`public: unsigned short * __thiscall WmiStringNode::GetValue(void)` | 765 (0x2fd) | Exported Function | 0x10009310 | 0x00009310
`public: unsigned short * __thiscall WmiStringRangeNode::LowerBound(void)` | 808 (0x328) | Exported Function | 0x10009270 | 0x00009270
`public: unsigned long __thiscall WmiUnsignedIntegerNode::GetValue(void)` | 766 (0x2fe) | Exported Function | 0x10009310 | 0x00009310
`public: int __thiscall WmiStringNode::LexicographicallyBefore(unsigned short * &)` | 805 (0x325) | Exported Function | 0x100245d0 | 0x000245d0
`public: int __thiscall WmiStringNode::LexicographicallyAfter(unsigned short * &)` | 802 (0x322) | Exported Function | 0x100244f0 | 0x000244f0
`public: int __thiscall WmiSignedIntegerNode::LexicographicallyBefore(long &)` | 804 (0x324) | Exported Function | 0x100245a0 | 0x000245a0
`public: class WmiNullNode & __thiscall WmiNullNode::operator=(class WmiNullNode &&)` | 357 (0x165) | Exported Function | 0x1001fb80 | 0x0001fb80
`public: class WmiNullNode & __thiscall WmiNullNode::operator=(class WmiNullNode const &)` | 358 (0x166) | Exported Function | 0x1001fb80 | 0x0001fb80
`public: class WmiNullRangeNode & __thiscall WmiNullRangeNode::operator=(class WmiNullRangeNode const &)` | 359 (0x167) | Exported Function | 0x1001fba0 | 0x0001fba0
`public: class WmiOperatorEqualNode & __thiscall WmiOperatorEqualNode::operator=(class WmiOperatorEqualNode const &)` | 360 (0x168) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorEqualOrGreaterNode & __thiscall WmiOperatorEqualOrGreaterNode::operator=(class WmiOperatorEqualOrGreaterNode const &)` | 361 (0x169) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorEqualOrLessNode & __thiscall WmiOperatorEqualOrLessNode::operator=(class WmiOperatorEqualOrLessNode const &)` | 362 (0x16a) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorGreaterNode & __thiscall WmiOperatorGreaterNode::operator=(class WmiOperatorGreaterNode const &)` | 363 (0x16b) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorIsANode & __thiscall WmiOperatorIsANode::operator=(class WmiOperatorIsANode const &)` | 364 (0x16c) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorLessNode & __thiscall WmiOperatorLessNode::operator=(class WmiOperatorLessNode const &)` | 365 (0x16d) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorLikeNode & __thiscall WmiOperatorLikeNode::operator=(class WmiOperatorLikeNode const &)` | 366 (0x16e) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorNode & __thiscall WmiOperatorNode::operator=(class WmiOperatorNode const &)` | 367 (0x16f) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorNotEqualNode & __thiscall WmiOperatorNotEqualNode::operator=(class WmiOperatorNotEqualNode const &)` | 368 (0x170) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiNotNode & __thiscall WmiNotNode::operator=(class WmiNotNode const &)` | 356 (0x164) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOperatorNotIsANode & __thiscall WmiOperatorNotIsANode::operator=(class WmiOperatorNotIsANode const &)` | 369 (0x171) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiOrNode & __thiscall WmiOrNode::operator=(class WmiOrNode const &)` | 371 (0x173) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiRangeNode & __thiscall WmiRangeNode::operator=(class WmiRangeNode const &)` | 372 (0x174) | Exported Function | 0x1001fbc0 | 0x0001fbc0
`public: class WmiRangeNode * __thiscall Conjunctions::GetRange(unsigned long)` | 694 (0x2b6) | Exported Function | 0x10023df0 | 0x00023df0
`public: class WmiRangeNode * __thiscall PartitionSet::GetRange(void)` | 695 (0x2b7) | Exported Function | 0x100092a0 | 0x000092a0
`public: class WmiSignedIntegerNode & __thiscall WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode &&)` | 373 (0x175) | Exported Function | 0x1001fc10 | 0x0001fc10
`public: class WmiSignedIntegerNode & __thiscall WmiSignedIntegerNode::operator=(class WmiSignedIntegerNode const &)` | 374 (0x176) | Exported Function | 0x1001fc10 | 0x0001fc10
`public: class WmiSignedIntegerRangeNode & __thiscall WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode &&)` | 375 (0x177) | Exported Function | 0x1001fc40 | 0x0001fc40
`public: class WmiSignedIntegerRangeNode & __thiscall WmiSignedIntegerRangeNode::operator=(class WmiSignedIntegerRangeNode const &)` | 376 (0x178) | Exported Function | 0x1001fc40 | 0x0001fc40
`public: class WmiStringNode & __thiscall WmiStringNode::operator=(class WmiStringNode const &)` | 377 (0x179) | Exported Function | 0x1001fc10 | 0x0001fc10
`public: class WmiStringRangeNode & __thiscall WmiStringRangeNode::operator=(class WmiStringRangeNode const &)` | 378 (0x17a) | Exported Function | 0x1001fc40 | 0x0001fc40
`public: class WmiTreeNode & __thiscall WmiTreeNode::operator=(class WmiTreeNode const &)` | 379 (0x17b) | Exported Function | 0x1001fc70 | 0x0001fc70
`public: class WmiTreeNode * __thiscall WmiTreeNode::GetLeft(void)` | 676 (0x2a4) | Exported Function | 0x10009290 | 0x00009290
`public: class WmiOperatorNotLikeNode & __thiscall WmiOperatorNotLikeNode::operator=(class WmiOperatorNotLikeNode const &)` | 370 (0x172) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class WmiTreeNode * __thiscall WmiTreeNode::GetParent(void)` | 686 (0x2ae) | Exported Function | 0x1001a0a0 | 0x0001a0a0
`public: class WmiAndNode & __thiscall WmiAndNode::operator=(class WmiAndNode const &)` | 355 (0x163) | Exported Function | 0x1001fb60 | 0x0001fb60
`public: class ProvValue & __thiscall ProvUInteger32::operator=(class ProvUInteger32 const &)` | 352 (0x160) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvMacAddressType & __thiscall ProvMacAddressType::operator=(class ProvMacAddressType const &)` | 333 (0x14d) | Exported Function | 0x10014970 | 0x00014970
`public: class ProvNegativeRangeType & __thiscall ProvNegativeRangeType::operator=(class ProvNegativeRangeType const &)` | 334 (0x14e) | Exported Function | 0x10014a30 | 0x00014a30
`public: class ProvNetworkAddressType & __thiscall ProvNetworkAddressType::operator=(class ProvNetworkAddressType const &)` | 335 (0x14f) | Exported Function | 0x10014a80 | 0x00014a80
`public: class ProvNullType & __thiscall ProvNullType::operator=(class ProvNullType const &)` | 337 (0x151) | Exported Function | 0x10014a30 | 0x00014a30
`public: class ProvObjectIdentifier * __thiscall ProvObjectIdentifier::Cut(class ProvObjectIdentifier &)const ` | 603 (0x25b) | Exported Function | 0x1001d560 | 0x0001d560
`public: class ProvObjectIdentifier __thiscall ProvObjectIdentifier::operator+(class ProvObjectIdentifier const &)const ` | 396 (0x18c) | Exported Function | 0x1001d020 | 0x0001d020
`public: class ProvObjectIdentifierType & __thiscall ProvObjectIdentifierType::operator=(class ProvObjectIdentifierType const &)` | 340 (0x154) | Exported Function | 0x10014b70 | 0x00014b70
`public: class ProvOctetStringType & __thiscall ProvOctetStringType::operator=(class ProvOctetStringType const &)` | 342 (0x156) | Exported Function | 0x10014bd0 | 0x00014bd0
`public: class ProvOpaqueType & __thiscall ProvOpaqueType::operator=(class ProvOpaqueType const &)` | 344 (0x158) | Exported Function | 0x10014c50 | 0x00014c50
`public: class ProvOSIAddressType & __thiscall ProvOSIAddressType::operator=(class ProvOSIAddressType const &)` | 338 (0x152) | Exported Function | 0x100148c0 | 0x000148c0
`public: class ProvPhysAddressType & __thiscall ProvPhysAddressType::operator=(class ProvPhysAddressType const &)` | 345 (0x159) | Exported Function | 0x100148c0 | 0x000148c0
`public: class ProvPositiveRangedType & __thiscall ProvPositiveRangedType::operator=(class ProvPositiveRangedType const &)` | 347 (0x15b) | Exported Function | 0x10014ad0 | 0x00014ad0
`public: class QueryPreprocessor & __thiscall QueryPreprocessor::operator=(class QueryPreprocessor const &)` | 354 (0x162) | Exported Function | 0x10014b20 | 0x00014b20
`public: class ProvPositiveRangeType & __thiscall ProvPositiveRangeType::operator=(class ProvPositiveRangeType const &)` | 346 (0x15a) | Exported Function | 0x10014a30 | 0x00014a30
`public: class ProvTimeTicksType & __thiscall ProvTimeTicksType::operator=(class ProvTimeTicksType const &)` | 350 (0x15e) | Exported Function | 0x10014850 | 0x00014850
`public: class ProvUDPAddressType & __thiscall ProvUDPAddressType::operator=(class ProvUDPAddressType const &)` | 351 (0x15f) | Exported Function | 0x10014970 | 0x00014970
`public: class ProvValue & __thiscall ProvCounter64::operator=(class ProvCounter64 const &)` | 310 (0x136) | Exported Function | 0x10014800 | 0x00014800
`public: class ProvValue & __thiscall ProvCounter::operator=(class ProvCounter const &)` | 312 (0x138) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvValue & __thiscall ProvGauge::operator=(class ProvGauge const &)` | 325 (0x145) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvValue & __thiscall ProvInteger::operator=(class ProvInteger const &)` | 328 (0x148) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvValue & __thiscall ProvIpAddress::operator=(class ProvIpAddress const &)` | 330 (0x14a) | Exported Function | 0x10014a50 | 0x00014a50
`public: class ProvValue & __thiscall ProvNull::operator=(class ProvNull const &)` | 336 (0x150) | Exported Function | 0x10014b20 | 0x00014b20
`public: class ProvValue & __thiscall ProvObjectIdentifier::operator=(class ProvObjectIdentifier const &)` | 339 (0x153) | Exported Function | 0x10014b30 | 0x00014b30
`public: class ProvValue & __thiscall ProvOctetString::operator=(class ProvOctetString const &)` | 341 (0x155) | Exported Function | 0x10014ba0 | 0x00014ba0
`public: class ProvValue & __thiscall ProvOpaque::operator=(class ProvOpaque const &)` | 343 (0x157) | Exported Function | 0x10014c10 | 0x00014c10
`public: class ProvValue & __thiscall ProvTimeTicks::operator=(class ProvTimeTicks const &)` | 349 (0x15d) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvRowStatusType & __thiscall ProvRowStatusType::operator=(class ProvRowStatusType const &)` | 348 (0x15c) | Exported Function | 0x10014c90 | 0x00014c90
`public: class WmiTreeNode * __thiscall WmiTreeNode::GetRight(void)` | 707 (0x2c3) | Exported Function | 0x10019eb0 | 0x00019eb0
`public: class WmiTreeNode * __thiscall WmiTreeNode::SetLeft(class WmiTreeNode *)` | 897 (0x381) | Exported Function | 0x10025280 | 0x00025280
`public: class WmiTreeNode * __thiscall WmiTreeNode::SetParent(class WmiTreeNode *)` | 901 (0x385) | Exported Function | 0x100252a0 | 0x000252a0
`public: int __thiscall ProvInstanceType::operator!=(class ProvInstanceType const &)const ` | 389 (0x185) | Exported Function | 0x10014d10 | 0x00014d10
`public: int __thiscall ProvInstanceType::operator==(class ProvInstanceType const &)const ` | 386 (0x182) | Exported Function | 0x10014cb0 | 0x00014cb0
`public: int __thiscall ProvInteger::Equivalent(class ProvInteger const &)const ` | 627 (0x273) | Exported Function | 0x10017c50 | 0x00017c50
`public: int __thiscall ProvIpAddress::Equivalent(class ProvIpAddress const &)const ` | 630 (0x276) | Exported Function | 0x10017d10 | 0x00017d10
`public: int __thiscall ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const &,unsigned long)const ` | 637 (0x27d) | Exported Function | 0x1001d790 | 0x0001d790
`public: int __thiscall ProvObjectIdentifier::operator!=(class ProvObjectIdentifier const &)const ` | 390 (0x186) | Exported Function | 0x10014d30 | 0x00014d30
`public: int __thiscall ProvObjectIdentifier::operator<(class ProvObjectIdentifier const &)const ` | 397 (0x18d) | Exported Function | 0x10014ed0 | 0x00014ed0
`public: int __thiscall ProvObjectIdentifier::operator<=(class ProvObjectIdentifier const &)const ` | 398 (0x18e) | Exported Function | 0x10014ef0 | 0x00014ef0
`public: int __thiscall ProvObjectIdentifier::operator==(class ProvObjectIdentifier const &)const ` | 387 (0x183) | Exported Function | 0x10014ce0 | 0x00014ce0
`public: int __thiscall ProvObjectIdentifier::operator>(class ProvObjectIdentifier const &)const ` | 399 (0x18f) | Exported Function | 0x10014f10 | 0x00014f10
`public: int __thiscall ProvObjectIdentifier::operator>=(class ProvObjectIdentifier const &)const ` | 400 (0x190) | Exported Function | 0x10014f30 | 0x00014f30
`public: int __thiscall ProvObjectIdentifier::Prefix(unsigned long,class ProvObjectIdentifier &)const ` | 839 (0x347) | Exported Function | 0x1001bfd0 | 0x0001bfd0
`public: int __thiscall ProvGauge::Equivalent(class ProvGauge const &)const ` | 624 (0x270) | Exported Function | 0x10017c50 | 0x00017c50
`public: int __thiscall ProvObjectIdentifier::Suffix(unsigned long,class ProvObjectIdentifier &)const ` | 926 (0x39e) | Exported Function | 0x1001c850 | 0x0001c850
`public: int __thiscall ProvOpaque::Equivalent(class ProvOpaque const &)const ` | 643 (0x283) | Exported Function | 0x10017e80 | 0x00017e80
`public: int __thiscall ProvPositiveRangedType::Check(unsigned long const &)` | 527 (0x20f) | Exported Function | 0x10016d40 | 0x00016d40
`public: int __thiscall ProvPositiveRangedType::IsValid(void)` | 798 (0x31e) | Exported Function | 0x1000f850 | 0x0000f850
`public: int __thiscall ProvTimeTicks::Equivalent(class ProvTimeTicks const &)const ` | 646 (0x286) | Exported Function | 0x10017c50 | 0x00017c50
`public: int __thiscall ProvUInteger32::Equivalent(class ProvUInteger32 const &)const ` | 649 (0x289) | Exported Function | 0x10017c50 | 0x00017c50
`public: int __thiscall ProvValue::operator!=(class ProvValue const &)const ` | 391 (0x187) | Exported Function | 0x10014d10 | 0x00014d10
`public: int __thiscall ProvValue::operator==(class ProvValue const &)const ` | 388 (0x184) | Exported Function | 0x10014cb0 | 0x00014cb0
`public: int __thiscall WmiRangeNode::ClosedLowerBound(void)` | 529 (0x211) | Exported Function | 0x10009310 | 0x00009310
`public: int __thiscall WmiRangeNode::ClosedUpperBound(void)` | 530 (0x212) | Exported Function | 0x10009300 | 0x00009300
`public: int __thiscall WmiRangeNode::InfiniteLowerBound(void)` | 775 (0x307) | Exported Function | 0x10009280 | 0x00009280
`public: int __thiscall WmiRangeNode::InfiniteUpperBound(void)` | 776 (0x308) | Exported Function | 0x100092b0 | 0x000092b0
`public: int __thiscall WmiSignedIntegerNode::LexicographicallyAfter(long &)` | 801 (0x321) | Exported Function | 0x100244c0 | 0x000244c0
`public: int __thiscall ProvOctetString::Equivalent(class ProvOctetString const &)const ` | 640 (0x280) | Exported Function | 0x1001d850 | 0x0001d850
`public: int __thiscall ProvDebugLog::GetLogging(void)` | 679 (0x2a7) | Exported Function | 0x1000f190 | 0x0000f190
`public: int __thiscall ProvCounter::Equivalent(class ProvCounter const &)const ` | 621 (0x26d) | Exported Function | 0x10017c50 | 0x00017c50
`public: int __thiscall ProvCounter64::Equivalent(class ProvCounter64 const &)const ` | 618 (0x26a) | Exported Function | 0x10017bd0 | 0x00017bd0
`public: class WmiTreeNode * __thiscall WmiTreeNode::SetRight(class WmiTreeNode *)` | 905 (0x389) | Exported Function | 0x10025340 | 0x00025340
`public: class WmiTreeNode * __thiscall WmiTreeNodeIterator::GetIterator(void)` | 674 (0x2a2) | Exported Function | 0x1000f850 | 0x0000f850
`public: class WmiTreeNode * __thiscall WmiTreeNodeIterator::SetIterator(class WmiTreeNode *)` | 895 (0x37f) | Exported Function | 0x10025260 | 0x00025260
`public: class WmiTreeNodeIterator & __thiscall WmiTreeNodeIterator::operator=(class WmiTreeNodeIterator const &)` | 380 (0x17c) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class WmiUnsignedIntegerNode & __thiscall WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode &&)` | 381 (0x17d) | Exported Function | 0x1001fc10 | 0x0001fc10
`public: class WmiUnsignedIntegerNode & __thiscall WmiUnsignedIntegerNode::operator=(class WmiUnsignedIntegerNode const &)` | 382 (0x17e) | Exported Function | 0x1001fc10 | 0x0001fc10
`public: class WmiUnsignedIntegerRangeNode & __thiscall WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode &&)` | 383 (0x17f) | Exported Function | 0x1001fc40 | 0x0001fc40
`public: class WmiUnsignedIntegerRangeNode & __thiscall WmiUnsignedIntegerRangeNode::operator=(class WmiUnsignedIntegerRangeNode const &)` | 384 (0x180) | Exported Function | 0x1001fc40 | 0x0001fc40
`public: class WmiValueNode & __thiscall WmiValueNode::operator=(class WmiValueNode const &)` | 385 (0x181) | Exported Function | 0x1001fcb0 | 0x0001fcb0
`public: enum ProvLexicon::LexiconToken __thiscall ProvLexicon::GetToken(void)` | 734 (0x2de) | Exported Function | 0x100092a0 | 0x000092a0
`public: enum ProvRowStatusType::ProvRowStatusEnum __thiscall ProvRowStatusType::GetRowStatus(void)const ` | 709 (0x2c5) | Exported Function | 0x10018490 | 0x00018490
`public: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::PreProcess(void *,struct SQL_LEVEL_1_RPN_EXPRESSION *,class WmiTreeNode * &)` | 837 (0x345) | Exported Function | 0x10006990 | 0x00006990
`public: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::PreProcess(void *,struct SQL_LEVEL_1_RPN_EXPRESSION *,class WmiTreeNode *,unsigned long,unsigned short * *,class PartitionSet * &)` | 838 (0x346) | Exported Function | 0x10006510 | 0x00006510
`public: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::Query(unsigned short *,struct SQL_LEVEL_1_RPN_EXPRESSION * &)` | 869 (0x365) | Exported Function | 0x100052f0 | 0x000052f0
`public: enum WmiTriState __thiscall Conjunctions::Initialize(void)` | 778 (0x30a) | Exported Function | 0x10024370 | 0x00024370
`public: enum WmiTriState __thiscall Disjunctions::Initialize(void)` | 779 (0x30b) | Exported Function | 0x10008e50 | 0x00008e50
`public: enum WmiTriState __thiscall PartitionSet::Initialize(unsigned long)` | 780 (0x30c) | Exported Function | 0x100243c0 | 0x000243c0
`public: enum WmiTriState __thiscall WmiSignedIntegerRangeNode::GetIntersectingRange(class WmiSignedIntegerRangeNode &,class WmiSignedIntegerRangeNode * &)` | 671 (0x29f) | Exported Function | 0x10021b60 | 0x00021b60
`public: enum WmiTriState __thiscall WmiSignedIntegerRangeNode::GetOverlappingRange(class WmiSignedIntegerRangeNode &,class WmiSignedIntegerRangeNode * &)` | 683 (0x2ab) | Exported Function | 0x10022a10 | 0x00022a10
`public: enum WmiTriState __thiscall WmiStringRangeNode::GetIntersectingRange(class WmiStringRangeNode &,class WmiStringRangeNode * &)` | 672 (0x2a0) | Exported Function | 0x10022030 | 0x00022030
`public: enum WmiTriState __thiscall WmiStringRangeNode::GetOverlappingRange(class WmiStringRangeNode &,class WmiStringRangeNode * &)` | 684 (0x2ac) | Exported Function | 0x100230c0 | 0x000230c0
`public: enum WmiTriState __thiscall WmiUnsignedIntegerRangeNode::GetIntersectingRange(class WmiUnsignedIntegerRangeNode &,class WmiUnsignedIntegerRangeNode * &)` | 673 (0x2a1) | Exported Function | 0x10022520 | 0x00022520
`public: enum WmiTriState __thiscall WmiUnsignedIntegerRangeNode::GetOverlappingRange(class WmiUnsignedIntegerRangeNode &,class WmiUnsignedIntegerRangeNode * &)` | 685 (0x2ad) | Exported Function | 0x10023720 | 0x00023720
`public: enum WmiValueNode::WmiValueFunction __thiscall WmiValueNode::GetConstantFunction(void)` | 662 (0x296) | Exported Function | 0x100092b0 | 0x000092b0
`public: enum WmiValueNode::WmiValueFunction __thiscall WmiValueNode::GetPropertyFunction(void)` | 690 (0x2b2) | Exported Function | 0x10009280 | 0x00009280
`public: int __thiscall PartitionSet::Leaf(void)` | 800 (0x320) | Exported Function | 0x100244b0 | 0x000244b0
`public: int __thiscall PartitionSet::Root(void)` | 891 (0x37b) | Exported Function | 0x10025230 | 0x00025230
`public: virtual __thiscall ProvNull::~ProvNull(void)` | 258 (0x102) | Exported Function | 0x10014130 | 0x00014130
`public: virtual __thiscall ProvNullType::~ProvNullType(void)` | 259 (0x103) | Exported Function | 0x10014180 | 0x00014180
`public: virtual __thiscall ProvObjectIdentifier::~ProvObjectIdentifier(void)` | 261 (0x105) | Exported Function | 0x1001cf20 | 0x0001cf20
`public: virtual __thiscall ProvObjectIdentifierType::~ProvObjectIdentifierType(void)` | 262 (0x106) | Exported Function | 0x10014240 | 0x00014240
`public: virtual void __thiscall WmiOperatorGreaterNode::Print(void)` | 847 (0x34f) | Exported Function | 0x100249c0 | 0x000249c0
`public: virtual void __thiscall WmiOperatorIsANode::Print(void)` | 848 (0x350) | Exported Function | 0x10024a10 | 0x00024a10
`public: virtual void __thiscall WmiOperatorLessNode::Print(void)` | 849 (0x351) | Exported Function | 0x10024a60 | 0x00024a60
`public: virtual void __thiscall WmiOperatorLikeNode::Print(void)` | 850 (0x352) | Exported Function | 0x10024ab0 | 0x00024ab0
`public: virtual void __thiscall WmiOperatorNotEqualNode::Print(void)` | 851 (0x353) | Exported Function | 0x10024b00 | 0x00024b00
`public: virtual void __thiscall WmiOperatorNotIsANode::Print(void)` | 852 (0x354) | Exported Function | 0x10024b50 | 0x00024b50
`public: virtual void __thiscall WmiOperatorNotLikeNode::Print(void)` | 853 (0x355) | Exported Function | 0x10024ba0 | 0x00024ba0
`public: virtual void __thiscall WmiOrNode::Print(void)` | 854 (0x356) | Exported Function | 0x10024bf0 | 0x00024bf0
`public: virtual void __thiscall WmiSignedIntegerNode::Print(void)` | 855 (0x357) | Exported Function | 0x10024cf0 | 0x00024cf0
`public: virtual void __thiscall WmiSignedIntegerRangeNode::Print(void)` | 856 (0x358) | Exported Function | 0x10024d30 | 0x00024d30
`public: virtual void __thiscall WmiStringNode::Print(void)` | 857 (0x359) | Exported Function | 0x10024de0 | 0x00024de0
`public: virtual void __thiscall WmiStringRangeNode::Print(void)` | 858 (0x35a) | Exported Function | 0x10024e20 | 0x00024e20
`public: virtual void __thiscall WmiOperatorEqualOrLessNode::Print(void)` | 846 (0x34e) | Exported Function | 0x10024970 | 0x00024970
`public: virtual void __thiscall WmiTreeNode::Print(void)` | 859 (0x35b) | Exported Function | 0x10009350 | 0x00009350
`public: virtual void __thiscall WmiUnsignedIntegerRangeNode::Print(void)` | 861 (0x35d) | Exported Function | 0x10024f00 | 0x00024f00
`public: void * __thiscall ProvEventObject::GetHandle(void)` | 667 (0x29b) | Exported Function | 0x1000f850 | 0x0000f850
`public: void * __thiscall ProvIpAddress::operator()(void)const ` | 401 (0x191) | Exported Function | 0x10014ec0 | 0x00014ec0
`public: void * __thiscall ProvObjectIdentifier::operator()(void)const ` | 402 (0x192) | Exported Function | 0x10014ec0 | 0x00014ec0
`public: void * __thiscall ProvOctetString::operator()(void)const ` | 403 (0x193) | Exported Function | 0x10014ec0 | 0x00014ec0
`public: void * __thiscall ProvOpaque::operator()(void)const ` | 404 (0x194) | Exported Function | 0x10014fe0 | 0x00014fe0
`public: void * __thiscall WmiTreeNode::GetData(void)` | 663 (0x297) | Exported Function | 0x100092a0 | 0x000092a0
`public: void * __thiscall WmiTreeNode::SetData(void *)` | 894 (0x37e) | Exported Function | 0x10025240 | 0x00025240
`public: void __cdecl ProvDebugLog::Write(unsigned short const *,...)` | 956 (0x3bc) | Exported Function | 0x1000f3e0 | 0x0000f3e0
`public: void __cdecl ProvDebugLog::WriteA(char const *,...)` | 957 (0x3bd) | Exported Function | 0x1000f460 | 0x0000f460
`public: void __cdecl ProvDebugLog::WriteFileAndLine(char const *,unsigned long,unsigned short const *,...)` | 958 (0x3be) | Exported Function | 0x1000f4e0 | 0x0000f4e0
`public: void __cdecl ProvDebugLog::WriteFileAndLine(unsigned short const *,unsigned long,unsigned short const *,...)` | 959 (0x3bf) | Exported Function | 0x1000f590 | 0x0000f590
`public: virtual void __thiscall WmiUnsignedIntegerNode::Print(void)` | 860 (0x35c) | Exported Function | 0x10024ec0 | 0x00024ec0
`public: void __cdecl ProvDebugLog::WriteFileAndLineA(char const *,unsigned long,char const *,...)` | 960 (0x3c0) | Exported Function | 0x1000f640 | 0x0000f640
`public: virtual void __thiscall WmiOperatorEqualOrGreaterNode::Print(void)` | 845 (0x34d) | Exported Function | 0x10024920 | 0x00024920
`public: virtual void __thiscall WmiNullRangeNode::Print(void)` | 843 (0x34b) | Exported Function | 0x10024890 | 0x00024890
`public: virtual unsigned short * __thiscall ProvCounter64Type::GetStringValue(void)const ` | 712 (0x2c8) | Exported Function | 0x10018500 | 0x00018500
`public: virtual unsigned short * __thiscall ProvCounterType::GetStringValue(void)const ` | 713 (0x2c9) | Exported Function | 0x100185b0 | 0x000185b0
`public: virtual unsigned short * __thiscall ProvDateTimeType::GetStringValue(void)const ` | 714 (0x2ca) | Exported Function | 0x10018660 | 0x00018660
`public: virtual unsigned short * __thiscall ProvDisplayStringType::GetStringValue(void)const ` | 715 (0x2cb) | Exported Function | 0x10018670 | 0x00018670
`public: virtual unsigned short * __thiscall ProvEnumeratedType::GetStringValue(void)const ` | 716 (0x2cc) | Exported Function | 0x100186d0 | 0x000186d0
`public: virtual unsigned short * __thiscall ProvFixedLengthDisplayStringType::GetStringValue(void)const ` | 717 (0x2cd) | Exported Function | 0x10018750 | 0x00018750
`public: virtual unsigned short * __thiscall ProvFixedLengthPhysAddressType::GetStringValue(void)const ` | 718 (0x2ce) | Exported Function | 0x100187b0 | 0x000187b0
`public: virtual unsigned short * __thiscall ProvGaugeType::GetStringValue(void)const ` | 719 (0x2cf) | Exported Function | 0x10018950 | 0x00018950
`public: virtual unsigned short * __thiscall ProvIntegerType::GetStringValue(void)const ` | 720 (0x2d0) | Exported Function | 0x10018a00 | 0x00018a00
`public: virtual unsigned short * __thiscall ProvIpAddressType::GetStringValue(void)const ` | 721 (0x2d1) | Exported Function | 0x10018ab0 | 0x00018ab0
`public: virtual unsigned short * __thiscall ProvMacAddressType::GetStringValue(void)const ` | 722 (0x2d2) | Exported Function | 0x10018c60 | 0x00018c60
`public: virtual unsigned short * __thiscall ProvNetworkAddressType::GetStringValue(void)const ` | 723 (0x2d3) | Exported Function | 0x10018ab0 | 0x00018ab0
`public: virtual void __thiscall WmiOperatorEqualNode::Print(void)` | 844 (0x34c) | Exported Function | 0x100248d0 | 0x000248d0
`public: virtual unsigned short * __thiscall ProvNullType::GetStringValue(void)const ` | 724 (0x2d4) | Exported Function | 0x10018da0 | 0x00018da0
`public: virtual unsigned short * __thiscall ProvOctetStringType::GetStringValue(void)const ` | 727 (0x2d7) | Exported Function | 0x10019220 | 0x00019220
`public: virtual unsigned short * __thiscall ProvOpaqueType::GetStringValue(void)const ` | 728 (0x2d8) | Exported Function | 0x10019300 | 0x00019300
`public: virtual unsigned short * __thiscall ProvOSIAddressType::GetStringValue(void)const ` | 725 (0x2d5) | Exported Function | 0x10018dc0 | 0x00018dc0
`public: virtual unsigned short * __thiscall ProvPhysAddressType::GetStringValue(void)const ` | 729 (0x2d9) | Exported Function | 0x10019490 | 0x00019490
`public: virtual unsigned short * __thiscall ProvRowStatusType::GetStringValue(void)const ` | 730 (0x2da) | Exported Function | 0x10019630 | 0x00019630
`public: virtual unsigned short * __thiscall ProvTimeTicksType::GetStringValue(void)const ` | 731 (0x2db) | Exported Function | 0x100185b0 | 0x000185b0
`public: virtual unsigned short * __thiscall ProvUDPAddressType::GetStringValue(void)const ` | 732 (0x2dc) | Exported Function | 0x10019640 | 0x00019640
`public: virtual void __thiscall ProvEventObject::Complete(void)` | 535 (0x217) | Exported Function | 0x10009350 | 0x00009350
`public: virtual void __thiscall ProvEventObject::Process(void)` | 863 (0x35f) | Exported Function | 0x10009350 | 0x00009350
`public: virtual void __thiscall WmiAndNode::Print(void)` | 840 (0x348) | Exported Function | 0x100246f0 | 0x000246f0
`public: virtual void __thiscall WmiNotNode::Print(void)` | 841 (0x349) | Exported Function | 0x100247f0 | 0x000247f0
`public: virtual void __thiscall WmiNullNode::Print(void)` | 842 (0x34a) | Exported Function | 0x10024890 | 0x00024890
`public: virtual unsigned short * __thiscall ProvObjectIdentifierType::GetStringValue(void)const ` | 726 (0x2d6) | Exported Function | 0x10019050 | 0x00019050
`public: void __cdecl ProvDebugLog::WriteFileAndLineW(unsigned short const *,unsigned long,unsigned short const *,...)` | 961 (0x3c1) | Exported Function | 0x1000f6f0 | 0x0000f6f0
`public: void __cdecl ProvDebugLog::WriteW(unsigned short const *,...)` | 962 (0x3c2) | Exported Function | 0x1000f3e0 | 0x0000f3e0
`public: void __thiscall Conjunctions::SetRange(unsigned long,class WmiRangeNode *)` | 903 (0x387) | Exported Function | 0x100252e0 | 0x000252e0
`public: void __thiscall ProvPositiveRangedType::SetStatus(int const &)` | 907 (0x38b) | Exported Function | 0x1001c690 | 0x0001c690
`public: void __thiscall ProvPositiveRangeType::SetLowerBound(unsigned long const &)` | 899 (0x383) | Exported Function | 0x1001c690 | 0x0001c690
`public: void __thiscall ProvPositiveRangeType::SetUpperBound(unsigned long const &)` | 911 (0x38f) | Exported Function | 0x1001c6f0 | 0x0001c6f0
`public: void __thiscall ProvTimeTicks::SetValue(unsigned long)` | 920 (0x398) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall ProvUInteger32::SetValue(unsigned long)` | 921 (0x399) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall WmiAndNode::``default constructor closure'(void)` | 509 (0x1fd) | Exported Function | 0x100208c0 | 0x000208c0
`public: void __thiscall WmiNotNode::``default constructor closure'(void)` | 510 (0x1fe) | Exported Function | 0x100208d0 | 0x000208d0
`public: void __thiscall WmiOperatorEqualNode::``default constructor closure'(void)` | 511 (0x1ff) | Exported Function | 0x100208e0 | 0x000208e0
`public: void __thiscall WmiOperatorEqualOrGreaterNode::``default constructor closure'(void)` | 512 (0x200) | Exported Function | 0x10020920 | 0x00020920
`public: void __thiscall WmiOperatorEqualOrLessNode::``default constructor closure'(void)` | 513 (0x201) | Exported Function | 0x10020960 | 0x00020960
`public: void __thiscall WmiOperatorGreaterNode::``default constructor closure'(void)` | 514 (0x202) | Exported Function | 0x100209a0 | 0x000209a0
`public: void __thiscall WmiOperatorIsANode::``default constructor closure'(void)` | 515 (0x203) | Exported Function | 0x100209e0 | 0x000209e0
`public: void __thiscall ProvPositiveRangedType::``default constructor closure'(void)` | 508 (0x1fc) | Exported Function | 0x10016780 | 0x00016780
`public: void __thiscall WmiOperatorLessNode::``default constructor closure'(void)` | 516 (0x204) | Exported Function | 0x10020a20 | 0x00020a20
`public: void __thiscall WmiOperatorNotEqualNode::``default constructor closure'(void)` | 518 (0x206) | Exported Function | 0x10020aa0 | 0x00020aa0
`public: void __thiscall WmiOperatorNotIsANode::``default constructor closure'(void)` | 519 (0x207) | Exported Function | 0x10020ae0 | 0x00020ae0
`public: void __thiscall WmiOperatorNotLikeNode::``default constructor closure'(void)` | 520 (0x208) | Exported Function | 0x10020b20 | 0x00020b20
`public: void __thiscall WmiOrNode::``default constructor closure'(void)` | 521 (0x209) | Exported Function | 0x10020b60 | 0x00020b60
`public: void __thiscall WmiTreeNode::``default constructor closure'(void)` | 522 (0x20a) | Exported Function | 0x10020b70 | 0x00020b70
`public: void __thiscall WmiTreeNode::GetData(void * *)` | 664 (0x298) | Exported Function | 0x10021b10 | 0x00021b10
`public: void __thiscall WmiTreeNode::GetLeft(class WmiTreeNode * * &)` | 677 (0x2a5) | Exported Function | 0x100229f0 | 0x000229f0
`public: void __thiscall WmiTreeNode::GetParent(class WmiTreeNode * * &)` | 687 (0x2af) | Exported Function | 0x10023dd0 | 0x00023dd0
`public: void __thiscall WmiTreeNode::GetRight(class WmiTreeNode * * &)` | 708 (0x2c4) | Exported Function | 0x10024350 | 0x00024350
`public: void __thiscall WmiTreeNode::SetType(unsigned long)` | 909 (0x38d) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`unsigned int __stdcall HashKey<unsigned short *>(unsigned short *)` | 2 (0x2) | Exported Function | 0x1000f8d0 | 0x0000f8d0
`unsigned short * __stdcall DbcsToUnicodeString(char const *)` | 605 (0x25d) | Exported Function | 0x10017810 | 0x00017810
`public: void __thiscall WmiOperatorLikeNode::``default constructor closure'(void)` | 517 (0x205) | Exported Function | 0x10020a60 | 0x00020a60
`public: void __thiscall ProvPhysAddressType::``default constructor closure'(void)` | 507 (0x1fb) | Exported Function | 0x10016770 | 0x00016770
`public: void __thiscall ProvOpaqueType::``default constructor closure'(void)` | 506 (0x1fa) | Exported Function | 0x10016760 | 0x00016760
`public: void __thiscall ProvOpaque::SetValue(unsigned char const *,unsigned long)` | 919 (0x397) | Exported Function | 0x1001c710 | 0x0001c710
`public: void __thiscall PartitionSet::SetKeyIndex(unsigned long)` | 896 (0x380) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall PartitionSet::SetPartition(unsigned long,class PartitionSet *)` | 902 (0x386) | Exported Function | 0x100252c0 | 0x000252c0
`public: void __thiscall PartitionSet::SetRange(class WmiRangeNode *)` | 904 (0x388) | Exported Function | 0x1001c6d0 | 0x0001c6d0
`public: void __thiscall ProvAnalyser::``default constructor closure'(void)` | 499 (0x1f3) | Exported Function | 0x100166f0 | 0x000166f0
`public: void __thiscall ProvAnalyser::PutBack(class ProvLexicon const *)` | 868 (0x364) | Exported Function | 0x1001c070 | 0x0001c070
`public: void __thiscall ProvAnalyser::Set(unsigned short const *)` | 892 (0x37c) | Exported Function | 0x1001c620 | 0x0001c620
`public: void __thiscall ProvCounter64::SetValue(unsigned long,unsigned long)` | 912 (0x390) | Exported Function | 0x1001dc90 | 0x0001dc90
`public: void __thiscall ProvCounter64Type::GetValue(unsigned long &,unsigned long &)const ` | 739 (0x2e3) | Exported Function | 0x10019e90 | 0x00019e90
`public: void __thiscall ProvCounter::SetValue(unsigned long)` | 913 (0x391) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall ProvDisplayStringType::``default constructor closure'(void)` | 500 (0x1f4) | Exported Function | 0x10016700 | 0x00016700
`public: void __thiscall ProvEventObject::``default constructor closure'(void)` | 501 (0x1f5) | Exported Function | 0x1000f160 | 0x0000f160
`public: void __thiscall ProvEventObject::Clear(void)` | 528 (0x210) | Exported Function | 0x1000f840 | 0x0000f840
`public: void __thiscall ProvEventObject::Set(void)` | 893 (0x37d) | Exported Function | 0x1000f860 | 0x0000f860
`public: void __thiscall ProvGauge::SetValue(unsigned long)` | 914 (0x392) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall ProvGaugeType::``default constructor closure'(void)` | 502 (0x1f6) | Exported Function | 0x10016710 | 0x00016710
`public: void __thiscall ProvInstanceType::``default constructor closure'(void)` | 503 (0x1f7) | Exported Function | 0x10016720 | 0x00016720
`public: void __thiscall ProvInstanceType::SetNull(int)` | 900 (0x384) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall ProvInstanceType::SetStatus(int)` | 906 (0x38a) | Exported Function | 0x1001c6d0 | 0x0001c6d0
`public: void __thiscall ProvInteger::SetValue(long)` | 915 (0x393) | Exported Function | 0x1001c6b0 | 0x0001c6b0
`public: void __thiscall ProvIntegerType::``default constructor closure'(void)` | 504 (0x1f8) | Exported Function | 0x10016740 | 0x00016740
`public: void __thiscall ProvIpAddress::SetValue(unsigned long)` | 916 (0x394) | Exported Function | 0x1001dcb0 | 0x0001dcb0
`public: void __thiscall ProvLexicon::SetToken(enum ProvLexicon::LexiconToken)` | 908 (0x38c) | Exported Function | 0x1001c6d0 | 0x0001c6d0
`public: void __thiscall ProvNegativeRangeType::SetLowerBound(long const &)` | 898 (0x382) | Exported Function | 0x1001c690 | 0x0001c690
`public: void __thiscall ProvNegativeRangeType::SetUpperBound(long const &)` | 910 (0x38e) | Exported Function | 0x1001c6f0 | 0x0001c6f0
`public: void __thiscall ProvObjectIdentifier::SetValue(unsigned long const *,unsigned long)` | 917 (0x395) | Exported Function | 0x1001dcd0 | 0x0001dcd0
`public: void __thiscall ProvOctetString::SetValue(unsigned char const *,unsigned long)` | 918 (0x396) | Exported Function | 0x1001dd60 | 0x0001dd60
`public: void __thiscall ProvOctetStringType::``default constructor closure'(void)` | 505 (0x1f9) | Exported Function | 0x10016750 | 0x00016750
`public: virtual unsigned short * __thiscall ProvBitStringType::GetStringValue(void)const ` | 711 (0x2c7) | Exported Function | 0x100184f0 | 0x000184f0
`public: class ProvLexicon * __thiscall ProvAnalyser::Get(int,int,int)` | 655 (0x28f) | Exported Function | 0x10017ef0 | 0x00017ef0
`public: virtual int __thiscall ProvNullType::IsProvV2CType(void)const ` | 796 (0x31c) | Exported Function | 0x1001a320 | 0x0001a320
`public: virtual int __thiscall ProvInstanceType::IsProvV2CType(void)const ` | 795 (0x31b) | Exported Function | 0x1001a330 | 0x0001a330
`public: virtual __thiscall WmiOperatorNotLikeNode::~WmiOperatorNotLikeNode(void)` | 291 (0x123) | Exported Function | 0x1001f8c0 | 0x0001f8c0
`public: virtual __thiscall WmiOrNode::~WmiOrNode(void)` | 292 (0x124) | Exported Function | 0x1001f940 | 0x0001f940
`public: virtual __thiscall WmiRangeNode::~WmiRangeNode(void)` | 293 (0x125) | Exported Function | 0x1001f9d0 | 0x0001f9d0
`public: virtual __thiscall WmiSignedIntegerNode::~WmiSignedIntegerNode(void)` | 294 (0x126) | Exported Function | 0x1001f350 | 0x0001f350
`public: virtual __thiscall WmiSignedIntegerRangeNode::~WmiSignedIntegerRangeNode(void)` | 295 (0x127) | Exported Function | 0x1001fa40 | 0x0001fa40
`public: virtual __thiscall WmiStringNode::~WmiStringNode(void)` | 296 (0x128) | Exported Function | 0x10007900 | 0x00007900
`public: virtual __thiscall WmiStringRangeNode::~WmiStringRangeNode(void)` | 297 (0x129) | Exported Function | 0x10007530 | 0x00007530
`public: virtual __thiscall WmiTreeNode::~WmiTreeNode(void)` | 298 (0x12a) | Exported Function | 0x1001fa90 | 0x0001fa90
`public: virtual __thiscall WmiTreeNodeIterator::~WmiTreeNodeIterator(void)` | 299 (0x12b) | Exported Function | 0x1001faa0 | 0x0001faa0
`public: virtual __thiscall WmiUnsignedIntegerNode::~WmiUnsignedIntegerNode(void)` | 300 (0x12c) | Exported Function | 0x10006f80 | 0x00006f80
`public: virtual __thiscall WmiUnsignedIntegerRangeNode::~WmiUnsignedIntegerRangeNode(void)` | 301 (0x12d) | Exported Function | 0x100070e0 | 0x000070e0
`public: virtual __thiscall WmiValueNode::~WmiValueNode(void)` | 302 (0x12e) | Exported Function | 0x1001fab0 | 0x0001fab0
`public: virtual __thiscall WmiOperatorNotIsANode::~WmiOperatorNotIsANode(void)` | 290 (0x122) | Exported Function | 0x1001f840 | 0x0001f840
`public: virtual class ProvInstanceType * __thiscall ProvBitStringType::Copy(void)const ` | 537 (0x219) | Exported Function | 0x10016dc0 | 0x00016dc0
`public: virtual class ProvInstanceType * __thiscall ProvCounterType::Copy(void)const ` | 541 (0x21d) | Exported Function | 0x10016e40 | 0x00016e40
`public: virtual class ProvInstanceType * __thiscall ProvDateTimeType::Copy(void)const ` | 542 (0x21e) | Exported Function | 0x10016e80 | 0x00016e80
`public: virtual class ProvInstanceType * __thiscall ProvDisplayStringType::Copy(void)const ` | 543 (0x21f) | Exported Function | 0x10016ec0 | 0x00016ec0
`public: virtual class ProvInstanceType * __thiscall ProvEnumeratedType::Copy(void)const ` | 544 (0x220) | Exported Function | 0x10016f20 | 0x00016f20
`public: virtual class ProvInstanceType * __thiscall ProvFixedLengthDisplayStringType::Copy(void)const ` | 545 (0x221) | Exported Function | 0x10016f60 | 0x00016f60
`public: virtual class ProvInstanceType * __thiscall ProvFixedLengthOctetStringType::Copy(void)const ` | 546 (0x222) | Exported Function | 0x10016fa0 | 0x00016fa0
`public: virtual class ProvInstanceType * __thiscall ProvFixedLengthOpaqueType::Copy(void)const ` | 547 (0x223) | Exported Function | 0x10016fe0 | 0x00016fe0
`public: virtual class ProvInstanceType * __thiscall ProvFixedLengthPhysAddressType::Copy(void)const ` | 548 (0x224) | Exported Function | 0x10017020 | 0x00017020
`public: virtual class ProvInstanceType * __thiscall ProvGaugeType::Copy(void)const ` | 550 (0x226) | Exported Function | 0x10017060 | 0x00017060
`public: virtual class ProvInstanceType * __thiscall ProvIntegerType::Copy(void)const ` | 552 (0x228) | Exported Function | 0x100170a0 | 0x000170a0
`public: virtual class ProvInstanceType * __thiscall ProvIpAddressType::Copy(void)const ` | 554 (0x22a) | Exported Function | 0x100170e0 | 0x000170e0
`public: virtual class ProvInstanceType * __thiscall ProvMacAddressType::Copy(void)const ` | 555 (0x22b) | Exported Function | 0x10017120 | 0x00017120
`public: virtual class ProvInstanceType * __thiscall ProvCounter64Type::Copy(void)const ` | 539 (0x21b) | Exported Function | 0x10016e00 | 0x00016e00
`public: virtual class ProvInstanceType * __thiscall ProvNetworkAddressType::Copy(void)const ` | 557 (0x22d) | Exported Function | 0x100171b0 | 0x000171b0
`public: virtual __thiscall WmiOperatorNotEqualNode::~WmiOperatorNotEqualNode(void)` | 289 (0x121) | Exported Function | 0x1001f7c0 | 0x0001f7c0
`public: virtual __thiscall WmiOperatorLikeNode::~WmiOperatorLikeNode(void)` | 287 (0x11f) | Exported Function | 0x1001f6f0 | 0x0001f6f0
`public: virtual __thiscall ProvOctetString::~ProvOctetString(void)` | 263 (0x107) | Exported Function | 0x1001cf80 | 0x0001cf80
`public: virtual __thiscall ProvOctetStringType::~ProvOctetStringType(void)` | 264 (0x108) | Exported Function | 0x100142a0 | 0x000142a0
`public: virtual __thiscall ProvOpaque::~ProvOpaque(void)` | 265 (0x109) | Exported Function | 0x10014320 | 0x00014320
`public: virtual __thiscall ProvOpaqueType::~ProvOpaqueType(void)` | 266 (0x10a) | Exported Function | 0x10014390 | 0x00014390
`public: virtual __thiscall ProvOSIAddressType::~ProvOSIAddressType(void)` | 260 (0x104) | Exported Function | 0x100141f0 | 0x000141f0
`public: virtual __thiscall ProvPhysAddressType::~ProvPhysAddressType(void)` | 267 (0x10b) | Exported Function | 0x10014410 | 0x00014410
`public: virtual __thiscall ProvPositiveRangedType::operator void *(void)` | 395 (0x18b) | Exported Function | 0x10014ec0 | 0x00014ec0
`public: virtual __thiscall ProvPositiveRangedType::~ProvPositiveRangedType(void)` | 269 (0x10d) | Exported Function | 0x10014470 | 0x00014470
`public: virtual __thiscall ProvPositiveRangeType::~ProvPositiveRangeType(void)` | 268 (0x10c) | Exported Function | 0x10014460 | 0x00014460
`public: virtual __thiscall ProvRowStatusType::~ProvRowStatusType(void)` | 270 (0x10e) | Exported Function | 0x10014520 | 0x00014520
`public: virtual __thiscall ProvTimeTicks::~ProvTimeTicks(void)` | 271 (0x10f) | Exported Function | 0x10014570 | 0x00014570
`public: virtual __thiscall ProvTimeTicksType::~ProvTimeTicksType(void)` | 272 (0x110) | Exported Function | 0x100145c0 | 0x000145c0
`public: virtual __thiscall WmiOperatorNode::~WmiOperatorNode(void)` | 288 (0x120) | Exported Function | 0x1001f770 | 0x0001f770
`public: virtual __thiscall ProvUDPAddressType::~ProvUDPAddressType(void)` | 273 (0x111) | Exported Function | 0x10014630 | 0x00014630
`public: virtual __thiscall ProvValue::~ProvValue(void)` | 275 (0x113) | Exported Function | 0x100146e0 | 0x000146e0
`public: virtual __thiscall QueryPreprocessor::~QueryPreprocessor(void)` | 276 (0x114) | Exported Function | 0x10009330 | 0x00009330
`public: virtual __thiscall WmiAndNode::~WmiAndNode(void)` | 277 (0x115) | Exported Function | 0x1001f250 | 0x0001f250
`public: virtual __thiscall WmiNotNode::~WmiNotNode(void)` | 278 (0x116) | Exported Function | 0x1001f2e0 | 0x0001f2e0
`public: virtual __thiscall WmiNullNode::~WmiNullNode(void)` | 279 (0x117) | Exported Function | 0x1001f350 | 0x0001f350
`public: virtual __thiscall WmiNullRangeNode::~WmiNullRangeNode(void)` | 280 (0x118) | Exported Function | 0x1001f3a0 | 0x0001f3a0
`public: virtual __thiscall WmiOperatorEqualNode::~WmiOperatorEqualNode(void)` | 281 (0x119) | Exported Function | 0x1001f3f0 | 0x0001f3f0
`public: virtual __thiscall WmiOperatorEqualOrGreaterNode::~WmiOperatorEqualOrGreaterNode(void)` | 282 (0x11a) | Exported Function | 0x1001f470 | 0x0001f470
`public: virtual __thiscall WmiOperatorEqualOrLessNode::~WmiOperatorEqualOrLessNode(void)` | 283 (0x11b) | Exported Function | 0x1001f4f0 | 0x0001f4f0
`public: virtual __thiscall WmiOperatorGreaterNode::~WmiOperatorGreaterNode(void)` | 284 (0x11c) | Exported Function | 0x1001f570 | 0x0001f570
`public: virtual __thiscall WmiOperatorIsANode::~WmiOperatorIsANode(void)` | 285 (0x11d) | Exported Function | 0x1001f5f0 | 0x0001f5f0
`public: virtual __thiscall WmiOperatorLessNode::~WmiOperatorLessNode(void)` | 286 (0x11e) | Exported Function | 0x1001f670 | 0x0001f670
`public: virtual __thiscall ProvUInteger32::~ProvUInteger32(void)` | 274 (0x112) | Exported Function | 0x10014690 | 0x00014690
`public: virtual class ProvInstanceType * __thiscall ProvNullType::Copy(void)const ` | 559 (0x22f) | Exported Function | 0x10017240 | 0x00017240
`public: virtual class ProvInstanceType * __thiscall ProvObjectIdentifierType::Copy(void)const ` | 562 (0x232) | Exported Function | 0x100172e0 | 0x000172e0
`public: virtual class ProvInstanceType * __thiscall ProvOctetStringType::Copy(void)const ` | 564 (0x234) | Exported Function | 0x10017320 | 0x00017320
`public: virtual class WmiTreeNode * __thiscall WmiNullNode::Copy(void)` | 576 (0x240) | Exported Function | 0x10021080 | 0x00021080
`public: virtual class WmiTreeNode * __thiscall WmiNullRangeNode::Copy(void)` | 577 (0x241) | Exported Function | 0x100210d0 | 0x000210d0
`public: virtual class WmiTreeNode * __thiscall WmiOperatorEqualNode::Copy(void)` | 578 (0x242) | Exported Function | 0x10007a30 | 0x00007a30
`public: virtual class WmiTreeNode * __thiscall WmiOperatorEqualOrGreaterNode::Copy(void)` | 579 (0x243) | Exported Function | 0x10021110 | 0x00021110
`public: virtual class WmiTreeNode * __thiscall WmiOperatorEqualOrLessNode::Copy(void)` | 580 (0x244) | Exported Function | 0x100211b0 | 0x000211b0
`public: virtual class WmiTreeNode * __thiscall WmiOperatorGreaterNode::Copy(void)` | 581 (0x245) | Exported Function | 0x10021250 | 0x00021250
`public: virtual class WmiTreeNode * __thiscall WmiOperatorIsANode::Copy(void)` | 582 (0x246) | Exported Function | 0x100212f0 | 0x000212f0
`public: virtual class WmiTreeNode * __thiscall WmiOperatorLessNode::Copy(void)` | 583 (0x247) | Exported Function | 0x10021390 | 0x00021390
`public: virtual class WmiTreeNode * __thiscall WmiOperatorLikeNode::Copy(void)` | 584 (0x248) | Exported Function | 0x10021430 | 0x00021430
`public: virtual class WmiTreeNode * __thiscall WmiOperatorNotEqualNode::Copy(void)` | 585 (0x249) | Exported Function | 0x100214d0 | 0x000214d0
`public: virtual class WmiTreeNode * __thiscall WmiOperatorNotIsANode::Copy(void)` | 586 (0x24a) | Exported Function | 0x10021570 | 0x00021570
`public: virtual class WmiTreeNode * __thiscall WmiOperatorNotLikeNode::Copy(void)` | 587 (0x24b) | Exported Function | 0x10021610 | 0x00021610
`public: virtual class WmiTreeNode * __thiscall WmiNotNode::Copy(void)` | 575 (0x23f) | Exported Function | 0x10020ff0 | 0x00020ff0
`public: virtual class WmiTreeNode * __thiscall WmiOrNode::Copy(void)` | 588 (0x24c) | Exported Function | 0x100216b0 | 0x000216b0
`public: virtual class WmiTreeNode * __thiscall WmiSignedIntegerRangeNode::Copy(void)` | 590 (0x24e) | Exported Function | 0x10021800 | 0x00021800
`public: virtual class WmiTreeNode * __thiscall WmiStringNode::Copy(void)` | 591 (0x24f) | Exported Function | 0x100076e0 | 0x000076e0
`public: virtual class WmiTreeNode * __thiscall WmiStringRangeNode::Copy(void)` | 592 (0x250) | Exported Function | 0x100080e0 | 0x000080e0
`public: virtual class WmiTreeNode * __thiscall WmiTreeNode::Copy(void)` | 593 (0x251) | Exported Function | 0x100263d0 | 0x000263d0
`public: virtual class WmiTreeNode * __thiscall WmiTreeNode::CopyNode(void)` | 597 (0x255) | Exported Function | 0x10026470 | 0x00026470
`public: virtual class WmiTreeNode * __thiscall WmiUnsignedIntegerNode::Copy(void)` | 595 (0x253) | Exported Function | 0x10006dc0 | 0x00006dc0
`public: virtual class WmiTreeNode * __thiscall WmiUnsignedIntegerRangeNode::Copy(void)` | 596 (0x254) | Exported Function | 0x10007270 | 0x00007270
`public: virtual class WmiTreeNodeIterator * __thiscall WmiTreeNodeIterator::Copy(void)` | 594 (0x252) | Exported Function | 0x10021860 | 0x00021860
`public: virtual int __thiscall ProvCounter64Type::IsProvV1Type(void)const ` | 793 (0x319) | Exported Function | 0x1001a320 | 0x0001a320
`public: virtual int __thiscall ProvEventObject::Wait(void)` | 955 (0x3bb) | Exported Function | 0x1000f870 | 0x0000f870
`public: virtual int __thiscall ProvInstanceType::IsNull(void)const ` | 791 (0x317) | Exported Function | 0x1000f850 | 0x0000f850
`public: virtual int __thiscall ProvInstanceType::IsProvV1Type(void)const ` | 794 (0x31a) | Exported Function | 0x1001a330 | 0x0001a330
`public: virtual class WmiTreeNode * __thiscall WmiSignedIntegerNode::Copy(void)` | 589 (0x24d) | Exported Function | 0x100217b0 | 0x000217b0
`public: virtual class WmiTreeNode * __thiscall WmiAndNode::Copy(void)` | 574 (0x23e) | Exported Function | 0x100075d0 | 0x000075d0
`public: virtual class WmiRangeNode * __thiscall WmiOperatorNotLikeNode::GetRange(void)` | 705 (0x2c1) | Exported Function | 0x100241a0 | 0x000241a0
`public: virtual class WmiRangeNode * __thiscall WmiOperatorNotIsANode::GetRange(void)` | 704 (0x2c0) | Exported Function | 0x100241a0 | 0x000241a0
`public: virtual class ProvInstanceType * __thiscall ProvOpaqueType::Copy(void)const ` | 566 (0x236) | Exported Function | 0x100173b0 | 0x000173b0
`public: virtual class ProvInstanceType * __thiscall ProvOSIAddressType::Copy(void)const ` | 560 (0x230) | Exported Function | 0x10017280 | 0x00017280
`public: virtual class ProvInstanceType * __thiscall ProvPhysAddressType::Copy(void)const ` | 567 (0x237) | Exported Function | 0x100173f0 | 0x000173f0
`public: virtual class ProvInstanceType * __thiscall ProvRowStatusType::Copy(void)const ` | 569 (0x239) | Exported Function | 0x100174a0 | 0x000174a0
`public: virtual class ProvInstanceType * __thiscall ProvTimeTicksType::Copy(void)const ` | 571 (0x23b) | Exported Function | 0x10017500 | 0x00017500
`public: virtual class ProvInstanceType * __thiscall ProvUDPAddressType::Copy(void)const ` | 572 (0x23c) | Exported Function | 0x10017540 | 0x00017540
`public: virtual class ProvNegativeRangeType * __thiscall ProvNegativeRangeType::Copy(void)` | 556 (0x22c) | Exported Function | 0x10017160 | 0x00017160
`public: virtual class ProvPositiveRangeType * __thiscall ProvPositiveRangeType::Copy(void)` | 568 (0x238) | Exported Function | 0x10017450 | 0x00017450
`public: virtual class ProvValue * __thiscall ProvCounter64::Copy(void)const ` | 538 (0x21a) | Exported Function | 0x1001d270 | 0x0001d270
`public: virtual class ProvValue * __thiscall ProvCounter::Copy(void)const ` | 540 (0x21c) | Exported Function | 0x1001d2b0 | 0x0001d2b0
`public: virtual class ProvValue * __thiscall ProvGauge::Copy(void)const ` | 549 (0x225) | Exported Function | 0x1001d310 | 0x0001d310
`public: virtual class ProvValue * __thiscall ProvInteger::Copy(void)const ` | 551 (0x227) | Exported Function | 0x1001d370 | 0x0001d370
`public: virtual class ProvValue * __thiscall ProvIpAddress::Copy(void)const ` | 553 (0x229) | Exported Function | 0x1001d3d0 | 0x0001d3d0
`public: virtual class ProvValue * __thiscall ProvNull::Copy(void)const ` | 558 (0x22e) | Exported Function | 0x100171f0 | 0x000171f0
`public: virtual class ProvValue * __thiscall ProvObjectIdentifier::Copy(void)const ` | 561 (0x231) | Exported Function | 0x1001d410 | 0x0001d410
`public: virtual class ProvValue * __thiscall ProvOctetString::Copy(void)const ` | 563 (0x233) | Exported Function | 0x1001d460 | 0x0001d460
`public: virtual class ProvValue * __thiscall ProvOpaque::Copy(void)const ` | 565 (0x235) | Exported Function | 0x10017360 | 0x00017360
`public: virtual class ProvValue * __thiscall ProvTimeTicks::Copy(void)const ` | 570 (0x23a) | Exported Function | 0x1001d4a0 | 0x0001d4a0
`public: virtual class ProvValue * __thiscall ProvUInteger32::Copy(void)const ` | 573 (0x23d) | Exported Function | 0x1001d500 | 0x0001d500
`public: virtual class WmiRangeNode * __thiscall WmiOperatorEqualNode::GetRange(void)` | 696 (0x2b8) | Exported Function | 0x10007b10 | 0x00007b10
`public: virtual class WmiRangeNode * __thiscall WmiOperatorEqualOrGreaterNode::GetRange(void)` | 697 (0x2b9) | Exported Function | 0x10023e10 | 0x00023e10
`public: virtual class WmiRangeNode * __thiscall WmiOperatorEqualOrLessNode::GetRange(void)` | 698 (0x2ba) | Exported Function | 0x10023f40 | 0x00023f40
`public: virtual class WmiRangeNode * __thiscall WmiOperatorGreaterNode::GetRange(void)` | 699 (0x2bb) | Exported Function | 0x10024070 | 0x00024070
`public: virtual class WmiRangeNode * __thiscall WmiOperatorIsANode::GetRange(void)` | 700 (0x2bc) | Exported Function | 0x100241a0 | 0x000241a0
`public: virtual class WmiRangeNode * __thiscall WmiOperatorLessNode::GetRange(void)` | 701 (0x2bd) | Exported Function | 0x10024220 | 0x00024220
`public: virtual class WmiRangeNode * __thiscall WmiOperatorLikeNode::GetRange(void)` | 702 (0x2be) | Exported Function | 0x100241a0 | 0x000241a0
`public: virtual class WmiRangeNode * __thiscall WmiOperatorNotEqualNode::GetRange(void)` | 703 (0x2bf) | Exported Function | 0x1001a320 | 0x0001a320
`public: virtual int __thiscall ProvInstanceType::IsValid(void)const ` | 797 (0x31d) | Exported Function | 0x100092a0 | 0x000092a0
`unsigned short * __stdcall UnicodeStringAppend(unsigned short const *,unsigned short const *)` | 949 (0x3b5) | Exported Function | 0x1001c8c0 | 0x0001c8c0
`public: class ProvLexicon & __thiscall ProvLexicon::operator=(class ProvLexicon const &)` | 332 (0x14c) | Exported Function | 0x10014ab0 | 0x00014ab0
`public: class ProvIntegerType & __thiscall ProvIntegerType::operator=(class ProvIntegerType const &)` | 329 (0x149) | Exported Function | 0x100149f0 | 0x000149f0
`protected: int __thiscall ProvIntegerType::Parse(unsigned short const *)` | 825 (0x339) | Exported Function | 0x1001ad10 | 0x0001ad10
`protected: int __thiscall ProvIpAddressType::Parse(unsigned short const *)` | 826 (0x33a) | Exported Function | 0x1001adb0 | 0x0001adb0
`protected: int __thiscall ProvMacAddressType::Parse(unsigned short const *)` | 827 (0x33b) | Exported Function | 0x1001b070 | 0x0001b070
`protected: int __thiscall ProvNetworkAddressType::Parse(unsigned short const *)` | 828 (0x33c) | Exported Function | 0x1001b180 | 0x0001b180
`protected: int __thiscall ProvObjectIdentifier::Equivalent(class ProvObjectIdentifier const &)const ` | 635 (0x27b) | Exported Function | 0x1001d6e0 | 0x0001d6e0
`protected: int __thiscall ProvObjectIdentifierType::Parse(unsigned short const *)` | 830 (0x33e) | Exported Function | 0x1001b670 | 0x0001b670
`protected: int __thiscall ProvOctetStringType::Parse(unsigned short const *)` | 831 (0x33f) | Exported Function | 0x1001b810 | 0x0001b810
`protected: int __thiscall ProvOpaqueType::Parse(unsigned short const *)` | 832 (0x340) | Exported Function | 0x1001b960 | 0x0001b960
`protected: int __thiscall ProvOSIAddressType::Parse(unsigned short const *)` | 829 (0x33d) | Exported Function | 0x1001b460 | 0x0001b460
`protected: int __thiscall ProvPhysAddressType::Parse(unsigned short const *)` | 833 (0x341) | Exported Function | 0x1001bab0 | 0x0001bab0
`protected: int __thiscall ProvPositiveRangedType::Parse(unsigned short const *)` | 834 (0x342) | Exported Function | 0x1001bc20 | 0x0001bc20
`protected: int __thiscall ProvPositiveRangedType::RangeDef(void)` | 871 (0x367) | Exported Function | 0x1001c170 | 0x0001c170
`protected: int __thiscall ProvGaugeType::Parse(unsigned short const *)` | 824 (0x338) | Exported Function | 0x1001ac70 | 0x0001ac70
`protected: int __thiscall ProvPositiveRangedType::RecursiveDef(void)` | 875 (0x36b) | Exported Function | 0x1001c4a0 | 0x0001c4a0
`protected: int __thiscall ProvUDPAddressType::Parse(unsigned short const *)` | 836 (0x344) | Exported Function | 0x1001bc60 | 0x0001bc60
`protected: int __thiscall QueryPreprocessor::Evaluate(void *,struct SQL_LEVEL_1_RPN_EXPRESSION &,class WmiTreeNode * *)` | 650 (0x28a) | Exported Function | 0x10021920 | 0x00021920
`protected: int __thiscall QueryPreprocessor::RecursiveEvaluate(void *,struct SQL_LEVEL_1_RPN_EXPRESSION &,class WmiTreeNode *,class WmiTreeNode * *,int &)` | 877 (0x36d) | Exported Function | 0x10007d10 | 0x00007d10
`protected: virtual class ProvLexicon * __thiscall ProvAnalyser::CreateLexicon(void)` | 601 (0x259) | Exported Function | 0x10017580 | 0x00017580
`protected: virtual class WmiRangeNode * __thiscall QueryPreprocessor::AllocInfiniteRangeNode(void *,unsigned short *)` | 523 (0x20b) | Exported Function | 0x10020b90 | 0x00020b90
`protected: virtual class WmiTreeNode * __thiscall QueryPreprocessor::AllocTypeNode(void *,unsigned short *,struct tagVARIANT &,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,class WmiTreeNode *)` | 524 (0x20c) | Exported Function | 0x10020ba0 | 0x00020ba0
`protected: virtual enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::InvariantEvaluate(void *,class WmiTreeNode *,class WmiTreeNode *)` | 784 (0x310) | Exported Function | 0x100244a0 | 0x000244a0
`protected: virtual int __thiscall ProvAnalyser::Analyse(class ProvLexicon *,unsigned long &,unsigned short,unsigned short const *,unsigned long &,int,int,int)` | 525 (0x20d) | Exported Function | 0x10016bb0 | 0x00016bb0
`protected: virtual int __thiscall ProvCounter64::Equivalent(class ProvValue const &)const ` | 617 (0x269) | Exported Function | 0x1001d5f0 | 0x0001d5f0
`protected: virtual int __thiscall ProvCounter64Type::Equivalent(class ProvInstanceType const &)const ` | 619 (0x26b) | Exported Function | 0x10017c00 | 0x00017c00
`protected: virtual int __thiscall ProvCounter::Equivalent(class ProvValue const &)const ` | 620 (0x26c) | Exported Function | 0x1001d640 | 0x0001d640
`protected: virtual int __thiscall ProvCounterType::Equivalent(class ProvInstanceType const &)const ` | 622 (0x26e) | Exported Function | 0x10017c70 | 0x00017c70
`protected: int __thiscall ProvTimeTicksType::Parse(unsigned short const *)` | 835 (0x343) | Exported Function | 0x1001aa00 | 0x0001aa00
`protected: virtual int __thiscall ProvGauge::Equivalent(class ProvValue const &)const ` | 623 (0x26f) | Exported Function | 0x1001d640 | 0x0001d640
`protected: int __thiscall ProvFixedLengthPhysAddressType::Parse(unsigned short const *)` | 823 (0x337) | Exported Function | 0x1001ab10 | 0x0001ab10
`protected: int __thiscall ProvCounter64Type::Parse(unsigned short const *)` | 819 (0x333) | Exported Function | 0x1001a700 | 0x0001a700
`protected: class ProvLexicon * __thiscall ProvPositiveRangedType::Get(void)` | 659 (0x293) | Exported Function | 0x100180d0 | 0x000180d0
`protected: class ProvLexicon * __thiscall ProvPositiveRangedType::Match(enum ProvLexicon::LexiconToken)` | 813 (0x32d) | Exported Function | 0x1001a520 | 0x0001a520
`protected: enum ProvObjectIdentifier::Comparison __thiscall ProvObjectIdentifier::Compare(class ProvObjectIdentifier const &,class ProvObjectIdentifier const &)const ` | 532 (0x214) | Exported Function | 0x1001d200 | 0x0001d200
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::DisjunctiveNormalForm(class WmiTreeNode * &)` | 614 (0x266) | Exported Function | 0x100218f0 | 0x000218f0
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::RecursiveDisjunctiveNormalForm(class WmiTreeNode * &)` | 876 (0x36c) | Exported Function | 0x100082e0 | 0x000082e0
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::RecursiveRemoveInvariants(void *,class WmiTreeNode * &)` | 881 (0x371) | Exported Function | 0x100068c0 | 0x000068c0
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::RecursiveRemoveNonOverlappingRanges(class WmiTreeNode * &,class WmiTreeNode * &)` | 882 (0x372) | Exported Function | 0x100067a0 | 0x000067a0
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::RemoveInvariants(void *,class WmiTreeNode * &)` | 885 (0x375) | Exported Function | 0x10025150 | 0x00025150
`protected: enum QueryPreprocessor::QuadState __thiscall QueryPreprocessor::RemoveNonOverlappingRanges(class WmiTreeNode * &)` | 886 (0x376) | Exported Function | 0x100251c0 | 0x000251c0
`protected: enum WmiTriState __thiscall QueryPreprocessor::ConvertToRanges(class WmiTreeNode * &)` | 536 (0x218) | Exported Function | 0x10020fe0 | 0x00020fe0
`protected: enum WmiTriState __thiscall QueryPreprocessor::CreateDisjunctionContainer(void *,class WmiTreeNode *,unsigned long,unsigned short * *,class Disjunctions * &)` | 599 (0x257) | Exported Function | 0x10008ba0 | 0x00008ba0
`protected: enum WmiTriState __thiscall QueryPreprocessor::CreateDisjunctions(void *,class WmiTreeNode *,class Disjunctions *,unsigned long,unsigned short * *,unsigned long &)` | 600 (0x258) | Exported Function | 0x10008d10 | 0x00008d10
`protected: int __thiscall ProvCounterType::Parse(unsigned short const *)` | 820 (0x334) | Exported Function | 0x1001aa00 | 0x0001aa00
`protected: enum WmiTriState __thiscall QueryPreprocessor::CreatePartitionSet(class Disjunctions *,class PartitionSet * &)` | 602 (0x25a) | Exported Function | 0x10008490 | 0x00008490
`protected: enum WmiTriState __thiscall QueryPreprocessor::EvaluateNotEqualExpression(class WmiTreeNode * &)` | 652 (0x28c) | Exported Function | 0x100219d0 | 0x000219d0
`protected: enum WmiTriState __thiscall QueryPreprocessor::EvaluateNotExpression(class WmiTreeNode * &)` | 653 (0x28d) | Exported Function | 0x10021a00 | 0x00021a00
`protected: enum WmiTriState __thiscall QueryPreprocessor::EvaluateOrExpression(class WmiTreeNode * &)` | 654 (0x28e) | Exported Function | 0x10021b00 | 0x00021b00
`protected: enum WmiTriState __thiscall QueryPreprocessor::InsertNode(class WmiTreeNode * &,class WmiTreeNode * &)` | 783 (0x30f) | Exported Function | 0x10024420 | 0x00024420
`protected: enum WmiTriState __thiscall QueryPreprocessor::RecursiveConvertToRanges(class WmiTreeNode * &)` | 872 (0x368) | Exported Function | 0x100083a0 | 0x000083a0
`protected: enum WmiTriState __thiscall QueryPreprocessor::RecursiveInsertNode(class WmiTreeNode * &,class WmiTreeNode * &)` | 878 (0x36e) | Exported Function | 0x10007150 | 0x00007150
`protected: enum WmiTriState __thiscall QueryPreprocessor::RecursivePartitionSet(class Disjunctions *,class PartitionSet * &,unsigned long,unsigned long *,unsigned long)` | 879 (0x36f) | Exported Function | 0x100085a0 | 0x000085a0
`protected: enum WmiTriState __thiscall QueryPreprocessor::RecursiveSort(class WmiTreeNode * &)` | 883 (0x373) | Exported Function | 0x10006a40 | 0x00006a40
`protected: enum WmiTriState __thiscall QueryPreprocessor::RecursiveSortConditionals(class WmiTreeNode * &,class WmiTreeNode * &)` | 884 (0x374) | Exported Function | 0x10006b10 | 0x00006b10
`protected: enum WmiTriState __thiscall QueryPreprocessor::RemoveOverlaps(unsigned long *,unsigned long,unsigned long *,unsigned long *,class WmiRangeNode * *)` | 887 (0x377) | Exported Function | 0x10008b30 | 0x00008b30
`protected: enum WmiTriState __thiscall QueryPreprocessor::Sort(class WmiTreeNode * &)` | 922 (0x39a) | Exported Function | 0x10025360 | 0x00025360
`protected: enum WmiTriState __thiscall QueryPreprocessor::SortConditionals(class WmiTreeNode * &)` | 923 (0x39b) | Exported Function | 0x10006a90 | 0x00006a90
`protected: enum WmiTriState __thiscall QueryPreprocessor::EvaluateAndExpression(class WmiTreeNode * &)` | 651 (0x28b) | Exported Function | 0x10021980 | 0x00021980
`protected: __thiscall ProvValue::ProvValue(void)` | 166 (0xa6) | Exported Function | 0x10013360 | 0x00013360
`protected: virtual int __thiscall ProvGaugeType::Equivalent(class ProvInstanceType const &)const ` | 625 (0x271) | Exported Function | 0x10017cc0 | 0x00017cc0
`protected: virtual int __thiscall ProvIntegerType::Equivalent(class ProvInstanceType const &)const ` | 628 (0x274) | Exported Function | 0x10017cc0 | 0x00017cc0
`protected: void __thiscall QueryPreprocessor::TransformIntersectingRange(class WmiTreeNode * &,class WmiTreeNode *,class WmiTreeNode *)` | 929 (0x3a1) | Exported Function | 0x100255f0 | 0x000255f0
`protected: void __thiscall QueryPreprocessor::TransformNonIntersectingRange(class WmiTreeNode * &,class WmiTreeNode *)` | 930 (0x3a2) | Exported Function | 0x10025640 | 0x00025640
`protected: void __thiscall QueryPreprocessor::TransformNotAndExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 931 (0x3a3) | Exported Function | 0x10025650 | 0x00025650
`protected: void __thiscall QueryPreprocessor::TransformNotEqualExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 932 (0x3a4) | Exported Function | 0x10025820 | 0x00025820
`protected: void __thiscall QueryPreprocessor::TransformNotNotExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 933 (0x3a5) | Exported Function | 0x10025a00 | 0x00025a00
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorEqualExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 934 (0x3a6) | Exported Function | 0x10025a90 | 0x00025a90
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorEqualOrGreaterExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 935 (0x3a7) | Exported Function | 0x10025b70 | 0x00025b70
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorEqualOrLessExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 936 (0x3a8) | Exported Function | 0x10025c50 | 0x00025c50
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorGreaterExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 937 (0x3a9) | Exported Function | 0x10025b70 | 0x00025b70
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorIsAExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 938 (0x3aa) | Exported Function | 0x10025d30 | 0x00025d30
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorLessExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 939 (0x3ab) | Exported Function | 0x10025c50 | 0x00025c50
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorLikeExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 940 (0x3ac) | Exported Function | 0x10025e10 | 0x00025e10
`protected: void __thiscall QueryPreprocessor::TransformAndTrueEvaluation(class WmiTreeNode * &,class WmiTreeNode *)` | 928 (0x3a0) | Exported Function | 0x10025580 | 0x00025580
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorNotEqualExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 941 (0x3ad) | Exported Function | 0x10025ef0 | 0x00025ef0
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorNotLikeExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 943 (0x3af) | Exported Function | 0x100260b0 | 0x000260b0
`protected: void __thiscall QueryPreprocessor::TransformNotOrExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 944 (0x3b0) | Exported Function | 0x10026190 | 0x00026190
`protected: void __thiscall QueryPreprocessor::TransformOperatorToRange(class WmiTreeNode * &)` | 945 (0x3b1) | Exported Function | 0x10026360 | 0x00026360
`protected: void __thiscall QueryPreprocessor::TransformOrFalseEvaluation(class WmiTreeNode * &,class WmiTreeNode *)` | 946 (0x3b2) | Exported Function | 0x10025580 | 0x00025580
`public: __thiscall CBString::CBString(int)` | 3 (0x3) | Exported Function | 0x1000fae0 | 0x0000fae0
`public: __thiscall CBString::CBString(unsigned short const *)` | 4 (0x4) | Exported Function | 0x1000fb10 | 0x0000fb10
`public: __thiscall CBString::CBString(void)` | 5 (0x5) | Exported Function | 0x1000fb40 | 0x0000fb40
`public: __thiscall CBString::~CBString(void)` | 228 (0xe4) | Exported Function | 0x10013610 | 0x00013610
`public: __thiscall Conjunctions::Conjunctions(unsigned long)` | 6 (0x6) | Exported Function | 0x1001dea0 | 0x0001dea0
`public: __thiscall Conjunctions::~Conjunctions(void)` | 229 (0xe5) | Exported Function | 0x1001f090 | 0x0001f090
`public: __thiscall Disjunctions::Disjunctions(unsigned long,unsigned long)` | 7 (0x7) | Exported Function | 0x1001dec0 | 0x0001dec0
`public: __thiscall Disjunctions::~Disjunctions(void)` | 230 (0xe6) | Exported Function | 0x1001f120 | 0x0001f120
`protected: void __thiscall QueryPreprocessor::TransformNotOperatorNotIsAExpression(class WmiTreeNode * &,class WmiTreeNode *)` | 942 (0x3ae) | Exported Function | 0x10025fd0 | 0x00025fd0
`protected: virtual int __thiscall ProvInteger::Equivalent(class ProvValue const &)const ` | 626 (0x272) | Exported Function | 0x1001d640 | 0x0001d640
`protected: void __thiscall QueryPreprocessor::TransformAndOrExpression(class WmiTreeNode * &,class WmiTreeNode *,class WmiTreeNode *)` | 927 (0x39f) | Exported Function | 0x10025390 | 0x00025390
`protected: void __thiscall QueryPreprocessor::RecursiveQuickSort(class WmiRangeNode * *,unsigned long *,unsigned long,unsigned long)` | 880 (0x370) | Exported Function | 0x10025060 | 0x00025060
`protected: virtual int __thiscall ProvIpAddress::Equivalent(class ProvValue const &)const ` | 629 (0x275) | Exported Function | 0x1001d690 | 0x0001d690
`protected: virtual int __thiscall ProvIpAddressType::Equivalent(class ProvInstanceType const &)const ` | 631 (0x277) | Exported Function | 0x10017d50 | 0x00017d50
`protected: virtual int __thiscall ProvNetworkAddressType::Equivalent(class ProvInstanceType const &)const ` | 632 (0x278) | Exported Function | 0x10017d50 | 0x00017d50
`protected: virtual int __thiscall ProvNull::Equivalent(class ProvValue const &)const ` | 633 (0x279) | Exported Function | 0x10017da0 | 0x00017da0
`protected: virtual int __thiscall ProvNullType::Equivalent(class ProvInstanceType const &)const ` | 634 (0x27a) | Exported Function | 0x10017da0 | 0x00017da0
`protected: virtual int __thiscall ProvObjectIdentifier::Equivalent(class ProvValue const &)const ` | 636 (0x27c) | Exported Function | 0x1001d740 | 0x0001d740
`protected: virtual int __thiscall ProvObjectIdentifierType::Equivalent(class ProvInstanceType const &)const ` | 638 (0x27e) | Exported Function | 0x10017de0 | 0x00017de0
`protected: virtual int __thiscall ProvOctetString::Equivalent(class ProvValue const &)const ` | 639 (0x27f) | Exported Function | 0x1001d800 | 0x0001d800
`protected: virtual int __thiscall ProvOctetStringType::Equivalent(class ProvInstanceType const &)const ` | 641 (0x281) | Exported Function | 0x10017e30 | 0x00017e30
`protected: virtual int __thiscall ProvOpaque::Equivalent(class ProvValue const &)const ` | 642 (0x282) | Exported Function | 0x1001d8b0 | 0x0001d8b0
`protected: virtual int __thiscall ProvOpaqueType::Equivalent(class ProvInstanceType const &)const ` | 644 (0x284) | Exported Function | 0x10017ea0 | 0x00017ea0
`protected: virtual int __thiscall ProvTimeTicks::Equivalent(class ProvValue const &)const ` | 645 (0x285) | Exported Function | 0x1001d640 | 0x0001d640
`protected: void __thiscall QueryPreprocessor::SortRanges(unsigned long,unsigned long *,class WmiRangeNode * *)` | 924 (0x39c) | Exported Function | 0x10025370 | 0x00025370
`protected: virtual int __thiscall ProvTimeTicksType::Equivalent(class ProvInstanceType const &)const ` | 647 (0x287) | Exported Function | 0x10017c70 | 0x00017c70
`protected: virtual unsigned char * __thiscall ProvOctetString::Replicate(unsigned char const *,unsigned long)` | 890 (0x37a) | Exported Function | 0x1001dc50 | 0x0001dc50
`protected: virtual unsigned long * __thiscall ProvObjectIdentifier::Replicate(unsigned long const *,unsigned long)const ` | 889 (0x379) | Exported Function | 0x1001dbf0 | 0x0001dbf0
`protected: virtual unsigned long * __thiscall ProvObjectIdentifier::Replicate(unsigned long const *,unsigned long,unsigned long const *,unsigned long)const ` | 888 (0x378) | Exported Function | 0x1001db20 | 0x0001db20
`protected: virtual void __thiscall ProvAnalyser::Initialise(void)` | 777 (0x309) | Exported Function | 0x10009350 | 0x00009350
`protected: virtual void __thiscall ProvObjectIdentifier::Initialize(unsigned long const *,unsigned long)` | 781 (0x30d) | Exported Function | 0x1001d9e0 | 0x0001d9e0
`protected: virtual void __thiscall ProvObjectIdentifier::UnReplicate(unsigned long *)` | 947 (0x3b3) | Exported Function | 0x1001ddc0 | 0x0001ddc0
`protected: virtual void __thiscall ProvOctetString::Initialize(unsigned char const *,unsigned long)` | 782 (0x30e) | Exported Function | 0x1001da70 | 0x0001da70
`protected: virtual void __thiscall ProvOctetString::UnReplicate(unsigned char *)` | 948 (0x3b4) | Exported Function | 0x1001de00 | 0x0001de00
`protected: void __thiscall ProvPositiveRangedType::PushBack(void)` | 867 (0x363) | Exported Function | 0x1001c060 | 0x0001c060
`protected: void __thiscall QueryPreprocessor::CountDisjunctions(class WmiTreeNode *,unsigned long &)` | 598 (0x256) | Exported Function | 0x100218b0 | 0x000218b0
`protected: void __thiscall QueryPreprocessor::PrintTree(class WmiTreeNode *)` | 862 (0x35e) | Exported Function | 0x10024fd0 | 0x00024fd0
`protected: void __thiscall QueryPreprocessor::QuickSort(class WmiRangeNode * *,unsigned long *,unsigned long)` | 870 (0x366) | Exported Function | 0x10025040 | 0x00025040
`protected: virtual int __thiscall ProvUInteger32::Equivalent(class ProvValue const &)const ` | 648 (0x288) | Exported Function | 0x1001d640 | 0x0001d640
`protected: __thiscall ProvInstanceType::ProvInstanceType(int,int)` | 74 (0x4a) | Exported Function | 0x10011670 | 0x00011670
`protected: __thiscall ProvInstanceType::ProvInstanceType(class ProvInstanceType const &)` | 73 (0x49) | Exported Function | 0x10011640 | 0x00011640
`private: void __thiscall ProvOctetString::OverWrite(unsigned char const *)` | 817 (0x331) | Exported Function | 0x1001daf0 | 0x0001daf0
`const ProvGaugeType::``vftable'{for ``ProvPositiveRangedType'}` | 435 (0x1b3) | Exported Function | 0x100032a0 | 0x000032a0
`const ProvInstanceType::``vftable'` | 436 (0x1b4) | Exported Function | 0x10001300 | 0x00001300
`const ProvInteger::``vftable'` | 437 (0x1b5) | Exported Function | 0x100013c0 | 0x000013c0
`const ProvIntegerType::``vftable'{for ``ProvInstanceType'}` | 438 (0x1b6) | Exported Function | 0x100032e0 | 0x000032e0
`const ProvIntegerType::``vftable'{for ``ProvNegativeRangedType'}` | 439 (0x1b7) | Exported Function | 0x100032d4 | 0x000032d4
`const ProvIpAddress::``vftable'` | 440 (0x1b8) | Exported Function | 0x10001380 | 0x00001380
`const ProvIpAddressType::``vftable'` | 441 (0x1b9) | Exported Function | 0x10003228 | 0x00003228
`const ProvMacAddressType::``vftable'` | 442 (0x1ba) | Exported Function | 0x1000129c | 0x0000129c
`const ProvMacAddressType::``vftable'{for ``ProvInstanceType'}` | 443 (0x1bb) | Exported Function | 0x100012b0 | 0x000012b0
`const ProvMacAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 444 (0x1bc) | Exported Function | 0x100012a4 | 0x000012a4
`const ProvNegativeRangeType::``vftable'` | 445 (0x1bd) | Exported Function | 0x1000133c | 0x0000133c
`const ProvNetworkAddressType::``vftable'` | 446 (0x1be) | Exported Function | 0x10003200 | 0x00003200
`const ProvGaugeType::``vftable'{for ``ProvInstanceType'}` | 434 (0x1b2) | Exported Function | 0x100032ac | 0x000032ac
`const ProvNull::``vftable'` | 447 (0x1bf) | Exported Function | 0x100013d0 | 0x000013d0
`const ProvObjectIdentifier::``vftable'` | 451 (0x1c3) | Exported Function | 0x10003358 | 0x00003358
`const ProvObjectIdentifierType::``vftable'` | 452 (0x1c4) | Exported Function | 0x100031d8 | 0x000031d8
`const ProvOctetString::``vftable'` | 453 (0x1c5) | Exported Function | 0x10003378 | 0x00003378
`const ProvOctetStringType::``vftable'{for ``ProvInstanceType'}` | 454 (0x1c6) | Exported Function | 0x10003140 | 0x00003140
`const ProvOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 455 (0x1c7) | Exported Function | 0x10003134 | 0x00003134
`const ProvOpaque::``vftable'` | 456 (0x1c8) | Exported Function | 0x10003348 | 0x00003348
`const ProvOpaqueType::``vftable'{for ``ProvInstanceType'}` | 457 (0x1c9) | Exported Function | 0x100031b0 | 0x000031b0
`const ProvOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 458 (0x1ca) | Exported Function | 0x100031a4 | 0x000031a4
`const ProvOSIAddressType::``vftable'{for ``ProvInstanceType'}` | 449 (0x1c1) | Exported Function | 0x10001160 | 0x00001160
`const ProvOSIAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 450 (0x1c2) | Exported Function | 0x10001154 | 0x00001154
`const ProvPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 459 (0x1cb) | Exported Function | 0x10001274 | 0x00001274
`const ProvPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 460 (0x1cc) | Exported Function | 0x10001268 | 0x00001268
`const ProvNullType::``vftable'` | 448 (0x1c0) | Exported Function | 0x10003308 | 0x00003308
`const ProvPositiveRangedType::``vftable'` | 462 (0x1ce) | Exported Function | 0x10003330 | 0x00003330
`const ProvGauge::``vftable'` | 433 (0x1b1) | Exported Function | 0x100013b0 | 0x000013b0
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 431 (0x1af) | Exported Function | 0x10001234 | 0x00001234
`const PartitionSet::``vftable'` | 405 (0x195) | Exported Function | 0x100010d4 | 0x000010d4
`const ProvAnalyser::``vftable'` | 406 (0x196) | Exported Function | 0x10001348 | 0x00001348
`const ProvBitStringType::``vftable'{for ``ProvInstanceType'}` | 407 (0x197) | Exported Function | 0x1000309c | 0x0000309c
`const ProvBitStringType::``vftable'{for ``ProvPositiveRangedType'}` | 408 (0x198) | Exported Function | 0x10003090 | 0x00003090
`const ProvCounter64::``vftable'` | 409 (0x199) | Exported Function | 0x10001360 | 0x00001360
`const ProvCounter64Type::``vftable'` | 410 (0x19a) | Exported Function | 0x100012d8 | 0x000012d8
`const ProvCounter::``vftable'` | 411 (0x19b) | Exported Function | 0x100013a0 | 0x000013a0
`const ProvCounterType::``vftable'` | 412 (0x19c) | Exported Function | 0x10003250 | 0x00003250
`const ProvDateTimeType::``vftable'{for ``ProvInstanceType'}` | 413 (0x19d) | Exported Function | 0x10003068 | 0x00003068
`const ProvDateTimeType::``vftable'{for ``ProvPositiveRangedType'}` | 414 (0x19e) | Exported Function | 0x1000305c | 0x0000305c
`const ProvDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 415 (0x19f) | Exported Function | 0x10001204 | 0x00001204
`const ProvDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 416 (0x1a0) | Exported Function | 0x100011f8 | 0x000011f8
`const ProvFixedType::``vftable'` | 432 (0x1b0) | Exported Function | 0x10001328 | 0x00001328
`const ProvEnumeratedType::``vftable'{for ``ProvInstanceType'}` | 417 (0x1a1) | Exported Function | 0x100030d0 | 0x000030d0
`const ProvEventObject::``vftable'` | 419 (0x1a3) | Exported Function | 0x10001104 | 0x00001104
`const ProvFixedLengthDisplayStringType::``vftable'` | 420 (0x1a4) | Exported Function | 0x100011bc | 0x000011bc
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvInstanceType'}` | 421 (0x1a5) | Exported Function | 0x100011d0 | 0x000011d0
`const ProvFixedLengthDisplayStringType::``vftable'{for ``ProvPositiveRangedType'}` | 422 (0x1a6) | Exported Function | 0x100011c4 | 0x000011c4
`const ProvFixedLengthOctetStringType::``vftable'` | 423 (0x1a7) | Exported Function | 0x100030f8 | 0x000030f8
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvInstanceType'}` | 424 (0x1a8) | Exported Function | 0x1000310c | 0x0000310c
`const ProvFixedLengthOctetStringType::``vftable'{for ``ProvPositiveRangedType'}` | 425 (0x1a9) | Exported Function | 0x10003100 | 0x00003100
`const ProvFixedLengthOpaqueType::``vftable'` | 426 (0x1aa) | Exported Function | 0x10003168 | 0x00003168
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvInstanceType'}` | 427 (0x1ab) | Exported Function | 0x1000317c | 0x0000317c
`const ProvFixedLengthOpaqueType::``vftable'{for ``ProvPositiveRangedType'}` | 428 (0x1ac) | Exported Function | 0x10003170 | 0x00003170
`const ProvFixedLengthPhysAddressType::``vftable'` | 429 (0x1ad) | Exported Function | 0x1000122c | 0x0000122c
`const ProvFixedLengthPhysAddressType::``vftable'{for ``ProvInstanceType'}` | 430 (0x1ae) | Exported Function | 0x10001240 | 0x00001240
`const ProvEnumeratedType::``vftable'{for ``ProvNegativeRangedType'}` | 418 (0x1a2) | Exported Function | 0x100030c4 | 0x000030c4
`const ProvPositiveRangeType::``vftable'` | 461 (0x1cd) | Exported Function | 0x10001330 | 0x00001330
`const ProvRowStatusType::``vftable'{for ``ProvInstanceType'}` | 463 (0x1cf) | Exported Function | 0x10001194 | 0x00001194
`const ProvRowStatusType::``vftable'{for ``ProvNegativeRangedType'}` | 464 (0x1d0) | Exported Function | 0x10001188 | 0x00001188
`const WmiUnsignedIntegerNode::``vftable'` | 496 (0x1f0) | Exported Function | 0x10001004 | 0x00001004
`const WmiUnsignedIntegerRangeNode::``vftable'` | 497 (0x1f1) | Exported Function | 0x10001018 | 0x00001018
`const WmiValueNode::``vftable'` | 498 (0x1f2) | Exported Function | 0x100010ac | 0x000010ac
`int __stdcall CompareElements<unsigned short *,unsigned short *>(unsigned short * const *,unsigned short * const *)` | 1 (0x1) | Exported Function | 0x1000f890 | 0x0000f890
`private: __thiscall ProvValue::ProvValue(class ProvValue const &)` | 165 (0xa5) | Exported Function | 0x10013350 | 0x00013350
`private: class ProvLexicon * __thiscall ProvAnalyser::GetToken(int,int,int)` | 733 (0x2dd) | Exported Function | 0x10019720 | 0x00019720
`private: class ProvLexicon * __thiscall ProvBitStringType::Get(void)` | 656 (0x290) | Exported Function | 0x10017f40 | 0x00017f40
`private: class ProvLexicon * __thiscall ProvBitStringType::Match(enum ProvLexicon::LexiconToken)` | 810 (0x32a) | Exported Function | 0x1001a460 | 0x0001a460
`private: class ProvLexicon * __thiscall ProvDateTimeType::Get(void)` | 657 (0x291) | Exported Function | 0x10017fb0 | 0x00017fb0
`private: class ProvLexicon * __thiscall ProvDateTimeType::Match(enum ProvLexicon::LexiconToken)` | 811 (0x32b) | Exported Function | 0x1001a490 | 0x0001a490
`private: class ProvLexicon * __thiscall ProvEnumeratedType::Get(void)` | 658 (0x292) | Exported Function | 0x10018010 | 0x00018010
`private: class ProvLexicon * __thiscall ProvEnumeratedType::Match(enum ProvLexicon::LexiconToken)` | 812 (0x32c) | Exported Function | 0x1001a4c0 | 0x0001a4c0
`const WmiTreeNodeIterator::``vftable'` | 495 (0x1ef) | Exported Function | 0x100014dc | 0x000014dc
`private: class ProvValue & __thiscall ProvValue::operator=(class ProvValue const &)` | 353 (0x161) | Exported Function | 0x10014b20 | 0x00014b20
`private: int __thiscall ProvBitStringType::Parse(unsigned short const *)` | 818 (0x332) | Exported Function | 0x1001a6c0 | 0x0001a6c0
`private: int __thiscall ProvBitStringType::RecursiveDef(void)` | 873 (0x369) | Exported Function | 0x1001c3a0 | 0x0001c3a0
`private: int __thiscall ProvDateTimeType::DateTimeDef(void)` | 604 (0x25c) | Exported Function | 0x100175d0 | 0x000175d0
`private: int __thiscall ProvDateTimeType::Parse(unsigned short const *)` | 821 (0x335) | Exported Function | 0x1001aaa0 | 0x0001aaa0
`private: int __thiscall ProvEnumeratedType::EnumerationDef(void)` | 616 (0x268) | Exported Function | 0x10017ac0 | 0x00017ac0
`private: int __thiscall ProvEnumeratedType::Parse(unsigned short const *)` | 822 (0x336) | Exported Function | 0x1001aad0 | 0x0001aad0
`private: int __thiscall ProvEnumeratedType::RecursiveDef(void)` | 874 (0x36a) | Exported Function | 0x1001c400 | 0x0001c400
`private: void __thiscall ProvBitStringType::PushBack(void)` | 864 (0x360) | Exported Function | 0x1001c030 | 0x0001c030
`private: void __thiscall ProvDateTimeType::Encode(unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &,unsigned long const &)` | 615 (0x267) | Exported Function | 0x100179f0 | 0x000179f0
`private: void __thiscall ProvDateTimeType::PushBack(void)` | 865 (0x361) | Exported Function | 0x1001c040 | 0x0001c040
`private: void __thiscall ProvEnumeratedType::PushBack(void)` | 866 (0x362) | Exported Function | 0x1001c050 | 0x0001c050
`private: void __thiscall ProvObjectIdentifier::OverWrite(unsigned long const *)` | 816 (0x330) | Exported Function | 0x1001dac0 | 0x0001dac0
`private: int __thiscall ProvBitStringType::BitStringDef(void)` | 526 (0x20e) | Exported Function | 0x10016bc0 | 0x00016bc0
`const WmiTreeNode::``vftable'` | 494 (0x1ee) | Exported Function | 0x1000102c | 0x0000102c
`const WmiStringRangeNode::``vftable'` | 493 (0x1ed) | Exported Function | 0x10001054 | 0x00001054
`const WmiStringNode::``vftable'` | 492 (0x1ec) | Exported Function | 0x100010c0 | 0x000010c0
`const ProvTimeTicks::``vftable'` | 465 (0x1d1) | Exported Function | 0x10001390 | 0x00001390
`const ProvTimeTicksType::``vftable'` | 466 (0x1d2) | Exported Function | 0x10003278 | 0x00003278
`const ProvUDPAddressType::``vftable'` | 467 (0x1d3) | Exported Function | 0x10001118 | 0x00001118
`const ProvUDPAddressType::``vftable'{for ``ProvInstanceType'}` | 468 (0x1d4) | Exported Function | 0x1000112c | 0x0000112c
`const ProvUDPAddressType::``vftable'{for ``ProvPositiveRangedType'}` | 469 (0x1d5) | Exported Function | 0x10001120 | 0x00001120
`const ProvUInteger32::``vftable'` | 470 (0x1d6) | Exported Function | 0x10001370 | 0x00001370
`const ProvValue::``vftable'` | 471 (0x1d7) | Exported Function | 0x100013e0 | 0x000013e0
`const QueryPreprocessor::``vftable'` | 472 (0x1d8) | Exported Function | 0x100010dc | 0x000010dc
`const WmiAndNode::``vftable'` | 473 (0x1d9) | Exported Function | 0x10001068 | 0x00001068
`const WmiNotNode::``vftable'` | 474 (0x1da) | Exported Function | 0x100033d0 | 0x000033d0
`const WmiNullNode::``vftable'` | 475 (0x1db) | Exported Function | 0x100033a8 | 0x000033a8
`const WmiNullRangeNode::``vftable'` | 476 (0x1dc) | Exported Function | 0x100013f0 | 0x000013f0
`const WmiOperatorEqualNode::``vftable'` | 477 (0x1dd) | Exported Function | 0x10001094 | 0x00001094
`const WmiOperatorEqualOrGreaterNode::``vftable'` | 478 (0x1de) | Exported Function | 0x100014ac | 0x000014ac
`const WmiOperatorEqualOrLessNode::``vftable'` | 479 (0x1df) | Exported Function | 0x10001494 | 0x00001494
`const WmiOperatorGreaterNode::``vftable'` | 480 (0x1e0) | Exported Function | 0x1000147c | 0x0000147c
`const WmiOperatorIsANode::``vftable'` | 481 (0x1e1) | Exported Function | 0x1000141c | 0x0000141c
`const WmiOperatorLessNode::``vftable'` | 482 (0x1e2) | Exported Function | 0x10001464 | 0x00001464
`const WmiOperatorLikeNode::``vftable'` | 483 (0x1e3) | Exported Function | 0x1000144c | 0x0000144c
`const WmiOperatorNode::``vftable'` | 484 (0x1e4) | Exported Function | 0x1000107c | 0x0000107c
`const WmiOperatorNotEqualNode::``vftable'` | 485 (0x1e5) | Exported Function | 0x100014c4 | 0x000014c4
`const WmiOperatorNotIsANode::``vftable'` | 486 (0x1e6) | Exported Function | 0x10001404 | 0x00001404
`const WmiOperatorNotLikeNode::``vftable'` | 487 (0x1e7) | Exported Function | 0x10001434 | 0x00001434
`const WmiOrNode::``vftable'` | 488 (0x1e8) | Exported Function | 0x100033e4 | 0x000033e4
`const WmiRangeNode::``vftable'` | 489 (0x1e9) | Exported Function | 0x10001040 | 0x00001040
`const WmiSignedIntegerNode::``vftable'` | 490 (0x1ea) | Exported Function | 0x100033bc | 0x000033bc
`const WmiSignedIntegerRangeNode::``vftable'` | 491 (0x1eb) | Exported Function | 0x10003394 | 0x00003394
`public: __thiscall PartitionSet::PartitionSet(class PartitionSet const &)` | 8 (0x8) | Exported Function | 0x1001dee0 | 0x0001dee0
`public: __thiscall PartitionSet::PartitionSet(void)` | 9 (0x9) | Exported Function | 0x1001df20 | 0x0001df20
`public: __thiscall ProvAnalyser::ProvAnalyser(class ProvAnalyser const &)` | 10 (0xa) | Exported Function | 0x1000fb50 | 0x0000fb50
`public: __thiscall ProvAnalyser::ProvAnalyser(unsigned short const *)` | 11 (0xb) | Exported Function | 0x1000fb80 | 0x0000fb80
`public: __thiscall ProvUInteger32::ProvUInteger32(long)` | 164 (0xa4) | Exported Function | 0x10013310 | 0x00013310
`public: __thiscall QueryPreprocessor::QueryPreprocessor(class QueryPreprocessor const &)` | 167 (0xa7) | Exported Function | 0x1001df40 | 0x0001df40
`public: __thiscall QueryPreprocessor::QueryPreprocessor(void)` | 168 (0xa8) | Exported Function | 0x10009320 | 0x00009320
`public: __thiscall WmiAndNode::WmiAndNode(class WmiAndNode const &)` | 169 (0xa9) | Exported Function | 0x1001df50 | 0x0001df50
`public: __thiscall WmiAndNode::WmiAndNode(class WmiTreeNode *,class WmiTreeNode *,class WmiTreeNode *)` | 170 (0xaa) | Exported Function | 0x1001dfb0 | 0x0001dfb0
`public: __thiscall WmiNotNode::WmiNotNode(class WmiNotNode const &)` | 171 (0xab) | Exported Function | 0x1001dff0 | 0x0001dff0
`public: __thiscall WmiNotNode::WmiNotNode(class WmiTreeNode *,class WmiTreeNode *)` | 172 (0xac) | Exported Function | 0x1001e050 | 0x0001e050
`public: __thiscall WmiNullNode::WmiNullNode(class WmiNullNode &&)` | 173 (0xad) | Exported Function | 0x1001e090 | 0x0001e090
`public: __thiscall WmiNullNode::WmiNullNode(class WmiNullNode const &)` | 174 (0xae) | Exported Function | 0x1001e090 | 0x0001e090
`public: __thiscall WmiNullNode::WmiNullNode(unsigned short *,unsigned long,class WmiTreeNode *)` | 175 (0xaf) | Exported Function | 0x1001e0f0 | 0x0001e0f0
`public: __thiscall WmiNullRangeNode::WmiNullRangeNode(class WmiNullRangeNode const &)` | 176 (0xb0) | Exported Function | 0x1001e140 | 0x0001e140
`public: __thiscall WmiNullRangeNode::WmiNullRangeNode(unsigned short *,unsigned long,class WmiTreeNode *,class WmiTreeNode *)` | 177 (0xb1) | Exported Function | 0x1001e1a0 | 0x0001e1a0
`public: __thiscall ProvUInteger32::ProvUInteger32(class ProvUInteger32 const &)` | 163 (0xa3) | Exported Function | 0x1001cee0 | 0x0001cee0
`public: __thiscall WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiOperatorEqualNode const &)` | 178 (0xb2) | Exported Function | 0x1001e1f0 | 0x0001e1f0
`public: __thiscall WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiOperatorEqualOrGreaterNode const &)` | 180 (0xb4) | Exported Function | 0x1001e2a0 | 0x0001e2a0
`public: __thiscall WmiOperatorEqualOrGreaterNode::WmiOperatorEqualOrGreaterNode(class WmiTreeNode *,class WmiTreeNode *)` | 181 (0xb5) | Exported Function | 0x1001e310 | 0x0001e310
`public: __thiscall WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiOperatorEqualOrLessNode const &)` | 182 (0xb6) | Exported Function | 0x1001e350 | 0x0001e350
`public: __thiscall WmiOperatorEqualOrLessNode::WmiOperatorEqualOrLessNode(class WmiTreeNode *,class WmiTreeNode *)` | 183 (0xb7) | Exported Function | 0x1001e3c0 | 0x0001e3c0
`public: __thiscall WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiOperatorGreaterNode const &)` | 184 (0xb8) | Exported Function | 0x1001e400 | 0x0001e400
`public: __thiscall WmiOperatorGreaterNode::WmiOperatorGreaterNode(class WmiTreeNode *,class WmiTreeNode *)` | 185 (0xb9) | Exported Function | 0x1001e470 | 0x0001e470
`public: __thiscall WmiOperatorIsANode::WmiOperatorIsANode(class WmiOperatorIsANode const &)` | 186 (0xba) | Exported Function | 0x1001e4b0 | 0x0001e4b0
`public: __thiscall WmiOperatorIsANode::WmiOperatorIsANode(class WmiTreeNode *,class WmiTreeNode *)` | 187 (0xbb) | Exported Function | 0x1001e520 | 0x0001e520
`public: __thiscall WmiOperatorLessNode::WmiOperatorLessNode(class WmiOperatorLessNode const &)` | 188 (0xbc) | Exported Function | 0x1001e560 | 0x0001e560
`public: __thiscall WmiOperatorLessNode::WmiOperatorLessNode(class WmiTreeNode *,class WmiTreeNode *)` | 189 (0xbd) | Exported Function | 0x1001e5d0 | 0x0001e5d0
`public: __thiscall WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiOperatorLikeNode const &)` | 190 (0xbe) | Exported Function | 0x1001e610 | 0x0001e610
`public: __thiscall WmiOperatorLikeNode::WmiOperatorLikeNode(class WmiTreeNode *,class WmiTreeNode *)` | 191 (0xbf) | Exported Function | 0x1001e680 | 0x0001e680
`public: __thiscall WmiOperatorEqualNode::WmiOperatorEqualNode(class WmiTreeNode *,class WmiTreeNode *)` | 179 (0xb3) | Exported Function | 0x1001e260 | 0x0001e260
`public: __thiscall WmiOperatorNode::WmiOperatorNode(class WmiOperatorNode const &)` | 192 (0xc0) | Exported Function | 0x1001e6c0 | 0x0001e6c0
`public: __thiscall ProvUDPAddressType::ProvUDPAddressType(void)` | 162 (0xa2) | Exported Function | 0x100132c0 | 0x000132c0
`public: __thiscall ProvUDPAddressType::ProvUDPAddressType(unsigned char const *)` | 160 (0xa0) | Exported Function | 0x10013210 | 0x00013210
`public: __thiscall ProvOSIAddressType::ProvOSIAddressType(void)` | 112 (0x70) | Exported Function | 0x10012290 | 0x00012290
`public: __thiscall ProvPhysAddressType::ProvPhysAddressType(class ProvOctetString const &,unsigned short const *)` | 136 (0x88) | Exported Function | 0x10012ad0 | 0x00012ad0
`public: __thiscall ProvPhysAddressType::ProvPhysAddressType(class ProvPhysAddressType const &)` | 135 (0x87) | Exported Function | 0x10012a90 | 0x00012a90
`public: __thiscall ProvPhysAddressType::ProvPhysAddressType(unsigned char const *,unsigned long,unsigned short const *)` | 137 (0x89) | Exported Function | 0x10012b10 | 0x00012b10
`public: __thiscall ProvPhysAddressType::ProvPhysAddressType(unsigned short const *)` | 139 (0x8b) | Exported Function | 0x10012bb0 | 0x00012bb0
`public: __thiscall ProvPhysAddressType::ProvPhysAddressType(unsigned short const *,unsigned short const *)` | 138 (0x8a) | Exported Function | 0x10012b60 | 0x00012b60
`public: __thiscall ProvPositiveRangedType::ProvPositiveRangedType(class ProvPositiveRangedType const &)` | 143 (0x8f) | Exported Function | 0x10012c80 | 0x00012c80
`public: __thiscall ProvPositiveRangedType::ProvPositiveRangedType(unsigned short const *)` | 144 (0x90) | Exported Function | 0x10012d30 | 0x00012d30
`public: __thiscall ProvPositiveRangeType::ProvPositiveRangeType(class ProvPositiveRangeType const &)` | 140 (0x8c) | Exported Function | 0x10012c00 | 0x00012c00
`public: __thiscall ProvPositiveRangeType::ProvPositiveRangeType(unsigned long,long)` | 141 (0x8d) | Exported Function | 0x10012c30 | 0x00012c30
`public: __thiscall ProvPositiveRangeType::ProvPositiveRangeType(void)` | 142 (0x8e) | Exported Function | 0x10012c60 | 0x00012c60
`public: __thiscall ProvRowStatusType::ProvRowStatusType(class ProvInteger const &)` | 147 (0x93) | Exported Function | 0x10012e30 | 0x00012e30
`public: __thiscall ProvUDPAddressType::ProvUDPAddressType(unsigned short const *)` | 161 (0xa1) | Exported Function | 0x10013260 | 0x00013260
`public: __thiscall ProvRowStatusType::ProvRowStatusType(class ProvRowStatusType const &)` | 146 (0x92) | Exported Function | 0x10012df0 | 0x00012df0
`public: __thiscall ProvRowStatusType::ProvRowStatusType(long const &)` | 145 (0x91) | Exported Function | 0x10012da0 | 0x00012da0
`public: __thiscall ProvRowStatusType::ProvRowStatusType(unsigned short const *)` | 149 (0x95) | Exported Function | 0x10012ed0 | 0x00012ed0
`public: __thiscall ProvRowStatusType::ProvRowStatusType(void)` | 150 (0x96) | Exported Function | 0x10012f20 | 0x00012f20
`public: __thiscall ProvTimeTicks::ProvTimeTicks(class ProvTimeTicks const &)` | 151 (0x97) | Exported Function | 0x1001cea0 | 0x0001cea0
`public: __thiscall ProvTimeTicks::ProvTimeTicks(unsigned long)` | 152 (0x98) | Exported Function | 0x10012f60 | 0x00012f60
`public: __thiscall ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicks const &)` | 154 (0x9a) | Exported Function | 0x10012ff0 | 0x00012ff0
`public: __thiscall ProvTimeTicksType::ProvTimeTicksType(class ProvTimeTicksType const &)` | 153 (0x99) | Exported Function | 0x10012fa0 | 0x00012fa0
`public: __thiscall ProvTimeTicksType::ProvTimeTicksType(unsigned long)` | 155 (0x9b) | Exported Function | 0x10013040 | 0x00013040
`public: __thiscall ProvTimeTicksType::ProvTimeTicksType(unsigned short const *)` | 156 (0x9c) | Exported Function | 0x100130a0 | 0x000130a0
`public: __thiscall ProvTimeTicksType::ProvTimeTicksType(void)` | 157 (0x9d) | Exported Function | 0x10013110 | 0x00013110
`public: __thiscall ProvUDPAddressType::ProvUDPAddressType(class ProvOctetString const &)` | 159 (0x9f) | Exported Function | 0x100131c0 | 0x000131c0
`public: __thiscall ProvUDPAddressType::ProvUDPAddressType(class ProvUDPAddressType const &)` | 158 (0x9e) | Exported Function | 0x10013170 | 0x00013170
`public: __thiscall ProvRowStatusType::ProvRowStatusType(enum ProvRowStatusType::ProvRowStatusEnum const &)` | 148 (0x94) | Exported Function | 0x10012e80 | 0x00012e80
`public: __thiscall WmiOperatorNode::WmiOperatorNode(unsigned long,class WmiTreeNode *,class WmiTreeNode *)` | 193 (0xc1) | Exported Function | 0x1001e720 | 0x0001e720
`public: __thiscall WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiOperatorNotEqualNode const &)` | 194 (0xc2) | Exported Function | 0x1001e760 | 0x0001e760
`public: __thiscall WmiOperatorNotEqualNode::WmiOperatorNotEqualNode(class WmiTreeNode *,class WmiTreeNode *)` | 195 (0xc3) | Exported Function | 0x1001e7d0 | 0x0001e7d0
`public: __thiscall WmiValueNode::WmiValueNode(unsigned long,unsigned short *,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode *)` | 227 (0xe3) | Exported Function | 0x1001efc0 | 0x0001efc0
`public: char * __thiscall ProvObjectIdentifier::GetAllocatedString(void)const ` | 660 (0x294) | Exported Function | 0x1001d900 | 0x0001d900
`public: class CBString & __thiscall CBString::operator=(class CBString const &)` | 303 (0x12f) | Exported Function | 0x100146f0 | 0x000146f0
`public: class CBString const & __thiscall CBString::operator=(unsigned short const *)` | 304 (0x130) | Exported Function | 0x10014710 | 0x00014710
`public: class Conjunctions & __thiscall Conjunctions::operator=(class Conjunctions const &)` | 305 (0x131) | Exported Function | 0x1001fb20 | 0x0001fb20
`public: class Conjunctions * __thiscall Disjunctions::GetDisjunction(unsigned long)` | 665 (0x299) | Exported Function | 0x10021b30 | 0x00021b30
`public: class Disjunctions & __thiscall Disjunctions::operator=(class Disjunctions const &)` | 306 (0x132) | Exported Function | 0x1001fb40 | 0x0001fb40
`public: class PartitionSet & __thiscall PartitionSet::operator=(class PartitionSet const &)` | 307 (0x133) | Exported Function | 0x10014820 | 0x00014820
`public: class PartitionSet * __thiscall PartitionSet::GetPartition(unsigned long)` | 688 (0x2b0) | Exported Function | 0x10009230 | 0x00009230
`public: class ProvAnalyser & __thiscall ProvAnalyser::operator=(class ProvAnalyser const &)` | 308 (0x134) | Exported Function | 0x10014740 | 0x00014740
`public: class ProvBitStringType & __thiscall ProvBitStringType::operator=(class ProvBitStringType const &)` | 309 (0x135) | Exported Function | 0x10014770 | 0x00014770
`public: class ProvCounter64Type & __thiscall ProvCounter64Type::operator=(class ProvCounter64Type const &)` | 311 (0x137) | Exported Function | 0x10014820 | 0x00014820
`public: __thiscall WmiValueNode::WmiValueNode(class WmiValueNode const &)` | 226 (0xe2) | Exported Function | 0x1001ef40 | 0x0001ef40
`public: class ProvCounterType & __thiscall ProvCounterType::operator=(class ProvCounterType const &)` | 313 (0x139) | Exported Function | 0x10014850 | 0x00014850
`public: class ProvDebugLog & __thiscall ProvDebugLog::operator=(class ProvDebugLog &&)` | 315 (0x13b) | Exported Function | 0x1000f080 | 0x0000f080
`public: class ProvDebugLog & __thiscall ProvDebugLog::operator=(class ProvDebugLog const &)` | 316 (0x13c) | Exported Function | 0x1000f080 | 0x0000f080
`public: class ProvDisplayStringType & __thiscall ProvDisplayStringType::operator=(class ProvDisplayStringType const &)` | 317 (0x13d) | Exported Function | 0x100148c0 | 0x000148c0
`public: class ProvEnumeratedType & __thiscall ProvEnumeratedType::operator=(class ProvEnumeratedType const &)` | 318 (0x13e) | Exported Function | 0x100148e0 | 0x000148e0
`public: class ProvEventObject & __thiscall ProvEventObject::operator=(class ProvEventObject const &)` | 319 (0x13f) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvFixedLengthDisplayStringType & __thiscall ProvFixedLengthDisplayStringType::operator=(class ProvFixedLengthDisplayStringType const &)` | 320 (0x140) | Exported Function | 0x10014970 | 0x00014970
`public: class ProvFixedLengthOctetStringType & __thiscall ProvFixedLengthOctetStringType::operator=(class ProvFixedLengthOctetStringType const &)` | 321 (0x141) | Exported Function | 0x10014990 | 0x00014990
`public: class ProvFixedLengthOpaqueType & __thiscall ProvFixedLengthOpaqueType::operator=(class ProvFixedLengthOpaqueType const &)` | 322 (0x142) | Exported Function | 0x100149c0 | 0x000149c0
`public: class ProvFixedLengthPhysAddressType & __thiscall ProvFixedLengthPhysAddressType::operator=(class ProvFixedLengthPhysAddressType const &)` | 323 (0x143) | Exported Function | 0x10014970 | 0x00014970
`public: class ProvFixedType & __thiscall ProvFixedType::operator=(class ProvFixedType const &)` | 324 (0x144) | Exported Function | 0x1000f0a0 | 0x0000f0a0
`public: class ProvGaugeType & __thiscall ProvGaugeType::operator=(class ProvGaugeType const &)` | 326 (0x146) | Exported Function | 0x100149f0 | 0x000149f0
`public: class ProvInstanceType & __thiscall ProvInstanceType::operator=(class ProvInstanceType const &)` | 327 (0x147) | Exported Function | 0x10014a30 | 0x00014a30
`public: class ProvDateTimeType & __thiscall ProvDateTimeType::operator=(class ProvDateTimeType const &)` | 314 (0x13a) | Exported Function | 0x10014880 | 0x00014880
`public: __thiscall WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(unsigned short *,unsigned long,int,int,int,int,unsigned long,unsigned long,class WmiTreeNode *,class WmiTreeNode *)` | 225 (0xe1) | Exported Function | 0x10006ff0 | 0x00006ff0
`public: __thiscall WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode const &)` | 224 (0xe0) | Exported Function | 0x1001eed0 | 0x0001eed0
`public: __thiscall WmiUnsignedIntegerRangeNode::WmiUnsignedIntegerRangeNode(class WmiUnsignedIntegerRangeNode &&)` | 223 (0xdf) | Exported Function | 0x1001eed0 | 0x0001eed0
`public: __thiscall WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiOperatorNotIsANode const &)` | 196 (0xc4) | Exported Function | 0x1001e810 | 0x0001e810
`public: __thiscall WmiOperatorNotIsANode::WmiOperatorNotIsANode(class WmiTreeNode *,class WmiTreeNode *)` | 197 (0xc5) | Exported Function | 0x1001e880 | 0x0001e880
`public: __thiscall WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiOperatorNotLikeNode const &)` | 198 (0xc6) | Exported Function | 0x1001e8c0 | 0x0001e8c0
`public: __thiscall WmiOperatorNotLikeNode::WmiOperatorNotLikeNode(class WmiTreeNode *,class WmiTreeNode *)` | 199 (0xc7) | Exported Function | 0x1001e930 | 0x0001e930
`public: __thiscall WmiOrNode::WmiOrNode(class WmiOrNode const &)` | 200 (0xc8) | Exported Function | 0x1001e970 | 0x0001e970
`public: __thiscall WmiOrNode::WmiOrNode(class WmiTreeNode *,class WmiTreeNode *,class WmiTreeNode *)` | 201 (0xc9) | Exported Function | 0x1001e9d0 | 0x0001e9d0
`public: __thiscall WmiRangeNode::WmiRangeNode(class WmiRangeNode const &)` | 202 (0xca) | Exported Function | 0x1001ea10 | 0x0001ea10
`public: __thiscall WmiRangeNode::WmiRangeNode(unsigned long,unsigned short *,unsigned long,int,int,int,int,class WmiTreeNode *,class WmiTreeNode *)` | 203 (0xcb) | Exported Function | 0x1001ea90 | 0x0001ea90
`public: __thiscall WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode &&)` | 204 (0xcc) | Exported Function | 0x1001eb20 | 0x0001eb20
`public: __thiscall WmiSignedIntegerNode::WmiSignedIntegerNode(class WmiSignedIntegerNode const &)` | 205 (0xcd) | Exported Function | 0x1001eb20 | 0x0001eb20
`public: __thiscall WmiSignedIntegerNode::WmiSignedIntegerNode(unsigned short *,long,unsigned long,class WmiTreeNode *)` | 206 (0xce) | Exported Function | 0x1001eb90 | 0x0001eb90
`public: __thiscall WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode &&)` | 207 (0xcf) | Exported Function | 0x1001ebe0 | 0x0001ebe0
`public: __thiscall WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(class WmiSignedIntegerRangeNode const &)` | 208 (0xd0) | Exported Function | 0x1001ebe0 | 0x0001ebe0
`public: __thiscall WmiSignedIntegerRangeNode::WmiSignedIntegerRangeNode(unsigned short *,unsigned long,int,int,int,int,long,long,class WmiTreeNode *,class WmiTreeNode *)` | 209 (0xd1) | Exported Function | 0x1001ec50 | 0x0001ec50
`public: __thiscall WmiStringNode::WmiStringNode(class WmiStringNode const &)` | 210 (0xd2) | Exported Function | 0x1001ecb0 | 0x0001ecb0
`public: __thiscall WmiStringNode::WmiStringNode(unsigned short *,unsigned short *,enum WmiValueNode::WmiValueFunction,enum WmiValueNode::WmiValueFunction,unsigned long,class WmiTreeNode *)` | 211 (0xd3) | Exported Function | 0x10007800 | 0x00007800
`public: __thiscall WmiStringRangeNode::WmiStringRangeNode(class WmiStringRangeNode const &)` | 212 (0xd4) | Exported Function | 0x1001ed20 | 0x0001ed20
`public: __thiscall WmiStringRangeNode::WmiStringRangeNode(unsigned short *,unsigned long,int,int,int,int,unsigned short *,unsigned short *,class WmiTreeNode *,class WmiTreeNode *)` | 213 (0xd5) | Exported Function | 0x10007430 | 0x00007430
`public: __thiscall WmiTreeNode::WmiTreeNode(class WmiTreeNode *)` | 216 (0xd8) | Exported Function | 0x1001ed90 | 0x0001ed90
`public: __thiscall WmiTreeNode::WmiTreeNode(class WmiTreeNode const &)` | 214 (0xd6) | Exported Function | 0x1001ed90 | 0x0001ed90
`public: __thiscall WmiTreeNode::WmiTreeNode(unsigned long,void *,class WmiTreeNode *,class WmiTreeNode *,class WmiTreeNode *)` | 215 (0xd7) | Exported Function | 0x1001edd0 | 0x0001edd0
`public: __thiscall WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNode *)` | 219 (0xdb) | Exported Function | 0x1001ee40 | 0x0001ee40
`public: __thiscall WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator *)` | 218 (0xda) | Exported Function | 0x1001ee20 | 0x0001ee20
`public: __thiscall WmiTreeNodeIterator::WmiTreeNodeIterator(class WmiTreeNodeIterator const &)` | 217 (0xd9) | Exported Function | 0x1001ee20 | 0x0001ee20
`public: __thiscall WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode &&)` | 220 (0xdc) | Exported Function | 0x1001ee60 | 0x0001ee60
`public: __thiscall WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(class WmiUnsignedIntegerNode const &)` | 221 (0xdd) | Exported Function | 0x1001ee60 | 0x0001ee60
`public: __thiscall WmiUnsignedIntegerNode::WmiUnsignedIntegerNode(unsigned short *,unsigned long,unsigned long,class WmiTreeNode *)` | 222 (0xde) | Exported Function | 0x10006eb0 | 0x00006eb0
`public: __thiscall ProvOSIAddressType::ProvOSIAddressType(unsigned short const *)` | 111 (0x6f) | Exported Function | 0x10012240 | 0x00012240
`public: class ProvIpAddressType & __thiscall ProvIpAddressType::operator=(class ProvIpAddressType const &)` | 331 (0x14b) | Exported Function | 0x10014a80 | 0x00014a80
`public: __thiscall ProvOSIAddressType::ProvOSIAddressType(unsigned char const *,unsigned long)` | 110 (0x6e) | Exported Function | 0x100121e0 | 0x000121e0
`public: __thiscall ProvOSIAddressType::ProvOSIAddressType(class ProvOctetString const &)` | 109 (0x6d) | Exported Function | 0x10012180 | 0x00012180
`public: __thiscall ProvEnumeratedType::ProvEnumeratedType(unsigned short const *,long const &)` | 42 (0x2a) | Exported Function | 0x10010a90 | 0x00010a90
`public: __thiscall ProvEnumeratedType::ProvEnumeratedType(unsigned short const *,unsigned short const *)` | 40 (0x28) | Exported Function | 0x10010900 | 0x00010900
`public: __thiscall ProvEventObject::ProvEventObject(class ProvEventObject const &)` | 44 (0x2c) | Exported Function | 0x1000f060 | 0x0000f060
`public: __thiscall ProvEventObject::ProvEventObject(unsigned short const *)` | 45 (0x2d) | Exported Function | 0x1000f7a0 | 0x0000f7a0
`public: __thiscall ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(class ProvFixedLengthDisplayStringType const &)` | 49 (0x31) | Exported Function | 0x10010d00 | 0x00010d00
`public: __thiscall ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const &)` | 46 (0x2e) | Exported Function | 0x10010be0 | 0x00010be0
`public: __thiscall ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const &,class ProvOctetString const &)` | 47 (0x2f) | Exported Function | 0x10010c30 | 0x00010c30
`public: __thiscall ProvFixedLengthDisplayStringType::ProvFixedLengthDisplayStringType(unsigned long const &,unsigned short const *)` | 48 (0x30) | Exported Function | 0x10010c80 | 0x00010c80
`public: __thiscall ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(class ProvFixedLengthOctetStringType const &)` | 54 (0x36) | Exported Function | 0x10010f00 | 0x00010f00
`public: __thiscall ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const &)` | 50 (0x32) | Exported Function | 0x10010d50 | 0x00010d50
`public: __thiscall ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const &,class ProvOctetString const &)` | 51 (0x33) | Exported Function | 0x10010db0 | 0x00010db0
`public: __thiscall ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const &,unsigned char const *)` | 52 (0x34) | Exported Function | 0x10010e20 | 0x00010e20
`public: __thiscall ProvEnumeratedType::ProvEnumeratedType(unsigned short const *,class ProvInteger const &)` | 43 (0x2b) | Exported Function | 0x10010b30 | 0x00010b30
`public: __thiscall ProvFixedLengthOctetStringType::ProvFixedLengthOctetStringType(unsigned long const &,unsigned short const *)` | 53 (0x35) | Exported Function | 0x10010e90 | 0x00010e90
`public: __thiscall ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const &)` | 55 (0x37) | Exported Function | 0x10010f70 | 0x00010f70
`public: __thiscall ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const &,class ProvOpaque const &)` | 56 (0x38) | Exported Function | 0x10010fd0 | 0x00010fd0
`public: __thiscall ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const &,unsigned char const *,unsigned long)` | 57 (0x39) | Exported Function | 0x10011040 | 0x00011040
`public: __thiscall ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(unsigned long const &,unsigned short const *)` | 58 (0x3a) | Exported Function | 0x100110b0 | 0x000110b0
`public: __thiscall ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(class ProvFixedLengthPhysAddressType const &)` | 63 (0x3f) | Exported Function | 0x100112a0 | 0x000112a0
`public: __thiscall ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const &)` | 60 (0x3c) | Exported Function | 0x100111a0 | 0x000111a0
`public: __thiscall ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const &,class ProvOctetString const &)` | 61 (0x3d) | Exported Function | 0x100111f0 | 0x000111f0
`public: __thiscall ProvFixedLengthPhysAddressType::ProvFixedLengthPhysAddressType(unsigned long const &,unsigned short const *)` | 62 (0x3e) | Exported Function | 0x10011240 | 0x00011240
`public: __thiscall ProvFixedType::ProvFixedType(class ProvFixedType const &)` | 64 (0x40) | Exported Function | 0x100112f0 | 0x000112f0
`public: __thiscall ProvFixedType::ProvFixedType(unsigned long)` | 65 (0x41) | Exported Function | 0x10011310 | 0x00011310
`public: __thiscall ProvGauge::ProvGauge(class ProvGauge const &)` | 66 (0x42) | Exported Function | 0x1001cae0 | 0x0001cae0
`public: __thiscall ProvGauge::ProvGauge(long)` | 67 (0x43) | Exported Function | 0x10011330 | 0x00011330
`public: __thiscall ProvFixedLengthOpaqueType::ProvFixedLengthOpaqueType(class ProvFixedLengthOpaqueType const &)` | 59 (0x3b) | Exported Function | 0x10011130 | 0x00011130
`public: __thiscall ProvGaugeType::ProvGaugeType(class ProvGauge const &,unsigned short const *)` | 69 (0x45) | Exported Function | 0x100113e0 | 0x000113e0
`public: __thiscall ProvEnumeratedType::ProvEnumeratedType(unsigned short const *)` | 41 (0x29) | Exported Function | 0x10010a10 | 0x00010a10
`public: __thiscall ProvDisplayStringType::ProvDisplayStringType(unsigned short const *,unsigned short const *)` | 37 (0x25) | Exported Function | 0x10010720 | 0x00010720
`public: __thiscall ProvBitStringType::ProvBitStringType(class ProvBitStringType const &)` | 12 (0xc) | Exported Function | 0x1000fbf0 | 0x0000fbf0
`public: __thiscall ProvBitStringType::ProvBitStringType(unsigned short const *)` | 13 (0xd) | Exported Function | 0x1000fd00 | 0x0000fd00
`public: __thiscall ProvBitStringType::ProvBitStringType(unsigned short const *,class ProvOctetString const &)` | 14 (0xe) | Exported Function | 0x1000fd80 | 0x0000fd80
`public: __thiscall ProvBitStringType::ProvBitStringType(unsigned short const *,unsigned short const * *,unsigned long const &)` | 15 (0xf) | Exported Function | 0x1000fe90 | 0x0000fe90
`public: __thiscall ProvCounter64::ProvCounter64(class ProvCounter64 const &)` | 16 (0x10) | Exported Function | 0x1001ca50 | 0x0001ca50
`public: __thiscall ProvCounter64::ProvCounter64(unsigned long,unsigned long)` | 17 (0x11) | Exported Function | 0x10010140 | 0x00010140
`public: __thiscall ProvCounter64Type::ProvCounter64Type(class ProvCounter64 const &)` | 19 (0x13) | Exported Function | 0x100101d0 | 0x000101d0
`public: __thiscall ProvCounter64Type::ProvCounter64Type(class ProvCounter64Type const &)` | 18 (0x12) | Exported Function | 0x10010180 | 0x00010180
`public: __thiscall ProvCounter64Type::ProvCounter64Type(unsigned long,unsigned long)` | 20 (0x14) | Exported Function | 0x10010220 | 0x00010220
`public: __thiscall ProvCounter64Type::ProvCounter64Type(unsigned short const *)` | 21 (0x15) | Exported Function | 0x10010270 | 0x00010270
`public: __thiscall ProvCounter64Type::ProvCounter64Type(void)` | 22 (0x16) | Exported Function | 0x100102c0 | 0x000102c0
`public: __thiscall ProvCounter::ProvCounter(class ProvCounter const &)` | 23 (0x17) | Exported Function | 0x1001caa0 | 0x0001caa0
`public: __thiscall ProvEnumeratedType::ProvEnumeratedType(class ProvEnumeratedType const &)` | 39 (0x27) | Exported Function | 0x100107f0 | 0x000107f0
`public: __thiscall ProvCounter::ProvCounter(unsigned long)` | 24 (0x18) | Exported Function | 0x10010300 | 0x00010300
`public: __thiscall ProvCounterType::ProvCounterType(class ProvCounterType const &)` | 25 (0x19) | Exported Function | 0x10010340 | 0x00010340
`public: __thiscall ProvCounterType::ProvCounterType(unsigned long)` | 27 (0x1b) | Exported Function | 0x100103e0 | 0x000103e0
`public: __thiscall ProvCounterType::ProvCounterType(unsigned short const *)` | 28 (0x1c) | Exported Function | 0x10010440 | 0x00010440
`public: __thiscall ProvCounterType::ProvCounterType(void)` | 29 (0x1d) | Exported Function | 0x100104b0 | 0x000104b0
`public: __thiscall ProvDateTimeType::ProvDateTimeType(class ProvDateTimeType const &)` | 30 (0x1e) | Exported Function | 0x10010510 | 0x00010510
`public: __thiscall ProvDateTimeType::ProvDateTimeType(class ProvOctetString const &)` | 31 (0x1f) | Exported Function | 0x10010570 | 0x00010570
`public: __thiscall ProvDateTimeType::ProvDateTimeType(unsigned short const *)` | 32 (0x20) | Exported Function | 0x100105e0 | 0x000105e0
`public: __thiscall ProvDateTimeType::ProvDateTimeType(void)` | 33 (0x21) | Exported Function | 0x10010650 | 0x00010650
`public: __thiscall ProvDebugLog::ProvDebugLog(char)` | 34 (0x22) | Exported Function | 0x1000f040 | 0x0000f040
`public: __thiscall ProvDisplayStringType::ProvDisplayStringType(class ProvDisplayStringType const &)` | 35 (0x23) | Exported Function | 0x100106a0 | 0x000106a0
`public: __thiscall ProvDisplayStringType::ProvDisplayStringType(class ProvOctetString const &,unsigned short const *)` | 36 (0x24) | Exported Function | 0x100106e0 | 0x000106e0
`public: __thiscall ProvDisplayStringType::ProvDisplayStringType(unsigned short const *)` | 38 (0x26) | Exported Function | 0x100107a0 | 0x000107a0
`public: __thiscall ProvCounterType::ProvCounterType(class ProvCounter const &)` | 26 (0x1a) | Exported Function | 0x10010390 | 0x00010390
`public: __thiscall ProvGaugeType::ProvGaugeType(class ProvGaugeType const &)` | 68 (0x44) | Exported Function | 0x10011370 | 0x00011370
`public: __thiscall ProvGaugeType::ProvGaugeType(unsigned long,unsigned short const *)` | 70 (0x46) | Exported Function | 0x10011470 | 0x00011470
`public: __thiscall ProvGaugeType::ProvGaugeType(unsigned short const *)` | 72 (0x48) | Exported Function | 0x100115c0 | 0x000115c0
`public: __thiscall ProvNull::ProvNull(void)` | 104 (0x68) | Exported Function | 0x10012050 | 0x00012050
`public: __thiscall ProvNullType::ProvNullType(class ProvNull const &)` | 106 (0x6a) | Exported Function | 0x10012080 | 0x00012080
`public: __thiscall ProvNullType::ProvNullType(class ProvNullType const &)` | 105 (0x69) | Exported Function | 0x10012080 | 0x00012080
`public: __thiscall ProvNullType::ProvNullType(void)` | 107 (0x6b) | Exported Function | 0x100120e0 | 0x000120e0
`public: __thiscall ProvObjectIdentifier::ProvObjectIdentifier(char const *)` | 114 (0x72) | Exported Function | 0x1001ccf0 | 0x0001ccf0
`public: __thiscall ProvObjectIdentifier::ProvObjectIdentifier(class ProvObjectIdentifier const &)` | 113 (0x71) | Exported Function | 0x1001cc90 | 0x0001cc90
`public: __thiscall ProvObjectIdentifier::ProvObjectIdentifier(unsigned long const *,unsigned long)` | 115 (0x73) | Exported Function | 0x1001cda0 | 0x0001cda0
`public: __thiscall ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifier const &)` | 117 (0x75) | Exported Function | 0x10012320 | 0x00012320
`public: __thiscall ProvObjectIdentifierType::ProvObjectIdentifierType(class ProvObjectIdentifierType const &)` | 116 (0x74) | Exported Function | 0x100122d0 | 0x000122d0
`public: __thiscall ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned long const *,unsigned long)` | 119 (0x77) | Exported Function | 0x100123d0 | 0x000123d0
`public: __thiscall ProvObjectIdentifierType::ProvObjectIdentifierType(unsigned short const *)` | 118 (0x76) | Exported Function | 0x10012370 | 0x00012370
`public: __thiscall ProvObjectIdentifierType::ProvObjectIdentifierType(void)` | 120 (0x78) | Exported Function | 0x10012420 | 0x00012420
`public: __thiscall ProvNetworkAddressType::ProvNetworkAddressType(void)` | 103 (0x67) | Exported Function | 0x10012000 | 0x00012000
`public: __thiscall ProvOctetString::ProvOctetString(class ProvOctetString const &)` | 121 (0x79) | Exported Function | 0x1001ce00 | 0x0001ce00
`public: __thiscall ProvOctetStringType::ProvOctetStringType(class ProvOctetString const &,unsigned short const *)` | 124 (0x7c) | Exported Function | 0x100124e0 | 0x000124e0
`public: __thiscall ProvOctetStringType::ProvOctetStringType(class ProvOctetStringType const &)` | 123 (0x7b) | Exported Function | 0x10012470 | 0x00012470
`public: __thiscall ProvOctetStringType::ProvOctetStringType(unsigned char const *,unsigned long,unsigned short const *)` | 125 (0x7d) | Exported Function | 0x10012570 | 0x00012570
`public: __thiscall ProvOctetStringType::ProvOctetStringType(unsigned short const *)` | 127 (0x7f) | Exported Function | 0x100126a0 | 0x000126a0
`public: __thiscall ProvOctetStringType::ProvOctetStringType(unsigned short const *,unsigned short const *)` | 126 (0x7e) | Exported Function | 0x10012600 | 0x00012600
`public: __thiscall ProvOpaque::ProvOpaque(class ProvOpaque const &)` | 128 (0x80) | Exported Function | 0x10012710 | 0x00012710
`public: __thiscall ProvOpaque::ProvOpaque(unsigned char const *,unsigned long)` | 129 (0x81) | Exported Function | 0x10012780 | 0x00012780
`public: __thiscall ProvOpaqueType::ProvOpaqueType(class ProvOpaque const &,unsigned short const *)` | 131 (0x83) | Exported Function | 0x10012860 | 0x00012860
`public: __thiscall ProvOpaqueType::ProvOpaqueType(class ProvOpaqueType const &)` | 130 (0x82) | Exported Function | 0x100127f0 | 0x000127f0
`public: __thiscall ProvOpaqueType::ProvOpaqueType(unsigned char const *,unsigned long,unsigned short const *)` | 132 (0x84) | Exported Function | 0x100128f0 | 0x000128f0
`public: __thiscall ProvOpaqueType::ProvOpaqueType(unsigned short const *)` | 134 (0x86) | Exported Function | 0x10012a20 | 0x00012a20
`public: __thiscall ProvOpaqueType::ProvOpaqueType(unsigned short const *,unsigned short const *)` | 133 (0x85) | Exported Function | 0x10012980 | 0x00012980
`public: __thiscall ProvOctetString::ProvOctetString(unsigned char const *,unsigned long)` | 122 (0x7a) | Exported Function | 0x1001ce50 | 0x0001ce50
`public: __thiscall ProvNetworkAddressType::ProvNetworkAddressType(unsigned short const *)` | 102 (0x66) | Exported Function | 0x10011fa0 | 0x00011fa0
`public: __thiscall ProvNetworkAddressType::ProvNetworkAddressType(unsigned long)` | 101 (0x65) | Exported Function | 0x10011f50 | 0x00011f50
`public: __thiscall ProvNetworkAddressType::ProvNetworkAddressType(class ProvNetworkAddressType const &)` | 99 (0x63) | Exported Function | 0x10011eb0 | 0x00011eb0
`public: __thiscall ProvGaugeType::ProvGaugeType(unsigned short const *,unsigned short const *)` | 71 (0x47) | Exported Function | 0x10011510 | 0x00011510
`public: __thiscall ProvInteger::ProvInteger(class ProvInteger const &)` | 75 (0x4b) | Exported Function | 0x1001cb20 | 0x0001cb20
`public: __thiscall ProvInteger::ProvInteger(long)` | 76 (0x4c) | Exported Function | 0x100116a0 | 0x000116a0
`public: __thiscall ProvIntegerType::ProvIntegerType(class ProvInteger const &,unsigned short const *)` | 78 (0x4e) | Exported Function | 0x10011750 | 0x00011750
`public: __thiscall ProvIntegerType::ProvIntegerType(class ProvIntegerType const &)` | 77 (0x4d) | Exported Function | 0x100116e0 | 0x000116e0
`public: __thiscall ProvIntegerType::ProvIntegerType(long,unsigned short const *)` | 79 (0x4f) | Exported Function | 0x100117c0 | 0x000117c0
`public: __thiscall ProvIntegerType::ProvIntegerType(unsigned short const *)` | 81 (0x51) | Exported Function | 0x10011910 | 0x00011910
`public: __thiscall ProvIntegerType::ProvIntegerType(unsigned short const *,unsigned short const *)` | 80 (0x50) | Exported Function | 0x10011860 | 0x00011860
`public: __thiscall ProvIpAddress::ProvIpAddress(char const *)` | 84 (0x54) | Exported Function | 0x1001cbb0 | 0x0001cbb0
`public: __thiscall ProvIpAddress::ProvIpAddress(class ProvIpAddress const &)` | 82 (0x52) | Exported Function | 0x1001cb60 | 0x0001cb60
`public: __thiscall ProvIpAddress::ProvIpAddress(unsigned long)` | 83 (0x53) | Exported Function | 0x10011990 | 0x00011990
`public: __thiscall ProvIpAddressType::ProvIpAddressType(class ProvIpAddress const &)` | 86 (0x56) | Exported Function | 0x10011a20 | 0x00011a20
`public: __thiscall ProvIpAddressType::ProvIpAddressType(class ProvIpAddressType const &)` | 85 (0x55) | Exported Function | 0x100119d0 | 0x000119d0
`public: __thiscall ProvIpAddressType::ProvIpAddressType(unsigned long)` | 87 (0x57) | Exported Function | 0x10011a70 | 0x00011a70
`public: __thiscall ProvIpAddressType::ProvIpAddressType(unsigned short const *)` | 88 (0x58) | Exported Function | 0x10011ac0 | 0x00011ac0
`public: __thiscall ProvIpAddressType::ProvIpAddressType(void)` | 89 (0x59) | Exported Function | 0x10011b20 | 0x00011b20
`public: __thiscall ProvLexicon::ProvLexicon(void)` | 90 (0x5a) | Exported Function | 0x10011b70 | 0x00011b70
`public: __thiscall ProvLexicon::~ProvLexicon(void)` | 254 (0xfe) | Exported Function | 0x10013f60 | 0x00013f60
`public: __thiscall ProvMacAddressType::ProvMacAddressType(class ProvMacAddressType const &)` | 91 (0x5b) | Exported Function | 0x10011b90 | 0x00011b90
`public: __thiscall ProvMacAddressType::ProvMacAddressType(class ProvOctetString const &)` | 92 (0x5c) | Exported Function | 0x10011be0 | 0x00011be0
`public: __thiscall ProvMacAddressType::ProvMacAddressType(unsigned char const *)` | 93 (0x5d) | Exported Function | 0x10011c30 | 0x00011c30
`public: __thiscall ProvMacAddressType::ProvMacAddressType(unsigned short const *)` | 94 (0x5e) | Exported Function | 0x10011c80 | 0x00011c80
`public: __thiscall ProvMacAddressType::ProvMacAddressType(void)` | 95 (0x5f) | Exported Function | 0x10011ce0 | 0x00011ce0
`public: __thiscall ProvNegativeRangeType::ProvNegativeRangeType(class ProvNegativeRangeType const &)` | 96 (0x60) | Exported Function | 0x10011d30 | 0x00011d30
`public: __thiscall ProvNegativeRangeType::ProvNegativeRangeType(long,long)` | 97 (0x61) | Exported Function | 0x10011d60 | 0x00011d60
`public: __thiscall ProvNegativeRangeType::ProvNegativeRangeType(void)` | 98 (0x62) | Exported Function | 0x10011d90 | 0x00011d90
`public: __thiscall ProvNetworkAddressType::ProvNetworkAddressType(class ProvIpAddress const &)` | 100 (0x64) | Exported Function | 0x10011f00 | 0x00011f00
`public: __thiscall ProvOSIAddressType::ProvOSIAddressType(class ProvOSIAddressType const &)` | 108 (0x6c) | Exported Function | 0x10012140 | 0x00012140
`unsigned short * __stdcall UnicodeStringDuplicate(unsigned short const *)` | 950 (0x3b6) | Exported Function | 0x1001c970 | 0x0001c970


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
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
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/dda77140a10dc7f5c8ce543943adb77fe9e65d3c02fbd345e6e9cb221ca7edc5/detection/





MIT License. Copyright (c) 2020 Strontic.


