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

Function Name | Ordinal | Type
-- | -- | --
`public: static long __cdecl core::RouteManeuver::FormatString(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,unsigned long,...)` | 88 | Exported Function
`public: static double __stdcall core::GeoCoordinates::GetMinLongitude(void)` | 155 | Exported Function
`public: static double __stdcall core::GeoCoordinates::GetMinLatitude(void)` | 154 | Exported Function
`public: static long __stdcall ApiAccessCheck::RestrictedAPIAccessCheck(void)` | 220 | Exported Function
`public: static long __stdcall core::RouteManeuver::GetStringResource(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)` | 169 | Exported Function
`public: static long __stdcall core::Route::Deserialize(class std::basic_istream<char,struct std::char_traits<char> > &,class core::Route *)` | 87 | Exported Function
`public: static long __stdcall core::GeoRect::CalculateGeoRect(class std::vector<class core::GeoCoordinates *,class std::allocator<class core::GeoCoordinates *> > &,class core::GeoRect *)` | 79 | Exported Function
`public: static double __stdcall core::GeoCoordinates::GetMaxLongitude(void)` | 153 | Exported Function
`public: static bool __stdcall MapsSettings::IsChinaVariant(void)` | 200 | Exported Function
`public: static bool __stdcall MapsSettings::GetEnableManeuverCondensing(void)` | 117 | Exported Function
`public: long __thiscall RouterAdapterCore::GetViolatedOptions(int *)` | 188 | Exported Function
`public: static bool __stdcall MapsSettings::IsOldChinaRegKeySet(void)` | 206 | Exported Function
`public: static double __stdcall core::GeoCoordinates::GetMaxLatitude(void)` | 152 | Exported Function
`public: static class core::GeoCoordinates const * __stdcall MapsSettings::GetDefaultCenterFromTimezone(void)` | 110 | Exported Function
`public: static bool __stdcall MapsSettings::IsWatermarkEnabled(void)` | 213 | Exported Function
`public: static long __stdcall MapsSettings::GetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 99 | Exported Function
`public: static long __stdcall MapsSettings::GetUserProfileLanguages(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 186 | Exported Function
`public: static long __stdcall MapsSettings::GetUserProfileLanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 184 | Exported Function
`public: static long __stdcall MapsSettings::GetUserPreferredUILanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 183 | Exported Function
`public: static long __stdcall MapsSettings::GetUserProfileLanguages(struct HSTRING__ * *)` | 185 | Exported Function
`public: static long __stdcall MapsSettings::SetKeyValidationStatus(int)` | 234 | Exported Function
`public: static long __stdcall MapsSettings::SetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const &)` | 228 | Exported Function
`public: static long __stdcall MapsSettings::SetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const &)` | 227 | Exported Function
`public: static long __stdcall MapsSettings::GetUserGeoRegionAsThreeLetterCode(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 182 | Exported Function
`public: static long __stdcall MapsSettings::GetKeyValidationStatus(int *)` | 135 | Exported Function
`public: static long __stdcall MapsSettings::GetDataAttribution(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 109 | Exported Function
`public: static long __stdcall MapsSettings::GetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 100 | Exported Function
`public: static long __stdcall MapsSettings::GetLimitNetworkUsage(bool *)` | 143 | Exported Function
`public: static long __stdcall MapsSettings::GetUserGeoRegion(struct HSTRING__ * *)` | 180 | Exported Function
`public: static long __stdcall MapsSettings::GetUserGeoRegion(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > *)` | 181 | Exported Function
`public: static long __stdcall MapsSettings::GetLocaleMapConfiguration(struct ILocaleMapConfiguration * *)` | 144 | Exported Function
`public: long __thiscall core::GeoRect::GetCenter(class core::GeoCoordinates *)const ` | 105 | Exported Function
`public: long __thiscall core::GeoRect::GetBottomRight(class core::GeoCoordinates *)const ` | 102 | Exported Function
`public: int __thiscall OperationAdapterCore::GetInstanceId(void)const ` | 130 | Exported Function
`public: long __thiscall core::GeoRect::GetTopLeft(class core::GeoCoordinates *)const ` | 173 | Exported Function
`public: long __thiscall core::RouteManeuver::GetCurrentRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 108 | Exported Function
`public: long __thiscall core::Route::Serialize(class std::basic_ostream<char,struct std::char_traits<char> > &)const ` | 221 | Exported Function
`public: long __thiscall core::Route::Initialize(class std::shared_ptr<class msnma::IRoute>)` | 191 | Exported Function
`public: enum QueryStatus __thiscall QueryAdapterCore::GetStatus(void)const ` | 167 | Exported Function
`public: double __thiscall core::GeoRect::GetLeft(void)const ` | 138 | Exported Function
`public: double __thiscall core::GeoRect::GetBottom(void)const ` | 101 | Exported Function
`public: class std::shared_ptr<class msnma::IRoute> __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::GetBackingObject(void)const ` | 94 | Exported Function
`public: double __thiscall core::GeoRect::GetRight(void)const ` | 162 | Exported Function
`public: enum core::RouteManeuverType __thiscall core::RouteManeuver::GetManeuverType(void)const ` | 149 | Exported Function
`public: enum core::CompassHeading __thiscall core::RouteManeuver::GetHeading(void)const ` | 128 | Exported Function
`public: double __thiscall core::GeoRect::GetTop(void)const ` | 172 | Exported Function
`public: long __thiscall core::RouteManeuver::GetFreewayExitNumber(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 121 | Exported Function
`public: long __thiscall RouterAdapterCore::GetAlternateRouteCount(unsigned int *)` | 90 | Exported Function
`public: long __thiscall RouterAdapterCore::GetAlternateRoute(unsigned int,class core::Route *)` | 89 | Exported Function
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > &&,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,struct engine::RouteOptions *)` | 81 | Exported Function
`public: long __thiscall RouterAdapterCore::GetAlternateRouteViolatedOption(unsigned int,int *)` | 91 | Exported Function
`public: long __thiscall RouterAdapterCore::GetRoute(class core::Route *)` | 163 | Exported Function
`public: long __thiscall RouterAdapterCore::GetProvider(enum engine::Provider *)` | 159 | Exported Function
`public: long __thiscall RouterAdapterCore::GetConnectivityType(enum engine::ConnectivityType *)` | 106 | Exported Function
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > &&,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,long,struct engine::RouteOptions *)` | 80 | Exported Function
`public: long __thiscall core::RouteManeuver::GetStartCoordinates(class core::GeoCoordinates *)const ` | 165 | Exported Function
`public: long __thiscall core::RouteManeuver::GetManeuverNotice(int *)const ` | 148 | Exported Function
`public: long __thiscall core::RouteManeuver::GetInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 131 | Exported Function
`public: long __thiscall core::RouteManeuver::GetTargetRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 171 | Exported Function
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const &,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,struct engine::RouteOptions *)` | 83 | Exported Function
`public: long __thiscall RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const &,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,long,struct engine::RouteOptions *)` | 82 | Exported Function
`public: long __thiscall OperationAdapterCore::GetErrorCode(void)const ` | 120 | Exported Function
`public: static long __stdcall MapsSettings::SetLimitNetworkUsage(bool)` | 236 | Exported Function
`public: virtual unsigned long __thiscall core::RouteLeg::GetManeuverCount(void)const ` | 147 | Exported Function
`public: virtual unsigned long __thiscall core::RouteLeg::GetLengthInMeters(void)const ` | 142 | Exported Function
`public: virtual unsigned long __thiscall core::RouteLeg::GetGeometryCoordinatesCount(void)const ` | 126 | Exported Function
`public: virtual unsigned long __thiscall RouterAdapterCore::GetResultSqmId(void)const ` | 161 | Exported Function
`public: virtual void __thiscall core::GeoCoordinates::SetLongitude(double)` | 237 | Exported Function
`public: virtual void __thiscall core::GeoCoordinates::SetLatitude(double)` | 235 | Exported Function
`public: virtual void __thiscall core::GeoCoordinates::SetAltitude(double)` | 222 | Exported Function
`public: virtual unsigned long __thiscall core::RouteLeg::GetDurationWithoutTrafficInSeconds(void)const ` | 116 | Exported Function
`public: virtual unsigned long __thiscall core::Route::GetDurationWithoutTrafficInSeconds(void)const ` | 115 | Exported Function
`public: virtual unsigned long __thiscall core::Route::GetDurationInSeconds(void)const ` | 113 | Exported Function
`public: virtual long __thiscall UIThreadCore<struct IRouterUI>::GetGenerationNumber(void)const ` | 122 | Exported Function
`public: virtual unsigned long __thiscall core::Route::GetGeometryCoordinatesCount(void)const ` | 125 | Exported Function
`public: virtual unsigned long __thiscall core::RouteLeg::GetDurationInSeconds(void)const ` | 114 | Exported Function
`public: virtual unsigned long __thiscall core::Route::GetLengthInMeters(void)const ` | 141 | Exported Function
`public: virtual unsigned long __thiscall core::Route::GetLegCount(void)const ` | 140 | Exported Function
`public: virtual void __thiscall RouterAdapterCore::OnRouteDone(struct engine::RouteResult const &)` | 214 | Exported Function
`SetDebugThreadId` | 229 | Exported Function
`public: void __thiscall UIThreadCore<struct IRouterUI>::ProcessDispatchQueue(struct IRouterUI *)` | 217 | Exported Function
`public: void __thiscall RouterAdapterCore::Cancel(void)` | 84 | Exported Function
`SetRenderThreadId` | 240 | Exported Function
`WaitForMosThreadToClose` | 245 | Exported Function
`SetUIThreadId` | 243 | Exported Function
`SetUIThreadChecksEnabled` | 242 | Exported Function
`public: void __thiscall core::GeoRect::CopyFrom(class core::GeoRect const &)` | 86 | Exported Function
`public: void __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::SetBackingObject(class Microsoft::ngeo::GeoCoordinates const &)` | 225 | Exported Function
`public: virtual void __thiscall UIThreadCore<struct IRouterUI>::Post(class TDispatchItem<struct IRouterUI> *)` | 216 | Exported Function
`public: virtual void __thiscall RouterAdapterCore::OnRouteProgress(unsigned long)` | 215 | Exported Function
`public: void __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::SetBackingObject(class Microsoft::ngeo::GeoRect const &)` | 226 | Exported Function
`public: void __thiscall core::DoublePoint::``default constructor closure'(void)` | 78 | Exported Function
`public: void __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::SetBackingObject(class std::shared_ptr<class msnma::IRoute> const &)` | 224 | Exported Function
`public: void __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::SetBackingObject(class std::shared_ptr<class msnma::IManeuver> const &)` | 223 | Exported Function
`public: unsigned long __thiscall core::RouteManeuver::GetManeuverWarningCount(void)const ` | 150 | Exported Function
`public: unsigned long __thiscall core::RouteManeuver::GetDistanceInMetersToNextManeuver(void)const ` | 112 | Exported Function
`public: unsigned long __thiscall core::RouteManeuver::GetDistanceInMetersFromPreviousManeuver(void)const ` | 111 | Exported Function
`public: unsigned long __thiscall core::RouteManeuver::GetTrafficCircleExitNumber(void)const ` | 174 | Exported Function
`public: virtual __thiscall core::GeoRect::~GeoRect(void)` | 39 | Exported Function
`public: virtual __thiscall core::GeoCoordinates::~GeoCoordinates(void)` | 38 | Exported Function
`public: unsigned long __thiscall OperationAdapterCore::GetProgress(void)const ` | 158 | Exported Function
`public: struct core::DoublePoint & __thiscall core::DoublePoint::operator=(struct core::DoublePoint const &)` | 55 | Exported Function
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultWalkingRouteOptions` | 250 | Exported Function
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultDrivingRouteOptions` | 249 | Exported Function
`public: static long __stdcall SuspendResumeDispatcher::RegisterListener(class ISuspendResumeListener *,bool *)` | 218 | Exported Function
`public: static void __stdcall MapsSettings::SetEnableManeuverCondensing(bool)` | 231 | Exported Function
`public: struct core::DoublePoint & __thiscall core::DoublePoint::operator=(struct core::DoublePoint &&)` | 54 | Exported Function
`public: static void __stdcall SuspendResumeDispatcher::UnregisterListener(class ISuspendResumeListener *)` | 244 | Exported Function
`public: static void __stdcall MosThread::WaitOnClose(void)` | 246 | Exported Function
`public: virtual __thiscall core::Route::~Route(void)` | 42 | Exported Function
`public: virtual long __thiscall core::Route::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates *)const ` | 123 | Exported Function
`public: virtual long __thiscall core::Route::GetBoundingBox(class core::GeoRect *)const ` | 103 | Exported Function
`public: virtual enum msnma::IRoute::TrafficCongestionType __thiscall core::RouteLeg::GetTrafficCongestion(void)const ` | 177 | Exported Function
`public: virtual long __thiscall core::Route::GetLeg(unsigned long,class core::RouteLeg *)const ` | 139 | Exported Function
`public: virtual long __thiscall core::RouteLeg::GetManeuver(unsigned long,class core::RouteManeuver *)const ` | 146 | Exported Function
`public: virtual long __thiscall core::RouteLeg::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates *)const ` | 124 | Exported Function
`public: virtual long __thiscall core::RouteLeg::GetBoundingBox(class core::GeoRect *)const ` | 104 | Exported Function
`public: virtual enum msnma::IRoute::TrafficCongestionType __thiscall core::Route::GetTrafficCongestion(void)const ` | 176 | Exported Function
`public: virtual bool __thiscall core::GeoCoordinates::IsValid(void)const ` | 209 | Exported Function
`public: virtual __thiscall core::RouteManeuver::~RouteManeuver(void)` | 44 | Exported Function
`public: virtual __thiscall core::RouteLeg::~RouteLeg(void)` | 43 | Exported Function
`public: virtual bool __thiscall core::GeoRect::IsValid(void)const ` | 210 | Exported Function
`public: virtual double __thiscall core::GeoCoordinates::GetLongitude(void)const ` | 145 | Exported Function
`public: virtual double __thiscall core::GeoCoordinates::GetLatitude(void)const ` | 136 | Exported Function
`public: virtual double __thiscall core::GeoCoordinates::GetAltitude(void)const ` | 92 | Exported Function
`protected: __thiscall OperationAdapterCore::OperationAdapterCore(void)` | 22 | Exported Function
`private: static enum core::CompassHeading __stdcall core::RouteManeuver::GetSnappedCompassHeading(unsigned long)` | 164 | Exported Function
`private: long __thiscall core::RouteManeuver::InitializeInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 195 | Exported Function
`protected: __thiscall QueryAdapterCore::QueryAdapterCore(void)` | 24 | Exported Function
`protected: bool __thiscall UIThreadCore<struct IRouterUI>::IsDispatchEnabled(void)` | 204 | Exported Function
`protected: __thiscall UIThreadCore<struct IRouterUI>::UIThreadCore<struct IRouterUI>(void)` | 13 | Exported Function
`protected: __thiscall RouterAdapterCore::RouterAdapterCore(void)` | 32 | Exported Function
`private: long __thiscall core::RouteManeuver::Initialize(class std::vector<class std::shared_ptr<class msnma::IManeuver>,class std::allocator<class std::shared_ptr<class msnma::IManeuver> > > const &,int)` | 193 | Exported Function
`private: long __thiscall core::RouteManeuver::GetTakeFerryInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 170 | Exported Function
`private: long __thiscall core::RouteManeuver::GetStopoverInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 168 | Exported Function
`private: long __thiscall core::RouteManeuver::GetStartInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 166 | Exported Function
`private: long __thiscall core::RouteManeuver::GetTrafficCircleInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 175 | Exported Function
`private: long __thiscall core::RouteManeuver::GetUturnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 187 | Exported Function
`private: long __thiscall core::RouteManeuver::GetUndefinedInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 179 | Exported Function
`private: long __thiscall core::RouteManeuver::GetTurnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 178 | Exported Function
`protected: class Microsoft::ngeo::GeoCoordinates & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)` | 95 | Exported Function
`protected: virtual void __thiscall QueryAdapterCore::SetProgress(unsigned long)` | 239 | Exported Function
`protected: virtual void __thiscall OperationAdapterCore::SetProgress(unsigned long)` | 238 | Exported Function
`protected: virtual unsigned long __thiscall OperationAdapterCore::GetResultSqmId(void)const ` | 160 | Exported Function
`protected: void __thiscall OperationAdapterCore::ResetProgress(void)` | 219 | Exported Function
`protected: void __thiscall QueryAdapterCore::SetStatus(enum QueryStatus)` | 241 | Exported Function
`protected: void __thiscall OperationAdapterCore::SetInstanceId(int)` | 233 | Exported Function
`protected: void __thiscall OperationAdapterCore::SetErrorCode(long)` | 232 | Exported Function
`protected: virtual __thiscall UIThreadCore<struct IRouterUI>::~UIThreadCore<struct IRouterUI>(void)` | 37 | Exported Function
`protected: long __thiscall UIThreadCore<struct IRouterUI>::IncrementGeneration(void)` | 189 | Exported Function
`protected: long __thiscall RouterAdapterCore::_CoreInitialize(int,class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >)` | 247 | Exported Function
`protected: class Microsoft::ngeo::GeoRect & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)` | 97 | Exported Function
`protected: long __thiscall UIThreadCore<struct IRouterUI>::Initialize(class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >)` | 190 | Exported Function
`protected: virtual __thiscall RouterAdapterCore::~RouterAdapterCore(void)` | 45 | Exported Function
`protected: virtual __thiscall QueryAdapterCore::~QueryAdapterCore(void)` | 41 | Exported Function
`protected: virtual __thiscall OperationAdapterCore::~OperationAdapterCore(void)` | 40 | Exported Function
`const UIThreadCore<struct IRouterUI>::``vftable'` | 67 | Exported Function
`const RouterAdapterCore::``vftable'{for ``UIThreadCore<struct IRouterUI>'}` | 75 | Exported Function
`const RouterAdapterCore::``vftable'{for ``QueryAdapterCore'}` | 77 | Exported Function
`GetMosThreadInstance` | 156 | Exported Function
`IsMosThread` | 205 | Exported Function
`IsDebugThread` | 201 | Exported Function
`GetMosThreadInstanceWithoutWait` | 157 | Exported Function
`const RouterAdapterCore::``vftable'{for ``IRouterUI'}` | 76 | Exported Function
`const core::Route::``vftable'` | 72 | Exported Function
`const core::GeoRect::``vftable'` | 69 | Exported Function
`const core::GeoCoordinates::``vftable'` | 68 | Exported Function
`const core::RouteLeg::``vftable'` | 73 | Exported Function
`const QueryAdapterCore::``vftable'` | 71 | Exported Function
`const OperationAdapterCore::``vftable'` | 70 | Exported Function
`const core::RouteManeuver::``vftable'` | 74 | Exported Function
`IsRenderThread` | 207 | Exported Function
`private: long __thiscall core::RouteManeuver::GetGoStraightInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 127 | Exported Function
`private: long __thiscall core::RouteManeuver::GetEnterFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 119 | Exported Function
`private: long __thiscall core::RouteManeuver::GetEndInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 118 | Exported Function
`private: long __thiscall core::RouteManeuver::GetInstructionTextFromBacking(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 132 | Exported Function
`private: long __thiscall core::RouteManeuver::GetLeaveFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 137 | Exported Function
`private: long __thiscall core::RouteManeuver::GetInstructionWithTargetAndReplacement(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 134 | Exported Function
`private: long __thiscall core::RouteManeuver::GetInstructionWithTarget(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 133 | Exported Function
`private: long __thiscall core::RouteManeuver::GetContinueFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > &)const ` | 107 | Exported Function
`private: long __thiscall core::Route::InitializeLegs(void)` | 196 | Exported Function
`private: bool __thiscall core::RouteLeg::IsValid(void)const ` | 212 | Exported Function
`IsUIThread` | 208 | Exported Function
`private: long __thiscall core::RouteLeg::Initialize(class std::shared_ptr<class msnma::IRoute>,unsigned long)` | 192 | Exported Function
`private: long __thiscall core::RouteLeg::InitializeManeuvers(void)` | 198 | Exported Function
`private: long __thiscall core::RouteLeg::InitializeManeuverCondensingContexts(bool)` | 197 | Exported Function
`private: long __thiscall core::RouteLeg::InitializeGeometryCoordinates(void)` | 194 | Exported Function
`protected: void __thiscall RouterAdapterCore::_CoreUninitialize(void)` | 248 | Exported Function
`public: bool __thiscall core::Route::IsValid(void)const ` | 211 | Exported Function
`public: bool __thiscall core::Route::IsDeserialized(void)const ` | 203 | Exported Function
`public: bool __thiscall core::GeoRect::IsDegenerate(void)const ` | 202 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> &&)` | 50 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> const &)` | 53 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> &&)` | 52 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const &)` | 51 | Exported Function
`public: bool __thiscall core::GeoRect::Intersects(class core::GeoRect const *)` | 199 | Exported Function
`public: bool __thiscall core::DoublePoint::operator!=(struct core::DoublePoint const &)const ` | 65 | Exported Function
`public: __thiscall QueryAdapterCore::QueryAdapterCore(class QueryAdapterCore const &)` | 25 | Exported Function
`public: __thiscall OperationAdapterCore::OperationAdapterCore(class OperationAdapterCore const &)` | 23 | Exported Function
`public: bool __thiscall core::DoublePoint::operator==(struct core::DoublePoint const &)const ` | 63 | Exported Function
`public: bool __thiscall core::GeoRect::Contains(class core::GeoCoordinates const *)` | 85 | Exported Function
`public: bool __thiscall core::GeoCoordinates::operator==(class core::GeoCoordinates const &)const ` | 64 | Exported Function
`public: bool __thiscall core::GeoCoordinates::operator!=(class core::GeoCoordinates const &)const ` | 66 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > &&)` | 46 | Exported Function
`public: class Microsoft::ngeo::GeoRect const & __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)const ` | 98 | Exported Function
`public: class Microsoft::ngeo::GeoCoordinates const & __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)const ` | 96 | Exported Function
`public: class core::RouteManeuver & __thiscall core::RouteManeuver::operator=(class core::RouteManeuver const &)` | 62 | Exported Function
`public: class msnma::IItineraryWarning const & __thiscall core::RouteManeuver::GetManeuverWarnings(unsigned long)const ` | 151 | Exported Function
`public: class std::shared_ptr<class msnma::IManeuver> __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::GetBackingObject(void)const ` | 93 | Exported Function
`public: class QueryAdapterCore & __thiscall QueryAdapterCore::operator=(class QueryAdapterCore const &)` | 59 | Exported Function
`public: class OperationAdapterCore & __thiscall OperationAdapterCore::operator=(class OperationAdapterCore const &)` | 58 | Exported Function
`public: class core::RouteLeg & __thiscall core::RouteLeg::operator=(class core::RouteLeg const &)` | 61 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const &)` | 49 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > &&)` | 48 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const &)` | 47 | Exported Function
`public: class core::GeoCoordinates & __thiscall core::GeoCoordinates::operator=(class core::GeoCoordinates const &)` | 56 | Exported Function
`public: class core::Route & __thiscall core::Route::operator=(class core::Route const &)` | 60 | Exported Function
`public: class core::GeoRect __thiscall core::GeoRect::GetInflatedGeoRect(void)const ` | 129 | Exported Function
`public: class core::GeoRect & __thiscall core::GeoRect::operator=(class core::GeoRect const &)` | 57 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const &)` | 2 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > &&)` | 1 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::~BackedType<class Microsoft::ngeo::GeoRect>(void)` | 36 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(void)` | 3 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const &)` | 5 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > &&)` | 4 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::~BackedType<class std::shared_ptr<class msnma::IManeuver> >(void)` | 33 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(void)` | 12 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const &)` | 8 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> &&)` | 7 | Exported Function
`protected: void __thiscall UIThreadCore<struct IRouterUI>::SetDispatchEnabled(bool)` | 230 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(void)` | 9 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> const &)` | 11 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> &&)` | 10 | Exported Function
`public: __thiscall core::BackedType<class Microsoft::ngeo::GeoCoordinates>::~BackedType<class Microsoft::ngeo::GeoCoordinates>(void)` | 35 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(void)` | 6 | Exported Function
`public: __thiscall core::Route::Route(void)` | 27 | Exported Function
`public: __thiscall core::Route::Route(class core::Route const &)` | 26 | Exported Function
`public: __thiscall core::GeoRect::GeoRect(void)` | 21 | Exported Function
`public: __thiscall core::RouteLeg::RouteLeg(class core::RouteLeg const &)` | 28 | Exported Function
`public: __thiscall core::RouteManeuver::RouteManeuver(void)` | 31 | Exported Function
`public: __thiscall core::RouteManeuver::RouteManeuver(class core::RouteManeuver const &)` | 30 | Exported Function
`public: __thiscall core::RouteLeg::RouteLeg(void)` | 29 | Exported Function
`public: __thiscall core::GeoRect::GeoRect(double,double,double,double)` | 19 | Exported Function
`public: __thiscall core::GeoCoordinates::GeoCoordinates(class core::GeoCoordinates const &)` | 15 | Exported Function
`public: __thiscall core::DoublePoint::DoublePoint(double,double)` | 14 | Exported Function
`public: __thiscall core::BackedType<class std::shared_ptr<class msnma::IRoute> >::~BackedType<class std::shared_ptr<class msnma::IRoute> >(void)` | 34 | Exported Function
`public: __thiscall core::GeoCoordinates::GeoCoordinates(double,double)` | 16 | Exported Function
`public: __thiscall core::GeoRect::GeoRect(class core::GeoRect const &)` | 18 | Exported Function
`public: __thiscall core::GeoRect::GeoRect(class core::GeoCoordinates const *,class core::GeoCoordinates const *)` | 20 | Exported Function
`public: __thiscall core::GeoCoordinates::GeoCoordinates(void)` | 17 | Exported Function


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


