---
title: MapControlCore.dll | Map Control Core
excerpt: What is MapControlCore.dll?
---

# MapControlCore.dll 

* File Path: `C:\Windows\SysWOW64\MapControlCore.dll`
* Description: Map Control Core

## Hashes

Type | Hash
-- | --
MD5 | `C4CE632BD367E478B40D2890C93824AC`
SHA1 | `AAC780961E8F761EE0C980206789CE42CC250897`
SHA256 | `C9B8C857ACC9BE5225C1324CBF49535D0AD2D15D2B1BEEC9F6FED9A7E7759955`
SHA384 | `C3B672FD6EB50611BDADC73378C6D8E9CF2517882C3D39818CC7B503FD69CCFEB69187D8CE27C8D7C8DF9CED869FE0F4`
SHA512 | `B0AEF0034398BF4DC8BD6D5608AF098F0E54AD19F21BE7CF0469ED2AB0D5FAD157FB59A408D5D438E4E96EF1634BBC73230EC852F6BE24493F64775E4C2C5ADA`
SSDEEP | `3072:Zxgd2IQ4ZnUetxWEAO2OEZcgL02r/jKxnoUNlUpNT1Ed0PC7QocdXPMg5eSDLts:Zxgd2IP0EKpxjYoZpV1PXPjL`
IMP | `740BB7F3BF6F83EBC2FD0A0C1EE8C1FA`
PESHA1 | `BE03FF51EDCDB00617E4F0016290981569CD5229`
PE256 | `00AC3A2119AD49E8E2B3B38EA215EFDD33888D38FC4107C4B2413EF0B46045F7`

## DLL Exports:

