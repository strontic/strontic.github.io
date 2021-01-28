---
title: "CLSID A2E6DDA0-06EF-4df3-B7BD-5AA224BB06E8 | ImageFile Class"
excerpt: What is COM-Object CLSID A2E6DDA0-06EF-4df3-B7BD-5AA224BB06E8?
---

# {A2E6DDA0-06EF-4df3-B7BD-5AA224BB06E8}

* `ImageFile Class`

## Registry


### InprocServer32

* `C:\Windows\System32\wiaaut.dll`
* ThreadingModel: `Apartment`

### ProgID

* `WIA.ImageFile.1`

### Programmable

* ``

### TypeLib

* `{94A0E92D-43C0-494E-AC29-FD45948A5221}`

### Version

* `1.0`

### VersionIndependentProgID

* `WIA.ImageFile`

## Instance

* Type: `__ComObject`

### Methods

* LoadFile: `void LoadFile (string)`
* SaveFile: `void SaveFile (string)`

### Properties

* FormatID: `string FormatID () {get} `
* FileExtension: `string FileExtension () {get} `
* FileData: `IVector FileData () {get} `
* ARGBData: `IVector ARGBData () {get} `
* Height: `int Height () {get} `
* Width: `int Width () {get} `
* HorizontalResolution: `double HorizontalResolution () {get} `
* VerticalResolution: `double VerticalResolution () {get} `
* PixelDepth: `int PixelDepth () {get} `
* IsIndexedPixelFormat: `bool IsIndexedPixelFormat () {get} `
* IsAlphaPixelFormat: `bool IsAlphaPixelFormat () {get} `
* IsExtendedPixelFormat: `bool IsExtendedPixelFormat () {get} `
* IsAnimated: `bool IsAnimated () {get} `
* FrameCount: `int FrameCount () {get} `
* ActiveFrame: `int ActiveFrame () {get} {set} `
* Properties: `IProperties Properties () {get} `

MIT License. Copyright (c) 2021 Strontic.


