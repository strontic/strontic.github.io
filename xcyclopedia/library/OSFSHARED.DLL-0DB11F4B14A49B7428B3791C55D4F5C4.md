---
title: OSFSHARED.DLL | Microsoft Office component
excerpt: What is OSFSHARED.DLL?
---

# OSFSHARED.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\OSFSHARED.DLL`
* Description: Microsoft Office component

## Hashes

Type | Hash
-- | --
MD5 | `0DB11F4B14A49B7428B3791C55D4F5C4`
SHA1 | `258DFF4B82B67081C3A9FAF77B669F890D69F5CB`
SHA256 | `285051885D62AF5598DDD3D5BB3C2D8FCDE0136E40C68D546D9B648D33448DD7`
SHA384 | `C1DCA1FDB3F6C43A6B6BAF20E12AACBC468B226395B19176111EBAE657A1AC615D09110ED86260591A4DD1270A8CB39E`
SHA512 | `DEABB342A14DFB466B11287A0CAA25F079B35F03B565D2BAD69FE62D4262902DA2E9CE8D6A26F1846EA0A6C1D37F04C3FF916555ECAFE2ED30C6D0193DB7D077`
SSDEEP | `12288:N8LHj1iNUXP464rdWCAYcRbJcXZ0o7ZsvetueSVHN1JjW:NuJvXP94rdWCAYcR8ZKnZjW`
IMP | `FBA7950C1377EEB6B33D7EC770ED8145`
PESHA1 | `442FAE04EB574F2B0353E3C59B5DBB2A2F2846F7`
PE256 | `0542429ECD2F20B0F959834357B42B5E6ABD6D93BC7775A39AB1E882F44F7C98`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static class Math::TUnits<float,struct Math::TUnitsRatioTag<struct Math::DevicePixels,struct Math::Inches> > __stdcall Osf::DpiUtils::GetPixelsPerInch(struct HWND__ *)` | 52 | Exported Function
`public: static int __stdcall Osf::DpiUtils::ScaleForHwnd(struct HWND__ *,int)` | 66 | Exported Function
`public: static bool __stdcall Osf::DpiUtils::IsDynamicDpiEnabled(void)` | 59 | Exported Function
`public: static class Math::TUnits<float,struct Math::TUnitsRatioTag<struct Math::DevicePixels,struct Math::DeviceIndependentPixels> > __stdcall Osf::DpiUtils::GetScaleFactorForHwnd(struct HWND__ *)` | 54 | Exported Function
`public: static long __stdcall Osf::ContextMenuExtensionPoint::Create(class Mso::TCntPtr<class Osf::ContextMenuExtensionPoint> &)` | 6 | Exported Function
`public: static long __stdcall Osf::CustomPaneExtensionPoint::Create(class Mso::TCntPtr<class Osf::CustomPaneExtensionPoint> &)` | 7 | Exported Function
`public: static long __stdcall Osf::BackgroundTaskExtensionPoint::Create(class Mso::TCntPtr<class Osf::BackgroundTaskExtensionPoint> &)` | 4 | Exported Function
`public: static long __stdcall Osf::ButtonExtensionElement::Create(struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::ButtonExtensionElement> &)` | 5 | Exported Function
`long __stdcall Osf::SuppressFlighting(enum Osf::OsfFlightingId)` | 69 | Exported Function
`long __stdcall Osf::HrReadCustomFunctionFromCache(struct tagVARIANT *)` | 56 | Exported Function
`long __stdcall Osf::HrWriteCustomFunctionToCache(wchar_t const *,wchar_t const *)` | 57 | Exported Function
`long __stdcall Osf::FillMarketplacesFromSolutionRef(struct IOsfSolutionReference const *,struct OsfMarketplace &,struct OsfMarketplace &)` | 45 | Exported Function
`long __stdcall Osf::GetAppCommandNoUIControlWindow(bool,struct HWND__ * *)` | 46 | Exported Function
`long __stdcall Osf::ResetSolutionReferenceTrustFlags(struct IOsfSolutionReference *)` | 65 | Exported Function
`long __stdcall Osf::ShutdownOsfAddinMiniCacheReader(void)` | 67 | Exported Function
`long __stdcall Osf::ManifestParser::ParseIdHelper(enum OsfStoreType,wchar_t const *,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > &)` | 64 | Exported Function
`long __stdcall Osf::MsoUtils::GetUNCPath(wchar_t const *,class ATL::CComBSTR &)` | 55 | Exported Function
`public: static long __stdcall Osf::DetectedEntityExtensionPoint::Create(class Mso::TCntPtr<class Osf::DetectedEntityExtensionPoint> &)` | 8 | Exported Function
`public: static void __stdcall Osf::DpiUtils::Initialize(enum OsfHost)` | 58 | Exported Function
`void __cdecl Osf::LogOsfRuntimeEvent(wchar_t const *,enum Mso::Logging::Severity,wchar_t const *,...)` | 61 | Exported Function
`public: static long __stdcall Osf::OsfSolutionHostExtender::Create(wchar_t const *,enum Osf::OfficeFormFactor::Enum,struct Osf::IWebAddInStringCollection *,class Mso::TCntPtr<class Osf::OsfSolutionHostExtender> &)` | 18 | Exported Function
`public: static long __stdcall Osf::WebAddInStringCollection::Create(class Mso::TCntPtr<class Osf::WebAddInStringCollection> &)` | 19 | Exported Function
`void __stdcall Osf::ShutdownOsfRuntimeLogging(void)` | 68 | Exported Function
`wchar_t const * __stdcall Osf::GetCompatExtensionIdForHost(enum OsfHost)` | 47 | Exported Function
`void __stdcall Osf::DeleteOsfRibbonExtensibilityManager(void)` | 42 | Exported Function
`void __stdcall Osf::LogOsfRuntimeEvent(enum Mso::Logging::Severity,wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 62 | Exported Function
`public: static long __stdcall Osf::OsfAppCommandAction::Create(class Mso::TCntPtr<class Osf::OsfAppCommandAction> &)` | 17 | Exported Function
`public: static long __stdcall Osf::GraphicalExtensionElement::Create(enum Osf::ExtensionElementType::Enum,struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::GraphicalExtensionElement> &)` | 11 | Exported Function
`public: static long __stdcall Osf::LaunchEventExtensionElement::Create(struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::LaunchEventExtensionElement> &)` | 12 | Exported Function
`public: static long __stdcall Osf::EventExtensionElement::Create(struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::EventExtensionElement> &)` | 9 | Exported Function
`public: static long __stdcall Osf::ExtensionPoint::Create(enum Osf::ExtensionPointType::Enum,class Mso::TCntPtr<class Osf::ExtensionPoint> &)` | 10 | Exported Function
`public: static long __stdcall Osf::ModuleExtensionPoint::Create(class Mso::TCntPtr<class Osf::ModuleExtensionPoint> &)` | 15 | Exported Function
`public: static long __stdcall Osf::NavNodeExtensionElement::Create(struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::NavNodeExtensionElement> &)` | 16 | Exported Function
`public: static long __stdcall Osf::LaunchEventsExtensionPoint::Create(class Mso::TCntPtr<class Osf::LaunchEventsExtensionPoint> &)` | 13 | Exported Function
`public: static long __stdcall Osf::MenuExtensionElement::Create(struct Osf::IExtensionPoint *,class Mso::TCntPtr<class Osf::MenuExtensionElement> &)` | 14 | Exported Function
`class Mso::TCntPtr<struct Osf::IOsfRibbonExtensibilityManager> __stdcall Osf::CreateOsfRibbonExtensibilityManagerEx(struct Osf::IUIExtensibilityRegistry *,enum OsfHost,struct Osf::IOsfSolutionAppCommandCallback *,bool,struct Osf::IOsfIdentityManager *)` | 30 | Exported Function
`class Mso::TCntPtr<struct Osf::IOsfRibbonExtensibilityManager> __stdcall Osf::GetRibbonExtensibilityManager(void)` | 53 | Exported Function
`class Mso::TCntPtr<struct Osf::IOsfRibbonExtensibilityManager> __stdcall Osf::CreateOsfRibbonExtensibilityManager(class NetUI::CntPtrTo<struct OfficeSpace::IOfficeSpaceEx>,enum OsfHost,struct Osf::IOsfSolutionAppCommandCallback *)` | 29 | Exported Function
`class Mso::TCntPtr<struct Osf::IOsfRibbonExtensibilityManager> __stdcall Osf::CreateOsfRibbonExtensibilityManager(struct Osf::IUIExtensibilityRegistry *,enum OsfHost,struct Osf::IOsfSolutionAppCommandCallback *)` | 28 | Exported Function
`enum Osf::ExtensionPointType::Enum __stdcall Osf::ExtensionPointType::ValFromName(wchar_t const *)` | 70 | Exported Function
`enum Osf::MsoUtils::MsoAddinXStatus __stdcall Osf::MsoUtils::GetMsoAddinXStatus(class std::vector<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> >,class std::allocator<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > > const &)` | 51 | Exported Function
`class Mso::TCntPtr<struct SDX::SDK::IExtensionIdentity> __stdcall SDX::SDK::CreateExtensionIdentity(wchar_t const *,struct AppVersion const &,wchar_t const *,wchar_t const *)` | 26 | Exported Function
`class std::shared_ptr<struct SDX::SDK::IExtensionLaunchProperties> __stdcall SDX::MSO::CreateLaunchProperties(void)` | 27 | Exported Function
`bool __stdcall Osf::MsoUtils::OsfIsCatalogEqual(wchar_t const *,wchar_t const *,enum OsfStoreType)` | 63 | Exported Function
`bool __stdcall Osf::CompareSolutionReferences(struct IOsfSolutionReference const *,struct IOsfSolutionReference const *,bool,bool &)` | 2 | Exported Function
`bool __stdcall Osf::FOsfRuntimeLoggingUserEnabled(void)` | 44 | Exported Function
`bool __stdcall Osf::CompareSolutionReferences(struct IOsfSolutionReference const *,struct IOsfExtensionPersistence const *)` | 3 | Exported Function
`bool __stdcall Osf::CompareSolutionReferences(struct IOsfSolutionReference const *,struct IOsfSolutionReference const *)` | 1 | Exported Function
`bool __stdcall Osf::GetFlightingStatusForFlag(enum Osf::OsfFlightingId,int,enum OsfHost)` | 50 | Exported Function
`bool __stdcall Osf::IsStorageCompatibleWithOsfSolutionReference(struct IOsfSolutionReference const *,struct IOsfExtensionPersistence const *)` | 60 | Exported Function
`bool __stdcall Osf::GetFlightingStatus(enum Osf::OsfFlightingId,enum OsfHost)` | 48 | Exported Function
`bool __stdcall Osf::GetFlightingStatusEx(enum Osf::OsfFlightingId)` | 49 | Exported Function
`long __stdcall Osf::CreateAppCommandNoUIControlContainer(struct IOsfAppManager *,struct IOsfExtensionPersistence *,struct IOsfControlContainer * *)` | 20 | Exported Function
`long __stdcall Osf::CreateWebAddInOptionalProperties(struct IWebAddInReferenceInstance const &,class Mso::TCntPtr<struct IWebAddInOptionalProperties> &)` | 37 | Exported Function
`long __stdcall Osf::CreateWebAddInReferenceInstance(enum OsfHost,enum Osf::OfficeFormFactor::Enum,wchar_t const *,wchar_t const *,struct IOsfSolutionReference &,class Mso::TCntPtr<struct IWebAddInReferenceInstance> &,struct IWebAddInOptionalProperties const *)` | 39 | Exported Function
`long __stdcall Osf::CreateWebAddInInstance(struct IWebAddInReferenceInstance const *,struct IOsfSolutionManifest &,class Mso::TCntPtr<struct IWebAddInInstance> &)` | 34 | Exported Function
`long __stdcall Osf::CreateWebAddInOptionalProperties(class Mso::TCntPtr<struct IWebAddInOptionalProperties> &)` | 36 | Exported Function
`long __stdcall Osf::CreateWebAddInSummaryInstance(struct IWebAddInReferenceInstance const *,struct IOsfSolutionSummary &,class Mso::TCntPtr<struct IWebAddInSummaryInstance> &)` | 40 | Exported Function
`long __stdcall Osf::DestroyAppCommandNoUIWindow(void)` | 43 | Exported Function
`long __stdcall Osf::CreateWebAddInReferenceInstance(struct IWebAddInReferenceInstance const *,struct IOsfSolutionReference &,class Mso::TCntPtr<struct IWebAddInReferenceInstance> &)` | 38 | Exported Function
`long __stdcall Osf::CreateWebAddInSummaryInstance(enum OsfHost,enum Osf::OfficeFormFactor::Enum,wchar_t const *,wchar_t const *,struct IOsfSolutionSummary &,class Mso::TCntPtr<struct IWebAddInSummaryInstance> &,struct IWebAddInOptionalProperties const *)` | 41 | Exported Function
`long __stdcall Osf::CreateWebAddInInstance(enum OsfHost,enum Osf::OfficeFormFactor::Enum,wchar_t const *,wchar_t const *,struct IOsfSolutionManifest &,class Mso::TCntPtr<struct IWebAddInInstance> &,struct IWebAddInOptionalProperties const *)` | 35 | Exported Function
`long __stdcall Osf::CreateAppCommandSolutionRef(wchar_t const *,struct AppVersion const &,enum OsfStoreType,wchar_t const *,wchar_t const *,wchar_t const *,struct Osf::IOsfAppCommandReference *,struct IOsfSolutionReference * *)` | 23 | Exported Function
`long __stdcall Osf::CreateAppCommandSource(struct Osf::IExtensionElement *,wchar_t const *,unsigned long,class Mso::TCntPtr<struct Osf::IOsfAppCommandSource> &)` | 24 | Exported Function
`long __stdcall Osf::CreateAppCommandReference(struct Osf::IExtensionElement *,class Mso::TCntPtr<struct Osf::IOsfAppCommandReference> &)` | 21 | Exported Function
`long __stdcall Osf::CreateAppCommandReference(struct Osf::IOsfAppCommandSource *,enum Osf::CommandActionType::Enum,enum Osf::AppCommandArgument::Enum,wchar_t const *,enum Osf::AppCommandArgument::Enum,wchar_t const *,class Mso::TCntPtr<struct Osf::IOsfAppCommandReference> &)` | 22 | Exported Function
`long __stdcall Osf::CreateSolutionRefFromMarketplaces(struct OsfMarketplace const &,struct OsfMarketplace const &,bool,struct IOsfSolutionReference * *)` | 32 | Exported Function
`long __stdcall Osf::CreateSolutionRefFromPersistence(struct IOsfExtensionPersistence const *,bool,struct IOsfSolutionReference * *)` | 33 | Exported Function
`long __stdcall Osf::CreateEmptyAppCommandReference(class Mso::TCntPtr<struct Osf::IOsfAppCommandReference> &)` | 25 | Exported Function
`long __stdcall Osf::CreateSolutionRef(wchar_t const *,struct AppVersion const &,enum OsfStoreType,wchar_t const *,wchar_t const *,wchar_t const *,bool,struct IOsfSolutionReference * *)` | 31 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: osfshared.dll
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20470
* Product Version: 16.0.12527.20470
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/285051885d62af5598ddd3d5bb3c2d8fcde0136e40c68d546d9b648d33448dd7/detection/




MIT License. Copyright (c) 2020 Strontic.


