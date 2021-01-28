---
title: "CLSID 9C1CC6E4-D7EB-4EEb-9091-15A7C8791ED9 | InkRenderer Class"
excerpt: What is COM-Object CLSID 9C1CC6E4-D7EB-4EEb-9091-15A7C8791ED9?
---

# {9C1CC6E4-D7EB-4EEb-9091-15A7C8791ED9}

* `InkRenderer Class`

## Registry


### InprocServer32

* `C:\Program Files\Common Files\Microsoft Shared\Ink\InkObj.dll`
* ThreadingModel: `Both`

### ProgID

* `msinkaut.InkRenderer.1`

### Programmable


### VersionIndependentProgID

* `msinkaut.InkRenderer`

## Instance

* Type: `__ComObject`

### Methods

* GetViewTransform: `void GetViewTransform (IInkTransform)`
* SetViewTransform: `void SetViewTransform (IInkTransform)`
* GetObjectTransform: `void GetObjectTransform (IInkTransform)`
* SetObjectTransform: `void SetObjectTransform (IInkTransform)`
* Draw: `void Draw (LONG_PTR, IInkStrokes)`
* DrawStroke: `void DrawStroke (LONG_PTR, IInkStrokeDisp, IInkDrawingAttributes)`
* PixelToInkSpace: `void PixelToInkSpace (LONG_PTR, int, int)`
* InkSpaceToPixel: `void InkSpaceToPixel (LONG_PTR, int, int)`
* PixelToInkSpaceFromPoints: `void PixelToInkSpaceFromPoints (LONG_PTR, Variant)`
* InkSpaceToPixelFromPoints: `void InkSpaceToPixelFromPoints (LONG_PTR, Variant)`
* Measure: `IInkRectangle Measure (IInkStrokes)`
* MeasureStroke: `IInkRectangle MeasureStroke (IInkStrokeDisp, IInkDrawingAttributes)`
* Move: `void Move (float, float)`
* Rotate: `void Rotate (float, float, float)`
* ScaleTransform: `void ScaleTransform (float, float, bool)`

MIT License. Copyright (c) 2021 Strontic.


