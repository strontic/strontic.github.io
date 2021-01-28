---
title: "CLSID E5CA59F5-57C4-4DD8-9BD6-1DEEEDD27AF4 | Microsoft InkEdit Control"
excerpt: What is COM-Object CLSID E5CA59F5-57C4-4DD8-9BD6-1DEEEDD27AF4?
---

# {E5CA59F5-57C4-4DD8-9BD6-1DEEEDD27AF4}

### `Microsoft InkEdit Control`

## Registry


### Control


### InprocServer32

##### `C:\Windows\System32\Inked.dll`
* ThreadingModel: `Apartment`

### Insertable


### MiscStatus

##### `0`

### (1)

##### `131473`

### ProgID

##### `InkEd.InkEdit.1`

### Programmable


### TypeLib

##### `{8405D0DF-9FDD-4829-AEAD-8E2B0A18FEA4}`

### Version

##### `1.0`

### VersionIndependentProgID

##### `InkEd.InkEdit`

## Instance

* Type: `__ComObject`

### Methods

* Recognize: `void Recognize ()`
* GetGestureStatus: `bool GetGestureStatus (InkApplicationGesture)`
* SetGestureStatus: `void SetGestureStatus (InkApplicationGesture, bool)`
* Refresh: `void Refresh ()`

### Properties

* Status: `InkEditStatus Status () {get} `
* UseMouseForInput: `bool UseMouseForInput () {get} {set} `
* InkMode: `InkMode InkMode () {get} {set} `
* InkInsertMode: `InkInsertMode InkInsertMode () {get} {set} `
* DrawingAttributes: `IInkDrawingAttributes DrawingAttributes () {get} {set by ref}`
* RecognitionTimeout: `int RecognitionTimeout () {get} {set} `
* Recognizer: `IInkRecognizer Recognizer () {get} {set by ref}`
* Factoid: `string Factoid () {get} {set} `
* SelInks: `Variant SelInks () {get} {set} `
* SelInksDisplayMode: `InkDisplayMode SelInksDisplayMode () {get} {set} `
* BackColor: `OLE_COLOR BackColor () {get} {set} `
* Appearance: `AppearanceConstants Appearance () {get} {set} `
* BorderStyle: `BorderStyleConstants BorderStyle () {get} {set} `
* Hwnd: `OLE_HANDLE Hwnd () {get} `
* Font: `IFontDisp Font () {get} {set by ref}`
* Text: `string Text () {get} {set} `
* MouseIcon: `IPictureDisp MouseIcon () {get} {set} {set by ref}`
* MousePointer: `InkMousePointer MousePointer () {get} {set} `
* Locked: `bool Locked () {get} {set} `
* Enabled: `bool Enabled () {get} {set} `
* MaxLength: `int MaxLength () {get} {set} `
* MultiLine: `bool MultiLine () {get} {set} `
* ScrollBars: `ScrollBarsConstants ScrollBars () {get} {set} `
* DisableNoScroll: `bool DisableNoScroll () {get} {set} `
* SelAlignment: `Variant SelAlignment () {get} {set} `
* SelBold: `Variant SelBold () {get} {set} `
* SelItalic: `Variant SelItalic () {get} {set} `
* SelUnderline: `Variant SelUnderline () {get} {set} `
* SelColor: `Variant SelColor () {get} {set} `
* SelFontName: `Variant SelFontName () {get} {set} `
* SelFontSize: `Variant SelFontSize () {get} {set} `
* SelCharOffset: `Variant SelCharOffset () {get} {set} `
* TextRTF: `string TextRTF () {get} {set} `
* SelStart: `int SelStart () {get} {set} `
* SelLength: `int SelLength () {get} {set} `
* SelText: `string SelText () {get} {set} `
* SelRTF: `string SelRTF () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


