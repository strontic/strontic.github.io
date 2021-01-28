---
title: "CLSID 3050f6b3-98b5-11cf-bb82-00aa00bdce0b | Template Printer class"
excerpt: What is COM-Object CLSID 3050f6b3-98b5-11cf-bb82-00aa00bdce0b?
---

# {3050f6b3-98b5-11cf-bb82-00aa00bdce0b}

* `Template Printer class`

## Registry


### InprocServer32

* `C:\Windows\System32\mshtml.dll`
* ThreadingModel: `Apartment`

### ProgID

* `TemplatePrinter.TemplatePrinter.1`

### Programmable


### VersionIndependentProgID

* `TemplatePrinter.TemplatePrinter`

## Instance

* Type: `__ComObject`

### Methods

* startDoc: `bool startDoc (string)`
* stopDoc: `void stopDoc ()`
* printBlankPage: `void printBlankPage ()`
* printPage: `void printPage (IDispatch)`
* ensurePrintDialogDefaults: `bool ensurePrintDialogDefaults ()`
* showPrintDialog: `bool showPrintDialog ()`
* showPageSetupDialog: `bool showPageSetupDialog ()`
* printNonNative: `bool printNonNative (IUnknown)`
* printNonNativeFrames: `void printNonNativeFrames (IUnknown, bool)`
* updatePageStatus: `void updatePageStatus (int)`
* deviceSupports: `Variant deviceSupports (string)`
* getPageMarginTop: `Variant getPageMarginTop (IDispatch, int, int)`
* getPageMarginRight: `Variant getPageMarginRight (IDispatch, int, int)`
* getPageMarginBottom: `Variant getPageMarginBottom (IDispatch, int, int)`
* getPageMarginLeft: `Variant getPageMarginLeft (IDispatch, int, int)`
* getPageMarginTopImportant: `bool getPageMarginTopImportant (IDispatch)`
* getPageMarginRightImportant: `bool getPageMarginRightImportant (IDispatch)`
* getPageMarginBottomImportant: `bool getPageMarginBottomImportant (IDispatch)`
* getPageMarginLeftImportant: `bool getPageMarginLeftImportant (IDispatch)`

### Properties

* framesetDocument: `bool framesetDocument () {get} {set} `
* frameActive: `bool frameActive () {get} {set} `
* frameAsShown: `bool frameAsShown () {get} {set} `
* selection: `bool selection () {get} {set} `
* selectedPages: `bool selectedPages () {get} {set} `
* currentPage: `bool currentPage () {get} {set} `
* currentPageAvail: `bool currentPageAvail () {get} {set} `
* collate: `bool collate () {get} {set} `
* duplex: `bool duplex () {get} `
* copies: `ushort copies () {get} {set} `
* pageFrom: `ushort pageFrom () {get} {set} `
* pageTo: `ushort pageTo () {get} {set} `
* tableOfLinks: `bool tableOfLinks () {get} {set} `
* allLinkedDocuments: `bool allLinkedDocuments () {get} {set} `
* header: `string header () {get} {set} `
* footer: `string footer () {get} {set} `
* marginLeft: `int marginLeft () {get} {set} `
* marginRight: `int marginRight () {get} {set} `
* marginTop: `int marginTop () {get} {set} `
* marginBottom: `int marginBottom () {get} {set} `
* pageWidth: `int pageWidth () {get} `
* pageHeight: `int pageHeight () {get} `
* unprintableLeft: `int unprintableLeft () {get} `
* unprintableTop: `int unprintableTop () {get} `
* unprintableRight: `int unprintableRight () {get} `
* unprintableBottom: `int unprintableBottom () {get} `
* selectionEnabled: `bool selectionEnabled () {get} {set} `
* frameActiveEnabled: `bool frameActiveEnabled () {get} {set} `
* orientation: `string orientation () {get} {set} `
* usePrinterCopyCollate: `bool usePrinterCopyCollate () {get} {set} `
* headerFooterFont: `string headerFooterFont () {get} {set} `

MIT License. Copyright (c) 2021 Strontic.


