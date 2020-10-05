---
title: MSOSVG.DLL | Microsoft Office SVG support
excerpt: What is MSOSVG.DLL?
---

# MSOSVG.DLL 

* File Path: `C:\Program Files (x86)\Microsoft Office\root\Office16\MSOSVG.DLL`
* Description: Microsoft Office SVG support

## Hashes

Type | Hash
-- | --
MD5 | `ACC4F2F0AF479D36936404B369BD96E2`
SHA1 | `6602A89680103C9557C86128563099B72FEB2928`
SHA256 | `815FA81A31E8F5B1F5BC30388B6F7BE76C8EB4421D4B63D0EB85A62FE782B549`
SHA384 | `664042394A23D9BED346DEF15B80EE620AF186A7F23C3F724F69906361EC9F1879D057634FA1B3FD8EE41E440AB71D0E`
SHA512 | `34F6549B1CD082C6307D2113DDB1F7B1EE1C147A3544459CD113F57F056599E0A065964A9F706DCEBBCAFDEBBBB9BFC10E2AC7E84CCF9B3DF62D65F68BBC6665`
SSDEEP | `24576:PyXWhJmWySPnHr8UoJAv/1lWkUjFrOvi5IfOhJcB/cHiSD9LOCX8juxraOMIFYEw:P0WhJmWySPgU/1lWkUjFrOvi5IfOhJcR`
IMP | `30976103998637A7F80519F870E8FB4E`
PESHA1 | `50C21F1ED2F37E9ABD68F5ABA05BE6BF50629063`
PE256 | `FAB506DC74F3394B84F3714D294F2839C00221A1C07582F90D83FAEB4FA91F19`

## DLL Exports:

Function Name | Ordinal | Type
-- | -- | --
`public: static class Mso::TCntPtr<struct GEL::ISVGImage> __stdcall GEL::ISVGImageFactory::CreateSVGImage(struct ARC::ICommandList const &,struct GEL::Rect const *,struct Mso::SVG::SVGCreationParams const &)` | 15 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImage> __stdcall GEL::ISVGImageFactory::CreateSVGImage(struct IStream &)` | 11 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImage> __stdcall GEL::ISVGImageFactory::CreateSVGImage(struct ARC::ICommandList const &,struct GEL::Rect const *)` | 13 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImage> __stdcall GEL::ISVGImageFactory::CreateSVGImage(struct ARC::ICommandList const &,struct GEL::Rect const *,struct Math::TVector2<class Math::TUnits<float,struct Math::TUnitsRatioTag<struct Math::DevicePixels,struct Math::Inches> > > const &)` | 14 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImageFactory> __stdcall GEL::ISVGImageFactory::Create(struct IStream &,bool)` | 10 | Exported Function
`wchar_t const * __stdcall Mso::SVG::GetSVGUnsupportedPropName(enum Mso::SVG::SVGUnsupportedProps)` | 16 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImage> __stdcall GEL::ISVGImageFactory::CreateSVGImage(struct IStream &,bool)` | 12 | Exported Function
`public: static class Mso::TCntPtr<struct GEL::ISVGImageFactory> __stdcall GEL::ISVGImageFactory::Create(struct IStream &)` | 9 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::ISceneIterator &,bool)` | 1 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::IShape const &,bool,bool)` | 3 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct GEL::ITopLevelEffect const &,bool)` | 4 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::ISceneGraph const &,bool)` | 2 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(struct Mso::SVG::SVGCreationParams const &,class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::ISceneIterator &,bool)` | 5 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(struct Mso::SVG::SVGCreationParams const &,class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::IShape const &,bool,bool)` | 7 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(struct Mso::SVG::SVGCreationParams const &,class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct GEL::ITopLevelEffect const &,bool)` | 8 | Exported Function
`bool __stdcall Mso::SVG::CanRenderAsSVG(struct Mso::SVG::SVGCreationParams const &,class std::set<enum Mso::SVG::SVGUnsupportedProps,struct std::less<enum Mso::SVG::SVGUnsupportedProps>,class std::allocator<enum Mso::SVG::SVGUnsupportedProps> > &,struct Gfx::ISceneGraph const &,bool)` | 6 | Exported Function


## Signature

* Status: Signature verified.
* Serial: `33000002CE7C9ACE7D905ED2B70000000002CE`
* Thumbprint: `B10607FB914700B40F794610850C1DE0A21566C1`
* Issuer: CN=Microsoft Code Signing PCA 2010, O=Microsoft Corporation, L=Redmond, S=Washington, C=US
* Subject: CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US

## File Metadata

* Original Filename: MSOSVG.DLL
* Product Name: Microsoft Office
* Company Name: Microsoft Corporation
* File Version: 16.0.12527.20134
* Product Version: 16.0.12527.20134
* Language: English (United States)
* Legal Copyright: 
* Machine Type: 32-bit

## File Scan

* VirusTotal Detections: 0/72
* VirusTotal Link: https://www.virustotal.com/gui/file/815fa81a31e8f5b1f5bc30388b6f7be76c8eb4421d4b63d0eb85a62fe782b549/detection/




MIT License. Copyright (c) 2020 Strontic.


