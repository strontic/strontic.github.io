---
title: BIPLAT.DLL | Microsoft Office BI Platform
excerpt: What is BIPLAT.DLL?
---

# BIPLAT.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\BIPLAT.DLL`
* Description: Microsoft Office BI Platform

## Hashes

Type | Hash
-- | --
MD5 | `BDE11FC9336F47E7F78AB08ED5CD581C`
SHA1 | `F2892FD21F93755DB0E73BEF66055C206B20812A`
SHA256 | `6F71053638EACBEFDF3115A640C1F13F5CF59307E7EEE3C155BF414C9DAA9FA3`
SHA384 | `BCF9DDEE27D9901BD4326D20ADAF9E51E01912AAC81A5C44BD09C09984ABC303EEFE234EE47B640C3FDF2770F8280134`
SHA512 | `268883452B2D220573C2052DC9C230E6117FFEF8F018DBDED9B03CCD7277E7EBBB5B39BC9BBE215DE190ED5DBBC7A85E3E8FB827EE87007A592D049C280AF94A`
SSDEEP | `6144:Q3fFrkx5THN81z2WXbPAkjY3umt714LIDCsM/5rtY3xcmaY1M8CYykqx:6Frkx5TNCX5mnsIAre3xURYBK`
IMP | `07279D2B197E6A6576BEEA0403F57C73`
PESHA1 | `8557303156FA0DD1515658964500051496D87585`
PE256 | `0FC6296C317CA06CC2D0FFF65147D64D06CD95A23545331C27D4F96D4B37D829`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: unsigned int __thiscall Mso::BI::Persistence::XmlReader::GetDepth(void)` | 43 | Exported Function
`public: virtual __thiscall Mso::BI::BIPlatActivity::~BIPlatActivity(void)` | 24 | Exported Function
`public: virtual long __stdcall Mso::BI::IVisualMoniker::QueryInterface(struct _GUID const &,void * *)` | 78 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __thiscall Mso::BI::Persistence::VersionTracker::GetVersion(void)` | 53 | Exported Function
`public: enum Mso::BI::Persistence::NodeType __thiscall Mso::BI::Persistence::XmlReader::GetNodeType(void)` | 51 | Exported Function
`public: unsigned int __thiscall Mso::BI::Persistence::VersionTracker::GetNamespaceVersion(void)const ` | 50 | Exported Function
`public: void __thiscall Mso::BI::Persistence::VersionTracker::EncounterFeature(wchar_t const *)` | 39 | Exported Function
`public: void __thiscall Mso::BI::Persistence::VersionTracker::RegisterFeature(wchar_t const *,enum Mso::BI::Persistence::XmlFeatureId,unsigned int)` | 80 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlReader::GetLocalName(wchar_t const * &,unsigned int &)` | 47 | Exported Function
`public: virtual void __thiscall Mso::BI::VisualCmdBase::Perform(class Ofc::IProgress &,class Ofc::CRollbackTransaction &,struct Ofc::CommandPerformParams const *)const ` | 64 | Exported Function
`public: void __thiscall Mso::BI::BIPlatActivity::OnFailure(class Mso::Functor<void __stdcall(class Mso::BI::BIPlatActivity &) noexcept> &&)` | 63 | Exported Function
`public: void __thiscall Mso::BI::Persistence::VersionTracker::Encounter(enum Mso::BI::Persistence::XmlFeatureId,unsigned int)` | 38 | Exported Function
`public: __thiscall Mso::BI::Persistence::XmlWriter::~XmlWriter(void)` | 25 | Exported Function
`public: bool __thiscall Mso::BI::Persistence::XmlReader::IsEmptyElement(void)` | 57 | Exported Function
`public: bool __thiscall Mso::BI::Persistence::XmlReader::MoveToFirstAttribute(void)` | 61 | Exported Function
`public: __thiscall Mso::BI::Persistence::XmlSchemaValidation::ElementValidation::ElementValidation(struct Mso::BI::Persistence::XmlSchemaElementInfo const &)` | 18 | Exported Function
`public: __thiscall Mso::BI::Persistence::XmlSchemaValidation::XmlSchemaValidation(class Mso::BI::Persistence::XmlSchema const &)` | 22 | Exported Function
`public: __thiscall Mso::BI::Persistence::XmlWriter::XmlWriter(struct ISequentialStream &,struct Mso::BI::Persistence::IFeatureVersionProvider &)` | 23 | Exported Function
`public: bool __thiscall Mso::BI::VisualCmdFactory::TryReadCommandListXml(class Ofc::IContentMoniker &,struct IStream &,class Ofc::TCntPtr<class Ofc::CommandList> &)` | 84 | Exported Function
`public: bool __thiscall Mso::BI::VisualCmdFactory::TryReadCommandXml(class Ofc::IContentMoniker &,struct IStream &,class Ofc::TCntPtr<class Ofc::Command const > &)` | 85 | Exported Function
`public: class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __thiscall Mso::BI::Persistence::VersionTracker::GetFeatures(void)` | 44 | Exported Function
`public: bool __thiscall Mso::BI::Persistence::XmlReader::MoveToNextAttribute(void)` | 62 | Exported Function
`public: bool __thiscall Mso::BI::Persistence::XmlReader::Read(enum Mso::BI::Persistence::NodeType &)` | 79 | Exported Function
`public: bool __thiscall Mso::BI::Persistence::XmlSchemaValidation::VerifyElement(enum Mso::BI::Persistence::XmlNamespaceId,enum Mso::BI::Persistence::XmlElementId)` | 86 | Exported Function
`void __stdcall BIPlatNotReachedTag(int)` | 29 | Exported Function
`void __stdcall BIPlatThrowLogicSzTag(char const *,int)` | 30 | Exported Function
`void __stdcall FailedBIPlatAssert(int)` | 40 | Exported Function
`struct Mso::BI::Color __stdcall Mso::BI::GetBiColorFromThemeInfo(class Art::ThemeInfo const *)` | 42 | Exported Function
`struct Mso::Telemetry::TelemetryNamespace const & __stdcall Office::BIPlat::GetNamespace(void)` | 48 | Exported Function
`void __stdcall BIPlatNotReachedSzTag(char const *,int)` | 28 | Exported Function
`void __stdcall Mso::BI::Persistence::SendTraceTag(unsigned int,enum Mso::Logging::Category,enum Mso::Logging::Severity,wchar_t const *)` | 81 | Exported Function
`void __stdcall Mso::BI::SerializeUniformProperties(struct Mso::BI::IUniformObject &,struct Mso::Json::IJsonWriter &)` | 82 | Exported Function
`void __stdcall Mso::BI::TransferUniformProperties(struct Mso::BI::IUniformObject &,struct Mso::BI::IUniformObject &,void (__stdcall*)(struct Mso::BI::IUniformObject &,struct Mso::BI::IUniformObject &))` | 83 | Exported Function
`void __stdcall FailedBIPlatAssertSz(char const *,int)` | 41 | Exported Function
`void __stdcall Mso::BI::AddErrorToBIPlatErrorData(long,unsigned long)` | 26 | Exported Function
`void __stdcall Mso::BI::AddErrorToBIPlatErrorData(unsigned long)` | 27 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteAttributeString(wchar_t const *,wchar_t const *)` | 89 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteAttributeString(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 88 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteEndDocument(void)` | 92 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlReader::GetNamespace(wchar_t const * &,unsigned int &)` | 49 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlReader::MoveToElement(void)` | 60 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlSchemaValidation::VerifyRequirements(void)` | 87 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteStartElement(wchar_t const *,wchar_t const *,wchar_t const *)` | 95 | Exported Function
`public: void __thiscall Mso::BI::VisualCmdFactory::WriteCommandXml(class Ofc::Command const &,struct IStream &)` | 91 | Exported Function
`struct Mso::BI::Color __stdcall Mso::BI::ConvertArtColorToBiColor(class Art::Color const &)` | 31 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteEndElement(void)` | 93 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteStartDocument(bool)` | 94 | Exported Function
`public: void __thiscall Mso::BI::Persistence::XmlWriter::WriteStartElement(wchar_t const *)` | 96 | Exported Function
`private: void __thiscall Mso::BI::Persistence::XmlWriter::WriteAttributeStringRaw(wchar_t const *,wchar_t const *,wchar_t const *,wchar_t const *)` | 90 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeBoolProperty::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 65 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeColorProperty::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 66 | Exported Function
`long __stdcall Mso::BI::HrSetPropertyAsVariant(struct Mso::BI::IUniformObject &,wchar_t const *,struct tagVARIANT const &,struct Mso::BI::SetOptions,struct Mso::BI::ISetPropertyAsVariantVisitor &)` | 56 | Exported Function
`private: __thiscall Mso::BI::VisualCmdFactory::VisualCmdFactory(void)` | 20 | Exported Function
`private: void __thiscall Mso::BI::Persistence::XmlReader::GetValueString(wchar_t const * &,unsigned int &)` | 52 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeInt32Property::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 70 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangePropertyToDefault::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 71 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeStringProperty::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 72 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeDataSource::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 67 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeDoubleProperty::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 68 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeEnumProperty::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 69 | Exported Function
`class Mso::TCntPtr<struct Mso::BI::IDataController> __stdcall Mso::BI::CreateDataController(void)` | 33 | Exported Function
`class Mso::TCntPtr<struct Mso::BI::IDataControllerClientCmdSite> __stdcall Mso::BI::CreateOfcDataCmdSite(class Ofc::TWeakPtr<class Art::View> const &,bool)` | 34 | Exported Function
`class Mso::TCntPtr<struct Mso::BI::IPopulateContext> __stdcall Mso::BI::CreatePopulateContext(void)` | 36 | Exported Function
`bool __stdcall Mso::BI::Flighting::IsEnabled(enum Mso::BI::Flighting::Feature)` | 58 | Exported Function
`class Art::Color __stdcall Mso::BI::ConvertBiColorToArtColor(struct Mso::BI::Color const &)` | 32 | Exported Function
`class Mso::optional<class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > > __stdcall Mso::BI::LoadStringResource(int)` | 59 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall Mso::BI::GetFirstPropId(wchar_t const *)` | 46 | Exported Function
`class std::unique_ptr<struct Mso::BI::IUniformObject,struct std::default_delete<struct Mso::BI::IUniformObject> > __stdcall Mso::BI::DeserializeUniformProperties(class Mso::Json::value const &)` | 37 | Exported Function
`long __stdcall Mso::BI::HrGetPropertyAsVariant(struct Mso::BI::IUniformObject &,wchar_t const *,struct tagVARIANT *,struct Mso::BI::GetOptions)` | 55 | Exported Function
`class Mso::TCntPtr<struct Mso::BI::IVisual> __stdcall Mso::BI::GetVisual(struct Mso::BI::IVisualMoniker &)` | 54 | Exported Function
`class Mso::TCntPtr<struct Mso::BI::IVisualCmdSite> __stdcall Mso::BI::CreateOfcVisualCmdSite(class Ofc::TWeakPtr<class Art::View> const &)` | 35 | Exported Function
`class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > __stdcall Mso::BI::GetFirstPropId(struct Mso::BI::UniformPropPath const &)` | 45 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangePropertyToDefault::CmdChangePropertyToDefault(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &)` | 12 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangePropertyToDefault::CmdChangePropertyToDefault(void)` | 13 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeStringProperty::CmdChangeStringProperty(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,class std::basic_string<wchar_t,struct std::char_traits<wchar_t>,class std::allocator<wchar_t> > const &)` | 14 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeEnumProperty::CmdChangeEnumProperty(void)` | 9 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeInt32Property::CmdChangeInt32Property(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,int)` | 10 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeInt32Property::CmdChangeInt32Property(void)` | 11 | Exported Function
`public: __thiscall Mso::BI::BIPlatActivity::BIPlatActivity(char const *,struct Mso::Telemetry::TelemetryNamespace const &,bool)` | 1 | Exported Function
`public: __thiscall Mso::BI::Persistence::VersionTracker::VersionTracker(struct Mso::BI::Persistence::IFeatureVersionProvider &)` | 19 | Exported Function
`public: __thiscall Mso::BI::Persistence::XmlReader::XmlReader(struct ISequentialStream &)` | 21 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeStringProperty::CmdChangeStringProperty(void)` | 15 | Exported Function
`public: __thiscall BIPlatXSD::CmdEstablishDataBinding::CmdEstablishDataBinding(struct Mso::BI::IVisualMoniker &,class Mso::BI::StrongUIntType<class Mso::BI::DataWellIdType>,class Mso::BI::StrongUIntType<class Mso::BI::SchemaElementIdType>,unsigned int)` | 16 | Exported Function
`public: __thiscall BIPlatXSD::CmdEstablishDataBinding::CmdEstablishDataBinding(void)` | 17 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdRemoveDataBinding::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 76 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdReplaceVisualContent::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 77 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeBoolProperty::CmdChangeBoolProperty(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,bool)` | 2 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdChangeVisualType::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 73 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdEstablishDataBinding::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 74 | Exported Function
`protected: virtual bool __thiscall BIPlatXSD::CmdMoveDataBinding::PerformAction(class Ofc::CRollbackTransaction &,class Ofc::CommandList *,class Ofc::RootContainerChanges *)const ` | 75 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeDoubleProperty::CmdChangeDoubleProperty(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,double)` | 6 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeDoubleProperty::CmdChangeDoubleProperty(void)` | 7 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeEnumProperty::CmdChangeEnumProperty(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,int)` | 8 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeBoolProperty::CmdChangeBoolProperty(void)` | 3 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeColorProperty::CmdChangeColorProperty(struct Mso::BI::IVisualMoniker &,struct Mso::BI::UniformPropPath const &,struct Mso::BI::Color const &)` | 4 | Exported Function
`public: __thiscall BIPlatXSD::CmdChangeColorProperty::CmdChangeColorProperty(void)` | 5 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: BIPLAT.DLL
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20134
* Product Version: 16.0.12527.20134
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/6f71053638eacbefdf3115a640c1f13f5cf59307e7eee3c155bf414c9daa9fa3/detection/




MIT License. Copyright (c) 2020 Strontic.