Function Name | Ordinal | Type | Address | Relative Address
-- | -- | -- | -- | --
`const core::GeoCoordinates::``vftable'` | 68 (0x44) | Exported Function | 0x100010e8 | 0x000010e8
`public: static bool __stdcall MapsSettings::IsChinaVariant(void)` | 200 (0xc8) | Exported Function | 0x100181f0 | 0x000181f0
`public: static bool __stdcall MapsSettings::IsOldChinaRegKeySet(void)` | 206 (0xce) | Exported Function | 0x10018200 | 0x00018200
`public: static bool __stdcall MapsSettings::IsWatermarkEnabled(void)` | 213 (0xd5) | Exported Function | 0x10018210 | 0x00018210
`public: static class core::GeoCoordinates const * __stdcall MapsSettings::GetDefaultCenterFromTimezone(void)` | 110 (0x6e) | Exported Function | 0x10017ca0 | 0x00017ca0
`public: static double __stdcall core::GeoCoordinates::GetMaxLatitude(void)` | 152 (0x98) | Exported Function | 0x10016de0 | 0x00016de0
`public: static double __stdcall core::GeoCoordinates::GetMaxLongitude(void)` | 153 (0x99) | Exported Function | 0x10016df0 | 0x00016df0
`public: static double __stdcall core::GeoCoordinates::GetMinLatitude(void)` | 154 (0x9a) | Exported Function | 0x10016e00 | 0x00016e00
`public: static double __stdcall core::GeoCoordinates::GetMinLongitude(void)` | 155 (0x9b) | Exported Function | 0x10016e10 | 0x00016e10
`public: static long __cdecl core::RouteManeuver::FormatString(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,unsigned long,...)` | 88 (0x58) | Exported Function | 0x1001af30 | 0x0001af30
`public: static long __stdcall ApiAccessCheck::RestrictedAPIAccessCheck(void)` | 220 (0xdc) | Exported Function | 0x1000c5a0 | 0x0000c5a0
`public: static long __stdcall core::GeoRect::CalculateGeoRect(class std::vector<class core::GeoCoordinates *,class std::allocator<class core::GeoCoordinates *> > &,class core::GeoRect *)` | 79 (0x4f) | Exported Function | 0x100167f0 | 0x000167f0
`public: static long __stdcall core::Route::Deserialize(class std::basic_istream<char,struct std::char_traits<char> > &,class core::Route *)` | 87 (0x57) | Exported Function | 0x1001ad90 | 0x0001ad90
`public: static long __stdcall core::RouteManeuver::GetStringResource(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)` | 169 (0xa9) | Exported Function | 0x1001cc00 | 0x0001cc00
`public: static long __stdcall MapsSettings::GetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 99 (0x63) | Exported Function | 0x10017ac0 | 0x00017ac0
`public: static long __stdcall MapsSettings::GetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 100 (0x64) | Exported Function | 0x10017b60 | 0x00017b60
`public: static long __stdcall MapsSettings::GetDataAttribution(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 109 (0x6d) | Exported Function | 0x10017bf0 | 0x00017bf0
`public: static long __stdcall MapsSettings::GetKeyValidationStatus(int *)` | 135 (0x87) | Exported Function | 0x10017d60 | 0x00017d60
`public: static long __stdcall MapsSettings::GetLimitNetworkUsage(bool *)` | 143 (0x8f) | Exported Function | 0x1000dd60 | 0x0000dd60
`public: static long __stdcall MapsSettings::GetLocaleMapConfiguration(struct ILocaleMapConfiguration * *)` | 144 (0x90) | Exported Function | 0x10017dc0 | 0x00017dc0
`public: static long __stdcall MapsSettings::GetUserGeoRegion(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 181 (0xb5) | Exported Function | 0x10017f40 | 0x00017f40
`public: static long __stdcall MapsSettings::GetUserGeoRegion(struct HSTRING__ * *)` | 180 (0xb4) | Exported Function | 0x10017e90 | 0x00017e90
`public: static long __stdcall MapsSettings::GetUserGeoRegionAsThreeLetterCode(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 182 (0xb6) | Exported Function | 0x10017fb0 | 0x00017fb0
`public: static long __stdcall MapsSettings::GetUserPreferredUILanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 183 (0xb7) | Exported Function | 0x10017fd0 | 0x00017fd0
`public: static long __stdcall MapsSettings::GetUserProfileLanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 184 (0xb8) | Exported Function | 0x10017ff0 | 0x00017ff0
`public: static long __stdcall MapsSettings::GetUserProfileLanguages(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 186 (0xba) | Exported Function | 0x10018110 | 0x00018110
`public: static long __stdcall MapsSettings::GetUserProfileLanguages(struct HSTRING__ * *)` | 185 (0xb9) | Exported Function | 0x100180d0 | 0x000180d0
`public: static long __stdcall MapsSettings::SetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const &)` | 227 (0xe3) | Exported Function | 0x10018260 | 0x00018260
`public: static bool __stdcall MapsSettings::GetEnableManeuverCondensing(void)` | 117 (0x75) | Exported Function | 0x10017d50 | 0x00017d50
`public: static long __stdcall MapsSettings::SetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const &)` | 228 (0xe4) | Exported Function | 0x10018300 | 0x00018300
`public: long __thiscall RouterAdapterCore::GetViolatedOptions(int *)` | 188 (0xbc) | Exported Function | 0x1001a900 | 0x0001a900
`public: long __thiscall RouterAdapterCore::GetProvider(enum engine::Provider *)` | 159 (0x9f) | Exported Function | 0x1001a880 | 0x0001a880
`public: double __thiscall core::GeoRect::GetLeft(void)const ` | 138 (0x8a) | Exported Function | 0x10016d70 | 0x00016d70
`public: double __thiscall core::GeoRect::GetRight(void)const ` | 162 (0xa2) | Exported Function | 0x10016e20 | 0x00016e20
`public: double __thiscall core::GeoRect::GetTop(void)const ` | 172 (0xac) | Exported Function | 0x10016e60 | 0x00016e60
`public: enum core::CompassHeading __thiscall core::RouteManeuver::GetHeading(void)const ` | 128 (0x80) | Exported Function | 0x1001bad0 | 0x0001bad0
`public: enum core::RouteManeuverType __thiscall core::RouteManeuver::GetManeuverType(void)const ` | 149 (0x95) | Exported Function | 0x1001c650 | 0x0001c650
`public: enum QueryStatus __thiscall QueryAdapterCore::GetStatus(void)const ` | 167 (0xa7) | Exported Function | 0x1001a1f0 | 0x0001a1f0
`public: int __thiscall OperationAdapterCore::GetInstanceId(void)const ` | 130 (0x82) | Exported Function | 0x1001a120 | 0x0001a120
`public: long __thiscall core::GeoRect::GetBottomRight(class core::GeoCoordinates *)const ` | 102 (0x66) | Exported Function | 0x10016b90 | 0x00016b90
`public: long __thiscall core::GeoRect::GetCenter(class core::GeoCoordinates *)const ` | 105 (0x69) | Exported Function | 0x10016be0 | 0x00016be0
`public: long __thiscall core::GeoRect::GetTopLeft(class core::GeoCoordinates *)const ` | 173 (0xad) | Exported Function | 0x10016ea0 | 0x00016ea0
`public: long __thiscall core::Route::Initialize(class std::shared_ptr<class msnma::IRoute>)` | 191 (0xbf) | Exported Function | 0x100104a0 | 0x000104a0
`public: long __thiscall core::Route::Serialize(class std::basic_ostream<char,struct std::char_traits<char> > &)const ` | 221 (0xdd) | Exported Function | 0x1001dea0 | 0x0001dea0
`public: long __thiscall core::RouteManeuver::GetCurrentRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 108 (0x6c) | Exported Function | 0x1001b2a0 | 0x0001b2a0
`public: long __thiscall core::RouteManeuver::GetFreewayExitNumber(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 121 (0x79) | Exported Function | 0x1001b760 | 0x0001b760
`public: long __thiscall core::RouteManeuver::GetInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 131 (0x83) | Exported Function | 0x1001bb50 | 0x0001bb50
`public: long __thiscall core::RouteManeuver::GetManeuverNotice(int *)const ` | 148 (0x94) | Exported Function | 0x1001c4e0 | 0x0001c4e0
`public: long __thiscall core::RouteManeuver::GetStartCoordinates(class core::GeoCoordinates *)const ` | 165 (0xa5) | Exported Function | 0x1001ca30 | 0x0001ca30
`public: long __thiscall core::RouteManeuver::GetTargetRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 171 (0xab) | Exported Function | 0x1001cd50 | 0x0001cd50
`public: long __thiscall OperationAdapterCore::GetErrorCode(void)const ` | 120 (0x78) | Exported Function | 0x10009950 | 0x00009950
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const &,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,long,struct engine::RouteOptions *)` | 82 (0x52) | Exported Function | 0x1000f0b0 | 0x0000f0b0
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const &,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,struct engine::RouteOptions *)` | 83 (0x53) | Exported Function | 0x1001a660 | 0x0001a660
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > &&,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,long,struct engine::RouteOptions *)` | 80 (0x50) | Exported Function | 0x1000ee40 | 0x0000ee40
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > &&,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,struct engine::RouteOptions *)` | 81 (0x51) | Exported Function | 0x1000f080 | 0x0000f080
`public: long __thiscall RouterAdapterCore::GetAlternateRoute(unsigned int,class core::Route *)` | 89 (0x59) | Exported Function | 0x1001a750 | 0x0001a750
`public: long __thiscall RouterAdapterCore::GetAlternateRouteCount(unsigned int *)` | 90 (0x5a) | Exported Function | 0x1001a7d0 | 0x0001a7d0
`public: long __thiscall RouterAdapterCore::GetAlternateRouteViolatedOption(unsigned int,int *)` | 91 (0x5b) | Exported Function | 0x1001a7f0 | 0x0001a7f0
`public: long __thiscall RouterAdapterCore::GetConnectivityType(enum engine::ConnectivityType *)` | 106 (0x6a) | Exported Function | 0x1001a860 | 0x0001a860
`public: long __thiscall RouterAdapterCore::GetRoute(class core::Route *)` | 163 (0xa3) | Exported Function | 0x1001a8b0 | 0x0001a8b0
`public: static long __stdcall MapsSettings::SetKeyValidationStatus(int)` | 234 (0xea) | Exported Function | 0x1000ddc0 | 0x0000ddc0
`public: static long __stdcall MapsSettings::SetLimitNetworkUsage(bool)` | 236 (0xec) | Exported Function | 0x1000de10 | 0x0000de10
`public: static long __stdcall SuspendResumeDispatcher::RegisterListener(class ISuspendResumeListener *,bool *)` | 218 (0xda) | Exported Function | 0x1001eda0 | 0x0001eda0
`public: virtual unsigned long __thiscall core::Route::GetDurationWithoutTrafficInSeconds(void)const ` | 115 (0x73) | Exported Function | 0x1000fe60 | 0x0000fe60
`public: virtual unsigned long __thiscall core::Route::GetGeometryCoordinatesCount(void)const ` | 125 (0x7d) | Exported Function | 0x1001b990 | 0x0001b990
`public: virtual unsigned long __thiscall core::Route::GetLegCount(void)const ` | 140 (0x8c) | Exported Function | 0x1001a130 | 0x0001a130
`public: virtual unsigned long __thiscall core::Route::GetLengthInMeters(void)const ` | 141 (0x8d) | Exported Function | 0x1001c1d0 | 0x0001c1d0
`public: virtual unsigned long __thiscall core::RouteLeg::GetDurationInSeconds(void)const ` | 114 (0x72) | Exported Function | 0x1001b440 | 0x0001b440
`public: virtual unsigned long __thiscall core::RouteLeg::GetDurationWithoutTrafficInSeconds(void)const ` | 116 (0x74) | Exported Function | 0x1000ff00 | 0x0000ff00
`public: virtual unsigned long __thiscall core::RouteLeg::GetGeometryCoordinatesCount(void)const ` | 126 (0x7e) | Exported Function | 0x1001ba30 | 0x0001ba30
`public: virtual unsigned long __thiscall core::RouteLeg::GetLengthInMeters(void)const ` | 142 (0x8e) | Exported Function | 0x1001c270 | 0x0001c270
`public: virtual unsigned long __thiscall core::RouteLeg::GetManeuverCount(void)const ` | 147 (0x93) | Exported Function | 0x1001c4a0 | 0x0001c4a0
`public: virtual unsigned long __thiscall RouterAdapterCore::GetResultSqmId(void)const ` | 161 (0xa1) | Exported Function | 0x1001a8a0 | 0x0001a8a0
`public: virtual void __thiscall core::GeoCoordinates::SetAltitude(double)` | 222 (0xde) | Exported Function | 0x100172d0 | 0x000172d0
`public: virtual void __thiscall core::GeoCoordinates::SetLatitude(double)` | 235 (0xeb) | Exported Function | 0x10017300 | 0x00017300
`public: virtual void __thiscall core::GeoCoordinates::SetLongitude(double)` | 237 (0xed) | Exported Function | 0x10017320 | 0x00017320
`public: virtual void __thiscall RouterAdapterCore::OnRouteDone(struct engine::RouteResult const &)` | 214 (0xd6) | Exported Function | 0x1001a9e0 | 0x0001a9e0
`public: virtual void __thiscall RouterAdapterCore::OnRouteProgress(unsigned long)` | 215 (0xd7) | Exported Function | 0x1001aa70 | 0x0001aa70
`public: virtual void __thiscall UIThreadCore<struct IRouterUI>::Post(class TDispatchItem<struct IRouterUI> *)` | 216 (0xd8) | Exported Function | 0x1001aac0 | 0x0001aac0
`public: void __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::SetBackingObject(class Microsoft::ngeo::GeoCoordinates const &)` | 225 (0xe1) | Exported Function | 0x1000d750 | 0x0000d750
`public: void __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::SetBackingObject(class Microsoft::ngeo::GeoRect const &)` | 226 (0xe2) | Exported Function | 0x1000d770 | 0x0000d770
`public: void __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::SetBackingObject(class std::shared_ptr<class msnma::IManeuver> const &)` | 223 (0xdf) | Exported Function | 0x100107e0 | 0x000107e0
`public: void __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::SetBackingObject(class std::shared_ptr<class msnma::IRoute> const &)` | 224 (0xe0) | Exported Function | 0x10010800 | 0x00010800
`public: void __thiscall core::DoublePoint::``default constructor closure'(void)` | 78 (0x4e) | Exported Function | 0x100167e0 | 0x000167e0
`public: void __thiscall core::GeoRect::CopyFrom(class core::GeoRect const &)` | 86 (0x56) | Exported Function | 0x10016b00 | 0x00016b00
`public: void __thiscall RouterAdapterCore::Cancel(void)` | 84 (0x54) | Exported Function | 0x1001a690 | 0x0001a690
`public: void __thiscall UIThreadCore<struct IRouterUI>::ProcessDispatchQueue(struct IRouterUI *)` | 217 (0xd9) | Exported Function | 0x1001aae0 | 0x0001aae0
`SetDebugThreadId` | 229 (0xe5) | Exported Function | 0x1001efe0 | 0x0001efe0
`SetRenderThreadId` | 240 (0xf0) | Exported Function | 0x1001f000 | 0x0001f000
`SetUIThreadChecksEnabled` | 242 (0xf2) | Exported Function | 0x1001f020 | 0x0001f020
`public: virtual unsigned long __thiscall core::Route::GetDurationInSeconds(void)const ` | 113 (0x71) | Exported Function | 0x1001b3a0 | 0x0001b3a0
`public: virtual long __thiscall UIThreadCore<struct IRouterUI>::GetGenerationNumber(void)const ` | 122 (0x7a) | Exported Function | 0x1001a120 | 0x0001a120
`public: virtual long __thiscall core::RouteLeg::GetManeuver(unsigned long,class core::RouteManeuver *)const ` | 146 (0x92) | Exported Function | 0x1001c330 | 0x0001c330
`public: virtual long __thiscall core::RouteLeg::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates *)const ` | 124 (0x7c) | Exported Function | 0x1001b8d0 | 0x0001b8d0
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultDrivingRouteOptions` | 249 (0xf9) | Exported Function | 0x1002838c | 0x0002838c
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultWalkingRouteOptions` | 250 (0xfa) | Exported Function | 0x10028394 | 0x00028394
`public: static void __stdcall MapsSettings::SetEnableManeuverCondensing(bool)` | 231 (0xe7) | Exported Function | 0x100183d0 | 0x000183d0
`public: static void __stdcall MosThread::WaitOnClose(void)` | 246 (0xf6) | Exported Function | 0x10019c70 | 0x00019c70
`public: static void __stdcall SuspendResumeDispatcher::UnregisterListener(class ISuspendResumeListener *)` | 244 (0xf4) | Exported Function | 0x1001eed0 | 0x0001eed0
`public: struct core::DoublePoint & __thiscall core::DoublePoint::operator=(struct core::DoublePoint &&)` | 54 (0x36) | Exported Function | 0x10016250 | 0x00016250
`public: struct core::DoublePoint & __thiscall core::DoublePoint::operator=(struct core::DoublePoint const &)` | 55 (0x37) | Exported Function | 0x10016270 | 0x00016270
`public: unsigned long __thiscall core::RouteManeuver::GetDistanceInMetersFromPreviousManeuver(void)const ` | 111 (0x6f) | Exported Function | 0x1001b360 | 0x0001b360
`public: unsigned long __thiscall core::RouteManeuver::GetDistanceInMetersToNextManeuver(void)const ` | 112 (0x70) | Exported Function | 0x1001b380 | 0x0001b380
`public: unsigned long __thiscall core::RouteManeuver::GetManeuverWarningCount(void)const ` | 150 (0x96) | Exported Function | 0x100101a0 | 0x000101a0
`public: unsigned long __thiscall core::RouteManeuver::GetTrafficCircleExitNumber(void)const ` | 174 (0xae) | Exported Function | 0x1001ce00 | 0x0001ce00
`public: unsigned long __thiscall OperationAdapterCore::GetProgress(void)const ` | 158 (0x9e) | Exported Function | 0x1001a130 | 0x0001a130
`public: virtual __thiscall core::GeoCoordinates::~GeoCoordinates(void)` | 38 (0x26) | Exported Function | 0x10009a50 | 0x00009a50
`public: double __thiscall core::GeoRect::GetBottom(void)const ` | 101 (0x65) | Exported Function | 0x10016b50 | 0x00016b50
`public: virtual __thiscall core::GeoRect::~GeoRect(void)` | 39 (0x27) | Exported Function | 0x100161e0 | 0x000161e0
`public: virtual __thiscall core::RouteLeg::~RouteLeg(void)` | 43 (0x2b) | Exported Function | 0x1001ad00 | 0x0001ad00
`public: virtual __thiscall core::RouteManeuver::~RouteManeuver(void)` | 44 (0x2c) | Exported Function | 0x1001ad40 | 0x0001ad40
`public: virtual bool __thiscall core::GeoCoordinates::IsValid(void)const ` | 209 (0xd1) | Exported Function | 0x10017280 | 0x00017280
`public: virtual bool __thiscall core::GeoRect::IsValid(void)const ` | 210 (0xd2) | Exported Function | 0x100172b0 | 0x000172b0
`public: virtual double __thiscall core::GeoCoordinates::GetAltitude(void)const ` | 92 (0x5c) | Exported Function | 0x10016b20 | 0x00016b20
`public: virtual double __thiscall core::GeoCoordinates::GetLatitude(void)const ` | 136 (0x88) | Exported Function | 0x10016d40 | 0x00016d40
`public: virtual double __thiscall core::GeoCoordinates::GetLongitude(void)const ` | 145 (0x91) | Exported Function | 0x10016db0 | 0x00016db0
`public: virtual enum msnma::IRoute::TrafficCongestionType __thiscall core::Route::GetTrafficCongestion(void)const ` | 176 (0xb0) | Exported Function | 0x10010320 | 0x00010320
`public: virtual enum msnma::IRoute::TrafficCongestionType __thiscall core::RouteLeg::GetTrafficCongestion(void)const ` | 177 (0xb1) | Exported Function | 0x100103e0 | 0x000103e0
`public: virtual long __thiscall core::Route::GetBoundingBox(class core::GeoRect *)const ` | 103 (0x67) | Exported Function | 0x1001b030 | 0x0001b030
`public: virtual long __thiscall core::Route::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates *)const ` | 123 (0x7b) | Exported Function | 0x1001b7c0 | 0x0001b7c0
`public: virtual long __thiscall core::Route::GetLeg(unsigned long,class core::RouteLeg *)const ` | 139 (0x8b) | Exported Function | 0x1001c0e0 | 0x0001c0e0
`public: virtual long __thiscall core::RouteLeg::GetBoundingBox(class core::GeoRect *)const ` | 104 (0x68) | Exported Function | 0x1001b110 | 0x0001b110
`public: virtual __thiscall core::Route::~Route(void)` | 42 (0x2a) | Exported Function | 0x1001ace0 | 0x0001ace0
`public: class std::shared_ptr<class msnma::IRoute> __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::GetBackingObject(void)const ` | 94 (0x5e) | Exported Function | 0x1000fe40 | 0x0000fe40
`public: class std::shared_ptr<class msnma::IManeuver> __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::GetBackingObject(void)const ` | 93 (0x5d) | Exported Function | 0x1000fe40 | 0x0000fe40
`public: class QueryAdapterCore & __thiscall QueryAdapterCore::operator=(class QueryAdapterCore const &)` | 59 (0x3b) | Exported Function | 0x10019ff0 | 0x00019ff0
`private: long __thiscall core::RouteManeuver::GetTakeFerryInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 170 (0xaa) | Exported Function | 0x1001cd30 | 0x0001cd30
`private: long __thiscall core::RouteManeuver::GetTrafficCircleInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 175 (0xaf) | Exported Function | 0x1001cee0 | 0x0001cee0
`private: long __thiscall core::RouteManeuver::GetTurnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 178 (0xb2) | Exported Function | 0x1001cf60 | 0x0001cf60
`private: long __thiscall core::RouteManeuver::GetUndefinedInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 179 (0xb3) | Exported Function | 0x1001d190 | 0x0001d190
`private: long __thiscall core::RouteManeuver::GetUturnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 187 (0xbb) | Exported Function | 0x1001d1f0 | 0x0001d1f0
`private: long __thiscall core::RouteManeuver::Initialize(class std::vector<class std::shared_ptr<class msnma::IManeuver>,class std::allocator<class std::shared_ptr<class msnma::IManeuver> > > const &,int)` | 193 (0xc1) | Exported Function | 0x100106d0 | 0x000106d0
`private: long __thiscall core::RouteManeuver::InitializeInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 195 (0xc3) | Exported Function | 0x1001d340 | 0x0001d340
`private: static enum core::CompassHeading __stdcall core::RouteManeuver::GetSnappedCompassHeading(unsigned long)` | 164 (0xa4) | Exported Function | 0x1001c910 | 0x0001c910
`protected: __thiscall OperationAdapterCore::OperationAdapterCore(void)` | 22 (0x16) | Exported Function | 0x10019f30 | 0x00019f30
`protected: __thiscall QueryAdapterCore::QueryAdapterCore(void)` | 24 (0x18) | Exported Function | 0x1001a1d0 | 0x0001a1d0
`protected: __thiscall RouterAdapterCore::RouterAdapterCore(void)` | 32 (0x20) | Exported Function | 0x1001a300 | 0x0001a300
`protected: __thiscall UIThreadCore<struct IRouterUI>::UIThreadCore<struct IRouterUI>(void)` | 13 (0xd) | Exported Function | 0x1001a2a0 | 0x0001a2a0
`protected: bool __thiscall UIThreadCore<struct IRouterUI>::IsDispatchEnabled(void)` | 204 (0xcc) | Exported Function | 0x1001a9d0 | 0x0001a9d0
`protected: class Microsoft::ngeo::GeoCoordinates & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)` | 95 (0x5f) | Exported Function | 0x1000d740 | 0x0000d740
`protected: class Microsoft::ngeo::GeoRect & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)` | 97 (0x61) | Exported Function | 0x1000d740 | 0x0000d740
`protected: long __thiscall RouterAdapterCore::_CoreInitialize(int,class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >)` | 247 (0xf7) | Exported Function | 0x1000f370 | 0x0000f370
`protected: long __thiscall UIThreadCore<struct IRouterUI>::IncrementGeneration(void)` | 189 (0xbd) | Exported Function | 0x100099d0 | 0x000099d0
`protected: long __thiscall UIThreadCore<struct IRouterUI>::Initialize(class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >)` | 190 (0xbe) | Exported Function | 0x1001a920 | 0x0001a920
`protected: virtual __thiscall OperationAdapterCore::~OperationAdapterCore(void)` | 40 (0x28) | Exported Function | 0x10019fb0 | 0x00019fb0
`protected: virtual __thiscall QueryAdapterCore::~QueryAdapterCore(void)` | 41 (0x29) | Exported Function | 0x10019fb0 | 0x00019fb0
`protected: virtual __thiscall RouterAdapterCore::~RouterAdapterCore(void)` | 45 (0x2d) | Exported Function | 0x1001a3e0 | 0x0001a3e0
`protected: virtual __thiscall UIThreadCore<struct IRouterUI>::~UIThreadCore<struct IRouterUI>(void)` | 37 (0x25) | Exported Function | 0x1001a350 | 0x0001a350
`protected: virtual unsigned long __thiscall OperationAdapterCore::GetResultSqmId(void)const ` | 160 (0xa0) | Exported Function | 0x1000c770 | 0x0000c770
`protected: virtual void __thiscall OperationAdapterCore::SetProgress(unsigned long)` | 238 (0xee) | Exported Function | 0x1001a190 | 0x0001a190
`protected: virtual void __thiscall QueryAdapterCore::SetProgress(unsigned long)` | 239 (0xef) | Exported Function | 0x1001a200 | 0x0001a200
`protected: void __thiscall OperationAdapterCore::ResetProgress(void)` | 219 (0xdb) | Exported Function | 0x1001a140 | 0x0001a140
`protected: void __thiscall OperationAdapterCore::SetErrorCode(long)` | 232 (0xe8) | Exported Function | 0x10009980 | 0x00009980
`private: long __thiscall core::RouteManeuver::GetStopoverInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 168 (0xa8) | Exported Function | 0x1001cbe0 | 0x0001cbe0
`private: long __thiscall core::RouteManeuver::GetStartInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 166 (0xa6) | Exported Function | 0x1001cb10 | 0x0001cb10
`private: long __thiscall core::RouteManeuver::GetLeaveFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 137 (0x89) | Exported Function | 0x1001bd70 | 0x0001bd70
`private: long __thiscall core::RouteManeuver::GetInstructionWithTargetAndReplacement(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 134 (0x86) | Exported Function | 0x1001bcd0 | 0x0001bcd0
`const core::GeoRect::``vftable'` | 69 (0x45) | Exported Function | 0x100010e0 | 0x000010e0
`const core::Route::``vftable'` | 72 (0x48) | Exported Function | 0x1000108c | 0x0000108c
`const core::RouteLeg::``vftable'` | 73 (0x49) | Exported Function | 0x100010b4 | 0x000010b4
`const core::RouteManeuver::``vftable'` | 74 (0x4a) | Exported Function | 0x100010dc | 0x000010dc
`const OperationAdapterCore::``vftable'` | 70 (0x46) | Exported Function | 0x100011e4 | 0x000011e4
`const QueryAdapterCore::``vftable'` | 71 (0x47) | Exported Function | 0x100011cc | 0x000011cc
`const RouterAdapterCore::``vftable'{for ``IRouterUI'}` | 76 (0x4c) | Exported Function | 0x10001234 | 0x00001234
`const RouterAdapterCore::``vftable'{for ``QueryAdapterCore'}` | 77 (0x4d) | Exported Function | 0x1000123c | 0x0000123c
`const RouterAdapterCore::``vftable'{for ``UIThreadCore<struct IRouterUI>'}` | 75 (0x4b) | Exported Function | 0x10001228 | 0x00001228
`const UIThreadCore<struct IRouterUI>::``vftable'` | 67 (0x43) | Exported Function | 0x10001208 | 0x00001208
`GetMosThreadInstance` | 156 (0x9c) | Exported Function | 0x10018f10 | 0x00018f10
`GetMosThreadInstanceWithoutWait` | 157 (0x9d) | Exported Function | 0x10018f50 | 0x00018f50
`IsDebugThread` | 201 (0xc9) | Exported Function | 0x1001ef70 | 0x0001ef70
`protected: void __thiscall OperationAdapterCore::SetInstanceId(int)` | 233 (0xe9) | Exported Function | 0x1001a170 | 0x0001a170
`IsMosThread` | 205 (0xcd) | Exported Function | 0x100193a0 | 0x000193a0
`IsUIThread` | 208 (0xd0) | Exported Function | 0x1001efb0 | 0x0001efb0
`private: bool __thiscall core::RouteLeg::IsValid(void)const ` | 212 (0xd4) | Exported Function | 0x1001ddd0 | 0x0001ddd0
`private: long __thiscall core::Route::InitializeLegs(void)` | 196 (0xc4) | Exported Function | 0x1001d700 | 0x0001d700
`private: long __thiscall core::RouteLeg::Initialize(class std::shared_ptr<class msnma::IRoute>,unsigned long)` | 192 (0xc0) | Exported Function | 0x10010590 | 0x00010590
`private: long __thiscall core::RouteLeg::InitializeGeometryCoordinates(void)` | 194 (0xc2) | Exported Function | 0x1001d210 | 0x0001d210
`private: long __thiscall core::RouteLeg::InitializeManeuverCondensingContexts(bool)` | 197 (0xc5) | Exported Function | 0x1001d800 | 0x0001d800
`private: long __thiscall core::RouteLeg::InitializeManeuvers(void)` | 198 (0xc6) | Exported Function | 0x1001da70 | 0x0001da70
`private: long __thiscall core::RouteManeuver::GetContinueFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 107 (0x6b) | Exported Function | 0x1001b1c0 | 0x0001b1c0
`private: long __thiscall core::RouteManeuver::GetEndInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 118 (0x76) | Exported Function | 0x1001b500 | 0x0001b500
`private: long __thiscall core::RouteManeuver::GetEnterFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 119 (0x77) | Exported Function | 0x1001b520 | 0x0001b520
`private: long __thiscall core::RouteManeuver::GetGoStraightInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 127 (0x7f) | Exported Function | 0x1001bab0 | 0x0001bab0
`private: long __thiscall core::RouteManeuver::GetInstructionTextFromBacking(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 132 (0x84) | Exported Function | 0x1001bbb0 | 0x0001bbb0
`private: long __thiscall core::RouteManeuver::GetInstructionWithTarget(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 133 (0x85) | Exported Function | 0x1001bc80 | 0x0001bc80
`IsRenderThread` | 207 (0xcf) | Exported Function | 0x1001ef90 | 0x0001ef90
`SetUIThreadId` | 243 (0xf3) | Exported Function | 0x1001f040 | 0x0001f040
`protected: void __thiscall QueryAdapterCore::SetStatus(enum QueryStatus)` | 241 (0xf1) | Exported Function | 0x1001a240 | 0x0001a240
`protected: void __thiscall UIThreadCore<struct IRouterUI>::SetDispatchEnabled(bool)` | 230 (0xe6) | Exported Function | 0x1001ab00 | 0x0001ab00
`public: bool __thiscall core::DoublePoint::operator!=(struct core::DoublePoint const &)const ` | 65 (0x41) | Exported Function | 0x100164a0 | 0x000164a0
`public: bool __thiscall core::DoublePoint::operator==(struct core::DoublePoint const &)const ` | 63 (0x3f) | Exported Function | 0x10016430 | 0x00016430
`public: bool __thiscall core::GeoCoordinates::operator!=(class core::GeoCoordinates const &)const ` | 66 (0x42) | Exported Function | 0x100164c0 | 0x000164c0
`public: bool __thiscall core::GeoCoordinates::operator==(class core::GeoCoordinates const &)const ` | 64 (0x40) | Exported Function | 0x10016470 | 0x00016470
`public: bool __thiscall core::GeoRect::Contains(class core::GeoCoordinates const *)` | 85 (0x55) | Exported Function | 0x10016ac0 | 0x00016ac0
`public: bool __thiscall core::GeoRect::Intersects(class core::GeoRect const *)` | 199 (0xc7) | Exported Function | 0x10016ef0 | 0x00016ef0
`public: bool __thiscall core::GeoRect::IsDegenerate(void)const ` | 202 (0xca) | Exported Function | 0x100171b0 | 0x000171b0
`public: bool __thiscall core::Route::IsDeserialized(void)const ` | 203 (0xcb) | Exported Function | 0x1001dbe0 | 0x0001dbe0
`public: bool __thiscall core::Route::IsValid(void)const ` | 211 (0xd3) | Exported Function | 0x1001dd00 | 0x0001dd00
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> &&)` | 50 (0x32) | Exported Function | 0x1000d650 | 0x0000d650
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const &)` | 51 (0x33) | Exported Function | 0x1000d670 | 0x0000d670
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> &&)` | 52 (0x34) | Exported Function | 0x1000d690 | 0x0000d690
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> const &)` | 53 (0x35) | Exported Function | 0x1000d6b0 | 0x0000d6b0
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > &&)` | 46 (0x2e) | Exported Function | 0x1000d5d0 | 0x0000d5d0
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const &)` | 47 (0x2f) | Exported Function | 0x1000d610 | 0x0000d610
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > &&)` | 48 (0x30) | Exported Function | 0x1000d630 | 0x0000d630
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const &)` | 49 (0x31) | Exported Function | 0x1000d610 | 0x0000d610
`public: class core::GeoCoordinates & __thiscall core::GeoCoordinates::operator=(class core::GeoCoordinates const &)` | 56 (0x38) | Exported Function | 0x10016290 | 0x00016290
`public: class core::GeoRect & __thiscall core::GeoRect::operator=(class core::GeoRect const &)` | 57 (0x39) | Exported Function | 0x100162c0 | 0x000162c0
`public: class core::GeoRect __thiscall core::GeoRect::GetInflatedGeoRect(void)const ` | 129 (0x81) | Exported Function | 0x10016c50 | 0x00016c50
`public: class core::Route & __thiscall core::Route::operator=(class core::Route const &)` | 60 (0x3c) | Exported Function | 0x10016340 | 0x00016340
`public: class core::RouteLeg & __thiscall core::RouteLeg::operator=(class core::RouteLeg const &)` | 61 (0x3d) | Exported Function | 0x10016370 | 0x00016370
`public: class core::RouteManeuver & __thiscall core::RouteManeuver::operator=(class core::RouteManeuver const &)` | 62 (0x3e) | Exported Function | 0x100163c0 | 0x000163c0
`public: class Microsoft::ngeo::GeoCoordinates const & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)const ` | 96 (0x60) | Exported Function | 0x1000d740 | 0x0000d740
`public: class Microsoft::ngeo::GeoRect const & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)const ` | 98 (0x62) | Exported Function | 0x1000d740 | 0x0000d740
`public: class msnma::IItineraryWarning const & __thiscall core::RouteManeuver::GetManeuverWarnings(unsigned long)const ` | 151 (0x97) | Exported Function | 0x10010210 | 0x00010210
`public: class OperationAdapterCore & __thiscall OperationAdapterCore::operator=(class OperationAdapterCore const &)` | 58 (0x3a) | Exported Function | 0x10019fc0 | 0x00019fc0
`public: __thiscall QueryAdapterCore::QueryAdapterCore(class QueryAdapterCore const &)` | 25 (0x19) | Exported Function | 0x10019f80 | 0x00019f80
`public: __thiscall OperationAdapterCore::OperationAdapterCore(class OperationAdapterCore const &)` | 23 (0x17) | Exported Function | 0x10019f50 | 0x00019f50
`public: __thiscall core::RouteManeuver::RouteManeuver(void)` | 31 (0x1f) | Exported Function | 0x1001acb0 | 0x0001acb0
`public: __thiscall core::RouteManeuver::RouteManeuver(class core::RouteManeuver const &)` | 30 (0x1e) | Exported Function | 0x10016170 | 0x00016170
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> &&)` | 7 (0x7) | Exported Function | 0x1000d440 | 0x0000d440
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const &)` | 8 (0x8) | Exported Function | 0x1000d460 | 0x0000d460
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(void)` | 9 (0x9) | Exported Function | 0x1000d480 | 0x0000d480
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::~BackedType<class Microsoft::ngeo::GeoCoordinates>(void)` | 35 (0x23) | Exported Function | 0x1000d590 | 0x0000d590
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> &&)` | 10 (0xa) | Exported Function | 0x1000d4a0 | 0x0000d4a0
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> const &)` | 11 (0xb) | Exported Function | 0x1000d4c0 | 0x0000d4c0
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(void)` | 12 (0xc) | Exported Function | 0x1000d4e0 | 0x0000d4e0
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::~BackedType<class Microsoft::ngeo::GeoRect>(void)` | 36 (0x24) | Exported Function | 0x1000d5a0 | 0x0000d5a0
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > &&)` | 1 (0x1) | Exported Function | 0x1000d3e0 | 0x0000d3e0
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const &)` | 2 (0x2) | Exported Function | 0x1000d410 | 0x0000d410
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(void)` | 3 (0x3) | Exported Function | 0x1000d430 | 0x0000d430
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::~BackedType<class std::shared_ptr<class msnma::IManeuver> >(void)` | 33 (0x21) | Exported Function | 0x1000d570 | 0x0000d570
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > &&)` | 4 (0x4) | Exported Function | 0x1000d3e0 | 0x0000d3e0
`protected: void __thiscall RouterAdapterCore::_CoreUninitialize(void)` | 248 (0xf8) | Exported Function | 0x1001ab20 | 0x0001ab20
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const &)` | 5 (0x5) | Exported Function | 0x1000d410 | 0x0000d410
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::~BackedType<class std::shared_ptr<class msnma::IRoute> >(void)` | 34 (0x22) | Exported Function | 0x1000d570 | 0x0000d570
`public: __thiscall core::DoublePoint::DoublePoint(double,double)` | 14 (0xe) | Exported Function | 0x10015eb0 | 0x00015eb0
`public: __thiscall core::GeoCoordinates::GeoCoordinates(class core::GeoCoordinates const &)` | 15 (0xf) | Exported Function | 0x10015ed0 | 0x00015ed0
`public: __thiscall core::GeoCoordinates::GeoCoordinates(double,double)` | 16 (0x10) | Exported Function | 0x100099e0 | 0x000099e0
`public: __thiscall core::GeoCoordinates::GeoCoordinates(void)` | 17 (0x11) | Exported Function | 0x10015f00 | 0x00015f00
`public: __thiscall core::GeoRect::GeoRect(class core::GeoCoordinates const *,class core::GeoCoordinates const *)` | 20 (0x14) | Exported Function | 0x10015fd0 | 0x00015fd0
`public: __thiscall core::GeoRect::GeoRect(class core::GeoRect const &)` | 18 (0x12) | Exported Function | 0x10015f30 | 0x00015f30
`public: __thiscall core::GeoRect::GeoRect(double,double,double,double)` | 19 (0x13) | Exported Function | 0x10015f60 | 0x00015f60
`public: __thiscall core::GeoRect::GeoRect(void)` | 21 (0x15) | Exported Function | 0x10016040 | 0x00016040
`public: __thiscall core::Route::Route(class core::Route const &)` | 26 (0x1a) | Exported Function | 0x100160c0 | 0x000160c0
`public: __thiscall core::Route::Route(void)` | 27 (0x1b) | Exported Function | 0x1001ac30 | 0x0001ac30
`public: __thiscall core::RouteLeg::RouteLeg(class core::RouteLeg const &)` | 28 (0x1c) | Exported Function | 0x10016100 | 0x00016100
`public: __thiscall core::RouteLeg::RouteLeg(void)` | 29 (0x1d) | Exported Function | 0x1001ac50 | 0x0001ac50
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(void)` | 6 (0x6) | Exported Function | 0x1000d430 | 0x0000d430
`WaitForMosThreadToClose` | 245 (0xf5) | Exported Function | 0x10019c60 | 0x00019c60


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
* File Version: 10.0.19041.1 (WinBuild.160101.0800)
* Product Version: 10.0.19041.1
* Language: English (United States)
* Legal Copyright:  Microsoft Corporation. All rights reserved.
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/71
* VirusTotal Link: https://www.virustotal.com/gui/file/c9b8c857acc9be5225c1324cbf49535d0ad2d15d2b1beec9f6fed9a7e7759955/detection/





MIT License. Copyright (c) 2020 Strontic.


