---
title: "CLSID 43FB1553-AD74-4ee8-88E4-3E6DAAC915DB | InkCollector Class"
excerpt: What is COM-Object CLSID 43FB1553-AD74-4ee8-88E4-3E6DAAC915DB?
---

# {43FB1553-AD74-4ee8-88E4-3E6DAAC915DB}

### `InkCollector Class`

## Registry


### InprocServer32

##### `C:\Program Files\Common Files\Microsoft Shared\Ink\InkObj.dll`
* ThreadingModel: `Both`

### ProgID

##### `msinkaut.InkCollector.1`

### Programmable


### VersionIndependentProgID

##### `msinkaut.InkCollector`

## Instance

* Type: `ComObject`

### Methods

* SetGestureStatus: `void SetGestureStatus (InkApplicationGesture, bool)`
* GetGestureStatus: `bool GetGestureStatus (InkApplicationGesture)`
* GetWindowInputRectangle: `void GetWindowInputRectangle (IInkRectangle)`
* SetWindowInputRectangle: `void SetWindowInputRectangle (IInkRectangle)`
* SetAllTabletsMode: `void SetAllTabletsMode (bool)`
* SetSingleTabletIntegratedMode: `void SetSingleTabletIntegratedMode (IInkTablet)`
* GetEventInterest: `bool GetEventInterest (InkCollectorEventInterest)`
* SetEventInterest: `void SetEventInterest (InkCollectorEventInterest, bool)`

### Properties

* hWnd: `LONG_PTR hWnd () {get} {set} `
* Enabled: `bool Enabled () {get} {set} `
* DefaultDrawingAttributes: `IInkDrawingAttributes DefaultDrawingAttributes () {get} {set by ref}`
* Renderer: `IInkRenderer Renderer () {get} {set by ref}`
* Ink: `IInkDisp Ink () {get} {set by ref}`
* AutoRedraw: `bool AutoRedraw () {get} {set} `
* CollectingInk: `bool CollectingInk () {get} `
* CollectionMode: `InkCollectionMode CollectionMode () {get} {set} `
* DynamicRendering: `bool DynamicRendering () {get} {set} `
* DesiredPacketDescription: `Variant DesiredPacketDescription () {get} {set} `
* MouseIcon: `IPictureDisp MouseIcon () {get} {set} {set by ref}`
* MousePointer: `InkMousePointer MousePointer () {get} {set} `
* Cursors: `IInkCursors Cursors () {get} `
* MarginX: `int MarginX () {get} {set} `
* MarginY: `int MarginY () {get} {set} `
* Tablet: `IInkTablet Tablet () {get} `
* SupportHighContrastInk: `bool SupportHighContrastInk () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


