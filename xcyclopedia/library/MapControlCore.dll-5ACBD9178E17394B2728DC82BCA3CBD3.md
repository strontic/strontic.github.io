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

Function Name | Ordinal | Type
-- | -- | --
`public: static long __cdecl ApiAccessCheck::RestrictedAPIAccessCheck(void)` | 220 | Exported Function
`public: static double __cdecl core::GeoCoordinates::GetMinLongitude(void)` | 155 | Exported Function
`public: static double __cdecl core::GeoCoordinates::GetMinLatitude(void)` | 154 | Exported Function
`public: static long __cdecl core::GeoRect::CalculateGeoRect(class std::vector<class core::GeoCoordinates * __ptr64,class std::allocator<class core::GeoCoordinates * __ptr64> > & __ptr64,class core::GeoRect * __ptr64)` | 79 | Exported Function
`public: static long __cdecl core::RouteManeuver::GetStringResource(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)` | 169 | Exported Function
`public: static long __cdecl core::RouteManeuver::FormatString(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,unsigned long,...)` | 88 | Exported Function
`public: static long __cdecl core::Route::Deserialize(class std::basic_istream<char,struct std::char_traits<char> > & __ptr64,class core::Route * __ptr64)` | 87 | Exported Function
`public: static double __cdecl core::GeoCoordinates::GetMaxLongitude(void)` | 153 | Exported Function
`public: static bool __cdecl MapsSettings::IsChinaVariant(void)` | 200 | Exported Function
`public: static bool __cdecl MapsSettings::GetEnableManeuverCondensing(void)` | 117 | Exported Function
`public: long __cdecl RouterAdapterCore::GetViolatedOptions(int * __ptr64) __ptr64` | 188 | Exported Function
`public: static bool __cdecl MapsSettings::IsOldChinaRegKeySet(void)` | 206 | Exported Function
`public: static double __cdecl core::GeoCoordinates::GetMaxLatitude(void)` | 152 | Exported Function
`public: static class core::GeoCoordinates const * __ptr64 __cdecl MapsSettings::GetDefaultCenterFromTimezone(void)` | 110 | Exported Function
`public: static bool __cdecl MapsSettings::IsWatermarkEnabled(void)` | 213 | Exported Function
`public: static long __cdecl MapsSettings::GetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 99 | Exported Function
`public: static long __cdecl MapsSettings::GetUserProfileLanguages(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 186 | Exported Function
`public: static long __cdecl MapsSettings::GetUserProfileLanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 184 | Exported Function
`public: static long __cdecl MapsSettings::GetUserPreferredUILanguage(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 183 | Exported Function
`public: static long __cdecl MapsSettings::GetUserProfileLanguages(struct HSTRING__ * __ptr64 * __ptr64)` | 185 | Exported Function
`public: static long __cdecl MapsSettings::SetKeyValidationStatus(int)` | 234 | Exported Function
`public: static long __cdecl MapsSettings::SetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const & __ptr64)` | 228 | Exported Function
`public: static long __cdecl MapsSettings::SetBingAuthenticationKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > const & __ptr64)` | 227 | Exported Function
`public: static long __cdecl MapsSettings::GetUserGeoRegionAsThreeLetterCode(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 182 | Exported Function
`public: static long __cdecl MapsSettings::GetKeyValidationStatus(int * __ptr64)` | 135 | Exported Function
`public: static long __cdecl MapsSettings::GetDataAttribution(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 109 | Exported Function
`public: static long __cdecl MapsSettings::GetBingMapsKey(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 100 | Exported Function
`public: static long __cdecl MapsSettings::GetLimitNetworkUsage(bool * __ptr64)` | 143 | Exported Function
`public: static long __cdecl MapsSettings::GetUserGeoRegion(struct HSTRING__ * __ptr64 * __ptr64)` | 180 | Exported Function
`public: static long __cdecl MapsSettings::GetUserGeoRegion(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > * __ptr64)` | 181 | Exported Function
`public: static long __cdecl MapsSettings::GetLocaleMapConfiguration(struct ILocaleMapConfiguration * __ptr64 * __ptr64)` | 144 | Exported Function
`public: long __cdecl core::GeoRect::GetCenter(class core::GeoCoordinates * __ptr64)const __ptr64` | 105 | Exported Function
`public: long __cdecl core::GeoRect::GetBottomRight(class core::GeoCoordinates * __ptr64)const __ptr64` | 102 | Exported Function
`public: int __cdecl OperationAdapterCore::GetInstanceId(void)const __ptr64` | 130 | Exported Function
`public: long __cdecl core::GeoRect::GetTopLeft(class core::GeoCoordinates * __ptr64)const __ptr64` | 173 | Exported Function
`public: long __cdecl core::RouteManeuver::GetCurrentRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 108 | Exported Function
`public: long __cdecl core::Route::Serialize(class std::basic_ostream<char,struct std::char_traits<char> > & __ptr64)const __ptr64` | 221 | Exported Function
`public: long __cdecl core::Route::Initialize(class std::shared_ptr<class msnma::IRoute>) __ptr64` | 191 | Exported Function
`public: enum QueryStatus __cdecl QueryAdapterCore::GetStatus(void)const __ptr64` | 167 | Exported Function
`public: double __cdecl core::GeoRect::GetLeft(void)const __ptr64` | 138 | Exported Function
`public: double __cdecl core::GeoRect::GetBottom(void)const __ptr64` | 101 | Exported Function
`public: class std::shared_ptr<class msnma::IRoute> __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::GetBackingObject(void)const __ptr64` | 94 | Exported Function
`public: double __cdecl core::GeoRect::GetRight(void)const __ptr64` | 162 | Exported Function
`public: enum core::RouteManeuverType __cdecl core::RouteManeuver::GetManeuverType(void)const __ptr64` | 149 | Exported Function
`public: enum core::CompassHeading __cdecl core::RouteManeuver::GetHeading(void)const __ptr64` | 128 | Exported Function
`public: double __cdecl core::GeoRect::GetTop(void)const __ptr64` | 172 | Exported Function
`public: long __cdecl core::RouteManeuver::GetFreewayExitNumber(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 121 | Exported Function
`public: long __cdecl RouterAdapterCore::GetAlternateRouteCount(unsigned int * __ptr64) __ptr64` | 90 | Exported Function
`public: long __cdecl RouterAdapterCore::GetAlternateRoute(unsigned int,class core::Route * __ptr64) __ptr64` | 89 | Exported Function
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > && __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,struct engine::RouteOptions * __ptr64) __ptr64` | 80 | Exported Function
`public: long __cdecl RouterAdapterCore::GetAlternateRouteViolatedOption(unsigned int,int * __ptr64) __ptr64` | 91 | Exported Function
`public: long __cdecl RouterAdapterCore::GetRoute(class core::Route * __ptr64) __ptr64` | 163 | Exported Function
`public: long __cdecl RouterAdapterCore::GetProvider(enum engine::Provider * __ptr64) __ptr64` | 159 | Exported Function
`public: long __cdecl RouterAdapterCore::GetConnectivityType(enum engine::ConnectivityType * __ptr64) __ptr64` | 106 | Exported Function
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<struct engine::RoutePoint,class std::allocator<struct engine::RoutePoint> > && __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,unsigned int,__int64,struct engine::RouteOptions * __ptr64) __ptr64` | 81 | Exported Function
`public: long __cdecl core::RouteManeuver::GetStartCoordinates(class core::GeoCoordinates * __ptr64)const __ptr64` | 165 | Exported Function
`public: long __cdecl core::RouteManeuver::GetManeuverNotice(int * __ptr64)const __ptr64` | 148 | Exported Function
`public: long __cdecl core::RouteManeuver::GetInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 131 | Exported Function
`public: long __cdecl core::RouteManeuver::GetTargetRoadName(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 171 | Exported Function
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const & __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,struct engine::RouteOptions * __ptr64) __ptr64` | 82 | Exported Function
`public: long __cdecl RouterAdapterCore::CalculateRoute(class std::vector<class core::GeoCoordinates,class std::allocator<class core::GeoCoordinates> > const & __ptr64,enum engine::TravelMode,enum engine::RouteOptimization,unsigned long,__int64,struct engine::RouteOptions * __ptr64) __ptr64` | 83 | Exported Function
`public: long __cdecl OperationAdapterCore::GetErrorCode(void)const __ptr64` | 120 | Exported Function
`public: static long __cdecl MapsSettings::SetLimitNetworkUsage(bool)` | 236 | Exported Function
`public: virtual unsigned long __cdecl core::RouteLeg::GetManeuverCount(void)const __ptr64` | 147 | Exported Function
`public: virtual unsigned long __cdecl core::RouteLeg::GetLengthInMeters(void)const __ptr64` | 142 | Exported Function
`public: virtual unsigned long __cdecl core::RouteLeg::GetGeometryCoordinatesCount(void)const __ptr64` | 126 | Exported Function
`public: virtual unsigned long __cdecl RouterAdapterCore::GetResultSqmId(void)const __ptr64` | 161 | Exported Function
`public: virtual void __cdecl core::GeoCoordinates::SetLongitude(double) __ptr64` | 237 | Exported Function
`public: virtual void __cdecl core::GeoCoordinates::SetLatitude(double) __ptr64` | 235 | Exported Function
`public: virtual void __cdecl core::GeoCoordinates::SetAltitude(double) __ptr64` | 222 | Exported Function
`public: virtual unsigned long __cdecl core::RouteLeg::GetDurationWithoutTrafficInSeconds(void)const __ptr64` | 116 | Exported Function
`public: virtual unsigned long __cdecl core::Route::GetDurationWithoutTrafficInSeconds(void)const __ptr64` | 115 | Exported Function
`public: virtual unsigned long __cdecl core::Route::GetDurationInSeconds(void)const __ptr64` | 113 | Exported Function
`public: virtual long __cdecl UIThreadCore<struct IRouterUI>::GetGenerationNumber(void)const __ptr64` | 122 | Exported Function
`public: virtual unsigned long __cdecl core::Route::GetGeometryCoordinatesCount(void)const __ptr64` | 125 | Exported Function
`public: virtual unsigned long __cdecl core::RouteLeg::GetDurationInSeconds(void)const __ptr64` | 114 | Exported Function
`public: virtual unsigned long __cdecl core::Route::GetLengthInMeters(void)const __ptr64` | 141 | Exported Function
`public: virtual unsigned long __cdecl core::Route::GetLegCount(void)const __ptr64` | 140 | Exported Function
`public: virtual void __cdecl RouterAdapterCore::OnRouteDone(struct engine::RouteResult const & __ptr64) __ptr64` | 214 | Exported Function
`SetDebugThreadId` | 229 | Exported Function
`public: void __cdecl UIThreadCore<struct IRouterUI>::ProcessDispatchQueue(struct IRouterUI * __ptr64) __ptr64` | 217 | Exported Function
`public: void __cdecl RouterAdapterCore::Cancel(void) __ptr64` | 84 | Exported Function
`SetRenderThreadId` | 240 | Exported Function
`WaitForMosThreadToClose` | 245 | Exported Function
`SetUIThreadId` | 243 | Exported Function
`SetUIThreadChecksEnabled` | 242 | Exported Function
`public: void __cdecl core::GeoRect::CopyFrom(class core::GeoRect const & __ptr64) __ptr64` | 86 | Exported Function
`public: void __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::SetBackingObject(class Microsoft::ngeo::GeoCoordinates const & __ptr64) __ptr64` | 225 | Exported Function
`public: virtual void __cdecl UIThreadCore<struct IRouterUI>::Post(class TDispatchItem<struct IRouterUI> * __ptr64) __ptr64` | 216 | Exported Function
`public: virtual void __cdecl RouterAdapterCore::OnRouteProgress(unsigned long) __ptr64` | 215 | Exported Function
`public: void __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::SetBackingObject(class Microsoft::ngeo::GeoRect const & __ptr64) __ptr64` | 226 | Exported Function
`public: void __cdecl core::DoublePoint::``default constructor closure'(void) __ptr64` | 78 | Exported Function
`public: void __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::SetBackingObject(class std::shared_ptr<class msnma::IRoute> const & __ptr64) __ptr64` | 224 | Exported Function
`public: void __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::SetBackingObject(class std::shared_ptr<class msnma::IManeuver> const & __ptr64) __ptr64` | 223 | Exported Function
`public: unsigned long __cdecl core::RouteManeuver::GetManeuverWarningCount(void)const __ptr64` | 150 | Exported Function
`public: unsigned long __cdecl core::RouteManeuver::GetDistanceInMetersToNextManeuver(void)const __ptr64` | 112 | Exported Function
`public: unsigned long __cdecl core::RouteManeuver::GetDistanceInMetersFromPreviousManeuver(void)const __ptr64` | 111 | Exported Function
`public: unsigned long __cdecl core::RouteManeuver::GetTrafficCircleExitNumber(void)const __ptr64` | 174 | Exported Function
`public: virtual __cdecl core::GeoRect::~GeoRect(void) __ptr64` | 39 | Exported Function
`public: virtual __cdecl core::GeoCoordinates::~GeoCoordinates(void) __ptr64` | 38 | Exported Function
`public: unsigned long __cdecl OperationAdapterCore::GetProgress(void)const __ptr64` | 158 | Exported Function
`public: struct core::DoublePoint & __ptr64 __cdecl core::DoublePoint::operator=(struct core::DoublePoint const & __ptr64) __ptr64` | 55 | Exported Function
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultWalkingRouteOptions` | 250 | Exported Function
`public: static struct engine::RouteOptions const RouterAdapterCore::c_DefaultDrivingRouteOptions` | 249 | Exported Function
`public: static long __cdecl SuspendResumeDispatcher::RegisterListener(class ISuspendResumeListener * __ptr64,bool * __ptr64)` | 218 | Exported Function
`public: static void __cdecl MapsSettings::SetEnableManeuverCondensing(bool)` | 231 | Exported Function
`public: struct core::DoublePoint & __ptr64 __cdecl core::DoublePoint::operator=(struct core::DoublePoint && __ptr64) __ptr64` | 54 | Exported Function
`public: static void __cdecl SuspendResumeDispatcher::UnregisterListener(class ISuspendResumeListener * __ptr64)` | 244 | Exported Function
`public: static void __cdecl MosThread::WaitOnClose(void)` | 246 | Exported Function
`public: virtual __cdecl core::Route::~Route(void) __ptr64` | 42 | Exported Function
`public: virtual long __cdecl core::Route::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates * __ptr64)const __ptr64` | 123 | Exported Function
`public: virtual long __cdecl core::Route::GetBoundingBox(class core::GeoRect * __ptr64)const __ptr64` | 103 | Exported Function
`public: virtual enum msnma::IRoute::TrafficCongestionType __cdecl core::RouteLeg::GetTrafficCongestion(void)const __ptr64` | 177 | Exported Function
`public: virtual long __cdecl core::Route::GetLeg(unsigned long,class core::RouteLeg * __ptr64)const __ptr64` | 139 | Exported Function
`public: virtual long __cdecl core::RouteLeg::GetManeuver(unsigned long,class core::RouteManeuver * __ptr64)const __ptr64` | 146 | Exported Function
`public: virtual long __cdecl core::RouteLeg::GetGeometryCoordinates(unsigned long,class core::GeoCoordinates * __ptr64)const __ptr64` | 124 | Exported Function
`public: virtual long __cdecl core::RouteLeg::GetBoundingBox(class core::GeoRect * __ptr64)const __ptr64` | 104 | Exported Function
`public: virtual enum msnma::IRoute::TrafficCongestionType __cdecl core::Route::GetTrafficCongestion(void)const __ptr64` | 176 | Exported Function
`public: virtual bool __cdecl core::GeoCoordinates::IsValid(void)const __ptr64` | 209 | Exported Function
`public: virtual __cdecl core::RouteManeuver::~RouteManeuver(void) __ptr64` | 44 | Exported Function
`public: virtual __cdecl core::RouteLeg::~RouteLeg(void) __ptr64` | 43 | Exported Function
`public: virtual bool __cdecl core::GeoRect::IsValid(void)const __ptr64` | 210 | Exported Function
`public: virtual double __cdecl core::GeoCoordinates::GetLongitude(void)const __ptr64` | 145 | Exported Function
`public: virtual double __cdecl core::GeoCoordinates::GetLatitude(void)const __ptr64` | 136 | Exported Function
`public: virtual double __cdecl core::GeoCoordinates::GetAltitude(void)const __ptr64` | 92 | Exported Function
`protected: __cdecl OperationAdapterCore::OperationAdapterCore(void) __ptr64` | 22 | Exported Function
`private: static enum core::CompassHeading __cdecl core::RouteManeuver::GetSnappedCompassHeading(unsigned long)` | 164 | Exported Function
`private: long __cdecl core::RouteManeuver::InitializeInstructionText(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 195 | Exported Function
`protected: __cdecl QueryAdapterCore::QueryAdapterCore(void) __ptr64` | 24 | Exported Function
`protected: bool __cdecl UIThreadCore<struct IRouterUI>::IsDispatchEnabled(void) __ptr64` | 204 | Exported Function
`protected: __cdecl UIThreadCore<struct IRouterUI>::UIThreadCore<struct IRouterUI>(void) __ptr64` | 13 | Exported Function
`protected: __cdecl RouterAdapterCore::RouterAdapterCore(void) __ptr64` | 32 | Exported Function
`private: long __cdecl core::RouteManeuver::Initialize(class std::vector<class std::shared_ptr<class msnma::IManeuver>,class std::allocator<class std::shared_ptr<class msnma::IManeuver> > > const & __ptr64,int) __ptr64` | 193 | Exported Function
`private: long __cdecl core::RouteManeuver::GetTakeFerryInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 170 | Exported Function
`private: long __cdecl core::RouteManeuver::GetStopoverInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 168 | Exported Function
`private: long __cdecl core::RouteManeuver::GetStartInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 166 | Exported Function
`private: long __cdecl core::RouteManeuver::GetTrafficCircleInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 175 | Exported Function
`private: long __cdecl core::RouteManeuver::GetUturnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 187 | Exported Function
`private: long __cdecl core::RouteManeuver::GetUndefinedInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 179 | Exported Function
`private: long __cdecl core::RouteManeuver::GetTurnInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 178 | Exported Function
`protected: class Microsoft::ngeo::GeoCoordinates & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void) __ptr64` | 95 | Exported Function
`protected: virtual void __cdecl QueryAdapterCore::SetProgress(unsigned long) __ptr64` | 239 | Exported Function
`protected: virtual void __cdecl OperationAdapterCore::SetProgress(unsigned long) __ptr64` | 238 | Exported Function
`protected: virtual unsigned long __cdecl OperationAdapterCore::GetResultSqmId(void)const __ptr64` | 160 | Exported Function
`protected: void __cdecl OperationAdapterCore::ResetProgress(void) __ptr64` | 219 | Exported Function
`protected: void __cdecl QueryAdapterCore::SetStatus(enum QueryStatus) __ptr64` | 241 | Exported Function
`protected: void __cdecl OperationAdapterCore::SetInstanceId(int) __ptr64` | 233 | Exported Function
`protected: void __cdecl OperationAdapterCore::SetErrorCode(long) __ptr64` | 232 | Exported Function
`protected: virtual __cdecl UIThreadCore<struct IRouterUI>::~UIThreadCore<struct IRouterUI>(void) __ptr64` | 37 | Exported Function
`protected: long __cdecl UIThreadCore<struct IRouterUI>::IncrementGeneration(void) __ptr64` | 189 | Exported Function
`protected: long __cdecl RouterAdapterCore::_CoreInitialize(int,class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >) __ptr64` | 247 | Exported Function
`protected: class Microsoft::ngeo::GeoRect & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void) __ptr64` | 97 | Exported Function
`protected: long __cdecl UIThreadCore<struct IRouterUI>::Initialize(class std::unique_ptr<struct IThreadSignal,struct destroy_delete<struct IThreadSignal> >) __ptr64` | 190 | Exported Function
`protected: virtual __cdecl RouterAdapterCore::~RouterAdapterCore(void) __ptr64` | 45 | Exported Function
`protected: virtual __cdecl QueryAdapterCore::~QueryAdapterCore(void) __ptr64` | 41 | Exported Function
`protected: virtual __cdecl OperationAdapterCore::~OperationAdapterCore(void) __ptr64` | 40 | Exported Function
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
`private: long __cdecl core::RouteManeuver::GetGoStraightInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 127 | Exported Function
`private: long __cdecl core::RouteManeuver::GetEnterFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 119 | Exported Function
`private: long __cdecl core::RouteManeuver::GetEndInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 118 | Exported Function
`private: long __cdecl core::RouteManeuver::GetInstructionTextFromBacking(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 132 | Exported Function
`private: long __cdecl core::RouteManeuver::GetLeaveFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 137 | Exported Function
`private: long __cdecl core::RouteManeuver::GetInstructionWithTargetAndReplacement(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 134 | Exported Function
`private: long __cdecl core::RouteManeuver::GetInstructionWithTarget(unsigned long,class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 133 | Exported Function
`private: long __cdecl core::RouteManeuver::GetContinueFreewayInstruction(class std::basic_string<unsigned short,struct std::char_traits<unsigned short>,class std::allocator<unsigned short> > & __ptr64)const __ptr64` | 107 | Exported Function
`private: long __cdecl core::Route::InitializeLegs(void) __ptr64` | 196 | Exported Function
`private: bool __cdecl core::RouteLeg::IsValid(void)const __ptr64` | 212 | Exported Function
`IsUIThread` | 208 | Exported Function
`private: long __cdecl core::RouteLeg::Initialize(class std::shared_ptr<class msnma::IRoute>,unsigned long) __ptr64` | 192 | Exported Function
`private: long __cdecl core::RouteLeg::InitializeManeuvers(void) __ptr64` | 198 | Exported Function
`private: long __cdecl core::RouteLeg::InitializeManeuverCondensingContexts(bool) __ptr64` | 197 | Exported Function
`private: long __cdecl core::RouteLeg::InitializeGeometryCoordinates(void) __ptr64` | 194 | Exported Function
`protected: void __cdecl RouterAdapterCore::_CoreUninitialize(void) __ptr64` | 248 | Exported Function
`public: bool __cdecl core::Route::IsValid(void)const __ptr64` | 211 | Exported Function
`public: bool __cdecl core::Route::IsDeserialized(void)const __ptr64` | 203 | Exported Function
`public: bool __cdecl core::GeoRect::IsDegenerate(void)const __ptr64` | 202 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> && __ptr64) __ptr64` | 50 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> const & __ptr64) __ptr64` | 53 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoRect> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::operator=(class core::BackedType<class Microsoft::ngeo::GeoRect> && __ptr64) __ptr64` | 52 | Exported Function
`public: class core::BackedType<class Microsoft::ngeo::GeoCoordinates> & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::operator=(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const & __ptr64) __ptr64` | 51 | Exported Function
`public: bool __cdecl core::GeoRect::Intersects(class core::GeoRect const * __ptr64) __ptr64` | 199 | Exported Function
`public: bool __cdecl core::DoublePoint::operator!=(struct core::DoublePoint const & __ptr64)const __ptr64` | 65 | Exported Function
`public: __cdecl QueryAdapterCore::QueryAdapterCore(class QueryAdapterCore const & __ptr64) __ptr64` | 25 | Exported Function
`public: __cdecl OperationAdapterCore::OperationAdapterCore(class OperationAdapterCore const & __ptr64) __ptr64` | 23 | Exported Function
`public: bool __cdecl core::DoublePoint::operator==(struct core::DoublePoint const & __ptr64)const __ptr64` | 63 | Exported Function
`public: bool __cdecl core::GeoRect::Contains(class core::GeoCoordinates const * __ptr64) __ptr64` | 85 | Exported Function
`public: bool __cdecl core::GeoCoordinates::operator==(class core::GeoCoordinates const & __ptr64)const __ptr64` | 64 | Exported Function
`public: bool __cdecl core::GeoCoordinates::operator!=(class core::GeoCoordinates const & __ptr64)const __ptr64` | 66 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > && __ptr64) __ptr64` | 46 | Exported Function
`public: class Microsoft::ngeo::GeoRect const & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::GetBackingObjectRef(void)const __ptr64` | 98 | Exported Function
`public: class Microsoft::ngeo::GeoCoordinates const & __ptr64 __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::GetBackingObjectRef(void)const __ptr64` | 96 | Exported Function
`public: class core::RouteManeuver & __ptr64 __cdecl core::RouteManeuver::operator=(class core::RouteManeuver const & __ptr64) __ptr64` | 62 | Exported Function
`public: class msnma::IItineraryWarning const & __ptr64 __cdecl core::RouteManeuver::GetManeuverWarnings(unsigned long)const __ptr64` | 151 | Exported Function
`public: class std::shared_ptr<class msnma::IManeuver> __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::GetBackingObject(void)const __ptr64` | 93 | Exported Function
`public: class QueryAdapterCore & __ptr64 __cdecl QueryAdapterCore::operator=(class QueryAdapterCore const & __ptr64) __ptr64` | 59 | Exported Function
`public: class OperationAdapterCore & __ptr64 __cdecl OperationAdapterCore::operator=(class OperationAdapterCore const & __ptr64) __ptr64` | 58 | Exported Function
`public: class core::RouteLeg & __ptr64 __cdecl core::RouteLeg::operator=(class core::RouteLeg const & __ptr64) __ptr64` | 61 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const & __ptr64) __ptr64` | 49 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IRoute> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > && __ptr64) __ptr64` | 48 | Exported Function
`public: class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > & __ptr64 __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::operator=(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const & __ptr64) __ptr64` | 47 | Exported Function
`public: class core::GeoCoordinates & __ptr64 __cdecl core::GeoCoordinates::operator=(class core::GeoCoordinates const & __ptr64) __ptr64` | 56 | Exported Function
`public: class core::Route & __ptr64 __cdecl core::Route::operator=(class core::Route const & __ptr64) __ptr64` | 60 | Exported Function
`public: class core::GeoRect __cdecl core::GeoRect::GetInflatedGeoRect(void)const __ptr64` | 129 | Exported Function
`public: class core::GeoRect & __ptr64 __cdecl core::GeoRect::operator=(class core::GeoRect const & __ptr64) __ptr64` | 57 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > const & __ptr64) __ptr64` | 2 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(class core::BackedType<class std::shared_ptr<class msnma::IManeuver> > && __ptr64) __ptr64` | 1 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::~BackedType<class Microsoft::ngeo::GeoRect>(void) __ptr64` | 36 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::BackedType<class std::shared_ptr<class msnma::IManeuver> >(void) __ptr64` | 3 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > const & __ptr64) __ptr64` | 5 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(class core::BackedType<class std::shared_ptr<class msnma::IRoute> > && __ptr64) __ptr64` | 4 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IManeuver> >::~BackedType<class std::shared_ptr<class msnma::IManeuver> >(void) __ptr64` | 33 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(void) __ptr64` | 12 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> const & __ptr64) __ptr64` | 8 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(class core::BackedType<class Microsoft::ngeo::GeoCoordinates> && __ptr64) __ptr64` | 7 | Exported Function
`protected: void __cdecl UIThreadCore<struct IRouterUI>::SetDispatchEnabled(bool) __ptr64` | 230 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::BackedType<class Microsoft::ngeo::GeoCoordinates>(void) __ptr64` | 9 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> const & __ptr64) __ptr64` | 11 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoRect>::BackedType<class Microsoft::ngeo::GeoRect>(class core::BackedType<class Microsoft::ngeo::GeoRect> && __ptr64) __ptr64` | 10 | Exported Function
`public: __cdecl core::BackedType<class Microsoft::ngeo::GeoCoordinates>::~BackedType<class Microsoft::ngeo::GeoCoordinates>(void) __ptr64` | 35 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::BackedType<class std::shared_ptr<class msnma::IRoute> >(void) __ptr64` | 6 | Exported Function
`public: __cdecl core::Route::Route(void) __ptr64` | 27 | Exported Function
`public: __cdecl core::Route::Route(class core::Route const & __ptr64) __ptr64` | 26 | Exported Function
`public: __cdecl core::GeoRect::GeoRect(void) __ptr64` | 21 | Exported Function
`public: __cdecl core::RouteLeg::RouteLeg(class core::RouteLeg const & __ptr64) __ptr64` | 28 | Exported Function
`public: __cdecl core::RouteManeuver::RouteManeuver(void) __ptr64` | 31 | Exported Function
`public: __cdecl core::RouteManeuver::RouteManeuver(class core::RouteManeuver const & __ptr64) __ptr64` | 30 | Exported Function
`public: __cdecl core::RouteLeg::RouteLeg(void) __ptr64` | 29 | Exported Function
`public: __cdecl core::GeoRect::GeoRect(double,double,double,double) __ptr64` | 19 | Exported Function
`public: __cdecl core::GeoCoordinates::GeoCoordinates(class core::GeoCoordinates const & __ptr64) __ptr64` | 15 | Exported Function
`public: __cdecl core::DoublePoint::DoublePoint(double,double) __ptr64` | 14 | Exported Function
`public: __cdecl core::BackedType<class std::shared_ptr<class msnma::IRoute> >::~BackedType<class std::shared_ptr<class msnma::IRoute> >(void) __ptr64` | 34 | Exported Function
`public: __cdecl core::GeoCoordinates::GeoCoordinates(double,double) __ptr64` | 16 | Exported Function
`public: __cdecl core::GeoRect::GeoRect(class core::GeoRect const & __ptr64) __ptr64` | 18 | Exported Function
`public: __cdecl core::GeoRect::GeoRect(class core::GeoCoordinates const * __ptr64,class core::GeoCoordinates const * __ptr64) __ptr64` | 20 | Exported Function
`public: __cdecl core::GeoCoordinates::GeoCoordinates(void) __ptr64` | 17 | Exported Function


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


