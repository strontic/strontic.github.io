---
title: "CLSID C45268A2-FA81-4E19-B1E3-72EDBD60AEDA | MSVidCtl Enhanced Video Renderer(DX10) Segment"
excerpt: What is COM-Object CLSID C45268A2-FA81-4E19-B1E3-72EDBD60AEDA?
---

# {C45268A2-FA81-4E19-B1E3-72EDBD60AEDA}

### `MSVidCtl Enhanced Video Renderer(DX10) Segment`

## Registry


### {0DE86A57-2BAA-11CF-A229-00AA003D7352}


### InprocServer32

##### `C:\Windows\System32\msvidctl.dll`
* ThreadingModel: `Apartment`

### ProgID

##### `MSVidCtl.EVR.1`

### Programmable


### TypeLib

##### `{B0EDF154-910A-11D2-B632-00C04F79498E}`

### Version

##### `1.0`

### VersionIndependentProgID

##### `MSVidCtl.EVR`

## Instance

* Type: `__ComObject`

### Methods

* IsEqualDevice: `bool IsEqualDevice (IMSVidDevice)`
* SetupMixerBitmap: `void SetupMixerBitmap (IPictureDisp, int, IMSVidRect)`
* Capture: `IPictureDisp Capture ()`

### Properties

* Name: `string Name () {get} `
* Status: `int Status () {get} `
* Power: `bool Power () {get} {set} `
* Category: `string Category () {get} `
* ClassID: `string ClassID () {get} `
* CustomCompositorClass: `string CustomCompositorClass () {get} {set} `
* MixerBitmap: `IPictureDisp MixerBitmap () {get} {set} `
* MixerBitmapPositionRect: `IMSVidRect MixerBitmapPositionRect () {get} {set} `
* MixerBitmapOpacity: `int MixerBitmapOpacity () {get} {set} `
* SourceSize: `SourceSizeList SourceSize () {get} {set} `
* OverScan: `int OverScan () {get} {set} `
* AvailableSourceRect: `IMSVidRect AvailableSourceRect () {get} `
* MaxVidRect: `IMSVidRect MaxVidRect () {get} `
* MinVidRect: `IMSVidRect MinVidRect () {get} `
* ClippedSourceRect: `IMSVidRect ClippedSourceRect () {get} {set} `
* UsingOverlay: `bool UsingOverlay () {get} {set} `
* FramesPerSecond: `int FramesPerSecond () {get} `
* DecimateInput: `bool DecimateInput () {get} {set} `
* Presenter: `IMFVideoPresenter Presenter () {get} {set} `
* SuppressEffects: `bool SuppressEffects () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


