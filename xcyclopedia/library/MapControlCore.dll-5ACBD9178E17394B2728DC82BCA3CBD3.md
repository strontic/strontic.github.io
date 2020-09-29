---
title: MapControlCore.dll | Map Control Core
excerpt: What is MapControlCore.dll?
---

# MapControlCore.dll 

* File Path: `C:\Windows\system32\MapControlCore.dll`
* Description: Map Control Core

## Hashes

Type | Hash
-- | --
MD5 | `5ACBD9178E17394B2728DC82BCA3CBD3`
SHA1 | `F060D5DCDFDAA95B06B7A5712FF2374DD722FDE4`
SHA256 | `667D4218B3EF2597355D872C916A8D32DB0D5125A179AB607ABCABE4F70D201D`
SHA384 | `B6ED7D271977A06BE9657C775F50892E7946A9AAB1C3B49AA644E2B40D8C3C43A4E6A20CFAF8F69C504EDBBF4E60341D`
SHA512 | `FBA46135EADE213A63962B7582A029DED60D6C8D9F32138E3335573468D87AC48B2B3995267A4E404681889771647B9B5CCD1DF557EBAFDBCC2E86A52E2DC879`
SSDEEP | `3072:6oysPvjFsFSogFmdUxgaqqyYHTtLwzQA8JU+EiMsUkpeFcBnoM5eSmYQFO12:fys3jFsFSrcdigaqqywdwcimnmYQ`
IMP | `FE972F74DDAFDC1F7F02652B8EF06F7B`
PESHA1 | `AB4D62EADD55278CD968928613E0643300F2AF6D`
PE256 | `CA024C543E2DCD22102979C0214876773683F05E254489C9B6A94A84862DF114`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const core::GeoCoordinates::``vftable'` | 68 (0x44) | Exported Function | 0x000000018001f1d0 | 0x0001f1d0
`public: static bool __cdecl MapsSettings::IsChinaVariant(void)` | 200 (0xc8) | Exported Function | 0x00000001800161a0 | 0x000161a0
`public: static bool __cdecl MapsSettings::IsOldChinaRegKeySet(void)` | 206 (0xce) | Exported Function | 0x00000001800161b0 | 0x000161b0
`public: static bool __cdecl MapsSettings::IsWatermarkEnabled(void)` | 213 (0xd5) | Exported Function | 0x0000000180016220 | 0x00016220
`public: static class core::GeoCoordinates const * __ptr64 __cdecl MapsSettings::GetDefaultCenterFromTimezone(void)` | 110 (0x6e) | Exported Function | 0x0000000180015bf0 | 0x00015bf0
`public: static double __cdecl core::GeoCoordinates::GetMaxLatitude(void)` | 152 (0x98) | Exported Function | 0x0000000180014d20 | 0x00014d20
`public: static double __cdecl core::GeoCoordinates::GetMaxLongitude(void)` | 153 (0x99) | Exported Function | 0x0000000180014d30 | 0x00014d30
`public: static double __cdecl core::GeoCoordinates::GetMinLatitude(void)` | 154 (0x9a) | Exported Function | 0x0000000180014d40 | 0x00014d40
`public: static double __cdecl core::GeoCoordinates::GetMinLongitude(void)` | 155 (0x9b) | Exported Function | 0x0000000180014d50 | 0x00014d50
`public: static long __cdecl ApiAccessCheck::RestrictedAPIAccessCheck(void)` | 220 (0xdc) | Exported Function | 0x0000000180007da0 | 0x00007da0
`public: static long __cdecl core::GeoRect::CalculateGeoRect(class std::vector<class core::GeoCoordinates * __ptr64,class std::allocator<class core::GeoCoordinates * __ptr64> > & __ptr64,class core::GeoRect * __ptr64)` | 79 (0x4f) | Exported Function | 0x0000000180014790 | 0x00014790
`public: static long __cdecl core::Route::Deserialize(class std::basic_istream<char,struct std::char_traits<char> > & __ptr64,class core::Route * __ptr64)` | 87 (0x57) | Exported Function | 0x0000000180017b40 | 0x00017b40
`public: static long __cdecl core::RouteManeuver::FormatString(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,unsigned long,...)` | 88 (0x58) | Exported Function | 0x0000000180017db0 | 0x00017db0
`public: static long __cdecl core::RouteManeuver::GetStringResource(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)` | 169 (0xa9) | Exported Function | 0x000000018001a810 | 0x0001a810
`public: static long __cdecl MapsSettings::GetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 99 (0x63) | Exported Function | 0x00000001800031b0 | 0x000031b0
`public: static long __cdecl MapsSettings::GetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 100 (0x64) | Exported Function | 0x0000000180015a20 | 0x00015a20
`public: static long __cdecl MapsSettings::GetDataAttribution(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 109 (0x6d) | Exported Function | 0x0000000180015af0 | 0x00015af0
`public: static long __cdecl MapsSettings::GetKeyValidationStatus(int * __ptr64)` | 135 (0x87) | Exported Function | 0x0000000180015cf0 | 0x00015cf0
`public: static long __cdecl MapsSettings::GetLimitNetworkUsage(bool * __ptr64)` | 143 (0x8f) | Exported Function | 0x0000000180009e80 | 0x00009e80
`public: static long __cdecl MapsSettings::GetLocaleMapConfiguration(struct ILocaleMapConfiguration * __ptr64 * __ptr64)` | 144 (0x90) | Exported Function | 0x0000000180015d60 | 0x00015d60
`public: static long __cdecl MapsSettings::GetUserGeoRegion(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 181 (0xb5) | Exported Function | 0x0000000180015fa0 | 0x00015fa0
`public: static long __cdecl MapsSettings::GetUserGeoRegion(struct HSTRING__ * __ptr64 * __ptr64)` | 180 (0xb4) | Exported Function | 0x0000000180015e90 | 0x00015e90
`public: static long __cdecl MapsSettings::GetUserGeoRegionAsThreeLetterCode(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 182 (0xb6) | Exported Function | 0x0000000180003ad0 | 0x00003ad0
`public: static long __cdecl MapsSettings::GetUserPreferredUILanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 183 (0xb7) | Exported Function | 0x0000000180016040 | 0x00016040
`public: static long __cdecl MapsSettings::GetUserProfileLanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 184 (0xb8) | Exported Function | 0x0000000180016050 | 0x00016050
`public: static long __cdecl MapsSettings::GetUserProfileLanguages(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 186 (0xba) | Exported Function | 0x0000000180003ca0 | 0x00003ca0
`public: static long __cdecl MapsSettings::GetUserProfileLanguages(struct HSTRING__ * __ptr64 * __ptr64)` | 185 (0xb9) | Exported Function | 0x0000000180003b40 | 0x00003b40
`public: static long __cdecl MapsSettings::SetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const & __ptr64)` | 227 (0xe3) | Exported Function | 0x00000001800162a0 | 0x000162a0
`public: static bool __cdecl MapsSettings::GetEnableManeuverCondensing(void)` | 117 (0x75) | Exported Function | 0x0000000180015ce0 | 0x00015ce0
`public: static long __cdecl MapsSettings::SetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const & __ptr64)` | 228 (0xe4) | Exported Function | 0x0000000180016370 | 0x00016370
`public: long __cdecl RouterAdapterCore::GetViolatedOptions(int * __ptr64) __ptr64` | 188 (0xbc) | Exported Function | 0x0000000180017660 | 0x00017660
`public: long __cdecl RouterAdapterCore::GetProvider(enum engine::Provider * __ptr64) __ptr64` | 159 (0x9f) | Exported Function | 0x000000018000bdb0 | 0x0000bdb0
`public: double __cdecl core::GeoRect::GetLeft(void)const __ptr64` | 138 (0x8a) | Exported Function | 0x0000000180014cb0 | 0x00014cb0
`public: double __cdecl core::GeoRect::GetRight(void)const __ptr64` | 162 (0xa2) | Exported Function | 0x0000000180014d60 | 0x00014d60
`public: double __cdecl core::GeoRect::GetTop(void)const __ptr64` | 172 (0xac) | Exported Function | 0x0000000180014da0 | 0x00014da0
`public: enum core::CompassHeading __cdecl core::RouteManeuver::GetHeading(void)const __ptr64` | 128 (0x80) | Exported Function | 0x0000000180018f50 | 0x00018f50
`public: enum core::RouteManeuverType __cdecl core::RouteManeuver::GetManeuverType(void)const __ptr64` | 149 (0x95) | Exported Function | 0x000000018001a0e0 | 0x0001a0e0
`public: enum QueryStatus __cdecl QueryAdapterCore::GetStatus(void)const __ptr64` | 167 (0xa7) | Exported Function | 0x0000000180016e30 | 0x00016e30
`public: int __cdecl OperationAdapterCore::GetInstanceId(void)const __ptr64` | 130 (0x82) | Exported Function | 0x0000000180016d70 | 0x00016d70
`public: long __cdecl core::GeoRect::GetBottomRight(class core::GeoCoordinates * __ptr64)const __ptr64` | 102 (0x66) | Exported Function | 0x0000000180014ad0 | 0x00014ad0
`public: long __cdecl core::GeoRect::GetCenter(class core::GeoCoordinates * __ptr64)const __ptr64` | 105 (0x69) | Exported Function | 0x0000000180014b40 | 0x00014b40
`public: long __cdecl core::GeoRect::GetTopLeft(class core::GeoCoordinates * __ptr64)const __ptr64` | 173 (0xad) | Exported Function | 0x0000000180014de0 | 0x00014de0
`public: long __cdecl core::Route::Initialize(class std::shared_ptr<class msnma::IRoute>) __ptr64` | 191 (0xbf) | Exported Function | 0x000000018000dab0 | 0x0000dab0
`public: long __cdecl core::Route::Serialize(class std::basic_ostream<char,struct std::char_traits<char> > & __ptr64)const __ptr64` | 221 (0xdd) | Exported Function | 0x000000018001c370 | 0x0001c370
`public: long __cdecl core::RouteManeuver::GetCurrentRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 108 (0x6c) | Exported Function | 0x0000000180018310 | 0x00018310
`public: long __cdecl core::RouteManeuver::GetFreewayExitNumber(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 121 (0x79) | Exported Function | 0x0000000180018a30 | 0x00018a30
`public: long __cdecl core::RouteManeuver::GetInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 131 (0x83) | Exported Function | 0x0000000180019000 | 0x00019000
`public: long __cdecl core::RouteManeuver::GetManeuverNotice(int * __ptr64)const __ptr64` | 148 (0x94) | Exported Function | 0x0000000180019f20 | 0x00019f20
`public: long __cdecl core::RouteManeuver::GetStartCoordinates(class core::GeoCoordinates * __ptr64)const __ptr64` | 165 (0xa5) | Exported Function | 0x000000018001a580 | 0x0001a580
`public: long __cdecl core::RouteManeuver::GetTargetRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 171 (0xab) | Exported Function | 0x000000018001a9c0 | 0x0001a9c0
`public: long __cdecl OperationAdapterCore::GetErrorCode(void)const __ptr64` | 120 (0x78) | Exported Function | 0x0000000180016d60 | 0x00016d60
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const & __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,__int64,struct engine::RouteOptions * __ptr64) __ptr64` | 83 (0x53) | Exported Function | 0x000000018000bbc0 | 0x0000bbc0
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const & __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,struct engine::RouteOptions * __ptr64) __ptr64` | 82 (0x52) | Exported Function | 0x0000000180017300 | 0x00017300
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > && __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,__int64,struct engine::RouteOptions * __ptr64) __ptr64` | 81 (0x51) | Exported Function | 0x000000018000b7d0 | 0x0000b7d0
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > && __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,struct engine::RouteOptions * __ptr64) __ptr64` | 80 (0x50) | Exported Function | 0x000000018000b790 | 0x0000b790
`public: long __cdecl RouterAdapterCore::GetAlternateRoute(unsigned int,class core::Route * __ptr64) __ptr64` | 89 (0x59) | Exported Function | 0x0000000180017480 | 0x00017480
`public: long __cdecl RouterAdapterCore::GetAlternateRouteCount(unsigned int * __ptr64) __ptr64` | 90 (0x5a) | Exported Function | 0x0000000180017530 | 0x00017530
`public: long __cdecl RouterAdapterCore::GetAlternateRouteViolatedOption(unsigned int,int * __ptr64) __ptr64` | 91 (0x5b) | Exported Function | 0x0000000180017550 | 0x00017550
`public: long __cdecl RouterAdapterCore::GetConnectivityType(enum engine::ConnectivityType * __ptr64) __ptr64` | 106 (0x6a) | Exported Function | 0x000000018000bd90 | 0x0000bd90
`public: long __cdecl RouterAdapterCore::GetRoute(class core::Route * __ptr64) __ptr64` | 163 (0xa3) | Exported Function | 0x0000000180017600 | 0x00017600
`public: static long __cdecl MapsSettings::SetKeyValidationStatus(int)` | 234 (0xea) | Exported Function | 0x0000000180009f00 | 0x00009f00
`public: static long __cdecl MapsSettings::SetLimitNetworkUsage(bool)` | 236 (0xec) | Exported Function | 0x0000000180009f60 | 0x00009f60
`public: static long __cdecl SuspendResumeDispatcher::RegisterListener(class ISuspendResumeListener * __ptr64,bool * __ptr64)` | 218 (0xda) | Exported Function | 0x000000018001d5f0 | 0x0001d5f0
`public: virtual unsigned long __cdecl core::Route::GetDurationWithoutTrafficInSeconds(void)const __ptr64` | 115 (0x73) | Exported Function | 0x000000018000d190 | 0x0000d190
`public: virtual unsigned long __cdecl core::Route::GetGeometryCoordinatesCount(void)const __ptr64` | 125 (0x7d) | Exported Function | 0x0000000180018d90 | 0x00018d90
`public: virtual unsigned long __cdecl core::Route::GetLegCount(void)const __ptr64` | 140 (0x8c) | Exported Function | 0x0000000180016e30 | 0x00016e30
`public: virtual unsigned long __cdecl core::Route::GetLengthInMeters(void)const __ptr64` | 141 (0x8d) | Exported Function | 0x0000000180019a80 | 0x00019a80
`public: virtual unsigned long __cdecl core::RouteLeg::GetDurationInSeconds(void)const __ptr64` | 114 (0x72) | Exported Function | 0x0000000180018590 | 0x00018590
`public: virtual unsigned long __cdecl core::RouteLeg::GetDurationWithoutTrafficInSeconds(void)const __ptr64` | 116 (0x74) | Exported Function | 0x000000018000d280 | 0x0000d280
`public: virtual unsigned long __cdecl core::RouteLeg::GetGeometryCoordinatesCount(void)const __ptr64` | 126 (0x7e) | Exported Function | 0x0000000180018e80 | 0x00018e80
`public: virtual unsigned long __cdecl core::RouteLeg::GetLengthInMeters(void)const __ptr64` | 142 (0x8e) | Exported Function | 0x0000000180019b70 | 0x00019b70
`public: virtual unsigned long __cdecl core::RouteLeg::GetManeuverCount(void)const __ptr64` | 147 (0x93) | Exported Function | 0x0000000180019e80 | 0x00019e80
`public: virtual unsigned long __cdecl RouterAdapterCore::GetResultSqmId(void)const __ptr64` | 161 (0xa1) | Exported Function | 0x00000001800175f0 | 0x000175f0
`public: virtual void __cdecl core::GeoCoordinates::SetAltitude(double) __ptr64` | 222 (0xde) | Exported Function | 0x00000001800151b0 | 0x000151b0
`public: virtual void __cdecl core::GeoCoordinates::SetLatitude(double) __ptr64` | 235 (0xeb) | Exported Function | 0x00000001800151d0 | 0x000151d0
`public: virtual void __cdecl core::GeoCoordinates::SetLongitude(double) __ptr64` | 237 (0xed) | Exported Function | 0x00000001800151f0 | 0x000151f0
`public: virtual void __cdecl RouterAdapterCore::OnRouteDone(struct engine::RouteResult const & __ptr64) __ptr64` | 214 (0xd6) | Exported Function | 0x0000000180017770 | 0x00017770
`public: virtual void __cdecl RouterAdapterCore::OnRouteProgress(unsigned long) __ptr64` | 215 (0xd7) | Exported Function | 0x0000000180017820 | 0x00017820
`public: virtual void __cdecl UIThreadCore<struct IRouterUI>::Post(class TDispatchItem<struct IRouterUI> * __ptr64) __ptr64` | 216 (0xd8) | Exported Function | 0x0000000180017870 | 0x00017870
`public: void __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::SetBackingObject(class Microsoft::ngeo::GeoCoordinates const & __ptr64) __ptr64` | 225 (0xe1) | Exported Function | 0x00000001800096b0 | 0x000096b0
`public: void __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::SetBackingObject(class Microsoft::ngeo::GeoRect const & __ptr64) __ptr64` | 226 (0xe2) | Exported Function | 0x00000001800096d0 | 0x000096d0
`public: void __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::SetBackingObject(class std::shared_ptr<class msnma::IManeuver> const & __ptr64) __ptr64` | 223 (0xdf) | Exported Function | 0x000000018000df50 | 0x0000df50
`public: void __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::SetBackingObject(class std::shared_ptr<class msnma::IRoute> const & __ptr64) __ptr64` | 224 (0xe0) | Exported Function | 0x000000018000df50 | 0x0000df50
`public: void __cdecl core::DoublePoint::``default constructor closure'(void) __ptr64` | 78 (0x4e) | Exported Function | 0x0000000180014770 | 0x00014770
`public: void __cdecl core::GeoRect::CopyFrom(class core::GeoRect const & __ptr64) __ptr64` | 86 (0x56) | Exported Function | 0x0000000180014a40 | 0x00014a40
`public: void __cdecl RouterAdapterCore::Cancel(void) __ptr64` | 84 (0x54) | Exported Function | 0x0000000180017330 | 0x00017330
`public: void __cdecl UIThreadCore<struct IRouterUI>::ProcessDispatchQueue(struct IRouterUI * __ptr64) __ptr64` | 217 (0xd9) | Exported Function | 0x0000000180017890 | 0x00017890
`SetDebugThreadId` | 229 (0xe5) | Exported Function | 0x000000018001d860 | 0x0001d860
`SetRenderThreadId` | 240 (0xf0) | Exported Function | 0x000000018001d870 | 0x0001d870
`SetUIThreadChecksEnabled` | 242 (0xf2) | Exported Function | 0x000000018001d880 | 0x0001d880
`public: virtual unsigned long __cdecl core::Route::GetDurationInSeconds(void)const __ptr64` | 113 (0x71) | Exported Function | 0x00000001800184a0 | 0x000184a0
`public: virtual long __cdecl UIThreadCore<struct IRouterUI>::GetGenerationNumber(void)const __ptr64` | 122 (0x7a) | Exported Function | 0x0000000180016d70 | 0x00016d70
`public: virtual long __cdecl core::RouteLeg::GetManeuver(unsigned long,class core::RouteManeuver * __ptr64)const __ptr64` | 146 (0x92) | Exported Function | 0x0000000180019c90 | 0x00019c90
`public: virtual long __cdecl core::RouteLeg::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates * __ptr64)const __ptr64` | 124 (0x7c) | Exported Function | 0x0000000180018c60 | 0x00018c60
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultDrivingRouteOptions` | 249 (0xf9) | Exported Function | 0x00000001800364a4 | 0x000364a4
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultWalkingRouteOptions` | 250 (0xfa) | Exported Function | 0x00000001800364ac | 0x000364ac
`public: static void __cdecl MapsSettings::SetEnableManeuverCondensing(bool)` | 231 (0xe7) | Exported Function | 0x0000000180016490 | 0x00016490
`public: static void __cdecl MosThread::WaitOnClose(void)` | 246 (0xf6) | Exported Function | 0x0000000180002ad0 | 0x00002ad0
`public: static void __cdecl SuspendResumeDispatcher::UnregisterListener(class ISuspendResumeListener * __ptr64)` | 244 (0xf4) | Exported Function | 0x0000000180001dc0 | 0x00001dc0
`public: struct core::DoublePoint & __ptr64 __cdecl core::DoublePoint::operator=(struct core::DoublePoint && __ptr64) __ptr64` | 54 (0x36) | Exported Function | 0x0000000180009630 | 0x00009630
`public: struct core::DoublePoint & __ptr64 __cdecl core::DoublePoint::operator=(struct core::DoublePoint const & __ptr64) __ptr64` | 55 (0x37) | Exported Function | 0x0000000180014280 | 0x00014280
`public: unsigned long __cdecl core::RouteManeuver::GetDistanceInMetersFromPreviousManeuver(void)const __ptr64` | 111 (0x6f) | Exported Function | 0x0000000180018440 | 0x00018440
`public: unsigned long __cdecl core::RouteManeuver::GetDistanceInMetersToNextManeuver(void)const __ptr64` | 112 (0x70) | Exported Function | 0x0000000180018470 | 0x00018470
`public: unsigned long __cdecl core::RouteManeuver::GetManeuverWarningCount(void)const __ptr64` | 150 (0x96) | Exported Function | 0x000000018000d670 | 0x0000d670
`public: unsigned long __cdecl core::RouteManeuver::GetTrafficCircleExitNumber(void)const __ptr64` | 174 (0xae) | Exported Function | 0x000000018001aad0 | 0x0001aad0
`public: unsigned long __cdecl OperationAdapterCore::GetProgress(void)const __ptr64` | 158 (0x9e) | Exported Function | 0x0000000180016d80 | 0x00016d80
`public: virtual __cdecl core::GeoCoordinates::~GeoCoordinates(void) __ptr64` | 38 (0x26) | Exported Function | 0x0000000180003490 | 0x00003490
`public: double __cdecl core::GeoRect::GetBottom(void)const __ptr64` | 101 (0x65) | Exported Function | 0x0000000180014a90 | 0x00014a90
`public: virtual __cdecl core::GeoRect::~GeoRect(void) __ptr64` | 39 (0x27) | Exported Function | 0x0000000180014230 | 0x00014230
`public: virtual __cdecl core::RouteLeg::~RouteLeg(void) __ptr64` | 43 (0x2b) | Exported Function | 0x0000000180017a80 | 0x00017a80
`public: virtual __cdecl core::RouteManeuver::~RouteManeuver(void) __ptr64` | 44 (0x2c) | Exported Function | 0x0000000180017ad0 | 0x00017ad0
`public: virtual bool __cdecl core::GeoCoordinates::IsValid(void)const __ptr64` | 209 (0xd1) | Exported Function | 0x0000000180015160 | 0x00015160
`public: virtual bool __cdecl core::GeoRect::IsValid(void)const __ptr64` | 210 (0xd2) | Exported Function | 0x0000000180015190 | 0x00015190
`public: virtual double __cdecl core::GeoCoordinates::GetAltitude(void)const __ptr64` | 92 (0x5c) | Exported Function | 0x0000000180014a60 | 0x00014a60
`public: virtual double __cdecl core::GeoCoordinates::GetLatitude(void)const __ptr64` | 136 (0x88) | Exported Function | 0x0000000180014c80 | 0x00014c80
`public: virtual double __cdecl core::GeoCoordinates::GetLongitude(void)const __ptr64` | 145 (0x91) | Exported Function | 0x0000000180014cf0 | 0x00014cf0
`public: virtual enum msnma::IRoute::TrafficCongestionType __cdecl core::Route::GetTrafficCongestion(void)const __ptr64` | 176 (0xb0) | Exported Function | 0x000000018000d870 | 0x0000d870
`public: virtual enum msnma::IRoute::TrafficCongestionType __cdecl core::RouteLeg::GetTrafficCongestion(void)const __ptr64` | 177 (0xb1) | Exported Function | 0x000000018000d990 | 0x0000d990
`public: virtual long __cdecl core::Route::GetBoundingBox(class core::GeoRect * __ptr64)const __ptr64` | 103 (0x67) | Exported Function | 0x0000000180017f60 | 0x00017f60
`public: virtual long __cdecl core::Route::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates * __ptr64)const __ptr64` | 123 (0x7b) | Exported Function | 0x0000000180018ab0 | 0x00018ab0
`public: virtual long __cdecl core::Route::GetLeg(unsigned long,class core::RouteLeg * __ptr64)const __ptr64` | 139 (0x8b) | Exported Function | 0x0000000180019910 | 0x00019910
`public: virtual long __cdecl core::RouteLeg::GetBoundingBox(class core::GeoRect * __ptr64)const __ptr64` | 104 (0x68) | Exported Function | 0x00000001800180c0 | 0x000180c0
`public: virtual __cdecl core::Route::~Route(void) __ptr64` | 42 (0x2a) | Exported Function | 0x0000000180017a60 | 0x00017a60
`public: class std::shared_ptr<class msnma::IRoute> __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::GetBackingObject(void)const __ptr64` | 94 (0x5e) | Exported Function | 0x000000018000d160 | 0x0000d160
`public: class std::shared_ptr<class msnma::IManeuver> __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::GetBackingObject(void)const __ptr64` | 93 (0x5d) | Exported Function | 0x000000018000d160 | 0x0000d160
`public: class QueryAdapterCore & __ptr64 __cdecl QueryAdapterCore::operator=(class QueryAdapterCore const & __ptr64) __ptr64` | 59 (0x3b) | Exported Function | 0x0000000180016c30 | 0x00016c30
`private: long __cdecl core::RouteManeuver::GetTakeFerryInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 170 (0xaa) | Exported Function | 0x000000018001a9a0 | 0x0001a9a0
`private: long __cdecl core::RouteManeuver::GetTrafficCircleInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 175 (0xaf) | Exported Function | 0x000000018001ac10 | 0x0001ac10
`private: long __cdecl core::RouteManeuver::GetTurnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 178 (0xb2) | Exported Function | 0x000000018001ace0 | 0x0001ace0
`private: long __cdecl core::RouteManeuver::GetUndefinedInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 179 (0xb3) | Exported Function | 0x000000018001b020 | 0x0001b020
`private: long __cdecl core::RouteManeuver::GetUturnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 187 (0xbb) | Exported Function | 0x000000018001b0a0 | 0x0001b0a0
`private: long __cdecl core::RouteManeuver::Initialize(class std::vector<class std::shared_ptr<class msnma::IManeuver>,class std::allocator<class std::shared_ptr<class msnma::IManeuver> > > const & __ptr64,int) __ptr64` | 193 (0xc1) | Exported Function | 0x000000018000dde0 | 0x0000dde0
`private: long __cdecl core::RouteManeuver::InitializeInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 195 (0xc3) | Exported Function | 0x000000018001b290 | 0x0001b290
`private: static enum core::CompassHeading __cdecl core::RouteManeuver::GetSnappedCompassHeading(unsigned long)` | 164 (0xa4) | Exported Function | 0x000000018001a490 | 0x0001a490
`protected: __cdecl OperationAdapterCore::OperationAdapterCore(void) __ptr64` | 22 (0x16) | Exported Function | 0x0000000180016b60 | 0x00016b60
`protected: __cdecl QueryAdapterCore::QueryAdapterCore(void) __ptr64` | 24 (0x18) | Exported Function | 0x0000000180016e00 | 0x00016e00
`protected: __cdecl RouterAdapterCore::RouterAdapterCore(void) __ptr64` | 32 (0x20) | Exported Function | 0x0000000180016ef0 | 0x00016ef0
`protected: __cdecl UIThreadCore<struct IRouterUI>::UIThreadCore<struct IRouterUI>(void) __ptr64` | 13 (0xd) | Exported Function | 0x0000000180016ec0 | 0x00016ec0
`protected: bool __cdecl UIThreadCore<struct IRouterUI>::IsDispatchEnabled(void) __ptr64` | 204 (0xcc) | Exported Function | 0x0000000180017760 | 0x00017760
`protected: class Microsoft::ngeo::GeoCoordinates & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void) __ptr64` | 95 (0x5f) | Exported Function | 0x00000001800096a0 | 0x000096a0
`protected: class Microsoft::ngeo::GeoRect & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void) __ptr64` | 97 (0x61) | Exported Function | 0x00000001800096a0 | 0x000096a0
`protected: long __cdecl RouterAdapterCore::_CoreInitialize(int,class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >) __ptr64` | 247 (0xf7) | Exported Function | 0x000000018000c140 | 0x0000c140
`protected: long __cdecl UIThreadCore<struct IRouterUI>::IncrementGeneration(void) __ptr64` | 189 (0xbd) | Exported Function | 0x00000001800043a0 | 0x000043a0
`protected: long __cdecl UIThreadCore<struct IRouterUI>::Initialize(class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >) __ptr64` | 190 (0xbe) | Exported Function | 0x0000000180017680 | 0x00017680
`protected: virtual __cdecl OperationAdapterCore::~OperationAdapterCore(void) __ptr64` | 40 (0x28) | Exported Function | 0x0000000180016bf0 | 0x00016bf0
`protected: virtual __cdecl QueryAdapterCore::~QueryAdapterCore(void) __ptr64` | 41 (0x29) | Exported Function | 0x0000000180016bf0 | 0x00016bf0
`protected: virtual __cdecl RouterAdapterCore::~RouterAdapterCore(void) __ptr64` | 45 (0x2d) | Exported Function | 0x0000000180017030 | 0x00017030
`protected: virtual __cdecl UIThreadCore<struct IRouterUI>::~UIThreadCore<struct IRouterUI>(void) __ptr64` | 37 (0x25) | Exported Function | 0x0000000180016fa0 | 0x00016fa0
`protected: virtual unsigned long __cdecl OperationAdapterCore::GetResultSqmId(void)const __ptr64` | 160 (0xa0) | Exported Function | 0x0000000180004390 | 0x00004390
`protected: virtual void __cdecl OperationAdapterCore::SetProgress(unsigned long) __ptr64` | 238 (0xee) | Exported Function | 0x0000000180016dd0 | 0x00016dd0
`protected: virtual void __cdecl QueryAdapterCore::SetProgress(unsigned long) __ptr64` | 239 (0xef) | Exported Function | 0x0000000180016e40 | 0x00016e40
`protected: void __cdecl OperationAdapterCore::ResetProgress(void) __ptr64` | 219 (0xdb) | Exported Function | 0x0000000180016d90 | 0x00016d90
`protected: void __cdecl OperationAdapterCore::SetErrorCode(long) __ptr64` | 232 (0xe8) | Exported Function | 0x0000000180016db0 | 0x00016db0
`private: long __cdecl core::RouteManeuver::GetStopoverInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 168 (0xa8) | Exported Function | 0x000000018001a800 | 0x0001a800
`private: long __cdecl core::RouteManeuver::GetStartInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 166 (0xa6) | Exported Function | 0x000000018001a6d0 | 0x0001a6d0
`private: long __cdecl core::RouteManeuver::GetLeaveFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 137 (0x89) | Exported Function | 0x0000000180019300 | 0x00019300
`private: long __cdecl core::RouteManeuver::GetInstructionWithTargetAndReplacement(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 134 (0x86) | Exported Function | 0x0000000180019220 | 0x00019220
`const core::GeoRect::``vftable'` | 69 (0x45) | Exported Function | 0x000000018001f1c0 | 0x0001f1c0
`const core::Route::``vftable'` | 72 (0x48) | Exported Function | 0x000000018001f118 | 0x0001f118
`const core::RouteLeg::``vftable'` | 73 (0x49) | Exported Function | 0x000000018001f168 | 0x0001f168
`const core::RouteManeuver::``vftable'` | 74 (0x4a) | Exported Function | 0x000000018001f1b8 | 0x0001f1b8
`const OperationAdapterCore::``vftable'` | 70 (0x46) | Exported Function | 0x000000018001f3a8 | 0x0001f3a8
`const QueryAdapterCore::``vftable'` | 71 (0x47) | Exported Function | 0x000000018001f378 | 0x0001f378
`const RouterAdapterCore::``vftable'{for ``IRouterUI'}` | 76 (0x4c) | Exported Function | 0x000000018001f448 | 0x0001f448
`const RouterAdapterCore::``vftable'{for ``QueryAdapterCore'}` | 77 (0x4d) | Exported Function | 0x000000018001f458 | 0x0001f458
`const RouterAdapterCore::``vftable'{for ``UIThreadCore<struct IRouterUI>'}` | 75 (0x4b) | Exported Function | 0x000000018001f430 | 0x0001f430
`const UIThreadCore<struct IRouterUI>::``vftable'` | 67 (0x43) | Exported Function | 0x000000018001f3f0 | 0x0001f3f0
`GetMosThreadInstance` | 156 (0x9c) | Exported Function | 0x0000000180003880 | 0x00003880
`GetMosThreadInstanceWithoutWait` | 157 (0x9d) | Exported Function | 0x0000000180016a00 | 0x00016a00
`IsDebugThread` | 201 (0xc9) | Exported Function | 0x000000018001d7b0 | 0x0001d7b0
`protected: void __cdecl OperationAdapterCore::SetInstanceId(int) __ptr64` | 233 (0xe9) | Exported Function | 0x0000000180016dc0 | 0x00016dc0
`IsMosThread` | 205 (0xcd) | Exported Function | 0x00000001800041d0 | 0x000041d0
`IsUIThread` | 208 (0xd0) | Exported Function | 0x000000018001d810 | 0x0001d810
`private: bool __cdecl core::RouteLeg::IsValid(void)const __ptr64` | 212 (0xd4) | Exported Function | 0x000000018001c280 | 0x0001c280
`private: long __cdecl core::Route::InitializeLegs(void) __ptr64` | 196 (0xc4) | Exported Function | 0x000000018001b8d0 | 0x0001b8d0
`private: long __cdecl core::RouteLeg::Initialize(class std::shared_ptr<class msnma::IRoute>,unsigned long) __ptr64` | 192 (0xc0) | Exported Function | 0x000000018000dc00 | 0x0000dc00
`private: long __cdecl core::RouteLeg::InitializeGeometryCoordinates(void) __ptr64` | 194 (0xc2) | Exported Function | 0x000000018001b0c0 | 0x0001b0c0
`private: long __cdecl core::RouteLeg::InitializeManeuverCondensingContexts(bool) __ptr64` | 197 (0xc5) | Exported Function | 0x000000018001ba50 | 0x0001ba50
`private: long __cdecl core::RouteLeg::InitializeManeuvers(void) __ptr64` | 198 (0xc6) | Exported Function | 0x000000018001bda0 | 0x0001bda0
`private: long __cdecl core::RouteManeuver::GetContinueFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 107 (0x6b) | Exported Function | 0x00000001800181c0 | 0x000181c0
`private: long __cdecl core::RouteManeuver::GetEndInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 118 (0x76) | Exported Function | 0x00000001800186b0 | 0x000186b0
`private: long __cdecl core::RouteManeuver::GetEnterFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 119 (0x77) | Exported Function | 0x00000001800186c0 | 0x000186c0
`private: long __cdecl core::RouteManeuver::GetGoStraightInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 127 (0x7f) | Exported Function | 0x0000000180018f30 | 0x00018f30
`private: long __cdecl core::RouteManeuver::GetInstructionTextFromBacking(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 132 (0x84) | Exported Function | 0x0000000180019080 | 0x00019080
`private: long __cdecl core::RouteManeuver::GetInstructionWithTarget(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 133 (0x85) | Exported Function | 0x00000001800191b0 | 0x000191b0
`IsRenderThread` | 207 (0xcf) | Exported Function | 0x000000018001d7e0 | 0x0001d7e0
`SetUIThreadId` | 243 (0xf3) | Exported Function | 0x000000018001d890 | 0x0001d890
`protected: void __cdecl QueryAdapterCore::SetStatus(enum QueryStatus) __ptr64` | 241 (0xf1) | Exported Function | 0x0000000180016e70 | 0x00016e70
`protected: void __cdecl UIThreadCore<struct IRouterUI>::SetDispatchEnabled(bool) __ptr64` | 230 (0xe6) | Exported Function | 0x00000001800178a0 | 0x000178a0
`public: bool __cdecl core::DoublePoint::operator!=(struct core::DoublePoint const & __ptr64)const __ptr64` | 65 (0x41) | Exported Function | 0x0000000180014480 | 0x00014480
`public: bool __cdecl core::DoublePoint::operator==(struct core::DoublePoint const & __ptr64)const __ptr64` | 63 (0x3f) | Exported Function | 0x0000000180014420 | 0x00014420
`public: bool __cdecl core::GeoCoordinates::operator!=(class core::GeoCoordinates const & __ptr64)const __ptr64` | 66 (0x42) | Exported Function | 0x00000001800144a0 | 0x000144a0
`public: bool __cdecl core::GeoCoordinates::operator==(class core::GeoCoordinates const & __ptr64)const __ptr64` | 64 (0x40) | Exported Function | 0x0000000180014450 | 0x00014450
`public: bool __cdecl core::GeoRect::Contains(class core::GeoCoordinates const * __ptr64) __ptr64` | 85 (0x55) | Exported Function | 0x0000000180014a00 | 0x00014a00
`public: bool __cdecl core::GeoRect::Intersects(class core::GeoRect const * __ptr64) __ptr64` | 199 (0xc7) | Exported Function | 0x0000000180014e50 | 0x00014e50
`public: bool __cdecl core::GeoRect::IsDegenerate(void)const __ptr64` | 202 (0xca) | Exported Function | 0x00000001800150d0 | 0x000150d0
`public: bool __cdecl core::Route::IsDeserialized(void)const __ptr64` | 203 (0xcb) | Exported Function | 0x000000018001bf70 | 0x0001bf70
`public: bool __cdecl core::Route::IsValid(void)const __ptr64` | 211 (0xd3) | Exported Function | 0x000000018001c120 | 0x0001c120
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> && __ptr64) __ptr64` | 50 (0x32) | Exported Function | 0x00000001800094f0 | 0x000094f0
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const & __ptr64) __ptr64` | 51 (0x33) | Exported Function | 0x0000000180009520 | 0x00009520
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> && __ptr64) __ptr64` | 52 (0x34) | Exported Function | 0x0000000180009550 | 0x00009550
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> const & __ptr64) __ptr64` | 53 (0x35) | Exported Function | 0x0000000180009580 | 0x00009580
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > && __ptr64) __ptr64` | 46 (0x2e) | Exported Function | 0x0000000180009470 | 0x00009470
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const & __ptr64) __ptr64` | 47 (0x2f) | Exported Function | 0x00000001800094b0 | 0x000094b0
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > && __ptr64) __ptr64` | 48 (0x30) | Exported Function | 0x00000001800094d0 | 0x000094d0
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const & __ptr64) __ptr64` | 49 (0x31) | Exported Function | 0x00000001800094b0 | 0x000094b0
`public: class core::GeoCoordinates & __ptr64 __cdecl core::GeoCoordinates::operator=(class core::GeoCoordinates const & __ptr64) __ptr64` | 56 (0x38) | Exported Function | 0x00000001800142a0 | 0x000142a0
`public: class core::GeoRect & __ptr64 __cdecl core::GeoRect::operator=(class core::GeoRect const & __ptr64) __ptr64` | 57 (0x39) | Exported Function | 0x00000001800142d0 | 0x000142d0
`public: class core::GeoRect __cdecl core::GeoRect::GetInflatedGeoRect(void)const __ptr64` | 129 (0x81) | Exported Function | 0x0000000180014bd0 | 0x00014bd0
`public: class core::Route & __ptr64 __cdecl core::Route::operator=(class core::Route const & __ptr64) __ptr64` | 60 (0x3c) | Exported Function | 0x0000000180014300 | 0x00014300
`public: class core::RouteLeg & __ptr64 __cdecl core::RouteLeg::operator=(class core::RouteLeg const & __ptr64) __ptr64` | 61 (0x3d) | Exported Function | 0x0000000180014340 | 0x00014340
`public: class core::RouteManeuver & __ptr64 __cdecl core::RouteManeuver::operator=(class core::RouteManeuver const & __ptr64) __ptr64` | 62 (0x3e) | Exported Function | 0x00000001800143b0 | 0x000143b0
`public: class Microsoft::ngeo::GeoCoordinates const & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)const __ptr64` | 96 (0x60) | Exported Function | 0x00000001800096a0 | 0x000096a0
`public: class Microsoft::ngeo::GeoRect const & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)const __ptr64` | 98 (0x62) | Exported Function | 0x00000001800096a0 | 0x000096a0
`public: class msnma::IItineraryWarning const & __ptr64 __cdecl core::RouteManeuver::GetManeuverWarnings(unsigned long)const __ptr64` | 151 (0x97) | Exported Function | 0x000000018000d700 | 0x0000d700
`public: class OperationAdapterCore & __ptr64 __cdecl OperationAdapterCore::operator=(class OperationAdapterCore const & __ptr64) __ptr64` | 58 (0x3a) | Exported Function | 0x0000000180016c10 | 0x00016c10
`public: __cdecl QueryAdapterCore::QueryAdapterCore(class QueryAdapterCore const & __ptr64) __ptr64` | 25 (0x19) | Exported Function | 0x0000000180016bb0 | 0x00016bb0
`public: __cdecl OperationAdapterCore::OperationAdapterCore(class OperationAdapterCore const & __ptr64) __ptr64` | 23 (0x17) | Exported Function | 0x0000000180016b80 | 0x00016b80
`public: __cdecl core::RouteManeuver::RouteManeuver(void) __ptr64` | 31 (0x1f) | Exported Function | 0x0000000180017a10 | 0x00017a10
`public: __cdecl core::RouteManeuver::RouteManeuver(class core::RouteManeuver const & __ptr64) __ptr64` | 30 (0x1e) | Exported Function | 0x0000000180014190 | 0x00014190
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> && __ptr64) __ptr64` | 7 (0x7) | Exported Function | 0x0000000180009220 | 0x00009220
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const & __ptr64) __ptr64` | 8 (0x8) | Exported Function | 0x0000000180009250 | 0x00009250
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(void) __ptr64` | 9 (0x9) | Exported Function | 0x0000000180009280 | 0x00009280
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::~BackedType<class Microsoft::ngeo::GeoCoordinates>(void) __ptr64` | 35 (0x23) | Exported Function | 0x00000001800093f0 | 0x000093f0
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> && __ptr64) __ptr64` | 10 (0xa) | Exported Function | 0x00000001800092b0 | 0x000092b0
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> const & __ptr64) __ptr64` | 11 (0xb) | Exported Function | 0x00000001800092e0 | 0x000092e0
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(void) __ptr64` | 12 (0xc) | Exported Function | 0x0000000180009310 | 0x00009310
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::~BackedType<class Microsoft::ngeo::GeoRect>(void) __ptr64` | 36 (0x24) | Exported Function | 0x0000000180009410 | 0x00009410
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > && __ptr64) __ptr64` | 1 (0x1) | Exported Function | 0x00000001800091b0 | 0x000091b0
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const & __ptr64) __ptr64` | 2 (0x2) | Exported Function | 0x00000001800091e0 | 0x000091e0
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(void) __ptr64` | 3 (0x3) | Exported Function | 0x0000000180009200 | 0x00009200
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::~BackedType<class std::shared_ptr<class msnma::IManeuver> >(void) __ptr64` | 33 (0x21) | Exported Function | 0x00000001800093d0 | 0x000093d0
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > && __ptr64) __ptr64` | 4 (0x4) | Exported Function | 0x00000001800091b0 | 0x000091b0
`protected: void __cdecl RouterAdapterCore::_CoreUninitialize(void) __ptr64` | 248 (0xf8) | Exported Function | 0x00000001800178b0 | 0x000178b0
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const & __ptr64) __ptr64` | 5 (0x5) | Exported Function | 0x00000001800091e0 | 0x000091e0
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::~BackedType<class std::shared_ptr<class msnma::IRoute> >(void) __ptr64` | 34 (0x22) | Exported Function | 0x00000001800093d0 | 0x000093d0
`public: __cdecl core::DoublePoint::DoublePoint(double,double) __ptr64` | 14 (0xe) | Exported Function | 0x0000000180002fd0 | 0x00002fd0
`public: __cdecl core::GeoCoordinates::GeoCoordinates(class core::GeoCoordinates const & __ptr64) __ptr64` | 15 (0xf) | Exported Function | 0x0000000180013dd0 | 0x00013dd0
`public: __cdecl core::GeoCoordinates::GeoCoordinates(double,double) __ptr64` | 16 (0x10) | Exported Function | 0x0000000180002f30 | 0x00002f30
`public: __cdecl core::GeoCoordinates::GeoCoordinates(void) __ptr64` | 17 (0x11) | Exported Function | 0x0000000180013e00 | 0x00013e00
`public: __cdecl core::GeoRect::GeoRect(class core::GeoCoordinates const * __ptr64,class core::GeoCoordinates const * __ptr64) __ptr64` | 20 (0x14) | Exported Function | 0x0000000180013f30 | 0x00013f30
`public: __cdecl core::GeoRect::GeoRect(class core::GeoRect const & __ptr64) __ptr64` | 18 (0x12) | Exported Function | 0x0000000180013e30 | 0x00013e30
`public: __cdecl core::GeoRect::GeoRect(double,double,double,double) __ptr64` | 19 (0x13) | Exported Function | 0x0000000180013e60 | 0x00013e60
`public: __cdecl core::GeoRect::GeoRect(void) __ptr64` | 21 (0x15) | Exported Function | 0x0000000180013ff0 | 0x00013ff0
`public: __cdecl core::Route::Route(class core::Route const & __ptr64) __ptr64` | 26 (0x1a) | Exported Function | 0x0000000180014090 | 0x00014090
`public: __cdecl core::Route::Route(void) __ptr64` | 27 (0x1b) | Exported Function | 0x0000000180017950 | 0x00017950
`public: __cdecl core::RouteLeg::RouteLeg(class core::RouteLeg const & __ptr64) __ptr64` | 28 (0x1c) | Exported Function | 0x00000001800140e0 | 0x000140e0
`public: __cdecl core::RouteLeg::RouteLeg(void) __ptr64` | 29 (0x1d) | Exported Function | 0x0000000180017980 | 0x00017980
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(void) __ptr64` | 6 (0x6) | Exported Function | 0x0000000180009200 | 0x00009200
`WaitForMosThreadToClose` | 245 (0xf5) | Exported Function | 0x0000000180002ac0 | 0x00002ac0


## Signature

* Status: Signature verified.
* Serial: `3300000266BD1580EFA75CD6D3000000000266`
* Thumbprint: `A4341B9FD50FB9964283220A36A1EF6F6FAA7840`
* Issuer: CN=Microsoft Windows Production PCA 2011, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Windows, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MapControlCore.dll
* Product Name: Microsoft Windows Operating System
* Company Name: Microsoft Corporation
* File Version: 10.0.19041.84 (WinBuild.160101.0800)
* Product Version: 10.0.19041.84
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 64-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/667d4218b3ef2597355d872c916a8d32db0d5125a179ab607abcabe4f70d201d/detection/





MIT License. Copyright (c) 2020 Strontic.


